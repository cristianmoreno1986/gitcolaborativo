# Archivos de configuración


## .gitkeep cuando quiero guardar una carpeta vacia

<br>

## .gitignore sirve para descartar archivos que no queremos subir a GIT

<br>

# GIT LOG

### Ayuda de git log
```sh
git log --help
``` 

### Muestra versión completa
```sh
git log
```

### Muestra versión corta
```sh
git log --oneline
```

### Muestra una cantidad de commit seleccionado
```sh
git log <cantidad-commit>
git log -3
```

### Busqueda por fechas
```sh
git log --since="2022-05-01" # Para buscar en una fecha determinada
git log --after="2022-07-03" # Para buscar despues de la fecha determinada
git log --before="2022-07-08" # Pata buscar antes de una fecha determinada
git log --since"<Fecha>" --before="<Fecha>" --oneline -4 # Para busquedas combinadas
```

<br>

# GIT STASH
Es una pila que almacena el working directory
Permite almacenar el working directory para seguir trabajar
Los stash que creo solo están en la copia local

### Creo un stash
```sh
git stash
```

### Ver los stash
```sh
git stash list
```

### Recuperar el ultimo stash
```sh
git stash pop
```

### Para borrar un stash
> Borrar el último stash
```sh
git stash drop
```

>Borrar un stash particular
```sh
git stash drop  stash@{0}
```

### Aplicar cualquier stash de los que tengo
```sh
git stash apply stash@{1}
```


# GIT BRANCH
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
