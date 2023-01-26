Colton Savage
Thesavage73 
cs2400
lab 2

1.) git version 2.17.1

2.) user.name=Colton Savage
    user.email=cs845221@ohio.edu

3.) These are common Git commands used in various situations:

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


4.)untacked files:
		README.md
		answers.md

5.)changes to be committed:
		new file: README.md
   untracked files:
		answers.md

6.)changes to be committed: 
		new file: README.md
		new file: answers.md

7.)nothing to commit, working tree clean

8.)commit d8c14246efeeec0da85101562e810d6cd7972b4b (HEAD -> master)
Author: Colton Savage <cs845221@ohio.edu>
Date:   Wed Jan 25 18:33:00 2023 -0500

    Initial commit

commit 34c29dea0e35ac2d45cb220447cdcf8e267d55bb
Author: Colton Savage <cs845221@ohio.edu>
Date:   Wed Jan 25 18:28:00 2023 -0500

    Initial commit

9.)On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
csavage@odd31:~/2400/git-lab$ 

10.) no

11.)  ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Thesavage73/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

12.)yes they were recorded

remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/Thesavage73/git-lab
   d8c1424..61e8eb6  main       -> origin/main
Updating d8c1424..61e8eb6
Fast-forward
 README.md | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)

13.)csavage@odd31:~/2400$ ls -a
.  ..  git-lab	git-lab-2  Labs


Done







