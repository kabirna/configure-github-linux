# configure-github-linux
Configuración de Git/GitHub y comandos mas comunes desde la terminal en Linux.

<br><b>Instalación desde Manjaro Linux</b>

    sudo pacman -Syu git
        
<br><b>Conociendo los 3 estados de Git</b>

<img src="https://github.com/kabirna/configure-github-linux/raw/master/images/3estados.png" width="320px">


<br><b>Creando repositorios</b>

Crear una carpeta e inicializarla como un nuevo repositorio:

    git init [directory]
    
Incializar la carpeta actual como un repositorio

    git init
    
Por defecto se va a inicializar en la rama <b>master</b>. Los datos del repositorios se almacenan dentro de la carpeta oculta .<b>git</b> que se crea automáticamente al inicializarlo.
