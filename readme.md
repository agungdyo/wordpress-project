WordPress

Semantic Personal Publishing Platform

First Things First

Welcome. WordPress is a very special project. Every developer and contributor adds something unique, and together they create something meaningful and continuously improved.

— Matt Mullenweg

Installation: Famous 5-Minute Install
Unzip package ke direktori kosong lalu upload semua file.

Buka:

wp-admin/install.php

di browser.

Jika gagal:

Edit wp-config-sample.php
Isi database credentials
Rename jadi wp-config.php
Upload ulang
Installer akan membuat tabel database.
Jika error → cek ulang wp-config.php
Jika masih gagal → gunakan forum support
Catatan:
Default username: admin
Simpan password yang di-generate

Login:

wp-login.php
Updating
Automatic Update

Buka:

wp-admin/update-core.php
Ikuti instruksi
Manual Update
Backup file penting (misalnya index.php)
Hapus file lama (kecuali yang dimodifikasi)
Upload file baru

Jalankan:

/wp-admin/upgrade.php
Migrating from Other Systems

WordPress bisa import dari berbagai platform.

Langkah:

Install WordPress

Gunakan:

wp-admin/import.php

Referensi:
https://developer.wordpress.org/advanced-administration/wordpress/import/

System Requirements
PHP ≥ 7.2.24
MySQL ≥ 5.5.5
Recommended
PHP ≥ 8.3
MySQL ≥ 8.0 atau MariaDB ≥ 10.6
Apache mod_rewrite
HTTPS support
Online Resources
Documentation: https://wordpress.org/documentation/
Blog: https://wordpress.org/news/
Community: https://wordpress.org/support/forums/
IRC: https://web.libera.chat/#wordpress
Final Notes
Gunakan forum untuk bug / ide
Gunakan Plugin API untuk extend (jangan modifikasi core)

Plugin docs:
https://developer.wordpress.org/plugins/

Share the Love

WordPress berkembang karena komunitas. Jika membantu, share ke orang lain atau kontribusi ke project.

License

WordPress menggunakan lisensi:

GPL v2 atau lebih baru

Lihat:

license.txt
