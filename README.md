# 🔐 Hotspot Login Page

Template halaman login hotspot yang modern, ringan, dan responsif untuk
MikroTik RouterOS. Cocok untuk warnet, kafe, kantor, sekolah, atau usaha
voucher WiFi.

## ✨ Fitur

- Tampilan modern dan responsif (desktop & mobile)
- Login dengan username & password atau kode voucher
- Ringan dan cepat dimuat, tanpa framework berat
- Mudah dikustomisasi (logo, warna, teks)
- Kompatibel dengan MikroTik Hotspot

## 📁 Struktur File
hotspot-login/
├── login.html
├── alogin.html
├── logout.html
├── status.html
├── error.html
├── css/
│ └── style.css
├── img/
│ └── logo.png
└── README.md

## 🚀 Cara Instalasi

1. Download atau clone repository ini:
```bash
   git clone https://github.com/username/hotspot-login.git
```
2. Buka **Winbox** → menu **Files**.
3. Upload folder `hotspot` (hasil download) ke router, timpa folder hotspot bawaan.
4. Buka **IP → Hotspot → Server Profiles**, lalu pilih **HTML Directory** yang sesuai.
5. Sambungkan perangkat ke WiFi hotspot dan uji halaman login.

## 🎨 Kustomisasi

- **Logo:** ganti file `img/logo.png`
- **Warna & tema:** ubah variabel di `css/style.css`
- **Teks & nama jaringan:** edit langsung di `login.html`

## 🖼️ Preview

![Preview](preview.png)

## ⚠️ Catatan

- Jangan menghapus variabel bawaan MikroTik seperti `$(username)`, `$(link-login-only)`, dan `$(chap-id)`, karena dibutuhkan agar proses login berfungsi.
- Backup folder hotspot asli sebelum menimpa file.

## 🤝 Kontribusi

Pull request dan saran sangat diterima. Silakan buka *issue* jika menemukan bug.

## 📄 Lisensi

Dirilis di bawah lisensi [MIT](LICENSE).
