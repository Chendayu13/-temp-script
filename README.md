# Facebook Temp Script via Tor + mail.tm

Script ini digunakan untuk membuat email sementara dari [mail.tm](https://mail.tm), digunakan untuk pendaftaran akun Facebook (atau lainnya), dengan koneksi aman melalui jaringan Tor.

## ✅ Fitur

- Auto-reset Tor (jika port bentrok)
- Cek IP publik via Tor
- Generate email acak dari domain mail.tm
- Ambil OTP otomatis dari inbox mail.tm
- Simpan semua data ke file log
- Bisa dijalankan langsung di Termux Android

## 📥 Instalasi di Termux

1. **Install dependensi** (hanya sekali):

```bash
pkg update && pkg install tor curl jq git -y
termux-setup-storage  # beri izin akses file
