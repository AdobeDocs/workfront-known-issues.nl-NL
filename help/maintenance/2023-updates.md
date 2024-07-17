---
title: Workfront Maintenance Updates in 2023
description: Onderhoudsupdates voor  [!DNL Adobe Workfront]
feature: Get Started with Workfront
exl-id: 87d54104-38b7-4950-ab21-6524a14f7f2a
source-git-commit: 1bc69d197e26e8c5543ad03164ebca1839789274
workflow-type: tm+mt
source-wordcount: '7242'
ht-degree: 0%

---

# [!DNL Workfront] Updates voor onderhoud in 2023

De volgende onderhoudsupdates zijn uitgevoerd in 2023.

>[!NOTE]
>
>Deze updates bevatten ook andere kleine of minder duidelijke foutoplossingen. [!DNL Workfront] Ondersteuning geeft een melding wanneer een probleem dat u hebt verzonden, is opgelost.

Voor onderhoudsupdates voorafgaand aan 2023, zie [ Vorige Updates van het Onderhoud ](#previous-maintenance-updates)

## Updates in december 2023

+++**Update van het Onderhoud op 21 December, 2023**

**Kwesties wanneer het bekijken van subtask status**

_Boards_

De volgende problemen zijn gemeld met betrekking tot het weergeven van de status van een subtaak op een kaart in de raden van bestuur:

* De status wordt weergegeven als &quot;Status selecteren&quot;, zelfs als de taak al een status heeft. Deze status is zichtbaar wanneer u de taak rechtstreeks bekijkt.
* Als de gebruiker een status probeert te selecteren, gaat het scherm leeg en moet het worden vernieuwd.

**kan geen document aan een kaart** vastmaken

_Boards_

Wanneer een gebruiker een document probeert te koppelen aan een aangesloten kaart, kan de gebruiker het document selecteren dat u wilt bijvoegen, maar het document wordt niet weergegeven in het documentgebied van de kaart en het document is niet gekoppeld aan het object waarmee de kaart is verbonden.

Dit is gemeld bij kaarten die verband houden met emissies.

**kan malplaatje van [!UICONTROL Favorites] lijst** niet selecteren

_Malplaatjes_

Wanneer een gebruiker een sjabloon probeert te selecteren in de lijst [!UICONTROL Favorites] , verdwijnt de lijst wanneer de gebruiker de muis naar de lijst verplaatst en kan de gebruiker geen sjabloon selecteren.

**Sommige updates ontbreken in de nieuwe het becommentariëren ervaring**

_Updates_

Wanneer een gebruiker updates in de nieuwe opmerkingervaring bekijkt, worden sommige commentaren die zouden moeten worden getoond niet getoond. Als de gebruiker overschakelt naar de oudere opmerkingervaring, worden alle opmerkingen weergegeven.

+++

+++**[!DNL Adobe Workfront Fusion]Onderhoudsupdate op 21 december 2023**

Het openen van het moduleveld duurt te lang

_[!DNL Workfront Fusion]_

<!--no article-->

Wanneer een gebruiker een module vormt en de module gegevens van de verbonden rekening (zoals voor het selecteren van een verslag) vereist, kan de module niet de gegevens terugwinnen, en het verzoek om gegevenstijden uit.

+++

+++**Update van het Onderhoud op 14 December, 2023**

**Proofs die goedkeuring in afwachting zijn verschijnen niet in rapporten**

_Proofs_

Wanneer een gebruiker een rapport bekijkt voor proefversies die in behandeling zijn, verschijnen sommige goedkeuringen die in behandeling zijn niet in het rapport.
+++

+++**Update van het Onderhoud op 7 December, 2023**

**Goedkeuring geplakt op [!UICONTROL Awaiting my approval] widget**

_Huis_

Wanneer een nieuwe versie van een document wordt geüpload en de vorige versie een goedkeuring heeft die niet volledig is, blijft de oude versie van het document vastzitten op de [!UICONTROL Awaiting my approval] -widget van de fiatteur. De goedkeuring kan niet worden goedgekeurd omdat er een nieuwe versie is en deze kan niet uit de widget worden verwijderd.

**Kwesties wanneer het toevoegen van het werkpunten in raad mening van taken of kwesties**

_Taken/Kwesties_

Wanneer een gebruiker de mening van de Raad van de Taken of het gebied van Kwesties in een project bekijkt en probeert om een taak of kwestie toe te voegen, kan het volgende voorkomen:

* Het pop-upvenster wisselt heen en weer tussen twee verschillende vensterstijlen
* De gebruiker kan het pop-upvenster niet sluiten

Dit is gemeld wanneer een gebruiker een gebied selecteert in de linkernavigatie van het pop-upvenster voordat hij gegevens invoert.

+++

## Updates in november 2023

+++**Update van het Onderhoud op 30 November, 2023**

**de Taken verschijnen niet in [!UICONTROL My Work] widget**

_[!UICONTROL Home]_

Wanneer een gebruiker de [!UICONTROL My Work] -widget in [!UICONTROL Home] bekijkt, worden sommige van de taken waaraan hij of zij heeft toegewezen, niet weergegeven in de widget. Een gebruiker kan bijvoorbeeld naar een project gaan en zien dat aan hem of haar taken in het project zijn toegewezen, maar deze taken worden niet weergegeven op de [!UICONTROL My Work] -widget van de gebruiker.

**Login pagina richt zich aan logout landende pagina** opnieuw

_Login_

Wanneer een gebruiker zich aanmeldt bij [!DNL Workfront] in plaats van de aanmeldingspagina, wordt de gebruiker verwezen naar de pagina waarop hij of zij zich zou afmelden.

**500 fout wanneer het uitvoeren van een rapport**

_Rapporten_

Wanneer een gebruiker een rapport probeert te exporteren, mislukt het exporteren met de volgende fout:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Dit is gemeld in rapporten die een `valueexpression` gebruiken om naar de `lastNote` notitietekst te verwijzen.

+++

+++**Update van het Onderhoud op 16 November, 2023**

**de begrote uren uren in gebruiksrapport passen in de begroting opgenomen uren niet aan die door API** worden gemeld

_Rapporten_

Wanneer een gebruiker een API vraag aan het voorwerp RPBGHR voor een bepaald project maakt, en de resultaten van die vraag aan het gebruiksrapport voor dat project vergelijkt, passen de resultaten niet aan.

**Onjuiste douanevaluta die op Nieuwe verzoekpagina wordt getoond**

_Verzoeken_

Wanneer een gebruiker een verzoek indient en een selectie maakt die veranderingen vertoningslogica op het verzoekformulier tonen, keert de getoonde munt terug naar de standaardmunt eerder dan de douanevaluta die op het project wordt geplaatst dat de verzoekrij vertegenwoordigt.

Wanneer de gebruiker zijn verzoek indient, wordt de valuta weergegeven als de juiste aangepaste valuta voor het project dat de aanvraagwachtrij vertegenwoordigt

**Extra regels in commentaar die door API of[!DNL Workfront Fusion]** wordt gemaakt

_Updates_

Wanneer een gebruiker een opmerking verzendt via de API of via [!DNL Workfront Fusion] , worden extra regels weergegeven voor de opmerking die wordt weergegeven in het gedeelte Updates. Soms zijn er zoveel regels dat de gebruiker omlaag moet schuiven om de inhoud van de opmerking te zien.

Dit is gemeld in de nieuwe ervaringen met opmerkingen.

+++

+++**Update van het Onderhoud op 9 November, 2023**

**Mijn widget van het Werk mist voorwerpen wanneer niet bij bovenkant van pagina**

_Huis_

Als de widget Mijn werk zich boven aan de nieuwe startpagina bevindt, worden alle verwachte objecten opgehaald. Als deze widget zich echter onder andere widgets op de pagina bevindt, worden slechts tien objecten opgehaald.

**kan proef** niet produceren

_Proofs_

Wanneer een gebruiker een proef probeert te produceren, wordt de proef niet gecreeerd, en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Error generating proof]&quot;

Dit komt voor wanneer het de toegangsniveau dat van de gebruiker [!UICONTROL  View Contact Info] plaatst aan Gehandicapten wordt geplaatst.

**Gebieden ontruimen wanneer een document aan een verzoek** wordt toegevoegd

_Verzoeken_

