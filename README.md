# Modem-extras (my repo)


## <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="32"> What You Should Know / <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="32"> Co powinieneś wiedzieć
> The sms-tool package is not available in the OpenWrt repository (waiting to be added). 
> If you do not have an image from forum eko.one.pl you have to compile the package manually.

> Pakiet sms-tool nie jest dostępny w repozytorium OpenWrt (czeka na dodanie).
> Jeśli nie posiadasz obrazu z forum eko.one.pl musisz skompilować pakiet ręcznie.

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> To install packages from my repository:

1) Add the following entry to the /etc/opkg/customfeeds.conf file to the OpenWrt router:
``` bash
src/gz IceG_repo https://github.com/4IceG/Modem-extras/raw/main/myrepo
```
2) Add repository public key with commands:
``` bash
wget https://github.com/4IceG/Modem-extras/raw/main/myrepo/IceG-repo.pub -O /tmp/IceG-repo.pub
opkg-key add /tmp/IceG-repo.pub
```
3) Execute the command:
``` bash
opkg update
```

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Aby móc instalować pakiety z mojego repozytorium należy: 

1) Do routera z OpenWrt dodać do pliku /etc/opkg/customfeeds.conf następujący wpis:
``` bash
src/gz IceG_repo https://github.com/4IceG/Modem-extras/raw/main/myrepo
```
2) Dodać klucz publiczny repozytorium za pomoca poleceń:
``` bash
wget https://github.com/4IceG/Modem-extras/raw/main/myrepo/IceG-repo.pub -O /tmp/IceG-repo.pub
opkg-key add /tmp/IceG-repo.pub
```
3) Wykonać polecenie:
``` bash
opkg update
```
