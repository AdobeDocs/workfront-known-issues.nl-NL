---
title: Workfront-onderhoudsupdates voor 2021
description: Historie van 2021 onderhoudsupdates voor  [!DNL Adobe Workfront]
exl-id: 57a3636e-fd01-4ee6-bc96-df535b62d4f7
feature: Get Started with Workfront
source-git-commit: 98d56729e44e7ab47e201bdfc00db8d40c5f15f6
workflow-type: tm+mt
source-wordcount: '9003'
ht-degree: 0%

---

# 2021 [!DNL Workfront] Updates voor onderhoud

De volgende onderhoudsupdates zijn uitgevoerd in 2021:

## Updates in december 2021

+++**Update van het Onderhoud op 23 December, 2021**

**Nieuwe taken gebrek aan onjuiste taakbeperking**

_Taken_

Wanneer een gebruiker tot een nieuwe taak gebruikend &quot;[!UICONTROL New Task]&quot;knoop leidt, en de [!UICONTROL New Task Default Start] optie van de Datum wordt geplaatst aan &quot; [!UICONTROL Today],&quot;wordt de taakbeperking van de gecreeerde taak geplaatst aan &quot; [!UICONTROL As soon as possible]&quot;eerder dan &quot;[!UICONTROL Start no earlier than].&quot; Dit kan ook voorkomen wanneer het gebruiken van projectmalplaatjes.

**Openend programma in [!UICONTROL Groups] gebied leidt tot lege pagina**

_Opstelling_

Wanneer een gebruiker groepen in het [!UICONTROL Setup] -gebied weergeeft en een schema probeert te openen, bewerken of kopiëren, wordt het schema niet geopend en ziet de gebruiker een lege pagina.

**de Veranderingen tonen niet wanneer het opnieuw ordenen van linkernavigatie**

_Navigatie_

Wanneer een gebruiker het navigatievenster aan de linkerkant probeert opnieuw te ordenen door een item te slepen, verschijnt het item weer op de vorige plaats wanneer de gebruiker het neerzet. Als de gebruiker de pagina vernieuwt, wordt in het linkerdeelvenster de nieuwe volgorde weergegeven.

**Verbinding om een gevraagd document voor te leggen leidt tot lege pagina.**

_Documenten_

Wanneer een gebruiker een verzoek ontvangt om een document te verzenden, en op de verbinding aan het voorwerp klikt waar het document werd gevraagd, leidt de verbinding tot een lege pagina. Dit kan voorkomen wanneer het klikken van een verbinding in een e-mail of in een in-app bericht.

**[!UICONTROL Workload Balancer]toont 0 toegewezen uren**

_[!UICONTROL Workload Balancer]_

Wanneer een gebruiker [!UICONTROL Workload Balancer] bekijkt en &quot;[!UICONTROL Show projected dates]&quot;plaatsen toegelaten heeft, om het even welke data in de toekomst tonen 0 toegewezen uren.

**Proefdrukken verdwijnen periodiek uit omslagen**

_[!DNL Workfront Proof]_

Wanneer een gebruiker die is aangemeld bij [!DNL Workfront Proof] een map weergeeft, wordt de map leeg weergegeven. Als de gebruiker later terugcheckt, zijn de proefdrukken zichtbaar.

+++

+++**Update van het Onderhoud op 16 December, 2021**

**klikkend aankondiging in berichtenlijst leidt tot lege pagina**

_Meldingen_

Wanneer een gebruiker zijn lijst met meldingen opent via het pictogram [!UICONTROL Notifications] en vervolgens op een aankondiging klikt, wordt naar een lege pagina gegaan en wordt de aankondiging niet weergegeven.

**Samenvattingspaneel toont &quot;[!UICONTROL No selection]&quot;wanneer de taak wordt geselecteerd**

_Taken_

Wanneer een gebruiker een documentoverzicht in het [!UICONTROL Documents] gebied van een project opent, dan naar de taaklijst gaat, een taak selecteert, en probeert om het taakoverzicht te openen, toont het taakoverzicht niet, en de gebruiker ziet het volgende bericht:

[!UICONTROL No selection. Select a document in the list to view details.]

Het bericht vermeldt documenten, ook al staat de gebruiker in de takenlijst.

**[!UICONTROL Unassigned Work]wordt niet geladen**

_[!UICONTROL Workload Balancer]_

Wanneer een gebruiker in de [!UICONTROL Workload Balancer] een filter maakt met het veld [!UICONTROL Assignment:Role ID] , wordt het gebied [!UICONTROL Unassigned Work] niet geladen.

**Bevatterend malplaatje gebruikend &quot;[!UICONTROL Customize and attach]&quot;optie ontruimt de waarden van het douanegebied**

_Projecten_

Als een gebruiker een malplaatje aan een project vastmaakt gebruikend &quot;[!UICONTROL Customize and attach]&quot;optie, en het project heeft een douaneformulier in bijlage aan het reeds, dragen de waarden van de douanegebieden niet over en moeten manueel re-ingegaan zijn. Dit gebeurt ook als de sjabloon hetzelfde aangepaste formulier bevat.

+++

+++**Update van het Onderhoud (Hete Fix) op 10 December, 2021**

**[!UICONTROL Whoops]fout wanneer het vastmaken van malplaatje aan bestaand project**

_Projecten_

Wanneer een gebruiker probeert om een malplaatje aan een bestaand project vast te maken, maakt het malplaatje niet vast, en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

+++

+++**Update van het Onderhoud op 9 December, 2021**


**Samengevouwen linkernavigatievenster breidt zich op paginading** uit

_Navigatie_

Wanneer een gebruiker de linkernavigatie heeft ingesteld op samenvouwen en vervolgens een pagina vernieuwt, wordt de linkernavigatie uitgebreid op de opnieuw geladen pagina. De linkernavigatie wordt ook uitgebreid als de gebruiker een pagina in een nieuw lusje opent.

**[!UICONTROL Workload Balancer]toont 0 toegewezen uren**

_[!UICONTROL Workload Balancer]_

Wanneer een gebruiker [!UICONTROL Workload Balancer] bekijkt en &quot;[!UICONTROL Show projected dates]&quot;plaatsen toegelaten heeft, om het even welke data in de toekomst tonen 0 toegewezen uren.

+++

+++**Update van het Onderhoud op 8 December, 2021**

**Erkenning stelt terug wanneer een update wordt gemaakt**

_Goedkeuringen_

Als een gebruiker een beslissing neemt over een goedkeuring met behulp van de objectkoptekst en vervolgens onmiddellijk een update uitvoert van het object, worden de goedkeuringspictogrammen opnieuw weergegeven in de koptekst en wordt de goedkeuringsbeslissing niet opgeslagen.

**[!UICONTROL Cannot inline edit an assignment in a report]**

_Rapporten_

Wanneer een gebruiker een toewijzing in een rapport inline probeert te bewerken, verandert de veldwaarde niet en wordt de bewerking niet opgeslagen.


+++

+++**Update van het Onderhoud op 2 December, 2021**

**Extra schuine streep toegevoegd toen manueel het typen URL**

_Verzoeken_

Wanneer een gebruiker een verzoek invult en handmatig een URL begint in te voeren, wordt op een bepaald punt aan het begin van de URL een extra schuine streep toegevoegd. De gebruiker kan de schuine streep niet verwijderen.

**de secties van de Douane kunnen niet uit linkernavigatievenster worden verwijderd**

_Navigatie_

Wanneer een gebruiker een aangepaste sectie uit het linkernavigatievenster probeert te verwijderen door op de X naast de sectie te klikken, wordt de sectie niet verwijderd.

**Niet toegewezen Werk laadt niet**

_[!UICONTROL Workload Balancer]_

Wanneer een gebruiker in de [!UICONTROL Workload Balancer] een filter maakt met het veld [!UICONTROL Assignment:Role ID] , wordt het gebied [!UICONTROL Unassigned Work] niet geladen.

**Pagina&#39;s laden niet in bepaalde browsers**

_[!DNL Workfront]_

Wanneer een gebruiker in [!DNL Workfront] werkt, worden pagina&#39;s niet geladen en krijgt de gebruiker de volgende foutmelding te zien:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

Dit is gemeld in

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Deze fout treedt willekeurig op en kan van invloed zijn op elk gebied van [!DNL Workfront] .

+++


## Updates in november 2021

+++**Update van het Onderhoud op 18 november, 2021**

**[!DNL Workfront]for [!DNL Jira] &quot;[!UICONTROL Invalid clientID or clientSecret]&quot; error on login**

_de integraties van Workfront_

Gebruikers zijn afgemeld bij [!DNL Jira] voor Workfront-integratie. Wanneer een gebruiker zich probeert aan te melden bij de [!DNL Workfront for Jira] -integratie, kan hij of zij zich niet aanmelden en wordt de volgende fout weergegeven:

&quot;[!UICONTROL Invalid clientID or clientSecret]&quot;

**De vorm van de Douane in bijlage aan verzoek werkt niet bij wanneer het nieuwe Onderwerp van de Rij wordt geselecteerd**

_Verzoeken_

Wanneer een gebruiker een verzoek creeert en een Onderwerp van de Rij selecteert dat automatisch een douaneformulier aan het verzoek vastmaakt, dan selecteert een verschillend Onderwerp van de Rij, blijft de douaneformulier van het eerste Onderwerp van de Rij in bijlage aan het verzoek.

**vertoning van Pictogrammen verkeerd**

_[!DNL Workfront]_

Pictogramafbeeldingen worden onjuist weergegeven. Dit is in vele gebieden over [!UICONTROL Workfront] gemeld.

**de Taken voeren niet naar PDF uit wanneer de &quot;Andere Grootte&quot;optie wordt geselecteerd.**

_Taken_

Als een gebruiker probeert om een taaklijst naar PDF uit te voeren, en &quot;[!UICONTROL Other Sizes]&quot;optie selecteert, kunnen zij een grootte selecteren en [!UICONTROL Export] klikken, maar de lijst voert niet uit. Er is geen foutbericht en er zijn geen andere aanwijzingen dat het exporteren is mislukt.

**de indicator van het Beeld toont niet in e-mailberichten**

_Meldingen_

Wanneer een gebruiker een afbeelding toevoegt aan een update en een e-mailbericht wordt verzonden naar de ontvanger van de update, bevat de e-mail geen indicator dat de update een afbeelding bevat.

**Pagina&#39;s laden niet in bepaalde browsers**

_[!DNL Workfront]_

Wanneer een gebruiker in [!DNL Workfront] werkt, worden pagina&#39;s niet geladen en krijgt de gebruiker de volgende foutmelding te zien:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

Dit is gemeld in

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Deze fout treedt willekeurig op en kan van invloed zijn op elk gebied van Workfront.

+++

+++**Update van het Onderhoud op 11 November, 2021**

**Uitgave met documentintegratie, lege pagina op document uploadt popup van[!DNL Google Drive*]*

_Documenten_

Wanneer een gebruiker een nieuw document aan [!DNL Workfront] van [!DNL Google Drive] probeert toe te voegen door [!UICONTROL Add New] te gebruiken > [!UICONTROL From [!DNL Google Drive]], blijft het uploadt popup scherm leeg.

**kan niet meer dan één filter in de Balancer van de Werkbelasting gebruiken**

_[!UICONTROL Workload Balancer]_

Wanneer een gebruiker probeert meer dan één filter in [!UICONTROL Workload Balancer] te gebruiken, zien zij de volgende kwesties:

