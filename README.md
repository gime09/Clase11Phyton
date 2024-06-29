
comandos
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

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.

Respuesta del punto 11 

PIP (Python Package Installer) es el sistema de gestión de paquetes estándar para Python. Permite instalar y gestionar paquetes de software escritos en Python que están disponibles en el Python Package Index (PyPI). Aquí tienes una explicación detallada sobre qué es PIP y por qué es importante actualizarlo:

¿Qué es PIP?
Gestor de Paquetes: PIP es un gestor de paquetes que facilita la instalación y gestión de paquetes de software escritos en Python.

Acceso a PyPI: Se conecta al Python Package Index (PyPI), que es un repositorio global de paquetes de software para Python. PyPI almacena miles de paquetes de software que pueden ser fácilmente instalados usando PIP.

Instalación de Dependencias: PIP se utiliza principalmente para instalar dependencias externas que un proyecto Python necesita para funcionar correctamente. Esto incluye bibliotecas de terceros, frameworks y herramientas adicionales.

¿Por qué es importante actualizar PIP?
Nuevas Funcionalidades y Mejoras: Las actualizaciones periódicas de PIP suelen incluir nuevas funcionalidades, mejoras de rendimiento y correcciones de errores. Mantener PIP actualizado garantiza que puedas beneficiarte de estas mejoras y tener acceso a las últimas características ofrecidas por PIP y PyPI.

Compatibilidad: Las versiones actualizadas de PIP suelen ser más compatibles con las versiones más recientes de Python y con las últimas versiones de los paquetes en PyPI. Esto ayuda a evitar problemas de compatibilidad y asegura que los paquetes que instalas funcionen correctamente con tu entorno de desarrollo.

Corrección de Vulnerabilidades: A veces, las actualizaciones de PIP también corrigen vulnerabilidades de seguridad conocidas. Es crucial mantener PIP actualizado para proteger tu sistema y tu código frente a posibles vulnerabilidades.

Cómo Actualizar PIP
Para actualizar PIP a la última versión, puedes usar el siguiente comando en tu terminal:

bash
Copiar código
pip install --upgrade pip
Este comando instalará la última versión de PIP disponible desde PyPI, sobrescribiendo la versión anterior si es necesario. Es una buena práctica ejecutar este comando regularmente para mantener PIP actualizado y aprovechar todas las ventajas mencionadas.

En resumen, PIP es esencial para la gestión de paquetes en Python, y actualizarlo regularmente es importante para acceder a nuevas funcionalidades, mejoras de rendimiento, correcciones de errores y mantener la seguridad de tu entorno de desarrollo.







