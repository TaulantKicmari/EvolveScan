# Wie EvolveScan funktioniert

EvolveScan analysiert Quellcode in mehreren Schichten.

---

## 1. Feature Extraction

Der Code wird in strukturierte Merkmale überführt:

- Zeilenanzahl
- Komplexität
- Parameter
- Guard Clauses
- ungenutzte Parameter

---

## 2. Detectors

Detektoren erzeugen erste Findings:

- long_function
- high_complexity

---

## 3. Engines

Heuristische Erweiterungen:

- patternflatblock
- semanticsuspiciousblock
- historysuspiciouspattern

---

## 4. Meta-Engine

Erzeugt finale Bewertung:

- refactor
- review
- ok

---

## 5. Mini-AI

Lernt aus:

- Features
- Scores
- Outcomes
- Vergleichen mit externen Modellen

und erzeugt probabilistische Entscheidungen.
