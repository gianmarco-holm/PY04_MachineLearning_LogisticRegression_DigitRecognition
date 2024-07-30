# Regresión Logística de Predicción de Digito en una Imagen
---

## Descripción del Proyecto

En este proyecto se usa el dataset digits de Scikit Learn, este dataset contiene imagenes en una escala de grises con el digito a que corresponde, el cual se ha usado para entrenar este modelo y luego se pueda predecir que digito se encuentra en esta imagen.

## Contenido

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Contenido](#contenido)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Resultados](#resultados)
- [Conclusión](#conclusión)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Requisitos

- Python 3.x
- Librerías:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - plotly
  - scikit-learn
  - regressors
  - pickle

## Instalación

1. Puedes descargar el archivo y correrlo en Google Colab

## Uso
Carga los datos:

```python
from sklearn.datasets import load_digits

digits = load_digits()
```

## Resultados
Los resultados del modelo se presentan mediante gráficos de dispersión, matrices de correlación y gráficos de residuos para visualizar la precisión y las predicciones del modelo.

## Conclusión
Este modelo uso 3 métricas principales para su evaluación, una matriz de confusión, una clasificación de reporte y el coeficiente de precisión, teniendo un 95%.

## Contribuciones
Las contribuciones son bienvenidas. Para grandes cambios, por favor abre un issue primero para discutir lo que te gustaría cambiar.# Regresión lineal: predecir los gastos médicos de pacientes

## Conclusión
El modelo inicial tiene un coeficiente de determinación (R²) de aproximadamente 0.50, lo cual es aceptable para la predicción de gastos hospitalarios. Se recomienda seguir afinando el modelo inicial y probar con diferentes características y técnicas para mejorar la precisión.

## Contribuciones
Las contribuciones son bienvenidas. Para grandes cambios, por favor abre un issue primero para discutir lo que te gustaría cambiar.
