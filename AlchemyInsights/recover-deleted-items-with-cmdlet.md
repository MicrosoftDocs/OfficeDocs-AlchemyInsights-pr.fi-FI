---
title: Poistettujen kohteiden palauttaminen cmdlet-komentolla
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1800008"
- "5718"
ms.openlocfilehash: d8f2a50f39d7bcd321692ab093e2efa6613e9814
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 04/15/2021
ms.locfileid: "51835808"
---
# <a name="recover-deleted-items-with-cmdlet"></a><span data-ttu-id="4aff4-102">Poistettujen kohteiden palauttaminen cmdlet-komentolla</span><span class="sxs-lookup"><span data-stu-id="4aff4-102">Recover deleted items with cmdlet</span></span>

- <span data-ttu-id="4aff4-103">Voit tarkastella [poistettuja kohteita postilaatikoissa Get-RecoverableItems-cmdlet-komentoa](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps) käyttämällä.</span><span class="sxs-lookup"><span data-stu-id="4aff4-103">Use the [Get-RecoverableItems](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps) cmdlet to view deleted items in mailboxes.</span></span> <span data-ttu-id="4aff4-104">Kun olet löytänyt poistetut kohteet, palauta ne [Restore-RecoverableItems-cmdlet-komentoa](https://docs.microsoft.com/powershell/module/exchange/Restore-RecoverableItems?view=exchange-ps) käyttämällä.</span><span class="sxs-lookup"><span data-stu-id="4aff4-104">After you find the deleted items, you use the [Restore-RecoverableItems](https://docs.microsoft.com/powershell/module/exchange/Restore-RecoverableItems?view=exchange-ps) cmdlet to restore them.</span></span>

- <span data-ttu-id="4aff4-105">Katso täydelliset tiedot [kohdassa Get-RecoverableItems](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps).</span><span class="sxs-lookup"><span data-stu-id="4aff4-105">See full details in [Get-RecoverableItems](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps).</span></span>

- <span data-ttu-id="4aff4-106">Sinulla on oltava postilaatikon tuonti- ja vientirooli määritettynä, ennen kuin voit suorittaa tämän cmdlet-komentoa.</span><span class="sxs-lookup"><span data-stu-id="4aff4-106">You need to be assigned the Mailbox Import Export role before you can run this cmdlet.</span></span> <span data-ttu-id="4aff4-107">Lisätietoja on [kohdassa Get-RecoverableItems.](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps)</span><span class="sxs-lookup"><span data-stu-id="4aff4-107">Please see [Get-RecoverableItems](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps) for more information.</span></span>
