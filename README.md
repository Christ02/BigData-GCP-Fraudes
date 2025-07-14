#  ig Data en GCP

Este repositorio contiene dos implementaciones de arquitecturas de Big Data en Google Cloud Platform (GCP): procesamiento por lotes (batch) y procesamiento en tiempo real (streaming).

---

## 🗂️ 1. GCP Batch: Auto Sales
**Objetivo:** Transformar y analizar datos históricos de ventas de automóviles.

**Componentes:**
- **Cloud Storage:** Almacenamiento de archivos CSV.
- **Cloud Data Fusion:** Pipeline visual ETL sin código.
- **Dataproc (PySpark):** Transformaciones distribuidas.
- **BigQuery:** Consulta y análisis a gran escala.
- **Looker Studio:** Visualización de resultados.
---

## 🔄 2. GCP Lambda: Detección de Fraudes
**Objetivo:** Simular un sistema de detección de fraudes en tiempo real.

**Componentes:**
- **Pub/Sub:** Ingesta continua de eventos.
- **Dataflow:** Procesamiento streaming.
- **BigQuery:** Almacenamiento y análisis.
- **BigQuery ML:** Entrenamiento y predicción de modelos.
- **Looker Studio:** Dashboards en tiempo real.

