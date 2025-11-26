# 🎬 IMDB Superhero Movie Scraping Project  
📌 Web Scraping Project for Data Collection & Analysis

---

## 📖 Overview

Project ini merupakan mini-project web scraping yang bertujuan mengumpulkan data film bertema **superhero** dari IMDB berdasarkan filter tertentu. Dataset ini dapat digunakan untuk analisis eksploratif, riset tren industri film, hingga pembuatan rekomendasi model berbasis Machine Learning.

Scraping dilakukan menggunakan Python (`BeautifulSoup / Requests`) dan hasil akhir disimpan dalam format **CSV** dan **Excel**.

---

## 🎯 Scraping Criteria

Dataset dikumpulkan berdasarkan kriteria berikut:

- 🎞️ **Genre:** Superhero Movie (Feature Film)
- ⭐ **Minimum Vote Count:** ≥ 5,000 votes
- 🔀 **Sorting:** Ranked by number of votes (descending)
- 🔎 Total data scraped: **200 films**

URL Referensi:  
🔗 `https://www.imdb.com/search/keyword/?keywords=superhero...&sort=num_votes,desc`

---

## 📦 Extracted Attributes

Setiap film memiliki field berikut:

| Attribute | Deskripsi |
|-----------|-----------|
| `Title` | Judul film |
| `Year` | Tahun rilis |
| `Genre` | Genre film (bisa lebih dari satu kategori) |
| `Runtime` | Durasi film |
| `Rating` | IMDb user rating |
| `Metascore` | Skor dari Metacritic |
| `Director` | Sutradara |
| `Votes` | Jumlah voting pengguna IMDb |
| `Gross` | Gross revenue (US) |

---

## 📁 Output Files

Format output scraping:

| File | Format | Rows |
|------|--------|------|
| `imdb_superhero_scraped.csv` | CSV | 200 |
| `imdb_superhero_scraped.xlsx` | Excel | 200 |

File ini berisi raw structured data hasil scraping dan siap diolah lebih lanjut.

---

## 🧪 Tools & Libraries

Scraping dilakukan menggunakan:

- `Python`
- `BeautifulSoup`
- `Requests`
- `Pandas`
