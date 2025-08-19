# 📊 Análisis Predictivo de Cancelación - Telecom X

## 📌 Descripción
Este proyecto desarrolla modelos de machine learning para predecir la probabilidad de cancelación de clientes en Telecom X. El objetivo es identificar factores de riesgo clave y proponer estrategias de retención basadas en insights de negocio.

## 📂 Dataset
Se utilizó la base de datos de clientes de Telecom X procesado previamente:
[telecom_clientes.csv]([https://www.google.com](https://drive.google.com/file/d/1J6Yhr6Ff1MW5DAsM8gMQf3qT2rTCFMAT/view?usp=drive_link))

## ⚙️ Proceso

### 1. Limpieza y Transformación
- Codificación de variables categóricas (One-Hot Encoding)
- Normalización de variables numéricas
- Balanceo del dataset para manejar desequilibrio de clases

### 2. Modelado Predictivo
- **Regresión Logística**: Para interpretabilidad de coeficientes
- **Random Forest**: Para importancia de variables y detección de patrones complejos
- Validación cruzada y evaluación rigurosa de métricas

### 3. Análisis de Variables
- Análisis de coeficientes para dirección e impacto
- Importancia de variables por reducción de impureza
- Identificación de factores protectores y de riesgo

## 📊 Principales Gráficas

**Matriz de correlación de variables numéricas**  
<img width="1230" height="1004" alt="image" src="https://github.com/user-attachments/assets/00e4e923-1ee0-4cee-a1d4-b4436f48a441" />


**Top 10 variables con mayor correlación con la variable evasión**  
<img width="1074" height="548" alt="image" src="https://github.com/user-attachments/assets/3db0d84b-c520-4ebd-aa5e-95e0094cc12c" />


**Comparación de modelos**  
<img width="1389" height="616" alt="image" src="https://github.com/user-attachments/assets/f460e5ea-2d6e-4f04-9d51-cc0ed7394083" />
<img width="1389" height="616" alt="image" src="https://github.com/user-attachments/assets/ba301937-ce5c-4a39-a7fb-65657f4bf3a6" />
<img width="1389" height="616" alt="image" src="https://github.com/user-attachments/assets/0b969583-3b3d-48d1-8a11-2947a7ec2c6a" />


**Matrices de confusión comparativas**  
<img width="1383" height="1181" alt="image" src="https://github.com/user-attachments/assets/e709c9a3-f64b-4fc2-8bb8-146ef73be179" />


**Variables clave por modelo**  
<img width="1189" height="790" alt="image" src="https://github.com/user-attachments/assets/8eef0451-a8ba-4a1d-90f8-b60ff1a5029e" />
<img width="1189" height="790" alt="image" src="https://github.com/user-attachments/assets/8592e876-622e-4b82-bf90-307c5fa026d5" />


## 🔍 Insights Clave

### 📈 Factores de Alto Riesgo
- **Contratos month-to-month**: 3.5x mayor probabilidad de cancelación
- **Pago con cheque electrónico**: Mayor propensión al abandono
- **Clientes nuevos** (0-6 meses): Período crítico de retención

### 🛡️ Factores Protectores
- **Contratos anuales/bienales**: Reducen 45% la cancelación
- **Soporte técnico**: Disminuye 33% la probabilidad de abandono
- **Servicios de seguridad**: Aumentan la retención significativamente

### 📊 Rendimiento de Modelos
- **Regresión Logística**: 76.21% exactitud - Mejor generalización
- **Random Forest**: 73.49% exactitud - Problemas de overfitting

## 🎯 Recomendaciones Estratégicas

### 🚀 Acciones Inmediatas (0-3 meses)
1. **Programa de conversión** de contratos mensuales a anuales
2. **Incentivos por pagos automáticos** y electrónicos
3. **Refuerzo de soporte técnico** con capacitación especializada

### 📅 Estrategias Mediano Plazo (3-6 meses)
1. **Sistema de alertas tempranas** para clientes de alto riesgo
2. **Programa de onboarding** intensivo primeros 90 días
3. **Paquetización inteligente** con servicios de seguridad incluidos

### 🎯 Métricas de Éxito
- **Reducción del 25-30%** en tasa de cancelación anual
- **Incremento del 40%** en conversión a contratos anuales
- **Mejora del 30%** en satisfacción de soporte técnico

## ⚠️ Limitaciones y Próximos Pasos
- **Calidad de datos**: Mejora en recolección de variables clave
- **Validación continua**: Actualización trimestral de modelos
- **Expansión**: Aplicación a otros segmentos de clientes

---

✍️ Autor: *[LeonelPrudencio](https://github.com/LeonelPrudencio/)*

👥 LinkedIn: *[leonel-prudencio](https://www.linkedin.com/in/leonel-antonio-prudencio-castro-9a266b292)*

📌 Proyecto de Análisis de Evasión de Clientes en TelecomX
