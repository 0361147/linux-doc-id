## Pengertian

Uniq di gunakan untuk menfilter kalimat kalimat yang sama dan hanya akan menampilkannya 1x. Dalam penggunannya jika tidak di berikan input maka secara otomatis akan menunggu dari keyboard, hanya saja ketika kita menekan "Enter" maka akan secara otomatis di check oleh uniq. Jika apa yang kita inputkan sudah ada maka tidak akan di tampilkan lagi, jika tidak baru di tampilkan.

**Options**
Options | Description
--- | --- 
**-c** | Menampilkan count dari masing masing kalimat
**-d** | Hanya menampilkan kalimat kalimat yang sama

**Example**
Commad | Meaning
--- | ---
**uniq < data.txt** | Memfilter kalimat yang sama dari data.txt dan menampilkannya 1x
**ls /bin /usr/bin \| uniq** | Memfilter output yang sama dari ls /bin dan /usr/din dan menampilkannya 1x