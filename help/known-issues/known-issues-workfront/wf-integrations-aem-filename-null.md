---
title: "Integratie: bestandsnaam is null wanneer verzonden naar AEM via integratie"
description: "Wanneer een groot bestand (meer dan 100 MB) via de integratie met Workfront naar Adobe Experience Manager wordt verzonden, is de bestandsnaam in AEM null. "
hidefromtoc: true
feature: Workfront Integrations and Apps, Digital Content and Documents
source-git-commit: 06a9c8dbbf73b6ee39e529c21248a3fc372cb252
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
