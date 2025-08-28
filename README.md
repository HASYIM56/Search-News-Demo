# 🔎 Search News • HASYIM56

Demo web sederhana untuk **mencari berita** menggunakan API publik [`h56-search-news-api`](https://h56-search-news-api.netlify.app/api/news).  
Website ini menampilkan antarmuka **dark theme, smooth, dan mobile friendly** untuk eksplorasi berita terbaru berdasarkan **kata kunci, bahasa, dan kategori**.

---

## 🚀 Fitur Utama

- 🔎 **Pencarian berita real-time** berdasarkan kata kunci.  
- 🌍 **Dukungan bahasa**: Bahasa Indonesia & English.  
- 📰 **Filter kategori berita**: Technology, Business, Sports, Entertainment, Health, Science, World.  
- 📱 **Responsive & mobile-friendly** dengan desain dark smooth UI.  
- ⚡ **Loading skeleton** untuk pengalaman lebih halus.  
- 📊 Menampilkan jumlah hasil pencarian.

---

## 🖼️ Preview UI

- **Form Pencarian**: Input kata kunci, pilih bahasa, pilih kategori.  
- **Hasil Pencarian**: Ditampilkan dalam bentuk **card berita** dengan gambar, judul, deskripsi, sumber, dan tanggal terbit.  
- **Status API & Info Bar**: Indikator status koneksi API dan progress pencarian.

---

## 📦 Teknologi yang Digunakan

- **HTML5**  
- **CSS3 (Custom Dark Theme)**  
- **Vanilla JavaScript (Fetch API)**  
- **Google Fonts** → `Inter` (UI), `Merriweather` (judul berita).

---

## 🔗 API yang Digunakan

### Base Endpoint
```http
https://h56-search-news-api.netlify.app/api/news

1. Cek Status API

fetch('https://h56-search-news-api.netlify.app/api/news')
  .then(r => r.json())
  .then(data => console.log(data));

2. Cari Berita (Contoh Request)

fetch('https://h56-search-news-api.netlify.app/api/news?q=teknologi&language=id&category=technology')
  .then(r => r.json())
  .then(data => console.log(data));

3. Parameter Query

Parameter	Deskripsi	Contoh

q	Kata kunci berita	teknologi, politik
language	Bahasa hasil berita	id, en
category	Kategori berita	technology, sports, business, health, science, world



---

⚙️ Cara Menjalankan

1. Clone repository / salin file HTML.

git clone <repo-url>
cd search-news-web


2. Buka file HTML di browser.

open index.html


3. Mulai pencarian berita dengan mengisi form pencarian.




---

📄 Struktur File

.
├── index.html   # File utama website (UI + Integrasi API)
├── README.md    # Dokumentasi proyek (file ini)


---

📜 Lisensi

Proyek ini dibuat untuk demo & pembelajaran.
API bebas digunakan tanpa rate-limit (unlimited access).