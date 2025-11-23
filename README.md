# Tarea 4 - Almacenamiento y Consultas de Datos en Big Data

## 📊 Proyecto: Análisis de YouTube Analytics con MongoDB

### 👥 Integrantes del Grupo
- [Nombre Estudiante 1]
- [Nombre Estudiante 2]
- [Nombre Estudiante 3]

**Curso:** Big Data (202016911)  
**Universidad:** UNAD - Universidad Nacional Abierta y a Distancia  
**Fecha:** Noviembre 2025

---

## 📋 Descripción del Proyecto

Este proyecto implementa una base de datos NoSQL en **MongoDB** utilizando el dataset *YouTube Analytics Data* de Kaggle.  
El conjunto de datos contiene más de **537 videos** con información relevante como vistas, likes, comentarios, fecha de publicación, métricas derivadas y características del canal.

MongoDB permite almacenar este tipo de información semi–estructurada mediante documentos JSON flexibles y consultas potentes utilizando agregaciones.

### 🎯 Objetivos del Proyecto

- Comparar los principales tipos de bases de datos NoSQL.
- Diseñar e implementar una base de datos NoSQL en MongoDB.
- Realizar consultas CRUD y consultas con operadores `$expr`.
- Aplicar agregaciones para analizar patrones de comportamiento en YouTube.
- Calcular métricas de engagement, tendencias y popularidad.

---

## 🗄️ Dataset Utilizado

**Fuente del Dataset:**  
https://www.kaggle.com/datasets/shaistashahid/youtube-analytics-data

**Número de registros:** 537  
**Principales campos:**

- `Title` — Título del video  
- `channel_title` — Nombre del canal  
- `published_at` — Fecha de publicación  
- `category_id` — Categoría de YouTube  
- `view_count` — Cantidad de vistas  
- `like_count` — Likes recibidos  
- `comment_count` — Comentarios recibidos  
- `engagement_rate` — Métrica derivada  
- `duration_seconds` — Duración del video  

---

## 🚀 Instalación y Configuración

### 🔧 Requisitos Previos

- MongoDB 6.0 o superior  
- MongoDB Shell (mongosh)  
- MongoDB Compass (opcional)  
- Git y terminal bash  

---

## 🛠 Pasos para Reproducir el Proyecto

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/[tu-usuario]/tarea4-mongodb-youtube.git
cd tarea4-mongodb-youtube
