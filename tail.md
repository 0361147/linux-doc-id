## Pengertian

tail memiliki fungsi yang sama dengan head hanya saja, jika head untuk menampilkan awal dari file maka tail di gunakan untuk menampilkan beberapa line terakhir dari file / output program. Secara default akan menampilkan 10 line terakhir.

**Options**
Option | Meaning
--- | ---
**-n NUM** | Menampilkan beberapa line terakhir sesuai dengan nilai dari NUM
**-c NUM** | Menampilkan beberapa line terakhir berdasarkan jumlah byte yang di berikan, NUM adalah jumlah byte
**-f** | Menampilkan beberapa line terakhir dari sebuah file, tetapi secara realtime

**Example**
Commad | Meaning
--- | ---
**tail -n 5 file.txt** | Menampilkan 5 line terakhir dari file.txt
**tail -c 10 file.txt** | Menampilkan 10 byte terakhir dari file.txt
**ls /bin \| tail -n 5** | Menampilkan 5 line terakhir dari hasil output ls /bin
**tail -f /var/log/messages** | Menampilkan 10 line terakhir secara realtime dari /var/log/messages