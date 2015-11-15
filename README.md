# codeigniter-id
codeigniter-id adalah platform untuk grup codeigniter indonesia facebook fanpage, boleh dikatakan ini adalah aplikasi untuk management posting dan lain-lain. menyediakan fitur admin untuk pengaturan default website pada umumnya dan posting management juga menyediakan fitur pembuatan static page, sebagai contoh about, us dan lain-lain. memoderator posting sebelum posting di tampilkan, dan pemantauan komentar jika dalam posting terdapat komentar, sedikit banyak meniru stackoverflow.

# Folder Structure
| codeigniter-id/
	| applications/
		| codeigniter-indonesia-admin/
			| [default codeigniter for application]
		| codeigniter-indonesia-website/
			| [default codeigniter for application]
		| .htaccess
	| codeigniter-indonesia-admin/
		| index.php [default codeigniter index.php untuk redirect ke folder codeigniter-indonesia-admin within codeigniter-id/applications/codeigniter-indonesia-admin]
		| .htaccess
	| codeigniter-indonesia-core-system/
		| [default codeigniter core system]
	| codeigniter-indonesia-db/
		| [folder dengan nama folder berupa tanggal perubahan]
			| [untuk menampung file .sql jika ada yang ditambah atau dirubah]
	| codeigniter-indonesia-website/
		| index.php [default codeigniter index.php untuk redirect ke folder codeigniter-indonesia-website within codeigniter-id/applications/codeigniter-indonesia-website]
	| CONTRIBUTORS.txt
	| LICENSE
	| README.md

# Component

- Auth modul [ion_auth : https://github.com/benedmunds/CodeIgniter-Ion-Auth]
	- default login key [admin@admin.com, password]
	
	
# Instalasi
1. clone repository ini.
2. import file codeigniter_indonesia_db-20151006.sql ke database anda
3. untuk mengakses admin page, http://yourdomain/codeigniter-id/codeigniter-indonesia-admin
4. untuk mengakses website page , http://yourdomain/codeigniter-id/codeigniter-indonesia-website

# Development Rules
1. Jangan bermain dengan master, jika ingin memulai development, buatlah branch turunan master, setelah selesai test, merge kembali ke master dan push. 