Wanneer een gebruiker een aanvraag maakt, velden in een formulier invult en vervolgens een document toevoegt of verwijdert, worden sommige velden in het formulier gewist en moeten de velden door de gebruiker opnieuw worden ingevuld voordat de aanvraag wordt verzonden.

**Persoonlijke taak verschijnt op timesheet**

_Timesheets_

Wanneer een gebruiker een taak maakt op de [!UICONTROL Todo] -widget van de nieuwe [!UICONTROL Home] -ervaring, wordt die taak weergegeven op het tijdspagina van de gebruiker. Dit komt zelfs voor als de taak geen het programma geopende uren heeft, en het persoonlijke project niet wordt vastgezet.

+++

+++**Update van het Onderhoud (Hete Fix) op 3 November, 2023**

**de taken van het Kind verschijnen uit orde wanneer bewogen onder oudertaak**

_Malplaatjes_

Wanneer een gebruiker taken op een malplaatje creeert, en dan die taken onder een oudertaak beweegt, verschijnen de aantallen die aan de kindtaken worden toegewezen niet in de verwachte orde. Daarom wanneer de pagina wordt verfrist, worden de kindtaken gesorteerd door de onverwachte taakaantallen, en de kindtaken zijn daarom uit orde.

+++

+++**Update van het Onderhoud op 2 November, 2023**

**Privé updatevertoning in de gebieden van de waardeuitdrukking**

_Rapporten_

Wanneer een rapportgebied een waardeuitdrukking omvat die verwijzingen een privé update, gebruikers die niet inbegrepen in de privé update zijn kan het in het rapport zien.

**de vertoningen van de Gebruiker als oververdeeld wegens onnauwkeurige capaciteit**

_de Balancer van de Werkbelasting_

Een gebruiker kan in de Workload Balancer tonen dat deze is oververdeeld. Als een gebruiker de overtoewijzing aanwijst, ziet hij of zij dat de capaciteit van de gebruiker op 0 is ingesteld.

Als de gebruiker het datumbereik wijzigt, is de toewijzing correct. Als de gebruiker de pagina echter vernieuwt, is de capaciteit mogelijk weer onjuist.

+++

## Updates in oktober 2023

+++**Update van het Onderhoud op 26 oktober, 2023**

**Onderzoek niet werkend**

_Boards_

Wanneer een gebruiker aan onderzoeksraad probeert, keert het onderzoek niet alle kaarten terug die aan de onderzoekscriteria voldoen.

**kan interactieve proef in Webkijker niet bekijken**

_Proofs_

Wanneer een gebruiker een proefdruk probeert weer te geven in de webproefdrukviewer, wordt de proefdruk niet weergegeven en ziet de gebruiker de volgende fout:

&quot;[!UICONTROL Missing Key-Pair-Id query parameter or cookie value]&quot;

**kan geen nieuwe versie van een proef** creëren

_Proofs_

Wanneer een gebruiker een nieuwe versie van een proefdruk probeert te maken, wordt de nieuwe versie niet gemaakt en ziet de gebruiker het volgende foutbericht:

&quot;[!UICONTROL Error generating proof]&quot;

**Gebruiker wordt gedupliceerd wanneer het delen van een verzoek**

_Verzoeken_

Wanneer het delen van een verzoek, als het toegangsniveau van een gebruiker die het verzoek wordt gedeeld met wordt gewijzigd, wordt de gebruiker net boven die gebruiker in de lijst die gebruiker.

Bijvoorbeeld, als het verzoek met Gebruiker A en Gebruiker B wordt gedeeld, en de toegang van Gebruiker B wordt gewijzigd, verandert Gebruiker A in Gebruiker B, en er zijn nu twee Bs van de Gebruiker in de lijst. Bovendien is alleen de toegang van de bovenste gebruiker B gewijzigd.

**&quot;[!UICONTROL Whoops]&quot;fout in taakkopbal**

_Taken_

Wanneer een gebruiker een taak bekijkt, bevat de taakkoptekst geen informatie. In plaats daarvan ziet de gebruiker het volgende foutbericht:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;

+++

+++**Update van het Onderhoud op 19 Oktober, 2023**

Gebruikers worden niet op de hoogte gesteld van reacties op een commentaarthread

_Meldingen_

Wanneer een gebruiker op een opmerking reageert, ontvangen andere gebruikers die berichten voor het antwoord moeten ontvangen, deze niet. Sommige gebruikers ontvangen de melding, andere niet.

**Extra, leeg commentaar wanneer het maken van een commentaar op een proef**

_Proofs_

Wanneer een gebruiker een opmerking maakt over een proefdruk, geeft de proefdruk ook een andere opmerking, die leeg is.

Dit is gemeld op videoproefdrukken.

**[!UICONTROL Proof activity]-tabblad wordt niet geopend**

_Proofs_

Wanneer een gebruiker een proef bekijkt en het [!UICONTROL Proof activity] lusje klikt, keert het lusje de gebruiker aan het [!UICONTROL Proof details] lusje terug.

**[!UICONTROL Planned Hours]worden opnieuw toegewezen wanneer een extra gebruiker aan een taak wordt toegewezen**

_Taken_

Wanneer een gebruiker wordt toegewezen aan een taak waarvoor [!UICONTROL Planned Hours] is toegewezen aan andere toewijzing aan de taak, worden de taaktaken [!UICONTROL Planned Hours] gelijkmatig verdeeld over alle taaktoewijzingen.

**&quot;[!UICONTROL Deleted]&quot;vertoningen als naam van gebruiker in systeemupdates wanneer de kwestie in taak** wordt omgezet

_Updates_

Wanneer een gebruiker die als een andere gebruiker het programma wordt geopend een kwestie in een taak omzet, en de kwestie wordt toegewezen aan een team, tonen de systeemupdates &quot;[!UICONTROL Deleted]&quot;als gebruiker die om dat het teamwerk aan de taak verzocht.

+++

+++**Update van het Onderhoud op 12 Oktober, 2023**

**Werkstromen die voor rekeningen worden verwijderd die hen niet gebruiken**

_Boards_

Voor accounts die nog nooit een werkstroom hebben gemaakt in de toepassing Boards, is het gebied Workstreams verwijderd van het dashboard Boards. Accounts die wel werkstromen gebruiken, hebben nog steeds toegang tot deze accounts.

**Berekende gebieden behouden geen waarde wanneer de kwestie in taak** wordt omgezet

_de vormen van de Douane_

Berekende velden die zelf naar verwijzen, behouden hun waarden niet wanneer een uitgave wordt omgezet in een taak.

Wanneer u de uitgave omzet in een taak, wordt de gewenste waarde correct weergegeven in het bewerkingsvenster. Nadat de conversie is voltooid, wordt in het berekende veld echter de waarde &quot;N.v.t.&quot; weergegeven.

**Fout bij het wijzigen van filters in[!UICONTROL Home]**

_Huis_

Wanneer een gebruiker de filters op [!UICONTROL Home] wijzigt, wordt het [!UICONTROL Home] -gebied niet geladen en ziet de gebruiker de volgende fout:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

+++

+++**Update van het Onderhoud op 5 Oktober, 2023**

**de ladingen van de Raad langzaam**

_Boards_

Wanneer een gebruiker een board laadt, wordt het board uiterst langzaam geladen. Dit kan gebeuren, ook al heeft het bord een klein aantal kaarten.

Gearchiveerde kaarten hadden, zelfs als ze niet worden weergegeven, invloed op de laadtijd van het bord.

**kan geen kaarten tussen kolommen bewegen**

_Boards_

Wanneer een gebruiker een kaart op een bord probeert te verplaatsen, wordt de kaart niet verplaatst. Dit gebeurt in de volgende omstandigheden:

* Slepen en slepen
* Optie Verplaatsen op kaart
* De kaart bewerken

**kan geen kaarten uit de inlaatkolom bewegen**

_Boards_

De gebruiker kan een kaart uit de inlaatkolom naar een andere kolom op het bord slepen, maar de volgende kaarten kunnen niet uit de inlaatkolom worden verplaatst.

**Groep door bordprestaties te beïnvloeden**

_Boards_

Wanneer de gebruiker de kaarten probeert te groeperen door middel van toewijzingen of tags, worden de prestaties van het toetsenbord zeer traag.

