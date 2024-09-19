# Pandas Exercise: Data Exploration with Weather Dataset

In deze oefening heb ik gewerkt met **pandas**, een populair package in data science en data engineering. Pandas maakt het veel gemakkelijker en sneller om met data te werken en biedt bovendien mogelijkheden om mooie grafieken te maken. In deze opdracht heb ik de basisprincipes van pandas verkend door met een weer-dataset te werken.

## Omschrijving

Ik heb een Jupyter Notebook aangemaakt waarin ik de weer-dataset heb geladen met behulp van pandas. In plaats van met gewone Python-lijsten te werken, heb ik nu gebruikgemaakt van pandas **Series**- en **DataFrame**-objecten. Een Series is vergelijkbaar met een Python-lijst, terwijl een DataFrame lijkt op een tweedimensionale lijst of een MySQL-tabel.

### Wat ik heb gedaan:

1. **Jupyter Notebook aangemaakt**:
   - Ik heb een nieuw Jupyter Notebook opgezet om mijn data-analyse te starten.

2. **Data ingeladen in een Pandas DataFrame**:
   - Ik heb de weer-dataset geladen in een DataFrame-object en dit object weergegeven in het Jupyter Notebook.

3. **Methodes gebruikt**:
   - Ik heb de methodes `head()`, `tail()`, `describe()`, en `info()` toegepast om informatie over de dataset te verkrijgen.
     - `head()`: Toont de eerste paar rijen van de dataset.
     - `tail()`: Toont de laatste paar rijen van de dataset.
     - `describe()`: Geeft een statistische beschrijving van de dataset.
     - `info()`: Biedt informatie over de kolommen en datatypes in de dataset.

4. **Gemiddelde temperatuur**:
   - Ik heb onderzocht welke functie de gemiddelde temperatuur in Nederland laat zien. Dit bleek de `mean()` functie te zijn die wordt toegepast op de relevante kolom in de DataFrame.

### Leerdoelen

- **DataFrame-object**: Ik heb geleerd hoe ik een DataFrame-object kan gebruiken om data efficiënt te verwerken.
- **Descriptive Functions**: Ik heb kennisgemaakt met verschillende functies die helpen om inzicht te verkrijgen in de dataset, zoals `describe()`, `head()`, `tail()`, en `info()`.
- **CSV-bestand laden**: Ik heb geleerd hoe ik een CSV-bestand kan laden als een DataFrame-object met behulp van de `read_csv` functie van pandas.

### Verwachte uitkomst

- **Jupyter Notebook**: Na het installeren van de benodigde libraries uit `requirements.txt` kan ik de Jupyter Notebook openen en de gegevens bekijken.
- **Dataset geladen**: De weer-dataset is geladen met de functie `read_csv` en opgeslagen in een variabele.
- **Output**: De output van de methodes `head()`, `describe()`, `info()`, en `tail()` is zichtbaar in het Jupyter Notebook.

Met deze oefening heb ik mijn vaardigheden in het gebruik van pandas verbeterd en mijn kennis over data-analyse uitgebreid.
