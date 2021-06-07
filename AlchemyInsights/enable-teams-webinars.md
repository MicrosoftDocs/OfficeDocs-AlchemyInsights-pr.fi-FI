---
title: Verkkoseinaarien Teams ottaminen käyttöön
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 06/02/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "11513"
- "9006672"
ms.openlocfilehash: 5a732e6746e9fd23e54a0b2ffeabb59623012a0e
ms.sourcegitcommit: 9de78b30602f917d58705057cdcce31fec349969
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 06/04/2021
ms.locfileid: "52793650"
---
# <a name="enable-teams-webinars"></a><span data-ttu-id="2a12b-102">Verkkoseinaarien Teams ottaminen käyttöön</span><span class="sxs-lookup"><span data-stu-id="2a12b-102">Enable Teams Webinars</span></span>

<span data-ttu-id="2a12b-103">Webinaarit ovat oletusarvoisesti käytössä.</span><span class="sxs-lookup"><span data-stu-id="2a12b-103">Webinars are enabled by default.</span></span> <span data-ttu-id="2a12b-104">Voit hallita sitä, kuka voi ajoittaa ja rekisteröidä Teams Webinaarit-Teams PowerShell-komennoilla.</span><span class="sxs-lookup"><span data-stu-id="2a12b-104">You can manage who can schedule and register for Teams Webinars by using Teams PowerShell commands.</span></span>

- <span data-ttu-id="2a12b-105">Kaikki käyttäjät, jotka voivat luoda kokouksen, voivat myös luoda webinaarikokouksen.</span><span class="sxs-lookup"><span data-stu-id="2a12b-105">All users who can create a meeting can also create a webinar meeting.</span></span> <span data-ttu-id="2a12b-106">Jos haluat hallita sitä, kuka voi Teams Webinaarit, käytä *AllowMeetingRegistration-sovellusta.*</span><span class="sxs-lookup"><span data-stu-id="2a12b-106">If you want to manage who can schedule Teams Webinars, use *AllowMeetingRegistration*.</span></span> 
- <span data-ttu-id="2a12b-107">*Oletusarvoisesti WhoCanRegister* on käytössä ja sen asetuksena on **Kaikki.**</span><span class="sxs-lookup"><span data-stu-id="2a12b-107">By default, *WhoCanRegister* is enabled and set to **Everyone**.</span></span> <span data-ttu-id="2a12b-108">Jos haluat poistaa kokouksen rekisteröinnin käytöstä, määritä *AllowMeetingRegistration-asetuksen arvoksi* **Epätosi.**</span><span class="sxs-lookup"><span data-stu-id="2a12b-108">If you want to turn off meeting registration, set *AllowMeetingRegistration* to **False**.</span></span>

<span data-ttu-id="2a12b-109">Jos haluat muuttaa näitä asetuksia, sinun on asennettava [Teams PowerShell.](/microsoftteams/teams-powershell-install)</span><span class="sxs-lookup"><span data-stu-id="2a12b-109">To change these settings, you must install [Teams PowerShell](/microsoftteams/teams-powershell-install).</span></span> <span data-ttu-id="2a12b-110">Kokouskäytännöt ovat myös käytössä Teams webinaarissa.</span><span class="sxs-lookup"><span data-stu-id="2a12b-110">Also, Meeting Policies are enforced on Teams Webinars.</span></span> <span data-ttu-id="2a12b-111">Jos esimerkiksi anonyymi liittyminen on poistettu käytöstä kokousasetuksissa, anonyymit käyttäjät eivät voi liittyä webinaariin.</span><span class="sxs-lookup"><span data-stu-id="2a12b-111">For example, if anonymous join is turned off in meeting settings, anonymous users can't join webinars.</span></span>

<span data-ttu-id="2a12b-112">Lisätietoja sen määrittämisestä, kuka voi rekisteröityä webinaariin, on kohdassa Määritä, [kuka voi rekisteröityä webinaariin.](/microsoftteams/set-up-webinars?source=docs#configure-who-can-register-for-webinars)</span><span class="sxs-lookup"><span data-stu-id="2a12b-112">To learn more about configuring who can register for webinars, see [Configure who can register for webinars](/microsoftteams/set-up-webinars?source=docs#configure-who-can-register-for-webinars).</span></span> <span data-ttu-id="2a12b-113">Lisätietoja Microsoft-luetteloiden asetuksista on artikkelissa [Microsoft-luetteloiden asetusten hallinta.](/sharepoint/control-lists)</span><span class="sxs-lookup"><span data-stu-id="2a12b-113">For more information about settings for Microsoft Lists, see [Control settings for Microsoft Lists](/sharepoint/control-lists).</span></span>