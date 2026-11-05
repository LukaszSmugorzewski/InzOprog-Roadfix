1. Tytuł projektu: Roadfix - aplikacja mobilna dla kierowców do szybszego wzywania pomocy drogowej

2. Zespół:

Łukasz Smugorzewski 180638 IO2  github: LukaszSmugorzewski

Wojciech Żyra 180652 IO2 github: Wojciechzyra

3. Idea i problem:
Projekt rozwiązuje problem stresującego i nieefektywnego procesu wzywania pomocy drogowej w przypadku awarii pojazdu. Z aplikacji będą korzystać kierowcy samochodów osobowych, którzy potrzebują wsparcia na drodze. System funkcjonuje jako zamknięte rozwiązanie dedykowane dla jednej firmy pomocy drogowej, łącząc aplikację kliencką z panelem dyspozytorskim. Obecnie użytkownik w stresie musi szukać numerów i telefonicznie tłumaczyć swoją lokalizację. Dzięki naszemu rozwiązaniu aplikacja automatycznie pobierze współrzędne GPS zdarzenia (lub umożliwi ręczne wpisanie adresu w przypadku braku sygnału czy zgody na udostępnienie lokalizacji) i wyśle natychmiastowe powiadomienie do panelu dyspozytora. Zapewni to usprawnienie procesu zgłaszania i redukcję pomyłek komunikacyjnych. Użytkownik będzie spokojniejszy, mając wgląd w aktualizowany przez dyspozytora status wezwania. Ważne: Aplikacja służy wyłącznie do wzywania pomocy technicznej i nie zastępuje numerów alarmowych – w przypadku bezpośredniego zagrożenia życia lub zdrowia użytkownik powinien dzwonić pod numer 112.

4. Użytkownicy i scenariusz:
Użytkownicy:

Kierowcy samochodów osobowych (zgłaszający awarię w aplikacji mobilnej)

Dyspozytorzy (odbierający zgłoszenia poprzez dedykowany panel webowy Roadfix)

Kierowcy lawet (tylko w ramach rozszerzenia systemu – udostępniający swoją lokalizację z terminala w pojeździe)

Scenariusz: Użytkownik rejestruje się w aplikacji (podając e-mail wyłącznie do korespondencji oraz weryfikując numer telefonu jako unikalny login). W momencie awarii loguje się i wybiera opcję "Wezwij pomoc". System pobiera współrzędne GPS (jeśli sygnał jest niedostępny lub użytkownik odmówi dostępu, wpisuje on adres ręcznie). Użytkownik dopisuje dane pojazdu (marka, kolor, nr rejestracyjny), dołącza opcjonalne zdjęcia i wysyła zgłoszenie. Aby uniknąć spamu, użytkownik może mieć tylko jedno aktywne zgłoszenie naraz. System wysyła powiadomienie do panelu dyspozytora, nadając status "Oczekujące na dyspozytora". Dyspozytor odbiera dane (lokalizacja/adres, auto, zdjęcia) i przypisuje lawetę, zmieniając status na "Laweta w drodze". W przypadku chwilowego braku wolnego sprzętu, dyspozytor może nadać status "Oczekujące na sprzęt" (kolejkowanie zgłoszenia). Dopiero w ostateczności (np. wezwanie poza obszarem działania firmy lub fałszywy alarm) dyspozytor może zmienić status na "Odrzucone", podając krótki powód, który wyświetli się użytkownikowi. Dane wrażliwe (telefon, dokładna lokalizacja, zdjęcia) są widoczne dla dyspozytora tylko do czasu zakończenia usługi. Po zrealizowaniu lub odrzuceniu wezwania, zgłoszenie trafia do zarchiwizowanej historii. W archiwum systemu (przechowywanym zgodnie z polityką prywatności firmy na potrzeby statystyk i reklamacji) dane wrażliwe zostają zamazane (zanonimizowane), a dostępna pozostaje jedynie historia ogólna: data, status końcowy, marka pojazdu i ewentualny powód odrzucenia. W ramach planowanego rozszerzenia użytkownik będzie mógł śledzić pozycję przypisanej lawety na mapie (dane będą pobierane ze zintegrowanego modułu GPS w lawecie lub dedykowanej prostej aplikacji dla kierowcy lawety).

5. Zakres funkcjonalny:
F01: Użytkownik może zarejestrować i zalogować się do konta przy użyciu numeru telefonu z weryfikacją (e-mail służy jedynie do późniejszej korespondencji) (Zakres: MVP).
F02: Użytkownik może udostępnić lokalizację zdarzenia poprzez automatyczny odczyt współrzędnych GPS lub ręczne wpisanie adresu, gdy GPS nie jest dostępny lub użytkownik nie wyrazi zgody na dostęp do lokalizacji (Zakres: MVP).
F03: Użytkownik może podać podstawowe dane swojego pojazdu (marka, kolor, numer rejestracyjny), aby ułatwić identyfikację na drodze (Zakres: MVP).
F04: Dyspozytor (korzystając z wewnętrznego panelu webowego) może odebrać powiadomienie o zgłoszeniu, przypisać lawetę i zarządzać jego statusem: Oczekujące na dyspozytora, Przyjęte, Oczekujące na sprzęt, Laweta w drodze, Zakończone, Odrzucone (wraz z dodaniem powodu) (Zakres: MVP).
F05: Użytkownik może sprawdzić zaktualizowany status swojego pojedynczego, bieżącego zgłoszenia oraz odczytać dodatkowe komunikaty (np. o kolejkowaniu lub powód ewentualnego odrzucenia) (Zakres: MVP).
F06: Użytkownik może dodać opcjonalne zdjęcie uszkodzonego pojazdu lub sytuacji na drodze, co ułatwi dyspozytorowi dobór sprzętu (Zakres: MVP).
F07: Użytkownik może śledzić na wbudowanej mapie dokładne położenie jadącej do niego lawety, bazujące na danych o lokalizacji przesyłanych z osobnego urządzenia/modułu GPS kierowcy lawety (Zakres: Rozszerzenie).
F08: Użytkownik może podpiąć kartę płatniczą i opłacić usługę bezpośrednio w aplikacji (Zakres: Rozszerzenie).

6. Poza Zakresem:

Wbudowany czat tekstowy na żywo i połączenia głosowe (VoIP) bezpośrednio w aplikacji między użytkownikiem a kierowcą lawety.

Tryb offline: funkcja pozwalająca na wysłanie zgłoszenia wraz z koordynatami GPS za pomocą zakodowanej wiadomości SMS w przypadku całkowitego braku zasięgu internetu na trasie.

7. Organizacja Współpracy:
Wstępny podział zadań: Łukasz zajmie się projektowaniem interfejsu (aplikacja mobilna) oraz funkcjonalnościami MVP, Wojciech odpowiedzialny będzie za bazę danych, architekturę panelu dyspozytora oraz dokumentację.
Komunikacja: aplikacja Discord i spotkania na uczelni.
Aktualizacja ustaleń: plik README na GitHub.

8. Odnośniki:
GitHub - https://github.com/LukaszSmugorzewski/InzOprog-Roadfix
Labochat - https://roadfix.labochat.com/
