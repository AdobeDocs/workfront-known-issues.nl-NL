---
title: "Workfront Fusion: Output formatting for dates"
description: "Wanneer Datums worden uitgevoerd als Tekenreeksen, kan de datum worden uitgevoerd als een UTC- of ISO-tekenreeks. Dit is afhankelijk van de logica in een toewijzingspaneel."
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---


# Workfront Fusion: uitvoeropmaak voor datums

Wanneer Datums worden uitgevoerd als Tekenreeksen, kan de datum worden uitgevoerd als een UTC- of ISO-tekenreeks. Dit is afhankelijk van de logica in een toewijzingspaneel:

* Als een Date binnen een functie wordt aangesloten bij een tekenreeks, wordt de tekenreeks uitgevoerd in **UTC** gebruiken.
* Als de Datum niet binnen een functie wordt aangesloten zal het als output worden **ISO-tekenreeks**.

Klanten moeten de opdracht `toString` (voor ISO) of `formatDate` functies om ervoor te zorgen dat de uitvoer in de gewenste indeling wordt uitgevoerd.
