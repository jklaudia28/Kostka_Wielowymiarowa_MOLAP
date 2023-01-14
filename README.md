# Model-wielowymiarowy-w-OLAP

Z danych z pliku csv utworzyłam model wielowymiarowy w OLAP (tabela z miarami - tabela faktów, do niej dopięte tabele wymiarów).
Następnie za pomocą Analysis Services dodałam klucze główne i stworzylam relacje pomiędzy tabelami oraz wygenerowałam kostkę wielomiarową.


Zawartość projektu:
- Projekt Integration Services -> pakiety ładujące dane i przekształcające je na model wielowymiarowy (tabela faktów + tabele wymiarów)
- Projekt Analysis Services -> przetworzona struktura wielowymiarowa w kostkę MOLAP
