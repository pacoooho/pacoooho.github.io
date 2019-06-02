paco@paco:~/Descargas/MOOCLinuxGithub/pacoooho.github.io$ cat readme
cat: readme: No existe el archivo o el directorio
paco@paco:~/Descargas/MOOCLinuxGithub/pacoooho.github.io$ git status
En la rama master
Cambios no preparados para el commit:
  (use «git add <archivo>...» para actualizar lo que se confirmará)
  (use «git checkout -- <archivo>...» para descartar cambios en el directorio de trabajo)

        modificado:    README.md

no hay cambios agregados al commit (use «git add» o «git commit -a»)
paco@paco:~/Descargas/MOOCLinuxGithub/pacoooho.github.io$ git add .
paco@paco:~/Descargas/MOOCLinuxGithub/pacoooho.github.io$ git status
En la rama master
Cambios para hacer commit:
  (use «git reset HEAD <archivo>...» para sacar del stage)

        modificado:    README.md

paco@paco:~/Descargas/MOOCLinuxGithub/pacoooho.github.io$ git commit -m "Cambio en README.md"
[master 6842737] Cambio en README.md
 1 file changed, 1 insertion(+), 1 deletion(-)
paco@paco:~/Descargas/MOOCLinuxGithub/pacoooho.github.io$ git push origin master
Username for 'https://github.com': pacoooho
Password for 'https://pacoooho@github.com':
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 395 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/pacoooho/pacoooho.github.io.git
   342e852..6842737  master -> master
paco@paco:~/Descargas/MOOCLinuxGithub/pacoooho.github.io$ ^C
paco@paco:~/Descargas/MOOCLinuxGithub/pacoooho.github.io$