# Anang Florist — Landing Page Profesional

Landing page upgrade untuk **Toko Karangan Bunga Karawang (Anang Florist)**.

## Cara Menjalankan
Cukup buka `index.html` di browser — tanpa build step, tanpa dependency.

## Struktur
```
index.html      → Halaman lengkap (HTML + CSS + JS dalam satu file)
assets/         → 17 foto produk asli (diunduh dari situs lama)
```

## Fitur
- Desain premium (deep green + gold), font Fraunces & Plus Jakarta Sans
- Responsif penuh (mobile, tablet, desktop)
- Hero dengan kolase foto + badge kepercayaan
- Statistik animasi, 8 kartu layanan, keunggulan
- Galeri filterable (Papan Selamat / Duka Cita / Wedding / Bunga Meja) + lightbox (keyboard: Esc, ←, →)
- Cara pesan 4 langkah, testimoni, FAQ accordion
- CTA & tombol WhatsApp mengambang (wa.me/6281315021922)
- Peta Google Maps + info kontak lengkap
- SEO: meta description, Open Graph, JSON-LD schema Florist

## Yang Perlu Anda Sesuaikan (data contoh)
| Item | Lokasi | Keterangan |
|---|---|---|
| Angka statistik (10+ tahun, 5.000+ terkirim) | bagian `.stats-inner` | Sesuaikan dengan data asli |
| 3 testimoni | section `#testimoni` | Ganti dengan testimoni pelanggan asli |
| Jam operasional | topbar, `#kontak`, footer | Cek kebenaran jam buka |
| Embed peta | section `#kontak` | Ganti query maps jika pin kurang tepat |
| Link canonical & og:url | `<head>` | Sesuaikan dengan domain final |

## Deploy
Upload `index.html` + folder `assets/` ke hosting apa pun (cPanel, Netlify, Vercel, GitHub Pages).
Untuk WordPress: gunakan plugin seperti "File Manager" untuk mengganti halaman, atau hosting terpisah.
