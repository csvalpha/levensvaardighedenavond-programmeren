# Levensvaardighedenavond Programmeren

Welkom allemaal bij deze avond waar we jullie de basis van de programmeertaal Python willen leren. Hiervoor verwachten we dat jullie het volgende installeren:
- Python 3.9
- PyCharm

In de secties hieronder zullen we uitleggen hoe deze geïnstalleerd kunnen worden.

## Python
1. Download de installer voor jouw besturingssysteem hier: https://www.python.org/downloads/release/python-390/
    - Voor Windows, kies de 'Windows x86-64 executable installer'
    - Voor MacOS, kies de 'macOS 64-bit installer'
2. Selecteer bij het eerste installatiescherm het vakje 'Add Python 3.9 to PATH' en volg de standaard installatie instructies

Voor een uitgebreide handleiding kun je deze site raadplegen: https://realpython.com/installing-python/

## PyCharm
Naast Python is het handig om een programma te hebben waar we de code in kunnen schrijven. Onze voorkeur gaat uit naar PyCharm van JetBrains.
1. Download PyCharm van: https://www.jetbrains.com/pycharm/ (De Professional versie is gratis te krijgen als je je registreert met je studentenaccount. Je kan ook de gratis Community versie installeren.)
2. Open PyCharm na het installeren en klik op "New Project".
3. Maak een nieuw project aan volgens de stappen op [deze site](https://www.jetbrains.com/help/pycharm/creating-and-running-your-first-python-project.html#creating-simple-project) naam "levensvaardighedenavond".
4. Wanneer het project geopend is, kopieer dan alle bestanden uit deze repo naar de map van dit project (dit is waarschijnlijk in `C:\Gebruikers\[Gebruikersnaam]\PyCharmProjects\levensvaardighedenavond` of `Users/[Gebruikersnaam]/PyCharmProjects\levensvaardighedenavond`). Je kan een zipje met de bestanden downloaden door hier rechtsboven op de groene knop "Code" te klikken.
5. Klik nu met de rechtermuisknop op de map `snake` en klik op "Mark Directory as -> Sources Root" .

## Requirements installeren
Als laatste moeten er nog wat extra dingen geïnstalleerd worden. Dit kan je doen door in PyCharm onderin op Terminal te klikken en het volgende in te typen: `pip install -r requirements.txt`, gevolgd door een Enter.

## Start het spel
Om het spel te starten kunnen je met de rechtermuisknop klikken op het bestand `main.py` in het `snake` mapje -> "Run 'main'".
