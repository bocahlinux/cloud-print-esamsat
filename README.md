# ☁️ Cloud Print Kutipan  

**Samsat Kalimantan Tengah**  
_Last Version: **1.2.5** (18-09-2025)_  

> 💡 _Cloud Print Kutipan_ adalah aplikasi cetak kutipan digital yang terintegrasi dengan sistem **Samsat Kalimantan Tengah**.  
> Dibuat menggunakan **Python + PyQt5**, aplikasi ini mendukung auto-update, integrasi cloud, dan kemudahan dalam manajemen printer.  

---

## 📌 Tentang Proyek
- **Instansi**: Badan Pendapatan Daerah Provinsi Kalimantan Tengah  
- **Support**: Tim IT Server Bapenda Kalteng  
- **Created by**: **Yudha**  

Aplikasi ini bertujuan untuk mempermudah pengelolaan **cetak kutipan cloud** dengan:
- 🔄 **Auto Updater**: aplikasi selalu diperbarui ke versi terbaru.  
- 🖨️ **Printer Integration**: otomatis mendeteksi printer yang tersedia di Windows.  
- 🪟 **Mini Widget Mode**: tampil elegan di pojok layar (always on top).  
- 🔐 **Secure Module**: enkripsi konfigurasi dan proteksi file `.pyd`.  

---

## 🚀 Teknologi yang Digunakan
- **Python 3.10+**
- **PyQt5** → GUI modern  
- **PyInstaller** → build `.exe`  
- **Requests / Psutil / PyStray** → updater, monitoring, tray icon  
- **Win32 API & WMI** → integrasi printer dan sistem Windows  

---

## 📥 Instalasi & Penggunaan
1. Download versi terbaru dari **[Releases](../../releases)**.  
2. Ekstrak file (jika berbentuk ZIP).  
3. Jalankan `kutipan.exe`.  
4. Aplikasi akan otomatis:
   - Mengecek update terbaru.  
   - Menyimpan versi di `version.json`.  
   - Menjalankan updater di background.  

---

## 📂 Struktur Repo
```bash
cloud-print-kutipan/
├── app.py              # Entry point utama
├── updater.py          # Auto updater
├── helper/             # Folder modul python
│   ├── conf/           # Konfigurasi
│   ├── secure/         # Modul keamanan
│   └── system/         # Modul sistem & UI
├── version.json        # Versi lokal
├── vkutipan.json       # Versi remote (untuk updater)
└── README.md
```

## 📜 Catatan Versi
🔖 Versi 1.2.5 (18-09-2025)
✨ Auto-start updater aktif default.
🖥️ GUI warning jika aplikasi dibuka lebih dari 1x.
📦 Distribusi modul .pyd via paket ZIP (lebih ringan & terstruktur).
⚡ Optimisasi updater (cek versi lebih cepat).

## ❤️ Credits
Support: IT Server Bapenda Provinsi Kalimantan Tengah
Developer: Yudha
Special Thanks: Open Source Community

## ⚠️ Notice
Aplikasi ini hanya digunakan untuk keperluan Samsat Kalimantan Tengah.
Tidak untuk diperjualbelikan atau digunakan di luar instansi resmi.