# AssignmentGitHub
Last login: Wed Feb  7 15:26:16 on ttys001
MEHRBANOs-MBP:~ mehrbanosyed$ mkdir lessons_learned
MEHRBANOs-MBP:~ mehrbanosyed$ cd lessons_learned/
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ touch Readme.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ pwd
/Users/mehrbanosyed/lessons_learned
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ ls
Readme.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ ls
Readme.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git init
Initialized empty Git repository in /Users/mehrbanosyed/lessons_learned/.git/
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git stat
git: 'stat' is not a git command. See 'git --help'.

The most similar commands are
	status
	stage
	stash
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	Readme.md

nothing added to commit but untracked files present (use "git add" to track)
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ ls
Readme.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git --help
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ 
Display all 1372 possibilities? (y or n)
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ s
-bash: s: command not found
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ cd ..
MEHRBANOs-MBP:~ mehrbanosyed$ ls
Applications	Downloads	Music		bloc		lessons_learned
Desktop		Library		Pictures	learned
Documents	Movies		Public		lesson
MEHRBANOs-MBP:~ mehrbanosyed$ cd lessons_learned/
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ ls
Readme.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git init
Reinitialized existing Git repository in /Users/mehrbanosyed/lessons_learned/.git/
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	Readme.md

nothing added to commit but untracked files present (use "git add" to track)
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git add Readme.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git commit -m "first commit"
[master (root-commit) 0976244] first commit
 Committer: MEHRBANO SYED <mehrbanosyed@mehrbanos-mbp.attlocal.net>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Readme.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ vi RFeadme.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ cat Readme.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ ls
RFeadme.md	Readme.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ rm RFeadme.md 
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ vi Readme.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ 
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ cat Readme.md 
1. HTML
2. CSS
3. Javascipt
4. Git
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git remote add origin https://github.com/Mehr786/Lesson-Learned
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git push -u origin master
Username for 'https://github.com': Mehr786
Password for 'https://Mehr786@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/Mehr786/Lesson-Learned/'
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ ls
Readme.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

MEHRBANOs-MBP:lessons_learned mehrbanosyed$ ls
Readme.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   Readme.md

no changes added to commit (use "git add" and/or "git commit -a")
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git commit -a
Aborting commit due to empty commit message.
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git add readme.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git commit -m" updating readme file"
On branch master
Changes not staged for commit:
	modified:   Readme.md

no changes added to commit
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git add Readme.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   Readme.md

MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git commit -m" updating readme file"
[master 549b28f]  updating readme file
 Committer: MEHRBANO SYED <mehrbanosyed@mehrbanos-mbp.attlocal.net>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 4 insertions(+)
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git status
On branch master
nothing to commit, working tree clean
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git push --set-upstream origin master
Username for 'https://github.com': sphere70s@yahoo.com
Password for 'https://sphere70s@yahoo.com@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/Mehr786/Lesson-Learned/'
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git push --set-upstream origin master
Username for 'https://github.com': mehr786
Password for 'https://mehr786@github.com': 
To https://github.com/Mehr786/Lesson-Learned
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/Mehr786/Lesson-Learned'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git pull
warning: no common commits
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/Mehr786/Lesson-Learned
 * [new branch]      master     -> origin/master
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> master

MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git branch --set-upstream-to=origin/<branch> master
-bash: branch: No such file or directory
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git branch --set-upstream-to=origin/master master
Branch master set up to track remote branch master from origin.
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git pull
fatal: refusing to merge unrelated histories
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git push
To https://github.com/Mehr786/Lesson-Learned
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/Mehr786/Lesson-Learned'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git pull
fatal: refusing to merge unrelated histories
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git pull --allow-unrelated-histories
Merge made by the 'recursive' strategy.
 README.md | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git push
Counting objects: 8, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (4/4), done.
Writing objects: 100% (8/8), 831 bytes | 831.00 KiB/s, done.
Total 8 (delta 0), reused 0 (delta 0)
To https://github.com/Mehr786/Lesson-Learned
   ef48dc8..4c9e43e  master -> master
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git status
On branch master
Your branch is up-to-date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   Readme.md

no changes added to commit (use "git add" and/or "git commit -a")
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git add .
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git commit -m "Updated readme"
[master 57066e6] Updated readme
 Committer: MEHRBANO SYED <mehrbanosyed@mehrbanos-mbp.attlocal.net>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+), 4 deletions(-)
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git push
Counting objects: 2, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 271 bytes | 271.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0)
To https://github.com/Mehr786/Lesson-Learned
   4c9e43e..57066e6  master -> master
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ git status
On branch master
Your branch is up-to-date with 'origin/master'.

nothing to commit, working tree clean
MEHRBANOs-MBP:lessons_learned mehrbanosyed$ 
