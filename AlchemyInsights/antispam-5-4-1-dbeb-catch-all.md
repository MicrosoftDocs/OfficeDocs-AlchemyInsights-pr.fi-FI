---
title: AntiSpam 5.4.1 DBEB saalis-kaikki
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001209"
- "3167"
ms.openlocfilehash: 4a56cfe74d8940e53a316d3bcc3809e8666c2e37
ms.sourcegitcommit: a8945ab0008f138b2992175b0640e78a505d29e1
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 11/04/2019
ms.locfileid: "37964137"
---
# <a name="fix-delivery-issues-for-error-code-550-541-relay-access-denied"></a><span data-ttu-id="7ae99-102">Korjaa toimitus ongelmat virhe koodissa 550 5.4.1 välityksen käyttö estetty</span><span class="sxs-lookup"><span data-stu-id="7ae99-102">Fix delivery issues for error code 550 5.4.1 Relay Access Denied</span></span>

<span data-ttu-id="7ae99-103">Tämä ongelma ilmenee, kun [tarkistetaan, onko Sähkö posti osoite kelvollinen estämään](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) käyttö ongelmia, kun siirrytään Office 365-verkkoon.</span><span class="sxs-lookup"><span data-stu-id="7ae99-103">This problem occurs when [checking to see if an email address is valid to prevent bouncebacks](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) when entering the Office 365 network.</span></span> <span data-ttu-id="7ae99-104">Kokeile seuraavia:</span><span class="sxs-lookup"><span data-stu-id="7ae99-104">Try the following:</span></span>

1. <span data-ttu-id="7ae99-105">Selvitä, onko ongelma koko toimi alueen vai yksittäisen Sähkö posti osoitteen osalta:</span><span class="sxs-lookup"><span data-stu-id="7ae99-105">Determine whether the problem is specific to an entire domain or a single email address:</span></span>
    - <span data-ttu-id="7ae99-106">Koko verkko tunnus: joskus toimi alue on synkronoitava. Kokeile asettaa [toimi alueen sisäinen ja sitten takaisin arvovaltainen](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains).</span><span class="sxs-lookup"><span data-stu-id="7ae99-106">Entire domain: Sometimes the domain needs to be synchronized; try [setting the domain to Internal and then back to Authoritative](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains).</span></span>
     - <span data-ttu-id="7ae99-107">Yksittäinen Sähkö posti osoite: joskus osoite on synkronoitava; SMTP-välitys palvelimen osoitteen muuttaminen ja sen muuttaminen takaisin voi auttaa.</span><span class="sxs-lookup"><span data-stu-id="7ae99-107">Single email address: Sometimes the address needs to be synchronized; changing the smtp proxy address and then changing it back can help.</span></span>
2. <span data-ttu-id="7ae99-108">Selvitä, onko ongelma tiettyyn ryhmään vai yleiseen kansioon.</span><span class="sxs-lookup"><span data-stu-id="7ae99-108">Determine whether the problem is specific to a group or public folder.</span></span> <span data-ttu-id="7ae99-109">Joidenkin objekti tyyppien kohdalla objektit on ehkä luotava manuaalisesti Azure Active Directoryssa.</span><span class="sxs-lookup"><span data-stu-id="7ae99-109">For some object types, the objects may need to be manually created in Azure Active Directory.</span></span>

<span data-ttu-id="7ae99-110">Jos tarvitset lisä apua, avaa tuki pyyntö ja Määritä ongelman laajuus (includidng lähetävän objektin tyyppi), jotta voimme auttaa sinua paremmin.</span><span class="sxs-lookup"><span data-stu-id="7ae99-110">If you need additional help, please open a support ticket and specify the scope of the issue (includidng the type of object you're sending to) so we can assist you better.</span></span>