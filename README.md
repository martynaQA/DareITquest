# Samples of test cases
https://drive.google.com/drive/folders/1j8Wfk8uaA3xm0arqU-0d7dMT6mdQvuiY?usp=sharing

# Samples of SQL requests

## Subtask 1

Wyświetlić zawartość tabeli “actors”

SELECT * FROM 'actors'

<img width="570" alt="subtask2" src="https://user-images.githubusercontent.com/116759119/204396627-5a10f1c9-b2cb-4fe2-9cdf-1e7b6f516f53.png">

## Subtask 2

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

## Subtask 3

11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈

<img width="744" alt="sql11" src="https://user-images.githubusercontent.com/116759119/205977805-b236fb7d-85a3-47d0-905f-4d9a9c913c4e.png">

12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.

13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: [pati@mail.com](mailto:pati@mail.com)

<img width="658" alt="sql13" src="https://user-images.githubusercontent.com/116759119/205977846-e8b6ef15-f6f7-49dc-91ab-1d019261621d.png">

14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).

15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag

16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.

<img width="443" alt="SQL16" src="https://user-images.githubusercontent.com/116759119/205977888-09871fa6-705e-4d24-85cc-91cf98224b86.png">

17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)

18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).

19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał

<img width="658" alt="sql19" src="https://user-images.githubusercontent.com/116759119/205977948-a5a288e7-cd15-45e1-99f8-bd8a45827c08.png">

20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = [honia@mail.com](mailto:honia@mail.com) oraz pseudonym = Hoa

<img width="764" alt="sql20" src="https://user-images.githubusercontent.com/116759119/205977991-019c75f2-5c14-4fc2-b35d-7ec08d23ee72.png">

## Subtask 4

<img width="906" alt="quiz-wyniki" src="https://user-images.githubusercontent.com/116759119/205976821-fc7e6f28-f642-40c1-8dfe-c511b3232d2f.png">





