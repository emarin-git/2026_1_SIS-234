# Proyecto final — Prototipo de Sistema IoT con AWS y Alexa

**Carrera:** Ingeniería de Sistemas
**Asignatura:** SIS-234

---

## 1. Descripción del proyecto

Se deberá diseñar e implementar un **Sistema IoT** compuesto por:

- Uno o varios **Objetos Inteligentes** con sensores y actuadores que cumplan una funcionalidad práctica, integrados a AWS IoT Core y con **Shadows**.
- Alexa frontend mediante la interfaz de pruebas (Pestaña Test en Alexa Developer Console).
- Alexa backend como función AWS Lambda.
- AWS IoT Rules + funciones AWS Lambda para procesar y almacenar los datos del objeto inteligente, y para incluir lógica de negocio si la aplicación lo requiere.
- Reportes y dashboards para la toma de decisiones.

**Funcionamiento del sistema:**
1. El objeto inteligente deberá:
- Conectarse a una red inalámbrica Wi-Fi parametrizable mediante un portal cautivo (Utilizar libreria WiFiManager).
- Capturar datos del entorno con sus sensores.
- Reportar el estado de sus sensores a AWS IoT Core.
- Recibir comandos de AWS IoT Core a través de su Shadow para controlar sus actuadores.
- Procesar lógica de negocio si la aplicación requiere que el procesamiento se realice en el **Edge**.
2. Alexa deberá:
- Recibir comandos del usuario.
- Interactuar con el Shadow del objeto a través de su backend en AWS haciendo consultas y modificaciones al Shadow.
3. AWS IoT Rules + funciones AWS Lambda:
- Procesar y almacenar los datos del objeto inteligente en una base de datos NoSQL (DynamoDB).
- Ejecutar la lógica de negocio si la aplicación requiere procesamiento en la **Nube**.
4. La plataforma de visualización gráfica deberá:
- Presentar información relevante para la toma de decisiones. Puede utilizarse QuickSight, Tableau, Power BI o Jupyter Notebooks.

---

> Nota: Cada grupo deberá definir sus requerimientos funcionales, no funcionales y la lógica de los algoritmos de control.

---

## 2. Entregables

### 2.1 Prototipo Funcional
Se deberá demostrar un prototipo del o de los objetos inteligentes completamente operativos e integrados a AWS y Alexa. (Puede realizarse en pequeña escala). Además de la demostración y explicación de los reportes y dashboards creados.

### 2.2 Repositorio de Código y Documentación Técnica
Incluir en un repositorio de GitHub:
1. Código fuente completo y debidamente documentado
2. Documentación Técnica

---

## 3. Evaluación

| Componente | Ponderación |
|-------------|-------------|
| Construcción y presentación del objeto inteligente | 20% |
| Utilización eficiente de AWS y Alexa | 20% |
| Presentación de información relevante | 20% |
| Código y Documentación Técnica | 20% |
| Evaluación individual (Preguntas individuales, dominio del tema y trabajo realizado) | 20% |

> Nota: Cada componente se calificará en una escala de 0 a 5: 0, 4, 8, 12, 16, 20.

---
