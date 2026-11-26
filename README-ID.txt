CARIYA.ID ANDROID WEB APP

Proyek Android sederhana yang membungkus https://app.cariya.id/home.html
sebagai aplikasi Android (WebView).

CARA BUILD APK:
1. Ekstrak ZIP ini.
2. Upload seluruh isi folder ke repository GitHub baru.
3. Buka tab Actions di repository.
4. Jalankan workflow "Build Cariya Android APK" melalui tombol Run workflow.
5. Setelah selesai, buka hasil workflow dan unduh artifact "Cariya-Android-APK".
6. Ekstrak artifact; file app-debug.apk adalah APK uji coba.

CATATAN:
- Ini adalah APK debug untuk pengujian, belum APK release bertanda tangan untuk distribusi publik.
- Android dapat meminta izin "Install unknown apps" saat APK dipasang dari browser/file manager.
- Aplikasi memerlukan internet dan memuat website app.cariya.id.
- Pastikan website dan halaman /home.html sudah aktif serta HTTPS valid.
- Jika ingin rilis publik, perlu membuat release signing key/keystore dan konfigurasi signing yang aman.