* Wanneer de gebruiker twee filters selecteert, wordt alleen het onderste filter toegepast.
* Als de gebruiker meer dan twee filters selecteert, worden er geen resultaten weergegeven.

**&quot;[!UICONTROL Project Folders]&quot;documentkopbal mist van gebied van projectdocumenten**

_Projecten_

Wanneer een gebruiker in een project is en de documenten van het project bekijkt, mist de rubriek &quot;[!UICONTROL Project Folders]&quot;van de linkernavigatie. De vervolgkeuzepijl is er nog steeds en de gebruiker kan een map selecteren.

**Kolommen op Kanban board zijn te breed en kunnen niet worden aangepast**

_Gelijk_

Wanneer een gebruiker een Kanban-bord met meerdere kolommen weergeeft, zijn de kolommen te breed en moet de gebruiker schuiven om de kaarten weer te geven of naar de meest rechtse kolommen te verplaatsen. De kolombreedten kunnen niet worden aangepast, zodat de gebruiker de kolommen niet kleiner kan maken, zodat ze allemaal tegelijk op het scherm zichtbaar zijn.

**Verbeterde interface voor het creëren van een nieuw team**

_Teams_

Het maken van teams is nu intuïtiever met nieuwe visuele aanwijzingen. Wanneer u het [!UICONTROL Switch Teams] pictogram op om het even welke teampagina selecteert, heeft de [!UICONTROL Create New Team] verbinding een pictogram om &quot;[!UICONTROL new] te wijzen,&quot;en de verbinding wordt gescheiden van de rest van de lijst zodat ziet het niet als een teamnaam. Deze interface is het zelfde voor flexibele en niet-flexibele teams.

+++

+++**Update van het Onderhoud op 4 November, 2021**

**Nieuwe taken gebrek aan onjuiste taakbeperking**

_Taken_

Wanneer een gebruiker een nieuwe taak gebruikend &quot;[!UICONTROL New Task]&quot;knoop creeert, en de Nieuwe optie van de Datum van het Begin van het Standaard van de Taak wordt geplaatst aan &quot; [!UICONTROL Today],&quot;de taakbeperking van de gecreeerde taak wordt geplaatst aan &quot; [!UICONTROL As soon as possible]&quot;eerder dan &quot; [!UICONTROL Start no earlier than].&quot;

**de Gebieden tonen niet op de kaartjes van het het verhaaltje van de Gateway**

_Gelijk_

Wanneer een gebruiker een Google-storyboard bekijkt, geven de kaarten alleen de velden [!UICONTROL Description] en [!UICONTROL Status] weer. Andere velden, inclusief aangepaste velden, worden niet weergegeven.

**Kaarten keren op originele kolom terug alvorens aan nieuwe kolom** te bewegen

_Gelijk_

Wanneer een gebruiker een kaart naar een nieuwe kolom op het storyboard sleept, kan de gebruiker de kaart zien die wordt gesleept. Wanneer de gebruiker de kaart echter in de nieuwe kolom neerzet, wordt de kaart kort in de oorspronkelijke kolom weergegeven voordat deze in de nieuwe kolom wordt weergegeven.

**Waarden niet beschikbaar voor douanegebied in filter**

_[!UICONTROL Workload Balancer]_

Wanneer een gebruiker een filter probeert te maken met een aangepast veld, wordt de waarde voor dat aangepaste veld niet weergegeven en kan deze niet in het filter worden ingevoerd.

**Pagina&#39;s laden niet in [!DNL Firefox] browser**

_[!DNL Workfront]_

Wanneer een gebruiker in [!DNL Workfront] met een [!DNL Firefox] -browser werkt, worden pagina&#39;s niet geladen en ziet de gebruiker het volgende foutbericht:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

Deze fout treedt willekeurig op en kan van invloed zijn op elk gebied van [!DNL Workfront] .

**op datum betrekking hebbende fout wanneer het creëren van project van malplaatje.**

_Malplaatjes_

Als een gebruiker tot een project van een malplaatje leidt, en de planningswijze aan [!UICONTROL Start Date] plaatst, dan selecteert een taakbeperking, wanneer de gebruiker probeert om het project tot stand te brengen, wordt het project niet gecreeerd en de gebruiker ziet een foutenmelding die op de taakbeperking wordt gebaseerd.

**[!UICONTROL Export Gantt Chart]reageert niet**

_Gantt Grafiek_

Als een gebruiker in de nieuwe [!DNL Workfront] ervaring probeert om [!UICONTROL Gantt Chart] uit te voeren en &quot;[!UICONTROL What I See]&quot;optie selecteert, [!UICONTROL Gantt Chart] wordt niet uitgevoerd en de dialoogdoos is niet reactievoerend. De gebruiker kan het dialoogvenster niet sluiten of verlaten.

**vertoning van Pictogrammen verkeerd**

_[!DNL Workfront]_

Pictogramafbeeldingen worden onjuist weergegeven. Dit zijn gerapporteerde situaties, waaronder, maar niet beperkt tot:

* Afbeeldingen voor taakrollen of -groepen bij het delen van een object
* Pictogrammen links en rechts in kalenderrapporten
* Pictogrammen sorteren op rapportkolommen

**voegt checkboxes aan Verzoeken in de [!UICONTROL Submitted] sectie van het [!UICONTROL Requests] gebied** toe

_Verzoeken_

Er zijn selectievakjes toegevoegd links van de aanvraagnamen in [!UICONTROL Submitted list] van het [!UICONTROL Requests] -gebied. Zo kunt u een aanvraag gemakkelijker selecteren en aanvullende informatie bekijken.

**de Kwarten van de Douane worden nu gesteund in de filters van de Balancer van de Werkbelasting**

_[!UICONTROL Workload Balancer]_

De filters in [!UICONTROL Workload Balancer] ondersteunen nu aangepaste kwartalen.

**Bijgewerkte filterexploitant voor het gebied van de Duur op de Filters van de Balancer van de Werkbelasting**

_[!UICONTROL Workload Balancer]_

We hebben de filteroperatoren bijgewerkt wanneer we de [!UICONTROL Workload Balancer] -gebieden filteren op [!UICONTROL Duration] .

+++


## Updates in oktober 2021

+++**Update van het Onderhoud op 28 oktober, 2021**

**[!UICONTROL Home]en [!UICONTROL My Work] blank page weergeven**

_[!UICONTROL Home]/[!UICONTROL My Work]_

Wanneer een gebruiker naar [!UICONTROL Home] of Mijn werk navigeert, wordt de pagina als leeg weergegeven.

**kan niet [!UICONTROL Topic Group] details** bekijken of uitgeven

_Verzoeken_

Wanneer een gebruiker probeert om de details van een Groep van het Onderwerp te bekijken of uit te geven, toont de pagina die opent &quot;[!UICONTROL Topic Group Detail]&quot;in de kopbal maar anders leeg is

**Lege vereiste radioknopen worden automatisch ingevuld**

_Verzoeken_

Wanneer een gebruiker een aanvraag met een vereist veld voor een keuzerondje indient en de gebruiker geen waarde voor dat veld heeft geselecteerd voordat de aanvraag wordt ingediend, wordt de eerste waarde automatisch geselecteerd wanneer de aanvraag wordt verzonden.

+++

+++**Update van het Onderhoud op 21 Oktober, 2021**

**Kan geen filter toevoegen in[!UICONTROL Workload Balancer]**

_[!UICONTROL Workload Balancer]_

Wanneer een gebruiker in [!UICONTROL Workload Balancer] een filter probeert toe te voegen, wordt het deelvenster [!UICONTROL Add filter] geopend, maar wordt de inhoud van het deelvenster niet geladen en kan de gebruiker het filter niet toevoegen.

**Gegraveerde Bord van het Trommel toont geen verhalen**

_Gelijk_

Wanneer een gebruiker probeert om het gebied van de Trommel in de herhaling van een team te bekijken, toont het manuscriptbord leeg.

**het verhaalbord van het Trommel is leeg wanneer het gebruiken van filters**

_Gelijk_

Wanneer een gebruiker probeert om een het verhaalbord van het Trommel te bekijken gebruikend om het even welk filter maar &quot;[!UICONTROL All Team]&quot;filter, een leeg scherm toont. De gebruiker kan niet terug naar &quot;[!UICONTROL All Team]&quot;filter schakelen.

**de Lijsten zijn zichtbaar slechts op een klein gebied van het scherm**

_Lijsten_

Wanneer een gebruiker een lijst probeert weer te geven terwijl een [!DNL Safari] browser op een [!DNL Mac] wordt gebruikt [!DNL Big Sur OS] , wordt de lijst slechts in een klein gedeelte van het scherm weergegeven. De gebruiker kan door de lijst schuiven, maar het gebied kan zo klein zijn dat de lijst moeilijk of onleesbaar is.

**Lege vereiste radioknopen worden automatisch ingevuld**

_Verzoeken_

Wanneer een gebruiker een aanvraag met een vereist veld voor een keuzerondje indient en de gebruiker geen waarde voor dat veld heeft geselecteerd voordat de aanvraag wordt ingediend, wordt de eerste waarde automatisch geselecteerd wanneer de aanvraag wordt verzonden.

+++

+++**Update van het Onderhoud (Hete Fix) op 21 Oktober, 2021**

**[!UICONTROL Home]en [!UICONTROL My Work] blank page weergeven**

_[!UICONTROL Home]/[!UICONTROL My Work]_

Wanneer een gebruiker naar [!UICONTROL Home] of [!UICONTROL My Work] navigeert, wordt de pagina als leeg weergegeven.

+++

+++**Update van het Onderhoud op 20 oktober, 2021**

**[!UICONTROL Workload Balancer]plaatsen als standaard het plannen optie**

_[!UICONTROL Workload Balancer]_

Als een gebruiker die [!UICONTROL Scheduler] als standaardwaarde heeft ingesteld, deze gaat gebruiken, ziet hij of zij dat [!UICONTROL Workload Balancer] als standaardwaarde is ingesteld.

+++

+++**Update van het Onderhoud (Hete Fix) op 19 Oktober, 2021**

**Onbekwaam om een verzoek toe te wijzen wanneer het creëren van het**

_Verzoeken_

Wanneer een gebruiker in de nieuwe [!DNL Workfront] ervaring een verzoek creeert en probeert om een gebruiker toe te wijzen door hun naam in het [!UICONTROL Assignments] gebied te typen, toont het gebied niet de drop-down lijst, en de gebruiker kan niet de naam van de ontvanger selecteren.

**het verhaalbord van het Trommel is leeg wanneer het gebruiken van filters**

_Gelijk_

Wanneer een gebruiker probeert om een het verhaalbord van het Trommel te bekijken gebruikend om het even welk filter maar &quot;[!UICONTROL All Team]&quot;filter, een leeg scherm toont. De gebruiker kan niet terug naar &quot;[!UICONTROL All Team]&quot;filter schakelen.

+++

+++**Update van het Onderhoud op 14 oktober, 2021**

**Malplaatjes die worden gedeeld systeem-breed zijn niet zichtbaar**

_Malplaatjes_

Wanneer een gebruiker een project creeert en probeert om een malplaatje te gebruiken dat systeem-breed is gedeeld, kan de gebruiker niet het malplaatje in de lijst van beschikbare malplaatjes zien, en kan niet het malplaatje gebruiken.

**Fout wanneer het creëren van projecten van malplaatjes**

_Malplaatjes_

