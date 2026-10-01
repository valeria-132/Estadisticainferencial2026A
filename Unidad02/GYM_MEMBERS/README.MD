# Acerca del conjunto de datos

Este conjunto de datos ofrece una visión detallada de las rutinas de ejercicio, atributos físicos y métricas de fitness de los miembros del gimnasio.

Contiene **973 muestras** de datos de gimnasios, incluyendo indicadores clave de rendimiento como la frecuencia cardíaca, las calorías quemadas y la duración del entrenamiento. Cada entrada también incluye datos demográficos y niveles de experiencia, lo que permite un análisis exhaustivo de los patrones de forma física, la progresión de los atletas y las tendencias de salud.

## Características clave

| Variable | Descripción |
|---|---|
| **Edad** | Edad del miembro del gimnasio. |
| **Género** | Género del miembro del gimnasio (hombre o mujer). |
| **Peso (kg)** | Peso del miembro en kilogramos. |
| **Altura (m)** | Altura del miembro en metros. |
| **Max_BPM** | Frecuencia cardíaca máxima durante las sesiones de entrenamiento. |
| **Avg_BPM** | Frecuencia cardíaca media durante las sesiones de entrenamiento. |
| **Resting_BPM** | Frecuencia cardíaca en reposo antes del entrenamiento. |
| **Session_Duration (horas)** | Duración de cada sesión de entrenamiento en horas. |
| **Calories_Burned** | Total de calorías quemadas durante cada sesión. |
| **Workout_Type** | Tipo de entrenamiento realizado, como Cardio, Fuerza, Yoga o HIIT. |
| **Fat_Percentage** | Porcentaje de grasa corporal del miembro. |
| **Water_Intake (litros)** | Ingesta diaria de agua durante los entrenamientos. |
| **Workout_Frequency (días/semana)** | Número de sesiones de entrenamiento realizadas por semana. |
| **Experience_Level** | Nivel de experiencia: 1 = principiante, 2 = intermedio y 3 = experto. |
| **IMC** | Índice de Masa Corporal, calculado a partir del peso y la altura. |

## Objetivo del conjunto de datos

Este conjunto de datos es adecuado para científicos de datos, investigadores en salud y entusiastas del fitness interesados en estudiar:

- Hábitos de ejercicio.
- Progresión del estado físico.
- Rendimiento deportivo.
- Intensidad de los entrenamientos.
- Resistencia física.
- Relación entre características demográficas y fisiológicas.
- Factores asociados con el gasto calórico.
- Tendencias relacionadas con la salud y la actividad física.

## Análisis que se pueden realizar

### 1. Análisis exploratorio de datos

Se pueden estudiar:

- Distribución de la edad.
- Distribución del peso y la altura.
- Distribución del IMC.
- Porcentaje de grasa corporal.
- Frecuencia cardíaca máxima, promedio y en reposo.
- Distribución de las calorías quemadas.
- Frecuencia de cada tipo de entrenamiento.
- Distribución de los niveles de experiencia.
- Valores faltantes y valores atípicos.

### 2. Análisis de correlaciones

Algunas relaciones interesantes que se pueden investigar son:

- `Session_Duration` ↔ `Calories_Burned`
- `Avg_BPM` ↔ `Calories_Burned`
- `Workout_Frequency` ↔ `Fat_Percentage`
- `Experience_Level` ↔ `Calories_Burned`
- `Workout_Type` ↔ `Calories_Burned`
- `IMC` ↔ `Fat_Percentage`
- `Age` ↔ `Resting_BPM`

### 3. Comparación entre grupos

Se pueden comparar diferentes grupos de usuarios según:

- Género.
- Nivel de experiencia.
- Tipo de entrenamiento.
- Frecuencia de entrenamiento.

Estas comparaciones pueden realizarse utilizando variables como:

- Calorías quemadas.
- Duración de la sesión.
- Frecuencia cardíaca.
- Porcentaje de grasa corporal.
- IMC.
- Frecuencia semanal de entrenamiento.

## Posibles preguntas de investigación

1. ¿Qué variables están más relacionadas con las calorías quemadas?
2. ¿Las sesiones más largas producen un mayor gasto calórico?
3. ¿Cómo cambia la frecuencia cardíaca según el tipo de entrenamiento?
4. ¿Existe una relación entre el nivel de experiencia y la duración de las sesiones?
5. ¿Qué diferencias existen entre los distintos tipos de entrenamiento?
6. ¿La frecuencia de entrenamiento semanal está asociada con el porcentaje de grasa corporal?
7. ¿Qué factores permiten predecir mejor las calorías quemadas?
8. ¿Existen perfiles diferenciados de usuarios según sus características físicas y rutinas?

## Posibles aplicaciones de Machine Learning

Una aplicación interesante sería predecir las **calorías quemadas** durante una sesión de entrenamiento.

La variable objetivo sería:

```text
Calories_Burned

