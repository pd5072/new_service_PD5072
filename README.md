# Dokumentacja projektu: new_service

## 1. Opis usługi medycznej

**Usługa:** Telekonsultacje zdrowotne  
Telekonsultacje umożliwiają pacjentom uzyskanie porady medycznej bez konieczności fizycznej wizyty w gabinecie lekarskim. Pacjenci mogą kontaktować się z lekarzem za pośrednictwem wideokonferencji, telefonu lub komunikatorów internetowych.

**Cele usługi:**
1. Poprawa dostępności do usług zdrowotnych.
2. Obniżenie kosztów leczenia.
3. Usprawnienie kontaktu pacjenta z lekarzem.

**Korzyści dla pacjentów:**
1. Oszczędność czasu dzięki braku konieczności dojazdu.
2. Szybszy dostęp do specjalistów.
3. Możliwość uzyskania porady z dowolnego miejsca

## 2. Dokumenty utworzone w projekcie

W repozytorium znajdują się następujące pliki:

\- `opis_uslugi.txt` – opis usługi oraz korzyści dla pacjentów.  

\- `plan_wdrożenia.txt` – plan działań niezbędnych do wdrożenia usługi.  

\- `ryzyka.txt` – analiza ryzyk związanych z telekonsultacjami.  

\- `kampania_marketingowa.txt` – plan kampanii marketingowej (gałąź **marketing**).  

\- `ankieta_pacjentow.txt` – przykładowa ankieta dotycząca opinii pacjentów.  

\- `images/logo.png` – przykładowe logo usługi (plik binarny).  

\- `.gitignore` – plik ignorowanych elementów.  

\- `.gitattributes` – konfiguracje oznaczające plik logo jako binarny.  


## 3. Instrukcja pracy z repozytorium

### 3.1. Pobranie repozytorium

&nbsp;   git clone https://github.com/pd5072/new_service_PD5072.git

&nbsp;   cd new_service_PD5072

### 3.2. Sprawdzanie gałęzi

&nbsp;   git branch

### 3.3. Przełączanie gałęzi

&nbsp;   git checkout marketing

&nbsp;   git checkout master

### 3.4. Tworzenie nowej gałęzi

&nbsp;   git checkout -b nazwa_galezi

### 3.5. Scalanie gałęzi

&nbsp;   git checkout master

&nbsp;   git merge --no-ff marketing -m "Scalono gałąź marketing z główną gałęzią"

### 3.6. Historia zmian

&nbsp;   git log --oneline --graph --all

### 3.7. Przywracanie wcześniejszych wersji dokumentów

&nbsp;   git checkout HEAD~1 -- nazwa_pliku.txt


## 4. Wykorzystane polecenia GIT:

\- `git init`

\- `git add`, `git commit`

\- `git status`, `git log`, `git diff`

\- `git branch`, `git checkout`, `git merge`

\- `git remote add`, `git push`, `git pull`

\- `git tag`, `git push --tags`

\- `.gitignore`, `.gitattributes`


## 5. Napotkane problemy i rozwiązania

**Problem 1:** *Polskie znaki w nazwie pliku*  

Plik `opis_usługi.txt` powodował błędy w terminalu.  

**Rozwiązanie:** zmiana nazwy na `opis_uslugi.txt`.

**Problem 2:** *Przypadkowa inicjalizacja repozytorium w katalogu images*

W wyniku `git init images` powstało drugie, niepotrzebne repozytorium.  

**Rozwiązanie:** usunięcie katalogu `images/.git` i ponowne dodanie `.gitkeep`.

**Problem 3:** *Błędne komendy terminala*

np. `cd.` lub brak `echo` przy dopisywaniu tekstu.  

**Rozwiązanie:** poprawienie poleceń.

**Problem 4:** *Literówka w nazwie pliku ankiety*  

**Rozwiązanie:** użycie poprawnej nazwy `ankieta_pacjentow.txt`.


## 6. Wersjonowanie projektu – tag v1.0

Do repozytorium dodano tag oznaczający pierwszą ukończoną wersję projektu:

&nbsp;   git tag -a v1.0 -m "v1.0 - Gotowy plan wdrożenia usługi medycznej"


## 7. Zdalne repozytorium GitHub

Repozytorium zostało utworzone jako:

&nbsp;   new\_service\_PD5072

Repozytorium połączono z lokalnym:

&nbsp;   git remote add origin https://github.com/pd5072/new\_service\_PD5072.git

&nbsp;   git push -u origin master

&nbsp;   git push origin marketing

&nbsp;   git push --tags





