# Práctica 1 — Integración de Sensores y Actuadores en un Objeto Inteligente

**Carrera:** Ingeniería de Sistemas
**Asignatura:** SIS-234

---

## 1. Nombre de la Actividad Evaluativa

**Integración de sensores y actuadores en un objeto inteligente.**

---

## 2. Propósito de la Actividad Evaluativa

Evaluar el desarrollo de los siguientes saberes:

### 2.1 Saber Conceptual
- Sensores.
- Actuadores.
- Objetos inteligentes.
- Microcontroladores (MCU).

### 2.2 Saber Procedimental
- Identificación de las funcionalidades de sensores, actuadores y otros dispositivos electrónicos.
- Implementación de controladores y algoritmos necesarios para la correcta interacción entre sensores y actuadores.
- Integración de hardware y software en un sistema funcional.

### 2.3 Saber Actitudinal (Saber Ser)
- Trabajo colaborativo.
- Responsabilidad en la ejecución de las actividades asignadas.
- Orden, sistematicidad y disciplina durante el análisis, diseño y construcción del prototipo.

---

## 3. Descripción de la Actividad

Se deberá diseñar e implementar un **Objeto Inteligente** que integre:

- **1 sensor ultrasónico**.
- **Actuadores:** mínimo **3 LEDs** o **1 servomotor**.
- **1 microcontrolador (MCU)** como unidad de procesamiento.

El microcontrolador deberá ejecutar un **algoritmo de control** que:

1. Procese la información obtenida del sensor ultrasónico.
2. Active los actuadores de acuerdo con criterios previamente definidos.

### 3.1 Ejemplo de requerimientos funcionales

El sistema deberá cumplir, como mínimo, con los siguientes requerimientos:

- Medir la distancia entre el sensor ultrasónico y un objeto.
- Interpretar correctamente la distancia medida.
- Activar los actuadores en función del rango de distancia detectado.

**Ejemplo de comportamiento esperado:**

| Distancia medida | Comportamiento |
|------------------|----------------|
| < 50 cm          | LED rojo parpadeando |
| ≥ 50 cm y < 100 cm | LED naranja parpadeando |
| ≥ 100 cm         | LED verde encendido |

> Nota: Los rangos de distancia y la lógica de control corresponden a un ejemplo, cada grupo deberá definir sus propios requerimientos.

### 3.2 Requerimientos No Funcionales

- El sistema debe ser **estable y confiable**.
- El código debe ser **legible, modular y documentado**.
- El sistema debe permitir **mantenimiento y ampliación futura**.

---

## 4. Entregables

### 4.1 Prototipo Funcional
Se deberá presentar un prototipo completamente operativo que demuestre la integración entre sensores, actuadores y el MCU.

### 4.2 Informe Técnico (Formato Digital)

El informe debe contener las siguientes secciones mínimas:

1. **Requerimientos Funcionales y No Funcionales**
2. **Diseño del Sistema**
   - Diagrama de bloques
   - Diagrama de circuito
   - Diagrama de arquitectura del sistema
   - Diagramas estructurales y de comportamiento
3. **Implementación**
   - Código fuente documentado
4. **Pruebas y Validaciones**
5. **Resultados**
6. **Conclusiones**
7. **Recomendaciones**
8. **Anexos**

---

## 5. Evaluación

### 5.1 Ponderación

| Componente | Porcentaje |
|-------------|-------------|
| Defensa / Demo | 40% |
| Informe Técnico | 60% |

**Detalle:**

- Defensa / Demo:  
  - 20% evaluación individual (dominio del trabajo realizado)  
  - 20% evaluación grupal (funcionalidad del sistema)

---

## 6. Rúbrica de Evaluación del Informe (60%)

### 6.1 Criterios de Evaluación

| Criterio | Puntuación |
|------------|--------------|
| Análisis y diseño | 1 – 4 |
| Desarrollo e implementación | 1 – 4 |
| Pruebas y validaciones | 1 – 4 |
| Resultados y conclusiones | 1 – 4 |

---

## 7. Rúbrica Analítica

### 7.1 Análisis y Diseño

| Nivel | Descripción |
|----------|---------------|
| **4 - Excelente** | Incluye diagramas completos: circuitos, arquitectura estructurales y de comportamiento. Los diagramas permiten comprender totalmente el sistema y su secuencia de ejecución. |
| **3 - Satisfactorio** | Incluye diagramas claros que explican el funcionamiento general del sistema. |
| **2 - Satisfactorio con recomendaciones** | Incluye diagramas incompletos o con poca claridad. |
| **1 - Necesita mejorar** | Falta uno o más diagramas esenciales. |

---

### 7.2 Desarrollo e Implementación

| Nivel | Descripción |
|----------|---------------|
| **4 - Excelente** | Código bien estructurado, modular (POO), documentado y con buenas prácticas. Prototipo completamente funcional. |
| **3 - Satisfactorio** | Código estructurado y funcional, con documentación básica. |
| **2 - Satisfactorio con recomendaciones** | Código funcional pero con mala organización o sin estándares claros. |
| **1 - Necesita mejorar** | Prototipo no funcional o con fallas críticas. |

---

### 7.3 Pruebas y Validaciones

| Nivel | Descripción |
|----------|---------------|
| **4 - Excelente** | Plan de pruebas completo, documentación detallada y análisis de errores. |
| **3 - Satisfactorio** | Plan de pruebas adecuado con documentación básica. |
| **2 - Satisfactorio con recomendaciones** | Plan incompleto con validaciones parciales. |
| **1 - Necesita mejorar** | Pruebas insuficientes o inexistentes. |

---

### 7.4 Resultados y Conclusiones

| Nivel | Descripción |
|----------|---------------|
| **4 - Excelente** | Resultados cuantificables, análisis crítico y recomendaciones técnicas. |
| **3 - Satisfactorio** | Resultados medibles con conclusiones coherentes. |
| **2 - Satisfactorio con recomendaciones** | Resultados limitados, conclusiones básicas. |
| **1 - Necesita mejorar** | Resultados poco claros o no medibles. |

---

# 8. Sugerencias Técnicas para Mejorar la Actividad

Para elevar el nivel técnico y académico del proyecto, se recomienda:

### 8.1 Mejoras en Software
- Implementar **filtrado de ruido en la lectura del sensor** (promedios móviles).
- Programación modular.
- Manejo de excepciones.
- Registro de datos (logging).

### 8.3 Pruebas Avanzadas
- Pruebas de estrés.
- Validación de precisión del sensor.
- Medición de error porcentual.
- Análisis de latencia.

### 8.4 Documentación
- Uso de diagramas UML.

---

## 9. Criterios de Calidad Esperados

- Código limpio y documentado.
- Diseño modular.
- Uso de estándares de nomenclatura.
- Diagramas claros.
- Resultados cuantificables.

---

## 10. Entrega Final

- Repositorio GitHub con:
  - Código fuente.
  - Documentación técnica.
  - Informe en formato Markdown.

---