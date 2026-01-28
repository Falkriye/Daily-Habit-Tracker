# 📝 Daily Habit Tracker

Aplikasi web sederhana untuk melacak dan memantau kebiasaan harian Anda.

## ✨ Fitur Lengkap

### Fitur Utama
- ✅ **Tambah Kebiasaan** - Mudah menambahkan kebiasaan baru
- ✅ **Checklist Interaktif** - Centang kebiasaan yang sudah selesai
- ✅ **Progress Tracking** - Lihat progress harian secara visual
- ✅ **Hapus Kebiasaan** - Hapus kebiasaan yang tidak diperlukan
- ✅ **Reset Harian** - Tombol reset untuk memulai hari baru
- ✅ **Penyimpanan Otomatis** - Data tersimpan di localStorage browser
- ✅ **Auto-Reset** - Checklist otomatis reset setiap hari baru

### Fitur PWA (Progressive Web App)
- 📱 **Installable** - Dapat diinstall ke home screen smartphone
- 🔌 **Offline Mode** - Berfungsi tanpa koneksi internet
- ⚡ **Fast Loading** - Caching untuk performa optimal
- 🎯 **Native Experience** - Terasa seperti aplikasi native

### Desain & UX
- 🎨 **Modern UI** - Tampilan modern dengan gradient background
- 💚 **Calming Colors** - Warna hijau-biru yang menenangkan
- 📱 **Responsive** - Sempurna di mobile, tablet, dan desktop
- ✨ **Smooth Animation** - Animasi halus dan user-friendly
- 🎯 **Minimalist** - Desain bersih dan mudah digunakan

## 📦 File yang Disertakan

```
daily-habit-tracker/
│
├── daily-habit-tracker.html    # File utama aplikasi
├── manifest.json                # PWA manifest untuk installasi
├── service-worker.js            # Service worker untuk offline mode
└── README.md                    # Dokumentasi ini
```

## 🚀 Cara Menggunakan

### Instalasi

1. **Download semua file** ke satu folder yang sama
2. **Buka file `daily-habit-tracker.html`** di browser modern (Chrome, Firefox, Edge, Safari)

### Penggunaan Aplikasi

1. **Menambah Kebiasaan:**
   - Ketik nama kebiasaan di kolom input
   - Tekan tombol "Tambah" atau Enter
   - Kebiasaan akan muncul di daftar

2. **Menandai Kebiasaan Selesai:**
   - Klik checkbox di samping nama kebiasaan
   - Progress akan otomatis terupdate
   - Kebiasaan yang selesai akan bergaris coret

3. **Menghapus Kebiasaan:**
   - Klik tombol merah dengan ikon tempat sampah
   - Kebiasaan akan dihapus permanen

4. **Reset Checklist Harian:**
   - Klik tombol "Reset Hari Ini"
   - Semua checkbox akan dikosongkan
   - Kebiasaan tetap tersimpan

### Install sebagai PWA (Opsional)

**Di Android/Chrome:**
1. Buka aplikasi di Chrome
2. Klik ikon "Install Aplikasi" yang muncul
3. Atau klik menu (⋮) → "Install app" / "Add to Home screen"
4. Aplikasi akan muncul di home screen

**Di iOS/Safari:**
1. Buka aplikasi di Safari
2. Tap ikon Share (kotak dengan panah ke atas)
3. Pilih "Add to Home Screen"
4. Beri nama dan tap "Add"

**Di Desktop:**
1. Buka aplikasi di Chrome/Edge
2. Klik ikon install di address bar (⊕)
3. Atau klik menu → "Install Daily Habit Tracker"

## 🎯 Target Pengguna

- 🎓 Mahasiswa dan pelajar
- 💼 Pekerja profesional
- 👥 Masyarakat umum
- 🌱 Siapa saja yang ingin membangun kebiasaan positif

## 💾 Penyimpanan Data

