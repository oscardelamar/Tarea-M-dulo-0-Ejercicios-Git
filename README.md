# *COMANDOS BÁSICOS DE LINUX*



pwd: Me permite conocer la ruta actual (Donde estoy ubicado).

ls: Ver los elementos de la carpeta donde estoy ubicado.

clear: Limpiar la pantalla.

ls -la: Ver detalle de la información con los permisos que tienen esos recursos.

mkdir: Crear un directorio.

rm – rf [nombre directorio]: Borrar de forma forzosa el recurso.

cd [carpeta]: Dirigirme a una carpeta deseada.

cd .. : Devolverme a una ruta o carpeta anterior.

touch [NombreNuevoArchivo] : Crear un archivo de cualquier tipo distinto a una carpeta.

nano [NombreNuevoArchivo] : Crear un archivo.

cat [NombreNuevoArchivo] : Mostrar los datos de un archivo.



# *COMANDOS GIT*



git config --global user.name "Nombre Completo": nombre para el registro

git --global user.email "email@example.com": con este comando se registra el correo electrónico de la cuenta git

git --global -e: para validad la información de configuración

git init: Inicializa el repositorio (esto va a crear una carpeta oculta .git dentro del proyecto

git add -A: Agrega todos los archivos

git add . : Prepara los archivos para el commit

git add <nombreArchivo>: Para agregar un solo archivo

git branch -M main

git commit -m <descripción de los cambios>: crea un commit 

git remote add origin <URL del repositorio>: Agrega la URL del repositorio

git push origin <Raman main>: Entrega los cambios

git pull origin <Raman main>: Baja los cambios

git status: Muestra la lista de archivos con cambios desde el último commit y los que van a ser incluidos en el siguiente commit
