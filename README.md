# PLPBasicGitAssignment
Basics of git and github workflow

Document the steps and commands used

eKipruto@eGreen MINGW64 /D
$ cd "Python Files"

eKipruto@eGreen MINGW64 /D/Python Files (master)
$ cd /PLPBasicGitAssignment
bash: cd: /PLPBasicGitAssignment: No such file or directory

eKipruto@eGreen MINGW64 /D/Python Files (master)
$ cd..
bash: cd..: command not found

eKipruto@eGreen MINGW64 /D/Python Files (master)
$ cd ..

eKipruto@eGreen MINGW64 /D
$ cd PLPBasicGitAssignment

eKipruto@eGreen MINGW64 /D/PLPBasicGitAssignment
$ git init
Initialized empty Git repository in D:/PLPBasicGitAssignment/.git/

eKipruto@eGreen MINGW64 /D/PLPBasicGitAssignment (master)
$ git remote add origin https://github.com/ekipruto/PLPBasicGitAssignment.git

eKipruto@eGreen MINGW64 /D/PLPBasicGitAssignment (master)
$ git add Heloo.txt

eKipruto@eGreen MINGW64 /D/PLPBasicGitAssignment (master)
$ git commit -m "Add hello.txt with a greeting"
[master (root-commit) d40f786] Add hello.txt with a greeting
 1 file changed, 1 insertion(+)
 create mode 100644 Heloo.txt

eKipruto@eGreen MINGW64 /D/PLPBasicGitAssignment (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 237 bytes | 237.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/ekipruto/PLPBasicGitAssignment/pull/new/master
remote:
To https://github.com/ekipruto/PLPBasicGitAssignment.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

eKipruto@eGreen MINGW64 /D/PLPBasicGitAssignment (master)
$
