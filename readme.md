# 📊 Análisis de Evasión de Clientes (Churn Rate)

## 🎯 Objetivo del Proyecto
Este proyecto analiza el comportamiento de los clientes de una empresa de telecomunicaciones para identificar los factores que impulsan la evasión (churn). El objetivo es proporcionar **insights basados en datos** que permitan al equipo de marketing y ventas implementar **estrategias de retención efectivas**.

---

## 📁 Estructura del Dataset
El dataset original fue **traducido y limpiado** para facilitar el análisis. Las variables principales incluyen:

### Demografía
- Género  
- Si es adulto mayor  
- Si tiene pareja  
- Si tiene dependientes  

### Servicios
- Telefonía  
- Internet  
- Seguridad en línea  
- Soporte técnico  
- Servicios de streaming  

### Contrato
- Tipo de contrato (mes a mes, anual, bianual)  
- Método de pago  
- Factura digital  

### Finanzas
- Cargos mensuales  
- Cargos totales  
- Permanencia del cliente en meses  

---

## 🛠️ Tecnologías Utilizadas
- **Python 3.12**
- **Pandas** → Manipulación y limpieza de datos
- **Seaborn** → Visualizaciones estadísticas
- **Matplotlib** → Gráficos y análisis visual
- **NumPy** → Operaciones matemáticas y cálculos

---

## 🔍 Hallazgos Principales (Insights)

### 📄 Tipo de Contrato
El contrato **"Month-to-month"** es el mayor predictor de evasión.  
Los clientes sin compromiso a largo plazo presentan una **tasa de cancelación significativamente mayor**.

### ⏳ Permanencia Crítica
La mayoría de los clientes que abandonan el servicio lo hacen **entre los primeros 6 y 12 meses**.

### 💰 Cargos Mensuales
Existe una **correlación positiva entre cargos mensuales altos (>$70)** y la probabilidad de cancelación.

### 🛡️ Servicios de Valor
Los clientes que cuentan con **Soporte Técnico y Seguridad en Línea** muestran **mayor fidelidad y menor tasa de churn**.

---

## 📈 Visualizaciones Destacadas

- **Gráfico de Pastel**  
  Muestra la distribución general de la evasión de clientes (**32.8% churn**).

- **KDE Plots**  
  Comparación de la densidad de permanencia entre **clientes que permanecen** y **clientes que abandonan**.

- **Matriz de Correlación**  
  Mapa de calor que muestra las **relaciones entre variables numéricas** del dataset.

---

## 🚀 Cómo Ejecutar el Proyecto

1. **Clona este repositorio**
```bash
git clone https://github.com/tu-usuario/churn-analysis.git
