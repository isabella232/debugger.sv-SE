---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;release notes
seo-description: 'null'
seo-title: Versionsinformation
title: Versionsinformation
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
translation-type: tm+mt
source-git-commit: 28e5681a3a2f58350348d4b9bc5b7e1bd979e749

---


# Versionsinformation{#release-notes}

## Versionsinformation {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Version 0.0.817 17 maj 2019 {#topic-5dc9026cac864330b04361b1da8309a8}

## Nya funktioner {#section-71352536e6894ad08f307535529394cd}

<table id="table_7EFCAF456B14404FAF3715FC56519AAF"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funktion </th> 
   <th colname="col2" class="entry"> Beskrivning </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Träff-data efter bearbetning </p> </td> 
   <td colname="col2"> <p> Lagt till möjligheten att <a href="solutions.md#section-f71dfcc22bb44c86bec328491606a482" format="dita" scope="local"> visa värden i analysträffar efter att bearbetningsreglerna har körts</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Version 0.0.810 6 mars 2019 {#topic-83bb7ddd68594177be9fd7826b650b80}

## Nya funktioner {#section-0a2f6fcb0045464fa11f0586c69f7ffd}

<table id="table_96AEBFF29F3D40CAA859133B22756B0C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funktion </th> 
   <th colname="col2" class="entry"> Beskrivning </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Granskningstester </p> </td> 
   <td colname="col2"> <p> Lagt till <a href="summary.md#section-82bc57440406461ebf27a16855b71655" format="dita" scope="local"> granskartester</a> i felsökaren </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe Audience Manager </p> </td> 
   <td colname="col2"> <p>Debugger visar nu AAM-svar </p> </td> 
  </tr> 
 </tbody> 
</table>

## Felkorrigeringar {#section-f5e9d54e9d2546afb97972cdb6d8a093}

* Ett problem där sidfoten dolde innehåll längst ned på sidan har korrigerats

* Felsökningssidfoten har uppdaterats
* Ett problem där inaktuell terminologi användes för Target har korrigerats

## Version 0.0.809 28 februari 2019 {#topic-6241de45fa9e4a23a95ad4d3a73f7348}

## Nya funktioner {#section-14036b9f2c0144fdac5e292ea42ce564}

<table id="table_66E255E9BA8845CAA92779F580D14EB4"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funktion </th> 
   <th colname="col2" class="entry"> Beskrivning </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Bädda in kodfunktioner </p> </td> 
   <td colname="col2"> <p> Dela upp Ersätt och infoga inbäddningsfunktioner för kod. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Förbättringar {#section-e9e8a6ddedde4c029b1d3d69c009cbad}

* Korrigerade en potentiell säkerhetslucka som orsakas av orensad användarinmatning.

## Felkorrigeringar {#section-556417ff055848c1bf037354dd43cbd0}

* Ett problem har korrigerats där AAM DIL-händelser inte hämtades på fliken AAM

* Ett problem i Dynamic Insert Launch där användargränssnittet verkade mappa till en annan inbäddningskod när det inte var det har åtgärdats
* Ett problem i Dynamic Insert Launch där en felaktig URL fortsatte att visas har åtgärdats
* Ett problem har korrigerats där felsökaren fortsatte att ersätta inbäddningskoder även när felsökningsfönstret stängdes

## Version 0.0.806 10 september 2018 {#topic-a41c9d1969ff4d06ac3bb4e7d6b6d18a}

## Nya funktioner {#section-4eb2a6ed26a44abc96623384a7e94b0f}

<table id="table_9AC6DE90AF4345DFA707BFBA1E58C328"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funktion </th> 
   <th colname="col2" class="entry"> Beskrivning </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Analyslänk på fliken Verktyg </p> </td> 
   <td colname="col2"> <p>Visa egna namn för e-var/props via Analytics API via IMS-inloggning. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Infoga start dynamiskt </p> </td> 
   <td colname="col2"> <p>På fliken Verktyg kan du dynamiskt infoga Launch på alla sidor för att testa något på en sida som inte har Launch installerat. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Målförbättringar </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_5FCD61733462495D8FB421DE7C813001"> 
      <li id="li_2E8E9AAE5D0D41DC8C42592AFDFA3377">Prestandatimingar har lagts till för Target-begäranden. </li> 
      <li id="li_98A56E71D72542D694A76DF84CE26AFA">Hämta adobe.target.trackEvent </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Förbättringar {#section-56003a12c32f4998bf1cf2a25a518592}

* Förbättrad visning av fliken Nätverk så att tabellens höjd inte blir för stor och tvingar användaren att rulla lodrätt innan de kan rulla vågrätt. Tidigare visades rullningslisterna längst ned i tabellen. Eftersom tabellen kunde bli ganska stor var man tvungen att rulla alla nedåt vertikalt för att kunna se dem.
* Länken till ObservePoint har uppdaterats från fliken Verktyg.

## Felkorrigeringar {#section-d9231f5c77254d0888347e5f569a8b1d}

* Ett problem där Experience Cloud-fliken inte uppdaterades har korrigerats

* Korrigerade ett problem där&quot;Media Optimizer&quot; visades på raden Lösning på fliken Nätverk i stället för det aktuella&quot;Advertising Cloud&quot;-namnet
* Ett problem som orsakade att felsökaren injicerade _satellit på varje sida har korrigerats

## Version 0.0.803 10 augusti 2018 {#topic-d2901fb70ce04a5586f6c7a994fce875}

Version 0.0.803 innehåller inga kundtillvända ändringar.

## Version 0.0.802 1 augusti 2018 {#topic-b93cd396af5e49dc97cd86264871aeb4}

## Nya funktioner {#section-e6699fb9c9b24035ace56d6a84c9d09b}

<table id="table_E847A9D6711F4CF59E98806FA7AF8379"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funktion </th> 
   <th colname="col2" class="entry"> Beskrivning </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Granskarlänk på fliken Verktyg </p> </td> 
   <td colname="col2"> <p>Lade till en länk till granskaren från felsökaren </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Komprimerade flikar </p> </td> 
   <td colname="col2"> <p>De komprimerade flikarna finns kvar på flikarna Sammanfattning och Verktyg </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Klicka för att visa </p> </td> 
   <td colname="col2"> <p> Lagt till funktioner för att klicka-för-visa på alla flikar </p> </td> 
  </tr> 
 </tbody> 
</table>

## Förbättringar {#section-0e7090e3e6a645f085d4553b983ecff8}

* Namnet på Media Optimizer har ändrats till Advertising Cloud
* Borttagna lösningar från fliken Nätverk om de inte hittas

## Felkorrigeringar {#section-7c0e4cc4b00a428489bed4a0a27c9501}

* Ett problem har korrigerats där funktionen &quot;Klicka i cell för att visa&quot; inte uppdaterades
* Ett problem där AAM-träffar inte visades på AAM-fliken har korrigerats

## Version 0.0.798 14 juni 2018 {#topic-3b2d44277f2f4c0295d82724c34bf467}

## Nya funktioner {#section-0d73ae8b7ced417e9039f986fafaa102}

<table id="table_8FDED5A7B7F7430A88AE441336F9C714"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funktion </th> 
   <th colname="col2" class="entry"> Beskrivning </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Exportalternativ för Excel </p> </td> 
   <td colname="col2"> <p>Exportalternativet Excel har lagts till på fliken Nätverk. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Förbättrat utseende </p> </td> 
   <td colname="col2"> <p>Teckensnittet Chrome-tillägg har uppdaterats till Adobe Clean. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Svep-funktion för styrplatta </p> </td> 
   <td colname="col2"> <p>Inaktiverad svepfunktion för framåt-/bakåtstyrplatta. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Anropsindikator för råserver </p> </td> 
   <td colname="col2"> <p>En indikator som anger att anropssträngen för raw-servern har kopierats har lagts till. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Rensa fliken Loggar </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_D1EB0BE3A01C494983DAAF625562AC62"> 
      <li id="li_2696D26320F54A089D3CC99962EC9670">Dölj lösningar i lösningsfiltret om det inte finns några radobjekt för lösningen i loggarna </li> 
      <li id="li_D4586A6AB2AD42BB9F0FA3E7A01382C6">Dölj nivåfiltret om inga DTM-anrop hittas, eftersom det bara gäller för DTM </li> 
      <li id="li_E2AF179037DC4C63B960013AB1F9AD6A">Ändra ikonerna som visas i kolumnen Nivå så att de inte ser klickbara ut när inget händer när du klickar </li> 
      <li id="li_3DB6682D6C9040D99F04C688E208CE1F">Standardisera formateringen av "Visa kod" på DTM-radobjekt </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Uppdatera hjälplänk i sidfot </p> </td> 
   <td colname="col2"> <p>Uppdatera hjälplänken i sidfoten till <a href="https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/" format="https" scope="external"> https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Felkorrigeringar {#section-c292cf7dcb17463bb1928de73bd55121}

* Ett problem har korrigerats där märkesnumret inte rensades
* Ett problem där en kund rapporterade tomma sammanfattningsdetaljer har korrigerats

## Version 0.0.797 25 maj 2018 {#topic-51490f4f42aa40eb879663fad9d62916}

## Nya funktioner {#section-bbf8ff7e000e4b5592d348e0870471f6}

<table id="table_8CF872DC245A46C38FE21490C842D47A"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funktion </th> 
   <th colname="col2" class="entry"> Beskrivning </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Mbox-växlar </p> </td> 
   <td colname="col2"> <p>Mbox-växlar har lagts till på fliken Target </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Filterinställningarna är nu fästa </p> </td> 
   <td colname="col2"> <p>Filterinställningarna ligger nu högst upp på skärmen i nätverket och loggar flikar. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Visa och kopiera nätverksvärden </p> </td> 
   <td colname="col2"> <p>Du kan visa detaljer och kopiera värdet för en cell på nätverksfliken. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Länkar till copyrightsidfötter </p> </td> 
   <td colname="col2"> <p>En giltig sidfotslänkar och copyrightinformation har lagts till i användargränssnittet. </p> </td> 
  </tr> 
 </tbody> 
</table>

