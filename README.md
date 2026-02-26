# AluraStoreLatamChallenge
Data Science Challenge 1 - Alura
# Análisis Estratégico de Tiendas - Alura Store

## Propósito del Proyecto

Este proyecto tiene como objetivo analizar el desempeño de cuatro tiendas de la cadena **Alura Store**, con el fin de recomendar cuál debería venderse para financiar un nuevo emprendimiento.

El análisis se basa en datos reales de ventas y considera múltiples variables estratégicas como:

- Ingresos totales
- Categorías más vendidas
- Productos más y menos vendidos
- Calificaciones promedio de clientes
- Costo de envío promedio
- Distribución geográfica de ventas (análisis extra)

La decisión final se fundamenta en evidencia cuantitativa y visualizaciones comparativas.

---

## Estructura del Proyecto
Alura-Store-Analysis/
tienda_1.csv
tienda_2.csv
tienda_3.csv
tienda_4.csv
AluraStoreLatam.ipynb
README.md

---

### Descripción de Archivos

- **tienda_X.csv** → Datos individuales de cada tienda.
- **AluraStoreLatam.ipynb** → Notebook con todo el análisis.
- **README.md** → Documentación del proyecto.

---

## Análisis Realizados

### Ingresos Totales
Se calcularon sumando la columna `Precio` para cada tienda.

Insight:
La Tienda 4 presenta el menor ingreso total, lo que indica menor rendimiento financiero.

---

### Categorías Más Vendidas
Se agruparon los datos por `Categoría del Producto` para identificar las categorías más populares.

Insight:
La categoría **Electrónicos** lidera en todas las tiendas, siendo la principal fuente de ingresos.

---

### Calificación Promedio
Se calculó el promedio de la columna `Calificación`.

Insight:
La Tienda 3 presenta la mejor evaluación de clientes, mientras que la Tienda 1 tiene la más baja.

---

### Productos Más y Menos Vendidos
Se identificaron usando conteos de la columna `Producto`.

Insight:
Cada tienda tiene productos destacados, pero la Tienda 4 no muestra un producto dominante que impulse significativamente sus ingresos.

---

### Costo de Envío Promedio
Se calculó el promedio de la columna `Costo de envío`.

Insight:
La Tienda 4 tiene el costo de envío promedio más bajo, pero esto no compensa su menor facturación.

---

### Análisis Geográfico (Extra)
Se utilizaron coordenadas `lat` y `lon` para analizar la distribución espacial de las ventas.

Insight:
Las ventas se concentran en determinadas regiones, pero la Tienda 4 no muestra una ventaja geográfica significativa frente a las demás.

---

## Ejemplos de Visualizaciones Generadas

El proyecto incluye distintos tipos de gráficos, Estos gráficos permiten identificar patrones claros y respaldar la recomendación final.

---

## Conclusión del Análisis

Después de evaluar todas las métricas clave, se recomienda vender la **Tienda 4**, debido a:

- Menor ingreso total.
- No lidera en calificaciones.
- No presenta productos estrella que impulsen el crecimiento.
- Ventaja en costos de envío insuficiente para compensar su menor rendimiento.

Esta decisión permite optimizar la estructura del negocio sin afectar significativamente la rentabilidad global de la cadena.

---

## Cómo Ejecutar el Proyecto

1. Clonar el repositorio o descargar los archivos.
2. Abrir el archivo `AluraStoreLatam.ipynb` en:
   - Google Colab, o
   - Jupyter Notebook.
3. Verificar que los archivos CSV estén en el mismo directorio.
4. Ejecutar las celdas en orden.

---

## Maria Jose Rincon Manrique

Proyecto desarrollado como parte del desafío de análisis de datos de Alura Latam.
