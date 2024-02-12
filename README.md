# mlops_task

#Task 1

git clone https://github.com/NehaAnalyticsHub/mlops_task
    Cloning into 'mlops_task'...
    remote: Enumerating objects: 3, done.
    remote: Counting objects: 100% (3/3), done.
    remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
    Receiving objects: 100% (3/3), done.

cd mlops_task
git checkout -b dev
    Switched to a new branch 'dev'
git checkout -b test
    Switched to a new branch 'test'
git checkout -b i200677
    Switched to a new branch 'i200677'
git checkout -b i201853
    Switched to a new branch 'i201853'
git branch
  dev
  i200677
* i201853
  main
  test

git push origin dev test i200677 i201853
    info: please complete authentication in your browser...
    Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
    To https://github.com/NehaAnalyticsHub/mlops_task
     * [new branch]      dev -> dev
     * [new branch]      test -> test
     * [new branch]      i200677 -> i200677
     * [new branch]      i201853 -> i201853



#Task 2
mkdir mlops_task-python-project
cd mlops_task-python-project
touch main.py
    'touch' is not recognized as an internal or external command,
    operable program or batch file.
echo. > main.py
echo. > utils.py
git init
    Initialized empty Git repository in C:/Users/Lenovo/mlops_task/mlops_task-python-project/.git/
git add .
git commit -m "Initial project scaffolding by i200677"
      Author identity unknown
      
      *** Please tell me who you are.
      
      Run
      
        git config --global user.email "you@example.com"
        git config --global user.name "Your Name"
      
      to set your account's default identity.
      Omit --global to set the identity only in this repository.

      fatal: unable to auto-detect email address (got 'Lenovo@DESKTOP-GNRJ18T.(none)')

git config --global user.email "neha.shabbir11@gmail.com"
git config --global user.name "i200677_Neha"
git commit -m "Initial project scaffolding by i200677"
      [master (root-commit) fdb9456] Initial project scaffolding by i200677
       2 files changed, 2 insertions(+)
       create mode 100644 main.py
       create mode 100644 utils.py

git remote add origin https://github.com/NehaAnalyticsHub/mlops_task
git push -u origin master
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

mlops_task-python-project>cd ..
git push -u origin i200677 i201853
      Everything up-to-date
      branch 'i200677' set up to track 'origin/i200677'.
      branch 'i201853' set up to track 'origin/i201853'.
git checkout dev
      Switched to branch 'dev'

git merge i200677
      Already up to date.

git merge i201853
      Already up to date.


  
