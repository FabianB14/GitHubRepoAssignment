Fabia@FabeSurface MINGW64 ~
$ mkdir GitHubRepoAssignment

Fabia@FabeSurface MINGW64 ~
$ cd githunrepoassignment
bash: cd: githunrepoassignment: No such file or directory

Fabia@FabeSurface MINGW64 ~
$ cd GitHubRepoAssignment

Fabia@FabeSurface MINGW64 ~/GitHubRepoAssignment
$ git init
Initialized empty Git repository in C:/Users/Fabia/GitHubRepoAssignment/.git/

Fabia@FabeSurface MINGW64 ~/GitHubRepoAssignment (master)
$ touch readme.md

Fabia@FabeSurface MINGW64 ~/GitHubRepoAssignment (master)
$ vi readme.md

Fabia@FabeSurface MINGW64 ~/GitHubRepoAssignment (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        readme.md

nothing added to commit but untracked files present (use "git add" to track)

Fabia@FabeSurface MINGW64 ~/GitHubRepoAssignment (master)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

Fabia@FabeSurface MINGW64 ~/GitHubRepoAssignment (master)
$ git add readme.md
warning: LF will be replaced by CRLF in readme.md.
The file will have its original line endings in your working directory.

Fabia@FabeSurface MINGW64 ~/GitHubRepoAssignment (master)
$ git commit
[master (root-commit) f587e5d] no entry on line 5
 1 file changed, 1 insertion(+)
 create mode 100644 readme.md

Fabia@FabeSurface MINGW64 ~/GitHubRepoAssignment (master)
$

Fabia@FabeSurface MINGW64 ~/GitHubRepoAssignment (master)
$ git remote add origin https://github.com/FabianB14/GitHubRepoAssignment.git

Fabia@FabeSurface MINGW64 ~/GitHubRepoAssignment (master)
$ git push -u origin master
fatal: HttpRequestException encountered.
   An error occurred while sending the request.
Username for 'https://github.com': FabianB14
043Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 273 bytes | 273.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/FabianB14/GitHubRepoAssignment.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

Fabia@FabeSurface MINGW64 ~/GitHubRepoAssignment (master)
$

