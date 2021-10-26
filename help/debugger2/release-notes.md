---
description: Versionsinformation om felsökning för Experience Platform
keywords: felsökning;Experience Platform Debugger extension;chrome;extension;release notes
seo-description: Experience Platform Debugger release notes
seo-title: Release Notes
title: Versionsinformation
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: 026ce852ded530e89f36bb01274d7481e07731c0
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 7%

---

# Versionsinformation{#release-notes}

## Versionsinformation {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Version 1.2.0 October 26, 2021

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
   <td colname="col1"> <p> Händelser från alla webbläsarflikar som visas i nätverksvyn </p> </td>
   <td colname="col2"> <p> Show events from all browser tabs in the network view. Om du bara vill visa händelser från den aktuella fliken klickar du på låsikonen i det nedre högra hörnet av felsökaren.</p> </td>
  </tr>
  <tr>
   <td colname="col1"> <p> Varumärkesändringar </p> </td>
   <td colname="col2"> <p> AEP Web SDK blir Adobe Experience Platform Web SDK och Launch blir Adobe Experience Platform-taggar.</p> </td>
  </tr>
 </tbody>
</table>

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
   <td colname="col1"> <p> Remote debugging visualization </p> </td>
   <td colname="col2"> <p> Organize the remote debugging events into a visual flow chart in the Adobe Experience Platform Web SDK &gt; Edge Transactions section. Kräv dessutom att den IMS-organisation för Adobe Experience Platform Web SDK som används på sidan matchar den inloggade organisationen när du startar en ny fjärrfelsökningssession. Filter edge transactions by the connected tab.</p> <p> <b>Obs!</b> Målspårningsloggar är fortfarande tillgängliga i avsnittet Loggar &gt; Edge.</p> </td>
  </tr>
  <tr>
   <td colname="col1"> <p> Förbättringar i konfigurationsavsnittet för Adobe Experience Platform Web SDK </p> </td>
   <td colname="col2"> <p> Tillåt att separata ID-konfigurationer för dataström åsidosätts för varje instans på sidan. Växla till Lägg till felsökning aktiverat.</p> </td>
  </tr>
 </tbody>
</table>

## Felkorrigeringar

* Fixed an issue where the Adobe Target trace token was not always sent with remote debugging sessions for the Adobe Experience Platform Web SDK.

## Version 1.0.0 May 5, 2021

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
