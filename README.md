# GmapScraper-V1.2

Perubahan:
Mengambil aria-label dari Elemen Ulasan: Menggunakan .get('aria-label') untuk mengambil nilai aria-label dari elemen ulasan dan memastikan teks tersebut berisi kata "ulasan".
Filter Angka dari aria-label: Menggunakan filter(str.isdigit, aria_label) untuk mengekstrak angka dari nilai aria-label.
