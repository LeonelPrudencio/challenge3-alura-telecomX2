# 📊 Análisis Predictivo de Cancelación - Telecom X

## 📌 Descripción
Este proyecto desarrolla modelos de machine learning para predecir la probabilidad de cancelación de clientes en Telecom X. El objetivo es identificar factores de riesgo clave y proponer estrategias de retención basadas en insights de negocio.

## 📂 Dataset
Se utilizó la base de datos de clientes de Telecom X procesado previamente:
[TelecomX_procesado]([https://www.google.com](https://drive.google.com/file/d/1J6Yhr6Ff1MW5DAsM8gMQf3qT2rTCFMAT/view?usp=drive_link))

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

**Distribución de cancelación por tipo de contrato**  
![Tipo de Contrato](reports/figuras/distribucion_contrato.png)

**Impacto de variables en cancelación (Coeficientes)**  
![Coeficientes](reports/figuras/coeficientes_logistica.png)

**Importancia de variables - Random Forest**  
![Importancia Variables](reports/figuras/importancia_variables_rf.png)

**Matrices de confusión comparativas**  
![Matrices Confusión](reports/figuras/matrices_confusion.png)

**Análisis de overfitting por modelo**  
![Overfitting Analysis](reports/figuras/analisis_overfitting.png)

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

## 👥 Autor
**Equipo de Ciencia de Datos - Telecom X**  
📧 analytics@telecomx.com

---
**Estado del Proyecto**: ✅ Completado - En fase de implementación  
**Próxima Revisión**: Trimestral con actualización de modelos
