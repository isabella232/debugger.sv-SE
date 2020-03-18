---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;summary;clear;requests;summary screen;solution;information;analytics;target;dtm;audience manager;launch;id service
seo-description: 'null'
seo-title: Sammanfattningsskärm
title: Sammanfattningsskärm
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: tm+mt
source-git-commit: 2c3d056451c5b7b4bf5603c22bf3bbdbc693491f

---


# Sammanfattningsskärm{#summary-screen}

Om du vill köra Experience Cloud Debugger klickar du på tilläggsikonen i tilläggsfältet och öppnar sedan sidan som du vill granska i Chrome.

![](assets/start-icon.jpg)

Skärmen Adobe Experience Cloud Debugger Summary visas.

![](assets/summary.jpg)

På den här skärmen visas information om varje Adobe Experience Cloud-lösning. Den information som visas varierar beroende på lösning, men omfattar vanligtvis information som lösningsbiblioteket och version (till exempel&quot;AppMeasurement v2.9&quot;) och kontoidentifierare (till exempel ID för Analytics-rapportsviten, målklientkoden, partner-ID för Audience Manager osv.)


## Kör en revision i revisor {#section-82bc57440406461ebf27a16855b71655}

Du kan använda Adobe Auditor för att utföra en serie granskningar på din sida. Om du vill köra Granskare klickar du på **[!UICONTROL Auditor]** den översta menyn och sedan på **[!UICONTROL Audit Page Now]**. Klicka **[!UICONTROL Run Multi-Page Audit Now]** för att öppna Adobe Auvisor.

## Information som visas i Felsökning {#section-88a95ba53dca43d9b96a585e75e5f5cf}

Felsökaren visar följande information för varje lösning:

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Rapportsvit(er) </p> </td> 
   <td colname="col2"> <p>En <a href="https://experiencecloud.adobe.com/resources/help/en_US/reference/report_suites_admin.html" format="html" scope="external"> rapportserie</a> definierar den fullständiga, oberoende rapporteringen på en vald webbplats, en uppsättning webbplatser eller en delmängd av webbsidor </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Den <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/appmeasure_mjs.html" format="html" scope="external"> AppMeasurement</a> -version som är definierad för sidan </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Besökarversion </p> </td> 
   <td colname="col2"> <p>Versionen av <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> besökar-ID</a> -biblioteket. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Sidnamn </p> </td> 
   <td colname="col2"> <p>Variabeln <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/pageName.html" format="html" scope="external"> pageName</a> som skickas till Analytics och som innehåller ett användarvänligt namn för webbplatsen. </p> </td> 
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
   <td colname="col2"> <p>DIL-instansens <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_dil_get_partner.html" format="html" scope="external"> partnernamn</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Versionsnumret<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_api_return_versions_dil.html" format="html" scope="external"> för</a> DIL-instansen </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>Det <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/ids-in-aam.html" format="html" scope="external"> unika användar-ID</a> som är associerat med DIL-instansen </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Namn </p> </td> 
   <td colname="col2"> <p>Namnet på Adobe Launch- <a href="https://docs.adobelaunch.com/administration/companies-and-properties" format="https" scope="external"> egenskapen</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Version av <a href="https://developer.adobelaunch.com/guides/extensions/turbine-free-variable/" format="https" scope="external"> turbin</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Skapad den </p> </td> 
   <td colname="col2"> <p>Startdatum <a href="https://docs.adobelaunch.com/publishing/libraries" format="https" scope="external"> för</a> biblioteket </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Miljö </p> </td> 
   <td colname="col2"> <p>Den <a href="https://docs.adobelaunch.com/administration/environments" format="https" scope="external"> miljö</a> som används av Launch-biblioteket </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Skriptkatalog </p> </td> 
   <td colname="col2"> <p>Katalogen där Launch-skriptet lagras </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Biblioteksnamn </p> </td> 
   <td colname="col2"> <p>Namnet på Adobe DTM<a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> -biblioteket</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Turbinversionen </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Skapad den </p> </td> 
   <td colname="col2"> <p>Startdatum <a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> för</a> biblioteket </p> </td> 
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

**Adobe Experience Cloud ID Service**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience Cloud-organisations-ID </p> </td> 
   <td colname="col2"> <p>Ditt <a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/" format="https" scope="external"> organisations-ID</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Versionen för<a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> besökar-ID</a> -biblioteket </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Klientkod </p> </td> 
   <td colname="col2"> <p>Din <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"> målklientkod </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Aktuell version av <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> at.js</a> eller mbox.js </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Namn på global mbox </p> </td> 
   <td colname="col2"> <p>Den<a href="https://docs.adobe.com/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> globala mbox</a> refererar till det enda serveranrop som görs högst upp på varje webbsida i Target-implementeringen </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Namn på mbox </p> </td> 
   <td colname="col2"> <p>Namnet på en mbox runt en <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> plats</a> på sidan. Endast tillgängligt utan autentisering om du implementerar händelseavlyssnaren för felsökning i koden eller tagghanteraren och aktiverar nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aktivitetsnamn </p> </td> 
   <td colname="col2"> <p>Namnet på Target- <a href="https://docs.adobe.com/content/help/en/target/using/activities/activities.html" format="html" scope="external"> kampanjen eller -aktiviteten</a>. Endast tillgängligt utan autentisering om du implementerar händelseavlyssnaren för felsökning i koden eller tagghanteraren och aktiverar nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aktivitets-ID </p> </td> 
   <td colname="col2"> <p>ID för målaktiviteten. Endast tillgängligt utan autentisering om du implementerar händelseavlyssnaren för felsökning i koden eller tagghanteraren och aktiverar nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Mottagarnamn </p> </td> 
   <td colname="col2"> <p>Namnet på Target- <a href="https://docs.adobe.com/content/help/en/target/using/experiences/experiences.html" format="html" scope="external"> upplevelsen</a>. Endast tillgängligt utan autentisering om du implementerar händelseavlyssnaren för felsökning i koden eller tagghanteraren och aktiverar nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Mottagar-ID </p> </td> 
   <td colname="col2"> <p>ID för målreceptet. Endast tillgängligt utan autentisering om du implementerar händelseavlyssnaren för felsökning i koden eller tagghanteraren och aktiverar nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Erbjudande </p> </td> 
   <td colname="col2"> <p>Namnet på Target- <a href="https://docs.adobe.com/content/help/en/target/using/experiences/offers/manage-content.html" format="html" scope="external"> erbjudandet</a>. Endast tillgängligt utan autentisering om du implementerar händelseavlyssnaren för felsökning i koden eller tagghanteraren och aktiverar nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Erbjudande-ID </p> </td> 
   <td colname="col2"> <p>ID:t för Target-erbjudandet. Endast tillgängligt utan autentisering om du implementerar händelseavlyssnaren för felsökning i koden eller tagghanteraren och aktiverar nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
 </tbody> 
</table>

