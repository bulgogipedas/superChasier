# superChasier
Final Project Python Fundamental PacmannAi

### Sistem kasir self-service di supermarket dengan menggunakan bahasa pemrograman Python yang memungkinkan customer yang tidak berada di kota tersebut dapat melakukan pembelian barang.

## 1. REQUIREMENTS/ OBJECTIVES
   #### Membuat sistem kasir self service dengan feature sebagai berikut:
   #### a. Membuat proses untuk memasukkan ID Transaksi
   #### b. Membuat proses untuk menambahkan barang yang ini dibeli dan detail jumlah dan harganya
   #### c. Membuat proses untuk mengupdate detail barang yang sudah diinputkan sebelumnya jika ada kesalahan input
   #### d. Membuat proses untuk menghapus salah satu pesanan yang telah diinputkan  
   #### e. Membuat proses untuk menghapus seluruh transaksi yang telah diinputkan
   #### f. Membuat proses untuk memeriksa apakah seluruh data yang diinput sudah benar dan lengkap
   #### g. Membuat proses untuk menghitung total belanja yang harus dibayarkan dan diskon yang didapatkan (jika dapat).
 
## 2. FLOWCHART
![Flowchart](https://user-images.githubusercontent.com/123846578/216514621-2c134ee1-4961-4a88-a5c2-5bca5df20e91.jpeg)

## 3. PENJELASAN CODE
   ### a. __init__()
   ### Merupakan fungsi inisialisasi untuk class Transaction.

   
   ### b. add_item
   ### Merupakan fungsi untuk menambahkan detail item, yang terdiri dari:
   #### item_name = Nama Barang
   #### item_qyt = Jumlah Barang
   #### item_price = Harga Barang

   
   ### c. update_item
   ### Merupakan fungsi untuk mengupdate/ mengubah detail item yang diinputkan.
   

   ### d. show_order
   ### Merupakan fungsi untuk menampilkan daftar pesanan yang sudah diinputkan.
   
   
   ### e. delete_item
   ### Merupakan fungsi untuk menghapus salah satu item/ barang yang sudah diinput.

   
   ### f. reset_transaction
   ### Merupakan fungsi untuk menghapus semua item/barang yang telah diinputkan.
   
   
   ### g. check_order
   ### Merupakan fungsi untuk untuk memeriksa apakah detail item/barang yang diinputkan sudah lengkap dan benar.

   
   ### h. total_price
   ### Merupakan fungsi untuk menghitung total harga yang harus dibayar oleh customer. Setelah dilakukan penghitungan total harga awal (sebelum diskon), terlebih dahulu akan ditentukan apakah customer mendapatkan diskon. Jika mendapat diskon berapa diskon yang didapatkan, dan setelah itu dilakukan perhitungan total harga awal dikurangi diskon, Lalu hasil akhirnya didapatkan harga total setelah diskon
   

## 4. HASIL TEST CASE

### TEST CASE 1

### TEST CASE 2

### TEST CASE 3

### MENAMBAHKAN KEMBALI ITEM PESANAN

### MENGUPDATE PESANAN

### MEMERIKSA INPUT PESANAN


### TEST CASE 4


## 5. FUTURE WORK
    Mengembangkan function untuk tebus mura, customer dapat keuntungan untuk dapat membeli barang-bareng tertentu dengan harga murah