**de Automatische e-mails van de Herinnering worden niet verzonden**

_Meldingen_

Automatische e-mailherinneringen worden niet verzonden. Dit begon op 14 september 2023.

+++

## Updates in september 2023

+++**Update van het Onderhoud op 28 september, 2023**

**kan douanegebied** niet schrappen

_de vormen van de Douane_

Wanneer een gebruiker probeert om een douanegebied te schrappen, kunnen zij niet het schrappen, en zij zien het bericht &quot;[!UICONTROL Database error due to constraint violation]&quot;.

**Commentaren die in nieuwe het becommentariëren ervaring worden gemaakt zijn niet zichtbaar in erfeniservaring**

_Updates_

Wanneer een gebruiker een opmerking maakt in de nieuwe opmerkingervaring en die opmerking wordt weergegeven in het gebied Opmerkingen van de nieuwe ervaring, wordt dezelfde opmerking mogelijk niet weergegeven in de oudere opmerkingervaring. Dit kan ertoe leiden dat gebruikers die de oudere ervaring gebruiken opmerkingen vergeten.

**de pagina van Objecten mist elementen**

_Workfront_

Wanneer een gebruiker naar een aangepaste sectie op een object in [!DNL Workfront] navigeert, ontbreken mogelijk enkele elementen op de pagina die wordt geladen. Deze elementen kunnen het volgende omvatten:

* Het linkernavigatievenster
* De naam van het object waartoe de aangepaste sectie behoort
* Velden en informatie in de koptekst

+++

+++**Update van het Onderhoud op 21 September, 2023**

**kan geen gebruiker op een raad op een werkstroom toewijzen**

_Boards_

Wanneer een gebruiker probeert een andere gebruiker aan een taak van een raad toe te wijzen die deel van een werkstroom uitmaakt, en de naam van de gebruiker begint te typen, verschijnt de gebruiker niet op de drop-down lijst van beschikbare gebruikers. Dit gebeurt zelfs wanneer de gebruiker actief is en een lid van zowel de raad als de werkstroom.

Het kan ook voorkomen dat gedeactiveerde gebruikers in de vervolgkeuzelijst worden weergegeven.

**kan checklist punt** niet schrappen

_Boards_

Wanneer een gebruiker een controlelijstitem probeert te verwijderen van een kaart op een bord, reageert de knop [!UICONTROL Delete] niet en wordt het item niet verwijderd.

**de Formulieren van de Douane laden langzaam**

_de vormen van de Douane_

Wanneer een gebruiker een aangepast formulier probeert te laden, wordt het aangepaste formulier langzaam geladen.

**kan document aan een verschillende omslag niet bewegen**

_Documenten_

Wanneer een gebruiker een document naar een objectmap verplaatst, kan hij of zij het object niet naar een andere map verplaatsen.

**fout van XML wanneer het downloaden**

_Documenten_

Wanneer een gebruiker een document probeert te downloaden, wordt het document niet gedownload en ziet de gebruiker een pagina met het volgende bericht gevolgd door XML-tekst.

&quot;[!UICONTROL The XML file does not appear to have any style information associated with it. The document tree is below.]&quot;

**kan geen documenten van de milieu&#39;s downloaden van de Voorproef/van Sandbox**

_Documenten_

Wanneer een gebruiker een document probeert te downloaden vanuit een andere omgeving dan productie, wordt het document niet gedownload en ziet de gebruiker de volgende fout:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;

**de proeven verschijnen verlaten of bebouwd**

_Proofs_

De volgende problemen zijn gemeld bij het maken van een proef via een URL.

* De proefdruk lijkt te zijn verzadigd of te zijn gewassen.
* De proefdruk wordt bijgesneden.

Dit kan ertoe leiden dat de bewijsvoering moeilijk is, omdat de bewijsvoering niet correct wordt weergegeven.

**Proefdrukken nemen buitensporige tijd om te produceren**

_Proofs_

Wanneer een gebruiker een bewijs probeert te produceren, vergt het bewijs een buitensporige hoeveelheid tijd om te produceren. De proefproductie kan enkele dagen duren.

+++

+++**Update van het Onderhoud op 14 september, 2023**

**&quot;[!UICONTROL No factory]&quot;fout wanneer het toevoegen van een document**

_Documenten_

Wanneer een gebruiker een document uit een externe bron probeert toe te voegen, heeft [!DNL Workfront] geen toegang tot de bron en ziet de gebruiker de volgende fout:

&quot;[!UICONTROL The following error occurred: No factory found for authentication type null]&quot;

**De fout van &quot;Wiops&quot;op matrixrapporten**

_Rapporten_

Wanneer een gebruiker probeert om een matrixrapport te bekijken, laadt het rapport niet, en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;

Dit komt voor wanneer het groeperen van een rapport door datumwaaiers.

+++

+++**Update van het Onderhoud op 11 September, 2023**

**Persoonlijke taken tonen niet in timesheets**

_Timesheets_

De persoonlijke taken tonen niet meer op timesheet door gebrek. De persoonlijke taken tonen op timesheet wanneer zij worden vastgezet of uren het programma worden geopend. Voorafgaand aan deze verandering, persoonlijke taken die op timesheets door gebrek worden getoond.

+++

+++**Update van het Onderhoud op 7 September, 2023**

**Project is leeg wanneer geladen van nieuwe [!UICONTROL Home] ervaring**

_Projecten_

Wanneer een gebruiker op een project van hun [!UICONTROL Home] pagina in de nieuwe ervaring van het Huis klikt, ontbreekt de pagina van het project om te laden.

Dit gebeurt wanneer de gebruiker zich heeft aangemeld als een andere gebruiker, zich vervolgens heeft afgemeld als de andere gebruiker en is teruggekeerd naar zijn eigen [!UICONTROL Home] pagina.

+++

## Updates in augustus 2023

+++**Update van het Onderhoud op 31 augustus, 2023**

**de Filters zijn niet van toepassing op widgets in de nieuwe [!UICONTROL Home] ervaring**

_[!UICONTROL Home]_

Wanneer een gebruiker een filter toepast op een widget in de nieuwe [!UICONTROL Home] -ervaring, geeft de widget items weer die door het filter moeten worden uitgesloten.

Dit is gemeld in de aangepaste sandbox-omgeving. Dezelfde widgets filteren in de voorvertoning- en productieomgevingen als u had verwacht.

**Kwesties wanneer het laden van de rapporten van de Matrijs**

_Rapporten_

Wanneer een gebruiker probeert om een rapport van de Matrijs als grafiek te laden, één van het volgende kan voorkomen:

* Bepaalde informatie in het rapport wordt niet geladen
* Het rapport geeft de fout &quot;[!UICONTROL Unable to load content from the server]&quot;

**de Planner laadt niet wanneer de filter wordt toegepast**

_[!UICONTROL Resource Planner]_

Wanneer een gebruiker probeert de [!UICONTROL Resource Planner] te laden, wordt de planner niet geladen en krijgt de gebruiker de volgende foutmelding te zien:

&quot;[!UICONTROL The following error occurred: Something went wrong while connecting to WorkPerDay service]&quot;

+++

+++**update van het Onderhoud op 24 augustus, 2023**

**kan geen tekst in lijsten of kogelpunten selecteren**

_Proofs_

Wanneer een gebruiker een proef in de het proefdrukken kijker bekijkt en probeert om tekst te selecteren die in een lijst of een kogelpunt is, is het hulpmiddel van de tekstselectie inefficiënt, en de tekst kan niet worden geselecteerd.

**Creërend een nieuwe proefdrukversie schrapt alle versies van proef**

_Proofs_

Wanneer een gebruiker een proefdruk maakt op basis van een document, wordt de proefdruk gemaakt. Als een gebruiker echter een andere versie van de proefdruk maakt, worden zowel de oude als de nieuwe versie verwijderd. Het oorspronkelijke document bevat een optie [!UICONTROL Create Proof] en de proefversies staan in het [!UICONTROL Trash] -gebied van het [!UICONTROL Proofing] -gebied in [!DNL Workfront] .

+++

+++**update van het Onderhoud op 17 augustus, 2023**

**kan niet aan project met URL navigeren die[!UICONTROL Reference ID]** gebruikt

_Projecten_

