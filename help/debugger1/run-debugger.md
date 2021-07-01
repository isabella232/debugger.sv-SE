---
description: Löpande Experience Cloud Debugger
keywords: felsökare;upplev molnfelsökningstillägg;chrome;extension;summary;clear;requests;summary screen;solution;information;analytics;target;dtm;målgruppshanterare;starta;id service
seo-description: Löpande Experience Cloud Debugger
seo-title: Sammanfattningsskärm
title: Sammanfattningsskärm
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
exl-id: 0ee0314b-1611-4581-ae54-2c784e0e56ff
source-git-commit: 8672a623442e5a0daa10597a4a93631131221fec
workflow-type: tm+mt
source-wordcount: '1069'
ht-degree: 2%

---

# Sammanfattningsskärm{#summary-screen}

Om du vill köra Adobe Experience Cloud Debugger klickar du på tilläggsikonen i tilläggsfältet och öppnar sedan sidan som du vill granska i Chrome.

![](assets/start-icon.jpg)

Skärmen Sammanfattning för Experience Cloud Debugger visas.

![](assets/summary.jpg)

På den här skärmen visas en miniatyrbild av sidan samt sidans URL och rubrik. Här finns också information om de olika Adobe Experience Cloud-lösningarna. Den information som visas varierar beroende på lösning, men omfattar vanligtvis information som lösningsbiblioteket och version (till exempel&quot;AppMeasurement v2.9&quot;) och kontoidentifierare (till exempel Analytics-rapportens programpaket-ID, målklientkoden, Audience Manager partner-ID osv.)

Siffrorna i blått bredvid flikarna högst upp i fönstret visar antalet serveranrop som har gjorts. Du kan återställa dessa till noll genom att klicka på **[!UICONTROL Clear All Requests]** på respektive flik.

I följande bild visas information om Adobe Target. Observera att om du vill visa aktivitetsinformationen som visas nedan utan autentisering måste du implementera felsökningshändelseavlyssnaren i koden eller tagghanteraren och aktivera de nödvändiga [svarstoken](https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html) i målgränssnittet.

![](assets/summary-target2.jpg)

## Kör en granskning i Adobe Experience Platform Auditor {#section-82bc57440406461ebf27a16855b71655}

Du kan använda verktyget Spela upp granskare för att köra en serie granskningar på sidan. Om du vill köra plattformsgranskaren klickar du på **[!UICONTROL Auditor]** på den översta menyn och sedan på **[!UICONTROL Audit Page Now]**. Klicka på **[!UICONTROL Run Multi-Page Audit Now]** om du vill öppna plattformsgranskaren.

## Information som visas i Experience Cloud Debugger {#section-88a95ba53dca43d9b96a585e75e5f5cf}

Experience Cloud Debugger visar följande information för varje lösning:

**Sidinformation**

