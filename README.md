# Análisis de Red de Tiendas RetailNow

## Descripción

Este proyecto tiene como objetivo analizar el desempeño de una red de tiendas utilizando Python, Pandas y NumPy. A partir de los conjuntos de datos proporcionados, se realizan procesos de limpieza, análisis y generación de métricas que permiten evaluar las ventas, el inventario disponible y la satisfacción de los clientes.

El desarrollo se realizó mediante un notebook de Jupyter, facilitando la exploración y visualización de los resultados obtenidos.

## Objetivos

* Cargar y procesar datos de ventas, inventarios y satisfacción del cliente.
* Limpiar los datos eliminando registros incompletos.
* Analizar el rendimiento de ventas por tienda.
* Identificar niveles de inventario y posibles riesgos de desabastecimiento.
* Evaluar la satisfacción promedio de los clientes.
* Aplicar funciones de NumPy para obtener métricas estadísticas.
* Simular escenarios futuros de ventas utilizando generación de datos aleatorios.

## Tecnologías Utilizadas

* Python 3
* Pandas
* NumPy
* Jupyter Notebook
* Visual Studio Code

## Estructura del Proyecto

```text
analisis-retailnow/
│
├── myenv/
├── workspace/
│   ├── sales.csv
│   ├── inventories.csv
│   └── satisfaction.csv
│
├── analisis_red_tiendas.ipynb
├── .gitignore
└── README.md
```

## Conjuntos de Datos

### sales.csv

Contiene información sobre las ventas realizadas por cada tienda.

Columnas:

* ID_Tienda
* Producto
* Cantidad_Vendida
* Precio_Unitario
* Fecha_Venta

### inventories.csv

Contiene información sobre el inventario disponible.

Columnas:

* ID_Tienda
* Producto
* Stock_Disponible
* Fecha_Actualización

### satisfaction.csv

Contiene información sobre la satisfacción promedio de los clientes.

Columnas:

* ID_Tienda
* Satisfacción_Promedio
* Fecha_Evaluación

## Funcionalidades Implementadas

### Limpieza de Datos

* Eliminación de registros con valores nulos utilizando `dropna()`.

### Análisis de Ventas

* Cálculo de ingresos totales.
* Agrupación de ventas por tienda.
* Identificación de tiendas con mejor desempeño.

### Análisis de Inventario

* Evaluación del stock disponible.
* Detección de productos con inventario bajo.

### Satisfacción del Cliente

* Análisis de las calificaciones promedio por tienda.
* Comparación de niveles de satisfacción.

### Estadísticas con NumPy

* Cálculo de mediana de ventas.
* Cálculo de desviación estándar.
* Simulación de ventas futuras mediante generación de datos aleatorios.

## Ejecución

1. Crear y activar un entorno virtual:

```bash
python -m venv myenv
source myenv/bin/activate
```

2. Instalar dependencias:

```bash
pip install pandas numpy jupyter
```

3. Ejecutar Jupyter Notebook:

```bash
jupyter notebook
```

4. Abrir el archivo:

```text
analisis_red_tiendas.ipynb
```

## Resultados Esperados

El análisis permite identificar tendencias de ventas, evaluar la disponibilidad de inventario y conocer el nivel de satisfacción de los clientes, proporcionando información útil para la toma de decisiones dentro de la organización.

## Autor

Jeffrey Vasquez
