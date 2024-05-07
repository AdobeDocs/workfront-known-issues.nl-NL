---
title: 'Integratie: bestandsnaam is null wanneer verzonden naar AEM via integratie'
description: 'Wanneer een groot bestand (meer dan 100 MB) via de integratie met Workfront naar Adobe Experience Manager wordt verzonden, is de bestandsnaam in AEM null. '
hidefromtoc: true
feature: Workfront Integrations and Apps, Digital Content and Documents
exl-id: c2d15424-ae04-414f-9384-a7b083212313
source-git-commit: 3ca57c76dc50a348cf6d85d4d3e7366834a5e791
workflow-type: tm+mt
source-wordcount: '104'
ht-degree: 0%

---

# Integratie: bestandsnaam is &quot;null&quot; wanneer deze wordt verzonden naar documentintegratie

Wanneer een groot bestand (meer dan 100 MB) via Workfront-integratie naar een documentprovider wordt verzonden, is de bestandsnaam in de documentprovider &#39;null&#39;.

Dit is gemeld bij zowel ZIP- als TIF-bestanden.

**Workaround**

Voer een van de volgende handelingen uit:

* Wijs de documentnaam toe aan de titel in de documentprovider.
* Voer de bestandsnaam rechtstreeks in de documentprovider in.

_Voor het eerst gerapporteerd op 23 april 2024._

