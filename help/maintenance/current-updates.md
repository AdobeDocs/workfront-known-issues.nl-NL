---
title: Workfront-onderhoudsupdates
description: Onderhoudsupdates voor [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: 50e30f70083284302eccb04fb056cd4725650419
workflow-type: tm+mt
source-wordcount: '1774'
ht-degree: 0%

---

# [!DNL Workfront] Onderhoudsupdates

De volgende onderhoudsupdates zijn uitgevoerd in 2023.

>[!NOTE]
>
>Deze updates bevatten ook andere kleine of minder duidelijke foutoplossingen. [!DNL Workfront] Ondersteuning geeft een melding wanneer een probleem dat u hebt verzonden, is opgelost.

Voor onderhoudsupdates vóór 2023, zie [Vorige onderhoudsupdates](#previous-maintenance-updates)

## Updates in maart 2023

+++**(Geplande) onderhoudsupdate op 2 maart 2023**

**Kan geen kaarten toevoegen bij groepering**

_Borden_

Wanneer een gebruiker een bord weergeeft met een groepering en probeert een kaart toe te voegen, kan de gebruiker alleen de naam van de kaart invoeren. De overige kaartvelden zijn uitgeschakeld, inclusief de [!UICONTROL Save] knop.

Als de gebruiker de groep wijzigt in [!UICONTROL None], blijft de kwestie. De gebruiker moet de groep wijzigen in [!UICONTROL None] en vernieuw vervolgens de pagina om de mogelijkheid om een kaart toe te voegen te herstellen.

**Koppeling naar een opmerking doorsturen naar [!UICONTROL Details] page**

_Updates_

Wanneer een gebruiker een koppeling volgt naar een opmerking over een object in Workfront, wordt de updatestream kort geladen en wordt de gebruiker omgeleid naar het object [!UICONTROL Details] gebied. Dit kan gebeuren als de gebruiker op de koppeling klikt in een e-mail of de koppeling in zijn browser plakt.

Dit is momenteel alleen van toepassing op objecten Document.

**Afdrukoverzicht wordt niet geladen**

_[!UICONTROL Workfront Proof]_

Wanneer een gebruiker de pagina Afdrukoverzicht probeert te laden, lijkt de pagina te zijn geladen, maar wordt deze nooit geladen.

+++

## Updates in februari 2023

+++**Onderhoudsupdate op 23 februari 2023**

**Koppeling naar een opmerking doorsturen naar [!UICONTROL Details] page**

_Updates_

Wanneer een gebruiker een koppeling volgt naar een opmerking over een object in Workfront, wordt de updatestream kort geladen en wordt de gebruiker omgeleid naar het object [!UICONTROL Details] gebied. Dit kan gebeuren als de gebruiker op de koppeling klikt in een e-mail of de koppeling in zijn browser plakt.

Dit is momenteel alleen van toepassing op objecten Document.

**Gebruiker kan zijn eigen meldingsinstellingen niet bewerken**

_Gebruikers_

Wanneer een gebruiker met een [!UICONTROL Worker] licentie probeert hun eigen meldingsinstellingen te bewerken, de [!UICONTROL Notifications] opties zijn niet zichtbaar in het dialoogvenster [!UICONTROL Edit] en de gebruiker kan de instellingen niet bewerken.

+++

+++**Onderhoudsupdate op 16 februari 2023**

**Meerdere teamtoewijzingen op raden van bestuur**

_Borden_

U kunt nu meerdere teams toewijzen aan een taak of uitgave in een bestuur en aan de raad zelf.

**Limiet voor wegvallen van kaart verhoogd**

_Borden_

De uiterste termijnen voor het wegvallen van kaarten zijn verlengd tot 8 weken/60 dagen in plaats van 4 weken/30 dagen.

**Geplande deactivering deactiveert gebruiker niet**

_Gebruikers_

Wanneer een gebruiker volgens de planning moet worden gedeactiveerd en de geplande datum en tijd verstrijken, wordt de gebruiker niet gedeactiveerd.

+++

+++**Onderhoudsupdate op 9 februari 2023**

**[!UICONTROL Story Points]veld toegevoegd aan taak- en uitgavelijsten en -rapporten**

_Rapporten_

De [!UICONTROL Story Points] is nu beschikbaar om aan lijsten en rapporten voor taken of kwesties toe te voegen. Het is een bewerkbaar, vrij formulierveld dat niet is gekoppeld aan geplande uren of teamtoewijzingen.

+++

+++**Onderhoudsupdate op 8 februari 2023**

**Filterknop in inlaatkolom**

_Borden_

De inlaatkolom op een bord bevat nu een **[!UICONTROL Add a filter]** als de kolom leeg is en er geen filters zijn gemaakt. De knoop opent het configuratiegebied, waar u filters kunt toevoegen om taken en kwesties in de inputkolom te brengen.

+++

+++**Onderhoudsupdate op 2 februari 2023**

**[!UICONTROL Boards]pictogram wordt weergegeven in [!UICONTROL Main Menu] standaard**

_Borden_

De [!UICONTROL Boards] wordt nu weergegeven in het dialoogvenster [!UICONTROL Main Menu] voor gebruikers die geen lay-outsjabloon hebben. Borden worden ook standaard opgenomen in het hoofdmenu voor alle nieuwe lay-outsjablonen die worden gemaakt. Bestaande lay-outsjablonen zijn niet gewijzigd.

**Kan e-mailsjablonen niet opslaan**

_Instellen_

Wanneer een gebruiker een e-mailsjabloon probeert te maken of te bewerken, [!UICONTROL Save] reageert niet en de gebruiker kan de sjabloon niet opslaan.

+++

## Updates in januari 2023

+++**Onderhoudsupdate op 30 januari 2023**

**Sneltoetsen die worden toegevoegd voor algemene tijdlijnhandelingen**

_Timesheets_

De volgende sneltoetsen zijn geïntroduceerd voor de volgende veelvoorkomende acties in een tijdspagina:

* Rij toevoegen (Cmd+Option++ / Ctrl+Option++)
* Rij verwijderen (Cmd+Option+- / Ctrl+Option+-)
* Een tijdelijk item vastzetten of vastzetten (Option+P / Option+P)
* Opmerking openen (Shift+F2 / Shift+F2)
* Opmerking opslaan (Cmd+Enter / Ctrl+Enter)
* Uitbreiden (Shift+Option+Pijl-omhoog / Shift+Alt+Pijl-omhoog)
* Samenvouwen (Shift+Option+Pijl-omlaag / Shift+Alt+Pijl-omlaag)

Het gebied waarop deze acties worden uitgevoerd, moet worden gemarkeerd om ze te kunnen toepassen.

**Nieuwe informatiepictogrammen voor voorkeuren voor tijdbladen, tijdlijnprofielen en tijdbladen**

_Timesheets_

>[!NOTE]
>
>Deze update is alleen beschikbaar in de voorbeeldomgeving op 3 november 2022 en is nu beschikbaar in Production.

Er zijn verschillende informatiepictogrammen toegevoegd aan de volgende instellingen:

* &quot;[!UICONTROL Can edit time]&quot; checkbox wanneer het creëren van of het uitgeven van een timesheet of een timesheet profiel om erop te wijzen dat wanneer toegelaten, de fiatteurs, timesheet ook kunnen voorleggen opnieuw openen of uitgeven, tenzij uw beheerder deze acties in beperkt [!UICONTROL Timesheet Preferences] gebied van [!UICONTROL Setup].
* &quot;[!UICONTROL Restrict timesheet editing to owners and admins]&quot; in de [!UICONTROL Timesheet & Hour Preferences] gebied van [!UICONTROL Setup] om aan te geven dat de volgende gebruikers, wanneer deze optie is uitgeschakeld, ook de tijdbladen kunnen bewerken: gebruikers met administratieve toegang tot timesheets en uren, beoordelaars van tijdbladen die tijd mogen uitgeven, en de managers van timesheet eigenaars.

De functionaliteit van deze instellingen is niet gewijzigd en alleen de informatiepictogrammen zijn toegevoegd om het bereik van de instellingen helderder te maken.

+++

+++**Onderhoudsupdate op 26 januari 2023**

**Fout bij verzenden van verzoek van[!DNL Outlook]**

_Integraties_

Wanneer een gebruiker een aanvraag probeert in te dienen met bijlagen van een [!DNL Outlook] e-mail, uploaden één of meerdere gehechtheid niet, en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL The following error occurred: File with handle xxxx does not exist.]&quot;

Dit komt slechts voor wanneer een taak voor het nieuwe verzoek wordt gemaakt, of door de verzoekrij of manueel wanneer het creëren van het verzoek.

**Nieuwe versie van Desktop Proofing Viewer**

_Proofing_

We hebben een nieuwe versie van de Desktop Proofing Viewer geïmplementeerd om een probleem met het bevriezen van bestanden in de Desktop Proofing Viewer te verhelpen. Gebruikers die de Desktop Proofing Viewer al hebben geïnstalleerd, krijgen deze update automatisch.

Gebruikers kunnen ook handmatig de nieuwste versie verkleinen. Zie voor meer informatie [De Desktop Proofing Viewer installeren](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=en).

* Vorige versie: 2.1.19.
* Nieuwe versie: 2.1.20.

**Gebruiker kan zijn eigen gebruikersinstelling niet bewerken**

_Gebruikers_

Wanneer een gebruiker met een licentie voor werk, revisie of aanvraag zijn eigen gebruikersinstellingen probeert te bewerken, is de pop-up die wordt geopend leeg en kan de gebruiker geen bewerkingen uitvoeren. Om popup weg te gaan, moet de gebruiker de pagina verfrissen.

+++

+++**Onderhoudsupdate op 19 januari 2023**

**Inlaatkolomfilters kunnen nu worden gedeeld**

_Borden_

Wanneer de inlaatkolomfunctie naar Boards is uitgebracht, konden de filters voor het instellen van de inlaatkolom alleen worden gezien door de persoon die deze filters heeft gemaakt. De maker kan de filters nu delen met andere gebruikers of teams.

**Puntfunctionaliteit beschikbaar in [!UICONTROL More] menu**

_Navigatie_

De volgende functies zijn nu beschikbaar in het dialoogvenster [!UICONTROL More] menu voor spelden in de productieomgeving:

* Naam punten wijzigen
* Punten opnieuw ordenen binnen de [!UICONTROL More] menu
* Een punt uit het deelvenster [!UICONTROL More] menu (wanneer u dit doet, wordt het laatste punt in de bovenste navigatiebalk naar de [!UICONTROL More] menu)

+++

+++**Onderhoudsupdate op 18 januari 2023**

**Expressies met jokertekens zijn niet geldig in aangepaste velden**

_Aangepaste Forms_

Wanneer een gebruiker een jokerteken zoals \$$TODAY of $$NOW samen met een bepaling (zoals &quot;-30d&quot;) in een douanegebied gebruikt, keurt de validator de vervanging niet als geldig goed. Jokertekens zonder wijzigingstoetsen worden als geldig beschouwd.

**[!UICONTROL Workload Balancer]toont uren niet verbonden aan een project/een taak/een kwestie**

_[!UICONTROL Workload Balancer]_

Wanneer een gebruiker de [!UICONTROL Workload Balancer], zien zij uren die voor een gebruiker worden geregistreerd die niet met om het even welk project, taak, of kwestie worden geassocieerd, noch worden zij geregistreerd als [!UICONTROL General] uren. Deze uren kunnen alleen worden weergegeven in de weergave van 4 weken of 6 weken.

+++

+++**[!DNL Adobe Workfront Fusion]Onderhoudsupdate (Hot Fix) op 12 januari 2023**

**404 fouten op [!DNL Workfront] modules**

_Workfront Fusion_

Wanneer een scenario loopt, a [!DNL Workfront] retourneert een fout van 404.

Dit is gerapporteerd in de volgende modules:

* [!UICONTROL Read a record]

+++

+++**Onderhoudsupdate (Hot Fix) op 12 januari 2023**

**&quot;[!UICONTROL Whoops]&quot; fout bij het instellen van een berekend veld**

_Aangepaste Forms_

Wanneer een gebruiker een berekend veld maakt of bewerkt op een aangepast formulier en een aangepast veld opneemt in de berekende expressie van het veld, wordt de expressie als ongeldig beschouwd. De [!UICONTROL Save] is uitgeschakeld en de gebruiker kan niet weg navigeren van het aangepaste veld. Bovendien ziet de gebruiker het volgende bericht onder het gebied:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;

Als u het aangepaste veld uit de expressie verwijdert, kan de gebruiker het veld opslaan en verder navigeren.

**Kan toegangsniveaus niet instellen**

_Gebruikers_

Wanneer een gebruiker probeert om het toegangsniveau van een andere gebruiker te veranderen, worden de toegangsniveaus grijs uit en de gebruiker kan hen niet veranderen. Dit gebeurt zelfs wanneer de gebruiker die de wijziging probeert, een systeembeheerder is.

+++

+++**Onderhoudsupdate op 12 januari 2023**

**Ctrl+F of Cmd+F werkt niet zoals verwacht in vervolgkeuzelijsten**

_Aangepaste Forms_

Wanneer een gebruiker een aangepast formulier invult en een vervolgkeuzelijst doorzoekt met Ctrl+F of Cmd+F, wordt vervolgens geprobeerd naar het volgende exemplaar van die zoekopdracht te gaan, keert de vervolgkeuzelijst terug naar de bovenkant van de lijst in plaats van naar het volgende exemplaar van de zoekopdracht te gaan. Dit gebeurt wanneer een vervolgkeuzelijst is ingesteld om meerdere selecties toe te staan.

**[!UICONTROL Edit Report]scherm is leeg**

_Rapporten_

Wanneer een gebruiker een rapport bekijkt en probeert om het rapport uit te geven, wordt de gebruiker genomen aan een leeg scherm en kan niet het rapport uitgeven.

**Ingesprongen taken blijven niet ingesprongen**

_Taken_

Wanneer een gebruiker een takenlijst bekijkt en een taak inspringt, keert de taak onmiddellijk aan zijn originele (uitgedreven) staat terug.

+++

+++**Onderhoudsupdate op 5 januari 2023**

**Puntfunctionaliteit beschikbaar in [!UICONTROL More] menu**

_Navigatie_

De volgende functies zijn nu beschikbaar in het dialoogvenster [!UICONTROL More] menu voor punten, alleen in de voorvertoningsomgeving:

* Naam punten wijzigen
* Punten opnieuw ordenen binnen de [!UICONTROL More] menu
* Een punt uit het deelvenster [!UICONTROL More] menu (wanneer u dit doet, wordt het laatste punt in de bovenste navigatiebalk naar de [!UICONTROL More] menu)

**Verwijderd de beperking van de projectgroep van het toevoegen van gebruikers aan het projectteam**

_Teams_

Wij hebben de beperking verwijderd die vereiste dat de gebruikers die aan een projectteam moeten worden toegevoegd in de Groep verbonden aan het project moeten zijn. Nu, kunt u om het even welke actieve gebruiker aan een projectteam toevoegen, ongeacht tot welke groepen zij behoren.

**Nieuwe informatiepictogrammen voor voorkeuren voor tijdbladen, tijdlijnprofielen en tijdbladen**

>[!NOTE]
>
>Deze update is op 3 november 2022 uitgebracht naar de voorvertoningsomgeving en is nu beschikbaar in Production

_Workfront_

Er zijn verschillende informatiepictogrammen toegevoegd aan de volgende instellingen:

* &quot;Kan tijd&quot;checkbox uitgeven wanneer het creëren van of het uitgeven van een timesheet of een timesheet profiel om erop te wijzen dat wanneer toegelaten, de fiatteurs ook kunnen voorleggen, opnieuw openen, of uitgeven timesheet, tenzij uw beheerder deze acties in het gebied van de Voorkeur van de Chronologie van Opstelling beperkt.
* &quot;Beperk het uitgeven van timesheet tot eigenaars en beheerders&quot;in het gebied van de Voorkeur van de Tijdopmaak &amp; van het Uur van Opstelling om erop te wijzen dat wanneer gehandicapt, de volgende gebruikers de timesheets kunnen ook uitgeven: gebruikers met administratieve toegang tot timesheets en uren, beoordelaars van tijdbladen die tijd mogen uitgeven, en de managers van timesheet eigenaars.

De functionaliteit van deze instellingen is niet gewijzigd en alleen de informatiepictogrammen zijn toegevoegd om het bereik van de instellingen helderder te maken.

+++

## Vorige onderhoudsupdates

Informatie over vorige onderhoudsupdates is hier beschikbaar:

* [[!DNL Workfront] Archief met onderhoudsupdates - 2022](2022-updates.md)
* [[!DNL Workfront] Archief met onderhoudsupdates - 2021](2021-updates.md)
