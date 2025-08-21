
build/install qbittorent for debian 12
--------------------------------------


source : https://github.com/qbittorrent/qBittorrent/wiki/Compilation-Debian-and-Ubuntu#dependencies

```bash
sudo apt install build-essential pkg-config automake libtool git zlib1g-dev libssl-dev libgeoip-dev
sudo apt install libboost-dev libboost-system-dev libboost-chrono-dev libboost-random-dev
sudo apt install python3
sudo apt install qtbase5-dev qtbase5-private-dev qttools5-dev libqt5svg5-dev
./configure
make
sudo make install
```


remove qbittorent for ubuntu 20.4
------------------------------------------

```bash
sudo make uninstall
```
