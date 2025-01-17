﻿#StudyGroupMobileProgrammingMotionLab

 Firebase adalah platform Backend-as-a-Service (BaaS) yang memiliki berbagai fitur diantaranya adalah:

 -Authentication

 Firebase Authentication adalah layanan autentikasi dari Firebase yang mempermudah pengelolaan login pengguna dan mendukung beberapa metode seperti Email/Password, menggunakan provider(Google, Facebook, dll.), nomor telpon, dll. Kegunaan nya dalam pengembangan aplikasi adalah dapat menghemat waktu karena tidak perlu membangun backend autentikasi sendiri dan mudah diintegrasikan dengan fitur lain seperti Realtime Database atau Firestore.

 -Firestore

 Firestore adalah database cloud NoSQL yang dirancang untuk menyiman, menyinkronkan, dan mengelola data aplikasi dengan fleksibilitas tinggi. Beberapa fitur yang terdapat di Firestore diantaranya adalah Collection & Document, mendukung query kompleks seperti filter, sorting, limit dan indexing, sikronisasi Real-Time, serta keamanan dan Skalabilitas. Kegunaan Firestore ini adalah karena dapat mendukung struktur data yang lebih kompleks dibandingkan dengan Firebase Realtime Database

 -Cloud Storage

 Firebase Cloud Storage adalah layanan penyimpanan file besar seperti gambar, video, audio, atau dokumen yang juga mampu menangani file dengan berbagai ukuran, mudah dihubungkan dengan fitur lain seperti Firestore atau Realtime Database serta mendukung metadata tambahan seperti ukuran file, jenis file, atau waktu unggah. Kegunaan dari Cloud Storage ini adalah penghematan waktu dan biaya dalam pembangunan infrastruktur penyimpanan file, ideal untuk aplikasi yang membutuhkan pengelolaan media, serta telah dirancang untuk menyimpan file dengan aman, efisien, dan mudah diakses.

 -Realtime Database
 
 Firebase Realtime Database adalah database NoSQL tanpa server yang menyimpan dan menyinkronkan data JSON antara para pengguna dalam hampir real-time, online atau offline, dengan user-based security yang kuat. Kegunaan dari Realtime Database ini adalah data yang disimpan sebagai objek JSON, data tersinkronisasi antar devices dalam realtime, serta dukungan offline untuk aplikasi mobile dan web.

 -Firebase Extensions
 
 Firebase extensions adalah berbagai bundle kode open source dan pre-packaged yang dapat membantu menambahkan fungsionalitas ke aplikasi. Kegunaannya dalam pengembangan aplikasi adalah membuat tugas development umum lebih simpel, dapat diintegrasi lebih mudah dengan layanan Firebase yang lain, dapat diubah, serta diatur dan dipertahankan oleh Firebase.

 -Cloud Functions

 Firebase Cloud Functions dapat membuat dan menjalankan app logic dari sisi server tanpa perlu membuat server sendiri. Beberapa kegunaan utamanya dalam pengembangan aplikasi adalah fungsi event-driven tanpa server, integrasi dengan layanan Firebase dan Google Cloud Platform, menulis fungsi dalam JavaScript, TypeScript, atau bahasa lain, serta scaling otomatis berdasarkan kebutuhan 

 Contoh singkat implementasi dalam pengembangan android ketika autentikasi berupa login Email/Password adalah seperti ini 
 
 ![image](https://github.com/user-attachments/assets/ba59ea04-5dc2-4f13-b216-37e144162c84)

 JIka sudah di setup di firebase dan user di aplikasi telah melakukan registrasi, maka di Console Firebase akan muncul seperti ini

 ![image](https://github.com/user-attachments/assets/ba31f52e-6cee-420f-9c03-e7e492743a16)



 
