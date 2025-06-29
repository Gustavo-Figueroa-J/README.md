# README.md
# Proyecto python-final

Este repositorio contiene el proyecto de Python con los pasos y comandos utilizados para configurar el entorno de trabajo, junto con la explicación sobre `pip` y su actualización.

---

## 1. Comandos utilizados para configurar el proyecto

```bash
# Crear carpeta del proyecto
mkdir python-final

# Entrar en la carpeta
cd python-final

# Inicializar repositorio git
git init

# Crear archivo Python
touch finales.py

# Abrir VS Code
code .

# Verificar versión de Python
python -V

# Crear entorno virtual
python -m venv venv

# Activar entorno virtual (Windows PowerShell)
.\venv\Scripts\Activate.ps1

# Actualizar pip
python -m pip install --upgrade pip

# Que es pip y porqué lo actualizamos?

pip es el administrador de paquetes de Python. Permite instalar, actualizar y desinstalar librerías externas que agregan funcionalidades a nuestros proyectos.

Actualizamos pip para:

Corregir errores y fallas de seguridad.

Mantener compatibilidad con las últimas versiones de paquetes.

Aprovechar nuevas funciones que se van incorporando.
