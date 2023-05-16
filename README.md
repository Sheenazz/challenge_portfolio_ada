# Task 1
## Subtask 1
9 punktów :).
## Subtask 3
Zdecydowałam się na udział w Portfolio challenge, ponieważ w poprzednich pracach odkryłam swój talent do bycia dokładną, a także mam frajdę w znajdywaniu błędów. Postanowiłam więc spróbować swoich sił w testowaniu. Jako, że brałam udział w programie mentoringowym Dare IT, wiedziałam, że będzie to dobry jakościowo kurs. Podoba mi się też, że jest nastawiony na zdobycie praktycznych umiejętności, a na tym mi zależało.

Moim celem jest wstępne przekonanie się czy testowanie to coś dla mnie, czy właśnie tu jest ukryta nisza, w której się odnajdę. Liczę, że dzięki projektowi poznam podstawy testowania, zrobię swój pierwszy projekt i poznam nowe osoby dzielące te same zainteresowania, z którymi będziemy się motywować i wspierać w znalezieniu pierwszej pracy.

**Link do mojego folderu projektowego w Google Drive:** [Challenge portfolio](https://drive.google.com/drive/folders/1hax-jaVoWcHCva8wGOgDqQFPxJeRWTLD?usp=share_link) 

## Subtask 4
Aplikacja służy do zarządzania graczami, meczami i do tworzenia raportów.



Funkcjonalności:
* zalogowanie/wylogowanie:
  - przypomnienie hasła
  - zmiana języka na angielski podczas logowania
* możliwość skontaktowania się przez Slack z Dev team
* dodanie nowego gracza:
  - dane gracza
  - opcja dodania języków jakimi się posługuje
  - opcja dodania linka z Youtube'a
  - opcja zatwierdzenia lub wyczyszczenia wpisanych informacji
* dodanie meczu
* dodanie  raportu
* przeglądnięcie dostępnych meczów i raportów dla zawodnika i możliwość ich edycji
* w zakładce gracze, możliwość:
  - filtrowania graczy
  - pobrania pliku CSV wszystkich graczy z informacją o nich
  - wydruku tych informacji
  - wyświetlania kolumn w zależności od ustawionych filtrów
* wyszukiwarka 



Interfejs aplikacji:
Interfejs jest prosty i przejrzysty, ale mógłby być bardziej intuicyjny. Nie wszystkie funkcje są zrozumiałe. Do zmiany:
- dodałabym przeniesienie na stronę główną po kliknięciu w Scouts Panel w lewym górnym rogu
- w zakładce meczu niezrozumiałe pole "General" - co tam trzeba wpisać?
- pod edycją meczu jest lista zdarzeń - czego? I czemu nic się tam nie wyświetla i niczego nie można dodać (czy to błąd?)
- w zakładce edycji raportu przycisk "save" przesuwa się razem z przesuwaniem stron - źle to wygląda
- ciężko się czyta podpowiedzi do sekcji "wstęp" itd., czasem brakuje spacji, tekst się zlewa
- nie bardzo rozumiem opcje "rozpocznij mecz" - nie zrozumiałam jak to działa, jak dodać jakąś akcję (czy to błąd?)
- możliwość dodania nieskończonej liczby połów meczu - bez sensu. (czy to błąd?)
- raport mógłby być inaczej skonstruowany, teraz jest dla mnie chaotyczny


# Task 2
## Subtask 3
**Przypadki testowe** piszemy po to by udokumentować użycie funkcjonalności aplikacji oraz by sprawdzić czy one działają. To uchroni nas przed błędami po wypuszczeniu aplikacji, zaoszczędzi dodatkowej pracy, zaoszczędzi pieniądze jeśli przez błędy byłyby nałożone kary pieniężne. Jeśli unikniemy błędów pokaże to firmę w dobrym świetle w oczach klienta. Również dla nowo przyjętych osób osób przypadki testowe są źródłem wiedzy o działaniu aplikacji.
Pisanie przypadków testowych jest też przydatne przy automatyzacji testów, ponieważ kroki jakie powinny być zautomatyzowane są dokładnie opisane.


# Task 4
## Subtask 3

1.	Aplikacja służy do:
- sprzedawania i kupowania produktów
- wystawiania ogłoszeń np. wynajmu mieszkania
- wystawiania ofert pracy
- oferowania usług

Jej celem jest ułatwienie procesów związanych ze sprzedażą, kupnem, wynajmem, szukaniem pracy, oferowaniem usług itd. Jej celem jest również aspekt finansowy, firma bogaci się np. na opłatach za promowanie ogłoszenia.

2.	Użytkownikiem końcowym jest osoba, która korzysta z oferowanych przez OLX usług czy to przez sprzedanie swojego produktu, czy osoba, która coś kupuje, osoba, która nawiązuje kontakt w sprawie wynajmu mieszkania, osoba, która znajduje pracę itd.

3.	Uważam, że tak. Aplikacja OLX jest user friendly. Jest czytelna, przyciski są dobrze opisane, jest szybka (nie zacina się, nie ładuje się za długo). Zakładki są dobrze opisane, kontakt między użytkownikami jest ułatwiony. Wyszukiwanie jest proste, dodawanie ogłoszenia również.

4.	
Poprawa funkcjonalności nr 1:
Kiedy wchodzimy np. w zakładkę „Praca”, wybieramy kategorie i przeglądamy oferty klikając „cofnij” przenosi nas do strony głównej. Uważam, że lepiej byłoby gdyby przenosiło użytkownika z powrotem do wyboru kategorii pracy. Przeklikiwanie się od początku zajmuje więcej czasu i jest (dla mnie) nieintuicyjne.

Poprawa funkcjonalności nr 2:
Nie rozumiem czym różni się kategoria „Usługi” i „Usługi i Firmy”. Wchodząc w kategorię „Usługi” i dalej np. „Budowa i remont”, dalej „Prace zewnętrzne” widzę ogłoszenia typu „kubek”, „obciążniki do ćwiczeń”, „sukienka mieniąca”, mało co związane jest z faktycznie z budową i remontem, wygląda to trochę jak śmietnik, do którego wszystko wpada. Koniecznie bym to poprawiła.

5.	Różnice między testowaniem aplikacji internetowych i natywnych:


| n/a | Aplikacja internetowa |	Aplikacja natywna |
| --- | --------------------- | ----------------- |
| Trzeba zwrócić uwagę wygodę korzystania z niej palcami | Nie | Tak |
| Sprawdzenie czy ekran się nie przekręca |	Nie	| Tak |
| Łatwiejszy dostęp ze strony głównej do wszystkich kategorii |	Tak |	Nie |
| Dostęp do informacji o aplikacji | Tak | Nie |

