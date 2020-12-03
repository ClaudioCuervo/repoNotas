# repoNotas
Alumno@PC13426 MINGW64 ~/desktop
$ git clone https://github.com/ClaudioCuervo/repoNotas.git
Cloning into 'repoNotas'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.

Alumno@PC13426 MINGW64 ~/desktop
$ cd repoNotas

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git add do.txt

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git add mi.txt

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git add re.txt

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git add fa.txt

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git add -A

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git init
Reinitialized existing Git repository in C:/Users/Alumno/Desktop/repoNotas/.git/

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git add do.txt

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git add re.txt

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git add mi.txt

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git add fa.txt

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git add -A

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   do.txt
        new file:   fa.txt
        new file:   mi.txt
        new file:   re.txt


Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git commit -m "añadidos los archivos"
[main f7a4b13] añadidos los archivos
 4 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 do.txt
 create mode 100644 fa.txt
 create mode 100644 mi.txt
 create mode 100644 re.txt

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git add -A

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git tag notasMusicales

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git tag
notasMusicales

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git log
commit f7a4b13b003fa802f8ed5887d6808c10c16bb73e (HEAD -> main, tag: notasMusicales)
Author: SoftwareIFP <52700609+SoftwareIFP@users.noreply.github.com>
Date:   Thu Dec 3 15:16:33 2020 +0100

    añadidos los archivos

commit 98fab9fe60ed198d04508433813de59d49c8c6b5 (origin/main, origin/HEAD)
Author: Claudio Cuervo Gayoso <73246772+ClaudioCuervo@users.noreply.github.com>
Date:   Thu Dec 3 15:05:00 2020 +0100

    Initial commit

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git add -A

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git push
Logon failed, use ctrl+c to cancel basic credential prompt.
git push error: unable to read askpass response from 'C:/Program Files/Git/mingw64/libexec/git-core/git-gui--askpass'
Username for 'https://github.com':
git push https://github.com/ClaudioCuervo/repoNotas.git
ClaudioCuervo
error: unable to read askpass response from 'C:/Program Files/Git/mingw64/libexec/git-core/git-gui--askpass'
Password for 'https://git push @github.com':
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/ClaudioCuervo/repoNotas.git/'

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git push https://github.com/ClaudioCuervo/repoNotas.git
Logon failed, use ctrl+c to cancel basic credential prompt.
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 6 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 323 bytes | 323.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/ClaudioCuervo/repoNotas.git
   98fab9f..f7a4b13  main -> main

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git branch claveSol

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git branch claveFa

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git branch sostenido

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git branch
  claveFa
  claveSol
* main
  sostenido

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git checkout claveSol
Switched to branch 'claveSol'

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveSol)
$ git push add
fatal: 'add' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveSol)
$ git pushhttps://github.com/ClaudioCuervo/repoNotas.git
error: cannot spawn git-pushhttps://github.com/ClaudioCuervo/repoNotas.git: Invalid argument

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveSol)
$ git push https://github.com/ClaudioCuervo/repoNotas.git
Logon failed, use ctrl+c to cancel basic credential prompt.
Total 0 (delta 0), reused 0 (delta 0)
remote:
remote: Create a pull request for 'claveSol' on GitHub by visiting:
remote:      https://github.com/ClaudioCuervo/repoNotas/pull/new/claveSol
remote:
To https://github.com/ClaudioCuervo/repoNotas.git
 * [new branch]      claveSol -> claveSol

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveSol)
$ git checkout claveFa
Switched to branch 'claveFa'

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveFa)
$ git push
fatal: The current branch claveFa has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin claveFa


Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveFa)
$ git push
fatal: The current branch claveFa has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin claveFa


Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveFa)
$ branch -d claveFa
bash: branch: command not found

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveFa)
$ git branch -D claveFa
error: Cannot delete branch 'claveFa' checked out at 'C:/Users/Alumno/Desktop/repoNotas'

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveFa)
$ git checkout claveSol
Switched to branch 'claveSol'

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveSol)
$ git branch -D claveFa
Deleted branch claveFa (was f7a4b13).

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveSol)
$ git add sol.txt

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveSol)
$ git add la.txt

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveSol)
$ git add -A

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveSol)
$ git commit -m "añadidos a la rama claveSol"
[claveSol 45dc8fa] añadidos a la rama claveSol
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 la.txt
 create mode 100644 sol.txt

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveSol)
$ git add -A

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveSol)
$ git push https://github.com/ClaudioCuervo/repoNotas.git
Logon failed, use ctrl+c to cancel basic credential prompt.
Ca5t1gad012
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/ClaudioCuervo/repoNotas.git/'

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveSol)
$ git push https://github.com/ClaudioCuervo/repoNotas.git
Logon failed, use ctrl+c to cancel basic credential prompt.
Ca5t1gad012
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 6 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 277 bytes | 277.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/ClaudioCuervo/repoNotas.git
   f7a4b13..45dc8fa  claveSol -> claveSol

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveSol)
$ git pull https://github.com/ClaudioCuervo/repoNotas.git
From https://github.com/ClaudioCuervo/repoNotas
 * branch            HEAD       -> FETCH_HEAD
