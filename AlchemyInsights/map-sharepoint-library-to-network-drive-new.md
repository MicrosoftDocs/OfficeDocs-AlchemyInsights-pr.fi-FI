---
title: SharePoint määrittäminen verkkoasemaan
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 4b8245c3-a179-4524-ae83-0c22d539c202
ms.openlocfilehash: 6b7cb38362baa26bd39fe7478ef6dd1971b5b063
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 05/19/2021
ms.locfileid: "52542818"
---
# <a name="map-a-sharepoint-library-to-a-network-drive"></a>SharePoint määrittäminen verkkoasemaan

Verkkoaseman yhdistämisen sijaan synkronoi SharePoint tiedostot uuden OneDrive kanssa, joka sisältää Tiedostot tarvittaessa -ominaisuuden. Voit käyttää kaikkia tiedostoja OneDrive ilman paikallista tallennustilaa. Lisätietoja on videotiedostojen [synkronoinnissa SharePoint ja Teams](https://support.microsoft.com/office/sync-sharepoint-and-teams-files-with-your-computer-6de9ede8-5b6e-4503-80b2-6190f3354a88) tietokoneen kanssa ja Levytilan säästäminen [OneDrive Files On-Demand for Windows 10 :n avulla.](https://support.microsoft.com/office/save-disk-space-with-onedrive-files-on-demand-for-windows-10-0e6860d3-d9f3-4971-b321-7092438fb38e)

Jos määrität aseman uuden synkronointisovelluksen [OneDrive](https://support.microsoft.com/office/sync-sharepoint-and-teams-files-with-your-computer-6de9ede8-5b6e-4503-80b2-6190f3354a88)sijaan, varmista, että toimit seuraavasti:

- [SharePoint Onlineen yhdistettyjen verkkoasemien vianmääritys](/sharepoint/support/administration/troubleshoot-mapped-network-drives)

- [Todennusvirheitä ilmenee, kun asiakasohjelmalla ei ole TLS 1.2 -tukea](/sharepoint/troubleshoot/administration/authentication-errors-tls12-support#network-drive-mapped-to-a-sharepoint-library)  

**HUOMAUTUS:** Jos käytät Internet Explorer 10 -Windows 8 tai Windows 7:ssä ja saat **Käyttö**  estetty- tai Polku-ominaisuuden käyttö ei ole käytettävissä aseman yhdistämisen yhteydessä, ratkaise tämä ongelma asentamalla tämä [hotfix-korjaus.](https://support.microsoft.com/topic/error-when-you-open-a-sharepoint-document-library-in-windows-explorer-or-map-a-network-drive-to-the-library-after-you-install-internet-explorer-10-96e640ba-059f-9b09-bb91-2a0319ee8b1d)