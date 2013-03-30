************************************************************
*  Product: Intel(r) Smart Connect Technology
*  Release: Beta 1
*  Version: 4.0.10.1688
*  Date: October 4, 2012
************************************************************

************************************************************
*  CONTENTS OF THIS DOCUMENT
************************************************************
This document contains the following sections:

1.  Overview
2.  System Requirements
3.  Contents of the Distribution Package
4.  Contents of the Extracted Files
5.  Installing the Software in Interactive Mode
6.  Installing the Software in Silent Mode

************************************************************
* 1.  OVERVIEW
************************************************************
This package installs the Intel(r) Smart Connect Technology Software to the target system. 

For more information, please contact your field representative.

************************************************************
* 2.  SYSTEM REQUIREMENTS 
************************************************************
1.  Core i3 or better CPU



2.  One of the following operating systems must be 
    fully installed and running on the system
    before installing this software:


    Microsoft Windows 7 SP1

    Microsoft Windows 8
  
3.  Close any running applications to avoid installation problems.

4.  Remove any previously installed versions of the software from 
    the system before installing the Intel(r) Smart Connect 
    Technology software


************************************************************
* 3.  CONTENTS OF THE DISTRIBUTION PACKAGE
************************************************************
The Intel Smart Connect Technology Software package contains the 
following items:

    File(s)       
    -------
    SETUP.EXE
    Intel(r) Smart Connect Technology 4.0 x64.msi
    Intel(r) Smart Connect Technology 4.0 x86.msi
    ReadMe.txt
    ReleaseNotes_4.0.10.1688.htm
    mup.xml


************************************************************
* 4.  CONTENTS OF THE EXTRACTED FILES AND VERSION
************************************************************
    File(s)       
    -------
    
    iSCTAgent.exe - 4.0.10.1688

    iSCTConnect.dll - 4.0.10.1688

    iSCTControl.exe - 4.0.10.1688

    iSCTSysTray.exe - 4.0.10.1688
   
    iSCTPlatformCheck.dll - 4.0.10.1688

    iSCTENSData.dll - 4.0.10.1688

    iSCTWizard.exe - 4.0.10.1688

    iSCTNetDetect.dll - 4.0.10.1688

    LServ.dll - 4.0.10.1688

    NetworkHeuristic.dll - 4.0.10.1688

    MutexManager.dll - 4.0.10.1688

    iSCTFormLibrary.dll - 4.0.10.1688

    ISCT.sys - 1.0.7

    ikbevent.sys - 1.0.7

    imsevent.sys - 1.0.8
    
************************************************************
* 5.  Setup Options
************************************************************
    -s       Silent Install

    -nogui   Driver and iSCTAgent only install (no GUI or SysTray Icon)
    -h       display help (not only works from Administrative Command Prompt)


Log file is created named iSCTInstall.log. If the install directory is not writable, 
the installation log will be created in the %TEMP% directory.


If the file "SmartConnect.ini" is found in the same directory as the setup.exe application, the contents of the file will be used to update the OEM section of the registry. Refer to the Setup/Config Guide for more information on using this feature.

************************************************************
* 6.  INSTALLING THE SOFTWARE IN INTERACTIVE MODE
************************************************************
1.  Verify that all system requirements have been met as 
    described in Section 2 above.

2.  Run the installation program setup.exe.  


************************************************************
* 7.  INSTALLING THE SOFTWARE IN SILENT MODE
************************************************************
1.  Verify that all system requirements have been met as 
    described in section 2.

2.  From a command window in a folder where the Intel(r) Smart Connect Technology 
    installer is present, using the following command: setup.exe -s


Note that this command will also create or overwrite an installation log file in the same folder, which will always be named iSCTInstall.log. If the install directory is not writable, the installation log will be created in the %TEMP% directory.

This command does not uninstall Intel(r) Smart Connect Technology, it will update from previous to current version without manual uninstall.


************************************************************
* DISCLAIMER
************************************************************
Intel is making no claims of usability, efficacy or warranty.  
The Intel(R) SOFTWARE LICENSE AGREEMENT
(OEM / IHV / ISV Distribution & Single User) 
completely defines the licensed use of this software.
************************************************************
Information in this document is provided in connection with 
Intel(R) products.  No license, express or implied, by estoppel 
or otherwise, to any intellectual property rights is granted 
by this document.  Intel assumes no liability whatsoever, 
and Intel disclaims any express or implied warranty relating 
to sale and/or use of Intel(R) products, including liability 
or warranties relating to fitness for a particular purpose, 
merchantability or infringement of any patent, copyright or 
other intellectual property right.  Intel(R) products are 
not intended for use in medical, life saving, or 
life-sustaining applications.

************************************************************
Intel Corporation disclaims all warranties and liabilities 
for the use of this document and the information contained 
herein, and assumes no responsibility for any errors which 
may appear in this document, nor does Intel make a 
commitment to update the information contained herein.  
Intel reserves the right to make changes to this document at 
any time, without notice.
************************************************************
************************************************************

* Intel is a trademark or registered trademark of Intel Corporation 
  or its subsidiaries in the United States and other countries.
* Other brands and names are the property of their 
  respective owners.

Copyright (c) Intel Corporation, 2012
