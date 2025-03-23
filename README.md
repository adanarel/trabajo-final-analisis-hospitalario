
# 🏥 Análisis de Datos Hospitalarios - Proyecto Final

## 📘 Descripción

Este proyecto corresponde al trabajo final del Bootcamp de Análisis de Datos impulsado por el MITIC. El objetivo fue aplicar todo lo aprendido en herramientas como Python, SQL y Power BI para realizar un análisis integral de un conjunto de datos hospitalarios sintéticos generados por Synthea.

## 🧠 Objetivos

- Aplicar técnicas de limpieza, transformación y análisis exploratorio de datos.
- Visualizar patrones temporales, geográficos y demográficos en la atención médica.
- Desarrollar un dashboard interactivo en Power BI.
- Proponer recomendaciones accionables para la gestión hospitalaria.

## 📁 Estructura del Proyecto

```
📂 data/
   ├── patients.csv
   ├── encounters.csv
   ├── procedures.csv
   ├── payers.csv
   ├── organizations.csv
   ├── data_dictionary.csv
📘 TrabajoFinal.ipynb
📄 citation.txt
```

## 🔍 Dataset

Los datos utilizados fueron generados por el simulador Synthea, que produce historiales clínicos electrónicos sintéticos realistas de pacientes.

> Jason Walonoski et al. *Synthea: An approach, method, and software mechanism for generating synthetic patients and the synthetic electronic health care record*, Journal of the American Medical Informatics Association, 2018.  
[DOI: 10.1093/jamia/ocx079](https://doi.org/10.1093/jamia/ocx079)

## ⚙️ Tecnologías utilizadas

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- SQL
- Power BI
- Google Colab
- Jupyter Notebook

## 🔧 Proceso del Proyecto

1. **Carga de Datos:** Importación y visualización inicial de los archivos CSV.
2. **Limpieza y Transformación:**
   - Conversión de fechas y formatos.
   - Detección y tratamiento de valores nulos personalizados.
   - Normalización de campos categóricos.
   - Validación de claves y relaciones entre tablas.
   - Identificación y tratamiento de outliers mediante IQR y sustitución por la mediana.
3. **Análisis Exploratorio (EDA):**
   - Distribución por género, edad, regiones y organizaciones.
   - Procedimientos más comunes.
   - Frecuencia de encuentros por mes y año.
4. **Análisis Temporal y Geográfico:**
   - Evolución mensual y anual de los procedimientos.
   - Comparación entre organizaciones públicas y privadas.
   - Mapeo de pacientes por región.
5. **Modelado Predictivo:**
   - Modelado preliminar para predecir la duración de la estancia hospitalaria.
6. **Dashboard en Power BI:**
   - Visualizaciones interactivas para explorar los hallazgos clave.
   - Filtros por región, organización y tipo de procedimiento.
7. **Recomendaciones Finales:**
   - Mejora de la planificación hospitalaria.
   - Reforzar infraestructura en regiones con alta carga de procedimientos.
   - Optimización de recursos según estacionalidad y tipo de atención.

## 📊 Dashboard Power BI

> El archivo `.pbix` del dashboard está disponible como parte del entregable.

## 📌 Conclusiones principales

- Las organizaciones privadas presentan una mayor cantidad de procedimientos especializados.
- Hay una concentración de pacientes en ciertas regiones que podría requerir redistribución de recursos.
- Se observaron patrones estacionales en los encuentros hospitalarios que podrían permitir una mejor planificación.
- Las recomendaciones apuntan a reforzar la infraestructura hospitalaria y mejorar la eficiencia operativa.

## 👤 Autor

- **Nombre:** [Ada Narel Noguera Sachelaridi]
- **Curso:** Bootcamp de Análisis de Datos - MITIC - Make It Real
- **Fecha de entrega:** 23 de marzo de 2025
