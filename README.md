# Final-Project-QA-API
Final project API

Pengujian yang dilakukan:
1. TEST CASE AUTH GET TOKEN
Tes case dengan melakukan pengujian untuk melakukan post data untuk mendapatkan token
Result: test case berhasil dijalankan dengan baik dan token didapatkan

2. TEST CASE GET BOOKING
Tes case dengan melakukan get data yang disimpan di global variable yang di chaining request nantinya ke dalam method put dengan menggunakan global variable
Result: test case berhasil dijalankan dengan baik dan ID disimpan dalam global variable
NOTE: JIKA ERROR GLOBAL VARIABLE IDBOOKINGNYA DAPAT DIUBAH KARENA IDBOOKING SANGAT CEPAT BERUBAH DAN TERHAPUS

3. TEST CASE POST BOOKING
Tes case dengan melakukan post data untuk menambahkan data baru pada API yang telah disimpan
Result: test case berhasil dijalankan dengan baik dan data baru dapat ditambahkan pada API

3. TEST CASE POST BOOKING
Tes case dengan melakukan PUT data berdasarkan ID yang didapatkan pada TEST CASE GET BOOKING dan API yang di CHAINING REQUEST melalui TEST CASE AUTH GET TOKEN
Result: test case berhasil dijalankan dengan baik dan data dapat diubah sesuai body yang dikirimkan
NOTE: JIKA ERROR GLOBAL VARIABLE IDBOOKINGNYA DAPAT DIUBAH KARENA IDBOOKING SANGAT CEPAT BERUBAH DAN TERHAPUS