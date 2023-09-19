---
title: Workfront-onderhoudsupdates
description: Onderhoudsupdates voor [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 2abcb617a2462f5e2a3231b35b0153add23d6969
workflow-type: tm+mt
source-wordcount: '5240'
ht-degree: 0%

---

# [!DNL Workfront] Onderhoudsupdates

De volgende onderhoudsupdates zijn uitgevoerd in 2023.

>[!NOTE]
>
>Deze updates bevatten ook andere kleine of minder duidelijke foutoplossingen. [!DNL Workfront] Ondersteuning geeft een melding wanneer een probleem dat u hebt verzonden, is opgelost.

Voor onderhoudsupdates vóór 2023, zie [Vorige onderhoudsupdates](#previous-maintenance-updates)

## Updates in september 2023

+++**(Geplande) onderhoudsupdate op 21 september 2023**

**Kan geen gebruiker toewijzen aan een board op een werkstroom**

_Borden_

Wanneer een gebruiker probeert een andere gebruiker aan een taak van een raad toe te wijzen die deel van een werkstroom uitmaakt, en de naam van de gebruiker begint te typen, verschijnt de gebruiker niet op de drop-down lijst van beschikbare gebruikers. Dit gebeurt zelfs wanneer de gebruiker actief is en een lid van zowel de raad als de werkstroom.

Het kan ook voorkomen dat gedeactiveerde gebruikers in de vervolgkeuzelijst worden weergegeven.

**Aangepaste formulieren worden langzaam geladen**

_Aangepaste formulieren_

Wanneer een gebruiker een aangepast formulier probeert te laden, wordt het aangepaste formulier langzaam geladen.

**Kan document niet naar een andere map verplaatsen**

_Documenten_

Wanneer een gebruiker een document naar een objectmap verplaatst, kan hij of zij het object niet naar een andere map verplaatsen.

**XML-fout tijdens downloaden**

_Documenten_

Wanneer een gebruiker een document probeert te downloaden, wordt het document niet gedownload en ziet de gebruiker een pagina met het volgende bericht gevolgd door XML-tekst.

&quot;[!UICONTROL The XML file does not appear to have any style information associated with it. The document tree is below.]&quot;

**Kan geen documenten downloaden uit een voorvertoning-/sandbox-omgeving**

_Documenten_

Wanneer een gebruiker een document probeert te downloaden vanuit een andere omgeving dan productie, wordt het document niet gedownload en ziet de gebruiker de volgende fout:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;

**Proefdrukken worden weergegeven zonder verzadiging of bijgesneden**

_Proefdrukken_

De volgende problemen zijn gemeld bij het maken van een proef via een URL.

* De proefdruk lijkt te zijn verzadigd of te zijn gewassen.
* De proefdruk wordt bijgesneden.

Dit kan ertoe leiden dat de bewijsvoering moeilijk is, omdat de bewijsvoering niet correct wordt weergegeven.

**Het genereren van proefdrukken duurt te lang**

_Proefdrukken_

Wanneer een gebruiker een bewijs probeert te produceren, vergt het bewijs een buitensporige hoeveelheid tijd om te produceren. De proefproductie kan enkele dagen duren.

+++

+++**Onderhoudsupdate op 14 september 2023**

**&quot;[!UICONTROL No factory]&quot; fout bij het toevoegen van een document**

_Documenten_

Wanneer een gebruiker een document uit een externe bron probeert toe te voegen, [!DNL Workfront] heeft geen toegang tot de bron en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL The following error occurred: No factory found for authentication type null]&quot;

**Fout in matrix-rapporten met de fout &quot;Wiops&quot;**

_Rapporten_

Wanneer een gebruiker probeert om een matrixrapport te bekijken, laadt het rapport niet, en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;

Dit komt voor wanneer het groeperen van een rapport door datumwaaiers.

+++

+++**Onderhoudsupdate op 11 september 2023**

**Persoonlijke taken worden niet weergegeven in timesheets**

_Timesheets_

De persoonlijke taken tonen niet meer op timesheet door gebrek. De persoonlijke taken tonen op timesheet wanneer zij worden vastgezet of uren het programma worden geopend. Voorafgaand aan deze verandering, persoonlijke taken die op timesheets door gebrek worden getoond.

+++

+++**Onderhoudsupdate op 7 september 2023**

**Project is leeg wanneer het uit nieuw wordt geladen [!UICONTROL Home] ervaring**

_Projecten_

Wanneer een gebruiker op een project van hun klikt [!UICONTROL Home] pagina in de nieuwe ervaring van het Huis, kan de pagina van het project niet laden.

Dit komt voor wanneer de gebruiker als een andere gebruiker heeft het programma geopend, dan het programma geopend als andere gebruiker en aan hun teruggekeerd [!UICONTROL Home] pagina.

+++

**Filters zijn niet van toepassing op widgets in de nieuwe [!UICONTROL Home] ervaring**

## Updates in augustus 2023

+++**Onderhoudsupdate op 31 augustus 2023**

**Filters zijn niet van toepassing op widgets in de nieuwe [!UICONTROL Home] ervaring**

_[!UICONTROL Home]_

Wanneer een gebruiker een filter toepast op een widget in de nieuwe [!UICONTROL Home] In de widget worden items weergegeven die door het filter moeten worden uitgesloten.

Dit is gemeld in de aangepaste sandbox-omgeving. Dezelfde widgets filteren in de voorvertoning- en productieomgevingen als u had verwacht.

**Problemen bij het laden van Matrix-rapporten**

_Rapporten_

Wanneer een gebruiker probeert om een rapport van de Matrijs als grafiek te laden, één van het volgende kan voorkomen:

* Bepaalde informatie in het rapport wordt niet geladen
* Het rapport geeft de fout &quot;[!UICONTROL Unable to load content from the server]&quot;

**De Planner wordt niet geladen wanneer het filter wordt toegepast**

_[!UICONTROL Resource Planner]_

Wanneer een gebruiker probeert de [!UICONTROL Resource Planner], wordt de planner niet geladen en ziet de gebruiker het volgende foutbericht:

&quot;[!UICONTROL The following error occurred: Something went wrong while connecting to WorkPerDay service]&quot;

+++

+++**Onderhoudsupdate op 24 augustus 2023**

**Kan geen tekst selecteren in lijsten of opsommingstekens**

_Proefdrukken_

Wanneer een gebruiker een proef in de het proefdrukken kijker bekijkt en probeert om tekst te selecteren die in een lijst of een kogelpunt is, is het hulpmiddel van de tekstselectie inefficiënt, en de tekst kan niet worden geselecteerd.

**Als u een nieuwe proefversie maakt, worden alle proefversies verwijderd**

_Proefdrukken_

Wanneer een gebruiker een proefdruk maakt op basis van een document, wordt de proefdruk gemaakt. Als een gebruiker echter een andere versie van de proefdruk maakt, worden zowel de oude als de nieuwe versie verwijderd. Er is een [!UICONTROL Create Proof] en de proefversies vindt u in het [!UICONTROL Trash] gebied van de [!UICONTROL Proofing] gebied in [!DNL Workfront].

+++

+++**Onderhoudsupdate op 17 augustus 2023**

**Kan niet navigeren naar project met URL die gebruikt[!UICONTROL Reference ID]**

_Projecten_

Wanneer een gebruiker naar een project probeert te navigeren met een URL die een [!UICONTROL Reference ID] -nummer, worden ze doorgestuurd naar een pagina met een foutbericht. Navigeren naar een taak met behulp van een URL met een [!UICONTROL Reference ID] werkt zoals verwacht.

**&quot;[!UICONTROL Disable proof email notifications]&quot; instelling wordt onjuist weergegeven**

_Proefdrukken_

Wanneer een gebruiker proefdrukinstellingen weergeeft in [!DNL Workfront], de &quot;[!UICONTROL Disable proof email notifications]&quot; het selectievakje geeft de juiste huidige instelling niet correct weer. Als dit selectievakje is ingeschakeld, worden e-mailmeldingen met een proefdruk uitgeschakeld. De meldingen worden nu daadwerkelijk ingeschakeld. Het tegendeel is ook waar.

**Kan proefdrukmarkeringen niet aanpassen**

_Proefdrukken_

Wanneer een gebruiker een opmerking maakt in de drukproefviewer en een markering maakt op de proefdruk en vervolgens wegklikt, kan de gebruiker de markering niet meer aanpassen.

+++

+++**Onderhoudsupdate op 10 augustus 2023**

**Kan niet verwijderen [!UICONTROL To-do] object in nieuw [!UICONTROL Home] ervaring**

_Home_

Wanneer een gebruiker in de nieuwe [!UICONTROL Home] ervaring probeert een item te verwijderen uit het dialoogvenster [!UICONTROL To-do] widget, het item wordt niet verwijderd en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL There was a problem removing your to-do, please try again soon.]&quot;

