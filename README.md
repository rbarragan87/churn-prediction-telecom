# 📉 Predicción de Churn en una Empresa de Telecomunicaciones
**`Ciencia de Datos`** · **`Machine Learning`** · **`Análisis de Negocio`**

---

## 🚀 Introducción

El **churn** (abandono de clientes) representa una pérdida directa y significativa para las empresas de telecomunicaciones: **más de €1.6 millones anuales** en ingresos perdidos solo por clientes que dejan el servicio.  
Este proyecto desarrolla un modelo predictivo que permite identificar anticipadamente a los clientes con mayor riesgo de abandono, facilitando acciones de retención que protejan los ingresos y mejoren la rentabilidad.

---

## 📋 Resumen Ejecutivo

- Impacto económico estimado por churn: **€1.6 millones anuales**  
- Modelos entrenados: Regresión Logística, Random Forest, XGBoost  
- Métrica clave priorizada: **Recall = 0.68**, para maximizar la detección de clientes en riesgo  
- Insights de negocio: adultos mayores, sin pareja ni dependientes, y quienes usan cheque electrónico, presentan mayor riesgo

---

## 🎯 Objetivos del Proyecto

- Identificar factores clave que influyen en el abandono
- Cuantificar el impacto económico del churn
- Construir un modelo predictivo confiable
- Generar insights accionables para áreas de negocio

---

## 🛠️ Herramientas y Tecnologías

- **Lenguaje:** Python  
- **Análisis de datos:** pandas, numpy  
- **Modelado:** scikit-learn, xgboost, imbalanced-learn (SMOTE), Boruta  
- **Visualización:** matplotlib, seaborn  
- **Entorno:** Jupyter Notebook  
- **Control de versiones:** Git y GitHub  
- **Otros:** GridSearchCV, balanceo de clases

---

## 📋 Plan de Trabajo

1. Importación de librerías y datos
2. Análisis inicial y limpieza
3. EDA (Análisis exploratorio)
4. Análisis financiero del churn
5. Selección de variables con Random Forest y Boruta
6. Preprocesamiento: One-Hot, estandarización, SMOTE
7. Modelado: logística, Random Forest, XGBoost
8. Evaluación y selección final (recall prioritario)
9. Insights para negocio
10. Informe de solución en el notebook

---

## 🧩 Datos Utilizados

Se integraron 4 datasets con información de:

- Contratos y clientes
- Servicios contratados
- Historial de pagos y métodos

---

## 📈 Resultados Clave

| Indicador                | Resultado         |
|-------------------------|-------------------|
| Tasa de churn           | 27%               |
| Pérdida mensual         | €139,130.85       |
| Pérdida anual proyectada| €1,669,570        |
| Modelo final            | Regresión Logística |
| Recall                  | 0.69              |
| F1 Score                | 0.65              |
| ROC AUC                 | 0.76              |

---

## 🧠 Insights Destacados

1. Adultos mayores sin pareja ni dependientes = mayor riesgo  
2. *Electronic check* se asocia con más abandonos  
3. Clientes con poca antigüedad tienen más churn  
4. Cargos altos sin beneficios adicionales = más riesgo

---

## 💼 Recomendaciones de Negocio

- Campañas para nuevos clientes
- Incentivar pagos automáticos
- Beneficios para adultos mayores
- Revisar políticas de precios iniciales

---

## 📁 Estructura del Repositorio

```plaintext
Proyecto_Churn/
├── data/
│   ├── raw_data/            # Datos originales sin procesar
│   │   ├── contract.csv
│   │   ├── internet.csv
│   │   ├── personal.csv
│   │   └── phone.csv
│   └── inter/               # Datos intermedios transformados 
│       └── df/
├── modelo/                  # Modelos entrenados
│   └── modelo_churn.pkl
├── notebooks/
│   └── Proyecto_Churn.ipynb
├── scripts/                 # Scripts Python modulares
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📬 Contacto

- 📧 [rbarraganaguilera@gmail.com](mailto:rbarraganaguilera@gmail.com)  
- 📞 [+52 443 942 3290](tel:+524439423290)  
- 💼 [LinkedIn - Roberto Octavio Barragán Aguilera](https://www.linkedin.com/in/roberto-octavio-barragan-aguilera/)
