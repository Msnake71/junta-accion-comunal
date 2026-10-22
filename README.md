# Página web: Junta de Acción Comunal

Proyecto básico de Flask para presentar información de una Junta de Acción Comunal.

## Ejecutar en el computador

1. Instala Python 3.10 o superior.
2. Abre una terminal en esta carpeta.
3. Crea un entorno virtual (opcional, recomendado):
   - Windows: `py -m venv .venv`
   - Activarlo: `.venv\Scripts\activate`
4. Instala dependencias: `pip install -r requirements.txt`
5. Ejecuta: `python app.py`
6. Abre `http://127.0.0.1:5000` en el navegador.

## Desplegar en Railway

1. Crea una cuenta o inicia sesión en Railway.
2. Sube esta carpeta a un repositorio de GitHub.
3. En Railway, selecciona crear un proyecto y desplegar desde GitHub.
4. Elige el repositorio que contiene estos archivos.
5. Railway instalará las dependencias de `requirements.txt` y usará el comando del `Procfile`.
6. Cuando termine el despliegue, genera un dominio público desde la configuración de Networking/Domains.
7. Abre el dominio y verifica que cargue la página.

Nota: el despliegue real requiere iniciar sesión en Railway y autorizar el acceso al repositorio. Este proyecto queda preparado, pero no se ha publicado desde esta sesión.
