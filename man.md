## Pengertian

Digunakan untuk menampilakm manual page dari sebuah commad. Dalam penampilan manual page tersebut biasanya akan menggunakan tampilan yang sama dengan less, jadi keyboard commad yang dapat di gunakan dalam less dapat juga di gunakan dalam man. Selain itu penampilan manual page pasti terurut mulai dari bagaimana cara commad tersebut di gunakan hingga penggunaannya oleh system admin. Kita juga dapat langsung membuka sebuah bagian dalam commad tersebut dengan menambahkan sebuah argument.

**Man Page Structur** 
Selection | Contents
--- | ---
**1** (default) | User commands
**2** | Programming interfaces for kernel system calls
**3** | Programming interfaces to the C library
**4** | Special files such as device nodes and drivers
**5** | File formats
**6** | Games and amusements such as screen savers
**7** | Miscellaneous
**8** | System administration commands

**Example**

Commad | Meaning
--- | ---
**man ls** | menampilkan manual page dari ls commad
**man 8 ping** | menampilkan manual page system administration commad untuk ping