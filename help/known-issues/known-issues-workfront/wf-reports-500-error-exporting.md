---
title: 'Rapporten: 500 fouten bij het exporteren van een rapport'
description: Wanneer een gebruiker probeert om een rapport uit te voeren, voert het rapport niet uit, en de gebruiker ziet een fout. Er is een tijdelijke oplossing beschikbaar.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5ebdf00e-122b-4646-b9d8-8775d6e7c1cf
source-git-commit: cebbfd27b0d07c77706a609e38935f01d9727404
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 0%

---

# Rapporten: 500 fouten bij het exporteren van een rapport

>[!NOTE]
>
>Dit probleem is op 5 april 2024 opgelost.

Wanneer een gebruiker probeert om een rapport uit te voeren, voert het rapport niet uit, en de gebruiker ziet de volgende fout:

500: Kan &quot;com.attask.biz.Parameter.getDisplayType()&quot; niet aanroepen omdat &quot;parameter&quot; null /attask/api-internal/report/export is

Dit komt voor wanneer het rapport verwijzingen een project-niveau gebied van de douanemunt.

**Workaround**

Verwijder de kolom die verwijzingen het gebied van de douanemunt en voer opnieuw het rapport uit.

_Voor het eerst gerapporteerd op 4 april 2024._
