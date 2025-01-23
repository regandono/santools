.. image:: https://img.shields.io/badge/Fla-v1.0.0 (BETA)-blue

Welcome to Fla
===================
``>_`` Fla is console application (**specifically**) for storage administrator/engineer to view configuration, logs and have built in tools that very usefull for any administrator/engineer.
 
.. image :: https://github.com/regandono/santools/blob/fla/images/fhelp.png


Features
----------
``>_`` It's portable.

``>_`` Available Mode/Module/Component/what ever we can call this:

  ::
 
    - IP Changer (IPC)
      Tools to change ip address when we connect many devices with different default ip or different ip segment.

    - Enterprise Offline Viewer (EOV) [PENDING]
      Offline tools to view Hitachi Vantara storage configuration.

    - HNAS
      Non-interactive online connection to hitachi NAS. Please refer each model of HNAS CLI Documentations for CLI command.

    - HNASF
      Offline tools for Hitachi NAS configuration.

    - Windows Command Line Terminal (CMD)
      Built in Windows Command Line Terminal.

    - SSH
      Non-interactive SSH client.

    - SSHX
      Interactive SSH client (Experimental).

    - Knowledge Base (KB)
      Tools to manages your knowledge/notes/tips&trics/etc.

    - MDS [PENDING]
      Offline tools for Cisco MDS.

    - BROCADE [PENDING]
      Offline tools for Brocade.

    - HCP [PENDING]
      Offline tools for Hitachi Content Platform.

    - HCPAE [PENDING]
      Offline tools for HCP Anywhere Enterprise.

Getting started
-------------
Fla is free application and please email me your hardware id to get your key.

Default password is ``fla``.

``>_`` How to get your key: 

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
  
``>_`` Navigations:

  ::
 
    Arrow Up/Down: command history
    Arrow Right: auto complete from history
    Tab: show command/sub command
    Ctrl+Space: show command/sub command

``>_`` Notes: 

  ::

    - General
      * Output can be wrapped, 
        - try to increase your Command Prompt "Screen Buffer Size" (eg: 500).
          Goto  your Command Prompt Properties or using CLI mode 'con:cols=Width_Size'
        - try to show/hide any column using 
          >_ COLUMN SET
 
    - IPC
      * To apply any profile, IPC required administrator privilage.

    - HNASF 
      * Some diagnostics output have limitation (only show (max) 20 records per vnode/pnodes).
      * Currently only suport one (1) cluster per diagnostic file.

``>_`` Changelog: 

  ::
 
    v1.0.0 - Beta
    STATUS     FILE                REMARK
    [OK]       fla 241218.rar      CMD, SSH, IPC, KB Mode
    [OK]       fla 241219.rar      HNAS Mode 
    [OK]       fla 250106.rar      HNASF, SSHX Mode, autocomplete, history, statusbar
    [PENDING]                      EOV, HNASF, MDS, BROCADE, HCP Mode, XView
     
