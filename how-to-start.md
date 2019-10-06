# Jak zacząć

## Spis streści
TODO: Wstawić spis

## Wstęp
Początek przygody z programowaniem może być całkiem trudnym wyzwaniem. Przede wszystkim mamy przed sobą mnóstwo, nie zawsze wartościowych, informacji. Potem pojawiają się problemy związane z ich segregacją, a następnie prawidłową kategoryzacją. <br />
Z tego powodu postanowiliśmy udostępnić Wam - przyszłym programistom - zbiór materiałów porządkujący
najważniejsze informacje o nowoczesnym webdevie. Mamy nadzieję, że prezentowane i udostępniane tutaj treści ułatwią Wam zdobywanie i poszerzanie wiedzy o obecnej 'webówce'.

## Od tekstu do strony
Pewnie każdy słyszał o HTMLu. Ten legendarny język znaczników (nie programowania) już od 25 lat umożliwia nam, zwykłym zjadaczom chleba, na wyświetlanie tekstu na ekranach naszych urządzeń. Jednak jak to się dzieje, że wpisując www.github.com/Rekseto/PolishWebDevForBeginners otrzymujemy jeden z najbardziej przydatnych spisów treści dla początkujących webdevelperów?

Najpierw coś oczywistego - część widoczna od strony użytkownika:
1. Wpisujemy adres strony do przeglądarki
2. Czekamy od mniej niż sekundy do kilkunastu sekund na załadowanie się strony
3. Zamykamy 10 okienek inforumująch o newsletterach, RODO (GIODO), ciasteczkach itp.
4. Cieszymy się stroną

Teraz zobaczmy jak to wygląda w uproszczeniu od strony maszyny:
1. Bierzemy daną *domenę* i wysyłamy odpowiednie *zapytanie* do **serwera DNS**. Orzymujemy adres zgodny z *IPv4* lub *IPv6*, wskazujący na inny serwer. Tłumacząc na język "człowieków": Wpisany adres (albo jego część) wysyłamy do innego komputera trzymającego listę  wszystkich adresów w internecie (zapisanych w postaci tekstu). Ten komputer szuka naszego adresu i jeśli on istnieje to wysyła do nas informacje zwrotną w której umieszczony jest adres prowadzący do innego komputera (zapisany w postaci cyferek i kropek). Czyli np. dla wpisanego www.facebook.com/jakis-smieszny-link do **serwera DNS** wysyłany jest adres www.facebook.com. W odpowiedzi powinniśmy uzyskać np. 69.63.184.142
2. Orzymujemy odpowiedź od serwera, jeśli strona istnieje idziemy dalej
3. Kierujemy się pod uzyskany adres. Tam ponownie wysyłamy nasze *zapytanie*. Dodatkowo (poza pełnym adresem strony) w *zapytaniu* mogą być inne informacje np. dotyczące imienia użytkownika.
4. Serwer, który jest najczęściej *hostowany*, przetwarza nasze zapytanie i zwraca *klientowi*, czyli naszemu komputerowi (ale nie nam bezpośrednio), odpowiedź w postaci pliku tekstowego. Tłumacząc:
Inny komputer (ten na który wskazuje "numerkowy adres"), który jest najczęściej wynajmowany przez osobę posiadjącą stronę, analizuje to co mu wysłaliśmy i tworzy plik tekstowy (zazwyczaj w postaci pliku HTML, ale nie zawsze!), a następnie nam go wysyła
5. Nasza przeglądarka wykorzystuje swoją maszynę do renderingu (dla Firefoxa będzie to Gecko, a dla Google Chrome będzie to Chromium), a następnie, jeśli to konieczne, wysyła kolejne zapytania (HTML może zawierać informacje na temat dodatkowych plików potrzebnych do załadowania strony)
6. Wyświetlamy odpowiednią treść użytkownikowi

Tak w skrócie to wygląda 
 
## Popularne języki
W dobie dzisiejszego internetu możemy wyróżnić kilka kluczowych technologii umożliwiających bezproblemowe kreowanie i modyfikowanie treści. Są nimi:
* **HTML (HyperText Markup Language)** - język znaczników (a nie programowania!) pozwalający na określenie celu w jakim został stworzony każdy element strony. Dla przykładu, pozwala on na 'powiedzenie' przeglądarce, że dany tekst jest artykułem, a tekst poniżej jest np. nóżką strony.

* **CSS (Cascading Style Sheets)** - jest to zbiór reguł, wedle których przeglądarka interpretuje, a następnie wyświetla wszelkie treści wizualne jak np. kolory, marginesy, czy pogrubienie tekstu.

* **JS (Javascript)** - język programowania mający ogomną ilość zastosowań. Wykorzystuje się go między innymi do frontendu, czyli dziedziny w której programista skupia się na wyglądzie aplikacji i prezentacji danych. Dodatkowo JS jest stosunkowo prostym i potężnym narzędziem w pracy przy backendzie, będącym niejako odwrotnością frontendu. Programowanie backendowe polega głównie na kontrolowaniu wszystkiego co dzieje się w 'bebechach' strony - połączenia z bazą danych, zwracania odpowiedniej strony po wpisaniu adresu 'google.com' itp.

* **PHP (Personal Home Page, PHP Hypertext Preprocessor)** - język programowania mający zastosowanie w backendzie. Możemy nazywać go nieśmiertelnym dinozaurem, gdyż 'umiera' (wychodzi z użytku) już od ponad dekady. Co jest interesujące, jego nowe wersje są bardzo szybkie, wydajne i bezpieczne, zaś sam język jest fundamentem dla ponad 60% stron internetowych.

* **SQL (Structured Query Language)** - język służący do operacji na bazach danych (opartych głównie na relacjach, cokolwiek to słowo dla Was teraz znaczy)

* **NoSQL (Not Only SQL)**

* **GIT** - system kontroli wersji. Służy do kontrolowania zmian w projekcie, ułatwia pracę zepołową i umożliwia szybki wgląd i edycję historii projektu.

<!-- @TODO extend content -->
