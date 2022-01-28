---
description: Experience Platform Debugger release notes
keywords: debugger;experience Platform Debugger extension;chrome;extension;release notes
seo-description: Experience Platform Debugger release notes
seo-title: Release Notes
title: Versionsinformation
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: 3cff0a4199d58fa18b89af42d77813f38f30b512
workflow-type: tm+mt
source-wordcount: '287'
ht-degree: 2%

---

# Versionsinformation{#release-notes}

## Versionsinformation {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Version 1.3.0 - 28 januari 2022

* Added About link to show current release version and notes.
* Tillagd växel för att visa efterbearbetade träffar för Analytics-begäranden. The toggle is available in the Analytics section.
* Fixed remote debugging session issue when session was closed outside of the debugger.
* Fixed error notification that was visible in the Web SDK Edge Transactions tab.
* Adobe-taggar på sidborttagningsvarning har åtgärdats när felsökaren använde _satellit-objektet.
* Korrigerade vissa fall där en AppMeasurement-instans inte hittades på sidan.
* Ett problem med sidanslutningen som uppstod när felsökningsfönstret öppnades för första gången har åtgärdats.

## Version 1.2.0 - 26 oktober 2021

* Visa händelser från alla webbläsarflikar i nätverksvyn. To only see the events from the current tab, click on the lock icon in the lower right corner of the debugger.
* Updated branding.

## Version 1.1.0 - 5 oktober 2021

* Visualisering av fjärrfelsökning - Ordna fjärrfelsökningshändelserna i ett visuellt flödesschema i Adobe Experience Platform Web SDK > Edge Transactions.
* Kräv att den IMS-organisation för Adobe Experience Platform Web SDK som används på sidan matchar den inloggade organisationen när en ny fjärrfelsökningssession startas.
* Only show the edge transactions for the connected tab.

> **Obs!** Målspårningsloggar är fortfarande tillgängliga i avsnittet Loggar > Edge.
* Tillåt att olika ID-konfigurationer för dataström åsidosätts för varje instans av Adobe Experience Platform Web SDK på sidan. Växla till Lägg till felsökning aktiverat.
* Ett problem har korrigerats där Adobe Target trace-token inte alltid skickades med fjärrfelsökningssessioner för Adobe Experience Platform Web SDK.

## Version 1.0.0 May 5, 2021

* Första huvudversionen av felsökaren för Experience Platform. Intended to replace the Experience Cloud Debugger.
