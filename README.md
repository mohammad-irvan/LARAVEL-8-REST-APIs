# LARAVEL 8 REST-APIs
latihan membuat API(Application Programing Interface) sederhana menggunakan laravel 8

## Cara instal laravel 8 REST-APIs
1. git clone https://github.com/mohammad-irvan/LARAVEL-8-REST-APIs.git / download zip
2. cd lara8-restAPIs
3. composer install
4. cp .env.example .env =>ubah settingan sesuai dengan database anda
5. php artisan key:generate
6. php artisan migrate
7. php artisan serve atau jalankan di localhost anda

## URL
1. menampilkan semua data [http://127.0.0.1:8000/api/transaction]
2. menampilkan satu data dengan memanggil id [http://127.0.0.1:8000/api/transaction/1]
3. mengubah/update data [http://127.0.0.1:8000/api/transaction/1]
4. menambah/menginput data baru [http://127.0.0.1:8000/api/transaction]
5. hapus/delete data [http://127.0.0.1:8000/api/transaction/1]
 *	catatan: angka 1 =>id 

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
