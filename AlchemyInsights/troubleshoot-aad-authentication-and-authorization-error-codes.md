---
title: Azure AD -todennuksen ja -valtuutuksen (AADSTS) virhekoodien vianmääritys
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 03/19/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9800"
- "9005744"
ms.openlocfilehash: 14555dfcb1406fd3a3977012393714a713ff80dc
ms.sourcegitcommit: c08bed4071baa3bb5879496df3ed44fb828c8367
ms.translationtype: MT
ms.contentlocale: fi-FI
ms.lasthandoff: 03/19/2021
ms.locfileid: "51036512"
---
# <a name="troubleshoot-azure-ad-authentication-and-authorization-aadsts-error-codes"></a><span data-ttu-id="4c309-102">Azure AD -todennuksen ja -valtuutuksen (AADSTS) virhekoodien vianmääritys</span><span class="sxs-lookup"><span data-stu-id="4c309-102">Troubleshoot Azure AD Authentication and Authorization (AADSTS) error codes</span></span>

<span data-ttu-id="4c309-103">Voit ratkaista AAD-todennuksen ja käyttöoikeuksien tarkistuksen virhekoodit (AADSTS) seuraavasti:</span><span class="sxs-lookup"><span data-stu-id="4c309-103">To resolve AAD authentication and authorization error codes (AADSTS), perform the following recommended steps:</span></span>

1. <span data-ttu-id="4c309-104">**Sovelluksen virhekoodien käsittely**</span><span class="sxs-lookup"><span data-stu-id="4c309-104">**Handling error codes in your application**</span></span>

- <span data-ttu-id="4c309-105">**OAuth2.0-määritys** sisältää ohjeet virheiden käsittelemiseksi todennuksen https://tools.ietf.org/html/rfc6749#section-5.2 aikana virhevastauksen virheosan avulla.</span><span class="sxs-lookup"><span data-stu-id="4c309-105">The **OAuth2.0 spec**, https://tools.ietf.org/html/rfc6749#section-5.2, provides guidance on how to handle errors during authentication using the error portion of the error response.</span></span>

    - <span data-ttu-id="4c309-106">**-virhe:** Virhekoodimerkkijono, jonka avulla voidaan luokitella ilmenevät virhetyypit ja jota tulee käyttää virheiden korjaamiseen.</span><span class="sxs-lookup"><span data-stu-id="4c309-106">**error**: An error code string that can be used to classify types of errors that occur, and should be used to react to errors.</span></span>
    - <span data-ttu-id="4c309-107">**Virhekentässä** on useita mahdollisia arvoja: tutustu protokollan dokumentaatiolinkkeihin ja OAuth 2.0 :n tietoihin, niin saat lisätietoja virheistä ja niiden reagoinnista.</span><span class="sxs-lookup"><span data-stu-id="4c309-107">The **error** field has several possible values - review the protocol documentation links and OAuth 2.0 specs for more information about specific errors and how to react to them.</span></span>

- <span data-ttu-id="4c309-108">Tässä on esimerkkivirhevastaus:</span><span class="sxs-lookup"><span data-stu-id="4c309-108">Here is a sample error response:</span></span>
```
{
  "error": "invalid_scope",
  "error_description": "AADSTS70011: The provided value for the input parameter 'scope' is not 
valid. The scope https://example.contoso.com/activity.read is not valid.\r\nTrace ID: 255d1aef- 8c98-452f-ac51-23d051240864\r\nCorrelation ID: fb3d2015-bc17-4bb9-bb85-30c5cf1aaaa7\r\nTimestamp: 2016-01-09 02:02:12Z",
  "error_codes": [
    70011
  ],
  "timestamp": "2016-01-09 02:02:12Z",
  "trace_id": "255d1aef-8c98-452f-ac51-23d051240864",
  "correlation_id": "fb3d2015-bc17-4bb9-bb85-30c5cf1aaaa7", 
  "error_uri":"https://login.microsoftonline.com/error?code=70011"
}
```
2. <span data-ttu-id="4c309-109">**Haku nykyisen virhekoodin tiedot**</span><span class="sxs-lookup"><span data-stu-id="4c309-109">**Lookup current error code information**</span></span>

- <span data-ttu-id="4c309-110">Virhekoodit ja viestit voivat muuttua.</span><span class="sxs-lookup"><span data-stu-id="4c309-110">Error codes and messages are subject to change.</span></span> <span data-ttu-id="4c309-111">Lisätietoja uusimmista tiedoista on sivulla, jossa on tietoja AADSTS-virheen kuvauksista, korjauksista ja joistakin ehdotetuista https://login.microsoftonline.com/error ratkaisuehdotuksista.</span><span class="sxs-lookup"><span data-stu-id="4c309-111">For the most current information, see the https://login.microsoftonline.com/error page to find AADSTS error descriptions, fixes, and some suggested workarounds.</span></span>
- <span data-ttu-id="4c309-112">Voit myös etsiä ja suorittaa vianmäärityksen [AADSTS-virhekoodeista,](https://docs.microsoft.com/azure/active-directory/develop/reference-aadsts-error-codes#aadsts-error-codes) jotka on lueteltu artikkelissa Azure AD -todennus- ja [valtuutusvirhekoodit.](https://docs.microsoft.com/azure/active-directory/develop/reference-aadsts-error-codes#handling-error-codes-in-your-application)</span><span class="sxs-lookup"><span data-stu-id="4c309-112">You can also search for and troubleshoot [AADSTS error codes](https://docs.microsoft.com/azure/active-directory/develop/reference-aadsts-error-codes#aadsts-error-codes) listed in the article [Azure AD Authentication and authorization error codes](https://docs.microsoft.com/azure/active-directory/develop/reference-aadsts-error-codes#handling-error-codes-in-your-application).</span></span>

3. <span data-ttu-id="4c309-113">**Hae ohjeita**</span><span class="sxs-lookup"><span data-stu-id="4c309-113">**Get Help**</span></span>

- <span data-ttu-id="4c309-114">[Tuki- ja ohjevaihtoehdot](https://docs.microsoft.com/azure/active-directory/develop/developer-support-help-options) kehittäjille – Jos tarvitset vastauksia ongelmaan, jota ei ole käsitelty asiakirjoissamme, sinun on ehkä aika ottaa yhteyttä asiantuntijoihin ja kysyä apua.</span><span class="sxs-lookup"><span data-stu-id="4c309-114">[Support and help options for developers](https://docs.microsoft.com/azure/active-directory/develop/developer-support-help-options) - If you need an answer to a question or help in solving a problem not covered in our documentation, it might be time to reach out to experts for help.</span></span> <span data-ttu-id="4c309-115">Tässä artikkelissa on useita ehdotuksia kysymyksiin vastaamiseksi, kun kehität sovelluksia, jotka integroituvat Microsoftin tunnistetietoympäristöön.</span><span class="sxs-lookup"><span data-stu-id="4c309-115">This article provides several suggestions for getting answers to your questions as you develop apps that integrate with the Microsoft identity platform.</span></span>







