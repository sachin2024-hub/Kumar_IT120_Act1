dmin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop
$ mkdir Kumar_IT120_act1

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop
$ cd Kumar_IT120_act1

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1
$ touch Profile.txt

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1
$ touch Education.txt

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1
$ touch Background.txt

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1
$ touch Readme.txt

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1
$ touch test.py

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1
$ git init
Initialized empty Git repository in C:/Users/Admin/Desktop/Kumar_IT120_act1/.git
/

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (master)
$ git branch Kumar_B1
fatal: not a valid object name: 'master'

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (master)
$ git add .

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (master)
$ git commit -m "First commit"
\[master (root-commit) 33a2ff1] First commit
 5 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.txt
 create mode 100644 test.py

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (master)
$ git branch Kumar_B1

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (master)
$ git branch Kumar_B2

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (master)
$ git branch Kumar_B3

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (master)
$ git branch Kumar_B4

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (master)
$ git branch
  Kumar_B1
  Kumar_B2
  Kumar_B3
  Kumar_B4
* master

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (master)
$
git add . 
git commit -m "second commit"



Branch 1
 git checkout Kumar_B1
Switched to branch 'Kumar_B1'

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (Kumar_B1)
$ git status
On branch Kumar_B1
nothing to commit, working tree clean

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (Kumar_B1)
$ git merge mastes
merge: mastes - not something we can merge

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (Kumar_B1)
$ git merge master
Updating 33a2ff1..e91c781
Fast-forward
 Background.txt |  1 +
 Education.txt  |  4 ++++
 Profile.txt    |  7 ++++++
 Readme.txt     | 67 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 test.py        |  2 ++
 5 files changed, 81 insertions(+)

git add Profile.txt
git add Readme.txt
git commit -m "Add a new 


branch 2
 git checkout Kumar_B2
Switched to branch 'Kumar_B2'

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (Kumar_B2)
$ git merge master
Updating 33a2ff1..e91c781
Fast-forward
 Background.txt |  1 +
 Education.txt  |  4 ++++
 Profile.txt    |  7 ++++++
 Readme.txt     | 67 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 test.py        |  2 ++
 5 files changed, 81 insertions(+)

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (Kumar_B2)
$ git checkout Kumar_B1 -- Readme.txt
git add Education.txt
git add Readme.txt
git commit -m "Added a new in branch2"