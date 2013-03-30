===============================================================================
  Winbond Electronics Corporation 
  Winbond Trusted Platform Module (TPM) Device Driver
  Copyright (c) 2008 Winbond Electronics Corporation. All Rights Reserved.
===============================================================================

Winbond Trusted Platform Module (TPM) Device Driver

Package Version: 6.1.42.2035

By downloading, installing, copying, or otherwise using the Winbond TPM Device
Driver, you accept the terms of the license agreement provided in the TPMEULA.txt 
file.

Package Contents
================
* tpm.inf       - The Winbond TPM Device Driver information file
* tpm12x32.sys  - TPM 1.2 Device Driver for x86
* tpmx64.sys    - TPM 1.2 Device Driver for x64
* tddl.dll      - TPM Device Driver Library
* tpm.cat       - Signed Windows Catalog File for TPM Device Driver
* TPMEULA.txt   - TPM End User License Agreement
* readme.txt    - This Release Letter

Description
============
This package provides the Winbond TPM driver for Microsoft(R) Windows(R) XP
and Microsoft Windows 2000.
The driver implements the interface as defined in the TCG Software Stack (TSS)
Specification Version 1.2.

Installation
============
This package contains the files required to install the TPM Device Driver on 
systems with an on-board Winbond TPM 1.2 device.

You must have administrator privileges to install/update the driver.

When you boot Windows for the first time, a system with a TPM 1.2 
PnP node prompts you with the "Found New Hardware" screen. 
Follow the on-screen instructions to complete the driver installation.

Limitations
===========
None.

Changes from Previous Release
=============================
Driver changes
--------------
From Package Version 5.1.47.2018
* Adjusted timeout values.
* Fixed intermittent failure in driver load.

From Package Version 5.1.47.2017
* Fixed compatibility issues in INF.

From Package Version 5.1.47.2016
* Fixed the issue: If BIOS reports a TPM PnP node and IRQ resource is not 
  allocated to the driver, the driver causes failure during system shut-down 
  or hibernate.

From Package Version 5.1.47.2015
* If an IRQ resource is not allocated, driver works in polling mode.

From Package Version 5.1.47.2014
* Driver reads command's duration timeout from TPM.

From Package Version 5.1.47.2011
* Added support for WPCT200 device.

From Package Version 5.0.47.2006
* Improved command handling.
* Added 64-bit support.

-------------------------------
Microsoft and Windows are trademarks of Microsoft Corporation 
in the United States, other countries, or both.
Other company, product, and service names may be trademarks or 
service marks of others.