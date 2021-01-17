
Zadanie jest przeznaczone do wykonania w wybranym sieciowym środowisku playground w Swifcie (np. http://online.swiftplayground.run, https://repl.it/languages/swift ).

W przypadku posiadania komputera marki Apple możliwość wykonania zadania w Xcode w języku Swift lub Objective-C.

Używając danych 2 załącznika stwórz aplikację składającą się z co najmniej tych 2 elementów:

- klasy imitującej interfejs użytkownika TodoViewControler (patrz załącznik)

- klasy zarządzającej wszystkimi operacjami na zadaniach

Aplikacja musi być zdolna do:

- dodania nowego do istniejących już 'todo' załadowanych z powyższej listy, tytuł oraz status wykonania powinien być uzyskany z metody imitującej pole tekstowe oraz checkmark
- dodania nowego wpisu zeruje pole tekstowe, jeśli pole tekstowe nie zawiera tytułu potraktuj to jako błąd I obsłuż wyjątek
- edycji statusu wykonania i usunięcia “TODO“ o wybranym ID, jeśli ID nie istnieje obsłuż wyjątek i poinformuj użytkownika imitacją alertu
- wyświetlenia danych o wszystkich “TODO“
- zaprezentuj przykładowe użycie powyższych zdolności

WSKAZOWKA

Możesz używać wszystkich elementów dostępnych we framework’u Foundation