Already up to date.

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveSol)
$ git checkout sostenido
Switched to branch 'sostenido'

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (sostenido)
$ git branch -m claveDo

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveDo)
$ git add -A

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveDo)
$ git push https://github.com/ClaudioCuervo/repoNotas.git
Logon failed, use ctrl+c to cancel basic credential prompt.
Ca5t1gad012
Total 0 (delta 0), reused 0 (delta 0)
remote:
remote: Create a pull request for 'claveDo' on GitHub by visiting:
remote:      https://github.com/ClaudioCuervo/repoNotas/pull/new/claveDo
remote:
To https://github.com/ClaudioCuervo/repoNotas.git
 * [new branch]      claveDo -> claveDo

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveDo)
$ git checkout master
error: pathspec 'master' did not match any file(s) known to git

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (claveDo)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git merge claveSol
Updating f7a4b13..45dc8fa
Fast-forward
 la.txt  | 0
 sol.txt | 0
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 la.txt
 create mode 100644 sol.txt

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git add -A

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git push https://github.com/ClaudioCuervo/repoNotas.git
Logon failed, use ctrl+c to cancel basic credential prompt.
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/ClaudioCuervo/repoNotas.git/'

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git push https://github.com/ClaudioCuervo/repoNotas.git
Logon failed, use ctrl+c to cancel basic credential prompt.
Total 0 (delta 0), reused 0 (delta 0)
To https://github.com/ClaudioCuervo/repoNotas.git
   f7a4b13..45dc8fa  main -> main


Alumno@PC13426 MINGW64 ~/desktop/repoNotas ((notasMusicales))
$ git push https://github.com/ClaudioCuervo/repoNotas.git
fatal: You are not currently on a branch.
To push the history leading to the current (detached HEAD)
state now, use

    git push https://github.com/ClaudioCuervo/repoNotas.git HEAD:<name-of-remote-branch>


Alumno@PC13426 MINGW64 ~/desktop/repoNotas ((notasMusicales))
$ git add -A

Alumno@PC13426 MINGW64 ~/desktop/repoNotas ((notasMusicales))
$ git push https://github.com/ClaudioCuervo/repoNotas.git
fatal: You are not currently on a branch.
To push the history leading to the current (detached HEAD)
state now, use

    git push https://github.com/ClaudioCuervo/repoNotas.git HEAD:<name-of-remote-branch>


Alumno@PC13426 MINGW64 ~/desktop/repoNotas ((notasMusicales))
$ git checkout main
Previous HEAD position was f7a4b13 añadidos los archivos
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git add -A

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git commit -m "tercer commit"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git push https://github.com/ClaudioCuervo/repoNotas.git
Logon failed, use ctrl+c to cancel basic credential prompt.
Everything up-to-date

Alumno@PC13426 MINGW64 ~/desktop/repoNotas (main)
$ git branch
  claveDo
  claveSol
* main
