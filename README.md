# 📊 Análisis de Evasión de Clientes (Churn) - TelecomX LATAM

Este proyecto corresponde a un análisis exploratorio de datos (EDA) aplicado a un dataset de clientes de **TelecomX LATAM**, una empresa ficticia de telecomunicaciones.  
El objetivo principal es **entender los factores que influyen en la evasión de clientes (churn)** y proponer estrategias basadas en datos para reducirla.

---

## 🎯 Objetivos del Proyecto
- Analizar la distribución general de la variable **abandono (churn)**.
- Explorar cómo las **variables categóricas** (género, tipo de contrato, método de pago, servicios adicionales, etc.) influyen en la tasa de abandono.
- Evaluar la relación entre **variables numéricas** (tiempo de contrato, gasto mensual, gasto total) y la evasión.
- Extraer **conclusiones e insights estratégicos** que permitan orientar acciones para la retención de clientes.

---

## 🛠️ Tecnologías Utilizadas
- **Python 3**
- **Pandas** → para limpieza y manipulación de datos.  
- **Matplotlib / Seaborn** → para visualización gráfica.  
- **Google Colab / Jupyter Notebook** → entorno de desarrollo.  

---

## 📈 Análisis Realizado
1. **Limpieza y tratamiento de datos**  
   - Conversión de variables binarias ("Yes/No") a valores booleanos.  
   - Renombrado de columnas al español para mejor interpretación.  
   - Revisión de valores nulos y consistencia de datos.  

2. **Exploración de la variable Churn**  
   - Distribución general de clientes que permanecen vs. los que abandonan.  
   - Visualización mediante gráficos de barras y torta.  

3. **Relación con variables categóricas**  
   - Género.  
   - Tipo de contrato.  
   - Método de pago.  
   - Servicio de internet y servicios adicionales.  

4. **Relación con variables numéricas**  
   - Meses de contrato (tenure).  
   - Cargos mensuales.  
   - Cargos totales.  

5. **Conclusiones e Insights**  
   - Los clientes con contrato mensual presentan mayor probabilidad de abandono.  
   - El pago automático está más asociado a la permanencia.  
   - Clientes nuevos (poco tiempo de contrato) y con bajo gasto total abandonan con mayor frecuencia.  

6. **Recomendaciones estratégicas**  
   - Incentivar contratos de mayor plazo con beneficios.  
   - Promover el pago automático como opción preferida.  
   - Diseñar campañas de fidelización para nuevos clientes.  
   - Mejorar la percepción del servicio de internet y soporte técnico.  

---

## 📂 Estructura del Repositorio
- `TelecomX_LATAM.ipynb` → Notebook principal con todo el análisis.  
- `datos_tratados.csv` → Dataset limpio y preparado para análisis.  
- `informe.html / informe.pdf` → Reporte final con visualizaciones y conclusiones.  

---

## 🚀 Resultados
Este análisis ofrece una **visión integral del churn en TelecomX LATAM**, apoyando la toma de decisiones estratégicas para **reducir la evasión y mejorar la retención de clientes**.  
