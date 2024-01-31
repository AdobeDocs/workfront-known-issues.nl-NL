---
title: Workfront-onderhoudsupdates
description: Onderhoudsupdates voor [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: b5a918850060b8fc02b8a9c978c4e2a4bc7a8dc4
workflow-type: tm+mt
source-wordcount: '1290'
ht-degree: 0%

---

# [!DNL Workfront] Onderhoudsupdates

De volgende onderhoudsupdates zijn uitgevoerd in 2024.

>[!NOTE]
>
>Deze updates bevatten ook andere kleine of minder duidelijke foutoplossingen. [!DNL Workfront] Ondersteuning geeft een melding wanneer een probleem dat u hebt verzonden, is opgelost.

Voor onderhoudsupdates vóór 2023, zie [Vorige onderhoudsupdates](#previous-maintenance-updates)

## Updates in februari 2024

+++**(Geplande) onderhoudsupdate op 1 februari 2024**

### (Geplande) onderhoudsupdate op 1 februari 2024

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
