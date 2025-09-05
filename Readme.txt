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

branch 3
 git status
On branch Kumar_B3
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Readme.txt
        deleted:    test.py

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Readme.txt


Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (Kumar_B3)
$ git add Readme.txt

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (Kumar_B3)
$ git commit -m "Mali "
[Kumar_B3 22486a7] Mali
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 test.py

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (Kumar_B3)
$ git merge master
CONFLICT (modify/delete): test.py deleted in HEAD and modified in master.  Versi
on master of test.py left in tree.
Automatic merge failed; fix conflicts and then commit the result.

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (Kumar_B3|MERGING)
$ git rm test.py
rm 'test.py'

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (Kumar_B3|MERGING)
$ git checkout Kumar -- Readme.txt
fatal: invalid reference: Kumar

Admin@DESKTOP-LSU5CF3 MINGW64 ~/Desktop/Kumar_IT120_act1 (Kumar_B3|MERGING)
$ git checkout Kumar_B2 -- Readme.txt
git add Background.txt
git add Readme.txt
git commit -m "added a new file in branch 3"
