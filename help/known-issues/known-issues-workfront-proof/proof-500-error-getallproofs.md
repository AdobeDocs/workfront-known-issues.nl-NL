---
title: "Workfront Proof: 500-fout bij toegang tot Workfront Proof via API of Workfront Fusion"
description: "Wanneer een gebruiker toegang krijgt tot de actie Proef API getAllProofs, retourneert de Workfront Proof-server het bericht: 500 Interne serverfout"
hidefromtoc: true
feature: Workfront Proof
source-git-commit: 98d56729e44e7ab47e201bdfc00db8d40c5f15f6
workflow-type: tm+mt
source-wordcount: '99'
ht-degree: 0%

---


# [!DNL Workfront Proof]: 500 fout bij toegang [!DNL Workfront Proof] via API of [!DNL Workfront Fusion]

>[!NOTE]
>
>Het team van het Product evalueert momenteel deze probleemoplossing, die productverbeteringen kan vereisen. De verbeteringen van het product worden meegedeeld in de Mededelingen van het Product en niet met de Updates van het Onderhoud.

<!--This article is on Proof and Fusion TOCs-->

Wanneer een gebruiker tot [!DNL Workfront Proof] API [!UICONTROL `getAllProofs`] actie, keert de server het volgende bericht terug:

[!UICONTROL 500 Internal Server Error]

Omdat [!DNL Workfront Fusion] gebruikt de [!DNL Workfront Proof] API voor [!DNL Workfront Proof] modules, kan deze fout aan een module zijn teruggekeerd, die een scenario tegenhoudt.

_Voor het eerst gerapporteerd op 28 april 2023._