Wanneer een gebruiker naar een project probeert te navigeren met een URL die een [!UICONTROL Reference ID] -nummer bevat, worden deze doorgestuurd naar een pagina met een foutbericht. Navigeren naar een taak met een URL met een [!UICONTROL Reference ID] werkt zoals u had verwacht.

**&quot;[!UICONTROL Disable proof email notifications]&quot;het plaatsen toont onjuist**

_Proofs_

Wanneer een gebruiker proefdrukinstellingen weergeeft in [!DNL Workfront] , geeft het selectievakje [!UICONTROL Disable proof email notifications] niet de juiste huidige instelling op de juiste wijze weer. Als dit selectievakje is ingeschakeld, worden e-mailmeldingen met een proefdruk uitgeschakeld. De meldingen worden nu daadwerkelijk ingeschakeld. Het tegendeel is ook waar.

**kan proefdrukmarkeringen niet aanpassen**

_Proofs_

Wanneer een gebruiker een opmerking maakt in de drukproefviewer en een markering maakt op de proefdruk en vervolgens wegklikt, kan de gebruiker de markering niet meer aanpassen.

+++

+++**update van het Onderhoud op 10 augustus, 2023**

**kan [!UICONTROL To-do] punt in nieuwe [!UICONTROL Home] ervaring niet schrappen**

_Huis_

Wanneer een gebruiker in de nieuwe [!UICONTROL Home] -ervaring een item probeert te verwijderen uit de [!UICONTROL To-do] -widget, wordt het item niet verwijderd en wordt de volgende fout weergegeven:

&quot;[!UICONTROL There was a problem removing your to-do, please try again soon.]&quot;

Dit kan gebeuren wanneer er uren zijn geregistreerd aan het [!UICONTROL To-do] punt.

**Vastgezet project toont geen informatie in sommige kolommen**

_Projecten_

Wanneer een gebruiker naar een vastgezet project navigeert gebruikend het punt, kunnen de objecten lijsten (zoals de taaklijst) lege kolommen tonen. Een kolom [!UICONTROL Assignments] kan bijvoorbeeld geen toewijzingen weergeven, ook al zijn er toewijzingen gemaakt.

**module van de Slaap veroorzakend scenario&#39;s om** te hangen

_[!DNL Workfront Fusion]_

De module [!UICONTROL Tools] > [!UICONTROL Sleep] in een scenario kan ertoe leiden dat de uitvoering van een scenario vastloopt. Deze uitvoeringen geven de status weer van Wordt uitgevoerd in de [!UICONTROL Scenario History] en zijn niet voltooid.

+++

+++**Update van het Onderhoud op 3 Augustus, 2023**

**Probleem plaatsend punten in inlaatkolom**

_Boards_

De inlaatkolom op een board werd eerder gesorteerd op de prioriteit die op taken en kwesties werd bepaald, die het moeilijk maakten om van specifieke punten de plaats te bepalen.

De standaardvolgorde is nu als volgt:

Taken:

* Primaire bestelling: Projectnaam
* Secundaire volgorde: structuur van werkverdeling

Problemen

* Primaire bestelling: Projectnaam
* Secundaire volgorde: Referentienummer

**het Project lost correct geen kwestie** op

_Projecten/Kwesties_

Wanneer een gebruiker de status wijzigt van een project dat het oplossende object voor een uitgave is, wordt de status van de uitgave gewijzigd in een status die niet overeenkomt met dezelfde sleutel als de status van het project.

**De fout van &quot;Wiops&quot;op matrixrapporten**

_Rapporten_

Wanneer een gebruiker probeert om een matrixrapport te bekijken, laadt het rapport niet, en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;

Dit is gemeld voor gebruikers in EMEA.

+++

## Updates in juli 2023

+++**Update van het Onderhoud op 27 Juli, 2023**

**Markeringen en controlelijstitems die niet correct in de mening van het projectbord werken**

_Boards_

Labels en controlelijstitems zijn verwijderd uit de weergave aan boord van projecten, omdat ze geen deel uitmaken van de Workfront-taken en niet kunnen worden gedeeld tussen gebruikers.

**&quot;[!UICONTROL Enable system-wide]&quot; en &quot;[!UICONTROL View system-wide]&quot;vertegenwoordigen verschillende functionaliteit**

_Filters_

Als een gebruiker een filter deelt en &quot;[!UICONTROL View system-wide]&quot;optie toelaat, wordt de filter gedeeld met elke gebruiker in het systeem. Nochtans, als een beheerder dan dit filter in [!UICONTROL Setup] bekijkt, zien zij dat dit filter &quot;[!UICONTROL false]&quot;in de &quot;[!UICONTROL Visible System-Wide]&quot;kolom toont. Als u van dit filter een standaardfilter wilt maken, moet de beheerder de optie &quot;[!UICONTROL Enable system-wide]&quot; in [!UICONTROL Setup] inschakelen. Dit kan enige verwarring veroorzaken vanwege de gelijkenis van de formulering.

+++

+++**Update van het Onderhoud op 20 Juli, 2023**

Deze update bevat alleen kleine of minder belangrijke opgeloste problemen. [!DNL Workfront] Ondersteuning geeft een melding wanneer een probleem dat u hebt verzonden, is opgelost.

+++

+++**Update van het Onderhoud op 13 Juli, 2023**

**de Chronologie herberekent niet**

_Projecten/Taken/Kwesties_

Wanneer een even gebeurtenis optreedt die een tijdlijnberekening zou moeten activeren, wordt de tijdlijn niet opnieuw berekend. Dit beïnvloedt herberekeningen die op veranderingen voorkomen, en geplande herberekeningen. Dit kan van invloed zijn op de nauwkeurigheid van de werklastverdeling.

**Vergrendelde proefdrukgoedkeuringen tonen nog in de Lijst van het Werk**

_Proofs_

Goedkeuringen met bewijzen die hun deadline hebben overschreden en zijn vergrendeld, worden nog steeds weergegeven op de thuiswerklijst van de fiatteur in plaats van de lijst af te sluiten wanneer de deadline is verstreken.

**het rapport van het Gebruik laadt niet**

_Rapporten_

Wanneer een klant probeert om een gebruiksrapport te bekijken, ziet de gebruiker een het draaien ladingsindicator, maar het rapport laadt niet. Het rapport heeft een fout van 500 geretourneerd, maar de gebruiker ziet geen aanwijzing dat het rapport is mislukt.

**geef de pagina van de Gebruiker uit is leeg**

<!--no article-->

_Gebruikers_

Wanneer een gebruiker probeert een andere gebruiker te bewerken, is de pagina Gebruiker bewerken leeg en kan de gebruiker de andere gebruiker niet bewerken.

+++

## Updates in juni 2023

+++**Update van het Onderhoud op 29 juni, 2023**

Deze update bevat alleen kleine of minder belangrijke opgeloste problemen. [!DNL Workfront] Ondersteuning geeft een melding wanneer een probleem dat u hebt verzonden, is opgelost.

+++

+++**Update van het Onderhoud op 22 Juni, 2023**

**&quot;[!UICONTROL Whoops]&quot;fout wanneer het bekijken matrixrapport**

_Rapporten_

Wanneer een gebruiker een matrixrapport weergeeft, wordt de volgende fout weergegeven:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;

Dit is gemeld wanneer het rapport door datum wordt gesorteerd en &quot;[!UICONTROL Show weeks with no results]&quot;optie wordt toegelaten.

**vertoning van Data verkeerd in matrixrapporten**

_Rapporten_

Wanneer een grafiek of matrixrapport op datum wordt gegroepeerd, kunnen de data dichtbij de randen van de groepering in de correcte groepering, de vorige/volgende groepering, of allebei verschijnen.

+++

+++**Update van het Onderhoud op 15 Juni, 2023**

Deze update bevat alleen kleine of minder belangrijke opgeloste problemen. [!DNL Workfront] Ondersteuning geeft een melding wanneer een probleem dat u hebt verzonden, is opgelost.

+++

+++**Update van het Onderhoud op 8 Juni, 2023**

Deze update bevat alleen kleine of minder belangrijke opgeloste problemen. [!DNL Workfront] Ondersteuning geeft een melding wanneer een probleem dat u hebt verzonden, is opgelost.

+++

+++**[!DNL Adobe Workfront Fusion]Onderhoudsupdate op 8 juni 2023**

