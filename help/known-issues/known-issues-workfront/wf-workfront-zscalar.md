---
title: "Workfront: ZScalar-instellingen kunnen leiden tot verminderde prestaties"
description: "De webservice van ZScalar maakt standaard gebruik van http/1.1, wat kan leiden tot verminderde prestaties in Workfront."
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 77345937934851b8ebfdf257f44e25133eade971
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 0%

---


# Workfront: ZScalar-instellingen kunnen leiden tot verminderde prestaties

>[!NOTE]
>
>Dit is een probleem met ZScalar en wordt niet door Workfront opgelost.

De webservice van ZScalar maakt standaard gebruik van `http/1.1` , wat kan leiden tot verminderde prestaties in Workfront.

**Oplossing**

Configureer uw ZScalar-software voor gebruik van `http/2` . Dit kan niet worden geconfigureerd in Workfront.

U vindt informatie over `http/2` in de ZScalar-documentatie.

_Eerste rapporteerde op 18 November, 2024._
