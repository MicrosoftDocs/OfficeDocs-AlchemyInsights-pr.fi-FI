---
title: Kalenterin käyttöoikeudet
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3800009"
- "611"
ms.openlocfilehash: bbd49134bd4a4451649b76bb5f60b19065910cae
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 04/15/2021
ms.locfileid: "51819905"
---
# <a name="calendar-permissions"></a>Kalenterin käyttöoikeudet

Käyttäjät voivat muuttaa omia kalenterikäyttöoikeuksiaan Outlookin verkkosovelluksessa tai muissa asiakasasiakkaissa, mutta järjestelmänvalvojana sinun on ehkä myös tutkittava asiaa.  
Exchange PowerShellin cmdlet-komennolla saat käyttöoikeutesi käyttäjän kalenteriin:

`Get-MailboxFolderPermission <SMTPAddress>:\Calendar | FT -a`

Saat lisätietoja seuraavasti:

- [Get-MailboxFolderPermission](https://docs.microsoft.com/powershell/module/exchange/get-mailboxfolderpermission?view=exchange-ps)

- [Set-MailboxFolderPermission](https://docs.microsoft.com/powershell/module/exchange/set-mailboxfolderpermission?view=exchange-ps)

- [Add-MailboxFolderPermission](https://office.visualstudio.com/DefaultCollection/MAX/_queries/query/Add-MailboxFolderPermission)

Kalenterin käyttöoikeuksia käytetään kalenterien jakamisessa. Lisätietoja Outlook-kalenterin jakamisesta on näissä artikkeleissa:

- [Outlook-kalenterin jakaminen muiden kanssa](https://support.office.com/article/353ed2c1-3ec5-449d-8c73-6931a0adab88)
- [Kalenterin jakaminen yrityksille 2010:ssä](https://support.office.com/article/7ecef8ae-139c-40d9-bae2-a23977ee58d5)

Kalenterin käyttöoikeuksien vianmäärityksessä voit käyttää [tuki- ja palautusavustajatyökalua.](https://support.microsoft.com/office/e90bb691-c2a7-4697-a94f-88836856c72f)