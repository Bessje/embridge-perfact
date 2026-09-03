# Embridge × Perfact — Samen sterker in de energietransitie

Eenpagina-website over de samenwerking tussen **Embridge** en **Perfact** in de
energietransitie. Gemaakt om te delen in gesprekken en presentaties.

**Live:** via GitHub Pages op deze repo.

## Inhoud

| Bestand | Wat |
|---|---|
| `index.html` | de hele site — één bestand, geen build, geen dependencies |
| `images/` | logo's van Embridge en Perfact plus de projectfoto's |

De site is opgebouwd uit vijf secties: de opgave, wie wij zijn, de gezamenlijke
propositie, wat het oplevert, en de contactsectie.

## Aanpassen

Open `index.html` in een editor en push naar `main` — Pages publiceert
automatisch. Lokaal bekijken kan met elke statische server; open het niet via
`file://`, want dan werkt de Content-Security-Policy niet zoals live.

Let op de twee `<meta>`-regels bovenaan: een strikte Content-Security-Policy en
een referrer-policy. Voeg je een externe bron toe (font, script, afbeelding),
dan moet de CSP daar mee uitgebreid worden, anders blokkeert de browser hem
zonder zichtbare foutmelding.

## Huisstijl

Embridge gebruikt blauw `#004B98` met teal `#69BEBC`. Perfact gebruikt grijs
`#53565A` met geel `#EFDF00`. Die twee zijn bewust gescheiden gehouden —
Embridge is geen onderdeel van Perfact.

## Historie

De QR-code in de contactsectie is vervangen door de logo's van beide partijen
(commit `73abb1b`). De losse QR-bestanden `qr-badge.html`, `qr-flyer.html` en
`QR-Embridge-Perfact.png` zijn daarmee overbodig geworden en verwijderd.

Deze map was lange tijd ook een verzamelmap voor andere projecten. Die zijn
verhuisd naar eigen repo's; zie `MIGRATIE.md` in de werkmap (niet in git).
