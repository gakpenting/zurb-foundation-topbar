

## Instalasi

Untuk menggunakan template ini, komputer Anda membutuhkan:

- [NodeJS] (https://nodejs.org/en/) (Versi 6 atau lebih tinggi disarankan, diuji dengan 6.11.4 dan 8.12.0)
- [Git] (https://git-scm.com/)

Template ini dapat diinstal dengan Foundation CLI, atau diunduh dan diatur secara manual.

### Menggunakan CLI

Instal Foundation CLI dengan perintah ini:

`` pesta
npm install foundation-cli --global
``

Gunakan perintah ini untuk menyiapkan proyek Foundation for Sites kosong dengan templat ini:

`` pesta
yayasan baru - situs bingkai --template zurb
``

CLI akan meminta Anda untuk memberi nama pada proyek Anda. Template akan diunduh ke dalam folder dengan nama ini.

Sekarang `cd` ke nama proyek Anda dan untuk memulai proyek Anda berjalan

`` pesta
jam yayasan
``

### Penyiapan Manual

Untuk mengatur template secara manual, unduh dulu dengan Git:

`` pesta
git clone https://github.com/zurb/foundation-zurb-template projectname
``

Kemudian buka folder di baris perintah Anda, dan instal dependensi yang diperlukan:

`` pesta
cd nama proyek
benang
``

Terakhir, jalankan `benang start` untuk menjalankan Gulp. Situs Anda yang sudah selesai akan dibuat dalam folder bernama `dist`, dapat dilihat di URL ini:

``
http: // localhost: 8000
``

Untuk membuat aset terkompresi dan siap produksi, jalankan `yarn run build`.
