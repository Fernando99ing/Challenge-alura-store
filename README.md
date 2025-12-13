# Challenge-alura-store
# 📊 Análisis de Ventas y Desempeño de Tiendas  
## Proyecto de Ciencia de Datos – Challenge Alura LATAM

## 📌 Descripción del Proyecto

El objetivo de este proyecto es analizar el desempeño de cuatro tiendas del Sr. Juan con el fin de **determinar cuál de ellas debe ser vendida** para dar lugar a un nuevo negocio.  

La decisión se basa en un análisis integral de datos de ventas, considerando ingresos, volumen de ventas, categorías de productos, satisfacción de los clientes, costos de envío, comportamiento temporal y distribución geográfica.

---

## 🛠️ Tecnologías Utilizadas

- **Python**
- **Pandas** → Manipulación y análisis de datos  
- **Matplotlib** → Visualización de datos  
- **NumPy** → Apoyo en cálculos numéricos  
- **Google Colab** → Entorno de desarrollo  

---

## 📥 Importación de Datos

Se trabajó con cuatro conjuntos de datos correspondientes a cada tienda, obtenidos desde un repositorio público en GitHub.  
Cada dataset contiene información sobre:

- Producto  
- Categoría del producto  
- Precio  
- Costo de envío  
- Fecha de compra  
- Calificación del cliente  
- Ubicación geográfica (latitud y longitud)  

---

## 📈 1. Análisis de Facturación

Se calculó el ingreso total de cada tienda sumando la columna **Precio**.

### Resultados:
- **Tienda 1:** $1,150,880,400  
- **Tienda 2:** $1,116,343,500  
- **Tienda 3:** $1,098,019,600  
- **Tienda 4:** $1,038,375,700  

📌 *La Tienda 4 presenta el menor nivel de ingresos totales.*

---

## 🧩 2. Ventas por Categoría

Se analizó:
- Cantidad de productos vendidos por categoría
- Valor total generado por cada categoría

### Hallazgos:
- Electrónicos y Electrodomésticos son las categorías más rentables en todas las tiendas.
- La Tienda 4 tiene menor volumen y menor valor total por categoría.
- Menor diversidad y rotación de productos en comparación con las otras tiendas.

---

## ⭐ 3. Calificación Promedio de los Clientes

Se calculó la calificación promedio para cada tienda.

### Resultados:
- **Tienda 1:** 3.98  
- **Tienda 2:** 4.04  
- **Tienda 3:** 4.05  
- **Tienda 4:** 3.99  

📌 *La Tienda 4 tiene la calificación más baja, lo que indica menor satisfacción del cliente.*

---

## 🏆 4. Productos Más y Menos Vendidos

Se identificaron:
- Productos con mayor y menor número de ventas
- Productos que generaron más y menos ingresos

### Observaciones:
- Todas las tiendas cuentan con productos estrella.
- En la Tienda 4, incluso los productos más vendidos tienen menor rotación.
- La Tienda 4 también concentra varios productos de bajo rendimiento económico.

---

## 🚚 5. Costo de Envío Promedio

Se calculó el costo promedio de envío por tienda.

### Resultados:
- **Tienda 1:** $26,018  
- **Tienda 2:** $25,216  
- **Tienda 3:** $24,805  
- **Tienda 4:** $23,459  

📌 *Aunque la Tienda 4 tiene el envío más barato, esto no compensa su bajo desempeño en ventas.*

---

## 📊 6. Visualización de Datos

Se generaron múltiples gráficos para facilitar la interpretación:

1. **Ingresos totales por tienda**  
2. **Cantidad de ventas vs ganancias totales**  
3. **Ingreso promedio por venta**  
4. **Ventas y costos totales por categoría**  
5. **Ingresos por tienda a lo largo del tiempo**  

Estas visualizaciones confirman que la Tienda 4 mantiene un desempeño inferior en casi todas las métricas.

---

## 🌍 7. Análisis Geográfico (Extra)

Se utilizaron las columnas de latitud y longitud para explorar patrones espaciales.

### Análisis realizado:
- Gráficos de dispersión para distribución geográfica
- Mapas de calor para concentración de ventas
- Relación entre ubicación, ingresos y calificaciones

### Conclusiones:
- Las zonas con mayor concentración de ventas también presentan mejores calificaciones.
- La Tienda 4 tiene menor presencia geográfica.
- Sus ventas se concentran en regiones con menor actividad comercial y menor valor promedio.

---

## 🧠 Conclusión Final

Tras analizar de forma integral:

- Ingresos totales  
- Ventas por categoría  
- Productos más y menos vendidos  
- Calificaciones de clientes  
- Costos de envío  
- Evolución temporal de ingresos  
- Distribución geográfica  

### ✅ **La tienda que debe vender el Sr. Juan es la *Tienda 4***.

### Justificación:
- Es la tienda con **menores ingresos totales**.
- Presenta **menor volumen y diversidad de ventas**.
- Tiene **las calificaciones promedio más bajas**.
- No muestra **tendencias de crecimiento** a lo largo del tiempo.
- Posee **menor presencia geográfica y menor impacto regional**.

Vender la Tienda 4 minimiza el impacto en el negocio global y abre la oportunidad de invertir en un nuevo proyecto con mayor potencial.

---

## 📌 Fernando Contreras

Proyecto desarrollado como parte del **Challenge de Ciencia de Datos – Alura LATAM**.