Dit kan voorkomen wanneer er uren aan het programma worden geregistreerd [!UICONTROL To-do] item.

**Vastgezet project toont geen informatie in sommige kolommen**

_Projecten_

Wanneer een gebruiker naar een vastgezet project navigeert gebruikend het punt, kunnen de objecten lijsten (zoals de taaklijst) lege kolommen tonen. Een [!UICONTROL Assignments] in de kolom kunnen geen toewijzingen worden weergegeven, ook al zijn er toewijzingen gemaakt.

**Slaapmodule zorgt ervoor dat scenario&#39;s hangen**

_[!DNL Workfront Fusion]_

De [!UICONTROL Tools] > [!UICONTROL Sleep] de module in een scenario kan een scenario uitvoeren om te hangen. Deze uitvoeringen tonen een status van Running in [!UICONTROL Scenario History]en niet voltooien.

+++

+++**Onderhoudsupdate op 3 augustus 2023**

**Probleem met items in inlaatkolom vinden**

_Borden_

De inlaatkolom op een board werd eerder gesorteerd op de prioriteit die op taken en kwesties werd bepaald, die het moeilijk maakten om van specifieke punten de plaats te bepalen.

De standaardvolgorde is nu als volgt:

Taken:

* Primaire bestelling: Projectnaam
* Secundaire volgorde: structuur van werkverdeling

