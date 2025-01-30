# Cómo crear un repositorio remoto en github y cómo sincronizarlo con el repositorio local.

## 1. Crear un repositorio en GitHub.

1. Inicia sesión en GitHub.

2. Hacer clic en el icono de "__+__" y seleccionar " __New repository__ ".

3. Introducir un nombre para el repositorio.

4. Añadir una descripción (opcional).

5. Seleccionar la visibilidad: __Public__ o __Private__.

6. Hacer clic en "__Create repository__".

7. En la página de GitHub te mostrarán los comandos necesarios para vincularlo con el repositorio local.

## 2. Vincular un repositorio local al remoto.

1. Abrir el Git bash y dirigirse a la carpeta del repositorio.

2. Agregar el repositorio remoto con la URL copiada, un ejemplo de este: __git remote add origin https://github.com/henryandr/Prog_Eval_Template.git__.

3. Verificar que se haya agregado correctamente con el siguiente comando __git remote -v__.

4. Subir la información al repositorio remoto con el siguiente comando __git push origin main__.


