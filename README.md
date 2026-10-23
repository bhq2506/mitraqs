# Mitra Potensial QS APAC 2026

Web-app satu halaman dengan dua tab:

- **Shortlist mitra potensial** — 30 universitas non-Indonesia peserta **QS Higher Ed Summit: Asia Pacific 2026** sebagai calon mitra kerja sama ITS dengan peringkat QS WUR 2027, skor indikator, tier prioritas, skor kesesuaian, dan nama delegasi.
- **Semua universitas** — 207 universitas non-Indonesia dari daftar delegasi (tanpa penilaian), dengan filter shortlist/negara/status QS dan pencarian nama.

Buka `index.html` di browser, atau aktifkan GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

Catatan: tier, skor kesesuaian, kelebihan, risiko, dan modus kerja sama adalah analisis, bukan data QS. Data per 23 Oktober 2026.

## Cara tier ditentukan

1. Setiap universitas dinilai 1–5 pada lima dimensi: Riset/IRN (30%), STEM/maritim (25%), Reputasi QS (20%), Mobilitas (15%), Realisme (10%).
2. Skor kesesuaian = rata-rata berbobot ÷ 5 × 100.
3. Tier:
   - **A – Strategis:** skor ≥ 85 dan STEM/maritim ≥ 4
   - **B – Riset/program:** skor 75–84, atau ≥ 85 dengan STEM/maritim < 4
   - **C – Selektif:** skor < 75, atau override kepatuhan (BIT, Harbin Engineering — afiliasi pertahanan, perlu cek US Entity List)

## Status MoU dengan ITS

Kedua tab menandai status kerja sama tiap universitas, dicocokkan manual dengan basis data kerja sama luar negeri ITS (https://mou.its.ac.id/beranda/kerjasama, diambil 23 Oktober 2026):

- **Aktif** — ada MoU/MoA yang masa berlakunya belum habis
- **Kedaluwarsa** — pernah ada, sudah berakhir
- **Perlu dicek** — tanpa tanggal berakhir, atau nama/kampus di basis data tidak persis sama
- **Belum ada** — tidak ditemukan di basis data