Problemen

* Primaire bestelling: Projectnaam
* Secundaire volgorde: Referentienummer

**Project lost probleem niet correct op**

_Projecten/problemen_

Wanneer een gebruiker de status wijzigt van een project dat het oplossende object voor een uitgave is, wordt de status van de uitgave gewijzigd in een status die niet overeenkomt met dezelfde sleutel als de status van het project.

**Fout in matrix-rapporten met de fout &quot;Wiops&quot;**

_Rapporten_

Wanneer een gebruiker probeert om een matrixrapport te bekijken, laadt het rapport niet, en de gebruiker ziet de volgende fout:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;

Dit is gemeld voor gebruikers in EMEA.

+++

## Updates in juli 2023

+++**Onderhoudsupdate op 27 juli 2023**

**Labels en controlelijstitems werken niet correct in de weergave van het projectbord**

_Borden_

Labels en controlelijstitems zijn verwijderd uit de weergave aan boord van projecten, omdat ze geen deel uitmaken van de Workfront-taken en niet kunnen worden gedeeld tussen gebruikers.

**&quot;[!UICONTROL Enable system-wide]&quot; en &quot;[!UICONTROL View system-wide]&quot; Andere functionaliteit vertegenwoordigen**

_Filters_

Als een gebruiker een filter deelt en &quot;[!UICONTROL View system-wide]&quot;, wordt het filter gedeeld met elke gebruiker in het systeem. Als een beheerder dit filter echter in [!UICONTROL Setup], zien ze dat dit filter wordt weergegeven &quot;[!UICONTROL false]&quot; in de &quot;[!UICONTROL Visible System-Wide]&quot; kolom. Om van dit filter een systeemgebrek te maken, moet admin &quot;[!UICONTROL Enable system-wide]&quot;, optie in [!UICONTROL Setup]. Dit kan enige verwarring veroorzaken vanwege de gelijkenis van de formulering.

+++

+++**Onderhoudsupdate op 20 juli 2023**

Deze update bevat alleen kleine of minder belangrijke opgeloste problemen. [!DNL Workfront] Ondersteuning geeft een melding wanneer een probleem dat u hebt verzonden, is opgelost.

+++

+++**Onderhoudsupdate op 13 juli 2023**

**Tijdlijn wordt niet opnieuw berekend**

_Projecten/taken/problemen_

Wanneer een even gebeurtenis optreedt die een tijdlijnberekening zou moeten activeren, wordt de tijdlijn niet opnieuw berekend. Dit beïnvloedt herberekeningen die op veranderingen voorkomen, en geplande herberekeningen. Dit kan van invloed zijn op de nauwkeurigheid van de werklastverdeling.

**Vergrendelde proefdrukgoedkeuringen worden nog steeds weergegeven in de werklijst**

_Proefdrukken_

Goedkeuringen met bewijzen die hun deadline hebben overschreden en zijn vergrendeld, worden nog steeds weergegeven op de thuiswerklijst van de fiatteur in plaats van de lijst af te sluiten wanneer de deadline is verstreken.

**Het gebruiksrapport wordt niet geladen**

_Rapporten_

Wanneer een klant probeert om een gebruiksrapport te bekijken, ziet de gebruiker een het draaien ladingsindicator, maar het rapport laadt niet. Het rapport heeft een fout van 500 geretourneerd, maar de gebruiker ziet geen aanwijzing dat het rapport is mislukt.

**Gebruikerspagina bewerken is leeg**

<!--no article-->

_Gebruikers_

