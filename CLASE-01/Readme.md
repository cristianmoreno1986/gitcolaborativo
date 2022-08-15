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














