# STAV — Shell Trap and Anti-Virus

**STAV** (Shell Trap and Anti-Virus) adalah skrip sederhana yang dirancang untuk menangkal perintah-perintah berbahaya di lingkungan shell Termux, seperti `rm -rf /` atau `rm -rf *`. STAV membantu mencegah kehilangan data akibat salah ketik atau perintah destruktif yang tidak disengaja.

---

## Fitur

- **Blokir perintah berbahaya secara otomatis**, seperti `rm -rf /` dan sejenisnya.
- **Proteksi langsung di shell** tanpa perlu aplikasi tambahan.
- **Ringan** dan mudah dipasang, cocok untuk pengguna Termux yang suka oprek.

---

## Instalasi

Clone repositori ini dan jalankan skrip instalasi:

```bash
git clone https://github.com/username/stav.git
cd stav
bash install.sh
