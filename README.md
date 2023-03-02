1.	Abrir la consola e imprimir la ubicación actual.
 pwd
2.	Crear una carpeta llamada ejercicios desde la consola.
 mkdir ejercicios
3.	Cambiar la ubicación a la nueva carpeta que crearon.
 cd ejercicios
4.	Abrir la carpeta con VSCode.
 
5.	En VSCode crear una carpeta ejercicio1.
 mkdir ejercicio1
 ls => para ver que la carpeta se creo.
6.	Crear un archivo llamado README.md (vacío) dentro de la carpeta ejercicio1.
 touch README.md
7.	Configurar nombre e email globalmente en git.
 $ git config --global user.name
 $ git config --global user.email
 $ git config -l => para verificar que quedaron configurados
 
8.	Inicializar el repositorio de git desde la línea de comandos desde la carpeta ejercicios.
 git init
9.	Crear un primer commit con el mensaje “Versión Inicial”.
 git add .
 git commit -m 'Version Inicial'
10.	Agregar al README.md los comandos que ejecutaron en cada paso.
add