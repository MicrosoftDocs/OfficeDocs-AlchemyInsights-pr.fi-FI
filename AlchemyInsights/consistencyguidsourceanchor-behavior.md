---
title: ConsistencyGuid / sourceAnchor-ongelma
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: 80516ed9e15040475a8b65a1af98a1b561704d49
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 01/15/2019
ms.locfileid: "28286631"
---
# <a name="consistencyguid--sourceanchor-behavior"></a><span data-ttu-id="ce45d-102">ConsistencyGuid / sourceAnchor-ongelma</span><span class="sxs-lookup"><span data-stu-id="ce45d-102">ConsistencyGuid / sourceAnchor behavior</span></span>

<span data-ttu-id="ce45d-p101">Azure AD Connect (versio 1.1.524.0 jälkeen) nyt helpottaa käyttöä, koska msDS-ConsistencyGuid sourceAnchor määrite. Kun käytät tätä ominaisuutta, Azure AD Yhdistä määrittää synkronoinnin säännöt:</span><span class="sxs-lookup"><span data-stu-id="ce45d-p101">Azure AD Connect (version 1.1.524.0 and after) now facilitates the use of msDS-ConsistencyGuid as sourceAnchor attribute. When using this feature, Azure AD Connect automatically configures the synchronization rules to:</span></span>
  
- <span data-ttu-id="ce45d-p102">Käyttää käyttöturvallisuustiedotteen-ConsistencyGuid sourceAnchor määrite käyttäjäobjekteja. ObjectGUID käytetään muiden kohteiden tyypit.</span><span class="sxs-lookup"><span data-stu-id="ce45d-p102">Use msDS-ConsistencyGuid as the sourceAnchor attribute for User objects. ObjectGUID is used for other object types.</span></span>
    
- <span data-ttu-id="ce45d-p103">Annettu jollekin paikallisen AD-käyttäjä objekti, jonka käyttöturvallisuustiedotteen ConsistencyGuid määrite ei ole täytetty, Azure AD Yhdistä kirjoituksia objectGUID arvonsa takaisin paikalliseen Active Directoryyn käyttöturvallisuustiedotteen-ConsistencyGuid-määritettä. Käyttöturvallisuustiedotteen ConsistencyGuid määrite täytetään, kun Azure AD Yhdistä Vie objekti sitten Azure AD.</span><span class="sxs-lookup"><span data-stu-id="ce45d-p103">For any given on-premises AD User object whose msDS-ConsistencyGuid attribute isn't populated, Azure AD Connect writes its objectGUID value back to the msDS-ConsistencyGuid attribute in on-premises Active Directory. After the msDS-ConsistencyGuid attribute is populated, Azure AD Connect then exports the object to Azure AD.</span></span>
    
 <span data-ttu-id="ce45d-p104">**Huomautus:** Kerran paikallisen AD-objekti tuodaan Azure AD-muodosta (eli, tuodaan AD Connector-tilaa ja suunniteltu yhdeksi Metaverse), sen sourceAnchor-arvoa ei voi muuttaa enää. Määritä sourceAnchor arvo antanut paikallisen AD määrittää sen koska ConsistencyGuid määritteen, ennen kuin se tuodaan Azure AD Connect-objektia.</span><span class="sxs-lookup"><span data-stu-id="ce45d-p104">**Note:** Once an on-premises AD object is imported into Azure AD Connect (that is, imported into the AD Connector Space and projected into the Metaverse), you cannot change its sourceAnchor value anymore. To specify the sourceAnchor value for a given on-premises AD object, configure its msDS-ConsistencyGuid attribute before it is imported into Azure AD Connect.</span></span> 
  
<span data-ttu-id="ce45d-111">Lisätietoja SourceAnchor ja ConsistencyGuid viittaavat seuraavasti: [Azure AD Yhdistä: käsitteet suunnitella](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span><span class="sxs-lookup"><span data-stu-id="ce45d-111">For more information on SourceAnchor and ConsistencyGuid, refer to the following: [Azure AD Connect: Design concepts](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span></span>
  
