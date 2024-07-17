---
title: 'Integratie: bestandsnaam is null wanneer verzonden naar AEM via integratie'
description: 'Wanneer een groot bestand (meer dan 100 MB) via de integratie met Workfront naar Adobe Experience Manager wordt verzonden, is de bestandsnaam in AEM null. '
hidefromtoc: true
feature: Workfront Integrations and Apps, Digital Content and Documents
exl-id: c2d15424-ae04-414f-9384-a7b083212313
source-git-commit: e24d266002a913e5c6e2d5e40e9dad36deff541a
workflow-type: tm+mt
source-wordcount: '110'
ht-degree: 0%

---

# Integratie: bestandsnaam is &quot;null&quot; wanneer deze wordt verzonden naar documentintegratie

>[!NOTE]
>
>Deze kwestie is op 8 mei 2024 opgelost.

Wanneer een groot bestand (meer dan 100 MB) via Workfront-integratie naar een documentprovider wordt verzonden, is de bestandsnaam in de documentprovider &#39;null&#39;.

Dit is gemeld bij zowel ZIP- als TIF-bestanden.

**Oplossing**

Voer een van de volgende handelingen uit:

* Wijs de documentnaam toe aan de titel in de documentprovider.
* Voer de bestandsnaam rechtstreeks in de documentprovider in.

_Eerste rapporteerde op 23 April, 2024._

