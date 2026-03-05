# Werkboek .NET MAUI – Leerjaar 3 Software Development

> **ROC van Twente – Opleiding Software Development – Leerjaar 3**
> Werkboek versie 4.0 (zie `Werkboek MAUI v4.0-1.pdf`)

---

## Inhoudsopgave

1. [Benodigdheden](#benodigdheden)
2. [Overzicht van de hoofdstukken](#overzicht-van-de-hoofdstukken)
3. [Inleveropdrachten](#inleveropdrachten)
4. [Eindproject](#eindproject)
5. [Hoe in te leveren](#hoe-in-te-leveren)

---

## Benodigdheden

Zorg dat je het volgende hebt geïnstalleerd voordat je begint:

| Software | Details |
|---|---|
| **Visual Studio 2022** | Installeer de workloads: `.NET desktop development` en `Mobile development with .NET` |
| **.NET SDK** | Wordt automatisch beheerd door Visual Studio |
| **Android SDK & Emulator** | Te installeren via Visual Studio (bijv. Pixel 5 emulator) |
| **Windows 10 of hoger** | Vereist voor Windows-app-ontwikkeling |

**Basiskennis vereist:** C# en XAML.

---

## Overzicht van de hoofdstukken

### Hoofdstuk 1 – Inleiding tot .NET MAUI (pagina 6)
- Wat is .NET MAUI en waarom gebruiken we het?
- Cross-platform (Windows, Android, iOS, macOS) met één codebase.
- Vergelijkbare tools: Flutter, React Native.
- **Oefeningen** aan het einde van het hoofdstuk uitvoeren.

### Hoofdstuk 2 – Configuratie en Installatie (pagina 10)
- Visual Studio 2022 installeren met de juiste workloads.
- .NET SDK installeren.
- Android SDK en emulator configureren.
- Windows-ontwikkelomgeving instellen.
- **Oefeningen** aan het einde van het hoofdstuk uitvoeren.

### Hoofdstuk 3 – Je eerste .NET MAUI Applicatie (pagina 14)
- Een nieuw .NET MAUI project aanmaken in Visual Studio.
- Projectstructuur verkennen (bijv. `MauiProgram.cs`, `MainPage.xaml`).
- De standaard "Hello World"-app aanpassen.
- Applicatie builden en uitvoeren op emulator of apparaat.
- **Oefeningen** aan het einde van het hoofdstuk uitvoeren.
- ➡️ **Inleveropdracht 1** (zie hieronder)

### Hoofdstuk 4 – Werken met Layouts (pagina 21)
- `StackLayout` (horizontaal en verticaal)
- `Grid` (rijen en kolommen)
- `AbsoluteLayout` (absolute positionering)
- `FlexLayout` (vergelijkbaar met CSS Flexbox)
- **Oefeningen + video tutorials** aan het einde van het hoofdstuk uitvoeren.

### Hoofdstuk 5 – Toevoegen van Functionaliteit (pagina 24)
- Werken met controls: `Label`, `Button`, `Entry`, `Slider`, etc.
- Data Binding (koppelen van UI aan data).
- Gebruikersinvoer verwerken.
- **Oefeningen + video tutorials** aan het einde van het hoofdstuk uitvoeren.
- ➡️ **Inleveropdracht 2, 3 en 4** (zie hieronder)

### Hoofdstuk 6 – Geavanceerde Functionaliteiten (pagina 35)
- Navigatie tussen pagina's (`NavigationPage`).
- Ingebouwde apparaatfuncties (GPS, camera).
- Animaties en visuele effecten (fade-in, slide, pulserende knoppen).
- **Oefeningen** aan het einde van het hoofdstuk uitvoeren.
- ➡️ **Inleveropdracht 5** (zie hieronder)

### Hoofdstuk 7 – Verschillende Soorten Pagina's (pagina 41)
- `ContentPage` – basis pagina
- `FlyoutPage` – navigatiemenu (hamburger menu)
- `TabbedPage` – tabbladen
- `NavigationPage` – stack navigatie
- **Oefeningen** aan het einde van het hoofdstuk uitvoeren.
- ➡️ **Inleveropdracht 6** (zie hieronder)

### Hoofdstuk 8 – Externe Data en API's (pagina 50)
- Data ophalen van een Web-API via `HttpClient`.
- Werken met JSON data (deserialiseren met `System.Text.Json` of `Newtonsoft.Json`).
- Fouten en netwerkproblemen afhandelen (try/catch, connectivity check).
- **Oefeningen** aan het einde van het hoofdstuk uitvoeren.
- ➡️ **Inleveropdracht 7** (zie hieronder)

### Hoofdstuk 9 – Internationale Ondersteuning en Lokalisatie (pagina 60)
- Resourcebestanden aanmaken (`Resources.resx`, `Resources.nl.resx`).
- Applicatie configureren om automatisch de systeemtaal te gebruiken.
- Dynamisch wisselen tussen talen zonder herstart.
- **Oefeningen** aan het einde van het hoofdstuk uitvoeren.
- ➡️ **Inleveropdracht 8** (zie hieronder)

### Hoofdstuk 10 – Integratie van Externe Bibliotheken (pagina 67)
- NuGet-pakketten installeren via Visual Studio of `.NET CLI`.
- SQLite integreren voor lokale dataopslag.
- Data Access Layer (DAL) opzetten voor CRUD-operaties.
- **Oefeningen** aan het einde van het hoofdstuk uitvoeren.
- ➡️ **Inleveropdracht 9** (zie hieronder)

### Hoofdstuk 11 – Push Notifications (pagina 75)
- Firebase Cloud Messaging (FCM) configureren.
- Pushnotificaties ontvangen op Android (voorgrond én achtergrond).
- Pushnotificaties ontvangen op Windows.
- Gebruikersinteractie met notificaties (deeplinks naar content).
- **Oefeningen** aan het einde van het hoofdstuk uitvoeren.
- ➡️ **Inleveropdracht 10** (zie hieronder)

### Hoofdstuk 12 – Eindproject (pagina 82)
- ➡️ Zie [Eindproject](#eindproject) hieronder.

---

## Inleveropdrachten

### Inleveropdracht 1 – Leren Rekenen App (na hoofdstuk 3)

Maak een app waarmee kinderen leren rekenen met **plus, min en maal**.

**Functionele eisen:**
- Genereer twee random getallen tussen 1 en 9.
- Kies een random berekening (plus, min of maal) en toon de berekening + uitkomst.
- Laat AI een toepasselijke afbeelding genereren voor je app.
- Achtergrond-/tekstkleuren per rekensoort:
  - Plus: achtergrond **rood**, tekst **geel**
  - Min: achtergrond **blauw**, tekst **wit**
  - Maal: achtergrond **geel**, tekst **rood**
- Tekstgrootte: 24, horizontaal gecentreerd.
- Koptekst van de app: **"Leren rekenen"**.
- Knop waarmee een nieuwe som gegenereerd kan worden.

📤 **Inleveren:** Laat werkend zien aan je docent. Maak screenshots en lever een Word-document in via Teams onder *Inleveropdracht 1*.

---

### Inleveropdracht 2 – Tekststijlen met Sliders (na hoofdstuk 5)

Maak een app die jouw naam toont en waarbij de stijl instelbaar is via sliders.

**Functionele eisen (M = Must):**
- Slider **Angle**: roteer de tekst van 0° tot 360° (standaard: 0). (M)
- Slider **Fontsize**: stel de tekstgrootte in van 10 tot 40 (standaard: 24). (M)
- Sliders **Red, Green, Blue**: stel de tekstkleur in (standaard: alle 0). (M)
- Koptekst van de app: **"Exercise 1"**. (M)
- De tekst is jouw eigen naam. (M)

**Niet-functionele eisen (S = Should):**
- De volledige app is nog steeds zichtbaar als het scherm draait (landscape). (S)

📤 **Inleveren:** Laat werkend zien aan je docent. Maak screenshots en lever een Word-document in via Teams onder *Inleveropdracht 1*.

---

### Inleveropdracht 3 – Stagepagina (na hoofdstuk 5)

Maak een app die informatie toont over **jouw eerste stageperiode**.

**Functionele eisen:**
- Koptekst: `Stage van [jouw naam] bij [stagebedrijf]`
- Achtergrondkleur gebaseerd op het logo van jouw stagebedrijf.
- Gebruik een ander lettertype dan het standaard lettertype.
- Toon de volgende informatie:
  - Afbeelding/logo van het stagebedrijf.
  - Naam van het stagebedrijf (fontsize 36, bold).
  - Adresgegevens (fontsize 24, italic): straat, huisnummer, postcode, plaats, website als hyperlink.
  - Minimaal 3 knoppen naast elkaar met technieken/talen waarmee je hebt gewerkt – elke knop werkt als hyperlink naar een uitlegpagina (bijv. W3Schools).
  - Een scrollvenster met jouw persoonlijke ervaringen tijdens de stage.
  - Een knop die in een popup jouw naam, klas en woonplaats toont.

📤 **Inleveren:** Laat werkend zien aan je docent. Maak screenshots en lever een Word-document in via Teams onder *Inleveropdracht 2*.

---

### Inleveropdracht 4 – Rekenmachine (na hoofdstuk 5)

Maak een eenvoudige rekenmachine.

**Functionele eisen:**
1. Gebruiker voert 2 getallen in.
2. Vijf knoppen voor: **Som** (+), **Verschil** (−), **Product** (×), **Quotiënt** (÷), **Restant** (%).
3. Uitkomst getoond op 2 decimalen.
4. Bij quotiënt of restant: toon een popup-foutmelding als getal 2 gelijk is aan 0.

📤 **Inleveren:** Laat werkend zien aan je docent. Lever een screenshot in via Teams onder *Inleveropdracht 3*.

---

### Inleveropdracht 5 – Navigatie, Apparaatfuncties & Animaties (na hoofdstuk 6)

Bouw een app die navigatie, apparaatfuncties en animaties combineert.

**Functionele eisen:**
1. **Navigatie:** Minimaal 3 pagina's (`MainPage`, `SettingsPage`, `InfoPage`) via `NavigationPage`.
2. **Apparaatfuncties:**
   - Op de instellingenpagina: huidige GPS-locatie ophalen en weergeven.
   - Knop om de camera te openen; toon de foto op de informatiepagina.
3. **Animaties:**
   - Fade-in effect bij het laden van de hoofdpagina of een pulserende knop.
   - Overgangsanimatie (slide of fade) bij navigatie tussen pagina's.

📤 **Inleveren:** Laat werkend zien aan je docent. Lever de broncode + screenshots in via Teams onder *Inleveropdracht 5*.

---

### Inleveropdracht 6 – Reisplanner App (na hoofdstuk 7)

Ontwikkel een **reisplanner-app** met meerdere paginatypes.

**Functionele eisen:**
1. `ContentPage` – Startscherm met welkomstboodschap en acties (bijv. "Reis Plannen").
2. `FlyoutPage` – Navigatiemenu voor "Mijn Reizen", "Reis Plannen" en "Instellingen".
3. `TabbedPage` – Tabbladen voor "Aankomende Reizen", "Afgeronde Reizen", "Favoriete Reizen".
4. `NavigationPage` – Detailscherm voor specifieke reizen.

**Op te leveren:**
1. Broncode van de applicatie.
2. Korte beschrijving van de structuur en hoe je de paginatypes hebt gecombineerd.
3. Screenshots of een korte video van de navigatie.

📤 **Inleveren:** Via Teams onder *Inleveropdracht 6*.

---

### Inleveropdracht 7 – RDW API App (na hoofdstuk 8)

Maak een app die data ophaalt van de **openbare RDW API**. Kies één van de volgende keuzeopdrachten:

#### Keuzeopdracht 7.1 – Parkeerlocaties in Hengelo *(max. 30/50 punten)*
- Haal parkeerlocaties op via: `https://opendata.rdw.nl/resource/ygq4-hh5q.json`
- Toon per locatie: adres (straat + huisnummer), postcode, e-mailadres.

#### Keuzeopdracht 7.2 – Kentekenopzoeker *(max. 30/50 punten)*
- Gebruiker voert een kenteken in; haal voertuiginfo op via: `https://opendata.rdw.nl/resource/m9d7-ebf2.json`
- Toon: kenteken, soort voertuig, merk, type, datum tenaamstelling, vervaldatum APK, kleur, massa rijklaar, aantal deuren, aantal wielen, lengte, breedte, catalogusprijs.

#### Keuzeopdracht 7.3 – Top 100 meest voorkomende auto's op snelwegen *(max. 40/50 punten)*
- Toon een aflopend gesorteerd overzicht van de 100 meest voorkomende merken/modellen van personenauto's op Nederlandse snelwegen.
- Toon: positie, merk, model, aantal.

#### Keuzeopdracht 7.4 – Zoeken op merk, bouwjaar en maand *(max. 50/50 punten)*
- Toon een lijst met alle merken personenauto's.
- Gebruiker kiest merk + bouwjaar + maand; toon alle bijbehorende kentekens.
- Gebruiker selecteert een kenteken; toon alle detailinformatie (zie 7.2).

📤 **Inleveren:** Via Teams onder *Inleveropdracht 7*.

---

### Inleveropdracht 8 – Lokalisatie App (na hoofdstuk 9)

Ontwikkel een **takenbeheer-app** met ondersteuning voor Nederlands en Engels.

**Functionele eisen:**
1. Resourcebestanden aanmaken: `Resources.resx` (Engels) en `Resources.nl.resx` (Nederlands).
2. App kiest automatisch de taal op basis van de systeeminstellingen.
3. Dynamisch wisselen tussen talen **zonder herstart** van de app.
4. Alle knoppen, labels en berichten zijn in beide talen beschikbaar.

**Op te leveren:**
1. Broncode inclusief resourcebestanden.
2. Korte beschrijving van de implementatie en uitdagingen.
3. Screenshots of video die de taalwisseling demonstreert.

📤 **Inleveren:** Via Teams onder *Inleveropdracht 8*.

---

### Inleveropdracht 9 – Notitie App met Externe Bibliotheek (na hoofdstuk 10)

Ontwikkel een **notitie-app** met externe bibliotheek voor dataopslag.

**Functionele eisen:**
1. Installeer **SQLite** (NuGet) voor lokale opslag.
2. Implementeer een Data Access Layer (DAL) met CRUD-operaties: aanmaken, lezen, bewerken, verwijderen van notities.
3. Gebruikers kunnen notities doorzoeken.
4. *(Optioneel)* Tweede bibliotheek voor synchronisatie met een cloudservice.

**Op te leveren:**
1. Broncode inclusief bibliotheekintegratie.
2. Korte beschrijving: welke bibliotheek, waarom, hoe geïmplementeerd.
3. Screenshots of video van de belangrijkste functionaliteiten.

📤 **Inleveren:** Via Teams onder *Inleveropdracht 9*.

---

### Inleveropdracht 10 – Pushnotificaties (na hoofdstuk 11)

Ontwikkel een **nieuwsapp** met pushnotificaties via Firebase Cloud Messaging (FCM).

**Functionele eisen:**
1. **FCM configureren:** Maak een Firebase-project aan en koppel het aan de MAUI-app.
2. **Android:** Ontvang notificaties zowel in voor- als achtergrond; toon in notificatiecentrum.
3. **Windows:** Ontvang notificaties in voor- en achtergrond; toon in Windows notificatiecentrum.
4. **Gebruikersinteractie:** Klikken op een notificatie navigeert naar de juiste nieuwssectie.
5. *(Optioneel)* Instellingenpagina waar gebruikers hun notificatievoorkeuren kunnen instellen.

**Op te leveren:**
1. Broncode inclusief volledige FCM-implementatie voor Android én Windows.
2. Beschrijving van de implementatiestappen en uitdagingen.
3. Screenshots of video.

📤 **Inleveren:** Via Teams onder *Inleveropdracht 10*.

---

## Eindproject

### Doel
Ontwikkel een **complete .NET MAUI-applicatie** die zowel op **Windows als Android** werkt en gebruik maakt van alles wat je hebt geleerd.

### Verplichte functies
- Meerdere pagina's en navigatie
- Data binding en MVVM-patroon
- Lokale gegevensopslag (database)
- Toegang tot apparaatfuncties (camera of GPS)
- Netwerkcommunicatie (API-aanroepen)
- Pushnotificaties

### Stappen
1. **Kies een casus** – Voorbeelden: takenbeheer-app, fitness-tracker, receptenboek, evenementenplanner.
2. **Maak een projectplan** – Beschrijf: overzicht, doelgroep, functionele eisen, technische eisen, wireframes/schetsen.
3. **Ontwikkel de applicatie:**
   - Stel de ontwikkelomgeving in voor Windows én Android.
   - Implementeer de basisstructuur, navigatie, data binding, MVVM, dataopslag, apparaatfuncties, API-aanroepen en pushnotificaties.
4. **Testen & debuggen** – Test uitvoerig op zowel Windows als Android.
5. **Documentatie** – Schrijf een gebruikershandleiding en technische documentatie.
6. **Presentatie** – Bereid een demo voor en leg uit welke technieken je hebt gebruikt.

### Beoordelingscriteria

| Criterium | Uitstekend (5) | Goed (4) | Voldoende (3) | Onvoldoende (2) | Slecht (1) |
|---|---|---|---|---|---|
| **Projectplan** | Zeer gedetailleerd en doordacht | Duidelijk en goed georganiseerd | Basisbeschrijving | Onvoldoende | Slecht/niet ingeleverd |
| **Functionaliteit** | Alles werkt foutloos | Meeste functies werken | Enkele functies werken | Veel functies werken niet | Meeste werken niet |
| **Navigatie & UI** | Uitstekende UI/UX, intuïtief | Goede UI/UX | Redelijke UI/UX | Slechte UI/UX | Zeer slecht/verwarrend |
| **Data Binding & MVVM** | Correct en volledig | Goed, kleine fouten | Basis, meerdere fouten | Slechte implementatie | Niet geïmplementeerd |
| **Gegevensopslag** | Volledig functioneel | Functioneel, kleine problemen | Basisfunctionaliteit | Onvoldoende | Niet geïmplementeerd |
| **Apparaatfuncties** | Volledig en foutloos | Goed, enkele fouten | Basis, meerdere fouten | Slecht/incompleet | Niet geïmplementeerd |

---

## Hoe in te leveren

- Lever opdrachten in via **Microsoft Teams** onder de bijbehorende opdrachtnaam.
- Voor de meeste opdrachten geldt: **laat de werkende app zien aan je docent** en lever daarna screenshots of broncode in.
- Zorg altijd dat je **je eigen code kunt uitleggen**.
