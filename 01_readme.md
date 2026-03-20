🏃‍♂️ Fitness-Tracker-Analyse: Kalorien-Vorhersage-Modell

📌 Projekt-Überblick
Dieses Projekt untersucht den Zusammenhang zwischen Workout-Metriken (Puls, Dauer, Schritte) 
und dem tatsächlichen Kalorienverbrauch. Ziel war es, ein Regressionsmodell zu entwickeln,
das den Energieumsatz präzise schätzt.

📊 Der Workflow
Explorative Datenanalyse (EDA): Identifikation von Korrelationen zwischen Herzfrequenz und Intensität.
Feature Engineering: Berechnung von Effizienz-Metriken (z. B. Steps per Minute).
Modell-Benchmark: Vergleich von Linear Regression, Random Forest und Gradient Boosting mittels 5-facher Cross-Validation (K-Fold).
Evaluation: Einsatz eines Custom-Scores (Kombination aus $R^2$ und normalisiertem RMSE).

📈 Ergebnisse & Metriken
Im aktuellen Datensatz erreichte das beste Modell einen $R^2$ Score von -0.0288.

Warum ist der Score negativ? (Ehrliches Fazit)
Ein negativer $R^2$ bedeutet, dass der Durchschnitt der Daten eine bessere Vorhersage liefert als das Modell selbst.
Dies ist ein klares Anzeichen für Underfitting aufgrund von:
    Fehlenden Biometrie-Daten: Kalorienverbrauch ist hochgradig individuell (Alter, Gewicht, Geschlecht fehlten im Datensatz).
    Daten-Rauschen: Die Komplexität menschlicher Physiologie lässt sich nicht allein durch "Schritte" und "Puls" linear oder in einfachen Bäumen abbilden.

🛠 Tech-Stack
Pandas & NumPy: Datenmanagement und Feature-Berechnung.
Matplotlib & Seaborn: Visualisierung der Fehler (Residuals) und der Feature-Importance.
Scikit-Learn: Machine Learning Pipeline (Train/Test-Split, K-Fold, Regressoren).

🚀 Ausblick & VerbesserungUm die Vorhersagekraft über die Baseline zu heben, sind folgende Schritte geplant:
Feature-Expansion: Integration von Körpergewicht (BMI) und VO2-Max Werten.
Hyperparameter-Tuning: Einsatz von GridSearchCV für den Random Forest.
Größere Datenbasis: Erhöhung der Stichprobenmenge, um das Rauschen zu minimieren.
