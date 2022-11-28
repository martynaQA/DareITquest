# TASK 1
## Subtask 1

8/10

## Subtask 3

Zdecydowałam się na udział w projekcie, ponieważ w grudniu zaczynam pierwszą pracę jako tester oprogramowania i chciałam się wdrożyć w rytm pracy testera. Chciałam też odświeżyć sobie wiadomości, które przyswoiłam w 2020 roku podczas kursu testera manualnego w jednej ze szkół programowania. Projekt traktuję jako okazję do sprawdzenia siebie. Bardzo zależy mi na feedbacku, bo dzięki temu będę mogła bardziej się rozwijać i lepiej wykonywać swoją pracę.

## Subtask 4

#### Na czym polega ta aplikacja? Do czego służy?
Zgodnie z informacją ze strony głównej aplikacji jest to Panel zarządzania graczami, meczami i do tworzenia raportów. Aplikacja pozwala na tworzenie profilów graczy, dodawanie do nich meczy, generowanie raportów. Można również filtrować graczy na liście po różnych parametrach,  

#### Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)

#### Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?

Interfejs aplikacji przywodzi na myśl Internet z lat 90. Układ treści na stronie jest niezbyt intuicyjny oraz niezgodny z dobrymi praktykami UX - po lewej stronie i na dole zostało dość dużo pustej przestrzeni. 

#### Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).

W polu linki pomocnicze znajduje się link do panelu dodawania gracza, ale na tym intuicyjność się kończy. Moduł dodawania meczu i raportu jest dostępny dopiero po wejściu w profil konkretnego gracza. Kafelki z informacjami na górze strony głównej są nieklikalne i dość ogólnie opisane - trudno domyślić się co obrazują te dane liczbowe.

#### Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)

- mało intuicyjna nawigacja
- UX - złe rozmieszczenie elementów na stronie (pusta przestrzeń na dolnej części strony)
- w wersji polskiej część tekstów jest w języku angielskim
- w panelu dodawania gracza - możliwość uzupełnienia pól dowolnymi znakami (brak walidacji formatów, np. adres@email.com albo DD/MM/RRRR), możliwość wpisania nierealnych wartości (np. w polu wzrost lub waga). Można również podać datę urodzenia z przyszłości.
- nie jestem pewna czy to błąd, ale każdy użytkownik (niezależnie od loginu) ma te same uprawnienia edycji graczy i innych parametrów. Sprawdziłabym specyfikację wymagań i doprecyzowałabym, czy rzeczywiście każdy użytkownik może edytować wpisy innych użytkowników.
- formularz tworzenia profilu gracza oraz formularz tworzenia meczu zawiera bardzo wiele pól, ale tylko niektóre dane są wyświetlane w tabeli z listą graczy
- w panelu gracza w module raporty kliknięcie w button "+ dodaj raport" przenosi użytkownika do modułu mecze. Faktyczna możliwość dodania raportu pojawia się dopiero w module mecze, jako przedostatni atrybut wiersza na liście meczów. Kolumna ta jest widoczna dopiero po przescrollowaniu strony w poziomie (niezgodne z dobrymi praktykami UX).
- ścieżka dodawania raportu jest mało intuicyjna. Kiedy już odnajdziemy właściwy button (strona główna -> gracze -> kliknięcie w wiersz danego gracza -> moduł mecze -> dodaj raport), użytkownik przenoszony jest do widoku, w którym widać tylko tytuł, ID gracza oraz ID meczu (brak możliwości edycji żadnego parametru) oraz przyciski clear i submit. Po kliknięciu w przycisk "clear" nic się nie dzieje. Po kliknięciu przycisku submit użytkownik jest przenoszony do formularza edycji raportu, w którym jest kilka edytowalnych pól, kilka pól bez możliwości edycji oraz button save. Po kliknięciu w przycisk save wyświetla się komunikat o zapisaniu zmian. Aby zobaczyć raport uzytkownik musi z lewego menu wybrać moduł raporty i przeskrollować na sam dół strony, gdyż najnowsze raporty pojawiają się właśnie tam (odwróciłabym kolejność wyświetlania lub dodałabym możliwość wyboru sortowania w kolumnach). 
- sam formularz raportu pozwala na dodanie bardzo dużej ilości tekstu w jednym polu - sprawdziłabym czy jest to zdefiniowane w wymaganiach
- filtrowanie jest dostępne tylko dla widoku listy graczy. Po wejściu w profil konkretnego gracza nie ma możliwości filtrowania meczu na liście meczów lub raportu na liście raportów. 
- brak możliwości podglądu raportu. Jest możliwość wyświetlenia raportu wyłącznie w trybie edycji
- jest możliwość pobrania listy graczy do pliku CSV, jednak pobierane jest tylko 10 rekordów (chociaż baza zawiera ich zdecydowanie więcej). Tylko kilka kolumn wyświetla dane poprawnie (imię, nazwisko, klub, recenzja). W kolumnie wiek zamiast liczby podana jest data urodzenia - należy rozważyć zmianę formatowania lub zmianę nazwy kolumny. Kolumna mecze oraz kolumna raporty wyświetlają dane jako [object Object].


