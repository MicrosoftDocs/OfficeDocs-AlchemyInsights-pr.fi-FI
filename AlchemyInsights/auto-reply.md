---
title: 'Voit määrittää automaattisen vastauksen kaikille Microsoft 365 -ryhmälle lähetetyille sähköposteille:'
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/19/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "8586"
- "9003200"
ms.openlocfilehash: c3c1d4e6b16b54d92771d7bdecdc9cb12bbf888c
ms.sourcegitcommit: 379e132c4d21ecf703d5506484ec96a767fdda39
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 03/04/2021
ms.locfileid: "50481349"
---
# <a name="to-configure-auto-reply-for-all-emails-sent-to-microsoft-365-group"></a>Voit määrittää automaattisen vastauksen kaikille Microsoft 365 -ryhmälle lähetetyille sähköposteille:

**Muodosta yhteys EXO PowerShelliin vuokraajan järjestelmänvalvojan tilillä ja käytä seuraavaa komentoa:**

`Set-MailboxAutoReplyConfiguration -Identity groupmailbox -AutoReplyState Enabled -InternalMessage "Internal auto-reply message." -ExternalMessage "External auto-reply message`

> [!NOTE]
> Muuta **groupmailbox** ryhmän nimeksi, johon haluat määrittää automaattisen vastauksen.

