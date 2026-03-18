# 🎮 Video Game Sales: Eine 40-jährige Marktanalyse (EDA)

Dieses Projekt bietet eine umfassende explorative Datenanalyse (EDA) der globalen Videospielverkäufe von 1980 bis heute. Ziel war es, Trends in Plattform-Lebenszyklen, Genre-Dominanz und regionalen Marktunterschieden statistisch zu belegen und interaktiv aufzubereiten.

## 🚀 Key Insights (Haupterkenntnisse)
* **Marktwachstum:** Der Gesamtmarkt zeigt eine extrem starke Korrelation mit der Zeit ($r \approx 0.94$), was auf eine stetige Expansion der Industrie hindeutet.
* **Regionale Treiber:** Die Verkaufszahlen in Nordamerika (NA) sind der stärkste Prädiktor für den globalen Erfolg eines Spiels ($r > 0.9$, $p < 0.001$).
* **Plattform-Zyklen:** Die Analyse visualisiert die klassischen "Glockenkurven" der Hardware-Generationen (Launch, Peak, Sunset) von der PS2 bis zur heutigen Ära.
* **Genre-Shift:** Dokumentation des Wandels von Platformer-Dominanz (80er) hin zu Action- und Shooter-Marktführerschaft in den modernen Dekaden.

## 🛠 Tech-Stack
* **Sprache:** Python 3.x
* **Analyse:** `Pandas`, `NumPy`
* **Visualisierung:** * `Matplotlib` & `Seaborn` (Statische Blueprints & Heatmaps)
    * `Plotly` (Interaktive HTML-Dashboards)
* **Statistik:** `SciPy` (Pearson-Korrelation & Signifikanzprüfung)

## 📁 Projektstruktur
Das Projekt folgt einer sauberen Ordnerstruktur, um Rohdaten von Analyse-Ergebnissen zu trennen:

* `00_Data/`: Enthält den Rohdatensatz (`vgsales.csv`).
* `00_Outputs/`: Automatisch generierte Ergebnisse:
    * **Grafiken:** Korrelations-Heatmaps, Plattform-Lebenszyklen, Genre-Trends.
    * **Interaktiv:** Plotly-Dashboards als `.html` (im Browser bedienbar).
    * **Tabellen:** Pivot-Matrizen und aggregierte Sales-Statistiken als `.csv`.

## 📈 Methodik & Data Engineering
1.  **Smart Imputation:** Fehlende Erscheinungsjahre wurden nicht gelöscht, sondern mittels **Mode-Imputation pro Plattform** vervollständigt (Datenintegrität).
2.  **Daten-Validierung:** Automatischer Check, ob `Global_Sales` der Summe der regionalen Verkäufe entspricht (Integritätsprüfung).
3.  **Statistische Absicherung:** Berechnung von Korrelationskoeffizienten ($r$) und p-Werten zur Validierung von Markttrends.
4.  **Portfolio-Ready:** Alle Grafiken werden hochauflösend (300 DPI) für Dokumentationszwecke exportiert.

---

### Installation & Ausführung
1. Repository klonen:
   ```bash
   git clone [https://github.com/DEIN_USERNAME/PROJEKTNAME.git](https://github.com/DEIN_USERNAME/PROJEKTNAME.git)
