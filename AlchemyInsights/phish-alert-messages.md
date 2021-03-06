---
title: 2491 "Phish Delivered due to tenant or user override" -käytännön ilmoitussähköpostiviestit
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 2b373423cf3e63b76a62465dd62076c023580e94
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 05/19/2021
ms.locfileid: "52544575"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a>Ilmoitus sähköpostiviesteihin Vuokraajan tai käyttäjän ohituksen vuoksi -phish Delivered due to tenant or user override -tekniikasta

Oletusilmoituskäytäntö nimeltä "Phish Delivered due to tenant or user override" on otettu käyttöön vuokraajille, joilla on Microsoft Defender for Office 365 P1- ja P2-käyttöoikeudet. Jos sait tämän ilmoituksen, voit tutkia asian seuraavasti:

1. Siirry tietoturva- ja **yhteensopivuuskeskuksen Ilmoitukset-sivulle** **valitsemalla** ilmoitusviestissä Näytä & ilmoitus.

2. Valitse ilmoitus, jos haluat nähdä vaihtoehdon Näytä **viestiluettelo tai** **Näytä viestit Resurssienhallinnassa**. Kummallakin vaihtoehdolla voit tarkastella viestin tietoja, joihin sisältyy viestitunnus. Huomaa, että Threat Explorer -linkki suodattaa automaattisesti ilmoitukset, jotka vastaavat ilmoitusehtoja. Saatat joutua muokkaamaan päivämääräsuodatinta Threat Explorerissa.

Tietojenkalasteluviesti toimitettiin manuaalisesti määritetyn ohituksen vuoksi:

- Käyttäjän määrittämä sallittu lähettäjä tai toimialue.

- Sallittu lähettäjä tai toimialue, jonka järjestelmänvalvoja on määrittänyt roskapostin estokäytännön mukaisesti.

- Sallittu IP-osoite yhteyssuodatinkäytännön avulla.

- Postinkulkusääntö (kutsutaan myös siirtosäännöksi), joka on määritetty sallimaan viestit.

Jos uskot, että viesti on virheellisesti merkitty tietojen [](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) kaakaksi, lähetä viestinäytteitä Microsoftille Outlook Ilmoita viestistä -apuohjelman avulla.
