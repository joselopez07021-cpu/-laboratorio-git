# -laboratorio-git
Laboratorio 2, se muestra pagina web informativa sobre GIT. Fomenta la utilización del mismo.
# Laboratorio #2 - Git

## Descripción
Este laboratorio tiene como objetivo practicar el uso de Git y GitHub, incluyendo el manejo de commits, ramas, merges y control de versiones en un proyecto web.

## Comandos utilizados

### Configuración inicial
git config --global user.name "Tu Nombre"
git config --global user.email "Tu correo"

### Inicialización del repositorio
git init

### Primer commit
git add .
git commit -m "Estructura inicial del proyecto"

### Ver historial
git log --oneline

### Crear y cambiar de rama
git checkout -b desarrollo

### Agregar cambios
git add .
git commit -m "Agrega contenido en index"

### Unir ramas
git checkout main
git merge desarrollo

### Ver diferencias
git diff

### Commit temporal
git add .
git commit -m "Cambio temporal"

### Eliminar commit
git reset --hard HEAD~1

### Recuperar commit
git reflog
git reset --hard bf61da7

### Crear .gitignore
git add .gitignore
git commit -m "Agrega gitignore"

### Conectar con GitHub
git remote add origin https://github.com/joselopez07021-cpu/laboratorio-git.git

### Subir proyecto
git push -u origin main

### Crear rama login
git checkout -b login

### Agregar login
git add .
git commit -m "Agrega login"

### Subir rama
git push origin login

### Merge de ramas
git checkout main
git merge login

### Sincronización
git pull origin main --allow-unrelated-histories
git push origin main