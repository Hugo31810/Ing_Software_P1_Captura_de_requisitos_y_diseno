# Railway Incidence Management System – Requirements & Design

Este repositorio contiene la **fase de análisis y diseño** de un sistema software para la **gestión de incidencias en infraestructuras ferroviarias**, desarrollado como parte de la asignatura **Ingeniería del Software** (URJC).

El proyecto se centra en la **captura de requisitos** y el **diseño UML** de una aplicación web orientada a la **detección, predicción y visualización de incidencias** en vías de tren a partir de datos eléctricos.

---

## 🎯 Objetivo del proyecto

El objetivo principal de este proyecto es:

- Analizar un **problema real del dominio ferroviario**
- Identificar y documentar:
  - Requisitos funcionales
  - Requisitos de dominio
- Diseñar la arquitectura del sistema mediante **diagramas UML**
- Justificar las decisiones de diseño adoptadas
- Aplicar una **metodología ágil** para la organización del trabajo

Este repositorio corresponde exclusivamente a la **fase de requisitos y diseño** del sistema.

---

## 🧩 Contexto del sistema

Las vías ferroviarias cuentan con **dispositivos eléctricos** que emiten señales de voltaje para indicar si una vía está ocupada o libre.

El sistema diseñado permite:

- Leer datos de voltaje desde ficheros CSV
- Detectar la ocupación de una vía por un tren
- Identificar y predecir incidencias, como:
  - Ausencia prolongada de datos (> 2 minutos)
  - Saltos bruscos de voltaje (≥ 0.5 V)
- Gestionar la suscripción de usuarios a incidencias
- Visualizar gráficamente los valores de voltaje y las incidencias detectadas

La aplicación se concibe como un **sistema web basado en HTTP/REST**.

---

## 👥 Equipo y roles

El proyecto ha sido desarrollado en equipo, con una asignación clara de roles:

### 🧑‍💼 Project Manager
- **Hugo Salvador Aizpún**

### 🧪 Software Analysts
- **Iván De Rada López**
- **Raúl Vicente Sánchez**
- **Tomás Cano Santa Catalina**

### 🏗️ Software Architects
- **Pablo Sastre Noriega**
- **Héctor Santiago Martínez**

Cada rol ha asumido responsabilidades específicas para garantizar la calidad del análisis y del diseño del sistema.

---

## 📐 Requisitos

Los requisitos del sistema se han capturado y documentado de forma estructurada:

- **Requisitos Funcionales (RF)**  
  Describen las funcionalidades que el sistema debe ofrecer.

- **Requisitos de Dominio (RD)**  
  Recogen restricciones, reglas y conceptos propios del dominio ferroviario.

Cada requisito incluye:
- Identificador único
- Nombre descriptivo
- Descripción detallada

---

## 🧱 Diseño UML

El diseño del sistema se ha realizado a partir de los requisitos definidos, empleando notación UML estándar.

Se incluyen los siguientes diagramas:

- Diagrama de clases y paquetes
- Diagrama de despliegue
- Diagrama de secuencia de una funcionalidad representativa

Además, se documentan las **decisiones de diseño** y los problemas arquitectónicos identificados durante el proceso.

---

## 🛠️ Metodología de trabajo

El desarrollo del proyecto se ha organizado mediante una **metodología ágil** (Scrum o Kanban), con el objetivo de:

- Planificar el trabajo por iteraciones
- Coordinar los distintos roles
- Facilitar la comunicación entre analistas y arquitectos
- Realizar un seguimiento continuo del progreso

El uso de la metodología y la herramienta asociada se documenta en la memoria del proyecto.


---

## 📄 Documentación

El proyecto se acompaña de una **memoria en formato PDF** que recoge:

- Captura completa de requisitos
- Diagramas UML
- Metodología utilizada
- Decisiones de diseño
- Conclusiones y lecciones aprendidas

---

## 📌 Nota

Este repositorio corresponde a la **fase de análisis y diseño**.  
La **implementación, testing y rediseño** del sistema se desarrollan en un repositorio independiente (Práctica 2).

---

## ✍️ Autoría

Proyecto desarrollado en el marco de la asignatura **Ingeniería del Software**  
Universidad Rey Juan Carlos – Curso 2025–2026
