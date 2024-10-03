# Clase 06 - Bootcamp

## Repaso GIT

# creo el repositorio de GIT

```sh
git init
```

# Listo el estado de los archivos

```sh
git status
```

# Haciendo un commit

1. Agrego el àrea de staging, los archivos que necesito que formen parte del commit

```sh
git add <nombre-archivo>
git add <nombre-archivo> <nombre-archivo> <nombre-archivo>
git add . # agrega todos los archivos que tengo en el working directory (WD)
```

2. hago el commit

```sh
git commit -m "mensaje descriptivo"
```

# Cambiar el editor por nano

```sh
git config --global core.editor nano
git config --global core.editor "code --wait"
```

# agregar un remoto a mi repositorio loc

```sh
git remote add origin <url-al-repo-remoto>
git remote add origin git remote add origin https://github.com/GiannMlclz/Repaso-ramas.git
```

# Para ver si se agrego el repo remoto

```sh
git remote -v
```

# Subo el remoto el repositorio local

```sh
git push -u origin main # la primera vez
git push
```
