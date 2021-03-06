---
title: Parhaiden käytäntöjen käyttäminen edistyneissä hakukyselyissä
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: cd13e2e8801db3df91140ce371813d900d72e38b
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 03/11/2021
ms.locfileid: "50746180"
---
# <a name="apply-best-practices-for-advanced-hunting-queries"></a>Parhaiden käytäntöjen käyttäminen edistyneissä hakukyselyissä

Voit saada tulokset nopeammin ja välttää aikakatkaisut monimutkaisia kyselyjä suorittamalla, soveltamalla seuraavia parhaita käytäntöjä:

- Kun yrität uusia kyselyjä, käytä aina rajaa, jotta et saa erittäin suuria tulosjoukkoja. Käytä myös tulosjoukon koon `count` alkuarviointia.
- Käytä ensin aikasuodattimia. Ihanne parasta, rajaa kyselyt seitsemään päivään.
- Lisää kyselyn alkuun heti aikasuodattimen jälkeen suodattimet, joiden odotetaan poistavan suurimman osan tiedoista.
- Kun etsit täysiä tunnuksia, käytä `has` operaattoria sen sijaan, että etsisit kokonaisia `contains` tunnuksia.
- Suorita haku tietyssä sarakkeessa kaikkien sarakkeiden sijaan.
- Kun liität taulukoita, määritä ensin taulukko, jossa on vähemmän rivejä.
- `project` vain tarvittavat sarakkeet taulukoista, jotka olet yhdistänyt.

Lisätietoja on ohjeaiheessa Edistyneet [hakukyselyn parhaat käytännöt.](https://go.microsoft.com/fwlink/?linkid=2144812)
