# Extensiones VSC

## Obligatorias
* Material Icon Theme
* Live Server

## Opciones
* GitLens

# Workflow normal, cuando ya tenemos el repositorio creado

1. git status
2. git add <nombre-archivo>
3. git commit -m "Mensaje del commit descriptivo"
4. git push

# Configurar remoto en un repo local

1. git remote add origin https://github.com/mlapeducacionit/nuevo-repo.git
2. git push -u origin main

# Ayuda git en local

```sh
git --help commit
git --help status
```

# Para comparar los cambios WD con respecto al repositorio (Al último commit)

```sh
git diff
```

# GIT LOG

## Para ver el log resumido

```sh
git log --oneline
```

## Cantidad especifica de commits
```sh
git log --oneline -2
```

## Commits entre fechas

```sh
git log --since="2021-05-01"
git log --after="2021-05-01"
git log --before="2021-05-01"
git log --after="2020-05-01" --before="2021-05-01" --oneline
```

# GIT BRANCH (RAMAS)

## Listar las ramas

```sh
git branch
```

## Para crear la ramas

```sh
git branch <nombre-rama>
```

## Para cambiar entre ramas

```sh
git switch <nombre-rama>
```