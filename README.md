# sebass
             COMO REGISTRARSE A GIT
--------------------------------------------------
como registrarte a git:
- git config --global user.name "FaridHI"
- git config --global user.email "1121041@senati.pe"
- git config --list

--------------------------------------------------
              COMPLEMENTOS DE CODIGOS
--------------------------------------------------
para eliminar un origin:
- git remote remove origin
- git remote set-url origin [new-url]

---------------------------------------------------

para agregar archivos:
- git status
- echo 'My Project' > README
- git push

--------------------------------------------------

para guardar cambios:
- git status
- git add .
- git commit 
- presionamos 'I'
- Esc ':wq' Enter
- git status
- git push

-------------------------------------------------

para eliminar archivos:
- rm 'nombre del archivo'
- git status
- git rm 'nombre del archivo'
- git status
- git commit -m 'elimine el archivo'
- git push

-------------------------------------------------

para cambiar el nombre de los archivos:
- git mv 'nombre antiguo.tipo de archivo' 'nuevo nombre'
- git status
- git commit
- git push

