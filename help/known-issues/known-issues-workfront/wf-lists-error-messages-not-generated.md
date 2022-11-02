---
title: "Lijsten: Fouten bij inlinebewerking door de gebruiker worden niet veroorzaakt door foutmeldingen"
description: "Wanneer een gebruiker een object inline bewerkt en een fout maakt die een foutbericht moet maken, wordt geen foutbericht weergegeven. De fout zelf wordt niet opgeslagen in Workfront, zodat de gegevens niet worden beïnvloed, maar het ontbreken van een foutenmelding kan verwarring veroorzaken."
hidefromtoc: true
source-git-commit: ed5bd591f4be66631dba19d666b7d280eda1e1ab
workflow-type: tm+mt
source-wordcount: '165'
ht-degree: 0%

---


# Lijsten: Foutberichten worden niet veroorzaakt door inline bewerkingsfouten van de gebruiker

Wanneer een gebruiker een object inline bewerkt en een fout maakt die een foutbericht moet maken, wordt geen foutbericht weergegeven. De fout zelf wordt niet opgeslagen in Workfront, dus de gegevens worden niet beïnvloed, maar het ontbreken van een foutbericht kan verwarring veroorzaken.

Dit is gemeld voor de volgende situaties:

* Voorgangers: Er wordt een voorganger-lus gemaakt, zoals het toewijzen van een taak aan zichzelf
* Datums: Er wordt een onmogelijke datum ingesteld, zoals een voltooiingsdatum die voor de begindatum ligt of die na de projectuitvoeringsdatum valt

_Voor het eerst gerapporteerd op 26 oktober 2022._

