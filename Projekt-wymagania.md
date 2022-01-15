# Projekt piosenki - Zbieranie wymagań





## Narzędzia 
### GIT - kroki

#### Problemy 
- na stronie banch main - w lokalnym folderze master


#### żródło: https://bedeprogramistka.pl/jak-uzywac-git-huba-instalacja-i-obsluga-gita-krok-po-kroku/

#### instalacja i konfiguracja 
- Arch linux --> sudo pacman -S git
- git config --global user.name "DevJa318"                                                                                                                                                   
- git config --global user.email rkipek@gmail.com ```

#### Tworzenie lokalnego folderu z repozytorium
- cd ./folder-z-repo
- git init  - tworzenie gałęzi master
- git add . - dodawanie wszystkich plików
- git status - podgląd wydarzenia
- git commit -m "komentarz" - dodanie commita wraz z komentarzem 
- git commit -m "komentarz"

#### Łączenie z repozytorium na Githubie
- utworzenie repozytorium na githubie
- git remote add origin https://github.com/DevJa318/piosenki.git
- git push -u origin master
- prosi o nazwę użytkownika i hasło --> a właściwie zamiast hasła o Personal Access Key
    - dostępny w Ustawienia ->  Developer settings -->      Personal access Tokens



#### 


### Baza danych - NoSQL - MongoDB
#### Pola
- tytuł
- wykonawca
- ścieżka bezwzględna
- ścieżka względna
- adres strony do pobierania tekstu piosenki
- Tekst - oryginal
- Tekst - translation

### Python

#### Połączenie z bazą danych
#### Wyszukiwanie napisów
#### Obsługa wyjątków

##### Tekst nieznaleziony

#### Tłumaczenie

#### Możliwe problemy
- kodowanie znaków


## Wykaz stron - 

https://pisni.ua/antytila-tdme
https://www.tekstowo.pl/piosenka,artik__asti,_1055_1088_1080_1074_1077_1090_.html
https://text-pesni.com/pesnya/pokazat/565668451/mohito/tekst-perevod-pesni-ruki-proch/
https://www.pisni.org.ua/songs/8157910.html
https://tekst-pesni.online/zvonkij-ohh-la-la/
http://www.megalyrics.ru/lyric/real-o/movchati-kokhati.htm
https://pesni.guru/text/лина-мицуки-мовчати-кохати
https://textove.com/real-o-movchati-kohati-tekst
https://www.gl5.ru/h/hensy/hensy-pobolelo-i-proshlo.html
https://genius.com/Hensy-hurt-and-healed-lyrics