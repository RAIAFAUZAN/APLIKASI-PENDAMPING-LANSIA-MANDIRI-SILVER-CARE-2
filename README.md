# Product Requirements Document (PRD)

## Aplikasi Pendamping Lansia Mandiri (Silver-Care)

## 1. Ringkasan Produk

Silver-Care adalah aplikasi berbasis **Laravel** yang membantu lansia
hidup lebih mandiri, aman, dan sehat, sekaligus memudahkan keluarga
serta caregiver dalam melakukan pemantauan dan perawatan.

## 2. Tujuan

-   Meningkatkan kualitas hidup lansia.
-   Mendukung kemandirian lansia.
-   Mempermudah komunikasi antara lansia, keluarga, caregiver, dan
    admin.
-   Menyediakan pemantauan kesehatan dan aktivitas secara terpusat.

## 3. Target Pengguna

### Lansia

-   Melihat jadwal obat.
-   Tombol darurat (SOS).
-   Pengingat aktivitas.

### Keluarga / Pendamping

-   Memantau kondisi lansia.
-   Menerima notifikasi.
-   Melihat riwayat aktivitas.

### Caregiver Formal

Profesi: - Nurse - Doctor - Care Worker - Home Care Nurse - Caregiver

Fitur: - Melihat pasien. - Update kondisi kesehatan. - Catatan
kunjungan.

### Admin

-   Verifikasi akun.
-   Kelola pengguna.
-   Kelola laporan.

## 4. User Flow

``` text
User
 └── Verifikasi User
      ├── Lansia
      └── Keluarga/Pendamping

Caregiver Formal
 └── Verifikasi Caregiver
      ├── Nurse
      ├── Doctor
      ├── Care Worker
      ├── Home Care Nurse
      └── Caregiver

Admin
 └── Verifikasi Admin
      └── Dashboard Admin
```

## 5. Functional Requirements

### Authentication

-   Registrasi
-   Login
-   Verifikasi akun
-   Reset password

### Lansia

-   Profil
-   Jadwal obat
-   Pengingat aktivitas
-   Tombol SOS
-   Riwayat kesehatan

### Keluarga

-   Monitoring lansia
-   Notifikasi
-   Riwayat kesehatan
-   Lokasi (opsional)

### Caregiver

-   Daftar pasien
-   Catatan pemeriksaan
-   Jadwal kunjungan
-   Update status pasien

### Admin

-   Dashboard
-   Manajemen pengguna
-   Verifikasi akun
-   Laporan

## 6. Non Functional Requirements

-   Framework: Laravel
-   Responsive Web
-   Keamanan autentikasi
-   Role-based access control
-   Audit log
-   Backup database

## 7. MVP

Prioritas: 1. Login & Registrasi 2. Verifikasi User 3. Dashboard
berdasarkan role 4. Jadwal obat 5. SOS 6. Monitoring keluarga 7. Catatan
caregiver 8. Admin panel

## 8. Future Enhancement

-   Integrasi wearable
-   Telemedicine
-   AI Health Assistant
-   Prediksi risiko kesehatan
-   Video Call
