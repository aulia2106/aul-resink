<<<<<<< HEAD
# Aul Resink — Website Jual Beli Sparepart Variasi Motor

Website slicing untuk tugas **Slicing Website Bebas**, dibuat oleh **Rizky Aulia Putri**.

🔗 **Demo (Deployment):** https://claude.ai/artifact/4Z7tEQMWjARoCKndJ3v3Q5D
> Ganti link di atas dengan link deployment kamu sendiri (Netlify/Vercel/GitHub Pages) setelah di-deploy ulang, karena link Claude artifact bersifat sementara/privat.

---

## 📸 Screenshot

| Halaman | Tampilan |
|---|---|
| Katalog (Beranda) | ![Katalog](screenshots/katalog.png) |
| Keranjang | ![Keranjang](screenshots/keranjang.png) |
| Invoice (Checkout) | ![Invoice](screenshots/invoice.png) |
| Login / Buat Akun | ![Login](screenshots/login.png) |
| Mode Gelap | ![Dark Mode](screenshots/dark-mode.png) |

> Ambil screenshot dari masing-masing halaman lalu simpan ke folder `screenshots/` dengan nama file di atas.

---

## 📝 Penjelasan Singkat

**Aul Resink** adalah website e-commerce sederhana untuk jual beli sparepart & variasi motor (body kit, lampu, knalpot, spion, dan aksesoris). Dibangun murni dengan **HTML, CSS, dan JavaScript (DOM)** tanpa framework/library CSS seperti Tailwind atau Bootstrap.

### Fitur Utama
- **Halaman Katalog (Beranda)** — daftar produk dalam bentuk grid, bisa difilter berdasarkan kategori (Body Kit, Lampu, Knalpot, Spion, Aksesoris).
- **Keranjang Belanja** — klik ikon keranjang di navbar akan memunculkan popup/drawer berisi produk yang sudah ditambahkan, lengkap dengan kontrol jumlah (+/−) dan total harga otomatis.
- **Checkout / Invoice** — klik tombol "Checkout" pada keranjang akan memunculkan popup invoice (nomor invoice, rincian item & harga, total, status pesanan berhasil).
- **Login & Buat Akun** — klik tombol "Masuk" untuk membuka halaman autentikasi dengan dua tab:
  - **Buat Akun**: unggah foto profil (dengan preview), nama depan, nama belakang, **username otomatis** (digabung dari nama depan + nama belakang, bisa diedit manual), nomor telepon, kata sandi, dan nomor telepon pemulihan.
  - **Masuk**: login dengan username & password.
- **Mode Terang / Gelap** — toggle tema tersimpan di `localStorage` dan otomatis menyesuaikan preferensi sistem perangkat.
- **Responsive** — tampilan menyesuaikan di perangkat mobile, tablet, dan desktop (grid produk otomatis menyesuaikan jumlah kolom).

### Teknologi
- HTML5 semantik
- CSS3 murni (Custom Properties / CSS Variables untuk theming, Flexbox & CSS Grid untuk layout responsif)
- JavaScript vanilla (manipulasi DOM, event handling, `localStorage` untuk menyimpan keranjang & preferensi tema)

### Catatan
Data produk dan proses login/registrasi pada versi ini bersifat **front-end only** (belum terhubung ke backend/database sungguhan) — sesuai cakupan tugas slicing UI.

### Cara Menjalankan
1. Clone/download repository ini.
2. Buka file `index.html` langsung di browser, **atau**
3. Deploy folder ini ke Netlify / Vercel / GitHub Pages untuk mendapatkan link publik.

---

**Dibuat oleh:** Rizky Aulia Putri — 2026
=======
# aul-resink
>>>>>>> 45edce817b0cdfdbe54d1f4145e148538f02a3b8
