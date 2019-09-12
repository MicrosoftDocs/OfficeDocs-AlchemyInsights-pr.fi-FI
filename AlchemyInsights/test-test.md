---
title: SharePoint Online-termi säilöstä puuttuvat termit
ms.author: pebaum
author: Techwriter40
ms.date: 10/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1243"
- "5200021"
ms.openlocfilehash: 0f9efe980987c9ffc64fcf9d5d72a67f0a622867
ms.sourcegitcommit: 23772ebd25a86a879ced40b10566a35e76a79eb5
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 09/05/2019
ms.locfileid: "36762055"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a>BitLocker-Sala uksen ottaminen käyttöön Intune-avulla

Intune-pääte pisteiden suojaus käytäntöä voidaan käyttää Windows-laitteiden Boitlocker-salaus asetusten määrittämiseen kohdassa: (ja uudemmat) asetukset suojaamaan laitteita Intune-toiminnolla

Huomaa, että monet uudemmat Windows 10-laitteet tukevat automaattista BitLocker-salausta, joka käynnistyy ilman MDM-käytännön soveltamista. Tämä saattaa vaikuttaa käytännön soveltamiseen, jos muita kuin oletus asetuksia on määritetty. Katso FAQ lisä tietoja.


FAQ  k: mitkä Windows-versiot tukevat laitteen salausta pääte pisteiden suojaus käytännön avulla?
 V: Intune-pääte pisteen suojaus käytännön asetukset toteutetaan BitLocker-SALAUS menetelmän avulla.Kaikki versiot ja Windows-versiot eivät tue BitLocker-salaus menetelmän tarjoaja. 
      Tällä kertaa Windows-versiot: Enterprise; Koulutus, mobiili, mobiili yritys ja ammatillinen (rakentaa 1809 eteenpäin) tuetaan.




K: Jos laite on jo salattu BitLockerin kanssa käyttämällä käyttö järjestelmän oletus asetuksia salaus menetelmälle ja Sala kirjoituksen voimakkuudesta (XTS-AES-128) soveltaa käytäntöä, jossa eri asetukset laukaisevat automaattisesti uudelleensalaus aseman uusilla asetuksilla?

A: ei. Jotta uudet salaus asetukset voidaan ottaa käyttöön, asema on ensin purettava.

Huomautus Autopilot-toiminnolla rekisteröidyille laitteille automaattista salausta, joka tapahtuisi OOBE-toiminnon aikana, ei käynnistetä, ennen kuin Intune-käytäntöä arvioidaan, jolloin käytäntöpohjaisia asetuksia voidaan käyttää käyttö järjestelmän oletus arvojen sijasta




Q Jos laite on salattu Intune-käytännön soveltamisen seura uksena, salaus puretaan, kun kyseinen käytäntö poistetaan?

A: Sala ukseen liittyvän käytännön poistaminen ei johda määritettyjen asemien Sala uksen purkamiseen.




K: Miksi Intune-yhteensopivuus käytäntö osoittaa, että laitteellasi ei ole "BitLocker käytössä", mutta se on?

V: "BitLocker Enabled"-asetus Intunen yhteensopivuus käytännössä hyödyntää Windows Device Health Attestation (DHA)-asiakasta. Tämä asiakas mittaa vain laitteen tilan käynnistyksen aikana. Jos laitetta ei ole käynnistetty uudelleen, koska BitLocker-salaus on suoritettu loppuun, DHA-asiakas palvelu ei ilmoita BitLockerin aktiivi seksi.