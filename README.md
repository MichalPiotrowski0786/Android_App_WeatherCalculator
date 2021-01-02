# Android_Projekt
Projekt zaliczeniowy z Android Studio

Stworzyliśmy aplikacje meteorologiczną, działającą w systemie Android.
Pozwala ona na obliczenie temperatury punktu rosy na podstawie wilgotności oraz podanej temperatury, 
a także na obliczenie wilgotności na podstawie temperatury punku rosy oraz temperatury.

Jak obliczyć?
1. Wybieramy suwakiem wartość, którą chcemy obliczyć.
2. Wpisujemy temperaturę powietrza.
3. Podajemy wartość jednostki innej niż obliczana 
(przykładowo, chcąc obliczyć punkt rosy, podajemy wilgotność powietrza).
4. (Dodatkowo) Z reguły wartość wilgotności powietrza jest w przedziale 0%-100%, a wartość temperatury punktu rosy nie może być wyższa niż temperatura powietrza.
5. Zatwierdzamy wprowadzone wartości przyciskiem "Oblicz".
6. Wynik ukazuje się w dolnej części ekranu smartphone'a.

Proces działania kodu:

+ Stworzenie Stringa z symbolem Celsiusa, i dwóch zmiennych dla wprowadzonej wartości i temperatury
+ Stworzenie zmiennej od switch'a
+ Pobranie informacji o dwóch wartościach wprowadzonych
+ Następnie, zamienienie ich na floaty
+ Sprawdzenie if-else if, która z opcji jest wybrana
+ Dla punktu rosy: obliczenie za pomocą formuły odpowiedniej wartości, 
przekonwertowanie wyniku do Stringa i zrobienie Toasta z wynikiem
+ Dla wilgotności: podzielenie temperatury przez punkt rosy co daje wynik, 
przekonwertowanie wyniku do Stringa i zrobienie Toasta z wynikiem

Wykorzystane funkcje:

+ View
+ EditText
+ Switch
+ Toast
+ Java.Math
+ boolean
+ parseFloat
+ String.valueOf()

Kompatybilność z wersjami android(SDK): 
minimum: 23(6.0)
docelowe: 30(11.0)