Wanneer een gebruiker probeert een andere gebruiker te bewerken, is de pagina Gebruiker bewerken leeg en kan de gebruiker de andere gebruiker niet bewerken.

+++

## Updates in juni 2023

+++**Onderhoudsupdate op 29 juni 2023**

Deze update bevat alleen kleine of minder belangrijke opgeloste problemen. [!DNL Workfront] Ondersteuning geeft een melding wanneer een probleem dat u hebt verzonden, is opgelost.

+++

+++**Onderhoudsupdate op 22 juni 2023**

**&quot;[!UICONTROL Whoops]&quot;-fout bij weergeven van matrixrapport**

_Rapporten_

Wanneer een gebruiker een matrixrapport weergeeft, wordt de volgende fout weergegeven:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;

Dit is gemeld wanneer het rapport is gesorteerd op datum en &quot;[!UICONTROL Show weeks with no results]&quot; is ingeschakeld.

**Datums worden onjuist weergegeven in matrixrapporten**

_Rapporten_

Wanneer een grafiek of matrixrapport op datum wordt gegroepeerd, kunnen de data dichtbij de randen van de groepering in de correcte groepering, de vorige/volgende groepering, of allebei verschijnen.

+++

+++**Onderhoudsupdate op 15 juni 2023**

Deze update bevat alleen kleine of minder belangrijke opgeloste problemen. [!DNL Workfront] Ondersteuning geeft een melding wanneer een probleem dat u hebt verzonden, is opgelost.

+++

+++**Onderhoudsupdate op 8 juni 2023**

Deze update bevat alleen kleine of minder belangrijke opgeloste problemen. [!DNL Workfront] Ondersteuning geeft een melding wanneer een probleem dat u hebt verzonden, is opgelost.

+++

+++**[!DNL Adobe Workfront Fusion]Onderhoudsupdate op 8 juni 2023**

[!DNL Fusion] heeft een oplossing geïmplementeerd die voorkomt dat de verbindingen van een gebruiker worden verwijderd wanneer de gebruiker in het dialoogvenster [!UICONTROL Adobe Admin Console].

[!DNL Fusion] teambeheerders zijn nog steeds in staat onnodige verbindingen uit de [!UICONTROL Connections] pagina in [!DNL Fusion].

+++

+++**Onderhoudsupdate op 1 juni 2023**

**Geen foutbericht bij opnieuw ordenen van taak in [!UICONTROL Pending approval] status**

_Taken_

Wanneer een gebruiker een taak in een takenlijst probeert opnieuw te rangschikken en de taak binnen is [!UICONTROL Pending approval] status, lijkt de taak in de takenlijst te bewegen. Na vernieuwen ziet de gebruiker dat het item niet is verplaatst. Het item kan niet worden verplaatst omdat het zich in [!UICONTROL Pending approval] status, maar er is geen bericht om de gebruiker te laten weten dat het item niet kan worden verplaatst, wat tot verwarring kan leiden.

**Geen foutbericht bij verplaatsen van voorgangstaak onder afhankelijke taak**

_Taken_

Wanneer een gebruiker een taak in een takenlijst probeert opnieuw te rangschikken en de taak binnen is [!UICONTROL Pending approval] status, lijkt de taak in de takenlijst te bewegen. Na vernieuwen ziet de gebruiker dat het item niet is verplaatst. Het item kan niet worden verplaatst omdat een voorganger niet kan worden verplaatst onder een taak waarvoor het de voorganger is, maar er is geen bericht om de gebruiker te laten weten dat het item niet kan worden verplaatst, wat tot verwarring kan leiden.

+++

## Updates in mei 2023

+++**Onderhoudsupdate op 25 mei 2023**

**[!UICONTROL Kanban]board wordt leeg gebruikt bij het bewerken van kaarten**

_Agile_

Wanneer een gebruiker iets wijzigt over een kaart op het tabblad [!UICONTROL Kanban] de [!UICONTROL Kanban] Het bord wordt leeg weergegeven in plaats van te vernieuwen met de wijziging. Als de gebruiker de pagina handmatig vernieuwt, [!UICONTROL Kanban] boardgeretourneerde waarden, met de juiste wijziging.

Dit is gemeld in de volgende omstandigheden:

* Een kaart bewerken
* Een kaart verplaatsen


+++

+++**Onderhoudsupdate op 22 mei 2023**

**Kan de grootte van beschrijvende tekst niet aanpassen**

_Aangepaste formulieren_

Toen de aangepaste formulierontwerper in de bètaversie werd uitgebracht, was de functionaliteit om de grootte van beschrijvende tekst aan te passen niet beschikbaar. Dit probleem is opgelost en gebruikers kunnen de grootte van beschrijvende tekst nu aanpassen.

