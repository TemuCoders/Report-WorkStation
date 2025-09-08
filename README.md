**COURSE PROJECT**

<p align="center">
  <img src="./imgs/logo-upc.png" alt="Logo de la UPC" />
</p>

<p align="center"><strong>Universidad Peruana de Ciencias Aplicadas</strong></p>

<p align="center"><strong>Ingeniería de Software</strong><br>
Desarrollo de Aplicaciones Open Source<br>
<strong>Profesor:</strong> Flores Moroco Juan Antonio</p>

<h2 align="center">INFORME</h2>

<h3 align="center">Startup: WorkStation</h3>
<p align="center"><strong>Producto: WorkState</strong></p>

<h3 align="center">Team Members:</h3>

<div align="center">

 | **Member**                   | **Code**   |
 | ---------------------------- | ---------- |
 | Quijada Magro Jeremy     | U202219657 |
 | Huang Liu Franco      | U201914541 |
 | La Madrid Lozano Ivan         | U202219657 |
 | Saravia Huaricancha Arturo     | U202313419 |
 | Cumba Rengifo Leonardo      | U20231D534 |


</div>

<p align="center"><strong>Diciembre 2025</strong></p>

# Registro de Versiones del Informe


| Versión | Fecha       | Autor | Descripción |
|---------|-------------|-------|-------------|
| TB1     | 08/09/2025  | Quijada Magro, Jeremy  | Desarrollé la carátula del repositorio. |
| TB1     | 17  |  Guzavez   | w |

---

## Contenido
#### Tabla de contenidos

- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de los integrantes del equipo](#112-perfiles-de-los-integrantes-del-equipo)
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
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
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
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)
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
    - [5.2.2. Sprint 2](#522-sprint-2)
      - [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
      - [5.2.2.2. Aspect Leaders and Collaborators](#5222-aspect-leaders-and-collaborators)
      - [5.2.2.3. Sprint Backlog 2](#5223-sprint-backlog-2)
      - [5.2.2.4. Development Evidence for Sprint Review](#5224-development-evidence-for-sprint-review)
      - [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
      - [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
      - [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
      - [5.2.2.8. Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)
    - [5.2.3. Sprint 3](#523-Sprint-3)
      - [5.2.3.1. Sprint Planning 3](#5231-Sprint-Planning-3)
      - [5.2.3.2. Aspect Leaders and Collaborators](#5232-Aspect-Leaders-and-Collaborators)
      - [5.2.3.3. Sprint Backlog 3](5233-Sprint-Backlog-3)
      - [5.2.3.4. Development Evidence for Sprint Review](5234-Development-Evidence-for-Sprint-Review)
      - [5.2.3.5. Execution Evidence for Sprint Review](5235-Executio-Evidence-for-Sprint-Review)
      - [5.2.3.6. Services Documentation Evidence for Sprint Review](5236-Services-Documentation-Evidence-for-Sprint-Review)
      - [5.2.3.7. Software Deployment Evidence for Sprint Review](5237-Software-Deployment-Evidence-for-Sprint-Review)
      - [5.2.3.8. Team Collaboration Insights during Sprint](5238-Team-Collaboration-Insights-during-Sprint)
    - [5.2.4. Sprint 4](#524-Sprint-4)
      - [5.2.4.1. Sprint Planning 4](#5241-Sprint-Planning-4)
      - [5.2.4.2. Aspect Leaders and Collaborators](#5242-Aspect-Leaders-and-Collaborators)
      - [5.2.4.3. Sprint Backlog 4](#5243-Sprint-Backlog-4)
      - [5.2.4.4. Development Evidence for Sprint Review](#5244-Development-Evidence-for-Sprint-Review)
      - [5.2.4.5. Execution Evidence for Sprint Review](#5245-Execution-Evidence-for-Sprint-Review)
      - [5.2.4.6. Services Documentation Evidence for Sprint Review](#5246-Services-Documentation-Evidence-for-Sprint-Review)
      - [5.2.4.7. Software Deployment Evidence for Sprint Review](#5247-Software-Deployment-Evidence-for-Sprint-Review)
      - [5.2.4.8. Team Collaboration Insights during Sprint](#5248-Team-Collaboration-Insights-during-Sprint)
   - [5.3. Validation Interviews](53-Validation-Interviews)
      - [5.3.1. Diseño de Entrevistas](531-Diseño-de-Entrevistas)
      - [5.3.2. Registro de Entrevistas](532-Registro-de-Entrevistas)
      - [5.3.3. Evaluaciones según heurísticas](533-Evaluaciones-según-heurísticas.)
      - [5.4. Video About-the-Product](54-Video-About-the-Product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)


## Student Outcome

---

**ABET – EAC - Student Outcome 3**  
**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias.  

En el siguiente cuadro se describen las acciones realizadas y conclusiones del equipo que sustentan el logro del ABET - EAC - Student Outcome 3:

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|---------------------|--------------|
| **1. Comunica oralmente con efectividad a diferentes rangos de audiencia** | **TB1:**  | **TB1**:  |
| **2. Comunica por escrito con efectividad a diferentes rangos de audiencia** | **TB1:**  | **TB1:**  |



## Capítulo I: Introducción

### 1.1. Startup Profile

### 1.1.1. Descripción de la Startup