- Data disimpan di **localStorage** browser
- Tidak memerlukan database atau backend
- Data tetap tersimpan saat refresh halaman
- Data akan hilang jika:
  - Cache browser dibersihkan
  - Aplikasi diakses dari browser/device berbeda
  
## 🔄 Auto-Reset Harian

Aplikasi secara otomatis mendeteksi pergantian hari:
- Checklist akan otomatis di-reset setiap hari baru
- Daftar kebiasaan tetap tersimpan
- Anda dapat memulai fresh setiap hari

## 🛠️ Teknologi yang Digunakan

- **HTML5** - Struktur aplikasi
- **CSS3** - Styling dan animasi
- **JavaScript (Vanilla)** - Logika aplikasi
- **Bootstrap 5** - Framework CSS modern
- **Bootstrap Icons** - Icon set
- **localStorage API** - Penyimpanan lokal
- **Service Worker** - Offline functionality
- **Web App Manifest** - PWA capabilities

## 📱 Kompatibilitas Browser

✅ Google Chrome (Recommended)
✅ Mozilla Firefox
✅ Microsoft Edge
✅ Safari (iOS & macOS)
✅ Samsung Internet
✅ Opera

## ⚡ Fitur Unggulan

### 1. Real-time Statistics
- Jumlah kebiasaan selesai
- Total kebiasaan
- Persentase progress
- Progress bar visual

### 2. Smart Auto-Save
- Setiap perubahan langsung tersimpan
- Tidak perlu tombol "Save"
- Data aman saat crash/close tab

### 3. Daily Reset Intelligence
- Deteksi otomatis pergantian hari
- Reset checklist tanpa hapus data
- Tracking tanggal terakhir

### 4. Responsive Design
- Optimal di layar kecil (mobile)
- Sempurna di layar besar (desktop)
- Adaptive layout

## 🎨 Kustomisasi

Anda dapat mengubah warna tema dengan mengedit variabel CSS:

```css
:root {
    --primary-color: #4CAF50;      /* Warna utama */
    --primary-dark: #388E3C;       /* Warna gelap */
    --secondary-color: #2196F3;     /* Warna sekunder */
}
```

## 📝 Tips Penggunaan

1. **Mulai dengan Sederhana** - Jangan tambahkan terlalu banyak kebiasaan sekaligus
2. **Spesifik** - Buat nama kebiasaan yang jelas (contoh: "Olahraga 30 menit" bukan "Olahraga")
3. **Konsisten** - Cek aplikasi setiap hari untuk tracking yang efektif
4. **Review Berkala** - Hapus kebiasaan yang tidak relevan lagi
5. **Install ke Home Screen** - Untuk akses lebih mudah

## 🔒 Privacy & Security

- ✅ Tidak ada data yang dikirim ke server
- ✅ Semua data tersimpan lokal di device Anda
- ✅ Tidak memerlukan login/registrasi
- ✅ Tidak ada tracking atau analytics
- ✅ 100% private dan offline-capable

## 🐛 Troubleshooting

**Data hilang setelah clear cache?**
- Data disimpan di localStorage yang terhapus saat clear cache
- Backup manual dengan screenshot jika perlu

**PWA tidak bisa diinstall?**
- Pastikan menggunakan HTTPS atau localhost
- Coba browser yang berbeda
- Pastikan file manifest.json dan service-worker.js tersedia

**Aplikasi tidak berfungsi offline?**
- Buka aplikasi sekali saat online untuk cache
- Tunggu service worker terinstall (cek console)

## 📄 Lisensi

Aplikasi ini gratis untuk digunakan dan dimodifikasi sesuai kebutuhan Anda.

## 🤝 Kontribusi

Silakan modifikasi dan kembangkan sesuai kebutuhan Anda!

## 📞 Support

Jika ada pertanyaan atau masalah, silakan dokumentasikan di browser console (F12) untuk debugging.

---

**Selamat membangun kebiasaan positif! 🌟**

Dibuat dengan ❤️ untuk membantu Anda mencapai goals harian