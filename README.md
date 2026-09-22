# Konstruva — Landing Page

Landing page statis untuk Konstruva (Desain, Bangun & Renovasi).

## Isi folder

```
index.html      halaman utama
support.js      runtime yang merender halaman
assets/         logo + seluruh foto proyek (PNG)
```

Semua tautan gambar bersifat relatif, jadi folder ini bisa dipindah/di-upload apa adanya.

## Cara upload ke GitHub Pages

1. Buat repository baru di GitHub, misal `konstruva-web`.
2. Upload seluruh isi folder ini ke root repository (`index.html` harus berada di root, bukan di dalam subfolder).
3. Buka **Settings → Pages**.
4. Bagian **Source** pilih `Deploy from a branch`, branch `main`, folder `/ (root)`, lalu **Save**.
5. Tunggu 1–2 menit. Situs akan aktif di `https://<username>.github.io/konstruva-web/`.

Untuk memakai domain sendiri (`konstruva.id`), tambahkan domain di **Settings → Pages → Custom domain**, lalu arahkan DNS domain ke GitHub Pages.

## Catatan

- Halaman memuat React dan font Google dari internet, jadi perlu koneksi saat dibuka.
- Nomor WhatsApp: `62895322422375` (ubah di `index.html`, cari `waNumber`).
- Email dan website: `konstruva.id@gmail.com`, `konstruva.id`.
- Mengganti foto: timpa file di `assets/` dengan nama yang sama, tanpa mengubah kode.
