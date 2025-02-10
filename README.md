# Paso 1: Instalación de Python3
## Ubuntu
- Primero intentaremos actualizar ubuntu con el siguiente comando  
*sudo apt-get update*
- Despues descargaremos python para ubuntu desde la pagina de python (https://www.python.org/downloads/) en formato tax.xz
- Descomprimiremos el archivo con el comando  
*tar xf nombre_del_archivo*
- Descargaremos las dependencias con el siguiente comando  
*sudo apt-get install build-essential zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libsqlite3-dev libreadline-dev libffi-dev curl libbz2-dev*
- Por ultimo haremos el siguiente comando dentro de la carpeta de python  
*sudo ./configure*
## Windows
- Descargaremos python para Windows desde la pagina de python (https://www.python.org/downloads/) en formato .exe
- Despues,abriremos el archivo descargado y seguiremos las instrucciones y pasos del instalador
- Una vez finalizado se puede comprobar la version de python escribiendo python en el cmd de windows
# Paso 2: Instalación de Pip
Iremos a la pagina de pip (https://pip.pypa.io) y seguiremos los pasos indicados
# Paso 3: Creacion de Entorno Virtual
- Abriremos nuestro IDE (Se recomienda y tratara en esta documentacion el IDE de Visual Studio Code)
- En la terminal de Visual Studio Code se realizara el siguiente comando  
*python3 -m venv venv*
- Despues se introducira el siguiente comando para activar el entorno virtual:  
*source venv/bin/activate*
- Para salir del entorno se usara  
*deactivate*
# Paso 4: Instalacion Pyside6
- Una vez dentro del entorno virtual (con el comando mencionado en el paso anterior) instalaremos pyside6 con el siguiente comando:  
*pip install PySide6*
# Paso 5: Ejecucion de la aplicacion
- Se descargara el archivo.py
- Se abrira dicho archivo en el IDE con el entorno virtual
- Se ejectuara el archivo