Wanneer een gebruiker probeert om een project van een malplaatje tot stand te brengen dat een douaneformulier met een sectie omvat die slechts voor beheerders zichtbaar is, kan de gebruiker niet het project tot stand brengen en het volgende bericht toont:

&quot;[!UICONTROL Category with primary key value(s) "xxxxxxxxxxxxxxxx" not found]&quot;

**Bijgewerkte verbindingen voor het kopiëren en het bewegen van taken**

_Taken_

De verbindingen voor het kopiëren en het bewegen van taken zijn bijgewerkt aan &quot;[!UICONTROL Copy to]&quot;en &quot;[!UICONTROL Move to]&quot;zowel op de taakpagina als in een taaklijst.

**verwijdert grens aan het onderzoek van de baanrol wanneer het met voeten treden van het factureringspercentages voor een project**

Taken rollen

OPMERKING: Deze update is momenteel beschikbaar in de voorbeeldomgeving en wordt tijdens de productieresessie 22.1 in productie gehouden. Voor meer informatie, zie &quot;22.1 Overzicht van de Versie.&quot;

Het met voeten treden van factureringspercentages voor baanrollen in een project zoekt nu naar alle baanrollen in het systeem.

Eerder, zocht [!DNL Workfront] naar baanrollen in de eerste 2000 rollen in alfabetische orde.

+++

+++**Update van het Onderhoud op 7 Oktober, 2021**

**[!UICONTROL In-app notifications disappear from]notifications center**

_Meldingen_

Wanneer een gebruiker het berichtcentrum bekijkt, zijn sommige eerder zichtbare berichten niet meer zichtbaar. In sommige gevallen kan het bericht verdwijnen voordat de gebruiker het ziet.

**de aankondigingen zijn niet zichtbaar op de [!UICONTROL All Announcements] pagina**

_Meldingen_

Wanneer een gebruiker de pagina [!UICONTROL All Announcements] opent vanuit het [!UICONTROL Notifications] -gebied, zijn er geen aankondigingen zichtbaar in de volgende gebieden:

* [!UICONTROL Inbox]
* [!UICONTROL Favorites]
* [!UICONTROL Drafts]
* [!UICONTROL Deleted]

**Fout wanneer het maken van toewijzing in[!UICONTROL Workload Balancer]**

_[!UICONTROL Workload Balancer]_

Wanneer een gebruiker een toewijzing probeert te maken vanuit [!UICONTROL Workload Balancer] , wordt het werk niet toegewezen en ziet de gebruiker de volgende fout:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

+++


## Updates in september 2021

+++**Update van het Onderhoud op 30 september, 2021**

**Fout wanneer het navigeren snel aan of weg van[!UICONTROL Home]**

_Huis_

Wanneer een gebruiker snel naar [!UICONTROL Home] navigeert of er vandaan, wordt de pagina niet geladen en wordt de volgende fout weergegeven:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

Dit kan ook gebeuren wanneer u via een punt naar [!UICONTROL Home] navigeert.

+++

+++**Update van het Onderhoud op 23 September, 2021**

**[!UICONTROL Access Denied]fout bij het bekijken van tickets verzonden naar[!DNL Workfront]**

_Kwesties_

Wanneer een gebruiker een ticket naar [!DNL Workfront] heeft verzonden en het ticket probeert te bekijken, wordt de volgende fout weergegeven:

&quot;[!UICONTROL Access Denied: Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

**Samenvatting van bedrijfsGeval toont onjuiste waarden**

_Projecten_

Wanneer een gebruiker het overzichtsvenster van [!UICONTROL Business Case] bekijkt, weerspiegelen de weergegeven waarden niet de waarden in de afzonderlijke [!UICONTROL Business Case] -secties.

**de kopballen van de Kolom lijnen niet omhoog met kolommen in lijsten**

_Opstelling_

Wanneer een gebruiker zich in het [!UICONTROL Setup] -gebied bevindt en een lijst weergeeft, zoals [!UICONTROL Custom Forms] of [!UICONTROL Access Levels] , worden de kolomkoppen voor die lijst niet uitgelijnd met de kolommen in de lijst.

**de Gebruikers zonder de juiste het delen toestemmingen kunnen douanevormen aan voorwerpen vastmaken**

_Aangepaste Forms_

Wanneer een aangepast formulier in de nieuwe [!DNL Adobe Workfront] -ervaring is ingesteld op systeembreed zichtbaar, kunnen alle gebruikers dit aangepaste formulier aan een object koppelen. Ze moeten het aangepaste formulier echter alleen kunnen bekijken en het alleen aan een object kunnen koppelen als het specifiek met hen is gedeeld.

+++

+++**Update van het Onderhoud op 16 september, 2021**

**kan groepen** niet uitgeven

_Groepen_

Wanneer een gebruiker een groep probeert te bewerken of te verwijderen, wordt de groep niet bewerkt of verwijderd en ziet de gebruiker het volgende bericht:

&quot;[!UICONTROL Let's try that again. Group with primary key value(s) "(Group's ID)" not found]&quot;

**[!UICONTROL Portfolio Optimizer]projecten niet weergeven**

_Portfolio&#39;s_

Wanneer een gebruiker probeert om projecten in [!UICONTROL Portfolio Optimizer] te bekijken, toont de projectlijst niet en de gebruiker kan daarom niet met de projecten in wisselwerking staan.

+++

+++**Update van het Onderhoud (Hete Fix) op 10 September, 2021**

**Datum en Tijd duidelijk als UTC wanneer het uitgeven inline**

_Lijsten_

Wanneer een gebruiker een datum of tijd inline bewerkt (in een lijst met objecten), worden de datum en tijd gemarkeerd als UTC. De datum en tijd worden niet ingesteld in UTC in [!DNL Workfront] . Dit probleem is alleen van invloed op de weergave, niet op de feitelijke gegevens.

**kleur van de Tekst die correct toont wanneer het voorwaardelijke formatteren wordt toegepast**

_Rapporten_

Wanneer een gebruiker een rapport weergeeft met voorwaardelijke opmaak waarmee de tekstkleur wordt gewijzigd, wordt de tekstkleur ongewijzigd weergegeven.

+++

+++**Update van het Onderhoud op 9 September, 2021**

**de Kwesties tonen geen uitgiftedetails**

_Huis_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] -ervaring een uitgave in [!UICONTROL Work List] selecteert, wordt in de voorvertoning in het rechterdeelvenster aangegeven dat er in bepaalde velden geen waarden zijn ingevoerd. Als u echter naar de uitgave navigeert en [!UICONTROL Issue Details] bekijkt, worden voor deze velden waarden ingevoerd.

**de Gebruikers hebben de toestemmingen van Contribute nodig om de [!UICONTROL Approvals] sectie in de nieuwe Ervaring van Workfront** te bekijken

_Goedkeuringen_

Gebruikers hebben [!UICONTROL Contribute] -machtigingen voor een object nodig om de sectie [!UICONTROL Approvals] in de nieuwe [!DNL Workfront] -ervaring te kunnen bekijken. Ze moeten alleen [!UICONTROL View] machtigingen hebben om het tabblad [!UICONTROL Approvals] te kunnen weergeven wanneer er een goedkeuringsproces voor het object plaatsvindt.

**[!UICONTROL Whoops]error when using filters**

_Lijsten_

Wanneer een gebruiker een van de volgende filters probeert te gebruiken:

* [!UICONTROL All Projects]
* [!UICONTROL Projects I'm On]
* [!UICONTROL My Current Tasks]

de lijst wordt leeg gelaten en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Let's try that again.]&quot;

**[!UICONTROL Tasks]-sectie wordt leeg gelaten wanneer u inline bewerkt**

_Malplaatjes_

Wanneer een gebruiker probeert om taken inline uit te geven in een malplaatje gebruikend een mening die &quot; [!UICONTROL Assign To: Name]&quot;gebied omvat, en de taak een gebruiker bevat, gaat de [!UICONTROL Tasks] sectie leeg en de gebruiker kan de malplaatjetaken niet uitgeven.

**Kan niet exporteren[!UICONTROL Portfolio Optimizer]**

_Portfolio&#39;s_

Wanneer een gebruiker probeert de [!UICONTROL Portfolio Optimizer] te exporteren en op een van de exportopties klikt, wordt de [!UICONTROL Portfolio Optimizer] niet geëxporteerd.

**de Meldingen worden niet verzonden voor antwoorden**

_Meldingen_

Wanneer een gebruiker op een update in [!DNL Workfront] antwoordt, ontvangen andere gebruikers in de commentaardraad geen berichten.

**Veranderingen in de vertraging van de douanegegevensoorzaak**

_de gebieden van de Douane_

Wanneer een gebruiker aangepaste gegevens wijzigt die wijzigingen in andere weergegeven gegevens activeren, worden de wijzigingen langzaam geladen.

**groeperen &quot;[!UICONTROL Collapse or Expand All]&quot;pictogram toont niet**

_Meldend_

Het pictogram &quot;[!UICONTROL Collapse or Expand All]&quot;toont niet in de kopbal van een lijst of een rapport wanneer de groeperingen op de lijst of het rapport worden toegepast.

**[!UICONTROL Check]en [!UICONTROL Cancel] opties niet zichtbaar wanneer het veranderen van taaktoewijzingen**

_[!UICONTROL Workload Balancer]_

Wanneer een gebruiker de taaktoewijzing voor een taak probeert te wijzigen en het tijdkader van die taak zich tot of buiten de rand van de zichtbare pagina uitstrekt, zijn de knoppen [!UICONTROL Check] en [!UICONTROL Cancel] niet zichtbaar en kan de gebruiker de toewijzingswijzigingen niet opslaan of annuleren.

**Toevoegend een douanegebied aan [!UICONTROL Home] veroorzaakt ontbrekende gebiedsgegevens**

_[!UICONTROL Home]_

Wanneer een aangepast veld wordt toegevoegd aan [!UICONTROL Home] , worden ontbrekende gegevens in andere velden onjuist weergegeven.

**kan geen verbonden punten bekijken wanneer het programma geopend als een andere gebruiker**

_Integraties_

Als een beheerder probeerde om verbonden punten van een externe leverancier te bekijken terwijl het programma opende als een andere gebruiker, konden zij niet de verbonden omslagen openen en konden niet de punten bekijken.

+++

+++**Update van het Onderhoud op 2 September, 2021**

**kan douane dashboard** vastzetten niet

_Dashboards_

Wanneer een gebruiker een aangepast dashboard probeert vast te zetten, wordt het dashboard niet vastgezet en ziet de gebruiker de volgende fout:

&quot;[!UICONTROL Something went wrong while pinning. Please contact [!DNL Workfront] so we can fix this.]&quot;

**[!DNL Workfront Proof]print summary is blank**

[!DNL Workfront Proof]

Wanneer een gebruiker het afdrukoverzicht opent om een proefdruk af te drukken, wordt de koptekst weergegeven, maar is het overzicht zelf leeg.

+++


## Updates in augustus 2021

+++**Update van het Onderhoud op 26 augustus, 2021**

**In [!DNL Safari] is er een donkergrijze achtergrond op de tekst van kolomkopballen**

_Lijsten_

In de browser van [!DNL Safari] is er een donkergrijze achtergrond op kolomkoppen, die de tekst markeert. Dit is geen probleem met andere ondersteunde browsers.

**Onverwachte fout wanneer het plaatsen van predecessors**

_Taken_

Wanneer een gebruiker een taak probeert in te stellen als een voorganger die inline bewerken gebruikt, wordt de voorganger niet ingesteld en ziet de gebruiker het volgende bericht:

&quot;[!UICONTROL An unexpected error happened]&quot;

+++

+++**Update van het Onderhoud op 19 augustus, 2021**

**Bewaarde filters vermist na het selecteren van een filter dat geen kwesties** toont

_Lijsten_

Opgeslagen filters ontbreken in een lijst met problemen nadat u een filter hebt geselecteerd dat geen resultaten weergeeft.

**de Kwesties tonen geen uitgiftedetails**

_[!UICONTROL Home]summary_

Wanneer een gebruiker in [!DNL Adobe Workfront Classic] een uitgave selecteert in [!UICONTROL Work List] , wordt in de voorvertoning in het rechterdeelvenster aangegeven dat er in bepaalde velden geen waarden zijn ingevoerd. Als u echter naar de uitgave navigeert en [!UICONTROL Issue Details] bekijkt, worden voor deze velden waarden ingevoerd.

+++

+++**Update van het Onderhoud op 12 augustus, 2021**

**kan niet veranderlijke mening op project** aanpassen

_Gelijk_

Wanneer een gebruiker probeert een eerder bestaande bestandsweergave aan te passen op een project, wordt het venster gesloten en kan de gebruiker de weergave niet bewerken.

**Naam verandert niet op nieuwe documentversies**

_Documenten_

Wanneer een gebruiker een nieuwe versie van een document uploadt, wordt de naam van het document niet bijgewerkt zodat deze overeenkomt met de naam van de nieuwste versie.

**het pictogram van de Voorganger wordt niet groen wanneer voorganger volledig is.**

_Taken_

Wanneer een taak een voorgangstaak heeft, en die voorgangstaak volledig is, wordt het voorgangerpictogram in de afhankelijke taak niet groen.

Wanneer een aangepast formulier in de nieuwe [!DNL Adobe Workfront] -ervaring is ingesteld op systeembreed zichtbaar, kunnen alle gebruikers dit aangepaste formulier aan een object koppelen. Ze moeten het aangepaste formulier echter alleen kunnen bekijken en het alleen aan een object kunnen koppelen als het specifiek met hen is gedeeld.

+++

+++**Update van het Onderhoud (Hete Fix) op 6 augustus, 2021**

**Onbekwaam om kalenders in [!DNL Outloo] k de montages van de Kalender** te selecteren

_Huis_

Wanneer een gebruiker in de nieuwe [!DNL Workfront] -ervaring zijn [!DNL Outlook] -agenda thuis bekijkt en de instellingen opent, ontbreken de selectievakjes voor het selecteren van kalenders. Als de gebruiker klikt op de plaats waar het selectievakje zich bevindt, reageert de kalender alsof het selectievakje aanwezig is.

**Kan verbinding met[!UICONTROL Webdam]** niet opnieuw autoriseren of verifiëren

_[!DNL Workfront Fusion]_

[!DNL Adobe Workfront Fusion] -gebruikers met scenario&#39;s die verbinding maken met [!UICONTROL Webdam] moeten er rekening mee houden dat [!UICONTROL Webdam] -verbindingen elke 14 dagen handmatig opnieuw moeten worden geverifieerd. De API van [!UICONTROL Webdam] ondersteunt momenteel geen automatische herautorisatie.

+++

+++**Update van het Onderhoud op 5 Augustus, 2021**

**Onbekwaam om met document in [!UICONTROL Summary panel] of [!UICONTROL More] menu** in wisselwerking te staan

_Documenten_

Wanneer een gebruiker in de nieuwe [!DNL Workfront] -ervaring een document weergeeft en probeert een selectie te maken in het menu [!UICONTROL Summary panel] of [!UICONTROL More] , wordt het document uitgeschakeld, waardoor het menu [!UICONTROL Summary panel] of [!UICONTROL More] leeg blijft.

**[!UICONTROL New Request]knop ontbreekt**

_Verzoeken_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] -ervaring naar de [!UICONTROL Requests] -pagina gaat, wordt de knop [!UICONTROL New Request] niet weergegeven en kan hij of zij geen aanvraag indienen.

