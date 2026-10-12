# Tablero de cartera de seguros de auto

Tablero interactivo en Streamlit (Diplomado Machine Learning en Seguros, FC UNAM, Módulo 5): filtros por cobertura, sexo, uso, combustible y edad; KPIs de cartera (exposición, siniestros, frecuencia, severidad, prima pura); gráficas de frecuencia y combined ratio por factor; y un cotizador con prima empírica, prima GLM y prima de tarifa.

## Correrlo local

```
pip install -r requirements.txt
streamlit run app_streamlit.py
```

Los datos están en `datos/datos.parquet`. La base `cartera.db` se reconstruye sola la primera vez.
