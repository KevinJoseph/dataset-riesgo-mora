# Dataset – Riesgo de Mora de Clientes

Este repositorio contiene un dataset simulado utilizado con fines académicos para el desarrollo de un modelo de **Aprendizaje Automático orientado a la predicción del riesgo de mora de clientes**.  
El dataset ha sido diseñado siguiendo principios de **Tidy Data** y representa patrones realistas observados en contextos empresariales de evaluación crediticia.

---

## Descripción de las columnas

| Columna | Descripción |
|------|------------|
| **Ingreso** | Ingreso mensual del cliente expresado en soles. Representa la capacidad económica del cliente para cumplir con sus obligaciones financieras. |
| **HistorialBueno** | Indicador del comportamiento crediticio previo del cliente. Valor **1** indica buen historial de pago y **0** indica historial negativo. |
| **AntiguedadLaboralMeses** | Número de meses que el cliente ha permanecido en su empleo actual. Se utiliza como indicador de estabilidad laboral. |
| **NumeroDependientes** | Cantidad de personas que dependen económicamente del ingreso del cliente. Un mayor número implica mayor presión financiera. |
| **Pago** | Variable objetivo del modelo. Valor **1** indica que el cliente pagó su obligación y **0** indica que incurrió en mora. |

---

## Uso del dataset

Este dataset puede ser utilizado para:
- Modelos de **clasificación supervisada**
- Análisis de **riesgo crediticio**
- Prácticas académicas de **regresión logística**
- Evaluación de métricas como *accuracy*, *precision*, *recall* y *f1-score*

---

## Consideraciones

- Los datos han sido generados con fines **académicos**.
- No contienen información personal real.
- El dataset no debe ser utilizado para decisiones financieras reales sin validación adicional.

---

## Licencia

Este proyecto se distribuye únicamente con fines educativos.
