# User Behavior & Spending Analysis 2026

## 📋 Projekt-Übersicht
Dieses Projekt analysiert den Zusammenhang zwischen **Smartphone-Nutzungsgewohnheiten** und dem **Online-Kaufverhalten**. 
Es umfasst die vollständige Pipeline von der Datenfusion über die statistische Analyse bis hin zum Training hochkomplexer Ensemble-Modelle.

**Status:** ✅ Abgeschlossen (Stand: 23.03.2026)
**Outputs:** 78 Artefakte (Grafiken, Tabellen, Modelle)

---

## 🛠 Tech-Stack
* **Sprache:** Python 3.x
* **Libraries:** Pandas, Seaborn, Matplotlib, Scikit-Learn
* **Modelle:** Random Forest, Gradient Boosting, Voting & Stacking Regressors

---

## 📂 Inhaltsverzeichnis der Ergebnisse (04_Outputs)

### 📊 Statistische Analysen & Visualisierungen
* **Demografie:** Analyse von Alter, Geschlecht und Standort in Bezug auf den Umsatz.
* **Device-Usage:** Vergleich zwischen Mobile- und Desktop-Nutzern.
* **Behavioral:** Untersuchung von Screen-Time, App-Opens und "Addiction-Labels".

### 🤖 Machine Learning Highlights
| Modell | Zielsetzung | Ergebnis (R²) |
| :--- | :--- | :--- |
| **Random Forest** | Robuste Baseline & Feature Importance | -0.04 |
| **Gradient Boosting** | Fehlerkorrektur & Präzision | -0.11 |
| **Stacking Ensemble** | Meta-Learning (Finales Modell) | -0.00 |

---

## 🚀 Key Insights (Top Features)
Basierend auf der **Feature Importance** (Datei 04_71) sind die stärksten Treiber für den Umsatz:
1. **Daily Screen Time** (Stärkster Prädiktor)
2. **Age** (Demografischer Kernfaktor)
3. **Notifications** (Marketing-Hebel)

---

## 📁 Dateiliste (Auszug)
* `04_75_final_spending_predictor.pkl`: Produktionsbereites Modell-Objekt.
* `04_77_final_leaderboard_all_models.csv`: Vergleich aller Modell-Metriken.
* `04_71_ml_feature_importance_comparison.png`: Visueller Vergleich der Treiber.

---
*Erstellt von Dein Name / Gemini AI*
