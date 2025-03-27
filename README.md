# data-science-exam
Repositiory for the Big Data lecture at DHBW Heidenheim

Using Crime Data from 2020 to Present from data.gov
[Download](https://catalog.data.gov/dataset/crime-data-from-2020-to-present)

Klassifikation

• Machine Learning – Teil 1
    • Daten bereinigen / vorbereiten [X]
    • 2 überwachte Lernalgorithmen trainieren, dabei
        • Ein Klassifikationsproblem lösen [Muhammat]
        • Ein Regressionsproblem lösen [Philipp]
    • Bewertung – Machine Learning
    • Evaluation beider Modelle (Vorhersagen) mit geeigneter Metrik
    • Visualisierung: Ergebnisse geeignet visualisieren
• Machine Learning – Teil 2
    • 2 Clustering Algorithmen anwenden [kMeans: , DBScan:]
    • Ergebnis erläutern
    • Visualisierung: Ergebnisse geeignet visualisieren


# Data Description

Don't modify these Variables copy then when you work with them!

e.q
```python
data.copy()
```

* data: contains the raw data from Crime Data from 2020 to Present
* encoded: contains the encoded data
    * following columns are encoded:
        - `UNIX_TIMESTAMP`: The timestamp of the crime event in UNIX format.
        - `TIME OCC`: The time the crime occurred.
        - `Vict Age`: The age of the victim.
        - `Crm Cd Desc`: The description of the crime code.
        - `AREA NAME`: The name of the area where the crime occurred.
        - `Vict Sex`: The gender of the victim.
        - `Premis Desc`: The description of the premises.
        - `Weapon Desc`: The description of the weapon used.
        - `LOCATION`: The geographical location of the crime.
* scaled_encoded: contains the scaled encoded data

