# Proyecto de Análisis de Datos: Presupuesto Público Nacional de Argentina 2025

## 📊 Acerca del proyecto
Este proyecto es un análisis integral de la ejecución del Presupuesto del año 2025, desarrollado en Power BI. El objetivo principal es poder transformar los datos proporcionados por el Gobierno Nacional en información estratégica, respondiendo preguntas clave acerca de la distribución del gasto, la eficiencia de las dependencias estatales y el impacto territorial del presupuesto, específicamente en la provincia de San Juan.

## 🛠️ Stack Tecnológico
- **Herramienta principal**: Power BI
- **Procesamiento de Datos (ETL)**: Power Query
- **Modelado y Cálculos**: Dax
- **Diseño visual del informe**: Canva y Power BI

## ⚙️ Limpieza, transformación y carga de los datos (ETL)
EL dataset original provisto por el *Ministerio de Economía de la Nación* a través de datos.gob.ar consistía en más de 113.000 registros. Las tareas de limpieza y modelado incluyeron los siguientes apartados:
- Eliminación de columnas redundantes para optimizar el tamaño y peso del modelo.
- Ajustes de tipos financieros para evitar errores de precisión decimal.
- Creación de medidas DAX personalizadas para escalar los montos de millones a **billones de pesos**, facilitando la lectura y comprensión de los resultados.

## 💡 Hallazgos Clave (Insights)
1. **El Gigante Previsional**: Mediante gráficos de dispersión para poder detectar valores atípicos (outliers), se comprobó que el programa "Prestaciones Previsionales" se despega por completo del resto de programas de la administración pública en volumen de gasto.
2. **La Regla de Pareto en la Administración**: Un análisis visual confirma que una mínima fracción de los programas estatales concentra la inmensa mayoría del presupuesto, confirmando la distribución 80/20 planteada por Vilfredo Pareto.
3. **Impacto Territorial**: Al tomar los datos de la provincia de San Juan, se observó que alcanzó una ejecución acelerada del presupuesto, superando el 120% de su límite vigente inicial. Dicha tendencia se extiende a Mendoza y, en menor medida, a San Luis.
4. **La Estructura Real**: El agrupamiento por "Sector de Gasto" y "Área Funcional" demuestra que los "Servicios Sociales" y la "Deuda Pública" dominan la matriz de gasto, desmitificando el peso de otras áreas del estado.

## 📂 Contenido del Repositorio
* `Informe Presupuesto APN 2025`: Presentación estática con los dashboards finales y conclusiones visuales.
* `Presupuesto_2025.pbix`: Archivo fuente de Power BI con el modelo de datos, medidas DAX y visualizaciones interactivas.

---

*Desarrollado por Brian Alaníz - Estudiante de Ciencias de la Computación*