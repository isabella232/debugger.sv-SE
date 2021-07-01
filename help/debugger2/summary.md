---
description: Sammanfattningsskärm för felsökning i Experience Platform
keywords: felsökning;Experience Platform Debugger extension;chrome;extension;summary;clear;requests;summary screen;solution;information;analytics;target;dtm;målgruppshanterare;starta;id service
seo-description: Sammanfattningsskärm för felsökning i Experience Platform
seo-title: Sammanfattningsskärm
title: Sammanfattningsskärm
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
exl-id: 91234125-15c4-4111-9ee4-f3af093a3c4d
source-git-commit: 8672a623442e5a0daa10597a4a93631131221fec
workflow-type: tm+mt
source-wordcount: '979'
ht-degree: 2%

---

# Sammanfattningsskärm{#summary-screen}

>[!IMPORTANT]
>
>Adobe Experience Platform Debugger är för närvarande i betaversion. Dokumentationen och funktionaliteten kan komma att ändras.

Om du vill köra Adobe Experience Platform Debugger klickar du på ikonen i webbläsarfältet och öppnar sedan sidan som du vill granska i webbläsaren.

![](assets/start-icon.jpg)

Skärmen Adobe Experience Platform Debugger Summary visas.

![](assets/summary.jpg)

På den här skärmen visas information om varje Adobe Experience Cloud-lösning. Den information som visas varierar beroende på lösning, men omfattar vanligtvis information som lösningsbiblioteket och version (till exempel&quot;AppMeasurement v2.9&quot;) och kontoidentifierare (till exempel Analytics-rapportens programpaket-ID, målklientkoden, Audience Manager partner-ID osv.)

## Information som visas i felsökningsprogrammet för Experience Platform

Felsökaren i Experience Platform visar följande information för varje lösning:

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Rapportsvit(er) </p> </td> 
   <td colname="col2"> <p>I <a href="https://experiencecloud.adobe.com/resources/help/en_US/reference/report_suites_admin.html" format="html" scope="external">-rapportsviten</a> definieras den fullständiga, oberoende rapporteringen på en vald webbplats, uppsättning webbplatser eller delmängd av webbsidor </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Versionen <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/appmeasure_mjs.html" format="html" scope="external"> AppMeasurement</a> som har definierats för sidan </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Besökarversion </p> </td> 
   <td colname="col2"> <p>Versionen för <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> besökar-ID</a>-biblioteket. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Sidnamn </p> </td> 
   <td colname="col2"> <p>Variabeln <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/pageName.html" format="html" scope="external"> pageName</a> har skickats till Analytics som innehåller ett användarvänligt namn för webbplatsen. </p> </td> 
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
   <td colname="col2"> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_dil_get_partner.html" format="html" scope="external">-partnernamnet</a> för DIL-instansen </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Versionsnumret<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_api_return_versions_dil.html" format="html" scope="external"></a> för instansen DIL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>Det unika användar-ID <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/ids-in-aam.html" format="html" scope="external"> som är associerat med DIL-instansen</a> </p> </td> 
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
   <td colname="col2"> <p>Version av turbin</a> </p> </td> 
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
   <td colname="col1"> <p>Tillägg </p> </td> 
   <td colname="col2"> <p>De tillägg som används på sidan </p> </td> 
  </tr> 
 </tbody> 
</table>

**Webb-SDK för Adobe Experience Platform**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Biblioteksversion </p> </td> 
   <td colname="col2"> <p>Antalet Adobe Experience Platform Web SDK <a href="https://docs.adobe.com/content/help/en/launch/using/extensions-ref/adobe-extension/aep-extension/overview.html" format="html" scope="external">biblioteksversion</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Namnutrymme</p> </td> 
   <td colname="col2"> <p>Namnet som identifieras i tillägget</p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Egenskaps-ID </p> </td> 
   <td colname="col2"> <p>Namnet på den Platform launch-egenskap som anges i tillägget </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Edge Domain </p> </td> 
   <td colname="col2"> <p>Domänen som Adobe Experience Platform-tillägget skickar och tar emot data från </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>IMS-organisations-ID </p> </td> 
   <td colname="col2"> <p>Organisationen som du vill att data skickas till på Adobe, enligt vad som anges i tillägget </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Loggning aktiverad </p> </td> 
   <td colname="col2"> <p>Anger om loggning har aktiverats för den här egenskapen</p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Cloud ID-tjänst**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience Cloud organisation-ID </p> </td> 
   <td colname="col2"> <p>Ditt <a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/" format="https" scope="external"> organisations-ID</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Versionen för besökar-ID<a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"></a>-biblioteket </p> </td> 
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
   <td colname="col1"> <p>Namn på global begäran </p> </td> 
   <td colname="col2"> <p>Den globala <a href="https://docs.adobe.com/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external">-rutan</a> refererar till det enda serveranropet som görs högst upp på varje webbsida i målinsimplementeringen </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Sidinläsningshändelse </p> </td> 
   <td colname="col2"> <p>Den typ av <a href="https://docs.adobe.com/content/help/en/launch/using/extensions-ref/adobe-extension/target-extension/overview.html" format="html" scope="external">händelse</a> som utlöses när sidan läses in </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Namn på begäran </p> </td> 
   <td colname="col2"> <p>Namnet på en begäran runt en <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> plats</a> på sidan. Endast tillgängligt utan autentisering om du implementerar felsökningshändelseavlyssnaren i koden eller tagghanteraren och aktiverar de nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
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
   <td colname="col1"> <p>Experience Name </p> </td> 
   <td colname="col2"> <p>Namnet på målupplevelsen <a href="https://docs.adobe.com/content/help/en/target/using/experiences/experiences.html" format="html" scope="external"></a>. Endast tillgängligt utan autentisering om du implementerar felsökningshändelseavlyssnaren i koden eller tagghanteraren och aktiverar de nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Experience ID </p> </td> 
   <td colname="col2"> <p>ID för Target-upplevelsen. Endast tillgängligt utan autentisering om du implementerar felsökningshändelseavlyssnaren i koden eller tagghanteraren och aktiverar de nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Namn på erbjudande</p> </td> 
   <td colname="col2"> <p>Namnet på målerbjudandet <a href="https://docs.adobe.com/content/help/en/target/using/experiences/offers/manage-content.html" format="html" scope="external"></a>. Endast tillgängligt utan autentisering om du implementerar felsökningshändelseavlyssnaren i koden eller tagghanteraren och aktiverar de nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Erbjudande-ID </p> </td> 
   <td colname="col2"> <p>ID:t för Target-erbjudandet. Endast tillgängligt utan autentisering om du implementerar felsökningshändelseavlyssnaren i koden eller tagghanteraren och aktiverar de nödvändiga <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> svarstoken</a> i målgränssnittet. </p> </td> 
  </tr> 
 </tbody> 
</table>
