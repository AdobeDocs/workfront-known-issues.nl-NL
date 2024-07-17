---
title: 'Timesheets: Vastgezet tijdblad gaat naar lege pagina'
description: Wanneer een gebruiker op een speldenknop in Workfront klikt die naar zijn tijdspagina moet gaan, gaat het speldenpakket naar een lege pagina. Er is een tijdelijke oplossing beschikbaar.
hidefromtoc: true
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
source-git-commit: 1aed6a440155c99f8ce0b0f42c44dd9a3c660af4
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 0%

---

# Timesheets: Vastgezet tijdblad verwijst naar lege pagina

<!--article live for workaround-->

Wanneer een gebruiker op een speldenknop in Workfront klikt die naar zijn tijdspagina moet gaan, gaat het speldenpakket naar een lege pagina.

De reden hiervoor is dat de URL van de tijdpagina is gewijzigd. De `/own` aan het einde van de URL is niet langer de juiste URL. Als de gebruiker een URL met `/own` heeft vastgezet, leidt dat tot een lege pagina.

**Oplossing**

1. Maak het tijdspad los.
1. `/own` verwijderen van het einde van de URL
1. Plaats de tijdpagina opnieuw.

_Eerste rapporteerde op 7 Mei, 2024._
