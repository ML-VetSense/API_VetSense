# VetAI Python Server

Este servidor FastAPI carga nuestros modelos PyTorch y expone endpoints para predicciones.

## Instalación

```bash
# Crear entorno virtual
python -m venv venv

# Activar entorno virtual
# En Windows:
venv\Scripts\activate
# En Mac/Linux:
source venv/bin/activate

# Instalar dependencias
pip install -r requirements.txt
```

uvicorn main:app --reload --port 8000
```

El servidor estará disponible en: `http://localhost:8000`