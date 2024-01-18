---
title: 'Aangepaste formulieren: kan geen grote hoeveelheden toevoegen of verwijderen van aangepaste formulieren voor sjabloontaken'
description: Als een gebruiker een aangepast formulier in een sjabloontaak in bulk probeert toe te voegen of te verwijderen, wordt het formulier niet toegevoegd of verwijderd en ziet de gebruiker een fout.
hidefromtoc: true
feature: Custom Forms
exl-id: e9014f67-2098-46e4-a301-6a742a0c2ddb
source-git-commit: d3d6529fea8f2d020f4920ee5b2bda723f348cc2
workflow-type: tm+mt
source-wordcount: '150'
ht-degree: 0%

---

# Aangepaste formulieren: kan geen grote hoeveelheden toevoegen of verwijderen van aangepaste formulieren voor sjabloontaken

>[!NOTE]
>
>Dit probleem is op 18 januari 2024 opgelost.

Als een gebruiker probeert een aangepast formulier in een sjabloontaak in bulk toe te voegen of te verwijderen, wordt het formulier niet toegevoegd of verwijderd en ziet de gebruiker de volgende fout:

[!UICONTROL Let's try that again. Invalid Parameter: templateID value "XXXXXXXXXXXXXXXX"]

Als de gebruiker van het malplaatje met gespecificeerde GUID de plaats bepaalt, dan probeert om douaneformulieren op de rest van de malplaatjetaken toe te voegen of te verwijderen, zal de fout opnieuw voorkomen gebruikend een andere templateID.

Aangepaste formulieren kunnen worden toegevoegd aan of verwijderd uit één sjabloontaak. Deze fout is alleen van toepassing op bulkoptellen of verwijderen.

_Voor het eerst gerapporteerd op 10 november 2023._