[!DNL Fusion] heeft een correctie geïmplementeerd die voorkomt dat gebruikersverbindingen worden verwijderd wanneer de gebruiker wordt verwijderd of gedeactiveerd in [!UICONTROL Adobe Admin Console] .

[!DNL Fusion] -teambeheerders kunnen nog steeds overbodige verbindingen van de [!UICONTROL Connections] pagina in [!DNL Fusion] verwijderen.

+++

+++**Update van het Onderhoud op 1 Juni, 2023**

**Geen foutenmelding wanneer het opnieuw ordenen van taak in [!UICONTROL Pending approval] status**

_Taken_

Wanneer een gebruiker een taak in een takenlijst probeert opnieuw te rangschikken en de taak de status [!UICONTROL Pending approval] heeft, lijkt de taak in de takenlijst te bewegen. Na vernieuwen ziet de gebruiker dat het item niet is verplaatst. Het item kan niet worden verplaatst omdat het de status [!UICONTROL Pending approval] heeft, maar er is geen bericht om de gebruiker te laten weten dat het item niet kan worden verplaatst, wat tot verwarring kan leiden.

**Geen foutenmelding wanneer het bewegen van voorgangerstaak onder afhankelijke taak**

_Taken_

Wanneer een gebruiker een taak in een takenlijst probeert opnieuw te rangschikken en de taak de status [!UICONTROL Pending approval] heeft, lijkt de taak in de takenlijst te bewegen. Na vernieuwen ziet de gebruiker dat het item niet is verplaatst. Het item kan niet worden verplaatst omdat een voorganger niet kan worden verplaatst onder een taak waarvoor het de voorganger is, maar er is geen bericht om de gebruiker te laten weten dat het item niet kan worden verplaatst, wat tot verwarring kan leiden.

+++

## Updates in mei 2023

+++**Update van het Onderhoud op 25 Mei, 2023**

**[!UICONTROL Kanban]-board blijft leeg wanneer u kaarten bewerkt**

_Gelijk_

Wanneer een gebruiker iets wijzigt over een kaart op de [!UICONTROL Kanban] -board, wordt het [!UICONTROL Kanban] -board leeg weergegeven in plaats van te worden vernieuwd met de wijziging. Als de gebruiker de pagina handmatig vernieuwt, wordt het [!UICONTROL Kanban] -bord geretourneerd en wordt de juiste wijziging weergegeven.

Dit is gemeld in de volgende omstandigheden:

* Een kaart bewerken
* Een kaart verplaatsen


+++

+++**Update van het Onderhoud op 22 Mei, 2023**

**kan niet de grootte van beschrijvende teksten aanpassen**

_de vormen van de Douane_

Toen de aangepaste formulierontwerper in de bètaversie werd uitgebracht, was de functionaliteit om de grootte van beschrijvende tekst aan te passen niet beschikbaar. Dit probleem is opgelost en gebruikers kunnen de grootte van beschrijvende tekst nu aanpassen.

+++

+++**Update van het Onderhoud op 18 Mei, 2023**

**het Rapport sorteert niet correct wanneer het sorteren door douanegebied**

_Rapporten_
Wanneer een gebruiker een taakrapport in werking stelt, lijkt het rapport correct te sorteren wanneer het laadt, maar wanneer het klaar is met laden ziet de gebruiker dat het rapport niet correct gesorteerd is.

Dit lijkt zich voor te doen als aan alle volgende voorwaarden is voldaan:

* Het verslag is een taakverslag
* Het rapport wordt gesorteerd op een aangepast veld
* Er is een groepering toegepast op het rapport

+++

+++**Update van het Onderhoud op 11 Mei, 2023**

**kan proefdrukversie niet schakelen wanneer het bekijken van bewijs**

_Proofs_

Wanneer een gebruiker een proefdruk weergeeft in [!UICONTROL Proofing Viewer] en overschakelt naar een andere versie, wordt het vervolgkeuzemenu uitgeschakeld en kan de gebruiker niet terugschakelen naar de oorspronkelijke versie die hij of zij bekeek, of naar een andere versie van de proefdruk.

**[!DNL Workfront]Zoektijden uit**

_Onderzoek_

[!DNL Workfront] zoekopdracht is time-out. De zoekopdracht kan een paar resultaten opleveren, of helemaal geen.

Dit probleem heeft ook invloed op de functionaliteit van de module [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Search] .

+++

+++**[!DNL Adobe Workfront Fusion]Onderhoudsupdate op 11 mei 2023**

**Time-outfouten in[!DNL Workfront Fusion]**

_de Fusie van Adobe Workfront_

Wanneer een scenario loopt, kan het een onderbrekingsfout hebben. De informatie van de module met de fout bereikt zijn bestemming niet.

**[!DNL Workfront]Zoektijden uit**

_Onderzoek_

[!DNL Workfront] zoekopdracht is time-out. De zoekopdracht kan een paar resultaten opleveren, of helemaal geen.

Dit probleem heeft ook invloed op de functionaliteit van de module [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Search] .

+++

+++**Update van het Onderhoud op 9 Mei, 2023**

**Bewaarde filters beschikbaar in de kolom van de bordinname**

_Boards_

U kunt nu bestaande Workfront-taken en -filters gebruiken bij het configureren van de innamekolom voor een board. Bestaande inlaatkolomfilters zijn nu echter alleen-lezen in het configuratievenster. De bestaande filters worden nog steeds toegepast op de inlaatkolom, maar u moet de filters opnieuw maken als u ze wilt bewerken.

+++

+++**Update van het Onderhoud op 4 Mei, 2023**

**Kan sjabloon niet selecteren vanuit[!UICONTROL Favorite templates]**

_Malplaatjes_

Wanneer een gebruiker een sjabloon probeert te selecteren in het menu Handelingen (drie punten), verdwijnt de lijst met sjablonen wanneer de gebruiker de muis naar de lijst verplaatst en kan de gebruiker geen sjabloon selecteren. De reden hiervoor is dat de schuifbalk zich tussen het menu en de lijst met sjablonen bevindt. De muis richt zich dan op de schuifbalk terwijl deze naar de lijst met sjablonen gaat.

+++

## Updates in april 2023

+++**Update van het Onderhoud op 27 April, 2023**

**Kan niet schakelen tussen proefdrukken in[!UICONTROL Proof Viewer]**

_Proofs_

Wanneer een gebruiker een proef in [!UICONTROL Proofing Viewer] bekijkt, en op een andere proef overschakelt, wordt de schakelaar proefdruk knoop niet ontvankelijk. De gebruiker kan niet terugschakelen naar de oorspronkelijke proefdruk die hij of zij bekeek of naar een andere proefdruk.

**geef beelden in bijlage uit wanneer het uitgeven van een commentaar**

_Updates_

U kunt de afbeelding die aan een opmerking is gekoppeld nu bewerken wanneer u een opmerking bewerkt. Dit is beschikbaar in de sectie Updates voor Workfront Goals en in die van problemen wanneer u de bètaervaring met opmerkingen inschakelt.

+++

+++**[!DNL Adobe Workfront Fusion]Onderhoudsupdate op 25 april 2023**

**[!DNL Fusion]In-app Help-koppelingen leiden niet tot specifieke Help-pagina&#39;s**

_[!DNL Workfront Fusion]_

Wanneer een gebruiker een proef in [!UICONTROL Proofing Viewer] bekijkt, en op een andere proef overschakelt, wordt de schakelaar proefdruk knoop niet ontvankelijk. De gebruiker kan niet terugschakelen naar de oorspronkelijke proefdruk die hij of zij bekeek of naar een andere proefdruk.

+++

+++**Update van het Onderhoud op 20 April, 2023**

**Kwesties in douane dropdown gebieden**

_de vormen van de Douane_

Aangepaste vervolgkeuzelijsten die zijn ingeschakeld als multiselect-velden, kunnen de volgende problemen weergeven:

* De knop &quot;+[!UICONTROL Add]&quot; is niet aanwezig wanneer het formulier zich niet in de bewerkingsmodus bevindt.
* De gebieden die geen waarden hebben tonen &quot;— [!UICONTROL no label]—&quot;optie.

**kan geen Veelhoekig hulpmiddel gebruiken wanneer het maken van een commentaar op een proef**

_Proofs_

