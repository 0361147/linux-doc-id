## Pengertian

Dalam penggunaannya mv memiliki dua fungsi yaitu untuk memindahkan file / directory dan untuk rename file / directory. Kedua hal tersebut tergantung dari bagaimana mv tersebut di gunakan. Ketika mv di jalankan, ternyata file dengan nama tersebut sudah ada maka secara otomatis akan di overwrite. Untuk penggunaan wildcard sama seperti commad cp.

**Options**

Option | Long Option | Meaning
--- | --- | ---
**-i** | --interactive | akan memunculkan pilihan untuk melakukan overwriting, jika tidak isi secara otomatis akan di overwrite
**-u** | --update | hanya akan memindahkan file yang lebih baru dari file sebelumnya atau file yang belum ada
**-v** | --verbose | menulis seluruh proses yang di lakukan ketika copy di jalankan
**-n** | --no-clobber | tidak akan melakukan overwrite


**Example**

Commad | Meaning
--- | ---
**mv file1 file2** | memindahkan file1 menjadi file2, jika file 2 ada maka akan di overwrite, jika tidak file1 hanya akan di rename menjadi file2
**mv -i file1 file2** | akan memunculkan pilihan jika akan melakukan overwrite
**mv file1 file2 dir1** | memindahkan file1 dan file2 kedalam dir1
**mv dir1 dir2** | memindahkan directory1 ke directory2 jika directory2 telah ada, jika tidak maka directory1 akan di rename menjadi directory2