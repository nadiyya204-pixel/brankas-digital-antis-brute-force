# 🔐 Sistem Brankas Digital Anti-Pembobolan (Anti-Brute Force)

![Status](https://img.shields.io/badge/Status-Completed-success)
![Logisim](https://img.shields.io/badge/Tool-Logisim_Evolution-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

Proyek UAS mata kuliah Organisasi dan Arsitektur Komputer. Simulasi brankas elektronik 4-digit yang dilengkapi dengan sistem keamanan *lockout* otomatis untuk mencegah serangan *brute force*.

---

## ✨ Fitur Utama

- ✅ **Verifikasi Password 4-Digit:** Memvalidasi input menggunakan *Comparator* dan *Logic Gates*.
- ✅ **Anti-Brute Force (Lockout):** Sistem akan terkunci permanen setelah 3 kali percobaan password yang salah.
- ✅ **Counter Stay-at-Value:** Menggunakan mode *Stay at Value* pada Counter untuk mencegah *wrap-around*.
- ✅ **Indikator Visual Real-time:** Menampilkan status brankas (Closed, Open, Error) menggunakan LED dan 7-Segment Display.
- ✅ **Reset Manual:** Membutuhkan otorisasi reset untuk mengembalikan sistem ke kondisi normal.

---

## ️ Teknologi & Komponen

Proyek ini dirancang dan disimulasikan menggunakan **Logisim Evolution**.

**Komponen Digital yang Digunakan:**
- `Comparator` (4-bit & 2-bit)
- `Counter` (2-bit, Max Value: 3, Action: Stay at Value)
- `Multiplexer` (4-port, 4-bit)
- `Logic Gates` (AND, NOT)
- `7-Segment Display` & `LED Indicators`
- `Clock Generator` (200ms)

---

## 📂 Struktur Repository

```text
Brankas-Digital-Logisim/
│
├── brankas_fiks.circ      # File utama rangkaian Logisim Evolution
├── Laporan_Praktikum.pdf  # Laporan lengkap proyek
├── screenshots/           # Dokumentasi visual rangkaian
│   ├── canvas_main.png
│   ├── blok1_verifikasi.png
│   ├── blok2_counter.png
│   └── blok3_output.png
└── README.md              # Dokumentasi repository ini
