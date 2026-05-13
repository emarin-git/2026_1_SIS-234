# Práctica 4 — Objeto Inteligente con AWS y Alexa

**Carrera:** Ingeniería de Sistemas
**Asignatura:** SIS-234

---

## 1. Nombre de la Actividad Evaluativa

**Integración de un objeto inteligente con AWS y Alexa.**

---

## 2. Propósito de la Actividad Evaluativa

Evaluar el desarrollo de los siguientes saberes:

### 2.1 Saber Conceptual
- Librerías y plataformas en la nube para el IoT: AWS IoT Core, AWS Lambda functions, AWS DynamoDB, AWS Athena.
- Herramientas de AI: Amazon Alexa.
- Analítica de datos para el IoT.

### 2.2 Saber Procedimental
- Implementa protocolos de aplicación con integración en la nube: MQTT.
- Implementa sistemas integrados con plataformas en la nube.

### 2.3 Saber Actitudinal (Saber Ser)
- Disposición a realizar prácticas y ejercicios en equipo.
- Responsabilidad en sus asignaciones y prácticas.

---

## 3. Descripción de la Actividad

Se deberá diseñar e implementar un **sistema distribuido** compuesto por:

- Uno o varios **Objetos Inteligentes** con sensores y actuadores que cumplan una funcionalidad práctica, integrado a AWS IoT Core y con **Shadow**.
- Alexa frontend mediante la interfaz de pruebas.
- Alexa backend como función Lambda en AWS.
- AWS IoT Rules + AWS Lambda functions para procesar y almacenar los datos del objeto inteligente, y para incluir lógica de negocio si la aplicación lo requiere.
- AWS Athena conectado a DynamoDB para realizar consultas de los datos almacenados.

**Funcionamiento del sistema:**
1. El objeto inteligente deberá:
- Capturar datos del entorno con sus sensores.
- Reportar el estado de sus sensores a AWS IoT Core.
- Recibir comandos de AWS IoT Core a través de su Shadow para controlar sus actuadores.
- Procesar lógica de negocio si la aplicación requiere que el procesamiento se realice en **Edge**.
2. Alexa deberá:
- Recibir comandos del usuario.
- Interactuar con el Shadow del objeto a través de su backend en AWS haciendo consultas y modificaciones al Shadow.
3. AWS IoT Rules + AWS Lambda functions:
- Procesar y almacenar los datos del objeto inteligente en una base de datos NoSQL (DynamoDB).
- Incluir lógica de negocio si la aplicación requiere procesamiento en la **Nube**.
4. AWS Athena:
- Permitir el realizar consultas SQL de los datos almacenados en DynamoDB. Los grupos deberán definir queries que obtengan información útil para un posterior análisis o para la toma de decisiones (Aún no es necesario implementar la visualización gráfica de la información, solo deberán mostrar las consultas y sus resultados en formato tabla).

> Nota: Cada grupo deberá definir sus requerimientos funcionales, no funcionales y la lógica de los algoritmos de control.

---

## 4. Entregables

### 4.1 Prototipo Funcional
Se deberá presentar un prototipo completamente operativo que demuestre la integración entre el objeto inteligente con AWS y Alexa.

### 4.2 Informe Técnico (Formato Digital)

El informe debe contener las siguientes secciones mínimas:

1. **Requerimientos Funcionales y No Funcionales**
2. **Diseño del Sistema**
   - Diagrama de bloques
   - Diagrama de circuito
   - Diagrama de arquitectura del sistema
   - Diagramas estructurales y de comportamiento
   - Diseño de la skill de Alexa
   - Diseño de reportes (mockups) con información relevante para la toma de decisiones
   - Diseño del modelo de datos (tablas, columnas, tipos de datos, relaciones, etc.) para DynamoDB
3. **Implementación**
   - Código fuente documentado
   - Configuraciones en Alexa
   - Configuraciones en AWS
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
| **4 - Excelente** | Incluye diagramas completos. Los diagramas permiten comprender totalmente el sistema y su secuencia de ejecución. |
| **3 - Satisfactorio** | Incluye diagramas claros que explican el funcionamiento general del sistema. |
| **2 - Satisfactorio con recomendaciones** | Incluye diagramas incompletos o con poca claridad. |
| **1 - Necesita mejorar** | Falta uno o más diagramas esenciales. |

---

### 7.2 Desarrollo e Implementación

| Nivel | Descripción |
|----------|---------------|
| **4 - Excelente** | Código bien estructurado, modular (POO) donde se aplique o funcional (Serverless), documentado y con buenas prácticas. Prototipo completamente funcional. |
| **3 - Satisfactorio** | Código estructurado y funcional, con documentación básica. |
| **2 - Satisfactorio con recomendaciones** | Código funcional pero con mala organización o sin estándares claros. Prototipo funcional pero con fallas. |
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