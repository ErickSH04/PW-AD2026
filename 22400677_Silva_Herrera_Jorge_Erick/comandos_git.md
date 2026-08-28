# Comandos de Git

## 1.- git init:
 
**Descripción del comando:** Crea un nuevo repositorio Git en el directorio actual

**Ejemplo real de uso:** Crear un repositorio: Entras a la carpeta de un proyecto y ejecutar git init para comenzar a controlar sus versiones.

## 2.- git clone: 

**Descripción del comando:** Copia un repositorio remoto a tu computadora, incluyendo su historial.

**Ejemplo real de uso:** Descargar un proyecto: git clone + url para obtener una copia del proyecto.

## 3.- git status:

**Descripción del comando:** Muestra el estado actual del repositorio y los archivos modificados, agregados o pendientes.

**Ejemplo real de uso:** Revisar cambios: Antes de hacer un commit se ejecuta git status para saber qué archivos han sido modificados. 

## 4.- git add:

**Descripción del comando:** Agrega archivos al área de preparación para incluirlos en el próximo commit.

**Ejemplo real de uso:**  Preparar un archivo: git add archivo.extension para indicar que quieres incluir ese archivo en el siguiente commit.

## 5.- git add .: 

**Descripción del comando:** Agrega todos los archivos modificados y nuevos del directorio actual al área de preparación.

**Ejemplo real de uso:**  Preparar varios cambios: Después de modificar archivos ejecutar el comando git add. para preparar dichos cambios.

## 6.- git commit:

**Descripción del comando:**  Guarda en el historial los cambios que fueron agregados al área de preparación.

**Ejemplo real de uso:**  Guardar un versión: git commit -m "agregar formulario de registro" para registrar una nueva versión del proyecto. 

## 7.- git log:  

**Descripción del comando:** Muestra el historial de commit realizados en el repositorio.

**Ejemplo real de uso:** Consultar versiones: Si ejecutas el comando git log podrás saber qué cambios se han realizado y quién los realizó. 

## 8.- git diff:

**Descripción del comando:**  Muestra las diferencias entre los cambios actuales y una versión anterior o el estado registrado.

**Ejemplo real de uso:** Revisar modificaciones: Antes de hacer commit, ejecutar git diff para comprobar exactamente qué líneas fueron cambiadas.

## 9.- git branch:

**Descripción del comando:**  Permite crear, consultar o administrar ramas del repositorio.

**Ejemplo real de uso:** Crear una rama: git branch + nombreRama, crea una rama para trabajar en nuevas funciones sin modificar directamente la principal.

## 10.- git switch:

**Descripción del comando:**  Permite cambiar entre ramas o crear y cambiar a una nueva rama.

**Ejemplo real de uso:** Cambiar rama: git switch + nombreRama, te lleva a la rama donde estás trabajando en una nueva función.

## 11.- git merge:

**Descripción del comando:**  Permite combinar los cambios de una rama con otra.

**Ejemplo real de uso:** Integrar una función: desde la rama principal, ejecutar git merge +  ramaNueva para incorporar a la rama principal los cambios realizados en la ramaNueva.

## 12.- git remote:

**Descripción del comando:**  Permite administrar las conexiones entre el repositorio local y repositorios remotos.

**Ejemplo real de uso:**  Agregar GitHub: git remote add origin + url, conectando un repositorio local a uno remoto.

## 13.- git fetch:

**Descripción del comando:** Descarga información y cambios del repositorio remoto sin incorporarlos automáticamente a la rama actual. 

**Ejemplo real de uso:** Consultar actualizaciones: git fetch origin, permite comprobar los cambios que existen en GitHub antes de decidir si integrarlos.

## 14.- git pull:

**Descripción del comando:**  Descarga los cambios del repositorio remoto sin incorporarlos automáticamente a la rama actual. 

**Ejemplo real de uso:**Actualizar el proyecto: git pull origin main, obtiene los últimos cambios de la rama principal desde el repositorio remoto.

## 15.- git push:

**Descripción del comando:** Envía los commits locales a un repositorio remoto. 

**Ejemplo real de uso:** Subir los cambios: git push origin main, publica los commits realizados localmente en la rama principal.

## 16.- git reset:

**Descripción del comando:**  Permite deshacer cambios en el historial o retirar archivos del área de preparación, dependiendo de las opciones utilizadas.

**Ejemplo real de uso:** Quitar un archivo del área de preparación: git reset + nombre del archivo, restaura el archivo a su estado registrado y elimina las modificaciones locales no guardadas. 

## 17.- git restore:

**Descripción del comando:** Permite restaurar archivos a una versión anterior, descartando cambios locales.

**Ejemplo real de uso:**  git restore + nombreArchivo, restaura el archivo a su estado registrado y elimina modificaciones locales no guardadas-

## 18.- git stash:

**Descripción del comando:** Guarda temporalmente cambios que todavía no deseas confirmar mediante un commit.

**Ejemplo real de uso:** Cambiar de tarea: Tienes cambios sin terminar y necesitas cambiar de rama, Al ejecutar el comando git stash guardas los cambio temporalmente.

## 19.- git tag:

**Descripción del comando:**  Crea etiquetas que permiten identificar versiones específicas del proyecto.

**Ejemplo real de uso:**  Marcar una versión: git tag + nombreVersion, identifica el commit actual con el nombre que se la haya dado a la versión que se le haya puesto en la etiqueta.

## 20.- git rm:

**Descripción del comando:**  Elimina archivos del proyecto y registra su eliminación para el siguiente commit.

**Ejemplo real de uso:**  Eliminar un archivo: git rm + nombreArchivo, eliminar el archivo y prepara su eliminación para el próximo commit.
