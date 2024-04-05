---
title: "Rapporten: 500 fout bij het exporteren van een rapport"
description: "Wanneer een gebruiker probeert om een rapport uit te voeren, voert het rapport niet uit, en de gebruiker ziet een fout. Er is een oplossing beschikbaar."
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 0dbb29f11088b5c963f7972f3ec9e64ee55d6263
workflow-type: tm+mt
source-wordcount: '99'
ht-degree: 0%

---


# Rapporten: 500 fouten bij het exporteren van een rapport

Wanneer een gebruiker probeert om een rapport uit te voeren, voert het rapport niet uit, en de gebruiker ziet de volgende fout:

500: Kan &quot;com.attask.biz.Parameter.getDisplayType()&quot; niet aanroepen omdat &quot;parameter&quot; null /attask/api-internal/report/export is

Dit komt voor wanneer het rapport verwijzingen een project-niveau gebied van de douanemunt.

**Workaround**

Verwijder de kolom die verwijzingen het gebied van de douanemunt en voer opnieuw het rapport uit.

_Voor het eerst gerapporteerd op 4 april 2024._

