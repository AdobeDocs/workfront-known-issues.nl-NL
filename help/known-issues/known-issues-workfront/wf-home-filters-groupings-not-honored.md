---
title: 'Nieuwe startpagina: standaardwaarden voor widgetfilter en -groepering volgen lay-outsjabloon niet'
description: Wanneer een gebruiker Mijn Projecten, Mijn Taken, of Mijn Uitgave widget in de nieuwe ervaring van het Huis bekijkt, zijn het standaardfilter en het groeperen voor die widget niet het gebrek plaatsend in het lay-outmalplaatje dat aan die gebruiker wordt toegewezen.
hidefromtoc: true
feature: Get Started with Workfront
exl-id: d7038535-98ff-405b-9c2b-d6474dc568c9
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: tm+mt
source-wordcount: '183'
ht-degree: 0%

---

# Nieuw [!UICONTROL Home]: standaardinstellingen voor widgetfilter en -groepering volgen niet de lay-outsjabloon

>[!NOTE]
>
>Deze kwestie is gesloten omdat het zoals ontworpen werkt.

Wanneer een gebruiker de widget [!UICONTROL My Projects] , [!UICONTROL My Tasks] of [!UICONTROL My Issues] in de nieuwe [!UICONTROL Home] -ervaring bekijkt, zijn het standaardfilter en de standaardgroep voor die widget niet de standaardinstelling in de lay-outsjabloon die aan die gebruiker is toegewezen.

**Oplossing**:

Wanneer u Nieuw startpunt gebruikt, is het belangrijk om te onthouden dat aan gebruikersinstellingen (voorkeuren) prioriteit wordt toegekend. Als u een standaardfilter of -groep voor een specifieke widget instelt met een lay-outsjabloon, wordt dit mogelijk niet onmiddellijk van kracht vanwege bestaande gebruikersvoorkeuren. Als u het nieuwe filter of de nieuwe groep wilt toepassen, moet u of de gebruiker de voorkeuren mogelijk opnieuw instellen. U doet dit door `/resetUser` aan uw URL toe te voegen.

_Eerste rapporteerde op 3 Januari 2024._
