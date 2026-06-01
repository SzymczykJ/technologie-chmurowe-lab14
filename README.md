Utworzenie i uruchomienie wszystkich kontenerów w tle (flaga -d sprawia, że procesy nie blokują terminala). 
![](Zrzut%20ekranu%202026-06-01%20192452.png)
Wyświetlenie statusu kontenerów, stanu ich zdrowia (healthcheck) oraz przekierowań portów sieciowych. 
![](Zrzut%20ekranu%202026-06-01%20193510.png)
Wyświetlenie domyślnej strony startowej w celu potwierdzenia poprawnej integracji serwera Nginx z procesorem PHP-FPM (dynamiczny odczyt wersji oprogramowania bezpośrednio z kontenerów). 
![](Zrzut%20ekranu%202026-06-01%20192738.png)
Wyświetlenie graficznego interfejsu panelu phpMyAdmin w celu uwierzytelnienia administratora (`root`) przed uzyskaniem dostępu do bazy danych MySQL. 


Pomyślne zalogowanie do serwera MySQL i zainicjalizowanie bazy danych o nazwie `testowa_baza` (widocznej na liście po lewej stronie), co ostatecznie potwierdza poprawną integrację wolumenów danych. 

