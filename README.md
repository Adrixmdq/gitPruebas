# gitPruebas
una prueba de git


# clonado de repositorio
git clone https://github.com/Adrixmdq/gitPruebas.git

# git status
Your branch is up to date with 'origin/main'.
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

# agregue dos md
PS D:\Cursos\Iplyc\git\Tp\gitPruebas> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ArchvoparaAdd.md
        archivoParaNosubir.md
        
# agrego uno + status
git add ArchvoparaAdd.md
PS D:\Cursos\Iplyc\git\Tp\gitPruebas> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   ArchvoparaAdd.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        archivoParaNosubir.md

# comiteo hasta ahora todo local
git commit -m "subo las modificaciones"
[main 7760298] subo las modificaciones
 1 file changed, 1 insertion(+)
 create mode 100644 ArchvoparaAdd.md

 # PS D:\Cursos\Iplyc\git\Tp\gitPruebas> git push
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 326 bytes | 326.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Adrixmdq/gitPruebas.git
   915ae86..7760298  main -> main
