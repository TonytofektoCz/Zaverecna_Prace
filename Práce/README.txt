# Scraping výsledků voleb 2017

## Popis projektu
Tento projekt scrapuje výsledky voleb 2017 pro daný územní celek z webu volby.cz a ukládá je do souboru CSV.

## Instalace
1. Vytvořte virtuální prostředí:

    python -m venv venv
    source venv/bin/activate  # Pro Windows použijte `venv\Scripts\activate`


2. Nainstalujte potřebné knihovny:

    pip install -r requirements.txt


## Použití
Spusťte skript s následujícími argumenty:

python volby17.py "<URL>" "<vystupni_soubor.csv>"