+++

+++**Onderhoudsupdate op 18 mei 2023**

**Rapport wordt niet correct gesorteerd bij sorteren op aangepast veld**

_Rapporten_
Wanneer een gebruiker een taakrapport in werking stelt, lijkt het rapport correct te sorteren wanneer het laadt, maar wanneer het klaar is met laden ziet de gebruiker dat het rapport niet correct gesorteerd is.

Dit lijkt zich voor te doen als aan alle volgende voorwaarden is voldaan:

* Het verslag is een taakverslag
* Het rapport wordt gesorteerd op een aangepast veld
* Er is een groepering toegepast op het rapport

+++

+++**Onderhoudsupdate op 11 mei 2023**

**Kan proefdrukversie niet wisselen bij weergave van proefdrukversie**

_Proefdrukken_

Wanneer een gebruiker een proef in bekijkt [!UICONTROL Proofing Viewer]en overschakelt naar een andere versie, wordt het vervolgkeuzemenu uitgeschakeld en kan de gebruiker niet terugschakelen naar de oorspronkelijke versie die hij of zij bekeek, of naar een andere versie van de proefdruk.

**[!DNL Workfront]Zoektijden uit**

_Zoeken_

[!DNL Workfront] zoekactie is time-out. De zoekopdracht kan een paar resultaten opleveren, of helemaal geen.

Deze kwestie beïnvloedt ook de functionaliteit van [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Search] -module.

+++

+++**[!DNL Adobe Workfront Fusion]Onderhoudsupdate op 11 mei 2023**

**Time-outfouten in[!DNL Workfront Fusion]**

_Adobe Workfront Fusion_

Wanneer een scenario loopt, kan het een onderbrekingsfout hebben. De informatie van de module met de fout bereikt zijn bestemming niet.

**[!DNL Workfront]Zoektijden uit**

_Zoeken_

[!DNL Workfront] zoekactie is time-out. De zoekopdracht kan een paar resultaten opleveren, of helemaal geen.

Deze kwestie beïnvloedt ook de functionaliteit van [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Search] -module.

+++

+++**Onderhoudsupdate op 9 mei 2023**

**Opgeslagen filters beschikbaar in de inlaatkolom**

_Borden_

U kunt nu bestaande Workfront-taken en -filters gebruiken bij het configureren van de innamekolom voor een board. Bestaande inlaatkolomfilters zijn nu echter alleen-lezen in het configuratievenster. De bestaande filters worden nog steeds toegepast op de inlaatkolom, maar u moet de filters opnieuw maken als u ze wilt bewerken.

+++

+++**Onderhoudsupdate op 4 mei 2023**

**Kan sjabloon niet selecteren vanuit[!UICONTROL Favorite templates]**

_Sjablonen_

Wanneer een gebruiker een sjabloon probeert te selecteren in het menu Handelingen (drie punten), verdwijnt de lijst met sjablonen wanneer de gebruiker de muis naar de lijst verplaatst en kan de gebruiker geen sjabloon selecteren. De reden hiervoor is dat de schuifbalk zich tussen het menu en de lijst met sjablonen bevindt. De muis richt zich dan op de schuifbalk terwijl deze naar de lijst met sjablonen gaat.

+++

## Updates in april 2023

+++**Onderhoudsupdate op 27 april 2023**

**Kan niet schakelen tussen proefdrukken in[!UICONTROL Proof Viewer]**

_Proefdrukken_

Wanneer een gebruiker een proef in bekijkt [!UICONTROL Proofing Viewer]en schakelt u over naar een andere proefdruk. De knop voor de proefdruk van de switch reageert dan niet. De gebruiker kan niet terugschakelen naar de oorspronkelijke proefdruk die hij of zij bekeek of naar een andere proefdruk.

**Gekoppelde afbeeldingen bewerken tijdens het bewerken van een opmerking**

_Updates_

U kunt de afbeelding die aan een opmerking is gekoppeld nu bewerken wanneer u een opmerking bewerkt. Dit is beschikbaar in de sectie Updates voor Workfront Goals en in die van problemen wanneer u de bètaervaring met opmerkingen inschakelt.

+++

+++**[!DNL Adobe Workfront Fusion]Onderhoudsupdate op 25 april 2023**

**[!DNL Fusion]Help-koppelingen in de app leiden niet tot specifieke Help-pagina&#39;s**

_[!DNL Workfront Fusion]_

Wanneer een gebruiker een proef in bekijkt [!UICONTROL Proofing Viewer]en schakelt u over naar een andere proefdruk. De knop voor de proefdruk van de switch reageert dan niet. De gebruiker kan niet terugschakelen naar de oorspronkelijke proefdruk die hij of zij bekeek of naar een andere proefdruk.

