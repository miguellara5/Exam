markdown
Copy code
## 🌟 Configuración Inicial

### Paso 1: 🧙‍♂️ Preparando el Entorno 
```bash
python -m venv env
env\Scripts\activate   # 🧙 Activa el entorno
```
Paso 2: ✨ Instala los requerimientos
```bash

pip install -r requirements.txt
```
Paso 3: 🏗️  Inicia la base de datos 
```bash
python manage.py migrate
```
Paso 4: 🌟 Inicia el servidor de desarrollo
```bash
python manage.py runserver
```
