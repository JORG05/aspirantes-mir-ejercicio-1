1-abrimos la consola, imprimimos la ubicación con el comando "pwd"
 2- nos colocamos en el escritorio con el comando "cd Deskop\". Luego creamos una carpeta llamada ejercicios con el comando "mkdir Ejercicios"
3. cambiamos la ubicación a la carpeta creada con el comando "cd Ejercicio"
4- Abrimos la carpeta con VsCode con el comando "code ."
5- creamos una carpeta llamada "ejercicio1" en visual code, dando click en el icono "new folder" y colocamos el nombre
6- creamos un archivo vacio llamado "README.md" en la carpeta "ejercicio1" dando click en el icono "New file" y lo nombramos
7- abrimos la consola de "Git bash", digitamos el comando "git config --global user.name "Juan"" para configuar el nombre de usuario global, y el comando "git config --global user.email "osvaldorada17@gmail.com"
8- inicializamos el repositorio  de git con el comando"git init" desde la carpeta ejercicios
9- creamos el primer commit con los comandos "git add ." y "git commit -m 'Version Inicial'"
10- utilizamos el comando "code ." para abrir visual code y posteriormente, agregamos esta lista de comandos utilizados al archivo vacio "README.md"
11-  creamos el el segundo commit con los comandos "git add ." y "git commit -m 'Agrega solución primer ejercicios'"
12-creamos un repositorio remoto en Git Hub para publicar nuestro repositorio local. luego digitamos "git remote add origin https://github.com/JORG05/aspirantes-mir-ejercicio-1.git", para configurar el repositorio remoto despues para sincronizar el repositorio local con el remoto digitamos "git branch -M main" y por ultimo git push "-u origin main"