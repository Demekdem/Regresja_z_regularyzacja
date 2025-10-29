# Budowa modeli regresji z regularyzacją na danych sensorycznych

## Cel projektu
Analiza predykcyjna zmiennej `sensor_measurement_4`na podstawie odczytów pozostałych czujników z wykorzystaniem różnych metod regularyzacji w modelach regresji liniowej.

W kontekście biznesowym projekt może wspierać monitorowanie i optymalizację procesów przemysłowych w oparciu o dane z czujników.

## Etapy 
1. Przygotowanie danych - wczytanie i oczyszczenie zbioru, eliminacja zmiennych nieprzydatnych do modelowania

2. Selekcja zmiennych - samodzielna analiza i dobór cech objaśniających z uzasadnieniem wykluczenia poszczególnych zmiennych

3. Budowa modeli:
 
- regresja liniowa

- Ridge (L2)

- Lasso (L1)

- Elastic Net (L1+L2)

4. Dobór parametrów - uzasadnienie wyboru wartości lambda dla poszczególnych modeli

5. Porównanie wyników - analiza R^2 oraz interpretacja różnic między dopasowaniem treningowym i testowym

## Opis projektu
Projekt pokazuje, jak metody regularyzacji wpływają na działanie modeli regresji. W tym przypadku regularyzacja nie poprawiła wyników, ale pozwoliła lepiej zrozumieć wpływ poszczególnych zmiennych i ocenić stabilność predykcji.
