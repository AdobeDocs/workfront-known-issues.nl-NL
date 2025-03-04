---
title: 'Integratie: outlookIdentityToken-fout bij gebruik van Workfront for Outlook'
description: Wanneer een gebruiker Workfront for Outlook-integratie gebruikt, wordt mogelijk een fout weergegeven.
hidefromtoc: true
feature: Workfront Integrations and Apps
source-git-commit: 19d438b3a368b076aa03a89fe6648ec4b225225f
workflow-type: tm+mt
source-wordcount: '127'
ht-degree: 0%

---


# Integratie: outlookIdentityToken-fout bij gebruik van Workfront for Outlook

Wanneer een gebruiker de integratie Workfront for Outlook gebruikt, kan de volgende fout optreden:

```
Unexpected error
Unable to get the outlookIdentityToken
```

**Oplossing**


Om deze fout op te lossen, moet u Microsoft 365 oudere tokens voor uw organisatie toelaten. Omdat dit moet gebeuren in Microsoft 365, kan Workfront deze tokens niet inschakelen voor uw organisatie.

Voor instructies bij het toelaten van Microsoft 365 erfenistokens, zie [ Online tokens van de Verouderde Uitwisseling van de Draai ](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off) in de documentatie van Microsoft.

Voor meer informatie over erfenistokens, zie [ Kan ik Uitwisseling Online erfenistokens terug draaien?](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on) in de documentatie van Microsoft.


_Eerste rapporteerde op 3 Maart, 2025, 2024._