**de Gebruikers zonder de juiste het delen toestemmingen kunnen douanevormen aan voorwerpen vastmaken**

_Aangepaste Forms_

Wanneer een aangepast formulier in de nieuwe [!DNL Adobe Workfront] -ervaring is ingesteld op systeembreed zichtbaar, kunnen alle gebruikers dit aangepaste formulier aan een object koppelen. Ze moeten het aangepaste formulier echter alleen kunnen bekijken en het alleen aan een object kunnen koppelen als het specifiek met hen is gedeeld.

**kan proefdrukmontages niet veranderen wanneer het creëren van een nieuwe proef**

_[!DNL Workfront Proof]_

Wanneer een gebruiker een nieuwe proefdruk maakt en de instellingen probeert te wijzigen, wordt de instelling hersteld naar de vorige instelling.

**[!UICONTROL Story Board]wordt niet correct geladen**

_Gelijk_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] -ervaring naar een [!UICONTROL Story Board] navigeert, kan het 10 seconden duren om het board te laden. De vertraging bij het laden is te wijten aan het feit dat het systeem alle kaarten laadt terwijl het slechts 50 kaarten tegelijk moet laden.

+++


## Updates in juli 2021

+++**Update van het Onderhoud (Hete Fix) op 29 Juli, 2021**

**Onbekwaam om nieuwe proef of nieuwe proefdrukversie** te uploaden

_[!DNL Workfront Proof]_

Wanneer een gebruiker een nieuwe proefdruk of een nieuwe versie van een proefdruk probeert te uploaden in de klassieke [!DNL Workfront] ervaring, is de nieuwe proefdruk of de nieuwe versiepagina leeg, en de gebruiker kan de proef of de versie niet uploaden.

+++

+++**Update van het Onderhoud op 29 Juli, 2021**

**[!UICONTROL Proof Activity]en [!UICONTROL Proof Viewer Settings] pagina&#39;s altijd beschikbaar**

_[!DNL Workfront Proof]_

De instellingenpagina&#39;s [!UICONTROL Proof Activity] en [!UICONTROL Proof Viewer] zijn nu altijd zichtbaar, zelfs als de gebruiker geen toegang heeft om deze pagina&#39;s bij te werken.

Eerder waren de pagina&#39;s [!UICONTROL Proof Activity] en [!UICONTROL Proof Viewer Settings] aan de linkerkant niet altijd zichtbaar wanneer een gebruiker met een aangepast machtigingsprofiel voor proefdrukken naar een document navigeerde.

**Foutbericht bij gebruik van [!UICONTROL Percentage] option for[!UICONTROL Allocated hours]**

_[!UICONTROL Workload Balancer]_

Wanneer een gebruiker de optie [!UICONTROL Percentage] voor [!UICONTROL Allocated hours] selecteert en het werk wordt vermeld in de sectie [!UICONTROL Unassigned work] , krijgt de gebruiker de volgende fout te zien:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

+++

+++**Update van het Onderhoud op 22 Juli, 2021**

**Nieuwe namen van de proefdrukversie die** worden afgesneden

_[!DNL Workfront Proof]_

Wanneer een gebruiker in [!DNL Adobe Workfront Classic] een nieuwe versie van een proefdruk uploadt die een punt in filename bevat, wordt filename geschrapt aan het eind.

+++

+++**Update van het Onderhoud (Hete Fix) op 19 Juli, 2021**

**Fout terwijl het proberen om aan projecten, timesheets, taken, of programma&#39;s te navigeren**

In de nieuwe [!DNL Adobe Workfront] ervaring, wanneer een gebruiker probeert om aan projecten, timesheets, taken, of programma&#39;s te navigeren, zien zij het foutenbericht &quot; [!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

+++

+++**Update van het Onderhoud op 15 Juli, 2021**

**Standaard prioriteit op nieuwe verzoeken is onjuist**

_Verzoeken_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] ervaring een verzoek creeert, respecteert het verzoek niet de standaardprioriteit die in [!UICONTROL Project Preferences] wordt geplaatst en zij kunnen niet de prioriteit aanpassen alvorens het verzoek te voorleggen.

**[!UICONTROL Go to proof]koppeling is niet rechtstreeks naar opmerking**

_E-mailberichten_

Wanneer een gebruiker een e-mailbericht voor een proefdrukopmerking ontvangt en op [!UICONTROL Go to proof] klikt, wordt hij of zij naar de verkeerde opmerking in de proefdrukproef verwezen of wordt hij of zij helemaal niet naar een opmerking verwezen.

**Rich het gebiedswaarden van de Tekst niet overgebracht na het omzetten van een kwestie in een taak**

_Aangepaste Forms_

Wanneer een gebruiker een uitgave in een taak omzet en de uitgave een douaneformulier in bijlage met een waarde in een tekstgebied met Rich Text het formatteren heeft, neemt de waarde in het tekstgebied niet na omzetting over.

**de gebiedswaarden van de Douane veranderen na selectie**

_[!DNL Workfront Proof]_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] ervaring een nieuwe proef creeert en zij een waarde in sommige douanevelden op een proef ingaan, keert de waarde van sommige vorige gebieden aan de standaardwaarden in plaats van de waarde terug de gebruiker inging.

**[!UICONTROL Assign to]typeahead werkt niet**

_[!UICONTROL Home]_

Wanneer een gebruiker in [!DNL Adobe Workfront Classic] een project, taak of verzoek maakt vanuit het [!UICONTROL Home] -gebied, worden in het [!UICONTROL Assign to] -veld typeahead geen gebruikersnamen ingevuld.

**het ronden van uren verkeerd**

_Timesheets_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] ervaring naar [!UICONTROL Timesheets] > [!UICONTROL All Timesheets] navigeert, ziet hij of zij dat de totale urenaantallen voor sommige tijdbladen tot één decimaal in plaats van in stappen van 0,25 worden afgerond, maar dat het totale aantal uren correct in de individuele tijdspagina wordt weergegeven. In het gebied All Timesheets wordt bijvoorbeeld in totaal 44,8 uur op het tijdschrift vermeld, maar bij het openen van het tijdschrift wordt in totaal 44,75 uur weergegeven.

**Onbekwaam om goedkeuringen** te delegeren

_[!UICONTROL Home]_

Wanneer een gebruiker in [!DNL Adobe Workfront Classic] [!UICONTROL Delegate My Approvals] in het [!UICONTROL Home] gebied klikt en hij of zij de naam begint te typen van de gebruiker aan wie hij of zij probeert af te vaardigen, worden er geen resultaten weergegeven in de lijst van [!UICONTROL typeahead] en kunnen hij of zij geen gebruiker selecteren.

**[!UICONTROL Gantt Chart]de mening is niet beschikbaar voor de rapporten van de Taak**

_Rapporten_

NOTA: Dit beïnvloedt ook de rapporten van het Project.

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] ervaring een Taakrapport opent, ontbreekt de optie om een [!UICONTROL Gantt Chart] mening van de rapporttoolbar te selecteren. Als de weergave [!UICONTROL Gantt Chart] standaard in het rapport wordt weergegeven, wordt een lijstopmaak weergegeven.

**het klikken [!UICONTROL See More] op rapport laadt niets**

_Dashboards_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] ervaring een rapport op een dashboard bekijkt en zij [!UICONTROL See More] klikken, gebeurt niets en kunnen zij niet alle punten in het rapport bekijken.

+++

