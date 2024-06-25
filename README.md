# Python-final

## Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 

mkdir python-final

3. Entramos en ella: 

cd python-final

4. Iniciamos el repositorio:

git init

5. Creamos un archivo:

touch finales.py

6. Abrimos VSC:

code .

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

python -V

python3 -V

8. Creamos el entorno virtual en Python:

python3 -m venv venv #Creamos el entorno virtual

9. Activamos el entorno virtual:

source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows

10. Hacemos actualización del pip de Python

python3 -m pip install --upgrade pip #Actualizamos el pip

11. Investigar ¿Qué es el pip y porque lo actualizamos?

  Respuestas:
  `pip` es una herramienta de línea de comandos en Python que se utiliza para instalar y gestionar paquetes de software escritos en Python. El nombre `pip` es un acrónimo recursivo que significa `"pip installs packages"` (pip instala paquetes).

### Funciones principales de pip:
Instalar paquetes: Puedes instalar cualquier paquete disponible en el Python Package Index (PyPI) usando un comando como `pip install nombre_paquete`.
Actualizar paquetes: Permite actualizar un paquete a su versión más reciente con `pip install --upgrade nombre_paquete`.
Desinstalar paquetes: Puedes desinstalar paquetes con `pip uninstall nombre_paquete`.
Listar paquetes instalados: Muestra todos los paquetes instalados en el entorno con `pip list`.
Mostrar información de un paquete: Puedes obtener detalles sobre un paquete específico usando `pip show nombre_paquete`.

### ¿Por qué actualizamos pip?
Actualizar pip es importante por varias razones:
Nuevas funcionalidades: 
Las nuevas versiones de pip a menudo incluyen nuevas características que pueden hacer que la gestión de paquetes sea más fácil y más eficiente.
Corrección de errores: Cada versión de pip puede incluir correcciones de errores y fallos que estaban presentes en versiones anteriores.
Mejoras de seguridad: Las actualizaciones de pip pueden incluir parches de seguridad importantes que protegen tu entorno de desarrollo de vulnerabilidades.
Compatibilidad: Las nuevas versiones pueden asegurar mejor compatibilidad con las versiones más recientes de Python y con los paquetes de PyPI.
Cómo actualizar pip
Para actualizar pip a la versión más reciente, puedes ejecutar el siguiente comando en la terminal:
```sh
  pip install --upgrade pip
```

> Este comando descargará e instalará la última versión de pip disponible, garantizando que tienes acceso a las últimas mejoras y correcciones.



12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.
