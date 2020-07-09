---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;tools;dtm;target
seo-description: 'null'
seo-title: verktyg
title: verktyg
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
translation-type: tm+mt
source-git-commit: 5a84797bda8c29f1e691de418c9837c76a63c17f
workflow-type: tm+mt
source-wordcount: '396'
ht-degree: 1%

---


# verktyg{#tools}

>[!IMPORTANT]
>
>Adobe Experience Cloud Debugger 2.0 är en betaversion. Dokumentationen och funktionaliteten kan komma att ändras.

På skärmen Verktyg kan du aktivera eller inaktivera olika verktyg för den installerade lösningen. Du kan till exempel aktivera felsökningsprogramsatser för Target konsol eller använda DTM Staging Library. Dessa verktyg är bara tillgängliga om Target och DTM är installerade på sidan.

![](assets/tools.jpg)

Du kan infoga Launch eller DTM dynamiskt på alla sidor för att testa något på en sida som inte har Launch eller DTM installerat. Klicka på **[!UICONTROL Embed Code]** ikonen, skriv [inbäddningskoden](https://experiencecloud.adobe.com/resources/help/en_US/dtm/deployment.html) och klicka på **[!UICONTROL Save]**.

![](assets/tools-embedcode.jpg)

## DTM-information {#section-c3d43040440449e5a050170843a600b7}

<table id="table_04625C3319134E169A35DB74C1D1FB31"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Verktyg </th> 
   <th colname="col2" class="entry"> Beskrivning </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> DTM Console-loggning </p> </td> 
   <td colname="col2"> <p>Det här verktyget visar DTM-specifika felsökningsprogramsatser för webbläsarkonsolen. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Använd mellanlagringsbibliotek </p> </td> 
   <td colname="col2"> <p>Det här verktyget använder mellanlagringsbiblioteket för DTM-felsökningsinformation. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Inaktivera DTM </p> </td> 
   <td colname="col2"> <p>Det här verktyget förhindrar att DTM-information kontrolleras. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Infoga DTM dynamiskt </p> </td> 
   <td colname="col2"> <p> Det här verktyget infogar DTM-kod på sidan. Använd redigeraren Bädda in kod för att redigera koden som infogas. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Target Information {#section-31090d95f50e455692b672c26e6a2051}

<table id="table_A71D269B49F4417599EBACA44D5CCF4F"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Verktyg </th> 
   <th colname="col2" class="entry"> Beskrivning </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Loggning av Target Console </p> </td> 
   <td colname="col2"> <p>Det här verktyget visar Target-specifika felsökningsprogramsatser för webbläsarkonsolen, som alla börjar med <span class="codeph"> AT:</span> genom att lägga till en cookie med namnet <span class="codeph"> mboxDebug=true</span> i webbläsaren. För närvarande visas inte konsolprogramsatserna på skärmen Felsökningsloggar, men de visas i webbläsarens interna felsökningskonsol. </p> <p> Det här verktyget kräver at.js 0.9.6+. Om du använder en äldre version av at.js kan du lägga till <span class="codeph"> ?mboxDebug=true</span> frågesträngsparametern i URL:en för att aktivera konsolloggning. Om du använder mbox.js kan du lägga till parametern <span class="codeph"> ?_AT_Debug=console</span> för att aktivera konsolloggning som begränsas till Visual Experience Composer-aktiviteter. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Aktivera Mbox Traces </p> </td> 
   <td colname="col2"> <p>Det här verktyget lägger till detaljerad information i Target-svar, som kan utforskas på skärmen för spårning <span class="uicontrol"> i</span> Target&gt;Mbox i felsökningsprogrammet. </p> <p> Du måste vara inloggad på Experience Cloud på någon av dina Chrome-flikar för att kunna aktivera det här verktyget. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Inaktivera Target </p> </td> 
   <td colname="col2"> <p>Det här verktyget inaktiverar alla Target-begäranden genom att lägga till en cookie med namnet <span class="codeph"> mboxDisable=true</span> i webbläsaren. </p> <p> Det här verktyget kräver at.js 0.9.6+. Om du använder en äldre version kan du lägga till <span class="codeph"> ?mboxDisable=true </span>frågesträngsparametern i URL:en för att inaktivera kryssrutor. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Markera ruta </p> </td> 
   <td colname="col2"> <p> Med det här verktyget ritar du en röd ruta runt gamla, figursatta rutor. </p> </td> 
  </tr> 
 </tbody> 
</table>

I följande video förklaras hur du använder Felsökning-tillägget med Adobe Target.

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/)
