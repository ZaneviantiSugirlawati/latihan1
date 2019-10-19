#Latihan 1
CARA MENGGUNAKAN GIT
1.	Download Git Bash (https://git-scm.com/downloads)
2.	Setelah Git Bash sudah terinstal, buka Git kemudian ketik git –version

![image](https://user-images.githubusercontent.com/56709070/67139677-00d05d80-f27d-11e9-8123-67c2f32b7f90.png)
 
3.	Untuk yang pertama kali menggunakan git, perlu melakukan settingan atau setelan pada sistem komputer agar masuk ke sistem jaringan dengan baik dan benar. Maka kita harus menambahkan user name dan user email
 
 ![image](https://user-images.githubusercontent.com/56709070/67139737-98ce4700-f27d-11e9-98ba-82818922443e.png)

4.	Selanjutnya buatlah folder dengan nama latihan1, dengan cara ketik pada Git  mkdir latihan1 dan cd latihan1
 
![image](https://user-images.githubusercontent.com/56709070/67139741-a388dc00-f27d-11e9-8c4f-6ed6db737953.png)
!

5.	Lalu akan muncul foldernya seperti ini

![image](https://user-images.githubusercontent.com/56709070/67139879-468e2580-f27f-11e9-90ac-01f88d07c3a4.png)
 
6.	Untuk menambahkan file pada repository di github, buatlah file bernama README.md dengan ketik text echo “#Latihan 1” >> README.md
 

![image](https://user-images.githubusercontent.com/56709070/67139753-b69bac00-f27d-11e9-91c8-0785c901ae93.png)

7.	Lalu akan muncul file bernama README

![image](https://user-images.githubusercontent.com/56709070/67139759-be5b5080-f27d-11e9-836d-0623e1e27150.png)

8.	Untuk membuat repository local ketik perintah git init
 
![image](https://user-images.githubusercontent.com/56709070/67139902-6aea0200-f27f-11e9-85f7-e1c995a6f106.png)

9.	Setelah itu ketik git add README.md

![image](https://user-images.githubusercontent.com/56709070/67139915-910fa200-f27f-11e9-8802-25c39b86da6d.png)

10.	Selanjutnya gunakan perintah git commit –m “komentar pertama”
$ git commit –m “latihan1”

![image](https://user-images.githubusercontent.com/56709070/67139932-b7cdd880-f27f-11e9-8a55-de81ba519058.png)

•	Untuk membuat Repository Server harus membuat akun terlebih dahulu

•	Setelah membuat akun klik New Repository

![image](https://user-images.githubusercontent.com/56709070/67140028-902b4000-f280-11e9-84d7-31d334ddaaf5.png)
   
•	Lalu isi nama repositorynya latihan1

•	Selanjutnya klik Create repository

![image](https://user-images.githubusercontent.com/56709070/67140042-af29d200-f280-11e9-99b9-ee3420ba53f9.png)

•	Kembali ke Git Bash ketik perintah git remote add origin [url]

![image](https://user-images.githubusercontent.com/56709070/67139781-00849200-f27e-11e9-978e-ef8aa596120e.png)
 
•	Untuk membuat perubahan pada file README pada local repository ke server,  ketik git push –u origin master
 
 ![image](https://user-images.githubusercontent.com/56709070/67139783-09756380-f27e-11e9-83ba-3a7759dd43b5.png)
 
•	Setelah itu perubahannya akan terlihat seperti ini
 
![image](https://user-images.githubusercontent.com/56709070/67139786-15612580-f27e-11e9-95fa-7ed67128da0c.png)
