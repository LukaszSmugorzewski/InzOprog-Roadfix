1. Tytuł projektu: Roadfix - aplikacja mobilna dla kierowców do szybszego wzywania pomocy drogowej

2. Zespół:

Łukasz Smugorzewski 180638 IO2 LukaszSmugorzewski

Wojciech Żyra 180652 IO2 Wojciechzyra

3. Idea i problem:
Projekt rozwiązuje problem stresującego i nieefektywnego procesu wzywania pomocy drogowej w przypadku awarii pojazdu. Z aplikacji będą korzystać kierowcy samochodów osobowych, którzy potrzebują wsparcia na drodze. Obecnie użytkownik w sytuacji stresowej musi szukać numerów do lokalnych firm holowniczych, a następnie telefonicznie tłumaczyć dyspozytorowi swoją dokładną lokalizację na podstawie nieznanych punktów orientacyjnych. Dzięki naszemu rozwiązaniu kierowca zyska możliwość wezwania lawety kilkoma kliknięciami. Aplikacja automatycznie pobierze dokładne współrzędne GPS zdarzenia i prześle je do dyspozytora. Zapewni to usprawnienie procesu zgłaszania i redukcję pomyłek komunikacyjnych. Dodatkowo użytkownik zyska spokój ducha, mając wgląd w aktualizowany przez dyspozytora status swojego zgłoszenia. System eliminuje barierę komunikacyjną, która często wydłuża czas oczekiwania na niebezpiecznym poboczu.

4. Użytkownicy i scenariusz:
Użytkownicy:

Kierowcy samochodów osobowych (zgłaszający awarię)

Dyspozytorzy (odbierający zgłoszenia)

Scenariusz: Użytkownik rejestruje się w aplikacji (podając e-mail wyłącznie do celów korespondencji oraz weryfikując numer telefonu, który staje się jego unikalnym loginem). W momencie awarii na drodze, loguje się na swoje konto i wybiera opcję "Wezwij pomoc". System automatycznie pobiera jego lokalizację GPS (jeśli użytkownik odmówi dostępu do GPS lub sygnał jest niedostępny, wpisuje adres ręcznie). Użytkownik dopisuje jedynie dane pojazdu, którym aktualnie się porusza (marka, kolor, nr rejestracyjny) oraz dołącza opcjonalne zdjęcia zdarzenia i krótki opis. W efekcie dyspozytor otrzymuje pakiet informacji podanych przez użytkownika oraz jego lokalizację, po czym w swoim systemie przypisuje do zgłoszenia konkretną lawetę. Użytkownik zyskuje wgląd w status zgłoszenia (np. "Przyjęte", a po przypisaniu "Laweta w drodze"). W ramach planowanego rozszerzenia systemu użytkownik będzie mógł również śledzić pozycję przypisanej lawety na mapie.

5. Zakres funkcjonalny:
F01: Użytkownik może zarejestrować i zalogować się do konta przy użyciu numeru telefonu z weryfikacją (e-mail służy jedynie do późniejszej korespondencji) (Zakres: MVP).
F02: Użytkownik może udostępnić lokalizację zdarzenia poprzez automatyczny odczyt GPS lub ręczne wpisanie adresu, gdy GPS nie jest dostępny lub użytkownik nie wyrazi zgody (Zakres: MVP).
F03: Użytkownik może podać podstawowe dane swojego pojazdu (marka, kolor, numer rejestracyjny), aby ułatwić identyfikację na drodze (Zakres: MVP).
F04: Dyspozytor może odebrać nowe zgłoszenie, przypisać do niego lawetę i zmienić jego status – np. Przyjęte, Laweta w drodze, Zakończone (Zakres: MVP).
F05: Użytkownik może sprawdzić zaktualizowany status swojego bieżącego zgłoszenia (Zakres: MVP).
F06: Użytkownik może dodać opcjonalne zdjęcie uszkodzonego pojazdu lub sytuacji na drodze, co ułatwi dyspozytorowi dobór odpowiedniego sprzętu (Zakres: MVP).
F07: Użytkownik może śledzić na wbudowanej mapie dokładne położenie jadącej do niego lawety, bazujące na danych o lokalizacji przesyłanych z urządzenia przypisanego kierowcy (Zakres: Rozszerzenie).
F08: Użytkownik może podpiąć kartę płatniczą i opłacić usługę bezpośrednio w aplikacji (Zakres: Rozszerzenie).

6. Poza Zakresem:

Wbudowany czat tekstowy na żywo i połączenia głosowe (VoIP) bezpośrednio w aplikacji między użytkownikiem a kierowcą lawety.

Tryb offline: funkcja pozwalająca na wysłanie zgłoszenia wraz z koordynatami GPS za pomocą zakodowanej wiadomości SMS w przypadku całkowitego braku zasięgu internetu na trasie.

7. Organizacja Współpracy:
Wstępny podział zadań: Łukasz zajmie się projektowaniem interfejsu oraz funkcjonalnościami MVP, Wojciech odpowiedzialny będzie za bazę danych oraz dokumentację techniczną.
Komunikacja: aplikacja Discord i spotkania na uczelni.
Aktualizacja ustaleń: plik README na GitHub.

8. Odnośniki:
GitHub - https://github.com/LukaszSmugorzewski/InzOprog-Roadfix
Labochat - https://roadfix.labochat.com/
