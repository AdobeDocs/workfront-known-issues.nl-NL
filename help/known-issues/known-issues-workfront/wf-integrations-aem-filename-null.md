---
title: 'Integratie: bestandsnaam is null wanneer verzonden naar AEM via integratie'
description: 'Wanneer een groot bestand (meer dan 100 MB) via de integratie met Workfront naar Adobe Experience Manager wordt verzonden, is de bestandsnaam in AEM null. '
hidefromtoc: true
feature: Workfront Integrations and Apps, Digital Content and Documents
exl-id: c2d15424-ae04-414f-9384-a7b083212313
source-git-commit: 2110bda5b8f0bec53c0503ce6b3f8da6fce693ca
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 0%

---

# Integratie: bestandsnaam is null wanneer deze via integratie naar AEM wordt verzonden

Wanneer een groot bestand (meer dan 100 MB) via de integratie met Workfront naar Adobe Experience Manager wordt verzonden, is de bestandsnaam in AEM &quot;null&quot;.

Dit is gemeld bij zowel ZIP- als TIF-bestanden.

**Workaround**

Voer een van de volgende handelingen uit:

* Wijs de documentnaam toe aan de AEM.
* Voer de bestandsnaam rechtstreeks in AEM in.

_Voor het eerst gerapporteerd op 23 april 2024._

