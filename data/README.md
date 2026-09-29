# Data Tugas 1

## Dataset yang Dipilih

| Item | Isi |
|---|---|
| Nama dataset | Indonesia palm oil - Supply chain data |
| Sumber | Trase Open Data |
| URL | https://trase.earth/open-data/datasets/supply-chains-indonesia-palm-oil |
| Lisensi/ketentuan pakai | Mengikuti Terms of Use dan ketentuan lisensi dataset Trase |
| Ukuran file | 88 MB (ZIP); ukuran CSV dicatat setelah ekstraksi |
| Jumlah baris | 1.694.907 |
| Jumlah kolom | 34 |
| Periode data | 2013–2022 |
| Unit analisis | Observasi rantai pasok minyak sawit Indonesia |

## Deskripsi Dataset

Dataset Indonesia palm oil - Supply chain data merupakan dataset
rantai pasok minyak sawit Indonesia yang disediakan oleh Trase.

Dataset mencakup periode 2013–2022 dan memuat informasi mengenai
rantai pasok komoditas minyak sawit serta sejumlah indikator
perusahaan dan keberlanjutan.

## Sumber Dataset

Trase Open Data:

https://trase.earth/open-data/datasets/supply-chains-indonesia-palm-oil

Dataset tersedia untuk periode 2013–2022 dan terakhir diperbarui
pada 22 April 2025.

## Cara Memperoleh Data

1. Buka halaman dataset Trase.
2. Pilih Indonesia palm oil - Supply chain data.
3. Klik tombol Download.
4. Pilih CSV (zipped).
5. Ekstrak file ZIP.
6. Letakkan file CSV hasil ekstraksi pada:
   `data/raw/`

Dataset mentah tidak dimodifikasi.

## Citation

Benedict, J. J., Biddle, H., Gollnow, F., Heilmayr, R.,
Mueller, C., Ribeiro, V., & Suavet, C. (2024).
Indonesia palm oil supply chain (2018–2022) (Version 1.2).
Trase.
https://doi.org/10.48650/X83N-7M36

## Ketentuan Penggunaan

Penggunaan data mengikuti Terms of Use Trase dan ketentuan
lisensi yang berlaku pada dataset.

Sumber dan atribusi Trase dicantumkan ketika data digunakan.

## Aturan Penyimpanan

- Dataset mentah disimpan pada `data/raw/`.
- Dataset mentah tidak diubah.
- Dataset mentah tidak di-commit ke Git.
- Hasil transformasi disimpan pada `data/processed/`
  jika diperlukan.
- Seluruh proses transformasi harus dapat direproduksi
  dari dataset mentah.