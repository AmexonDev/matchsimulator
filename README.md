# Match Simulator ⚽

Match Simulator to prosta aplikacja, która przewiduje wyniki meczów piłkarskich na podstawie statystyk drużyn i modeli analitycznych. System analizuje formę, historię spotkań oraz podstawowe dane drużyn, aby wygenerować przewidywany wynik oraz prawdopodobieństwa.

Celem projektu jest symulacja realistycznych wyników meczów, a nie dokładne przewidywanie rzeczywistych rezultatów.

## Przykładowe wyniki symulacji

| Mecz                | Wynik meczu | Wynik według symulatora | Trafność |
|---------------------|-------------|--------------------------|----------|
| Real Madrid vs Barca | 2:1         | 1:2                      | ❌       |
| Liverpool vs Chelsea | 3:0         | 2:1                      | ❌       |
| Bayern vs Dortmund   | 2:2         | 2:2                      | ✅       |
| PSG vs Marseille     | 1:0         | 1:0                      | ✅       |
| Arsenal vs City      | 0:2         | 1:2                      | ❌       |

## Oznaczenia
- ✅ = trafiony wynik
- ❌ = nietrafiony wynik

## Technologie
- Python / JavaScript (w zależności od wersji)
- Analiza danych
- Prosty model predykcyjny
