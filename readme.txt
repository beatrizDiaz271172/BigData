# Predicción de ingresos con el dataset Adult (Censo 1994)

Proyecto final de la Maestría en Inteligencia de Datos orientada a Big Data
(Universidad Nacional de La Plata).

## Objetivo

Predecir si los ingresos anuales de una persona superan los USD 50.000 a partir
de sus datos demográficos y laborales (problema de clasificación binaria).

## Datos

- Fuente: [Adult Dataset – UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/2/adult),
  extraído del censo de EE. UU. de 1994.
- Variables: edad, nivel educativo,ocupación, horas trabajadas por semana, estado civil, etc.
- Variable objetivo: ingreso `<=50K` / `>50K`.

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `TrabajoFinal_BeatrizDiaz.ipynb` | Notebook en Python con todo el análisis |
| `Informe de Minería de Datos.docx` | Informe con la metodología y las conclusiones |
| `adult.csv` | Conjunto de datos utilizado |

## Metodología

1. **Exploración de datos:** [distribuciones, correlaciones, desbalance de clases].
2. **Limpieza y preparación:** [tratamiento de valores faltantes, codificación de
   variables categóricas, escalado, etc.].
3. **Modelado:** [modelos probados, regresión logística, árbol de
   decisión, random forest].
4. **Evaluación:** [métricas usadas: exactitud, precisión, recall, F1, matriz de
   confusión].

## Cómo ejecutarlo

1. Clonar el repositorio.
2. Instalar las dependencias: `pip install pandas numpy scikit-learn matplotlib`
  
3. Abrir `TrabajoFinal_BeatrizDiaz.ipynb` con Google Colab y ejecutar
   las celdas en orden.

## Tecnologías

Python · pandas · scikit-learn · [otras]

## Autora

Beatriz Cristina Díaz