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

# REACTION ROLES - 

**NADAJ ROBIE ROLĘ "ZWERYFIKOWANY UCZESTNIK", NAJEDŹ NA SWÓJ PROFIL I PRAWYM PRZYCISKIEM MYSZY NA ROLI WYWOŁAJ MENU, SKOPIUJ id ROLI I ZAPISZ GDZIEŚ W NOTATNIKU!!**
![obraz](https://github.com/user-attachments/assets/68529756-a2d2-433f-99aa-f361a3324661)


Wróć na serwer Discord i znajdź kanał *polecenia* w kategorii admin zone.
Wpisuj zastępujące komendy w pole wysyłania wiadomości i wyślij je

```
??rr create
```
Kliknij prawym przyciskiem wyszy na kanał *#weryfikacja* i skopiuj ID Kanału.

```
rr channel (wklej ID kanału)
```

```
rr desc Cześć, witamy na serwerze Ossowa w ramach imprezy Skorpion 2025! Prosimy o weryfikację czy nie jesteś botem.

Hi, welcome to Ossowa server for Skorpion 2025 event! Please verify yourself that you are not a bot.
```
```
rr name weryfikacja
```
```
rr notify
```
```
rr mode
```
```
rr roles
```
```
rr add (wklej ID Roli)
```
```
rr emoji :ok: 
```
```
rr submit
```
```
rr back
```
```
rr submit
```
