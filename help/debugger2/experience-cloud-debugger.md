---
description: Felsökaren undersöker dina webbsidor och hjälper dig att hitta problem med hur Experience Cloud-lösningarna implementeras
keywords: debugger;experience cloud debugger extension;chrome;extension
seo-description: Teknisk dokumentation för Adobe Experience Cloud Debugger 2.0 Chrome och Firefox Extension - Granska dina webbsidor och förstå problem med Experience Cloud-lösningens implementeringar
seo-title: Adobe Experience Platform Debugger Chrome och Firefox Extension
title: Adobe Experience Platform Debugger Extension
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: 3dc1876c0516b7a81f68a207c6a1651bc95b17ab

---


# (Beta) Adobe Experience Platform Debugger 2.0 {#adobe-experience-platform-debugger}

>[!IMPORTANT]
>
>Adobe Experience Cloud Debugger 2.0 är en betaversion. Dokumentationen och funktionaliteten kan komma att ändras.

Felsökaren för [Adobe Experience Platform för Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) och [Firefox](https://addons.mozilla.org/en-US/firefox/addon/adobe-experience-platform-dbg/) undersöker dina webbsidor och hjälper dig att hitta problem med hur Experience Cloud-lösningarna implementeras.

Använd Adobe Experience Platform Debugger tillsammans med andra Adobe-aktiveringslösningar för ett arbetsflöde som följande:

1. Använd [Launch](https://docs.adobe.com/content/help/en/launch/using/overview.html) eller [DTM](https://docs.adobe.com/content/help/en/dtm/using/dtm-home.html) för att infoga kod som aktiverar [Adobe Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) -lösningar på era sidor.

1. Använd [Adobe Cloud Platform Auditor](https://experiencecloud.adobe.com/resources/help/en_US/auditor/) för att testa implementeringarna.
1. Använd Adobe Experience Platform Debugger för att felsöka problem som Auditor har hittat eller för att undersöka annan information om era implementeringar.

Ovanstående steg utförs inte nödvändigtvis i den ordningen, men det är en vanlig process.

Även om du kan köra felsökaren på en webbsida är alla icke-offentliga data bara tillgängliga i tillägget om du autentiseras i Experience Cloud på någon av dina öppna Chrome-flikar.

## Användningsexempel {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Använd Felsökning för att samla in information som hjälper er att förstå hur era Experience Cloud-lösningar implementeras. Exempel:

* **Starta:** Se vilken egenskap, miljö, bygge som distribueras på en sida.
* **Target:** Se vilka aktiviteter du är berättigad till eller inte är berättigad till och varför.
