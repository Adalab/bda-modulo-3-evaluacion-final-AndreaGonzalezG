# Análisis comportamiento de clientes aerolínea

_Este proyecto tiene como objetivo analizar el comportamiento de los clientes que forman parte del plan de lealtad de una aerolínea. A través de este análisis, se buscan identificar tendencias o patrones valiosos que puedan apoyar la toma de decisiones estratégicas de la empresa._

## Datos utilizados  🗂️
El conjunto de datos está compuesto por dos archivos principales:
1. _Customer Flight Analysis.csv_: Contiene información detallada sobre la actividad de vuelo de los clientes, como el número de vuelos reservados, distancia volada, puntos de lealtad acumulados y redimidos, y los costos asociados a la redención de puntos.
2. _Customer Loyalty History.csv_: roporciona un perfil detallado de los clientes, que incluye su ubicación, nivel educativo, ingresos, estado civil, y detalles sobre su membresía en el programa de lealtad (como tipo de tarjeta, valor de vida del cliente, y fechas de inscripción y cancelación).
   
Después de limpiar y procesar estos datos, se creó un archivo consolidado:_Customer_limpio.csv_, que combina la información de ambos archivos originales.



## Fases  🟧

### **Fase 1. Exploración y Limpieza**
- Exploración inicial para identificar problemas como valores nulos, atípicos o faltantes en columnas relevantes.
- Implementación de funciones para la limpieza y transformación de datos.
- Imputación de valores nulos para garantizar la consistencia de la información.

Ejemplo:
**Gráfica 1. _Outliers Salary_**

![salary1](https://github.com/user-attachments/assets/b2914d7c-a23e-4997-90c4-5cd29892ef77)

### **Fase 2. Visualización**

Se utilizaron bibliotecas como Seaborn y Matplotlib para generar visualizaciones que respondan a preguntas de negocio específicas.

Ejemplos:

**Gráfica 3. _Proporción clientes por tipo de tarjeta loyalty_**

![output](https://github.com/user-attachments/assets/554ba9cb-9085-4246-b37e-e0e32e369b63)

**Gráfica 4._Distribución de clientes por provincia_**

![output1](https://github.com/user-attachments/assets/5e98ecdc-f60a-4cba-bbe7-d1f41ab38d04)

### **Fase 3. Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo**

Se buscó determinar si existen diferencias significativas en el número de vuelos reservados según el nivel educativo de los clientes. Los pasos realizados incluyeron:
- Preparación y limpieza de los datos.
- Análisis estadístico descriptivo.
- Aplicación de pruebas estadísticas, incluyendo el desarrollo de un A/B testing.


## Librerías utilizadas  🔧
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy.stats`
- `regex`
- `sklearn.impute`
- `sklearn.experimental`


## Autora ✒️

* **Andrea González** 




