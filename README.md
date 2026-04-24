<div align="center">

<img src="assets/img/upc-logo.png" alt="UPC Logo" width="150"/>

# Universidad Peruana de Ciencias Aplicadas

## Facultad de Ingeniería

## Programa Académico de Ingeniería de Software

**Ciclo:** 2026-10

**Curso:** Desarrollo de aplicaciones Open Source

**NRC:** 11881

**Docente del curso:** Efraín Ricardo Bautista Ubillús


# Informe de Trabajo Final

**Nombre de la Startup:** Dermacare

**Nombre del producto:** Bloomie


## Integrantes

<p align="center">
u202416272 - Asmat Alminco, Martin Alejandro<br>
u202414802 - Contreras Torres, Arturo Valentino<br>
u202414970 - Gallardo Morales, Carla Alejandra<br>
u20241b843 - Mechan Montenegro, Luciana Carolina<br>
u202415551 - Ramirez Ruiz, Nickolas
</p>


*Abril, 2026*

</div>

---

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|-----------------------------|
| | | | |

---

# Project Report Collaboration Insights

---

# Contenido

## Tabla de Contenidos

- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2. Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
    - [2.1. Competidores](#21-competidores)
        - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
        - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2. Entrevistas](#22-entrevistas)
        - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
        - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
        - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
    - [2.3. Needfinding](#23-needfinding)
        - [2.3.1. User Personas](#231-user-personas)
        - [2.3.2. User Task Matrix](#232-user-task-matrix)
        - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
        - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
    - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1. User Stories](#31-user-stories)
    - [3.2. Impact Mapping](#32-impact-mapping)
    - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [4.1. Style Guidelines](#41-style-guidelines)
        - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
        - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    - [4.2. Information Architecture](#42-information-architecture)
        - [4.2.1. Organization Systems](#421-organization-systems)
        - [4.2.2. Labeling Systems](#422-labeling-systems)
        - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
        - [4.2.4. Searching Systems](#424-searching-systems)
        - [4.2.5. Navigation Systems](#425-navigation-systems)
    - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
        - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
        - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
    - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
        - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
        - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
        - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
        - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
    - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
    - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
        - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
        - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
        - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
        - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.8. Database Design](#48-database-design)
        - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
    - [5.1. Software Configuration Management](#51-software-configuration-management)
        - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2. Source Code Management](#512-source-code-management)
        - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
        - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
        - [5.2.1. Sprint 1](#521-sprint-1)
            - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
            - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
            - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
            - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
            - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
            - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
            - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
            - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

---

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 3**

**Criterio:** *Capacidad de comunicarse efectivamente con un rango de audiencias.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|---------------------|--------------|
| **Comunica oralmente con efectividad a diferentes rangos de audiencia.** | Asmat Alminco, Martin Alejandro <br>**AV1** <br> <br> Contreras Torres, Arturo Valentino <br>**AV1** <br> <br> Gallardo Morales, Carla Alejandra <br>**AV1** <br> <br> Mechan Montenegro, Luciana Carolina <br>**AV1** <br> <br> Ramirez Ruiz, Nickolas <br>**AV1** <br> | |
| **Comunica por escrito con efectividad a diferentes rangos de audiencia.** | Asmat Alminco, Martin Alejandro <br>**AV1** <br> <br> Contreras Torres, Arturo Valentino <br>**AV1** <br> <br> Gallardo Morales, Carla Alejandra <br>**AV1** <br> <br> Mechan Montenegro, Luciana Carolina <br>**AV1** <br> <br> Ramirez Ruiz, Nickolas <br>**AV1** <br> | |

---

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Hoy en día, el cuidado personal ha tomado gran relevancia, lo que ha convertido al mercado del skincare en uno de los más dinámicos y en constante crecimiento. Cada vez más personas, tanto jóvenes como adultos, buscan alternativas que les permitan mantener una piel saludable y cuidar su apariencia. Sin embargo, este creciente interés ha traído consigo la necesidad de soluciones innovadoras que conecten las expectativas de los usuarios con herramientas confiables, accesibles y basadas en información objetiva.

Es en este escenario que nace Dermacare, una startup comprometida en ayudar a las personas a comprender y gestionar su rutina de cuidado de la piel de manera informada y personalizada. Como parte de esta propuesta surge Bloomie, una aplicación web y móvil que integra servicios de Inteligencia Artificial para analizar el estado de la piel a partir de imágenes y generar recomendaciones personalizadas.

Bloomie se posiciona como el núcleo de la solución, brindando una experiencia digital intuitiva que acompaña al usuario en la toma de decisiones relacionadas con su cuidado personal. A través de la combinación de análisis automatizado, seguimiento de la evolución de la piel y acceso a servicios dermatológicos, la plataforma busca convertirse en un aliado confiable en el día a día del usuario.

---

### Misión

Brindamos una guía integral y personalizada para el cuidado de la piel mediante el uso de servicios de inteligencia artificial y análisis de datos dermatológicos. Ofrecemos rutinas adaptadas a cada tipo de piel, recomendaciones de productos ajustadas al presupuesto y objetivos del usuario, así como herramientas digitales accesibles que promueven hábitos de skincare saludables y sostenibles.

---

### Visión

Convertirnos en la plataforma líder de cuidado de la piel a nivel global, reconocida por integrar análisis inteligente y validación profesional como base para generar rutinas personalizadas y efectivas. Nuestro propósito es impactar positivamente en millones de personas, ayudándoles a prevenir y tratar problemas dermatológicos, al mismo tiempo que fortalecemos su confianza y bienestar.

---

### Valores

- **Accesibilidad:**  
  En Dermacare creemos que el cuidado de la piel debe estar al alcance de todos. Nuestra plataforma está diseñada para ser intuitiva y fácil de usar, adaptándose a distintos niveles de conocimiento y presupuestos.

- **Innovación:**  
  Integramos servicios de inteligencia artificial para transformar la experiencia del skincare, ofreciendo recomendaciones basadas en datos y en constante mejora. Apostamos por la tecnología como motor de soluciones modernas y efectivas.

- **Confianza:**  
  La salud de la piel requiere respaldo y seguridad. Por ello, combinamos análisis automatizados con la posibilidad de acceso a profesionales dermatológicos, fortaleciendo la credibilidad de la plataforma.

- **Bienestar:**  
  Más allá de la estética, buscamos mejorar la calidad de vida de nuestros usuarios. Promovemos hábitos de cuidado que fortalecen la salud de la piel y contribuyen a su bienestar integral.

### 1.1.2. Perfiles de integrantes del equipo

### Perfil del Integrante

<table>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/img/luciana-mechan.png" alt="Foto de Luciana Mechan" width="650"/>
    </td>
    <td><b>Nombre:</b> Luciana Carolina Mechan Montenegro</td>
  </tr>
  <tr>
    <td><b>Código:</b> u20241b843</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b>Luciana Carolina Mechan Montenegro</b>, estudiante del quinto ciclo de la carrera de Ingeniería de Software. Cuento con conocimientos en lenguajes de programación como C++, Python y Java, los cuales he aplicado en distintos proyectos académicos orientados a la resolución de problemas y desarrollo de sistemas.<br/><br/>
      Dentro del equipo, mi contribución se enfoca tanto en el desarrollo frontend como backend, participando en la implementación de funcionalidades y en la integración de los distintos componentes del sistema. Me caracterizo por ser responsable, proactiva y con una alta capacidad de aprendizaje, además de tener facilidad para el trabajo en equipo y la adaptación a nuevos retos dentro del proyecto.
    </td>
  </tr>
</table>

## 1.2. Solution Profile
### Descripción de la Solución

Nuestra solución consiste en una aplicación web y móvil denominada Bloomie, diseñada para asistir a personas interesadas en el cuidado de la piel mediante un sistema de análisis inteligente y personalizado. La aplicación permite que los usuarios registren un perfil personal y suban fotografías de su rostro, las cuales son procesadas a través de servicios de Inteligencia Artificial para identificar características relevantes de la piel, como presencia de acné, manchas, arrugas o textura desigual.

A partir de este análisis, Bloomie genera recomendaciones personalizadas de productos y hábitos de skincare, adaptadas a las necesidades específicas de cada usuario. A diferencia de otras soluciones basadas únicamente en cuestionarios, la plataforma combina el análisis automatizado con la posibilidad de acceso a servicios dermatológicos, brindando una experiencia más confiable y completa.

Asimismo, la aplicación permite realizar un seguimiento de la evolución de la piel a lo largo del tiempo, facilitando la comparación de resultados y la mejora continua de las rutinas recomendadas. Adicionalmente, integra funcionalidades como la visualización de productos disponibles en el mercado y la localización de puntos de compra cercanos.

El modelo de negocio de Bloomie se basa en un esquema de suscripción escalonado, en el cual los usuarios pueden acceder a distintos niveles de personalización, seguimiento y soporte según el plan contratado. Este enfoque permite ofrecer una solución accesible para distintos perfiles de usuario, al mismo tiempo que garantiza la sostenibilidad del servicio.

Como parte de la evolución del producto, se contempla la integración futura de dispositivos IoT orientados al monitoreo de condiciones de la piel, lo que permitirá complementar el análisis y mejorar la precisión de las recomendaciones, sin que ello represente una dependencia en la versión actual del sistema.

Para el sistema de análisis inteligente, se considerará el uso de Inteligencia Artificial (IA) para aplicación de algoritmos que logren Aprendizaje automático para aprender comportamiento o patrones con previo criterio programado. Dicho criterio constará de estudios sobre el cuidado de la piel para luego poder realizar comparaciones y diferenciar tipos de piel. Para ello, nos apoyaremos de la subdisciplina de IA: Visión de Computadora para que esta pueda interpretar información significativa a través de imágenes o videos.

### 1.2.1. Antecedentes y problemática

El interés por el cuidado de la piel ha incrementado de manera significa en jóvenes y adultos que buscan prevenir o tratar afecciones cutáneas comunes. Según el Fortune Business Insight (2024), el mercado de skin care fue valorado en 115.6 mil millones de dólares y se estima que crezca a 194 mil millones en el año 2032. Sin embargo, dicha relevancia adquirida generó una sobreoferta de productos y desinformación sobre el cuidado de piel. Diariamente, los usuarios se enfrentan a cientos de marcas, auspiciadores y catálogos de cosméticos extenuantes, lo que genera confusión en la correcta adquisión de dichos productos y dificulta la elección de una rutina apta para el usuario.


### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

# Capítulo III: Requirements Specification

## 3.1. User Stories

## 3.2. Impact Mapping

## 3.3. Product Backlog

# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture

### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming
### 4.6.2. Software Architecture Context Diagram
### 4.6.3. Software Architecture Container Diagrams
### 4.6.4. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

## 4.8. Database Design

### 4.8.1. Database Diagrams

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration

En esta sección se describen las herramientas y tecnologías utilizadas por el equipo para el desarrollo colaborativo del producto digital, abarcando actividades de gestión de proyecto, diseño UX/UI, desarrollo de software, pruebas, documentación y despliegue. Estas herramientas permiten asegurar consistencia, trazabilidad y eficiencia durante todo el ciclo de vida del proyecto.

A continuación, se presenta la configuración del entorno de desarrollo de Bloomie:

| **Herramienta / Tecnología** | **Propósito en el Proyecto**                                                             | **Tipo**       | **Ruta de Acceso / Descarga**                                  |
| ---------------------------- | ---------------------------------------------------------------------------------------- | -------------- | -------------------------------------------------------------- |
| GitHub                       | Control de versiones, gestión de repositorios y colaboración mediante commits y branches | SaaS           | [https://github.com](https://github.com)                       |
| Trello                       | Gestión de tareas y seguimiento del Sprint Backlog mediante tableros Kanban              | SaaS           | [https://trello.com](https://trello.com)                       |
| Figma                        | Diseño de interfaces UI (wireframes, mockups y prototipos)                               | SaaS           | [https://figma.com](https://figma.com)                         |
| UXPressia                    | Elaboración de artefactos UX como User Personas, Journey Maps y Empathy Maps             | SaaS           | [https://uxpressia.com](https://uxpressia.com)                 |
| Postman                      | Pruebas de endpoints RESTful y validación de servicios backend                           | Desktop / SaaS | [https://www.postman.com](https://www.postman.com)             |
| Visual Studio Code           | Entorno de desarrollo para frontend y backend                                            | Desktop        | [https://code.visualstudio.com](https://code.visualstudio.com) |
| Angular Framework            | Desarrollo de aplicaciones web frontend bajo arquitectura SPA                            | Framework      | [https://angular.io](https://angular.io)                       |
| HTML5, CSS3, JavaScript      | Tecnologías base para estructura, estilos e interacción en frontend                      | Lenguajes      | [https://developer.mozilla.org](https://developer.mozilla.org) |
| MySQL                        | Sistema de gestión de base de datos relacional para persistencia de datos                | DBMS           | [https://www.mysql.com](https://www.mysql.com)                 |
| Vercel                       | Plataforma de despliegue para aplicaciones frontend (Landing Page y Web App)             | SaaS (Cloud)   | [https://vercel.com](https://vercel.com)                       |
| Markdown (GitHub README) | Documentación técnica del proyecto y del informe en formato Markdown | SaaS | [https://www.markdownguide.org](https://www.markdownguide.org) |

### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1
#### 5.2.1.2. Aspect Leaders and Collaborators
#### 5.2.1.3. Sprint Backlog 1
#### 5.2.1.4. Development Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint