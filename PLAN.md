# Sportshop 111 – Website-Prototyp: Auftrag & Plan

Stand: 26.11.2026 · Status: **wartet auf Freigabe** (noch nichts umgesetzt)

## 1. Finaler Auftrag

> Baue einen klickbaren, mehrseitigen Prototyp einer **Schaufenster-Website mit Shop-Optik** für den
> Sportshop 111 in Nürnberg-Mögeldorf. Stilprinzip: die TWOTWO-Referenz (Monochrom + genau ein Akzent,
> zwei Radien 16px/50px, Linien statt Schatten, Regular-Schnitt statt Fett), aber mit der Identität des
> Ladens (Gelbgrün aus dem Logo als Akzent) und ohne TWOTWO 1:1 zu kopieren.
>
> **Regeln**
> - Keine Kaufabwicklung. Produktkarten mit Preis, Button führt zu „Im Laden reservieren“ (Anruf / E-Mail).
> - Tennis, Padel und Hockey gleichwertig; Padel (24/7-Automat) zusätzlich als Erwähnung auf der Startseite.
> - Echte Fakten nur aus sportshop111.de. Alles Unbekannte sichtbar als **[Platzhalter]** markiert.
> - Produkte: echte Modellnamen der geführten Marken, **Preis und Foto als Platzhalter** („ab –,– €“, „Foto folgt“).
> - Keine Stock- oder KI-Bilder, keine erfundenen Bewertungen, Zahlen oder Werbefloskeln, keine Emojis.
> - Logo: neue typografische Wortmarke „SPORTSHOP 111“ in Ladenfarben, gekennzeichnet als Vorschlag.
> - Technik: statisches HTML/CSS, kein CMS, keine Datenbank, kein jQuery, keine Drittanbieter-Skripte.
> - Schriften frei lizenziert und **lokal gehostet** (Inter Tight + IBM Plex Mono), kein Google-CDN.
> - Keine Cookies, kein Tracking, keine eingebettete Karte (nur Link) → kein Cookie-Banner nötig.
> - Security-Header: CSP, HSTS, X-Content-Type-Options, Referrer-Policy, Permissions-Policy, frame-ancestors.
> - Mobile first; Öffnungszeiten, Anruf- und Routen-Button ohne Scrollen erreichbar.
> - Kontrast WCAG AA; Gelbgrün nie als Textfarbe auf Weiß.
> - Impressum und Datenschutz als markierte Platzhalter-Seiten.
>
> **Reihenfolge**
> 1. Fakten sammeln ✅
> 2. Plan & Seitenstruktur zeigen → **STOPP, Freigabe abwarten** ⬅ wir sind hier
> 3. Vier unterschiedliche Design-Richtungen der Startseite → Auswahl
> 4. Gewählte Richtung auf alle Seiten ausbauen
> 5. Prüfung durch einen unabhängigen Agenten gegen diese Regeln → erst dann Übergabe (Link + Repo)

## 2. Seitenstruktur

| Seite | Inhalt |
|---|---|
| Start | Hero, Infoleiste (heute geöffnet? / Anruf / Route), drei gleichwertige Sport-Kacheln, Padel-Hinweis 24/7-Automat, Besaitung-Teaser, Marken, Kontakt-Block |
| Tennis | Schläger (Wilson, Yonex, Babolat), Testschläger kostenlos, Kinderschläger ab 3 J., Kleidung & Schuhe (Babolat, Head), Zubehör, Bälle; Produktkarten |
| Padel | Schläger, Bälle, Griffbänder, Leihschläger, 24/7-Automat, Link zur Platzbuchung NHTC; Produktkarten |
| Hockey | Ansprechpartnerinnen Susa & Barbara, Sortiment als [Platzhalter] |
| Besaitung | Babolat Stringing Team seit 2011, WTA-Turnier Nürnberg, 1. FCN, Sensor Expert Dual, 60+ Saiten, eigene Saite mitbringen, Rollenware, Vielbesaiter-Konditionen |
| Team | Jens, Jochen, Susa & Barbara – Texte von der alten Seite, Fotos als Platzhalter |
| Kontakt | Adresse, Telefon, Fax, E-Mail, Öffnungszeiten, Termin außerhalb der Zeiten, Routen-Link |
| Impressum / Datenschutz | Platzhalter mit Hinweis „vom Inhaber auszufüllen / rechtlich prüfen lassen“ |

