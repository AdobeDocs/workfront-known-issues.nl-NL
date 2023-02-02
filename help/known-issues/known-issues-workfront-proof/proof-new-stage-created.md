---
title: 'Proefdrukken: Nieuwe fase gemaakt omdat deadline niet overeenkomt met deadline van bestaand werkgebied.'''
description: Wanneer nieuwe proefdrukken worden gemaakt, kan de deadline worden ingesteld in stappen van 15 minuten (10:00, 10:15, 10:30, 20:45, enz.). Wanneer een gebruiker echter aan een bewijs wordt toegevoegd nadat de proefdruk is gemaakt, kan de deadline alleen worden ingesteld in stappen van 30 minuten (10:00, 10:30, 11:00, enz.).
hidefromtoc: true
source-git-commit: 3826558093ba7d8aa6ee25211010c60610d03fcc
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Proefdrukken: Nieuwe fase gemaakt omdat deadline niet overeenkomt met deadline van bestaand werkgebied

Wanneer nieuwe proefdrukken worden gemaakt, kan de deadline worden ingesteld in stappen van 15 minuten (10:00, 10:15, 10:30, 20:45, enz.). Wanneer een gebruiker echter aan een bewijs wordt toegevoegd nadat de proefdruk is gemaakt, kan de deadline alleen worden ingesteld in stappen van 30 minuten (10:00, 10:30, 11:00, enz.). Daarom kan de nieuwe gebruiker niet worden toegevoegd aan een werkgebied met een deadline die eindigt op 0,15 of 0,45, omdat de deadlines niet kunnen worden gehaald. In plaats daarvan wordt de nieuwe gebruiker toegevoegd aan een nieuw werkgebied, met een deadline die in stappen van 30 minuten wordt ingesteld.

**Workaround**:

* Als u een deadline voor een nieuwe proefdruk selecteert, stelt u de deadline in op een tijd die eindigt op 0,00 of 0,30 (10:00, 10:30, 11:00, enz.).
* Als de deadline automatisch wordt ingesteld op het moment dat de proef wordt gemaakt, stelt u de deadline van de proef handmatig in op een tijdstip dat eindigt op 00 of 00:30 (10:00, 10:30, 11:00, enz.).
