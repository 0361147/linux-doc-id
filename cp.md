## Pengertian

Digunakan untuk mengcopy file atau folder. Dalam penggunaannya kita bisa menggunakan wildcard untuk memfilter file yang akan di copy. Selain itu dalam 1x commad berjalan juga bisa di gunakan untuk mengcopy beberapa file sekaligus.

**Often used Options**

Option | Long Option | Meaning
--- | --- | ---
**-a** | --archive | mengcopy files atau directory dengan seluruh atribut yang dimiliki oleh file atau directory tersebut
**-i** | --interactive | akan memunculkan pilihan untuk melakukan overwriting, jika tidak isi secara otomatis akan di overwrite
**-r** | --recursive | akan mengcopy seluruh isi dari directory
**-u** | --update | hanya akan mengcopy file yang lebih baru dari file sebelumnya atau file yang belum ada
**-v** | --verbose | menulis seluruh proses yang di lakukan ketika copy di jalankan

**Example**

Commad | Meaning
--- | ---
**cp file1 file2 data** | mengcopy file1 dan file2 kedalam folder data
**cp -r dir1 dir2** | mengcopy dir1 dengan seluruh file didalamnya ke die2
**cp -a dir1/\* dir2** | mengcopy seluruh file yang ada di dalam dir1 ke dir2