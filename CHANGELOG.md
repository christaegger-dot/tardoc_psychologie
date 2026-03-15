# Changelog

Alle relevanten Änderungen an diesem Projekt werden in dieser Datei dokumentiert.

## [1.1.1] - 2026-03-15
### Geändert
- **Fix:** Druckdatei-Links auf relative Pfade mit `.html`-Extension umgestellt (funktioniert nun auch in Deploy Previews und lokal).
- **Inhalt:** EA.05.0070-Beschreibung in der Positionstabelle um Angehörigen-Hinweis ergänzt (KG-Führung S.1).
- **Dokumentation:** CHANGELOG bereinigt, `[Unreleased]`-Block geleert.

## [1.1.0] - 2026-03-15
### Hinzugefügt
- **Quick-Action-Cards:** Neues UI-Element für den schnellen Einstieg über typische Alltagsszenarien.
- **Quick-Tools-Bar:** Sticky-Toolbar mit Suchfunktion und Links zu den Druckansichten.

### Geändert
- **Code-Bereinigung:** CSS-Variablen korrigiert (En-Dash zu `--`), Markdown-Artefakte entfernt.
- **Darstellung:** Doppeltes "240 Min" in der 4h-Box entfernt.
- **Konsistenz:** `EA.05.`-Präfix in der Telefon-Tabelle ergänzt.
- **Fix:** Quick-Card "Therapie-/Diagnostikplanung" navigiert zu Abschnitt 10 (LAP-Topf) statt 5 (Positionen).
- **Fix:** Quick-Card "Patient-E-Mail" navigiert zu Abschnitt 7 (Telefon) statt 5 (Positionen).
- **Fix:** EA00-Schreibweise in Quick-Cards korrigiert (`EA.00.0110`, `EA.00.0090`).
- **Druckdateien:** Explizite Seitenumbrüche in Verlaufseintrag und Positionen gesetzt.
- **Druckdateien:** Badge-Texte im Verlaufseintrag gekürzt und font-size reduziert.

## [1.0.0] - 2026-03-15
### Hinzugefügt
- Initiale Version der Web-Applikation.
- 14 inhaltliche Abschnitte (Zwei Ebenen, Grundregeln, Limits, Entscheidungsbaum, Positionen, Diagnostik, Telefon/Mail, Krise A/B, Exposition, LAP-Topf, Berichte/IV, Überbrückung, Szenarien, 11-Punkte).
- Drei separate Druckansichten (Spickzettel, Positionen, Verlaufseintrag).
- Intelligente Suchfunktion.
- Mobile-optimierte Navigation und Accordions.
