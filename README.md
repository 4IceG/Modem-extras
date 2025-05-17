<p align="center">
 <a href="https://github.com/4IceG/Modem-extras"><img width=7% src="https://github.com/4IceG/Personal_data/blob/master/ipk-repo.png?raw=true"></a>
 <a href="https://github.com/4IceG/Modem-extras-apk"><img width=5% src="https://github.com/4IceG/Personal_data/blob/master/apk-repo.png?raw=true"></a>
</p>

# Modem-extras (My repository)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/4IceG/Modem-extras?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/4IceG/Modem-extras?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/4IceG/Modem-extras?style=flat-square)

## <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> What You Should Know / <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Co powinieneś wiedzieć
> [!IMPORTANT]
> The sms-tool package is available in the OpenWrt repository since v23.05.   
> Pakiet sms-tool jest dostępny w repozytorium OpenWrt od wydania v23.05.

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> To install packages from my repository:
- Execute following commands on your OpenWrt router:
  ```
  grep -q IceG_repo /etc/opkg/customfeeds.conf || echo 'src/gz IceG_repo https://github.com/4IceG/Modem-extras/raw/main/myrepo' >> /etc/opkg/customfeeds.conf
  wget https://github.com/4IceG/Modem-extras/raw/main/myrepo/IceG-repo.pub -O /tmp/IceG-repo.pub
  opkg-key add /tmp/IceG-repo.pub
  opkg update

  opkg install luci-app-sms-tool-js
  ```
- OR, to do it manually:
  1. Add the following entry to the /etc/opkg/customfeeds.conf file to the OpenWrt router:
     ```
     src/gz IceG_repo https://github.com/4IceG/Modem-extras/raw/main/myrepo
     ```
      <details>
         <summary>Show me how</summary>
         
      ![](https://github.com/4IceG/Personal_data/blob/master/repo1.PNG?raw=true)
      ![](https://github.com/4IceG/Personal_data/blob/master/repo2en.png?raw=true)
      
      </details>
  2. Add repository public key with commands:
      ``` bash
      wget https://github.com/4IceG/Modem-extras/raw/main/myrepo/IceG-repo.pub -O /tmp/IceG-repo.pub
      opkg-key add /tmp/IceG-repo.pub
      ```
  3. Execute command to update repositories:
      ``` bash
      opkg update
      ```
  4. Execute command to install the package:
      ``` bash
      opkg install luci-app-sms-tool-js
      ```

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Aby móc instalować pakiety z mojego repozytorium należy: 
#### Metoda 1. 
Wykonaj te polecenia na routerze z OpenWrt:
  ```
  grep -q IceG_repo /etc/opkg/customfeeds.conf || echo 'src/gz IceG_repo https://github.com/4IceG/Modem-extras/raw/main/myrepo' >> /etc/opkg/customfeeds.conf
  wget https://github.com/4IceG/Modem-extras/raw/main/myrepo/IceG-repo.pub -O /tmp/IceG-repo.pub
  opkg-key add /tmp/IceG-repo.pub
  opkg update

  opkg install luci-app-sms-tool-js
  ```
#### Metoda 2. (Wykonujemy powyższe polecenia ręcznie, ale krok po kroku, polecenie po poleceniu):

Krok 1. Do routera z OpenWrt dodaj do pliku /etc/opkg/customfeeds.conf następujący wpis:
``` bash
src/gz IceG_repo https://github.com/4IceG/Modem-extras/raw/main/myrepo
```

<details>
   <summary>Pokaż jak to zrobić</summary>
   
![](https://github.com/4IceG/Personal_data/blob/master/repo1.PNG?raw=true)
![](https://github.com/4IceG/Personal_data/blob/master/repo2pl.png?raw=true)

</details>

Krok 2. Dodaj klucz publiczny repozytorium za pomoca poleceń:
``` bash
wget https://github.com/4IceG/Modem-extras/raw/main/myrepo/IceG-repo.pub -O /tmp/IceG-repo.pub
opkg-key add /tmp/IceG-repo.pub
```
Krok 3. Wykonaj polecenie aktualizacji repozytoriów:
``` bash
opkg update
```
Krok 4. Wykonaj polecenie instalujące pakiet:
``` bash
opkg install luci-app-sms-tool-js
```
### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Pokaż swoje wsparcie | <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> Show your support

<p align="center">
</p>
<p align="center">
<a href="https://github.com/sponsors/4IceG">
  <img width=25% src="https://github.com/4IceG/Personal_data/blob/master/nspons.PNG?raw=true">
</a>
</p>

<p align="center">
<a href="https://suppi.pl/rafalwabik"><img width=25% src="https://github.com/4IceG/Personal_data/blob/master/kawa.png?raw=true" alt="https://suppi.pl/rafalwabik" /></a>
</p>
