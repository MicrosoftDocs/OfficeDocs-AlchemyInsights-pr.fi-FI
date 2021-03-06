---
title: Esimerkki Microsoft Defender for Office 365:n turvallisten liitteiden käytännön käytöstä
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
ms.openlocfilehash: 077762dd37a2974b4e519c1f242fa753623cb49a
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 03/11/2021
ms.locfileid: "50745997"
---
# <a name="example-microsoft-defender-for-office-365-safe-attachment-policy"></a>Esimerkki Microsoft Defender for Office 365:n turvallisten liitteiden käytännön käytöstä

Näillä asetuksilla otetaan käyttöön *Ei viiveitä* -niminen käytäntö, joka toimittaa viestit heti ja ottaa sitten liitteet uudelleen käyttöön skannatun tiedoston jälkeen:

- **Nimi**: Ei viiveitä
- **Kuvaus:** Toimittaa viestit heti ja ottaa liitteet uudelleen käyttöön tarkistuksen jälkeen.
- **Vastaus:** Valitse **Dynaaminen toimitus -vaihtoehto.** Lisätietoja on kohdassa Dynaaminen [toimitus turvallisten liitteiden käytännöistä.](https://go.microsoft.com/fwlink/?linkid=2092328)
-  Uudelleenohjausliite-osa: Valitse Ota uudelleenohjaus käyttöön ja kirjoita sitten microsoft 365:n yleisen järjestelmänvalvojan, suojauksen järjestelmänvalvojan tai suojausanalyytikon sähköpostiosoite, joka tutkii vahingollisia liitteitä.
- **Applied To** section: **Select The recipient domain is,** and then select your domain. Valitse **lisää** ja valitse sitten **OK.** Kun olet valmis, valitse **Tallenna.**

Lisätietoja on Office [365:n Microsoft Defenderin turvallisten liitteiden ohjeissa.](https://go.microsoft.com/fwlink/?linkid=2092213)
