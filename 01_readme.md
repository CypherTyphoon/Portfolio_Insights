# 🏃‍♂️ Fitness-Tracker-Analyse & Kalorien-Vorhersage (ML)

Dieses Projekt umfasst eine vollständige End-to-End Data Science Pipeline zur Analyse von Fitness-Daten und zur Vorhersage des Kalorienverbrauchs mittels Machine Learning. Von der explorativen Datenanalyse (EDA) über fortgeschrittenes Feature Engineering bis hin zum Modell-Benchmark mit K-Fold Cross-Validation.

## 📋 Projektübersicht

Ziel war es, aus klassischen Wearable-Daten (Dauer, Schritte, Herzfrequenz) ein Modell zu entwickeln, das den Energieverbrauch (Calories Burned) mit hoher Präzision vorhersagt. Das Projekt demonstriert den Weg von rohen Sensordaten zu einer validierten KI-Entscheidungsgrundlage.

## 🛠 Technologien & Bibliotheken

- **Sprache:** Python 3.x
- **Datenanalyse:** Pandas, NumPy
- **Visualisierung:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn (Linear Regression, Random Forest, Gradient Boosting)
- **Validierung:** K-Fold Cross-Validation, R²-Score, RMSE, MAE

## 🚀 Der Workflow (25 Schritte)

Das Notebook ist in logische Phasen unterteilt:

1.  **Explorative Datenanalyse (EDA):** Verteilung der Aktivitäten, Korrelationsmatrizen und Identifikation von Mustern.
2.  **Datenreinigung:** Handling von Ausreißern und Bereinigung von Sensorfehlern.
3.  **Feature Engineering:** * Berechnung der **Kadenz** (Schritte pro Minute).
    * Ermittlung der **Herzfrequenz-Dichte**.
    * Erstellung von Effizienz-Raten (Kalorien pro Minute).
4.  **Modellierung:** Vergleich von drei Algorithmen:
    * *Linear Regression* (Baseline & Interpretierbarkeit).
    * *Random Forest* (Stabilität durch Ensemble-Learning).
    * *Gradient Boosting* (Maximale Präzision durch iteratives Lernen).
5.  **Validierung:** Einsatz eines **Custom Performance-Scores**, der Präzision ($R^2$) gegen Fehlerstabilität (RMSE) abwägt.
6.  **Abschluss-Analyse:** Kritische Reflexion über Underfitting und Roadmap für zukünftige Verbesserungen.

## 📊 Zentrale Ergebnisse

- **Top-Feature:** Die Analyse der *Feature Importance* ergab, dass [Dein Top-Feature, z.B. Herzfrequenz oder Dauer] den stärksten Einfluss auf den Kalorienverbrauch hat.
- **Modell-Performance:** Das Champion-Modell erreichte einen **R²-Score von [Dein Wert, z.B. 0.92]**.
- **Stabilität:** Durch K-Fold Cross-Validation wurde ein niedriger *Overfitting-Gap* nachgewiesen, was die Generalisierungsfähigkeit des Modells bestätigt.

## 📈 Visualisierungen (Auszug)

Das Projekt generiert automatisch Berichte und Grafiken im Ordner `output/`, darunter:
- Korrelations-Heatmaps
- Modell-Leaderboards
- Predicted-vs-Actual Scatterplots
- Feature Importance Charts



[Image of a data science lifecycle diagram]


## 💡 Ausblick & Optimierung

Für zukünftige Versionen sind folgende Erweiterungen geplant:
- Integration von VO2 Max und BMI-Daten.
- Einbeziehung von GPS-Höhendaten (Steigung).
- Testen von Deep Learning Ansätzen bei steigender Datenmenge.

---
**Autor:** Stefan Fölz / (https://github.com/CypherTyphoon)
**Datum:** April 2026