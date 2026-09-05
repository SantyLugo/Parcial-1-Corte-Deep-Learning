## Preparación y ejecución

Instala las dependencias del proyecto y ejecuta las pruebas y el linter:

```bash
uv sync
uv run pytest
uv run ruff check .
```

### Abrir los cuadernos en Visual Studio Code

Instala la extensión **Jupyter** de Visual Studio Code y abre el archivo `.ipynb`. En la esquina superior derecha, selecciona **Select Kernel** y elige el intérprete del ambiente del proyecto. Si no aparece, selecciona **Select Another Kernel...** → **Python Environments...** y escoge el entorno creado por `uv` (normalmente `.venv\Scripts\python.exe` en Windows).
