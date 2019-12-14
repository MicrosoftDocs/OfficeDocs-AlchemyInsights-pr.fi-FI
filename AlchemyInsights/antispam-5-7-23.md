---
title: Antispam-5.7.23
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3156"
- "9001196"
ms.openlocfilehash: 9c9bc2d04fb8efaa5e75194b4ca09316d24e018e
ms.sourcegitcommit: 07b47d7f3ca191363e6bc84140e8e01524d6f08e
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 10/24/2019
ms.locfileid: "37682116"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a><span data-ttu-id="b5a93-102">Korjaa sähkö postin toimitus ongelmat virhe koodilla 5.7.23</span><span class="sxs-lookup"><span data-stu-id="b5a93-102">Fix email delivery issues for error code 5.7.23</span></span>

<span data-ttu-id="b5a93-103">Tarkista verkko tunnuksesi SPF DNS-tietue julkisesti saatavilla olevalla SPF-tai DNS-tietueen tarkistus sivulla verkossa.</span><span class="sxs-lookup"><span data-stu-id="b5a93-103">Verify the SPF DNS record for your domain at a publicly available SPF or DNS record checker on the web.</span></span>

<span data-ttu-id="b5a93-104">Varmista, että Office 365 ei tunnistanut lähtevää viestiä roska postiksi ja että se on reititetty [suuren riskin toimitus varannon](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages)kautta.</span><span class="sxs-lookup"><span data-stu-id="b5a93-104">Verify that the outbound message wasn't identified as spam by Office 365 and routed through the [High Risk Delivery Pool](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages).</span></span> <span data-ttu-id="b5a93-105">Suuren riskin toimitus varannon viestit eivät läpäise SPF-tarkastuksia, joten kohde Sähkö posti organisaatio ei hyväksy niitä.</span><span class="sxs-lookup"><span data-stu-id="b5a93-105">Messages in the High Risk Delivery Pool won't pass SPF checks, and therefore won't be accepted by the destination email organization.</span></span>

<span data-ttu-id="b5a93-106">Jos ongelma jatkuu, sinun on ehkä otettava yhteyttä Sähkö posti isännän ylläpitäjään, johon yrität lähettää sähkö postia.</span><span class="sxs-lookup"><span data-stu-id="b5a93-106">If the problem persists, you may need to contact the admin of the mail host to which you are attempting to send email.</span></span> <span data-ttu-id="b5a93-107">Merkitse heijastus viestissä käytettävissä oleva yksityiskohtainen ulkoinen virhe.</span><span class="sxs-lookup"><span data-stu-id="b5a93-107">Make note of the detailed external error available in the bounce message.</span></span>  <span data-ttu-id="b5a93-108">Office 365-tuki ei välttämättä pysty auttamaan.</span><span class="sxs-lookup"><span data-stu-id="b5a93-108">Office 365 support may not be able to assist further.</span></span>