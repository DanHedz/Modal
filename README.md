# Modal
Deklaracja stałych i funkcji:
Definiuje stałą "actionBtn" jako odwołanie do elementu na stronie o klasie "action-btn".
Funkcja "modal" przyjmuje obiekt "body" jako argument i zwraca ciąg znaków reprezentujący kod HTML dla modala na podstawie podanych parametrów.
Funkcja "createModal":
Tworzy nowy element div o klasie "modal-container".
Wstawia kod HTML modala (wygenerowany przez funkcję "modal") do tego elementu.
Dodaje utworzony element do ciała dokumentu.
Dodaje obsługę zamknięcia modalu na kliknięcie przycisku z ikoną zamknięcia ("X").
Dodaje obsługę zamknięcia modalu na kliknięcie przycisków akcji ("Tak" i "Nie").
Ustawia fokus na modalu, aby użytkownik mógł go obsługiwać za pomocą klawiatury.
Dodaje obsługę klawisza "Escape" do zamknięcia modalu.
Dodaje obsługę zamknięcia modalu po kliknięciu na obszar z klasą "modal-container".
Obsługa przycisku "actionBtn":
Wywołuje funkcję "addToBasket" po kliknięciu na przycisk o klasie "action-btn".
Funkcja "addToBasket" wywołuje funkcję "createModal" z argumentami konfigurującymi modal. Modal będzie miał ikonę ostrzeżenia, tytuł "Lorem ipsum dolor title", opis "lorem ipusm description bla bla bla cos tam jeszcze chcialem" oraz przyciski "Zaakceptuj" i "Anuluj".
Obsługa przycisku "actionTwoBtn":
Dodaje nasłuchiwanie na przycisk o klasie "action-two-btn".
Po kliknięciu na ten przycisk wywołuje funkcję "createModal" z innymi argumentami konfigurującymi modal. Modal będzie miał ikonę niebezpieczeństwa, tytuł "Drugi tekst modala" oraz opis " lorem lorem lorem lorem lorem ", a przyciski będą nazywać się "Ok" i "Nie".
Obsługa przycisku "actionThreeBtn":
Dodaje nasłuchiwanie na przycisk o klasie "action-three-btn".
Po kliknięciu na ten przycisk wywołuje funkcję "createModal" bez podawania argumentów, co spowoduje utworzenie modalu z domyślnymi wartościami (brak ikony, tytułu i opisu) oraz przyciskami "Tak" i "Nie".
To jest ogólna charakterystyka kodu, który tworzy i obsługuje proste modale w HTML, CSS i JavaScript. Modale są popularnym elementem interfejsu użytkownika, które pozwalają na prezentację ważnych informacji i prośby o potwierdzenie przed wykonaniem pewnych akcji na stronie.