# TASK 2

## Subtask 1 i 2
https://drive.google.com/drive/folders/1j8Wfk8uaA3xm0arqU-0d7dMT6mdQvuiY?usp=sharing

## Subtask 3

Dlaczego piszemy przypadki testowe? Przede wszystkim po to, aby zyskać pewność, że przetestowaliśmy wszystkie funkcjonalności aplikacji. To również ważne, aby zapewnić porządek w dokumentacji - dzięki temu inni współpracownicy będą mieli jasny i klarowny komunikat o tym, któte funkcje zostały przetestowane, w jakim zakresie i z jakim skutkiem.

# TASK 3



# TASK 4

## Subtask 1 i 2
https://docs.google.com/spreadsheets/d/1eTtsT2IT_e-fJ3Ru2bSVD5c__e5AF6Puqe0QcjdXRjA/edit?usp=sharing

## Subtask 3

1. Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?

Aplikacja gromadzi w jednym miejscu materiały, nagrania, muzykę i informacje, które pomagają w wykształceniu nawyku medytacji i pomagają użytkownikowi dbać o swój well-being w wybranych obszarach zdrowia psychicznego (redukcja stresu, łatwiejsze zasypianie, rozwój itd).

2. Kto ma być użytkownikiem końcowym aplikacji?

Użytkownikiem końcowym powinna być osoba, która chce się nauczyć medytacji i rozwijać się w tym zakresie (poznawać najlepsze techniki).

3. Czy według Ciebie aplikacja jest user friendly? (Przyjazna dla użytkownika- np. wchodzisz do aplikacji i szybko łapiesz do czego służą przyciski. Poczytaj na ten temat w internecie- co to znaczy, że aplikacja jest przyjazna dla użytkownika)

Według mnie aplikacja jest user friendly z małymi wyjątkami. Nawigacja nie jest bardzo skomplikowana, ale materiały w kategoriach wyświetlają się w losowej kolejności i to jest trochę mylące (użytkownik może się zgubić). Problematyczne było dla mnie zrozumienie pierwszej sekcji (funkcja dzień/noc - screen w załączniku) na głównym ekranie (pierwszy widok). Próbowałam przesunąć w lewo, żeby odkryć opcję noc, a okazało się, że trzeba tapnąć (po przesunięciu przeniosłam się do kolejnego widoku). Zdziwiła mnie też tak duża różnica między polską i angielską wersją językową aplikacji.

