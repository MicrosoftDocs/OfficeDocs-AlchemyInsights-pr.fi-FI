---
title: Dynamics 365-lomakkeiden liiketoiminta säännöt-liiketoiminta sääntö ei ampumisen lomaketta varten
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1926"
- "6200018"
ms.openlocfilehash: 7422b67973f93ce10c1639209cc50206a1016c10
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 09/14/2020
ms.locfileid: "47711488"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a>Muutettaessa-tapahtumaa ei toteuteta, jos kenttää muutetaan ohjelmallisesti

*OnChange* -tapahtumaa ei toteuteta, jos kenttää muutetaan ohjelmallisesti *määritteen avulla.* [SetValue](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) -menetelmä. Jos haluat, että *onChange* -tapahtuman käsittelyt suoritetaan, kun olet määrittänyt arvon, sinun on käytettävä koodissa *formcontext. data. Entity-määritteen* [fireonchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) -menetelmää.

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
