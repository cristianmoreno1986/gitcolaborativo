# GIT BRANCH (Cont...)

### Para crear una rama
```sh
git branch <nombre-rama>
```

### Listar ramas
```sh
git branch
```

### Para cambiar de rama
```sh
git switch <nombre-rama>
```

### Para eliminar una rama
```sh
git branch -d <nombre-rama>
```

### Para forzar la eliminación de una rama
```sh
git branch -D <nombre-rama>
```

## GIT MERGE (Fusiones de ramas)

Combinar los cambios de la rama actual con la rama especificada
<br>
**IMPORTANTE**: Es que siempre tengo que estar en la rama que quiero recibir los cambios. 

Ej: Si quiero traerme a **master** lo que tengo en **dev**, tengo que estar posicionado sobre la rama **master**
```sh
    git merge <nombre-rama>
    git merge dev
```

### TIPOS DE MERGE 

* Fast-Fodward (No hay ningun conflicto, se hace en forma automatica)
* Recursivo - Uniones automaticas (Tampoco hay conflicto) - Trabaja con algoritmo
* Manual - (Donde hay conflictos - Y acá es cuando hay que junstarse para resolver el conflicto)

<br>

# GIT ALIAS
```sh
git config --global alias.lg "log --oneline --decorate --all --graph"
git config --global alias.set "config --global"
git config --global alias.s "status --short"
```

## Mostrar parametros incluidos en la configuración
```sh
git config --global --get-regexp alias
git config --global --get-regexp user
```