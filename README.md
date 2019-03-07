# configure-github-linux
Configuración de Git/GitHub y comandos mas comunes desde la terminal en Linux.

<br><h2>Instalación desde Manjaro Linux</h2>

    sudo pacman -Syu git
        
<br><h2>Recordando los tres estados de Git</h2>

<img src="https://github.com/kabirna/configure-github-linux/raw/master/images/3estados.png" width="320px">


<br><h2>1. Creando repositorios</h2>

Crear una carpeta e inicializarla como un nuevo repositorio:

    git init [directorio]
    
Incializar la carpeta actual como un repositorio

    git init
    
Por defecto se va a inicializar en la rama <b>master</b>. Los datos del repositorios se almacenan dentro de la carpeta oculta .<b>git</b> que se crea automáticamente al inicializarlo.

Borrar de la carpeta actual el repositorio

    rm -rf .git
    
<br><h2>2. Agregando archivos al staging area</h2>    

Agregando el archivo especificado al staging area

    git add [archivo]

Podemos agregar todos los archivos modificados al staging area en un solo paso
    
    git add -A
    
Eliminando un archivo especifico del staging area

    git rm --cached [archivo]
    
Eliminando un archivo del staging area y del working directory

    git rm -f [archivo]

<b>Untracked files</b>
En git, todos los archivos que estan en el working directory pero que no han sido explicitamente agregados (git add) son marcados como "untracked" (por defecto). Esto significa que existen, pero git aún no esta monitoreando cambios en ellos.

