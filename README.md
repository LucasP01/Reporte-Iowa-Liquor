# Análisis de Ventas de Licor en Iowa (EE.UU.) - Power BI

<div align="center">  
  <a href="https://app.fabric.microsoft.com/groups/me/reports/b922ce3d-ba3d-45b2-b754-d6a7fa14c1b4/f4644cd8da60b5e62232?experience=power-bi" target="_blank">
    <img src="https://drive.google.com/uc?export=view&id=15LYfkCtUpGMTswVbMlHq6naVugUWVjQR" width="300px" alt="Reporte Power BI">
  </a>
  
  <br>  
  <sub><i style="color:gray;">🔗 Haz clic en la imagen para abrir el reporte</i></sub>
</div>

___
## 📌 Fuentes de Datos  
Este dashboard fue construido con datos reales de ventas de licor en Iowa (EE.UU.), obtenidos de [Kaggle](https://www.kaggle.com/). Para mejorar los tiempos de carga, se utilizó una **muestra** del dataset original.  

- **Formato del dataset:** Archivo `.csv` llamado **"Iowa Liquor Sales"**.  
- **Frecuencia de actualización:** El reporte fue creado con fines educativos y no recibirá actualizaciones. Sin embargo, si fuera necesario, se puede obtener el dataset completo con datos actualizados hasta **febrero de 2025**.  

---


___

## 🍾 Situación Problemática  
El **Departamento de Comercio de Iowa** exige que todas las tiendas que vendan alcohol embotellado para consumo fuera de las instalaciones tengan una licencia de venta de bebidas alcohólicas de clase **"E"**.  

Este departamento registra todas las ventas realizadas por estas tiendas y publica los datos como **open data**. El conjunto de datos incluye información sobre:  
✔ Nombre y tipo del producto.  
✔ Precio y cantidad vendida.  
✔ Ubicación de las ventas.  

### **Objetivo del Análisis**  
Explorar los datos y responder preguntas clave sobre la venta de alcohol en Iowa, permitiendo tomar decisiones basadas en información real.  

___

## 📍Pasos del proyecto

### **1️⃣ Carga de Datos**  
- Los datos fueron importados en **Power BI Desktop** desde un archivo `.csv`.  

### **2️⃣ Definición de Preguntas de Negocio**  
- Se establecieron las preguntas clave que podrían hacer colegas o superiores para orientar el análisis.  

### **3️⃣ Limpieza y Modelado de Datos**  
- Se estructuró el modelo de datos en **Power BI**, creando:  
  - **Tabla de hechos** (Fact Invoices).  
  - **Tablas de dimensión** (productos, tiendas, fechas, etc.).  
  - **Dimensión de calendario** para organizar las fechas correctamente.  

 <img src="https://drive.google.com/uc?export=view&id=1jGzvDXNgHk6frqW3Wo4mTnFg05DZVKrX" width="800px" alt="Reporte Power BI">
 
### **4️⃣ Creación de Medidas DAX**  
Se crearon **medidas en DAX** para realizar cálculos avanzados. DAX (Data Analysis Expressions) es el lenguaje de formulas que utilizamos en Power BI para crear medidas y cálculos personalizados) las cuales van a servir para hacer visualizaciones de calidad. Entre ellas podemos destacar las medidas utilizadas para la creación de los Ranking, medidas de totales, promedios y porcentajes.

<img src="https://drive.google.com/uc?export=view&id=1q2-nT4Cl0OvOvphvodqYukYyVM7tljg8" width="500" > Esta fórmula en DAX calcula los litros vendidos sumando el volumen de todas las botellas vendidas en las facturas. 

<img src="https://drive.google.com/uc?export=view&id=13lIxIGnW8eYWcvt73g8TeW72fqMIkJk8" width="500" > Esta calcula el Ticket Medio, que representa el valor promedio de cada unidad vendida.

<img src="https://drive.google.com/uc?export=view&id=1LrYUDawpZOcUTs8-VejrxJmw7HJpJ5xD" width="500" > Esta medida calcula el total de ventas asegurando que, si no hay datos, el resultado sea 0 en lugar de BLANK()

### **5️⃣ Creación de Visualizaciones** * Se seleccionaron los gráficos adecuados según el tipo de dato. * Se aseguró que la información fuera clara y fácil de interpretar.

### **6️⃣ Formato y Diseño del Dashboard** * Se aplicaron segmentaciones, filtros y estilos visuales para mejorar la experiencia del usuario.”

<img src="https://drive.google.com/uc?export=view&id=19Hd9FPJjpGLd0SQpUJx8jBlWgIXj7Fmq" width="600" >
<img src="https://drive.google.com/uc?export=view&id=1HP4jNOHvKimDf42VGyjWiWlPyC32Ol6n" width="600" >

### **7️⃣ Publicación y Feedback** * El reporte fue publicado en **Power BI Service** y compartido con la organización. * Se programaron reuniones para recibir retroalimentación y mejorar el análisis

<img src="https://drive.google.com/uc?export=view&id=150Ixy6L2wfOQkgvhU1cGTXhFAMbhRBaS" width="400" > 



