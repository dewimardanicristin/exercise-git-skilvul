1 Cara push file ke github

1. git init #nama_folder
 
2. git init . #jika folder sudah tersedia

3. git remote add [orgin] [link_repo] 

4. git add . #jika semua file dalam folder akan di push

   git add nama_file #jika terdapat satu file dalam folder yang akan dipush

5. git commit -m "message" #memberikan informasi 

6. git push -u origin master

2. Perbedaan git revert dan git reset

Git revert akan akan mengambil kondisi file yang dituju, kemudian menggabungkannya dengan commit terakhir. Sedangkan git reset akan menghapus catatan seluruh commit yang telah dilakukan setelahnya.

3. Perbedaan git dan github 

Git merupakan alat version control. GitHub merupakan alat version control sekaligus sebagai penyimpanan cloud



