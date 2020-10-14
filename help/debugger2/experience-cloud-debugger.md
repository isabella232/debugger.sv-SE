---
description: Experience Platform Debugger undersöker dina webbsidor och hjälper dig att hitta problem med hur dina Experience Cloud-lösningar implementeras
keywords: debugger;experience Platform Debugger extension;chrome;extension
seo-description: Teknisk dokumentation för Adobe Experience Platform Debugger Chrome och Firefox Extension - Granska dina webbsidor och förstå problem med Experience Cloud-lösningar
seo-title: Adobe Experience Platform Debugger Chrome och Firefox Extension
title: Adobe Experience Platform Debugger Extension
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: 53f027d5a5ae56c7a8e812b10a2649a38df3b31d
workflow-type: tm+mt
source-wordcount: '312'
ht-degree: 13%

---


# (Beta) Adobe Experience Platform Debugger {#adobe-experience-platform-debugger}

>[!IMPORTANT]
>
>Adobe Experience Platform Debugger är för närvarande i betaversion. Dokumentationen och funktionaliteten kan komma att ändras.

Med [Adobe Experience Platform Debugger för Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) och [Firefox](https://addons.mozilla.org/en-US/firefox/addon/adobe-experience-platform-dbg/) kan du undersöka dina webbsidor och hitta problem med hur dina Experience Cloud-lösningar implementeras.

Använd Adobe Experience Platform Debugger tillsammans med andra aktiveringslösningar för Adobe för ett arbetsflöde som följande:

1. Använd [Launch](https://docs.adobe.com/content/help/en/launch/using/overview.html) eller [DTM](https://docs.adobe.com/content/help/sv-SE/dtm/using/dtm-home.html) för att infoga kod som aktiverar [Adobe Experience Cloud](https://docs.adobe.com/content/help/sv-SE/core-services/interface/experience-cloud.html) -lösningar på dina sidor.

1. Testa implementeringarna med [Adobe Cloud Platform Auditor](https://experiencecloud.adobe.com/resources/help/en_US/auditor/) .
1. Använd Adobe Experience Platform Debugger för att felsöka problem som Auditor har hittat eller för att undersöka annan information om implementeringarna.

Ovanstående steg utförs inte nödvändigtvis i den ordningen, men det är en vanlig process.

Även om du kan köra felsökningsprogrammet för Experience Platform på en webbsida är alla data som inte är offentliga bara tillgängliga i tillägget om du autentiseras i Experience Cloud på någon av dina öppna Chrome-flikar.

## Användningsfall {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Använd Experience Platform Debugger för att samla in information som hjälper dig förstå hur dina Experience Cloud-lösningar implementeras. Exempel:

* **Starta:** Se vilken egenskap, miljö, bygge som distribueras på en sida.
* **Target:** Se vilka aktiviteter du är berättigad till eller inte är berättigad till och varför.

## Videosjälvstudiekurs

>[!VIDEO](https://video.tv.adobe.com/v/32156?quality=12&learn=on)