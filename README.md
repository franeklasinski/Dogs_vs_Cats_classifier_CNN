# Dogs vs Cats Classifier

Projekt: Klasyfikacja obrazów kotów i psów z użyciem Convolutional Neural Network (CNN) w PyTorch.

## Opis
Ten projekt to kompletny pipeline do rozpoznawania kotów i psów na zdjęciach. Zawiera:
- Przygotowanie i augmentację danych
- Definicję modelu CNN
- Pętlę treningową i walidacyjną
- Testowanie na osobnym zbiorze
- Wizualizację wyników i predykcji

## Struktura katalogów
```
archive-2/
    train/
        cats/
        dogs/
    test/
        cats/
        dogs/
```

## Wymagania
- Python 3.8+
- PyTorch
- torchvision
- matplotlib
- numpy
- tensorboard (opcjonalnie)

Instalacja zależności:
```bash
pip install torch torchvision matplotlib numpy tensorboard
```

## Uruchomienie
1. Umieść dane w strukturze jak wyżej.
2. Otwórz notebook w Jupyter Notebook lub VSCode.
3. Uruchom komórki po kolei:
    - Przygotowanie danych
    - Definicja modelu
    - Trening
    - Testowanie i wizualizacja

## Najważniejsze pliki
- `Dogs_vs_Cats_classifier.ipynb` – główny notebook z kodem
- `README.md` – ten plik

## Wyniki
- Model trenuje na zbiorze `train`, testuje na `test`.
- Po treningu wyświetlane są przykładowe predykcje oraz wykresy strat i dokładności.

## Autor
Projekt stworzony do klasyfikacji obrazów z użyciem sieci neuronowych w PyTorch.
Franciszek Łasiński 
