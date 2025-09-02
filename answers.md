1) git version 2.43.0
2) user.name=Ella Semancik
user.email=es175224@ohio.edu
3) When you type
git add --help, the documentation for the git add command will be displayed. It shows a description, what the command does, and it's purpose, which is to add file contents to the index.
4) The output reads:
On branch master

No commits yet

Untracked files:
(use "git add <file>..." to include in what will be committed)
    README.md
    answers.md
nothing added to commit but untracked files present (use "git add" to track)
5) The new output reads:
On branch master

No commits yet

Changes to be committed:
    (use "git rm --cached <file>..." to unstage)
    new file:  README.md

Untracked files:
(use "git add <file>..." to include in what will be committed)
    answers.md
6) The new output reads:
On branch master

No commits yet

Changes to be committed:
    (use "git rm --cached <file>..." to unstage)
    new file:  README.md
    new file:  answers.md
7) The output is:
On branch master
Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git restore <file>..." to discard changes in working directory)
        modified: answers.md
8) The output is:
commit f869f39ffbb2839925df34dc4ac76842c38781e7 (HEAD -> master)
Author: Ella Semancik <es175224@ohio.edu>
Date:   Tue Sep 2 17:07:04 2025 -0400

    Initial commit

