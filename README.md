# DataVista Student Insights

Projekt do analizy danych studentow z wykorzystaniem Pythona, Pandas i wizualizacji (Seaborn/Matplotlib).

## Wymagania

- Python 3.10+
- pip

## Instalacja

```bash
pip install -r requirements.txt
```

## Uruchamianie

1. Analiza z poziomu skryptu:

```bash
python data_analysis_main.py dataset.csv
```

Mozesz tez podac inny plik wejsciowy `.csv`, `.xls` lub `.xlsx`.

2. Praca w notebooku:

```bash
jupyter notebook
```

Nastepnie otworz `data_analize.ipynb`.

## Co generuje skrypt

Skrypt zapisuje statystyki do katalogu `results/`, m.in.:

- `results/numerical_statistics.csv`
- `results/categorical_statistics.csv`

W kodzie sa tez przygotowane funkcje do wykresow i redukcji wymiarow (PCA, t-SNE), ktore mozna wlaczyc w sekcji `if __name__ == '__main__':`.

## Struktura projektu

```text
MsidProject/
|-- data_analysis_main.py
|-- loader.py
|-- dataset.csv
|-- data_analize.ipynb
|-- development of the first machine learning models.ipynb
|-- final project of machine learning.ipynb
|-- requirements.txt
|-- README.md
|-- results.txt
`-- anaconda_projects/
```

## Autor

Blazej Kowal (2025)
