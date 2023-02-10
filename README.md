# Model wielowymiarowy

Z danych z pliku csv utworzyłam model wielowymiarowy w OLAP (tabela z miarami - tabela faktów, do niej dopięte tabele wymiarów).
Następnie za pomocą Analysis Services dodałam klucze główne i stworzyłam relacje pomiędzy tabelami oraz wygenerowałam kostkę wielowymiarową.


Zawartość projektu:
- Projekt Integration Services -> pakiety ładujące dane i przekształcające je na model wielowymiarowy (tabela faktów + tabele wymiarów)
- Projekt Analysis Services -> przetworzona struktura wielowymiarowa w kostkę MOLAP

Wykorzystano:
- Visual Studio 2019
- Microsoft SQL Server
