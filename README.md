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



Cara Push beda Branch :
1. git init (kalo belum ada, kalo sudah ada lewat aja)
2. git remote add origin https://github.com/rizkydwiananto/simklinik.git
3. git branch -M (nama branch : update_view_pegawai_detail)
4. git add . (titik)
5. git commit -m "ini contoh update"
6. git push -u origin update_view_pegawai_detail

.. Disarankan berbeda branch untuk push , atau branch sama tidak apa, yang penting ada perubahan / commit ditulis lengkap


Cara cek branch :
git branch

Cara menghapus branch :
1. git push origin --delete <nama branch : update_view_pegawai_detail>
