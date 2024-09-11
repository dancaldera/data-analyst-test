# Prueba Técnica: Data Analyst

**Requisitos**: Al menos tener versión de Python 3.9 o superior.

## Instrucciones

1. Crea un entorno virtual de Python, activa el entorno y asegúrate de tener instaladas las librerías necesarias.
2. Carga el dataset llamado `tasas_credito.csv`. Este dataset contiene las tasas de interés de crédito hipotecario de varios bancos.
3. Carga el dataset en Python usando pandas.
4. Muestra un resumen de los datos (número de filas, columnas, valores nulos, tipos de datos).
5. Realiza un análisis descriptivo, mostrando la tasa promedio, mediana, tasa máxima y mínima para cada banco.
6. Realiza una visualización que muestre la evolución de las tasas a lo largo del tiempo para los distintos bancos.
7. Aplica un modelo de regresión lineal para predecir la tasa de interés del próximo mes.
8. Realiza una visualización que muestre la predicción de la tasa de interés del próximo mes.

**Dataset**: `tasas_credito.csv` (Se te mandará un dataset más completo a la hora de la prueba técnica)

**Ejemplo de dataset**:

```csv
Fecha,Banco,Tasa
2020-01-01,Banco A,6.5
2020-01-01,Banco B,7.5
2020-01-01,Banco C,8.5
2020-02-01,Banco A,6.6
2020-02-01,Banco B,7.6
2020-02-01,Banco C,8.6
```

## Código Base

El código base se encuentra en el archivo: `main.py`.

## Comandos útiles:

### Crear un entorno virtual y activarlo:

```bash
python -m venv venv
source venv/bin/activate
```

### Instalar las librerías necesarias:

```bash
pip install -r requirements.txt
```

### Ejecutar el script:

```bash
python main.py
```
