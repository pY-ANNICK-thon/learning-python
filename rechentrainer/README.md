# Rechentrainer

Lokale Website zum Üben von Kopfrechnen. Keine Installation nötig.

## Starten
`index.html` doppelklicken (öffnet im Browser) – oder im Terminal:

```bash
open rechentrainer/index.html
```

## Modi
| Modus | Aufgaben |
|---|---|
| Kleines Einmaleins | 1–10 · 1–10 |
| Großes Einmaleins | 11–20 · 1–20 |
| Addieren & Subtrahieren | bis 20 / 100 / 1000, keine negativen Ergebnisse |
| Multiplizieren & Dividieren | Faktoren bis 10 / 20 / 50, Division immer ohne Rest |

Eingabe mit **Enter** bestätigen. Statistik: richtig, falsch, Serie, Quote, Verlauf.

## Zufall & Wiederholen
- **Keine Wiederholung pro Runde:** Jede Aufgabe einer Kategorie kommt erst wieder, wenn alle anderen einmal dran waren.
- **Wie bei Anki:** Falsche oder übersprungene Aufgaben kommen **nach 3 Aufgaben** wieder (markiert mit 🔁). Bei richtiger Antwort noch einmal **nach 8 Aufgaben**, danach gelten sie als gelernt. Wieder falsch → Abstand beginnt von vorn.
- Abstände ändern: `STEPS = [3, 8]` in `index.html`.
