# Análisis ConnectaTel

Este repositorio contiene el análisis realizado durante el proyecto final del Sprint 7.
El objetivo es evaluar el comportamiento de los clientes de una empresa de telecomunicaciones en México y en Colombia, ConnectaTel, de 2022 hasta 2024.

Trabajé con 3 datasets:
plans.csv → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
users.csv → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
usage.csv → detalle del uso real de los servicios (llamadas y mensajes)

Los datasets contienen valores ausentes, sentinels y outliers que hay que procesar antes de cualquier analisis de datos.
Las etapas de analisis son las siguientes: Cargar → Explorar → Detectar problemas → Limpiar → Calcular estadísticas → Visualizar → Detectar outliers → Segmentar → Generar insights → Publicar en GitHub 


## Abrir el notebook en Google Colab:
Abre en [Google Colab](https://colab.research.google.com/drive/1dp1dzzftRMGFCjh8UIzlZ7jKf_Y_ygdu?usp=sharing)

## Cómo reproducir el análisis
1. Abre `notebooks/S7 Version-Estudiante-Project-ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)
