# Quiz-App-React-Bootstrap-
Quiz App (React + Bootstrap)

Prosta aplikacja quizowa w React 18, stylowana przy pomocy Bootstrapa. Użytkownik odpowiada na pytania z pliku questions.json, może przechodzić między pytaniami, a aplikacja zlicza punkty i oznacza poprawne/niepoprawne odpowiedzi.

Funkcje

Nawigacja między pytaniami (Prev / Next).

Sprawdzanie poprawności odpowiedzi.

Zliczanie punktów.

Oznaczanie odpowiedzi kolorami (bg-success, bg-danger).

Struktura komponentów

App – punkt startowy, ładuje QuizComponent.

QuizComponent – logika quizu (stan pytań, punktów, wybory).

Question – wyświetla treść i numer pytania.

Answers – lista odpowiedzi (deleguje do Table).

Actions – przyciski Prev / Next.

Results – pokazuje wynik.

Test1 / Test2 – przykłady komponentów klasowego i funkcyjnego z hookami.

Technologie

React 18

Bootstrap 5

Create React App (CRA)

Uruchomienie
