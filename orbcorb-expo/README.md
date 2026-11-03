# OrbCorb Expo website

Simpele statische website (HTML + CSS) voor de OrbCorb Expo, 13 november 13:00-17:00, TTH 06B16.

## Structuur
- `index.html` - homepagina met kaarten van de 6 groepen
- `groepen/groep-1.html` t/m `groep-6.html` - projectpagina per groepje
- `aanmelden.html` - aanmeldformulier (Google Form)
- `css/style.css` - alle opmaak; kleuren staan bovenaan in `:root`
- `images/` - foto's (nu nog placeholders `groep-1.svg` ...)

## Een groepspagina invullen
Open bijvoorbeeld `groepen/groep-1.html` en zoek op `HIER INVULLEN`:
1. **Titel:** verander de tekst in `<h1>`.
2. **Foto:** zet je foto in `images/` en pas `src="../images/groep-1.svg"` aan naar bijv. `../images/groep-1.jpg`.
3. **Beschrijving:** vervang de tekst in de `<p>`-regels.

Doe dezelfde titel, foto en korte tekst ook in de kaart op `index.html`.

## Aanmelden (Google Form)
1. Maak een Google Form met twee vragen: **Naam** en **Aantal personen**.
2. Klik op Verzenden > tabblad `<>` (insluiten) en kopieer de `src="..."`-link.
3. Plak die in `aanmelden.html` in plaats van `HIER_JE_GOOGLE_FORM_EMBED_LINK`.
4. Verwijder het oranje bericht (`class="notice"`).
Antwoorden komen in Google Forms/Sheets.

## Op GitHub zetten
1. Maak een repo op github.com en upload alle bestanden (Add file > Upload files).
2. Ga naar Settings > Pages > Source: `main` branch, map `/ (root)` > Save.
3. Na een minuutje staat de site op `https://<gebruikersnaam>.github.io/<repo>/`.

## Lokaal bekijken
Dubbelklik op `index.html`.
