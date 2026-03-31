# Repo-teste

Alterar

Todos os passos realizados:

Usuario@DESKTOP-IT9PK95 MINGW64 ~/projects_facul/atividade_Eron
$ mkdir atividade_Eron

Usuario@DESKTOP-IT9PK95 MINGW64 ~/projects_facul/atividade_Eron
$ history | grep git > history.txt

Usuario@DESKTOP-IT9PK95 MINGW64 ~/projects_facul/atividade_Eron
$ Recentes | grep git > history.txt
bash: Recentes: command not found

Usuario@DESKTOP-IT9PK95 MINGW64 ~/projects_facul/atividade_Eron
$ history | grep git > history.txt

Usuario@DESKTOP-IT9PK95 MINGW64 ~/projects_facul/atividade_Eron
$ git config --global user.name
Chrystian de Almeida Silva

Usuario@DESKTOP-IT9PK95 MINGW64 ~/projects_facul/atividade_Eron
$ git clone git@github.com:ESChrystian/Repo-teste.git
Cloning into 'Repo-teste'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

Usuario@DESKTOP-IT9PK95 MINGW64 ~/projects_facul/atividade_Eron
$ cd Repo-teste/

Usuario@DESKTOP-IT9PK95 MINGW64 ~/projects_facul/atividade_Eron/Repo-teste (main)
$ code .

Usuario@DESKTOP-IT9PK95 MINGW64 ~/projects_facul/atividade_Eron/Repo-teste (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

Usuario@DESKTOP-IT9PK95 MINGW64 ~/projects_facul/atividade_Eron/Repo-teste (main)
$ git add .

Usuario@DESKTOP-IT9PK95 MINGW64 ~/projects_facul/atividade_Eron/Repo-teste (main)
$ git commit -m "Insere alterações"
[main ebeea26] Insere alterações
 1 file changed, 3 insertions(+), 1 deletion(-)

Usuario@DESKTOP-IT9PK95 MINGW64 ~/projects_facul/atividade_Eron/Repo-teste (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 293 bytes | 293.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:ESChrystian/Repo-teste.git
   fee34ac..ebeea26  main -> main

Usuario@DESKTOP-IT9PK95 MINGW64 ~/projects_facul/atividade_Eron/Repo-teste (main)
$
