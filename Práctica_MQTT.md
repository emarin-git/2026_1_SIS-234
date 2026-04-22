# Práctica MQTT — Integración de un Objeto Inteligente con MQTT

**Carrera:** Ingeniería de Sistemas
**Asignatura:** SIS-234

---

## 1. Nombre de la Actividad Evaluativa

**Integración de un objeto inteligente con una aplicación móvil y una herramienta de IA con la ayuda de MQTT y MCP.**

---

## 2. Propósito de la Actividad Evaluativa

Evaluar el desarrollo de los siguientes saberes:

### 2.1 Saber Conceptual
- MQTT (Message Queuing Telemetry Transport).
- Herramientas de IA: MCP Agents.

### 2.2 Saber Procedimental
- Implementa protocolos de aplicación con integración en la nube: MQTT.

### 2.3 Saber Actitudinal (Saber Ser)
- Disposición a realizar prácticas y ejercicios en equipo.
- Responsabilidad en sus asignaciones y prácticas.

---

## 3. Descripción de la Actividad

Se deberá diseñar e implementar un **sistema** compuesto por:

- Un **Objeto Inteligente** con un sensor ultrasónico y con actuadores (mínimo 3 LEDs o 1 servomotor)
- Una aplicación móvil que implementa el protocolo MQTT(Ej. IoT MQTT Panel)
- Un broker en la nube de uso libre MQTT (Ej. HiveMQ)
- Una herramienta de IA (Claude Desktop)

**Funcionamiento del sistema:**
1. El objeto inteligente deberá:
- Publicar información de su sensor.
- Estar suscrito para recibir comandos para activar/desactivar sus actuadores.
2. La aplicación móvil deberá:
- Desplegar la información del sensor de manera gráfica, no textual.
- Enviar comandos al objeto inteligente para activar/desactivar sus actuadores.
3. La herramienta de IA deberá:
- Interpretar lenguaje natural para mostrar datos del sensor o ejecutar comandos sobre los actuadores del Objeto Inteligente.

---

## 4. Entregables

### 4.1 Prototipo Funcional
Se deberá presentar un prototipo completamente operativo que demuestre el funcionamiento del sistema.

### 4.2 Informe Técnico (Formato Digital)

El informe debe contener las siguientes secciones mínimas:

1. **Implementación**
   - Código fuente documentado
   - Configuraciones realizadas
2. **Anexos**

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
| Desarrollo e implementación | 1 – 4 |

---

## 7. Rúbrica Analítica

### 7.1 Desarrollo e Implementación

| Nivel | Descripción |
|----------|---------------|
| **4 - Excelente** | Código bien estructurado, modular (POO), documentado y con buenas prácticas. Prototipo completamente funcional. |
| **3 - Satisfactorio** | Código estructurado y funcional, con documentación básica. |
| **2 - Satisfactorio con recomendaciones** | Código funcional pero con mala organización o sin estándares claros. |
| **1 - Necesita mejorar** | Prototipo no funcional o con fallas críticas. |

---