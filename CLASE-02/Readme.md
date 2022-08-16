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




