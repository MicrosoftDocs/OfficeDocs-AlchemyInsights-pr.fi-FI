---
title: Poistetun tiedoston tai kansion palauttaminen
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: ba1573a5-9f44-482b-8082-6f648f169449
ms.openlocfilehash: d5250d75a982c0afc9d3e1b2a43be2ba9c3e8f59
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 06/04/2019
ms.locfileid: "34716504"
---
## <a name="restore-a-deleted-file-or-folder"></a><span data-ttu-id="8edef-102">Poistetun tiedoston tai kansion palauttaminen</span><span class="sxs-lookup"><span data-stu-id="8edef-102">Restore a deleted file or folder</span></span>

<span data-ttu-id="8edef-103">SharePoint Online säilyttää kaiken sisällön varmuuskopiot 14 lisäpäiviin todellinen poistamisen jälkeen.</span><span class="sxs-lookup"><span data-stu-id="8edef-103">SharePoint Online retains backups of all content for 14 additional days beyond actual deletion.</span></span> <span data-ttu-id="8edef-104">Jos sisältöä ei voi palauttaa Roskakori tai palauttaa tiedostoja kautta, järjestelmänvalvojat voivat ottaa yhteyttä Microsoft Support pyytää palautusta milloin tahansa ikkunan 14 päivän sisällä.</span><span class="sxs-lookup"><span data-stu-id="8edef-104">If content cannot be restored via the Recycle Bin or Files Restore, an administrator can contact Microsoft Support to request a restore any time inside the 14 day window.</span></span> <span data-ttu-id="8edef-105">Palautukset varmuuskopioista voi suorittaa vain sivustokokoelmien tai alisivustoille kuin tiettyjen tiedostojen, luettelot tai kirjastot.</span><span class="sxs-lookup"><span data-stu-id="8edef-105">Restorations from backups can only be completed for site collections or sub-sites, not for specific files, lists, or libraries.</span></span>

<span data-ttu-id="8edef-106">Kun poistat Sharepoint-kohteen tai sivuston, se ei ole välittömästi poistaa.</span><span class="sxs-lookup"><span data-stu-id="8edef-106">When you delete an item or site from Sharepoint, it isn't immediately removed.</span></span> <span data-ttu-id="8edef-107">Poistetut viestit Roskakori siirtyvät ajan kuluessa.</span><span class="sxs-lookup"><span data-stu-id="8edef-107">Deleted items go into the recycle bin for a period of time.</span></span> <span data-ttu-id="8edef-108">Tänä aikana voit palauttaa poistetut kohteet niiden alkuperäiseen sijaintiin.</span><span class="sxs-lookup"><span data-stu-id="8edef-108">During that time, you can restore the items you deleted to their original location.</span></span> <span data-ttu-id="8edef-109">Lisätietoja on osoitteessa alla olevia linkkejä.</span><span class="sxs-lookup"><span data-stu-id="8edef-109">For more information, please visit the links below.</span></span>

<span data-ttu-id="8edef-110">[SharePoint-sivuston Roskakorin kohteiden palauttaminen](https://support.office.com/en-us/article/restore-deleted-items-from-the-site-collection-recycle-bin-5fa924ee-16d7-487b-9a0a-021b9062d14b?ui=en-US&amp;rs=en-US&amp;ad=US).</span><span class="sxs-lookup"><span data-stu-id="8edef-110">[Restore items in the Recycle Bin of a SharePoint site](https://support.office.com/en-us/article/restore-deleted-items-from-the-site-collection-recycle-bin-5fa924ee-16d7-487b-9a0a-021b9062d14b?ui=en-US&amp;rs=en-US&amp;ad=US).</span></span>

[<span data-ttu-id="8edef-111">Palauta poistetut tiedostot tai kansiot OneDrive</span><span class="sxs-lookup"><span data-stu-id="8edef-111">Restore deleted files or folders in OneDrive</span></span>](https://support.office.com/en-us/article/Restore-deleted-files-or-folders-in-OneDrive-949ada80-0026-4db3-a953-c99083e6a84f)

[<span data-ttu-id="8edef-112">Palauttaa poistetun sivustokokoelman (mukaan lukien ryhmän, tietoliikenteen ja muut sivustot)</span><span class="sxs-lookup"><span data-stu-id="8edef-112">Restore a deleted site collection (Including group, communication and other sites)</span></span>](https://docs.microsoft.com/sharepoint/restore-deleted-site-collection)

[<span data-ttu-id="8edef-113">Palauta poistettu OneDrive-sivusto</span><span class="sxs-lookup"><span data-stu-id="8edef-113">Restore a deleted OneDrive site</span></span>](https://docs.microsoft.com/en-us/onedrive/restore-deleted-onedrive)

<span data-ttu-id="8edef-114">Bulk recycle bin toimintojen valvojat voivat harkita [Sharepoint Online PNP](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps).</span><span class="sxs-lookup"><span data-stu-id="8edef-114">For bulk recycle bin actions, admins may consider using [Sharepoint Online PNP](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps).</span></span>

## <a name="files-restore-feature"></a><span data-ttu-id="8edef-115">Tiedostojen palauttaminen</span><span class="sxs-lookup"><span data-stu-id="8edef-115">Files Restore feature</span></span>

<span data-ttu-id="8edef-116">Jos paljon OneDrive tai Sharepoint-tiedostojen tulee poistaa, korvata, vioittunut tai haittaohjelmia tartunnan, edellisen kerran, tiedostojen palauttaminen-ominaisuuden avulla voit palauttaa koko OneDrive tai Sharepoint-kirjastosta.</span><span class="sxs-lookup"><span data-stu-id="8edef-116">If lots of your OneDrive or Sharepoint files get deleted, overwritten, corrupted, or infected by malware, you can restore your entire OneDrive or Sharepoint library to a previous time using the files restore feature.</span></span>

[<span data-ttu-id="8edef-117">Palauttaa OneDrive-kirjasto</span><span class="sxs-lookup"><span data-stu-id="8edef-117">Restore a OneDrive library</span></span>](https://support.office.com/en-us/article/restore-your-onedrive-fa231298-759d-41cf-bcd0-25ac53eb8a15)

[<span data-ttu-id="8edef-118">Asiakirjakirjaston palautus</span><span class="sxs-lookup"><span data-stu-id="8edef-118">Restore a Document library</span></span>](https://support.office.com/en-us/article/restore-a-document-library-317791c3-8bd0-4dfd-8254-3ca90883d39a?ui=en-US&amp;rs=en-US&amp;ad=US.)
