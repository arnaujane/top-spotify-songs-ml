# Cas Kaggle · Spotify

Anàlisi exploratòria de [Top Spotify songs from 2010–2019](https://www.kaggle.com/datasets/leonardopena/top-spotify-songs-from-20102019-by-year). L’objectiu inicial és estimar la puntuació de popularitat (`pop`).

- [Notebook únic](notebooks/projecte.ipynb)
- [Informe](informe.md)

## Execució

Amb Python 3.14, des d’aquesta carpeta:

```bash
python -m pip install -r requirements.txt
jupyter lab
```

Obriu `notebooks/projecte.ipynb` i executeu-lo de dalt a baix. El fitxer `data/top10s.csv` original fa servir codificació `cp1252`. El test es reserva per artista amb llavor 42.
