# Gebang Store — Landing Page

Landing page utama untuk Gebang Studio (3 produk: Gebang Lagu, LoopStream, Gebang Render).

Live: https://gebangkiidiw.github.io/Demo-gebanglagu/

## Isi repo

- `index.html` — Landing page utuh (hero, 3 paket per produk, harga, FAQ, kontak)
- `snowcase/index.html` — Showcase UI interaktif Gebang Lagu (single-file, 144 KB, semua asset ter-inlined). Di-embed via iframe di landing page.

## Produk

| Slug | Produk | Halaman di repo |
|---|---|---|
| `#gebanglagu` | Gebang Lagu — Batch AI Music Creator | section di `index.html` |
| `#loopstream` | LoopStream — Live 24/7 | section di `index.html` |
| `#gebangrender` | Gebang Render — Render Cepat YouTube | section di `index.html` |

Setiap tombol "Pilih Paket" mengarah ke checkout di `lynk.id/gebangkiidiw/.../checkout`.

## Lokal development

```bash
python3 -m http.server 8000
# buka http://localhost:8000
```

## Lisensi

© Gebang Studio. Untuk preview & penjualan produk.
