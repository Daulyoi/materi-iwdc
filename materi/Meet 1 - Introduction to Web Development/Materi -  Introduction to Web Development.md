# Pengenalan Web Development (FE vs BE)
- Web Development = Proses membuat aplikasi berbasis web
- Terbagi menjadi 2 (Frontend, Backend):
	- Frontend :
		- Berurusan dengan bagian yang dilihat oleh user.
		- Memungkinkan user untuk berinteraksi dengan aplikasi. 
	- Backend : 
		- Berurusan dengan bagian yang tidak dilihat oleh user. 
		- Mengolah data yang dikirim dari/ke aplikasi
- Baca lebih lanjut : https://aws.amazon.com/id/compare/the-difference-between-frontend-and-backend/
# Pengenalan Struktur Dasar Website (HTML, CSS, JS)
- Pada dasarnya, website tersusun atas 3 jenis file, masing-masing dengan fungsinya sendiri. 
	- HTML (HyperText Markup Language)
		- Merupakan "kerangka" dari sebuah website
		- Digunakan untuk menuliskan struktur 
		- Contoh : Kita mau nampilin teks "Halo", atau "Wello Horld!" di halaman web.
	- CSS
		- Digunakan untuk styling 
		- Contoh : Kita mau teks "Halo" untuk berwarna biru, bold, berukuran 34px, dan pakai font comic sans
		- Contoh lagi : Kita mau bikin tombol "login" dengan warna tertentu, ukuran tertentu, dan tombol nya melingkar
	- JS
		- Digunakan untuk menambahkan interaktivitas 
		- Contoh : Misal ada tombol, kita mau bikin supaya saat tombol itu di klik, bakal muncul teks baru yg bertuliskan "Aduh!"
- Baca lebih lanjut : https://www.geeksforgeeks.org/javascript/learn-web-development-basics-with-html-css-and-javascript/
# Tools yang digunakan
- Visual Studio Code 
	- Kita ngoding disini
	- Download disini -> https://code.visualstudio.com/download
- Developer Tools di Browser (klik kanan -> inspect) 
- Github 
	- Untuk file sharing, version control
	- Bikin akun disini -> https://github.com/

# Membuat halaman HTML pertama - "Hello World!"
> Pastikan kalian sudah download vscode
## 1. Buat folder baru untuk menyimpan file kita
Biasakan untuk meng-organisir project kalian ke folder nya tersendiri supaya rapih. 

Misalnya disini, kita bikin folder namanya `first-website` di `/Documents/Ngoding/`. Jangan lupa untuk pastikan nama folder/file kalian mengikuti konvensi penamaan file (Baca disini -> https://josephpinder.com/blog/file-naming-conventions-for-web-developers/)
![[bikin-folder-baru.png]]

## 2. Buka folder tadi di vscode
- Buka vscode
- Di pojok kiri atas, klik `File` -> `Open Folder...` ![[vscode-open-folder.png]]
- Navigasi ke folder yang tadi dibuat 
- Kalau berhasil, harusnya tertulis nama folder kalian, kayak di foto ini ![[vscode-in-project-folder.png]]

## Bikin file index.html
- Klik tombol ini untuk bikin sebuah file, lalu kasih nama `index.html` ![[vscode-buttons.png]]
- Kalau udah jadi, harusnya muncul kayak begini ![[vscode-index-html-created.png]]
## Mulai ngoding
- Di editor nya, ketik `!` lalu tekan enter di keyboard. Ini akan membuat struktur dasar html. ![[html-scaffold.png]]
- Kalau sudah, seharusnya menjadi seperti ini ![[html-scaffold-result.png]]
- Jangan lupa untuk save file kalian setiap kali membuat perubahan 
	- Tekan `CTRL+S` di keyboard, atau klik `File` -> `Save`
	- Kalau masih ada buletan di sebelah nama file kalian, berarti file nya belum ke save
- Ketik nama kalian di dalam `tag` body
	- "Struktur" HTML di definisikan dengan `tag`, contohnya yang kalian bisa lihat adalah tag `<body></body>`
	- Kalau kalian sudah belajar alpro, ini mirip kayak kurung kurawal `{}`
	- Untuk menuslikan teks, kita bisa gunakan tag `<p></p>` yaitu tag paragraph. 
	- Berikut contoh hasilnya ![[html-name-p.png]]
	- Sekali lagi, jangan lupa untuk save file kalian

## Melihat website kita
- Ada beberapa cara untuk melihat hasil yang telah kita buat
- Buka langsung di browser
	- Cara yang paling mudah adalah dengan double click `index.html`, ini akan membuka file html kita di browser
	- Kekurangan dari metode ini adalah jika kita mengubah isi dari index.html, yang di browser tidak ikut berubah. Melainkan harus dibuka lagi `index.html` yang udah diubah isinya itu
- Menggunakan extension di vscode bernama `Live Server`
	- Untuk metode ini, kita perlu install extension di vscode. Navigasi sidebar supaya berada di tab extensions, lalu search `Live Server`, lalu klik install ![[vscode-install-live-server.png]]
	- Kalau udah, kembali ke file `index.html`, lalu tekan tombol `Go Live` di pojok kanan bawah ![[go-live-button.png]]
	- Kalau sudah, akan muncul pesan seperti ini ![[live-server-started.png]]
	- Website kita juga akan otomatis terbuka di browser kita ![[live-server-website.png]]
	- Jika ingin menghentikan live server, tinggal klik lagi tombol `Go Live` tadi

## Menuliskan perkenalan di website kita
- Mari kita perkenalkan diri kita lebih lanjut
- Kita akan menggunakan tag heading yaitu `<h1></h1>`
- Tag ini berfungsi sebagai Heading, misalnya judul dari sebuah artikel
- Coba tuliskan "Halo teman teman!" menggunakan tag `h1`
- Kemudian lanjutkan dengan menuliskan kalimat perkenalan dengan tag `p`
- Kira kira perlu kode seperti apa untuk menampilkan ini? ![[html-finished.png]]