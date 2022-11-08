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