+++

+++**Onderhoudsupdate op 20 april 2023**

**Problemen in aangepaste vervolgkeuzelijsten**

_Aangepaste formulieren_

Aangepaste vervolgkeuzelijsten die zijn ingeschakeld als multiselect-velden, kunnen de volgende problemen weergeven:

* De &quot;+[!UICONTROL Add]De knop &quot;&quot; is niet aanwezig als het formulier zich niet in de bewerkingsmodus bevindt.
* Velden zonder waarden geven een &quot;—[!UICONTROL no label]—&quot;.

**Kan het gereedschap Veellijn niet gebruiken wanneer u een opmerking maakt over een proefdruk**

_Proefdrukken_

Wanneer een gebruiker een proefdruk weergeeft in de Proofing Viewer en probeert een opmerking te maken met het gereedschap Veelzijdig, markeert het gereedschap de proefdruk niet.

**In het vak Tekstopties wordt &quot;textAnnotations&quot; weergegeven**

_Proefdrukken_

Wanneer een gebruiker een proefdruk weergeeft, een opmerking toevoegt en het gereedschap Tekst opent, wordt het woord &quot;textAnnotation&quot; weergegeven naast de opties in het gereedschap. Het gereedschap Tekst functioneert nog steeds zoals u had verwacht en &quot;textAnnotation&quot; verdwijnt na het plaatsen van de opmerking.

**Behoud afbeeldingen als concept wanneer u afstapt van een update voor doelen en voor problemen in de bètaervaring met opmerkingen**

>[!NOTE]
>
>Deze functie is op 19 april 2023 uitgebracht aan Preview en is op 20 april 2023 in productie genomen.

_Updates_

Wanneer u nu weg navigeert van de pagina Updates terwijl u midden in het samenstellen van een bericht bent waar u een afbeelding hebt gekoppeld, blijven het bericht en de afbeelding behouden wanneer u terugnavigeert. Vóór deze update bleef de niet-verzonden opmerking behouden, maar werd de afbeelding verwijderd. Dit is beschikbaar in de sectie van Updates voor doelstellingen en in die van kwesties wanneer het toelaten van de het becommentariëren bètaervaring.

**Updates in realtime en verwijderde opmerkingen in de sectie Updates**

>[!NOTE]
>
>Deze functie is op 19 april 2023 uitgebracht aan Preview en is op 20 april 2023 in productie genomen.

_Updates_

Wanneer iemand nu een opmerking of antwoord toevoegt of een opmerking verwijdert uit het gedeelte Updates, kunt u de nieuwe opmerking of een indicatie zien dat de opmerking in real-time en zonder vertraging is verwijderd. Dit is beschikbaar in de sectie van Updates voor doelstellingen en in die van kwesties wanneer het toelaten van de het becommentariëren bètaervaring.

**Toegangsniveau gewijzigd door systeem zonder een verslag van de verandering**

_Gebruikers_

Het toegangsniveau van een gebruiker kan onvoorspelbaar door het systeem worden veranderd. Wanneer dit voorkomt, is er geen zichtbare update, en de verandering verschijnt niet in het controlelogboek.

+++

+++**Onderhoudsupdate op 17 april 2023**

**Nieuwe opmerkingen buiten het zichtbare schermgebied in het dialoogvenster weergeven [!UICONTROL Updates] een gedeelte met problemen (nieuwe ervaringen met bèta-opmerkingen) en[!UICONTROL Goals]**

_Updates_

We hebben een meldingsbanner toegevoegd voor de [!UICONTROL Updates] om gebruikers te informeren wanneer er nieuwere opmerkingen zijn over een item dat zich mogelijk buiten het zichtbare gebied op het scherm bevindt. Deze update is momenteel beschikbaar in het dialoogvenster [!UICONTROL Updates] gedeelte met doelen en dat van problemen wanneer de nieuwe bètaervaring voor opmerkingen is ingeschakeld voor problemen.

+++

+++**Onderhoudsupdate op 13 april 2023**

**Filters worden niet toegepast op de lijst met aanvragen**

_Verzoeken_

Wanneer een gebruiker een lijst met aanvragen weergeeft waarop een filter is toegepast, bevat de lijst aanvragen die het filter moet uitsluiten.

**Kan niet selecteren [!UICONTROL Default Hour Type] of[!UICONTROL Available Hour Types]**

_Gebruikers_

