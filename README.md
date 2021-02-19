![](https://komarev.com/ghpvc/?username=korn-sudo&color=green)

<h1 align="center">☁️☁️☁️ Project Fog ☁️☁️☁️ </h1>
 <p align="center"> <img src="https://img.shields.io/badge/Version-2.3.3-pink.svg" </p>
<br>  

<p align="center">
Project Fog is VPS AutoScript for Debian and Ubuntu Distros. 
<br> Contains pre-installed tunneling application. Read below all supported application.
  </p>
  <br>  
  
<p align="center">
  Credits to:
PHC-Ford [FordSenpai] 🐱 |
Bon-chan 🦢 |
lfasmpao 🐯 |
ADM-Manager 🐬 |
Sprov 🌤️ |
WaGo-G 🔥
  </p>

<h3 align="center">Supported Linux Distro:</h3>
<p align="center">
  <a><img src="https://img.shields.io/badge/Support-Debian%209-red.svg"></a>
  <a><img src="https://img.shields.io/badge/Support-Debian 10-red.svg"></a>
  <a><img src="https://img.shields.io/badge/Support-Ubuntu 18-blue.svg"></a>
  <a><img src="https://img.shields.io/badge/Support-Ubuntu 20-blue.svg"></a>
</p>

<h3 align="center">Services</h3>
<p align="center">
  <a><img src="https://img.shields.io/badge/Service-OpenSSH-green.svg" ></a>
  <a><img src="https://img.shields.io/badge/Service-Dropbear-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Stunnel-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-OpenVPN TCP-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-OpenVPN UDP-green.svg"></a>
 <a><img src="https://img.shields.io/badge/Service-Squid3-green.svg"></a>
  <p align="center">
  <a><img src="https://img.shields.io/badge/Service-Privoxy-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-OHP-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Python Socks Proxy-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Shadowsocks-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-V2Ray-green.svg"></a>
   <a><img src="https://img.shields.io/badge/Service-OCS Panel-green.svg"></a>
  </p>
  
<h3 align="center">Commands</h3>
<p align="center">
   <a><img src="https://img.shields.io/badge/ Commands:-menu-yellow.svg"></a>
  </p>

<h3 align="left">Installation:</h3>
  </p>
#  For Debian

```sh
sudo su
wget https://github.com/korn-sudo/Project-Fog/raw/main/fog-debian && chmod +x ./fog-debian && ./fog-debian
```


<br>For Ubuntu:
<br>1. sudo su
<br>2. wget https://github.com/korn-sudo/Project-Fog/raw/main/fog-ubuntu && chmod +x ./fog-ubuntu && ./fog-ubuntu


<h3 align="center">Screenshots</h3>
<p align="center">
<img src="https://phcorner.net/attachments/1613046228263-png.1297707/" width=300 height=600 >
<img src="https://phcorner.net/attachments/screenshot_20210211-183356_chrome-jpg.1297712/" width=300 height=600 >
 <img src="https://phcorner.net/attachments/1613383892218-png.1302954/" width=300 height=600 >
</p>

<br>
<br>Features:
<br>✔ Automatic delete expired user account
<br>✔ Automatic update OHP and Python Socks in every changes port in SSH and other services.
<br>✔ Customize OHP and Python Socks [ Change Port, On or Off ]
<br>✔ Webmin installed version 1.970 [updated]
<br>✔ Automatic disconnect multilogin users [except in Openvpn].
⠀<br>⠀⠀⠀⠀⠀⠀★Multi-login Limit customize per user (see menu).
<br>✔ Automatic applied rules in Iptables in every reboot and changes ports.
<br>⠀⠀⠀⠀⠀⠀⠀Rules: Protection for torrent and other abusive use.
<br>⠀⠀⠀⠀⠀⠀⠀★ Torrent Protection [ add newest torrent port]
<br>⠀⠀⠀⠀⠀⠀⠀★ Port Scanner Basic Protection
<br>⠀⠀⠀⠀⠀⠀⠀★ Brute Force Attack Basic Protection
<br>
<br>How to access V2Ray Panel:
<br>Go to your browser and enter this link:
<br>⠀⠀⠀⠀⠀⠀⠀》http://123.123.123.123:65432
<br>Note: Change 123.123.123.123 to your VPS IP Address
<br>Username: admin | Password: admin
<br>
<br>Note: Panel Settings not working.
<br>Change Panel Port through VPS Menu if you don't want others access your Panel.
<br>
<br>How to access OCS Panel and OVPN Config:
<br>Go to your browser and enter this link:
<br>⠀⠀⠀⠀⠀⠀⠀》http://123.123.123.123:85
<br>Note: Change 123.123.123.123 to your VPS IP Address
<br>
<br>Note:
<br>To Enable OCS Panel, you must edit the index.php | Directory Path: /home/vps/public_html/index.php
<br>Put your root password in Line 45 of /home/vps/public_html/index.php
<br>

