---
title: 'Integratie: outlookIdentityToken-fout bij gebruik van Workfront for Outlook'
description: Wanneer een gebruiker Workfront for Outlook-integratie gebruikt, wordt mogelijk een fout weergegeven.
hidefromtoc: true
feature: Workfront Integrations and Apps
exl-id: a5abe90c-4583-467e-8131-60bead300673
source-git-commit: 87c56abf4a5020632877263329f1455bbf4cc7f3
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 0%

---

# Integratie: outlookIdentityToken-fout bij gebruik van Workfront for Outlook

>[!NOTE]
>
>De Workfront for Outlook-integratie is niet meer beschikbaar. Dit artikel wordt in de nabije toekomst verwijderd.

Wanneer een gebruiker de integratie Workfront for Outlook gebruikt, kan de volgende fout optreden:

```
Unexpected error
Unable to get the outlookIdentityToken
```

**Oplossing**


Om deze fout op te lossen, moet u Microsoft 365 oudere tokens voor uw organisatie toelaten. Omdat dit moet gebeuren in Microsoft 365, kan Workfront deze tokens niet inschakelen voor uw organisatie.

Voor instructies bij het toelaten van Microsoft 365 erfenistokens, zie [&#x200B; Online tokens van de Verouderde Uitwisseling van de Draai &#x200B;](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off) in de documentatie van Microsoft.

Voor meer informatie over erfenistokens, zie [&#x200B; Kan ik Uitwisseling Online erfenistokens terug draaien?](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on) in de documentatie van Microsoft.


_Eerste rapporteerde op 3 Maart, 2025, 2024._