Wanneer een beheerder een gebruiker bewerkt en probeert een [!UICONTROL Default Hour Type] of [!UICONTROL Available Hour Type], zien ze dat de keuzelijsten voor die velden zijn uitgeschakeld en dat ze geen uurtypen kunnen selecteren.

+++

+++**Onderhoudsupdate op 6 april 2023**

**De vervolgkeuzelijsten worden niet geopend wanneer een gebruiker aan een proefdruk wordt toegevoegd**

_Proefdrukken_

Wanneer een gebruiker een andere gebruiker toevoegt aan een proefdruk in het dialoogvenster [!UICONTROL Proofing Viewer], de &quot;[!UICONTROL Proof role]&quot; en &quot;[!UICONTROL Email alerts]&quot;-dropdowns kunnen niet worden geopend. De gebruiker kan geen proefdrukscherm of e-mailwaarschuwing toewijzen. Dit kan voorkomen wanneer het toevoegen van een gebruiker door een commentaar, of wanneer het delen van de proef met de gebruiker.

+++

## Updates in maart 2023

+++**Onderhoudsupdate op 30 maart 2023**

**Kan proefdrukversie niet wisselen bij weergave van proefdrukversie**

_Proefdrukken_

Wanneer een gebruiker een proef in bekijkt [!UICONTROL Proofing Viewer]en overschakelt naar een andere versie, wordt het vervolgkeuzemenu uitgeschakeld en kan de gebruiker niet terugschakelen naar de oorspronkelijke versie die hij of zij bekeek, of naar een andere versie van de proefdruk.

**504-fout bij het exporteren van rapporten**

_Rapporten_

Wanneer een gebruiker probeert om een rapport met een hoog aantal punten uit te voeren, zien zij een fout 504 en kunnen niet het rapport uitvoeren.

**Bijwerken die namens een gebruiker worden uitgevoerd, worden direct door de gebruiker weergegeven**

_Updates_

Wanneer een beheerder als gebruiker wordt aangemeld en een opmerking maakt, wordt die opmerking direct door de gebruiker weergegeven in plaats van door de beheerder namens de gebruiker.

+++

+++**Onderhoudsupdate op 23 maart 2023**

**[!UICONTROL Summary]de inhoud van het deelvenster is te breed voor het deelvenster**

_Documenten_

Wanneer een gebruiker de [!UICONTROL Summary] voor een document is de inhoud te breed om in het deelvenster te kunnen worden weergegeven. Het deelvenster heeft nu een horizontale schuifbalk en de gebruiker moet horizontaal schuiven om de [!UICONTROL Summary] inhoud van het deelvenster. Dit gebeurt omdat de bestandsnaam van het document niet omloopt. Dit probleem is beperkt tot bestanden waarvan de bestandsnaam een bestandsextensie HTML heeft.

**Nieuw [!UICONTROL Desktop Proofing Viewer] versie**

_Proofing_

Een opmerkingsprobleem corrigeren in het dialoogvenster [!UICONTROL Desktop Proofing Viewe]We hebben een nieuwe versie van de Desktop Proofing Viewer geïmplementeerd.

Gebruikers die al beschikken over de [!UICONTROL Desktop Proofing Viewer] deze update wordt automatisch opgehaald.

Gebruikers kunnen ook handmatig de nieuwste versie verkleinen. Zie voor meer informatie [Installeer de [!UICONTROL Desktop Proofing Viewer]](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html).

* Vorige versie: 2.1.22
* Nieuwe versie: 2.1.23

+++

+++**Onderhoudsupdate op 16 maart 2023**

**De items in de controlelijst worden niet gekopieerd wanneer een kaart wordt gekopieerd**

_Borden_

Bij het kopiëren van een ad-hockaart (gekoppelde kaarten kunnen niet worden gekopieerd) worden de items in de controlelijst niet naar de nieuwe kaart gekopieerd.

**Aangepast veld ontbreekt wanneer uitgave wordt omgezet in project**

_Projecten_

Wanneer een gebruiker een kwestie in een project gebruikend een malplaatje omzet, een douanegebied dat op de kwestie was niet op het project toont. Dit probleem betreft alleen niet-beheerders.

**Aangepaste berichten worden niet weergegeven in e-mailberichten**

_Proefdrukken_

Wanneer een gebruiker een proef deelt en een douanebericht toevoegt, verschijnt dat douanebericht niet in het bericht e-mail aan de ontvanger. Het onderwerp is de proefdruknaam en het bericht komt niet voor in het e-mailbericht.

+++

+++**Onderhoudsupdate op 9 maart 2023**

**Toegangsniveau wordt niet toegewezen wanneer gebruiker opnieuw wordt geactiveerd**

_Gebruikers_

