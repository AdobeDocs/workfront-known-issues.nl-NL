---
title: 'Workfront: ZScaler-instellingen kunnen leiden tot verminderde prestaties'
description: De webservice van ZScaler maakt standaard gebruik van http/1.1, wat kan leiden tot verminderde prestaties in Workfront.
hidefromtoc: true
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 8bb5041a13374ce5dde6a1db173487f50d049f17
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 0%

---

# Workfront: ZScaler-instellingen kunnen leiden tot verminderde prestaties

>[!NOTE]
>
>Dit is een probleem met ZScaler en wordt niet door Workfront opgelost.

De webservice van ZScaler maakt standaard gebruik van `http/1.1` , wat kan leiden tot verminderde prestaties in Workfront.

**Oplossing**

Configureer uw ZScaler-software voor gebruik van `http/2` . Dit kan niet worden geconfigureerd in Workfront.

U vindt informatie over `http/2` in de ZScaler-documentatie.

_Eerste rapporteerde op 18 November, 2024._
