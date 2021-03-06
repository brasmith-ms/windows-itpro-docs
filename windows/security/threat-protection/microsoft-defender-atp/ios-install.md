---
title: App-based deployment for Microsoft Defender ATP for iOS
ms.reviewer:
description: Describes how to deploy Microsoft Defender ATP for iOS using an app
keywords: microsoft, defender, atp, ios, app, installation, deploy, uninstallation, intune
search.product: eADQiWindows 10XVcnh
search.appverid: met150
ms.prod: w10
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security
ms.author: macapara
author: mjcaparas
ms.localizationpriority: medium
manager: dansimp
audience: ITPro
ms.collection: 
- m365-security-compliance 
- m365initiative-defender-endpoint 
ms.topic: conceptual
---

# App-based deployment for Microsoft Defender ATP for iOS

[!INCLUDE [Microsoft 365 Defender rebranding](../../includes/microsoft-defender.md)]

> [!IMPORTANT]
> **PUBLIC PREVIEW EDITION**
> 
> This documentation is for a pre-release solution. The guidelines and the solution are subject to change between now and its general availability.
> 
> As with any pre-release solution, remember to exercise caution when determining the target population for your deployments.

Microsoft Defender ATP for iOS is currently available as a preview app on TestFlight, Apple's beta testing platform. In GA, it will be available on the Apple App store.

Deployment devices need to be enrolled on Intune Company portal. Refer to
[Enroll your
device](https://docs.microsoft.com/mem/intune/enrollment/ios-enroll) to
learn more about Intune device enrollment

## Before you begin

-   Ensure you have access to [Microsoft Endpoint manager admin
    center](https://go.microsoft.com/fwlink/?linkid=2109431).

-   Ensure iOS enrollment is done for your users. Users need to have Microsoft Defender ATP
    license assigned in order to use Microsoft Defender ATP for iOS. Refer [Assign licenses to
    users](https://docs.microsoft.com/azure/active-directory/users-groups-roles/licensing-groups-assign)
    for instructions on how to assign licenses.


## Deployment steps

To install Microsoft Defender ATP for iOS, end-users can visit
<https://aka.ms/defenderios> on their iOS devices. This link will open the
TestFlight application on their device or prompt them to install TestFlight. On
the TestFlight app, follow the onscreen instructions to install Microsoft
Defender ATP.


![Image of deployment steps](images/testflight-get.png)

## Complete onboarding and check status

1.  Once Microsoft Defender ATP for iOS has been installed on the device, you
    will see the app icon.

    ![A screen shot of a smart phone Description automatically generated](images/41627a709700c324849bf7e13510c516.png)

2.  Tap the Microsoft Defender ATP app icon and follow the on-screen
    instructions to complete the onboarding steps. The details include end-user
    acceptance of iOS permissions required by Microsoft Defender ATP for iOS.

3.  Upon successful onboarding, the device will start showing up on the Devices
    list in Microsoft Defender Security Center.

    > [!div class="mx-imgBorder"]
    > ![A screenshot of a cell phone Description automatically generated](images/e07f270419f7b1e5ee6744f8b38ddeaf.png)

## Next Steps

[Configure Microsoft Defender ATP for iOS features](ios-configure-features.md)
