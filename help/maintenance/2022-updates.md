---
title: Workfront Maintenance Updates in 2022
description: 2022 Onderhoudsupdates voor  [!DNL Adobe Workfront]
exl-id: 78ea4e31-143f-4a70-bb9a-060b5a8e097e
feature: Get Started with Workfront
source-git-commit: 003a38b5009e80e1b65c23354c8fb9b38d6a7819
workflow-type: tm+mt
source-wordcount: '15333'
ht-degree: 0%

---

# [!DNL Workfront] Updates voor onderhoud in 2022

De volgende onderhoudsupdates zijn uitgevoerd in 2022.

>[!NOTE]
>
>Deze updates bevatten ook andere kleine of minder duidelijke foutoplossingen. [!DNL Workfront] Ondersteuning geeft een melding wanneer een probleem dat u hebt verzonden, is opgelost.

<!--
* [July 2022](#updates-in-july-2022)
* [June 2022](#updates-in-june-2022)
* [May 2022](#updates-in-may-2022)
* [April 2022](#updates-in-april-2022)
* [March 2022](#updates-in-march-2022)
* [February 2022](#updates-in-february-2022)
* [January 2022](#updates-in-january-2022)
-->

Voor onderhoudsupdates voorafgaand aan 2022, zie [&#x200B; Vorige Updates van het Onderhoud &#x200B;](#previous-maintenance-updates)

## Updates in december 2022

+++**update van het Onderhoud op 15 December, 2022**

**de updates van de Toegankelijkheid in lijsten**

*Lijsten*

De volgende toegankelijkheidsfuncties zijn nu beschikbaar in lijsten:

* Selectievakjes in lijsten hebben nu een zichtbare focusindicator wanneer u er met Tab naartoe gaat. Hierdoor is het gemakkelijker om de toetsenbordnavigatie van items in een lijst visueel te volgen.
* Alle knoppen in de lijstwerkbalken hebben nu dezelfde aanwijs- en focusstatus, met een grijze achtergrond die wordt weergegeven op de aanwijsbalk en een grijze achtergrond en een blauwe omtrek die scherp wordt weergegeven.
* Als u eerder een vervolgkeuzemenu opent in een lijst met de spatietoets, wordt het menu geopend en wordt de pagina ook een beetje omlaag geschoven, wat niet de bedoeling was. De pagina wordt nu niet meer verschoven wanneer u op Ruimte drukt in een vervolgkeuzelijst. Dit is de juiste manier.
* Wanneer u een lijst bekijkt terwijl het selectievakje voor rijen is ingeschakeld, kunt u nu met de Tab-toets door elk bewerkbaar item bladeren en vervolgens op de toets Ruimte drukken om over te schakelen op de modus Bewerken en om te beginnen met het bewerken van die cel in de rij. Eerder was navigatie met het toetsenbord niet mogelijk voor deze items en was het gebruik van een muis vereist. Nu is het schakelen naar de bewerkingsmodus zowel muisvriendelijk als toetsenbordvriendelijk.

**&quot;[!UICONTROL Whoops]&quot;fout wanneer het creëren van een project van een malplaatje**

*Projecten*

Wanneer een gebruiker probeert om een project van een malplaatje tot stand te brengen, wordt het project niet gecreeerd, en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

**grafiek van de Combinatie toont tweemaal de zelfde gegevens**

*Rapporten*

Wanneer een gebruiker een combinatieschema bekijkt, wordt in het diagram tweemaal één waardenset weergegeven in plaats van twee waardensets te vergelijken. De juiste waardensets vindt u in de rapportdetails.

**Tooltips die voor gedimde uurcellen in timesheets worden toegevoegd**

*Timesheets*

Wij hebben tooltips toegevoegd om de reden te verklaren waarom een uurcel in een timesheet kan worden gedimd. Een aantal van de redenen kan bijvoorbeeld zijn omdat het tijdspad is gesloten of omdat het project is voltooid.

**Gedeactiveerde gebruikers beschikbaar wanneer het selecteren van chronologie goedkeurde**

*Timesheets*

Wanneer een gebruiker een timesheet maakt en een fiatteur probeert toe te wijzen, bevat de vervolgkeuzelijst gedeactiveerde gebruikers. Als een gedeactiveerde gebruiker wordt geselecteerd, wordt timesheet niet bewaard en de gebruiker ziet het volgende bericht:

&quot;[!UICONTROL Error. Sorry! Only users with Plan license can approve or reject timesheets. Please contact your system administrator.]&quot;

Aangezien de gedeactiveerde gebruiker niet kan worden toegewezen, moet de gebruiker een geactiveerde gebruiker selecteren. De tijdpagina functioneert daarom zoals verwacht, maar de gedeactiveerde gebruikers in de lijst kunnen verwarring of ongemak veroorzaken voor de gebruiker.

**kan geen tijd op timesheet** ingaan

*Timesheets*

Wanneer een gebruiker probeert om tijd aan een timesheet toe te voegen, zien zij dat de uurvakjes in om het even welke tijd van het Project of de rijen van de Tijd van de Taak uit grijs zijn, en zij kunnen geen tijd in deze vakjes ingaan. Ze kunnen alleen tijd invoeren in het gebied Algemene tijd.

+++

+++**update van het Onderhoud op 8 December, 2022**

**Slimme gebruikersselectie wanneer het toevoegen van fiatteurs aan een goedkeuringspad**

*Goedkeuringen*

De weergave van gebruikers is verbeterd wanneer u deze toevoegt aan het veld [!UICONTROL Approvers] van een nieuwe goedkeuring.

Wanneer u nu een gebruiker toevoegt aan het veld [!UICONTROL Approvers] van een systeemniveau of goedkeuring voor eenmalig gebruik, worden naast zijn naam en avatar ook zijn primaire rol en de e-mail weergegeven. Zo kunt u beter onderscheid maken tussen meerdere gebruikers met dezelfde of vergelijkbare namen.

**de status van het Project volgt niet het projectvoorkeur van de Groep**

*Projecten*

Wanneer een gebruiker tot een project van een malplaatje leidt, neemt het nieuwe project niet de status die in de het projectvoorkeur van de Groep wordt geplaatst. Als een project zonder een malplaatje wordt gecreeerd, wijst de status op het projectvoorkeur van de Groep zoals verwacht.

**kan subtask** toevoegen niet

*Taken*

Wanneer een gebruiker probeert om een subtaak toe te voegen gebruikend &quot;[!UICONTROL +New]&quot;knoop, verschijnen geen opties in het [!UICONTROL New Task] venster, en de gebruiker ziet het volgende bericht:

&quot;[!UICONTROL Cannot read properties of undefined (reading 'validations)]&quot;

**Fouten wanneer het sluiten van of het bewaren van chronologie**

*Timesheets*

Wanneer een gebruiker probeert om tijd aan toe te voegen of een timesheet te sluiten, bewaart timesheet niet, en de gebruiker ziet de volgende fouten:

* Databasefout vanwege ongeldige SQL-instructie.
* De recente wijzigingen zijn niet opgeslagen. Vernieuw de pagina om de laatst opgeslagen wijzigingen weer te geven.

+++

+++**Update van het Onderhoud (Hete Fix) op 1 December, 2022**

**Inline het uitgeven fouten door gebruiker veroorzaken geen foutenmeldingen**

*Lijsten*

Wanneer een gebruiker een object inline bewerkt en een fout maakt die een foutbericht moet maken, wordt geen foutbericht weergegeven. De fout zelf wordt niet opgeslagen in Workfront, dus de gegevens worden niet beïnvloed, maar het ontbreken van een foutbericht kan verwarring veroorzaken.

Dit is gemeld voor de volgende situaties:

* Voorgangers: er wordt een voorganger gemaakt, bijvoorbeeld een taak aan zichzelf toewijzen
* Datums: er wordt een onmogelijke datum ingesteld, zoals een voltooiingsdatum die voor de begindatum ligt of die na de projectuitvoeringsdatum ligt

**de optie &quot;van de Beweging aan&quot;niet beschikbaar op uitgifterapporten**

*Rapporten*

Wanneer een gebruiker een probleemrapport weergeeft en een probleem probeert te verplaatsen, is de optie &quot;Verplaatsen naar&quot; niet beschikbaar in het menu Meer (drie punten).


**kan gebruikerskaart in updatestroom niet sluiten**

*Updates*

Wanneer een gebruiker updates weergeeft en deze boven een naam plaatst, wordt een kaart met gegevens over de gebruiker wiens naam wordt geopend en wordt deze niet automatisch gesloten. De pagina reageert pas als de kaart handmatig wordt gesloten door op de X in de rechterbovenhoek te klikken.


+++

+++**Update van het Onderhoud op 1 December, 2022**

**de Taak heeft een Kanban achterlogorde van 0**

*Gelijk*

Wanneer een gebruiker de achterstand van een Kanban-team bekijkt, tonen een of meer van de taken een achterlogorde van 0.

**&quot;[!UICONTROL Invalid custom expression]&quot;bericht wanneer het van verwijzingen voorzien &quot;[!UICONTROL owner]&quot;op een berekend gebied**

*de vormen van de Douane*

Wanneer een gebruiker een berekend gebied aan een kwestie-vlakke douaneformulier toevoegt en om het even welke verwijzing naar &quot; [!UICONTROL owner]&quot;(zoals `ownerID`) probeert toe te voegen, slaat het gebied niet op, en de gebruiker ziet het volgende bericht:

&quot;[!UICONTROL This is an invalid customer expression, please try again.]&quot;

Dit gebeurt zelfs wanneer de expressie geldig is.

**kan tot elementen van [!DNL Workfront for Jira] integratie** niet toegang hebben

*Integraties*

De volgende elementen zijn momenteel niet toegankelijk via de [!DNL Workfront for Jira] -integratie voor [!DNL Jira Cloud] :

* De pagina [!UICONTROL Configuration]
* De knop &quot;[!UICONTROL Open Workfront]&quot; op een [!DNL Jira] -uitgave

**Toevoegend douanebericht veroorzaakt kwestie in de kijker van het Bewijs**

*Proofs*

Wanneer een gebruiker een proef deelt en probeert om een douanebericht toe te voegen, komt het volgende voor:

* In de proefdrukviewer wordt ingezoomd.
* De gebieden in de linkernavigatie reageren niet meer.

**Gedeactiveerde gebruikers beschikbaar wanneer het selecteren van chronologie goedkeurde**

*Timesheets*

Wanneer een gebruiker een timesheet maakt en een fiatteur probeert toe te wijzen, bevat de vervolgkeuzelijst gedeactiveerde gebruikers. Als een gedeactiveerde gebruiker wordt geselecteerd, wordt timesheet niet bewaard en de gebruiker ziet het volgende bericht:

&quot;[!UICONTROL Error. Sorry! Only users with Plan license can approve or reject timesheets. Please contact your system administrator.]&quot;

Aangezien de gedeactiveerde gebruiker niet kan worden toegewezen, moet de gebruiker een geactiveerde gebruiker selecteren. De tijdpagina functioneert daarom zoals verwacht, maar de gedeactiveerde gebruikers in de lijst kunnen verwarring of ongemak veroorzaken voor de gebruiker.

**Timesheet wordt niet geproduceerd**

*Timesheets*

Tijdschema&#39;s worden niet gegenereerd, ondanks tijdbladprofielinstellingen. Omdat het timesheet nooit wordt geproduceerd, is het niet beschikbaar voor de gebruiker om tijd in te gaan, en het is niet zichtbaar op lijsten.

+++

## Updates in november 2022

+++**Update van het Onderhoud op 17 November, 2022**

**Documenten die in [!UICONTROL Recycle Bin] worden geplaatst als unselected wanneer het bewegen van een taak of een kwestie**

*Documenten*

Wanneer u nu de optie [!UICONTROL Documents] uitschakelt tijdens het verplaatsen van een taak of een uitgave, worden de documenten die aan de taak zijn gekoppeld, of de uitgave 30 dagen in de [!UICONTROL Recycle Bin] geplaatst. Een beheerder kan deze indien nodig herstellen. De gebruiker die de selectie van Documenten tijdens het bewegingsproces opheft, ontvangt een waarschuwing over dit gedrag in het vak [!UICONTROL Move Task] of [!UICONTROL Move Issue] . Vóór deze verbetering zijn de documenten definitief verwijderd.

**Hiding van een punt verbergt het onjuiste punt**

*malplaatjes van de Lay-out*

Wanneer een gebruiker wijzigt of een item verborgen of weergegeven is, worden deze wijzigingen doorgevoerd in een ander item in de lay-outsjabloon.


+++

+++**Update van het Onderhoud op 10 November, 2022**

**Bulk die taken uitgeeft verandert taaktaken**

*Taken*

Wanneer een gebruikersbulk om het even welk gebied voor een reeks taken uitgeeft, worden de Taken van de eerste taak toegepast op alle taken. Hierdoor worden vorige toewijzingen verwijderd.

**kan geen interactieve proef** openen

*Workfront Proof*

Wanneer een gebruiker een interactieve proef probeert te openen, opent de proef niet en de gebruiker ziet het volgende bericht:

&quot;[!UICONTROL Proof not loaded (501) Try again]&quot;

+++

+++**Update van het Onderhoud (Hete Fix) op 4 November, 2022**

**Kwesties met taken die aan een herhaling** worden toegevoegd

*Gelijk*

De volgende problemen zijn gemeld met betrekking tot kwesties die aan een herhaling zijn toegevoegd:

* Sommige subtaken van een taak die aan een herhaling is toegevoegd, worden niet weergegeven op de pagina [!UICONTROL Iteration] .
* Wanneer een gebruiker een ontbrekende taak aan de herhaling probeert toe te voegen, wordt de taak niet toegevoegd en ziet de gebruiker het volgende bericht:

  &quot;[!UICONTROL The following error occurred: None of the selected items could be moved, because they are not assigned to an agile team or are not agile items]&quot;

**Taken die door bulk het uitgeven worden toegewezen verschijnen niet op de achterstand van het team**

*Gelijk*

Wanneer een gebruiker taken toewijst aan een team van het Trommel door bulkhet uitgeven te gebruiken, verschijnen die taken niet op de achterstand van het team.

Deze kwestie heeft geen gevolgen voor Kanbanteams.

**&quot;[!UICONTROL New proof recipients]&quot;tekstvakje is te klein**

*Proofs*

Wanneer een gebruiker een proef bekijkt en probeert om de proef van het [!UICONTROL Sharing] lusje te delen, is het &quot;[!UICONTROL New proof reciepients]&quot;tekstvakje zeer klein. De gebruiker kan een naam typen, maar omdat het vak zo klein is, loopt de tekst om op een manier die moeilijk leesbaar is.

**het gebruiksinformatie van het Rapport niet** bijwerkt

*Rapporten*

Wanneer een gebruiker een rapport weergeeft, wordt de informatie bij Laatst weergegeven, zoals de datum van laatste weergave en Laatst weergegeven door, niet bijgewerkt. Dit betekent dat eventuele gebruiksinformatie mogelijk onjuist is.

Dit gedrag is gemeld wanneer de gebruiker tot het rapport op de volgende manieren toegang heeft:

* Zoeken
* Punten
* Favorieten
* Recenten

Als u rapporten opent via een dashboard, worden de gegevens in de laatste weergave bijgewerkt.

**[!DNL Workfront]: 500 fout wanneer het aanbrengen van veranderingen in [!DNL Workfront] voorwerp**+

*[!DNL Workfront]*

Wanneer een gebruiker wijzigingen in een [!DNL Workfront] -object probeert aan te brengen, worden de wijzigingen niet opgeslagen en ziet de gebruiker de volgende fout:

&quot;[!UICONTROL 500: Database error due to invalid SQL statement.]&quot;

Dit is gemeld in de volgende situaties:

* De status van een object wijzigen
* Tijdlijnen opnieuw berekenen
* Een sjabloon koppelen
* Registratietijd

+++

+++**[!DNL Workfront Fusion]Onderhoudsupdate op 3 november 2022**

**Fout betreffende [!UICONTROL apiKey] in [!DNL Workfront] > [!UICONTROL Watch Events] module**

*[!DNL Workfront Fusion]*

Wanneer een gebruiker een webhaak probeert toe te voegen aan de module [!DNL Workfront] > [!UICONTROL Watch Events] , wordt de volgende fout gegenereerd:

&quot;[!UICONTROL The apiKey provided was empty or deemed invalid.]&quot;

+++

+++**Update van het Onderhoud op 3 November, 2022**

**noem het &quot;Programma&quot;en &quot;Plannend&quot;secties voor teams en projecten in het lay-outmalplaatje**

*malplaatjes van de Lay-out*

De tabbladen &quot;Planning&quot; en &quot;Planning&quot; die beschikbaar zijn om in een lay-outsjabloon aan het linkerdeelvenster van een team of project toe te voegen, hebben de naam &quot;Werklastbalans&quot; gewijzigd.

**Fouten wanneer de toegang tot van e-mailbericht montages**

*Meldingen*

>[!NOTE]
>
>Dit probleem doet zich zowel voor in de productieomgeving als in de voorbeeldomgeving.

Wanneer een gebruiker de instellingen voor e-mailmeldingen probeert te wijzigen, wordt mogelijk een van de volgende fouten weergegeven:

* &quot;[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

* &quot;[!UICONTROL Failed to fetch email notification]&quot;

Dit is gemeld op de volgende gebieden:

* [!UICONTROL Setup] > [!UICONTROL Email notifications]
* [!UICONTROL User] > [!UICONTROL Edit user]
* [!UICONTROL Groups]

**Nieuwe informatiepictogrammen voor timesheets, timesheet profielen, en timesheet voorkeur**

*Workfront*

>[!NOTE]
>
>Deze update wordt alleen vrijgegeven voor de voorvertoningsomgeving. De licentie wordt vrijgegeven aan Production met de release van 23.1.

Er zijn verschillende informatiepictogrammen toegevoegd aan de volgende instellingen:

* &quot;Kan tijd&quot;checkbox uitgeven wanneer het creëren van of het uitgeven van een timesheet of een timesheet profiel om erop te wijzen dat wanneer toegelaten, de fiatteurs ook kunnen voorleggen, opnieuw openen, of uitgeven timesheet, tenzij uw beheerder deze acties in het gebied van de Voorkeur van de Chronologie van Opstelling beperkt.
* &quot;Beperk timesheet uitgeven tot eigenaars en beheerders&quot;in het gebied van de Voorkeur van de Tijdopmaak &amp; van het Uur van Opstelling om erop te wijzen dat wanneer gehandicapt, de volgende gebruikers ook timesheets kunnen uitgeven: gebruikers met administratieve toegang tot timesheets en uren, timeesheet fiatteurs toegestaan om tijd uit te geven, en de managers van timesheet eigenaars.

De functionaliteit van deze instellingen is niet gewijzigd en alleen de informatiepictogrammen zijn toegevoegd om het bereik van de instellingen helderder te maken.

+++

## Updates in oktober 2022

+++**Update van het Onderhoud op 27 oktober, 2022**

**[!UICONTROL HOUR]functie in berekende velden gebruikt UTC**

*de vormen van de Douane*

Wanneer een berekend veld de functie [!UICONTROL HOUR] bevat, retourneert de functie waarden die zijn gebaseerd op UTC in plaats van op de verwachte tijdzone. Daarom zijn berekeningen op basis van de UUR-waarde onjuist.

**[!UICONTROL Quick filter]retourneert geen resultaten bij het zoeken naar teams**

*Lijsten*

Wanneer een gebruiker [!UICONTROL Quick filter] in een lijst probeert te gebruiken om naar een team te zoeken, keert het ingaan van de naam van het team geen resultaten terug, zelfs wanneer het team in de lijst (zoals in het [!UICONTROL Assigned to] gebied) zichtbaar is. Het zoeken naar het woord &quot;[!UICONTROL team]&quot;keert ook geen resultaten terug.

**kan een pagina re-speld niet nadat zijn speld wordt verwijderd**

*Navigatie*

>[!NOTE]
>
>Dit probleem is opgelost in Voorvertoning op 13 oktober 2022. Het werd vastgesteld in Production op 27 oktober 2022.

Wanneer een gebruiker &quot;[!UICONTROL Remove pin]&quot;optie op een speld selecteert, een bericht over de verwijdering ontvangt, en probeert om het speld te vervangen door &quot;[!UICONTROL Undo]&quot;in het bericht te klikken, wordt het speld niet vervangen in de hoogste navigatie, noch wordt het toegevoegd aan de lijst van spelden onder de [!UICONTROL More pins] lijst (het drie puntenmenu in het [!UICONTROL Pins] gebied).

Als een gebruiker de pagina opnieuw vastzet door naar de pagina te gaan en deze vast te zetten, wordt het punt niet gemaakt en kan de gebruiker de pagina niet vastzetten.

**Alle gebruikers die in [!UICONTROL Workload Balancer] worden vermeld wanneer het gebruiken van een shareable verbinding in [!DNL Safari] browser**

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker een deelbare koppeling naar de [!UICONTROL Workload Balancer] volgt terwijl hij een [!DNL Safari] -browser gebruikt, zien hij alle gebruikers in plaats van alleen de vermelde teamleden.

+++

+++**Update van het Onderhoud op 20 oktober, 2022**

**Fout wanneer bulk die een team toewijst**

*Taken*

Wanneer een gebruiker in bulk bewerkingstaken of kwesties is en een team toewijst na het toewijzen van een individu, slaan de toewijzingen niet op en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Let's try that again - The following error occurred: teamAssignments must be either a list of objects or a list of IDs]&quot;

**&quot;[!UICONTROL Failed to upload file] &quot;fout**

*Documenten*

Wanneer een gebruiker een bestand probeert te uploaden naar het [!UICONTROL Documents] -gebied, wordt het bestand niet geüpload en ziet de gebruiker de fout &quot;[!UICONTROL Failed to upload file]&quot;.

Dit is gemeld bij pogingen om MP4-bestanden te uploaden.

**de telling van de kwestie in linkernavigatie van taak is onjuist**

*Kwesties*

Wanneer een gebruiker een taak weergeeft, geeft het nummer dat in de sectie [!UICONTROL Issues] van de linkernavigatie wordt weergegeven, niet exact het werkelijke aantal problemen weer dat aan de taak is gekoppeld.


**[!UICONTROL Predecessor]pictogram ontbreekt in taakkopbal**

*Taken*

Wanneer een gebruiker een taak bekijkt, ontbreekt het taakvoorgangerpictogram in de koptekst.

+++

+++**Update van het Onderhoud op 13 oktober, 2022**

**kan een pagina re-speld niet nadat zijn speld wordt verwijderd**

*Navigatie*

>[!NOTE]
>
>Dit probleem wordt opgelost in Voorvertoning op 13 oktober 2022. Het zal op 27 oktober 2022 in productie worden vastgesteld.

Wanneer een gebruiker &quot;[!UICONTROL Remove pin]&quot;optie op een speld selecteert, een bericht over de verwijdering ontvangt, en probeert om het speld te vervangen door &quot;[!UICONTROL Undo]&quot;in het bericht te klikken, wordt het speld niet vervangen in de hoogste navigatie, noch wordt het toegevoegd aan de lijst van spelden onder de [!UICONTROL More pins] lijst (het drie puntenmenu in het [!UICONTROL Pins] gebied).

Als een gebruiker de pagina opnieuw vastzet door naar de pagina te gaan en deze vast te zetten, wordt het punt niet gemaakt en kan de gebruiker de pagina niet vastzetten.

**kan nieuwe filters** niet noemen of bewaren

*[!UICONTROL Resource Planner]*

Wanneer een gebruiker een nieuwe filter een naam probeert te geven in [!UICONTROL Resource Planner] , blijft het naamvak leeg. Als de gebruiker op de spatiebalk heeft gedrukt, schakelt u de knop [!UICONTROL Save] uit.

**kan naam of percenten uitgeven volledig van een taak of een kwestie**

*Taken en kwesties*

Gebruikers met [!UICONTROL Contribute] toegang tot een taak of uitgave kunnen de naam van de taak of uitgave in de koptekst niet bewerken. Bovendien kunnen gebruikers met [!UICONTROL Contribute] toegang het percentage van voltooiing van een taak of kwestie niet uitgeven.

**De aanvragers en de Recensenten tellen naar de licentietelling van een organisatie**

*[!DNL Workfront Proof]*

Wanneer een gebruiker aan een proef als Recensent of een Aanvrager wordt toegevoegd, krijgen zij &quot;[!UICONTROL Visitor]&quot;toestemmingenprofiel, dat geen [!DNL Workfront Proof] vergunning zou moeten gebruiken. Wanneer de gebruiker echter wordt toegevoegd, neemt het aantal gebruikte [!DNL Workfront Proof] -licenties toe.

+++

+++**update van het Onderhoud op 11 Oktober, 2022**

**kan een pagina re-speld niet nadat zijn speld wordt verwijderd**

*Navigatie*

>[!NOTE]
>
>Dit probleem is opgelost in Voorvertoning op 13 oktober 2022. Het zal op 27 oktober 2022 in productie worden vastgesteld.

Wanneer een gebruiker &quot;[!UICONTROL Remove pin]&quot;optie op een speld selecteert, een bericht over de verwijdering ontvangt, en probeert om het speld te vervangen door &quot;[!UICONTROL Undo]&quot;in het bericht te klikken, wordt het speld niet vervangen in de hoogste navigatie, noch wordt het toegevoegd aan de lijst van spelden onder de [!UICONTROL More pins] lijst (het drie puntenmenu in het [!UICONTROL Pins] gebied).

Als een gebruiker de pagina opnieuw vastzet door naar de pagina te gaan en deze vast te zetten, wordt het punt niet gemaakt en kan de gebruiker de pagina niet vastzetten.

+++

+++**Update van het Onderhoud op 6 Oktober, 2022**

**Nieuw blauwdruktype**

*Blauwdrukken*

Het blauwdruktype &#39;Dashboard&#39; is toegevoegd aan de catalogus met blauwdrukken. Eerder waren alleen blauwdrukken voor projectsjablonen en organisatiestructuur beschikbaar.

**Elementen die in linkerpaneel overlappen**

*de vormen van de Douane*

Wanneer een gebruiker in de formulierbuilder werkt en het formulier meer dan 100 velden bevat, overlappen elementen in het linkerdeelvenster in het bericht dat de gebruiker op de hoogte wordt gebracht van de veldlimiet.

**de plukker van de Datum opent automatisch niet meer op inputnadruk of klikt**

*Navigatie*

Wanneer een gebruiker met het toetsenbord navigeert, worden de datumkiezers niet meer automatisch geopend bij de datum waarop de toetsenbordfocus wordt ontvangen. In plaats daarvan moeten toetsenbordgebruikers met de Tab-toets naar het pictogram van de datumkiezer gaan en op Enter drukken om de datumkiezer te openen. Wanneer een gebruiker met de muis navigeert, worden de datumkiezers niet meer automatisch geopend wanneer op de datuminvoer wordt geklikt. In plaats daarvan moeten muisgebruikers op het pictogram van de datumkiezer klikken om de datumkiezer te openen.

Deze wijziging is aangebracht om beter te voldoen aan de UX-patronen van de standaarddatumkiezer en om een toegankelijkere ervaring te creëren voor gebruikers van toetsenbord en schermlezers.

**Toewijzend veelvoudige toegewezen teamresultaten in slechts één toegewezen team**

*Teams*

>[!NOTE]
>
>Dit probleem doet zich alleen voor in de voorvertoningsomgeving.

Wanneer een gebruiker meerdere teams toewijst aan een taak of uitgave, wordt slechts één team weergegeven in de toewijzingslijst. Dit probleem heeft ook invloed op de rapportage. Rapporten waarin teamtoewijzingen worden weergegeven, zijn onjuist omdat slechts één team wordt weergegeven als toegewezen aan de taak of uitgave.

**&quot;[!UICONTROL Your recent changes were not saved]&quot;fout wanneer het autosaving veranderingen op een timesheet**

*Timesheets*

Wanneer een gebruiker probeert om een timesheet op een manier uit te geven die autosave zou teweegbrengen worden de veranderingen niet bewaard en de gebruiker ziet het volgende bericht:

&quot;[!UICONTROL Your recent changes were not saved. Refresh the page to view.]&quot;

Dit is gemeld bij het bewerken van het volgende:

* Uren
* Taken

**E-mailberichten worden vertraagd**

*Workfront Proof*

Wanneer een gebeurtenis plaatsvindt in [!DNL Workfront Proof] die een e-mailmelding activeert, ontvangt de gebruiker het bericht niet onmiddellijk. De kennisgeving kan enkele uren worden uitgesteld.

+++

+++**Update van het Onderhoud op 3 Oktober, 2022**

**sparen manueel uw timesheet wanneer de vorige baanrollen** zijn veranderd

*Timesheets*

Als een taakrol waarvoor u tijd hebt geregistreerd is gewijzigd en de instelling [!UICONTROL Assign job roles to hour entries manually] is uitgeschakeld, moet u uw tijdinvoer handmatig opslaan totdat de uren niet meer zijn geregistreerd voor de gewijzigde taakrol.

+++

## Updates in september 2022

+++**Update van het Onderhoud op 29 September, 2022**

**de Gebruiker keert niet aan vorige pagina terug wanneer het sluiten van proef**

*Proofs*

Wanneer een gebruiker die een proef weergeeft binnen [!DNL Workfront] de proef sluit, keren zij niet de pagina terug zij waren alvorens zij de proef opende. In plaats daarvan worden ze doorgestuurd naar een andere pagina in [!DNL Workfront] .

**Kan proef niet openen in[!DNL Workfront]**

*Proofs*

Wanneer een gebruiker een document weergeeft in [!DNL Workfront] en de proefdruk probeert te openen, wordt de proefdruk niet geopend en wordt de gebruiker teruggestuurd naar de [!UICONTROL Document Details] -pagina.

**Uren sparen niet wanneer het gebruiken van [!UICONTROL Tab] sleutel**

*Timesheets*

Wanneer een gebruiker een tijdblad invult en met de toets [!UICONTROL Tab] tussen cellen navigeert, worden de uren niet opgeslagen. De melding [!UICONTROL Auto-save] wordt niet onder in het scherm weergegeven en als de gebruiker de pagina vernieuwt, ziet hij of zij dat de uren niet zijn opgeslagen.

**Lege pagina&#39;s wanneer het bekijken van een proef met veelvoudige pagina&#39;s**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een proefdruk op meerdere pagina&#39;s weergeeft, kan de gebruiker miniaturen van de pagina&#39;s zien, maar worden de pagina&#39;s niet geopend in de hoofdviewer.



+++

+++**Update van het Onderhoud op 22 September, 2022**

**kan gebruikerskaart in updatestroom niet sluiten**

*Updates*

Wanneer een gebruiker updates weergeeft en deze boven een naam plaatst, wordt een kaart met gegevens over de gebruiker wiens naam wordt geopend en wordt deze niet automatisch gesloten. De pagina reageert pas als de kaart handmatig wordt gesloten door op de X in de rechterbovenhoek te klikken.

+++

+++**Update van het Onderhoud op 15 September, 2022**

**&quot;[!UICONTROL Someone else tried to save this project]&quot;fout wanneer het ingaan van uren**

*Timesheets*

Wanneer een gebruiker uren aan een taak op hun timesheet probeert te registreren, autosave niet, en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL We're sorry, but your save failed because someone else tried to save this project at the same time. Please try to save again.]&quot;

**kan gebruikerskaart in updatestroom niet sluiten**

*Updates*

Wanneer een gebruiker updates weergeeft en deze boven een naam plaatst, wordt een kaart met gegevens over de gebruiker wiens naam wordt geopend en wordt deze niet automatisch gesloten. De pagina reageert pas als de kaart handmatig wordt gesloten door op de X in de rechterbovenhoek te klikken.

**het &quot;[!UICONTROL Task role assignment]&quot;gebied is anders genoemd aan &quot;[!UICONTROL Role assignment]&quot;wanneer het toewijzen van werk in bulk gebruikend[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

Om op de nieuwe functionaliteit te wijzen van het kunnen zowel taken als kwesties in bulk van het [!UICONTROL Unassigned Work] gebied toewijzen, hebben wij genoemd het &quot;[!UICONTROL Task role assignment]&quot;gebied aan &quot;[!UICONTROL Role assignment]&quot;in [!UICONTROL Workload Balancer] anders genoemd. Het veld verwijst naar taakrollen die zijn toegewezen aan taken of uitgaven en het wordt weergegeven wanneer gebruikers worden toegewezen aan items in het vak [!UICONTROL Bulk Assignments] .

+++

+++**[!DNL Workfront Scenario Planner]Onderhoudsupdate op 15 september 2022**

**filter dat met een Groep wordt gedeeld toont nu in de [!DNL Scenario Planner] [!UICONTROL Import Projects] lijst van 1&rbrace; &lbrace;voor leden van alle Subgroups**

*[!DNL Workfront Scenario Planner]*

Wanneer u nu een projectfilter deelt met een groep die aanvullende subgroepen heeft, is het filter zichtbaar voor alle groep- en subgroepsleden die projecten weergeven in het vak [!UICONTROL Import Projects] van een plan in [!DNL Scenario Planner] .

+++

+++**Update van het Onderhoud op 8 September, 2022**

**Bijgewerkte namen die voor gebruiker en rol-taak gebieden** worden teruggedraaid

*Taken*

De toewijzingsvelden waarvan de naam vorige week tijdelijk is gewijzigd, zijn teruggezet naar de oorspronkelijke naam:

* [!UICONTROL Assignment Users]
* [!UICONTROL Assignment Roles]

**Fout wanneer het verwijderen van de Eigenaar van het Project uit de kopbal**

*Projecten*

Wanneer een gebruiker een [!UICONTROL Project Owner] probeert te verwijderen uit de koptekst van een project, wordt [!UICONTROL Project Owner] niet verwijderd en ziet de gebruiker het volgende foutbericht:

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**Resized [!UICONTROL Description] doos gaat terug naar originele grootte**

*Projecten, taken, en kwesties*

Wanneer een gebruiker de grootte van het vak [!UICONTROL Description] wijzigt in het detailgebied van een tijdelijk item om het item groter te maken en vervolgens in het vak begint te typen, wordt de oorspronkelijke grootte van het vak hersteld. De gebruiker kan nog steeds in het vak typen en de inhoud opslaan zoals verwacht

**Onbedoelde uitgang wanneer het creëren van taken of kwesties**

*Taken en kwesties*

Wanneer een gebruiker een taak of kwestie in een project creeert en buiten de verwezenlijking pop-up klikt, sluit pop-up zonder waarschuwing en alle eerder ingegaan informatie wordt verloren.

**Verwijderde capaciteit om een proef aan dropzone** te e-mailen

*[!DNL Workfront Proof]*

Vanaf donderdag 8 september 2022 hebben we de mogelijkheid om een bewijs te verzenden naar een dropzone in het standalone [!DNL Workfront Proof] product verwijderd.

U kunt dropzones nog steeds op andere manieren gebruiken om nieuwe proefdrukken en nieuwe versies van proefdrukken naar uw account te verzenden zonder u aan te hoeven melden bij uw account. Zie [&#x200B; Dropzone &#x200B;](https://experienceleague.adobe.com/docs/workfront/using/workfront-proof/work-with-proofs-in-wf-proof/create-proofs-and-files/dropzone.html?lang=nl-NL) voor meer informatie.

+++

+++**Update van het Onderhoud op 6 September, 2022**

**Geprojecteerde die data aan de lijst van gebieden voor klantgerichte projectkopballen worden toegevoegd**

*Projecten*

De kolommen [!UICONTROL Projected Start Date] en [!UICONTROL Projected Completion Date] zijn toegevoegd aan de lijst met velden voor aanpasbare projectheaders wanneer een lay-outsjabloon wordt gebruikt.

**Nieuwe grens met een bevestigingsbericht dat het aantal punten toont die aan een timesheet** worden toegevoegd

*Timesheets*

Wanneer u meer dan 50 punten selecteert om aan een timesheet toe te voegen, ontvangt u nu een bevestigingsbericht dat het aantal punten toont dat aan timesheet moet worden toegevoegd en u de kans geeft om cursus te veranderen en niet alle punten toe te voegen. Alle toegevoegde punten worden automatisch vastgezet aan timesheet en zullen manueel uit huidige en alle toekomstige chronologie moeten worden verwijderd.

+++

+++**Update van het Onderhoud op 2 September, 2022**

Voeg het veld [!UICONTROL Integrations] toe aan de aangepaste koptekst van het project

*Integraties*

U kunt nu het veld [!UICONTROL Integrations] toevoegen aan de aangepaste koptekst van een project wanneer u een lay-outsjabloon gebruikt. Nadat het veld is toegevoegd, wordt een koppeling weergegeven naar een extern item dat is gekoppeld aan het project in [!DNL Salesforce] of [!DNL Anaplan] , afhankelijk van uw integratie.

>[!NOTE]
>
>Deze onderhoudsupdate is eerder op 25 augustus 2022 uitgebracht naar de voorvertoningsomgeving en is nu in productie.

+++

+++**Update van het Onderhoud op 1 September, 2022**

**Voltooide punten die van delegatie worden verwijderd**

*Delegaties*

Nu worden alleen onvolledige items waarvan de data overeenkomen met de data van een delegatie gedelegeerd aan andere gebruikers wanneer de delegatie van werkitems begint. Als de punten vóór de delegatie begonnen werden voltooid, zullen zij niet worden afgevaardigd. De punten die tijdens het tijdkader van de delegatie worden voltooid zullen op de Lijst van het Werk van het gebied van het Huis voor zowel de afgevaardigde als de aangewezen persoon twee weken blijven alvorens zij automatisch worden verwijderd, als de delegatie niet tijdens deze weken heeft geëindigd.

**updates van Meta-gegevens voor [!DNL Adobe Workfront] voor [!DNL Experience Manager Assets] en [!DNL Assets Essentials] integraties**

*Integraties*

Metagegevens worden automatisch geactiveerd wanneer u middelen aan een gekoppelde map toevoegt.

Eerder werden metagegevens alleen &#39;push&#39; weergegeven wanneer u een element toevoegde via de vervolgkeuzelijst [!UICONTROL Add new] .

**kan uren op een kwestie goedkeuren of verwerpen**

*Kwesties*

Wanneer een gebruiker uren op het tabblad [!UICONTROL Hours] van een uitgave probeert goed te keuren of af te wijzen, ontbreken de knoppen [!UICONTROL Approve] en [!UICONTROL Reject] .

**Converterend een kwestie aan een project gebruikend een malplaatje toont een onjuist foutenmelding**

*Kwesties*

Wanneer het omzetten van een kwestie in een project gebruikend een malplaatje en een fout wordt ontmoet, wordt de gebruiker getoond een pagina met het bericht &quot;[!UICONTROL The Project no longer exists]&quot;in plaats van het correcte foutenbericht dat de oorzaak van de ontbroken omzetting verklaart.

**kan geen proef voor dossiers tot stand brengen meer dan 1.5GB**

*[!DNL Workfront Proof]*

Als een gebruiker bij het maken van een nieuwe proefdruk een bestand uploadt dat groter is dan 1,5 GB, wordt de bestandsnaam rood en kan de proefdruk niet worden gemaakt.

+++

## Updates in augustus 2022

+++**Update van het Onderhoud op 25 augustus, 2022**

**de verbindingsvertoning van de Balancer van de Werkbelasting verkeerd in dashboards**

*Dashboards*

Koppelingen voor werklastverdeling worden onjuist weergegeven wanneer ze als externe pagina aan een dashboard worden toegevoegd. In plaats van de unieke weergave of filters te gebruiken die aan de koppeling zijn gekoppeld, gebruikt het dashboard de laatst toegepaste weergave of filters voor werklastbalans.

**voeg het [!UICONTROL Integrations] gebied aan de kopbal van de projectdouane** toe

*Projecten*

U kunt nu het veld [!UICONTROL Integrations] toevoegen aan de aangepaste koptekst van een project wanneer u een lay-outsjabloon gebruikt. Nadat het veld is toegevoegd, wordt een koppeling weergegeven naar een extern item dat is gekoppeld aan het project in [!DNL Salesforce] of [!DNL Anaplan] , afhankelijk van uw integratie.

>[!NOTE]
>
>Deze onderhoudsupdate is momenteel alleen beschikbaar in de voorvertoningsomgeving. Deze wordt een week na de release Preview vrijgegeven voor Production.

**de gegevens van de Douane worden niet bewaard wanneer het omzetten van een kwestie in een leeg project**

*Projecten*

Wanneer een gebruiker een kwestie in een leeg project (zonder een malplaatje) omzet, worden de gegevens op berekende gebieden niet overgebracht naar het nieuwe project.

**&quot;De wijze van de Planning van de Chronologie&quot;fout wanneer het veranderen van een datum op een project**

*Projecten*

Wanneer een gebruiker een datum probeert te wijzigen in een project waarvoor [!UICONTROL Plan Mode] is ingesteld op [!UICONTROL Manual save] > [!UICONTROL Timeline Planning] , verandert de datum niet en ziet de gebruiker een fout.

&quot;[!UICONTROL Timeline Planning mode is available only when timelineDate is loaded. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

**Consistentie wanneer het openen van de Balancer van de Werkbelasting gebruikend de mening van de Maand**

*de Balancer van de Werkbelasting*

In Workload Balancer worden nu de door gebruikers toegewezen items weergegeven die zijn uitgevouwen wanneer deze worden weergegeven in de weergaven [!UICONTROL Day] , [!UICONTROL Week] of [!UICONTROL Month] . Vóór deze update werden de toegewezen items weergegeven als uitgevouwen voor de weergaven [!UICONTROL Day] en [!UICONTROL Week] en samengevouwen voor de weergave [!UICONTROL Month] .


+++

+++**Update van het Onderhoud op 18 augustus, 2022**

**&quot;[!UICONTROL Add to Iteration]&quot; en &quot;[!UICONTROL Add to Kanban Board]&quot;opties niet beschikbaar wanneer het inline uitgeven taken in een rapport**

*Rapporten*

Wanneer een gebruiker een lijst van taken in een rapport bekijkt en [!UICONTROL More] (drie punten) menu opent, zijn &quot;[!UICONTROL Add to Iteration]&quot;en &quot;[!UICONTROL Add to Kanban Board]&quot;opties niet beschikbaar in dropdown. Als het rapport in een dashboard wordt bekeken, zijn &quot;[!UICONTROL Add to Iteration]&quot;en &quot;[!UICONTROL Add to Kanban Board]&quot;opties beschikbaar in dropdown.

**de rapporten van de Matrijs tonen verkeerd wanneer het scrollen**

*Rapporten*

Wanneer een gebruiker een rapport van de Matrijs bekijkt en scrolt, kunnen sommige visuele elementen van het rapport overlappen of dupliceren.

**[!UICONTROL Milestone]weergave verwijderd uit de projectlijst Timesheets**

*Timesheets*

De weergave [!UICONTROL Milestone] is verwijderd uit de lijst met tijdlijnprojecten wanneer u een project toevoegt.

**de Hyperlinks in een interactief bewijs zijn niet actief**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een interactieve proef bekijkt en op een verbinding of een knoop klikt die een verbinding bevat, wordt de gebruiker niet genomen aan de pagina die de verbinding of de knoop verbindt met.

**Nieuwe Pagina van het Bewijs ontbrekende Gebieden van de Tekst**

*[!DNL Workfront Proof]*

Op de pagina [!DNL New Proof] worden veel tekstvelden niet weergegeven (zoals veldlabels, vervolgkeuzemogelijkheden en namen van selectievakjes).

**de Gebruikers ontvangen geen berichten wanneer geëtiketteerd in een proef**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een proefdrukopmerking heeft geplaatst, ontvangt hij geen e-mailbericht over de opmerking.

+++

+++**Update van het Onderhoud op 12 augustus, 2022**

**Nieuw aanpasbaar kopbalgebied dat aan het begin van de kopbal** wordt toegevoegd

*Kopballen*

Wanneer u een nieuw veld toevoegt aan een aanpasbare koptekst, wordt het veld nu toegevoegd als het eerste veld links in de koptekst of direct na het vak [!UICONTROL Search] in de Indelingssjabloon. Vóór deze wijziging is het veld toegevoegd als het laatste veld in de koptekst.

+++

+++**Update van het Onderhoud op 11 augustus, 2022**

**kan douaneformulieren wegens onjuiste karaktergrens op Beschrijvende tekstgebieden uitgeven**

*de vormen van de Douane*

Wanneer een gebruiker een aangepast formulier probeert te bewerken en dat aangepaste formulier een [!UICONTROL Descriptive text] -veld heeft dat momenteel meer dan 512 tekens bevat, kan de gebruiker de bewerkingen niet opslaan in het aangepaste formulier. De volgende fout wordt weergegeven:

&quot;De volgende velden zijn ongeldig: (Veld) is te lang, max. 512&quot;

Dit is van toepassing op [!UICONTROL Descriptive text] -velden die eerder goed hebben gewerkt, hoewel ze meer dan 512 tekens bevatten.

**Gegevens op gebieden die door sectieonderbreking worden verborgen wordt niet bewaard wanneer het omzetten van een kwestie in een project**

*de vormen van de Douane*

Wanneer een gebruiker een uitgave in een project omzet, en de kwestie omvat een douaneformulier met gegevens in een sectieonderbreking die kan worden verborgen gebruikend vertoningslogica, worden de gegevens in die sectie niet gedragen aan het nieuwe project.

**Gegevens op gebieden die door sectieonderbreking worden verborgen wordt niet bewaard wanneer het omzetten van een verzoek in een project**

*de vormen van de Douane*

Wanneer een gebruiker een verzoek in een project omzet, en het verzoek een douaneformulier met gegevens in een sectieonderbreking omvat die kunnen worden verborgen gebruikend vertoningslogica, worden de gegevens in die sectie niet gedragen aan het nieuwe project.

**kan douaneformulieren wegens het Omschrijvende gebied van de Tekst niet uitgeven**

*de vormen van de Douane*

Wanneer een gebruiker een aangepast formulier probeert te bewerken dat een beschrijvend tekstveld bevat, wordt het label van het veld niet gevuld. De gebruiker ziet de fout &quot;[!UICONTROL This field is required]&quot;onder het etiketgebied, en de gebruiker kan niet het douaneformulier wegens deze fout uitgeven.

**kan instructies uit een douanegebied in de bouwer van de douanevorm niet verwijderen**

*de vormen van de Douane*

Wanneer een gebruiker een aangepast veld bewerkt en probeert bestaande tekst in het [!UICONTROL Instructions] -gebied te verwijderen, wordt de tekst niet verwijderd wanneer het veld wordt opgeslagen. De gebruiker kan tekst bewerken, maar niet geheel verwijderen.

**de taak van het Team wanneer het creëren van verzoek verschijnt niet op nieuw verzoek**

*Verzoeken*

Wanneer een gebruiker een verzoek creeert en een team aan het verzoek toewijst, dan legt het verzoek voor, wordt het team niet toegewezen aan het verzoek dat wordt gecreeerd. Dit is alleen van invloed op teamtoewijzing. De toewijzingsfunctie van de gebruiker functioneert naar behoren.

+++

+++**Update van het Onderhoud op 4 augustus, 2022**

Deze problemen zijn alleen opgelost in de nieuwe [!DNL Workfront] -ervaring.

Alle [!DNL Workfront Classic] -functionaliteit is verwijderd op 14 juli 2022.

**Fout wanneer het veranderen van de Geplande Datum van de Voltooiing in de kopbal van een taak of kwestie**

*Taken en Kwesties*

Wanneer een gebruiker probeert de [!UICONTROL Planned Completion Date] in de koptekst van een taak of uitgave te wijzigen, verandert de datum niet en ziet de gebruiker een fout die vergelijkbaar is met de volgende:

`500: (Date that user is attempting to change to)/attask/api-internal/(object type)/(object ID)`

+++

## Updates in juli 2022

+++**Update van het Onderhoud op 28 juli, 2022**

Deze problemen zijn alleen opgelost in de nieuwe [!DNL Workfront] -ervaring.

Alle [!DNL Workfront Classic] -functionaliteit is verwijderd op 14 juli 2022.

**Fout wanneer het openen van een punt van[!UICONTROL Home Work List]**

*[!UICONTROL Home]*

Wanneer een gebruiker een item op zijn [!UICONTROL Home Work List] probeert te openen, wordt het item niet geopend en ziet de gebruiker het volgende bericht:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work try refreshing this browser page.]&quot;

**Taken en kwesties die aan een gebruiker worden gedelegeerd verschijnen niet in de Lijst van het Werk van het Huis van de gebruiker**

*[!UICONTROL Home]*

Wanneer de gebruiker hun [!UICONTROL Home Work List] bekijkt, verschijnen om het even welke die taken of kwesties aan de gebruiker worden gedelegeerd niet in de lijst, en de gebruiker kan niet op de hoogte zijn van de delegaties.

**Geplande rapporten worden niet verzonden naar alle ontvangers**

*Rapporten*

Wanneer een gepland rapport wordt verzonden, wordt het niet verzonden naar alle gebruikers in &quot;[!UICONTROL Send to]&quot;sectie. De weggelaten gebruikers zijn willekeurig, en kunnen variëren telkens als het rapport wordt verzonden.

**[!UICONTROL Cannot deselect tasks when attaching template]**

*Malplaatjes*

Wanneer een gebruiker een sjabloon koppelt en aanpast, wordt hem gevraagd de selectie op te heffen van taken die hij of zij niet wil opnemen. Geen van de taken wordt echter weergegeven als geselecteerd en de gebruiker kan de selectie ervan niet opheffen.

**&quot;Landinstelling&quot;-velden hebben nu specifiekere labels**

*Terminologie*

Om de functie van &quot;[!UICONTROL Locale]&quot;gebieden duidelijker te maken, hebben wij hun etiketten bijgewerkt.

* Het veld &quot;[!UICONTROL Locale]&quot; in het gebruikersprofiel heeft nu het label &quot;[!UICONTROL Email Locale]&quot;
* Het veld &quot;[!UICONTROL Locale]&quot; in het gebied [!UICONTROL Setup] > [!UICONTROL System] > [!UICONTROL Customer Info] wordt nu gelabeld &quot;[!UICONTROL Default Email Locale]&quot;

De functionaliteit van deze velden is niet gewijzigd.

**Kwesties wanneer het creëren van timesheets**

*Timesheets*

De volgende kwesties zijn gemeld met betrekking tot het opstellen van tijdbladen:

* Wanneer een gebruiker probeert om een timesheet voor een Rol tot stand te brengen, wordt timesheet niet gecreeerd en de gebruiker ziet de fout &quot;[!UICONTROL User with primary key values 'XXXXXXXXXXX' not found.]&quot;
* Wanneer een gebruiker een tijdspagina voor een team probeert te maken, wordt het veld [!UICONTROL typeahead] niet gevuld met teams en wordt de knop [!UICONTROL Create timesheet] uitgeschakeld.


**Gebieden van [!DNL Workfront Proof] werken niet bij wanneer een proef wordt gecreeerd, bewogen of gearchiveerd**

*[!DNL Workfront]Proef*

Het bewijs ervaart momenteel indexerende vertragingen. Dit kan van invloed zijn op de gebruikerservaring, waaronder:

* Het juiste aantal proefdrukken wordt niet weergegeven op dashboards
* Mappen worden niet bijgewerkt wanneer een proefdruk wordt gemaakt of verplaatst
* Gearchiveerde proefdrukken blijven op actieve proefdruklijsten.

+++

+++**update van het Onderhoud (Hete Fix) op 26 Juli, 2022**

Deze problemen zijn alleen opgelost in de nieuwe [!DNL Workfront] -ervaring.

Alle [!DNL Workfront Classic] -functionaliteit is verwijderd op 14 juli 2022.

**Uren die op timesheet worden getoond zijn verschillend van de lijst van Tijdopnemers**

*Timesheets*

Wanneer een gebruiker een timesheet opent om het te bekijken, zijn de getoonde uren verschillend van wanneer de gebruiker zelfde timesheet in een timesheet lijst bekijkt.


**Verzoek dat in project met malplaatje wordt omgezet toont groep van verzoekrij, niet groep van malplaatje**

*Verzoeken*

Wanneer een gebruiker een verzoek in een project gebruikend een malplaatje omzet, wordt het nieuwe gecreeerd project geassocieerd met de groep die de verzoekrij, niet de groep bezit die op het malplaatje wordt toegewezen. Dit gebeurt ook als het project wordt gemaakt en de groep die aan de sjabloon is gekoppeld, in het veld [!UICONTROL Group] wordt ingevuld.

+++

+++**Update van het Onderhoud op 21 Juli, 2022**

Deze problemen zijn alleen opgelost in de nieuwe [!DNL Workfront] -ervaring.

Alle [!DNL Workfront Classic] -functionaliteit is verwijderd op 14 juli 2022.

**de status van de Afwijzing verbonden aan een goedkeuring neemt het goedkeuringswerkschema**

**NOTA: Deze functionaliteit kwam op 22 Juli, 2022 vrij.**

*Goedkeuringen*

Als u een status verbonden aan een goedkeuringsproces als verwerpingsstatus voor een goedkeuringspad selecteert, beweegt het verworpen voorwerp zich naar de geselecteerde status, en het zal als &quot;[!UICONTROL Pending approval]&quot;worden gemerkt. Bijvoorbeeld, als u [!UICONTROL On Hold] voor de verwerpingsstatus selecteert en de [!UICONTROL On Hold] status met een goedkeuringsproces wordt geassocieerd, wordt het verworpen voorwerp geplaatst in de status van &quot;[!UICONTROL On Hold- Pending approval]&quot;, die de goedkeuring vereist.

Vóór deze update heeft het object het goedkeuringsproces voor de afwijzingsstatus overgeslagen en is het object in de status [!UICONTROL On Hold] geplaatst.

**vorm een douaneHulp URL**

*[!UICONTROL Main Menu]*

Als uw organisatie een aangepaste interne Help-site heeft, kunt u het pictogram [!UICONTROL Main Menu] [!UICONTROL Help] configureren om naar die site te gaan. Dit is handig als de Help-site informatie bevat over hoe uw organisatie [!DNL Workfront] gebruikt.
Deze aangepaste URL heeft geen invloed op de hoofdkoppeling van de Help in het bovenste gebied van [!DNL Workfront] en ook niet op contextgevoelige Help-koppelingen in [!DNL Workfront] , die gebruikers naar de Help-site van [!DNL Workfront] brengen.

**Kan Verlopen tijd niet selecteren bij inline bewerken[!UICONTROL Task Duration]**

*Taken*

Wanneer een gebruiker een takenlijst weergeeft en probeert [!UICONTROL Task Duration] te bewerken, zijn de volgende tijdseenheden niet beschikbaar:

* [!UICONTROL Elapsed Minutes]
* [!UICONTROL Elapsed Hours]
* [!UICONTROL Elapsed Days]
* [!UICONTROL Elapsed Weeks]
* [!UICONTROL Elapsed Months]

**[!UICONTROL My Updates]page is blank**

*Updates*

Wanneer een gebruiker zijn [!UICONTROL My Updates] -pagina probeert weer te geven, wordt de pagina niet geladen. De gebruiker kan alleen de [!DNL Workfront] navigatiekop zien.

**&quot;[!UICONTROL Only Allow SAML 2.0 Authentication]&quot;het plaatsen mist wanneer het kopiëren van een gebruiker**

*Gebruikers*

Wanneer een groepsbeheerder een gebruiker kopieert en &quot;[!UICONTROL Send an invite email to this person]&quot;optie schrapt, O [!UICONTROL nly Allow SAML 2.0 Authentication] checkbox niet zoals verwacht verschijnt. Dit kan zelfs voorkomen wanneer alle toegangs en toestemmingsvereisten voor deze actie worden voldaan aan.

+++

+++**Update van het Onderhoud op 14 Juli, 2022**

Deze problemen zijn alleen opgelost in de nieuwe [!DNL Workfront] -ervaring.

Alle [!DNL Workfront Classic] -functionaliteit is verwijderd op 14 juli 2022.

**Fout wanneer het terugstellen van wachtwoord**

*Login*

Wanneer een gebruiker probeert om hun wachtwoord terug te stellen, kunnen zij het niet terugstellen, en zij zien een bericht hen vertellen zij hebben geen toegang. De gebruiker kan zich niet aanmelden bij Workfront.

**kan niet meer toegang tot een rapport verzoeken**

*Rapporten*

Wanneer een gebruiker met beperkte toegang tot een rapport probeert meer toegang tot een rapport te vragen, is de optie om meer toegang aan te vragen niet beschikbaar onder het [!UICONTROL report actions] menu.

**Bijgewerkt bevestigingsbericht wanneer het schrappen van een verzoekontwerp**

*Verzoeken*

Wanneer het verwerpen van een geschreven verzoek, toont het bevestigingsbericht dat na &quot;[!UICONTROL Discard draft]&quot;klikt het volgende:

* [!UICONTROL Draft was discarded] (dit is een melding om u te laten weten dat uw concept is verwijderd)
* [!UICONTROL Undo] (dit is een koppeling waarop u kunt klikken om de handeling van het verwijderen van het concept te herstellen. Zo blijft het concept behouden in plaats van het te verwijderen.)

Vóór deze wijziging waren de volgende opties beschikbaar:

* [!UICONTROL Draft will be discarded]
* [!UICONTROL Cancel]

**de waarden van de Datum voor de gebieden van de Ingang van het Dagboek onjuist wanneer betreden door API**

*Updates*

Wanneer een gebruiker een datumwaarde op een object wijzigt en vervolgens het Journal-item dat die datumwijziging vertegenwoordigt, wordt benaderd via de API, zijn de datumwaarden voor [!UICONTROL oldDateVal] en [!UICONTROL newDateVal] die door de API worden geretourneerd, onjuist.

**Fout wanneer het proberen om commentaar** ongedaan te maken

*Updates*

Wanneer een gebruiker een opmerking ongedaan probeert te maken, wordt de opmerking niet ongedaan gemaakt en wordt de volgende fout weergegeven:

[!UICONTROL Error 403: You do not have sufficient access to delete this Note /attask/api-internal/NOTE]

**Nieuwe beperking aan het aantal karakters in een update in Voorproef**

*Updates*

Om de prestaties van het [!UICONTROL Updates] gebied te verbeteren, hebben wij een nieuwe grens aan het aantal karakters geïntroduceerd dat u in een update of een antwoord op een bestaande update kunt ingaan. De nieuwe limiet is 15.000 tekens. Deze update heeft het toegestane aantal tekens voor het gebruik van de API niet gewijzigd. De API-tekenlimiet voor updates is 4.000.

**Fout wanneer het uploaden van gehechtheid van [!DNL Workfront] voor de integratie van Vooruitzichten**

*de Integraties van Workfront*

Wanneer een gebruiker een bijlage probeert te uploaden met behulp van de [!DNL Workfront for Outlook] -integratie, wordt de bijlage niet geüpload en ziet de gebruiker het volgende bericht:

[!UICONTROL Some attachments have not been uploaded. Reason: Something went wrong with uploading attachments.]

**update van het e-mailbericht van het Bewijs**

*[!DNL Workfront]Proef*

Eerder deze maand hebben we als onderdeel van een patch voor de [!DNL Workfront] Production-omgeving een fout opgelost in het e-mailmeldingssysteem voor proefdrukken. Deze wijziging werd niet meegedeeld in de onderhoudsupdate toen deze werd vrijgegeven. Wij hebben de volgende informatie aan de [&#x200B; Update van het Onderhoud op 2 Juni, 2022 &#x200B;](#maintenance-update-on-june-2-2022) toegevoegd:

Als gevolg van deze foutoplossingen is het e-mailadres dat wordt gebruikt voor het verzenden van proefdrukmeldingen, gewijzigd.

Eerder bevatte het proefdrukken van e-mailadressen het subdomein van uw organisatie. Bijvoorbeeld, berichten@[ bedrijfdomein ] .my.workfront.com

Het opgeven van e-mailadressen bevat nu geen subdomein voor organisaties meer. Alle e-mailmeldingen over proefdrukken zijn afkomstig van het volgende adres: `notification@my.workfront.com`

Dientengevolge, adviseren wij u de volgende acties als u nog niet hebt:

* Werk uw spamfilters bij om e-mails van `notification@my.workfront.com` te accepteren
* Werk uw lijsten van gewenste personen bij om e-mails van `notification@my.workfront.com` te accepteren
  **de opties van de Gebruiker kunnen niet na aanvankelijke configuratie in de Malplaatjes van het Werkschema worden gewijzigd**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een gebruiker aan een Malplaatje van het Werkschema toevoegt, kunnen zij opties vormen. Nochtans, nadat de aanvankelijke configuratie volledig is, kan de gebruiker niet meer het volgende wijzigen:

* Mogelijkheid &quot;[!UICONTROL Resolve comments and apply actions]&quot;
* [!UICONTROL "Share proof by tagging]&quot;-mogelijkheid
* Proefdrukrol ([!UICONTROL Reviewer], [!UICONTROL Approver], enz.)

**&quot;[!UICONTROL This project's work items]&quot;filter is hersteld in het project[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

Het filter &#39;Werkitems van dit project&#39; in het [!UICONTROL Assigned] -gebied is hersteld wanneer u het [!UICONTROL Workload Balancer] -object opent vanuit een project.

Dit filter wordt nu vermeld onder de sectie &quot;[!UICONTROL Suggested]&quot; van de filters voor het [!UICONTROL Assigned Work] -gebied van het project [!UICONTROL Workload Balancer] .

+++

## Updates in juni 2022

+++**Update van het Onderhoud op 30 Juni, 2022**

**Vertoning [!UICONTROL Workload Balancer] voor één week**

*[!UICONTROL Workload Balancer]*

Op basis van de feedback die we van veel klanten hebben ontvangen, hebben we nu een optie toegevoegd om de [!UICONTROL Workload Balancer] voor een week weer te geven. Voordat u deze update uitvoert, kunt u de [!UICONTROL Workload Balancer] gedurende 4, 6 en 12 weken weergeven. Met deze update hebben we ook de optie van 12 weken gewijzigd in 3 maanden.

**het paneel van de Afgevaardigde is nu beschikbaar bij de Balancer van de Werkbelasting**

*[!UICONTROL Workload Balancer]*

OPMERKING: deze update bestaat alleen in de voorvertoningsomgeving. De functionaliteit die aan deze update is gekoppeld, is beschikbaar in Production met de release 22.3.

U kunt de afgevaardigden van een taak of een kwestie van de Balancer van de Werkbelasting nu bekijken. Wanneer u een taak of een probleem toewijst vanuit Workload Balancer, kunt u een lijst met toewijzingen en een lijst met afgevaardigden voor de taak of kwestie weergeven als deze momenteel zijn gedelegeerd.

**kan eindpuntinformatie in API Ontdekkingsreiziger niet openen**

*API*

Wanneer een gebruiker [!DNL API Explorer] bekijkt en op een eindpunt klikt, toont de eindpuntinformatie niet.

**Kwesties met [!UICONTROL Details] knoop wanneer het gebruiken van[!UICONTROL Home Calendar]**

*Huis*

Wanneer een gebruiker de [!UICONTROL Home Calendar] gebruikt en op een taak klikt, kan een van de volgende gebeurtenissen plaatsvinden:

* De knop [!UICONTROL Details] wordt kort weergegeven en verdwijnt vervolgens. De gebruiker heeft geen toegang tot de details.
* De knop [!UICONTROL Details] wordt niet weergegeven. De gebruiker heeft geen toegang tot de details.
* De knop [!UICONTROL Details] wordt weergegeven, maar bevindt zich niet op de juiste locatie. De gebruiker kan op de knop klikken om de details te openen.

+++

+++**Update van het Onderhoud (Hete Fix) op 24 Juni, 2022**

**de plukker van de Datum sluit niet wanneer het uitgeven van de Vorm van de Douane**

*Aangepaste Forms*

Wanneer een gebruiker een aangepast formulier bewerkt en probeert een datum te wijzigen, wordt de datumkiezer niet gesloten wanneer de datum wordt geselecteerd. De gebruiker kan de datumkiezer niet sluiten door op te slaan, te annuleren of buiten de datumkiezer te klikken.

Dit is gemeld op de volgende gebieden:

* [!UICONTROL Updates] -gebied
* [!UICONTROL Home]

**de Gebruiker kan niet zelf naar een ander stadium van een proef** bewegen

*Proofs*

Wanneer een gebruiker [!UICONTROL Proof Workflow] van een proef bekijkt en probeert om zich aan een verschillend stadium van de proef te slepen, breekt de naam van de gebruiker terug naar het originele stadium, en zij worden niet toegevoegd aan het gewenste stadium.

+++

+++**Update van het Onderhoud op 23 Juni, 2022**

**[!UICONTROL Cannot add new request through dashboard]**

*Dashboards*

Wanneer een gebruiker een dashboard in een project bekijkt en een nieuwe aanvraag probeert toe te voegen door op de knop [!UICONTROL +New Request] te klikken, reageert de knop niet en kan de gebruiker geen nieuwe aanvraag toevoegen.

**Fout wanneer het bekijken van punten in de Werklijst van het Huis**

*[!UICONTROL Home]*

Wanneer een gebruiker zijn [!UICONTROL Home Work List] weergeeft en op een item in de [!UICONTROL Approvals I've Submitted] -sectie klikt, wordt de volgende fout weergegeven op de pagina:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

Als de gebruiker de pagina vernieuwt en vervolgens op een item in de [!UICONTROL Work List] klikt, wordt de fout weergegeven. Het probleem heeft niet langer alleen invloed op items in de sectie [!UICONTROL Approvals I've Submitted] .

**de sectie van de Douane op een voorwerp omvat resultaten niet in dat voorwerp**

*Voorwerpen*

Wanneer een gebruiker een [!UICONTROL custom] -sectie op een object weergeeft, worden in de aangepaste sectie items weergegeven die geen deel uitmaken van dat object. Dit is gemeld wanneer de aangepaste sectie rechtstreeks aan het object wordt toegevoegd en wanneer een aangepaste sectie wordt toegevoegd via een lay-outsjabloon.

**Taken worden bewogen aan onjuist project**

*Taken*

Wanneer een gebruiker taken van Project A aan Project B beweegt, dan bewegingen meer taken van Project A aan Project C, de taken oorspronkelijk die aan Project B oorspronkelijk werden verplaatst op Project C verschijnen.

**sommige knopen/pictogrammen werken niet wanneer het toegang tot van [!UICONTROL Workload Balancer] van een gedeelde verbinding of dashboard**

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker naar de [!UICONTROL Workload Balancer] gaat via een gedeelde koppeling of een koppeling in een dashboard en het element boven aan het scherm probeert te gebruiken, werken de elementen niet. Dit is gerapporteerd voor de volgende elementen:

* [!UICONTROL Today]
* Pijlen naar achteren en naar voren
* [!UICONTROL Weeks]
* Kalenderpictogram (datumkiezer)

+++

+++**[!DNL Workfront]Scenario Planner Maintenance Update op 23 juni 2022**

**Gebruikers met [!UICONTROL Manage] toestemmingen aan een plan kunnen het met anderen delen**

Als gebruiker met [!UICONTROL Manage] machtigingen voor een abonnement in [!DNL Scenario Planner] kunt u het abonnement nu delen met andere gebruikers. Vóór deze update kon alleen de maker van het abonnement het abonnement met andere gebruikers delen.

+++

+++**Update van het Onderhoud op 16 juni, 2022**

**de beheerder van de Groep kan geen leden aan groep** toevoegen

*Groepen*

Wanneer een groepsbeheerder een gebruiker aan een groep probeert toe te voegen, dropdown om de gebruiker te selecteren bevolkt niet. De groepsbeheerder kan geen gebruikers selecteren en kan daarom geen gebruikers aan de groep toevoegen.

**de kwarten van de Douane verschijnen niet wanneer het plaatsen van een filter**

*Filters*

Wanneer een gebruiker een filter en filters op een datumveld maakt, bevat het vervolgkeuzemenu met beschikbare operatoren voor het datumveld geen onlangs toegevoegde aangepaste kwartalen.

**&quot;Wiops&quot;fout wanneer het omzetten van een kwestie in een project via een malplaatje**

*Projecten*

Wanneer een gebruiker een uitgave via een malplaatje probeert om te zetten in een project, en de kwestie heeft een douaneformulier dat een admin-enige sectie bevat, wordt de kwestie niet omgezet en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

**de verzoeken worden voorgelegd zonder vereiste gevulde gebieden**

*Verzoeken*

Wanneer een gebruiker een aanvraag maakt en de vereiste velden niet invult, wordt de aanvraag verzonden zonder gegevens in de vereiste velden. Het verwachte gedrag is dat de aanvraag niet wordt verzonden en dat de gebruiker op de hoogte wordt gesteld dat hij de vereiste velden moet invullen voordat hij de aanvraag indient.

**Nieuwe douanekwarten schijnen niet om** te bewaren

*Opstelling*

Wanneer een gebruiker een nieuw douanekwart van het gebied van Projecten van Opstelling toevoegt en [!UICONTROL Save] klikt, is er geen visuele aanwijzing van sparen. De gebruiker ziet geen succesbericht en de knop [!UICONTROL Save] blijft aanwezig en is actief. Als de gebruiker de pagina echter vernieuwt, ziet hij of zij dat de nieuwe kwartalen worden weergegeven in de lijst met aangepaste kwartalen.

Als de gebruiker een nieuw kwart toevoegt, op [!UICONTROL Save] klikt, geen indicatie van sparen ontvangt, een ander kwart toevoegt zonder de pagina te verfrissen, en opnieuw [!UICONTROL Save] klikt, kan het tweede toegevoegde kwart niet worden bewaard.

**[!UICONTROL Team Work Requests]page is blank**

*Teams*

OPMERKING: dit probleem bestaat alleen in de voorvertoningsomgeving.

Wanneer een gebruiker probeert het [!UICONTROL Work Requests] -gebied op een teampagina te openen, is de pagina leeg. De gebruiker kan de bovenste navigatiebalk zien, maar geen pagina-inhoud.

+++

+++**Update van het Onderhoud op 9 Juni, 2022**

**kan geen voorwerpen selecteren om in [!UICONTROL Portfolio Optimizer] voorkeur** te filtreren

*Portfolio&#39;s*

Wanneer een gebruiker zich in de [!UICONTROL Portfolio Optimizer] bevindt en de tab [!UICONTROL Project Filters] in het [!UICONTROL Preferences] -gebied weergeeft, ontbreken de selectievakjes naast de objecten. De gebruiker kan selectievakjes niet in- of uitschakelen en kan daarom geen objecten selecteren om te filteren.

**kan niet [!UICONTROL Planned Start Date] veranderen of [!UICONTROL Planned Completion Date] wanneer &quot;[!UICONTROL Schedule From]&quot;niet wordt gecontroleerd**

*Projecten*

Wanneer een gebruiker probeert om [!UICONTROL Planned Start Date] of [!UICONTROL Planned Completion Date] van een project uit te geven, en de &quot;[!UICONTROL Schedule From]&quot;optie voor dat project niet wordt gecontroleerd, worden de [!UICONTROL Planned Start Date] en [!UICONTROL Planned Completion Date] gebieden onbruikbaar gemaakt, en de gebruiker kan die data niet uitgeven.

**kan toegangsniveau van gebruikers** niet uitgeven

*Gebruikers*

Wanneer een gebruiker die toegang heeft tot de Planner en waartoe User Admin (Group Users)-toegang behoort, probeert gebruikers te bewerken in de groep waarvoor hij of zij beheerder is, wordt het veld [!UICONTROL Access] level uitgeschakeld en kan de gebruiker het toegangsniveau niet bewerken.

+++

+++**[!DNL Workfront Scenario Planner]Onderhoudsupdate op 9 juni 2022**

**resizable linkerpaneel in[!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

U kunt nu de grootte van het linkerdeelvenster wijzigen in een abonnement, in de map [!DNL Scenario Planner] . Hierdoor kunnen langere initiatiefnamen volledig worden weergegeven. Voorafgaand aan deze update werden langere initiatiefnamen afgebroken.

+++

+++**[!DNL Workfront Fusion]Onderhoudsupdate op 9 juni 2022**

**Gegevens van douanevormen niet beschikbaar in [!DNL Workfront Fusion] [!DNL Workfront] modules**

*[!DNL Workfront Fusion]*

Wanneer een gebruiker een [!DNL Workfront] -module in [!DNL Workfront Fusion] configureert en uitvoerbestanden voor de module probeert te selecteren, zijn velden van aangepaste formulieren niet zichtbaar. Dit gebeurt wanneer het aangepaste formulier voor een bepaald type [!DNL Workfront] -object is gemaakt en er een ander type aan is toegevoegd. [!DNL Workfront Fusion] geeft alleen velden weer van aangepaste formulieren die oorspronkelijk voor het geselecteerde objecttype zijn gemaakt.

**kan niet scrollen om alle scenario&#39;s te bekijken uitvoeringen**

*[!DNL Workfront Fusion]*

Wanneer een gebruiker de uitvoeringshistorie van een scenario bekijkt en naar beneden probeert te scrollen om meer uitvoeringen te bekijken, houden de executies ladend op en de gebruiker kan hen niet bekijken. Bovendien kan de gebruiker niet naar de meest recente uitvoeringen terugschuiven.

+++

+++**Update van het Onderhoud op 2 Juni, 2022**

**[!UICONTROL Portfolio Optimizer]toont een score van 0 wanneer het gebruiken van andere taal dan het Engels**

*Portfolio&#39;s*

Wanneer een gebruiker [!DNL Workfront] in een andere taal dan Engels gebruikt en [!UICONTROL Portfolio Optimizer] bekijkt, wordt de score weergegeven als 0. Dit kan zelfs gebeuren wanneer de bedrijfscase niet volledig is.

**Berekende gebiedswaarden onjuist wanneer het creëren van project van malplaatje**

*Projecten*

Wanneer een gebruiker een project van een malplaatje creeert dat berekende gebieden omvat, zijn de gebiedswaarden die op het nieuwe project verschijnen onjuist.

**Kan [!UICONTROL Conditions] niet bewerken in [!UICONTROL Project Preferences] gebied van[!UICONTROL Setup]**

*[!UICONTROL Setup]*

Wanneer een gebruiker [!UICONTROL Conditions] probeert te bewerken in het [!UICONTROL Project Preferences] gebied van [!UICONTROL Setup] , is de pagina leeg.

**Nieuwe beperking aan het aantal karakters in een update in Voorproef**

*[!UICONTROL Workload Balancer]*

>[!NOTE]
>
>Deze update geldt alleen voor de voorvertoningsomgeving.

Om de prestaties van het gebied van Updates te verbeteren, hebben wij een nieuwe grens aan het aantal karakters geïntroduceerd die u in een update of een antwoord op een bestaande update kunt ingaan. De nieuwe limiet is 15.000 tekens. Deze update heeft het toegestane aantal tekens voor het gebruik van de API niet gewijzigd. De API-tekenlimiet voor updates is 4.000. Updates
Ondersteuning voor aangepaste velden van het type Typehead in Workload Balancer-filters

We ondersteunen nu filters op basis van het type [!UICONTROL Typeahead] aangepaste velden in Workload Balancer. Vóór deze patch was het filteren voor dit type aangepaste velden niet mogelijk in Workload Balancer.

**kan geen toestemmingen op de rol van een gebruiker uitgeven**

*[!DNL Workfront Proof]*

Wanneer een gebruiker probeert om &quot;[!UICONTROL Resolve comments and apply actions]&quot;of &quot;[!UICONTROL Share a proof by tagging]&quot;toestemmingen op de rol van een gebruiker in [!DNL Workfront Proof] uit te geven, worden de veranderingen niet bewaard. De gebruiker krijgt een bericht dat het malplaatje is bijgewerkt, maar als de gebruiker de roltoestemmingen opnieuw opent kunnen zij zien dat de veranderingen niet werden bewaard.

+++


## Updates in mei 2022

+++**Update van het Onderhoud op 26 Mei, 2022**

Deze problemen zijn alleen opgelost in de nieuwe [!DNL Workfront] -ervaring. [!DNL Adobe Workfront Classic] wordt niet meer ondersteund.

Alle [!DNL Workfront Classic] -functionaliteit wordt verwijderd in juli 2022. Ga zo snel mogelijk over naar de nieuwe ervaring.

**bijgewerkte breadcrumb separators**

*[!DNL Workfront]*

OPMERKING: Deze update is gepubliceerd op 24 mei 2022.

We hebben de scheidingstekens voor broodkruimels bijgewerkt op alle gebieden waar er broodkruimels beschikbaar zijn. De objecten in de broodkruimels worden nu gescheiden door pijpen (|). Vóór deze update werden ze gescheiden door slashes (/).

**kan douaneformulieren met sectieonderbrekingen niet uitgeven**

*Aangepaste Forms*

Wanneer een gebruiker een aangepast formulier met een sectie-einde probeert te bewerken, kan het formulier niet worden bewerkt. De volgende melding wordt weergegeven:

[!UICONTROL Specified section break security cannot be applied on all object types]

**Kwesties wanneer druk Dashboards aan PDF**

*Dashboards*

De volgende problemen zijn gemeld bij het afdrukken van een dashboard op een PDF:
De PDF drukt niet elke rij in het rapport af. Waar regels ontbreken, wordt alleen lege ruimte weergegeven.
PDF omvat lege ruimten tussen de kolomkopballen en de eerste rij van het rapport.

**[!DNL Portfolio Optimizer]toont een score van 0 wanneer het gebruiken van andere taal dan het Engels**

*Portfolio&#39;s*

Wanneer een gebruiker [!DNL Workfront] in een andere taal dan Engels gebruikt en [!UICONTROL Portfolio Optimizer] bekijkt, wordt de score weergegeven als 0. Dit kan zelfs gebeuren wanneer de bedrijfscase niet volledig is.

**sommige douanevormen tonen niet wanneer het uitgeven van een malplaatje**

*Malplaatjes*

Wanneer een gebruiker de aangepaste formulieren op een sjabloon probeert te bewerken door op [!UICONTROL Edit] in de koptekst van de sjabloon te klikken, wordt in het [!UICONTROL Edit Template] -venster slechts een van de aangepaste formulieren weergegeven die aan de sjabloon zijn gekoppeld.

**Gedeelde verbinding aan de vertoningen van de Balancer van de Werkbelasting toegewezen werk verkeerd**

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker de [!UICONTROL Workload Balancer] via een gedeelde koppeling weergeeft, wordt de sectie [!DNL Workload Balancer] include [!UICONTROL Assigned Work] in de sectie [!UICONTROL Unassigned Work] weergegeven. [!UICONTROL Assigned Work] heeft geen aparte sectie. Wanneer de gebruiker de [!UICONTROL Workload Balancer] weergeeft zonder de gedeelde koppeling te gebruiken, wordt [!UICONTROL Assigned Work] naar behoren weergegeven.

+++

+++**Update van het Onderhoud op 19 Mei, 2022**

**Kan geen proef van a tot stand brengen[!DNL PowerPoint]**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een proef probeert tot stand te brengen van [!DNL PowerPoint] die een grafiek omvat, ontbreekt de proefverwezenlijking.

**kan geen proef van a [!UICONTROL Word] document** tot stand brengen

*[!DNL Workfront Proof]*

Wanneer een gebruiker een proef probeert tot stand te brengen van een [!DNL Word] document dat een grafiek omvat, ontbreekt de proefverwezenlijking.

**kan douanebericht niet toevoegen wanneer het delen van een proef**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een proefdruk weergeeft, het [!UICONTROL Share proof] -gebied opent en de knop [!UICONTROL Add custom message] selecteert, kan de gebruiker niet in het tekstvak typen dat wordt geopend. Wanneer de gebruiker in dit vak probeert te typen, verdwijnt het vak direct.

**kan proef niet sluiten**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een proefdruk weergeeft en deze probeert te sluiten, ontbreekt in de rechterbovenhoek van de proefdruk de X om de proefdruk te sluiten.

**kan groepsbeheerder toevoegen of verwijderen**

*Groepen*

Als een gebruiker een [!UICONTROL Group] -pagina weergeeft en via het [!UICONTROL Group Administrators] -gebied in de koptekst probeert een groepsbeheerder toe te voegen of te verwijderen, worden de wijzigingen niet opgeslagen en ziet de gebruiker de volgende fout:

[!UICONTROL Error Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Horizontaal de blokpunt van de rolbar aan het eind van lijst**

*Projecten*

Wanneer een gebruiker een lijst weergeeft met een weergave die buiten het scherm valt, blokkeert de horizontale schuifbalk de weergave van het laatste item in de lijst.

**&quot;[!UICONTROL Unexpected error]&quot; wanneer het omzetten van een kwestie in een project gebruikend een malplaatje**

*Lijsten*

Wanneer een gebruiker een uitgave in een project probeert om te zetten gebruikend een malplaatje, zet de kwestie niet om en de gebruiker ziet het volgende bericht:

[!UICONTROL An unexpected error happened]

**het [!UICONTROL Status] gebied in een timesheet mening is nu read-only**

*Timesheets*

Het veld [!UICONTROL Status] in een tijdlijnweergave is gewijzigd in alleen-lezen. Voorafgaand aan deze verandering, konden de gebruikers het statuut van een timesheet inline uitgeven dat hen toestaat om het besluit van timesheet fiatteurs met voeten te treden.

+++

+++**Update van het Onderhoud op 12 Mei, 2022**

De knop **[!UICONTROL Save]houdt niet op met laden wanneer u een project bewerkt**

*Projecten*

Wanneer een gebruiker een project bewerkt en probeert op te slaan, wordt op de knop [!UICONTROL Save] het woord &quot;[!UICONTROL Loading]&quot; weergegeven. Als de gebruiker op deze knop klikt om de wijzigingen in het project op te slaan, reageert de knop niet en worden de wijzigingen niet opgeslagen.

**De etiketten van het Gebied verschijnen niet wanneer het bekijken van een voorwerp in[!UICONTROL Home]**

*Huis*

Wanneer een gebruiker een object selecteert in [!UICONTROL Home Work List] , bevat het gebied rechts van [!UICONTROL Home Work List] dat het object weergeeft geen veldlabels. De veldwaarden zijn aanwezig.

**Snelle Filter richt zich niet automatisch op onderzoeksbar**

*Lijsten*

Wanneer een gebruiker in een lijst is en op het vergrootglas klikt om snel te filteren, begint het typen en wordt de tekst niet weergegeven. Dit komt doordat de focus op het vergrootglaspictogram blijft en niet op de zoekbalk.

Wanneer u op de zoekbalk klikt, wordt de focus overgedragen en kan de gebruiker de tekst van zijn zoekopdracht invoeren.

**Gebruikers kunnen niet inline uitgeven gebieden in een rapport**

*Rapporten*

Wanneer een gebruiker een veld in een rapport probeert te bewerken en dat veld uit een aangepast formulier wordt gehaald, kan de gebruiker het veld niet bewerken. Dit gebeurt wanneer het aangepaste formulier oorspronkelijk is gemaakt voor een ander objecttype dan het object waaraan het is gekoppeld.

**Etiket en knooptekst niet zichtbaar wanneer het creëren van een proef**

*[!DNL Workfront Proof]*

OPMERKING: dit probleem bestaat alleen in de voorvertoningsomgeving.

Wanneer een gebruiker een proef probeert te creëren, is de tekst niet zichtbaar voor opties of knopen. Daarom weet de gebruiker niet wat elke optie of knoop vertegenwoordigt, en kan niet de proef vormen.

+++

+++**Update van het Onderhoud op 5 Mei, 2022**

**kan geen nieuw Facturerend Verslag toevoegen**

*Projecten*

Wanneer een gebruiker zich in het [!UICONTROL Billing Records] -gebied van een project bevindt en de [!UICONTROL New Billing Record] -weergave gebruikt, worden de velden voor een nieuw Factureringsrecord niet weergegeven en kan het Factureringsrecord niet worden gemaakt als de gebruiker een nieuw Factureringsrecord probeert toe te voegen.

**Fout bij maken van bulktoewijzing in[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker taken in [!DNL Workload Balancer] van een project probeert uit te voeren, wordt de gebruiker omgeleid naar een pagina met het volgende bericht:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

De gebruiker kan pas vanaf deze pagina navigeren nadat de pagina is vernieuwd.

**Bijgewerkte navigatie om het [!UICONTROL Summary] paneel voor taken en kwesties in te openen[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

Als u nu gewoon op een taak- of probleembalk klikt in [!UICONTROL Workload Balancer] , wordt het deelvenster Samenvatting geopend. Voordat deze update werd uitgevoerd, moest u op het pictogram [!UICONTROL Open Summary] op de werkbalk klikken en vervolgens op de taak of het probleem klikken. Dit was een verwarrende ervaring gebleken die nu is gecorrigeerd. U kunt ook op het menu [!UICONTROL More] naast de naam van de taak of uitgave klikken en vervolgens op [!UICONTROL Open Summary] klikken.

**de beheerder van de Groep kan geen details van gebruikers in de groep** bekijken

*Gebruikers*

Wanneer een gebruiker die aan een toegangsniveau wordt toegewezen dat [!UICONTROL User Admin (Group Users)] toegang het plaatsen omvat probeert om details van een gebruiker in hun groep te bekijken, zien zij de volgende fout:

&quot;[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

**kan de status van de douanegroep niet schrappen**

*Groepen*

Wanneer een gebruiker een aangepaste groepsstatus probeert te verwijderen van de pagina [!UICONTROL Group] , wordt de pagina leeg gelaten en wordt de status niet verwijderd.

**de waakzame montages van de E-mail zijn inconsistent tussen het gebied van Contacten en de Details van de Gebruiker**

*[!DNL Workfront Proof]*

De instellingen voor e-mailwaarschuwingen die worden weergegeven in het [!UICONTROL Contacts] gebied [!DNL Workfront Proof] voor een bepaalde gebruiker, verschillen van de instelling voor e-mailwaarschuwingen in het gedeelte [!UICONTROL User Details] van de gebruiker.

**kan het hulpmiddel van de Tekst niet gebruiken wanneer het maken van een commentaar op een proef**

*[!DNL Workfront Proof]*

Wanneer een gebruiker opmerkingen maakt over een proefdruk en probeert het gereedschap [!UICONTROL Text] te openen, wordt het gereedschap niet geopend en ziet de gebruiker het volgende bericht:

&quot;[!UICONTROL Text data for this page is still downloading. Please wait.]&quot;

**de e-mails van het proefteken zullen naar primaire e-mail van de gebruiker** gaan

*[!DNL Workfront Proof]*

We zijn bezig met het aanpassen van de manier waarop e-mailmeldingen met proefdrukken worden verzonden. Meldingen gaan nu naar het primaire e-mailadres van de gebruiker in plaats van naar het alias-e-mailadres dat door het systeem wordt gegenereerd.

Zie Gebruikerssynchronisatie tussen Adobe [!DNL Workfront] en [!DNL Workfront Proof] voor meer informatie over waarom het systeem e-mailberichten met alias genereert.

+++

## Updates in april 2022

+++**Update van het Onderhoud op 28 April, 2022**

**kan niet aan [!UICONTROL Save] knoop scrollen wanneer het uitgeven van een timesheet**

*Timesheets*

Wanneer een gebruiker een timesheet bewerkt, kan hij of zij het bewerkingsvenster niet ver genoeg schuiven om de knop [!UICONTROL Save] weer te geven. Daarom kan hij of zij de tijdpagina niet bewerken.

**elektronische handtekening controleert nu identiteitskaart van de Federatie**

*Proofs*

Wanneer u een proefdruk elektronisch ondertekent, controleert het systeem nu de federatie-id, als u SSO hebt ingesteld in [!DNL Workfront Proof], naast uw e-mail in [!DNL Workfront] .

Eerder controleerde het systeem alleen uw e-mail in Workfront.

+++

+++**Update van het Onderhoud (Hete Fix) op 25 April, 2022**

**[!UICONTROL Workload Balancer]wordt niet geladen**

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker probeert de [!UICONTROL Workload Balancer] te openen, worden de koptekst en de linkernavigatie geladen, maar wordt de inhoud van Workload Balancer niet geladen. De gebruiker ziet opvlammende grijze vierkanten in plaats van gegevens. Soms wordt een deel van de inhoud geladen, maar ziet de gebruiker nog steeds flitsende grijze vierkantjes waar de ontbrekende gegevens zich bevinden.

+++

+++**Update van het Onderhoud op 21 April, 2022**

**Toevoegend een taak veroorzaakt pagina om neer te springen**

*Taken*

Wanneer een gebruiker een taak toevoegt onder een bestaande taak in een lijst, springt de pagina naar een lagere taak in de lijst. Hoewel de nieuwe taak op de juiste plaats is, moet de gebruiker omhoog scrollen om van het de plaats te bepalen.

**Gebruikers die aan een proef zijn toegevoegd, hebben geen toegang tot het werkitem van de proef in[!DNL Workfront]**

*Proofs*

Als een gebruiker aan een werkgebied in de werkstroom van een proefdruk wordt toegevoegd, wordt de gebruiker niet toegevoegd aan het delen van het Document en krijgt geen toestemmingen aan het het werkpunt van de proef in [!DNL Workfront]. Wanneer de gebruiker zich in [!DNL Workfront] bevindt en probeert het werkitem te openen waaraan de proefdruk is gekoppeld, wordt het volgende bericht weergegeven:

&quot;[!UICONTROL You do not have sufficient access to view this (object)]&quot;

Deze kwestie is specifiek voor reeds gecreeerd proefdrukken en gebruikers die na het feit worden toegevoegd. Gebruikers aan de workflow toevoegen voordat het maken van proefdrukken werkt zoals u had verwacht.

**Kan geen e-mail met opnieuw ingestelde wachtwoorden verzenden vanuit[!DNL Workfront]**

*Gebruikers*

Wanneer een gebruiker een e-mail probeert te verzenden om het wachtwoord opnieuw in te stellen vanuit een gebruikerslijst in [!DNL Workfront] , is de optie om het e-mailbericht te verzenden niet beschikbaar.

**de vertoningen van de Knoop &quot;[!UICONTROL Start Issue]&quot;eerder dan &quot;[!UICONTROL Start Request]&quot;**

*Verzoeken*

Wanneer een gebruiker een verzoek bekijkt dat aan hun team wordt toegewezen, zien zij een &quot;[!UICONTROL Start Issue]&quot;knoop in de kopbal eerder dan een &quot;[!UICONTROL Start Request]&quot;knoop.

**&quot;[!UICONTROL Undo comment]&quot; optie verwijdert geëtiketteerde gebruikers**

*Updates*

Wanneer een gebruiker een andere gebruiker in een opmerking van tags heeft voorzien, de opmerking plaatst en vervolgens de optie &quot;[!UICONTROL Undo comment]&quot; selecteert, wordt de opmerking op de gebruikelijke wijze in een updatevak weergegeven, maar wordt de gecodeerde gebruiker niet in het vak [!UICONTROL Tagged users] weergegeven.

**kan niet scrollen wanneer het gebruiken van [!UICONTROL Milestone] mening in een rapport**

*Rapporten*

Wanneer een gebruiker een rapport weergeeft en de [!UICONTROL Milestone] -weergave selecteert, wordt de Mijlpaal-weergave weergegeven maar wordt niet meer verschoven. De gebruiker kan geen Mijlpalen weergeven die verder onder de pagina zouden liggen.

**Onjuiste munt wanneer het rapport in dashboard** wordt getoond

*Rapporten*

Wanneer een gebruiker een rapport in een dashboard bekijkt, is de valuta die in het rapport wordt gebruikt onjuist. Wanneer de gebruiker het rapport buiten het dashboard bekijkt, is de valuta correct.

**Voltooid filter toont niet Voltooid het werkpunt** &#x200B; s

*[!UICONTROL Home]*

Wanneer een gebruiker hun [!UICONTROL Home Work List] met het [!UICONTROL Completed] geselecteerde filter bekijkt, worden de voltooide het werkpunten niet getoond in de lijst. Wanneer het filter [!UICONTROL All] is geselecteerd, worden voltooide items in de lijst opgenomen, waaruit blijkt dat de voltooide items bestaan.

**[!DNL Workfront]wordt niet geladen**

*[!DNL Workfront]*

Wanneer een gebruiker zich aanmeldt bij [!DNL Workfront] , lijkt de pagina vast te zitten in een lus van omleidingen of vernieuwingen en wordt de pagina niet geladen.

+++

+++**Update van het Onderhoud op 14 April, 2022**

**kan geen taak van een rapport over een douanesectie op een taak toevoegen**

*Taken*

Wanneer een gebruiker een douanesectie op een taak bekijkt, en de sectie een taakrapport bevat, kan de gebruiker geen taak van dat rapport toevoegen. Met de knop [!UICONTROL Add Task] wordt het rapport gemarkeerd, maar wordt er geen venster geopend waarin de gebruiker een taak kan toevoegen.

**Gedaan knoop in verkeerde plaats wanneer het uitgeven van een mening**

*Weergaven*

Wanneer een gebruiker een weergave bewerkt, wordt de knop [!UICONTROL Done] hoger op het scherm weergegeven en kan de tekst overlappen.

De gebruiker kan de weergave op de gebruikelijke manier bewerken. Dit heeft geen invloed op de functionaliteit.

**kan niet scrollen wanneer het gebruiken van [!UICONTROL Milestone] mening in een rapport**

*Rapporten*

Wanneer een gebruiker een rapport weergeeft en de [!UICONTROL Milestone] -weergave selecteert, wordt de Mijlpaal-weergave weergegeven maar wordt niet meer verschoven. De gebruiker kan geen Mijlpalen weergeven die verder onder de pagina zouden liggen.

**Leeg scherm wanneer het bekijken van updates**

*Updates*

Wanneer een gebruiker updates weergeeft en het scherm schuift om updates verder naar beneden te bekijken, wordt het scherm leeg en kan de gebruiker geen updates zien.

**Fout wanneer bulk die gebruiker toewijst aan taak die niet aan de rol van de Gebruiker** wordt toegewezen

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker in [!UICONTROL Workload Balancer] taken aan een gebruiker probeert toe te wijzen de waarvan Rol van de Baan niet de rol aanpast die aan de taken wordt toegewezen, ziet de gebruiker een bericht dat de taak zal worden toegewezen gebruikend de primaire Rol van de Baan van de toegewezen gebruiker. Nochtans, wanneer de gebruiker &quot;[!UICONTROL Assign] klikt,&quot;worden de taken niet toegewezen en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Error. The server encountered an unknown error.]&quot;

+++

+++**Update van het Onderhoud op 7 April, 2022**

**Gebruikers die aan proeven worden toegevoegd hebben onjuiste rollen**

*Proofs*

Wanneer een gebruiker een andere gebruiker aan een proef toevoegt, wordt de rol van die gebruiker op de proef geplaatst als &quot;[!UICONTROL Read-only]&quot;ondanks de daadwerkelijke het proefdrukrol van de gebruiker.

**kan geen wachtwoord verzenden teruggestelde e-mail naar gebruiker**

*Gebruikers*

Wanneer een gebruiker een wachtwoordinstelling naar een andere gebruiker probeert te verzenden, ziet hij of zij dat de optie [!UICONTROL Send Forgot Password Email] niet beschikbaar is in het menu [!UICONTROL More] .

**[!UICONTROL Update All]verzendt updates naar gebruikersprofielen in plaats van project**

*Updates*

Wanneer een gebruiker het [!UICONTROL People] -gebied van een project bekijkt en de optie [!UICONTROL Update All] selecteert, wordt een update ingevoerd en wordt de update niet naar het project zelf gepost. In plaats daarvan wordt het naar de individuele gebruikersprofielen van elke gebruiker op het project gepost.

**Te veel pagina&#39;s wanneer het drukken updates**

*Updates*

Wanneer een gebruiker een updatestream bekijkt die meer dan één gedrukte pagina zou zijn, en probeert om de pagina te drukken, toont het drukscherm dat het aantal pagina&#39;s ver boven het daadwerkelijke aantal pagina&#39;s is nodig om de updates te drukken. Als de gebruiker vervolgens probeert af te drukken naar PDF, mislukt het maken van de PDF.

**de Gebruikers kunnen niet de volledige lijst van entiteiten zien die met een rapport worden gedeeld wanneer &quot;[!UICONTROL Visible System-Wide]&quot;het plaatsen** wordt toegelaten

*Rapporten*

Wanneer het delen van rapporten met veelvoudige entiteiten die in [!UICONTROL Report Access] worden getoond doos, kunnen de gebruikers niet aan de bodem van de lijst scrollen om de volledige lijst te zien wanneer &quot;[!UICONTROL Visible System-Wide]&quot;plaatsen toegelaten.

**Onjuiste die munt in rapporten wordt gebruikt**

*Rapporten*

Als een gebruiker de valuta van een project plaatst om anders te zijn dan de standaardmunt, dan bekijkt een rapport over dat project, verschijnt de munt als standaardmunt in plaats van de munt van het project.

**Laatste Bekeken informatie die niet in [!UICONTROL Report Usage] rapporten** bijwerkt

*Rapporten*

Wanneer een gebruiker een rapport bekijkt dat informatie betreffende de laatste tijd toont het rapport werd bekeken, kan die informatie leeg zijn of oude gegevens kunnen zijn. Dit probleem betreft onder meer de volgende velden:

* [!UICONTROL Last Viewed By]
* [!UICONTROL Last Viewed Data]
* [!UICONTROL Last X Viewers]
* [!UICONTROL Views This Month / Quarter / Year]

**Voltooide taken die in[!UICONTROL Home Work List]** tonen

*[!UICONTROL Home]*

Wanneer een gebruiker hun [!UICONTROL Home Work List] bekijkt, zien zij Volledige taken in de lijst, zelfs wanneer de optie om Voltooide taken te tonen niet wordt geselecteerd.

**knoop van het Programma niet zichtbaar om Sandbox te plannen verfrist zich**

*Sandbox Milieu*

De knop [!UICONTROL Schedule] die wordt gebruikt om een sandbox te plannen die wordt vernieuwd, is niet zichtbaar in de bovenste banner van de sandboxomgeving.

**de Veranderingen in een berekend gebied beïnvloeden alle berekende gebieden op een vorm**

*Aangepaste Forms*

Wanneer een gebruiker in de Aangepaste Formulier Builder werkt en de waarde van een berekend formulier wijzigt, wordt in alle berekende velden op het formulier de nieuwe waarde weergegeven. Dit kan van invloed zijn op nieuwe of bestaande berekende velden.

**Kleuren die op de bouwer van de douanevorm flikkeren**

*Aangepaste Forms*

Wanneer een gebruiker met berekende velden werkt in de aangepaste formulierbuilder, flikkeren de kleuren van de velden en expressies.

**[!UICONTROL Cannot reject an approval]**

*Goedkeuringen*

Wanneer een gebruiker een goedkeuring probeert af te wijzen, reageert de knop [!UICONTROL Reject] niet en wordt de goedkeuring niet afgewezen.

**[!UICONTROL Projects]tabblad is ondanks de vorige selectie standaard ingesteld op de sectie Alle projecten.**

*Projecten*

Wanneer een gebruiker naar een pagina van Projecten via een lusje gaat dat als deel van het lay-outmalplaatje is vastgezet, blijft de pagina aan het [!UICONTROL All Projects] gebied van de linkernavigatie in gebreke. Dit komt zelfs voor wanneer de gebruiker een ander gebied van de linkernavigatie kiest, dan weg van de pagina van Projecten en terug navigeert.

+++


## Updates in maart 2022

+++**Update van het Onderhoud op 31 Maart, 2022**

**Tijdzones zijn niet consistent tussen [!DNL Workfront] en[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Wanneer het profiel van een gebruiker is ingesteld op een specifieke tijdzone in [!DNL Workfront] , wordt de tijdzone van de gebruiker in [!DNL Workfront Proof] ingesteld op een andere tijdzone.

**Verbinding om een gevraagd document voor te leggen leidt tot lege pagina**

*Documenten*

Wanneer een gebruiker een verzoek ontvangt om een document te verzenden, en op de verbinding aan het voorwerp klikt waar het document werd gevraagd, leidt de verbinding tot een lege pagina. Dit kan voorkomen wanneer het klikken van een verbinding in een e-mail of in een in-app bericht.

**Groep wordt verkeerd toegewezen wanneer het omzetten van kwestie in project**

Groepen

Wanneer een gebruiker een kwestie in een project gebruikend een malplaatje omzet, is de functionaliteit:

* Als het malplaatje een toegewezen groep heeft, toont die groep in het venster van de uitgave omzetting als groep voor het nieuwe project.
* Als het malplaatje geen toegewezen groep heeft, de standaardgroep van de gebruiker die de kwestie omzet toont in het venster van de uitgaveconversie als groep voor het nieuwe project.
* Als het malplaatje geen groep heeft, zou het nieuwe project de groep van het project van de kwestie moeten erven.

**kan geen dwars-objecten douanevorm aan verzoekrij vastmaken**

Verzoeken

Wanneer een gebruiker een aangepast objectoverschrijdend formulier probeert toe te voegen aan de detailpagina van een wachtrij, wordt het objectoverschrijdende formulier niet weergegeven in de vervolgkeuzelijst met beschikbare formulieren en kan de gebruiker het formulier niet selecteren om het toe te voegen aan de rijdetails.

**De gebruikers kunnen niet met secundaire baanrol op[!UICONTROL Workload Balancer]** worden toegewezen

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker een andere gebruiker aan een taak op [!UICONTROL Workload Balancer] probeert toe te wijzen, en de taak aan een baanrol buiten de toegewezen baanrol wordt toegewezen, wordt de gebruiker toegewezen aan de taak door hun primaire baanrol, en het volgende bericht toont:

&quot;\&lt;Name\> komt niet overeen met de rol van \&lt;Taakroltoewijzing\>. 1 werkitem dat momenteel is toegewezen aan de rol van &lt;\Taakroltoewijzing\> wordt toegewezen aan \&lt;Naam\> als rol \&lt;Primaire taakrol\>.&quot;

Dit komt zelfs voor als de gebruiker de de baanrol van de roltoewijzing van de Taak als secundaire baanrol heeft.

**kwestie met het Comité van het Trommel &quot;toont meer het werkpunten&quot;b** &#x200B; ar

*Gelijk*

Wanneer een gebruiker op de [!UICONTROL Show more work items] -balk op een scrollbord klikt, schuift de [!UICONTROL Show more work items] -balk naar de nieuwe items en wordt deze bij het schuiven mee verplaatst. Dit kan de kaarten moeilijk leesbaar maken.

**rode stippen verschijnen op vereiste gebieden in douaneformulieren**

Aangepaste Forms

Wanneer een gebruiker een vereist veld op een aangepast formulier weergeeft, ziet hij twee rode stippen onder de asterisk die aangeeft dat het veld verplicht is.

**drop-down van de Tijd besnoeiing in herinneringen**

*Rapporten*

Wanneer een gebruiker de herinneringen voor een rapport invult en een datumplukker ontmoet, toont de tijdselecteur bij de bodem van de datumkiezer geen uren voorbij 2, en de gebruiker kan geen uurwaarde buiten 1 of 2 selecteren.

+++

+++**Update van het Onderhoud (Hete Fix) op 29 Maart, 2022**

**Onbekwaam om berekeningen in de Bouwer van de Vorm van de Douane te wijzigen of te bewaren**

*de vormen van de Douane*

Als een gebruiker handmatig een berekening invoert in een berekeningsveld in de builder van het aangepaste formulier en het formulier opslaat, wordt de berekening niet opgeslagen. Als de gebruiker het aangepaste formulier opnieuw opent, is dat veld leeg.

Als een gebruiker een berekening invoert in een berekeningsveld in de Aangepaste formulierbuilder door de dropdowns te gebruiken en het formulier op te slaan, wordt die waarde opgeslagen. Als de gebruiker het aangepaste formulier echter opnieuw opent, kan hij of zij dit veld niet bewerken of de waarde handmatig of met het vervolgkeuzemenu verwijderen.

OPMERKING: deze probleemoplossing bevatte extra functionaliteit. Wanneer u nu begint te typen in een berekend veld, worden mogelijke expressies of berekeningen weergegeven in een vervolgkeuzelijst hieronder, net als in de Rekeningeditor. Klik op een item in het vervolgkeuzemenu om het toe te voegen aan het berekende veld.

+++

+++**Update van het Onderhoud op 24 Maart, 2022**

**Tijdzones zijn niet consistent tussen [!DNL Workfront] en[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Wanneer het profiel van een gebruiker is ingesteld op een specifieke tijdzone in [!DNL Workfront] , wordt de tijdzone van de gebruiker in [!DNL Workfront Proof] ingesteld op een andere tijdzone.

**Vereiste gebiedsfout voor vullen-binnen douanegebieden wanneer het vastmaken van een malplaatje**

*Projecten*

Wanneer het vastmaken van een malplaatje met vereiste douanegebieden aan een project waar het gebied reeds bestaat en wordt gevuld, zien de gebruikers de volgende fout: &quot;[!UICONTROL There are incomplete fields. Enter values for required fields before you can continue.]&quot;
Als u op &quot; [!UICONTROL Take me there]&quot; klikt, kunnen de gebruikers zien dat de velden zijn ingevuld en dat ze de sjabloon met succes kunnen koppelen.

**de [!UICONTROL Workload Balancer] flitsen wanneer u tussen data** van een knevel voorziet

*[!UICONTROL Workload Balancer]*

De uren van de gebruiker die als eerste in [!UICONTROL Workload Balancer] worden vermeld, worden niet weergegeven wanneer u de tijdlijn bijwerkt. De gebruiker en zijn uren tonen met alle grijze dozen die enkel knipperen. Dit gebeurt als u vooruit en achteruit gaat op de tijdlijn.

Het bijwerken van het filter lijkt de weergave te herstellen. Als u echter achterwaarts en voorwaarts beweegt op de tijdlijn, wordt de weergaveflitser opnieuw weergegeven en worden de gebruikersuren niet weergegeven.

**de terminologie van de Douane is inconsistent**

*Malplaatjes van de Lay-out*

Gebruikers melden dat wanneer de [!DNL Workfront] -beheerder de terminologie voor bepaalde objecten aanpast met behulp van een lay-outsjabloon, de nieuwe objectnaam inconsistent wordt weergegeven in de interface.

Bijvoorbeeld, op de [!UICONTROL Projects] pagina, kunt u nog de paginatitel zien die als &quot; [!UICONTROL Projects]&quot;wordt getoond, alhoewel de [!DNL Workfront] beheerder de naam voor &quot; [!UICONTROL Projects]&quot;in iets anders veranderde.

Dit veroorzaakt verwarring voor eindgebruikers.

+++

+++**Update van het Onderhoud op 17 Maart, 2022**

**de Duimnagel en belangrijkste beelden zijn leeg wanneer het bekijken van multipage dossiers gebruikend [!DNL Safari] browser**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een bestand met meerdere pagina&#39;s in de [!DNL Safari] -browser probeert weer te geven, zijn de miniatuurpaginaafbeeldingen leeg. Soms is de hoofdafbeelding ook leeg.

**Onjuiste gebruikerslijst wanneer het maken van bulktoewijzingen in[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker een bulktoewijzing in [!UICONTROL Workload Balancer] maakt en een Project en Rol van de Baan selecteert, is de lijst van beschikbare gebruikers onjuist. Het kan gebruikers zonder de de Rol van de Taak of toestemmingen van het Project tonen, en de gebruikers met de Rol van de Taak en de toestemmingen van het Project verschijnen niet in de lijst.

**[!UICONTROL Sorting is not working in reports]**

*Rapporten*

Wanneer een gebruiker op een kolom klikt om er op te sorteren, lijkt de sortering te werken, maar direct keren de resultaten terug naar de oorspronkelijke sortering zoals deze werd weergegeven voordat op de kolom werd geklikt. De sortering op een kolom blijft niet behouden.

**het Selecteren &quot;[!UICONTROL Nothing]&quot;keert aan [!UICONTROL Report Default] het groeperen** terug

*Rapporten*

Wanneer een rapport een ingebouwde groepering heeft en de gebruiker &quot;[!UICONTROL Nothing]&quot;in het [!UICONTROL Grouping] drop-down menu probeert te selecteren, toont het rapport kort zonder groepering en dan aan de [!UICONTROL Report Default] groepering terug.

**Verwijderd &quot;[!UICONTROL Blueprints access]&quot;lusje van de voorkeur van Vervagen**

*Blauwdrukken*

OPMERKING: dit probleem bestaat alleen in de voorvertoningsomgeving.

Het tabblad [!UICONTROL Blueprints access] is verwijderd uit het modaal voorkeurenvenster Vervagen. Er is geen functionaliteit verwijderd uit de voorkeuren voor blauwdrukken.

+++

+++**Update van het Onderhoud (Hete Fix) op 14 Maart, 2022**

**kan niet onderaan gebruikerslijst scrollen wanneer het maken van taak op Kanban board**

*Gelijk*

Wanneer een gebruiker een [!DNL Kanban] -board weergeeft en een toewijzing probeert te maken, wordt de gebruikerslijst die wordt weergegeven wanneer de gebruiker typt, steeds weer teruggesprongen naar de bovenkant wanneer de gebruiker omlaag schuift. De gebruiker kan geen gebruiker selecteren die zich niet bij de bovenkant van de lijst bevindt en kan de toewijzingswijziging niet opslaan.

**[!UICONTROL Milestone]De mening in projectrapport veroorzaakt fout**

*Rapporten*

Wanneer het tonen van een projectrapport gebruikend de [!UICONTROL Milestone] Mening, krijgen de gebruikers &quot;[!UICONTROL APIModel INTERNAL does not support namedQuery TILE:milestone-view (UIVW)]&quot;fout.

**de terminologie van de Douane is inconsistent**

*Malplaatjes van de Lay-out*

Gebruikers melden dat wanneer de [!DNL Workfront] -beheerder de terminologie voor bepaalde objecten aanpast met behulp van een lay-outsjabloon, de nieuwe objectnaam inconsistent wordt weergegeven in de interface.

Bijvoorbeeld, op de [!UICONTROL Projects] pagina, kunt u nog de paginatitel zien die als &quot; [!UICONTROL Projects]&quot;wordt getoond, alhoewel de [!DNL Workfront] beheerder de naam voor &quot; [!UICONTROL Projects]&quot;in iets anders veranderde.

Dit veroorzaakt verwarring voor eindgebruikers.

**Onbekwaam om berekeningen voor bestaande berekende gebieden bij te werken**

*Aangepaste Forms*

Gebruikers kunnen de berekeningen in berekende velden niet bijwerken of wijzigen. Als het veld zonder berekening is gemaakt en opgeslagen, wordt de builder telkens weer leeg wanneer u een expressie probeert toe te voegen en op te slaan/toe te passen.

Als u een berekend veld met een bepaalde expressie maakt en dit opslaat, wordt telkens wanneer u de berekening probeert te wijzigen, de vorige waarde hersteld.

**[!UICONTROL Invalid Parameter]fout bij het opnieuw instellen van wachtwoorden**

*Login*

Gebruikers kunnen hun wachtwoorden in geen enkele omgeving opnieuw instellen. Als ze hun e-mail invoeren en doorgaan, wordt er een fout weergegeven.

[!UICONTROL Error: Invalid Parameter: Search Parameter value "domain"].

+++

+++**Update van het Onderhoud op 10 Maart, 2022**

**Kwesties het programma openen aan het milieu van de Voorproef**

*Login*

De volgende problemen met aanmelden bij de voorbeeldomgeving zijn gemeld.

Wanneer een gebruiker zich aanmeldt bij de voorvertoningsomgeving, wordt een bericht weergegeven waarin wordt aangegeven dat de gebruiker de verkeerde id of het verkeerde wachtwoord heeft ingevoerd.

Wanneer een gebruiker probeert om hun wachtwoord terug te stellen, zien zij de fout &quot;[!UICONTROL ?Multiple users were found with the email address <example@example.com>?]&quot;

**de Formulieren van de Douane laden langzaam in [!UICONTROL Project Details] gebied**

*Projecten*

Wanneer een gebruiker probeert om het gebied [!UICONTROL Project Details] van een project te bekijken, om het even welke douaneformulieren die aan het project in bijlage zijn slechts na een vertraging van 15 seconden of meer laden. Deze vertraging heeft ook invloed op de optie [!UICONTROL Add custom forms] .

**de waarden van het vormgebied van de Douane niet bewaard in het paneel van de documentsamenvatting**

*Documenten*

Wanneer een gebruiker aangepaste formuliervelden bijwerkt in het documentoverzichtsvenster, en een of meer velden een tekstkopveld zijn, worden de wijzigingen opgeslagen en niet in het overzichtsvenster genavigeerd, worden de updates niet opgeslagen. Dit gebeurt alleen wanneer een veld typekop wordt bewerkt, hoewel dit invloed heeft op alle velden.

**Gegevens niet bewaard wanneer het omzetten van malplaatjes toe te schrijven aan malplaatje delend toegangsniveaus**

*Projecten*

Wanneer een gebruiker die toegang tot de Mening op een gedeelde malplaatje heeft probeert om een kwestie in een project om te zetten, worden om het even welke gegevens in de secties van de douanevorm die [!UICONTROL Conrtibute] of hogere toegang vereisen om tot mening over te brengen niet overgebracht naar het gecreeerde project.

**Fout wanneer het uploaden van nieuwe documentversie**

*Documenten*

Wanneer een gebruiker een nieuwe versie van een document probeert te uploaden uit de documentlijst, wordt het document niet geüpload en ziet de gebruiker de volgende fout:

[!UICONTROL Error Cannot invoke "com.attask.boz.Document.getCurrentVersion()" because "document" is null]

**Onbekwaam om het factureren tarieven uit te geven**

*Projecten*

Wanneer een gebruiker een factureringssnelheid probeert te bewerken op het tabblad [!UICONTROL Billing Rates] van een project en u klikt op de knop [!UICONTROL Edit] , wordt het venster [!UICONTROL Edit] kort geopend, maar wordt het venster gesloten voordat de gebruiker de factureringssnelheid kan bewerken. Als u nogmaals op de knop klikt, wordt het bewerkingsvenster niet geopend.

**Openbare verbinding voor document leidt tot lege pagina**

*Documenten*

Wanneer een gebruiker een document probeert te openen met een openbare koppeling, leidt de koppeling naar een lege pagina. Dit gebeurt wanneer de koppeling wordt geopend in een venster waarin een actieve [!DNL Workfront] -sessie is geopend.

**De fout van Hele toen het toevoegen van taak of kwestie aan lijst**

*Taken en Kwesties*

Wanneer een gebruiker die geen beheerder is, een taak of uitgave aan een lijst probeert toe te voegen en aangepaste velden invult, wordt de taak of uitgave niet gemaakt en ziet de gebruiker de volgende fout:

[!UICONTROL Error Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**het verlaten van een update na een statusverandering keert het voorwerp aan een vorige staat terug**

Projecten, taken en problemen

Als u de status van een project, taak of uitgave wijzigt en onmiddellijk een update begint te typen zonder de pagina te vernieuwen, wordt in het updatevak de vorige status weergegeven. Als de update wordt gepost, wordt het voorwerp teruggekeerd aan de vorige status.

**Gebruikers die aan proeven worden toegevoegd hebben onjuiste rollen**

*Proofs*

Wanneer een gebruiker een andere gebruiker aan een proef toevoegt, wordt de rol van die gebruiker op de proef geplaatst als &quot;[!UICONTROL Read-only]&quot;ondanks de daadwerkelijke het proefdrukrol van de gebruiker.

Oplossing:
Stel de proefdrukrol van de gebruiker in hun profiel in op iets anders en stel vervolgens de juiste rol in.

**de vorm van de Douane laadt niet wanneer het omzetten van kwestie in project gebruikend malplaatje**

*de vormen van de Douane*

Wanneer een gebruiker een uitgave naar een project probeert om te zetten gebruikend een malplaatje, één of meerdere douaneformulieren in bijlage aan het malplaatje kunnen niet laden. Wanneer de gebruiker het malplaatje voor het nieuwe project vormt, in plaats van de douaneformulieren zien zij het volgende bericht:

&quot;[!UICONTROL Something went wrong, could not load form].&quot;

**Gebruiker kan geen kwestie inline met douane drop-down gebied toevoegen dat in de mening** toont

*Lijsten*

Wanneer een gebruiker een uitgave van gealigneerd toevoegt en er een douanemening is met douaneveld drop-down die gebieden op de lijst worden toegepast, is er een fout wanneer zij het drop-down gebied slechts invullen. De gebruiker heeft toegang om douaneformulier uit te geven en is de projecteigenaar met beheerde rechten aan het project.

[!UICONTROL Error: Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it!]

**Toestemmingen om taken aan een project toe te voegen worden niet vereist om een taak aan het project te bewegen of te kopiëren**

*Taken*

U kunt nu een taak naar een andere taak in een project verplaatsen of kopiëren zonder toestemmingen te hebben om taken aan het bestemmingsproject toe te voegen. U moet toestemmingen hebben om taken aan minstens één van de taken van het bestemmingsproject toe te voegen. Voorafgaand aan deze update, moest u toestemmingen hebben om taken aan het project toe te voegen om een taak naar het project of aan om het even welk van zijn taken te bewegen of te kopiëren.  Deze update is nu beschikbaar in de productieomgeving. Het is beschikbaar in de Voorvertoningsomgeving vanaf de onderhoudsupdate van 24 maart 2022.

OPMERKING: deze update is beschikbaar in de productieomgeving wanneer problemen na de productievrijgave 22.2 worden gekopieerd of verplaatst. Ga voor meer informatie over de huidige release naar workfront.com/release.

**Prompt drop-down menu wordt geknipt**

*Rapporten*

Wanneer het gebruiken van een herinnering in een rapport, worden de drop-down menu&#39;s die u toestaan om de het filtreren criteria voor het rapport te selecteren afgesneden. De criteria onder aan de keuzelijst met selecties worden daarom niet weergegeven.

**het punt van het Werk keert aan vorige status terug wanneer een update wordt gemaakt**

*Updates*

Wanneer een gebruiker de status van een tijdelijk item in de koptekst wijzigt, wordt de status niet bijgewerkt in het [!UICONTROL Update] -gebied. Als de gebruiker dan een update uitvoert, toont dropdown nog de vorige status. Wanneer de update wordt opgeslagen, overschrijft deze vorige, onjuiste status de status die in de koptekst is ingesteld.

+++

+++**Update van het Onderhoud op 3 Maart, 2022**

**Kan document niet toevoegen vanuit[!DNL Google Drive]**

*Documenten*

Wanneer een gebruiker een document probeert toe te voegen vanuit [!DNL Google Drive] , reageert de selectie niet en kan de gebruiker geen documenten selecteren om toe te voegen.

**de Gelabelde gebruikers worden niet toegevoegd om draad** bij te werken

*Updates*

Wanneer een gebruiker in een update wordt geëtiketteerd, worden zij niet getoond in &quot;[!UICONTROL To]&quot;gebied van de update of zijn antwoorden.

**de gebruiker van het proef heeft twee afzonderlijke het proef rekeningen**

*[!DNL Workfront Proof]*

Het e-mailadres van een gebruiker in [!DNL Workfront Proof] kan zich in twee aparte accounts met verschillende id&#39;s bevinden, waardoor de gebruiker twee accounts krijgt. Hierdoor kan het moeilijk zijn om de juiste account te vinden.

**De fout die van HelePop in rapportkopballen toont**

*Rapporten*

Wanneer een gebruiker een rapport bekijkt, toont de volgende fout in de rapportkopbal:

&quot;[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

Als de gebruiker een dashboard bekijkt, kan de fout in de kopbal voor alle rapporten op het dashboard verschijnen.

**Gegevens in Admin-geef-slechts gebieden van douanevorm wordt niet bewaard wanneer het omzetten van kwesties in projecten**

*Projecten*

Wanneer een niet-admin gebruiker probeert om een kwestie in een project om te zetten gebruikend een malplaatje, en de kwestie gegevens op gebieden bevat die slechts door admin kunnen worden uitgegeven, dragen de gegevens op die gebieden niet over aan het nieuwe project.

Wanneer een beheerder de uitgave omzet, worden de gegevens gedragen naar het nieuwe project zoals verwacht.

**[!DNL XLS]en [!DNL XLSX] de bestandsgroottelimiet is tijdelijk verlaagd naar 100 MB voor proefdrukken**

*het Bewijs*

Om een beveiligingsprobleem op te lossen, hebben we de maximale bestandsgrootte voor [!DNL XLS] - en [!DNL XLSX] -bestanden tijdelijk beperkt tot 100 MB wanneer we een proefdruk maken.

OPMERKING: deze update bevond zich op 24 februari in de voorvertoningsomgeving en bevindt zich op 3 maart in de productieomgeving.

**Update aan het Onderzoek van Workfront**

Zoeken

Deze week is een gefaseerde uitrol gestart om de infrastructuur voor de zoekfunctie van [!DNL Workfront] bij te werken. De update maakt toekomstige verbeteringen aan Onderzoek gemakkelijker en betrouwbaarder. Door deze wijzigingen worden items die aan [!DNL Workfront] zijn toegevoegd, sneller geïndexeerd en worden ze dus sneller in de zoekresultaten opgenomen.

De gefaseerde uitrol zal twee weken duren.

**bijgewerkte toolbars voor rapporten binnen dashboards**

Rapporten

In rapporten in dashboards wordt nu een nieuwe werkbalk weergegeven. Deze werkbalk maakt deel uit van de updates van lijsten en rapporten die overal in [!DNL Workfront] plaatsvinden.

+++


## Updates in februari 2022

+++**Update van het Onderhoud (Hete Fix) op 24 Februari, 2022**

**Gegevens behouden niet wanneer het omzetten van kwesties in projecten als het gebied op malplaatje** wordt verborgen

*Projecten*

Wanneer een gebruiker een uitgave in een malplaatje omzet, en het malplaatje een douaneformulier omvat dat gebieden toont of verbergt die op de waarden in andere gebieden worden gebaseerd, worden om het even welke gegevens in gebieden die op het (gegevensloze) malplaatje op het tijdstip van omzetting verborgen zijn niet gedragen in het nieuwe project.

**kan middelplanner door Rol niet uitvoeren**

*Planner van het Middel*

Wanneer een gebruiker de instructie [!DNL Resource Planner] probeert te exporteren wanneer de optie [!UICONTROL View by Role] wordt gebruikt, mislukt het exporteren en ontvangt de gebruiker een e-mail met het volgende bericht:

Er is een fout opgetreden bij het exporteren van uw [!DNL Resource Planner] -gegevens.

**het verzoekknoop van het Exemplaar het werk niet**

*Verzoeken*

Wanneer een gebruiker een verzoek probeert te kopiëren, werkt de [!UICONTROL Copy Request] knoop niet als de gebruiker geen Toegang van de Mening tot het rijonderwerp heeft.

+++

+++**Update van het Onderhoud op 24 Februari, 2022**

**de vormgegevens van de Douane verdwijnen wanneer andere vormgebieden worden ingevuld**

*de vormen van de Douane*

Wanneer een gebruiker een aangepast formulier invult als onderdeel van de conversie van een uitgave naar een project, kan het invullen van een aangepast veld ertoe leiden dat gegevens in een ander aangepast veld verdwijnen. Wanneer de gebruiker de ontbrekende gegevens opnieuw invoert en het project probeert te maken, wordt het volgende foutbericht weergegeven:

&quot;[!UICONTROL You must be a system admin to change this custom data parameter value]&quot;

**&quot;[!UICONTROL This approval process can be used by...] &quot;gebied mist**

*Goedkeuringen*

Wanneer een gebruiker een goedkeuringsproces in het [!UICONTROL Setup] gebied creeert of uitgeeft, ontbreekt het &quot;[!UICONTROL This approval process can be used by...]&quot;gebied. Dit kan voorkomen wanneer het creëren van een goedkeuringsproces of wanneer het uitgeven van bestaande.

**Admin van het Systeem kan gebruikers opnieuw toewijzen wanneer het schrappen van een groep**

*Groepen*

Wanneer een systeembeheerder een groep schrapt, zullen zij slechts de optie hebben om de gebruikers van die groep aan groepen opnieuw toe te wijzen die de systeembeheerder een groepsbeheerder voor is. Andere groepen worden niet weergegeven in het vervolgkeuzemenu en de beheerder kan deze niet selecteren.

**De fout van Hele wanneer het omzetten van kwestie in project**

*Projecten*

Wanneer een gebruiker een uitgave in een project probeert om te zetten gebruikend een malplaatje, en douaneformulieren toevoegt of verwijdert uit het malplaatje, zet de kwestie niet om en de gebruiker ziet het volgende bericht:

[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**kan bewijs openen niet; de pagina verfrist zich**

*Proofs*

Wanneer een gebruiker een proef probeert te openen, kan de proef niet openen. Uiteindelijk wordt de pagina vernieuwd.

**[!DNL XLS]en [!DNL XLSX] de bestandsgroottelimiet is tijdelijk verlaagd naar 100 MB voor proefdrukken**

*het Bewijs*

Om een beveiligingsprobleem op te lossen, hebben we de maximale bestandsgrootte voor [!DNL XLS] - en [!DNL XLSX] -bestanden tijdelijk beperkt tot 100 MB wanneer we een proefdruk maken.

OPMERKING: deze update vindt plaats in de voorbeeldomgeving op 24 februari en in de productieomgeving op 3 maart.

**Toestemmingen om taken of kwesties aan een project toe te voegen worden niet vereist om een taak of een kwestie aan het project te bewegen of te kopiëren**

*Projecten*

U kunt nu een taak of een kwestie aan een andere taak in een project bewegen of kopiëren zonder het hebben toestemmingen om taken of kwesties aan het bestemmingsproject toe te voegen. U moet toestemmingen hebben om taken of kwesties aan minstens één van de taken van het bestemmingsproject toe te voegen. Voorafgaand aan deze update moest u machtigingen hebben om taken of problemen aan het project toe te voegen om een taak of een uitgave naar het project of een van de taken te verplaatsen of te kopiëren. Deze update is alleen beschikbaar in de voorvertoningsomgeving.

OPMERKING: deze update is beschikbaar in de productieomgeving wanneer taken op 10 maart worden uitgevoerd of verplaatst. Deze update is beschikbaar in de productieomgeving wanneer u problemen kopieert of verplaatst met de 22.2 Production release. Ga voor meer informatie over de huidige release naar workfront.com/release.

**Update aan het Onderzoek van Workfront**

*Onderzoek*

Deze week is een gefaseerde uitrol gestart om de infrastructuur voor de zoekfunctie van [!DNL Workfront] bij te werken. De update maakt toekomstige verbeteringen aan Onderzoek gemakkelijker en betrouwbaarder. Door deze wijzigingen worden items die aan [!DNL Workfront] zijn toegevoegd, sneller geïndexeerd en worden ze dus sneller in de zoekresultaten opgenomen.

De gefaseerde uitrol zal twee weken duren.

+++

+++**[!DNL Workfront Fusion]Onderhoudsupdate op 18 februari 2022**

**de waarde van het Gebied typebevestiging werd toegevoegd aan [!DNL Anaplan] lijstitemeigenschappen**

*[!DNL Adobe Workfront Fusion]*

Er is een probleem opgelost waarmee gebruikers het onjuiste gegevenstype in velden voor lijstitemeigenschappen konden plaatsen. Met validatie van het type eigenschap kan [!DNL Fusion] ervoor zorgen dat het juiste gegevenstype naar Anaplan wordt verzonden, zodat fouten die door onjuiste gegevenstypen worden veroorzaakt, worden voorkomen.

+++

+++**Update van het Onderhoud op 17 Februari, 2022**

**Fout wanneer het schrappen van voorganger van Predecessors tabel**

*Taken*

Wanneer een gebruiker een voorganger probeert te verwijderen van het tabblad [!UICONTROL Predecessors] voor een taak, wordt de taak niet verwijderd en wordt de volgende fout weergegeven:

[!UICONTROL Task with primary key value(s) "" not found]

**De fout van Hele toen het openen van gebruikerspagina**

*Gebruikers*

Wanneer een gebruiker de pagina [!UICONTROL Users] probeert te openen, wordt de pagina niet geopend en ziet de gebruiker de volgende fout:

[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Overlappende elementen in de kopbal van een rapport over een dashboard**

*Dashboards*

Wanneer een gebruiker een rapport op een dashboard weergeeft, ziet hij of zij dat het groeperingspictogram en het label de koppelingen naar [!UICONTROL Details] en [!UICONTROL Summary] overlappen.

**Kwesties met &quot;[!UICONTROL More]&quot;menu voor documenten en proeven**

*Documenten*

Wanneer een gebruiker een document of proef op een [!DNL Workfront Classic] documentlijst selecteert, dan &quot; [!UICONTROL More] klikt,&quot;zij kunnen één van de volgende kwesties zien:
De knop reageert niet
Alle opties onder de knoop zijn geëtiketteerd &quot;[!UICONTROL object Object]&quot;en kunnen niet worden gebruikt.

**&quot;U moet een systeem admin&quot;fout zijn wanneer het creëren van een project**

*Projecten*

Wanneer een gebruiker die geen beheerder is, een project probeert te creëren, en een douaneformulier vastmaakt dat een sectie beschikbaar slechts aan beheerders heeft, kunnen zij niet het project tot stand brengen en zij zien de volgende fout:

&quot;U moet systeembeheerder zijn om deze parameterwaarde van douanegegevens te veranderen&quot;

**Gegevens in admin-enige sectie van douanevorm wordt niet bewaard wanneer het omzetten van kwesties in projecten**

*Projecten*

Wanneer een gebruiker een kwestie in een project gebruikend een malplaatje omzet dat een douaneformulier met een admin-enige sectie heeft, worden om het even welke gegevens in de admin-enige sectie niet overgebracht naar het nieuwe project. Dit gebeurt zelfs als een beheerder de uitgave converteert.

+++

+++**Update van het Onderhoud op 10 Februari, 2022**

**&quot;[!UICONTROL You must be a system admin]&quot;fout wanneer het creëren van een project**

*Projecten*

Wanneer een gebruiker die geen beheerder is, een project probeert te creëren, en een douaneformulier vastmaakt dat een sectie beschikbaar slechts aan beheerders heeft, kunnen zij niet het project tot stand brengen en zij zien de volgende fout:

&quot;[!UICONTROL You must be a system admin to change this custom data parameter value]&quot;

**Gebruikers die zijn gedeactiveerd en opnieuw geactiveerd, verschijnen niet in[!UICONTROL Proof contacts]**

*[!DNL Workfront Proof]*

Wanneer een gebruiker zijn lijst met contactpersonen in [!DNL Workfront Proof] weergeeft, verschijnen gebruikers die zijn gedeactiveerd en opnieuw geactiveerd niet in de lijst.

**&quot;Iets ging fout&quot;bericht toen het omzetten van een kwestie in een project gebruikend een malplaatje**

*Projecten*

Wanneer een gebruiker die geen beheerder is, een uitgave naar een project probeert om te zetten met behulp van een sjabloon, wordt het volgende bericht weergegeven in aangepaste formuliervelden die alleen zichtbaar zijn voor beheerders:

&quot;[!UICONTROL Something went wrong, could not load form]&quot;

**&quot;Kan pagina-inhoud niet laden&quot;-fout bij het weergeven van projectvoorkeuren**

*Opstelling*

Wanneer een beheerder probeert projecten, taken of problemen onder [!UICONTROL Project Preferences] in het [!UICONTROL Setup] -gebied weer te geven, wordt de pagina niet geladen en ziet de gebruiker de volgende fout:

&quot;[!UICONTROL Cannot load page content. Please try refreshing the page.]&quot;

+++

+++**Update van het Onderhoud op 3 Februari, 2022**

**[!UICONTROL BizContext]Fout bij aanmelden**

*Login*

Wanneer een gebruiker zich aanmeldt bij [!DNL Workfront] , mislukt de aanmelding en wordt het volgende bericht weergegeven:

&quot;[!UICONTROL Let's try that again. Database error: BizContext commit failed!]&quot;

Dit is gemeld in de voorvertoningsomgeving.

**de updatestroom van de Uitgave verdwijnt als de kwestie goedkeuring** in afwachting is

*Updates*

Wanneer een gebruiker in de doos [!UICONTROL New update] in de updatestroom van een kwestie klikt die goedkeuring wacht, verdwijnt de volledige updatestroom.

**Fout wanneer het uploaden van nieuwe versie van een document**

*Documenten*

Wanneer een gebruiker een nieuwe versie van een document probeert te uploaden, wordt de nieuwe versie niet geüpload en ziet de gebruiker een van de volgende fouten:

* [!UICONTROL documentID cannot be null]
* [!UICONTROL Error: Invalid Parameter: documentID value "undefined"]

**Openbare verbinding voor document leidt tot lege pagina**

*Documenten*

Wanneer een gebruiker een document probeert te openen met een openbare koppeling, leidt de koppeling naar een lege pagina. Dit gebeurt wanneer de koppeling wordt geopend in een venster waarin een actieve [!DNL Workfront] -sessie is geopend.

**de controles van de Lijst werken niet aan rapporten in dashboards**

*Dashboards*

Wanneer een gebruiker een rapport in een dashboard bekijkt en probeert om de filter, de groepering, of de mening van het rapport te veranderen, verandert de filter, de groepering, of de mening niet.

**&quot;[!UICONTROL You must be a system admin]&quot;fout wanneer het creëren van een project**

*Projecten*

Wanneer een gebruiker die geen beheerder is, een project probeert te creëren, en een douaneformulier vastmaakt dat een sectie beschikbaar slechts aan beheerders heeft, kunnen zij niet het project tot stand brengen en zij zien de volgende fout:

&quot;[!UICONTROL You must be a system admin to change this custom data parameter value]&quot;

**de gegevens van de Douane worden niet bewaard wanneer het omzetten van kwestie in project**

*Projecten*

Wanneer een gebruiker een kwestie in een project gebruikend een malplaatje omzet, worden de gegevens van een douaneformulier over de kwestie niet overgebracht naar de vergelijkbare douaneformulier op het project. Dit gebeurt met gegevens in aangepaste velden die kunnen worden verborgen op basis van de waarden van andere aangepaste velden.

**Fout wanneer het omzetten van kwestie in project**

*Projecten*

Wanneer een gebruiker een uitgave in een project probeert om te zetten, wordt de kwestie niet omgezet en zij zien de volgende fout:

&quot;[!UICONTROL An unexpected error occurred]&quot;

+++


## Updates in januari 2022

+++**Update van het Onderhoud op 27 Januari, 2022**

**de gegevens van de Douane worden niet bewaard wanneer het omzetten van kwestie in project**

*Projecten*

Wanneer een gebruiker een kwestie in een project gebruikend een malplaatje omzet, worden de gegevens van een douaneformulier over de kwestie niet overgebracht naar de vergelijkbare douaneformulier op het project. Dit gebeurt met gegevens in aangepaste velden die kunnen worden verborgen op basis van de waarden van andere aangepaste velden.

**de lijst van de Gebruiker op agile board is niet alfabetisch**

*Gelijk*

Wanneer een gebruiker de gebruikerslijst op een agile-board bekijkt, worden de gebruikers niet in alfabetische volgorde weergegeven. In plaats daarvan worden eerst de gebruikers met de meeste toewijzingen vermeld.

**Bijgewerkte verbindingen voor het kopiëren en het bewegen van kwesties**

*Kwesties*

In het milieu van de Voorproef, zijn de verbindingen voor het kopiëren en het bewegen van kwesties bijgewerkt aan &quot;[!UICONTROL Copy to]&quot;en &quot;[!UICONTROL Move to]&quot;zowel op de uitgiftepagina als in een uitgiftenlijst.

**voeg tot 45 IP adressen aan uw [!DNL Workfront] lijst van gewenste personen** toe

*Opstelling*

De grens voor IP adressen die aan uw [!DNL Workfront] lijst van gewenste personen worden toegevoegd is gestegen van 30 tot 45.

+++

+++**Update van het Onderhoud op 20 Januari, 2022**

**&quot;[!UICONTROL Invalid Parameter]&quot;fout wanneer het creëren van project van malplaatje**

*Projecten*

Wanneer een gebruiker probeert om een project van een malplaatje tot stand te brengen, en een douaneformulier uit het malplaatje verwijdert wanneer het creëren van het project, wordt het project niet gecreeerd en de gebruiker ziet &quot;[!UICONTROL Invalid Parameter]&quot;foutenmelding die een vereist gebied op de verwijderde douanevorm bespreekt.

**lijst van de Gebruiker laadt niet in [!DNL Safari] browser**

*Gebruikers*

Wanneer een gebruiker naar het [!UICONTROL Users] -gebied gaat, wordt de koptekst weergegeven, maar wordt de lijst met gebruikers niet geladen.

**Lag wanneer het slepen van taken in een lijst veroorzaakt taak om zich aan verkeerde plaats** te bewegen

*Lijsten*

Wanneer een gebruiker een taak in een lijst probeert te bewegen door het te slepen, de blauwe lijn die erop wijst waar de taak zal worden bewogen om veel langzamer dan de curseur te bewegen. Wanneer de gebruiker de taak loslaat, wordt deze naar de positie verplaatst waar de blauwe lijn zich bevindt, zelfs als de cursor naar een andere locatie in de lijst wijst.

+++

+++**[!DNL Workfront Fusion]Onderhoudsupdate op 14 januari 2022**

**Sommige toegewezen velden worden opnieuw ingesteld wanneer u selecteert[!UICONTROL new field to map]**

*[!DNL Workfront Fusion]*

Wanneer ten minste één veld in de modules [!DNL Workfront] [!UICONTROL Create] of [!UICONTROL Update] de toewijzing heeft ingeschakeld en een gebruiker een nieuw veld selecteert om toe te wijzen, verliezen de eerder toegewezen velden die de toewijzing hebben ingeschakeld, toewijzingswaarden.

+++

+++**Update van het Onderhoud op 13 Januari, 2022**

**Onbekwaam om een hyperlink aan een commentaar in het Summiere paneel toe te voegen**

*Taken*

Wanneer een gebruiker in het overzichtsvenster van een taak een opmerking maakt en probeert een hyperlink naar de opmerking toe te voegen, wordt het hyperlinkkader geopend, maar zodra de gebruiker in het venster klikt, wordt het gesloten en kan de gebruiker geen hyperlink toevoegen. Als een gebruiker met Tab naar het venster gaat, kan hij een koppeling in het veld typen of plakken, maar de hyperlink slaat niet op. In beide gevallen wordt de taak uitgeschakeld.

**geeft de pagina van het Team uit sluit niet**

*Teams*

Wanneer een gebruiker een team probeert te bewerken, wordt de pagina [!DNL Edit team] niet gesloten. De gebruiker kan de pagina niet sluiten door op een van de knoppen te klikken, op de X te klikken of weg van de pagina te navigeren.

**e-mail en in-app berichten worden niet verzonden**

*Meldingen*

Wanneer een gebeurtenis die een bericht zou moeten teweegbrengen voorkomt, wordt het bericht niet verzonden. Dit kan voorkomen voor e-mail of in-app berichten, en kan voorkomen zelfs alhoewel andere berichten worden verzonden.

**[!UICONTROL My Work]list lijkt empty**

*[!UICONTROL My Work]*

Wanneer een gebruiker zijn [!UICONTROL My Work] -lijst weergeeft en de lay-outsjabloon voor zijn [!UICONTROL My Work] -lijst een numerieke waarde bevat, zoals [!UICONTROL Percent Complete] , wordt de [!UICONTROL My Work] -lijst niet weergegeven.

**[!UICONTROL Percent Complete]en [!UICONTROL Hours Complete] kunnen niet worden gewijzigd op het Klembord**

*Gelijk*

Wanneer een gebruiker &quot;[!UICONTROL Show more work items]&quot;op de Raad van de Gelijkheid selecteert, dan probeert om [!UICONTROL Percent Complete] of [!UICONTROL Hours Complete] op één van de onlangs geladen het werkpunten te veranderen, kunnen zij niet de Volgorde of Volledige Uren veranderen. De knop [!UICONTROL Percent Complete] is ook grijs om aan te geven dat deze inactief is.

+++

+++**Update van het Onderhoud op 6 Januari, 2022**

**&quot;[!UICONTROL Invalid Parameter]&quot;fout wanneer het vastmaken van malplaatjes of douaneformulieren aan projecten**

*Projecten*

Wanneer een gebruiker probeert om een douaneformulier of een malplaatje aan een bestaand project vast te maken, dan vult de vereiste gebieden op het douaneformulier of het malplaatje en bewaart de veranderingen in het project, slaan de veranderingen niet en de gebruiker ziet &quot;[!UICONTROL Invalid Parameter]&quot;fout bij de bovenkant van de pagina van projectdetails.

**de commentaren van het Bewijs tonen niet in de updates van het Document**

*Proofs*

Wanneer een gebruiker een proef in het [!UICONTROL Documents] gebied bekijkt, tonen om het even welke commentaren die op de proef zelf worden gemaakt niet in [!UICONTROL updates] gebied van het document.

**[!UICONTROL Workload Balancer]: &quot;[!UICONTROL ?[object Object]?]&quot; wordt weergegeven in overtoewijzingsgegevens**

*[!UICONTROL Workload Balancer]*

Als een gebruiker als oververdeeld in [!UICONTROL Workload Balancer] wegens een taak toont die de tijd van de gebruiker wegoverlapt, en een andere gebruiker hun overtoverdracht bekijkt, &quot;[!UICONTROL Capacity]&quot;toont het gebied van de overtoewijzingsinformatie &quot;[!UICONTROL ?[object Object]?]&quot;in plaats van de daadwerkelijke capaciteit van de gebruiker.

+++

## Vorige onderhoudsupdates

Informatie over vorige onderhoudsupdates is hier beschikbaar:

* [[!DNL Workfront] Archief met onderhoudsupdates - 2021](2021-updates.md)
