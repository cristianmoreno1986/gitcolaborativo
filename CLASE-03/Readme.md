# GIT BRANCH (Cont...)

### Para crear una rama
```sh
git branch <nombre-rama>
```

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