En este repositorio son las primeras pruebas para el git y github.

Para crear un documento txt es necesario utilizar el siguiente comando:
pip freeze > paquetes.txt

Con este comando se pondra en el documento paquetes.txt todas las librerias que hemos instalado en el entorno virtual.

Si el dia de mañana deseamos instalar los paquetes en un nuevo equipo se tendrá que crear el entorno virtual recordando que se usa el siguiente comando para crear un entorno virtual con el nombre de Entorno:
python3 -m venv Entorno

Para activarlo es accediendo mediante la termina a la carpeta del entorno (en mi caso es Entorno). Accedemos a la carpeta bin o Scripts, y ejecutamos activate.

Podemos crear un alias de la siguiente forma para que sea más fácil de activar el entorno :
alias activate="source Entorno/bin/activate"

Para desactivarlo es con el comando: deactivate.
