# Schießtagebuch & Grafik-Generator

Single-File Web-App (`Schiesstagebuch.html`) zum Erfassen von Schießtrainings und zum Erzeugen einer
Ergebnisgrafik im Format 1920×1080 (PNG).

## Benutzung

Online über GitHub Pages: <http://ewiesmair.github.io/Schiesstagebuch/>

Oder lokal: `Schiesstagebuch.html` im Browser öffnen – keine Installation, kein Server nötig.
Alle Daten bleiben lokal im Browser (IndexedDB). Über **Daten → JSON-Backup** lassen sie sich
sichern und auf ein anderes Gerät übertragen.

## Funktionen

- **Treffer erfassen:** 10 Serien × 5 Schuss, Wertung in Ringen (0–10/X) oder IPSC (A/C/D/M, Minor/Major),
  Touch-Tastenfeld und Tastatursteuerung
- **Grafik-Generator:** Live-Vorschau und PNG-Export/Teilen mit Waffe, Distanz, Datum, Waffen- und Zieltyp-Icon
- **Waffen-Presets:** Standardliste plus eigene Waffen
- **Munitions-Datensätze:** Hersteller, Kaliber, Geschosstyp, Gewicht (gr) und Bemerkung einmal anlegen und
  wiederverwenden; passende Munition zum Kaliber der Waffe wird zuerst angezeigt
- **Tagebuch:** Suche, Filter, Sortierung, Laden älterer Trainings, Vorlage für neues Training
- **Statistik:** Kennzahlen, Leistungsverlauf und Schussbelastung je Waffe
- **Daten:** JSON-Backup/-Import, CSV-Export, optionale Direkt-Synchronisierung in eine lokale Datei

## Abhängigkeiten

Wird online über CDN geladen: Tailwind CSS (`cdn.tailwindcss.com`) und Google Fonts
(Barlow Condensed, Inter).
