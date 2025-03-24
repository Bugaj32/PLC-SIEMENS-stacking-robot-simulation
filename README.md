Załączone pliki są częścią prezentacji projektu wykonanego w celu rozwijania moich umiejętności programowania sterowników rodziny Siemens wraz z interfejsami HMI. Projekt ten jest efektem pracy nad praktycznym wykorzystaniem zdobytych przeze mnie  umiejętności i może posłużyć jako przykład mojego podejścia do rozwiązywania problemów w dziedzinie automatyki. 

Zadanie i funkcje stanowiska:
Program jest odpowiedzialny za sterowanie dwuosiowym manipulatorem który układa wybraną przez operatora liczbę produktów w skrzyniach, jednocześnie identyfikując aktualny produkt i przypisując mu parametry zapisane w bazie receptur w bloku danych sterownika PLC. 

Śledzenie danych:
Każda skrzynka posiada własny log w którym zapisywana jest aktualna kolejność ułożonych produktów w stosie, ich właściwości, całkowita masa skrzyni oraz indywidualny numer do identyfikacji skrzynki. Następnie wszystkie te informacje zapisywane są w osobnym bloku danych, który może być wykorzystany przez następną maszynę. 

Algorytmy:
W programie zaimplementowano sekwencje sterowania dwuosiowym manipulatorem, algorytm wyszukiwania zapisanych właściwości zidentyfikowanego wcześniej produktu w bloku danych, skalowanie wejść i wyjść analogowych manipulatora, edycję bloku danych receptur z poziomu HMI. 

Panel HMI:
Panel operatora zawiera ogólny widok zlecenia oraz aktualnego stosu, komunikaty błędów, okno sterowania pracą maszyny, okno pracy ręcznej, edycję bloku danych receptur, okno edycji pozycji manipulatora, widok stanu wejść i wyjść cyfrowych.
