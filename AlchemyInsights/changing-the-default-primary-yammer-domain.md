---
title: Yammer-oletustoimialueen vaihtaminen
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002662"
- "5162"
ms.openlocfilehash: 099feb5c58a2b1068a2ec501ff966c6ac73d804d
ms.sourcegitcommit: 87aa36e3ff4835efb120a320c5169bfa77199ec4
ms.translationtype: HT
ms.contentlocale: fi-FI
ms.lasthandoff: 05/01/2020
ms.locfileid: "43991133"
---
# <a name="changing-the-defaultprimary-yammer-domain"></a>Yammerin oletustoimialueen / ensisijaisen toimialueen vaihtaminen

Yammerin URL-osoite sisältää Yammer-verkostosi nykyisen ensisijaisen toimialuenimen. Tämä toimialuenimi ei välttämättä vastaa Office 365:ssä tai Azure AD:ssä määritettyä ensisijaista toimialuenimeä. Toiminnassa on eroja riippuen siitä, kuinka monta mukautettua toimialuetta vuokraajaan on liitetty ja onko Yammerin kokoonpano tuettu (1 vuokraaja, 1 verkko tai 1:1). Lisätietoja [Yammer-toimialueista ja Office 365:stä](https://docs.microsoft.com/yammer/configure-your-yammer-network/manage-yammer-domains) on saatavilla.

Yleisin syy väärän toimialueen näkemiseen on se, että on olemassa useita Yammer-verkostoja, jotka on yhdistettävä. [Yhdistäminen yhdeksi verkostoksi](https://docs.microsoft.com/yammer/configure-your-yammer-network/consolidate-multiple-yammer-networks) verkoston siirtotyökalulla on tärkeä ensimmäinen askel. Tee tämä ennen kuin määrität ensisijaisen toimialueen.

**Ei mukautettuja toimialueita**

Uusien vuokraajien kohdalla Yammerissa käytetään vuokraajan oletustoimialuetta (esim. fabrikam.onmicrosoft.com). Ensisijaiseksi toimialueeksi määritetään yammer.com/fabrikam.onmicrosoft.com.

**Yksi mukautettu toimialue**

Yammer valitsee vuokraajan mukautetun toimialueen (esim. fabrikam.com) automaattisesti Yammerin ensisijaiseksi toimialueeksi. Toimialueeksi määritetään yammer.com/fabrikam.com. Tämä muutos tehdään toimialueen synkronointipalvelussa, ja sen voimaantulo voi kestää enintään 24 tuntia.

**Useita mukautettuja toimialueita**

Yammerin ensisijainen toimialue voi olla eri kuin vuokraajan oletustoimialue. Mukautettuja toimialueita on useita, joten Yammer ei yritä arvata oikeaa toimialuetta käytettävissä olevista vaihtoehdoista. Sinun on avattava tukipyyntö, jotta ensisijaiseksi toimialuenimeksi vaihdetaan valitsemasi ensisijainen toimialue.

**Muita vianmääritysohjeita**

Joissakin tapauksissa toimialueita on saatettu siirtää vuokraajien välillä eikä toimialueen synkronointipalvelun suorittaminen ole onnistunut. Saatat kohdata kirjautumiseen liittyviä tai muita ongelmia väärän ensisijaisen toimialueen lisäksi. Jos haluat ratkaista tämän ongelman, toimialueet on ehkä siirrettävä oikeaan verkostoon Microsoft-tuen avulla. Tämä tilanne vaatii suoraa tukea ja sen ratkaiseminen saattaa kestää jonkin aikaa, varsinkin jos toimialuenimien luettelo on hyvin pitkä. Avaa tukipyyntö, jotta saat apua tämäntyyppisten ongelmien ratkaisemiseen.

Kun työskentelet tukiedustajan kanssa, hän tarkistaa, että toimialueet on vahvistettu hallinnassasi olevassa vuokraajassa. Hän voi kysyä lisävarmennuskysymyksiä toimialueistasi, jos ne on liitetty vuokraajaasi mutta DNS ei ole vahvistanut niitä. Varmista, että DNS on vahvistanut toimialueet prosessin nopeuttamiseksi.