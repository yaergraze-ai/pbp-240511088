# Analisis Komparatif Platform Web, Desktop, dan Mobile

**Nama:** Kana Nurhana  
**NIM:** 240511088  
**Kelas:** TI24D

## Tabel Perbandingan

| Aspek | Web | Desktop | Mobile |
|---|---|---|---|
| Bahasa utama | HTML, CSS, JavaScript; sisi server dapat memakai bahasa lain. | C#, Java, C++, atau JavaScript, bergantung pada teknologi. | Android: Kotlin/Java; iOS: Swift. |
| Arsitektur | Browser sebagai client, server menangani permintaan HTTP/API. | Berjalan di OS; proses dan integrasi bergantung pada framework. | Memakai komponen dan siklus hidup OS; dapat memakai backend. |
| Cara distribusi | Deploy ke server, diakses melalui URL. | Installer, paket aplikasi, atau toko aplikasi desktop. | Android APK/AAB; iOS melalui kanal distribusi platform. |
| Keunggulan | Akses lewat browser; pembaruan server bisa terpusat. | Memanfaatkan fitur lokal dan layanan OS. | Portabel; dapat memakai fitur/sensor perangkat. |
| Keterbatasan | Fitur perangkat dibatasi izin browser; sebagian layanan memerlukan internet. | Kompatibilitas dan distribusi perlu disesuaikan dengan OS. | Variasi perangkat, layar, dan sumber daya. |
| Contoh aplikasi | Wikipedia versi browser; Google Docs web. | Visual Studio Code; Notepad Windows. | Google Maps Android/iOS; aplikasi kamera. |

## Pembahasan

Web menggunakan browser sebagai client yang meminta halaman dan data kepada server [1]. Aplikasi Desktop dapat menerapkan arsitektur yang berbeda-beda. Sebagai contoh, Electron memiliki main process dan renderer process [2]. Android mengenal komponen seperti Activity dan Service [3], sedangkan Swift digunakan untuk pengembangan dalam ekosistem Apple [4].

## Daftar Referensi

[1] MDN Web Docs. *How the web works*. Diakses 24 Oktober 2026. https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Web_standards/How_the_web_works

[2] Electron. *Process Model*. Diakses 24 Oktober 2026. https://www.electronjs.org/docs/latest/tutorial/process-model

[3] Android Developers. *Application fundamentals*. Diakses 24 Oktober 2026. https://developer.android.com/guide/components/fundamentals

[4] Apple Developer. *Swift*. Diakses 24 Oktober 2026. https://developer.apple.com/documentation/swift
