---
title: "Enroll devices "
titleSuffix: "Configuration Manager"
description: "Learn about methods to enroll devices for On-premises Mobile Device Management in Configuration Manager."
ms.date: 03/05/2017
ms.prod: configuration-manager
ms.technology: configmgr-hybrid
ms.topic: conceptual
ms.assetid: b58472e3-31a5-4305-8eb6-2522befebe02
author: aczechowski
ms.author: aaroncz
manager: dougeby
ms.collection: M365-identity-device-management
---
# Enroll devices for On-premises Mobile Device Management in Configuration Manager

*Applies to: Configuration Manager (current branch)*

To manage computers and devices with Configuration Manager On-premises Mobile Device Management, the devices need to be enrolled so that Configuration Manager can communicate with the devices for management tasks. Configuration Manager provides two methods for enrolling devices:  

- **User enrollment** - In this method, users initiate the enrollment process on their devices. For user enrollment to be successful, the device must have a trusted root certificate installed on it, and the user must be provisioned for enrollment by Configuration Manager.  To enroll device, the user simply provides work credentials, and the device is enrolled to be managed.  

   For more information, see [How users enroll devices with On-premises Mobile Device Management](../../mdm/deploy-use/user-enroll-devices-on-premises-mdm.md)  

- **Bulk enrollment** - In this method, the user of the device is not required to initiate enrollment. Instead a bulk enrollment package created in Configuration Manager and  is then put on the device and opened. When opened, the package provides the information required to enroll the device.  

   For more information, see [How to bulk-enroll devices with On-premises Mobile Device Management](../../mdm/deploy-use/bulk-enroll-devices-on-premises-mdm.md)  

  > [!NOTE]
  >  The current branch of Configuration Manager supports enrollment in On-premises Mobile Device Management for devices running the following operating systems:  
  > 
  > - Windows 10 Enterprise  
  >   -   Windows 10 Pro  
  >   -   Windows 10 Team 
  >   -   Windows 10 Mobile  
  >   -   Windows 10 Mobile Enterprise   
