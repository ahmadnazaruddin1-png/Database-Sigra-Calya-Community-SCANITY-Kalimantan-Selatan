# SCANITY Kalsel Android v2.0

Aplikasi Android untuk **Sigra Calya Community (SCANITY) Chapter Kalimantan Selatan**.

## Fitur v2.0
- Dashboard dengan jumlah anggota dan anggota aktif.
- Data anggota: ID, nama, panggilan, WhatsApp, kendaraan, nomor polisi, tahun, Korwil, status.
- Foto anggota dari galeri.
- Pencarian anggota.
- Tambah dan edit data anggota melalui Admin.
- Hapus data anggota melalui Admin.
- Kartu anggota digital.
- QR Code berisi data anggota untuk verifikasi/identifikasi.
- Data Korwil: Tatanko, Babam, Banam, Balat.
- Kegiatan & pengumuman yang dapat diedit Admin.
- Backup data JSON dan pemulihan dari file JSON.
- Password Admin dapat diganti.
- Data utama tersimpan lokal di perangkat.

## Login Admin awal
Username: `admin`  
Password awal: `scanity2026`

Segera ganti password setelah instalasi.

## Membuat APK
1. Buka folder `SCANITY-Kalsel-Android` di Android Studio.
2. Pastikan Android SDK 35 dan koneksi internet tersedia untuk mengambil dependency ZXing.
3. Gradle Sync.
4. Pilih **Build > Build APK(s)**.
5. APK debug biasanya berada di `app/build/outputs/apk/debug/app-debug.apk`.

## Catatan pengembangan tahap berikutnya
Versi ini memakai penyimpanan lokal. Untuk dipakai banyak pengurus/perangkat secara bersamaan, tahap berikutnya dapat dihubungkan ke Firebase/Firestore dengan autentikasi, database online, sinkronisasi anggota, role Admin/Korwil, dan verifikasi QR online.
