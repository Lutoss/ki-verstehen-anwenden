# KI verstehen und anwenden

Ein praxisnaher Einsteigerkurs zu Künstlicher Intelligenz für neugierige
Alltagsnutzerinnen und -nutzer — entwickelt für einen Live-Kurs an der
Volkshochschule (VHS Landshut, Erstdurchlauf am 14.07.2026).

Der Kurs führt in zwei Teilen von „Was ist das eigentlich?" bis zum ersten
eigenen kleinen KI-Projekt: verständlich, werkzeugorientiert und ohne
Fachjargon. Als Haupttool dient ChatGPT, stellvertretend für vergleichbare
KI-Assistenten.

**➡️ Live-Website:** https://lutoss.github.io/ki-verstehen-anwenden/

---

## Was der Kurs vermittelt

Nach dem Kurs kann die Zielgruppe KI im Alltag sicher ausprobieren, typische
Tools einordnen, bessere Fragen stellen, Antworten kritisch prüfen und ein
eigenes kleines KI-Projekt starten. Der Kurs ist bewusst für Einsteiger
gedacht — keine Expertenausbildung, keine vollständige Marktübersicht.

## Inhalte

| Material | Beschreibung |
|----------|--------------|
| [**Teil 1 — Orientierung**](kurs/teil-1-orientierung.html) | Überblick über KI, die aktuelle Tool-Landschaft, sichere Nutzung und erste Grundlagen guter Prompts. |
| [**Teil 2 — Projektwerkstatt**](kurs/teil-2-projektwerkstatt.html) | Ein eigenes KI-Projekt auswählen, mit KI bearbeiten, Ergebnisse prüfen und den nächsten Schritt festlegen. |
| [**Zusatzlinks**](kurs/zusatzlinks.html) | Die große Linksammlung: kuratierte Tools, Webseiten und Ressourcen zum Nachschlagen. |

Alle Seiten sind eigenständige HTML-Dateien ohne externe Abhängigkeiten — sie
funktionieren offline im Browser und sind beamertauglich.

## Design-Varianten

Im Ordner [`designs/`](designs/) liegen fünf gestalterische Experimente von
Teil 1 (Lehrbuch, Raster, Arbeitsheft, Neo-Brutalismus, Terminal) — als
Vergleich verschiedener Layoutrichtungen. Details in
[`designs/README.md`](designs/README.md).

## Nutzung

**Online:** Über die [Live-Website](https://lutoss.github.io/ki-verstehen-anwenden/) direkt im Browser öffnen.

**Lokal:** Repository herunterladen und die gewünschte `.html`-Datei per
Doppelklick im Browser öffnen — keine Installation, kein Server nötig.

```bash
git clone https://github.com/Lutoss/ki-verstehen-anwenden.git
cd ki-verstehen-anwenden
# index.html oder kurs/teil-1-orientierung.html im Browser öffnen
```

## Aufbau des Repos

```
ki-verstehen-anwenden/
├── index.html                       Startseite (verlinkt alles)
├── kurs/
│   ├── teil-1-orientierung.html     Teil 1 — Orientierung
│   ├── teil-2-projektwerkstatt.html Teil 2 — Projektwerkstatt
│   └── zusatzlinks.html             Zusatzlinks / Linksammlung
├── designs/                         5 Design-Varianten von Teil 1
├── LICENSE                          CC BY-SA 4.0
└── README.md
```

## Lizenz

Dieses Kursmaterial steht unter der
[Creative Commons BY-SA 4.0](LICENSE)-Lizenz: frei nutzbar, teilbar und
anpassbar bei Namensnennung und Weitergabe unter gleichen Bedingungen.
Verlinkte externe Werkzeuge und Ressourcen unterliegen ihren eigenen Lizenzen.

---

_Erstellt für einen VHS-Kurs. Rückmeldungen und Verbesserungsvorschläge sind willkommen._
