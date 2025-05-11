# Administracja Botem i Reaction Roles

Reaction Roles (RR) jest sposobem automatycznego nadawania roli dla użytkownika. Rola nadawana jest przez bota BOOMFinity.

Cele RR:
1. Weryfikacja nowego użytkownika
2. Nadawanie roli posiadacza sprzetu lub przynależności do zespołu.

## Administracja botem - OGÓLNE

Zaloguj się na panel administracyjny bota https://boomfinity.xyz/manage/servers i wybierz serwer. 
W Ustawieniach wybierz OGÓLNE i zmień prefix na ?? ![obraz](https://github.com/user-attachments/assets/1c10c06d-f9ce-4a06-b71c-8f9366068936)

Wybierz kanał "modlog" dla funkcji Modlog
![obraz](https://github.com/user-attachments/assets/edc7a473-7551-41dc-9e7a-d54cbd54c8d9)

Włącz autorolę i wybierz wolę "DO WERYFIKACJI" 
![obraz](https://github.com/user-attachments/assets/02b5a48e-7496-44b4-8346-a54d94c53504)

## Administracja botem - POWITANIA

W ustawieniach bota wejdź w Powitania i włącz je.

Wybierz kanał powitań na WELCOME

![obraz](https://github.com/user-attachments/assets/022d1807-1219-4cc9-8777-bc211b2a2d9a)

Dodaj własny tytuł powitania

![obraz](https://github.com/user-attachments/assets/3f44b624-7285-4b37-828a-fe17d971f6e4)

Dodaj tekst powitania:
Witaj {MENTION}! Prosimy o ukończenie weryfikacji na kanale #weryfikacja.
Welcome {MENTION}! Please verify yourself on #weryfikacja channel.

![obraz](https://github.com/user-attachments/assets/c034fbac-4ac3-44e8-a355-61e4bf99ecc7)


## Administracja botem - ZABEZPIECZENIA

W ustawieniach bota wybierz opcję Zabezpieczenia i włącz cztery pierwsze opcje:

![obraz](https://github.com/user-attachments/assets/0eaffbc7-0099-42d7-9b7e-c910b611bb9e)

## Administracja botem - AutoModerator

W ustawieniach bota wybierz opcję AutoModerator i wyłącz wszystkie opcje poza pierwszą:

![obraz](https://github.com/user-attachments/assets/525c9a8a-45fa-41fc-8796-e117b3c550ba)

# REACTION ROLES - wydokujemy na serwerze discord

**NADAJ SOBIE ROLĘ "ZWERYFIKOWANY UCZESTNIK", NAJEDŹ NA SWÓJ PROFIL I PRAWYM PRZYCISKIEM MYSZY NA ROLI WYWOŁAJ MENU, SKOPIUJ ID ROLI I ZAPISZ GDZIEŚ W NOTATNIKU!!**


![obraz](https://github.com/user-attachments/assets/68529756-a2d2-433f-99aa-f361a3324661)


Znajdź kanał *polecenia* w kategorii admin zone.
Wpisuj zastępujące komendy w pole wysyłania wiadomości i wyślij je

Stworzenie RR:
```
??rr create
```
Kliknij prawym przyciskiem wyszy na kanał *#weryfikacja* i skopiuj ID Kanału.

Dodanie kanału dla RR:
```
rr channel (wklej ID kanału)
```
Dodanie opisu, oczywiście można mofyfikować. Nową linię dodajemy za pomocą *shift+enter*
```
rr desc Cześć, witamy na serwerze Ossowa w ramach imprezy Skorpion 2025! Prosimy o weryfikację czy nie jesteś botem.

Hi, welcome to Ossowa server for Skorpion 2025 event! Please verify yourself that you are not a bot.
```
Nadanie nazwy RR:
```
rr name weryfikacja
```
Wyłaczenie prywatnej wiadomości z nadaniem roli:
```
rr notify
```
Zmiana trybu nadawania roli:
```
rr mode
```
Dodanie roli serwera do RR:
```
rr roles
```
Dodanie konkretnej roli:
```
rr add (wklej ID Roli)
```
Dodanie emoji, która której wybranie danaje rolę:
Wszystkie emoji w Discordzie zaczynają się i kończą na *:*, staramy się używać domyślych emoji dostarczonych w discordzie. Uzycie emoji innego serwera spowoduje błąd (bot nie ma do niej dostępu). 
Jeżeli chcesz dodać własną emoji do serwera możesz zrobić to w menu serwera. Wtedy taka emoji jest dostępna dla bota i RR. 
```
rr emoji :ok: 
```
Zatwierdzenie zmian:
```
rr submit
```
Powrót do poprzedniego menu
```
rr back
```
Zatwierdzenia zmian RR
```
rr submit
```
Bot automatycznie doda wiadomość na odpowiednim kanale:

![obraz](https://github.com/user-attachments/assets/0e1c95ab-b954-4879-b07b-8f87abc66bf6)
