## Pengertian

Cat adalah sebuah commad yang di gunakan untuk membaca satu atau lebih file dan mengcopynya ke standar output. Dalam penggunaanya cat sama seperti type dalam DOS. Dalam penggunaanya jika kita tidak memberikan input ke dalam cat maka secara otomatis cat akan mengunggu input dari keyboard, untuk melihat hasilnya gunakan kombinasi ctrl-d untuk memberitau itu adalah akhir dari inputan.

**Example**
Commad | Meaning
--- | ---
**cat > file.txt** | Menerima input dari keyboard dan menuliskannya kedalam file.txt. Untuk mengakhiri kita gunakan ctrl-d
**cat file.txt** | Melihat isi dari file.txt dan menampilkannya ke layar
**cat < file.txt** | Merubah standar input dari cat menjadi dari file.txt bukan lagi dari keyboard
**cat movie.mpeg.0* > movie.mpeg** | Melihat isi seluruh file movie.mpeg.0 dan merubahnya menjadi movie.mpeg