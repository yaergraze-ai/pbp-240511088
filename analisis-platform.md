# Analisis Komparatif Platform Web, Desktop, dan Mobile

**Nama:** Kana Nurhana  
**NIM:** 240511088  
**Kelas:** TI24D  
**Mata kuliah:** Pemrograman Berbasis Platform

## Tabel perbandingan

| Aspek | Web | Desktop | Mobile |
|---|---|---|---|
| Bahasa utama | HTML, CSS, JavaScript/TypeScript; backend dapat menggunakan bahasa lain. | C#, Java, C++, atau JavaScript/TypeScript sesuai framework. | Android: Kotlin/Java; iOS: Swift; juga tersedia framework lintas platform. |
| Arsitektur | Browser sebagai client, berkomunikasi dengan server melalui HTTP/API. | Aplikasi terinstal di OS, menjalankan logika lokal dan menggunakan API OS. | Berjalan mengikuti lifecycle Android/iOS, dapat berkomunikasi dengan backend. |
| Cara distribusi | Deploy ke server/hosting, diakses melalui browser dan URL. | Installer/paket aplikasi, situs resmi, atau app store desktop. | Google Play, App Store, atau kanal yang diizinkan platform. |
| Keunggulan | Mudah diakses melalui browser, lintas perangkat, update terpusat. | Integrasi dengan OS dan sumber daya komputer; cocok untuk pekerjaan lokal yang intensif. | Portabel dan memanfaatkan kamera, GPS, sensor, serta notifikasi. |
| Keterbatasan | Dibatasi izin browser; beberapa fungsi membutuhkan koneksi internet. | Variasi OS memengaruhi kompatibilitas, instalasi, dan update. | Variasi perangkat, layar, baterai, serta aturan distribusi. |
| Contoh aplikasi | Wikipedia web, Google Docs web. | Visual Studio Code, Notepad Windows. | Google Maps Android/iOS, aplikasi kamera ponsel. |

## Pembahasan

**Web:** Browser meminta halaman dan data kepada server melalui protokol web. HTML, CSS, dan JavaScript digunakan untuk membangun pengalaman pengguna [1].

**Desktop:** Aplikasi dijalankan pada komputer dan dapat mengakses kapabilitas OS. Arsitektur tergantung teknologi; Electron, misalnya, menggunakan main process dan renderer process [2].

**Mobile:** Aplikasi menyesuaikan komponen dan siklus hidup OS. Android menyediakan komponen aplikasi dan pengembangan dengan Kotlin/Java, sedangkan Apple mendukung Swift [3][4].

Perbandingan ini menjelaskan karakteristik umum. Aplikasi di ketiga platform dapat memakai backend ataupun menyediakan fungsi offline bergantung pada implementasi.

## Referensi

1. MDN Web Docs. *How the web works*. https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Web_standards/How_the_web_works (23 Oktober 2026).
2. Electron. *Process Model*. https://www.electronjs.org/docs/latest/tutorial/process-model (23 Oktober 2026).
3. Android Developers. *Application fundamentals*. https://developer.android.com/guide/components/fundamentals (23 Oktober 2026).
4. Apple Developer. *Swift*. https://developer.apple.com/documentation/swift (23 Oktober 2026).
