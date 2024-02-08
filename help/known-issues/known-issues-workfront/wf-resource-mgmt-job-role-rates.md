---
title: "Resourcebeheer: onjuiste financiële berekeningen als gevolg van problemen met de functie"
description: "De berekeningen van uren en van de financiën kunnen onjuist zijn, die een kosten van 0 tonen alhoewel de uren in een baanrol worden geregistreerd die een kostentarief heeft."
hidefromtoc: true
feature: Resource Management
source-git-commit: f8579e17458f702580e1a4cf3600c14376d7591b
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 0%

---


# Resourcebeheer: onjuiste financiële berekeningen als gevolg van problemen met functies

>[!NOTE]
>
>Dit probleem is op 8 februari 2024 opgelost.

De berekeningen van uren en van de financiën kunnen onjuist zijn, die een kosten van 0 tonen alhoewel de uren in een baanrol worden geregistreerd die een kostentarief heeft.

Dit komt omdat de Rollen van de Baan automatisch dubbele tarieven zonder begin of einddata creëren. Omdat ze geen begin- of einddatum hebben, worden ze behandeld als een waarde van 0 wanneer financieringsberekeningen worden uitgevoerd.

**Workaround**

1. Zorg ervoor dat de correcte gegevens uit het verleden zijn opgeslagen.
1. Verwijder de dubbele tarieven zonder begin- of einddatum.
1. De financiën opnieuw berekenen.

_Eerste rapportage op 18 januari 2023._
