# Autoscript SSH x V2ray MultiPATH

### PERHATIAN
- Jika mendapatkan error pada status service dalam jangka panjang, bisa report masalah ini di github open issue.

### INSTALL SCRIPT
***ROOT*** 
 ```  
 sudo su 
 ``` 
 ***Install*** 
 ``` 
apt update ; apt install wget curl gnupg openssl perl tmux -y ; wget -O install.sh "https://raw.githubusercontent.com/fuso123/naruto/main/install.sh" ; chmod +x install.sh ; tmux new -s rerechan "./install.sh"
 ```
 
 ***If there is a disconnection during installation***
 ```
tmux attach-session -t rerechan
 ```

 <p align="center"> 
 <img src="https://img.shields.io/badge/-Demo%20%26%20Script-brightgreen"> 

  ![image](https://raw.githubusercontent.com/FN-Rerechan02/scriptvps/refs/heads/main/IMG_20250805_021337.jpg)<br></html> 

### VPS Support:
- KVM, NVME, OpenVZ7
- IPv4 Only, IPv4 + IPv6
- 215MB Ram & 0.5vCPU + 10 GB Storage

### OS Support:
- Debian 11, 12 & 13
- Ubuntu 20.04 LTS, 22.04 LTS, 23.03, 23.10, 24.04 LTS, 25.04

### FITUR TAMBAHAN
- Auto Backup & Notif Create Account
- Backups are encrypted as securely as possible
- MultiPath SSH & Vless

### PORT:
```
Port & Service
=========================
OpenSSH: 22
WebSocket TLS: 443
WebSocket NonTLS: 80
UDP Custom: 1-65535
BadVPN/UDPWG: 7300
Dropbear SSH: 109
gRPC: 443
=========================
```

### SETTING CLOUDFLARE
```
- SSL/TLS : FULL
- SSL/TLS Recommender : ON
- GRPC : ON
- WEBSOCKET : ON
- Always Use HTTPS : OFF
- UNDER ATTACK MODE : OFF
```

### STATUS
`@Lastest 1.4 Project Rerechan`

### Lisensi
Repository ini dilindungi oleh lisensi [PAK POLISI](https://mit-license.org/)

 <p align="center"> 
<a href="https://t.me/project_rerechan"><img title="Made in Indonesia" src="https://img.shields.io/badge/MADE%20IN-INDONESIA?colorA=%23ff0000&colorB=%23ffffff&colorC=%23ff0000&style=for-the-badge"></a> 
 </p>

## Lisensi

Karya ini dilisensikan di bawah [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).
![Lisensi Creative Commons](https://mirrors.creativecommons.org/presskit/icons/cc.svg)
![Lisensi Creative Commons](https://mirrors.creativecommons.org/presskit/icons/by.svg)
![Lisensi Creative Commons](https://mirrors.creativecommons.org/presskit/icons/sa.svg)
