# 🏪 AluraStore Latam — Análisis de Datos

## 📋 Descripción

Análisis exploratorio de datos de ventas de la cadena **AluraStore Latam**, realizado como parte del Challenge Data Science de Alura. El objetivo es identificar la tienda menos eficiente y recomendar al Sr. Juan cuál vender para financiar su nuevo emprendimiento.

---

## 📁 Estructura del Proyecto

```
alura-store-latam/
├── AluraStoreLatam.ipynb        # Notebook principal con análisis completo
├── tienda_1_.csv                # Datos de Tienda 1 (2.359 registros)
├── tienda_2.csv                 # Datos de Tienda 2 (2.359 registros)
├── tienda_3.csv                 # Datos de Tienda 3 (2.359 registros)
├── tienda_4.csv                 # Datos de Tienda 4 (2.358 registros)
├── grafico1_ingresos.png        # Gráfico de barras — Ingresos totales
├── grafico2_calificaciones.png  # Gráfico horizontal — Calificaciones promedio
├── grafico3_categorias.png      # Gráfico agrupado — Ventas por categoría
├── grafico4_envios.png          # Gráfico de línea — Costo de envío promedio
├── grafico5_resumen.png         # Gráfico de pastel + producto más vendido
└── README.md
```

---

## 🛠️ Tecnologías Utilizadas

| Librería | Uso |
|----------|-----|
| **Python 3.x** | Lenguaje principal |
| **Pandas** | Carga, manipulación y análisis de datos CSV |
| **Matplotlib** | Generación de gráficos y visualizaciones |
| **NumPy** | Cálculos numéricos auxiliares |

---

## 📊 Análisis Realizados

1. **Facturación total** — Suma de ingresos por `Precio` en cada tienda
2. **Ventas por categoría** — Agrupación por `Categoría del Producto`
3. **Calificación promedio** — Promedio de la columna `Calificación` (escala 1–5)
4. **Productos más/menos vendidos** — Ranking de productos por frecuencia de venta
5. **Costo de envío promedio** — Promedio de la columna `Costo de envío`

---

## 📈 Gráficos Generados

| # | Tipo | Contenido |
|---|------|-----------|
| 1 | Barras verticales | Ingresos totales por tienda |
| 2 | Barras horizontales | Calificación promedio de clientes |
| 3 | Barras agrupadas | Ventas por categoría de producto |
| 4 | Línea con puntos | Costo de envío promedio |
| 5 | Pastel + Barras | Distribución de ingresos y producto top |

---

## ⚙️ Instalación y Uso

```bash
# Instalar dependencias
pip install pandas matplotlib numpy

# Ejecutar el notebook
jupyter notebook AluraStoreLatam.ipynb
```

> Los archivos CSV deben estar en la misma carpeta que el notebook.

---

## 🏁 Conclusión

Tras analizar los cinco indicadores clave, se recomienda al Sr. Juan **vender la Tienda 4**:

- 💰 **Menores ingresos totales** de la cadena: $1,038,375,700 COP
- ⭐ **Tercer lugar en satisfacción** de clientes (4.00 / 5.00)
- 📦 **Portafolio menos diversificado** en categorías de alto volumen
- 🚚 Costo de envío más bajo, indicando cobertura geográfica limitada

Vender la Tienda 4 permite obtener liquidez con el menor impacto posible sobre la rentabilidad de la cadena, conservando las tres tiendas más productivas.

---

## 👤 Autor

Challenge Data Science — Alura Latam
