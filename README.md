# mlops_task
git clone https://github.com/NehaAnalyticsHub/mlops_task
C:\Users\Lenovo>git clone https://github.com/NehaAnalyticsHub/mlops_task
Cloning into 'mlops_task'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.



C:\Users\Lenovo>cd mlops_task

C:\Users\Lenovo\mlops_task>git checkout -b dev
Switched to a new branch 'dev'

C:\Users\Lenovo\mlops_task>git checkout -b test
Switched to a new branch 'test'

C:\Users\Lenovo\mlops_task>git checkout -b i200677
Switched to a new branch 'i200677'

C:\Users\Lenovo\mlops_task>git checkout -b i201853
Switched to a new branch 'i201853'

C:\Users\Lenovo\mlops_task>git branch
  dev
  i200677
* i201853
  main
  test

C:\Users\Lenovo\mlops_task>git push origin dev test i200677 i201853
info: please complete authentication in your browser...
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/NehaAnalyticsHub/mlops_task
 * [new branch]      dev -> dev
 * [new branch]      test -> test
 * [new branch]      i200677 -> i200677
 * [new branch]      i201853 -> i201853





C:\Users\Lenovo\mlops_task>mkdir mlops_task-python-project

C:\Users\Lenovo\mlops_task>cd mlops_task-python-project

C:\Users\Lenovo\mlops_task\mlops_task-python-project>touch main.py
'touch' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\Lenovo\mlops_task\mlops_task-python-project>echo. > main.py

C:\Users\Lenovo\mlops_task\mlops_task-python-project>echo. > utils.py

C:\Users\Lenovo\mlops_task\mlops_task-python-project>git init
Initialized empty Git repository in C:/Users/Lenovo/mlops_task/mlops_task-python-project/.git/

C:\Users\Lenovo\mlops_task\mlops_task-python-project>git add .

C:\Users\Lenovo\mlops_task\mlops_task-python-project>git commit -m "Initial project scaffolding by i200677"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Lenovo@DESKTOP-GNRJ18T.(none)')

C:\Users\Lenovo\mlops_task\mlops_task-python-project> git config --global user.email "neha.shabbir11@gmail.com"

C:\Users\Lenovo\mlops_task\mlops_task-python-project> git config --global user.name "i200677_Neha"

C:\Users\Lenovo\mlops_task\mlops_task-python-project>git commit -m "Initial project scaffolding by i200677"
[master (root-commit) fdb9456] Initial project scaffolding by i200677
 2 files changed, 2 insertions(+)
 create mode 100644 main.py
 create mode 100644 utils.py

C:\Users\Lenovo\mlops_task\mlops_task-python-project>git remote add origin https://github.com/NehaAnalyticsHub/mlops_task

C:\Users\Lenovo\mlops_task\mlops_task-python-project>git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 247 bytes | 247.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/NehaAnalyticsHub/mlops_task/pull/new/master
remote:
To https://github.com/NehaAnalyticsHub/mlops_task
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.



  
