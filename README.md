## 🚀 Project Testing Automation Website Saucedemo With Selenium

kali ini saya buat project untuk website saucedemo dengan selenium, javascript, dan mocha sebagai framework nya. pengujian pada website ini untuk memastikan apakah semua fitur yang ada pada website ini berjalan sesuai standar yang ditentukan atau tidak.

## 🎯 Scope Pengujian
Project ini mencakup automated test untuk beberapa fitur utama di Parabank, antara lain:
- **Login** – Autentikasi pengguna dengan beberapa credential memastikan tidak adanya kegagalan dalam proses login dengan credential yang valid
- **Sort** – Sorting product  
- **Checkout** – Memasukan product ke keranjang dan melakukan proses checkout. 

## 💻 Cara Menjalankan Project ini
- Clone Project ini
- jalankan npm install
- jika ingin menjalankan spesifik testcase saja jalankan: ``npm run tc01_login`` misalnya pada testcase login
- jika ingin menjalankan seluruh testcase langsung jalankan: ``npm run tc_all``
- kemudian setelah selesai dijalakan, report akan otomatis tergenerate dan dapat dilihat melalui mochawesome-report.html nya
- report juga dapat dilihat berupa screnshot pada folder ss_screnshot
