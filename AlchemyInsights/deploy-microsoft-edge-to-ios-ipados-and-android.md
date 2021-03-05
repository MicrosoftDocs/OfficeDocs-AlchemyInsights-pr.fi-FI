---
title: Microsoft Edgen käyttöönotto iOS:ssä, iPadOS:ssä ja Androidissa
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/10/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "8241"
- "9004604"
ms.openlocfilehash: 524e87ab57e29823361053093708c83831f19687
ms.sourcegitcommit: 03378c78eadac5d950802dcbacc328bca3314032
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 02/10/2021
ms.locfileid: "50194480"
---
# <a name="deploy-microsoft-edge-to-ios-ipados-and-android"></a><span data-ttu-id="f267f-102">Microsoft Edgen käyttöönotto iOS:ssä, iPadOS:ssä ja Androidissa</span><span class="sxs-lookup"><span data-stu-id="f267f-102">Deploy Microsoft Edge to iOS, iPadOS, and Android</span></span>

<span data-ttu-id="f267f-103">Alla esitetty ohjattu skenaario auttaa microsoft Edgen määrittämisessä iOS-, iPadOS- ja Android-laitteiden käyttäjille.</span><span class="sxs-lookup"><span data-stu-id="f267f-103">The guided scenario summarized below will help you assign Microsoft Edge to users of iOS, iPadOS, and Android devices.</span></span>

> [!NOTE]
> <span data-ttu-id="f267f-104">Jos olet estänyt käyttäjiä rekisteröimällä mobiililaitteita, tämä ohjattu skenaario ei toimi, ja käyttäjien on asennettava Microsoft Edge itse.</span><span class="sxs-lookup"><span data-stu-id="f267f-104">If you blocked users from enrolling mobile devices, this guided scenario won't work and the users will need to install Microsoft Edge on their own.</span></span>

<span data-ttu-id="f267f-105">Ohjattu skenaario sisältää seuraavat vaiheet:</span><span class="sxs-lookup"><span data-stu-id="f267f-105">The guided scenario involves the following steps:</span></span>

1. [<span data-ttu-id="f267f-106">Ennakkovaatimukset</span><span class="sxs-lookup"><span data-stu-id="f267f-106">Prerequisites</span></span>](https://docs.microsoft.com/mem/intune/fundamentals/guided-scenarios-edge#prerequisites)
2. [<span data-ttu-id="f267f-107">Johdanto</span><span class="sxs-lookup"><span data-stu-id="f267f-107">Introduction</span></span>](https://docs.microsoft.com/mem/intune/fundamentals/guided-scenarios-edge#step-1---introduction)
3. [<span data-ttu-id="f267f-108">Perusteet</span><span class="sxs-lookup"><span data-stu-id="f267f-108">Basics</span></span>](https://docs.microsoft.com/mem/intune/fundamentals/guided-scenarios-edge#step-2---basics)
4. [<span data-ttu-id="f267f-109">Määritys</span><span class="sxs-lookup"><span data-stu-id="f267f-109">Configuration</span></span>](https://docs.microsoft.com/mem/intune/fundamentals/guided-scenarios-edge#step-3---configuration)
5. [<span data-ttu-id="f267f-110">Tehtävät</span><span class="sxs-lookup"><span data-stu-id="f267f-110">Assignments</span></span>](https://docs.microsoft.com/mem/intune/fundamentals/guided-scenarios-edge#step-4---assignments)
6. [<span data-ttu-id="f267f-111">Tarkistus ja luominen</span><span class="sxs-lookup"><span data-stu-id="f267f-111">Review and creation</span></span>](https://docs.microsoft.com/mem/intune/fundamentals/guided-scenarios-edge#step-5---review--create)

<span data-ttu-id="f267f-112">Kun olet suorittanut ohjatun skenaarion vaiheet, Microsoft Intune -käytännöt mahdollistavat seuraavat Microsoft Edge for Businessin ominaisuudet:</span><span class="sxs-lookup"><span data-stu-id="f267f-112">After you complete the steps in the guided scenario, Microsoft Intune policies will enable the following features of Microsoft Edge for business:</span></span>

- <span data-ttu-id="f267f-113">Kaksi käyttäjätietoa</span><span class="sxs-lookup"><span data-stu-id="f267f-113">Dual identity</span></span>
- <span data-ttu-id="f267f-114">Integrointi Microsoft Intune -sovelluksen suojauskäytäntöön</span><span class="sxs-lookup"><span data-stu-id="f267f-114">Integration with Microsoft Intune app protection policy</span></span>
- <span data-ttu-id="f267f-115">Azure Active Directory -sovelluksen välityspalvelimen integrointi</span><span class="sxs-lookup"><span data-stu-id="f267f-115">Integration with Azure Active Directory Application Proxy</span></span>
- <span data-ttu-id="f267f-116">Hallitut suosikit ja aloitussivun pikanäppäimet</span><span class="sxs-lookup"><span data-stu-id="f267f-116">Managed favorites and home page shortcuts</span></span>