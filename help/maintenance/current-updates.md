---
title: Workfront-onderhoudsupdates
description: Onderhoudsupdates voor [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: c3e3297bd52a4189321102e75cd952ac5162f1fa
workflow-type: tm+mt
source-wordcount: '3642'
ht-degree: 0%

---

# [!DNL Workfront] Onderhoudsupdates

De volgende onderhoudsupdates zijn uitgevoerd in 2024.

>[!NOTE]
>
>Deze updates bevatten ook andere kleine of minder duidelijke foutoplossingen. [!DNL Workfront] Ondersteuning geeft een melding wanneer een probleem dat u hebt verzonden, is opgelost.

Voor onderhoudsupdates vóór 2024, zie [Vorige onderhoudsupdates](#previous-maintenance-updates)

## Updates in mei 2024

+++ **(Geplande) onderhoudsupdate op 30 mei 2024**

### (Geplande) onderhoudsupdate op 30 mei 2024

#### Aangepaste formulieren

Fout bij het bewerken van beschrijvende tekstvelden

Wanneer een gebruiker probeert de beschrijvende tekst op een aangepast formulier te bewerken, wordt de tekst niet opgeslagen en ziet de gebruiker de volgende fout:

&quot;Dubbele sleutelwaarde schendt unieke restrictie&quot;

Dit is gemeld in de verouderde formulierbuilder.

#### Updates

**Als een vermelding wordt gekopieerd en geplakt, wordt de opgegeven gebruiker niet op de hoogte gesteld**

Wanneer een gebruiker een opmerking kopieert die een vermelding in @-indeling bevat, wordt die opmerking vervolgens in het gedeelte Updates van een ander object geplakt, zodat de vermelde gebruiker geen melding krijgt van de geplakte opmerking.

+++

+++ **Onderhoudsupdate op 23 mei 2024**

### Onderhoudsupdate op 23 mei 2024

#### Rapporten

Wanneer een gebruiker een rapport weergeeft en op de knop Vorige van de browser klikt, kan een van de volgende gebeurtenissen optreden:

* De gebruiker blijft op de pagina Rapport.
* De gebruiker wordt naar de bestemmingspagina van de browser geleid.
* De gebruiker wordt naar de aanmeldingspagina geleid.

Dit is gemeld in de Chrome-browser.

#### Updates

**De gecodeerde gebruiker kan niet zien wie hen etiketteerde**

Wanneer een gebruiker in een update van tags is voorzien, kan hij of zij niet zien wie deze tags heeft. Dit gebeurt wanneer de instelling &quot;Personen in andere bedrijven mogen alleen gebruikers van...&quot; is ingesteld op &quot;Hun bedrijf&quot;.

**Het labelen van een gebruiker met @ in het deelvenster Samenvatting is niet effectief**

Wanneer een gebruiker probeert om een andere gebruiker te etiketteren door @ in het gebied van Updates van een Samenvatting paneel te gebruiken, is het klikken op de naam van de gebruiker in dropdown ineffectief. Poging om de gebruiker een tweede keer tags toe te wijzen werkt zoals verwacht.

+++

+++**Onderhoudsupdate op 16 mei 2024**

### Onderhoudsupdate op 16 mei 2024

#### Instellen

**Standaardstatus van problemen ontbreekt in bepaalde typen problemen in Setup**

Wanneer een gebruiker uitgavestatussen in Opstelling bekijkt, zien zij dat de standaardstatussen voor kwesties (Nieuw, Bezig, en Voltooid) van sommige types van kwesties ontbreken. De standaardstatussen hebben niet de optie om het uitgevende type te veranderen, zodat kan de gebruiker niet de statussen aanpassen om voor de beïnvloede uitgaventypen te tonen.

#### Gebruikers

**Kan gebruikers niet verwijderen**

Wanneer een gebruiker probeert gebruikers te verwijderen, worden de gebruikers niet verwijderd. Dit is gemeld in organisaties die naar de Adobe Admin Console zijn gemigreerd.

+++

+++**Onderhoudsupdate op 9 mei 2024**

### Onderhoudsupdate op 9 mei 2024

Deze update bevat alleen kleine of minder belangrijke opgeloste problemen. [!DNL Workfront] Ondersteuning geeft een melding wanneer een probleem dat u hebt verzonden, is opgelost.

+++

+++**Onderhoudsupdate op 2 mei 2024**

### Onderhoudsupdate op 2 mei 2024

#### Registratietijd

**Kan de uren op taken of problemen niet bewerken**

Wanneer een gebruiker de uren voor een taak of uitgave probeert te bewerken, worden de wijzigingen niet opgeslagen.

+++

## Updates in april 2024

+++**Onderhoudsupdate op 25 april 2024**

### Onderhoudsupdate op 25 april 2024

#### Updates

**Genummerde lijsten zijn niet correct genummerd**

Wanneer een gebruiker een opmerking verzendt die een genummerde lijst bevat, wordt in de update een onjuiste nummering weergegeven.

Dit is gemeld in de nieuwe ervaringen met opmerkingen.

**Tekst blijft niet behouden wanneer u weg en terug navigeert naar opmerking**

Wanneer een gebruiker een opmerking schrijft die een @entry bevat, navigeert dan weg van en terug naar de opmerking voordat deze wordt verzonden, eventuele tekst die na de @entry is ingevoerd, ontbreekt in het opmerkingsconcept.

Dit is gemeld in de nieuwe ervaringen met opmerkingen.

+++

+++**Onderhoudsupdate op 18 april 2024**

### Onderhoudsupdate op 18 april 2024

#### Agile

**Kanbankkaarten geven geen aangepaste velden weer**

Wanneer een gebruiker een Kanban-bord weergeeft dat is geconfigureerd om aangepaste velden op te nemen, worden deze aangepaste velden mogelijk niet weergegeven.

#### Kalenders

**Fout bij vernieuwen van kalender**

Wanneer een gebruiker een kalender weergeeft en de pagina vernieuwt, wordt een foutbericht met de naam &#39;Oeps&#39; weergegeven. De gegevens in de kalender worden weergegeven zoals u had verwacht, maar worden mogelijk verborgen door het foutbericht.

#### Aangepaste formulieren

**Externe opzoekvelden leveren geen resultaten op**

Als een extern opzoekveld verwijst naar een veld met meerdere selecties waarin slechts één waarde is geselecteerd, wordt de waarde niet geretourneerd in het veld.

Als een extern opzoekveld bijvoorbeeld verwijst naar een veld met meerdere selecties waarin zowel de waarde &quot;rood&quot; als &quot;blauw&quot; is geselecteerd, functioneert het veld naar behoren. Als in het veld alleen &quot;rood&quot; is geselecteerd, retourneert het externe opzoekveld geen waarde.

#### Projecten

**Kan uitgave niet converteren naar project als een webproefdruk is bijgevoegd**

Wanneer een uitgave een Webproef in bijlage (een proef URL gebruikend een verbinding van een externe documentleverancier zoals SharePoint) heeft, en een gebruiker probeert om die kwestie in een project om te zetten, ontbreekt de omzetting en het project wordt niet gecreeerd. De gebruiker ziet de volgende fout:

&quot;Er was een probleem het kopiëren van het dossier (Dossier GUID). Verwijder het bestand of neem contact op met de ondersteuningsafdeling en probeer het opnieuw.&quot;

+++

+++**Onderhoudsupdate op 11 april 2024**

### Onderhoudsupdate op 11 april 2024

#### Zoeken

**Kan niet bewerken vanuit Zoeken**

Wanneer een gebruiker Geavanceerd zoeken gebruikt en probeert de zoekresultaten te bewerken of bulksgewijs te bewerken, reageert het pictogram Bewerken niet.

#### Updates

**Voorvertoning van afbeelding in updates is wazig**

Wanneer een gebruiker updates bekijkt en op het vergrootglas op een afbeelding klikt om een voorvertoning van de afbeelding weer te geven, is de voorvertoning die wordt geopend zeer vaag met pixels.

Als de gebruiker de afbeelding downloadt, wordt de afbeelding met de verwachte resolutie weergegeven.

**&quot;[!UICONTROL We're unable to post your comment]&quot; bericht wanneer wordt beantwoord**

Wanneer een gebruiker probeert te reageren op een bericht in de nieuwe opmerkingervaring, wordt het antwoord niet opgeslagen en ziet de gebruiker het volgende bericht:

&quot;[!UICONTROL We're unable to post your comment right now. Please wait a moment then try again.]&quot;

+++

+++**Onderhoudsupdate op 4 april 2024**

### Onderhoudsupdate op 4 april 2024

#### Zoeken

**Kan niet bewerken vanuit Zoeken**

Wanneer een gebruiker Geavanceerd zoeken gebruikt en probeert de zoekresultaten te bewerken of bulksgewijs te bewerken, reageert het pictogram Bewerken niet.

#### Updates

**Voorvertoning van afbeelding in updates is wazig**

Wanneer een gebruiker updates bekijkt en op het vergrootglas op een afbeelding klikt om een voorvertoning van de afbeelding weer te geven, is de voorvertoning die wordt geopend zeer vaag met pixels.

Als de gebruiker de afbeelding downloadt, wordt de afbeelding met de verwachte resolutie weergegeven.

**&quot;[!UICONTROL We're unable to post your comment]&quot; bericht wanneer wordt beantwoord**

Wanneer een gebruiker probeert te reageren op een bericht in de nieuwe opmerkingervaring, wordt het antwoord niet opgeslagen en ziet de gebruiker het volgende bericht:

&quot;[!UICONTROL We're unable to post your comment right now. Please wait a moment then try again.]&quot;

+++

+++**Onderhoudsupdate op 4 april 2024**

### Onderhoudsupdate op 4 april 2024

#### Integraties

**Documenten die niet zijn gekoppeld bij het maken van een verzoek van[!DNL Outlook]**

Wanneer een gebruiker een aanvraag maakt van [!DNL Outlook], zijn de documenten die bij de e-mail zijn gevoegd, niet bij de aanvraag gevoegd.

Dit is gemeld voor de volgende typen bijlagen:

XLS PDF

#### Registratietijd

**Gebruiker kan geen tijd voor huidige dag aanmelden**

Wanneer een gebruiker probeert om tijd in het gebied van Updates te registreren, is de huidige dag grayed uit, en de gebruiker kan geen tijd voor de huidige dag registreren.

#### Updates

<!--no article-->

**Fout bij weergeven van opmerkingen**

Wanneer een gebruiker opmerkingen probeert weer te geven in de nieuwe opmerkingervaring, kunnen de opmerkingen niet worden weergegeven. In plaats daarvan wordt de volgende fout weergegeven:

&quot;Er ging iets mis. Probeer het later opnieuw.&quot;

De oudere ervaring met opmerkingen werkt zoals u had verwacht.

+++

## Updates in maart 2024

+++**Onderhoudsupdate op 28 maart 2024**

### Onderhoudsupdate op 28 maart 2024

#### Integraties

**Documenten die niet zijn gekoppeld bij het maken van een verzoek van[!DNL Outlook]**

Wanneer een gebruiker een aanvraag maakt van [!DNL Outlook], zijn de documenten die bij de e-mail zijn gevoegd, niet bij de aanvraag gevoegd.

Dit is gemeld voor de volgende typen bijlagen:

XLS PDF

#### Proefdrukken

**Proefdrukken blijven beschikbaar op de widget Mijn goedkeuringen**

Er blijft een bewijs op de widget staan dat uit de widget Mijn goedkeuringen moet verdwijnen. Dit kan gebeuren wanneer meerdere gebruikers tegelijkertijd beslissingen nemen over een bewijs of wanneer één gebruiker een beslissing neemt en deze snel wijzigt.

#### Bronbeheer

**Verschil in begrote uren**

De begrote uren die in een van de volgende gebieden worden weergegeven, komen mogelijk niet overeen met de uren die in een ander van deze gebieden worden weergegeven:

* Bedrijfs-case
* Rapporten
* Hulpprogramma voor het budgetteren van bronnen

#### Taken

**De voorganger-knopinfo geeft geen taaknaam weer**

Wanneer een gebruiker een takenlijst bekijkt en de muis boven een voorgangerpictogram houdt voor meer informatie, wordt in de knopinfo die wordt weergegeven, niet de naam van de voorgangertaak weergegeven.

#### Updates

**Opmerkingen bij het document worden niet weergegeven in updates van het bovenliggende object**

Wanneer een gebruiker een opmerking maakt over een document, wordt die opmerking niet direct weergegeven in het gedeelte Updates van het bovenliggende object van het document.

Dit probleem is gemeld in de nieuwe ervaringen met opmerkingen. Opmerkingen worden weergegeven in de oudere opmerkingervaring zoals u had verwacht.

**Het labelen van een gebruiker is niet effectief**

Wanneer een gebruiker in een opmerking is gelabeld, is die opmerking niet zichtbaar voor de gelabelde gebruiker. De gelabelde gebruiker wordt ook niet via e-mail of via een bericht in de app op de hoogte gesteld van de opmerking.

Dit is gemeld in de oudere ervaringen met opmerkingen.

+++

+++**Workfront Fusion Maintenance Update op 28 maart 2024**

### Workfront Fusion Maintenance Update op 28 maart 2024

**RuntimeError met 200 reactie van Workfront module**

Een Workfront-module kan een `RuntimeError [200]` reactie. De 200 impliceert een succesvol antwoord, maar de fout toont aan dat het verzoek niet succesvol was.

Dit kan voorkomen als de respons extreem lang is. De gegevens worden geretourneerd aan Fusion, maar kunnen niet door Fusion worden verwerkt.

+++

+++**Onderhoudsupdate op 21 maart 2024**

### Onderhoudsupdate op 21 maart 2024

#### Updates

**Grote spaties tussen lijnen**

Wanneer een gebruiker een update typt met meerdere regels met de toets Return of Enter, of meerdere regels in een update plakt, wordt de update naar behoren weergegeven. Nochtans, als een gebruiker dan die update in een rapport bekijkt, zijn er grote ruimten tussen de lijnen.

Dit is gemeld in de nieuwe ervaringen met opmerkingen.

**Het labelen van een gebruiker met @ is niet effectief**

Wanneer een gebruiker een andere gebruiker met @ in een commentaar etiketteert, wordt de gebruiker niet toegevoegd aan het geëtiketteerde gebruikersgebied, en ontvangt geen bericht over de commentaar.

Deze correctie is alleen van toepassing op de nieuwe opmerkingervaring.

+++

+++**Onderhoudsupdate op 14 maart 2024**

### Onderhoudsupdate op 14 maart 2024

#### Proefdrukken

**Op basis van gekoppelde documenten gemaakte proefdrukken hebben geen proefdruksjabloon toegepast**

Wanneer een gebruiker een proef van een verbonden document creeert, wordt het proefdrukmalplaatje niet correct toegepast, en het bewijs kan informatie zoals het werkschema missen.

Dit geldt ook voor proefdrukken die zijn gemaakt via de API en via Workfront Fusion.

#### Gebruikers

**Lagere toegangsniveaus niet beschikbaar wanneer het creëren van een gebruiker**

Wanneer een gebruiker een andere gebruiker maakt, is alleen het toegangsniveau van de eerste gebruiker beschikbaar voor de nieuwe gebruiker. Alle toegangsniveaus met lagere toestemmingen dan die van de het creëren gebruiker zouden beschikbaar moeten zijn om aan de nieuwe gebruiker toe te wijzen.

+++

+++**Onderhoudsupdate op 7 maart 2024**

### Onderhoudsupdate op 7 maart 2024

#### Borden

**400 fout bij het toevoegen van een taak aan een board**

Wanneer een gebruiker een project bekijkt en probeert om een taak aan een raad toe te voegen, wordt de taak niet toegevoegd, en de gebruiker ziet de volgende fout:

Fout: &quot;400: undefined /boards-service/graphql&quot;

#### Home

**Fout bij inlinebewerking van een taak in de widget Mijn taak**

Wanneer een gebruiker een taak inline probeert uit te geven in Mijn Taken widget, zien zij de volgende fout:

&quot;Er is een fout opgetreden en we werken eraan het probleem op te lossen. Vernieuw deze browserpagina om verder te gaan met uw werk.&quot;


#### Werklastverdeling

**Geplande uren worden niet bijgewerkt in werklastbalans**

Wanneer de geplande uren voor een project worden bijgewerkt, worden ze niet bijgewerkt in Workload Balancer. Dit kan voorkomen alhoewel de verandering nauwkeurig in het project wordt weerspiegeld.

+++

++**Workfront Fusion Maintenance Update op 7 maart 2024

**Workfront Proof > Tijd in de module Controle**

Scenario&#39;s waarin de module Workfront Proof > Watch Proof wordt gebruikt, worden mogelijk gedeactiveerd vanwege de timing van de module Controle.

+++

## Updates in februari 2024

+++**Onderhoudsupdate op 29 februari 2024**

### Onderhoudsupdate op 29 februari 2024

#### Updates

**Updates: het scherm gaat leeg wanneer het antwoorden aan een gebruiker van een ander bedrijf**

Wanneer een gebruiker een opmerking van een gebruiker in een ander bedrijf probeert te beantwoorden, wordt het scherm leeg gelaten.

Dit komt omdat de gebruiker geen toestemming heeft om gebruikers van andere bedrijven te zien.

+++

+++**Onderhoudsupdate op 22 februari 2024**

### Onderhoudsupdate op 22 februari 2024

#### Home

**[!UICONTROL Home]: [!UICONTROL Workspace] en punten niet laden**

Wanneer een gebruiker zich aanmeldt, kan het volgende voorkomen:

* Nieuwe gebruiker [!UICONTROL Home Workspace] wordt niet geladen en wordt de fout &quot;[!UICONTROL We are unable to load your Workspace information. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;
* De punten van de gebruiker worden niet geladen en de fout &quot;[!UICONTROL Your pins are unavailable because of a system error. Try refreshing your browser to fix the problem.]&quot;

#### Gebruikers

**De beheerder van de groep kan niet het toegangsniveau van een gebruiker plaatsen of veranderen**

<!--no article-->

Wanneer een groepsbeheerder probeert om het toegangsniveau van een gebruiker te veranderen, één van het volgende kan voorkomen:

* Het veld Toegangsniveau is uitgeschakeld.
* De groepsbeheerder kan geen lager toegangsniveau kiezen.

#### Werklastverdeling

**Etiket voor niet-werkuren**

De werklastbalans en de persoonlijke tijd van de kalender tonen nu &quot;[!UICONTROL Non-working Hours]&quot; voor tijd dat een gebruiker opstart. Eerder werd het scherm weergegeven &quot;[!UICONTROL Working Hours]&quot; voor niet-arbeidstijd.

+++

+++**Onderhoudsupdate op 15 februari 2024**

### Onderhoudsupdate op 15 februari 2024

#### Problemen

**Tijdvelden besparen onjuiste tijd bij problemen met bulkbewerking**

Wanneer een gebruiker bulkbewerkingsproblemen heeft en een datum en tijd selecteert voor een datumveld en opslaat, is de tijd die aan dit veld wordt opgeslagen in de uitgave niet de tijd die de gebruiker heeft geselecteerd. In plaats daarvan lijkt de tijd te worden omgezet in UTC wanneer de gebruiker opslaat.

#### Taken

**Gebruiker is niet toegewezen aan een of meer taken**

De toewijzing van een gebruiker aan een taak kan automatisch ongedaan worden gemaakt. Dit kan voor één of meerdere taken voorkomen. De toewijzing ongedaan maken wordt niet weergegeven in het gedeelte System Updates van de taken, maar wel in de sectie Update feeds van het instellingsmenu.

#### Updates

**De optie Uitgeschakelde afbeelding is beschikbaar wanneer u een opmerking bewerkt**

Na een [!DNL Workfront] de beheerder heeft de optie voor het toevoegen van afbeeldingen aan opmerkingen uitgeschakeld. Deze optie is niet beschikbaar wanneer u een opmerking maakt. Als een gebruiker echter een bestaande opmerking bewerkt, is de afbeeldingsoptie beschikbaar.

+++

+++**Onderhoudsupdate op 8 februari 2024**

### Onderhoudsupdate op 8 februari 2024

#### Borden

**Kan een kaart niet naar een kolom verplaatsen met [!UICONTROL Move] opties**

Wanneer een gebruiker een kaart in een kolom probeert te verplaatsen met &quot;[!UICONTROL Top of column]&quot; of &quot;[!UICONTROL Bottom of column]&quot;-opties in het menu met drie punten wordt de kaart niet verplaatst.

**Kaarten blijven bestaan wanneer u de iteratie wijzigt**

Wanneer een gebruiker een herhaling op een board bekijkt en dan de herhaling verandert, zijn de kaarten die voor de nieuwe herhaling tonen de kaarten van een herhaling de gebruiker eerder bekeken.

#### Rapporten

**De kolom &quot;Geen waarde&quot; geeft geen resultaten weer**

Wanneer een grafiekrapport een &quot;[!DNL No value]&quot;, toont de kolom geen gegevens, hoewel de gegevens aanwezig zouden moeten zijn.

#### Bronbeheer

**Onjuiste financiële berekeningen als gevolg van problemen met de functie**

De berekeningen van uren en van de financiën kunnen onjuist zijn, die een kosten van 0 tonen alhoewel de uren in een baanrol worden geregistreerd die een kostentarief heeft.

Dit komt omdat de Rollen van de Baan automatisch dubbele tarieven zonder begin of einddata creëren. Omdat ze geen begin- of einddatum hebben, worden ze behandeld als een waarde van 0 wanneer financieringsberekeningen worden uitgevoerd.

+++

+++**Onderhoudsupdate op 1 februari 2024**

### Onderhoudsupdate op 1 februari 2024

#### Aanmelden

**Gebruikers die SSO gebruiken, worden niet omgeleid naar de oorspronkelijke locatie wanneer ze zich aanmelden**

Wanneer een gebruiker zich op een pagina bevindt in [!DNL Workfront] en zich aanmeldt bij SSO, als de aanmelding is voltooid, wordt naar [!UICONTROL Home] in plaats van de pagina waarop ze stonden voordat ze zich aanmelden.

#### Sjablonen

**Fout bij kopiëren van sjablonen**

Wanneer een gebruiker een nieuwe of bestaande sjabloon probeert te kopiëren, wordt de sjabloon niet gekopieerd en ziet de gebruiker de volgende fout:

&quot;[!UICONTROL ID Cannot be Null]&quot;

+++

## Updates in januari 2024

+++**Onderhoudsupdate (Hot Fix) op 30 januari 2024**

### Onderhoudsupdate (Hot Fix) op 30 januari 2024

#### Rapporten

**Extern API-veld geeft niet alle beschikbare waarden in lijsten en rapporten weer**

Eerder konden gebruikers de geselecteerde waarde (en de waarde bewerken) voor een extern opzoekveld zien in lijsten en rapporten, maar het vervolgkeuzemenu met de opties uit de API werd niet weergegeven.

Wanneer nu een extern opzoekaangepast veld wordt gebruikt in een lijst of rapport, is het vervolgkeuzemenu met alle opties van de externe API beschikbaar.

+++

+++**Onderhoudsupdate op 25 januari 2024**

### Onderhoudsupdate op 25 januari 2024

#### Borden

**Kaarten die niet naar de juiste kolom worden verplaatst wanneer de status wordt gewijzigd**

Wanneer de status van het gekoppelde object van een aangesloten kaart rechtstreeks op het object wordt gewijzigd, wordt de kaart niet naar de juiste kolom verplaatst. Als de objectstatus op de kaart wordt gewijzigd of als de kaart naar de nieuwe kolom wordt gesleept, gedraagt de kaart zich zoals verwacht.

#### Meldingen

**Markeringsmeldingen blijven niet bestaan**

Wanneer een gebruiker zijn berichten zoals gezien merkt en dan naar een verschillende pagina binnen navigeert [!DNL Workfront]Het waarschuwingspictogram geeft nog steeds het aantal ongelezen meldingen weer dat bestond voordat de gebruiker de berichten zoals weergegeven markeerde. De meldingen worden nog steeds weergegeven wanneer de gebruiker op het pictogram klikt. Dit gaat door als de gebruiker deze zoals gezien markeert en naar een andere pagina of terug naar de oorspronkelijke pagina navigeert.

#### Updates

**Problemen met labelen in ervaringen met oudere opmerkingen**

Wanneer een gebruiker gelabeld is in een opmerking in de oudere opmerkingervaring, doen zich de volgende problemen voor:

* Alleen de voornaam van de gebruiker komt voor in de opmerking
* De gebruikersnaam is niet gemarkeerd met een @-symbool
* De gebruikersnaam is niet blauw
* De gebruikersnaam is geen koppeling naar het profiel van die gebruiker

De gebruiker ontvangt wel een e-mailbericht over de tag, zoals verwacht.

+++

+++**Onderhoudsupdate op 18 januari 2024**

### Onderhoudsupdate op 18 januari 2024

#### Borden

**Kan een document niet aan een kaart koppelen**

Wanneer een gebruiker een document probeert te koppelen aan een aangesloten kaart, kan de gebruiker het document selecteren dat u wilt bijvoegen, maar het document wordt niet weergegeven in het documentgebied van de kaart en het document is niet gekoppeld aan het object waarmee de kaart is verbonden.

Dit is gemeld bij kaarten die verband houden met emissies.

**Kaart wordt weergegeven op meerdere veren**

Wanneer een gebruiker een sprint op Borden bekijkt, verschijnen kaarten die in verschillende sprot zijn op het bord. Dit is een periodiek probleem.

**De kaart wordt niet gesloten wanneer de mening van Borden in een Project wordt gebruikt**

Wanneer een gebruiker de mening van Borden op een taaklijst in een project bekijkt, en een kaart creeert, sluit of bewaart de kaart niet. Dit verhindert de gebruiker aan het project terug te keren.

Om de kaart te sluiten, moet de gebruiker de URL bewerken om &quot;board&quot; en alles rechts van &quot;board&quot; te verwijderen.

**Kaarten blijven bestaan wanneer u de iteratie wijzigt**

Wanneer een gebruiker een herhaling op een board bekijkt en dan de herhaling verandert, zijn de kaarten die voor de nieuwe herhaling tonen de kaarten van een herhaling de gebruiker eerder bekeken.

**Fout in [!UICONTROL Comments] deel kaarten**

Wanneer een gebruiker een kaart weergeeft en naar de [!UICONTROL Comments], sectie, opmerkingen worden niet weergegeven en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Something went wrong. Please try again later.]&quot;

**Problemen tijdens weergeven van status van subtaak**

De volgende problemen zijn gemeld met betrekking tot het weergeven van de status van een subtaak op een kaart in de raden van bestuur:

* De status wordt weergegeven als &quot;Status selecteren&quot;, zelfs als de taak al een status heeft. Deze status is zichtbaar wanneer u de taak rechtstreeks bekijkt.
* Als de gebruiker een status probeert te selecteren, gaat het scherm leeg en moet het worden vernieuwd.

**&quot;[!UICONTROL You have no access]&quot; als u opmerkingen op een kaart weergeeft**

Wanneer een gebruiker opmerkingen probeert weer te geven op een kaart die niet is verbonden met een [!DNL Workfront] , wordt het volgende bericht weergegeven:

&quot;[!UICONTROL You have no access to view comments on this object]&quot;

Dit kan zelfs gebeuren als de gebruiker eerder opmerkingen op de kaart kon zien.

#### Aangepaste formulieren

**Kan aangepaste formulieren niet bulksgewijs toevoegen of verwijderen voor sjabloontaken**

Als een gebruiker probeert een aangepast formulier in een sjabloontaak in bulk toe te voegen of te verwijderen, wordt het formulier niet toegevoegd of verwijderd en ziet de gebruiker de volgende fout:

[!UICONTROL Let's try that again. Invalid Parameter: templateID value "XXXXXXXXXXXXXXXX"]

Als de gebruiker van het malplaatje met gespecificeerde GUID de plaats bepaalt, dan probeert om douaneformulieren op de rest van de malplaatjetaken toe te voegen of te verwijderen, zal de fout opnieuw voorkomen gebruikend een andere templateID.

Aangepaste formulieren kunnen worden toegevoegd aan of verwijderd uit één sjabloontaak. Deze fout is alleen van toepassing op bulkoptellen of verwijderen.

#### Portfolio&#39;s

**Aangepaste terminologie is niet van toepassing op groepspagina**

Wanneer een gebruiker aangepaste terminologie op het niveau van het Portfolio instelt, is de terminologie niet van toepassing op de pagina op groepsniveau.

#### Instellen

**Kan optionele statussen niet verbergen**

Wanneer een gebruiker probeert optionele statussen op systeem- en groepsniveau te verbergen, wordt de status niet verborgen. Als de gebruiker de status weergeeft, is de optie om de status te verbergen niet ingeschakeld, ook al heeft de gebruiker deze wel ingeschakeld en de wijzigingen opgeslagen.

**Standaardstatus van problemen ontbreekt in bepaalde typen problemen in Setup**

Wanneer een gebruiker uitgavestatussen in Opstelling bekijkt, zien zij dat de standaardstatussen voor kwesties (Nieuw, Bezig, en Voltooid) van sommige types van kwesties ontbreken. De standaardstatussen hebben niet de optie om het uitgevende type te veranderen, zodat kan de gebruiker niet de statussen aanpassen om voor de beïnvloede uitgaventypen te tonen.

#### Teams

**Problemen met het instellen van teamstatussen voor [!UICONTROL Done] knop**

De volgende kwesties zijn gemeld met betrekking tot de status van de [!UICONTROL Done] knop bij het bewerken of maken van een team:

* Sommige statussen ontbreken mogelijk in het knopgebied Gereed van het dialoogvenster [!UICONTROL New team] of het [!UICONTROL Team Settings] deel van een bestaand team.
* Als de gebruiker probeert het team op te slaan, wordt mogelijk de fout &quot;U moet ten minste één status in elke categorie selecteren&quot; weergegeven.

#### Sjablonen

**Fout bij koppelen van sjabloon aan project**

Wanneer een gebruiker probeert om een malplaatje aan een project vast te maken, ontvangen zij de volgende fout:

&quot;Oeps! Er is iets misgegaan. Neem contact op met Workfront om uit te zoeken wat er fout is gegaan en het op te lossen.&quot;

Dit gebeurt wanneer de gebruiker geen weergavemachtiging heeft voor een aangepast formulier dat aan de sjabloon is gekoppeld.

#### Updates

**Opmerkingen worden niet overgedragen tussen oude en nieuwe ervaringen**

Een opmerking die is gemaakt in de oudere opmerkingervaring is mogelijk niet zichtbaar in de nieuwe opmerkingervaring. Het omgekeerde kan zich ook voordoen.

+++

+++**Onderhoudsupdate op 11 januari 2024**

### Onderhoudsupdate op 11 januari 2024

#### Borden

**Voltooide kaarten worden niet correct geladen op dynamische borden**

Eerder was het alleen mogelijk om voltooide werkzaamheden op een dynamisch bord op te nemen door de kaarten als gearchiveerde kaarten te laden. Anders werden de voltooide kaarten helemaal niet op het bord geladen. Dit zorgde voor problemen met het vinden van kaarten.

Wanneer u nu een dynamisch bord maakt, worden voltooide kaarten standaard geladen als gearchiveerde kaarten, maar u kunt de optie Voltooide kaarten niet archiveren selecteren om alle voltooide kaarten op het bord te laden als zichtbare kaarten in de kolom Voltooid.

+++

## Vorige onderhoudsupdates

Informatie over vorige onderhoudsupdates is hier beschikbaar:

* [[!DNL Workfront] Archief met onderhoudsupdates - 2023](2023-updates.md)
* [[!DNL Workfront] Archief met onderhoudsupdates - 2022](2022-updates.md)
* [[!DNL Workfront] Archief met onderhoudsupdates - 2021](2021-updates.md)
