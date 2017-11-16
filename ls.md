## Pengertian

ls adalah sebuah commad dalam linux yang digunakan untuk melihat list / isi dari sebuah folder. Dalam penggunaannya jika ls tidak diikuti dengan option atau argument maka secara otomais ls hanya akan menampilkan list dari directory yang sekarang. Jika kita menggunakan ls dan memberikan sebuah argument yang biasanya adalah sebuah path maka ls akan menampilkan list dari path tersebut, jika option di berikan dalam ls biasanya itu hanya akan mempengaruhi bagaimana hasil output dari list tersebut.

## Tips
Commad | Description
--- | ---
**ls path1 path2** | akan menampilkan isi dari kedua path tersebut

## Often used Options
Option | Long Option | Description
--- | --- | ---
**-a** | **--all** | menampilkan seluruh folder yang ada temasuk hidden folder, back folder dan current folder
**-A** | **--almost-all** | menampilakn seluruh folder yang ada tetapi tidak termasuk back folder dan current folder
**-h** | **--human-readable** | manampilkan penulisan list yang mudah di baca oleh manusia (default in ubuntu)
**-l** | | menampilkan list dengan format lengkap
**-r** | **--reverse** | menampilkan list dengan urutan terbalik (descending)
**-S** | | menampilkan berdasarkan ukuran file
**-t** | | menampilkan berdasarkan waktu modifikasi

**Example**

Commad | Meanig
--- | ---
**ls** | melihat seluruh list file dan directory dari directory sekarang
**ls -a** | melihat seluruh list file dan directory termasuk yang terhidden
**ls /** | melihat seluruh list file dan directory dari directory root ( / )
**ls /bin ./** | melihat seluruh list file dan directory dari directory /bin dan directory sekarang
**ls -a /usr /bin ./** | melihat seluruh list file dan directory termasuk yang terhidden dari directory /bin, directory sekarang dan directory /usr