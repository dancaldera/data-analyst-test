Prueba Técnica: Data Analyst

Al menos tener versión de Python 3.9 o superior.

Instrucciones

    1.  Crea un entorno virtual de Python, activa el entorno y asegúrate de tener instaladas las librerías necesarias.
    2.	Carga el dataset llamado tasas_credito.csv. Este dataset contiene las tasas de interés de crédito hipotecario de varios bancos.
    3.	Carga el dataset en Python usando pandas.
    4.	Muestra un resumen de los datos (número de filas, columnas, valores nulos, tipos de datos).
    5.	Realiza un análisis descriptivo, mostrando la tasa promedio, mediana, tasa máxima y mínima para cada banco.
    6.	Realiza una visualización que muestre la evolución de las tasas a lo largo del tiempo para los distintos bancos.
    7.	Aplica un modelo de regresión lineal para predecir la tasa de interés del próximo mes.

Dataset: tasas_credito.csv (Se te mandará un dataset más completo a la hora de la prueba técnica)

Ejemplo:

```csv
Fecha,Banco,Tasa
2020-01-01,Banco A,6.5
2020-01-01,Banco B,7.5
2020-01-01,Banco C,8.5
2020-02-01,Banco A,6.6
2020-02-01,Banco B,7.6
2020-02-01,Banco C,8.6
```

## Requerimientos

1. Carga y Exploración de Datos:
   • Usa pandas para cargar el archivo CSV y explora los datos.
   • Muestra las primeras 5 filas del dataset.
   • Proporciona un resumen general (df.describe()).
2. Análisis Descriptivo:
   • Calcula la media, mediana, tasas máximas y mínimas para cada banco.
   • Identifica valores faltantes y describe cómo los manejarías.
3. Visualización:
   • Utiliza matplotlib o seaborn para crear una gráfica de líneas que muestre la evolución de las tasas de cada banco a lo largo del tiempo.

Ejemplo de gráfico esperado:
• Eje X: Fecha
• Eje Y: Tasa de interés
• Líneas: Una para cada banco.
• Predicción con Regresión Lineal:
• Usa scikit-learn para aplicar un modelo de regresión lineal para predecir la tasa de un banco en particular para el próximo mes.
• Utiliza las fechas anteriores como la variable predictora y las tasas como la variable objetivo.
• Muestra el resultado de la predicción y la visualización de la tendencia.

Código base se encuentra en el archivo: main.py.

Algunos comandos que te pueden ser útiles:

Para crear un entorno virtual y activarlo

```bash
python -m venv venv
source venv/bin/activate
```

Instalar las librerías necesarias

```bash
pip install -r requirements.txt
```

Para ejecutar el script

```bash
python main.py
```
