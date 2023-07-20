---
title: Workfront-onderhoudsupdates in 2022
description: 2022 Onderhoudsupdates voor [!DNL Adobe Workfront]
exl-id: 78ea4e31-143f-4a70-bb9a-060b5a8e097e
feature: Get Started with Workfront
source-git-commit: 6f245f70ca00bef3db833a891cc4c7d822761c37
workflow-type: tm+mt
source-wordcount: '15283'
ht-degree: 0%

---

# [!DNL Workfront] Onderhoudsupdates

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

Voor onderhoudsupdates vóór 2022, zie [Vorige onderhoudsupdates](#previous-maintenance-updates)

## Updates in december 2022

+++**Onderhoudsupdate op 15 december 2022**

**Toegankelijkheidsupdates in lijsten**

*Lijsten*

De volgende toegankelijkheidsfuncties zijn nu beschikbaar in lijsten:

* Selectievakjes in lijsten hebben nu een zichtbare focusindicator wanneer u er met Tab naartoe gaat. Hierdoor is het gemakkelijker om de toetsenbordnavigatie van items in een lijst visueel te volgen.
* Alle knoppen in de lijstwerkbalken hebben nu dezelfde aanwijs- en focusstatus, met een grijze achtergrond die wordt weergegeven op de aanwijsbalk en een grijze achtergrond en een blauwe omtrek die scherp wordt weergegeven.
* Als u eerder een vervolgkeuzemenu opent in een lijst met de spatietoets, wordt het menu geopend en wordt de pagina ook een beetje omlaag geschoven, wat niet de bedoeling was. De pagina wordt nu niet meer verschoven wanneer u op Ruimte drukt in een vervolgkeuzelijst. Dit is de juiste manier.
* Wanneer u een lijst bekijkt terwijl het selectievakje voor rijen is ingeschakeld, kunt u nu met de Tab-toets door elk bewerkbaar item bladeren en vervolgens op de toets Ruimte drukken om over te schakelen op de modus Bewerken en om te beginnen met het bewerken van die cel in de rij. Eerder was navigatie met het toetsenbord niet mogelijk voor deze items en was het gebruik van een muis vereist. Nu is het schakelen naar de bewerkingsmodus zowel muisvriendelijk als toetsenbordvriendelijk.

**&quot;[!UICONTROL Whoops]&quot;-fout bij het maken van een project op basis van een sjabloon**

*Projecten*

Wanneer een gebruiker probeert om een project van een malplaatje tot stand te brengen, wordt het project niet gecreeerd, en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

**In een combinatieschema worden dezelfde gegevens twee keer weergegeven**

*Rapporten*

Wanneer een gebruiker een combinatieschema weergeeft, wordt in het diagram tweemaal één waarde weergegeven in plaats van twee waardensets te vergelijken. De juiste waardensets vindt u in de rapportdetails.

**Knopinfo die voor gedimde uurcellen in timesheets wordt toegevoegd**

*Timesheets*

Wij hebben tooltips toegevoegd om de reden te verklaren waarom een uurcel in een timesheet kan worden gedimd. Een aantal van de redenen kan bijvoorbeeld zijn omdat het tijdspad is gesloten of omdat het project is voltooid.

**Gedetailleerde gebruikers beschikbaar bij het selecteren van de fiatteur van het tijdblad**

*Timesheets*

Wanneer een gebruiker een timesheet maakt en een fiatteur probeert toe te wijzen, bevat de vervolgkeuzelijst gedeactiveerde gebruikers. Als een gedeactiveerde gebruiker wordt geselecteerd, wordt timesheet niet bewaard en de gebruiker ziet het volgende bericht:

&quot;[!UICONTROL Error. Sorry! Only users with Plan license can approve or reject timesheets. Please contact your system administrator.]&quot;

Aangezien de gedeactiveerde gebruiker niet kan worden toegewezen, moet de gebruiker een geactiveerde gebruiker selecteren. De tijdpagina werkt daarom zoals verwacht, maar de gedeactiveerde gebruikers in de lijst kunnen verwarring of ongemak veroorzaken voor de gebruiker.

**Kan tijd niet invoeren op tijdblad**

*Timesheets*

Wanneer een gebruiker probeert om tijd aan een timesheet toe te voegen, zien zij dat de uurvakjes in om het even welke tijd van het Project of de rijen van de Tijd van de Taak uit grijs zijn, en zij kunnen geen tijd in deze vakjes ingaan. Ze kunnen alleen tijd invoeren in het gebied Algemene tijd.

+++

+++**Onderhoudsupdate op 8 december 2022**

**Selectie van slimme gebruikers bij het toevoegen van fiatteurs aan een goedkeuringspad**

*Goedkeuringen*

We hebben de manier verbeterd waarop gebruikers deze weergeven wanneer u ze toevoegt aan de [!UICONTROL Approvers] gebied van een nieuwe goedkeuring.

Nu, wanneer u een gebruiker aan toevoegt [!UICONTROL Approvers] in het veld van een goedkeuring op systeemniveau of voor eenmalig gebruik, naast hun naam en avatar, ook hun primaire rol en hun e-mailadres. Zo kunt u beter onderscheid maken tussen meerdere gebruikers met dezelfde of vergelijkbare namen.

**Projectstatus volgt niet de projectvoorkeuren voor groepen**

*Projecten*

Wanneer een gebruiker tot een project van een malplaatje leidt, neemt het nieuwe project niet de status die in de het projectvoorkeur van de Groep wordt geplaatst. Als een project zonder een malplaatje wordt gecreeerd, wijst de status op het projectvoorkeur van de Groep zoals verwacht.

**Kan subtaak niet toevoegen**

*Taken*

Wanneer een gebruiker een subtaak probeert toe te voegen met &quot;[!UICONTROL +New]&quot;, worden er geen opties weergegeven in het dialoogvenster [!UICONTROL New Task] en de gebruiker ziet het volgende bericht:

&quot;[!UICONTROL Cannot read properties of undefined (reading 'validations)]&quot;

**Fouten bij het sluiten of opslaan van tijdbladen**

*Timesheets*

Wanneer een gebruiker probeert om tijd aan toe te voegen of een timesheet te sluiten, bewaart timesheet niet, en de gebruiker ziet de volgende fouten:

* Databasefout vanwege ongeldige SQL-instructie.
* De recente wijzigingen zijn niet opgeslagen. Vernieuw de pagina om de laatst opgeslagen wijzigingen weer te geven.

+++

+++**Onderhoudsupdate (Hot Fix) op 1 december 2022**

**Foutberichten worden niet veroorzaakt door inline bewerkingsfouten van de gebruiker**

*Lijsten*

Wanneer een gebruiker een object inline bewerkt en een fout maakt die een foutbericht moet maken, wordt geen foutbericht weergegeven. De fout zelf wordt niet opgeslagen in Workfront, dus de gegevens worden niet beïnvloed, maar het ontbreken van een foutbericht kan verwarring veroorzaken.

Dit is gemeld voor de volgende situaties:

* Voorgangers: Er wordt een voorganger-lus gemaakt, zoals het toewijzen van een taak aan zichzelf
* Datums: Er wordt een onmogelijke datum ingesteld, zoals een voltooiingsdatum die voor de begindatum ligt of die na de projectuitvoeringsdatum valt

**De optie &quot;Verplaatsen naar&quot; is niet beschikbaar in rapporten over problemen**

*Rapporten*

Wanneer een gebruiker een probleemrapport weergeeft en een probleem probeert te verplaatsen, is de optie &quot;Verplaatsen naar&quot; niet beschikbaar in het menu Meer (drie punten).


**Kan gebruikerskaart niet sluiten in updatestroom**

*Updates*

Wanneer een gebruiker updates weergeeft en deze boven een naam plaatst, wordt een kaart met gegevens over de gebruiker wiens naam wordt geopend en wordt deze niet automatisch gesloten. De pagina reageert pas als de kaart handmatig wordt gesloten door op de X in de rechterbovenhoek te klikken.


+++

+++**Onderhoudsupdate op 1 december 2022**

**De taak heeft een Kanban-achterstand van 0**

*Agile*

Wanneer een gebruiker de achterstand van een Kanban-team bekijkt, tonen een of meer van de taken een achterlogorde van 0.

**&quot;[!UICONTROL Invalid custom expression]&quot; bericht bij verwijzing &quot;[!UICONTROL owner]&quot; in een berekend veld**

*Aangepaste formulieren*

Wanneer een gebruiker een berekend veld toevoegt aan een aangepast formulier op emissieniveau en probeert een verwijzing toe te voegen aan &quot;[!UICONTROL owner]&quot; (zoals `ownerID`), slaat het veld niet op en de gebruiker ziet het volgende bericht:

&quot;[!UICONTROL This is an invalid customer expression, please try again.]&quot;

Dit gebeurt zelfs wanneer de expressie geldig is.

**Kan geen toegang krijgen tot elementen van [!DNL Workfront for Jira] integratie**

*Integraties*

De volgende elementen zijn momenteel niet toegankelijk in het dialoogvenster [!DNL Workfront for Jira] integratie voor [!DNL Jira Cloud]:

* De [!UICONTROL Configuration] page
* De &quot;[!UICONTROL Open Workfront]&quot; op een knop op een [!DNL Jira] kwestie

**Aangepast bericht toevoegen veroorzaakt probleem in de proefdrukviewer**

*Proefdrukken*

Wanneer een gebruiker een proef deelt en probeert om een douanebericht toe te voegen, komt het volgende voor:

* In de proefdrukviewer wordt ingezoomd op de proefdruk.
* De gebieden in de linkernavigatie reageren niet meer.

**Gedetailleerde gebruikers beschikbaar bij het selecteren van de fiatteur van het tijdblad**

*Timesheets*

Wanneer een gebruiker een timesheet maakt en een fiatteur probeert toe te wijzen, bevat de vervolgkeuzelijst gedeactiveerde gebruikers. Als een gedeactiveerde gebruiker wordt geselecteerd, wordt timesheet niet bewaard en de gebruiker ziet het volgende bericht:

&quot;[!UICONTROL Error. Sorry! Only users with Plan license can approve or reject timesheets. Please contact your system administrator.]&quot;

Aangezien de gedeactiveerde gebruiker niet kan worden toegewezen, moet de gebruiker een geactiveerde gebruiker selecteren. De tijdpagina werkt daarom zoals verwacht, maar de gedeactiveerde gebruikers in de lijst kunnen verwarring of ongemak veroorzaken voor de gebruiker.

**Tijdschema is niet gegenereerd**

*Timesheets*

Tijdschema&#39;s worden niet gegenereerd, ondanks tijdbladprofielinstellingen. Omdat het timesheet nooit wordt geproduceerd, is het niet beschikbaar voor de gebruiker om tijd in te gaan, en het is niet zichtbaar op lijsten.

+++

## Updates in november 2022

+++**Onderhoudsupdate op 17 november 2022**

**Documenten die in het [!UICONTROL Recycle Bin] als deze optie niet is geselecteerd wanneer u een taak of probleem verplaatst**

*Documenten*

Wanneer u nu de optie [!UICONTROL Documents] tijdens het verplaatsen van een taak of een probleem, de documenten die aan de taak zijn gekoppeld of het probleem wordt in de [!UICONTROL Recycle Bin] gedurende 30 dagen. Een beheerder kan deze indien nodig herstellen. De gebruiker die Documenten tijdens het bewegingsproces uitschakelt, ontvangt een waarschuwing over dit gedrag in het dialoogvenster [!UICONTROL Move Task] of [!UICONTROL Move Issue] doos. Vóór deze verbetering zijn de documenten definitief verwijderd.

**Door een item te verbergen, wordt het onjuiste item verborgen**

*Lay-outsjablonen*

Wanneer een gebruiker wijzigt of een item verborgen of weergegeven is, worden deze wijzigingen doorgevoerd in een ander item in de lay-outsjabloon.


+++

+++**Onderhoudsupdate op 10 november 2022**

**Opsommingbewerkingstaken wijzigen taaktoewijzingen**

*Taken*

Wanneer een gebruikersbulk om het even welk gebied voor een reeks taken uitgeeft, worden de Taken van de eerste taak toegepast op alle taken. Hierdoor worden vorige toewijzingen verwijderd.

**Kan geen interactieve proefdruk openen**

*Workfront Proof*

Wanneer een gebruiker een interactieve proef probeert te openen, opent de proef niet en de gebruiker ziet het volgende bericht:

&quot;[!UICONTROL Proof not loaded (501) Try again]&quot;

+++

+++**Onderhoudsupdate (Hot Fix) op 4 november 2022**

**Problemen met taken die aan een herhaling zijn toegevoegd**

*Agile*

De volgende problemen zijn gemeld met betrekking tot kwesties die aan een herhaling zijn toegevoegd:

* Sommige subtaken van een taak die aan een herhaling is toegevoegd, worden niet weergegeven op de knop [!UICONTROL Iteration] pagina.
* Wanneer een gebruiker een ontbrekende taak aan de herhaling probeert toe te voegen, wordt de taak niet toegevoegd en ziet de gebruiker het volgende bericht:

  &quot;[!UICONTROL The following error occurred: None of the selected items could be moved, because they are not assigned to an agile team or are not agile items]&quot;

**Taken die via bulkbewerking zijn toegewezen, worden niet weergegeven op de achterstand van het team**

*Agile*

Wanneer een gebruiker taken toewijst aan een team van het Trommel door bulkhet uitgeven te gebruiken, verschijnen die taken niet op de achterstand van het team.

Deze kwestie heeft geen gevolgen voor Kanbanteams.

**&quot;[!UICONTROL New proof recipients]&quot; tekstvak is te klein**

*Proefdrukken*

Wanneer een gebruiker een proefdruk weergeeft en de proefdruk probeert te delen via de [!UICONTROL Sharing] tab, de &quot;[!UICONTROL New proof reciepients]&quot; het tekstvak is erg klein. De gebruiker kan een naam typen, maar omdat het vak zo klein is, loopt de tekst om op een manier die moeilijk leesbaar is.

**Gebruiksgegevens van rapport worden niet bijgewerkt**

*Rapporten*

Wanneer een gebruiker een rapport weergeeft, wordt de informatie bij Laatst weergegeven, zoals de datum van laatste weergave en Laatst weergegeven door, niet bijgewerkt. Dit betekent dat eventuele gebruiksinformatie mogelijk onjuist is.

Dit gedrag is gemeld wanneer de gebruiker tot het rapport op de volgende manieren toegang heeft:

* Zoeken
* Punten
* Favorieten
* Recenten

Als u rapporten opent via een dashboard, worden de gegevens in de laatste weergave bijgewerkt.

**[!DNL Workfront]: 500 fout bij het aanbrengen van wijzigingen in een [!DNL Workfront] object**+

*[!DNL Workfront]*

Wanneer een gebruiker wijzigingen in een [!DNL Workfront] -object, de wijzigingen worden niet opgeslagen en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL 500: Database error due to invalid SQL statement.]&quot;

Dit is gemeld in de volgende situaties:

* De status van een object wijzigen
* Tijdlijnen opnieuw berekenen
* Een sjabloon koppelen
* Registratietijd

+++

+++**[!DNL Workfront Fusion]Onderhoudsupdate op 3 november 2022**

**Fout bij [!UICONTROL apiKey] in [!DNL Workfront] > [!UICONTROL Watch Events] module**

*[!DNL Workfront Fusion]*

Wanneer een gebruiker een webhaak probeert toe te voegen aan de [!DNL Workfront] > [!UICONTROL Watch Events] ontvangen ze de volgende fout:

&quot;[!UICONTROL The apiKey provided was empty or deemed invalid.]&quot;

+++

+++**Onderhoudsupdate op 3 november 2022**

**Wijzig de namen van de secties &quot;Planning&quot; en &quot;Planning&quot; voor teams en projecten in de lay-outsjabloon**

*Lay-outsjablonen*

De tabbladen &quot;Planning&quot; en &quot;Planning&quot; die beschikbaar zijn om in een lay-outsjabloon aan het linkerdeelvenster van een team of project toe te voegen, hebben de naam &quot;Werklastbalans&quot; gewijzigd.

**Fouten bij het openen van instellingen voor e-mailmeldingen**

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

**Nieuwe informatiepictogrammen voor voorkeuren voor tijdbladen, tijdlijnprofielen en tijdbladen**

*Workfront*

>[!NOTE]
>
>Deze update wordt alleen vrijgegeven voor de voorvertoningsomgeving. De licentie wordt vrijgegeven aan Production met de release van 23.1.

Er zijn verschillende informatiepictogrammen toegevoegd aan de volgende instellingen:

* &quot;Kan tijd&quot;checkbox uitgeven wanneer het creëren van of het uitgeven van een timesheet of een timesheet profiel om erop te wijzen dat wanneer toegelaten, de fiatteurs ook kunnen voorleggen, opnieuw openen, of uitgeven timesheet, tenzij uw beheerder deze acties in het gebied van de Voorkeur van de Chronologie van Opstelling beperkt.
* &quot;Beperk het uitgeven van timesheet tot eigenaars en beheerders&quot;in het gebied van de Voorkeur van de Tijdopmaak &amp; van het Uur van Opstelling om erop te wijzen dat wanneer gehandicapt, de volgende gebruikers de timesheets kunnen ook uitgeven: gebruikers met administratieve toegang tot timesheets en uren, beoordelaars van tijdbladen die tijd mogen uitgeven, en de managers van timesheet eigenaars.

De functionaliteit van deze instellingen is niet gewijzigd en alleen de informatiepictogrammen zijn toegevoegd om het bereik van de instellingen helderder te maken.

+++

## Updates in oktober 2022

+++**Onderhoudsupdate op 27 oktober 2022**

**[!UICONTROL HOUR]functie in berekende velden UTC gebruikt**

*Aangepaste formulieren*

Wanneer een berekend veld de [!UICONTROL HOUR] de functie waarden retourneert op basis van UTC in plaats van de verwachte tijdzone. Daarom zijn berekeningen op basis van de UUR-waarde onjuist.

**[!UICONTROL Quick filter]retourneert geen resultaten bij het zoeken naar teams**

*Lijsten*

Wanneer een gebruiker de opdracht [!UICONTROL Quick filter] in een lijst om naar een team te zoeken, keert het ingaan van de naam van het team geen resultaten terug, zelfs wanneer het team in de lijst (zoals in [!UICONTROL Assigned to] veld). Het woord &quot;[!UICONTROL team]&quot; retourneert ook geen resultaten.

**Kan een pagina niet opnieuw vastzetten nadat het punt is verwijderd**

*Navigatie*

>[!NOTE]
>
>Dit probleem is opgelost in Voorvertoning op 13 oktober 2022. Het werd vastgesteld in Production op 27 oktober 2022.

Wanneer een gebruiker &quot;[!UICONTROL Remove pin]&quot; op een punt, ontvangt een bericht over de verwijdering en probeert het punt te vervangen door te klikken op &quot;[!UICONTROL Undo]&quot; in het bericht wordt het punt niet vervangen in de bovenste navigatie en wordt het evenmin toegevoegd aan de lijst met punten onder de [!UICONTROL More pins] lijst (het menu met drie punten in het menu [!UICONTROL Pins] gebied).

Als een gebruiker de pagina opnieuw vastzet door naar de pagina te gaan en deze vast te zetten, wordt het punt niet gemaakt en kan de gebruiker de pagina niet vastzetten.

**Alle gebruikers die worden vermeld in [!UICONTROL Workload Balancer] wanneer u een deelbare koppeling gebruikt in [!DNL Safari] browser**

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker een deelbare koppeling naar de [!UICONTROL Workload Balancer] tijdens het gebruik van een [!DNL Safari] browser, zien zij alle gebruikers eerder dan enkel de leden van het vermelde team.

+++

+++**Onderhoudsupdate op 20 oktober 2022**

**Fout bij bulksgewijze toewijzing van een team**

*Toewijzingen*

Wanneer een gebruiker in bulk bewerkingstaken of kwesties is en een team toewijst na het toewijzen van een individu, slaan de toewijzingen niet op en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Let's try that again - The following error occurred: teamAssignments must be either a list of objects or a list of IDs]&quot;

**&quot;[!UICONTROL Failed to upload file]&quot;-fout**

*Documenten*

Wanneer een gebruiker een bestand probeert te uploaden naar de [!UICONTROL Documents] gebied, wordt het bestand niet geüpload en de gebruiker ziet de fout &quot;[!UICONTROL Failed to upload file].&quot;

Dit is gemeld bij pogingen om MP4-bestanden te uploaden.

**Aantal problemen in linkernavigatie van taak is onjuist**

*Problemen*

Wanneer een gebruiker een taak bekijkt, het aantal dat op [!UICONTROL Issues] in de linkernavigatie geeft het werkelijke aantal problemen dat aan de taak is gekoppeld, niet correct weer.


**[!UICONTROL Predecessor]pictogram ontbreekt in taakkoptekst**

*Taken*

Wanneer een gebruiker een taak bekijkt, ontbreekt het taakvoorgangerpictogram in de koptekst.

+++

+++**Onderhoudsupdate op 13 oktober 2022**

**Kan een pagina niet opnieuw vastzetten nadat het punt is verwijderd**

*Navigatie*

>[!NOTE]
>
>Dit probleem wordt opgelost in Voorvertoning op 13 oktober 2022. Het zal op 27 oktober 2022 in productie worden vastgesteld.

Wanneer een gebruiker &quot;[!UICONTROL Remove pin]&quot; op een punt, ontvangt een bericht over de verwijdering en probeert het punt te vervangen door te klikken op &quot;[!UICONTROL Undo]&quot; in het bericht wordt het punt niet vervangen in de bovenste navigatie en wordt het evenmin toegevoegd aan de lijst met punten onder de [!UICONTROL More pins] lijst (het menu met drie punten in het menu [!UICONTROL Pins] gebied).

Als een gebruiker de pagina opnieuw vastzet door naar de pagina te gaan en deze vast te zetten, wordt het punt niet gemaakt en kan de gebruiker de pagina niet vastzetten.

**Kan nieuwe filters geen naam geven of opslaan**

*[!UICONTROL Resource Planner]*

Wanneer een gebruiker een naam probeert te geven aan een nieuw filter in het dialoogvenster [!UICONTROL Resource Planner], blijft het naamvak leeg. Als de gebruiker op de spatiebalk heeft gedrukt, wordt bovendien de [!UICONTROL Save] wordt uitgeschakeld.

**Kan naam of percentage van voltooiing van een taak of kwestie niet uitgeven**

*Taken en problemen*

Gebruikers met [!UICONTROL Contribute] Als u toegang hebt tot een taak of uitgave, kunt u de naam van de taak of uitgave in de koptekst niet bewerken. Bovendien kunnen gebruikers met [!UICONTROL Contribute] de toegang kan niet het percentage uitgeven voltooide van een taak of kwestie.

**Aanvragers en revisoren tellen mee voor het aantal licenties van een organisatie**

*[!DNL Workfront Proof]*

Wanneer een gebruiker aan een proef als Revisor of een Aanvrager wordt toegevoegd, krijgen zij &quot;[!UICONTROL Visitor]&quot; machtigingenprofiel, dat geen [!DNL Workfront Proof] licentie. Wanneer de gebruiker echter wordt toegevoegd, wordt het aantal gebruikte [!DNL Workfront Proof] de licenties stijgen.

+++

+++**Onderhoudsupdate op 11 oktober 2022**

**Kan een pagina niet opnieuw vastzetten nadat het punt is verwijderd**

*Navigatie*

>[!NOTE]
>
>Dit probleem is opgelost in Voorvertoning op 13 oktober 2022. Het zal op 27 oktober 2022 in productie worden vastgesteld.

Wanneer een gebruiker &quot;[!UICONTROL Remove pin]&quot; op een punt, ontvangt een bericht over de verwijdering en probeert het punt te vervangen door te klikken op &quot;[!UICONTROL Undo]&quot; in het bericht wordt het punt niet vervangen in de bovenste navigatie en wordt het evenmin toegevoegd aan de lijst met punten onder de [!UICONTROL More pins] lijst (het menu met drie punten in het menu [!UICONTROL Pins] gebied).

Als een gebruiker de pagina opnieuw vastzet door naar de pagina te gaan en deze vast te zetten, wordt het punt niet gemaakt en kan de gebruiker de pagina niet vastzetten.

+++

+++**Onderhoudsupdate op 6 oktober 2022**

**Nieuw blauwdruktype**

*Blauwdrukken*

Het blauwdruktype &#39;Dashboard&#39; is toegevoegd aan de catalogus met blauwdrukken. Eerder waren alleen blauwdrukken voor projectsjablonen en organisatiestructuur beschikbaar.

**Elementen die elkaar overlappen in het linkerdeelvenster**

*Aangepaste formulieren*

Wanneer een gebruiker in de formulierbuilder werkt en het formulier meer dan 100 velden bevat, overlappen elementen in het linkerdeelvenster in het bericht dat de gebruiker op de hoogte wordt gebracht van de veldlimiet.

**De datumkiezer wordt niet meer automatisch geopend bij invoerfocus of klikt op**

*Navigatie*

Wanneer een gebruiker met het toetsenbord navigeert, worden de datumkiezers niet meer automatisch geopend bij de datum waarop de toetsenbordfocus wordt ontvangen. In plaats daarvan moeten toetsenbordgebruikers met de Tab-toets naar het pictogram van de datumkiezer gaan en op Enter drukken om de datumkiezer te openen. Wanneer een gebruiker met de muis navigeert, worden de datumkiezers niet meer automatisch geopend wanneer op de datuminvoer wordt geklikt. In plaats daarvan moeten muisgebruikers op het pictogram van de datumkiezer klikken om de datumkiezer te openen.

Deze wijziging is aangebracht om beter te voldoen aan de UX-patronen van de standaarddatumkiezer en om een toegankelijkere ervaring te creëren voor gebruikers van toetsenbord en schermlezers.

**Het toewijzen van veelvoudige teamresultaten in slechts één toegewezen team**

*Teams*

>[!NOTE]
>
>Dit probleem doet zich alleen voor in de voorvertoningsomgeving.

Wanneer een gebruiker meerdere teams toewijst aan een taak of uitgave, wordt slechts één team weergegeven in de toewijzingslijst. Dit probleem heeft ook invloed op de rapportage. Rapporten waarin teamtoewijzingen worden weergegeven, zijn onjuist omdat slechts één team wordt weergegeven als toegewezen aan de taak of uitgave.

**&quot;[!UICONTROL Your recent changes were not saved]&quot; fout bij het automatisch opslaan van wijzigingen op een tijdblad**

*Timesheets*

Wanneer een gebruiker probeert om een timesheet op een manier uit te geven die autosave zou teweegbrengen worden de veranderingen niet bewaard en de gebruiker ziet het volgende bericht:

&quot;[!UICONTROL Your recent changes were not saved. Refresh the page to view.]&quot;

Dit is gemeld bij het bewerken van het volgende:

* Uren
* Taken

**E-mailmeldingen worden vertraagd**

*Workfront Proof*

Wanneer een gebeurtenis plaatsvindt in [!DNL Workfront Proof] die een e-mailbericht activeert, ontvangt de gebruiker het bericht niet onmiddellijk. De kennisgeving kan enkele uren worden uitgesteld.

+++

+++**Onderhoudsupdate op 3 oktober 2022**

**Sla uw timesheet handmatig op wanneer vorige taakrollen zijn gewijzigd**

*Timesheets*

Als een baanrol waarvoor u tijd registreerde is veranderd en [!UICONTROL Assign job roles to hour entries manually] instelling is uitgeschakeld, moet u uw tijdinvoer handmatig opslaan totdat de uren niet meer zijn geregistreerd voor de gewijzigde taakrol.

+++

## Updates in september 2022

+++**Onderhoudsupdate op 29 september 2022**

**Gebruiker keert niet terug naar vorige pagina wanneer proefdruk wordt gesloten**

*Proefdrukken*

Wanneer een gebruiker die een proef bekijkt binnen [!DNL Workfront] Sluit de proefdruk af, omdat ze de pagina waarop ze stonden niet retourneren voordat ze de proefdruk opende. In plaats daarvan worden ze doorgestuurd naar een andere pagina in [!DNL Workfront].

**Kan proef niet openen in[!DNL Workfront]**

*Proefdrukken*

Wanneer een gebruiker een document weergeeft in [!DNL Workfront] en probeert de proefdruk te openen, wordt de proefdruk niet geopend en wordt de gebruiker teruggestuurd naar de [!UICONTROL Document Details] pagina.

**Uren worden niet opgeslagen tijdens het gebruik [!UICONTROL Tab] key**

*Timesheets*

Wanneer een gebruiker een tijdblad invult en met het gereedschap [!UICONTROL Tab] -toets, de uren worden niet opgeslagen. De [!UICONTROL Auto-save] Deze melding wordt niet onder aan het scherm weergegeven. Als de gebruiker de pagina vernieuwt, ziet hij of zij dat de uren niet zijn opgeslagen.

**Lege pagina&#39;s bij weergave van een proefdruk op meerdere pagina&#39;s**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een proefdruk op meerdere pagina&#39;s weergeeft, kan de gebruiker miniaturen van de pagina&#39;s zien, maar worden de pagina&#39;s niet geopend in de hoofdviewer.



+++

+++**Onderhoudsupdate op 22 september 2022**

**Kan gebruikerskaart niet sluiten in updatestroom**

*Updates*

Wanneer een gebruiker updates weergeeft en deze boven een naam plaatst, wordt een kaart met gegevens over de gebruiker wiens naam wordt geopend en wordt deze niet automatisch gesloten. De pagina reageert pas als de kaart handmatig wordt gesloten door op de X in de rechterbovenhoek te klikken.

+++

+++**Onderhoudsupdate op 15 september 2022**

**&quot;[!UICONTROL Someone else tried to save this project]&quot; fout bij het invoeren van uren**

*Timesheets*

Wanneer een gebruiker uren aan een taak op hun timesheet probeert te registreren, autosave niet, en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL We're sorry, but your save failed because someone else tried to save this project at the same time. Please try to save again.]&quot;

**Kan gebruikerskaart niet sluiten in updatestroom**

*Updates*

Wanneer een gebruiker updates weergeeft en deze boven een naam plaatst, wordt een kaart met gegevens over de gebruiker wiens naam wordt geopend en wordt deze niet automatisch gesloten. De pagina reageert pas als de kaart handmatig wordt gesloten door op de X in de rechterbovenhoek te klikken.

**De &quot;[!UICONTROL Task role assignment]De naam van het veld is gewijzigd in &quot;[!UICONTROL Role assignment]&quot; als u werk in bulk toewijst met de[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

Om de nieuwe functionaliteit te weerspiegelen van het kunnen zowel taken als kwesties in bulk van toewijzen [!UICONTROL Unassigned Work] gebied hebben we de naam &quot;[!UICONTROL Task role assignment]&quot; veld naar &quot;[!UICONTROL Role assignment]&quot; in de [!UICONTROL Workload Balancer]. Het veld verwijst naar taakrollen die aan taken of problemen zijn toegewezen en het wordt weergegeven wanneer gebruikers aan items in het dialoogvenster [!UICONTROL Bulk Assignments] doos.

+++

+++**[!DNL Workfront Scenario Planner]Onderhoudsupdate op 15 september 2022**

**Filter dat met een groep wordt gedeeld, wordt nu weergegeven in het dialoogvenster [!DNL Scenario Planner]s  [!UICONTROL Import Projects] lijst voor leden van alle subgroepen**

*[!DNL Workfront Scenario Planner]*

Nu, wanneer u een projectfilter met een groep deelt die extra subgroepen heeft, is de filter zichtbaar aan alle groep en subgroepsleden die projecten in bekijken [!UICONTROL Import Projects] vak van een plan in het [!DNL Scenario Planner].

+++

+++**Onderhoudsupdate op 8 september 2022**

**Bijgewerkte namen die zijn teruggedraaid voor de velden gebruiker en role-toewijzen**

*Toewijzingen*

De toewijzingsvelden waarvan de naam vorige week tijdelijk is gewijzigd, zijn teruggezet naar de oorspronkelijke naam:

* [!UICONTROL Assignment Users]
* [!UICONTROL Assignment Roles]

**Fout bij het verwijderen van de eigenaar van het project uit de koptekst**

*Projecten*

Wanneer een gebruiker een [!UICONTROL Project Owner] van de kopbal van een project, [!UICONTROL Project Owner] niet wordt verwijderd en de gebruiker ziet het volgende foutbericht:

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**Formaat gewijzigd [!UICONTROL Description] vak gaat terug naar oorspronkelijke grootte**

*Projecten, taken en problemen*

Wanneer een gebruiker de grootte van de [!UICONTROL Description] in het detailgebied van een werkitem om het groter te maken, typt u het vak en keert u terug naar de oorspronkelijke grootte. De gebruiker kan nog steeds in het vak typen en de inhoud opslaan zoals verwacht

**Onbedoeld afsluiten bij het maken van taken of problemen**

*Taken en problemen*

Wanneer een gebruiker een taak of kwestie in een project creeert en buiten de verwezenlijking pop-up klikt, sluit pop-up zonder waarschuwing en alle eerder ingegaan informatie wordt verloren.

**De mogelijkheid om een proefdruk via e-mail naar een dropzone te verzenden is verwijderd**

*[!DNL Workfront Proof]*

Vanaf donderdag 8 september 2022 hebben we de mogelijkheid om een bewijs via e-mail te verzenden naar een dropzone in de stand-alone [!DNL Workfront Proof] product.

U kunt dropzones nog steeds op andere manieren gebruiken om nieuwe proefdrukken en nieuwe versies van proefdrukken naar uw account te verzenden zonder u aan te hoeven melden bij uw account. Zie [Dropzone](https://experienceleague.adobe.com/docs/workfront/using/workfront-proof/work-with-proofs-in-wf-proof/create-proofs-and-files/dropzone.html) voor meer informatie .

+++

+++**Onderhoudsupdate op 6 september 2022**

**Geprojecteerde datums toegevoegd aan de lijst met velden voor aanpasbare projectheaders**

*Projecten*

We hebben de [!UICONTROL Projected Start Date] en [!UICONTROL Projected Completion Date] aan de lijst van gebieden voor klantgerichte projectkopballen wanneer het gebruiken van een lay-outmalplaatje.

**Nieuwe grens met een bevestigingsbericht dat het aantal punten toont die aan een timesheet worden toegevoegd**

*Timesheets*

Wanneer u meer dan 50 punten selecteert om aan een timesheet toe te voegen, ontvangt u nu een bevestigingsbericht dat het aantal punten toont dat aan timesheet moet worden toegevoegd en u de kans geeft om cursus te veranderen en niet alle punten toe te voegen. Alle toegevoegde punten worden automatisch vastgezet aan timesheet en zullen manueel uit huidige en alle toekomstige chronologie moeten worden verwijderd.

+++

+++**Onderhoudsupdate op 2 september 2022**

Voeg de [!UICONTROL Integrations] veld naar de aangepaste koptekst van het project

*Integraties*

U kunt nu de opdracht [!UICONTROL Integrations] aan de douanekopbal van een project wanneer u een lay-outmalplaatje gebruikt. Zodra toegevoegd, zal het gebied een verbinding aan een extern punt tonen verbonden aan het project dat binnen wordt gevestigd [!DNL Salesforce] of [!DNL Anaplan], afhankelijk van uw integratie.

>[!NOTE]
>
>Deze onderhoudsupdate is eerder op 25 augustus 2022 uitgebracht naar de voorvertoningsomgeving en is nu in productie.

+++

+++**Onderhoudsupdate op 1 september 2022**

**Voltooide items uit delegatie verwijderd**

*Delegaties*

Nu worden alleen onvolledige items waarvan de data overeenkomen met de data van een delegatie gedelegeerd aan andere gebruikers wanneer de delegatie van werkitems begint. Als de punten vóór de delegatie begonnen werden voltooid, zullen zij niet worden afgevaardigd. De punten die tijdens het tijdkader van de delegatie worden voltooid zullen op de Lijst van het Werk van het gebied van het Huis voor zowel de afgevaardigde als de aangewezen persoon twee weken blijven alvorens zij automatisch worden verwijderd, als de delegatie niet tijdens deze weken heeft geëindigd.

**Metagegevensupdates voor de [!DNL Adobe Workfront] for [!DNL Experience Manager Assets] en [!DNL Assets Essentials] integratie**

*Integraties*

Metagegevens worden automatisch geactiveerd wanneer u middelen aan een gekoppelde map toevoegt.

Eerder werden metagegevens alleen &#39;push&#39; weergegeven wanneer u een element toevoegt met het gereedschap [!UICONTROL Add new] vervolgkeuzemenu.

**Kan uren in een uitgave niet goedkeuren of afwijzen**

*Problemen*

Wanneer een gebruiker uren op de [!UICONTROL Hours] tabblad van een uitgave, [!UICONTROL Approve] en [!UICONTROL Reject] knoppen ontbreken.

**Als u een uitgave omzet in een project met behulp van een sjabloon, wordt een onjuist foutbericht weergegeven**

*Problemen*

Wanneer het omzetten van een kwestie in een project gebruikend een malplaatje en een fout wordt ontmoet, wordt de gebruiker getoond een pagina met het bericht &quot;[!UICONTROL The Project no longer exists]&quot; in plaats van het juiste foutbericht waarin de oorzaak van de mislukte conversie wordt uitgelegd.

**Kan geen proefdruk maken voor bestanden van meer dan 1,5 GB**

*[!DNL Workfront Proof]*

Als een gebruiker bij het maken van een nieuwe proefdruk een bestand uploadt dat groter is dan 1,5 GB, wordt de bestandsnaam rood en kan de proefdruk niet worden gemaakt.

+++

## Updates in augustus 2022

+++**Onderhoudsupdate op 25 augustus 2022**

**Koppelingen voor werklastverdeling worden onjuist weergegeven in dashboards**

*Dashboards*

Koppelingen voor werklastverdeling worden onjuist weergegeven wanneer ze als externe pagina aan een dashboard worden toegevoegd. In plaats van de unieke weergave of filters te gebruiken die aan de koppeling zijn gekoppeld, gebruikt het dashboard de laatst toegepaste weergave of filters voor werklastbalans.

**Voeg de [!UICONTROL Integrations] veld naar de aangepaste koptekst van het project**

*Projecten*

U kunt nu de opdracht [!UICONTROL Integrations] aan de douanekopbal van een project wanneer u een lay-outmalplaatje gebruikt. Zodra toegevoegd, zal het gebied een verbinding aan een extern punt tonen verbonden aan het project dat binnen wordt gevestigd [!DNL Salesforce] of [!DNL Anaplan], afhankelijk van uw integratie.

>[!NOTE]
>
>Deze onderhoudsupdate is momenteel alleen beschikbaar in de voorvertoningsomgeving. Deze wordt een week na de release Preview vrijgegeven voor Production.

**Aangepaste gegevens blijven niet behouden wanneer u een uitgave omzet in een leeg project**

*Projecten*

Wanneer een gebruiker een kwestie in een leeg project (zonder een malplaatje) omzet, worden de gegevens op berekende gebieden niet overgebracht naar het nieuwe project.

**De fout &quot;van de Planning van de Chronologie wijze&quot;wanneer het veranderen van een datum op een project**

*Projecten*

Wanneer een gebruiker een datum probeert te veranderen op een project dat heeft [!UICONTROL Plan Mode] instellen op [!UICONTROL Manual save] > [!UICONTROL Timeline Planning], verandert de datum niet en de gebruiker ziet een fout.

&quot;[!UICONTROL Timeline Planning mode is available only when timelineDate is loaded. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

**Consistentie bij het openen van de werklastbalans met de Maand-weergave**

*Werklastverdeling*

Nu, toont de Balancer van de Werkbelasting de toegewezen punten van de gebruikers uitgevouwen wanneer het tonen van hen in [!UICONTROL Day], [!UICONTROL Week], of [!UICONTROL Month] weergaven. Vóór deze update werden de toegewezen items weergegeven als uitgevouwen voor de [!UICONTROL Day] en [!UICONTROL Week] weergaven en samengevouwen voor de [!UICONTROL Month] weergeven.


+++

+++**Onderhoudsupdate op 18 augustus 2022**

**&quot;[!UICONTROL Add to Iteration]&quot; en &quot;[!UICONTROL Add to Kanban Board]&quot;-opties niet beschikbaar als inline bewerkingstaken in een rapport worden uitgevoerd**

*Rapporten*

Wanneer een gebruiker een lijst van taken in een rapport bekijkt en opent [!UICONTROL More] (met drie punten), de[!UICONTROL Add to Iteration]&quot; en &quot;[!UICONTROL Add to Kanban Board]&quot;-opties zijn niet beschikbaar in het vervolgkeuzemenu. Als het rapport wordt weergegeven op een dashboard, wordt &quot;[!UICONTROL Add to Iteration]&quot; en &quot;[!UICONTROL Add to Kanban Board]&quot;-opties zijn beschikbaar in het vervolgkeuzemenu.

**Matrixrapporten worden onjuist weergegeven wanneer er wordt geschoven**

*Rapporten*

Wanneer een gebruiker een rapport van de Matrijs bekijkt en scrolt, kunnen sommige visuele elementen van het rapport overlappen of dupliceren.

**[!UICONTROL Milestone]weergave verwijderd uit de projectlijst Timesheets**

*Timesheets*

De [!UICONTROL Milestone] de mening is verwijderd uit de timesheet projectlijst wanneer het toevoegen van een project.

**Hyperlinks in een interactieve proefdruk zijn niet actief**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een interactieve proef bekijkt en op een verbinding of een knoop klikt die een verbinding bevat, wordt de gebruiker niet genomen aan de pagina die de verbinding of de knoop verbindt.

**Ontbrekende tekstvelden van nieuwe proefpagina**

*[!DNL Workfront Proof]*

Op de [!DNL New Proof] pagina, worden veel tekstvelden niet weergegeven (zoals veldlabels, vervolgkeuzemogelijkheden en namen van selectievakjes).

**Gebruikers ontvangen geen meldingen wanneer ze deze in een proefdruk labelen**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een proefdrukopmerking heeft geplaatst, ontvangt hij geen e-mailbericht over de opmerking.

+++

+++**Onderhoudsupdate op 12 augustus 2022**

**Nieuw aanpasbaar koptekstveld toegevoegd aan het begin van de koptekst**

*Kopteksten*

Wanneer u een nieuw veld toevoegt aan een aanpasbare koptekst, wordt het veld nu toegevoegd als het eerste veld aan de linkerkant van de koptekst, of direct na de knop [!UICONTROL Search] in de Lay-outsjabloon. Vóór deze wijziging is het veld toegevoegd als het laatste veld in de koptekst.

+++

+++**Onderhoudsupdate op 11 augustus 2022**

**Kan aangepaste formulieren niet bewerken vanwege een onjuiste tekenlimiet voor beschrijvende tekstvelden**

*Aangepaste formulieren*

Wanneer een gebruiker een aangepast formulier probeert te bewerken en dat aangepaste formulier een [!UICONTROL Descriptive text] in een veld dat momenteel meer dan 512 tekens bevat, kan de gebruiker de bewerkingen niet opslaan in het aangepaste formulier. De volgende fout wordt weergegeven:

&quot;De volgende velden zijn ongeldig: (Veld) is te lang, max. 512 inch

Dit is [!UICONTROL Descriptive text] velden die eerder goed hebben gewerkt, ondanks meer dan 512 tekens.

**Gegevens in velden die door sectie-einde worden verborgen, blijven niet behouden wanneer u een uitgave omzet in een project**

*Aangepaste formulieren*

Wanneer een gebruiker een uitgave in een project omzet, en de kwestie omvat een douaneformulier met gegevens in een sectieonderbreking die kan worden verborgen gebruikend vertoningslogica, worden de gegevens in die sectie niet gedragen aan het nieuwe project.

**Gegevens in velden die door sectie-einde worden verborgen, blijven niet behouden wanneer een aanvraag wordt geconverteerd naar een project**

*Aangepaste formulieren*

Wanneer een gebruiker een verzoek in een project omzet, en het verzoek een douaneformulier met gegevens in een sectieonderbreking omvat die kunnen worden verborgen gebruikend vertoningslogica, worden de gegevens in die sectie niet gedragen aan het nieuwe project.

**Kan aangepaste formulieren niet bewerken vanwege het beschrijvende tekstveld**

*Aangepaste formulieren*

Wanneer een gebruiker een aangepast formulier probeert te bewerken dat een beschrijvend tekstveld bevat, wordt het label van het veld niet gevuld. De gebruiker ziet de fout &quot;[!UICONTROL This field is required]&quot; onder het labelveld en de gebruiker kan het aangepaste formulier vanwege deze fout niet bewerken.

**Kan instructies niet verwijderen uit een aangepast veld in de aangepaste formulierbuilder**

*Aangepaste formulieren*

Wanneer een gebruiker een aangepast veld bewerkt en de bestaande tekst in het dialoogvenster [!UICONTROL Instructions] wordt de tekst niet verwijderd wanneer het veld wordt opgeslagen. De gebruiker kan tekst bewerken, maar niet geheel verwijderen.

**Teamtoewijzing bij het maken van een verzoek wordt niet weergegeven bij een nieuwe aanvraag**

*Verzoeken*

Wanneer een gebruiker een verzoek creeert en een team aan het verzoek toewijst, dan legt het verzoek voor, wordt het team niet toegewezen aan het verzoek dat wordt gecreeerd. Dit is alleen van invloed op teamtoewijzing. De toewijzingsfunctie van de gebruiker functioneert naar behoren.

+++

+++**Onderhoudsupdate op 4 augustus 2022**

Deze kwesties zijn alleen in het nieuwe [!DNL Workfront] ervaring.

Alles [!DNL Workfront Classic] Deze functie is verwijderd op 14 juli 2022.

**Fout bij het wijzigen van de Geplande Voltooiingsdatum in de koptekst van een taak of uitgave**

*Taken en problemen*

Wanneer een gebruiker probeert de [!UICONTROL Planned Completion Date] in de koptekst van een taak of uitgave verandert de datum niet en ziet de gebruiker een fout gelijkend op het volgende:

`500: (Date that user is attempting to change to)/attask/api-internal/(object type)/(object ID)`

+++

## Updates in juli 2022

+++**Onderhoudsupdate op 28 juli 2022**

Deze kwesties zijn alleen in het nieuwe [!DNL Workfront] ervaring.

Alles [!DNL Workfront Classic] Deze functie is verwijderd op 14 juli 2022.

**Fout bij het openen van een item in het dialoogvenster[!UICONTROL Home Work List]**

*[!UICONTROL Home]*

Wanneer een gebruiker een item op zijn [!UICONTROL Home Work List], het item wordt niet geopend en de gebruiker ziet het volgende bericht:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work try refreshing this browser page.]&quot;

**Taken en problemen die aan een gebruiker zijn gedelegeerd, worden niet weergegeven in de lijst met thuiswerk van de gebruiker**

*[!UICONTROL Home]*

Wanneer de gebruiker hun [!UICONTROL Home Work List], worden aan de gebruiker gedelegeerde taken of kwesties niet in de lijst vermeld en is de gebruiker wellicht niet op de hoogte van de delegaties.

**Geplande rapporten worden niet naar alle ontvangers verzonden**

*Rapporten*

Wanneer een gepland rapport wordt verzonden, wordt het niet verzonden naar alle gebruikers in &quot;[!UICONTROL Send to]&quot;. De weggelaten gebruikers zijn willekeurig, en kunnen variëren telkens als het rapport wordt verzonden.

**[!UICONTROL Cannot deselect tasks when attaching template]**

*Sjablonen*

Wanneer een gebruiker een sjabloon koppelt en aanpast, wordt hem gevraagd de selectie op te heffen van taken die hij of zij niet wil opnemen. Geen van de taken wordt echter weergegeven als geselecteerd en de gebruiker kan de selectie ervan niet opheffen.

**Velden met de naam &quot;Landinstelling&quot; hebben nu specifiekere labels**

*Terminologie*

Om de functie van &quot;[!UICONTROL Locale]&quot; velden zijn duidelijker , we hebben hun labels bijgewerkt .

* De &quot;[!UICONTROL Locale]&quot; in het gebruikersprofiel is nu gelabeld &quot;[!UICONTROL Email Locale]&quot;
* De &quot;[!UICONTROL Locale]&quot; veld gevonden in het dialoogvenster [!UICONTROL Setup] >[!UICONTROL System] >[!UICONTROL Customer Info] gebied is nu gelabeld &quot;[!UICONTROL Default Email Locale]&quot;

De functionaliteit van deze velden is niet gewijzigd.

**Problemen bij het maken van tijdbladen**

*Timesheets*

De volgende kwesties zijn gemeld met betrekking tot het opstellen van tijdbladen:

* Wanneer een gebruiker een timesheet voor een Rol probeert te creëren, wordt timesheet niet gecreeerd en de gebruiker ziet de fout &quot;[!UICONTROL User with primary key values 'XXXXXXXXXXX' not found.]&quot;
* Wanneer een gebruiker probeert om een timesheet voor een Team tot stand te brengen, [!UICONTROL typeahead] veld wordt niet gevuld met teams en de [!UICONTROL Create timesheet] is uitgeschakeld.


**Gebieden van [!DNL Workfront Proof] niet bijwerken wanneer een proefdruk wordt gemaakt, verplaatst of gearchiveerd**

*[!DNL Workfront]Proef*

Het bewijs ervaart momenteel indexerende vertragingen. Dit kan van invloed zijn op de gebruikerservaring, waaronder:

* Het juiste aantal proefdrukken wordt niet weergegeven op dashboards
* Mappen worden niet bijgewerkt wanneer een proefdruk wordt gemaakt of verplaatst
* Gearchiveerde proefdrukken blijven op actieve proefdruklijsten.

+++

+++**Onderhoudsupdate (Hot Fix) op 26 juli 2022**

Deze kwesties zijn alleen in het nieuwe [!DNL Workfront] ervaring.

Alles [!DNL Workfront Classic] Deze functie is verwijderd op 14 juli 2022.

**De uren die op timesheet worden getoond zijn verschillend van de lijst van Tijdopnamen**

*Timesheets*

Wanneer een gebruiker een timesheet opent om het te bekijken, zijn de getoonde uren verschillend van wanneer de gebruiker zelfde timesheet in een timesheet lijst bekijkt.


**Verzoek omgezet in project met malplaatje toont groep van verzoekrij, niet groep van malplaatje**

*Verzoeken*

Wanneer een gebruiker een verzoek in een project gebruikend een malplaatje omzet, wordt het nieuwe gecreeerd project geassocieerd met de groep die de verzoekrij, niet de groep bezit die op het malplaatje wordt toegewezen. Dit komt voor alhoewel wanneer het project wordt gecreeerd, de groep verbonden aan het malplaatje in wordt bevolkt [!UICONTROL Group] veld.

+++

+++**Onderhoudsupdate op 21 juli 2022**

Deze kwesties zijn alleen in het nieuwe [!DNL Workfront] ervaring.

Alles [!DNL Workfront Classic] Deze functie is verwijderd op 14 juli 2022.

**Afwijzingsstatus die aan een goedkeuring is gekoppeld, voldoet aan de goedkeuringswerkstroom**

**OPMERKING: Deze functionaliteit is uitgebracht op 22 juli 2022.**

*Goedkeuringen*

Als u een status selecteert die aan een goedkeuringsproces is gekoppeld als de afwijzingsstatus voor een goedkeuringspad, wordt het geweigerde object naar de geselecteerde status verplaatst en wordt deze gemarkeerd als &quot;[!UICONTROL Pending approval]&quot;. Als u bijvoorbeeld [!UICONTROL On Hold] voor de afwijzingsstatus en de [!UICONTROL On Hold] status is gekoppeld aan een goedkeuringsproces, wordt het geweigerde object in de status &quot;[!UICONTROL On Hold- Pending approval]&quot;, waarbij de goedkeuring is vereist.

Vóór deze update heeft het object het goedkeuringsproces voor de afwijzingsstatus overgeslagen en is het object in het dialoogvenster [!UICONTROL On Hold] status.

**Een aangepaste Help-URL configureren**

*[!UICONTROL Main Menu]*

Als uw organisatie een aangepaste interne helpsite heeft, kunt u de [!UICONTROL Main Menu] [!UICONTROL Help] pictogram om naar die site te gaan. Dit is handig als de Help-site informatie bevat over het gebruik van uw organisatie [!DNL Workfront].
Deze aangepaste URL heeft geen invloed op de hoofdkoppeling van de Help in het bovenste gebied van [!DNL Workfront], noch de contextgevoelige hulpverbindingen door [!DNL Workfront], die gebruikers naar de [!DNL Workfront] Help-site.

**Kan Verstreken tijd niet selecteren bij inline bewerken[!UICONTROL Task Duration]**

*Taken*

Wanneer een gebruiker een takenlijst weergeeft en probeert de [!UICONTROL Task Duration], zijn de volgende tijdseenheden niet beschikbaar:

* [!UICONTROL Elapsed Minutes]
* [!UICONTROL Elapsed Hours]
* [!UICONTROL Elapsed Days]
* [!UICONTROL Elapsed Weeks]
* [!UICONTROL Elapsed Months]

**[!UICONTROL My Updates]pagina is leeg**

*Updates*

Wanneer een gebruiker probeert hun [!UICONTROL My Updates] pagina, wordt de pagina niet geladen. De gebruiker kan alleen de [!DNL Workfront] navigatiekop.

**&quot;[!UICONTROL Only Allow SAML 2.0 Authentication]&quot;-instelling ontbreekt bij het kopiëren van een gebruiker**

*Gebruikers*

Wanneer een groepsbeheerder een gebruiker kopieert en &quot;[!UICONTROL Send an invite email to this person]&quot;, de optie &quot;O[!UICONTROL nly Allow SAML 2.0 Authentication]&#39;&#39; selectievakje wordt niet weergegeven zoals u had verwacht. Dit kan zelfs voorkomen wanneer alle toegangs en toestemmingsvereisten voor deze actie worden voldaan aan.

+++

+++**Onderhoudsupdate op 14 juli 2022**

Deze kwesties zijn alleen in het nieuwe [!DNL Workfront] ervaring.

Alles [!DNL Workfront Classic] Deze functie is verwijderd op 14 juli 2022.

**Fout bij opnieuw instellen van wachtwoord**

*Aanmelden*

Wanneer een gebruiker probeert om hun wachtwoord terug te stellen, kunnen zij het niet terugstellen, en zij zien een bericht hen vertellen zij hebben geen toegang. De gebruiker kan zich niet aanmelden bij Workfront.

**Kan niet om meer toegang tot een rapport verzoeken**

*Rapporten*

Wanneer een gebruiker met beperkte toegang tot een rapport probeert om meer toegang tot een rapport te verzoeken, is de optie om meer toegang te verzoeken niet beschikbaar onder [!UICONTROL report actions] -menu.

**Bijgewerkt bevestigingsbericht wanneer het schrappen van een verzoekontwerp**

*Verzoeken*

Bij het negeren van een geschreven verzoek, het bevestigingsbericht dat wordt weergegeven na het klikken op &quot;[!UICONTROL Discard draft]&quot; geeft het volgende weer:

* [!UICONTROL Draft was discarded] (Dit is een melding om u te laten weten dat uw concept is verwijderd)
* [!UICONTROL Undo] (Dit is een koppeling waarop u kunt klikken om de handeling van het verwijderen van het concept te herstellen. Zo blijft het concept behouden in plaats van het te verwijderen.)

Vóór deze wijziging waren de volgende opties beschikbaar:

* [!UICONTROL Draft will be discarded]
* [!UICONTROL Cancel]

**Datumwaarden voor de velden Dagboekinvoer zijn onjuist wanneer ze via de API worden benaderd**

*Updates*

Wanneer een gebruiker een datumwaarde op een voorwerp verandert, en dan wordt de ingang van het Dagboek die die datumverandering vertegenwoordigt betreden door API, de datumwaarden voor [!UICONTROL oldDateVal] en [!UICONTROL newDateVal] wordt geretourneerd door de API is onjuist.

**Fout bij poging opmerking ongedaan te maken**

*Updates*

Wanneer een gebruiker een opmerking ongedaan probeert te maken, wordt de opmerking niet ongedaan gemaakt en wordt de volgende fout weergegeven:

[!UICONTROL Error 403: You do not have sufficient access to delete this Note /attask/api-internal/NOTE]

**Nieuwe beperking voor het aantal tekens in een update in Voorvertoning**

*Updates*

Om de prestaties van [!UICONTROL Updates] hebben we een nieuwe limiet ingevoerd voor het aantal tekens dat u kunt invoeren in een update of in een antwoord op een bestaande update. De nieuwe limiet is 15.000 tekens. Deze update heeft het toegestane aantal tekens voor het gebruik van de API niet gewijzigd. De API-tekenlimiet voor updates is 4.000.

**Fout bij uploaden van bijlage van [!DNL Workfront] voor Outlook-integratie**

*Workfront-integratie*

Wanneer een gebruiker een bijlage probeert te uploaden met de [!DNL Workfront for Outlook] integratie, uploadt de gehechtheid niet, en de gebruiker ziet het volgende bericht:

[!UICONTROL Some attachments have not been uploaded. Reason: Something went wrong with uploading attachments.]

**Bijwerken van e-mailmeldingen controleren**

*[!DNL Workfront]Proef*

Eerder deze maand, als onderdeel van een patch naar de [!DNL Workfront] In productieomgeving hebben we een fout opgelost in het e-mailmeldingssysteem voor proefdrukken. Deze wijziging werd niet meegedeeld in de onderhoudsupdate toen deze werd vrijgegeven. De volgende gegevens zijn toegevoegd aan de [Onderhoudsupdate op 2 juni 2022](#maintenance-update-on-june-2-2022) :

Als gevolg van deze foutoplossingen is het e-mailadres dat wordt gebruikt voor het verzenden van proefdrukmeldingen, gewijzigd.

Eerder bevatte het proefdrukken van e-mailadressen het subdomein van uw organisatie. Meldingen@[bedrijfsdomein].my.workfront.com

Het opgeven van e-mailadressen bevat nu geen subdomein voor organisaties meer. Alle e-mailmeldingen over proefdrukken zijn afkomstig van het volgende adres: notification@my.workfront.com

Dientengevolge, adviseren wij u de volgende acties als u nog niet hebt:

* Werk uw spamfilters bij om e-mails van notification@my.workfront.com te accepteren
* Werk uw lijsten van gewenste personen bij om e-mails van notification@my.workfront.com te accepteren

**Gebruikersopties kunnen niet worden gewijzigd na de eerste configuratie in workflowsjablonen**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een gebruiker aan een Malplaatje van het Werkschema toevoegt, kunnen zij opties vormen. Nochtans, nadat de aanvankelijke configuratie volledig is, kan de gebruiker niet meer het volgende wijzigen:

* &quot;[!UICONTROL Resolve comments and apply actions]&quot; bekwaamheid
* [!UICONTROL "Share proof by tagging]&quot; bekwaamheid
* Proefdrukrol ([!UICONTROL Reviewer], [!UICONTROL Approver], enz.)

**&quot;[!UICONTROL This project's work items]&quot; filter is hersteld in het project[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

Het filter &quot;Werkonderdelen van dit project&quot; is hersteld in het dialoogvenster [!UICONTROL Assigned] gebied wanneer u toegang hebt tot [!UICONTROL Workload Balancer] van een project.

Dit filter wordt nu vermeld onder &quot;[!UICONTROL Suggested]&quot; van de filters voor de [!UICONTROL Assigned Work] gebied van een project [!UICONTROL Workload Balancer].

+++

## Updates in juni 2022

+++**Onderhoudsupdate op 30 juni 2022**

**De weergave van [!UICONTROL Workload Balancer] gedurende één week**

*[!UICONTROL Workload Balancer]*

Op basis van de feedback die we van veel klanten hebben ontvangen, hebben we nu een optie toegevoegd om de [!UICONTROL Workload Balancer] gedurende een week. Voordat u deze update uitvoert, kunt u de [!UICONTROL Workload Balancer] gedurende 4, 6 en 12 weken. Met deze update hebben we ook de optie van 12 weken gewijzigd in 3 maanden.

**Het deelvenster Delegatie is nu beschikbaar via Workload Balancer**

*[!UICONTROL Workload Balancer]*

OPMERKING: Deze update bestaat alleen in de voorvertoningsomgeving. De functionaliteit die aan deze update is gekoppeld, is beschikbaar in Production met de release 22.3.

U kunt de afgevaardigden van een taak of een kwestie van de Balancer van de Werkbelasting nu bekijken. Wanneer u een taak of een probleem toewijst vanuit Workload Balancer, kunt u een lijst met toewijzingen en een lijst met afgevaardigden voor de taak of kwestie weergeven als deze momenteel zijn gedelegeerd.

**Kan eindpuntinformatie in API Explorer niet openen**

*API*

Wanneer een gebruiker de [!DNL API Explorer] en klikt op een eindpunt, wordt de informatie over het eindpunt niet weergegeven.

**Problemen met [!UICONTROL Details] wanneer u de[!UICONTROL Home Calendar]**

*Home*

Wanneer een gebruiker de [!UICONTROL Home Calendar] en klikt op een taak, kan één van het volgende voorkomen:

* De [!UICONTROL Details] wordt kort weergegeven en verdwijnt vervolgens. De gebruiker heeft geen toegang tot de details.
* De [!UICONTROL Details] wordt niet weergegeven. De gebruiker heeft geen toegang tot de details.
* De [!UICONTROL Details] wordt weergegeven, maar bevindt zich niet op de juiste locatie. De gebruiker kan op de knop klikken om de details te openen.

+++

+++**Onderhoudsupdate (Hot Fix) op 24 juni 2022**

**De datumkiezer wordt niet gesloten tijdens het bewerken van een aangepast formulier**

*Aangepaste Forms*

Wanneer een gebruiker een aangepast formulier bewerkt en probeert een datum te wijzigen, wordt de datumkiezer niet gesloten wanneer de datum wordt geselecteerd. De gebruiker kan de datumkiezer niet sluiten door op te slaan, te annuleren of buiten de datumkiezer te klikken.

Dit is gemeld op de volgende gebieden:

* [!UICONTROL Updates] gebied
* [!UICONTROL Home]

**Gebruiker kan zichzelf niet verplaatsen naar een ander proefgebied**

*Proefdrukken*

Wanneer een gebruiker de [!UICONTROL Proof Workflow] van een proef en pogingen om zich aan een verschillend stadium van de proef te slepen, breekt de naam van de gebruiker terug naar het originele stadium, en zij worden niet toegevoegd aan het gewenste stadium.

+++

+++**Onderhoudsupdate op 23 juni 2022**

**[!UICONTROL Cannot add new request through dashboard]**

*Dashboards*

Wanneer een gebruiker een dashboard op een project bekijkt en een nieuw verzoek probeert toe te voegen door te klikken op [!UICONTROL +New Request] , reageert de knop niet en kan de gebruiker geen nieuwe aanvraag toevoegen.

**Fout bij weergeven van items in Home Worklist**

*[!UICONTROL Home]*

Wanneer een gebruiker hun [!UICONTROL Home Work List] en klikt u op een item in het dialoogvenster [!UICONTROL Approvals I've Submitted] op de pagina wordt de volgende fout weergegeven:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

Als de gebruiker de pagina vernieuwt, klikt u op een item in het dialoogvenster [!UICONTROL Work List], wordt de fout weergegeven. De kwestie beïnvloedt niet meer slechts punten in [!UICONTROL Approvals I've Submitted] sectie.

**De sectie Aangepast van een object bevat resultaten die niet in dat object voorkomen**

*Objecten*

Wanneer een gebruiker een [!UICONTROL custom] In de aangepaste sectie worden items weergegeven die geen deel uitmaken van dat object. Dit is gemeld wanneer de aangepaste sectie rechtstreeks aan het object wordt toegevoegd en wanneer een aangepaste sectie wordt toegevoegd via een lay-outsjabloon.

**Taken worden verplaatst naar een onjuist project**

*Taken*

Wanneer een gebruiker taken van Project A aan Project B beweegt, dan bewegingen meer taken van Project A aan Project C, de taken oorspronkelijk die aan Project B oorspronkelijk werden verplaatst op Project C verschijnen.

**Sommige knoppen/pictogrammen werken niet bij het openen van [!UICONTROL Workload Balancer] van een gedeelde koppeling of een gedeeld dashboard**

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker naar de [!UICONTROL Workload Balancer] via een gedeelde koppeling of een koppeling in een dashboard en wanneer wordt geprobeerd het element boven aan het scherm te gebruiken, werken de elementen niet. Dit is gerapporteerd voor de volgende elementen:

* [!UICONTROL Today]
* Pijlen naar achteren en naar voren
* [!UICONTROL Weeks]
* Kalenderpictogram (datumkiezer)

+++

+++**[!DNL Workfront]Scenario Planner Maintenance Update op 23 juni 2022**

**Gebruikers met [!UICONTROL Manage] machtigingen voor een abonnement kunnen deze delen met anderen**

Als gebruiker met [!UICONTROL Manage] machtigingen voor een abonnement in de [!DNL Scenario Planner]kunt u deze nu delen met andere gebruikers. Vóór deze update kon alleen de maker van het abonnement het abonnement met andere gebruikers delen.

+++

+++**Onderhoudsupdate op 16 juni 2022**

**De beheerder van de groep kan geen leden toevoegen aan groep**

*Groepen*

Wanneer een groepsbeheerder een gebruiker aan een groep probeert toe te voegen, dropdown om de gebruiker te selecteren bevolkt niet. De groepsbeheerder kan geen gebruikers selecteren en kan daarom geen gebruikers aan de groep toevoegen.

**Aangepaste kwarten worden niet weergegeven wanneer u een filter instelt**

*Filters*

Wanneer een gebruiker een filter en filters op een datumveld maakt, bevat het vervolgkeuzemenu met beschikbare operatoren voor het datumveld geen onlangs toegevoegde aangepaste kwartalen.

**Fout bij het omzetten van een uitgave in een project via een sjabloon**

*Projecten*

Wanneer een gebruiker een uitgave via een malplaatje probeert om te zetten in een project, en de kwestie heeft een douaneformulier dat een admin-enige sectie bevat, wordt de kwestie niet omgezet en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

**Verzoeken worden verzonden zonder dat de vereiste velden zijn ingevuld**

*Verzoeken*

Wanneer een gebruiker een aanvraag maakt en de vereiste velden niet invult, wordt de aanvraag verzonden zonder gegevens in de vereiste velden. Het verwachte gedrag is dat de aanvraag niet wordt verzonden en dat de gebruiker op de hoogte wordt gesteld dat hij de vereiste velden moet invullen voordat hij de aanvraag indient.

**Nieuwe aangepaste kwartalen lijken niet te zijn opgeslagen**

*Instellen*

Wanneer een gebruiker een nieuw douanekwart van het gebied van Projecten van Opstelling toevoegt en klikt [!UICONTROL Save], is er geen visuele indicatie van de save. De gebruiker ziet geen succesbericht en de [!UICONTROL Save] nog steeds aanwezig en actief. Als de gebruiker de pagina echter vernieuwt, ziet hij of zij dat de nieuwe kwartalen worden weergegeven in de lijst met aangepaste kwartalen.

Als de gebruiker een nieuw kwartaal toevoegt, klikt u op [!UICONTROL Save], ontvangt geen aanwijzing van sparen, voegt een extra kwart toe zonder de pagina te verfrissen, en klikt [!UICONTROL Save] het tweede toegevoegde kwart wordt mogelijk niet opgeslagen.

**[!UICONTROL Team Work Requests]pagina is leeg**

*Teams*

OPMERKING: Dit probleem doet zich alleen voor in de voorvertoningsomgeving.

Wanneer een gebruiker de opdracht [!UICONTROL Work Requests] op een teampagina is de pagina leeg. De gebruiker kan de bovenste navigatiebalk zien, maar geen pagina-inhoud.

+++

+++**Onderhoudsupdate op 9 juni 2022**

**Kan objecten niet selecteren waarin moet worden gefilterd [!UICONTROL Portfolio Optimizer] voorkeuren**

*Portfolio*

Wanneer een gebruiker zich in de [!UICONTROL Portfolio Optimizer] en geeft de [!UICONTROL Project Filters] in de [!UICONTROL Preferences] zijn de selectievakjes naast de objecten niet beschikbaar. De gebruiker kan selectievakjes niet in- of uitschakelen en kan daarom geen objecten selecteren om te filteren.

**Kan niet wijzigen [!UICONTROL Planned Start Date] of [!UICONTROL Planned Completion Date] wanneer &quot;[!UICONTROL Schedule From]&quot; is niet gecontroleerd**

*Projecten*

Wanneer een gebruiker de opdracht [!UICONTROL Planned Start Date] of [!UICONTROL Planned Completion Date] van een project en de[!UICONTROL Schedule From]&quot; optie voor dat project is niet gecontroleerd, [!UICONTROL Planned Start Date] en [!UICONTROL Planned Completion Date] gebieden zijn uitgeschakeld en de gebruiker kan deze datums niet bewerken.

**Kan toegangsniveau van gebruikers niet bewerken**

*Gebruikers*

Wanneer een gebruiker die toegang tot de Planner heeft en waartoe User Admin (Group Users)-toegang behoort, probeert gebruikers te bewerken in de groep waarvoor hij of zij een beheerder is, wordt [!UICONTROL Access] niveauveld is uitgeschakeld en de gebruiker kan het toegangsniveau niet bewerken.

+++

+++**[!DNL Workfront Scenario Planner]Onderhoudsupdate op 9 juni 2022**

**Het formaat van het linkerdeelvenster wijzigen in het dialoogvenster[!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

U kunt nu de grootte van het linkerdeelvenster wijzigen in een abonnement, in het dialoogvenster [!DNL Scenario Planner]. Hierdoor kunnen langere initiatiefnamen volledig worden weergegeven. Voorafgaand aan deze update werden langere initiatiefnamen afgebroken.

+++

+++**[!DNL Workfront Fusion]Onderhoudsupdate op 9 juni 2022**

**Gegevens uit aangepaste formulieren niet beschikbaar in [!DNL Workfront Fusion] [!DNL Workfront] modules**

*[!DNL Workfront Fusion]*

Wanneer een gebruiker een [!DNL Workfront] module in [!DNL Workfront Fusion]en pogingen om uitvoerbestanden voor de module te selecteren, zijn velden van aangepaste formulieren niet zichtbaar. Dit gebeurt wanneer het aangepaste formulier wordt gemaakt voor één type [!DNL Workfront] en er is een ander type aan toegevoegd. [!DNL Workfront Fusion] Hiermee geeft u alleen velden weer van aangepaste formulieren die oorspronkelijk voor het geselecteerde objecttype zijn gemaakt.

**Kan niet schuiven om alle uitgevoerde scenario&#39;s weer te geven**

*[!DNL Workfront Fusion]*

Wanneer een gebruiker de uitvoeringshistorie van een scenario bekijkt en naar beneden probeert te scrollen om meer uitvoeringen te bekijken, houden de executies ladend op en de gebruiker kan hen niet bekijken. Bovendien kan de gebruiker niet naar de meest recente uitvoeringen terugschuiven.

+++

+++**Onderhoudsupdate op 2 juni 2022**

**[!UICONTROL Portfolio Optimizer]toont een score van 0 wanneer het gebruiken van andere taal dan het Engels**

*Portfolio*

Wanneer een gebruiker [!DNL Workfront] in een andere taal dan het Engels en wordt de [!UICONTROL Portfolio Optimizer]De score wordt weergegeven als 0. Dit kan zelfs gebeuren wanneer de bedrijfscase niet volledig is.

**Berekende veldwaarden zijn onjuist wanneer u een project maakt op basis van een sjabloon**

*Projecten*

Wanneer een gebruiker een project van een malplaatje creeert dat berekende gebieden omvat, zijn de gebiedswaarden die op het nieuwe project verschijnen onjuist.

**Kan niet bewerken [!UICONTROL Conditions] in [!UICONTROL Project Preferences] gebied van[!UICONTROL Setup]**

*[!UICONTROL Setup]*

Wanneer een gebruiker probeert te bewerken [!UICONTROL Conditions] in de [!UICONTROL Project Preferences] gebied van [!UICONTROL Setup], is de pagina leeg.

**Nieuwe beperking voor het aantal tekens in een update in Voorvertoning**

*[!UICONTROL Workload Balancer]*

>[!NOTE]
>
>Deze update is alleen van toepassing op de voorvertoningsomgeving.

Om de prestaties van het gebied van Updates te verbeteren, hebben wij een nieuwe grens aan het aantal karakters geïntroduceerd die u in een update of een antwoord op een bestaande update kunt ingaan. De nieuwe limiet is 15.000 tekens. Deze update heeft het toegestane aantal tekens voor het gebruik van de API niet gewijzigd. De API-tekenlimiet voor updates is 4.000. Updates voor aangepaste velden voor Type Typehead in Workload Balancer-filters

We steunen nu filters die gebaseerd zijn op de [!UICONTROL Typeahead] typ aangepaste velden in het deelvenster Werklastbalans. Vóór deze patch was het filteren voor dit type aangepaste velden niet mogelijk in Workload Balancer.

**Kan machtigingen voor een gebruikersrol niet bewerken**

*[!DNL Workfront Proof]*

Wanneer een gebruiker probeert om &quot;[!UICONTROL Resolve comments and apply actions]&quot; of &quot;[!UICONTROL Share a proof by tagging]&quot; machtigingen voor de rol van een gebruiker in [!DNL Workfront Proof], worden de wijzigingen niet opgeslagen. De gebruiker krijgt een bericht dat het malplaatje is bijgewerkt, maar als de gebruiker de roltoestemmingen opnieuw opent kunnen zij zien dat de veranderingen niet werden bewaard.

+++


## Updates in mei 2022

+++**Onderhoudsupdate op 26 mei 2022**

Deze kwesties zijn alleen in het nieuwe [!DNL Workfront] ervaring. [!DNL Adobe Workfront Classic] wordt niet meer ondersteund.

Alles [!DNL Workfront Classic] Deze functie wordt in juli 2022 verwijderd. Ga zo snel mogelijk over naar de nieuwe ervaring.

**Bijgewerkte scheidingstekens voor broodkruimels**

*[!DNL Workfront]*

OPMERKING: Deze update is gepubliceerd op 24 mei 2022.

We hebben de scheidingstekens voor broodkruimels bijgewerkt op alle gebieden waar er broodkruimels beschikbaar zijn. De objecten in de broodkruimels worden nu gescheiden door pijpen (|). Vóór deze update werden ze gescheiden door slashes (/).

**Kan aangepaste formulieren met sectie-einden niet bewerken**

*Aangepaste Forms*

Wanneer een gebruiker een aangepast formulier met een sectie-einde probeert te bewerken, kan het formulier niet worden bewerkt. De volgende melding wordt weergegeven:

[!UICONTROL Specified section break security cannot be applied on all object types]

**Problemen bij het afdrukken van dashboards naar PDF**

*Dashboards*

De volgende problemen zijn gemeld bij het afdrukken van een dashboard op een PDF: De PDF drukt niet elke rij in het rapport af. Waar regels ontbreken, wordt alleen lege ruimte weergegeven.
De PDF omvat lege ruimten tussen de kolomkopballen en de eerste rij van het rapport.

**[!DNL Portfolio Optimizer]toont een score van 0 wanneer het gebruiken van andere taal dan het Engels**

*Portfolio*

Wanneer een gebruiker [!DNL Workfront] in een andere taal dan het Engels en wordt de [!UICONTROL Portfolio Optimizer]De score wordt weergegeven als 0. Dit kan zelfs gebeuren wanneer de bedrijfscase niet volledig is.

**Sommige aangepaste formulieren worden niet weergegeven wanneer u een sjabloon bewerkt**

*Sjablonen*

Wanneer een gebruiker de aangepaste formulieren op een sjabloon probeert te bewerken door op [!UICONTROL Edit] in de koptekst van de sjabloon: [!UICONTROL Edit Template] wordt slechts een van de aangepaste formulieren weergegeven die aan de sjabloon zijn gekoppeld.

**Gedeelde koppeling naar werklastbalans geeft toegewezen werk onjuist weer**

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker de [!UICONTROL Workload Balancer] met behulp van een gedeelde koppeling [!DNL Workload Balancer] include [!UICONTROL Assigned Work] in de [!UICONTROL Unassigned Work] sectie. [!UICONTROL Assigned Work] heeft geen aparte sectie. Wanneer de gebruiker de [!UICONTROL Workload Balancer] zonder gebruik te maken van de gedeelde koppeling, [!UICONTROL Assigned Work] worden weergegeven zoals verwacht.

+++

+++**Onderhoudsupdate op 19 mei 2022**

**Kan geen proefdruk maken van een[!DNL PowerPoint]**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een proef probeert tot stand te brengen van een [!DNL PowerPoint] dat een grafiek bevat, mislukt het maken van de proefdruk.

**Kan geen proefdruk maken van een [!UICONTROL Word] document**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een proef probeert tot stand te brengen van een [!DNL Word] In een document met een grafiek kan de proefdruk niet worden gemaakt.

**Kan geen aangepast bericht toevoegen tijdens het delen van een proefdruk**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een proefdruk weergeeft, wordt het dialoogvenster [!UICONTROL Share proof] en selecteert het [!UICONTROL Add custom message] , kan de gebruiker niet in het tekstvak typen dat wordt geopend. Wanneer de gebruiker in dit vak probeert te typen, verdwijnt het vak direct.

**Kan proefdruk niet sluiten**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een proefdruk weergeeft en deze probeert te sluiten, ontbreekt in de rechterbovenhoek van de proefdruk de X om de proefdruk te sluiten.

**Kan groepsbeheerder toevoegen of verwijderen**

*Groepen*

Als een gebruiker een [!UICONTROL Group] pagina en probeert een groepsbeheerder toe te voegen of te verwijderen door [!UICONTROL Group Administrators] in de koptekst worden de wijzigingen niet opgeslagen en ziet de gebruiker de volgende fout:

[!UICONTROL Error Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Horizontale schuifbalkblokitem aan einde van lijst**

*Projecten*

Wanneer een gebruiker een lijst weergeeft met een weergave die buiten het scherm valt, blokkeert de horizontale schuifbalk de weergave van het laatste item in de lijst.

**&quot;[!UICONTROL Unexpected error]&quot; wanneer het omzetten van een kwestie in een project gebruikend een malplaatje**

*Lijsten*

Wanneer een gebruiker een uitgave in een project probeert om te zetten gebruikend een malplaatje, zet de kwestie niet om en de gebruiker ziet het volgende bericht:

[!UICONTROL An unexpected error happened]

**De [!UICONTROL Status] veld in een tijdlijnweergave is nu alleen-lezen**

*Timesheets*

We hebben de [!UICONTROL Status] in een tijdlijnweergave alleen-lezen te zijn. Voorafgaand aan deze verandering, konden de gebruikers het statuut van een timesheet inline uitgeven dat hen toestaat om het besluit van timesheet fiatteurs met voeten te treden.

+++

+++**Onderhoudsupdate op 12 mei 2022**

**[!UICONTROL Save]de knop houdt niet op met laden wanneer u een project bewerkt**

*Projecten*

Wanneer een gebruiker een project bewerkt en probeert op te slaan, wordt het volgende opgemerkt: [!UICONTROL Save] wordt het woord &quot;[!UICONTROL Loading].&quot; Als de gebruiker op deze knop klikt om de wijzigingen in het project op te slaan, reageert de knop niet en worden de wijzigingen niet opgeslagen.

**Veldlabels worden niet weergegeven wanneer u een object weergeeft in[!UICONTROL Home]**

*Home*

Wanneer een gebruiker een object in zijn/haar [!UICONTROL Home Work List], het gebied rechts van het [!UICONTROL Home Work List] die het object weergeeft, bevat geen veldlabels. De veldwaarden zijn aanwezig.

**Quick Filter richt zich niet automatisch op zoekbalk**

*Lijsten*

Wanneer een gebruiker in een lijst is en op het vergrootglas klikt om snel te filteren, begint het typen en wordt de tekst niet weergegeven. Dit komt doordat de focus op het vergrootglaspictogram blijft en niet op de zoekbalk.

Wanneer u op de zoekbalk klikt, wordt de focus overgedragen en kan de gebruiker de tekst van zijn zoekopdracht invoeren.

**Gebruikers kunnen velden in een rapport niet inline bewerken**

*Rapporten*

Wanneer een gebruiker een veld in een rapport probeert te bewerken en dat veld uit een aangepast formulier wordt gehaald, kan de gebruiker het veld niet bewerken. Dit gebeurt wanneer het aangepaste formulier oorspronkelijk is gemaakt voor een ander objecttype dan het object waaraan het is gekoppeld.

**Label- en knoptekst is niet zichtbaar bij het maken van een proefdruk**

*[!DNL Workfront Proof]*

OPMERKING: Dit probleem doet zich alleen voor in de voorvertoningsomgeving.

Wanneer een gebruiker een proef probeert te creëren, is de tekst niet zichtbaar voor opties of knopen. Daarom weet de gebruiker niet wat elke optie of knoop vertegenwoordigt, en kan niet de proef vormen.

+++

+++**Onderhoudsupdate op 5 mei 2022**

**Kan geen nieuwe factureringsrecord toevoegen**

*Projecten*

Wanneer een gebruiker zich in de [!UICONTROL Billing Records] van een project [!UICONTROL New Billing Record] Als de gebruiker een nieuwe Factuurrecord probeert toe te voegen, worden de velden voor een nieuwe Factuurrecord niet weergegeven en kan de Factuurrecord niet worden gemaakt.

**Fout bij maken van bulktoewijzing in[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker taken in het dialoogvenster [!DNL Workload Balancer] van een project wordt de gebruiker omgeleid naar een pagina met het volgende bericht:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

De gebruiker kan pas vanaf deze pagina navigeren nadat de pagina is vernieuwd.

**Bijgewerkte navigatie om te openen [!UICONTROL Summary] voor taken en problemen in het[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

Klik nu gewoon op een taak of probleembalk in het dialoogvenster [!UICONTROL Workload Balancer] Hiermee opent u het deelvenster Samenvatting. Voordat deze update werd uitgevoerd, moest u op de knop [!UICONTROL Open Summary] op de werkbalk en klik vervolgens op de taak of het probleem. Dit was een verwarrende ervaring gebleken die nu is gecorrigeerd. U kunt ook op de knop [!UICONTROL More] naast de naam van de taak of uitgave en klik vervolgens op [!UICONTROL Open Summary].

**De beheerder van de groep kan geen details van gebruikers in de groep bekijken**

*Gebruikers*

Wanneer een gebruiker die aan een toegangsniveau wordt toegewezen dat omvat [!UICONTROL User Admin (Group Users)] toegang het plaatsen probeert om details van een gebruiker in hun groep te bekijken, zien zij de volgende fout:

&quot;[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

**Kan aangepaste groepsstatus niet verwijderen**

*Groepen*

Wanneer een gebruiker een status van een aangepaste groep probeert te verwijderen uit het dialoogvenster [!UICONTROL Group] pagina, wordt de pagina leeg gelaten en wordt de status niet verwijderd.

**De instellingen voor e-mailwaarschuwingen in het gedeelte Contacten en in Gebruikersdetails zijn inconsistent**

*[!DNL Workfront Proof]*

Instellingen voor e-mailwaarschuwingen worden weergegeven in het dialoogvenster [!UICONTROL Contacts] gebied van [!DNL Workfront Proof] voor een bepaalde gebruiker anders zijn dan de instelling voor e-mailwaarschuwingen in de [!UICONTROL User Details].

**Kan het gereedschap Tekst niet gebruiken wanneer u een opmerking maakt over een proefdruk**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een opmerking maakt over een proefdruk en probeert het dialoogvenster [!UICONTROL Text] wordt het gereedschap niet geopend en ziet de gebruiker het volgende bericht:

&quot;[!UICONTROL Text data for this page is still downloading. Please wait.]&quot;

**E-mails met bewijs gaan naar de primaire e-mail van de gebruiker**

*[!DNL Workfront Proof]*

We zijn bezig met het aanpassen van de manier waarop e-mailmeldingen met proefdrukken worden verzonden. Meldingen gaan nu naar het primaire e-mailadres van de gebruiker in plaats van naar het alias-e-mailadres dat door het systeem wordt gegenereerd.

Voor meer informatie over waarom het systeem alias e-mails produceert, zie de synchronisatie van de Gebruiker tussen Adobe [!DNL Workfront] en [!DNL Workfront Proof].

+++

## Updates in april 2022

+++**Onderhoudsupdate op 28 april 2022**

**Kan niet schuiven naar [!UICONTROL Save] knop tijdens het bewerken van een timesheet**

*Timesheets*

Wanneer een gebruiker een tijdpagina bewerkt, kan hij of zij niet ver genoeg schuiven om de [!UICONTROL Save] en kan daarom de tijdpagina niet bewerken.

**Elektronische handtekening controleert nu de federatie-id**

*Proefdrukken*

Wanneer u een bewijs elektronisch ondertekent, controleert het systeem nu de federatie-id als u SSO hebt ingesteld in [!DNL Workfront Proof], naast uw e-mail in [!DNL Workfront].

Eerder controleerde het systeem alleen uw e-mail in Workfront.

+++

+++**Onderhoudsupdate (Hot Fix) op 25 april 2022**

**[!UICONTROL Workload Balancer]niet laden**

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker de opdracht [!UICONTROL Workload Balancer], de koptekst en de linkernavigatie worden geladen, maar de inhoud van Workload Balancer wordt niet geladen. De gebruiker ziet opvlammende grijze vierkanten in plaats van gegevens. Soms wordt een deel van de inhoud geladen, maar ziet de gebruiker nog steeds flitsende grijze vierkantjes waar de ontbrekende gegevens zich bevinden.

+++

+++**Onderhoudsupdate op 21 april 2022**

**Als u een taak toevoegt, springt de pagina omlaag**

*Taken*

Wanneer een gebruiker een taak toevoegt onder een bestaande taak in een lijst, springt de pagina naar een lagere taak in de lijst. Hoewel de nieuwe taak op de juiste plaats is, moet de gebruiker omhoog scrollen om van het de plaats te bepalen.

**Gebruikers die aan een proefdruk zijn toegevoegd, hebben geen toegang tot het werkitem van de proefdruk in[!DNL Workfront]**

*Proefdrukken*

Als een gebruiker aan een werkgebied in de werkstroom van een proefdruk wordt toegevoegd, wordt de gebruiker niet toegevoegd aan het delen van het Document en krijgt geen toestemmingen aan het het werkpunt van de proef in [!DNL Workfront]. Wanneer de gebruiker zich [!DNL Workfront] en pogingen om het het werkpunt te openen de proef aan wordt vastgemaakt, zien zij het volgende bericht:

&quot;[!UICONTROL You do not have sufficient access to view this (object)]&quot;

Deze kwestie is specifiek voor reeds gecreeerd proefdrukken en gebruikers die na het feit worden toegevoegd. Gebruikers aan de workflow toevoegen voordat het maken van proefdrukken werkt zoals u had verwacht.

**Kan geen e-mail voor opnieuw instellen van wachtwoord verzenden vanuit[!DNL Workfront]**

*Gebruikers*

Wanneer een gebruiker een e-mail probeert te verzenden om het wachtwoord opnieuw in te stellen vanuit een gebruikerslijst in [!DNL Workfront], is de optie om de e-mail te verzenden niet beschikbaar.

**Knoppenweergave &quot;[!UICONTROL Start Issue]in plaats van &quot;[!UICONTROL Start Request]&quot;**

*Verzoeken*

Wanneer een gebruiker een verzoek bekijkt dat aan zijn team is toegewezen, zien zij &quot;[!UICONTROL Start Issue]&quot; in de koptekst in plaats van een &quot;[!UICONTROL Start Request]&quot;.

**&quot;[!UICONTROL Undo comment]&quot;-optie verwijdert getagde gebruikers**

*Updates*

Wanneer een gebruiker een andere gebruiker in een opmerking van tags voorziet, wordt de opmerking geplaatst en wordt &quot;[!UICONTROL Undo comment]&quot;, wordt de opmerking op de gebruikelijke manier in een updatevak weergegeven, maar de gelabelde gebruiker bevindt zich niet in de [!UICONTROL Tagged users] doos.

**Kan niet schuiven bij gebruik [!UICONTROL Milestone] weergave in een rapport**

*Rapporten*

Wanneer een gebruiker een rapport weergeeft en de optie [!UICONTROL Milestone] In de pagina wordt de Mijlpaal-weergave weergegeven, maar de gebruiker kan niet langer schuiven. De gebruiker kan geen Mijlpalen weergeven die verder naar beneden op de pagina zouden zijn.

**Onjuiste valuta wanneer rapport wordt weergegeven op dashboard**

*Rapporten*

Wanneer een gebruiker een rapport in een dashboard bekijkt, is de valuta die in het rapport wordt gebruikt onjuist. Wanneer de gebruiker het rapport buiten het dashboard bekijkt, is de valuta correct.

**Voltooid filter geeft het voltooide werkitem niet weer**&#x200B; s

*[!UICONTROL Home]*

Wanneer een gebruiker hun [!UICONTROL Home Work List] met de [!UICONTROL Completed] geselecteerde, voltooide werkitems worden niet weergegeven in de lijst. Wanneer de [!UICONTROL All] is geselecteerd. Voltooide items worden in de lijst opgenomen en tonen aan dat de voltooide items bestaan.

**[!DNL Workfront]niet laden**

*[!DNL Workfront]*

Wanneer een gebruiker zich aanmeldt [!DNL Workfront], lijkt de pagina vast te zitten in een lus van omleidingen of vernieuwingen en wordt niet geladen.

+++

+++**Onderhoudsupdate op 14 april 2022**

**Kan geen taak van een rapport over een douanesectie op een taak toevoegen**

*Taken*

Wanneer een gebruiker een douanesectie op een taak bekijkt, en de sectie een taakrapport bevat, kan de gebruiker geen taak van dat rapport toevoegen. De [!UICONTROL Add Task] de knoop benadrukt het rapport, maar opent geen venster voor de gebruiker om een taak toe te voegen.

**Gereed op verkeerde locatie wanneer u een weergave bewerkt**

*Weergaven*

Wanneer een gebruiker een weergave bewerkt, [!UICONTROL Done] verschijnt hoger op het scherm en kan tekst overlappen.

De gebruiker kan de weergave op de gebruikelijke manier bewerken. Dit heeft geen invloed op de functionaliteit.

**Kan niet schuiven bij gebruik [!UICONTROL Milestone] weergave in een rapport**

*Rapporten*

Wanneer een gebruiker een rapport weergeeft en de optie [!UICONTROL Milestone] In de pagina wordt de Mijlpaal-weergave weergegeven, maar de gebruiker kan niet langer schuiven. De gebruiker kan geen Mijlpalen weergeven die verder naar beneden op de pagina zouden zijn.

**Leeg scherm bij weergeven van updates**

*Updates*

Wanneer een gebruiker updates weergeeft en het scherm schuift om updates verder naar beneden te bekijken, wordt het scherm leeg en kan de gebruiker geen updates zien.

**Fout bij het bulksgewijs toewijzen van gebruiker aan een taak die niet is toegewezen aan de rol van de gebruiker**

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker in de [!UICONTROL Workload Balancer] pogingen om taken toe te wijzen aan een gebruiker wiens Rol van de Baan niet de rol aanpast die aan de taken wordt toegewezen, ziet de gebruiker een bericht dat de taak zal worden toegewezen gebruikend de primaire Rol van de Baan van de toegewezen gebruiker. Wanneer de gebruiker echter op &quot;[!UICONTROL Assign],&quot; de taken worden niet toegewezen en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Error. The server encountered an unknown error.]&quot;

+++

+++**Onderhoudsupdate op 7 april 2022**

**Gebruikers die aan proefdrukken zijn toegevoegd, hebben onjuiste rollen**

*Proefdrukken*

Wanneer een gebruiker een andere gebruiker aan een proef toevoegt, wordt de rol van die gebruiker op de proef geplaatst als &quot;[!UICONTROL Read-only]&quot; ondanks de feitelijke proefdrukrol van de gebruiker.

**Kan geen e-mail voor opnieuw instellen van wachtwoord verzenden aan gebruiker**

*Gebruikers*

Wanneer een gebruiker een wachtwoordinstelling naar een andere gebruiker probeert te verzenden, ziet hij of zij dat de instelling [!UICONTROL Send Forgot Password Email] is niet beschikbaar in het dialoogvenster [!UICONTROL More] -menu.

**[!UICONTROL Update All]verzendt updates naar gebruikersprofielen in plaats van project**

*Updates*

Wanneer een gebruiker de [!UICONTROL People] gebied van een project en selecteert het [!UICONTROL Update All] en voert u vervolgens een update in. De update wordt niet naar het project zelf gepost. In plaats daarvan wordt het naar de individuele gebruikersprofielen van elke gebruiker op het project gepost.

**Te veel pagina&#39;s tijdens afdrukken van updates**

*Updates*

Wanneer een gebruiker een updatestream bekijkt die meer dan één gedrukte pagina zou zijn, en probeert om de pagina te drukken, toont het drukscherm dat het aantal pagina&#39;s ver boven het daadwerkelijke aantal pagina&#39;s is nodig om de updates te drukken. Als de gebruiker vervolgens probeert af te drukken naar PDF, mislukt het maken van de PDF.

**Gebruikers kunnen niet de volledige lijst met entiteiten zien die met een rapport worden gedeeld wanneer &quot;[!UICONTROL Visible System-Wide]&quot; instelling is ingeschakeld**

*Rapporten*

Wanneer het delen van rapporten met veelvoudige entiteiten die in [!UICONTROL Report Access] kunnen gebruikers niet naar de onderkant van de lijst bladeren om de volledige lijst weer te geven wanneer &quot;[!UICONTROL Visible System-Wide]Instelling ingeschakeld.

**Onjuiste valuta in rapporten**

*Rapporten*

Als een gebruiker de valuta van een project plaatst om anders te zijn dan de standaardmunt, dan bekijkt een rapport over dat project, verschijnt de munt als standaardmunt in plaats van de munt van het project.

**Laatst weergegeven gegevens worden niet bijgewerkt in [!UICONTROL Report Usage] rapporten**

*Rapporten*

Wanneer een gebruiker een rapport bekijkt dat informatie betreffende de laatste tijd toont het rapport werd bekeken, kan die informatie leeg zijn of oude gegevens kunnen zijn. Dit probleem betreft onder meer de volgende velden:

* [!UICONTROL Last Viewed By]
* [!UICONTROL Last Viewed Data]
* [!UICONTROL Last X Viewers]
* [!UICONTROL Views This Month / Quarter / Year]

**Voltooide taken weergeven in[!UICONTROL Home Work List]**

*[!UICONTROL Home]*

Wanneer een gebruiker hun [!UICONTROL Home Work List], zien zij Volledige taken in de lijst, zelfs wanneer de optie om Voltooide taken te tonen niet wordt geselecteerd.

**De knop Schema is niet zichtbaar om Sandbox te vernieuwen**

*Sandbox-omgeving*

De [!UICONTROL Schedule] de knop die wordt gebruikt om een sandbox te plannen, wordt niet weergegeven in de bovenste banner van de sandboxomgeving.

**Wijzigingen in een berekend veld zijn van invloed op alle berekende velden op een formulier**

*Aangepaste Forms*

Wanneer een gebruiker in de Aangepaste Formulier Builder werkt en de waarde van een berekend formulier wijzigt, wordt in alle berekende velden op het formulier de nieuwe waarde weergegeven. Dit kan van invloed zijn op nieuwe of bestaande berekende velden.

**Kleuren die flikkeren op aangepaste formulierbuilder**

*Aangepaste Forms*

Wanneer een gebruiker met berekende velden werkt in de aangepaste formulierbuilder, flikkeren de kleuren van de velden en expressies.

**[!UICONTROL Cannot reject an approval]**

*Goedkeuringen*

Wanneer een gebruiker een goedkeuring probeert te verwerpen, [!UICONTROL Reject] reageert niet en de goedkeuring wordt niet afgewezen.

**[!UICONTROL Projects]tabblad is standaard ingesteld op Alle projectsecties ondanks vorige selectie**

*Projecten*

Wanneer een gebruiker naar een pagina van Projecten via een lusje gaat dat als deel van het lay-outmalplaatje is vastgezet, is de pagina in gebreke blijft aan [!UICONTROL All Projects] gebied van de linkernavigatie. Dit komt zelfs voor wanneer de gebruiker een ander gebied van de linkernavigatie kiest, dan weg van de pagina van Projecten en terug navigeert.

+++


## Updates in maart 2022

+++**Onderhoudsupdate op 31 maart 2022**

**Tijdzones zijn niet consistent tussen [!DNL Workfront] en[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Wanneer het profiel van een gebruiker is ingesteld op een specifieke tijdzone in [!DNL Workfront], de tijdzone van de gebruiker in [!DNL Workfront Proof] wordt ingesteld op een andere tijdzone.

**Koppeling naar het verzenden van een aangevraagd document leidt tot een lege pagina**

*Documenten*

Wanneer een gebruiker een verzoek ontvangt om een document te verzenden, en op de verbinding aan het voorwerp klikt waar het document werd gevraagd, leidt de verbinding tot een lege pagina. Dit kan voorkomen wanneer het klikken van een verbinding in een e-mail of in een in-app bericht.

**De groep wordt verkeerd toegewezen wanneer het omzetten van kwestie in project**

Groepen

Wanneer een gebruiker een kwestie in een project gebruikend een malplaatje omzet, is de functionaliteit:

* Als het malplaatje een toegewezen groep heeft, toont die groep in het venster van de uitgave omzetting als groep voor het nieuwe project.
* Als het malplaatje geen toegewezen groep heeft, de standaardgroep van de gebruiker die de kwestie omzet toont in het venster van de uitgaveconversie als groep voor het nieuwe project.
* Als het malplaatje geen groep heeft, zou het nieuwe project de groep van het project van de kwestie moeten erven.

**Kan aangepast objectoverschrijdend formulier niet koppelen aan aanvraagwachtrij**

Verzoeken

Wanneer een gebruiker een aangepast objectoverschrijdend formulier probeert toe te voegen aan de detailpagina van een wachtrij, wordt het objectoverschrijdende formulier niet weergegeven in de vervolgkeuzelijst met beschikbare formulieren en kan de gebruiker het formulier niet selecteren om het toe te voegen aan de rijdetails.

**De gebruikers kunnen niet met secundaire baanrol worden toegewezen op[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker een andere gebruiker aan een taak op probeert toe te wijzen [!UICONTROL Workload Balancer]en de taak wordt toegewezen aan een andere taakrol dan de primaire taakrol van de toegewezen gebruiker, wordt de gebruiker aan de taak toegewezen door hun primaire taakrol, en het volgende bericht toont:

&quot;\&lt;name> komt niet overeen met de rol van \&lt;task role=&quot;&quot; assignment=&quot;&quot;>. 1 werkitem dat momenteel is toegewezen aan de rol van &lt;\Taakroltoewijzing\> wordt toegewezen aan \&lt;name> in de rol van \&lt;primary job=&quot;&quot; role=&quot;&quot;>.&quot;

Dit komt zelfs voor als de gebruiker de de baanrol van de roltoewijzing van de Taak als secundaire baanrol heeft.

**Probleem met scrollbord &quot;Meer werkitems weergeven&quot; b**&#x200B;

*Agile*

Wanneer een gebruiker op de knop [!UICONTROL Show more work items] schuift op een scrollbord en vervolgens schuift u om de nieuwe items weer te geven, de [!UICONTROL Show more work items] de staaf kleeft aan de Rand en beweegt met het wanneer scrolt. Dit kan de kaarten moeilijk leesbaar maken.

**Rode stippen worden weergegeven in vereiste velden in aangepaste formulieren**

Aangepaste Forms

Wanneer een gebruiker een vereist veld op een aangepast formulier weergeeft, ziet hij twee rode stippen onder de asterisk die aangeeft dat het veld verplicht is.

**Time dropdown cut off in prompt**

*Rapporten*

Wanneer een gebruiker de herinneringen voor een rapport invult en een datumplukker ontmoet, toont de tijdselecteur bij de bodem van de datumkiezer geen uren voorbij 2, en de gebruiker kan geen uurwaarde buiten 1 of 2 selecteren.

+++

+++**Onderhoudsupdate (Hot Fix) op 29 maart 2022**

**Kan berekeningen niet wijzigen of opslaan in de Aangepaste formulierbuilder**

*Aangepaste formulieren*

Als een gebruiker handmatig een berekening invoert in een berekeningsveld in de builder van het aangepaste formulier en het formulier opslaat, wordt de berekening niet opgeslagen. Als de gebruiker het aangepaste formulier opnieuw opent, is dat veld leeg.

Als een gebruiker een berekening invoert in een berekeningsveld in de Aangepaste formulierbuilder door de dropdowns te gebruiken en het formulier op te slaan, wordt die waarde opgeslagen. Als de gebruiker het aangepaste formulier echter opnieuw opent, kan hij of zij dit veld niet bewerken of de waarde handmatig of met het vervolgkeuzemenu verwijderen.

OPMERKING: Dit probleem is opgelost met extra functionaliteit. Wanneer u nu begint te typen in een berekend veld, worden mogelijke expressies of berekeningen weergegeven in een vervolgkeuzelijst hieronder, net als in de Rekeningeditor. Klik op een item in het vervolgkeuzemenu om het toe te voegen aan het berekende veld.

+++

+++**Onderhoudsupdate op 24 maart 2022**

**Tijdzones zijn niet consistent tussen [!DNL Workfront] en[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Wanneer het profiel van een gebruiker is ingesteld op een specifieke tijdzone in [!DNL Workfront], de tijdzone van de gebruiker in [!DNL Workfront Proof] wordt ingesteld op een andere tijdzone.

**Vereiste veldfout voor ingevulde aangepaste velden bij het koppelen van een sjabloon**

*Projecten*

Wanneer gebruikers een sjabloon met vereiste aangepaste velden koppelen aan een project waarvan het veld al bestaat en is ingevuld, wordt de volgende fout weergegeven: &quot;[!UICONTROL There are incomplete fields. Enter values for required fields before you can continue.]&quot; Klik op &quot;[!UICONTROL Take me there]&quot; staat hen toe om te zien dat de gebieden worden ingevuld en zij kunnen het malplaatje met succes vastmaken.

**De [!UICONTROL Workload Balancer] knippert als u schakelt tussen datums**

*[!UICONTROL Workload Balancer]*

De uren van de gebruiker die als eerste in de lijst worden vermeld [!UICONTROL Workload Balancer] niet weergeven wanneer u de tijdlijn bijwerkt. De gebruiker en zijn uren tonen met alle grijze dozen die enkel knipperen. Dit gebeurt als u vooruit en achteruit gaat op de tijdlijn.

Het bijwerken van het filter lijkt de weergave te herstellen. Als u echter achterwaarts en voorwaarts beweegt op de tijdlijn, wordt de weergaveflitser opnieuw weergegeven en worden de gebruikersuren niet weergegeven.

**Aangepaste terminologie is inconsistent**

*Lay-outsjablonen*

De gebruikers melden dat wanneer [!DNL Workfront] De beheerder past de terminologie voor sommige voorwerpen aan gebruikend een Malplaatje van de Lay-out, de nieuwe objecten naam toont inconsistent in de interface.

Bijvoorbeeld op [!UICONTROL Projects] pagina, kunt u de paginatitel nog steeds weergeven als &quot;[!UICONTROL Projects]&quot;, hoewel de [!DNL Workfront] beheerder heeft de naam gewijzigd voor &quot;[!UICONTROL Projects]&quot; op iets anders.

Dit veroorzaakt verwarring voor eindgebruikers.

+++

+++**Onderhoudsupdate op 17 maart 2022**

**Miniatuur en hoofdafbeeldingen zijn leeg wanneer bestanden met meerdere pagina&#39;s worden weergegeven met [!DNL Safari] browser**

*[!DNL Workfront Proof]*

Wanneer een gebruiker een bestand met meerdere pagina&#39;s probeert weer te geven in het dialoogvenster [!DNL Safari] de miniatuurafbeeldingen zijn leeg. Soms is de hoofdafbeelding ook leeg.

**Onjuiste gebruikerslijst bij het maken van bulktoewijzingen in het dialoogvenster[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

Wanneer een gebruiker een bulktoewijzing maakt in het dialoogvenster [!UICONTROL Workload Balancer] en selecteert een project- en taakrol, is de lijst met beschikbare gebruikers onjuist. Het kan gebruikers zonder de de Rol van de Taak of toestemmingen van het Project tonen, en de gebruikers met de Rol van de Taak en de toestemmingen van het Project verschijnen niet in de lijst.

**[!UICONTROL Sorting is not working in reports]**

*Rapporten*

Wanneer een gebruiker op een kolom klikt om er op te sorteren, lijkt de sortering te werken, maar direct keren de resultaten terug naar de oorspronkelijke sortering zoals deze werd weergegeven voordat op de kolom werd geklikt. De sortering op een kolom blijft niet behouden.

**Selecteren &quot;[!UICONTROL Nothing]&quot; terugkeren naar de [!UICONTROL Report Default] groeperen**

*Rapporten*

Wanneer een rapport een ingebouwde groep heeft en de gebruiker &quot;[!UICONTROL Nothing]&quot; in de [!UICONTROL Grouping] vervolgkeuzemenu, wordt het rapport kort zonder groepering weergegeven en keert u terug naar de [!UICONTROL Report Default] groeperen.

**Verwijderd &quot;[!UICONTROL Blueprints access]&quot;, tabblad van Voorkeuren voor blauwdrukken**

*Blauwdrukken*

OPMERKING: Dit probleem doet zich alleen voor in de voorvertoningsomgeving.

De [!UICONTROL Blueprints access] is verwijderd uit de modaal voorkeurenvenster Vervagen. Er is geen functionaliteit verwijderd uit de voorkeuren voor blauwdrukken.

+++

+++**Onderhoudsupdate (Hot Fix) op 14 maart 2022**

**Kan niet omlaag schuiven in gebruikerslijst bij toewijzen op Kanban-bord**

*Agile*

Wanneer een gebruiker een [!DNL Kanban] en pogingen om een toewijzing te maken. De gebruikerslijst die wordt weergegeven wanneer gebruikers typen, springt steeds terug naar de bovenkant wanneer ze omlaag schuiven. De gebruiker kan geen gebruiker selecteren die zich niet bij de bovenkant van de lijst bevindt en kan de toewijzingswijziging niet opslaan.

**[!UICONTROL Milestone]Weergave in projectrapport veroorzaakt fout**

*Rapporten*

Wanneer het tonen van een projectrapport gebruikend [!UICONTROL Milestone] Gebruikers krijgen een &#39;[!UICONTROL APIModel INTERNAL does not support namedQuery TILE:milestone-view (UIVW)]&quot; fout.

**Aangepaste terminologie is inconsistent**

*Lay-outsjablonen*

De gebruikers melden dat wanneer [!DNL Workfront] De beheerder past de terminologie voor sommige voorwerpen aan gebruikend een Malplaatje van de Lay-out, de nieuwe objecten naam toont inconsistent in de interface.

Bijvoorbeeld op [!UICONTROL Projects] pagina, kunt u de paginatitel nog steeds weergeven als &quot;[!UICONTROL Projects]&quot;, hoewel de [!DNL Workfront] beheerder heeft de naam gewijzigd voor &quot;[!UICONTROL Projects]&quot; op iets anders.

Dit veroorzaakt verwarring voor eindgebruikers.

**Kan berekeningen voor bestaande berekende velden niet bijwerken**

*Aangepaste Forms*

Gebruikers kunnen de berekeningen in berekende velden niet bijwerken of wijzigen. Als het veld zonder berekening is gemaakt en opgeslagen, wordt de builder telkens weer leeg wanneer u een expressie probeert toe te voegen en op te slaan/toe te passen.

Als u een berekend veld met een bepaalde expressie maakt en dit opslaat, wordt telkens wanneer u de berekening probeert te wijzigen, de vorige waarde hersteld.

**[!UICONTROL Invalid Parameter]fout bij opnieuw instellen van wachtwoorden**

*Aanmelden*

Gebruikers kunnen hun wachtwoorden in geen enkele omgeving opnieuw instellen. Als ze hun e-mail invoeren en doorgaan, wordt er een fout weergegeven.

[!UICONTROL Error: Invalid Parameter: Search Parameter value "domain"].

+++

+++**Onderhoudsupdate op 10 maart 2022**

**Problemen met aanmelden bij voorvertoningsomgeving**

*Aanmelden*

De volgende problemen met aanmelden bij de voorbeeldomgeving zijn gemeld.

Wanneer een gebruiker zich aanmeldt bij de voorvertoningsomgeving, wordt een bericht weergegeven waarin wordt aangegeven dat de gebruiker de verkeerde id of het verkeerde wachtwoord heeft ingevoerd.

Wanneer een gebruiker zijn wachtwoord opnieuw probeert in te stellen, wordt de fout &quot;[!UICONTROL ?Multiple users were found with the email address <example@example.com>?]&quot;

**Aangepaste formulieren worden langzaam geladen [!UICONTROL Project Details] gebied**

*Projecten*

Wanneer een gebruiker probeert om project te bekijken [!UICONTROL Project Details] , aangepaste formulieren die na een vertraging van 15 seconden of meer aan het project zijn gekoppeld. De [!UICONTROL Add custom forms] deze vertraging heeft ook gevolgen voor deze optie .

**Aangepaste waarden voor formuliervelden worden niet opgeslagen in het deelvenster voor documentoverzicht**

*Documenten*

Wanneer een gebruiker aangepaste formuliervelden bijwerkt in het documentoverzichtsvenster, en een of meer velden een tekstkopveld zijn, worden de wijzigingen opgeslagen en niet in het overzichtsvenster genavigeerd, worden de updates niet opgeslagen. Dit gebeurt alleen wanneer een veld typekop wordt bewerkt, hoewel dit invloed heeft op alle velden.

**Gegevens niet behouden bij het converteren van sjablonen vanwege sjabloon delen van toegangsniveaus**

*Projecten*

Wanneer een gebruiker die toegang tot de Mening over een gedeelde malplaatje heeft probeert om een kwestie in een project om te zetten, om het even welke gegevens in de secties van de douaneformulier die vereisen [!UICONTROL Conrtibute] of hogere toegang tot mening wordt niet overgebracht naar het gecreeerde project.

**Fout bij het uploaden van een nieuwe documentversie**

*Documenten*

Wanneer een gebruiker een nieuwe versie van een document probeert te uploaden uit de documentlijst, wordt het document niet geüpload en ziet de gebruiker de volgende fout:

[!UICONTROL Error Cannot invoke "com.attask.boz.Document.getCurrentVersion()" because "document" is null]

**Factureringssnelheden kunnen niet worden bewerkt**

*Projecten*

Wanneer een gebruiker een factureringssnelheid probeert te bewerken op de knop [!UICONTROL Billing Rates] tabblad van een project, klikken op de knop [!UICONTROL Edit] de knop opent de knop [!UICONTROL Edit] wordt kort gesloten, maar de gebruiker kan de factureringssnelheid nog niet bewerken. Als u nogmaals op de knop klikt, wordt het bewerkingsvenster niet geopend.

**Openbare koppeling voor document leidt tot een lege pagina**

*Documenten*

Wanneer een gebruiker een document probeert te openen met een openbare koppeling, leidt de koppeling naar een lege pagina. Dit gebeurt wanneer de koppeling wordt geopend in een venster waarin een actieve koppeling [!DNL Workfront] sessie is geopend.

**De fout in het geheel wanneer het toevoegen van taak of kwestie aan lijst**

*Taken en problemen*

Wanneer een gebruiker die geen beheerder is, een taak of uitgave aan een lijst probeert toe te voegen en aangepaste velden invult, wordt de taak of uitgave niet gemaakt en ziet de gebruiker de volgende fout:

[!UICONTROL Error Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Als u een update verlaat nadat de status is gewijzigd, wordt de vorige status van het object hersteld**

Projecten, taken en problemen

Als u de status van een project, taak of uitgave wijzigt en onmiddellijk een update begint te typen zonder de pagina te vernieuwen, wordt in het updatevak de vorige status weergegeven. Als de update wordt gepost, wordt het voorwerp teruggekeerd aan de vorige status.

**Gebruikers die aan proefdrukken zijn toegevoegd, hebben onjuiste rollen**

*Proefdrukken*

Wanneer een gebruiker een andere gebruiker aan een proef toevoegt, wordt de rol van die gebruiker op de proef geplaatst als &quot;[!UICONTROL Read-only]&quot; ondanks de feitelijke proefdrukrol van de gebruiker.

Oplossing: Stel de proefdrukrol van de gebruiker in hun profiel in op iets anders en stel vervolgens de juiste rol in.

**Het aangepaste formulier wordt niet geladen wanneer u een uitgave naar een project converteert met een sjabloon**

*Aangepaste formulieren*

Wanneer een gebruiker een uitgave naar een project probeert om te zetten gebruikend een malplaatje, één of meerdere douaneformulieren in bijlage aan het malplaatje kunnen niet laden. Wanneer de gebruiker het malplaatje voor het nieuwe project vormt, in plaats van de douaneformulieren zien zij het volgende bericht:

&quot;[!UICONTROL Something went wrong, could not load form].&quot;

**Gebruiker kan uitgave niet inline toevoegen met aangepast vervolgkeuzeveld dat in de weergave wordt weergegeven**

*Lijsten*

Wanneer een gebruiker een uitgave van gealigneerd toevoegt en er een douanemening is met douaneveld drop-down die gebieden op de lijst worden toegepast, is er een fout wanneer zij het drop-down gebied slechts invullen. De gebruiker heeft toegang om douaneformulier uit te geven en is de projecteigenaar met beheerde rechten aan het project.

[!UICONTROL Error: Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it!]

**Machtigingen om taken aan een project toe te voegen zijn niet vereist om een taak naar het project te verplaatsen of te kopiëren**

*Taken*

U kunt nu een taak naar een andere taak in een project verplaatsen of kopiëren zonder toestemmingen te hebben om taken aan het bestemmingsproject toe te voegen. U moet toestemmingen hebben om taken aan minstens één van de taken van het bestemmingsproject toe te voegen. Voorafgaand aan deze update moest u machtigingen hebben om taken aan het project toe te voegen om een taak naar het project of naar een van de taken te verplaatsen of te kopiëren.  Deze update is nu beschikbaar in de productieomgeving. Het is beschikbaar in de Voorvertoningsomgeving vanaf de onderhoudsupdate van 24 maart 2022.

OPMERKING: Deze update is beschikbaar in de productieomgeving wanneer u problemen kopieert of verplaatst na de productieversie 22.2. Ga voor meer informatie over de huidige release naar workfront.com/release.

**Vervolgkeuzemenu Vragen is afgesloten**

*Rapporten*

Wanneer het gebruiken van een herinnering in een rapport, worden de drop-down menu&#39;s die u toestaan om de het filtreren criteria voor het rapport te selecteren afgesneden. De criteria onder aan de keuzelijst met selecties worden daarom niet weergegeven.

**Het werkpunt keert aan vorige status terug wanneer een update wordt gemaakt**

*Updates*

Wanneer een gebruiker de status van een tijdelijk item in de koptekst wijzigt, wordt de status niet bijgewerkt in het dialoogvenster [!UICONTROL Update] gebied. Als de gebruiker dan een update uitvoert, toont dropdown nog de vorige status. Wanneer de update wordt opgeslagen, overschrijft deze vorige, onjuiste status de status die in de header is ingesteld.

+++

+++**Onderhoudsupdate op 3 maart 2022**

**Kan document niet toevoegen vanuit[!DNL Google Drive]**

*Documenten*

Wanneer een gebruiker een document probeert toe te voegen van [!DNL Google Drive], reageert de selectie niet en kan de gebruiker geen documenten selecteren om toe te voegen.

**Gelabelde gebruikers worden niet toegevoegd aan updatethread**

*Updates*

Wanneer een gebruiker gelabeld is in een update, worden deze niet weergegeven in de &quot;[!UICONTROL To]&quot;gebied van de bijwerking of de antwoorden daarop.

**Proefgebruiker heeft twee aparte proefdrukaccounts**

*[!DNL Workfront Proof]*

E-mailadres van een gebruiker in [!DNL Workfront Proof] kan zich in twee aparte accounts met verschillende id&#39;s bevinden, waarbij de gebruiker twee accounts krijgt toegewezen. Hierdoor kan het moeilijk zijn om de juiste account te vinden.

**De fout die van het Oeps in rapportkopballen toont**

*Rapporten*

Wanneer een gebruiker een rapport bekijkt, toont de volgende fout in de rapportkopbal:

&quot;[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

Als de gebruiker een dashboard bekijkt, kan de fout in de kopbal voor alle rapporten op het dashboard verschijnen.

**Gegevens in gebieden met alleen Admin-edit-formulieren blijven niet behouden wanneer uitgaven worden geconverteerd naar projecten**

*Projecten*

Wanneer een niet-admin gebruiker probeert om een kwestie in een project om te zetten gebruikend een malplaatje, en de kwestie gegevens op gebieden bevat die slechts door admin kunnen worden uitgegeven, dragen de gegevens op die gebieden niet over aan het nieuwe project.

Wanneer een beheerder de uitgave omzet, worden de gegevens gedragen naar het nieuwe project zoals verwacht.

**[!DNL XLS]en [!DNL XLSX] De bestandsgroottelimiet wordt tijdelijk verlaagd naar 100 MB voor proefdrukken**

*Proofing*

Om een beveiligingsprobleem op te lossen, hebben we de maximale bestandsgrootte voor [!DNL XLS] en [!DNL XLSX] bestanden naar 100 MB als u een proefdruk maakt.

OPMERKING: Deze update vond plaats in de Preview-omgeving op 24 februari en zal op 3 maart in de Production-omgeving worden uitgevoerd.

**Bijwerken naar Workfront Search**

Zoeken

Deze week is een gefaseerde uitrol gestart om de infrastructuur voor de [!DNL Workfront] Zoekfunctionaliteit. De update maakt toekomstige verbeteringen aan Onderzoek gemakkelijker en betrouwbaarder. Met deze wijzigingen worden items toegevoegd aan [!DNL Workfront] zal sneller worden geïndexeerd en zal daarom sneller in onderzoeksresultaten terugkeren.

De gefaseerde uitrol zal twee weken duren.

**Bijgewerkte werkbalken voor rapporten binnen dashboards**

Rapporten

In rapporten in dashboards wordt nu een nieuwe werkbalk weergegeven. Deze werkbalk maakt deel uit van de updates van lijsten en rapporten die overal voorkomen [!DNL Workfront].

+++


## Updates in februari 2022

+++**Onderhoudsupdate (Hot Fix) op 24 februari 2022**

**Gegevens niet behouden bij conversie van uitgaven naar projecten als het veld verborgen is in een sjabloon**

*Projecten*

Wanneer een gebruiker een uitgave in een malplaatje omzet, en het malplaatje een douaneformulier omvat dat gebieden toont of verbergt die op de waarden in andere gebieden worden gebaseerd, worden om het even welke gegevens in gebieden die op het (gegevensloze) malplaatje op het tijdstip van omzetting verborgen zijn niet gedragen in het nieuwe project.

**Kan de bronnenplanner niet exporteren op rol**

*Resource Planner*

Wanneer een gebruiker de opdracht [!DNL Resource Planner] wanneer u de [!UICONTROL View by Role] -optie, wordt het exporteren niet voltooid en ontvangt de gebruiker een e-mail met het volgende bericht:

Er is een fout opgetreden tijdens het exporteren van uw [!DNL Resource Planner] gegevens.

**Aanvraagknop kopiëren werkt niet**

*Verzoeken*

Wanneer een gebruiker een verzoek probeert te kopiëren, [!UICONTROL Copy Request] knoop werkt niet als de gebruiker geen toegang van de Mening tot het rijonderwerp heeft.

+++

+++**Onderhoudsupdate op 24 februari 2022**

**Aangepaste formuliergegevens verdwijnen wanneer andere formuliervelden worden ingevuld**

*Aangepaste formulieren*

Wanneer een gebruiker een aangepast formulier invult als onderdeel van de conversie van een uitgave naar een project, kan het invullen van een aangepast veld ertoe leiden dat gegevens in een ander aangepast veld verdwijnen. Wanneer de gebruiker de ontbrekende gegevens opnieuw invoert en het project probeert te maken, wordt het volgende foutbericht weergegeven:

&quot;[!UICONTROL You must be a system admin to change this custom data parameter value]&quot;

**&quot;[!UICONTROL This approval process can be used by...]&quot; veld ontbreekt**

*Goedkeuringen*

Wanneer een gebruiker een goedkeuringsproces maakt of bewerkt in het dialoogvenster [!UICONTROL Setup] gebied, de[!UICONTROL This approval process can be used by...]&quot; veld ontbreekt. Dit kan voorkomen wanneer het creëren van een goedkeuringsproces of wanneer het uitgeven van bestaande.

**Systeembeheerder kan gebruikers niet opnieuw toewijzen wanneer een groep wordt verwijderd**

*Groepen*

Wanneer een systeembeheerder een groep schrapt, zullen zij slechts de optie hebben om de gebruikers van die groep aan groepen opnieuw toe te wijzen die de systeembeheerder een groepsbeheerder voor is. Andere groepen worden niet weergegeven in het vervolgkeuzemenu en de beheerder kan deze niet selecteren.

**De fout van de Hele wanneer het omzetten van kwestie in project**

*Projecten*

Wanneer een gebruiker een uitgave in een project probeert om te zetten gebruikend een malplaatje, en douaneformulieren toevoegt of verwijdert uit het malplaatje, zet de kwestie niet om en de gebruiker ziet het volgende bericht:

[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Kan bewijs niet openen; pagina vernieuwt**

*Proefdrukken*

Wanneer een gebruiker een proef probeert te openen, kan de proef niet openen. Uiteindelijk wordt de pagina vernieuwd.

**[!DNL XLS]en [!DNL XLSX] De bestandsgroottelimiet wordt tijdelijk verlaagd naar 100 MB voor proefdrukken**

*Proofing*

Om een beveiligingsprobleem op te lossen, hebben we de maximale bestandsgrootte voor [!DNL XLS] en [!DNL XLSX] bestanden naar 100 MB als u een proefdruk maakt.

OPMERKING: Deze update vindt plaats in de voorbeeldomgeving op 24 februari en in de productieomgeving op 3 maart.

**De toestemmingen om taken of kwesties aan een project toe te voegen worden niet vereist om een taak of een kwestie aan het project te bewegen of te kopiëren**

*Projecten*

U kunt nu een taak of een kwestie aan een andere taak in een project bewegen of kopiëren zonder het hebben toestemmingen om taken of kwesties aan het bestemmingsproject toe te voegen. U moet toestemmingen hebben om taken of kwesties aan minstens één van de taken van het bestemmingsproject toe te voegen. Voorafgaand aan deze update moest u machtigingen hebben om taken of problemen aan het project toe te voegen om een taak of een uitgave naar het project of een van de taken te verplaatsen of te kopiëren. Deze update is alleen beschikbaar in de voorvertoningsomgeving.

OPMERKING: Deze update is beschikbaar in de productieomgeving wanneer taken op 10 maart worden uitgevoerd of verplaatst. Deze update is beschikbaar in de productieomgeving wanneer u problemen kopieert of verplaatst met de 22.2 Production release. Ga voor meer informatie over de huidige release naar workfront.com/release.

**Bijwerken naar Workfront Search**

*Zoeken*

Deze week is een gefaseerde uitrol gestart om de infrastructuur voor de [!DNL Workfront] Zoekfunctionaliteit. De update maakt toekomstige verbeteringen aan Onderzoek gemakkelijker en betrouwbaarder. Met deze wijzigingen worden items toegevoegd aan [!DNL Workfront] zal sneller worden geïndexeerd en zal daarom sneller in onderzoeksresultaten terugkeren.

De gefaseerde uitrol zal twee weken duren.

+++

+++**[!DNL Workfront Fusion]Onderhoudsupdate op 18 februari 2022**

**Validatie van veldwaardetype toegevoegd aan [!DNL Anaplan] lijstitemeigenschappen**

*[!DNL Adobe Workfront Fusion]*

Er is een probleem opgelost waarmee gebruikers het onjuiste gegevenstype in velden voor lijstitemeigenschappen konden plaatsen. Validatie van het type eigenschap staat toe [!DNL Fusion] om ervoor te zorgen dat het correcte gegevenstype naar Anaplan wordt verzonden, eliminerend fouten die door onjuiste gegevenstypes worden veroorzaakt.

+++

+++**Onderhoudsupdate op 17 februari 2022**

**Fout bij verwijderen van voorganger van tabblad Voorgangers**

*Taken*

Wanneer een gebruiker een voorganger probeert te verwijderen uit de [!UICONTROL Predecessors] op een taak, wordt de taak niet verwijderd en wordt de volgende fout weergegeven:

[!UICONTROL Task with primary key value(s) "" not found]

**De fout in het openen van de gebruikerspagina**

*Gebruikers*

Wanneer een gebruiker de opdracht [!UICONTROL Users] pagina, wordt de pagina niet geopend en ziet de gebruiker de volgende fout:

[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Overlappende elementen in de koptekst van een rapport op een dashboard**

*Dashboards*

Wanneer een gebruiker een rapport op een dashboard bekijkt, zien ze dat het groeperingspictogram en het label de koppelingen overlapt naar [!UICONTROL Details] en [!UICONTROL Summary].

**Problemen met &quot;[!UICONTROL More]&quot; menu voor documenten en proefdrukken**

*Documenten*

Wanneer een gebruiker een document of proef op een [!DNL Workfront Classic] documentlijst en klik vervolgens op &quot;[!UICONTROL More],&quot; kunnen zij een van de volgende problemen zien: De knop reageert niet. Alle opties onder de knop hebben het label &quot;[!UICONTROL object Object]&quot; en kan niet worden gebruikt.

**&quot;U moet een systeem admin&quot;fout zijn wanneer het creëren van een project**

*Projecten*

Wanneer een gebruiker die geen beheerder is, een project probeert te creëren, en een douaneformulier vastmaakt dat een sectie beschikbaar slechts aan beheerders heeft, kunnen zij niet het project tot stand brengen en zij zien de volgende fout:

&quot;U moet systeembeheerder zijn om deze parameterwaarde van douanegegevens te veranderen&quot;

**Gegevens in het gedeelte met alleen beheer van aangepaste formulieren blijven niet behouden wanneer uitgaven worden geconverteerd naar projecten**

*Projecten*

Wanneer een gebruiker een kwestie in een project gebruikend een malplaatje omzet dat een douaneformulier met een admin-enige sectie heeft, worden om het even welke gegevens in de admin-enige sectie niet overgebracht naar het nieuwe project. Dit gebeurt zelfs als een beheerder de uitgave converteert.

+++

+++**Onderhoudsupdate op 10 februari 2022**

**&quot;[!UICONTROL You must be a system admin]&quot;-fout bij het maken van een project**

*Projecten*

Wanneer een gebruiker die geen beheerder is, een project probeert te creëren, en een douaneformulier vastmaakt dat een sectie beschikbaar slechts aan beheerders heeft, kunnen zij niet het project tot stand brengen en zij zien de volgende fout:

&quot;[!UICONTROL You must be a system admin to change this custom data parameter value]&quot;

**Gebruikers die gedeactiveerd en opnieuw geactiveerd zijn, worden niet weergegeven in[!UICONTROL Proof contacts]**

*[!DNL Workfront Proof]*

Wanneer een gebruiker zijn lijst met contactpersonen in [!DNL Workfront Proof], worden gebruikers die gedeactiveerd en opnieuw geactiveerd zijn, niet weergegeven in de lijst.

**Er is iets fout gegaan tijdens het converteren van een uitgave naar een project met een sjabloon**

*Projecten*

Wanneer een gebruiker die geen beheerder is, een uitgave naar een project probeert om te zetten met behulp van een sjabloon, wordt het volgende bericht weergegeven in aangepaste formuliervelden die alleen zichtbaar zijn voor beheerders:

&quot;[!UICONTROL Something went wrong, could not load form]&quot;

**Fout &quot;Kan pagina-inhoud niet laden&quot; bij weergeven van projectvoorkeuren**

*Instellen*

Wanneer een beheerder probeert om projecten, taken, of kwesties onder te bekijken [!UICONTROL Project Preferences] in de [!UICONTROL Setup] wordt de pagina niet geladen en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Cannot load page content. Please try refreshing the page.]&quot;

+++

+++**Onderhoudsupdate op 3 februari 2022**

**[!UICONTROL BizContext]fout bij aanmelden**

*Aanmelden*

Wanneer een gebruiker zich aanmeldt bij [!DNL Workfront], is de aanmelding mislukt en wordt het volgende bericht weergegeven:

&quot;[!UICONTROL Let's try that again. Database error: BizContext commit failed!]&quot;

Dit is gemeld in de voorvertoningsomgeving.

**De updatestroom van de uitgave verdwijnt als het probleem in afwachting van goedkeuring is**

*Updates*

Wanneer een gebruiker in [!UICONTROL New update] in de updatestream van een probleem dat in behandeling is voor goedkeuring, verdwijnt de volledige updatestream.

**Fout bij het uploaden van een nieuwe versie van een document**

*Documenten*

Wanneer een gebruiker een nieuwe versie van een document probeert te uploaden, wordt de nieuwe versie niet geüpload en ziet de gebruiker een van de volgende fouten:

* [!UICONTROL documentID cannot be null]
* [!UICONTROL Error: Invalid Parameter: documentID value "undefined"]

**Openbare koppeling voor document leidt tot een lege pagina**

*Documenten*

Wanneer een gebruiker een document probeert te openen met een openbare koppeling, leidt de koppeling naar een lege pagina. Dit gebeurt wanneer de koppeling wordt geopend in een venster waarin een actieve koppeling [!DNL Workfront] sessie is geopend.

**Besturingselementen voor lijsten werken niet bij rapporten in dashboards**

*Dashboards*

Wanneer een gebruiker een rapport in een dashboard bekijkt en probeert om de filter, de groepering, of de mening van het rapport te veranderen, verandert de filter, de groepering, of de mening niet.

**&quot;[!UICONTROL You must be a system admin]&quot;-fout bij het maken van een project**

*Projecten*

Wanneer een gebruiker die geen beheerder is, een project probeert te creëren, en een douaneformulier vastmaakt dat een sectie beschikbaar slechts aan beheerders heeft, kunnen zij niet het project tot stand brengen en zij zien de volgende fout:

&quot;[!UICONTROL You must be a system admin to change this custom data parameter value]&quot;

**Aangepaste gegevens blijven niet behouden bij conversie van uitgave naar project**

*Projecten*

Wanneer een gebruiker een kwestie in een project gebruikend een malplaatje omzet, worden de gegevens van een douaneformulier over de kwestie niet overgebracht naar de vergelijkbare douaneformulier op het project. Dit gebeurt met gegevens in aangepaste velden die kunnen worden verborgen op basis van de waarden van andere aangepaste velden.

**Fout bij converteren van uitgave naar project**

*Projecten*

Wanneer een gebruiker een uitgave in een project probeert om te zetten, wordt de kwestie niet omgezet en zij zien de volgende fout:

&quot;[!UICONTROL An unexpected error occurred]&quot;

+++


## Updates in januari 2022

+++**Onderhoudsupdate op 27 januari 2022**

**Aangepaste gegevens blijven niet behouden bij conversie van uitgave naar project**

*Projecten*

Wanneer een gebruiker een kwestie in een project gebruikend een malplaatje omzet, worden de gegevens van een douaneformulier over de kwestie niet overgebracht naar de vergelijkbare douaneformulier op het project. Dit gebeurt met gegevens in aangepaste velden die kunnen worden verborgen op basis van de waarden van andere aangepaste velden.

**Gebruikerslijst op het Klembord is niet alfabetisch**

*Agile*

Wanneer een gebruiker de gebruikerslijst op een agile-board bekijkt, worden de gebruikers niet in alfabetische volgorde weergegeven. In plaats daarvan worden eerst de gebruikers met de meeste toewijzingen vermeld.

**Bijgewerkte koppelingen voor het kopiëren en verplaatsen van problemen**

*Problemen*

In de voorvertoningsomgeving zijn de koppelingen voor het kopiëren en verplaatsen van problemen bijgewerkt naar &quot;[!UICONTROL Copy to]&quot; en &quot;[!UICONTROL Move to]&quot; zowel op de uitgavepagina als in een lijst met uitgaven.

**Voeg maximaal 45 IP adressen aan uw toe [!DNL Workfront] lijst van gewenste personen**

*Instellen*

De limiet voor IP-adressen die aan uw [!DNL Workfront] De lijst van gewenste personen is gestegen van 30 naar 45.

+++

+++**Onderhoudsupdate op 20 januari 2022**

**&quot;[!UICONTROL Invalid Parameter]&quot;-fout bij het maken van een project op basis van een sjabloon**

*Projecten*

Wanneer een gebruiker probeert om een project van een malplaatje tot stand te brengen, en een douaneformulier uit het malplaatje verwijdert wanneer het creëren van het project, wordt het project niet gecreeerd en de gebruiker ziet &quot;[!UICONTROL Invalid Parameter]&quot; foutbericht waarin een vereist veld in het verwijderde aangepaste formulier wordt vermeld.

**Gebruikerslijst wordt niet geladen in [!DNL Safari] browser**

*Gebruikers*

Wanneer een gebruiker naar de [!UICONTROL Users] wordt de koptekst weergegeven, maar wordt de lijst met gebruikers niet geladen.

**Lag wanneer het slepen van taken in een lijst veroorzaakt taak om aan verkeerde plaats te bewegen**

*Lijsten*

Wanneer een gebruiker een taak in een lijst probeert te bewegen door het te slepen, de blauwe lijn die erop wijst waar de taak zal worden bewogen om veel langzamer dan de curseur te bewegen. Wanneer de gebruiker de taak loslaat, wordt deze naar de positie verplaatst waar de blauwe lijn zich bevindt, zelfs als de cursor naar een andere locatie in de lijst wijst.

+++

+++**[!DNL Workfront Fusion]Onderhoudsupdate op 14 januari 2022**

**Bepaalde toegewezen velden worden opnieuw ingesteld wanneer u[!UICONTROL new field to map]**

*[!DNL Workfront Fusion]*

Als ten minste één veld in het veld [!DNL Workfront] [!UICONTROL Create] of [!UICONTROL Update] de modules heeft kaart toegelaten en een gebruiker selecteert een nieuw gebied om in kaart te brengen, verliezen de eerder in kaart gebrachte gebieden die kaart toegelaten kaartwaarden worden toegelaten.

+++

+++**Onderhoudsupdate op 13 januari 2022**

**Kan geen hyperlink toevoegen aan een opmerking in het deelvenster Samenvatting**

*Taken*

Wanneer een gebruiker in het overzichtsvenster van een taak een opmerking maakt en probeert een hyperlink naar de opmerking toe te voegen, wordt het hyperlinkkader geopend, maar zodra de gebruiker in het venster klikt, wordt het gesloten en kan de gebruiker geen hyperlink toevoegen. Als een gebruiker met Tab naar het venster gaat, kan hij of zij een koppeling in het veld typen of plakken, maar de hyperlink slaat niet op. In beide gevallen wordt de taak uitgeschakeld.

**De pagina Team bewerken wordt niet gesloten**

*Teams*

Wanneer een gebruiker een team probeert te bewerken, [!DNL Edit team] pagina wordt niet gesloten. De gebruiker kan de pagina niet sluiten door op een van de knoppen te klikken, op de X te klikken of weg van de pagina te navigeren.

**E-mailberichten en meldingen in de app worden niet verzonden**

*Meldingen*

Wanneer een gebeurtenis die een bericht zou moeten teweegbrengen voorkomt, wordt het bericht niet verzonden. Dit kan voorkomen voor e-mail of in-app berichten, en kan voorkomen zelfs alhoewel andere berichten worden verzonden.

**[!UICONTROL My Work]lijst is leeg**

*[!UICONTROL My Work]*

Wanneer een gebruiker hun [!UICONTROL My Work] en de lay-outsjabloon voor hun [!UICONTROL My Work] list bevat een numerieke waarde, zoals [!UICONTROL Percent Complete]de [!UICONTROL My Work] wordt niet weergegeven.

**[!UICONTROL Percent Complete]en [!UICONTROL Hours Complete] kan niet worden gewijzigd in de raad van bestuur**

*Agile*

Wanneer een gebruiker &quot;[!UICONTROL Show more work items]&quot; in de Raad van Bestuur probeert vervolgens de [!UICONTROL Percent Complete] of [!UICONTROL Hours Complete] op een van de zojuist geladen werkitems kunnen ze de stappen Percentage voltooid of Uren voltooid niet wijzigen. De [!UICONTROL Percent Complete] is ook grijs om aan te geven dat de knop inactief is.

+++

+++**Onderhoudsupdate op 6 januari 2022**

**&quot;[!UICONTROL Invalid Parameter]&quot;-fout bij het koppelen van sjablonen of aangepaste formulieren aan projecten**

*Projecten*

Wanneer een gebruiker een aangepast formulier of een sjabloon probeert toe te voegen aan een bestaand project, vult de vereiste velden in het aangepaste formulier of de aangepaste sjabloon in en slaat de wijzigingen in het project op. De wijzigingen worden niet opgeslagen en de gebruiker ziet een &quot;[!UICONTROL Invalid Parameter]&quot; fout bij de bovenkant van de pagina met projectdetails.

**Proefdrukopmerkingen worden niet weergegeven in documentupdates**

*Proefdrukken*

Wanneer een gebruiker een proefdruk weergeeft in het dialoogvenster [!UICONTROL Documents] in het gebied, worden eventuele opmerkingen op het bewijs zelf niet weergegeven in [!UICONTROL updates] in het document.

**[!UICONTROL Workload Balancer]: &quot;[!UICONTROL ?[object Object]?]&quot; weergegeven in overtoewijzingsgegevens**

*[!UICONTROL Workload Balancer]*

Als een gebruiker ziet als oververdeeld in het dialoogvenster [!UICONTROL Workload Balancer] omdat een taak de tijd van de gebruiker overlapt en een andere gebruiker de overtoewijzing bekijkt, wordt &quot;[!UICONTROL Capacity]&quot; het gebied van de overtoewijzingsinformatie wordt weergegeven &quot;[!UICONTROL ?[object Object]?]&quot; in plaats van de werkelijke capaciteit van de gebruiker.

+++

## Vorige onderhoudsupdates

Informatie over vorige onderhoudsupdates is hier beschikbaar:

* [[!DNL Workfront] Archief met onderhoudsupdates - 2021](2021-updates.md)