[IMG_6061](https://user-images.githubusercontent.com/116759119/203377590-33518331-c743-41c4-87e3-b45cd23dfd9c.jpg)

4. Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność? (Żeby nie było: nie jest to aplikacja przy której pracuję, takie pytania pojawiają się na rozmowach rekrutacyjnych dlatego dobrze jest to przećwiczyć :D )

Ujednoliciłabym wersje językowe. Poprawiłabym kategorie, żeby wyświetlany content był bardziej relevant. Aplikacja wymaga bardzo szybkiego łącza z Internetem - może dałoby się jakoś to poprawić, żeby nie wykluczać osób z obszarów, na których szybkie łącze jest problemem? Dobrze byłoby, żeby zmiana wersji językowej nie powodowała usunięcie danych użytkownika (postępów itd).

5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?

Aplikacja natywna jest pisana pod urządzenie mobilne, więc na pewno będzie zawierała mniej błędów UX niż aplikacja internetowa, która nie jest dedykowana urządzeniom mobilnym i może się na nich źle wyświetlać (np. zmienia się kolejność elementów na stronie, teksty są ucięte, scrollowanie może być uciążliwe). Aplikację internetową można przetestować w przeglądarce, aplikację natywną na wirtualnym urządzeniu mobilnym lub na rzeczywistym urządzeniu mobilnym.

(Przy tym pytaniu nie jestem pewna, bo aplikację internetową rozumiem jako aplikację webową, a aplikacja natywna to aplikacja mobilna? Jeśli tak to unikałabym tego wyrażenia, bo natywność to chyba cecha aplikacji mobilnej (np. natywna na iOS pisana w Swifcie lub na Androida pisana w Kotlinie/Javie, a inne aplikacje np. w Xamarinie to aplkacje cross-platformowe).

## Subtask 4

https://qa768.atlassian.net/jira/software/projects/QAC/boards/1

# TASK 5

## Subtask 1

SELECT * FROM

SELECT certainitem FROM nazwabazy WHERE exampleitemid = certainvalue
SELECT certainitem, anotheritem, anothervalue FROM nazwabazy WHERE exampleitemid > certainvalue
SELECT certainitem, anotheritem, anothervalue FROM nazwabazy WHERE exampleitemid BETWEEN certainvalue AND anothervalue
SELECT certainitem FROM nazwabazy WHERE exampleitemparameter = 'tujakaswartoscnieliczbowa'

SELECT certainitem FROM nazwabazy WHERE examplename = 'E%'
SELECT certainitem FROM nazwabazy WHERE examplename = '%Example%'
SELECT certainitem FROM nazwabazy WHERE examplename = 'Example1, _'

ORDER BY Parametr DESC
ORDER BY Parameter ASC

AND
OR
IS NOT NULL
IS NULL
IN

SELECT DATEDIFF
GETDATE()
AS
SELECT COUNT(*)
SELECT MIN(nazwabazy)
SELECT SUM(nazwabazy)

JOIN
ON

## Subtask 2

Wyświetlić się zawartość tabeli “actors”

SELECT * FROM 'actors'

<img width="570" alt="subtask2" src="https://user-images.githubusercontent.com/116759119/204396627-5a10f1c9-b2cb-4fe2-9cdf-1e7b6f516f53.png">


## Subtask 3

1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

<img width="596" alt="subtask3point1" src="https://user-images.githubusercontent.com/116759119/204396725-474b8601-08f7-4ba7-9106-cd4653c31863.png">

2. Wyświetl film, który powstał w 2019 roku.

<img width="587" alt="subtask3point2" src="https://user-images.githubusercontent.com/116759119/204396746-345f1a5e-beaf-4bbf-b68c-e0ead797e8cd.png">

3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

<img width="584" alt="SUBTASK3point3" src="https://user-images.githubusercontent.com/116759119/204396774-abca51c3-29b2-4622-9523-65acb6579af5.png">

4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$ 

<img width="769" alt="subtask3point4" src="https://user-images.githubusercontent.com/116759119/204396795-3aeeaa74-4dbe-434c-b3fa-eb9a35989df0.png">

5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

<img width="751" alt="subtask3point5" src="https://user-images.githubusercontent.com/116759119/204396835-cdbdf7cf-0bd2-44fb-8c37-e91b42571ef3.png">

6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny. 

<img width="770" alt="subtask3point66" src="https://user-images.githubusercontent.com/116759119/204396847-e335897d-ae27-46d7-bd50-7f7f86929bb9.png">

7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN. 

<img width="766" alt="subtask3point7" src="https://user-images.githubusercontent.com/116759119/204396861-99d0bc29-e4ba-4c36-9a2c-f6a26bab1e2f.png">

8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.

<img width="774" alt="subtask3point8" src="https://user-images.githubusercontent.com/116759119/204396888-7edd80cb-0981-4367-bf36-d000d1231347.png">

9. Wyświetl dane klienta, który nie ma podanego adresu email.

<img width="770" alt="subtask3point9" src="https://user-images.githubusercontent.com/116759119/204396916-43349c66-6cc7-4c3e-b8ef-738b16742fcf.png">

10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

<img width="779" alt="subtask3pointTEN" src="https://user-images.githubusercontent.com/116759119/204396938-a811405f-83fc-4265-ad6c-4ba8e5fb80b2.png">


