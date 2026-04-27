# 🚀 Guía de Ejecución - GamesHub

Sigue estos pasos en orden para configurar y correr el proyecto en tu computadora local:

### 1. Clonar el repositorio
Abre tu terminal y descarga el proyecto:
```bash
git clone [https://github.com/AndrishAraiza/Gameshub.git](https://github.com/AndrishAraiza/Gameshub.git)
cd Gameshub


# Crear el entorno
python3 -m venv venv

# Activar el entorno (Mac/Linux)
source venv/bin/activate

# Activar el entorno (Windows)
# venv\Scripts\activate

pip install -r requirements.txt

# Ejecutar el script de llenado de datos
python3 seed.py

python3 run.py
