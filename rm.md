## Pengertian

Digunakan untuk menghapus directory dan file. Dalam penggunaannya rm hanya dapat menghapus file, tetapi dalam ada sebuah option yang membuat rm memungkinkan untuk menghapus sebuah directory. Jadi jika tidak di beri option tersebut rm tidak dapat menghapus directory kosong maupun yang berisi file.

**Often used Option**

Option | Long Option | Meaning
--- | --- | ---
**-i** | --interactive | menampilkan pilihan setiap akan menghapus file, jika tidak di isi secara default akan langsung menghapus
**-r** | --recursive | menghapus directory beserta seluruh isinya
**-d** | --dir | menghapus directory kosong, jika ada isinya akan gagal
**-f** | --force | menghapus file tanpa menampilkan pilihan
**-v** | --verbose | menampilkan log segala sesuatu yang di hapus

**Warning**

Perlu diingat bahwa ketika menggunakan commad rm maka seluruh file yang telah terhapus tidak dapat lagi di kembalikan seperti semua. Hal ini sebabkan oleh linux tidak memiliki commad untuk mengembalikan file yang telah terhapus.

**Example**

Commad | Meaning
--- | ---
**rm file1** | menghapus file1
**rm *.txt** | menghapus seluruh .txt file
**rm file1 file2** | menghapus file1 dan file2
**rm -d dir1** | menghapus dir1 dimana dir1 haruslah sebuah directory kosong
**rm -r dir1** | menghapus dir1 dan seluruh isinya
**rm -rf dir1 dir2** | menghapus dir1 dir2 dan seluruh isinya tanpa menampilkan peringatan