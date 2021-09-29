**Nama Mahasiswa 	: Najma Attaqiya Alya**


**NIM		        : 162012133015**


**Prodi		        : Teknologi Sains Data**


**Matkul | Kelas	: Algoritma Pemrograman 2 | SD-A1**




Langkah-langkah dalam menggunakan dan commit pada GitHub: 


1. Login GitHub

3. Setting identitas pada Git. Masukkan Username dan Email GitHub dengan menggunakan perintah
 
**$ git config --global user.name "UsernameAnda"** -> Username pada GitHub


**$ git config --global user.email <alamat email>**  -> Email yang terdaftar pada GitHub
  

**$ git config --list**  -> Memastikan proses login berhasil
  
  
3. Buat Repository Online dengan nama yang saya buat sesuai dengan nama pada folder directory lokal.
5. Membuat folder pada directory lokal dan repository lokal dengan memberikan nama file sesuai dengan nama repository Online pada GitHub yakni **Tugas1-Alpro2**. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah dibuat.
4. Membuka GitBash pada folder yang telah dibuat. Buka folder dengan klik kanan lalu pilih Git Bash Here. Setelah itu, akan muncul Command Line Interface (CLI). 
5. Lakukan Inisialisasi dengan menggunakan perintah **$git init**
6. Masukkan File pada area staging Repository dengan menggunakan perintah **$ git add Readme.md**
7. Commit file yang telah dibuat di repository lokal dengan perintah **$git commit** , untuk menambahkan keterangan/status perubahan saat mengupload ke repository online, gunakan **$ git commit -m "isi commit"**

9. Menambahkan alamat Remote Repository Github dengan menggunakan perintah **$git remote add server-alya <link repository GitHub>**.
11. Push ke GitHub. Push file Readme.md kosong ini pada repository dengan **$git push server-alya master**
12. Mengedit file Readme.md yang nantinya akan berisi langkah langkah menggunakan dan commit pada GitHub. 
13. Setelah itu, menambahkan file yang telah diedit Readme.md pada staging area dengan perintah **$ git add Readme.md**
14. Commit file Readme.md yang telah diedit dengan perintah **$ git commit**
15. Selanjutnya, kita push file Readme.md dengan perintah **$ git push server-alya master**
