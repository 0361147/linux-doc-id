## Pengertian

ln adalah commad yang digunakan untuk membuat link baik hardlinks atau softlinks. Dalam penggunaannya ln secara default akan membuat sebuah hardlinks, sedangkan untuk membuat softlinks kita harus menambahkan sebuah options.

**Often used Options**

Commad | Long Commad | Meaning
--- | --- | ---
**-s** | --symbolic | digunakan untuk membuat softlink

**Example**

Commad | Meaning
--- | ---
**ln file1 file2** | membuat sebuah hardlink dari file1 dengan nama file2
**ln -s fil1 file2e** | membuat sebuah softlink dari file1 dengan nama file2e
**ln file1 ~/file1-link** | membuat hardlink dari file1 dengan lokasi di home folder dengan nama file1-link
**ln -s file1 ~/file1-link** | membuat softlink dari file1 dengan lokasi di home folder dengan nama file1-link
**ln -s dir1 dir2-link** | membuat softlink dari directory dir1 dengan nama dir2-link

**Tips**

- Dalam desktop environment gnome kita dapat membuat softlink dengan melakukan ctrl + shift lalu drag file tersebut maka secara otomatis softlink akan di buat.