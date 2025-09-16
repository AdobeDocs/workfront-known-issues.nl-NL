---
title: 'Workfront Fusion: Jira Search module retourneert een fout'
description: De zoekmodule die door de verouderde Jira-connector wordt gebruikt, kan een fout veroorzaken. Een oplossing is beschikbaar
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 0f4dba4664f645920752cc0c346782c9582b0e54
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 0%

---


# Workfront Fusion: Jira Search module retourneert een fout

>[!NOTE]
>
>Dit probleem is het gevolg van een wijziging die Jira in zijn product heeft aangebracht.

De zoekmodule die door de verouderde Jira-connector wordt gebruikt, kan de volgende fout opleveren:

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

Dit is te wijten aan een afkeer aan de zijde van Jira.

Let op:

* Dit heeft alleen invloed op de module Zoeken. Op dit moment worden andere Jira API-eindpunten die door de Fusion-connector worden gebruikt, niet beïnvloed door deze afleiding.

* Geografische rollout kan inconsistenties veroorzaken. Atlassian voert deze verandering regionaal uit, wat betekent sommige instanties van de Wolk van Jira nog kunnen oudere eindpunten tijdelijk steunen. Dit kan leiden tot inconsequent gedrag in verschillende omgevingen.

**Oplossing**

Als deze fout optreedt, kunt u de zoekmodule van de verouderde Jira-connector vervangen door de zoekmodule van de nieuwe connector. Met de nieuwe connector kunt u de gebruikte API-versie selecteren. Ben zeker om **V3** op het **te selecteren API gebied van de Versie** wanneer het creëren van de verbinding.

_Eerste rapporteerde op 15 September, 2025._

