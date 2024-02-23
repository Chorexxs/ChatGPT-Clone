````markdown
# ChatGPT Clone

Este proyecto es un clon de un chatbot que utiliza OpenAI GPT-3.5 Turbo para generar respuestas.

## Configuración

### Requisitos previos

- Python 3.12
- Cuenta en OpenAI con acceso a la API GPT-3.5 Turbo

### Instalación de dependencias

```bash
pip install django
pip install openai
```
````

### Configuración de claves API

Obtén tu clave de API de OpenAI y colócala en el archivo `views.py`:

```python
openai_api_key = 'tu_clave_de_api'
```

## Uso

1. Ejecute el servidor Django:

```bash
python manage.py runserver
```

2. Abra su navegador y vaya a http://127.0.0.1:8000/login para iniciar sesión o registrarse.

3. Después de iniciar sesión, acceda a http://127.0.0.1:8000/chatbot para interactuar con el chatbot.

## Estructura del proyecto

- `chatbot/`: Aplicación Django principal.

  - `views.py`: Lógica de vistas y funciones relacionadas con OpenAI.
  - `models.py`: Definición del modelo de datos del chat.
  - Otros archivos y carpetas estándar de Django.

- `templates/`: Plantillas HTML para las vistas.
  - `base.html`: Plantilla base.
  - `chatbot.html`: Plantilla para la interfaz del chat.

## Licencia

Este proyecto está realizado siguiendo las intrucciones del siguiente vídeo: https://www.youtube.com/watch?v=qrZGfBBlXpk

Ninguno de los derechos me pertenece.
