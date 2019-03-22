---
title: sama tiedostonimi on paras
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 5555
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: 68f743ee9c448565470815f8410cc6ce4b384bed
ms.sourcegitcommit: 0b6e9470c6b73616ba8bacef7010f739b7fac332
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 03/21/2019
ms.locfileid: "30742390"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a><span data-ttu-id="06dcc-102">Edellyttää Alkemia otsikon H1, H2 ja eivät toimi.</span><span class="sxs-lookup"><span data-stu-id="06dcc-102">Required Alchemy Header H1, H2's dont work.</span></span>
<span data-ttu-id="06dcc-103">Parhaita käytäntöjä ja ohjeita Alkemia authoring:</span><span class="sxs-lookup"><span data-stu-id="06dcc-103">Best Practices and guidelines for Alchemy authoring:</span></span>

1. <span data-ttu-id="06dcc-104">**Alkemia asuun kansioihin ei luoda sisäkkäisiä**- se hajottaa url-rakenteen.</span><span class="sxs-lookup"><span data-stu-id="06dcc-104">**Do not nest Alchemy Insights in folders**- this will break the url structure.</span></span> <span data-ttu-id="06dcc-105">Näkymä korjataan tämä levy.</span><span class="sxs-lookup"><span data-stu-id="06dcc-105">We're looking into fixing this.</span></span>
1. <span data-ttu-id="06dcc-106">**AlchemyInsights** -kansiossa olevat tiedostot pitäisi olla-tilojen yhdysmerkeillä pieniä tiedostonimet.</span><span class="sxs-lookup"><span data-stu-id="06dcc-106">Files in the **AlchemyInsights** folder should have lowercase filenames with hyphens for spaces ex.</span></span> <span data-ttu-id="06dcc-107">***how-to-käyttöön-oikeudenkäyntiä-pito***.</span><span class="sxs-lookup"><span data-stu-id="06dcc-107">***how-to-enable-litigation-hold***.</span></span>
    1. <span data-ttu-id="06dcc-108">Sisällyttää säännön tunnus tai erääntymisjakauman tunnus [Alkemia kumppani portal](https://alchemyportal.azurewebsites.net) ms.custom-kenttään.</span><span class="sxs-lookup"><span data-stu-id="06dcc-108">Include the Rule ID or bucket ID from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the ms.custom field.</span></span> <span data-ttu-id="06dcc-109">ex.</span><span class="sxs-lookup"><span data-stu-id="06dcc-109">ex.</span></span> <span data-ttu-id="06dcc-110">***MS.Custom: 100021***</span><span class="sxs-lookup"><span data-stu-id="06dcc-110">***ms.custom: 100021***</span></span>
1. <span data-ttu-id="06dcc-111">Käyttää mallin metatietojen loput tämän tiedoston yläosassa.</span><span class="sxs-lookup"><span data-stu-id="06dcc-111">Use the rest of the metadata at the top of this file as your template.</span></span>
1. <span data-ttu-id="06dcc-112">[Alkemia kumppani portaali](https://alchemyportal.azurewebsites.net)Siirry osioon **Customer Insight-otsikko:** ja käyttö, joka alkavan osoittaa että H1 otsikko insight.</span><span class="sxs-lookup"><span data-stu-id="06dcc-112">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="06dcc-113">Alkemia näkemyksistä on oltava vain yksi H1 yläreunassa tai ne lakkaavat toimimasta tuotannossa.</span><span class="sxs-lookup"><span data-stu-id="06dcc-113">Alchemy Insights MUST have only a single H1 at the top or they will break in production.</span></span> <span data-ttu-id="06dcc-114">H2s ei tehdä, niin Käytä **lihavointia** tai muiden sopimusten kommunikoinnin erillisiä osia.</span><span class="sxs-lookup"><span data-stu-id="06dcc-114">H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="06dcc-115">Täytä seuraavaksi luonnoksesta aines käyttäen Alkemia sääntö-sivun kohdassa asiakkaiden näkemyksistä leipäteksti</span><span class="sxs-lookup"><span data-stu-id="06dcc-115">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="06dcc-116">Luettelomerkein varustetut luettelot on hieno</span><span class="sxs-lookup"><span data-stu-id="06dcc-116">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="06dcc-117">Numeroitujen luetteloiden liian</span><span class="sxs-lookup"><span data-stu-id="06dcc-117">Numbered lists too</span></span>
    1. <span data-ttu-id="06dcc-118">**Lihavointi** ja *kursivointi* on a-ok</span><span class="sxs-lookup"><span data-stu-id="06dcc-118">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="06dcc-119">Linkit on aina oltava joko **linkkejä ”web” tai ulkoisen** tai **syvä linkkejä Käyttöliittymän osat**, ei ole sisäisiä linkkejä.</span><span class="sxs-lookup"><span data-stu-id="06dcc-119">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>
    1. <span data-ttu-id="06dcc-120">Kuvat ovat ei tueta virallisesti tällä hetkellä, mutta se on tiekartan.</span><span class="sxs-lookup"><span data-stu-id="06dcc-120">Pictures are not officially supported at this time, but it's on the roadmap.</span></span>

<span data-ttu-id="06dcc-121">Ja tämä on todella jo hieman liian pitkä.</span><span class="sxs-lookup"><span data-stu-id="06dcc-121">And this is really already a bit too long.</span></span> <span data-ttu-id="06dcc-122">Paras käytäntö on noin 400 merkkiä---</span><span class="sxs-lookup"><span data-stu-id="06dcc-122">Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="06dcc-123">Kun sisältösi on valmiina, erotettu elävään oksaan.</span><span class="sxs-lookup"><span data-stu-id="06dcc-123">Once your content is ready, pull it to the live branch.</span></span> <span data-ttu-id="06dcc-124">Siirry [portal Alkemia kumppani](https://alchemyportal.azurewebsites.net) , ja kirjoita URL-osoite-kenttään tiedoston nimi.</span><span class="sxs-lookup"><span data-stu-id="06dcc-124">Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field.</span></span> <span data-ttu-id="06dcc-125">M</span><span class="sxs-lookup"><span data-stu-id="06dcc-125">M</span></span>