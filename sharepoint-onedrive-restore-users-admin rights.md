---
title: Antaa käyttäjille ja SharePoint-OneDrive
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: ae4d2c00be6387744bdc84e1d8a021530f80f8fa
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 06/04/2019
ms.locfileid: "34715209"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a>Antaa käyttäjille ja SharePoint-OneDrive

<p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Tämä ongelma ilmenee usein, kun käyttäjä poistetaan ja luodaan uudelleen sama käyttäjätunnus (UPN) kanssa. Uusi tili on luotu käyttämällä eri PUID (yksilöllisen Passport-tunnus)-arvoa. Kun käyttäjä yrittää käyttää sivustokokoelman tai niiden OneDrive, käyttäjällä on virheellinen PUID. Toinen tilanne liittyy directory-synkronointia Active Directoryn organisaatioyksikössä (OU). Jos käyttäjät ovat jo kirjautuneena SharePoint-ovat siirretään eri OU ja SharePointin kanssa resynced, he saattavat kohdata tämän ongelman.</span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Voit ratkaista tämän ongelman, palauta alkuperäinen UPN artikkelin, jossa <a href="https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide">palauttaa käyttäjälle Office 365: ssä.</a></span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Tämän jälkeen voit tarkistaa käyttäjällä on OneDrive-sivuston admin oikeudet tekemällä vaiheet <a href="https://docs.microsoft.com/en-us/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive">admin's lisätä käyttäjän OneDrive.</a></span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Lisätietoja käyttöoikeustasoista on artikkelissa, <a href="https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels">tietoja SharePoint-käyttöoikeustasojen.</a>&nbsp;</span></p>