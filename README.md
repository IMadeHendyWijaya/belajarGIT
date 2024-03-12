# belajarGIT
 Daftar tugas / branch
 1. Tugas-git
 2. Tugas-html
 3. Tugas-css
 4. Tugas-js
 5. Tugas-midProject
 6. Tugas-php
 7. Tugas-finalProject
 Daftar perintah GiT
 …
LEGION@Shion MINGW64 /c/TUGAS WEB
$ git clone "https://github.com/IMadeHendyWijaya/belajarGIT.git"
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

LEGION@Shion MINGW64 /c/TUGAS WEB
$ git config --global user.email "madewijaya39@gmail.com"

LEGION@Shion MINGW64 /c/TUGAS WEB
$ cd belajarGIT

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-git)
$ git commit -m "commit 1 tambah tugasgit dan keterangan"
[Tugas-git 23c8c0b] commit 1 tambah tugasgit dan keterangan
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git merge Tugas-git
Updating 6b9dbfd..23c8c0b
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 307 bytes | 307.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/IMadeHendyWijaya/belajarGIT.git
   6b9dbfd..23c8c0b  main -> main

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-html)
$ git commit -m "commit 1 tambah tugashtml dan keterangan"
[Tugas-html 92a5e5a] commit 1 tambah tugashtml dan keterangan
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git merge Tugas-html
Updating 23c8c0b..92a5e5a
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 341 bytes | 341.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/IMadeHendyWijaya/belajarGIT.git
   23c8c0b..92a5e5a  main -> main

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-css)
$ git commit -m "commit 1 tambah tugascss dan keterangan"
[Tugas-css 38d85d1] commit 1 tambah tugascss dan keterangan
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git merge Tugas-css
Updating 92a5e5a..38d85d1
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 374 bytes | 374.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/IMadeHendyWijaya/belajarGIT.git
   92a5e5a..38d85d1  main -> main

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-js)
$ git commit -m "commit 1 tambah tugasjs dan keterangan"
[Tugas-js c22eb78] commit 1 tambah tugasjs dan keterangan
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git merge Tugas-js
Updating 38d85d1..c22eb78
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 301 bytes | 301.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/IMadeHendyWijaya/belajarGIT.git
   38d85d1..c22eb78  main -> main

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-midProject)
$ git commit -m "commit 1 tambah tugasmidProject dan keterangan"
[Tugas-midProject bf579cb] commit 1 tambah tugasmidProject dan keterangan
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git merge Tugas-midProject
Updating c22eb78..bf579cb
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 319 bytes | 319.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/IMadeHendyWijaya/belajarGIT.git
   c22eb78..bf579cb  main -> main

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-php)
$ git commit -m "commit 1 tambah tugasphp dan keterangan"
[Tugas-php d081396] commit 1 tambah tugasphp dan keterangan
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git merge Tugas-php
Updating bf579cb..d081396
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 309 bytes | 309.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/IMadeHendyWijaya/belajarGIT.git
   bf579cb..d081396  main -> main

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalproject.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalproject.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-finalProject)
$ git commit -m "commit 1 tambah tugasfinalproject dan keterangan"
[Tugas-finalProject 99bca43] commit 1 tambah tugasfinalproject dan keterangan
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalproject.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git merge Tugas-finalproject
Updating d081396..99bca43
Fast-forward
 Tugas-finalproject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalproject.txt

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 300 bytes | 300.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/IMadeHendyWijaya/belajarGIT.git
   d081396..99bca43  main -> main

LEGION@Shion MINGW64 /c/TUGAS WEB/belajarGIT (main)
$
