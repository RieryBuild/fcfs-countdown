# ⏱️ FCFS Countdown

Penghitung mundur simpel buat jadwal mint / claim **FCFS** (first come, first served).

Tambahin nama project + jam bukanya, pantau hitung mundurnya, dan pas nyampe nol
halaman bunyi **beep** + status berubah jadi **LIVE**. Nggak mau lagi kan kelewat
 gara-gara lupa jam?

## Fitur

- Countdown besar buat mint terdekat, update tiap detik
- Daftar banyak jadwal sekaligus, urut otomatis dari yang paling deket
- Badge status: **MENUNGGU** → **LIVE** (1 jam pertama setelah buka) → **LEWAT**
- Beep 3x pas countdown nyampe nol (tab harus tetap kebuka)
- Data tersimpan otomatis di browser (localStorage) — refresh nggak ilang
- Link mint per jadwal, tinggal klik pas LIVE
- Bahasa Indonesia, enak di HP maupun laptop

## Cara pakai

Nggak ada install, nggak ada server, nggak ada akun. Pilih salah satu:

1. **Download `index.html`**, buka di browser. Selesai.
2. Hosting statis di mana aja (GitHub Pages, Netlify, Vercel): taruh `index.html` sebagai halaman utama.

Jam yang diisi dianggap jam di perangkat kamu sendiri, jadi set jam mint-nya
sesuai zona waktu yang kamu pakai (mis. WITA).

## Kenapa dibuat?

Free mint FCFS itu seringnya habis dalam hitungan menit — yang menang yang udah
standby sebelum jam buka. Tool ini biar nggak ada lagi cerita "eh, udah buka toh?"

## Lisensi

MIT — bebas dipakai, diubah, disebar.
