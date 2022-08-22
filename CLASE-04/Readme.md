# GIT ADD REPASO

### Para agregar un solo archivo
```sh
git add <nombre-archivo>
```

### Una vez que se utiliza el git add y se requiere sacarlo del stage area
```sh
git restore --staged <nombre-archivo>
```

### Para agregar un archivo y hacer un commit
```sh
git commit -a -m "Mensaje"
```

### GIT add patch
Me permite separar de un mismo archivo. Partes en diferentes commit
```sh
git add --patch
git add -p
```
> Comandos posiblres <br>
y: si <br>
n: no <br>
s: split

# APUNTADORES

## Estaticos

RAMAS <br>
TAGS <br>
REMOTOS

## Dinamicos

HEAD

# GIT TAG
Identificar puntos claves de mi desarrollo
```sh
git tag -a v0.1.0 <hash> -m "Mensaje"
```

Para subir los tags
```sh
git push <remote> <tag>
```

Para listar los tags
```sh
git tag
```

Para mostrar que contiene el tag de forma detallada
```sh
git show <tag>
```

