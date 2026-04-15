# -laboratorio-git
Laboratorio 2, se muestra pagina web informativa sobre GIT. Fomenta la utilizacion del mismo.

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

## Evidencias

### Creación Login
![Creación Login](<api/src/main/resources/pantallazos/Creación Login.png>)

### Evidencia GitHub
![Evidencia GitHub](<api/src/main/resources/pantallazos/evidencia GitHub.png>)

### Gitignore
![Gitignore](<api/src/main/resources/pantallazos/gitignore.png>)

### Creacion de pagina
![Creacion de pagina](<api/src/main/resources/pantallazos/Creacion de pagina.png>)

### Primer Commit
![Primer Commit](<api/src/main/resources/pantallazos/primer commit.png>)

### Evidencia 1
![Evidencia 1](<api/src/main/resources/pantallazos/evidencia 1.png>)

### Evidencia 2
![Evidencia 2](<api/src/main/resources/pantallazos/evidencia 2.png>)

### Union de Ramas
![Union de Ramas](<api/src/main/resources/pantallazos/Union de ramas.png>)

### Evidencia 3
![Evidencia 3](<api/src/main/resources/pantallazos/evidencia 3.png>)

### Evidencia 4
![Evidencia 4](<api/src/main/resources/pantallazos/evidencia 4.png>)

### Evidencia 5
![Evidencia 5](<api/src/main/resources/pantallazos/evidencia 5.png>)

### Evidencia 6
![Evidencia 6](<api/src/main/resources/pantallazos/evidencia 6.png>)

### Evidencia 7
![Evidencia 7](<api/src/main/resources/pantallazos/evidencia 7.png>)

### Evidencia 8
![Evidencia 8](<api/src/main/resources/pantallazos/evidencia 8.png>)

### Evidencia 9
![Evidencia 9](<api/src/main/resources/pantallazos/evidencia 9.png>)

### Evidencia 10
![Evidencia 10](<api/src/main/resources/pantallazos/evidencia 10.png>)

### Evidencia 11
![Evidencia 11](<api/src/main/resources/pantallazos/evidencia 11.png>)

### Evidencia 12
![Evidencia 12](<api/src/main/resources/pantallazos/evidencia 12.png>)

### Evidencia 13
![Evidencia 13](<api/src/main/resources/pantallazos/evidencia 13.png>)

### Evidencia 14
![Evidencia 14](<api/src/main/resources/pantallazos/evidencia 14.png>)

### Evidencia 15
![Evidencia 15](<api/src/main/resources/pantallazos/evidencia 15.png>)

### Merge
![Merge](<api/src/main/resources/pantallazos/Merge.png>)


### Cambios Finales
![Cambios Finales](<api/src/main/resources/pantallazos/Cambios Finales.png>)
