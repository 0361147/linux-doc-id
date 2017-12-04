## Pengertian

Grep adalah sebuah commad yang di gunakan untuk melakukan filter berdasarkan pattern yang di berikan. Dalam penggunaannya kita harus memberikan pattern ke pada grep jika tidak maka akan muncul pesan peringatan bahwa pattern di butuhkan. Untuk file yang akan di filter berada setelah pattern, bisa juga berasal dari output program lainnnya, dinama nantinya akan di pipe ke grep.

**Example**
Commad | Meaning
--- | ---
**grep ada file.txt** | Hanya menampilkan kalimat yang memiliki kata "ada" di dalamnya
**ls / \| grep root** | Hanya menampilkan file yang memiliki nama root