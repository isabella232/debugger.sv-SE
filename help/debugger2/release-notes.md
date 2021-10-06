---
description: Versionsinformation om felsökning för Experience Platform
keywords: felsökning;Experience Platform Debugger extension;chrome;extension;release notes
seo-description: Experience Platform Debugger release notes
seo-title: Release Notes
title: Versionsinformation
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: 016054f3cd47b9089afbdfbe75c5beec6945ce56
workflow-type: tm+mt
source-wordcount: '169'
ht-degree: 8%

---

# Versionsinformation{#release-notes}

## Versionsinformation {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Version 1.1.0 5 oktober 2021

## Nya funktioner

<table id="table">
 <thead>
  <tr>
   <th colname="col1" class="entry"> Funktion </th>
   <th colname="col2" class="entry"> Beskrivning </th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td colname="col1"> <p> Visualisering av fjärrfelsökning </p> </td>
   <td colname="col2"> <p> Ordna fjärrfelsökningshändelserna i ett visuellt flödesdiagram i Adobe Experience Platform Web SDK &gt; Edge Transactions. Kräv dessutom att den IMS-organisation för Adobe Experience Platform Web SDK som används på sidan matchar den inloggade organisationen när du startar en ny fjärrfelsökningssession. Filtrera kanttransaktioner efter den anslutna fliken.</p> <p> <b>Obs! </b> Målspårningsloggar är fortfarande tillgängliga i avsnittet Loggar &gt; Edge.</p> </td>
  </tr>
  <tr>
   <td colname="col1"> <p> Förbättringar i konfigurationsavsnittet för Adobe Experience Platform Web SDK </p> </td>
   <td colname="col2"> <p> Tillåt att separata ID-konfigurationer för dataström åsidosätts för varje instans på sidan. Växla till Lägg till felsökning aktiverat.</p> </td>
  </tr>
 </tbody>
</table>

## Felkorrigeringar

* Ett problem har korrigerats där Adobe Target trace-token inte alltid skickades med fjärrfelsökningssessioner för Adobe Experience Platform Web SDK.

## Version 1.0.0 5 maj 2021

## Nya funktioner

<table id="table_7EFCAF456B14404FAF3715FC56519AAF">
 <thead>
  <tr>
   <th colname="col1" class="entry"> Funktion </th>
   <th colname="col2" class="entry"> Beskrivning </th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td colname="col1"> <p> Inledande version </p> </td>
   <td colname="col2"> <p> Första huvudversionen av felsökaren för Experience Platform. Avsedd att ersätta Experience Cloud Debugger. </p> </td>
  </tr>
 </tbody>
</table>
