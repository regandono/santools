.. image:: https://img.shields.io/badge/Fla-v1.0.0 (BETA)-blue

 

Welcome to Fla
===================
``>_`` Fla is console application (**specifically**) for storage administrator/engineer to view configuration, logs and have built in tools that very usefull for any administrator/engineer.
 
.. image :: https://github.com/regandono/santools/blob/fla/images/fla - fhelp.png


Features
----------
``>_`` It's portable and lightweight as terminal application.

``>_`` Available Mode/Module/Component/what ever we can call this:


- ``IPC`` IP Changer

  IP Changer tools manages static ip address profiles that enables you to quickly connect every devices on your customers.

- ``EOV`` Enterprise Offline Viewer
   
  Offline tools for Hitachi Enterprise storage.

- ``HNAS``

  Non-interactive online connection to hitachi NAS CLI. 

  Please refer each model of HNAS CLI Documentations for CLI command.

- ``HNASF`` HNAS Offline Viewer

  Offline tools for Hitachi NAS.

- ``CMD`` Windows Command Line Terminal 
  
  Built in Windows Command Line Terminal.

- ``SSH``

  Non-interactive SSH client.

- ``SSHX``

  Interactive SSH client (Experimental).

- ``KB`` Knowledge Base

  Simple tools to manages your knowledge/snip/notes/tips&trics/etc.

- ``MDS`` MDS Offline Viewer

  Offline tools for Cisco MDS SAN switch.

- ``BROCADE`` Brocade Offline Viewer

  Offline tools for Brocade SAN switch.

- ``HCP`` HCP Offline Viewer
      
  Offline tools for Hitachi Content Platform. 

``>_`` Build in to log terminal session into file.
 
::
 
    * enable log session from app start 
      - Fla     
        Fla> setting setup
      - SETTING     
        SETTING> setup

    * Log session on the fly
      - Fla     
        Fla> setting log enable
      - SETTING     
        SETTING> log enable


``>_`` Run and show output from terminal.

  Required to disable password before execute from outside.
 
::

   c:\fla.exe eov show pool



``>_`` Suported logs 

- ``EOV`` Enterprise Offline Viewer: Storage Navigator Configuration Report and Config Collector

- ``HNASF`` HNAS Offline Viewer: HNAS Diagnostic

- ``MDS`` MDS Offline Viewer: Cisco Tech-Support

- ``BROCADE`` Brocade Offline Viewer: Brocade supportshow

- ``HCP`` HCP Offline Viewer: HCP Internal Log


Getting started
-------------
Fla is free application and please email me your hardware id to get your key to unlock all.

Default password is ``fla``.

Navigate to ``Release`` or can click this link to download latest version https://github.com/regandono/santools/releases

``>_`` How to get your key and apply: 
 
::
 
    1. Get HWID 
       - Fla     
         Fla> setting hwid
       - SETTING     
         SETTING> hwid
         
    2. Email your hwid   
       to:   
       subject: Register Fla   
       Email body: [HWID]
       
    4. After receiving email for key, apply new key
       - Fla     
         Fla> setting applykey
       - SETTING     
         SETTING> applykey
  
    5. Setup repository folder
       - Fla     
         Fla> setting setup repository
       - SETTING     
         SETTING> setup repository

``>_`` Navigations:


- ``Arrow Up/Down``: command history
- ``Arrow Right``: auto complete from history
- ``Tab``: show command/sub command/change focus
- ``Shift+Tab``: change to previous focus
- ``Ctrl+Space``: show command/sub command
- ``Ctrl+S``: search
- ``Ctrl+A``: select all
- ``Ctrl+X``: exit from mode (force)
- ``Ctrl+D``: quit from fla console (force)
 
 
``>_`` Notes: 


- ``General``


  * To import VSP One Block (B20 & B85) configurations, please use ``Config Collector (cc)``

  * If font cannot show properly, change your terminal font (eg: Cascadia Mono)


  * If cannot increase/decrease font size by press CTRL + Mouse Scroll Up/Down and table output is wrapped, 

    - Increase your terminal "Screen Buffer Size" (eg: 500).

      Goto  your terminal Properties or using CLI mode 'con:cols=Width_Size'

    - Show/hide any column using 

      ``>_`` SHOW COLUMN or COLUMN SET or COLUMN RESET


- ``IPC``

  * To apply any profile, IPC required administrator privilage.


- ``HNASF`` 

  * Diagnostics output have limitation (only show (max) 20 records per vnode/pnodes).
  
  * Currently only suport one (1) cluster per diagnostic file.   


``>_`` Version Changelog: 

::

     VERSION             STATUS        FILE                     REMARK
     v1.0.0 BETA1        [OK]          fla.v1.0.0.Beta1.rar     Mode: CMD, SSH, SSHX, IPC, KB, HNAS, HNASF, BROCADE, MDS, HCP
                                                                Bugs fix
     v1.0.0 BETA2        [OK]          fla.v1.0.0.Beta2.rar     Mode: EOV
                                                                Bugs fix on HCP, MDS
                                                                Update IPC/KB Add/Edit/Delete
     Next release        [PENDING]                              VSP B20 & B85
                                                                Log session into file
                                                                Run and show output from terminal (eg. fla.exe eov show pool)
                                                                Bugs fix

               
