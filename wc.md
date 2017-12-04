## Pengertian

wc di gunakan untuk menampilkan jumlah line, kata kata dan jumlah byte. Dalam penggunaanya jika kita tidak memberikan input ke dalam wc maka secara otomatis wc akan mengunggu input dari keyboard, untuk melihat hasilnya gunakan kombinasi ctrl-d untuk memberitau itu adalah akhir dari inputan. Output yang di hasilkan pasti berurutan yaitu jumlah lines, jumlah kata-kata, dan jumlah byte.

**Options**
Option | Meaning
--- | ---
**-c** | Menampilkan jumlah byte
**-m** | Menampilkan jumlah character
**-l** | Menampilkan jumlah newline
**-w** | Menampilkan jumlah kata / word

**Example**
Commad | Meaning
--- | --
**wc < file.txt** | Memberikan input file.txt ke dalam wc
**wc file.txt** | Memberikan input file.txt ke dalam wc
**ls / \| wc** | Memberikan hasil output dari ls / ke dalam wc
