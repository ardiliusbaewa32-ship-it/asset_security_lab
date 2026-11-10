# Asset Security Lab

**Virtual Network Asset Identification Laboratory** — lab maya pengenalan aset keamanan jaringan
(Keamanan Jaringan, Fase F, Kelas XI SMK) · SMK Swasta Kristen BNKP Gunungsitoli.

Aplikasi web statis (HTML + CSS + JavaScript) tanpa backend, tanpa instalasi, dan tanpa build.
Progres peserta didik disimpan di `localStorage` browser masing-masing.

## Menjalankan di GitHub Pages

1. Buat repository baru di GitHub (mis. `asset-security-lab`).
2. Unggah **seluruh isi folder ini** (`index.html` harus berada di akar repository).
3. Buka **Settings → Pages**.
4. Pada *Build and deployment*, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
5. Tunggu 1–2 menit. Alamat situs: `https://USERNAME.github.io/asset-security-lab/`

## Menjalankan di komputer sendiri

Klik dua kali `index.html`, atau jalankan server statis apa pun, misalnya `python -m http.server`.

## Struktur

| Berkas / folder | Isi |
|---|---|
| `index.html` | Aplikasi utama (SPA) |
| `css/style.css` | Tampilan |
| `js/` | Navigasi & penyimpanan, ikon & ilustrasi SVG, Tanya RESA, lima tampilan, musik latar |
| `data/` | Materi, soal, basis pengetahuan Tanya RESA |
| `assets/img/` | Logo dan gambar karakter RESA |
| `panduan/` | Panduan guru dan peserta didik (siap cetak/PDF) |

## Logo sekolah & musik (opsional)

- Logo resmi: simpan sebagai `assets/img/logo-sekolah.png` (PNG transparan, ± 512×512 px).
- Musik sendiri: `assets/audio/musik-eksplorasi.mp3` dan/atau `assets/audio/musik-asesmen.mp3`.
  Bila tidak ada, browser membuat musik latar instrumental sendiri.

Semua kegiatan adalah simulasi; aplikasi tidak memindai jaringan nyata.
