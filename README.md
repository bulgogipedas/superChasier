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
![Flowchart](https://github.com/bulgogipedas/superChasier/blob/main/assets/flowchart.png)

## 3. PENJELASAN CODE
   ### a. __init__()
   ### Merupakan fungsi inisialisasi untuk class Transaction.
![Init](https://github.com/bulgogipedas/superChasier/blob/main/assets/1%20fungsi.png)
   
   ### b. add_item
   ### Merupakan fungsi untuk menambahkan detail item, yang terdiri dari:
   #### item_name = Nama Barang
   #### item_qyt = Jumlah Barang
   #### item_price = Harga Barang
![Add_item] (https://github.com/bulgogipedas/superChasier/blob/main/assets/2%20add%20item.png)

   
   ### c. update_item
   ### Merupakan fungsi untuk mengupdate/ mengubah detail item yang diinputkan.
![update_item](https://github.com/bulgogipedas/superChasier/blob/main/assets/3%20update%20item.png)

   ### d. show_order
   ### Merupakan fungsi untuk menampilkan daftar pesanan yang sudah diinputkan.
![show_order](https://github.com/bulgogipedas/superChasier/blob/main/assets/4%20show%20order.png)
   
   ### e. delete_item
   ### Merupakan fungsi untuk menghapus salah satu item/ barang yang sudah diinput.
![delete_item](https://github.com/bulgogipedas/superChasier/blob/main/assets/5%20delete%20item.png)
   
   ### f. reset_transaction
   ### Merupakan fungsi untuk menghapus semua item/barang yang telah diinputkan.
![reset](https://github.com/bulgogipedas/superChasier/blob/main/assets/6%20reset.png)
   
   ### g. check_order
   ### Merupakan fungsi untuk untuk memeriksa apakah detail item/barang yang diinputkan sudah lengkap dan benar.
![checkOrder](https://github.com/bulgogipedas/superChasier/blob/main/assets/7%20check.png)
   
   ### h. total_price
   ### Merupakan fungsi untuk menghitung total harga yang harus dibayar oleh customer. Setelah dilakukan penghitungan total harga awal (sebelum diskon), terlebih dahulu akan ditentukan apakah customer mendapatkan diskon. Jika mendapat diskon berapa diskon yang didapatkan, dan setelah itu dilakukan perhitungan total harga awal dikurangi diskon, Lalu hasil akhirnya didapatkan harga total setelah diskon
![total](https://github.com/bulgogipedas/superChasier/blob/main/assets/8%20total.png)
![diskon](https://github.com/bulgogipedas/superChasier/blob/main/assets/9%20diskon.png)

## 4. HASIL TEST CASE

### TEST CASE 1
![tc1](https://github.com/bulgogipedas/superChasier/blob/main/assets/test-case%201.png)
### TEST CASE 2
![tc2](https://github.com/bulgogipedas/superChasier/blob/main/assets/test-case%202.png)
### TEST CASE 3
![tc3](https://github.com/bulgogipedas/superChasier/blob/main/assets/test-case%203.png)
### MENAMBAHKAN KEMBALI ITEM PESANAN
![addItem](https://github.com/bulgogipedas/superChasier/blob/main/assets/tambah-kembali%204.png)
### MENGUPDATE PESANAN
![updatePesan](https://github.com/bulgogipedas/superChasier/blob/main/assets/update.png)
### TEST CASE 4
![tc4](https://github.com/bulgogipedas/superChasier/blob/main/assets/test-case-4.png)

## 5. FUTURE WORK
    Mengembangkan function untuk tebus mura, customer dapat keuntungan untuk dapat membeli barang-bareng tertentu dengan harga murah
