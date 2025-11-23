# Tarea 4 - Almacenamiento y Consultas de Datos en Big Data

## 📊 Proyecto: Análisis de YouTube Analytics con MongoDB

### 👥 Integrantes del Grupo
- Wilson Stiven Rojas Diaz

**Curso:** Big Data (202016911)  
**Universidad:** UNAD - Universidad Nacional Abierta y a Distancia  
**Fecha:** Noviembre 2025

---

## 📋 Descripción del Proyecto

Este proyecto desarrolla una base de datos NoSQL en **MongoDB** utilizando el dataset *YouTube Analytics Data* proveniente de Kaggle.  
Se analiza información de 537 videos, incluyendo vistas, likes, comentarios, categorías, métricas de engagement y datos del canal.

MongoDB es una herramienta adecuada para este tipo de datos porque permite almacenar información semi–estructurada en documentos flexibles y realizar consultas avanzadas utilizando agregaciones.

---

## 🎯 Objetivos del Proyecto

- Comparar los principales modelos de bases de datos NoSQL.  
- Diseñar un modelo orientado a documentos para datos de YouTube.  
- Importar datos reales a MongoDB utilizando MongoDB Compass.  
- Ejecutar consultas CRUD, filtros con `$expr` y agregaciones.  
- Analizar métricas de popularidad y engagement en YouTube.

---

## 🗄️ Dataset Utilizado

**Fuente:**  
https://www.kaggle.com/datasets/shaistashahid/youtube-analytics-data

**Registros:** 537 videos  
**Principales campos:**
- Title  
- channel_title  
- published_at  
- view_count  
- like_count  
- comment_count  
- category_id  
- engagement_rate  

---

## 🚀 Instalación y Configuración

### 1️⃣ Instalar MongoDB Community Server

Descargar desde el sitio oficial:  
https://www.mongodb.com/try/download/community

Durante la instalación se seleccionó:

- **MongoDB Server**
- **MongoDB Compass** (interfaz gráfica)

### 2️⃣ Abrir MongoDB Compass

Se abre desde el menú de Windows como **MongoDB Compass**.

### 3️⃣ Crear la base de datos

En Compass:

1. Clic en **"Create Database"**  
2. Nombre de la base: **base_youtube**  
3. Nombre de la colección: **youtube_video**

### 4️⃣ Importar el dataset

1. Abrir la colección `youtube_video`
2. Clic en **"ADD DATA"**
3. Seleccionar **"Import Data"**
4. Elegir el archivo CSV descargado de Kaggle
5. Confirmar la importación

✔ Esto cargó las **537 filas** en MongoDB sin usar comandos de consola.

---


---

## 🔍 Consultas Realizadas

### ✔ Operaciones CRUD
- Insertar documentos  
- Consultar datos  
- Actualizar campos  
- Eliminar registros  

### ✔ Consultas con `$expr`
- Likes > Comentarios  
- Likes = Comentarios  
- Likes < Comentarios  
- Comparación entre tasa de likes y tasa de comentarios  
- Videos con +100k vistas y likes > comentarios  

### ✔ Agregaciones
1. Conteo de videos por categoría  
2. Promedio de vistas por categoría  
3. Top 10 videos más vistos  
4. Engagement promedio por canal  

---

## 📊 Principales Resultados

- **Categoría predominante:** ID 27 (150 videos)  
- **Video más visto:** *“Making a beat with a BABY!”* – 369M vistas  
- **Canal con mayor engagement:** FactTechz  
- **Contenido dominante:** Formato tipo YouTube Shorts  

---

## 📝 Referencias

- MongoDB Documentation (2024)  
- Dataset: YouTube Analytics – Kaggle  
- Evaluación comparativa de bases NoSQL (Miranda et al., 2023)

---

## 👨‍💻 Autores
Wilson stiven rojas diaz
Proyecto desarrollado para el curso Big Data – UNAD  
Noviembre 2025
