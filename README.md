# Modem-extras

Aby móc instalować pakiety z mojego repozytorium należy:

1) Do routera z OpenWrt dodać do pliku /etc/opkg/customfeeds.conf następujący wpis:
``` bash
src/gz IceG_repo https://github.com/4IceG/Modem-extras/raw/main/myrepo
```
2) Dodac klucz publiczny repozytorium za pomoca polecen:
``` bash
wget https://github.com/4IceG/Modem-extras/raw/main/myrepo/IceG-repo.pub -O /tmp/IceG-repo.pub
opkg-key add /tmp/IceG-repo.pub
```
3) Wykonac polecenie:
``` bash
opkg update
```
