1. tytuł projektu: roadfix - aplikacja mobilna dla kierowców do szybszego wzywania pomocy drogowej

2. Zespół: 
- Łukasz Smugorzewski 180638 IO2 LukaszSmugorzewski
- Wojciech Żyra 180652 IO2 Wojciechzyra

3. Idea i problem: 
Projekt rozwiązuje problem stresującego i nieefektywnego procesu wzywania pomocy drogowej w przypadku awarii pojazdu. Z aplikacji będą korzystać kierowcy samochodów osobowych, którzy potrzebują wsparcia na drodze. Obecnie użytkownik w sytuacji stresowej musi szukać numerów do lokalnych firm holowniczych, a następnie telefonicznie tłumaczyć dyspozytorowi swoją dokładną lokalizację na podstawie nieznanych punktów orientacyjnych. Dzięki naszemu rozwiązaniu kierowca zyska możliwość wezwania lawety kilkoma kliknięciami. Aplikacja automatycznie pobierze dokładne współrzędne GPS zdarzenia i prześle je do dyspozytora. Zapewni to usprawnienie procesu zgłaszania i redukcję pomyłek komunikacyjnych. Dodatkowo użytkownik zyska spokój ducha, mając podgląd na status swojego zgłoszenia na żywo. System eliminuje barierę komunikacyjną, która często wydłuża czas oczekiwania na niebezpiecznym poboczu.

4. Użytkownicy i scenariusz:
Użytkownicy: 
-kierowcy samochodów osobowych (zgłaszający awarię)
-Dyspozytorzy (odbierający zgłoszenia)
scenariusz: Użytkownik rejestruje się w aplikacji (podając swój e-mail do korespondencji oraz weryfikując numer telefonu, który staje się jego loginem). W momencie awarii na drodze, loguje się na swoje konto i wybiera opcję "Wezwij pomoc". System automatycznie pobiera jego lokalizację GPS (jeśli użytkownik odmówi dostępu do GPS, to wpisuje adres ręcznie). Użytkownik dopisuje jedynie dane pojazdu, którym aktualnie się porusza (marka, kolor, nr rejestracyjny) oraz dołącza zdjęcia zdarzenia i opcjonalny opis. W efekcie dyspozytor otrzymuje pełen i zweryfikowany pakiet informacji (lokalizacja, auto, zdjęcia), a użytkownik zyskuje trwały podgląd na status zgłoszenia i śledzenie lawety na mapie. 

5. Zakres funkcjonalny:
F01: Użytkownik może zarejestrować i zalogować się do konta przy użyciu numeru telefonu z weryfikacją (Zakres: MVP).

F02: Użytkownik może udostępnić lokalizację zdarzenia poprzez automatyczny odczyt GPS lub ręczne wpisanie adresu w przypadku braku sygnału (Zakres: MVP).

F03: Użytkownik może podać podstawowe dane swojego pojazdu (marka, kolor, numer rejestracyjny), aby ułatwić identyfikację na drodze (Zakres: MVP).

F04: Dyspozytor może odebrać nowe zgłoszenie i zmienić jego status – np. Oczekujące, Laweta w drodze, Zakończone (Zakres: MVP).

F05: Użytkownik może sprawdzić zaktualizowany status swojego bieżącego zgłoszenia (Zakres: MVP).

F06: Użytkownik może dodać zdjęcie uszkodzonego pojazdu lub sytuacji na drodze, co ułatwi dyspozytorowi dobór odpowiedniego sprzętu. (Zakres: MVP),

F07: Użytkownik może śledzić na wbudowanej mapie dokładne położenie jadącej do niego lawety (Zakres: MVP).

F08: Użytkownik może podpiąć kartę płatniczą i opłacić usługę bezpośrednio w aplikacji (Zakres: Rozszerzenie).

6. Poza Zakresem: 
-Wbudowany czat tekstowy na żywo i połączenia głosowe (VoIP) bezpośrednio w aplikacji między użytkownikiem a kierowcą lawety

-tryb offline: funkcja pozwalająca na wysłanie zgłoszenia wraz z koordynatami GPS za pomocą zakodowanej wiadomości SMS w przypadku całkowitego braku zasięgu internetu na trasie.

7. Organizacja Współpracy:
Wstępny podział zadań: Łukasz zajmie się projektowaniem interfejsu oraz funkcjonalnościami MVP, Wojciech odpowiedzialny będzie za bazę danych oraz dokumentację techniczną.
komunikacja: aplikacja discord i spotkania na uczelni.
aktualizacja ustaleń: plik readme na github

8. odnośniki:
github - https://github.com/LukaszSmugorzewski/InzOprog-Roadfix
labochat - https://roadfix.labochat.com/
