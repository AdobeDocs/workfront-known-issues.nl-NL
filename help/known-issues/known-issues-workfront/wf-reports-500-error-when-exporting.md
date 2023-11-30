---
title: 'Rapporten: 500 fouten bij het exporteren van een rapport'
description: Wanneer een gebruiker probeert om een rapport uit te voeren, ontbreekt de uitvoer met een fout 500.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 88126bda7f7c51895ae512bb5f7686119febd32f
workflow-type: tm+mt
source-wordcount: '65'
ht-degree: 0%

---

# Rapporten: 500 fouten bij het exporteren van een rapport

>[!NOTE]
>
>Dit probleem is op 30 november 2023 opgelost.

Wanneer een gebruiker een rapport probeert te exporteren, mislukt het exporteren met de volgende fout:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Dit is gemeld in meldingen die een `valueexpression` de `lastNote` notitietekst.

_Voor het eerst gemeld op 8 november 2023._
