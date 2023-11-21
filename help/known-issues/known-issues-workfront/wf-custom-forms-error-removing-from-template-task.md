---
title: "Aangepaste formulieren: kan geen grote hoeveelheden toevoegen of verwijderen van aangepaste formulieren voor sjabloontaken"
description: "Als een gebruiker probeert een aangepast formulier in bulk toe te voegen of te verwijderen voor een sjabloontaak, wordt het formulier niet toegevoegd of verwijderd en ziet de gebruiker een fout."
hidefromtoc: true
feature: Custom Forms
source-git-commit: 41df80641db82b225753338d8564e12b90566c40
workflow-type: tm+mt
source-wordcount: '144'
ht-degree: 0%

---


# Aangepaste formulieren: kan geen grote hoeveelheden toevoegen of verwijderen van aangepaste formulieren voor sjabloontaken

Als een gebruiker probeert een aangepast formulier in een sjabloontaak in bulk toe te voegen of te verwijderen, wordt het formulier niet toegevoegd of verwijderd en ziet de gebruiker de volgende fout:

[!UICONTROL Let's try that again. Invalid Parameter: templateID value "XXXXXXXXXXXXXXXX"]

Als de gebruiker van het malplaatje met gespecificeerde GUID de plaats bepaalt, dan probeert om douaneformulieren op de rest van de malplaatjetaken toe te voegen of te verwijderen, zal de fout opnieuw voorkomen gebruikend een andere templateID.

Aangepaste formulieren kunnen worden toegevoegd aan of verwijderd uit één sjabloontaak. Deze fout is alleen van toepassing op bulkoptellen of verwijderen.

_Voor het eerst gerapporteerd op 10 november 2023._
