# Resume Git
Git adalah perangkat lunak pengendali versi atau proyek manajemen kode perangkat lunak yang diciptakan oleh Linus Torvalds, yang pada awalnya ditujukan untuk pengembangan kernel Linux.
Berikut perintah command penting untuk git:
1. Setting global atau default user menggunakan username git
```sh
git config --global user.name “[firstname lastname]”
```
2. Setting global atau default user github menggunakan email git
```sh
git config --global user.email “[valid-email]”
```
3. Menampilkan file yang sudah dimodifikasi di workspace lalu di tempatkan di staging untuk di commit
```sh
git status
```
4. Menambahkan file untuk di commit dan di tempatkan di stage
```sh
git add [file]
```
5. Menambahkan commit di stage untuk di push disertai pesan yang descriptive
```sh
git commit -m “[descriptive message]”
```
6. Untuk menginisialisasi project git
```sh
git init
```
7. Push commit di stage ke cloud atau ke git
```sh
git push -u origin 
```
8. Mengambil repositori dari URL
```sh
git clone [url]
```
9. Menampilkan list branch dan current active branch
```sh
git branch
```
10. Membuat branch baru dengan nama yang di tentukan
```sh
git branch [branch-name]
```
11. Berpindah dari branch 1 ke yang lain dan menjadikannya working directory
```sh
git checkout
```
12. Merge atau menggabungkan 2 branch menjadi 1
```sh
git merge [branch]
```
13. Menampilkan semua commit di spesifik branch
```sh
git log
```
14. Menambahkan remote url agar dapat di push ke cloud
```sh
git remote add origin [repo-url]
```
15. Menampilkan existing remotes
```sh
git remote -v
```
15. Menyimpan modified changes untuk disimpan di stage agar menghindari kecelakaan ikut ter push
```sh
git stash
```
16. Menampilkan file apa saja yang sudah di stash
```sh
git stash list
```
17. Menampilkan list file apa saja yang sudah di stash
```sh
git stash list
```
18. Untuk menghapus commit yang diinginkan dan otomatis membuat commit baru yang berawalan 'revert' yang ready untuk di push ke cloud 
```sh
git revert [commit]
```