# Dónde poner la lupa, focalización sectorial de la formalización laboral

Proyecto Final Integrador, Diplomado en Ciencia de Datos y Análisis Avanzado (UTN BA).
Bernardita Viera y Renzo Mirabella.

## Requisitos

Python 3.10 o superior y las dependencias de `requirements.txt`.

```bash
pip install -r requirements.txt
```

## Cómo ejecutarlo

### En forma local

1. Clonar el repositorio y abrir `proyecto_integrador_entrega.ipynb` desde la carpeta del repositorio.
2. Ejecutar todas las celdas en orden (Kernel → Restart & Run All).

La base de datos no está incluida por lo que se debe descargar desde el siguiente enlace https://www.indec.gob.ar/indec/web/Institucional-Indec-BasesDeDatos debe ser la correspondiente al primer trimestre de 2026. La ejecución completa tarda unos 3 minutos, más alrededor de 1,5 minutos la primera vez, porque se lee el `.xlsx` y se guarda una copia en `data/usu_individual_T126.parquet` que acelera las ejecuciones siguientes. Las tablas y figuras se guardan en `results/`.

### En Google Colab

Ejecutar en una celda al principio del notebook

```python
!git clone <url-del-repositorio>
%cd <nombre-del-repositorio>
```

y después ejecutar el resto del notebook.

## Datos

INDEC, Encuesta Permanente de Hogares, microdatos del 1.er trimestre de 2026, base individual. Son datos públicos y anonimizados, y la cita de la fuente es obligatoria.