+++**[!DNL Adobe Workfront Fusion]Onderhoudsupdate op 1 juli 2021**

**het kopiëren modules werkt niet**

_[!DNL Adobe Workfront Fusion]_

Wanneer een gebruiker meerdere modules selecteert en probeert te kopiëren en plakken, plakken de modules niet.

+++

+++**Update van het Onderhoud op 1 Juli, 2021**

**Kleur die voor kaarten wordt geplaatst niet gerespecteerd**

_Kanban_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] ervaring specifieke kaartkleuren in de teammontages plaatst, worden die kleuren niet weerspiegeld op de kaarten Kanban.

**Onbekwaam om tekst op het gebied van het douanebericht te kleven**

_[!DNL Workfront Proof]_

Wanneer een gebruiker een nieuwe proefdruk maakt in [!UICONTROL Web Proofing Viewer] en probeert tekst te plakken in het [!UICONTROL Message] -veld in de [!UICONTROL Email notification] -sectie, kan de gebruiker de tekst niet plakken. Dit lijkt alleen te gebeuren wanneer de tekst alinea-opmaak heeft en er een alinea-einde is.

**de verzoeken worden voorgelegd met lege vereiste gebieden**

_Verzoeken_

Wanneer een gebruiker een verzoek indient en het verzendt, wordt de informatie op vereiste gebieden niet voorgelegd met het verzoek.

**[!UICONTROL New Request]knop ontbreekt**

_Verzoeken_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] -ervaring naar de [!UICONTROL Requests] -pagina gaat, wordt de knop [!UICONTROL New Request] niet weergegeven en kan hij of zij geen aanvraag indienen.

**Fout wanneer het uitbreiden van een douanevorm**

_Projecten_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] ervaring probeert om een douaneformulier uit te breiden in bijlage aan een project, kunnen zij niet het douaneformulier openen en het foutenbericht &quot; [!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;zien verfrist de pagina niet de kwestie oplossen.

**[!DNL Adobe Workfront]branding wordt nu weergegeven in e-mails van het aankondigingscentrum**

E-mails

Aangezien de [!DNL Adobe Workfront] -branding in de hele toepassing wordt geïmplementeerd, zijn de volgende updates uitgevoerd om e-mailberichten in het aankondigingscentrum te verzenden:

* De [!DNL Adobe Workfront] leeuw is toegevoegd aan het hoofdinhoudsgebied.
* Het [!DNL Adobe Workfront] -logo is toegevoegd aan de voettekst.

In de toekomst wordt deze branding weergegeven op extra soorten e-mails van Workfront.

+++


## Updates in juni 2021

+++**Update van het Onderhoud op 24 juni, 2021**

**kan geen team** uitgeven

_Gelijk_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] -ervaring op [!UICONTROL Edit] klikt om de [!DNL Edit] Team-pagina voor een Agile-team te openen, wordt de pagina in eerste instantie geladen, verdwijnen de instellingen en wordt de pagina leeg gelaten.

**Gegevens die uit voorgelegd verzoek worden verwijderd**

_Verzoeken_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] -ervaring een aanvraag invult, ontbreekt in de verzonden aanvraag de ingevoerde waarden voor sommige aangepaste velden, soms inclusief vereiste velden.

**Kolommen tonen niet**

_Kanban_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] -ervaring een aangepaste [!UICONTROL Additional Fields] -kolom toevoegt aan een Kanban Board, worden alle kolomkoppen niet meer weergegeven op het bord.

+++

+++**[!DNL Adobe Workfront Fusion]Onderhoudsupdate op 23 juni 2021**

**Verwijderde gebroken verbinding in berichte-mails**

_[!DNL Adobe Workfront Fusion]_

De koppeling naar meldingsinstellingen is verwijderd uit e-mailberichten van [!DNL Adobe Workfront Fusion] .
Zie [!DNL Adobe Workfront Fusion] Organisaties en teams voor informatie over het wijzigen van meldingsinstellingen.

+++

+++**Update van het Onderhoud op 17 Juni, 2021**

**[!UICONTROL Gantt Chart]de mening is niet beschikbaar voor het rapport van de Taak**

_Rapporten_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] ervaring een Taakrapport opent, ontbreekt de optie om een [!UICONTROL Gantt Chart] mening van de rapporttoolbar te selecteren. Als de weergave [!UICONTROL Gantt Chart] standaard in het rapport wordt weergegeven, wordt een lijstopmaak weergegeven.

**fout van de de grensbeperking van het Karakter die niet op verzoekvoorlegging voorkomt**

_Verzoeken_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] -ervaring een aanvraag probeert in te dienen en de tekenlimiet voor een veld overschrijdt, kunnen deze de aanvraag niet verzenden en wordt er geen foutbericht weergegeven. In [!DNL Adobe Workfront Classic] ziet de gebruiker de waarschuwing &quot;[!UICONTROL [number] characters over" and when they attempt to submit the request, they see the error message "Please check the following: Please enter no more than 2000 characters (you entered [number] characters).]&quot;

+++

+++**Update van het Onderhoud op 10 Juni, 2021**

**Geherordende malplaatjetaken bewegen zich niet**

_Malplaatjes_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] ervaring een malplaatjetaak aan een nieuwe plaats in een lijst sleept, werkt het aantal van de malplaatjetaak bij, maar het verandert niet in orde.

**de taken van het Kind selecteerden niet met oudertaken**

_Malplaatjes_

Wanneer een gebruiker een oudertaak op een project selecteert dat van een malplaatje wordt gecreeerd, worden de kindtaken niet automatisch geselecteerd.

**Inline het uitgeven mijlpalen op een taaklijst toont alle mijlpalen**

_Projecten_

Wanneer er een milestone-pad aan een project is toegevoegd en een gebruiker in de nieuwe [!DNL Adobe Workfront] -ervaring de [!UICONTROL Milestone: Name] -kolom in die takenlijst inline bewerkt, worden alle milestone-paden weergegeven in het vervolgkeuzemenu, in plaats van alleen de milestone-paden die aan dat project zijn gekoppeld.

+++

+++**Update van het Onderhoud op 3 Juni, 2021**

**Vragen veroorzaakt pagina om te schudden**

_Rapporten_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] ervaring een rapport met een herinnering in werking stelt, bewegen de kolommen in het rapport snel van links naar rechts.

**Sommige uitdrukkingen op de [!UICONTROL New proof] pagina vertalen niet behoorlijk**

_[!DNL Workfront Proof]_

Wanneer een gebruiker naar de pagina [!UICONTROL New proof creation] in [!DNL Workfront Proof] navigeert en de inhoud naar een andere taal dan het Engels wordt vertaald, worden sommige woorden nog steeds in het Engels weergegeven.

**Gedeactiveerde en verwijderde labels die aan gebruikers zijn toegevoegd[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

[!UICONTROL Deactivated] en [!UICONTROL Deleted] -gebruikerslabels zijn toegevoegd aan de volgende gebieden in [!DNL Workfront] Proef:

* [!UICONTROL Proof details] pagina
* [!UICONTROL Proofing views]
* [!UICONTROL Proofing viewer]
* [!UICONTROL Proofing workflows]
* [!UICONTROL Print comments] pagina
* [!UICONTROL User] pagina

+++


## Updates in mei 2021

+++**Update van het Onderhoud op 27 Mei, 2021**

**[!UICONTROL Commit Date]Kalender wordt weergegeven voor updates**

_Taken_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] -ervaring een update voor een taak invoert, wordt de [!UICONTROL Commit Date] -kalender weergegeven zonder dat de gebruiker het [!UICONTROL Commit Date] -veld selecteert.

**[!UICONTROL More]ontbreekt in filters, weergaven en groepen**

_Lijsten_

Wanneer een gebruiker in de nieuwe [!DNL Adobe Workfront] ervaring de filters, meningen, of groepen voor een lijst bekijkt, mist het [!UICONTROL More] menupictogram, die hen verhindert te delen of - als zij toegang hebben - verwijderend filters, meningen, of groeperingen.

**het kopiëren en het Plakken van een project [!UICONTROL Reference Number] voegt &quot;[!UICONTROL This] toe&quot;**

_Projecten_

Wanneer een gebruiker in de nieuwe [!DNL Workfront] ervaring aan een project navigeert, kopieert [!UICONTROL Reference Number] van het [!UICONTROL Overview] gebied, dan kleeft het, wordt het woord &quot;[!UICONTROL This]&quot;toegevoegd aan het eind van het aantal.

**[!UICONTROL Daily Digest]E-mails worden verzonden wanneer deze zijn uitgeschakeld**

_E-mailberichten_

Sommige gebruikers ontvangen [!UICONTROL Daily Digest] e-mailmeldingen wanneer deze niet zijn ingeschakeld in hun gebruikersinstellingen.

**het voorwerp bestaat niet meer fout**

_Voorwerpen_

Wanneer een gebruiker in de nieuwe [!DNL Workfront] ervaring probeert om bepaalde voorwerpen te openen, zien zij het foutenbericht &quot; [!UICONTROL The (object) no longer exists: You may have mistyped the web address. Double check it and try entering the address again.]&quot;De objecten verbinding verschijnt nog in lijsten, recents, favorieten, onderzoeksresultaten, enz., maar zij kunnen niet tot het toegang hebben en het verschijnt niet in de Bak met geschrapte voorwerpen.



+++

+++**Update van het Onderhoud op 20 Mei, 2021**

**de opties van het Bewijs ontbreken**

_Proofs_

Wanneer een gebruiker een andere versie van een proefdruk uploadt in [!DNL Workfront] , ontbreken de koppelingen [!UICONTROL Open Proof] en [!UICONTROL Proofing Workflow] , zodat het lijkt alsof het een document in plaats van een proefdruk is. Wanneer deze koppelingen ontbreken, wordt het label [!UICONTROL Pending] ook weergegeven en kunnen andere gebruikers de proefdruk niet genereren wanneer deze de status [!UICONTROL Pending] heeft.

**Gebruikers die geen geplande rapportleveringen ontvangen**

_Rapporten_

Wanneer sommige rapporten voor rapportlevering gepland zijn, ontvangen de gebruikers soms niet de rapporten.

**Onbekwaam om toegang voor het Malplaatje van de Lay-out te verwijderen**

_Dashboards_

Wanneer een gebruiker [!UICONTROL Sharing] -opties opent voor een dashboard om de toegang voor een lay-outsjabloon te verwijderen, verschijnt er geen pictogram [!UICONTROL Delete] naast de sjabloon voor lay-out en kunnen de gebruikers de toegang niet verwijderen.

+++

+++**[!DNL Workfront Fusion]Onderhoudsupdate op 17 mei 2021**

**Dashboard van de Organisatie toont nu correct het aantal actieve scenario&#39;s**

_[!DNL Workfront Fusion]_

Op het dashboard van [!UICONTROL Organization] werd eerder een leeg veld weergegeven in plaats van het aantal scenario&#39;s dat wordt gebruikt.

**de opslag die van Gegevens nu doorbladert toont kolometiketten**

_[!DNL Workfront Fusion]_

Gegevensstructuren die gebruik maakten van kolomlabels, gaven de kolomnaam eerder weer in de weergave [!UICONTROL data store browsing] .  Nu wordt het kolomlabel weergegeven.  Als er geen label voor de kolom wordt geïdentificeerd, wordt de kolomnaam weergegeven.

**de initialisatiefout van het scenario beïnvloedt niet meer webhaakgegevens**