## 3. Gesicherte Fakten (Quelle: sportshop111.de, abgerufen 26.11.2026)

- Sportshop 111 · Siedlerstraße 111 · 90480 Nürnberg · Tel. 0911 5434890 · Fax 0911 5434891
- E-Mail: sportshop111@gmx.de, sportshop111@nhtc.de
- Seit 2007 Tennis- und Hockeyspezialist in Nürnberg-Mögeldorf
- Öffnungszeiten: Mo geschlossen · Di–Fr 16–19 Uhr · Sa 10–12 Uhr (April–Oktober), Nov–März Sa geschlossen · So geschlossen. Nach Vereinbarung auch außerhalb.
- Termine: Tennis Jens Gugel 0177 5514256 · Hockey Susa Wesley 0178 5441545
- Team: Jens (Tennis seit 1977, Bayernliga Herren 40, Mitinhaber), Jochen (Tennis seit 1982, Besaiter seit 1991, Mitinhaber), Susa & Barbara (Hockey)
- Babolat Stringing Team seit 2011; WTA-Turnier Nürnberg (Nürnberger Versicherungscup); Bundesliga 1. FCN seit 2011; Babolat Sensor Expert Dual
- Saiten: über 60; Hersteller Babolat, Wilson, Head, Luxilon, Polystar, Kirschbaum
- Bälle: Babolat, Head, Dunlop, Wilson; Angebote für Turnierbälle (Medenrunde, LK-Turnier)
- Padel: 4 Courts im NHTC, Schläger/Bälle/Griffbänder, Leihschläger gegen Gebühr, 24/7-Padelautomat vor dem Shop
- Logo-Farben: Gelbgrün #b9c300, Petrol #004b6b, Orange #dc7605

**Offen / vom Inhaber zu bestätigen:** aktuelle Öffnungszeiten, Hockey-Sortiment, Preise, Fotos, Impressum-Angaben,
ob Spielerinnen-Namen (WTA) genannt werden dürfen.

## 4. Vier Design-Richtungen (Schritt 3)

| | Name | Idee | Farben |
|---|---|---|---|
| A | **Court** | Am nächsten an TWOTWO: Weiß, schwarze Haarlinien, große 72px-Headline im Akzent über Foto-Platzhalter | Schwarz/Weiß + Gelbgrün |
| B | **Petrol** | Ladenfarben im System: Petrol ersetzt Schwarz für Header-Band und Footer | Petrol/Weiß + Gelbgrün |
| C | **Saitenbild** | Editoriales Raster aus Haarlinien wie ein Saitenbett, Infos (Öffnungszeiten) direkt im Hero, Concrete-Grau-Flächen | Schwarz/Weiß/Concrete + Gelbgrün |
| D | **Werkstatt** | Besaitungs-Kompetenz im Vordergrund, technische Mono-Typo für Daten (kg, Saite, Maschine), Tag-Optik | Schwarz/Weiß + Gelbgrün, Petrol im Footer |

## 5. Sicherheit (Checkliste)

- Nur statische Dateien, keine serverseitige Logik, kein Formular (Kontakt via `tel:` / `mailto:`)
- Keine externen Requests beim Seitenaufruf (Fonts lokal, keine Karten-/Video-Embeds)
- CSP `default-src 'self'`, kein Inline-Skript; Header als `_headers` (Netlify/Cloudflare) **und** `.htaccess` (Apache)
- Externe Links mit `rel="noopener noreferrer"`
- Kein Cookie, kein LocalStorage für Tracking
