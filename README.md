# Vorhersage der Fluggastzufriedenheit mit Machine Learning

## Überblick

Dieses Projekt verwendet Methoden des maschinellen Lernens, um anhand strukturierter Passagier- und Flugdaten vorherzusagen, ob ein Fluggast mit seiner Flugreise zufrieden oder unzufrieden ist.

## Verwendete Technologien

- Python
- Pandas
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Vorgehensweise

- Datenvorverarbeitung mithilfe von `SimpleImputer` und `ColumnTransformer`
- Kodierung kategorialer Merkmale mit `OneHotEncoder`
- Kodierung der Zielvariable mit `LabelEncoder`, sofern erforderlich
- Training des Vorhersagemodells mit XGBoost
- Erstellung von Vorhersagen für die Einreichung bei Kaggle

## Modellbewertung

Kaggle ROC-AUC-Wert: **0,92**

## Projektstruktur

- `airline_satisfaction.ipynb` — Datenaufbereitung, Modelltraining und Auswertung
- `requirements.txt` — Abhängigkeiten des Projekts

## Reproduzierbarkeit

Installieren Sie die in `requirements.txt` aufgeführten Abhängigkeiten und führen Sie anschließend das Notebook in Jupyter aus.

*Hinweis: Der angegebene Wert basiert auf der Bewertung durch Kaggle. Um exakt dasselbe Ergebnis auf der Rangliste zu reproduzieren, können die ursprünglichen Wettbewerbsdaten und die entsprechende Bewertungsumgebung erforderlich sein.*