Wanneer een gebruiker een proefdruk weergeeft in de Proofing Viewer en probeert een opmerking te maken met het gereedschap Veelzijdig, markeert het gereedschap de proefdruk niet.

**de optiesvakje van de Tekst toont &quot;textAnnotations&quot;**

_Proofs_

Wanneer een gebruiker een proefdruk weergeeft, een opmerking toevoegt en het gereedschap Tekst opent, wordt het woord &quot;textAnnotation&quot; weergegeven naast de opties in het gereedschap. Het gereedschap Tekst functioneert nog steeds zoals u had verwacht en &quot;textAnnotation&quot; verdwijnt na het plaatsen van de opmerking.

**houd beelden als ontwerp wanneer het bewegen weg van een update voor doelstellingen en voor kwesties in het becommentariëren bètaervaring**

>[!NOTE]
>
>Deze functie is op 19 april 2023 uitgebracht aan Preview en is op 20 april 2023 in productie genomen.

_Updates_

Wanneer u nu weg navigeert van de pagina Updates terwijl u midden in het samenstellen van een bericht bent waar u een afbeelding hebt gekoppeld, blijven het bericht en de afbeelding behouden wanneer u terugnavigeert. Vóór deze update bleef de niet-verzonden opmerking behouden, maar werd de afbeelding verwijderd. Dit is beschikbaar in de sectie van Updates voor doelstellingen en in die van kwesties wanneer het toelaten van de het becommentariëren bètaervaring.

**updates in real time en geschrapte commentaren in de sectie van Updates**

>[!NOTE]
>
>Deze functie is op 19 april 2023 uitgebracht aan Preview en is op 20 april 2023 in productie genomen.

_Updates_

Wanneer iemand nu een opmerking of antwoord toevoegt of een opmerking verwijdert uit het gedeelte Updates, kunt u de nieuwe opmerking of een indicatie zien dat de opmerking in real-time en zonder vertraging is verwijderd. Dit is beschikbaar in de sectie van Updates voor doelstellingen en in die van kwesties wanneer het toelaten van de het becommentariëren bètaervaring.

**het niveau van de Toegang dat door systeem zonder een verslag van de verandering wordt veranderd**

_Gebruikers_

Het toegangsniveau van een gebruiker kan onvoorspelbaar door het systeem worden veranderd. Wanneer dit voorkomt, is er geen zichtbare update, en de verandering verschijnt niet in het controlelogboek.

+++

+++**Update van het Onderhoud op 17 April, 2023**

**toon nieuwe commentaren buiten het zichtbare schermgebied in de [!UICONTROL Updates] sectie van kwesties (nieuw het becommentariëren Beta ervaring) en[!UICONTROL Goals]**

_Updates_

Er is een berichtenbanner toegevoegd voor de sectie [!UICONTROL Updates] om gebruikers te informeren wanneer er nieuwere opmerkingen over een item zijn die buiten het zichtbare gebied op het scherm vallen. Deze update is momenteel beschikbaar in het gedeelte [!UICONTROL Updates] met doelen en die van problemen wanneer de nieuwe bètaervaring voor opmerkingen is ingeschakeld voor problemen.

+++

+++**Update van het Onderhoud op 13 April, 2023**

**de Filters worden niet toegepast op de lijst van verzoeken**

_Verzoeken_

Wanneer een gebruiker een lijst met aanvragen weergeeft waarop een filter is toegepast, bevat de lijst aanvragen die het filter moet uitsluiten.

**Kan [!UICONTROL Default Hour Type] of[!UICONTROL Available Hour Types]** niet selecteren

_Gebruikers_

Wanneer een beheerder een gebruiker bewerkt en een [!UICONTROL Default Hour Type] of [!UICONTROL Available Hour Type] probeert te selecteren, zien ze dat de vervolgkeuzelijsten voor die velden zijn uitgeschakeld en dat de gebruikers geen uurtypen kunnen selecteren.

+++

+++**Update van het Onderhoud op 6 April, 2023**

**Dropdowns openen niet wanneer een gebruiker aan een proef** wordt toegevoegd

_Proofs_

Wanneer een gebruiker een andere gebruiker aan een proef in [!UICONTROL Proofing Viewer] toevoegt, kunnen &quot;[!UICONTROL Proof role]&quot;en &quot;[!UICONTROL Email alerts]&quot;dropdowns niet openen. De gebruiker kan geen proefdrukscherm of e-mailwaarschuwing toewijzen. Dit kan voorkomen wanneer het toevoegen van een gebruiker door een commentaar, of wanneer het delen van de proef met de gebruiker.

+++

## Updates in maart 2023

+++**Update van het Onderhoud op 30 Maart, 2023**

**kan proefdrukversie niet schakelen wanneer het bekijken van bewijs**

_Proofs_

Wanneer een gebruiker een proefdruk weergeeft in [!UICONTROL Proofing Viewer] en overschakelt naar een andere versie, wordt het vervolgkeuzemenu uitgeschakeld en kan de gebruiker niet terugschakelen naar de oorspronkelijke versie die hij of zij bekeek, of naar een andere versie van de proefdruk.

**504 fout wanneer het uitvoeren van rapporten**

_Rapporten_

Wanneer een gebruiker probeert om een rapport met een hoog aantal punten uit te voeren, zien zij een fout 504 en kunnen niet het rapport uitvoeren.

**Update die in naam van een gebruikersvertoningen wordt gemaakt direct van de gebruiker**

_Updates_

Wanneer een beheerder als gebruiker wordt aangemeld en een opmerking maakt, wordt die opmerking direct door de gebruiker weergegeven in plaats van door de beheerder namens de gebruiker.

+++

+++**Update van het Onderhoud op 23 Maart, 2023**

**[!UICONTROL Summary]de inhoud van het deelvenster is te breed voor het deelvenster**

_Documenten_

Wanneer een gebruiker het deelvenster [!UICONTROL Summary] voor een document bekijkt, is de inhoud te breed om in het deelvenster te zien. Het deelvenster heeft nu een horizontale schuifbalk en de gebruiker moet horizontaal schuiven om de inhoud van het deelvenster [!UICONTROL Summary] te kunnen zien. Dit gebeurt omdat de bestandsnaam van het document niet omloopt. Dit probleem is beperkt tot bestanden waarvan de bestandsnaam een bestandsextensie HTML heeft.

**Nieuwe [!UICONTROL Desktop Proofing Viewer] versie**

_het Bewijs_

Om een commentaarkwestie in [!UICONTROL Desktop Proofing Viewe] r te bevestigen, hebben wij een nieuwe versie van de Desktop het proef kijker opgesteld.

Gebruikers die [!UICONTROL Desktop Proofing Viewer] al hebben geïnstalleerd, krijgen deze update automatisch.

Gebruikers kunnen ook handmatig de nieuwste versie verkleinen. Voor meer informatie, zie [ installeer [!UICONTROL Desktop Proofing Viewer] ](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html).

* Vorige versie: 2.1.22
* Nieuwe versie: 2.1.23

+++

+++**Update van het Onderhoud op 16 Maart, 2023**

**controlelijstitems niet gekopieerd wanneer het kopiëren van een kaart**

_Boards_

Bij het kopiëren van een ad-hockaart (gekoppelde kaarten kunnen niet worden gekopieerd) worden de items in de controlelijst niet naar de nieuwe kaart gekopieerd.

**het gebied van de Douane mist wanneer de kwestie in project** wordt omgezet

_Projecten_

Wanneer een gebruiker een kwestie in een project gebruikend een malplaatje omzet, een douanegebied dat op de kwestie was niet op het project toont. Dit probleem betreft alleen niet-beheerders.

**de geen berichten van de Douane verschijnen in e-mailberichten**

_Proofs_

Wanneer een gebruiker een proef deelt en een douanebericht toevoegt, verschijnt dat douanebericht niet in het bericht e-mail aan de ontvanger. Het onderwerp is de proefdruknaam en het bericht komt niet voor in het e-mailbericht.

+++

+++**Update van het Onderhoud op 9 Maart, 2023**

**het niveau van de Toegang wordt niet toegewezen wanneer het opnieuw activeren van gebruiker**

_Gebruikers_

