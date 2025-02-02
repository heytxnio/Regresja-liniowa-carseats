# Regresja liniowa

## Opis projektu
Sprawozdanie z przedmiotu Regresja i Analiza Wariancji. Przeprowadzenie analizy regresji liniowej na zbiorze danych `Carseats` z pakietu `ISLR`. Celem analizy jest zbadanie zależności między zmiennymi objaśniającymi a sprzedażą fotelików samochodowych.

## Wykorzystane technologie
Projekt został zrealizowany w języku R z wykorzystaniem następujących pakietów:
- `tidyverse` - operacje na danych i wizualizacje,
- `ISLR` - dostęp do zbioru danych `Carseats`,
- `lmtest` - testy statystyczne dla modeli regresji,
- `caret` - podział zbioru danych na zestawy treningowe i testowe.

Aby uruchomić kod, należy zainstalować i załadować następujące pakiety w języku R:
```r
install.packages(c("tidyverse", "ISLR", "caret", "ggcorrplot", "car", "broom", "lmtest"))
```

## Kroki analizy
1. **Eksploracja danych**: obliczenie podstawowych statystyk, analiza korelacji między zmiennymi.
2. **Wizualizacja danych**: wykresy punktowe oraz boxploty dla zmiennych objaśniających.
3. **Podział danych**: na zbiór treningowy (75%) i testowy (25%).
4. **Regresja liniowa prosta**.
5. **Regresja liniowa wieloraka**.
6. **Podsumowanie**.



