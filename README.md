# Article-test

1. Silahkan Downloaf File Zib Article-test
2. setelah download silahkan extrak
3. selanjutnya klik kanan pada Folder Post-article dan klik Git bash
4. buka vs code dan buka folder Post-article
5. pada file .env 
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=post-article
DB_USERNAME=root
DB_PASSWORD=
bisa diperhatikan ada databse dengan nama db post-article, silahkan buat db dengan nama tersebut dengan dbms kesayangan anda
6.kembali ke terminal git bash kita ssebelumnya silakan jalankan " php artisan migrate:fresh --seed " lalu tekan enter
7.terakhir jalankan "php artisan serve " akan muncur url server yang bisa kita jalankan " http://127.0.0.1:8000/ " , silahkan copy dan paste di browser, article sudah bisa dijalankan dan akan muncul halaman dashboard
