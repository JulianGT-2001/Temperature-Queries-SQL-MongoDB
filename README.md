# Repositorio: Sensor de Temperatura - MongoDB

## Introducción
Este repositorio contiene los resultados en formato JSON de diversas consultas realizadas sobre una colección de sensores de temperatura almacenada en MongoDB. Su propósito es servir como material de práctica para el estudio y análisis de bases de datos NoSQL, así como para la comprensión de operaciones básicas, consultas con filtros y agregaciones estadísticas.

## Contenido
- **sensor_data.json**: Contiene 100 registros de ejemplo generados para la colección `sensor`.
- **consultas**: Resultados de consultas ejecutadas en MongoDB, exportadas a JSON, incluyendo:
  - Lecturas por sensor (`count` por sensorId)
  - Promedios, mínimos y máximos de temperatura
  - Lecturas filtradas por rango de fecha (últimas 24 horas)
  - Lecturas con condiciones de estado (`status`) y batería

## Objetivo
Permitir al usuario:
- Visualizar datos de sensores en formato JSON.
- Practicar consultas básicas (`find`, `insert`, `update`, `delete`) en MongoDB.
- Analizar datos mediante filtros y operadores.
- Aplicar agregaciones para obtener estadísticas de interés, como promedio, mínimo, máximo y conteo de registros.

## Uso
1. Clonar el repositorio:
```bash
git clone <url-del-repositorio>
