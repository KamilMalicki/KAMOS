KAMOS - Prosty System Operacyjny
Czym jest KAMOS?
KAMOS to minimalistyczny system operacyjny stworzony jako projekt edukacyjny. Jest to prosty system wzorowany na 16-bitowych rozwiązaniach, ale bez ich ograniczeń. System ten oferuje podstawowe funkcje do interakcji z użytkownikiem i zarządzania danymi na dysku.

## Funkcje systemu
System KAMOS 1.0 oferuje następujące polecenia:

# LOAD - Wczytuje dane z wybranego sektora dysku

Po wpisaniu polecenia system poprosi o numer sektora

Wyświetli zawartość tego sektora

# SAVE - Zapisuje dane do wybranego sektora dysku

Po wpisaniu polecenia system poprosi o numer sektora

Następnie poprosi o wprowadzenie danych do zapisania

Dane zostaną zapisane na dysku

# INFO - Wyświetla informacje o systemie

Pokazuje wersję systemu

Wyświetla informacje o autorze

Zawiera link do projektu na GitHubie

# EXIT - Kończy pracę systemu

Po wpisaniu tego polecenia system wyświetla komunikat o zakończeniu pracy

Należy wyłączyć komputer ręcznie

Jak korzystać z systemu?
Po uruchomieniu system wyświetla powitalny komunikat "Welcome to the kernel 1.0 !"

System pokazuje znak zachęty #, po którym można wpisywać polecenia

Wpisz jedno z dostępnych poleceń i naciśnij Enter

Postępuj zgodnie z instrukcjami wyświetlanymi na ekranie

## Przykładowa sesja 
Welcome to the kernel 1.0 !

# INFO


INFO: Kernel version 1.0
Jest to prosty system operacyjny wzorowany na 16 bitowej wersji systemu KAMOS...
Autor: Kamil Malicki
Wersja: 1.0
Github: github.com/KamilMalicki/KAMOS

# SAVE

Enter sector to WRITE: 5

Enter data to save: To jest moja wiadomość testowa

Message saved to disk (sector 5): To jest moja wiadomość testowa

# LOAD

Enter sector to READ: 5

Message read from disk (sector 5): To jest moja wiadomość testowa

# EXIT

Exiting kernel...

Press power button to turn off the computer.
Informacje dodatkowe
System został stworzony przez Kamila Malickiego jako projekt demonstracyjny i edukacyjny. Kod źródłowy jest dostępny na GitHubie pod adresem: github.com/KamilMalicki/KAMOS
