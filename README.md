# D Ajiks Akademi — Tes Kecerdasan (CAT)

Aplikasi **Computer Assisted Test (CAT)** untuk Bimbel **D Ajiks Akademi**.
Versi mandiri (self-contained): `index.html` + `soal.json`, tanpa dependensi.

## Struktur & Akses (GitHub Pages)

| URL | Isi |
|-----|-----|
| `…/psiko-kecerdasan-cat/` (root) | **D Ajiks Akademi (v2)** — versi utama |
| `…/psiko-kecerdasan-cat/v1/` | Versi lama (arsip) |

- v2 (root): `https://gustiyuda14-source.github.io/psiko-kecerdasan-cat/`
- v1 (lama): `https://gustiyuda14-source.github.io/psiko-kecerdasan-cat/v1/`

## Komposisi Soal v2 (100 soal)

| Aspek | Nomor | Tipe | Jumlah |
|-------|-------|------|--------|
| **Verbal** | 1–60 | Sinonim (20), Antonim (20), Analogi (10), Kata Ganjil (10) | 60 |
| **Analitis** | 61–80 | Deret angka & huruf | 20 |
| **Praktis** | 81–100 | Hitung / Matematika | 20 |

- Durasi: **90 menit**.
- Setiap soal dilengkapi **pembahasan** yang tampil di layar *Lihat Pembahasan* setelah tes.
- Soal sudah lewat validasi struktural + verifikasi komputasi (aritmetika & deret).

## Menjalankan Lokal

```bash
python3 -m http.server 8000
# v2: http://localhost:8000/
# v1: http://localhost:8000/v1/
```

## Deploy

Otomatis via GitHub Actions (`.github/workflows/deploy-pages.yml`) setiap push ke `master`.
Seluruh isi repo dipublish, sehingga root (v2) dan `/v1/` keduanya live.
