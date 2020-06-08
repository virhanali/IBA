# IBA
Investment Bandung Agreement adalah platform untuk membantu individu maupun perusahaan yang ingin berinvestasi di Kota Bandung

Cara install

Untuk melakukan instalasi sistem diharapkan telah menginstal github dan juga telah mengintall composer. Github diperlukan untuk mendownload repository sistem ini sedangkan composer diperlukan untuk mendownload framework Laravel.

Buka cmd dengan menekan tombol WIN+R lalu inputkan cmd dan tekan enter, untuk linux tekan tombol CTRL+ALT+T untuk membuka Terminal.
Lakukan CD (change directory) untuk mengubah alamat folder yang nantinya akan jadi tempat penyimpanan sistem digital library ini.
Jika sudah, ketikan "git clone https://github.com/virhanali/IBA".
Tunggu proses instalasi berakhir, selanjutnya masih didalam terminal atau cmd. Ketikkan composer install tunggu hingga proses instalasi selesai untuk setiap masing - masing perintah.
Jika sudah selesai, maka copy file yang bernama .env.example pastekan di halaman yang sama lalu ubah namanya menjadi .env. Untuk linux hanya perlu mengetikkan perintah cp .env.example .env.
Selanjutnya ketikkan php artisan key:generate.
Jika sukses maka akan muncul tulisan successful generate key bla... bla....
Lalu nyalakan xampp dan buat database namanya laravel, jika sudah ketikkan php artisan migrate .
Jika berhasil ketikkan perintah php artisan serve dan akan muncul response htttp://localhost:8000/.