Wanneer een gebruiker een gedeactiveerde gebruiker opnieuw activeert en deze een toegangsniveau in het [!UICONTROL Reactivate User] -venster probeert toe te wijzen, wordt het vervolgkeuzemenu van het toegangsniveau niet gevuld zoals de gebruiker typt en kan de gebruiker geen toegangsniveau selecteren. Als de gebruiker in het toegangsniveau typt en bewaart, wordt dat toegangsniveau niet toegewezen aan de opnieuw geactiveerde gebruiker.

**sparen het ontwerp van een commentaar in het [!DNL Goals] gebied**

_[!DNL Workfront Goals]_

Wanneer u nu vanaf de [!UICONTROL Updates] -pagina van een doel navigeert terwijl u midden in het samenstellen van een bericht bent, blijft het bericht behouden wanneer u terugnavigeert. Vóór deze update zou de niet-verzonden opmerking zijn verwijderd.

+++

+++**Update van het Onderhoud op 2 Maart, 2023**

**kan geen kaarten toevoegen wanneer het groeperen wordt toegepast**

_Boards_

Wanneer een gebruiker een bord weergeeft met een groepering en probeert een kaart toe te voegen, kan de gebruiker alleen de naam van de kaart invoeren. De overige kaartvelden zijn uitgeschakeld, inclusief de knop [!UICONTROL Save] .

Als de gebruiker de groepering in [!UICONTROL None] verandert, blijft de kwestie. De gebruiker moet de groepering in [!UICONTROL None] veranderen en dan de pagina vernieuwen om de capaciteit te herstellen om een kaart toe te voegen.

**Verbonden kaarten niet toegevoegd aan kolommen die op status** worden gebaseerd

_Boards_

Hoewel het kolombeleid wordt toegepast op status, verschijnen de nieuwe verbonden kaarten in de uiterst linkse kolom en niet in de kolom die aan hun status beantwoordt.


**Verbinding aan een commentaar richt zich aan [!UICONTROL Details] pagina** opnieuw

_Updates_

Wanneer een gebruiker een koppeling volgt naar een opmerking over een object in Workfront, wordt de updatestream kort geladen en wordt de gebruiker omgeleid naar het gebied [!UICONTROL Details] van het object. Dit kan gebeuren als de gebruiker op de koppeling klikt in een e-mail of de koppeling in zijn browser plakt.

Dit is momenteel alleen van toepassing op objecten Document.

**Samenvatting van de Druk laadt niet**

_[!UICONTROL Workfront Proof]_

Wanneer een gebruiker de pagina Afdrukoverzicht probeert te laden, lijkt de pagina te zijn geladen, maar wordt deze nooit geladen.

+++

## Updates in februari 2023

+++**Update van het Onderhoud op 23 Februari, 2023**

**Verbinding aan een commentaar richt zich aan [!UICONTROL Details] pagina** opnieuw

_Updates_

Wanneer een gebruiker een koppeling volgt naar een opmerking over een object in Workfront, wordt de updatestream kort geladen en wordt de gebruiker omgeleid naar het gebied [!UICONTROL Details] van het object. Dit kan gebeuren als de gebruiker op de koppeling klikt in een e-mail of de koppeling in zijn browser plakt.

Dit is momenteel alleen van toepassing op objecten Document.

**de Gebruiker kan hun eigen berichtmontages** niet uitgeven

_Gebruikers_

Wanneer een gebruiker met een [!UICONTROL Worker] -licentie zijn eigen meldingsinstellingen probeert te bewerken, zijn de [!UICONTROL Notifications] -opties niet zichtbaar in het [!UICONTROL Edit] -venster en kan de gebruiker de instellingen niet bewerken.

+++

+++**Update van het Onderhoud op 16 Februari, 2023**

**Veelvoudige teamtaken op raden van bestuur**

_Boards_

U kunt nu meerdere teams toewijzen aan een taak of uitgave in een bestuur en aan de raad zelf.

**de wegvallimietverhoging van de Kaart**

_Boards_

De uiterste termijnen voor het wegvallen van kaarten zijn verlengd tot 8 weken/60 dagen in plaats van 4 weken/30 dagen.

**Geplande deactivatie deactiveert geen gebruiker**

_Gebruikers_

Wanneer een gebruiker volgens de planning moet worden gedeactiveerd en de geplande datum en tijd verstrijken, wordt de gebruiker niet gedeactiveerd.

+++

+++**Update van het Onderhoud op 9 Februari, 2023**

**[!UICONTROL Story Points]veld toegevoegd aan taak- en uitgavelijsten en -rapporten**

_Rapporten_

Het veld [!UICONTROL Story Points] kan nu worden toegevoegd aan lijsten en rapporten voor taken of problemen. Het is een bewerkbaar, vrij formulierveld dat niet is gekoppeld aan geplande uren of teamtoewijzingen.

+++

+++**Update van het Onderhoud op 8 Februari, 2023**

**knoop van de Filter in inlaatkolom**

_Boards_

De opnamekolom op een bord bevat nu een knop **[!UICONTROL Add a filter]** wanneer de kolom leeg is en er geen filters zijn gemaakt. De knoop opent het configuratiegebied, waar u filters kunt toevoegen om taken en kwesties in de inputkolom te brengen.

+++

+++**Update van het Onderhoud op 2 Februari, 2023**

**[!UICONTROL Boards]wordt standaard weergegeven in [!UICONTROL Main Menu]**

_Boards_

Het pictogram [!UICONTROL Boards] wordt nu weergegeven in [!UICONTROL Main Menu] voor gebruikers die geen lay-outsjabloon hebben. Borden worden ook standaard opgenomen in het hoofdmenu voor alle nieuwe lay-outsjablonen die worden gemaakt. Bestaande lay-outsjablonen zijn niet gewijzigd.

**kan e-mailmalplaatjes niet bewaren**

_Opstelling_

Wanneer een gebruiker een e-mailsjabloon probeert te maken of te bewerken, reageert de knop [!UICONTROL Save] niet en kan de gebruiker de sjabloon niet opslaan.

+++

## Updates in januari 2023

+++**Update van het Onderhoud op 30 Januari, 2023**

**Sneltoetsen die voor gemeenschappelijke die timesheet acties** worden toegevoegd

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

**Nieuwe informatiepictogrammen voor timesheets, timesheet profielen, en timesheet voorkeur**

_Timesheets_

>[!NOTE]
>
>Deze update is alleen beschikbaar in de voorbeeldomgeving op 3 november 2022 en is nu beschikbaar in Production.

Er zijn verschillende informatiepictogrammen toegevoegd aan de volgende instellingen:

* Selectievakje &quot;[!UICONTROL Can edit time]&quot; wanneer u een tijdspagina of een tijdbladprofiel maakt of bewerkt, om aan te geven dat fiatteurs, indien ingeschakeld, ook de tijdspagina kunnen verzenden, opnieuw openen of bewerken, tenzij uw beheerder deze handelingen beperkt in het [!UICONTROL Timesheet Preferences] gebied van [!UICONTROL Setup] .
* &quot;[!UICONTROL Restrict timesheet editing to owners and admins]&quot; in het [!UICONTROL Timesheet & Hour Preferences] gebied van [!UICONTROL Setup] om aan te geven dat wanneer uitgeschakeld, de volgende gebruikers de tijdbladen ook kunnen bewerken: gebruikers met beheerdersrechten voor tijdbladen en uren, fiatteurs van tijdschriften die tijd mogen bewerken en managers van tijdbladeigenaars.

De functionaliteit van deze instellingen is niet gewijzigd en alleen de informatiepictogrammen zijn toegevoegd om het bereik van de instellingen helderder te maken.

+++

+++**Update van het Onderhoud op 26 Januari, 2023**

**Fout bij het indienen van verzoek van[!DNL Outlook]**

_Integraties_

Wanneer een gebruiker een aanvraag probeert te verzenden met bijlagen uit een [!DNL Outlook] -e-mail, worden een of meer bijlagen niet geüpload en wordt de volgende fout weergegeven:

&quot;[!UICONTROL The following error occurred: File with handle xxxx does not exist.]&quot;

Dit komt slechts voor wanneer een taak voor het nieuwe verzoek wordt gemaakt, of door de verzoekrij of manueel wanneer het creëren van het verzoek.

**Nieuwe versie van de Kijker van de Desktop Proofing**

_het Bewijs_

