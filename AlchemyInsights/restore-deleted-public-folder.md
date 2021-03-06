---
title: Poistetun yleisen kansion palauttaminen
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
- "3500007"
- "3488"
ms.openlocfilehash: d5480389c3bf50cee9fe30f7ec8d8ff28ef694ca
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 04/15/2021
ms.locfileid: "51809436"
---
# <a name="restore-a-deleted-public-folder"></a>Poistetun yleisen kansion palauttaminen

**Poistettujen kohteiden palauttaminen julkisesta kansiosta:**

- Katso [Poistettuja kohteita ei voi palauttaa Outlook 2016:n](https://aka.ms/pfrec)yleisistä kansioista.
 
**Poistetun yleisen kansion (minkä tahansa tyypin) palauttaminen:** 

- Käytä seuraavaa EXO PowerShell -komentoa:

    Syntaksi:

     `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored>`

    Esimerkki: Seuraava komento palauttaa Alikansio1:n ja sijoittaa sen \Parent1-kansioon:

    `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1`

Lisätietoja [on kohdassa Poistetun yleisen](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) kansion palauttaminen.
