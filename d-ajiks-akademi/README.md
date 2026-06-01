# D Ajiks Akademi — Tes Kecerdasan (CAT)

Aplikasi **Computer Assisted Test (CAT)** untuk Bimbel **D Ajiks Akademi**.
Versi mandiri (self-contained): cukup `index.html` + `soal.json`, tanpa dependensi.

## Komposisi Soal (100 soal)

| Aspek | Nomor | Tipe | Jumlah |
|-------|-------|------|--------|
| **Verbal** | 1–60 | Sinonim (20), Antonim (20), Analogi (10), Kata Ganjil (10) | 60 |
| **Analitis** | 61–80 | Deret angka & huruf | 20 |
| **Praktis** | 81–100 | Hitung / Matematika | 20 |

- Durasi: **90 menit**.
- Setiap soal dilengkapi **pembahasan** yang tampil di layar *Lihat Pembahasan* setelah tes.
- Sinonim/Antonim/Analogi/Deret/Hitung sudah lewat validasi struktural + verifikasi
  komputasi (aritmetika & deret) agar tidak ada soal yang salah nalar.

## Menjalankan

Buka langsung di browser, atau lewat server statis:

```bash
python3 -m http.server 8000
# lalu buka http://localhost:8000/   (folder ini)
```

## Akses via GitHub Pages

Bila Pages aktif pada branch sumber (mis. `master`):

- v1 (lama): `https://gustiyuda14-source.github.io/psiko-kecerdasan-cat/`
- v2 (ini):  `https://gustiyuda14-source.github.io/psiko-kecerdasan-cat/d-ajiks-akademi/`
