# Comandos utiles de GIT
1. git init                         (inicializar)
2. git add .                        (agregar)
3. git reset .                      (resetear)
4. git commit -m "primer_commit"    (colocar nombre)
5. git checkout -- .                (volver al ultimo commit)
6. git log                          (muestras todos los commits sales con la letra Q)
7. git commit --amend         (Editar el nombre del ultimo commit (tecla i) para salir Esc + :wq!)
8. git checkout -b rama-heroes      (crear una nueva rama ejemplo:rama-heroes)
9. git branch                       (ver cuantas ramas tengo)
10. git checkout master             (para volver a la rama principal) 
11. git merge rama-heroes           (incluir ramas secundarias a rama master)  
12. git branch -d rama-heroes       (para eliminar las ramas que ya no nos sirven)

# PARA HACER EL REPLIEGUE EN UN REPOSITORIO EXTERNO COMO EJEMPLO GIBHUB
  COPIAR LOS COMANDOS 
  1. git remote add origin https://github.com/Antonmarchitec/ProyectoDePruebaGIT.git
  2. git branch -M main
  3. git push -u origin main

# CUANDO SE QUIERE EDITAR EN EL REPOSITORIO SOLO SERA 
  1. git push
  2. git commit -am "mensaje"     (reemplaza al git add . // git commit -m "comentario")