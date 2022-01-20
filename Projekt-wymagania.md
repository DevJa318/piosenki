# Projekt piosenki - Zbieranie wymagań


## Linux run program in background
& - add this sign at the end



## Wirtualne środowisko 
Przechodzimy do naszego katalogu, po czym na potrzeby naszego programu, tworzymy wirtualne środowisko pracy, poleceniem:
```
```
<!--- python3 -m venv <nazwa środowiska>
$ source ./venv/bin/activate -->
<!---
your comment goes here
and here
-->

[//]: # (This may be the most platform independent comment)
### pipenv 
Źródło: https://ichi.pro/pl/wirtualne-srodowiska-do-nauki-o-danych-uruchamianie-pythona-i-jupytera-z-pipenv-218576997098501
```
pip install pipenv
	w folderze
pipenv --python 3.10
pipenv install beautifulsoup4 eyed3
	ew,aby usunąć pipenv uninstall pandas



	otwieranie jupyterlab z nowym środowiskiem
	```
pipenv install ipykernel

python -m ipykernel install --user --display-name pipenv_test --name pipenv_test

jupyter lab

```
https://ichi.pro/pl/wirtualne-srodowiska-do-nauki-o-danych-uruchamianie-pythona-i-jupytera-z-pipenv-218576997098501

## Narzędzia
### GIT - kroki

#### Problemy
- na stronie banch main - w lokalnym folderze master
#### Pytania
- co zrobić, żeby nie wpisywać loginu i PAK za każdym razem przy pushu

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

#### Łączenie z repozytorium na Githubie
- utworzenie repozytorium na githubie
- git remote add origin https://github.com/DevJa318/piosenki.git
- git push -u origin master
- prosi o nazwę użytkownika i hasło --> a właściwie zamiast hasła o Personal Access Key
    - dostępny w Ustawienia ->  Developer settings -->      Personal access Tokens

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

#### Pseudokod
dla każdego pliku pobierz tytuł i autora 



for witryna in witryny
    wyszukaj tytul autor
    sprawdź czy pierwszy wynik zgadza się autor i tytuł
    jeśli tak:
        przejdź w link i pobierz tekst
        break
    jeśli nie:
        przejdź do kolejnej witryny 

Wyślij tekst do tłumacza
pobierz pobrany tekst piosenki 

with open database:
    


1. Stworzenie pliku init
    1. Zastanowić się ile plików z "modułami" własnymi
2. Importy
    1. request
    2. Beautifulsoup
    3. mongodb
    3. json?
    4. os
    5. eye3D - to extract mp3 metadata with Python
	    1. or tinytag?


####


#### Użycie Klash
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