Wanneer een gebruiker een gedeactiveerde gebruiker opnieuw activeert en deze een toegangsniveau in het dialoogvenster [!UICONTROL Reactivate User] in het venster, wordt het vervolgkeuzemenu op toegangsniveau niet gevuld en kan de gebruiker geen toegangsniveau selecteren. Als de gebruiker in het toegangsniveau typt en bewaart, wordt dat toegangsniveau niet toegewezen aan de opnieuw geactiveerde gebruiker.

**Sla het concept van een opmerking op in het dialoogvenster [!DNL Goals] gebied**

_[!DNL Workfront Goals]_

Nu, wanneer u vanaf [!UICONTROL Updates] pagina van een doel terwijl in het midden van het samenstellen van een bericht, wordt het bericht bewaard wanneer u terug navigeert. Vóór deze update zou de niet-verzonden opmerking zijn verwijderd.

+++

+++**Onderhoudsupdate op 2 maart 2023**

**Kan geen kaarten toevoegen bij groepering**

_Borden_

Wanneer een gebruiker een bord weergeeft met een groepering en probeert een kaart toe te voegen, kan de gebruiker alleen de naam van de kaart invoeren. De overige kaartvelden zijn uitgeschakeld, inclusief de [!UICONTROL Save] knop.

Als de gebruiker de groep wijzigt in [!UICONTROL None], blijft de kwestie. De gebruiker moet de groep wijzigen in [!UICONTROL None] en vernieuw vervolgens de pagina om de mogelijkheid om een kaart toe te voegen te herstellen.

**Aangesloten kaarten die niet aan kolommen zijn toegevoegd op basis van status**

_Borden_

Hoewel het kolombeleid wordt toegepast op status, verschijnen de nieuwe verbonden kaarten in de uiterst linkse kolom en niet in de kolom die aan hun status beantwoordt.


**Koppeling maken naar een opmerking omleidt naar [!UICONTROL Details] page**

_Updates_

Wanneer een gebruiker een koppeling volgt naar een opmerking over een object in Workfront, wordt de updatestream kort geladen en wordt de gebruiker omgeleid naar het object [!UICONTROL Details] gebied. Dit kan gebeuren als de gebruiker op de koppeling klikt in een e-mail of de koppeling in zijn browser plakt.

Dit is momenteel alleen van toepassing op objecten Document.

**Afdrukoverzicht wordt niet geladen**

_[!UICONTROL Workfront Proof]_

Wanneer een gebruiker de pagina Afdrukoverzicht probeert te laden, lijkt de pagina te zijn geladen, maar wordt deze nooit geladen.

+++

## Updates in februari 2023

+++**Onderhoudsupdate op 23 februari 2023**

**Koppeling maken naar een opmerking omleidt naar [!UICONTROL Details] page**

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

**[!UICONTROL Story Points]veld toegevoegd aan lijst en rapporten met taken en uitgaven**

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
* &quot;[!UICONTROL Restrict timesheet editing to owners and admins]&quot; in de [!UICONTROL Timesheet & Hour Preferences] gebied van [!UICONTROL Setup] om erop te wijzen dat wanneer gehandicapt, de volgende gebruikers de timesheets kunnen ook uitgeven: gebruikers met administratieve toegang tot timesheets en uren, toegelaten fiatteurs timesheet om tijd uit te geven, en de managers van timesheet eigenaars.

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

* Vorige versie: 2.1.19
* Nieuwe versie: 2.1.20

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

De volgende functies zijn nu beschikbaar in de [!UICONTROL More] menu voor spelden in de productieomgeving:

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

De volgende functies zijn nu beschikbaar in de [!UICONTROL More] menu voor punten, alleen in de voorvertoningsomgeving:

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
* &quot;Beperk timesheet uitgeven tot eigenaars en beheerders&quot;in het gebied van de Voorkeur van de Tijdopmaak &amp; van het Uur van Opstelling om erop te wijzen dat wanneer gehandicapt, de volgende gebruikers ook timesheets kunnen uitgeven: gebruikers met administratieve toegang tot timesheets en uren, timeesheet fiatteurs toegestaan om tijd uit te geven, en de managers van timesheet eigenaars.

De functionaliteit van deze instellingen is niet gewijzigd en alleen de informatiepictogrammen zijn toegevoegd om het bereik van de instellingen helderder te maken.

+++

## Vorige onderhoudsupdates

Informatie over vorige onderhoudsupdates is hier beschikbaar:

* [[!DNL Workfront] Archief met onderhoudsupdates - 2022](2022-updates.md)
* [[!DNL Workfront] Archief met onderhoudsupdates - 2021](2021-updates.md)
