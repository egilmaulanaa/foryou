# Untukmu 🌹

Halaman surat interaktif (amplop → bunga → puisi).

## Isi folder
- `index.html` — halaman utama
- `musik-awal.mp3` — musik sebelum surat dibuka
- `musik-buka.mp3` — musik setelah surat dibuka

Ketiga file harus selalu berada di folder yang sama.

## Pengaturan
Buka `index.html`, ubah di bagian paling atas `<script>`:
- `WA_NUMBER` — nomor WhatsApp (format 62xxx, tanpa + dan tanpa 0 di depan)
- `WA_MESSAGE` — isi pesan otomatis
- `MUSIC_INTRO` / `MUSIC_OPEN` — nama file musik

## Pasang di GitHub Pages
1. Push semua isi folder ini ke repository GitHub.
2. Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)` → Save.
3. Tunggu 1–2 menit, lalu buka `https://USERNAME.github.io/NAMA-REPO/`.
