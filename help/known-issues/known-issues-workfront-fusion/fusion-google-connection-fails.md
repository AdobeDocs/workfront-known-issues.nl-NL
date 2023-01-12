---
title: 'Workfront Fusion: Kan geen verbinding maken met Google'
description: Wanneer een gebruiker een verbinding probeert te maken in een van de Google-connectors (zoals Google Sheets of Google Drive), wordt de verbinding niet gemaakt en ziet de gebruiker verschillende foutberichten.
hidefromtoc: true
exl-id: 068793be-63e5-40b5-bf10-c01d76c1b6e7
source-git-commit: dd093aff6103901898c561c9f6f544c1648682a3
workflow-type: tm+mt
source-wordcount: '93'
ht-degree: 0%

---

# [!DNL Workfront Fusion]: Kan geen verbinding maken met [!DNL Google]

>[!NOTE]
>
>Dit probleem is op 9 januari 2023 opgelost.

Wanneer een gebruiker een verbinding probeert te maken in een van de [!DNL Google] connectors (zoals [!DNL Google Sheets] of [!DNL Google Drive]), wordt een venster geopend met de volgende fout:

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

Wanneer de gebruiker dit venster sluit, mislukt de verbinding met de volgende fout in [!DNL Fusion]:

&quot;[!UICONTROL Error: The request failed due to the failure of a prevoius request. No access token specified.]&quot;

_Voor het eerst gerapporteerd op 21 november 2022._
