---
description: Experience Platform Debugger Network screen
keywords: felsökning;Experience Platform Debugger extension;chrome;extension;network;information
seo-description: Experience Platform Debugger Network screen
seo-title: Nätverksinformation
title: Nätverksinformation
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
exl-id: ed0579ef-ec26-43df-9453-a395c105038a
source-git-commit: 8672a623442e5a0daa10597a4a93631131221fec
workflow-type: tm+mt
source-wordcount: '236'
ht-degree: 2%

---

# Nätverk{#network}

>[!IMPORTANT]
>
>Adobe Experience Platform Debugger är för närvarande i betaversion. Dokumentationen och funktionaliteten kan komma att ändras.

Om du vill visa nätverksinformation klickar du på **[!UICONTROL Network]**.

På nätverksskärmen samlas alla Adobe Experience Cloud-lösningsanrop som görs på sidan och visas i ordning från vänster till höger. Standardparametrar etiketteras automatiskt med egna namn och ordnas för att gruppera gemensamma parametrar i samma roll.

![](assets/network.jpg)

Den här skärmen är användbar när du vill jämföra nyckelvärdepar i olika träffar. Du kan bekräfta att de parametrar som används för integreringar, till exempel Experience Cloud Visitor-ID eller Kompletterande data-ID, är konsekventa för alla integreringar.

>[!NOTE]
>
>I nuläget visas inte alla parametrar som skickas i lösningsanrop (till exempel kontextvariabler för Analytics, anpassade målparametrar eller kundID:n för Experience Cloud ID-tjänsten) på nätverksskärmen.

Om du vill ändra information per lösning väljer du den lösning du vill visa i listan i det vänstra navigeringsfältet. Följande exempel filtreras så att endast Analytics visas:

![](assets/network-analytics.jpg)

Om du vill återgå till att visa alla lösningar klickar du på **[!UICONTROL Network]**

Klicka på ett objekt i nätverksvyn för att visa en utökad vy. I det utökade visningsfönstret kan du kopiera den information som visas till Urklipp.

![](assets/network-expand.jpg)

<!--Use the icon at the top of each column to copy the server call URL to your clipboard, where you can paste it into another document for reference or debugging purposes.

![](assets/copy.jpg)-->

Om du vill rensa listan klickar du på **[!UICONTROL Remove Events]**.

Om du vill hämta en Excel-fil som innehåller informationen på den här skärmen klickar du på **[!UICONTROL Download]**.
