---
description: Felsökaren undersöker dina webbsidor och hjälper dig att hitta problem med hur dina Experience Cloud-lösningar implementeras
keywords: felsökare;upplev felsökningstillägg i molnet;kroma;tillägg
seo-description: Teknisk dokumentation för Adobe Experience Cloud Debugger Chrome Extension - Granska dina webbsidor och förstå problem med implementeringen av din Experience Cloud-lösning
seo-title: Adobe Experience Cloud Debugger Chrome Extension
title: Adobe Experience Cloud Debugger Extension
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
exl-id: 02d88172-3fb1-4111-a80d-e9d46df9ea1e
source-git-commit: e3f0fa30fa5caeccc9a01b5d1949722836645da9
workflow-type: tm+mt
source-wordcount: '274'
ht-degree: 5%

---

# Adobe Experience Cloud Debugger Extension{#adobe-experience-cloud-debugger-extension}

[Adobe Experience Cloud Debugger-tillägget för Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) undersöker dina webbsidor och hjälper dig att hitta problem med hur dina Experience Cloud-lösningar implementeras.

Använd Adobe Experience Cloud Debugger-tillägget tillsammans med andra Adobe-aktiveringslösningar för ett arbetsflöde som följande:

1. Använd [Adobe Experience Platform Launch](https://experienceleague.adobe.com/docs/launch/using/home.html) för att infoga kod som aktiverar [Adobe Experience Cloud](https://experienceleague.adobe.com/docs/home.html)-lösningar på dina sidor.

1. Använd [Adobe Experience Platform Auditor](https://docs.adobe.com/content/help/en/auditor/using/overview.html) för att testa implementeringarna.
1. Använd tillägget Adobe Experience Cloud Debugger för att felsöka problem som Auditor har hittat eller för att undersöka annan information om implementeringarna.

Ovanstående steg utförs inte nödvändigtvis i den ordningen, men det är en vanlig process.

Även om du kan köra felsökaren på en webbsida är alla icke-offentliga data bara tillgängliga i tillägget om du autentiseras i Experience Cloud på någon av dina öppna Chrome-flikar.

## Använd fall {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Använd Felsökning för att samla in information som hjälper dig att förstå hur dina Experience Cloud-lösningar implementeras. Exempel:

* **platform launch:** Se vilken egenskap, miljö, bygge som ska distribueras på en sida.
* **Target:** Se vilka aktiviteter du är berättigad till eller inte är berättigad till och varför.
