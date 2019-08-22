---
title: SharePoint Online-rajoitin
ms.author: kirks
author: Techwriter40
ms.date: 9/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.openlocfilehash: c7881c0c7331e0aa74fcc439f52157bb75a56160
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 08/22/2019
ms.locfileid: "36559838"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="2ad9c-102">SharePoint Online-rajoitin</span><span class="sxs-lookup"><span data-stu-id="2ad9c-102">SharePoint Online Throttling</span></span>

<span data-ttu-id="2ad9c-103">Käyttäjät saattavat saada 503 palvelin on varattu virhe yritettäessä siirtyä SharePoint-sivustossa tai OneDrive.</span><span class="sxs-lookup"><span data-stu-id="2ad9c-103">Users may receive a 503 server is busy error when attempting to navigate to SharePoint or OneDrive sites.</span></span> 

<span data-ttu-id="2ad9c-104">Tämä virhe voi johtua SharePoint-palvelun rajoittaminen.</span><span class="sxs-lookup"><span data-stu-id="2ad9c-104">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="2ad9c-105">SharePoint Online käyttää rajoitin ylläpitää optimaalisen suorituskyvyn ja luotettavuuden SharePoint Online-palvelun.</span><span class="sxs-lookup"><span data-stu-id="2ad9c-105">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="2ad9c-106">Rajoitin rajoittaa määrä käyttäjän toimia tai samanaikainen kutsuja (mukaan komentosarjoja tai koodia) luonnonvarojen liikakäyttö estetään.</span><span class="sxs-lookup"><span data-stu-id="2ad9c-106">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> <span data-ttu-id="2ad9c-107">Jos voit saada rajoitettu aika mukautettua koodia on 99 %.</span><span class="sxs-lookup"><span data-stu-id="2ad9c-107">If you do get throttled, 99% of the time it is because of custom code.</span></span>

<span data-ttu-id="2ad9c-108">Lisätietoja rajoittaminen Katso, [Älä rajoitettu tai estetty SharePoint Onlinessa](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span><span class="sxs-lookup"><span data-stu-id="2ad9c-108">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

<span data-ttu-id="2ad9c-109">Jos tämä virhe ei vaikuta siihen, rajoitus, voit tarkistaa onko aktiivisen ylläpidon käynnistämien että vuokralaisen siirtymällä [viestikeskuksesta](https://portal.office.com/adminportal/home#/MessageCenter).</span><span class="sxs-lookup"><span data-stu-id="2ad9c-109">If you believe this error is unrelated to throttling, you can check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span>

 <span data-ttu-id="2ad9c-110">Varmista lopuksi, käyt tiedotteiden ja tapahtumat, jotka on määrä tarkistaa [Palvelun kunto](https://portal.office.com/adminportal/home#/servicehealth) -sivulle.</span><span class="sxs-lookup"><span data-stu-id="2ad9c-110">Finally, ensure you visit the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>

