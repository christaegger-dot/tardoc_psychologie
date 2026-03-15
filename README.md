# Tarif-Kompass 2026 · Psychologinnen KJPP

Eine interaktive, mobile-optimierte Web-Applikation zur schnellen Orientierung im TARDOC (Kapitel EA.05) für Psychologinnen mit Psychotherapieausbildung in der KJPP-Tagesklinik.

**Live-Version:** [tardoc-psychologiekjpp.netlify.app](https://tardoc-psychologiekjpp.netlify.app/)

## Features

- **Quick-Action-Cards:** Schneller Einstieg über typische Alltagsszenarien ("Was will ich tun?").
- **Zwei-Ebenen-System:** Klare Trennung zwischen öffentlichen EA.05-Tarifziffern und internen KJPP-Psychologen-Codes (PA/PE/PK).
- **Intelligente Suche:** Findet Codes, Aliase und Begriffe in Echtzeit.
- **Mobile-First:** Sticky-Navigation, Accordions und touch-optimierte Elemente für den Einsatz auf dem Smartphone im Klinikalltag.
- **Druckansichten:** Drei separate, auf A4 optimierte Druckansichten (Spickzettel, Positionen, Verlaufseintrag).

## Struktur

- `index.html`: Hauptapplikation (Single-File, enthält CSS und JS)
- `files/`: Ordner für die drei Druckansichten
  - `spickzettel-psych-print.html`
  - `positionen-psych-print.html`
  - `verlaufseintrag-psych-print.html`
- `shared-print.css`: Gemeinsames Stylesheet für die Druckansichten

## Deployment

Die Applikation wird automatisch via Netlify aus dem `main`-Branch deployed.

## Stand
Gültig ab 01.01.2026 (TARDOC EA.05)
