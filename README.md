# gitpractice
Practice git commands 
D:\code>mkdir git_learn
D:\code>cd git_learn
D:\code\git_learn>git init
Initialized empty Git repository in D:/code/git_learn/.git/
D:\code\git_learn>
D:\code\git_learn>git remote add origin "https://github.com/pampanaharish/gitpractice.git"
D:\code\git_learn>
D:\code\git_learn>git pull origin master
fatal: couldn't find remote ref master
D:\code\git_learn>git pull origin main
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 621 bytes | 1024 bytes/s, done.
From https://github.com/pampanaharish/gitpractice
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
D:\code\git_learn>
D:\code\git_learn>git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Git_commands.txt.txt

nothing added to commit but untracked files present (use "git add" to track)

D:\code\git_learn>git add .

D:\code\git_learn>git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Git_commands.txt.txt
D:\code\git_learn>git commit -m "My 1st commit"
[master d939892] My 1st commit
 1 file changed, 18 insertions(+)
 create mode 100644 Git_commands.txt.txt
D:\code\git_learn>git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/pampanaharish/gitpractice.git'
D:\code\git_learn>git push origin master
Select an authentication method for 'https://github.com/':
  1. Web browser (default)
  2. Personal access token
option (enter for default):
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 616 bytes | 616.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/pampanaharish/gitpractice/pull/new/master
remote:
To https://github.com/pampanaharish/gitpractice.git
 * [new branch]      master -> master
D:\code\git_learn>