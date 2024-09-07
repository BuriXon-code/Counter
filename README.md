# Gra Counter (Licznik)!
## O grze...

### Gra polega Naciśnięciu możliwie wiele razy CTRL+C w ciągu 60 sekund.

Gra dedykowana jest osobom, którym się wybitnie nudzi. ;)


### Gra jest w 100% skryptem shell'owym.

Gra wymaga działającego pakietu **figlet** dla prawidłowego działania.

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
pkg install figlet
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
Aby wyświetlić listę wyników bez konieczności gry, należy użyć komendy :
```
./counter top
```


