---
title: LDAP:n määrittäminen
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 01/15/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004394"
- "7923"
ms.openlocfilehash: b6e89bca4e924c5570123194cb26358ba2c162ce
ms.sourcegitcommit: 83fe2a8d060794fdf58445b469b30a3294b7a9b6
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 01/15/2021
ms.locfileid: "49885159"
---
# <a name="configure-ldap"></a><span data-ttu-id="f3648-102">LDAP:n määrittäminen</span><span class="sxs-lookup"><span data-stu-id="f3648-102">Configure LDAP</span></span>

<span data-ttu-id="f3648-103">Voit määrittää LDAP:n seuraavasti:</span><span class="sxs-lookup"><span data-stu-id="f3648-103">To configure LDAP, do the following:</span></span>

1. <span data-ttu-id="f3648-104">Tarkista toimialueesi kunto [Azure-portaalissa.](https://aka.ms/aadds-health)</span><span class="sxs-lookup"><span data-stu-id="f3648-104">Check your domain’s health on the [Azure portal](https://aka.ms/aadds-health).</span></span>
1. <span data-ttu-id="f3648-105">Varmista, että kelvollinen Azure AD -tilaus on saatavilla ja Azure AD -toimialueen palvelut on otettu käyttöön.</span><span class="sxs-lookup"><span data-stu-id="f3648-105">Ensure a valid Azure AD subscription is available and Azure AD Domain Services has been enabled.</span></span>
1. <span data-ttu-id="f3648-106">Suojatun LDAP-järjestelmän käyttöönottoon tarvittava varmenne on hankittava luotettavalta julkiselta varmenteen myöntäjältä tai itse allekirjoitettu varmenne.</span><span class="sxs-lookup"><span data-stu-id="f3648-106">The certificate required to enable secure LDAP must be obtained from a trusted public certification authority or be a self-signed certificate.</span></span>
1. <span data-ttu-id="f3648-107">Varmista, että varmenne noudattaa tarvittavia [ohjeita.](https://docs.microsoft.com/azure/active-directory-domain-services/active-directory-ds-admin-guide-configure-secure-ldap#requirements-for-the-secure-ldap-certificate)</span><span class="sxs-lookup"><span data-stu-id="f3648-107">Ensure the certificate follows the required [guidelines](https://docs.microsoft.com/azure/active-directory-domain-services/active-directory-ds-admin-guide-configure-secure-ldap#requirements-for-the-secure-ldap-certificate).</span></span>

<span data-ttu-id="f3648-108">**Virheellinen varmenne**</span><span class="sxs-lookup"><span data-stu-id="f3648-108">**Invalid Certificate**</span></span>
1. <span data-ttu-id="f3648-109">Jos haluat uusia varmenteen, luo uusi varmenne ja lataa se uudelleen noudattamalla ohjeita: [LDAP:n määrittäminen.](https://docs.microsoft.com/azure/active-directory-domain-services/tutorial-configure-ldaps?WT.mc_id=Portal-Microsoft_Azure_Support)</span><span class="sxs-lookup"><span data-stu-id="f3648-109">To renew a certificate, follow the steps to create a new certificate and reupload: [Configure LDAP](https://docs.microsoft.com/azure/active-directory-domain-services/tutorial-configure-ldaps?WT.mc_id=Portal-Microsoft_Azure_Support).</span></span>
1. <span data-ttu-id="f3648-110">Lisätietoja suojatun LDAP-ilmoitusten tunnetun ongelman ratkaisemisesta Azure Active Directory -toimialueen palveluissa on [ohjeaiheessa LDAP-ilmoitusten ratkaiseminen.](https://docs.microsoft.com/azure/active-directory-domain-services/alert-ldaps?WT.mc_id=Portal-Microsoft_Azure_Support)</span><span class="sxs-lookup"><span data-stu-id="f3648-110">To resolve known issue with Secure LDAP alerts in Azure Active directory Domain Services, see [Resolve LDAP alerts](https://docs.microsoft.com/azure/active-directory-domain-services/alert-ldaps?WT.mc_id=Portal-Microsoft_Azure_Support).</span></span>