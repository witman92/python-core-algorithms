# Validación de datos y clasificación de riesgo de salud con Python puro

Procesamiento de un dataset de estilo de vida y salud **sin pandas en la etapa de validación**, usando solo estructuras nativas de Python, funciones y programación funcional.

## Qué incluye
- **Parsing y validación de CSV** con `open`/`split`: estructura de columnas, tipos de dato, valores categóricos válidos y conteo de filas inválidas (`verificar_fila`).
- **Clasificación de riesgo** (Alto / Medio / Bajo / Muy bajo) combinando IMC ≥ 30, tabaquismo y actividad física.
- **Agregaciones por grupo** con filtros opcionales por tipo de dieta y nivel educacional.
- **Programación funcional**: `map` + `lambda` para categorizar el IMC, `filter` para aislar casos de obesidad y `reduce` para conteos por categoría.
- **Carga robusta** (`cargar_y_procesar`) con `try/except/finally` ante archivos inexistentes, columnas incompletas y tipos inválidos.

## Estructura
```
health_lifestyle_risk_analysis.ipynb      # Notebook principal
health_lifestyle_classification.csv       # Dataset
clasificación de estilo de vida saludable..xlsx
```

**Stack:** Python · functools · pandas (solo para visualizar tablas)
