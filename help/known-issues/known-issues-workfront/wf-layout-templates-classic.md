---
title: 'Lay-outsjablonen: lay-outsjablonen die inconsistenties in rapporten veroorzaken'
description: Layoutsjablonen uit de klassieke Workfront-ervaring zijn niet meer beschikbaar in de Workfront-interface, maar kunnen nog steeds van invloed zijn op Workfront-gegevens. Dit kan inconsistenties veroorzaken in velden die worden beïnvloed door lay-outsjablonen (zoals Gedeeld met) in rapporten of dashboards.
hidefromtoc: true
feature: System Setup and Administration
exl-id: 1542291f-4797-477e-83b8-0706ac6801ae
source-git-commit: 10507904c2e6d6a8adc182551f6425b78aab4fce
workflow-type: tm+mt
source-wordcount: '191'
ht-degree: 0%

---

# Lay-outsjablonen: Lay-outsjablonen veroorzaken inconsistenties in rapporten

Lay-outsjablonen vanuit de klassieke [!DNL Workfront] de ervaring is niet meer beschikbaar in het dialoogvenster [!DNL Workfront] interface, maar kan nog beïnvloeden [!DNL Workfront] gegevens. Dit kan inconsistenties veroorzaken in velden die worden beïnvloed door lay-outsjablonen (zoals [!UICONTROL Shared with]) op rapporten of dashboards.

**Workaround**

Verwijder de klassieke lay-outsjablonen met een API-aanroep. U moet zijn aangemeld bij Workfront.

>[!NOTE]
>
>De globale en de lay-outmalplaatjes van het Systeem kunnen niet worden geschrapt.

1. Zoek de lay-outsjabloon die u wilt verwijderen met behulp van de volgende API-aanroep:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. Noteer de id van de lay-outsjabloon die u wilt verwijderen.
1. Zoek de sessie-id met de volgende API-aanroep:
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >Deel uw sessie-id nooit met iemand.

1. Plaats de id van de lay-outsjabloon en de sessie-id in de volgende API-aanroep:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. Plak de API-aanroep vanuit stap 4 in de URL-balk van uw browser en druk op Enter.

   Hiermee verwijdert u de lay-outsjabloon.
