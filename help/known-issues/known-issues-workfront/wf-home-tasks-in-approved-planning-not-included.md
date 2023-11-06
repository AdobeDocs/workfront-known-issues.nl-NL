---
title: "Huis: De taken in projecten met Goedgekeurd of de status van de Planning zijn niet inbegrepen in Mijn Taken of Lijst van het Werk van het Huis"
description: "De taken van projecten die de goedgekeurde status of de Planning hebben worden niet getoond in Huis. Er is een oplossing beschikbaar."
hidefromtoc: true
feature: Get Started with Workfront
source-git-commit: 5b22b37a13774e4552ec9390a70040f0182851d3
workflow-type: tm+mt
source-wordcount: '166'
ht-degree: 0%

---


# Home: De taken in projecten met Goedgekeurde of de status van de Planning zijn niet inbegrepen in Mijn Taken of de Lijst van het Werk van het Huis

De taken van projecten die de goedgekeurde status of de Planning hebben worden niet getoond op de volgende gebieden:

* Klassieke startpagina: werklijst
* Nieuwe startpagina: De widget Mijn taken

Dit is omdat de taken van projecten in deze statussen momenteel inbegrepen in de 2000 grens van de puntvraag zijn, maar zij worden niet getoond in Mijn Taken of de Lijst van het Werk van het Huis. Hierdoor kan een situatie ontstaan waarin een gebruiker met minder dan 2000 taken deze taken niet zichtbaar is.

**Workaround**

Maak een aangepast toewijzingsrapport dat de volgende tekstmodusfilters bevat:

Wanneer de Toewijzing AWAITING_ACCEPTANCE is, omvat HUIDIGE|GOEDGEKEURDE projecten:

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

Wanneer de toewijzing wordt AANVAARD, omvat HUIDIGE|GOEDGEKEURDE|PLANNINGprojecten:

```
OR:1:assignedToID=$$USER.ID
OR:1:status=AD
OR:1:status_Mod=eq
OR:1:project:statusEquatesWith=CUR,APR,PLN
OR:1:project:statusEquatesWith_Mod=in
OR:1:task:statusEquatesWith=CPL
OR:1:task:statusEquatesWith_Mod=ne
```

_Voor het eerst gerapporteerd op 6 november 2023._
