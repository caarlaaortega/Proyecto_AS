# Proyecto Análisis de Señales
Proyecto de Análisis de Señales centrado en la extracción de características de datos de canciones, y clasificación del género musical.

# Descargar datos

Crear un virtual environment de python e instalar las dependencias:

```
python -m venv .venv
```

Activar el environment:
```
source .venv/bin/activate # linux
?? # mac
?? # windows
```

Instalar la dependencia necesaria para descargar los datos:

```
pip install modelscope[framework]
```

Finalmente, solo queda abrir la libreta `download_data.ipynb` y ejecutar la única celda que hay.

> [!WARNING]
> **Son casi 14 GB de datos, la descarga puede tardar mucho tiempo.**