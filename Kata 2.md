#   Crear un paquete
PruebaEn este ejercicio, aprenderás a utilizar entornos virtuales como una forma para no afectar a los paquetes instalados globalmente u otros programas que se ejecutan en tu máquina.

*Para este ejercicio es necesario que lo ejecutes desde la terminal, línea de comandos, cmd, consola, cli, etc. de tu computadora, sé que es desafíante, pero no te preocupes ¡¡Sé que puedes lograrlo!!*

# Crear un entorno virtual

Crea un entorno virtual mediante *venv*

- Ejecutar en su terminal: *__python3 -m venv env__*

Ahora tienes un directorio (folder) *env* creado en tu terminal.

<image src="https://github.com/josuevelaz/Katas-Launch-X/blob/josuevelaz-patch-1/Imagenes/Imagen%201.JPG">

- Ejecuta el comando para activar el entorno virtual: *__source env/bin/activate__*

<image src="https://github.com/josuevelaz/Katas-Launch-X/blob/josuevelaz-patch-1/Imagenes/Imagen%202.JPG">

Ahora ves en tu terminal (*env*). Eso significa que has activado tu entorno virtual y se ha aislado del resto de tu máquina.

## Instalar una biblioteca
Ahora que estás dentro de tu entorno virtual, puedes instalar una biblioteca y saber que la biblioteca solo existirá en el entorno virtual.

- Ejecuta el comando *__pip freeze__* para ver las bibliotecas instaladas en tu entorno:

<image src="https://github.com/josuevelaz/Katas-Launch-X/blob/josuevelaz-patch-1/Imagenes/Imagen%203.JPG">

- Ejecuta el comando *__pip install__* para instalar una biblioteca:

<image src="https://github.com/josuevelaz/Katas-Launch-X/blob/josuevelaz-patch-1/Imagenes/Imagen%204.JPG">

- Vuelve a ejecutar *__pip freeze__* para ver cómo ha cambiado tu lista de bibliotecas:

<image src="https://github.com/josuevelaz/Katas-Launch-X/blob/josuevelaz-patch-1/Imagenes/Imagen%205.JPG">

## Desactivar un entorno virtual

Hasta ahora, has creado un entorno virtual y le has agregado un paquete. Sin embargo, es posible que estés trabajando en varios proyectos de Python y necesites cambiar entre ellos. Para hacer eso, debes salir (desactivar) tu entorno virtual.

Ejecuta el comando *__deactivate__*:

<image src="https://github.com/josuevelaz/Katas-Launch-X/blob/josuevelaz-patch-1/Imagenes/Imagen%206.JPG">

## Entorno Virtual en el Directorio local

<image src="https://github.com/josuevelaz/Katas-Launch-X/blob/josuevelaz-patch-1/Imagenes/Imagen%207.JPG">


