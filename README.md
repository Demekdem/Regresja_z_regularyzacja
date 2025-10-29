# Projekt analizy danych sensorycznych z wykorzystaniem regresji z regularyzacją

## Cel projektu
Analiza predykcyjna zmiennej sensor_measurement_4 na podstawie odczytów pozostałych czujników z wykorzystaniem różnych metod regularyzacji w modelach regresji liniowej.

W kontekście biznesowym projekt może wspierać monitorowanie i optymalizację procesów przemysłowych w oparciu o dane z czujników.

## Etapy 
1. Przygotowanie danych - wczytanie i oczyszczenie zbioru, eliminacja zmiennych nieprzydatnych do modelowania

2. Selekcja zmiennych - samodzielna analiza i dobór cech objaśniających z uzasadnieniem wykluczenia poszczególnych zmiennych

3. Budowa modeli:
 
- model regresji liniowej 

- model Ridge z regularyzacją L2

- model Lasso z regularyzacją L1

- model Elastic Net z regularyzacją mieszaną L1+L2

5. Dobór parametrów - uzasadnienie wyboru wartości lambda dla każdego modelu regularyzacji

6. Porównanie wyników - analiza współczynników determinacji oraz interpretacja różnic między dopasowaniem treningowym i testowym

## Opis projektu
Projekt pokazuje, jak można przewidywać parametry systemu za pomocą metod regularyzacji, które pomagają poprawić ogólne działanie modeli i zapobiegają ich przeuczeniu.
