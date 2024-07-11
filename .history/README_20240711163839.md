## MY-PFOLIO
<p><b>
MY-PFOLIO adalah aplikasi website portfolio dengan konten dinamis.
</b></p>

## Instalasi
- download zip <a href="https://github.com/rahmathidayat9/simple-portfolio/archive/master.zip">disini</a> 
- atau clone : git clone https://github.com/rahmathidayat9/simple-portfolio.git

## Setup
- buka direktori project di terminal anda.
- ketikan command : cp .env.example .env (copy paste file .env.example)
- buat database 

Lalu ketik command dibawah ini
- composer install
- php artisan optimize:clear 
- php artisan key:generate (generate app key)
- php artisan migrate (migrasi database)
- php artisan db:seed --class=UserClass (mengisi data table users)

## Login
Email : anggarihi09@gmail.com
Password : password

## Fitur
- Home (Banner Hero,About,Portfolio) 
- Login
- Halaman Dashboard
- Halaman Profile
- Ubah Profile
- Manage User (CRUD)
- Manage Front Header Layout (CRUD)
- Manage Front About Layout (CRUD)
- Manage Skill Layout (CRUD)
- Manage Portfolio (CRUD)
- Manage Footer Layout (CRUD)


## Author
- Angga Bayu Agustian Rihi
