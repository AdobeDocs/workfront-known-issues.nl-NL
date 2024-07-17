---
title: 'Workfront Fusion: uitvoeropmaak voor datums'
description: Wanneer Datums worden uitgevoerd als Tekenreeksen, kan de datum worden uitgevoerd als een UTC- of ISO-tekenreeks. Dit is afhankelijk van de logica in een toewijzingspaneel.
hidefromtoc: true
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
source-git-commit: 7aba3a4ce3e0436a8fd9850197bc44da9dafe347
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---

# Workfront Fusion: uitvoeropmaak voor datums

Wanneer Datums worden uitgevoerd als Tekenreeksen, kan de datum worden uitgevoerd als een UTC- of ISO-tekenreeks. Dit is afhankelijk van de logica in een toewijzingspaneel:

* Als een Datum binnen een functie aan een koord wordt aangesloten, dan zal het koord in **UTC** formaat worden uitgevoerd.
* Als de Datum niet binnen een functie wordt aangesloten zal het als **koord van ISO** worden uitgevoerd.

Klanten moeten de functies `toString` (voor ISO) of `formatDate` gebruiken om ervoor te zorgen dat de uitvoer de gewenste indeling heeft.
