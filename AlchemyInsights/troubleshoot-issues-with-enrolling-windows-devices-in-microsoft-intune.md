---
title: Rekisteröiminen Windows Microsoft Intune-laitteiden ongelmien vianmääritys
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.openlocfilehash: 8d19bbd5a5782c7793c87499baf62b2eb7de82ae
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 01/15/2019
ms.locfileid: "28287298"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a><span data-ttu-id="9ba4b-102">Rekisteröiminen Windows Microsoft Intune-laitteiden ongelmien vianmääritys</span><span class="sxs-lookup"><span data-stu-id="9ba4b-102">Troubleshoot issues with enrolling Windows devices in Microsoft Intune</span></span>

<span data-ttu-id="9ba4b-103">Tarkista ongelman nyt alla luetellut resurssit.</span><span class="sxs-lookup"><span data-stu-id="9ba4b-103">Review the resources listed below to resolve your issue now.</span></span> 
  
<span data-ttu-id="9ba4b-104">Joitakin yleisiä virhesanomia ja tarkkuutta vaiheet:</span><span class="sxs-lookup"><span data-stu-id="9ba4b-104">Some common error messages and resolution steps:</span></span>
  
 <span data-ttu-id="9ba4b-p101">**Ei voi asentaa ohjelmiston 0x80cf4017:** Käyttäjän tili on vanhentunut. Lataa uudelleen PC-Client-ohjelmistopaketin Intune hallintakonsolissa. Tarkista tästä lisätietoja ohjeista.</span><span class="sxs-lookup"><span data-stu-id="9ba4b-p101">**The software cannot be installed, 0x80cf4017:** Your account certificate has expired. Re-download the PC Client software package in the Intune Admin Console. Review this documentation for more information.</span></span> 
  
 <span data-ttu-id="9ba4b-108">**0x801c0003-virhekoodi:** Virhe voi ilmetä seuraavissa tilanteissa:</span><span class="sxs-lookup"><span data-stu-id="9ba4b-108">**Error code 0x801c0003:** The error can occur in the following scenarios:</span></span> 
  
1. <span data-ttu-id="9ba4b-p102">Käyttäjä on rekisteröitynyt ylittää laitteen enimmäiskoon laitteita. Tarkasteltava näitä asiakirjoja, voit [poistaa laitteen](https://docs.microsoft.com/en-us/intune/devices-wipe) tai [muuttaa laitteen enimmäiskoon](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="9ba4b-p102">The user has more devices enrolled than the device limit. Review these documents to [remove a device](https://docs.microsoft.com/en-us/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>
    
2. <span data-ttu-id="9ba4b-p103">”Käyttäjät voivat liittää laitteet Azure AD” on määritetty ”none”. Valitse tai määritä se kaikille käyttäjille. Voit tarkastella [näitä ohjeita](https://docs.microsoft.com/en-us/azure/active-directory/device-management-azure-portal#configure-device-settings) .</span><span class="sxs-lookup"><span data-stu-id="9ba4b-p103">"Users may join devices to Azure AD" is set to "none". Set it to all or select users. Review [this documentation](https://docs.microsoft.com/en-us/azure/active-directory/device-management-azure-portal#configure-device-settings) for more information.</span></span> 
    
3. <span data-ttu-id="9ba4b-p104">Toinen käyttäjä on jo liitetty laite. Jos näin on, poista laite Azure Intune konsolista tai Peruuta laitteen ilmoittautuminen manuaalisesti ennen kuin yrität uudelleen.</span><span class="sxs-lookup"><span data-stu-id="9ba4b-p104">The device is already enrolled by another user. If that's the case, remove the device from the Azure Intune console or manually unenroll the device before trying again.</span></span>
    
4. <span data-ttu-id="9ba4b-p105">Laite on Windows 10 Home. Vain Windows 10 Pro, koulutus ja Enterprise SKU-tietoja voit liittää Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="9ba4b-p105">The device is Windows 10 Home. Only Windows 10 Pro, Education and Enterprise SKUs can join Azure Active Directory.</span></span>
    
<span data-ttu-id="9ba4b-118">Lisätietoja ja resursseja auttaa ratkaisemaan ongelmaasi:</span><span class="sxs-lookup"><span data-stu-id="9ba4b-118">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="9ba4b-p106">[Intune vianmääritys-portaalin](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) avulla voit diagnosoida ja ratkaista yhteisen rekisteröinti virheitä. Lisätietoja [tämän asiakirjan](https://docs.microsoft.com/en-us/intune/help-desk-operators) tarkasteleminen.</span><span class="sxs-lookup"><span data-stu-id="9ba4b-p106">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures. Review [this document](https://docs.microsoft.com/en-us/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="9ba4b-121">Tarkasteltava näitä asiakirjoja yleisiä virheitä, jotka estävät rekisteröinti ja ratkaisuja jokaiseen luettelo: [Vianetsintä opas](https://support.microsoft.com/en-us/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) ja [vianmääritys doc](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="9ba4b-121">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/en-us/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) and [Troubleshooting doc](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>
    
<span data-ttu-id="9ba4b-122">[Rekisteröi Windows Microsoft Intune-laitteiden tietoja](https://docs.microsoft.com/en-us/intune/windows-enroll).</span><span class="sxs-lookup"><span data-stu-id="9ba4b-122">[Learn how to enroll Windows devices in Microsoft Intune](https://docs.microsoft.com/en-us/intune/windows-enroll).</span></span>
  

