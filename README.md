# Gra Counter (Licznik)! 🇵🇱
![Gra](/tree/Zdjęcia/Counter0.png)
## O grze...

### Gra polega na naciśnięciu możliwie wiele razy CTRL+C w ciągu 60 sekund.

Gra dedykowana jest osobom, którym się wybitnie nudzi. ;)


### Gra jest w 100% skryptem shell'owym.

Gra wymaga instalacji pakietu **figlet** dla prawidłowego działania.

## Aby zagrać w grę należy ...

Posiadać zainstalowany **bash** oraz **figlet**.

Posiadać **klawiaturę**.

### Pobieranie i instalacja :
Instalacja pakietu **figlet** :
```
sudo apt update
sudo apt install figlet -y
```
lub w środowisku Termux :
```
pkg update
pkg install figlet -y
```
Pobieranie i instalacja Counter'a :
```
git clone https://github.com/BuriXon-code/Counter
cd Counter
chmod +x counter
```
### Uruchamianie :
```
./counter
```

### Podglądanie listy wyników :
![Gra](/tree/Zdjęcia/Counter1.png)

Aby wyświetlić listę wyników bez konieczności gry, należy użyć komendy :
```
./counter top
```
## Uwagi!
### Lokalizacja pliku z wynikami :
Plik z wynikami **.counter-scores** znajduje się w katalogu **home** użytkownika.

Jego usunięcie spowoduje permanentne usunięcie zapisu dotychczasowej gry.
### Przytrzymanie CTRL+C :
Grę na systemach Linux łatwo oszukać przytrzymując CTRL+C zamiast naciskać na czas.

Obejście to jednak nie działa na Termux. Przez wzgląd na wydajność środowisk Termux skrypt zatrzyma się i/lub przejdzie od razu do pola wpisywania nicku i wyników.
### Kompatybilność :
Skrypt kompatybilny jest z wszystkimi systemami Linux oraz Termux posiadającymi możliwość instaacji **bash** oraz **figlet**.

Co jednak ważne - przez wzgląd na użycie kolorów RGB (ANSI escape \e[38;2...) gra nie będzie dopasowywać się do schematów kolorów używanego emulatora terminala.

Zalecane uruchamianie w terminalu z ciemnym motywem.


