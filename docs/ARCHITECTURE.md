# Architekturübersicht — EvolveScan

EvolveScan besteht aus fünf Kernkomponenten:

## 1. Feature Layer
Extrahiert strukturierte Merkmale aus Quellcode.

## 2. Detector Layer
Klassische statische Analyse (Long Function, Complexity).

## 3. Engine Layer
Heuristische Mustererkennung:

- PatternEngine
- SemanticEngine
- HistoryEngine

## 4. Meta-Engine
Aggregiert Scores und erzeugt finale Entscheidungen.

## 5. Mini-AI
Lernfähige Komponente mit:

- ProbabilityMemory
- RuleEvolution
- probabilistischen Predictions

---

## Datenfluss

Source Code → FeatureExtractor → Detectors → Engines → MetaEngine → Mini-AI

---

## Hinweis

Die Mini-AI ersetzt langfristig viele heuristische Engines durch Lernen.