<table id="table_FF3B9083524244D29AF350978A0AC236"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Sidskärmbild </p> </td> 
   <td colname="col2"> <p>Miniatyrbild av sidan </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>URL </p> </td> 
   <td colname="col2"> <p>URL för sidan </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Titel </p> </td> 
   <td colname="col2"> <p>Namnet som anges i <span class="codeph"> &lt;TITLE&gt;</span>-taggen </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Rapportsvit(er) </p> </td> 
   <td colname="col2"> <p>I <a href="https://docs.adobe.com/content/help/en/analytics/admin/manage-report-suites/report-suites-admin.html" format="html" scope="external">-rapportsviten</a> definieras den fullständiga, oberoende rapporteringen på en vald webbplats, uppsättning webbplatser eller delmängd av webbsidor </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Versionen <a href="https://docs.adobe.com/content/help/en/analytics/implementation/js/overview.html" format="html" scope="external"> AppMeasurement</a> som har definierats för sidan </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Besökarversion </p> </td> 
   <td colname="col2"> <p>Versionen för <a href="https://docs.adobe.com/content/help/en/analytics/technotes/visitor-identification.html" format="html" scope="external"> besökar-ID</a>-biblioteket. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Sidnamn </p> </td> 
   <td colname="col2"> <p>Variabeln <a href="https://docs.adobe.com/content/help/en/analytics/implementation/vars/page-vars/page-variables.html" format="html" scope="external"> pageName</a> har skickats till Analytics som innehåller ett användarvänligt namn för webbplatsen. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Moduler </p> </td> 
   <td colname="col2"> <p>Modulerna som läses in av Adobe Analytics </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Partner </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobe.com/content/help/en/audience-manager/user-guide/dil-api/dil-instance-methods.html#getpartner" format="html" scope="external">-partnernamnet</a> för DIL-instansen </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Versionsnumret<a href="https://docs.adobe.com/content/help/en/audience-manager/user-guide/api-and-sdk-code/rest-apis/aam-api-dil-methods.html#return-version-dil" format="html" scope="external"></a> för instansen DIL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>Det unika användar-ID <a href="https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/ids-in-aam.html" format="html" scope="external"> som är associerat med DIL-instansen</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Platform Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Namn </p> </td> 
   <td colname="col2"> <p>Namnet på Platforma launchen <a href="https://docs.adobe.com/content/help/en/launch/using/reference/admin/companies-and-properties.html" format="https" scope="external"> egenskap</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Versionen av <a href="https://developer.adobelaunch.com/extensions/reference/turbine-free-variable/" format="https" scope="external"> turbin</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Skapad den </p> </td> 
   <td colname="col2"> <p>Platforma launchen <a href="https://docs.adobe.com/content/help/en/launch/using/reference/publish/libraries.html" format="https" scope="external"> bibliotek</a> byggdatum </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Miljö </p> </td> 
   <td colname="col2"> <p>Miljön <a href="https://docs.adobe.com/content/help/en/launch/using/reference/publish/environments.html" format="https" scope="external"></a> som används av Platforma launchen bibliotek </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Skriptkatalog </p> </td> 
   <td colname="col2"> <p>Katalogen där Platforma launchen lagras </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Biblioteksnamn </p> </td> 
   <td colname="col2"> <p>Namnet på Adobe DTM<a href="https://docs.adobe.com/content/help/en/dtm/using/library-management.html" format="html" scope="external">-biblioteket</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Turbinversionen </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Skapad den </p> </td> 
   <td colname="col2"> <p>Platforma launchen <a href="https://docs.adobe.com/content/help/en/dtm/using/library-management.html" format="html" scope="external"> bibliotek</a> byggdatum </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Miljö </p> </td> 
   <td colname="col2"> <p>Den miljö som används av DTM-biblioteket </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Skriptkatalog </p> </td> 
   <td colname="col2"> <p>Katalogen där DTM-skriptet lagras </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Cloud ID-tjänst**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience Cloud organisation-ID </p> </td> 
   <td colname="col2"> <p>Ditt <a href="https://docs.adobe.com/content/help/en/id-service/using/home.html" format="https" scope="external"> organisations-ID</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Versionen för besökar-ID<a href="https://docs.adobe.com/content/help/en/analytics/technotes/visitor-identification.html" format="html" scope="external"></a>-biblioteket </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Klientkod </p> </td> 
   <td colname="col2"> <p>Ditt mål <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"> klientkod </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Aktuell version av <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> at.js</a> eller mbox.js </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Namn på global mbox </p> </td> 
   <td colname="col2"> <p>Den globala <a href="https://docs.adobe.com/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external">-rutan</a> refererar till det enda serveranropet som görs högst upp på varje webbsida i målinsimplementeringen </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Namn på mbox </p> </td> 
   <td colname="col2"> <p>Namnet på en mbox runt en <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> plats</a> på sidan. Endast tillgängligt utan autentisering om du implementerar felsökningshändelseavlyssnaren i koden eller tagghanteraren och aktiverar de nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aktivitetsnamn </p> </td> 
   <td colname="col2"> <p>Namnet på målkampanjen <a href="https://docs.adobe.com/content/help/en/target/using/activities/activities.html" format="html" scope="external"> eller aktiviteten</a>. Endast tillgängligt utan autentisering om du implementerar felsökningshändelseavlyssnaren i koden eller tagghanteraren och aktiverar de nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aktivitets-ID </p> </td> 
   <td colname="col2"> <p>ID för målaktiviteten. Endast tillgängligt utan autentisering om du implementerar felsökningshändelseavlyssnaren i koden eller tagghanteraren och aktiverar de nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Mottagarnamn </p> </td> 
   <td colname="col2"> <p>Namnet på målupplevelsen <a href="https://docs.adobe.com/content/help/en/target/using/experiences/experiences.html" format="html" scope="external"></a>. Endast tillgängligt utan autentisering om du implementerar felsökningshändelseavlyssnaren i koden eller tagghanteraren och aktiverar de nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Mottagar-ID </p> </td> 
   <td colname="col2"> <p>ID för målreceptet. Endast tillgängligt utan autentisering om du implementerar felsökningshändelseavlyssnaren i koden eller tagghanteraren och aktiverar de nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Erbjudande </p> </td> 
   <td colname="col2"> <p>Namnet på målerbjudandet <a href="https://docs.adobe.com/content/help/en/target/using/experiences/offers/manage-content.html" format="html" scope="external"></a>. Endast tillgängligt utan autentisering om du implementerar felsökningshändelseavlyssnaren i koden eller tagghanteraren och aktiverar de nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Erbjudande-ID </p> </td> 
   <td colname="col2"> <p>ID:t för Target-erbjudandet. Endast tillgängligt utan autentisering om du implementerar felsökningshändelseavlyssnaren i koden eller tagghanteraren och aktiverar de nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
 </tbody> 
</table>
