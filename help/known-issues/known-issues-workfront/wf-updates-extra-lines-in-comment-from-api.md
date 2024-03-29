---
title: "Updates: extra regels in opmerkingen die zijn gemaakt via API of Workfront Fusion"
description: "Wanneer een gebruiker een opmerking verzendt via de API of via Workfront Fusion, worden extra regels weergegeven voor de opmerking die wordt weergegeven in het gedeelte Updates. Soms zijn er zo veel regels dat de gebruiker omlaag moet schuiven om de inhoud van de opmerking te zien."
hidefromtoc: true
feature: Updates and Notifications
source-git-commit: 6d87394383aaf54385163729f85ea065588967c9
workflow-type: tm+mt
source-wordcount: '173'
ht-degree: 0%

---


# Updates: extra regels in opmerkingen die zijn gemaakt via API of [!DNL Workfront Fusion]

>[!NOTE]
>
>Dit probleem is op 16 november 2023 opgelost.

Wanneer een gebruiker een opmerking verzendt via de API of via [!DNL Workfront Fusion]bevat de opmerking die wordt weergegeven in het gedeelte Updates extra regels. Soms zijn er zoveel regels dat de gebruiker omlaag moet schuiven om de inhoud van de opmerking te zien.

Dit is gemeld in de nieuwe ervaringen met opmerkingen.

**Workaround**

Dit probleem wordt veroorzaakt door spaties of regeleinden in de HTML die wordt verzonden in de opmerking.

U voorkomt dit door ervoor te zorgen dat alle HTML zich op één regel bevindt, zonder spaties of regeleinden tussen de HTML-elementen.

Schakel over naar de klassieke ervaring met opmerkingen als u de desbetreffende opmerkingen zonder de extra regels wilt weergeven.

_Voor het eerst gerapporteerd op 27 oktober 2023._
