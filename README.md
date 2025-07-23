Google Play App & Review Scraper with Topic Classification  

Script ini digunakan untuk **mengambil data aplikasi dan ulasan dari Google Play Store** menggunakan library `google-play-scraper`, sekaligus melakukan pembersihan data, klasifikasi topik ulasan, dan menyimpan hasil ke format Excel dan CSV.  

---

Fitur Utama:
- Scraping aplikasi berdasarkan kata kunci
- Mengambil deskripsi aplikasi & fitur potensial  
- Mengambil ulasan pengguna dengan filter meaningful review  
- Klasifikasi topik ulasan (Crash, Performance, Login, Ads, Fitur Hilang, Payment, Harga, Navigasi, Customer Support, UI/UX)  
- Export hasil scraping ke file `.xlsx` dan `.csv`  

---

Dependensi
```bash
pip install --upgrade google-play-scraper pandas openpyxl
