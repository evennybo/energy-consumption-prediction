# Prediksjon av strømforbruk
## Prosjektmål
Dette prosjektet predikerer strømforbruk for de neste 30 dagene ved bruk av Prophet-modellen. Målet er å identifisere trender og optimalisere energibruk.

## Datasett
- Kilde: Open Power Systems Data
- Kolonner brukt: DE_load_actual_entsoe_transparency (Tyskland)

## Teknologi brukt
- Python (pandas, matplotlib, prophet)
- Modell: Facebook Prophet for tid-serieanalyse

## Resultater
- Prediksjonene indikerer en jevn trend med ukentlige variasjoner.
- Gjennomsnittlig feilmål (MAE): [Sett inn verdi]

## Hvordan kjøre prosjektet
1. Klon dette repositoriet.
2. Installer avhengigheter: `pip install -r requirements.txt`
3. Kjør `main.py` for å generere prediksjoner.
