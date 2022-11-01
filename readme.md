<h1>Cara Upload file/folder local ke github</h1>
<br>
<ol>
<li>Buat repository baru di github

![Create new repository](resource/img/create-new.png)
![Create new repository](resource/img/rename.png)
![Create new repository](resource/img/copy.png)
</li>
<li>Pilih folder dimana tempat file dan foldernya akan diupload ke github.</li>
<li>Klik kanan dan pilih git bash</li>
<li>ketik di git bash
   
    git init
    git add .
    git commit -m "message"
    git remote add origin https://github.com
    git push -u origin master
</li>
<li>Silahkan periksa di github untuk memastikan berhasil atau tidaknya.</li>
</ol>
<br><br>
<h5>Note : jika belum login git maka login terlebih dahulu dengan command </h5>

    git config --global user.email "example.gmail.com"
    git config --global user.name "example username"
