# denkpause.

**Drei Minuten Brain-Games statt Scrollen.**

Denkpause ersetzt den automatischen Griff zu Instagram, TikTok & Co. durch ein kurzes, bewusst endliches Tagesritual: fünf Mini-Spiele, nach denen du etwas gelernt hast.

👉 **Jetzt spielen:** [moritzkloer.github.io/denkpause](https://moritzkloer.github.io/denkpause/)

---

## Die Idee

Der Feed hört nie auf. Eine Denkpause schon.
Statt Social Media zu verbieten, bietet Denkpause etwas Besseres für die ersten Minuten am Handy. Nach rund 4 Minuten ist die Runde vorbei, und du weißt mehr als vorher.

## Die Spiele

| Spiel | Was du machst |
|---|---|
| **Geo-Quiz** | Eine Hauptstadt plus zwei aus Flagge, Landesumriss und Länder-Steckbrief (Wahrzeichen, Währung, Sprache, Kultur) |
| **Wissen** | Drei Fragen aus 13 Bereichen, von Geschichte bis Weltall, jeweils mit kurzem Fakt |
| **Schätzen** | Zwei Fragen, die niemand genau weiß. Je näher deine Schätzung, desto mehr XP |
| **Kopfrechnen** | Vier Aufgaben auf Zeit |
| **Mini-Sudoku** | Ein 4×4-Rätsel |

## Funktionen

- **Tagesrunde** mit Streak und Level-System
- **Bonuslevel** mit doppelten XP nach 3 Tagen am Stück
- **„Das hast du heute gelernt“** nach jeder Runde
- **Drei Schwierigkeitsgrade:** Leicht, Mittel, Schwer
- **Konto (optional)** mit E-Mail und Passwort: Spielstand wird online gesichert und auf allen Geräten synchronisiert
- **Live-Rangliste mit Freunden:** Freunde per Benutzername hinzufügen
- **Ohne Konto:** Freunde per Freundescode, Sicherungscode zum Übertragen des Spielstands
- **Fragenpool:** 150 Länder, 139 Landesumrisse, 70 Steckbriefe, über 120 Wissensfragen, über 30 Schätzfragen

## Auf dem iPhone installieren

1. Link oben in **Safari** öffnen
2. **Teilen** → **„Zum Home-Bildschirm“** → **Hinzufügen**
3. Denkpause startet ab jetzt wie eine App, mit Icon und im Vollbild

**Tipp:** Mit einer Kurzbefehl-Automation („Wenn Instagram geöffnet wird → Denkpause öffnen“) wird Denkpause zum automatischen Ersatzritual.

## Datenschutz

- Kein Tracking, keine Werbung
- **Ohne Konto:** Dein Spielstand wird nur lokal auf deinem Gerät gespeichert. Wird die App gelöscht, ist er weg. Vorher den Sicherungscode in den Einstellungen kopieren.
- **Mit Konto:** E-Mail, Benutzername und Spielfortschritt liegen bei [Supabase](https://supabase.com) auf Servern in Frankfurt (EU). Freunde sehen nur Name, XP, Streak und Länderzahl.
- Konto und alle Online-Daten lassen sich jederzeit in den Einstellungen löschen.

## Technik

- Reines HTML, CSS und JavaScript, ohne Framework und ohne Build-Schritt
- `index.html`: App
- `questions.js`: kompletter Fragenpool, leicht erweiterbar
- `shapes.js`: Länderumrisse aus [Natural Earth](https://www.naturalearthdata.com/) (gemeinfrei), vereinfacht als SVG-Pfade
- `manifest.webmanifest` und Icons: Installation als Web-App
- Konten und Rangliste über Supabase (Postgres mit Row Level Security)
- Gehostet über GitHub Pages

## Roadmap

- [x] Länderumrisse erkennen
- [ ] Fragen zu Einwohnern und Fläche mit Daten aus offiziellen Quellen
- [x] Konten und Live-Rangliste mit Freunden
- [ ] Weltkarte mit gelernten Ländern
- [ ] Wochenrückblick
- [ ] Offline-Modus

## Feedback

Fehler gefunden oder eine Idee? Gern als [Issue](https://github.com/Moritzkloer/denkpause/issues) anlegen oder direkt bei mir melden.

---

Ein Nebenprojekt von Moritz Klör, entwickelt mit [Claude](https://claude.ai).
