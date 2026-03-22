🌍 Global AI & Tech Salary Intelligence 2026
Predictive Analytics & Market Insights with Machine Learning
📌 Project Overview
Dieses Projekt analysiert die globalen Gehaltsstrukturen im Tech-Sektor mit einem speziellen Fokus auf den KI-Premium-Faktor. Durch die Fusion von Gehaltsdaten, demografischen Faktoren (Bevölkerungsdichte) und geografischen Informationen liefert die Pipeline nicht nur Vorhersagen, sondern erklärt auch die treibenden Kräfte hinter den Lohnunterschieden im Jahr 2026.

🛠 Tech Stack & Methodology
Data Engineering: Bereinigung und Integration multipler Datenquellen (Salaries, World Cities, Geo-Data) mit Pandas.

Interactive Visualization: Globale Choropleth-Karten und interaktive Opportunity-Indizes mit Plotly Express.

Predictive Modeling: Einsatz von RandomForestRegressor und GradientBoostingRegressor zur Gehaltsprognose.

Explainable AI (XAI): Einsatz von SHAP (Shapley Additive Explanations) und Partial Dependence Plots (PDP) zur Dekonstruktion der Modellentscheidungen.

📈 Key Insights (2026)
The AI Alpha: KI-Spezialisierungen erzielen im globalen Median einen Aufschlag von X% gegenüber klassischen Full-Stack-Rollen.

Urban Pressure: Die Bevölkerungsdichte korreliert nicht linear mit dem Gehalt; wir identifizierten "Hidden Gem Hubs" mit hoher Kaufkraft bei moderater Dichte.

Experience Saturation: SHAP-Analysen zeigen, dass der Grenznutzen von KI-Erfahrung nach ca. 5-7 Jahren abflacht, während die Standortwahl ein dominanter Preistreiber bleibt.

🚀 Interactive Dashboards
Das Projekt generiert automatisierte HTML-Reports:

03_interactive_ai_premium_map.html: Weltkarte des KI-Gehaltsfaktors.

03_interactive_pdp_analysis.html: Sensitivitätsanalyse der Features.

📋 How to Run
Installation:

Bash
pip install pandas numpy scikit-learn plotly shap statsmodels matplotlib seaborn
Execution:
Starte das Jupyter Notebook AI_Salary_Analysis_2026.ipynb. Stelle sicher, dass die Quelldaten im /data Ordner liegen.

🧠 Model Explainability Example
Ein zentraler Bestandteil ist der SHAP Force Plot, der individuelle Marktvorhersagen erklärt:

"Ein Gehalt in Land X liegt 20% über dem globalen Schnitt, primär getrieben durch die hohe lokale KI-Nachfrage (Rot), trotz dämpfender Effekte durch die lokale Steuerstruktur (Blau)."