_[!DNL Workfront Fusion]_

Eerder, zou een WebHaak-in werking gesteld scenario (met inbegrip van die die een gebeurtenis in real time gebruiken om teweeg te brengen) dat een fout tijdens scenario initialisering ontmoette potentieel in het verliezen van toegang tot die WebHaakgegevens resulteren.  Nu, als een fout tijdens scenario initialisatie voorkomt (zoals het niet kunnen verifiëren van een verbinding), zullen de WebHaakgegevens in de WebHaakrij worden gehandhaafd en de uitvoering wordt automatisch opnieuw geprobeerd.  Na drie mislukte pogingen, wordt het scenario gedeactiveerd en de informatie zal nog in de rij blijven.

**Verslagen in webhaakrijen worden nu verwerkt in kleinere partijen**

_[!DNL Workfront Fusion]_

Eerder, als een gebruiker een inactief scenario activeerde dat een bijbehorende webharij van vele verslagen had, [!DNL Workfront Fusion] zou proberen om de volledige rij in één enkele uitvoering (alhoewel veelvoudige cycli) te verwerken.  Afhankelijk van de hoeveelheid verwerkte verslagen, kon dit soms de enige uitvoering veroorzaken om de maximumhoeveelheid uitvoeringstijd (40 minuten) te overschrijden.  Nu, wanneer u een inactief scenario activeert dat een bijbehorende webharij van verslagen heeft, zal Workfront Fusion tot het maximumaantal verslagen verwerken die in één enkele uitvoering worden geïdentificeerd (gewoonlijk 2 verslagen per uitvoering).

**de opslag van Gegevens toont nu correct &quot;0&quot;waarden**

_[!DNL Workfront Fusion]_

Eerder werden de waarden voor de gegevensopslagruimte 0 als leeg weergegeven. &lt;...>

+++

+++**Update van het Onderhoud op 13 Mei, 2021**

**drop-down kalender verschijnt achter de [!UICONTROL Unassigned Work] kopbal**

_[!UICONTROL Workload Balancer]_

Wanneer een gebruiker naar de [!UICONTROL Workload Balancer] in [!DNL Workfront Classic] navigeert, wordt de bovenkant van de datepicker verborgen achter de header [!UICONTROL Unassigned Work] , waardoor de gebruiker niet naar andere maanden kan navigeren.

**Onbekwaam om tekst op het gebied van het douanebericht te kleven**

_[!DNL Workfront Proof]_

Opmerking: dit probleem heeft momenteel alleen invloed op de webbrowser van [!DNL Google Chrome] .

Wanneer een gebruiker een nieuwe proefdruk maakt in [!DNL Workfront Proof] en probeert tekst uit een e-mail te plakken in het veld [!UICONTROL Message] in de sectie [!UICONTROL Email notification] , kan hij of zij de tekst niet plakken.

**Niet gesteunde gebieden tonen in de bouwer**

_Aangepaste Forms_

Wanneer een gebruiker een aangepast formulier maakt en probeert een berekend veld te maken met een dynamisch veld, bijvoorbeeld [!UICONTROL Number of Open Risks] , wordt het berekeningsvak rood gemarkeerd en kunt u de wijzigingen niet opslaan. Dynamische velden mogen niet worden weergegeven in de kiezer voor berekende velden.

**Voorproef voor taken in [!UICONTROL Work List] zal niet laden**

_Huis_

Wanneer een gebruiker in de nieuwe [!DNL Workfront] -ervaring wordt toegewezen aan een lay-outsjabloon die aangepaste velden op [!UICONTROL Home] bevat, reageert de pagina niet en worden taken niet geladen vanuit de [!UICONTROL Work List] als de gebruikers deze selecteren.

**Objecten in [!UICONTROL Work List] worden niet geladen in[!UICONTROL Home]**

_[!UICONTROL Home]_

Wanneer een gebruiker op een object in de [!UICONTROL Home Work List] klikt, wordt de koptekst van het object in het rechterdeelvenster weergegeven, maar worden de details van het object niet weergegeven. Uiteindelijk ziet de gebruiker het bericht &quot;[!UICONTROL Pages Unresponsive.]&quot;

**Rich text field issues in[!DNL Microsoft Outlook]**

_de Integraties van Workfront_

Wanneer een gebruiker een RTF-veld bijwerkt met de integratie met [!DNL Workfront for Outlook] , kunnen deze niet:

* Backspace
* Tekst kopiëren
* Tekst plakken
* Een aanvraag indienen wanneer alle velden zijn ingevuld

+++

+++**Update van het Onderhoud op 6 Mei, 2021**

**[!UICONTROL Currency]-veld werkt niet zoals verwacht**

_Lijsten_

Wanneer een gebruiker probeert om het gebied van de Kromme  ency in een lijst inline uit te geven, kunnen zij geen veranderingen wegens de volgende kwesties bewaren:

* Taak- en emissielijsten staan invoer van valutasymbolen niet toe
* Lijsten die geen input van muntafkortingen toestaan wanneer het gebruiken van een scène buiten het Engels
* Subtask- en Issue-lijsten die alleen de valutakorting van USD toestaan, ongeacht de vastgestelde projectvaluta

**Naam die niet bijwerkt om nieuwe proefnaam** aan te passen

_Documenten_

Wanneer een gebruiker een nieuwe versie van een proefdruk maakt en de proefdruknaam bijwerkt, behoudt het documentobject in [!DNL Workfront] de oorspronkelijke naam in plaats van de nieuwe proefdruknaam.

**[!UICONTROL Business Case]De knoppen werken niet wanneer aangepaste formulieren worden gekoppeld.**

_Projecten_

Wanneer een project in de nieuwe [!DNL Workfront] ervaring van een projectmalplaatje wordt gecreeerd en er een douaneformulier in bijlage is, kunnen de gebruikers een bedrijfscase voorleggen, verwerpen of goedkeuren niet.

**Gearchiveerde proeven die op lijsten en rapporten** tonen

_Proofs_

Wanneer een gebruiker zijn werklijst in [!UICONTROL Home] of [!UICONTROL My Work] weergeeft, worden proefdrukken die al zijn gearchiveerd, weergegeven in de lijst. Gearchiveerde proefdrukken worden ook weergegeven in rapporten en dashboards.

**Project dat van malplaatje wordt gecreeerd heeft onjuiste toegangsmontages**

_Projecten_

Wanneer een gebruiker een project van een malplaatje creeert, dragen de de toegangsmontages van het malplaatje niet over aan het nieuwe gecreeerde project.

**Objecten in [!UICONTROL Work List] worden niet geladen in[!UICONTROL Home]**

_[!UICONTROL Home]_

Wanneer een gebruiker op een object in de [!UICONTROL Home Work List] klikt, wordt de koptekst van het object in het rechterdeelvenster weergegeven, maar worden de details van het object niet weergegeven. Uiteindelijk ziet de gebruiker het bericht &quot;[!UICONTROL Pages Unresponsive.]&quot;

+++


## Updates in april 2021

+++**Update van het Onderhoud op 29 April, 2021**

**[!DNL SharePoint]de integratie verifieert gebruikend geloofsbrieven van een afzonderlijke integratie**

_de Integraties van Workfront_

Wanneer een gebruiker meer dan één [!DNL SharePoint] integratie heeft, probeert één [!DNL SharePoint] authentificatie om voor authentiek te verklaren gebruikend de geloofsbrieven van een andere [!DNL SharePoint] integratie.

**kan geen dossiers van [!DNL Adobe] producten** uploaden of uitvoeren

_de Integraties van Workfront_

Wanneer een gebruiker bestanden probeert te uploaden of te exporteren met [!DNL Workfront for Adobe Creative Cloud] integratie, wordt het foutbericht &quot; [!UICONTROL Cannot read property 'stages' of undefined]&quot; weergegeven en kunnen de bestanden niet worden geüpload of geëxporteerd.

**Bestanden zijn niet zichtbaar in[!DNL Internet Explorer]**

_Documenten_

Wanneer een gebruiker met een [!DNL Internet Explorer] browser naar het [!UICONTROL Documents] gebied van een voorwerp navigeert, is het [!UICONTROL Documents] scherm leeg en laadt niet de dossiers. Voor sommige gebruikers laadt het scherm sommige bestanden wel, maar het aantal weergegeven bestanden komt niet overeen met het aantal dat wordt weergegeven naast de sectie [!UICONTROL Documents] .

+++

+++**Update van het Onderhoud op 22 April, 2021**

**Taken die in de verkeerde orde** worden toegevoegd

_Malplaatjes_

Wanneer een gebruiker een taak aan een malplaatje toevoegt, ontvangt de taak niet het taakaantal zij verwachten en de taak wordt toegevoegd op de verkeerde plaats.

**De proef wordt nu gecombineerd in één enkele e-mail**

_Proofs_

[!DNL Workfront] verzendt nu één e-mail voor gecombineerde proefdrukken in plaats van een e-mail voor elk inbegrepen dossier te verzenden.
+++

+++**[!DNL Workfront Fusion]Onderhoudsupdate op 15 april 2021**

**&quot;[!UICONTROL Scenario rejected]&quot;fout wanneer het runnen van een scenario**

_[!DNL Workfront Fusion]_

Wanneer een gebruiker probeert om een scenario in werking te stellen, voert het scenario niet uit en de gebruiker ontvangt het bericht &quot;[!UICONTROL Scenario rejected.]&quot;

+++

+++**Update van het Onderhoud op 15 April, 2021**

**[!UICONTROL Workload Balancer]geeft onjuiste geplande uren weer**

_[!UICONTROL Workload Balancer]_

Wanneer een gebruiker de geplande uren van een taak in [!UICONTROL Workload Balancer] bekijkt, komt de waarde van de geplande uren niet overeen met de geplande uren die aan de taak zijn toegewezen.

