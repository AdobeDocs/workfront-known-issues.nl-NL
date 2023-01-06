---
title: "Aangepaste formulieren: Kan veld niet gebruiken in berekening als de veldnaam aanhalingstekens of een apostrof bevat."
description: "Wanneer een gebruiker een berekende veldexpressie maakt en probeert een typeahead-veld op te nemen met een naam met een apostrof- of aanhalingsteken, wordt de berekening niet geaccepteerd en ziet de gebruiker het bericht Dit is een ongeldige aangepaste expressie. Probeer het opnieuw."
hidefromtoc: true
source-git-commit: 254339d1baa9d8d7825e851aeafc9b27b1a1b669
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---


# Aangepaste formulieren: Kan veld niet gebruiken in berekening als veldnaam apostroffen of aanhalingstekens bevat

>[!NOTE]
>
>Het team van het Product evalueert momenteel deze probleemoplossing, die productverbeteringen kan vereisen. De verbeteringen van het product worden meegedeeld in de Mededelingen van het Product en niet met de Updates van het Onderhoud.

Wanneer een gebruiker een berekende veldexpressie maakt en probeert een veld met een typekop te nemen dat een naam met een `'` of `"`, wordt de berekening niet geaccepteerd en ziet de gebruiker het bericht &quot;[!UICONTROL This is an invalid custom expression, please try again.]&quot;

Dit probleem doet zich alleen voor bij velden met typekoppen. Tekstvelden met `'` of `"` in de naam kan worden gebruikt in berekende velduitdrukkingen zonder kwestie.

_Voor het eerst gerapporteerd op 10 november 2022._

