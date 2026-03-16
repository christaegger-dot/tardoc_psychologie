# Tarif-Kompass 2026 — Audit-Fixes Changelog
## Version 1.3.0 · 16.03.2026

### Geänderte Dateien
- `index.html` (Hauptseite)
- `shared-print.css` (gemeinsame Druckstyles)
- `files/positionen-psych-print.html`
- `files/entscheidungsbaum-psych-print.html`
- `files/spickzettel-psych-print.html`

### Strukturelle Änderung
- 13 statt 14 Sektionen: Überbrückungsleistungen als Hinweisbox in Sektion 8 integriert.

---

### Alle 19 Befunde erledigt

#### KRITISCH (5/5)
- **K1** Headings: div → h2 (13 Sektionen). Screenreader-Navigation funktioniert.
- **K2** Skip-Link eingefügt, bei Tab-Focus sichtbar.
- **K3** Inline-Styles: 118 → 46 (72 extrahiert in 30+ Utility-Klassen).
- **K4** Print-Seitenumbruch: .sheet auf min-height + overflow: visible.
- **K5** Startseite: Sidebar versteckt (Toggle), Sektionen geschlossen, Filter nur bei Suchfokus.

#### HOCH (5/5)
- **H1** Redundanz auf 2 Stellen: Positions-Beschreibungen gekürzt + Verweise auf Detailsektionen.
- **H2** S/W-Drucktauglichkeit: Print-Fallback für Kategorie-Pills.
- **H3** EA.05.0120 als Sonderfall mit separatem Budget + Rücksprache-Hinweis.
- **H4** Druckdateien nur noch an 1 Stelle (Quick-Tools-Bar).
- **H5** Alle Sektionen geschlossen.

#### MITTEL (5/5)
- **M1** Popover: ×-Button, breiter, Click-outside mit Filter-Reset.
- **M2** Spickzettel: 10-Punkte-Texte 6.5pt → 7pt.
- **M3** Entscheidungsbaum-Karte an Position 1, Vollbreite.
- **M4** Szenario 11: Abgrenzungshilfe-Box mit Label.
- **M5** Überbrückungsleistungen in Sektion 8 integriert. 14 → 13 Sektionen.

#### NIEDRIG (4/4)
- **N1** Suchfeld: Placeholder gekürzt, min-width 160px.
- **N2** Entscheidungsbaum-Drucktitel: white-space: nowrap.
- **N3** CSS-Variablen --teal/--purple entfernt.
- **N4** Mobile-Tooltips: hinter «mehr…»-Toggle versteckt (Tap to expand).

#### BEFUND C
- 12 dekorative <strong>-Tags entfernt (68 → 56). Emojis beibehalten.

### Verbleibend
- 46 Inline-Styles (Einzelfälle, nicht sinnvoll extrahierbar)
