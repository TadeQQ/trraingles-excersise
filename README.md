Problem: Parametry trójkąta [C#, mono]
Napisz program, który ze standardowego wejścia wczyta trzy liczby określające długości boków pewnego trójkąta. Liczby te są podane w postaci zmiennoprzecinkowej, z dokładnością do dwóch miejsc po przecinku, w jednej linii, oddzielone średnikiem i jedną spacją. Liczby podane są w formacie "en-US" (z kropką dziesiętną).

Następnie, zweryfikuj poprawność danych, w podanej kolejności:

Jeśli którakolwiek z podanych liczb jest niedodatnia, wypisz komunikat Błędne dane. Długości boków muszą być dodatnie! i przerwij działanie programu.
Jeśli z podanych długości boków nie można zbudować trójkąta, wypisz komunikat: Błędne dane. Trójkąta nie można zbudować! i przerwij działanie programu. (UWAGA: dopuszczamy trójkąt, którego boki się pokrywają, o polu zerowym).
Jeśli dane są poprawne, wykonaj obliczenia z dokładnością do 2 miejsc po przecinku i wypisz na standardowe wyjście komunikaty:

obwód = {obwód} - z dokładnością 2 miejsc po przecinku,,
pole = {pole} - z dokładnością 2 miejsc po przecinku
trójkąt jest {typ}, gdzie typ jest jednym z napisów: prostokątny, ostrokątny, rozwartokątny.
W ostatniej linii, jeśli trójkąt jest równoboczny, wypisz komunikat trójkąt równoboczny, zaś jeśli jest równoramienny, wypisz komunikat trójkąt równoramienny.
