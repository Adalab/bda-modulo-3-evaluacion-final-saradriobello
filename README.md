
# Evaluación Final: Módulo 3 - Análisis de Datos

## Introducción
Este ejercicio consiste en analizar el comportamiento de los clientes dentro de un programa de lealtad de una aerolínea utilizando dos conjuntos de datos:
- **Customer Flight Analysis.csv**: Contiene información sobre la actividad de vuelo de los clientes.
- **Customer Loyalty History.csv**: Proporciona detalles sobre el perfil de los clientes y su participación en el programa de lealtad.

Los pasos a seguir son una exploración inicial, limpieza, visualización y un análisis adicional para responder preguntas clave sobre los datos y evaluar diferencias significativas en el comportamiento de los clientes.

---

## Estructura del Proyecto

### Fase 1: Exploración y Limpieza de Datos

1. **Exploración Inicial**:
   - Inspección general de los conjuntos de datos.
   - Identificación de valores nulos, atípicos y problemas de consistencia.
   - Unión eficiente de los conjuntos de datos mediante la columna `Loyalty Number`.

2. **Limpieza de Datos**:
   - Eliminación o tratamiento de valores nulos en columnas clave.
   - Verificación de la coherencia en formatos y valores.
   - Identificación y tratamiento de valores duplicados
   - Ajustes necesarios en los tipos de datos para garantizar la correcta manipulación de la información.

---

### Fase 2: Visualización
Usando herramientas como Matplotlib y Seaborn, se crearán visualizaciones para responder las siguientes preguntas:

1. **Distribución de vuelos reservados por mes durante el año**.
2. **Relación entre la distancia de los vuelos y los puntos acumulados**.
3. **Distribución de los clientes por provincia o estado**.
4. **Comparación del salario promedio entre diferentes niveles educativos**.
5. **Proporción de clientes con diferentes tipos de tarjetas de lealtad**.
6. **Distribución de los clientes según su estado civil y género**.

---

### Fase 3 (Bonus): Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo

1. **Preparación de Datos**:
   - Filtrado de columnas `Flights Booked` y `Education`.

2. **Análisis Descriptivo**:
   - Cálculo de estadísticas descriptivas como promedio y desviación estándar por nivel educativo.

3. **Prueba Estadística**:
   - Aplicación de una prueba de hipótesis para determinar si existen diferencias significativas en el número de vuelos reservados entre diferentes niveles educativos.

---


## Resultados Esperados

- Conjuntos de datos limpios y listos para análisis.
- Gráficas claras y detalladas que respondan las preguntas planteadas.
- Análisis estadístico con interpretación de resultados.