We hebben een nieuwe versie van de Desktop Proofing Viewer geïmplementeerd om een probleem met het bevriezen van bestanden in de Desktop Proofing Viewer te verhelpen. Gebruikers die de Desktop Proofing Viewer al hebben geïnstalleerd, krijgen deze update automatisch.

Gebruikers kunnen ook handmatig de nieuwste versie verkleinen. Voor meer informatie, zie [ installeer de Desktop het Proofing Kijker ](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=en).

* Vorige versie: 2.1.19
* Nieuwe versie: 2.1.20

**de Gebruiker kan niet hun eigen gebruiker uitgeven die** plaatst

_Gebruikers_

Wanneer een gebruiker met een licentie voor werk, revisie of aanvraag zijn eigen gebruikersinstellingen probeert te bewerken, is de pop-up die wordt geopend leeg en kan de gebruiker geen bewerkingen uitvoeren. Om popup weg te gaan, moet de gebruiker de pagina verfrissen.

+++

+++**Update van het Onderhoud op 19 Januari, 2023**

**de kolomfilters van de Inname kunnen nu worden gedeeld**

_Boards_

Wanneer de inlaatkolomfunctie naar Boards is uitgebracht, konden de filters voor het instellen van de inlaatkolom alleen worden gezien door de persoon die deze filters heeft gemaakt. De maker kan de filters nu delen met andere gebruikers of teams.

**Vastzetten functionaliteit beschikbaar in [!UICONTROL More] menu**

_Navigatie_

De volgende functies zijn nu beschikbaar in het menu [!UICONTROL More] voor pinnen in de productieomgeving:

* Naam punten wijzigen
* Punten opnieuw ordenen in het menu [!UICONTROL More]
* Een punt uit het menu [!UICONTROL More] verplaatsen (wanneer u dit doet, wordt het laatste punt in de bovenste navigatiebalk naar het menu [!UICONTROL More] verplaatst)

+++

+++**Update van het Onderhoud op 18 Januari, 2023**

**Uitdrukkingen met vervangingen zijn niet geldig op douanegebieden**

_Aangepaste Forms_

Wanneer een gebruiker een jokerteken zoals \$$TODAY of $$NOW samen met een bepaling (zoals &quot;-30d&quot;) in een douanegebied gebruikt, keurt de validator de vervanging niet als geldig goed. Jokertekens zonder wijzigingstoetsen worden als geldig beschouwd.

**[!UICONTROL Workload Balancer]toont uren niet verbonden aan een project/taak/kwestie**

_[!UICONTROL Workload Balancer]_

Wanneer een gebruiker [!UICONTROL Workload Balancer] bekijkt, zien zij uren die voor een gebruiker worden geregistreerd die niet met om het even welk project, geen taak, of geen kwestie worden geassocieerd, noch worden zij geregistreerd als [!UICONTROL General] uren. Deze uren kunnen alleen worden weergegeven in de weergave van 4 weken of 6 weken.

+++

+++**[!DNL Adobe Workfront Fusion]Onderhoudsupdate (Hot Fix) op 12 januari 2023**

**404 fouten op [!DNL Workfront] modules**

_de Fusie van Workfront_

Wanneer een scenario wordt uitgevoerd, retourneert een module [!DNL Workfront] een fout van 404.

Dit is gerapporteerd in de volgende modules:

* [!UICONTROL Read a record]

+++

+++**Update van het Onderhoud (Hete Fix) op 12 Januari, 2023**

**&quot;[!UICONTROL Whoops]&quot;fout wanneer vestiging een berekend gebied**

_Aangepaste Forms_

Wanneer een gebruiker een berekend veld maakt of bewerkt op een aangepast formulier en een aangepast veld opneemt in de berekende expressie van het veld, wordt de expressie als ongeldig beschouwd. De knop [!UICONTROL Save] is uitgeschakeld en de gebruiker kan niet weg navigeren van het aangepaste veld. Bovendien ziet de gebruiker het volgende bericht onder het gebied:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;

Als u het aangepaste veld uit de expressie verwijdert, kan de gebruiker het veld opslaan en verder navigeren.

**kan toegangsniveaus niet plaatsen**

_Gebruikers_

Wanneer een gebruiker probeert om het toegangsniveau van een andere gebruiker te veranderen, worden de toegangsniveaus grijs uit en de gebruiker kan hen niet veranderen. Dit gebeurt zelfs wanneer de gebruiker die de wijziging probeert, een systeembeheerder is.

+++

+++**Update van het Onderhoud op 12 Januari, 2023**

**Ctrl+F of Cmd+F werkt niet zoals verwacht op dropdown gebieden**

_Aangepaste Forms_

Wanneer een gebruiker een aangepast formulier invult en een vervolgkeuzelijst doorzoekt met Ctrl+F of Cmd+F, wordt vervolgens geprobeerd naar het volgende exemplaar van die zoekopdracht te gaan, keert de vervolgkeuzelijst terug naar de bovenkant van de lijst in plaats van naar het volgende exemplaar van de zoekopdracht te gaan. Dit gebeurt wanneer een vervolgkeuzelijst is ingesteld om meerdere selecties toe te staan.

**[!UICONTROL Edit Report]screen is blank**

_Rapporten_

Wanneer een gebruiker een rapport bekijkt en probeert om het rapport uit te geven, wordt de gebruiker genomen aan een leeg scherm en kan niet het rapport uitgeven.

**Ingesprongen taken blijven niet ingesprongen**

_Taken_

Wanneer een gebruiker een takenlijst bekijkt en een taak inspringt, keert de taak onmiddellijk aan zijn originele (uitgedreven) staat terug.

+++

+++**Update van het Onderhoud op 5 Januari, 2023**

**Vastzetten functionaliteit beschikbaar in [!UICONTROL More] menu**

_Navigatie_

De volgende functies zijn nu alleen beschikbaar in het menu [!UICONTROL More] voor punten in de voorvertoningsomgeving:

* Naam punten wijzigen
* Punten opnieuw ordenen in het menu [!UICONTROL More]
* Een punt uit het menu [!UICONTROL More] verplaatsen (wanneer u dit doet, wordt het laatste punt in de bovenste navigatiebalk naar het menu [!UICONTROL More] verplaatst)

**Verwijderde de beperking van de projectgroep van het toevoegen van gebruikers aan het projectteam**

_Teams_

Wij hebben de beperking verwijderd die vereiste dat de gebruikers die aan een projectteam moeten worden toegevoegd in de Groep verbonden aan het project moeten zijn. Nu, kunt u om het even welke actieve gebruiker aan een projectteam toevoegen, ongeacht tot welke groepen zij behoren.

**Nieuwe informatiepictogrammen voor timesheets, timesheet profielen, en timesheet voorkeur**

>[!NOTE]
>
>Deze update is op 3 november 2022 uitgebracht naar de voorvertoningsomgeving en is nu beschikbaar in Production

_Workfront_

Er zijn verschillende informatiepictogrammen toegevoegd aan de volgende instellingen:

* &quot;Kan tijd&quot;checkbox uitgeven wanneer het creëren van of het uitgeven van een timesheet of een timesheet profiel om erop te wijzen dat wanneer toegelaten, de fiatteurs ook kunnen voorleggen, opnieuw openen, of uitgeven timesheet, tenzij uw beheerder deze acties in het gebied van de Voorkeur van de Chronologie van Opstelling beperkt.
* &quot;Beperk timesheet uitgeven tot eigenaars en beheerders&quot;in het gebied van de Voorkeur van de Tijdopmaak &amp; van het Uur van Opstelling om erop te wijzen dat wanneer gehandicapt, de volgende gebruikers ook timesheets kunnen uitgeven: gebruikers met administratieve toegang tot timesheets en uren, timeesheet fiatteurs toegestaan om tijd uit te geven, en de managers van timesheet eigenaars.

De functionaliteit van deze instellingen is niet gewijzigd en alleen de informatiepictogrammen zijn toegevoegd om het bereik van de instellingen helderder te maken.

+++

## Vorige onderhoudsupdates

Informatie over vorige onderhoudsupdates is hier beschikbaar:

* [[!DNL Workfront] Archief met onderhoudsupdates - 2022](2022-updates.md)
* [[!DNL Workfront] Archief met onderhoudsupdates - 2021](2021-updates.md)
