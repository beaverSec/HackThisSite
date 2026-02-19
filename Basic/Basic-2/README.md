## Problem 
Level 2

Network Security Sam set up a password protection script. He made it load the real password from an unencrypted text file and compare it to the password the user enters. However, he neglected to upload the password file...

## Solusi
Karena pada soal kita diberitahu bahwa Sam lupa mengupload file passwordnya, maka program tidak akan membandingkan password yang diinput oleh user. Maka dari itu, kita hanya perlu membiarkan kolom password kosong dan menekan tombol "Submit", dan aplikasi akan membandingkan string input yang kosong dengan string di server yang juga kosong. Karena "" == "" (kosong sama dengan kosong), sehingga autentikasi berhasil dilewati.
