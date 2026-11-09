RAGANTARA STUDIO - PROYEK ANDROID OFFLINE

Status:
- Ini adalah proyek sumber Android Studio, bukan file APK yang sudah dikompilasi.
- Lingkungan pembuatan saat ini tidak memiliki Android SDK/Gradle, jadi APK tidak dapat dikompilasi dan diuji di sini.
- Setelah proyek dibuka dan dibangun di Android Studio, aplikasi berjalan offline karena HTML dan ikon disimpan di dalam APK dan aplikasi tidak meminta izin internet.

Cara membuat APK:
1. Ekstrak ZIP ini.
2. Buka Android Studio.
3. Pilih Open, lalu pilih folder Ragantara_Studio_Android.
4. Tunggu Gradle Sync selesai (internet mungkin diperlukan sekali untuk mengunduh Android Gradle Plugin/SDK).
5. Pilih Build > Build Bundle(s) / APK(s) > Build APK(s).
6. APK debug akan muncul di app/build/outputs/apk/debug/app-debug.apk.

Catatan:
- Aplikasi menggunakan Android WebView lokal; tidak ada izin INTERNET di manifest.
- Riwayat prompt tersimpan di penyimpanan lokal WebView perangkat.
- Jika ikon launcher tidak berubah setelah instalasi ulang, hapus shortcut lama dari layar utama lalu tambahkan kembali.
