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
