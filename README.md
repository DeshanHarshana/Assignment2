### 1. Create a repository named as “Assignment 2” in github with Readme.md file, Questions must be paste in the readme file.

### 2. Clone Your repository 
    git clone https://github.com/DeshanHarshana/Assignment2.git
    Cloning into 'Assignment2'...
    remote: Enumerating objects: 6, done.
    remote: Counting objects: 100% (6/6), done.
    remote: Compressing objects: 100% (3/3), done.
    remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
    Receiving objects: 100% (6/6), done.
    
 ### 3. Add the text file that should have the answer of Q1.
    git add Q1.txt
         
 ### 4. Add another file to do the following
    touch anotherfile.txt
         
 ### 5. Create another branch
    git checkout -b anotherBranch
    Switched to a new branch 'anotherBranch'
    
### 6. Make changes to your files.
### 7. see if the file change is detected with git status.

    $ git status
    On branch anotherBranch
    Changes to be committed:
      (use "git restore --staged <file>..." to unstage)
            new file:   Q1.txt

    Untracked files:
      (use "git add <file>..." to include in what will be committed)
            anotherfile.txt
            
 ### 8. stage the changes with git add .
 
    $ git add .

### 9. check that the add did what you expected with git status.
    $ git status
    On branch anotherBranch
    Changes to be committed:
      (use "git restore --staged <file>..." to unstage)
            new file:   Q1.txt
            new file:   anotherfile.txt

### 10. make the commit with git commit.
### 11. Write a meaningful commit message (e.g. "Answers question 1").

    $ git commit -am "Answer Question"
    [anotherBranch 609a6db] Answer Question
     2 files changed, 7 insertions(+)
     create mode 100644 Q1.txt
     create mode 100644 anotherfile.txt
     
### 12 check that your working directory is clean with git status.
    git status
    On branch anotherBranch
    nothing to commit, working tree clean

### 13. check that your commit succeeded as expected with git log
    $ git log
    commit 609a6dbe5620d4f8ce50ab2c94be647ca72e9198 (HEAD -> anotherBranch)
    Author: DeshanHarshana <nawarathnadeshan@gmail.com>
    Date:   Wed Sep 8 15:40:13 2021 +0530

    Answer Question

    commit 5be743b5d5174a81fdab0cdb91a811c7fc2bedc5 (main)
    Author: DeshanHarshana <39896755+DeshanHarshana@users.noreply.github.com>
    Date:   Wed Sep 8 14:44:03 2021 +0530

     Q1

    commit ae44dd0e0b0f5dd3635f4a56a854047651eed5ff
    Author: DeshanHarshana <39896755+DeshanHarshana@users.noreply.github.com>
    Date:   Wed Sep 8 14:42:45 2021 +0530

    Initial commit

### 14. Push your code up to a github repository
    $ git push origin anotherBranch
    Enumerating objects: 5, done.
    Counting objects: 100% (5/5), done.
    Delta compression using up to 4 threads
    Compressing objects: 100% (3/3), done.
    Writing objects: 100% (4/4), 471 bytes | 471.00 KiB/s, done.
    Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
    remote:
    remote: Create a pull request for 'anotherBranch' on GitHub by visiting:
    remote:      https://github.com/DeshanHarshana/Assignment2/pull/new/anotherBranch
    remote:
    To https://github.com/DeshanHarshana/Assignment2.git
     * [new branch]      anotherBranch -> anotherBranch

