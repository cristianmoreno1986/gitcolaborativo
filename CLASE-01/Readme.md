# GIT

## Instalaciones necesarias

* https://cmder.net/
* https://code.visualstudio.com/
* https://git-scm.com/
* https://github.com/

## Markdown

## Uso de consola

* ls - Listar directorios
* pwd - Saber en el directorio en el que estoy
* cd - Cambiar directorios
* cd <directorio>
* cd .. - Salgo de directorio
* clear - Limpiar consola
* mkdir - Creo directorios ejm.
```sh
mkdir <nombre-carpeta>
```
* touch - Crea archivo ejm.
```sh
touch <nombre-archivo>
```
* rm - Borrar archivos
* rm -rf - Borrar directorios
* Tirar múltiples comandos en una línea ejm.
```sh
touch index.min.js && mkdir css js && git init
```

## Uso de GIT inicial

<br>

### Configuración inicial

<br>

### Verificar que versión de GIT tengo
```sh
git --version
```

<br>

#### Configurar GIT usuario global
```sh
git config --global user.name "Cristian Moreno C"
git config --global user.email "cristian.moreno1986@outlook.com"
```

#### Configurar GIT usuario local por repositorio
```sh
git config --local user.name "Cristian Moreno C"
git config --local user.email "cristian.moreno1986@outlook.com"
```

### Configurar GIT editor predeterminado
```sh
git config --global core.editor "code --wait"
git config --global core.editor "nano"
```

### Cofiguración GIT mostrar
```sh
git config --list
```

### Configuración GIT modificar en el editor
```sh
git config --global -e
git config --local -e
```

<br>

### Crear repositorio GIT
```sh
git init
```

### Agrego archivos al stage area o index
```sh
git add <nombre-archivo>
git add . # para agregar todos los archvios
git add *.exe # para agregar los archivos que terminan en .exe
git add *.js # para agregar los archivos que terminan en .js
```

### Puedo hacer un commit (saco foto/snapshot)
```sh
git commit # me abre el editor por defecto que tengo configurado
git commit -m "mensaje descritivo de lo que contiene el commit"
```

### Ver la historia, listar commits
```sh
git log # para mostrar los log de forma detallada
git log --oneline # para mostrar los log de forma resumida
```

### Para quitar del stage area un archivo 
```sh
git rm --cache <nombre-archivo>
```

### Para ver las diferencias entre el working directory contra lo que tengo en el repo
```sh
git diff <nombre-archivo>
```












