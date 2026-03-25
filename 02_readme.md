🎬 Executive Summary: Die Resilienz der Kunst (1980–2026)
Projektziel: Untersuchung des Zusammenhangs zwischen makroökonomischen Indikatoren (BIP, Gini-Index, Armutsrate) und der Rezeption von Film-Meisterwerken (IMDb Top 250).

🔍 Kernerkenntnisse (The Data Story)
Eskapismus-Effekt bestätigt: Unsere Machine-Learning-Modelle (Ensemble aus Random Forest & Gradient Boosting) zeigen, dass die Zuschauerbewertungen in wirtschaftlichen Krisenzeiten tendenziell steigen. Film wird in harten Zeiten als emotionales Ventil genutzt.

Comedy als Krisenwährung: Während Genres wie Drama oder Biography extrem stabil auf Wirtschaftsschwankungen reagieren, zeigt Comedy die höchste Sensitivität. In einer Rezession steigt das prognostizierte Rating für Komödien um ca. 0,04 Punkte – ein Indiz dafür, dass Humor bei sinkendem BIP an Wert gewinnt.

Qualität schlägt Ökonomie: Trotz globaler Krisen bleibt das Grundniveau der Top 250 stabil (Delta < 0,05 Sterne). Ein "Meisterwerk" definiert sich durch zeitlose Qualität, die von der Inflation unberührt bleibt.

🤖 Tech-Stack & Methodik
Data Lineage: Konsequente Nutzung von Arbeitskopien (.copy()) zur Wahrung der Rohdaten-Integrität.

Feature Engineering: One-Hot-Encoding von Genres und Integration globaler Wirtschaftsdaten über 45 Jahre.

Machine Learning: Einsatz eines Voting Regressors, um nicht-lineare Zusammenhänge zwischen Wohlstand und Publikumsgeschmack zu modellieren.