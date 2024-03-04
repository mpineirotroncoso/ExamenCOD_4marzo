# Pasos examen
1. `git checkout 7ee11512` volver al commit anterior de interface 
2. `git reset --hard` deshacer ultimo commit de la rama interface 
3. `git checkout interface` por siacaso
4. `git merge --squash datos` merge datos a interface en un solo commit
5. `git checkout main` cambiar a la rama main

6. Edito el .gitignore
7. `git merge --squash interface` merge interface a main en un solo commit
8. `git commit -m "Version 1.0"` Commit en main

9. `git tag -a v1.0 db2d965a` añadir tag 1.0 al ultimo commit de main
10. `git push origin main` Hacer push de la rama main
11. `git push origin v1.0` Hacer push del tag
12. Añadir un artifact en `Project structure`
13. Compilar el jar en `Build > Build artifacts`
14. Hacer la release en GitHub usando el tag `v1.0` creado anteriormente, subir el .jar
15. Listo!