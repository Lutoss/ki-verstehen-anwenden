# Per Anhalter durch die KI

Ein praxisnaher Selbstlernkurs zu Künstlicher Intelligenz für neugierige
Alltagsnutzerinnen und -nutzer — entwickelt für die Volkshochschule und
vollständig ohne Präsenzveranstaltung nutzbar.

Der Kurs führt in zwei Teilen von „Was ist das eigentlich?" bis zum ersten
eigenen kleinen KI-Projekt: verständlich, praktisch und ohne vorausgesetzte
Fachkenntnisse. ChatGPT dient häufig als Beispiel; die Arbeitsprinzipien sind
weitgehend auf vergleichbare KI-Assistenten übertragbar.

Aktueller veröffentlichter Stand: Teil 1 V37, Teil 2 V22 und Zusatzlinks V35
(14.07.2026).

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
| [**Teil 1 — KI verstehen und anwenden**](kurs/teil-1-orientierung.html) | KI ausprobieren, ihre Funktionsweise verstehen, gute Aufträge schreiben und Ergebnisse kritisch prüfen. |
| [**Teil 2 — Projektwerkstatt**](kurs/teil-2-projektwerkstatt.html) | Ein eigenes Projekt lokal und in klaren Phasen planen, bearbeiten, prüfen und bewusst abschließen. |
| [**Die große Linksammlung**](kurs/zusatzlinks.html) | Kuratierte Tools, Spiele, Webseiten und Lernquellen zum Nachschlagen und Weiterstöbern. |

Alle Kursseiten sind eigenständige HTML-Dateien. Oberfläche, Interaktionen und
die lokalen Webseiten-Vorschaubilder funktionieren offline; externe Lernangebote
werden erst beim Öffnen eines Links benötigt.

## Design-Varianten

Im Ordner [`designs/`](designs/) liegen fünf frühere gestalterische Experimente
von Teil 1 (Lehrbuch, Raster, Arbeitsheft, Neo-Brutalismus, Terminal). Sie zeigen
ältere Inhaltsstände und dienen nur noch als Vergleich verschiedener
Layoutrichtungen. Details in
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
│   ├── teil-1-orientierung.html     Teil 1 — KI verstehen und anwenden
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

_Erstellt für die VHS und als eigenständiger Selbstlernkurs. Rückmeldungen und Verbesserungsvorschläge sind willkommen._
