# Portfolio Website — Dita Shahihah

Single-page personal portfolio (overview/CV style) with a live project gallery.
Pure **HTML + CSS** (no build step, no dependencies) — satu file `index.html`.

## Isi
Hero · About · Skills · **Projects (dengan link demo live)** · Experience · Education · Contact.

## Jalankan lokal
```bash
python3 -m http.server 8080
# buka http://localhost:8080
```
Atau cukup buka `index.html` langsung di browser.

## Deploy (gratis, pilih salah satu)

**Netlify (paling mudah — drag & drop):**
1. Buka https://app.netlify.com/drop
2. Seret file `index.html` (atau folder ini) ke sana → langsung dapat URL.

**Netlify via Git:** hubungkan repo ini → Netlify auto-deploy tiap push.

**GitHub Pages:**
1. Push repo ini ke GitHub (sudah).
2. Settings → Pages → Source: `main` / root → Save.
3. Live di `https://ditashahihah.github.io/<nama-repo>/`.

**Hugging Face Spaces (static):** buat Space SDK *Static*, upload `index.html`.

## Edit konten
Semua teks ada di `index.html` — ubah langsung (nama, ringkasan, skill, project, pengalaman).
Tambah project baru: salin satu blok `<div class="pcard">...</div>` di bagian Projects.
