# Cómo crear un repositorio local con git bash.

## 1. Abrir git bash.

Asegurarse de estar en el directorio donde se quiere crear el repositorio. Si no, navegar al directorio con el comando __cd__.

## 2. Inicializar el repositorio.

Se usa el comando __git init__ para crear un repositorio vacío en el directorio actual.
Esto genera un subdirectorio oculto llamado .git que contiene toda la información de control de versiones.

## 3. Agregar archivos a la zona "stage".

Usando el comando __git add__ puedes agregar los archivos del directorio a la zona de "stage" para que Git los rastree.

## 4. Confirmar los cambios en el repositorio.

Realizar un commit para guardar los cambios en el historial del repositorio con el comando __git commit -m""__. Es importante añadir un mensaje que describa los cambios realizados.

## 5. Observar el historial de commits.

Usando el comando __git log__ podemos ver el autor, correo, fecha, hora y la descripción del commit.

# Notas importantes.

## 1. Configurar nombre de usuario y correo electrónico.

Antes de realizar commits se debe configurar estos usando los comandos __git config --global user.name__ y __git config --global user.email__.

## 2. Verificar el estado del repositorio.

Con el comando __git status__ podemos ver que archivos han sido modificados, añadidos a la zona de "stage", o archivos sin rastrear.

# Imagenes de ejemplo.

![Git add y commit](<../images/git add y commit.png>)
![Repositorios modificados y commit](<../images/repo local y commit.png>)
![Git log y commit](<../images/git log y commit.png>)
![Commit fallido y nuevo commit](<../images/commit fallido y nuevo commit.png>)
![Cambio en gitignore y commit](<../images/gitignore cambio y commit.png>)