# **    PRIMERA SESION DE GITHUB**

Pasos a seguir:

1. Crear un repositorio en github.
2. El repositorio se encuentra vacío.

   * git clone https:nombre_del_repositorio.git
   
4. Ubicarse dentro del directorio con el nombre del repositorio.
5. Desarrollar el proyecto o generar los archivos.
6. Dentro del directorio con el nombre del repositorio, utilizar los siguientes comandos:
   
    a.  git init

    b.  git add nombre_archivo.txt

    c.  git status

    d.  git commit -m "Mi primer commit"

    e.  git push


7. Refrescar la pagina del repositorio.
8. Crear un archivo llamado README.md
9. Editar el archivo respetando la sintaxis MarkDown y repetir el paso 6 para actualizar

# **    2DO METODO PARA CREAR Y ACTUALIZAR UN REPOSITORIO POR PRIMERA VEZ**

1. Creamos el directorio

2. Generamos nuestros archivos o codigo. En nuestro podemos editar un archivo llamado ejemplo.md.

3. Utilizamos el comando git init

4. Luego el comando que vincula el link con el repositorio:

  * git remote add origin https://github.com/sebastianVP/git_23102024_test.git
    
5. Para verificar el estado: git status

6. Luego, para añadir al area de stagging: git add ejemplo.md

7. Para agregar al respositorio de manera local y añadir un identificado usamos el comando: git commit -m "1er Comentario"

8. Luego el comando git status para verificar el estado.

9. Luego para subir nuestros cambios: git push

10. Aqui se genera un mensaje de error y esto solo ocurre una vez, por ser la primera vez debemos colocar el siguiente comando. git push --set-upstream origin master
