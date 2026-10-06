# Catatan.

Aplikasi catatan harian yang simpel. Satu file HTML, tanpa server, tanpa build, jalan offline. Semua data tersimpan lokal di browser kamu — tidak ada yang dikirim ke mana pun.

## Fitur

- ✍️ Editor harian dengan **autosave** (tersimpan otomatis tiap berhenti mengetik)
- 📅 Navigasi tanggal: hari sebelumnya / hari ini / hari berikutnya
- 🔍 Pencarian ke seluruh catatan
- ⬇️ Ekspor & ⬆️ impor backup dalam format JSON
- 🗑 Hapus catatan per hari
- 🌓 Mode terang & gelap otomatis mengikuti sistem
- 📱 Responsif, enak dipakai di HP maupun laptop

## Cara pakai

1. Unduh / clone repo ini
2. Buka `index.html` di browser — selesai. Tidak perlu install apa pun.

Mau di-hosting? File ini statis, jadi bisa langsung ditaruh di GitHub Pages, Netlify, Vercel, atau hosting statis apa pun.

## Data

Catatan disimpan di `localStorage` browser dengan kunci `catatan.v1`, formatnya:

```json
{
  "2026-10-06": "isi catatan hari itu…"
}
```

Gunakan tombol **Ekspor JSON** untuk backup berkala.

## Lisensi

MIT — bebas dipakai, diubah, dan dibagikan.
