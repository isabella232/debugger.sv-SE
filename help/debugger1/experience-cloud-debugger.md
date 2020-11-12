---
description: Felsökaren undersöker dina webbsidor och hjälper dig att hitta problem med hur dina Experience Cloud-lösningar implementeras
keywords: debugger;experience cloud debugger extension;chrome;extension
seo-description: Teknisk dokumentation för Adobe Experience Cloud Debugger Chrome Extension - Granska dina webbsidor och förstå problem med implementeringen av din Experience Cloud-lösning
seo-title: Adobe Experience Cloud Debugger Chrome Extension
title: Adobe Experience Cloud Debugger Extension
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 13%

---


# Adobe Experience Cloud Debugger Extension{#adobe-experience-cloud-debugger-extension}

Med [Adobe Experience Cloud Debugger-tillägget för Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) kan du undersöka dina webbsidor och hitta problem med hur dina Experience Cloud-lösningar implementeras.

Använd Adobe Experience Cloud Debugger-tillägget tillsammans med andra Adobe-aktiveringslösningar för ett arbetsflöde som följande:

1. Använd [Adobe Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/overview.html) eller [DTM](https://docs.adobe.com/content/help/sv-SE/dtm/using/dtm-home.html) för att infoga kod som aktiverar [Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html) -lösningar på dina sidor.

1. Testa implementeringarna med [Adobe Experience Platform Auditor](https://docs.adobe.com/content/help/en/auditor/using/overview.html) .
1. Använd tillägget Adobe Experience Cloud Debugger för att felsöka problem som Auditor har hittat eller för att undersöka annan information om implementeringarna.

Ovanstående steg utförs inte nödvändigtvis i den ordningen, men det är en vanlig process.

Även om du kan köra felsökaren på en webbsida är alla icke-offentliga data bara tillgängliga i tillägget om du autentiseras i Experience Cloud på någon av dina öppna Chrome-flikar.

## Use Cases {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Använd Felsökning för att samla in information som hjälper dig att förstå hur dina Experience Cloud-lösningar implementeras. Exempel:

* **Platform Launch:** Se vilken egenskap, miljö, bygge som distribueras på en sida.
* **Target:** Se vilka aktiviteter du är berättigad till eller inte är berättigad till och varför.
