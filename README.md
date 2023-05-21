<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel
Alur kerjanya:
Buka VS code :

1. Karna Folder Vendor dihilangkan, Aktifkan Xampp dan database buat dulu 
Buat kembalikan Folder Vendor
Ketik : Composer install

2. copy env.ecample .env 
kita buat enc dan isi database, username dan password yg kita masukkan di Mysql

3. composer update

4. php artisan key:generate

5. php artisan migrate

6. sekarang kita aktifkan jwt
composer require tymon/jwt-auth   <br>  
  isi file Tymon\JWTAuth\Provider\LaravelServiceProvider::class

7. generate secret Token pada file env
php artisan jwt:secret

8. Ketik : php artisan serve --port=8001

9. buka website: hhtp://127.0.0.1:8001

10. Buka postman


![data barang](https://github.com/AlfiNashri-WebDesign/ProjectTiga/assets/23645665/fa5973fe-5e0a-453e-9bbf-ca87728c0d1f)
![input barang](https://github.com/AlfiNashri-WebDesign/ProjectTiga/assets/23645665/3dc7c56b-5369-4148-8c10-8a5bb12b2f78)
