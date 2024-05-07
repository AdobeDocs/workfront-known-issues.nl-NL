---
title: "Timesheets: Vastgezet tijdblad gaat naar lege pagina"
description: "Wanneer een gebruiker op een speldenknop in Workfront klikt die naar zijn tijdspagina moet gaan, gaat het speldenpakket naar een lege pagina. Er is een oplossing beschikbaar."
hidefromtoc: true
feature: Timesheets
source-git-commit: 229d3accabec51a7c559279b680336ca096c0e70
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 0%

---


# Timesheets: Vastgezet tijdblad verwijst naar lege pagina

Wanneer een gebruiker op een speldenknop in Workfront klikt die naar zijn tijdspagina moet gaan, gaat het speldenpakket naar een lege pagina.

De reden hiervoor is dat de URL van de tijdpagina is gewijzigd. de `/own` aan het einde van de URL is niet langer de juiste URL. Als de gebruiker een URL heeft vastgezet die `/own`, leidt dit tot een lege pagina.

**Workaround**

1. Maak het tijdspad los.
1. Verwijderen `/own` vanaf het einde van de URL
1. Plaats de tijdpagina opnieuw.

_Voor het eerst gerapporteerd op 7 mei 2024._

