# Kebijakan Privasi Resmi Lacakin (100% Offline-First Privacy Policy)

**Terakhir Diperbarui:** 26 Agustus 2026

Selamat datang di **Lacakin** ("Aplikasi"). Kami berkomitmen penuh untuk melindungi privasi finansial Anda. Kebijakan Privasi ini menjelaskan bagaimana Aplikasi menangani informasi Anda dengan filosofi **100% Offline-First**.

---

## 1. Prinsip Utama: Nol Kebocoran Data (Zero Cloud Leakage)
- **Tidak Memerlukan Akun**: Aplikasi tidak meminta pendaftaran nama lengkap, alamat surel (email), nomor telepon, atau data sensitif perbankan.
- **Penyimpanan 100% Lokal**: Seluruh basis data transaksi, dompet, anggaran, target tabungan, dan berkas citra struk belanja disimpan secara eksklusif di memori internal perangkat Anda menggunakan basis data SQLite lokal.
- **Nol Server Luar**: Kami tidak mengoperasikan server penyimpanan awan (*cloud*), basis data jarak jauh, maupun *backend* pengumpul data.

---

## 2. Penggunaan Izin Perangkat (Device Permissions)
Aplikasi hanya meminta izin sistem operasi yang benar-benar esensial untuk fungsionalitas lokal:
1. **Kamera (`android.permission.CAMERA`)**:
   - Digunakan secara eksklusif untuk mengambil foto struk belanja fisik.
   - Pemrosesan teks (OCR) dilakukan 100% di memori ponsel melalui *Google ML Kit On-Device Text Recognition*.
   - Gambar struk tidak pernah dikirim atau diunggah ke internet.
2. **Pemberitahuan Lokal (`android.permission.POST_NOTIFICATIONS`)**:
   - Digunakan murni oleh sistem notifikasi luring untuk mengingatkan pencatatan harian dan batas anggaran.
3. **Biometrik (`android.permission.USE_BIOMETRIC`)**:
   - Digunakan untuk membuka kunci aplikasi secara lokal menggunakan modul keamanan sidik jari atau wajah ponsel.

---

## 3. Nol Pelacak & Analitik Pihak Ketiga
- Aplikasi **TIDAK** menyertakan SDK pelacak atau analitik pihak ketiga (seperti Firebase Analytics, Facebook Pixel, Mixpanel, dll).
- Aplikasi **TIDAK** menyertakan jaringan periklanan pihak ketiga (*100% Bebas Iklan*).

---

## 4. Cadangan & Kendali Data Pengguna
- Pengguna memiliki kendali penuh atas data mereka. Anda dapat mengekspor salinan cadangan lengkap berupa berkas JSON kapan saja.
- Menghapus aplikasi dari perangkat akan menghapus seluruh data lokal secara permanen kecuali Anda telah membuat berkas cadangan manual.

---

## 5. Kontak Pengembang
Jika Anda memiliki pertanyaan mengenai kebijakan privasi ini atau ingin menyampaikan masukan:
- **Pengembang**: Adit Hardiansyah ([@Wilhelm-art](https://github.com/Wilhelm-art))
- **Email**: `adithardiansyah091@gmail.com`
- **Lokasi**: Bandung, Jawa Barat, Indonesia
