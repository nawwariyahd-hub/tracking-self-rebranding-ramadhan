# 🌙 Ramadan Self Rebranding Tracker

**High-Performance Formula** untuk tracking ibadah harian selama 30 hari Ramadan dengan sistem checklist otomatis dan visualisasi progress.

![Preview](screenshot.png) <!-- optional, bisa bikin screenshot nanti -->

## ✨ Features

- 📊 **44 amalan harian** terstruktur berdasarkan waktu (Sahur sampai Penutup Malam)
- ✅ **Dropdown checklist** ✓/- untuk tracking cepat
- 🎨 **Auto-color coding** — hijau (selesai) / merah (terlewat)
- 📈 **Progress bar otomatis** — merah → kuning → hijau berdasarkan persentase
- 📱 **Dual format:** Excel/Google Sheets + HTML (responsive)
- 💾 **Data persistence** — tracking tersimpan otomatis di browser
- 🎯 **3 dekade Ramadan** dengan color-coded sections

## 📦 Isi Package

1. **`tracking-ramadan.xlsx`** — File Excel dengan dropdown & conditional formatting
2. **`tracking-ramadan.html`** — Web version dengan auto-save ke localStorage
3. **`jadwal-ramadan.html`** — Timeline infografis jadwal ibadah harian

## 🚀 Cara Pakai

### Excel / Google Sheets
1. Download `tracking-ramadan.xlsx`
2. Upload ke Google Sheets atau buka di Excel
3. Isi nama di baris kuning emas (baris 2)
4. Klik sel hari → pilih ✓ atau - dari dropdown
5. Progress otomatis terhitung!

### HTML (Browser)
1. Buka `tracking-ramadan.html` di browser
2. Ketik nama di header atas
3. Klik kotak centang tiap amalan per hari
4. Data tersimpan otomatis (pakai localStorage)

## 📋 Struktur Amalan

| Waktu | Kategori | Jumlah Amalan |
|-------|----------|---------------|
| 03.00-04.00 | Sahur & Qiyamullail | 4 |
| 04.00-04.29 | Dzikir Intensif | 3 |
| 04.29-selesai | Subuh | 7 |
| 08.00-09.00 | Dhuha | 2 |
| 11.30-12.30 | Dzuhur | 5 |
| 15.00-15.35 | Ashar | 6 |
| 18.16-19.27 | Maghrib | 8 |
| 19.27-20.30 | Isya & Tarawih | 6 |
| 22.00-22.30 | Penutup Malam | 3 |

**Total: 44 amalan × 30 hari = 1,320 peluang ibadah**

## 🎨 Color Coding

- 🔵 **Biru** — Dekade 1 (Hari 1-10)
- 🟢 **Hijau** — Dekade 2 (Hari 11-20)
- 🟡 **Kuning** — Dekade 3 (Hari 21-30)
- 🔴 **Merah** — Amalan khusus (Doa Lailatul Qadr malam terakhir)

## 🛠️ Tech Stack

- **Excel:** openpyxl (data validation, conditional formatting)
- **HTML:** Vanilla JS, localStorage API, CSS animations
- **Design:** Clean, minimal, performance-focused

## 📝 Notes

- Waktu shalat disesuaikan dengan daerah masing-masing
- Jadwal bersifat panduan — fleksibel sesuai kondisi
- Bisa digunakan personal atau dishare ke jamaah/komunitas

## 🤝 Contributing

Pull requests welcome! Kalau ada saran amalan tambahan atau improvement fitur, silakan buka issue.

## 📄 License

MIT License - feel free to use, modify, and distribute

---

Made with 💚 for Ramadan 1446H / 2025
```

---

## **File Structure yang Di-upload**
```
ramadan-self-rebranding-tracker/
├── README.md
├── LICENSE
├── tracking-ramadan.xlsx
├── tracking-ramadan.html
├── jadwal-ramadan.html
├── screenshot-excel.png (optional)
├── screenshot-html.png (optional)
└── .gitattributes (untuk LFS kalau file Excel >100MB)
```

---

## **Topics/Tags untuk GitHub**
```
ramadan
productivity-tracker
habit-tracker
worship-tracker
checklist
excel
google-sheets
web-app
self-improvement
islamic-tools
