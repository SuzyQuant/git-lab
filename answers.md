Answers 1 git version 2.24.1.windows.2
Answers 2
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
credential.helper=manager
user.name=Suzanne Conejos
user.email=sc721719@ohio.edu

Answer 3
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)    
   clone     Clone a repository into a new directory  
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a 
symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and 
working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated 
objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help 
<concept>'
to read about a specific subcommand or concept.       
See 'git help git' for an overview of the system.  

Answer 4
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be 
committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

Answer 5
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)        
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be 
committed)
        answers.md

Answer 6
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)        
        new file:   README.md
        new file:   answers.md

Answer 7
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

no changes added to commit (use "git add" and/or "git 
commit -a")

Answer 8
commit e8316f7b4aaf55b9fddbfd3542dfddaec64a4244 (HEAD 
-> master)
Author: Suzanne Conejos <sc721719@ohio.edu>
Date:   Thu May 14 10:46:02 2020 -0400

    Initial commit

Answer 9
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 1.45 KiB | 1.45 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/SuzyQuant/git-lab.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

Answer 10 NO
Answer 11
To https://github.com/SuzyQuant/git-lab.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/SuzyQuant/git-lab.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push 
--help' for details.

Answer 12 YES

Answer 13
Directory: C:\Users\suzanneconejos\Desktop\cs2400\git-lab-2


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----        5/14/2020  11:13 AM            302 .gitignore
-a----        5/14/2020  11:13 AM             11 README.md