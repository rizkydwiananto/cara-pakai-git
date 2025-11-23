# cara-pakai-git
Untuk pembelajaran sendiri, cara menggunakan git

Cara ubah git repository
1. git remote -v
2. git remote set-url origin https://github.com/rizkydwiananto/sis.git


Cara Pakai GIT pertama kali : 
1. git init 
2. git add . (titik)
3. git commit -m "first commit"
4. git branch -M main
5. git remote add origin https://github.com/rizkydwiananto/simklinik.git

Jika terkendala atau ada notifikasi *** Please tell me who you are. Lakukan :
1. Run git config --global user.email "rizkydwiananto@gmail.com"
2. git config --global user.name "rizkydwiananto"
3. Lanjut ke commit ke nomor 3


Cara Push beda Branch :
1. git init (kalo belum ada, kalo sudah ada lewat aja)
2. git remote add origin https://github.com/rizkydwiananto/simklinik.git
3. git branch -M (nama branch : update_view_pegawai_detail)
4. git add . (titik)
5. git commit -m "ini contoh update"
6. git push -u origin update_view_pegawai_detail

.. Disarankan berbeda branch untuk push , atau branch sama tidak apa, yang penting ada perubahan / commit ditulis lengkap


Cara git Clone :
1. cd C:\xampp\htdocs
2. git clone https://github.com/dhabyap/mbg-website.git
3. 3. cd mbg-website (done)

Cara cek branch :
git branch

Cara menghapus branch :
1. git push origin --delete <nama branch : update_view_pegawai_detail>
