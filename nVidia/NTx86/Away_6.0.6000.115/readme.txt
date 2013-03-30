==========================================
 NVIDIA AwayMode Driver 

 Copyright (C) 2009    NVIDIA Corporation
==========================================

Introduction:

Away Mode is an OS feature originally introduced with Update Rollup 2 for Microsoft 
Windows XP Media Center Edition 2005. Away Mode was conceived as a new power management 
usage model for media PCs that allows the computer to appear off to the user while the 
system continues to perform tasks that do not require user input, such as recording 
television and viewing Media Center Extender sessions. 

Requirements:

The Away Mode Device will appear after BIOS has defined the Away mode device and ACPI
control method in the ACPI namespaces.

For the platform which Away Mode device has been defined in BIOS, that means the Away Mode
is ready to work on Microsoft Windows XP Media Center Edition 2005 with Update Rollup 2 
and Windows Vista, for the other operatiing system like Windows XP or Server 2003, a null
INF is needed to remove the unresolved hardware detection (YELLOW BANG!).

1. For Windows XP Media Center Edition 2005 with Update Rollup 2,

   Microsoft has inbox Away Mode Driver included, NVIDIA Away Mode Driver is not needed.

2. Windows Vista will provide much of the same functionality that Away mode provided for 
   the Update Rollup 2 of Windows XP Media Center Edition 2005, with one notable exception:
   the computer¡¦s power LED no longer toggles when the computer transitions in and out of 
   Away mode. 
   To retaining the LED toggle, we need the NVIDIA Away Mode driver to be installed which
   will notifies the BIOS when the operating system transitions in and out of Away mode by
   Away Mode Set Mode (SMOD) control method.

3. For the other operating system, Away Mode is not supported so the user has to disable
   the Away Mode device in BIOS, but for the BIOS that didn't has an option to disable the
   Away Mode device, 

   An null Away Mode INF is needed to remove the unresolved hardware detection (YELLOW BANG!)
   in Windows Device Manager.

Installation Instructions:

1. Right click on "My Computer" then select "Properties".
2. Select tab "Hardware" and hit the "Device Manager" button.
3. Find the "Unknown device" which has the "Device Instance Id" starts with "ACPI\AWY0001".
4. Right-click on this "Unknown device" and select "Properties".
5. Click tab "Driver", then click the button "Update Driver...".
6. Select "Install from a list or specific location (Advanced)".
7. Click "Next" to continue.
8. Select "Don't search. I will choose the driver to install".
9. Click "Next" to continue.
10. Click on "Have Disk".
11. Specify the directory location of the inf file.
12. An entry "NVIDIA AwayMode" should appear under the "Model" section.
13. Select that entry and click "Next" to continue.
14. Click "Finish" to complete the installation.

Uninstall instructions:

1. Delete the "oem*.inf" file from the "%windir%\inf" directory that contains the header
   "NVIDIA Away Mode Inf".
2. Right click on "My Computer" and select "Properties".
3. Click the tab "Hardware", then click on the button "Device Manager".
4. Find the NVIDIA Away Mode device under "System devices", then right-click on it to select
   "Uninstall", follow the dialog boxes to complete the "uninstall" process.




