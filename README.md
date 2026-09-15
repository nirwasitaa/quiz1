# Emanate - Quiz 1 HTML/CSS

Implementasi desain pada PDF tugas menggunakan HTML dan CSS responsif.

## Struktur file
- `index.html` — halaman utama, mencakup Hero, Modular Design, Dark Features, Fast section, Pricing, dan Footer.
- `pricing.html` — halaman Pricing.
- `login.html` — halaman Log In.
- `signup.html` — halaman Sign Up.
- `style.css` — seluruh styling responsif.
- `assets/mountain-bg.svg` — background hero yang dibuat lokal agar project tidak bergantung pada internet.

## Menjalankan
Cukup buka `index.html` di browser, atau gunakan VS Code Live Server.

## Saran pembagian kontribusi Git (5 orang)
1. Anggota 1: `index.html` (Hero + navigasi)
2. Anggota 2: `index.html` (Modular + Features)
3. Anggota 3: `pricing.html` + Pricing section
4. Anggota 4: bagian **Style Guide / Modular Design** di `index.html` + styling terkait di `style.css`
5. Anggota 5: `login.html` + `signup.html`

Setiap anggota tetap harus melakukan commit dan push dari akun masing-masing agar histori GitHub menunjukkan kontribusi.

## Contoh alur Git untuk anggota
```bash
git clone <URL_REPOSITORY>
cd <NAMA_FOLDER>
git checkout -b feat/nama-fitur
# edit file
git add .
git commit -m "feat: implement nama fitur"
git push -u origin feat/nama-fitur
```

Setelah itu lakukan Pull Request / merge ke branch utama sesuai aturan kelompok.
