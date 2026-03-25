#  Gforth Lernplattform V.1.0.12

Eine vollständige, interaktive Lernplattform für die Programmiersprache **Forth** — speziell für [Gforth](https://gforth.org/) auf Linux/Arch. Keine Installation, keine Abhängigkeiten, kein Internet nötig. Eine einzige HTML-Datei.

---

##  Wofür ist das?

Forth ist eine faszinierende, aber ungewöhnliche Sprache — Stack-basiert, minimalistisch, extrem mächtig. Die meisten Lernressourcen sind entweder zu technisch, zu alt oder nur auf Englisch. Diese Plattform soll das ändern:

- Anfänger können **von Null** starten und werden Schritt für Schritt geführt
- Fortgeschrittene finden eine **vollständige Syntax-Referenz** mit über 275 Wörtern
- Alle können mit dem **eingebauten Simulator** direkt im Browser experimentieren
- Der Fokus liegt auf **Gforth auf Arch Linux / CachyOS** — aber der Inhalt gilt für jede moderne Forth-Implementierung

---

##  Für wen ist das?

| Zielgruppe | Was sie bekommen |
|---|---|
| **Absolute Anfänger** | 19 Tutorial-Kapitel von „Was ist ein Stack?" bis zum eigenen Interpreter |
| **Umsteiger** aus Python, C, etc. | Idiom-Bibliothek, Querverweise, Erklärungen warum Forth anders denkt |
| **Embedded-Entwickler** | Grundlagen die sich 1:1 auf AmForth/Mecrisp übertragen |
| **Neugierige** | Historie, Philosophie, warum Forth im Space Shuttle und in Bitcoin steckt |

---

##  Features im Überblick

###  Referenz
Vollständige Wort-Referenz mit **Schwierigkeitsfilter**, **Querverweisen** und **Favoriten**.
- ~126 Basiswörter mit Stack-Effekt, Beschreibung und Codebeispiel
- Schwierigkeitsgrad: 🟢 Anfänger / 🟡 Mittel / 🔴 Fortgeschritten
- „Siehe auch"-Chips die direkt zum verwandten Wort springen
- Wörter als „gelernt" markieren und Favoriten speichern
- Wort des Tages

###  Erweitert
Weitere ~149 Wörter für fortgeschrittene Themen:
Doppelzahlen, gemischte Arithmetik, piktografische Ausgabe, Vokabular-System, erweiterte Kompilierung, lokale Variablen, erweiterte Strings, Floating Point, System/OS-Zugriff, Debugging-Tools, Gforth OOP

###  Tutorial — 19 Kapitel
Geführte Lernpfade mit animierten Stack-Visualisierungen, Schritt-für-Schritt-Erklärungen und Mini-Quiz am Ende jedes Kapitels:

| # | Kapitel | Level | XP |
|---|---|---|---|
| 1 | Was ist ein Stack? | 🟢 | 50 |
| 2 | Arithmetik in Forth | 🟢 | 60 |
| 3 | Stack-Manipulation | 🟢 | 70 |
| 4 | Eigene Wörter schreiben | 🟢 | 80 |
| 5 | Schleifen | 🟡 | 90 |
| 6 | Bedingungen: if / else / then | 🟡 | 80 |
| 7 | Variablen & Speicher | 🟢 | 90 |
| 8 | Text & Strings | 🟢 | 70 |
| 9 | Rekursion | 🟡 | 100 |
| 10 | Mini-Projekt: RPN-Taschenrechner | 🟡 | 150 |
| 11 | Der Return-Stack | 🟡 | 110 |
| 12 | Datenstrukturen bauen | 🟡 | 120 |
| 13 | Fehlerbehandlung | 🟡 | 100 |
| 14 | Zahlenformate & Basen | 🟡 | 90 |
| 15 | Mini-Projekt: Zahlenraten | 🟡 | 130 |
| 16 | Mini-Projekt: Tiny Forth im Forth | 🔴 | 200 |
| 17 | Immediate Words & Compiler-Erweiterungen | 🔴 | 150 |
| 18 | Das Vokabular-System | 🔴 | 130 |
| 19 | Floating Point in der Praxis | 🟡 | 110 |

**~1.760 XP** wenn man alle Kapitel abschließt. Fortschritt wird lokal im Browser gespeichert.

###  Flashcards
- Karte umdrehen → Beschreibung + Beispiel erscheinen
- ✓ Gewusst / ✗ Nochmal / ★ Als gelernt markieren
- Filter: Alle / Noch nicht gelernt / Nur Favoriten
- Nach Kategorie einschränkbar

###  Quiz
Multiple-Choice mit drei Fragetypen:
- „Was macht das Wort?" — Beschreibung raten
- „Welches Wort ist das?" — Wort zur Beschreibung finden
- „Stack-Effekt erraten" — Notation zuordnen

###  Simulator
- Echtzeit-Stack-Visualisierung mit TOS-Hervorhebung
- Unterstützt Arithmetik, Stack-Ops, Vergleiche, Logik, Variablen, eigene Wörter, Schleifen
- 10 anklickbare Beispiele, Eingabe-Verlauf, Fehler-Highlighting

###  Fortschritt
- Fortschrittsbalken pro Kategorie
- Favoriten-Sammlung auf einen Blick
- Fortschritt zurücksetzen

### 📜 Historie
- Vollständige Zeitleiste 1968–heute
- Porträts der wichtigsten Personen (Chuck Moore, Elizabeth Rather, Leo Brodie, Anton Ertl …)
- Einsatzgebiete heute: Space Shuttle, Open Firmware, Mikrocontroller, Bitcoin Script …
- Forth-Philosophie und Originalzitate

###  Idiom-Bibliothek — 35 Einträge
Typische Forth-Muster mit Stack-Effekt, Codebeispiel und Praxis-Tipp:

| Kategorie | Beispiele |
|---|---|
| Stack | Wert aufbewahren, 2dup-Vergleich, Stack aufräumen, depth-Check |
| Kontrollfluss | Ternärer Operator, n-mal wiederholen, early return, Schrittweite |
| Speicher | Getter/Setter, Variable tauschen, Array mit Bounds-Check |
| Strings | Teilstring, Zahl formatieren, Datei lesen, Datei schreiben |
| Definitionen | Factory-Pattern, Wort mit Default, Linked List |
| Float | Grad↔Radiant, Runden, Statistik/Mittelwert |
| Fortgeschritten | Execution Tokens, deferred words, require-Pattern, Benchmark |

---

##  Sprachen

🇩🇪 Deutsch &nbsp;·&nbsp; 🇬🇧 English &nbsp;·&nbsp; 🇮🇹 Italiano &nbsp;·&nbsp; 🇪🇸 Español &nbsp;·&nbsp; 🇫🇷 Français

Umschaltbar per Knopfdruck — die Suche funktioniert in der jeweiligen Sprache.

---

##  Dark & Light Mode

Umschaltbar per Toggle oben rechts. Dark Mode ist Standard.

---

##  Tastaturkürzel

| Kürzel | Aktion |
|---|---|
| `/` | Suche fokussieren |
| `Esc` | Suche leeren / Detail schließen |

---

##  Aufbau der Datei

Alles in einer einzigen HTML-Datei (`gforth_lernplattform_final.html`, ~353 KB):

```
gforth_lernplattform_final.html
│
├── <style>           CSS mit Variablen für Dark/Light Mode
│
├── <header>          Navigation, Suche, Sprach- und Theme-Switcher
├── .mode-nav         Tab-Leiste (9 Modi)
├── .cat-tabs         Kategorie-Filter (Referenz / Erweitert)
│
├── <main>
│   ├── #mode-ref     Referenz mit Schwierigkeitsfilter
│   ├── #mode-fc      Flashcard-Modus
│   ├── #mode-quiz    Quiz-Modus
│   ├── #mode-sim     Forth-Simulator
│   ├── #mode-prog    Fortschrittsanzeige
│   ├── #mode-adv     Erweiterte Referenz
│   ├── #mode-tut     Tutorial (19 Kapitel)
│   ├── #mode-hist    Geschichte von Forth
│   └── #mode-idiom   Idiom-Bibliothek
│
└── <script>
    ├── UI-Texte (5 Sprachen)
    ├── Basis-Wörter (~126 Einträge + Metadaten)
    ├── Erweiterte Wörter (~149 Einträge)
    ├── Tutorial-Daten (19 Kapitel × ~4 Schritte)
    ├── Idiom-Daten (35 Einträge)
    ├── Simulator-Engine
    ├── Flashcard-, Quiz- und Tutorial-Engine
    ├── Historie- und Idiom-Renderer
    ├── Fortschritts-System (localStorage)
    └── INIT
```



Kein Server, kein Node, kein npm. Läuft komplett offline.

---

##  Empfohlener Lernpfad

```
Einstieg        →  Kapitel 1–4   (Stack, Arithmetik, Manipulation, eigene Wörter)
Grundlagen      →  Kapitel 5–6   (Schleifen, Bedingungen) + Simulator ausprobieren
Mittelstufe     →  Kapitel 7–10  (Variablen, Strings, Rekursion, RPN-Rechner)
                   Flashcards    (Wörter festigen)
                   Kapitel 11–15 (Return-Stack, Datenstrukturen, Fehler, Spiel)
Fortgeschritten →  Kapitel 16–19 (Interpreter, Immediate Words, Vokabulare, Float)
                   Erweitert     (Vertiefung)
                   Idiome        (typische Muster)
                   Historie      (Hintergrund)
```

---

##  Getestet mit

- Gforth 0.7.9 auf Arch Linux / CachyOS
- Firefox 120+, Chromium 120+, Chrome 120+
- Mobile: grundsätzlich funktionsfähig, für Desktop optimiert

---

##  Forth-Ressourcen

- [Gforth Manual](https://gforth.org/manual/) — offizielle Dokumentation
- [Starting Forth](https://www.forth.com/starting-forth/) — Leo Brodis Klassiker (frei online)
- [Thinking Forth](http://thinking-forth.sourceforge.net/) — Forth-Philosophie und Stil
- [Forth Interest Group](https://www.forth.org/) — Community und Standards
- [AmForth](http://amforth.sourceforge.net/) — Forth für AVR-Mikrocontroller
- [Mecrisp](http://mecrisp.sourceforge.net/) — Forth für ARM Cortex-M
- [r/Forth](https://www.reddit.com/r/Forth/) — Reddit-Community

---

##  Auf einen Blick

| | |
|---|---|
| Basis-Wörter | ~126 |
| Erweiterte Wörter | ~149 |
| Tutorial-Kapitel | 19 |
| Erreichbare XP | ~1.760 |
| Idiome | 35 |
| Sprachen | 5 |
| Dateigröße | 353 KB |

---

Lizenz der Seite liegt bei:

## Patrick Bruno Klingforth

---

## *Gebaut mit ❤️ für die Forth-Community — eine Sprache die seit 1968 Computer anders denkt.*
