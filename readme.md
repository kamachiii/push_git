<h1>Cara Upload file/folder local ke github</h1>
<br>
<ol>
<li>Buat repository baru di github dan copy link https

![Create new repository](resource/img/create-new.png)
![Rename repository](resource/img/rename.png)
![Copy link https](resource/img/copy.png)
</li>
<li>Pilih folder dimana tempat file dan foldernya akan diupload ke github.</li>

![Select folder](resource/img/select-folder.png)
<li>Klik kanan dan pilih git bash</li>

![right click to git bash](resource/img/rightclick-folder.png)
<li>ketik di dalam git bash
   
    git init
    git add .
    git commit -m "message"
    git remote add origin https://github.com
    git push -u origin master
</li>
<li>Jika sudah periksa refresh github untuk melihatnya</li>
</ol>
<br><br>
<h5>Note : jika belum login git maka login terlebih dahulu dengan command </h5>

    git config --global user.email "example.gmail.com"
    git config --global user.name "example username"
