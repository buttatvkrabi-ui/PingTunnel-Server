# PingTunnel Server Installer

This script installs [PingTunnel](https://github.com/esrrhs/pingtunnel) on your server and configures it to run as a background service in **server mode** using `systemd`.

## 📱 Client App

iOS app : [Ping Tunnel – VPN over ICMP](https://apps.apple.com/app/ping-tunnel-vpn-over-icmp/id6748279683)

Android app : [Ping Tunnel – VPN over ICMP](https://play.google.com/store/apps/details?id=dev.hexasoftware.PingTunnel)

---

## ✅ Features

- Detects OS and architecture automatically  
- Downloads the **latest version** of PingTunnel  
- Installs it into `/opt/pingtunnel`  
- Creates a `systemd` service (`pingtunnel.service`)  
- Starts and enables the service on boot  

---

## 📥 Installation

Run this command tcurl -fsSL https://raw.githubusercontent.com/HexaSoftwareDev/PingTunnel-Server/main/installer.sh | sudo basho install PingTunnel server:

```bash
curl -fsSL https://raw.githubusercontent.com/HexaSoftwareDev/PingTunnel-Server/main/installer.sh | sudo bash
```
if install command not working use this instead:
```bash
curl -fsSL https://raw.githubusercontent.com/HexaSoftwareDev/PingTunnel-Server/main/installer.sh -o installer.sh

sudo bash installer.sh
```

## ▶️ Service Check
```bash
systemctl status pingtunnel
```
## 🙏 Thanks

Thanks to [esrrhs](https://github.com/esrrhs) for creating [PingTunnel](https://github.com/esrr[installer.sh](https://github.com/user-attachments/files/24358243/installer.sh)
[README.md](https://github.com/user-attachments/files/24358242/README.md)
hs/pingtunnel).
[installer.sh](https://github.com/user-attachments/files/24358244/installer.sh)