**De bovenste navigatiebalk is niet zichtbaar in[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

Wanneer een gebruiker naar een andere [!DNL Workfront Proof] pagina dan de dashboardpagina navigeert, verdwijnt de bovenste navigatiebalk. De gebruiker heeft geen toegang tot de functionaliteit op de navigatiebalk, zoals de accountinstellingen of het bijbehorende profiel.

**Verbetering van de Vorm van de Douane**

_de vormen van de Douane_

Voor een betere ervaring bij het invullen van een aangepast formulier hebben we de manier verbeterd waarop de lange aangepaste veldlabels worden weergegeven. Wanneer er voldoende horizontale ruimte is om deze in hun geheel weer te geven, worden deze labels niet meer afgekapt.

+++

+++**Update van het Onderhoud op 8 April, 2021**

**kan geen proefdrukken in [!DNL Adobe Creative Cloud] integratie** tot stand brengen

_de Integraties van Workfront_

Wanneer een gebruiker rechtstreeks vanuit [!DNL Adobe Creative Cloud] een proefdruk probeert te maken, wordt deze niet gegenereerd.

+++

+++**Update van het Onderhoud op 1 April, 2021**

**Problemen bij weergave van overzichtsvenster in[!DNL Chrome]**

_[!UICONTROL Summary]_

Wanneer een gebruiker het deelvenster [!UICONTROL Summary] opent terwijl de [!DNL Chrome] -browser wordt gebruikt, gedraagt de interface van het deelvenster Samenvatting zich niet zoals verwacht. De gebruiker kan niet schuiven, de pictogrammen kunnen verdwijnen en de inhoud kan andere inhoud overlappen.

**[!UICONTROL Teams]in [!UICONTROL Setup] niet alle teams weergeven**

_[!UICONTROL Setup]_

Wanneer een beheerder naar het [!UICONTROL Teams] -gebied van [!UICONTROL Setup] gaat, kunnen alleen de teams worden weergegeven die ze hebben gemaakt. Teams die door andere beheerders zijn gemaakt, zijn niet zichtbaar.

**kan geen updates aan project in [!UICONTROL Pending Approval] status** toevoegen

_Projecten_

Als een gebruiker probeert om een update aan een project in [!UICONTROL Pending Approval] status toe te voegen, en zij niet de gebruiker zijn die wordt toegewezen om het project goed te keuren, wordt de update niet toegevoegd en zij zien de volgende verklaring:

Een project met een &quot;[!DNL Pending Approval]&quot;status kan niet worden uitgegeven. U kunt het project wijzigen door de status te wijzigen.

+++


## Updates in maart 2021

+++**Update van het Onderhoud op 26 Maart, 2021**

**Knopen in een bedrijfscasevertoning verkeerd**

_Projecten_

Wanneer een gebruiker een business case bekijkt en het venster in de modus Volledig scherm wordt weergegeven, staan de knoppen [!UICONTROL Save] en [!UICONTROL Cancel] midden in het scherm, met overlappende business case-elementen.

**kan het sorteren van een rapport niet veranderen**

_Rapporten_

Wanneer een gebruiker probeert de sortering van een rapport te wijzigen in de nieuwe [!DNL Workfront] -ervaring, verandert de sortering niet van de geselecteerde sortering op het moment dat het rapport werd gemaakt.

**het Delen gehandicapt op nieuwe proefdrukken**

_[!DNL Workfront Proof]_

Wanneer een gebruiker die [!UICONTROL Public Sharing] in de standaardinstellingen voor proefdrukken heeft ingeschakeld, een proefdruk maakt, wordt de proefdruk gemaakt met Delen uitgeschakeld. Andere gebruikers kunnen de knop [!UICONTROL Share] niet zien of de proefdruk delen.

**&quot;[!UICONTROL Proof failed to generate]&quot;fout wanneer het creëren van proef**

_[!DNL Workfront Proof]_

Wanneer een gebruiker een proef probeert tot stand te brengen, wordt de proef niet gecreeerd, en de gebruiker ziet het volgende foutenbericht:

&quot;[!UICONTROL Proof failed to generate -- internal error]&quot;

+++

+++**[!DNL Workfront Fusion]Onderhoudsupdate op 25 maart 2021**

**Verwijderd overtollige inzameling of verwijzingsgebied van het kaartpaneel**

_[!DNL Workfront Fusion]2.0_

Wanneer een gebruiker een term uit de [!DNL Workfront] API gebruikt om een verzameling of een verwijzingsveld te selecteren dat moet worden opgenomen in de uitvoer van een [!DNL Workfront] -module, geeft de uitvoer van die module dat veld weer met een dubbele punt (zoals [!UICONTROL owner:name] ) en ook in de kenmerken (de naam is een veld onder de eigenaar). Het veld met een dubbele punt bevat geen gegevens en bevat onjuiste gegevens als deze later in het scenario aan een module worden toegewezen.

+++

+++**[!DNL Workfront Fusion]Onderhoudsupdate op 18 maart 2021**

**het malplaatjemontages van het Project zijn nu van toepassing op projecten die door [!DNL Workfront Fusion] 2.0** worden gecreeerd

_[!DNL Workfront Fusion]2.0_

Wanneer u een project maakt op basis van een sjabloon met [!DNL Workfront Fusion] 2.0, worden de sjablooninstellingen toegepast op het nieuwe project. Dit gedrag is hetzelfde wanneer u een project maakt op basis van een sjabloon in de [!DNL Workfront] -toepassing.

+++

+++**Update van het Onderhoud op 18 Maart, 2021**

**het malplaatjemontages van het Project zijn nu van toepassing op projecten die door API** worden gecreeerd

_[!DNL Workfront]API_

Wanneer u een project maakt op basis van een sjabloon met de [!DNL Workfront] API, worden de sjablooninstellingen toegepast op het nieuwe project. Dit gedrag is hetzelfde wanneer u een project maakt op basis van een sjabloon in de [!DNL Workfront] -toepassing.

+++

+++**Update van het Onderhoud (Hete Fix) op 15 Maart, 2021**

**Gedeelde component die niet zoals verwacht functioneert**

_[!DNL Workfront Proof]_

Als zelfstandige [!DNL Workfront Proof] -accounts naar een gedeelde component worden verplaatst, kan de volgende functionaliteit optreden wanneer een gebruiker een nieuwe versie van een proefdruk of document toevoegt:

* De gebruiker kan de gebruiker [!UICONTROL Studio Proof] niet verwijderen.
* Het standaardbericht wordt niet weergegeven in de nieuwe versie.

**Openbare verbinding die niet op nieuwe versie van een proef** deelt

_Documenten_

Wanneer een gebruiker het delen van openbare koppelingen op een proefdruk inschakelt en vervolgens een nieuwe versie van de proefdruk uploadt, wordt het delen van openbare koppelingen niet automatisch ingeschakeld voor de nieuwe versie van de proefdruk.

**[!UICONTROL Approve], [!UICONTROL Changes] , [!UICONTROL Reject] knoppen ontbreken in proefdruk**

_[!DNL Workfront Proof]_

Wanneer een gebruiker een proef in de Kijker van het Bewijs bekijkt, ontbreken de [!UICONTROL Approve], [!UICONTROL Changes], en [!UICONTROL Reject] knopen van de bovenkant van het scherm.

**kan het sorteren van een rapport niet veranderen**

_Rapporten_

Wanneer een gebruiker probeert de sortering van een rapport te wijzigen in de nieuwe [!DNL Workfront] -ervaring, verandert de sortering niet van de geselecteerde sortering op het moment dat het rapport werd gemaakt.

**het bericht van de Douane op proef die niet aan nieuwe versie** draagt

_[!DNL Workfront Proof]_

Wanneer een gebruiker een aangepast bericht aan een proefdruk toevoegt en vervolgens een nieuwe versie van die proefdruk uploadt, wordt het aangepaste bericht niet weergegeven op de nieuwe proefdruk.

**lijst van de Gebruiker toont niet**

_Lijsten_

Wanneer een gebruiker probeert om een lijst van de Gebruiker te bekijken, en de mening omvat &quot;[!UICONTROL Status Icons]&quot;kolom, toont de lijst niet.

**&quot;[!UICONTROL Notify recipients about this proof]&quot; optie gehandicapt ongeacht werkschemamontages**

_[!DNL Workfront Proof]_

Wanneer een gebruiker tot een nieuwe proef leidt, en niet manueel de &quot;[!UICONTROL Notify recipients about this proof]&quot;optie aanzet, wordt de voorgenomen ontvanger niet op de hoogte gebracht. Dit geldt ook als de optie is ingeschakeld in workflowinstellingen.

**Onbekwaam om tijdkader** te veranderen

_[!UICONTROL Enhanced Analytics]_

Wanneer een gebruiker [!UICONTROL Enhanced analytics] bekijkt en op de kalender klikt om het datumbereik aan te passen, veranderen de datums niet.

**kan openbaar gedeeld document niet downloaden**

_Documenten_

Wanneer een gebruiker op een gedeelde koppeling klikt om een document te downloaden, wordt het document niet gedownload en ziet de gebruiker een fout van de browser die aangeeft dat de pagina niet bestaat.

+++

+++**Update van het Onderhoud op 11 Maart, 2021**

**Sectie van douanevorm die niet voor niet-admins uitvoert**

_Aangepaste Forms_

Als een douaneformulier in bijlage aan een voorwerp een sectieonderbreking heeft die om het even wat boven &quot; [!UICONTROL View]&quot;toegang nodig heeft om de inhoud van de sectie te bekijken, kan de inhoud van de sectie niet door iemand buiten Admin worden uitgevoerd.

**Gedownload document heeft onjuiste naam**

_[!DNL Workfront Proof]_

Wanneer gebruikers een document downloaden van [!UICONTROL Proof viewer], heeft het document de naam van een vorige versie van het document, niet de versie die werd gedownload.

+++

+++**Update van het Onderhoud op 4 Maart, 2021**

**Fout wanneer het toegang tot van het Malplaatje van de Lay-out**

_Malplaatjes van de Lay-out_

Wanneer een gebruiker die is ingeschreven voor de nieuwe [!DNL Workfront] -ervaring overschakelt naar de [!DNL Classic] -ervaring en probeert toegang te krijgen tot een [!DNL Classic] -lay-outsjabloon, wordt de fout &quot; [!UICONTROL That Page does not exist.]&quot; weergegeven

**Kan filters in[!UICONTROL Workload Balancer]** niet uitgeven

_[!UICONTROL Workload Balancer]_

Wanneer een gebruiker een filter in [!UICONTROL Workload Balancer] probeert te bewerken, wordt de filterconstructor niet geopend.

**&quot;[!UICONTROL See All Notifications]&quot;verbinding in e-mailbericht richt aan onjuiste pagina** opnieuw

_E-mailberichten_

Wanneer een gebruiker op de &quot;[!UICONTROL See All Notifications]&quot;verbinding in een e-mailbericht klikt, worden zij opnieuw gericht aan een pagina met het volgende bericht:

&quot;[!UICONTROL The User no longer exists. You may have mistyped the web address. Double check it and try entering the address again.]&quot;

**Gebruiker wordt niet geleid aan de proefdrukcommentaar zij in** worden geëtiketteerd

_E-mailberichten_

Wanneer een gebruiker in een proefdrukopmerking is gelabeld en in een e-mailmelding op de koppeling [!UICONTROL Go To Proof] klikt, wordt hij of zij naar de proefdrukopmerking verwezen, maar niet naar de specifieke opmerking. Als de gebruiker zich in [!DNL Workfront Classic] bevindt, worden ze naar de [!UICONTROL Document Details] -pagina geleid in plaats van naar de opmerking in de proefdruk.

**Gebruikers toegevoegd aan [!DNL Workfront] stadium die e-mailberichten ontvangen**

_[!DNL Workfront Proof]_

Wanneer een gebruiker die zich niet in de workflow bevindt, een proefdruk opent vanuit [!DNL Workfront] , maakt het systeem automatisch een werkgebied, voegt deze gebruiker aan de proefdruk toe en verzendt het e-mailbericht van [!UICONTROL New Proof] .

**het summiere paneel van het Document verdonkert, makend acties niet beschikbaar**

_Documenten_

Wanneer een gebruiker zich op een documentpagina bevindt en boven het documentoverzichtsvenster beweegt, wordt het deelvenster donkerder en worden mogelijk andere knoppen weergegeven. De gebruiker kan niet op de acties in het overzichtspaneel klikken.

**de veranderingen van de stroomprestaties van de Update**

_stroom van de Update_

We hebben het aantal gebruikersupdates dat op het tabblad [!UICONTROL Updates] wordt weergegeven, teruggebracht van 50 naar 25 tegelijk om de prestaties te verbeteren.

+++

+++**Update van het Onderhoud (Hete Fix) op 1 Maart, 2021**

**Nieuwe proefe-mails worden niet verzonden**

_[!DNL Workfront Proof]_

OPMERKING: dit probleem is opgelost in de nieuwe [!DNL Workfront] -ervaring op 26 februari 2021.
Deze is vastgelegd in de [!DNL Classic] -ervaring op 1 maart 2021.

Wanneer een gebruiker een nieuwe proefdruk maakt en de optie [!UICONTROL Notify recipients about this proof] inschakelt, wordt geen e-mail verzonden om de ontvanger op de hoogte te stellen.

+++


## Updates in februari 2021

+++**Update van het Onderhoud op 25 Februari, 2021**

**[!UICONTROL Scheduling]-gereedschap wordt in geen enkel gebied geladen.**

_Beheer van het Middel_

Wanneer een gebruiker met een apostrof in de gebruikersnaam toegang probeert te krijgen tot het gereedschap [!UICONTROL Scheduling] in [!DNL Workfront Classic] , is de pagina leeg en wordt het gereedschap nooit geladen.

**Naam verandert niet op nieuwe proefversies**

_Documenten_

Wanneer een gebruiker in de nieuwe [!DNL Workfront] ervaring een nieuwe versie van een document met een verschillende naam uploadt, past de naam niet aan de naam van de nieuwste versie aan.

**[!UICONTROL Document Share]fout bij het verwijderen van projecten**

_Projecten_

Wanneer een de beheerdergebruiker van het Systeem een toegang tot een project heeft dat is gekopieerd en zij proberen om het te schrappen of een document in het project te schrappen, kunnen zij niet het voorwerp schrappen en zij zien de fout &quot;[!UICONTROL Document Share with primary key value(s) not found.]&quot;

**het rapport van de Gebruiker past niet alle filters** toe

_Rapporten_

Wanneer een gebruiker in de nieuwe [!DNL Workfront] ervaring tot een rapport van de Gebruiker met een filterregel leidt die het [!UICONTROL Top Parent ID] gebied omvat, worden geen andere filterregels in het rapport toegepast.

**Berekende gebieden niet herberekenen na geeft uit**

_Aangepaste Forms_

Wanneer een gebruiker in de nieuwe [!DNL Workfront] een aangepast formulier bewerkt en opslaat dat berekende velden bevat, worden deze velden niet bijgewerkt.

**Documenten die schrappen wanneer de douanevorm wordt geschrapt**

_Aangepaste Forms_

Wanneer een gebruiker in de nieuwe [!DNL Workfront] ervaring een douaneformulier schrapt dat aan documenten in bijlage is, worden die documenten eveneens geschrapt.

+++

+++**Update van het Onderhoud op 18 Februari, 2021**

**Unnecessary checkbox verwijderd uit [!UICONTROL Requests] gebied**

_Verzoeken_

Het selectievakje links van de aanvraagnamen in de lijst Verzenden van het gebied [!UICONTROL Requests] is verwijderd. Dit selectievakje was niet verbonden met enige functionaliteit, dus we hebben het verwijderd om verwarring te voorkomen.

**Onbekwaam om tot documenten van verbindingen** toegang te hebben

_Documenten_

Wanneer een gebruiker in de nieuwe [!DNL Workfront] -ervaring op enkele documentkoppelingen klikt, heeft hij of zij geen toegang tot het document en wordt het foutbericht &quot; [!UICONTROL The Document no longer exists: You may have mistyped the web address. Double check it and try entering the address again.]&quot; weergegeven. Dezelfde fout treedt op met de koppeling [!UICONTROL View Details] in proefdrukken van e-mailberichten.

+++

+++**Update van het Onderhoud van de Fusie van Workfront op 16 Februari, 2021**

**[!DNL Workfront Fusion]2.0 geeft onjuiste tijdzones weer**

_Scenario&#39;s_

Deze update verhelpt een probleem waarbij in [!DNL Fusion] 2.0 de tijdzones van de gebruiker onjuist werden weergegeven. Gebruikers kunnen hun tijdzone nu zien onder invoervelden voor datums.

+++

+++**Update van het Onderhoud op 11 Februari, 2021**

**Proofs uploadt niet aan geselecteerde omslag**

_[!DNL Workfront Proof]_

Wanneer een gebruiker een map opent en een nieuwe proefdruk toevoegt, wordt de proefdruk geüpload naar het algemene gedeelte [!UICONTROL Documents] van het object in plaats van naar de map.

**Te veel vastgezette pagina&#39;s veroorzaakt Bovenste Navigatie om te verdwijnen**

_Navigatie_

Wanneer een gebruiker meer dan 60 vastgezette pagina&#39;s heeft, stopt de bovenste navigatie met het weergeven, waardoor de gebruiker geen toegang krijgt tot [!UICONTROL Search] , de [!UICONTROL Main Menu] , [!UICONTROL Notifications] en meer.

**de Gebruiker kan geen tekst in rijk tekstgebied** typen

_Lijsten_

Wanneer een gebruiker een RTF-veld inline probeert te bewerken, kan hij slechts één teken typen.

+++

+++**Update van het Onderhoud op 4 Februari, 2021**

**Geëxporteerd rapport toont [!DNL Workfront Classic] branding**

_Rapporten_

Wanneer een gebruiker in de nieuwe Workfront een rapport exporteert, komt het logo dat in het geëxporteerde rapport wordt weergegeven, overeen met de [!DNL Workfront Classic] -instellingen onder [!UICONTROL Setup] > [!UICONTROL System] > [!UICONTROL Branding] .

+++


## Updates in januari 2021

+++**Update van het Onderhoud op 28 Januari, 2021**

**Commentaren tonen niet &quot;[!UICONTROL on behalf of]&quot;**

_Updates_

Wanneer een [!DNL Workfront] beheerder zich als een andere gebruiker aanmeldt en op een opmerking in het [!UICONTROL Updates] -gebied van een object reageert, wordt de tekst &quot;[!UICONTROL on behalf of]&quot; niet vóór de gebruikersnaam weergegeven.

**Onbekwaam om een document** vast te maken

_Verzoeken_

Wanneer een gebruiker in de nieuwe [!DNL Workfront] -ervaring een document probeert toe te voegen aan een nieuwe aanvraag van een externe documentprovider, wordt de lijst van [!UICONTROL Documents] niet geladen. Hierdoor kan de gebruiker het document niet selecteren en de aanvraag voltooien.

**de breedte die van het Scherm aan het recht uitbreidt, veroorzakend navigatiekwesties**

_[!UICONTROL Home Calendar]_

Wanneer een gebruiker in de nieuwe [!DNL Workfront] ervaring [!UICONTROL Home Calendar] opent en zij punten hebben die op sommige weken worden verouderd, breidt het scherm zich aan het recht uit, die hen verhinderen de volledige week in één keer te bekijken. Als de gebruiker een item selecteert om het deelvenster [!UICONTROL Details] in deze toestand te openen en details voor een ander item wilt bekijken, moet hij naar links schuiven, waardoor het deelvenster [!UICONTROL Details] wordt gesloten.

**Enige-gebruiks verbeterd etiket van het goedkeuringsproces**

_Projecten_

Wanneer u een goedkeuringsproces voor één gebruik gebruikt voor een project in de nieuwe [!DNL Workfront] ervaring, wordt het nu weergegeven als &quot;[!UICONTROL Single-use approval process]&quot; in plaats van &quot;\&lt;Custom\>&quot; in het vak [!UICONTROL Edit Project] . Dit is nog niet beschikbaar voor taken en problemen.

**Verbeterde blik en voelt voor douanevormen**

_Projecten_

In de nieuwe [!DNL Workfront] -ervaring voor projecten hebben we de vormgeving van aangepaste formulieren verbeterd.

**API functionaliteit voor projectmunt past nu in-app functionaliteit aan**

_Projecten_

U kunt de valuta van een project niet wijzigen als er al financiële informatie over het project beschikbaar is. Met de meest recente onderhoudsupdate komt de API-functionaliteit voor dit geval nu overeen met de ervaring in de [!DNL Workfront] -interface.

**produceert automatisch niet de volgende week**

_Timesheets_

Wanneer een gebruiker naar het [!UICONTROL Timesheets] -gebied navigeert, wordt alleen de tijdpagina voor de huidige week weergegeven. Het tijdschema voor de komende weken wordt niet automatisch gegenereerd.

+++

+++**Update van het Onderhoud op 21 Januari, 2021**

**manueel sorterend door een kolom toont alle resultaten**

_Rapporten_

Wanneer een gebruiker in de nieuwe [!DNL Workfront] ervaring een bar in de grafiek van een rapport klikt, dan klikt een kolomkopbal om resultaten voor die groepering manueel te sorteren, tonen alle rapportresultaten, niet alleen resultaten voor de oorspronkelijk geselecteerde groepering.

**&quot;[!UICONTROL Allow sharing proof via URL or embed code]&quot;het plaatsen verandert**

_[!DNL Workfront Proof]_

Wanneer een gebruiker een proefdruk maakt en de instelling [!UICONTROL Allow sharing proof via URL or embed code] uitschakelt, wordt de instelling opnieuw gecontroleerd nadat de proefdruk is gegenereerd. Als de gebruiker de instelling heeft ingeschakeld, wordt deze uitgeschakeld nadat de proefdruk is gegenereerd.

**[!DNL Mac]gebruikers kunnen niet in tekstvelden in de proefdrukviewer plakken**

_[!DNL Workfront Proof]_

Wanneer een gebruiker tekst probeert te plakken in bepaalde velden in de proefdrukviewer, wordt de tekst niet weergegeven in het veld.

+++

+++**Update van het Onderhoud op 14 Januari, 2021**

**Onbekwaam om de montages van E-mailberichten bij te werken**

_Opstelling_

Wanneer een gebruiker instellingen voor e-mailmeldingen probeert bij te werken, heeft hij of zij geen toegang tot het gebied [!UICONTROL Email Notifications] en ziet hij het foutbericht &quot;[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

**[!UICONTROL Gantt chart]zorgt ervoor dat sommige velden worden afgekapt**

_Lijsten_

Wanneer een gebruiker de [!UICONTROL Gantt chart] in bepaalde lijstgebieden opent, beknotten bepaalde gebieden-zoals [!UICONTROL Description] - de tekst. De gebruiker moet dubbelklikken op het veld om de volledige tekst weer te geven.

**Kan geen bestanden verzenden vanuit[!UICONTROL Document Details]**

_Documenten_

Wanneer een gebruiker in de nieuwe [!DNL Workfront] ervaring probeert om een document van de [!UICONTROL Document Details] pagina te verzenden, zien zij het foutenbericht &quot; [!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

+++

+++**Update van het Onderhoud op 7 Januari, 2021**

**Afgevaardigde sluit de dialoog van Goedkeuringen**

_Huis_

Wanneer een gebruiker goedkeuringen probeert te delegeren in [!UICONTROL Home] en op een willekeurige datum klikt, wordt het dialoogvenster gesloten zonder de datum te selecteren of de gebruiker toe te staan de gebruikersdelegatie te voltooien.

**Uitgave met het bewegen van een document aan een taak**

_Documenten_

Wanneer een gebruiker een document of proef in de nieuwe [!DNL Workfront] ervaring probeert te bewegen, sommige taken buiten het project niet van het ouderproject zoals verwacht een lijst maken.

**Gedownloade PDF heeft onjuiste naam**

_[!DNL Workfront Proof]_

Wanneer een gebruiker via e-mail ([!UICONTROL Proof] > [!UICONTROL Print Comments] > [!UICONTROL PDF] ) een downloadkoppeling ontvangt en het bestand exporteert, krijgt het gedownloade bestand de naam met willekeurige nummers in plaats van met de proef-id.

+++
