# Health & Life Dashboard

Ein schlanker, komplett lokal laufender **Gesundheits-, Trainings- und Alltagstracker** als Single-File-HTML-Web-App (PWA) – ohne Benutzerkonto, ohne Cloud und ohne Tracking.

## Projektidee & Entstehung

- **100 % Offline & Datenschutzfreundlich:** Alle eingegebenen Daten (Workouts, Blutdruck, Fokus-Ziele, Mind-Dumps, Ernährung & Körperwerte) werden ausschließlich im `localStorage` des eigenen Browsers gespeichert und können jederzeit als JSON-Datei gesichert oder wiederhergestellt werden.
- **Gelenkschonende Übungsideen:** Die integrierte 7-Minuten-Aktivierung (Kettlebell & Bodyweight) sowie die Trainingsvorlagen setzen auf kontrollierte Bewegungen, Rumpfstabilität und gelenkschonende Winkel.
- **Mit KI erstellt – frei anpassbar:** Die App wurde mithilfe von Künstlicher Intelligenz (KI) entwickelt. Der Code ist bewusst in einer einzigen HTML-Datei gebündelt, sodass jeder das Projekt unter der **MIT-Lizenz** frei nutzen, mit einer eigenen KI weiterentwickeln oder mit HTML/JS-Kenntnissen auf seine eigenen Bedürfnisse zuschneiden kann.

## Funktionen

1. **Täglich:** 7-Minuten-Intervalltimer (45s Belastung / 15s Pause) mit Kettlebell- und Bodyweight-Modus, Audio-Signalen, WakeLock (Display bleibt aktiv) und Übungsgrafiken.
2. **Training:** Kraft- & Ausdauer-Logbuch mit automatischer Speicherung der letzten Gewichte.
3. **Blutdruck:** Protokoll für Systole, Diastole und Puls inkl. 14-Tage-Verlaufsdiagramm.
4. **Fokus:** Tägliche Checkliste gegen digitalen Überkonsum + 7-Tage-Rückblick.
5. **Ruhe:** Animiertes Box Breathing (4-4-4-4) und abendlicher Mind-Dump.
6. **Körper & Ernährung:** Monatskalender für Mahlzeiten-Planung, Meal-Prep-Rezepte und Körperwerte-Tracking.
7. **Backup:** JSON-Export und -Import zur lokalen Datensicherung.

## Installation als App (PWA) & GitHub Pages

1. Lade die Dateien (`index.html`, `manifest.json`, `sw.js`, `icon.svg`, `README.md`, `LICENSE`) in ein öffentliches GitHub-Repository hoch.
2. Aktiviere unter **Settings → Pages** den Branch `main` (`/root`).
3. Öffne die erzeugte `github.io`-URL auf dem Smartphone (Chrome/Edge auf Android oder Safari auf iOS) und wähle **„Zum Startbildschirm hinzufügen“** bzw. **„App installieren“**.

## Wichtiger Hinweis / Haftungsausschluss

**Training auf eigene Gefahr.** Dieses Projekt dient ausschließlich der persönlichen Dokumentation und Selbstorganisation. Es stellt **keine medizinische, ärztliche, physiotherapeutische oder ernährungswissenschaftliche Beratung** dar und ersetzt keine Konsultation von medizinischem Fachpersonal.

## Lizenz

Veröffentlicht unter der [MIT-Lizenz](LICENSE).
