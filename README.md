# Análisis Comparativo de 4 Tiendas

Este proyecto realiza un análisis completo de **cuatro tiendas** para identificar patrones de ventas, categorías más y menos rentables, costos de envío y calificaciones promedio.  
El objetivo es ayudar a tomar una decisión estratégica sobre **cuál tienda vender** en función de su desempeño y potencial.

---

# Descripción del Proyecto

El análisis combina datos de ventas de las cuatro tiendas, que incluyen:

- **Ventas Totales** → Suma total de ingresos por tienda.
- **Ventas por Categoría** → Identificación de la categoría más y menos vendida.
- **Calificación Promedio** → Opinión de los clientes sobre cada tienda.
- **Ventas por Producto** → Producto estrella de cada tienda.
- **Costo de Envío** → Gasto total en logística de envíos.

A partir de estos datos, se construye una **comparación visual y numérica** para determinar:
1. La tienda con **mayor revenue** (ingreso total).
2. La tienda con **menor producción y revenue** (candidata a ser vendida).
3. El balance entre ingresos, costos y reputación.

---

# Tecnologías Utilizadas

- **Python **  
- **Pandas** → Limpieza y análisis de datos.  
- **Matplotlib / Seaborn** → Visualización de resultados.  
- **Google Colab** → Ejecución del análisis.  

---

# Flujo del Análisis

1. **Carga de datos** desde 4 archivos CSV (uno por tienda).
2. **Combinación** en un único DataFrame para análisis global.
3. **Cálculo de métricas clave**:
   - Ventas totales.
   - Categoría más y menos vendida.
   - Calificación promedio.
   - Producto más vendido.
   - Costo total de envío.
4. **Visualización**:
   - Gráficos de barras para ventas, costos y calificaciones.
   - Gráficos de pastel para distribución de categorías.
   - Ranking de productos más vendidos.
5. **Conclusión**:
   - Identificación de la tienda más rentable.
   - Identificación de la tienda menos rentable (candidata a venta).


# Resultados Clave

| Tienda   | Ventas Totales | Calificación Promedio | Costo Envío Total | Categoría más vendida | Producto más vendido |
|----------|---------------:|----------------------:|------------------:|-----------------------|----------------------|
| Tienda 1 | ₡1,150,880,000 | 3.98 ⭐ | ₡61,377,900 | Electrónicos | TV LED UHD 4K |
| Tienda 2 | ₡1,116,344,000 | 4.04 ⭐ | ₡59,485,100 | Electrónicos | iPhone 15 |
| Tienda 3 | ₡1,098,020,000 | 4.05 ⭐ | ₡58,516,600 | Electrónicos | Refrigerador |
| Tienda 4 | **₡1,038,376,000** | 4.00 ⭐ | **₡55,317,400** | Electrónicos | iPhone 15 |

---

# Conclusión y Recomendación

- **Mayor revenue**: Tienda 1 (más atractiva si el objetivo es vender la más valiosa).  
- **Menor revenue y producción**: Tienda 4 (candidata lógica para vender si se busca deshacerse de la menos rentable).  
- **Mejor reputación**: Tienda 3 (clientes más satisfechos).  

En términos estratégicos:
- **Vender Tienda 4** → libera recursos de la tienda menos rentable.
- **Vender Tienda 1** → genera mayor ganancia inmediata por su alto valor de mercado.

# Autor

Yustin Baltodano
