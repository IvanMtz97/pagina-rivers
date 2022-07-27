- Como cambiarse de rama:
`git checkout NOMBRE DE RAMA`

- Como hacer un commit:
Paso 1: `git add .` Agregar cambios para subir
Paso 2: `git commit -m "Mensaje del commit"` Crear un commit (paquete de cambios) con un mensaje
Paso 3: `git push origin NOMBREDERAMA` Subir cambios a la rama especificada del repositorio

- Como bajar cambios de una rama:
Paso 1: `git checkout NOMBREDERAMA` Cambio de rama
Paso 2: `git pull origin NOMBREDERAMA` Bajar cambios de rama del repositorio

- Como guardar cambios temporales para bajar cambios o cambiarse de rama:
Paso 1: `git stash` Guardar cambios en una bolsa temporal
Paso 2: Cambiarse de rama o hacer pull
Paso 3: `git stash apply` Regresar cambios de la bolsa temporal