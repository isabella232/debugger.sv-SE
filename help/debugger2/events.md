---
description: Skärm för felsökningshändelser i Experience Platform
keywords: debugger;experience platform debugger extension;chrome;extension;events;dtm;target
seo-description: Skärm för felsökningshändelser i Experience Platform
seo-title: Händelser
title: Händelser
translation-type: tm+mt
source-git-commit: 53f027d5a5ae56c7a8e812b10a2649a38df3b31d
workflow-type: tm+mt
source-wordcount: '169'
ht-degree: 2%

---


# Händelser{#events}

>[!IMPORTANT]
>
>Adobe Experience Platform Debugger är för närvarande i betaversion. Dokumentationen och funktionaliteten kan komma att ändras.

På skärmen Händelser visas en grafisk vy över händelser som inträffar, som visas på en tidslinje.

![](assets/events.jpg)

För varje händelse visas en ikon för den tillämpliga lösningen på tidslinjen. Ikoner visar även ändringar i datalagret (om det är aktiverat). Håll pekaren över en ikon om du vill se en sammanfattning av händelsen. Klicka på händelsen för mer information. Du kan Skift-klicka eller Ctrl-klicka om du vill visa flera händelser.

![](assets/events-details.jpg)

Klicka på en detalj om du vill ha mer information.

![](assets/events-details-more.jpg)

## Spåra ändringar i datalager

Så här aktiverar du spårning av datalagerändringar på tidslinjen:

1. Klicka på ikonen Kugghjulet längst upp till höger.
1. Ange namnet på datalagret.

   ![](assets/event-datalayer.jpg)

1. Klicka på **[!UICONTROL Save]**.

Information om datalagrets ändringar visar allt som har tagits bort eller lagts till. Du kan klicka på **{}** om du vill se mer detaljerad ut i datalagret.

## Hämta händelseinformation

Klicka **[!UICONTROL Download]** för att ladda ned en Excel-fil med information om dina sidsamtal.