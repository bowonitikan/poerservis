<div align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEihP2EbYNmNB1vmNlvLysEXdLM7VrHkxWCEGmFl5XQGuoRcIq1p2uvtXnAJzzoosXfw3vH48JExdbGlQIdyjPT7HZcLw0TTkn3xT0Q1YKiT1QNbahFgRFkaCtGSB5IVr3niUa-ivOvEW4x82lVGJcw8uzRHMkWQDkE8_NTL_aRnTu9LtCkwHGH9Rr2-6fka/s225/purwanto.jpg" width="150" style="border-radius: 30px; box-shadow: 0 4px 8px rgba(0,0,0,0.2); margin-bottom: 20px;" alt="Logo Poer Electro">

  <h1>🛠️ Poer Electro Servis App</h1>
  <p><b>Sistem Manajemen Perbaikan Gadget Modern & Transparan</b></p>

  <!-- Badges Animasi & Warna -->
  <a href="https://nextjs.org/"><img src="https://img.shields.io/badge/Next.js-Black?style=for-the-badge&logo=next.js&logoColor=white" alt="Next JS"></a>
  <a href="https://tailwindcss.com/"><img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind"></a>
  <a href="https://turso.tech/"><img src="https://img.shields.io/badge/Turso_DB-4ade80?style=for-the-badge&logo=sqlite&logoColor=black" alt="Turso"></a>
  <a href="https://vercel.com/"><img src="https://img.shields.io/badge/Deployed_on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel"></a>
  
  <br><br>
</div>

---

## ✨ Fitur Unggulan

Aplikasi ini didesain dengan gaya **Claymorphism** yang lembut dan memanjakan mata, dilengkapi fitur-fitur super canggih:

*   📝 **Pendaftaran Mandiri (Self-Service):** Pelanggan dapat mendaftarkan keluhan gadgetnya sendiri dari HP mereka dan langsung mendapatkan Nomor Antrean.
*   🔍 **Pelacakan Status Real-time:** Tidak perlu lagi ditanya "Service-an saya sudah sampai mana?". Pelanggan cukup memasukkan Nomor ID untuk mengecek status secara mandiri.
*   🔐 **Admin Dashboard Terpusat:** Portal khusus kasir/teknisi untuk mengelola status perbaikan (Antrean ➔ Dikerjakan ➔ Selesai) lengkap dengan rincian biaya sparepart.
*   💬 **Integrasi WhatsApp:** Beri tahu pelanggan bahwa perangkat mereka sudah selesai hanya dengan satu kali klik. Sistem akan membuatkan format pesan WA otomatis beserta rincian biayanya!
*   🖨️ **Smart Print Nota:** Cetak struk/nota perbaikan berdesain rapi langsung dari *browser* untuk diberikan kepada pelanggan.
*   📊 **Live Report:** Pantau total antrean, perangkat yang sedang dikerjakan, dan yang siap diambil dalam satu layar *dashboard*.

---

## 🚀 Teknologi yang Digunakan

Aplikasi ini dibangun menggunakan arsitektur web modern yang super cepat:

| Komponen | Teknologi | Deskripsi |
| :--- | :--- | :--- |
| **Frontend** | Next.js 14 & React | Membangun antarmuka yang sangat responsif & interaktif. |
| **Styling** | Tailwind CSS | Desain khusus bergaya *Claymorphism* (efek 3D tanah liat). |
| **Backend** | Next.js API Routes | Menangani komunikasi data secara *serverless*. |
| **Database** | Turso (LibSQL) | Database Edge super cepat berbasis SQLite di *cloud*. |
| **Hosting** | Vercel | *Deployment* otomatis & *hosting serverless* gratis. |

---

## 📱 Panduan Penggunaan Singkat

### Untuk Pelanggan (Customer)
1. Buka halaman utama aplikasi.
2. Klik tombol **📝 Daftar Service** jika baru pertama kali datang. Isi data diri dan kendala perangkat, lalu simpan **ID Tiket** yang diberikan.
3. Klik tombol **🔍 Lacak Servis** untuk mengecek progres perangkat berdasarkan ID Tiket.

### Untuk Admin / Teknisi
1. Buka halaman utama, klik logo **🔐 Admin Portal** di paling bawah.
2. Masukkan kata sandi rahasia untuk masuk ke Dashboard.
3. Di Dashboard, Admin bisa melakukan:
   * **Tambah Antrean Manual** (Jika ada pelanggan *offline*).
   * **Update Status & Biaya** (Klik tombol ikon pensil/edit).
   * **Cetak Nota & Kirim WA** (Akan muncul otomatis jika status perangkat diubah menjadi `Selesai`).

---

## 🛠️ Instalasi di Komputer Lokal (Bagi Developer)

Jika ingin menjalankan aplikasi ini di laptop Anda sendiri, ikuti langkah ini:

1. **Clone repositori ini:**
   ```bash
   git clone [https://github.com/UsernameAnda/NamaRepositoryAnda.git](https://github.com/UsernameAnda/NamaRepositoryAnda.git)
   cd NamaRepositoryAnda