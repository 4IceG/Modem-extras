# Modem-extras (My repository)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/4IceG/Modem-extras?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/4IceG/Modem-extras?style=flat-square)

## <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> What You Should Know / <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Co powinieneś wiedzieć
> The sms-tool package is available in the OpenWrt Master repository. 

> Pakiet sms-tool jest dostępny w repozytorium OpenWrt Master.

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> To install packages from my repository:

Step 1) Add the following entry to the /etc/opkg/customfeeds.conf file to the OpenWrt router:
``` bash
src/gz IceG_repo https://github.com/4IceG/Modem-extras/raw/main/myrepo
```
<details>
   <summary>Show me how</summary>
   
![](https://github.com/4IceG/Personal_data/blob/master/repo1.PNG?raw=true)
![](https://github.com/4IceG/Personal_data/blob/master/repo2.png?raw=true)

</details>

Step 2) Add repository public key with commands:
``` bash
wget https://github.com/4IceG/Modem-extras/raw/main/myrepo/IceG-repo.pub -O /tmp/IceG-repo.pub
opkg-key add /tmp/IceG-repo.pub
```
Step 3) Execute the command:
``` bash
opkg update
```

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Aby móc instalować pakiety z mojego repozytorium należy: 

Krok 1) Do routera z OpenWrt dodać do pliku /etc/opkg/customfeeds.conf następujący wpis:
``` bash
src/gz IceG_repo https://github.com/4IceG/Modem-extras/raw/main/myrepo
```

<details>
   <summary>Pokaż jak to zrobić</summary>
   
![](https://github.com/4IceG/Personal_data/blob/master/repo1.PNG?raw=true)
![](https://github.com/4IceG/Personal_data/blob/master/repo2.png?raw=true)

</details>

Krok 2) Dodać klucz publiczny repozytorium za pomoca poleceń:
``` bash
wget https://github.com/4IceG/Modem-extras/raw/main/myrepo/IceG-repo.pub -O /tmp/IceG-repo.pub
opkg-key add /tmp/IceG-repo.pub
```
Krok 3) Wykonać polecenie:
``` bash
opkg update
```
