---
title: 'Workfront Proof: 500-fout bij toegang tot Workfront Proof via API of Workfront Fusion'
description: 'Wanneer een gebruiker de actie Proef API getAllProofs opent, retourneert de Workfront Proof-server het volgende bericht: 500 Interne serverfout'
hidefromtoc: true
feature: Workfront Proof
exl-id: 3c968354-58e2-43fc-8c27-2670683ac862
source-git-commit: 2426476490c3762c7511afee99380afa0bfd85e3
workflow-type: tm+mt
source-wordcount: '102'
ht-degree: 0%

---

# [!DNL Workfront Proof]: 500 fout bij toegang tot [!DNL Workfront Proof] via API of [!DNL Workfront Fusion]

>[!NOTE]
>
>Het team van het Product evalueert momenteel deze probleemoplossing, die productverbeteringen kan vereisen. De verbeteringen van het product worden meegedeeld in de Mededelingen van het Product en niet met de Updates van het Onderhoud.

<!--This article is on Proof and Fusion TOCs-->

Wanneer een gebruiker de handeling [!DNL Workfront Proof] API [!UICONTROL `getAllProofs`] benadert, geeft de server het volgende bericht:

[!UICONTROL 500 Internal Server Error]

Omdat [!DNL Workfront Fusion] de [!DNL Workfront Proof] API voor [!DNL Workfront Proof] modules gebruikt, kan deze fout naar een module worden geretourneerd, waardoor een scenario wordt gestopt.

_Eerste rapporteerde op 28 April, 2023._
