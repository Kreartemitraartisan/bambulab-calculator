# 🎲 Bambu Lab 3D Print Cost Calculator

Kalkulator biaya 3D printing khusus untuk printer **Bambu Lab** dengan fitur tracking history print. Dibangun dengan HTML + Tailwind CSS + Vanilla JS, 100% client-side tanpa backend.

![Version](https://img.shields.io/badge/version-1.0.0-cyan)
![License](https://img.shields.io/badge/license-MIT-green)
![Deploy](https://img.shields.io/badge/deploy-Vercel-black)

## ✨ Fitur

### 🧮 Kalkulator Biaya
- Perhitungan otomatis: **filament + listrik + depresiasi printer + wear & tear**
- Support semua printer Bambu Lab: X1C, X1E, P1S, P1P, A1, A1 Mini
- Support berbagai jenis filament: PLA, PETG, ABS, ASA, TPU, PC, PA, dan varian CF
- Kalkulasi **harga jual** dengan profit margin custom
- Real-time calculation saat input berubah

### 💾 Save & Track Print History
- Simpan data print ke `localStorage` (persist di browser)
- Edit & delete print yang sudah tersimpan
- Statistik lengkap: total prints, total cost, total filament, total jam
- Filter berdasarkan status (Success / Failed / In Progress) & model printer
- Search by nama print atau jenis filament

### 📤 Export & Backup
- **Export CSV** — buka di Excel / Google Sheets
- **Export JSON** — backup lengkap untuk restore
- **Import JSON** — restore data dari backup

### ⚙️ Settings
- Default electricity rate, profit margin, printer
- Multi-currency: IDR (Rp), USD ($), EUR (€)
- Referensi spesifikasi semua printer Bambu Lab

## 🛠️ Tech Stack

| Teknologi | Keterangan |
|-----------|-----------|
| HTML5 | Struktur halaman |
| Tailwind CSS (CDN) | Styling utility-first |
| Vanilla JavaScript | Logic & interaktivitas |
| Font Awesome | Icon |
| localStorage | Data persistence (client-side) |

> ⚡ **Zero dependencies** — tidak perlu `npm install`, tidak ada build step.

## 🚀 Cara Menjalankan

### Opsi 1: Buka Langsung (Paling Gampang)
```bash
# Clone repo
git clone https://github.com/USERNAME/bambu-calculator.git
cd bambu-calculator

# Double-click index.html — selesai!