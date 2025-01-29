Cómo crear un repositorio local con git bash.

1. Abrir git bash.

    Asegurarse de estar en el directorio donde se quiere crear el repositorio. Si no, navegar al directorio con el comando cd.

2. Inicializar el repositorio.

    Se usa el comando git init para crear un repositorio vacío en el directorio actual.
    Esto genera un subdirectorio oculto llamado .git que contiene toda la información de control de versiones.

3. Agregar archivos a la zona "stage".

    Usando el comando git add podemos agregar los archivos del directorio a la zona de "stage" para que Git los rastree.

4. Confirmar los cambios en el repositorio.

    Realizar un commit para guardar los cambios en el historial del repositorio con el comando git commit -m"". Es importante añadir un mensaje que describa los cambios realizados.

Notas importantes.

1. Configurar nombre de usuario y correo electrónico.

    Antes de realizar commits se debe configurar estos usando los comandos git config --global user.name y git config --global user.email.

2. Verificar el estado del repositorio.

    Con el comando git status podemos ver que archivos han sido modificados, añadidos a la zona de "stage", o archivos sin rastrear.