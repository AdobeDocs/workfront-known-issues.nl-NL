---
title: 'Proefdrukken: proefdrukken van webvastlegging genereren geen'
description: Wanneer een gebruiker een proefdruk voor het vastleggen van webgegevens probeert te maken, wordt de proefdruk niet gegenereerd.
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
source-git-commit: 7b66d253831c83bf6166cc5be39e18be704503a6
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 0%

---

# Proefdrukken: proefdrukken van webvastlegging genereren geen

>[!NOTE]
>
>Deze kwestie is gesloten omdat het zoals ontworpen werkt. Zie hieronder de tijdelijke oplossing.

Wanneer een gebruiker een proefdruk voor het vastleggen van webgegevens probeert te maken, wordt de proefdruk niet gegenereerd.

**Oplossing**

Dit probleem wordt veroorzaakt door lange proefgeneratietijden voor bepaalde PDF-bestanden. Als u de time-out bij het genereren wilt verhogen vanaf de standaardinstelling in 30 seconden, bewerkt u de onderstaande eigenschap in Verwerkingsinstellingen op accountniveau in Proefbeheerder:

`WebCaptureNavigationTimeout -> 120`

_Eerste rapporteerde op 3 Oktober, 2024._
