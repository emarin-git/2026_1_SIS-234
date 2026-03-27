# Práctica 1 — Integración de Sensores y Actuadores en un Objeto Inteligente

**Carrera:** Ingeniería de Sistemas
**Asignatura:** SIS-234

---

## 1. Nombre de la Actividad Evaluativa

**Integración de objetos inteligentes mediante arquitectura cliente-servidor basada en TCP/IP.**

---

## 2. Propósito de la Actividad Evaluativa

Evaluar el desarrollo de los siguientes saberes:

### 2.1 Saber Conceptual
- Redes de sensores IP sobre IEEE 802.11.
- Modelo TCP/IP.
- Arquitectura cliente-servidor.
- Protocolos de transporte (TCP).

### 2.2 Saber Procedimental
- Configura conectividad en redes IP (WiFi – IEEE 802.11).
- Implementa comunicación cliente-servidor mediante sockets TCP.
- Diseña e implementa un protocolo de aplicación simple para el intercambio de datos entre clientes y servidor.

### 2.3 Saber Actitudinal (Saber Ser)
- Colaboración con sus compañeros.
- Responsabilidad en la ejecución de las actividades asignadas.
- Orden, sistematicidad y disciplina durante el análisis, diseño y construcción del prototipo.

---

## 3. Descripción de la Actividad

Se deberá diseñar e implementar un **sistema distribuido** compuesto por:

- Un **Objeto Inteligente con sensor** ultrasónico (cliente).
- Un **Objeto Inteligente con actuadores** (mínimo 3 LEDs o 1 servomotor) (cliente).
- Un **Servidor TCP (PC)** que actuará como entidad central de control.

**Funcionamiento del sistema:**
1. El objeto con sensor deberá:
- Capturar datos del entorno.
- Enviar la información al servidor mediante comunicación TCP sobre red WiFi (IEEE 802.11).
2. El servidor deberá:
- Procesar los datos recibidos.
- Ejecutar un algoritmo de control definido por el grupo.
- Enviar comandos al objeto actuador.
3. El objeto actuador deberá:
- Recibir instrucciones del servidor.
- Activar los dispositivos según las órdenes recibidas.

> Nota: Cada grupo deberá definir sus requerimientos funcionales, no funcionales y la lógica del algoritmo de control.

---

## 4. Entregables

### 4.1 Prototipo Funcional
Se deberá presentar un prototipo completamente operativo que demuestre la integración entre sensores, actuadores y el sistema distribuido basado en TCP/IP.

### 4.2 Informe Técnico (Formato Digital)

El informe debe contener las siguientes secciones mínimas:

1. **Requerimientos Funcionales y No Funcionales**
2. **Diseño del Sistema**
   - Diagrama de bloques
   - Diagrama de circuito
   - Diagrama de arquitectura del sistema
   - Especificación del protocolo de aplicación
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