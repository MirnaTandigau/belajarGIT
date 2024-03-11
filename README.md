Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
…

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ echo "Hari ini kita belajar github" > Tugas-git.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-git.txt

nothing added to commit but untracked files present (use "git add" to track)

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
warning: in the working copy of 'Tugas-git.txt', LF will be replaced by CRLF the next time Git touches it

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan dan mengedit Tugas-git.txt"
[Tugas-git 4839656] Menambahkan dan mengedit Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git merge Tugas-git
Updating 442fd1f..4839656
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 333 bytes | 333.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MirnaTandigau/belajarGIT.git
   442fd1f..4839656  main -> main

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ echo "Hari ini kita belajar git" > Tugas-html.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-html.txt

nothing added to commit but untracked files present (use "git add" to track)

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ git add Tugas-html.txt
warning: in the working copy of 'Tugas-html.txt', LF will be replaced by CRLF the next time Git touches it

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-html.txt


LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan dan mengedit Tugas-html.txt"
[Tugas-html f9c73eb] Menambahkan dan mengedit Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git merge Tugas-html
Updating 4839656..f9c73eb
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 359 bytes | 359.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MirnaTandigau/belajarGIT.git
   4839656..f9c73eb  main -> main

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ echo "Hari ini kita belajar git" > Tugas-css.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ git add Tugas-css.txt
warning: in the working copy of 'Tugas-css.txt', LF will be replaced by CRLF the next time Git touches it

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-css.txt


LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan dan mengedit Tugas-css.txt"
[Tugas-css 986492a] Menambahkan dan mengedit Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
nothing to commit, working tree clean

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git merge Tugas-css
Updating f9c73eb..986492a
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 253 bytes | 253.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MirnaTandigau/belajarGIT.git
   f9c73eb..986492a  main -> main

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ echo "Hari ini kita belajar git" > Tugas-js.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ git add Tugas-js.txt
warning: in the working copy of 'Tugas-js.txt', LF will be replaced by CRLF the next time Git touches it

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-js.txt


LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan dan mengedit Tugas-js.txt"
[Tugas-js 6a3ad11] Menambahkan dan mengedit Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
nothing to commit, working tree clean

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git merge Tugas-js
Updating 986492a..6a3ad11
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 276 bytes | 276.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MirnaTandigau/belajarGIT.git
   986492a..6a3ad11  main -> main

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ echo "Hari ini kita belajar git" > Tugas-midProject.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt
warning: in the working copy of 'Tugas-midProject.txt', LF will be replaced by CRLF the next time Git touches it

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-midProject.txt


LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan dan mengedit Tugas-midProject.txt"
[Tugas-midProject d1ef974] Menambahkan dan mengedit Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
nothing to commit, working tree clean

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
gi
LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git merge Tugas-midProject
Updating 6a3ad11..d1ef974
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 270 bytes | 270.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MirnaTandigau/belajarGIT.git
   6a3ad11..d1ef974  main -> main

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ echo "Hari ini kita belajar git" > Tugas-php.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-php.txt

nothing added to commit but untracked files present (use "git add" to track)

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ git add Tugas-php.txt
warning: in the working copy of 'Tugas-php.txt', LF will be replaced by CRLF the next time Git touches it

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-php.txt


LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan dan mengedit Tugas-php.txt"
[Tugas-php ddddd79] Menambahkan dan mengedit Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
nothing to commit, working tree clean

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
gi
LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git merge Tugas-php
Updating d1ef974..ddddd79
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 257 bytes | 257.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MirnaTandigau/belajarGIT.git
   d1ef974..ddddd79  main -> main

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ echo "Hari ini kita belajar git" > Tugas-finalProject.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-finalProject
        Tugas-finalProject.txt

nothing added to commit but untracked files present (use "git add" to track)

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt
warning: in the working copy of 'Tugas-finalProject.txt', LF will be replaced by CRLF the next time Git touches it

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-finalProject.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-finalProject


LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan dan mengedit Tugas-finalProject.txt"
[Tugas-finalProject 5742b18] Menambahkan dan mengedit Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-finalProject

nothing added to commit but untracked files present (use "git add" to track)

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git merge Tugas-finalProject
Updating ddddd79..5742b18
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

LENOVO@mrnaxx MINGW64 /d/TugasWeb/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 273 bytes | 273.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MirnaTandigau/belajarGIT.git
   ddddd79..5742b18  main -> main
