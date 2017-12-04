## Pengertian

head di gunakan untuk menampilkan beberapa line awal dari sebuah file / output commad. Secara default akan menampilkan 10 line awal dari file / output commad.

**Options**
Option | Meaning
--- | ---
**-n NUM** | Menampilkan beberapa line awal sesuai dengan nilai dari NUM
**-c NUM** | Menampilkan beberapa line awal berdasarkan jumlah byte yang di berikan, NUM adalah jumlah byte

**Example**
Commad | Meaning
--- | ---
**head -n 5 file.txt** | Menampilkan 5 line awal dari file.txt
**head -c 10 file.txt** | Menampilkan 10 byte awal dari file.txt
**ls /bin \| head -n 5** | Menampilkan 5 line awal dari hasil output ls /bin