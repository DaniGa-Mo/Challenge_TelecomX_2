# 📊 Análisis Predictivo de Cancelación de Clientes (Churn Rate) 🏃‍♂️💨

¡Bienvenido! Este proyecto utiliza técnicas de **Machine Learning** para predecir qué clientes tienen mayor probabilidad de cancelar sus servicios en una empresa de telecomunicaciones. El objetivo es transformar datos en estrategias de retención accionables. 🚀

## 📋 Tabla de Contenidos
1. [Resumen del Proyecto](#-resumen-del-proyecto)
2. [Análisis Exploratorio (EDA)](#-análisis-exploratorio-eda)
3. [Preprocesamiento de Datos](#-preprocesamiento-de-datos)
4. [Modelado y Evaluación](#-modelado-y-evaluación)
5. [Conclusiones y Estrategias](#-conclusiones-y-estrategias)

---

## 🎯 Resumen del Proyecto
El "Churn" o cancelación de clientes es uno de los mayores desafíos para las empresas de servicios. En este repositorio, desarrollamos un flujo de trabajo completo: desde la limpieza de datos hasta la creación de modelos predictivos capaces de identificar patrones de abandono. 📉

## 🔍 Análisis Exploratorio (EDA)
Realizamos una investigación profunda de las variables para entender el comportamiento de los clientes:
* **Correlaciones:** Identificamos que el **tipo de contrato** y la **antigüedad** son los factores más determinantes. 🔗
* **Visualizaciones:** Utilizamos *Boxplots* y *Scatter Plots* para ver cómo el gasto mensual y el tiempo de permanencia afectan la decisión de irse. 📈
* **Hallazgos clave:** Los clientes con **fibra óptica** y contratos **mes a mes** representan el mayor riesgo de fuga. 🚨

## ⚙️ Preprocesamiento de Datos
Para que los modelos funcionen correctamente, aplicamos:
* **Codificación:** Transformamos variables categóricas a numéricas. 🔢
* **Escalamiento:** Normalizamos variables como `TotalCharges` para modelos sensibles a la escala (como Regresión Logística). ⚖️
* **Balanceo de Clases:** Usamos técnicas para manejar el desequilibrio entre clientes que se quedan y los que se van. 🔄
* **División de Datos:** Separamos el dataset en **Entrenamiento (80%)** y **Prueba (20%)**. ✂️

## 🤖 Modelado y Evaluación
Comparamos dos aproximaciones distintas para elegir la mejor:

1.  **Regresión Logística:** 📈
    * *Ventaja:* Alta explicabilidad y buena generalización.
    * *Uso:* Ideal para entender el impacto directo de cada variable.
2.  **Random Forest (Bosque Aleatorio):** 🌲🌲
    * *Ventaja:* Gran capacidad para capturar relaciones complejas no lineales.
    * *Resultado:* Fue el modelo con mejor **F1-Score** y **Exactitud (~85%)**.

### 📊 Métricas evaluadas:
* **Exactitud (Accuracy):** ¿Qué tan bien predice en general?
* **Recall (Sensibilidad):** ¿Cuántos de los que realmente se fueron logramos atrapar? (Nuestra métrica más importante). 🎯
* **Matriz de Confusión:** Para visualizar falsos positivos y falsos negativos.

## 💡 Conclusiones y Estrategias
El modelo nos permitió proponer 4 estrategias clave de negocio:
1.  **Migración de Contratos:** Incentivar el paso de contratos mensuales a anuales. 📑
2.  **Fidelización Temprana:** Reforzar el soporte en los primeros 12 meses de vida del cliente. 🤝
3.  **Digitalización:** Promover el pago automático para reducir la fricción mensual. 💳
4.  **Revisión de Valor:** Mejorar la oferta en el segmento de fibra óptica. 🌐

---

## 🛠️ Tecnologías Utilizadas
* **Python 🐍**
* **Pandas & Numpy** (Manipulación de datos)
* **Matplotlib & Seaborn** (Visualización)
* **Scikit-Learn** (Machine Learning)

---
*Proyecto realizado como parte del análisis de retención de clientes - 2024.* ✌️

---

**👨‍💻Autor**

**Daniel Gallardo**

*Analista Junior de Machine Learning*

---
