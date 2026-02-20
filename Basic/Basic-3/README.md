## Problem
Level 3

This time Network Security Sam remembered to upload the password file, but there were deeper problems than that.

## Solusi
Pada soal ini, aplikasi menggunakan sebuah form untuk memvalidasi kata sandi, sama seperti soal sebelumnya. Langkah pertama yang harus kita lakukan adalah memeriksa source code HTML terutama pada bagian `<form>` 

<img width="976" height="259" alt="image" src="https://github.com/user-attachments/assets/1fad43a5-8791-4381-9694-6483d6090618" />

Pada gambar di atas, dapat kita ketahui bahwa terdapat path file yang terekspos, dan kita dapat mencoba mengaksesnya secara langsung dengan menambahkan password.php di akhir URL saat ini (https://www.hackthissite.org/missions/basic/3/ menjadi https://www.hackthissite.org/missions/basic/3/password.php).

Setelah itu, password akan ditemukan, yaitu 7710c5d9
<img width="867" height="273" alt="image" src="https://github.com/user-attachments/assets/eb4de865-6093-4fa5-917d-3611c6a61531" />
