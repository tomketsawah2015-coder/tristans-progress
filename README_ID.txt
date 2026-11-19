TRISTAN'S PROGRESS — proyek Android APK

Proyek ini membungkus jurnal web menjadi aplikasi Android sederhana menggunakan WebView.
Data jurnal disimpan oleh browser WebView di perangkat melalui localStorage.

CARA BUILD DARI HP:
1. Ekstrak ZIP ini di HP.
2. Buat akun / masuk ke GitHub melalui browser.
3. Buat repository baru, misalnya: tristans-progress (boleh Public atau Private).
4. Unggah seluruh ISI folder proyek ini ke repository, pertahankan struktur folder.
   Pastikan folder .github/workflows ikut terunggah.
5. Buka tab Actions di repository. Jika diminta, izinkan workflows.
6. Pilih workflow "Build Tristan's Progress APK", tekan Run workflow.
   (Push ke branch main juga otomatis menjalankan workflow.)
7. Tunggu sampai workflow selesai dengan tanda hijau.
8. Buka hasil run tersebut, cari bagian Artifacts, unduh
   "Tristans-Progress-debug-apk".
9. Ekstrak ZIP artifact, lalu buka app-debug.apk untuk memasang.

CATATAN:
- Ini APK debug untuk uji coba pribadi, bukan rilis Play Store.
- Simpan ZIP sumber ini agar proyek dapat dibangun ulang.
- Jurnal disimpan lokal di aplikasi. Jangan hapus data aplikasi jika ingin
  mempertahankan jurnal; gunakan fitur ekspor JSON untuk cadangan.
- Jangan bagikan kredensial akun GitHub atau kata sandi kepada siapa pun.
