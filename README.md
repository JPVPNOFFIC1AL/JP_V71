# SENSEI-TUNNEL ULTIMATE v7.1
Premium Auto Installer • SSH • WebSocket TLS/NTLS • Hysteria2 • ZipVPN • Panel UI Biru

Installer generasi terbaru dengan full fitur premium: WebSocket SSH, Hysteria2 Turbo, ZipVPN UDP, Firewall Protec, Auto Snapshot, Dashboard Panel Blue UI, dan auto login panel setelah pemasangan.

---

## ⭐ Fitur Utama

### 🔹 SSH & WebSocket
- SSH Dropbear Multi-Port
- SSH over WebSocket (TLS dan Non-TLS)
- Otomatis membuat service WS
- Auto create akun SSH/WS dari panel & menu

### 🔹 Hysteria2 Turbo (UDP)
- Auto install Hy2
- Support password/user
- Buat akun Hysteria langsung dari panel
- Config otomatis dengan hostname & port

### 🔹 ZipVPN (UDP Tunnel)
- Install otomatis
- Port manager langsung di panel/menu
- Protec firewall UDP-Limit

### 🔹 Dashboard Panel UI Biru
- Tampilan panel modern full warna blue-cyan
- Real-time system info
- Menu manajemen lengkap:
  - Create SSH/WebSocket user  
  - Create Hysteria2 user  
  - Cek bandwidth VPS  
  - Port manager  
  - User list & delete  
- Auto open panel setelah install selesai

### 🔹 Proteksi & Optimasi
- SSL Certificate otomatis
- Firewall UDPLIMIT proteksi DDoS dasar
- Hardening sysctl
- Snapshot + rollback otomatis

---

## 📥 Cara Instalasi

Jalankan perintah ini di VPS:

wget -O install.sh https://raw.githubusercontent.com/JPVPNOFFICIAL/JP_V71/main/sensei.sh chmod +x install.sh ./install.sh install

Setelah instalasi selesai, VPS akan **otomatis membuka Panel UI** melalui browser terminal.

---

## 📁 Lokasi File Penting

| Fungsi | Lokasi File |
|-------|--------------|
| Panel UI | `/etc/sensei/panel/index.html` |
| Database panel | `/root/sensei.db` |
| Config Hysteria2 | `/etc/hysteria/config.json` |
| Snapshot rollback | `/root/.sensei/snapshots/` |
| Script rollback | `/usr/local/bin/sensei-rollback.sh` |

---

## 📊 Monitoring

- Penggunaan bandwidth VPS (vnstat)
- Tracking pengguna & log sistem
- Panel menampilkan informasi real-time

---

## 🧩 Kompatibilitas

- Ubuntu **20.04**
- Ubuntu **22.04**
- CPU: x86_64 / ARM64
- RAM minimal 512MB

---

## 🔧 Menu Utama

1. Create SSH/WebSocket Account


2. Create Hysteria2 Account


3. Create ZipVPN Account (opsional)


4. List Users


5. Delete User


6. Change Ports


7. Check Bandwidth VPS


8. Backup & Snapshot


9. Panel Manager


10. Exit
