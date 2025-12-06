# Proyecto SQL + Power BI – INACAP  
**Mini Data Warehouse – Diseño, Carga, Transformación y Visualización de Datos**

Este proyecto corresponde a un trabajo académico realizado para INACAP, donde se desarrolló un mini data warehouse utilizando **SQL Server**, con posterior análisis y visualización en **Power BI** mediante **Power Query**. El objetivo fue construir una base de datos funcional, poblarla con datos relevantes y generar un informe visual claro, comprensible y útil para la toma de decisiones.

---

## 📌 Contenido del proyecto

El repositorio incluye:

| Archivo / Carpeta | Descripción |
|------------------|-------------|
| `db/DB_Scripts.sql` | Script SQL completo que **crea la base de datos**, **tablas**, **relaciones** y **carga los datos** necesarios. Permite recrear la BD desde cero. |
| `AquaSafe.pbix` | Informe interactivo de Power BI conectado directamente a SQL Server. Incluye visualizaciones, métricas y paneles. |
| `AquaSafe.pdf` | Versión exportada del informe Power BI para visualización sin Power BI Desktop. |
| `InformeES2_Arriagada_Castro.docx` | Informe académico completo del proyecto: objetivos, análisis, desarrollo técnico, screenshots y conclusiones. |
| `README.md` | Documento principal del repositorio (este archivo). |

---

## 🏗️ Arquitectura del proyecto

### **1. Base de datos en SQL Server**
- Creación de tablas con claves primarias y foráneas.
- Definición de entidades: clientes, empleados, productos/servicios, transacciones, etc.
- Inserción de datos mediante scripts SQL incluidos en `DB_Scripts.sql`.
- Estructura diseñada para análisis descriptivo y exploratorio.

### **2. ETL con Power Query (Power BI)**
- Conexión directa a SQL Server.
- Limpieza de datos:
  - Tipificación de columnas.
  - Eliminación de duplicados.
  - Transformación de valores.
- Modelado en Power BI para facilitar la lectura y creación de visualizaciones.

### **3. Informe en Power BI**
Incluye:
- dashboard principal
- métricas clave
- tablas dinámicas
- gráficos comparativos
- segmentadores
- visualizaciones diseñadas para comprensión rápida

![AquaSafe_page-0001](https://github.com/user-attachments/assets/a12fdf10-82f1-4cdd-9285-2d29f6d53432)


## 🚀 Cómo ejecutar este proyecto

### **1) Crear la base de datos**
1. Abrir **SQL Server Management Studio**.
2. Crear una nueva consulta.
3. Ejecutar el archivo completo `db/DB_Scripts.sql`.

Esto generará todas las tablas y poblará los datos automáticamente.

---

### **2) Abrir el informe en Power BI**
1. Abrir `AquaSafe.pbix` en **Power BI Desktop**.
2. Verificar que la conexión apunta al nombre correcto del servidor SQL local.
3. Si es necesario, actualizar las credenciales.
4. Presionar **Refresh** para que las visualizaciones utilicen la BD recién creada.

---

## 🎯 Objetivos del proyecto

- Comprender el proceso completo de construcción de un mini data warehouse.
- Diseñar un modelo de datos relacional funcional.
- Aplicar procesos de limpieza y transformación realistas.
- Comunicar resultados mediante dashboards profesionales.
- Desarrollar habilidades prácticas para roles de **BI**, **Data Analyst** o **Ingeniería en Datos**.

---

## 🛠️ Tecnologías utilizadas
- **SQL Server**  
- **T-SQL**  
- **Power Query**  
- **Power BI Desktop**  
- **Modelo relacional (DER)**  

---

## 📌 Posibles mejoras futuras
- Separar el script SQL en `01_schema.sql` y `02_data.sql`.
- Añadir un diagrama entidad-relación en formato `.png`.
- Construir medidas DAX adicionales.
- Crear un informe más avanzado con storytelling.

---

## 👤 Autor
**Benjamín Arriagada Achavar**  
INACAP – 2025  
Contacto: benja105.achavar@gmail.com

