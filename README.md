# Análisis de Ventas por Tienda - Proyecto Sr. Juan

Este proyecto tiene como objetivo ayudar al Sr. Juan a tomar una decisión estratégica sobre cuál de sus cuatro tiendas debería considerar vender, basándose en un análisis exhaustivo de sus datos de ventas, satisfacción del cliente y distribución geográfica.

## 📊 Objetivo

Analizar las métricas clave de desempeño de las tiendas para identificar cuál presenta menor rentabilidad, menor volumen de ventas, menor aceptación por parte de los clientes y peor desempeño logístico.

## 📁 Fuentes de Datos

Los datos provienen de cuatro archivos `.csv` disponibles en línea y contienen información sobre:

- Productos vendidos
- Categorías
- Ingresos
- Costos de envío
- Calificaciones de clientes
- Ubicación geográfica (latitud y longitud)

## 🛠 Herramientas Utilizadas

- **Python**
- **Pandas** y **NumPy** para manipulación de datos
- **Matplotlib** y **Seaborn** para visualización
- **GeoPandas** y **Shapely** para mapas geográficos
- **Google Colab** para entorno de desarrollo

## 📈 Análisis Realizado

### 1. Ingresos Totales
- **Tienda 1**: La más rentable.
- **Tienda 4**: Genera los ingresos más bajos.

### 2. Categorías Más y Menos Vendidas
- Tecnología y hogar: Las categorías más populares.
- Tienda 4: Baja rotación en varias categorías.

### 3. Calificaciones Promedio
- **Tienda 2**: Mejor calificación.
- **Tienda 3**: Peor calificación.
- **Tienda 4**: Evaluación promedio.

### 4. Productos Más y Menos Vendidos
- **Tiendas 1 y 2** concentran las unidades más vendidas.
- **Tienda 4** vende menos unidades por producto.

### 5. Coste de Envío Promedio
- No hay diferencias significativas.
- Tienda 1 logra altos ingresos con costos de envío moderados.

### 6. Distribución Geográfica
- **Tienda 1**: Concentrada en zonas de alta demanda.
- **Tienda 4**: Ventas dispersas, lo que afecta la logística.

## 📌 Conclusión y Recomendación

Se recomienda considerar la **venta de la Tienda 4**, ya que es la menos competitiva en términos de:

- Ingresos
- Volumen de ventas
- Presencia geográfica

Sin embargo, esta decisión debe alinearse con los objetivos estratégicos del Sr. Juan. También puede considerarse una intervención en la **Tienda 3** si el enfoque es mejorar la experiencia del cliente.

Se sugiere complementar esta decisión con un análisis financiero más profundo y considerar estrategias de refuerzo para las tiendas restantes.

---

## 👤 Autor

Proyecto realizado por Frank Teheran, como parte del Challenge de Análisis de Datos de Alura Latam.
