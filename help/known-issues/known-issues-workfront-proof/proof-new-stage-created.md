---
title: 'Proefversies: nieuwe fase gemaakt omdat deadline niet kan overeenkomen met deadline van bestaande werkgebied'
description: Wanneer nieuwe proefdrukken worden gemaakt, kan de deadline worden ingesteld in stappen van 15 minuten (10:00, 10:15, 10:30, 20:45, enz.). Wanneer een gebruiker echter aan een bewijs wordt toegevoegd nadat de proefdruk is gemaakt, kan de deadline alleen worden ingesteld in stappen van 30 minuten (10:00, 10:30, 11:00, enz.).
hidefromtoc: true
feature: Workfront Proof
exl-id: dc0725f4-d31b-4f55-a3ea-24486ce73ebf
source-git-commit: 98d56729e44e7ab47e201bdfc00db8d40c5f15f6
workflow-type: tm+mt
source-wordcount: '223'
ht-degree: 0%

---

# Proefversies: nieuwe fase gemaakt omdat deadline niet kan overeenkomen met deadline van bestaande werkgebied

<!--Requested article-->

Wanneer nieuwe proefdrukken worden gemaakt, kan de deadline worden ingesteld in stappen van 15 minuten (10:00, 10:15, 10:30, 20:45, enz.). Wanneer een gebruiker echter aan een bewijs wordt toegevoegd nadat de proefdruk is gemaakt, kan de deadline alleen worden ingesteld in stappen van 30 minuten (10:00, 10:30, 11:00, enz.). Daarom kan de nieuwe gebruiker niet worden toegevoegd aan een werkgebied met een deadline die eindigt op 0,15 of 0,45, omdat de deadlines niet kunnen worden gehaald. In plaats daarvan wordt de nieuwe gebruiker toegevoegd aan een nieuw werkgebied, met een deadline die in stappen van 30 minuten wordt ingesteld.

**Oplossing**:

* Als u een deadline voor een nieuwe proefdruk selecteert, stelt u de deadline in op een tijd die eindigt op 0,00 of 0,30 (10:00, 10:30, 11:00, enz.).
* Als de deadline automatisch wordt ingesteld op het moment dat de proef wordt gemaakt, stelt u de deadline van de proef handmatig in op een tijdstip dat eindigt op 00 of 00:30 (10:00, 10:30, 11:00, enz.).
