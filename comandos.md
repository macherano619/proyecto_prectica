cd C:\Users\CHRISTIAN\OneDrive\Documents\GitHub\python

# crear entorno de python
conda create --name entorno_holajango_310 pyton=3.10

# activar conda
conda activate entorno_holajango_310

# desactivar el entorno
conda desactivate

# instalar django
pip install Django==3.*

# guardar un texto con todos los paquetes instalados y sus versiones
pip freeze > reqyurements.txt

# Instalar todos los paquetes y versiones desde el listado
pip install -r requirements.txt

# Verificar que todo esté bien
pip check
# Crear un entorno en Django
 django-admin startproject holamundo
 # entrar al directorio del proyecto
 cd holamundo
 
 # correr el servidor local para ver la aplicación
 python manage.py runserver
 # Para detener el servidor se pone ctrl + c

 python manage.py startapp holaMundo