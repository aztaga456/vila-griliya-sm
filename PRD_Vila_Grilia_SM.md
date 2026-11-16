# Product Requirement Document (PRD)
## Website Landing Page & Booking Portal: Vila Griliya SM

* **Nama Produk:** Website Resmi Vila Griliya SM  
* **Versi Dokumen:** 1.1 (Revisi Kustomisasi)  
* **Status:** Live Prototype Available on Localhost  
* **Framework Styling:** Tailwind CSS (Modern, Fully Responsive)  
* **Lokasi / Alamat:** Dusun Jorong, Jln. Puri Rinjani, Kaki Gunung Rinjani, NTB  
* **Aset Brand & Visual:** `logo.jpg`, `vila.jpeg` (Kabin A-Frame Pegunungan)  

---

## 1. Executive Summary & Ringkasan Pembaruan

### 1.1 Profil Vila & Konsep Hunian
**Vila Griliya SM** adalah penginapan berkonsep kabin kayu segitiga (A-Frame) bernuansa sejuk alami di kaki Gunung Rinjani, beralamat di **Dusun Jorong, Jln. Puri Rinjani**. Website ini dirancang ramah pengunjung, berbahasa Indonesia, modern, dan memudahkan reservasi instan via WhatsApp.

### 1.2 Detail Kapasitas & Kamar
* **Total Kamar:** 5 Kamar Unit
  1. **3 Unit Kamar Tipe Biasa (Standard):**
     * Tarif: **Rp 250.000 / malam**
     * Kapasitas: 2 - 3 Tamu
     * Fasilitas: 1 Queen Bed, Kamar Mandi Dalam (*tanpa water heater*), Kipas / Udara Sejuk Pegunungan Alami, Free Wi-Fi, Teras Santai.
  2. **2 Unit Kamar Tipe Family Room:**
     * Tarif: **Rp 450.000 / malam**
     * Kapasitas: 4 - 6 Tamu
     * Fasilitas: Unit 2 Lantai dengan Balkon Menghadap Pemandangan Rinjani, Ruang Kumpul Keluarga, Akses Dapur Bersama.
  3. **Opsi Sewa Seluruh Vila (Full Area):**
     * Menyewa seluruh 5 kamar sekaligus untuk rombongan hingga 15–20 orang dengan privasi total 100%.

### 1.3 Penyesuaian Fasilitas
* **Catatan Penting:** Penginapan **TIDAK menyediakan water heater**. Suasana mandi mengutamakan kesegaran air pegunungan alami yang sejuk.
* **Fasilitas Tersedia:** Wi-Fi Gratis, Peralatan Barbeque & Api Unggun, Dapur Bersama & Alat Masak, Udara Sejuk Alami, Halaman Batu Koral, dan Parkir Luas.

---

## 2. Spesifikasi Antarmuka & Hero Section

### 2.1 Hero Section: Rounded Box Container
* **Bentuk Container:** Menggunakan kartu kontainer melengkung elegan (`rounded-3xl` hingga `rounded-[2.5rem]`) yang membungkus hero section dengan bayangan halus (*soft shadow*) sesuai gaya antarmuka `UI refrensi.jpg`.
* **Visualisasi Kabin:** Foto vila (`vila.jpeg`) ditampilkan penuh dan tajam di dalam bingkai gambar bersudut lengkung dengan efek bayangan dan border putih, memperlihatkan kemegahan dua kabin segitiga (A-Frame), balkon lantai dua, taman koral, dan panorama lereng Rinjani secara utuh tanpa terpotong atau tertutup gradasi berlebih.
* **Floating Booking Bar Overlap:** Komponen pencarian tanggal dan ikon fasilitas mengapung (*overlap*) di batas bawah kontainer hero box.

### 2.2 Headline 2 Baris Simpel & Ringkas
* **Baris 1 (Headline Tetap):**
  > **"Ketenangan Alami"**
* **Baris 2 (Hook Animasi Berganti Tiap 3.2 Detik):**
  1. `"di Kaki Rinjani"`
  2. `"di Kabin Kayu Sejuk"`
  3. `"bersama Keluarga"`
* Kata-kata dirancang ringkas (2–3 kata per baris) agar tidak terpecah menjadi 3 baris di berbagai ukuran layar smartphone maupun desktop.

---

## 3. Fitur Aktivitas & Rekreasi: Auto-Slide Carousel

* **Format:** Menggantikan format video lama menjadi **Auto-Slide Carousel Foto & Highlight**.
* **Mekanisme Otomatis:**
  * Berganti slide secara otomatis setiap 3.8 detik.
  * Terdapat tombol panah manual (*Prev / Next*) dan titik indikator (*dots*).
  * 4 thumbnail di bagian bawah yang dapat langsung diklik untuk melompat ke slide tertentu.
* **Konten Slide:**
  1. *Suasana Senja:* Kehangatan Kabin Kayu Segitiga di Waktu Senja.
  2. *Identitas Vila:* Sentuhan Rustic Alami Vila Griliya SM.
  3. *Balkon Atas:* Pemandangan Lepas Menatap Lembah Rinjani.
  4. *Malam Barbeque:* Area BBQ & Santai Halaman Batu Koral.

---

## 4. Alamat & Kontak Integrasi

* **Alamat Lengkap:** Dusun Jorong, Jln. Puri Rinjani, Kaki Gunung Rinjani, Nusa Tenggara Barat (NTB).
* **Nomor Kontak / WhatsApp:** **085967109790** (+62 859-6710-9790)
* **Integrasi WhatsApp Langsung:**
  * Tombol **"Cek Jadwal"** pada floating search bar otomatis menyusun pesan WhatsApp berisi:
    * Lokasi: Dusun Jorong, Jln. Puri Rinjani
    * Pilihan Tipe Kamar (Tipe Biasa Rp 250rb / Family Room)
    * Tanggal Check-in
  * Tautan langsung ke nomor: `https://wa.me/6285967109790`
* **Peta:** Tautan langsung ke Google Maps rute Dusun Jorong, Jln. Puri Rinjani.
