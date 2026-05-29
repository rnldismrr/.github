# Budgetly

**Platform Manajemen Keuangan Cerdas untuk Mahasiswa Indonesia**
<img src="assets/1.png" alt="Gambar 1" width="100%">

Partner kamu untuk keuangan yang lebih cerdas. Catat transaksi, atur anggaran, rencanakan tabungan, dan bagi tagihan bersama teman — semua dalam satu app yang dirancang untuk ritme hidup mahasiswa yang dinamis dan penuh kejutan.

---

## 📋 Daftar Isi

- [Tentang Budgetly](#tentang-budgetly)
- [Kenapa Mahasiswa Selalu Bokek?](#kenapa-mahasiswa-selalu-bokek)
- [Fitur Utama](#fitur-utama)
- [Cara Menggunakan Platform](#cara-menggunakan-platform)
  - [1. Registrasi & Login](#1-registrasi--login)
  - [2. Dashboard](#2-menggunakan-dashboard)
  - [3. Transaksi](#3-mencatat-transaksi)
  - [4. Budgeting & Kalender Tagihan](#4-mengatur-budget)
  - [5. Target Tabungan](#5-target-tabungan)
  - [6. Split Bill](#6-membuat-split-bill)
  - [7. Financial Health](#7-melihat-financial-health)
  - [8. Pantau Investasi](#8-memantau-investasi)
  - [9. Export Data](#export-data)
- [Tips Penggunaan](#tips-penggunaan)
- [Troubleshooting](#troubleshooting)
- [Tim Pengembang](#tim-pengembang)

---

## 💡 Tentang Budgetly

Budgetly adalah platform manajemen keuangan berbasis web yang dirancang khusus untuk mahasiswa Indonesia. Bukan aplikasi keuangan generik yang penuh fitur tidak relevan — Budgetly memahami konteks nyata kehidupan mahasiswa: uang kiriman yang harus diatur sampai akhir bulan, pengeluaran kos dan makan sehari-hari, nongkrong bareng teman, langganan digital, dan target tabungan yang selalu tertunda.

Platform ini hadir dengan pendekatan yang sederhana namun powerful: kamu yang catat, Budgetly yang menganalisa. Teknologi neural network di baliknya membantu mengidentifikasi setiap pola pengeluaran kamu secara otomatis, sehingga kamu tidak perlu repot mengkategorikan satu per satu.

**Links:**

- Website/URL: <https://budgetly-dbs.vercel.app/>
- Backend/Render: <https://budgetly-backend-qhl3.onrender.com/>
- AI/Render: <https://ai-budgetly.onrender.com/>

---

## Fitur Utama

| Fitur | Deskripsi |
|-------|-----------|
| 📒 **Catat Transaksi Unlimited** | Rekam setiap pemasukan dan pengeluaran tanpa batas, dengan kategorisasi otomatis |
| 🎯 **Budget Otomatis** | Atur batas pengeluaran per kategori dan pantau progress secara real-time |
| 💰 **Target Tabungan** | Buat goals dengan estimasi waktu tercapai yang dihitung dari kebiasaan belanjamu |
| 🤝 **Split Bill** | Bagi tagihan bersama teman dengan mudah, pantau siapa sudah bayar |
| 📊 **AI Insight** | Laporan visual mingguan bergaya editorial langsung ke Website-mu |
| 📈 **Investasi Sejak Kuliah** | Pantau harga aset investasi sebagai langkah awal literasi finansial |

---

## 🤔 Kenapa Mahasiswa Selalu Bokek?

Masalah finansial mahasiswa bukan karena tidak punya uang, tapi karena sistemnya yang tidak ada. Tiga masalah utama yang paling sering terjadi:

**01 — Lupa Catat Pengeluaran**
> "Tiba-tiba saldo tinggal 50 ribu, padahal baru awal bulan."

**02 — FOMO & Impulsive Buying**
> "Beli kopi mahal demi nongkrong, besoknya makan promag."

**03 — Nabung Cuma Wacana**
> "Niat nabung buat konser, malah kepake buat jajan seblak."

Budgetly hadir sebagai sistem yang selama ini tidak ada — membantu kamu tahu ke mana uang pergi, sebelum uangnya habis duluan.

---

## 📝 Cara Menggunakan Platform

### 1. Registrasi & Login

#### Daftar Akun Baru

**Langkah 1: Akses Halaman Registrasi**

Buka browser dan akses URL Budgetly. Klik "Mulai Gratis" di landing page, atau langsung akses `/auth/register`.

**Langkah 2: Isi Form Registrasi**

Halaman registrasi menampilkan form "Daftar." di sisi kanan dengan tampilan motivasi "Mulai perjalanan finansialmu." di sisi kiri. Form meminta:

- Nama Lengkap
- Email
- Nama Universitas *(opsional)*
- Password
- Konfirmasi Password

Di sisi kiri juga ditampilkan 4 keunggulan platform: Catat transaksi unlimited, Budget & target tabungan, Split bill dengan teman, dan AI insight keuanganmu.

Atau klik tombol **"Daftar dengan Google"** untuk registrasi instan tanpa mengisi form manual.

**Langkah 3: Klik "Daftar Sekarang"**

Setelah form terisi, klik tombol **"DAFTAR SEKARANG"**. Sistem akan membuat akun dan langsung mengarahkan ke Dashboard.

---

#### Jika Sudah Punya Akun

**Langkah 1: Akses Halaman Login**

Buka URL Budgetly. Halaman login menampilkan form "Masuk." di sisi kanan dengan pesan "Selamat datang kembali" di sisi kiri, dilengkapi statistik: 10K+ User, AI Powered, 100% Free.

**Langkah 2: Masukkan Kredensial**

Masukkan email dan password, lalu klik **"MASUK"**. Atau klik **"Masuk dengan Google"** untuk login menggunakan akun Google yang dipakai saat registrasi.

**Langkah 3: Proses Autentikasi Google**

Jika memilih Google, browser akan membuka tab baru dengan tampilan loading "Menghubungkan akun Google Anda..." — tunggu beberapa detik hingga proses selesai dan diarahkan otomatis ke Dashboard.

**Catatan Keamanan:**

- Sesi login disimpan secara aman di browser menggunakan token
- Jika sesi habis, sistem otomatis mengarahkan kembali ke halaman login
- Pengguna yang login via Google tidak memiliki password — fitur ganti password tidak tersedia untuk akun ini
- Terdapat tombol "Lupa Password?" di bawah field password untuk akun email/password

---

### 2. Menggunakan Dashboard

**Langkah 1: Kenali Layout Dashboard**

Setelah login, kamu akan langsung berada di halaman Dashboard (`/dashboard`). Sidebar di sebelah kiri menampilkan logo Budgetly, nama user, dan menu navigasi: Dashboard, Transactions, Budgeting, Savings, Split Bill, Financial Health, Investment, Settings, Logout.

**Langkah 2: Baca Metrik Utama**

Di bagian atas dashboard terdapat tiga panel utama:

- Panel kiri: **Total Saldo Aktif** dengan nominal besar dan status hemat/boros
- Panel tengah: **Spending Trends** berupa grafik mini
- Panel kanan: **Target Tabungan** dengan tombol "Buat Target"

**Langkah 3: Cek Peringatan**

Jika ada peringatan dari sistem (contoh: pengeluaran sudah melebihi pemasukan), banner notifikasi berwarna akan muncul di bagian kanan dengan tombol **"Analisis Lengkap"** yang mengarah ke halaman Financial Health.

**Langkah 4: Lihat Transaksi Terbaru**

Di bagian tengah dashboard terdapat daftar "Transaksi Terbaru" — 5 transaksi terakhir yang dicatat. Klik **"Lihat Semua"** untuk menuju halaman Transactions.

**Langkah 5: Pantau Budget dan Grafik**

Bagian bawah menampilkan grafik pengeluaran dan pemasukan per bulan, donut chart distribusi pengeluaran per kategori, dan section **"Budget Limits"** yang menampilkan status budget saat ini.

---

### 3. Mencatat Transaksi

**Langkah 1: Buka Halaman Transaksi**

Klik menu **"Transactions"** di sidebar. Halaman akan menampilkan judul "Transaksi." dengan navigator bulan di bawahnya.

**Langkah 2: Navigasi Antar Bulan**

Gunakan tombol panah kiri (←) dan kanan (→) di samping nama bulan untuk berpindah ke bulan lain. Klik nama bulan di tengah untuk kembali ke bulan ini.

**Langkah 3: Baca Summary**

Di bagian atas halaman terdapat tiga angka besar:

- **Total Pemasukan** — semua income bulan ini
- **Total Pengeluaran** — semua expense bulan ini
- **Selisih Bersih** — hasil akhir (bisa positif atau negatif)

Terdapat pula indikator perbandingan vs bulan lalu (contoh: "+100% vs Bulan Lalu").

**Langkah 4: Gunakan Filter**

Di panel kanan terdapat filter transaksi:

- **Kategori** — pilih satu atau beberapa kategori (Semua, Makan & Minum, Transportasi, Pendidikan, Hiburan & Lifestyle, Belanja)
- **Tipe** — Semua, Income, atau Expense
- **Metode Pembayaran** — pilih sesuai metode yang ingin ditampilkan

Klik **"Reset All"** untuk menghapus semua filter aktif.

**Langkah 5: Tambah Transaksi Baru**

Klik tombol **"TAMBAH TRANSAKSI +"** di pojok kanan atas. Modal "Input Transaksi." akan muncul.

**Langkah 6: Isi Form Transaksi**

| Field | Keterangan | Wajib |
|-------|------------|-------|
| Tipe Transaksi | Toggle: EXPENSE / INCOME | ✅ |
| Tanggal | Pilih tanggal — default hari ini | ✅ |
| Nominal (Rp) | Masukkan angka, contoh: 80000 | ✅ |
| Deskripsi | Nama/keterangan transaksi | ✅ |
| Kategori | Pilih dari dropdown — bisa ter-isi otomatis | ✅ |
| Metode Pembayaran | E-wallet, bank transfer, dll | ✅ |
| Catatan | Keterangan tambahan | ❌ |

Contoh pengisian untuk pemasukan: Tipe = INCOME, Deskripsi = "REIMBURSE DARI ORANG TUA", Kategori = "Uang Saku", Metode = "Bank Transfer".

Contoh pengisian untuk pengeluaran: Tipe = EXPENSE, Deskripsi = "INDOMIE + MIE + SUKA PULANG - PERGI", Kategori = "Transportasi", Catatan = "Untuk kebutuhan transportasi".

**Langkah 7: Fitur Auto-Kategorisasi**

Setelah selesai mengetik deskripsi dan kursor berpindah dari field tersebut, sistem secara otomatis menganalisis teks dan mengisi kategori yang paling sesuai. Jika hasilnya tidak tepat, ubah kategori secara manual menggunakan dropdown.

**Langkah 8: Simpan Transaksi**

Klik **"SIMPAN TRANSAKSI →"**. Transaksi langsung muncul di daftar dan semua angka summary diperbarui otomatis.

**Langkah 9: Baca AI Journal**

Di panel kanan atas terdapat section **"AI JOURNAL"** yang memberikan analisis singkat bulan ini. Tersedia juga chip shortcut **"Tab Nabung"** dan **"Anggota Nabung"** untuk aksi lanjutan.

---

### 4. Mengatur Budget

#### Tab Budget

**Langkah 1: Buka Halaman Budgeting**

Klik menu **"Budgeting"** di sidebar. Halaman menampilkan judul "Budgeting." dengan dua tab di pojok kanan atas: **Budget** dan **Kalender**, serta tombol **"Tambah Kategori +"**.

**Langkah 2: Kondisi Awal — Belum Ada Budget**

Jika belum pernah membuat budget, halaman akan menampilkan ilustrasi kosong dengan tulisan "Belum Ada Budget" dan tombol **"Tambah Budget Pertama"**. Klik tombol tersebut untuk mulai.

**Langkah 3: Tambah Budget Kategori**

Modal "Tambah Budget" akan muncul dengan dua field:

- **Kategori** — dropdown pilih kategori (contoh: Tempat Tinggal, Makan & Minum, Hiburan & Lifestyle, Langganan, Pendidikan)
- **Limit Anggaran** — masukkan nominal batas, contoh: 900000

Klik **"Simpan"** untuk menyimpan, atau **"Batal"** untuk membatalkan.

**Langkah 4: Pantau Status Budget**

Setelah ada transaksi di kategori tersebut, kartu budget akan menampilkan:

- Nama dan ikon kategori
- Nominal terpakai vs limit
- Progress bar dengan label persentase
- Badge **"OVERBUDGET"** merah jika sudah melebihi batas

Contoh tampilan: Summary header menampilkan "Budget Bulan Ini: Rp 3.500.000" dengan persentase "171%" jika sudah overbudget.

#### Tab Kalender

**Langkah 1: Buka Tab Kalender**

Klik tab **"Kalender"** di sebelah tab Budget. Halaman berubah menampilkan grid kalender bulan berjalan.

**Langkah 2: Baca Kalender Tagihan**

Tanggal-tanggal yang memiliki tagihan terjadwal akan menampilkan chip berwarna dengan nama tagihan. Panel di sebelah kanan menampilkan **"Daftar Tagihan"** lengkap dengan nama, nominal, dan status "↑ Tambah Lunas" per tagihan.

**Langkah 3: Tambah Tagihan Rutin**

Klik tombol **"+ Tambah Tagihan"** di pojok kanan atas kalender. Modal "Tambah Tagihan" muncul dengan field:

- **Nama Tagihan** — contoh: "LANGGANAN NETFLIX BULANAN"
- **Nominal** — contoh: 50000
- **Kategori** — contoh: Langganan
- **Tanggal Jatuh Tempo** — pilih tanggal dalam bulan (0–31)

Klik **"Simpan"** untuk menyimpan tagihan rutin.

---

### 5. Target Tabungan

**Langkah 1: Buka Halaman Savings**

Klik menu **"Savings"** di sidebar. Halaman menampilkan judul "Target Tabungan." dengan info jumlah goal aktif dan tombol **"Tambah Goal +"** di pojok kanan atas.

**Langkah 2: Kondisi Awal**

Jika belum ada goal, summary menampilkan "Total Tabungan: Rp 0" dan "0% dari Target Total". Tersedia tombol untuk langsung membuat goal pertama.

**Langkah 3: Buat Goal Baru**

Klik **"Tambah Goal +"**. Modal "Buat Goal Baru" muncul dengan field:

- **Nama Goal** — contoh: "iPhone 17 256"
- **Target (Rp)** — contoh: 17000000
- **Deadline *(opsional)*** — masukkan tanggal target, contoh: 06/09/yyyy

Klik **"Buat Goal"** untuk menyimpan.

**Langkah 4: Lihat Goal Card**

Setelah goal dibuat, kartu goal muncul dengan:

- Label status: **"AKTIF"**
- Nama goal
- Persentase progress: 0%
- Nominal terkumpul: Rp 0
- Sisa yang dibutuhkan
- Tombol **"Top Up Goal"**

**Langkah 5: Top Up Dana ke Goal**

Klik **"Top Up Goal"** pada kartu goal yang ingin ditambah. Masukkan nominal yang ingin disisihkan dan catatan opsional. Progress ring dan persentase akan langsung diperbarui setelah berhasil.

**Langkah 6: Baca AI Saving Tips**

Di bawah daftar goal terdapat section **"AI Saving Tips"** dengan dua tip:

- **Optimalkan Pengeluaran** — Tips hemat berdasarkan data transaksi untuk rekomendasi personal
- **Konsistensi Menabung** — Menabung secara rutin, meskipun kecil, akan membantu kamu mencapai goal lebih cepat

---

### 6. Membuat Split Bill

**Langkah 1: Buka Halaman Split Bill**

Klik menu **"Split Bill"** di sidebar. Halaman menampilkan judul "SPLIT BILL.." dengan summary stats: total tagihan keseluruhan, jumlah tagihan, dan total orang terlibat. Di pojok kanan atas terdapat tombol **"Belum Lunas"**, **"Riwayat"**, dan **"Buat Split Bill +"**.

**Langkah 2: Buat Split Bill Baru**

Klik **"Buat Split Bill +"**. Modal "BUAT SPLIT BILL" muncul.

**Langkah 3: Isi Detail Utama**

- **Nama Tagihan** — contoh: "Agemeno Ramen Resto, South Jakarta"
- **Tanggal** — contoh: 26/05/2026
- **Metode Split** — pilih **"Sama Rata"** atau **"Per Item"**

**Langkah 4A — Jika Memilih Sama Rata:**

- Input item dan harga total
- Pilih siapa saja yang ikut
- Tambah peserta dengan klik ikon "+"
- Peserta yang ditambahkan akan otomatis terbagi sama rata
- Klik **"Konfirmasi & Kirim"**

**Langkah 4B — Jika Memilih Per Item:**

- Input setiap nama item beserta harganya
- Untuk setiap item, pilih siapa saja yang memesan dengan mencentang nama peserta
- Total Tagihan dihitung otomatis
- Di bagian bawah, masukkan nama peserta yang membayar — share amount dihitung otomatis per orang
- Klik **"Konfirmasi & Kirim"**

**Langkah 5: Pantau Status Pembayaran**

Setelah split bill dibuat, kartu akan muncul di halaman Split Bill dengan:

- Nama tagihan dan total nominal
- Jumlah tagihan dan peserta
- Avatar peserta yang terlibat
- Status pembayaran per orang (badge hijau "Lunas" / status belum bayar)
- Tombol **"SELESAIKAN"** dan ikon tambah untuk menandai pembayaran

---

### 7. Melihat Financial Health

**Langkah 1: Buka Halaman Financial Health**

Klik menu **"Financial Health"** di sidebar. Halaman menampilkan judul **"Financial Health."** dengan subtitle "Analisis AI mencakup keseluruhan transaksi dan data keuangan serta model prediksi."

> **Notes:** Jika ingin menjalankan Financial Health, masuk ke laman [CC26-PSU168](https://ai-budgetly.onrender.com/) terlebih dahulu untuk mengaktifkan layanan AI-nya.

**Langkah 2: Baca Skor Kesehatan Keuangan**

Di bagian kiri atas terdapat gauge melingkar dengan skor di tengah (contoh: 68) dan label grade di bawahnya (contoh: "Grade C — Perlu Perhatian").

**Langkah 3: Pahami Analisis AI**

Di sebelah kanan gauge terdapat panel **"Analisis AI"** dengan penjelasan singkat faktor penentu skor. Di bawahnya terdapat dua kolom:

- **Situasi Buruk** — poin-poin negatif yang perlu diperbaiki (dengan ikon merah)
- **Dampak Skor** — dampak dari kondisi tersebut terhadap skor

**Langkah 4: Cek Ringkasan Pengeluaran**

Scroll ke bawah untuk melihat section **"Ringkasan Pengeluaran."** yang menampilkan:

- Volume transaksi total
- Grafik tren dengan toggle Pengeluaran/Pemasukan
- Breakdown per kategori beserta persentase dan status badge (contoh: BOROS)

**Langkah 5: Pahami Analisis Perilaku Belanja**

Section **"Analisis Perilaku Belanja."** menampilkan tiga kolom:

- **Kerawanan** (ikon segitiga kuning) — contoh: Pengeluaran melebihi pemasukan sebesar 42,8%
- **Hal Positif** (ikon bintang hijau) — poin-poin finansial yang sudah baik
- **Hal Aktif** (ikon api oranye) — aktivitas finansial yang sedang berjalan

**Langkah 6: Baca Prediksi Pengeluaran**

Section **"Prediksi Pengeluaran."** menampilkan **"Budgetly AI Forecast"** — proyeksi pengeluaran 7 hari ke depan dengan:

- Total prediksi pengeluaran
- Rata-rata per hari
- Hari pengeluaran tertinggi yang diprediksi
- Persentase akurasi model
- Tombol **"Atur Budget Kategori"** dan **"Lihat Semua Transaksi"**

**Langkah 7: Terapkan Rekomendasi**

Section **"Rekomendasi AI."** menampilkan saran konkret beserta estimasi penghematan yang bisa diraih jika rekomendasi diikuti.

---

### 8. Memantau Investasi

**Langkah 1: Buka Halaman Investment**

Klik menu **"Investment"** di sidebar. Halaman menampilkan judul **"Pantau Investasi."** dengan subtitle "Data harga terkini untuk referensi investasi finansialmu."

**Langkah 2: Cek Harga Aset**

Di bagian atas terdapat tiga kartu harga (diperbarui setiap 1 menit):

- **Harga Emas** — harga per gram dalam Rupiah
- **Bitcoin (IDR)** — harga BTC dalam Rupiah
- **Harga per Gram (USD)** — konversi USD

Setiap kartu dilengkapi grafik sparkline dan perubahan harga.

**Langkah 3: Baca Panduan Investasi Pemula**

Panel di bawah price cards memberikan penjelasan singkat tentang aset yang ditampilkan, cara membandingkannya, dan langkah awal memulai investasi.

**Langkah 4: Pelajari Tips Investasi**

Section **"Tips Investasi."** menampilkan empat kartu:

- **Mulai dari yang Kecil** — mulai dengan Rp 10.000–50.000 untuk membangun kebiasaan
- **Diversifikasi Portofolio** — sebarkan investasi ke beberapa instrumen
- **Investasi Jangka Panjang** — manfaatkan compound interest dari investasi rutin
- **Terus Belajar** — ikuti berita finansial dan bergabung komunitas investor

**Langkah 5: Kenali Profil Risiko**

| Profil | Return | Karakteristik |
|--------|--------|---------------|
| **Konservatif** | 0–5% | Fokus pelestarian modal, cocok untuk dana darurat atau tujuan jangka pendek |
| **Moderat** | 5–10% | Keseimbangan pertumbuhan dan keamanan, cakrawala investasi 3–5 tahun |
| **Agresif** | 10%+ | Toleransi risiko tinggi, cocok untuk saham, reksa dana saham, kripto, dan ETF |

**Langkah 6: Lihat Perbandingan Instrumen**

| Instrumen | Risiko | Likuiditas | Modal Min | Imbal Hasil |
|-----------|--------|------------|-----------|-------------|
| Deposito Bank | Sangat Rendah | Rendah | Rp 1 juta | Ya, 20% |
| Reksa Dana Pasar Uang | Rendah | Tinggi | Rp 10 ribu | Tidak |
| Obligasi/SBN | Rendah | Sedang | Rp 1 juta | Ya 10% |
| Emas | Sedang | Sedang | Rp 5 ribu | Tidak |
| Reksa Dana Saham | Tinggi | Tinggi | Rp 10 ribu | Tidak |
| Saham | Tinggi | Tinggi | Rp 100 ribu | Tidak |
| Bitcoin/Kripto | Sangat Tinggi | Sangat Tinggi | Rp 10 ribu | Ya 0,1% |

**Langkah 7: Gunakan Kalkulator Aturan 72**

Formula sederhana untuk menghitung berapa lama menggandakan investasi:

```
72 ÷ Return% = Jumlah Tahun
```

Contoh: `72 ÷ 8 = 9 Tahun`

**Langkah 8: Pahami Dollar Cost Averaging (DCA)**

Investasi rutin dalam jumlah kecil tetap dapat berkembang signifikan dalam jangka panjang. Platform menampilkan simulasi DCA dengan visualisasi progress menabung bulanan.

---

## 📤 Export Data

**Cara Export Transaksi ke CSV:**

1. Buka halaman **"Settings"** via menu sidebar atau klik avatar profil
2. Scroll ke section **"Preferensi & Data"**
3. Klik ikon/tombol **"CSV"** di sebelah teks "Export Transaksi"
4. File CSV akan otomatis terunduh berisi seluruh riwayat transaksi akun

File CSV dapat dibuka di Microsoft Excel, Google Sheets, atau aplikasi spreadsheet lainnya untuk analisis lebih lanjut.

---

## 🎯 Tips Penggunaan

**1. Catat Transaksi Sesegera Mungkin**

Jangan tunda hingga akhir hari atau akhir minggu. Langsung buka Budgetly setelah setiap transaksi terjadi. Kebiasaan ini membuat data lebih akurat dan analisis AI Journal lebih relevan.

**2. Set Budget Realistis, Bukan Ideal**

Budget yang terlalu ketat justru sering dilanggar dan membuat frustrasi. Lihat rata-rata pengeluaran 2–3 bulan terakhir dari AI Journal, lalu set limit yang sedikit di bawahnya sebagai target wajar.

**3. Jadwalkan Semua Tagihan Rutin di Kalender**

Masukkan semua tagihan bulanan (kos, langganan streaming, internet, dll) ke kalender tagihan di awal bulan. Ini mencegah keterlupaan dan membantu mengalokasikan budget yang lebih akurat.

**4. Gunakan Split Bill Konsisten**

Setiap makan atau nongkrong bareng, langsung buat split bill di tempat. Ini menghindari momen canggung saat nagih belakangan dan memastikan tidak ada yang kelewat.

**5. Top Up Savings Segera Setelah Terima Uang**

Begitu uang kiriman atau gaji masuk, langsung sisihkan ke goals tabungan sesuai target. Baru sisanya dipakai untuk kebutuhan bulan ini. Prinsip "bayar diri sendiri dulu" terbukti membuat tabungan lebih konsisten.

**6. Pantau Financial Health Score Tiap Akhir Bulan**

Jadikan skor Financial Health sebagai laporan bulanan. Perhatikan tren dari bulan ke bulan dan coba terapkan minimal satu rekomendasi AI per bulan.

**7. Lihat AI Journal Sebelum Bikin Budget Bulan Baru**

Sebelum set budget bulan depan, baca dulu AI Journal di halaman Transaksi. Informasi tentang kategori terbesar dan perbandingan bulan lalu sangat berguna untuk menyesuaikan anggaran dengan lebih tepat.

---

## 🆘 Troubleshooting

### Tidak bisa login

- Pastikan email dan password yang dimasukkan sudah benar, perhatikan huruf besar dan kecil pada password
- Jika mendaftar menggunakan Google, gunakan tombol "Masuk dengan Google" — tidak bisa login dengan email/password manual
- Bersihkan cache dan cookies browser, lalu coba lagi
- Gunakan fitur "Lupa Password?" jika lupa password akun email/password

### Auto-kategorisasi tidak berjalan saat input transaksi

- Pastikan deskripsi transaksi diisi lebih dari 2 kata agar sistem memiliki cukup konteks untuk menganalisis
- Klik field lain atau tekan Tab setelah selesai mengetik deskripsi — proses analisis dimulai saat kursor meninggalkan field deskripsi
- Jika koneksi lambat, tunggu beberapa detik
- Pilih kategori secara manual jika tidak ada saran yang muncul

### Health Score tidak berubah meskipun sudah banyak transaksi

- Health Score di-cache selama 1 jam untuk menjaga performa platform. Tunggu atau gunakan tombol Refresh di halaman Financial Health
- Pastikan transaksi yang dicatat sudah memiliki kategori yang benar — skor dihitung berdasarkan distribusi kategori dan rasio tabungan
- Fitur refresh dibatasi untuk mencegah beban server berlebih

### Prediksi pengeluaran tidak tersedia atau tidak akurat

- Sistem prediksi membutuhkan minimal data dari 2 bulan penuh. Pastikan sudah mencatat transaksi secara konsisten setidaknya 2 bulan terakhir
- Semakin banyak dan konsisten data yang dicatat, semakin akurat proyeksinya
- Persentase akurasi model ditampilkan langsung di halaman Financial Health

### Harga investasi tidak berubah

- Data harga diperbarui secara berkala dari API publik. Refresh halaman dan tunggu beberapa saat
- Timestamp "Data diperbarui X menit yang lalu" di bagian atas halaman menunjukkan kapan terakhir data diambil
- Jika masalah berlanjut lebih dari 10 menit, kemungkinan ada gangguan dari penyedia data eksternal — coba lagi beberapa saat kemudian

### Split bill tidak update setelah tandai lunas

- Refresh halaman setelah melakukan perubahan status
- Pastikan koneksi internet stabil saat menekan tombol konfirmasi

### Export CSV tidak terunduh

- Pastikan browser tidak memblokir unduhan otomatis — periksa pengaturan izin unduhan di browser
- Coba gunakan browser lain (Chrome atau Edge direkomendasikan)
- Pastikan sudah ada transaksi yang tercatat — file tidak akan dibuat jika data kosong

---

## 👥 Tim Pengembang

**Team CC26-PSU168 — Dicoding Coding Camp DBS Foundation 2026**

### Fullstack Web Developer

| ID | Nama | Institusi |
|----|------|-----------|
| CFCC001D6Y0247 | Ahmad Faris Al Aziz | IPB University |
| CFCC001D6Y0322 | Renaldi Simamora | IPB University |

### Data Scientist

| ID | Nama | Institusi |
|----|------|-----------|
| CDCC001D6Y0082 | Muhammad Omar Wylie | IPB University |

### AI Engineer

| ID | Nama | Institusi |
|----|------|-----------|
| CACC452D6Y0694 | Zaky Pratama Adriano | Universitas Muhammadiyah Jakarta |
| CACC283D6Y1176 | Aditya Pratama Juliyawan | Universitas Negeri Semarang |

---

## 📞 Kontak & Support

Untuk pertanyaan, laporan bug, atau kontribusi pengembangan, silakan buka issue di repository GitHub proyek ini atau hubungi tim pengembang.

---

*Versi Dokumen: 1.0.0*  
*Program: Dicoding Coding Camp DBS Foundation 2026*  
*© 2026 Budgetly. Smart Finance for Students.*
