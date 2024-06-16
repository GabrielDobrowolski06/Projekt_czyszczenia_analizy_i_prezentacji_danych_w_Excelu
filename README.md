# Projekt_czyszczenia_analizy_i_prezentacji_danych_w_Excelu
Mój projekt w Excelu, gdzie skupiam się głównie na poprawieniu przejrzystości tabeli danych oraz prezentacji dashboardu


Dane zawierają osiem kolumn:

ID - Unikalny identyfikator dla każdego wpisu

Name - Imię osoby, w niektórych przypadkach z dodatkowymi spacjami na początku i końcu

Date - Losowo wygenerowana data w przeszłości (do 1000 dni wstecz)

Amount - Losowa wartość pieniężna w zakresie od 10,5 do 5000,5

Category - Losowo przypisana kategoria (A, B, C, D, E)

Description - Opis, w niektórych przypadkach z dodatkowymi spacjami na początku i końcu

Status - Status wpisu (Nowy, W trakcie, Zakończony, Wstrzymany)

Email - Adres e-mail powiązany z każdym wpisem

Gender - Płeć osoby (M lub F)

Children - Liczba dzieci (od 0 do 8, z przewagą wartości 1 i 2)


Usuwam kolumny Description oraz Email, ponieważ nie będzie przydatna podczas analizy danych i tworzenia dashbordów


Dodaje nową kolumnę Date by day, gdzie nie będzie godzin, a następnie kopiuję te wartości do Date


Kasuje duplikaty


Używam funkcji TRIM aby wyeliminować niepotrzebne spacje


Zmieniam kolumne Gender, aby F = Female, a M = Male


Stwarzam nową kolumnę, gdzie 5 lub więcej dzieci danego pracownika to "5 +"


Sortuje wszystko względem kolumny ID asc


Tworzę pivot tables, wykresy i dashboard (razem z slicers)
