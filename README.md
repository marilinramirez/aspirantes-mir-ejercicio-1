1.Abrir la consola e imprimir la ubicación actual.
pwd 

2.Crear una carpeta llamada ejercicios en el escritorio desde la consola, si no estas en la ruta del escritorio, muevete a ella.

cd Desktop
mkdir ejercicios

3.Cambiar la ubicación a la nueva carpeta que crearon.
cd ejercicios

4.Abrir la carpeta con VSCode.
code . 

5.En VSCode crear una carpeta ejercicio1.
cree la carpeta ejercicio1 y guarde los cambios

6.Crear un archivo llamado README.md (vacío) dentro de la carpeta ejercicio1.
cd ejercicio1
touch README.md

7.Configurar nombre e email globalmente en git.
git config --global user.name "marilin"
git config --global user.email "marilin.ramirez1222@gmail.com"

8.Inicializar el repositorio de git desde la línea de comandos desde la carpeta ejercicios.
git init

9.Crear un primer commit con el mensaje “Versión Inicial”.
git commit -m "version inicial"
