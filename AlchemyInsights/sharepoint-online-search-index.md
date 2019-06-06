---
title: Hallitse SharePoint Online-haku sanastot
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: c2960093bb1cfb649c26528c9f671e6d720ff237
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 06/05/2019
ms.locfileid: "34736050"
---
# <a name="search-in-sharepoint-online"></a><span data-ttu-id="a4cde-102">SharePoint Search Online</span><span class="sxs-lookup"><span data-stu-id="a4cde-102">Search in SharePoint Online</span></span>

<span data-ttu-id="a4cde-103">Sisältö on indeksoitu ja lisätä käyttäjät löytävät mitä he etsiä SharePoint Online-hakuindeksi.</span><span class="sxs-lookup"><span data-stu-id="a4cde-103">Content must be crawled and added to the search index for users to find what they're searching for in SharePoint Online.</span></span> <span data-ttu-id="a4cde-104">Sisältöä selataan automaattisesti (selaamisen aikataulua ei voi muuttaa) indeksoinnin ennalta määritetyn aikataulun mukaan.</span><span class="sxs-lookup"><span data-stu-id="a4cde-104">Content is automatically crawled based on a pre-defined crawl schedule (the crawl schedule cannot be changed).</span></span> <span data-ttu-id="a4cde-105">Verkkohakuri luurin ja sisältöä, joka on muuttunut edellisen selaamisen jälkeen ja päivittää indeksin.</span><span class="sxs-lookup"><span data-stu-id="a4cde-105">The crawler picks up content that has changed since the last crawl and updates the index.</span></span> <span data-ttu-id="a4cde-106">Jotta sisältöä selataan ja indeksi päivittyy, noudata alla olevia ohjeita.</span><span class="sxs-lookup"><span data-stu-id="a4cde-106">To ensure content is crawled and the index is updated, follow the steps below.</span></span>

<span data-ttu-id="a4cde-107">Varmista, että sisältö löytyy tekemällä sivuston sisältöä etsittävän.</span><span class="sxs-lookup"><span data-stu-id="a4cde-107">Make sure content can be found by making site content searchable.</span></span> <span data-ttu-id="a4cde-108">Lisätietoja Katso [voi etsiä tietoja sivuston sisällön käyttöön](https://docs.microsoft.com/en-us/sharepoint/make-site-content-searchable).</span><span class="sxs-lookup"><span data-stu-id="a4cde-108">For more info, see [Enable content on a site to be searchable](https://docs.microsoft.com/en-us/sharepoint/make-site-content-searchable).</span></span>

<span data-ttu-id="a4cde-109">Hallitun ominaisuuden ovat muuttuneet tai ovat muuttuneet yhdistäminen, selata ja hallita ominaisuudet sivuston on selattu uudelleen, ennen kuin muutokset näkyvät etsinnän indeksin.</span><span class="sxs-lookup"><span data-stu-id="a4cde-109">When you have changed a managed property, or when you have changed the mapping of crawled and managed properties, the site must be re-crawled before your changes will be reflected in the search index.</span></span> 

<span data-ttu-id="a4cde-110">Muutokset tehdään haun rakenteeksi, ja ei ole todellinen sivuston, koska verkkohakuri ei automaattisesti uudelleen indeksoi sivuston.</span><span class="sxs-lookup"><span data-stu-id="a4cde-110">Because your changes are made in the search schema, and not to the actual site, the crawler will not automatically re-index the site.</span></span> 

<span data-ttu-id="a4cde-111">Saat lisätietoja, [Pyydä Läpikäymiselle ja indeksoinnille sivuston kirjasto tai luettelo uudelleen manuaalisesti](https://docs.microsoft.com/en-us/sharepoint/crawl-site-conten).</span><span class="sxs-lookup"><span data-stu-id="a4cde-111">For more info, see [Manually request crawling and re-indexing of a site, a library or a list](https://docs.microsoft.com/en-us/sharepoint/crawl-site-conten).</span></span>

 <span data-ttu-id="a4cde-112">Odota vähintään 24 tunnin hidas indeksoinnin ja koko indeksoi Nähdäksesi Jos jatkuvat edelleen ongelma.</span><span class="sxs-lookup"><span data-stu-id="a4cde-112">Wait at least 24 hours after manually requesting a crawl and full re-index to see if you're still experiencing an issue.</span></span> 

<span data-ttu-id="a4cde-113">Jos on kulunut yli 24 tuntia aloittaa selaamisen ja koko indeksoi, kirjaudu tukipyynnön.</span><span class="sxs-lookup"><span data-stu-id="a4cde-113">If more than 24 hours have passed since you initiated the crawl and full re-index, please log a support case.</span></span> <span data-ttu-id="a4cde-114">Monissa tapauksissa olemme jo käsittelet ratkaisua.</span><span class="sxs-lookup"><span data-stu-id="a4cde-114">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="a4cde-115">Antakaa meille vähintään 24 tuntia ratkaisua.</span><span class="sxs-lookup"><span data-stu-id="a4cde-115">Please give us at least 24 hours to complete a solution.</span></span>

<span data-ttu-id="a4cde-116">**Tärkeää**: Jos sivuston tai luettelon (library)-tiedosto on poistettu ja edelleen näyttää hakutuloksissa, käyttäjien tulee-virhe 404 Tiedostoa ei löydy, kun yrität käyttää.</span><span class="sxs-lookup"><span data-stu-id="a4cde-116">**Important**: If a site, document (library), or a list was deleted and still shows in the search results, users should receive an Error 404 File Not Found when trying to access.</span></span> <span data-ttu-id="a4cde-117">Tämän ongelman pitäisi olla kirjautuneena tukipyynnön lisätutkimuksia varten.</span><span class="sxs-lookup"><span data-stu-id="a4cde-117">This issue should be logged as a support case for further investigation.</span></span> 


