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

WorkStation es una aplicación web innovadora diseñada para facilitar la reserva eficiente de espacios de trabajo en oficinas compartidas. Su propósito es conectar a freelancers, trabajadores remotos, startups y empresas de todos los tamaños con espacios de coworking disponibles en su ciudad o alrededor del mundo.

La plataforma permitirá a los usuarios buscar, comparar y reservar escritorios, salas de reuniones, oficinas privadas y otros recursos disponibles en tiempo real. Cada espacio contará con información detallada como ubicación, precios, horarios, disponibilidad, fotos, servicios incluidos (Wi-Fi, café, impresoras, etc.), y valoraciones de otros usuarios

Considerando la flexibildad y la adaptabilidad como puntos esenciales para el crecimiento de las startups y los trabajos freelance, WorkStation brinda una solución que compite con la rigidez de los contratos tradicionales, y propone una instancia mucho más moderna para este espacio de trabajo que las empresas necesitan.

### 1.1.2. Perfiles de integrantes del equipo

| Foto                                                                                   | Alumno                         | Descripción                                                                                                                                                                                                                                                                   |
| -------------------------------------------------------------------------------------- | ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Luis](Imagenes/perfil-integrante-jeremy.png)                                         | Quijada Magro Jeremy Alexander | Edatos.                                                                                                                         |
| ![Rodrigo](Imagenes/rodrigo.png)                                                       | Lib     | Estudl acia el cumplimiento de sus metas.                                                        |
| ![Sebastian](Imagenes/sebastian.png)                                                   | S   | Estu SQ y lal.                   |
| ![Luis](Imagenes/Luisfoto.png)                                                         | J        | Estudicrabase, MongoDB, . |
| ![Emilia](Imagenes/emilia.png)                                                         | Em         | Estudi                                                                                         |
| ![yo] | S    | Es                                                                                        |

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

- **Who (¿Quiénes son los involucrados?)**  
  Los principales usuarios son freelancers, trabajadores remotos, pequeñas empresas, startups y nómadas digitales que requieren espacios de trabajo profesionales, cómodos y flexibles sin necesidad de alquilar una oficina a largo plazo.  
  Además, los propietarios y administradores de espacios de coworking forman parte clave, ya que buscan visibilidad, gestión eficiente de sus reservas y captación de nuevos clientes.

- **What (¿Qué se necesita?)**  
  Se necesita una plataforma centralizada e intuitiva que permita a los usuarios buscar, comparar, reservar y pagar por espacios de coworking en diferentes ubicaciones, con información clara y disponibilidad en tiempo real.  
  Actualmente, el proceso de reserva suele ser manual, lento y disperso en múltiples canales no estandarizados (webs propias, redes sociales, WhatsApp, etc.).

- **Where (¿Dónde ocurre el problema?)**  
  En ciudades con alta actividad profesional y creciente demanda por espacios flexibles, como Lima, Arequipa, Medellín, Bogotá o CDMX. La necesidad puede extenderse a nivel nacional e internacional a medida que el trabajo remoto se consolida.

- **When (¿Cuándo surge esta necesidad?)**  
  La necesidad es continua y puede surgir en cualquier momento. Muchos usuarios requieren espacios por horas, días o semanas. Además, algunos necesitan soluciones de último minuto para reuniones o trabajo inmediato.

- **Why (¿Por qué existe esta necesidad?)**  
  El mundo laboral ha cambiado. La pandemia aceleró el trabajo remoto y la cultura freelance. Las personas necesitan trabajar en ambientes productivos y profesionales, pero sin compromisos de largo plazo. Sin embargo, no existe una solución eficiente y masiva que integre toda la oferta disponible y facilite el proceso de reserva.

- **How (¿Cómo se puede solucionar?)**  
  Mediante el desarrollo de una aplicación web llamada WorkStation, que permita a los usuarios explorar una variedad de espacios de coworking, visualizar disponibilidad, leer reseñas, aplicar filtros, hacer reservas en tiempo real y pagar desde una sola interfaz.

- **How Much (¿Cuánto costaría y cómo se monetiza?)**  
  Los precios varían según ciudad, tipo de espacio, servicios y duración. La plataforma podrá mostrar precios claros y actualizados. El modelo de negocio se sustentará en comisiones por reserva, planes de suscripción para coworking o membresías premium para usuarios frecuentes.

### Descripción de la Problemática

En los últimos años, el trabajo remoto y el modelo freelance han experimentado un crecimiento significativo en Perú y América Latina. Según Statista (2023), más del 20% de los trabajadores peruanos realiza actividades de forma independiente o remota, y esta tendencia continúa en aumento. Sin embargo, este cambio en la modalidad laboral no ha sido acompañado por soluciones tecnológicas que respondan de manera efectiva a las necesidades de espacio físico flexible, accesible y bien ubicado.

Por otro lado, el mercado de espacios coworking también ha crecido rápidamente en Lima, con más de 300 centros operando actualmente, especialmente en distritos como Miraflores, San Isidro y Surco (Andina, 2023). A pesar de esta expansión, muchos de estos espacios enfrentan dificultades para ocupar sus instalaciones de forma constante, especialmente en horarios valle o días con baja demanda. La mayoría de propietarios aún dependen de canales informales (WhatsApp, redes sociales o referidos) para captar nuevos usuarios, lo que limita su visibilidad y su capacidad para escalar comercialmente.

Esta desconexión entre la **alta demanda de espacios temporales de trabajo** y la **oferta disponible sin digitalización adecuada** genera ineficiencias notorias: usuarios que no encuentran espacios adecuados en tiempo real, y propietarios que pierden ingresos por no contar con una plataforma de reservas automatizada. Además, la falta de sistemas de gestión y comparación centralizada crea una experiencia fragmentada, poco confiable y lenta para ambas partes.

En este contexto, **WorkStation** surge como una solución tecnológica que busca cerrar esta brecha, permitiendo a freelancers, startups y profesionales acceder fácilmente a espacios de trabajo mediante una plataforma web intuitiva, al mismo tiempo que otorga a los propietarios herramientas de visibilidad, control de disponibilidad y generación de ingresos más eficientes.

### 1.2.2 Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

##### Dominio del Problema

El proyecto WorkStation se desarrolla en el dominio de los espacios de trabajo compartidos (coworking), una industria en expansión que responde a la evolución del trabajo remoto, el crecimiento del autoempleo y la economía de los servicios digitales. A pesar de esta expansión, la interacción entre la oferta (espacios disponibles) y la demanda (profesionales independientes o empresas en crecimiento) aún se encuentra fragmentada y desorganizada, especialmente en el mercado peruano, donde no existen plataformas digitales de gran alcance que faciliten esta conexión de manera eficiente.

#### Segmentos de Cliente

1. **Freelancers, startups y profesionales remotos**: Personas entre 22 y 40 años que requieren espacios de trabajo flexibles, temporales y bien ubicados. Este segmento prioriza la autonomía, la conectividad y la comodidad, y espera poder gestionar sus reservas de manera rápida y sencilla desde una plataforma digital.
2. **Propietarios o administradores de espacios coworking**: Emprendedores o pequeñas empresas que buscan visibilidad, gestión automatizada de reservas y canales efectivos para ocupar sus instalaciones durante todo el día. Muchos de estos propietarios no cuentan con sistemas digitales propios y dependen de medios manuales o redes sociales para captar usuarios.

#### Puntos de Dolor

- **Freelancers y startups**:

  - No encuentran una oferta centralizada y confiable de espacios disponibles.
  - Carecen de filtros que les permitan comparar opciones según ubicación, precio o servicios.
  - El proceso de reserva suele ser informal, poco transparente y lento.

- **Propietarios de coworkings**:
  - Alta dependencia de canales informales para captar clientes (WhatsApp, redes sociales).
  - Ausencia de herramientas para gestionar disponibilidad en tiempo real.
  - Pérdida de ingresos por falta de reservas constantes y baja visibilidad.

#### Brecha Detectada

En Perú, no existe actualmente una plataforma digital consolidada que conecte, en tiempo real, a freelancers y startups con espacios coworking disponibles. Esta brecha genera una experiencia ineficiente tanto para quienes buscan un lugar para trabajar como para quienes lo ofrecen. A diferencia de mercados como Estados Unidos o Europa —donde plataformas como LiquidSpace o Deskpass dominan el rubro, el ecosistema local aún carece de soluciones tecnológicas adaptadas al comportamiento y necesidades del mercado peruano.

#### Visión y Estrategia

**Visión**: Crear una plataforma web que actúe como un marketplace digital para espacios de coworking, brindando a los usuarios una experiencia de reserva ágil, confiable y personalizada, y a los propietarios una solución de gestión eficiente que maximice el uso de sus instalaciones.
**Estrategia**:

- Desarrollar un producto mínimo viable (MVP) que permita validar tempranamente la propuesta de valor.
- Enfocarse en la usabilidad, accesibilidad y confiabilidad de la plataforma.
- Establecer alianzas estratégicas con coworkings emergentes de Lima.
- Implementar un modelo de monetización basado en comisión por reserva, con herramientas analíticas para los propietarios.

#### Segmento Inicial

Para validar la propuesta de valor de WorkStation, se priorizará un segmento específico en la etapa inicial del proyecto:

- **Usuarios meta**: Freelancers y profesionales digitales entre 22 y 35 años, ubicados en Lima Metropolitana, que trabajan de forma remota o de manera independiente.
- **Aliados estratégicos**: Coworkings de tamaño pequeño a mediano, ubicados en distritos céntricos como Miraflores, Barranco y San Isidro, que no cuentan con plataformas propias de gestión o marketing digital.

#### 1.2.2.2. Lean UX Problem Assumptions

- **Asumimos que los usuarios requieren flexibilidad y comodidad en sus espacios de trabajo**
- **Asumimos que los propietarios de espacios de coworking necesitan mayor visibilidad y eficiencia en la gestión de reservas**
- **Asumimos que la búsqueda y reserva de espacios de coworking es un proceso fragmentado y poco confiable**
- **Asumimos que los usuarios están dispuestos a pagar por una solución eficiente y confiable**
- **Asumimos que la digitalización mejorará la eficiencia operativa de los espacios de coworking**

#### 1.2.2.3. Lean UX Problem Hypothesis Statements

- **Hipótesis 1: Si ofrecemos una plataforma centralizada y fácil de usar para reservar espacios de coworking, entonces los freelancers y pequeñas empresas preferirán utilizarla debido a la flexibilidad y la facilidad de acceso a diferentes opciones de trabajo.**

- **Hipótesis 2: Si los propietarios de espacios de coworking obtienen mayor visibilidad y una herramienta para gestionar eficientemente las reservas, entonces experimentarán un aumento en la ocupación de sus espacios y en la satisfacción de sus clientes.**

- **Hipótesis 3: Si los usuarios pueden comparar precios, ver disponibilidad en tiempo real y leer reseñas de otros usuarios, entonces tomarán decisiones de reserva con mayor rapidez y precisión, mejorando la experiencia del cliente.**

- **Hipótesis 4: Si la plataforma cobra una comisión por reserva o un modelo de membresía, entonces se generarán ingresos recurrentes tanto para los propietarios de los espacios como para la plataforma, incentivando la adopción de la herramienta.**

- **Hipótesis 5: Si se digitaliza el proceso de gestión de reservas, entonces los propietarios de espacios de coworking podrán reducir sus costos operativos y mejorar su rentabilidad a largo plazo.**

#### 1.2.2.4. Lean UX Problem Canvas

#### 1. Business Problem

- La conexion entre las demandas crecientes de espacios trabajos flexibles y la oferta de coworkings está dividida. La mayoría de usuarios no cuentan con plataformas confiables así como los propietarios carecen de herramientas de gestión.

---

#### 2. Business Outcomes

- Aumentar de los ingresos mediantes comisiones y membresías.
- Disminuir el tiempo promedio de búsqueda de reserva de espacios.
- Ayudar a miles de peruanos a buscar un lugar para trabajar garantizando mejores resultados.

---

#### 3. Users

- Nustros clientes serán Freelancers y trabajadores remotos de entre 22 a 40 años que buscan habitaciones disponibles y acogedoras y con servicios como Wi-Fi, salas de reuniones.
- Startups y equipos pequeños que buscan espacio temporal para trabajos de colaboración o reuniones.
- Propietarios de coworking que desean captar más usuarios y administrar las reservas de manera efectiva.

---

#### 4. User Benefits

- Los usuarios contarán con salas de trabajo para satisfacer sus necesidades especiales (precio, ubicación, servicios).
- Los propietarios logran más actividad con menos esfuerzos de rendimiento y no tendrán incertidumbres.
- Con respecto a los propietarios, se reservan con más frecuencia y recomendarán el servicio a otros.

---

#### 5. Solutions

- Motor de búsqueda y filtrado de coworkings por ciudad, precio, servicios.
- Sistema de reservas con calendario en tiempo real.
- Panel para propietarios con gestión de disponibilidad, estadísticas, reseñas.
- Sistema de notificaciones (email, push) para recordatorios y confirmaciones.

---

#### 6. Hypotheses

- Si centralizamos la oferta de coworkings, los usuarios ahorrarán tiempo y confiarán más en el proceso.

- Si los propietarios digitalizan su gestión de reservas, incrementarán su ocupación y reducirán su carga operativa.

- Si los usuarios pueden ver disponibilidad, precios y reseñas en tiempo real, tomarán decisiones más informadas y rápidas.

- Si cobramos comisiones por reserva o membresías premium, el modelo será rentable y sostenible.

- Si la plataforma es ágil y confiable, se convertirá en el canal principal de reserva para usuarios frecuentes.

---

#### 7. What’s the most important thing we need to learn first?

- Primero necesitamos entender si los usuarios finales desean una plataforma de reserva centralizada, sus preferencias y necesidades para implementarlo y mejorar la experiencia.
- Necesitamos saber si les cómodo de usar ante otros métodos tradicionals.

---

#### 8. What’s the least amount of work we need to do to learn the next most important thing?

- Realizar entrevistas, feedback además de pruebas de usabilidad para explorar la relevancia de las reservas de espacios de trabajo tanto para trabajadores como los propietarios.

## 1.3. Segmentos objetivo

En el proyecto nos enfocamos en dos segmentos principales de usuarios, directamente relacionados con el dominio del problema: los propietarios de espacios de coworking y los usuarios que buscan dichos espacios, como freelancers y startups. A continuación, se describen en detalle ambos perfiles.

### Propietarios de Inmuebles (Coworkings)

Corresponde a personas naturales o jurídicas que administran o alquilan espacios acondicionados para trabajo compartido, como oficinas, salas de reuniones, escritorios flexibles, entre otros.

#### Características Demográficas

- **Ubicación:** Principalmente zonas urbanas de alto flujo empresarial, como Miraflores, San Isidro, Surco (Lima).
- **Edad promedio de los administradores:** 30 a 55 años.
- **Nivel socioeconómico:** Medio-alto a alto.
- **Tipo de propiedad:** Empresas formales, pymes inmobiliarias o propietarios individuales.

#### Datos Relevantes

- En Lima existen más de 150 espacios de coworking activos (Andina, 2023).
- El 67% de estos espacios reporta dificultades para llenar su capacidad total, especialmente en horarios valle (CoworkIntel, 2022).
- La mayoría carece de una plataforma de reservas centralizada, y operan mediante WhatsApp, redes sociales o formularios web.

#### Necesidades Clave

- Mayor visibilidad de su espacio.
- Automatización del proceso de reservas.
- Optimización de la ocupabilidad de sus ambientes.
- Acceso a métricas sobre uso y satisfacción de clientes.

---

### Freelancers y Startups

Este grupo está compuesto por trabajadores independientes, equipos pequeños de desarrollo, marketing, diseño, entre otros, así como emprendedores en etapa inicial.

#### Características Demográficas

- **Edad:** Entre 20 y 40 años.
- **Ubicación:** Centros urbanos con alta conectividad.
- **Nivel educativo:** Técnico o universitario completo.
- **Ocupación:** Diseñadores, desarrolladores, consultores, creadores de contenido, equipos de startups.
- **Ingreso promedio mensual:** S/ 2,000 – S/ 5,000 (varía por actividad y clientes).

#### Datos Relevantes

- Se estima que más de 500,000 peruanos trabajan como freelancers (Statista, 2022), y esta cifra crece con el auge del trabajo remoto postpandemia.
- Según un estudio de WeWork (2021), el 78% de los trabajadores remotos en LATAM buscan espacios fuera de casa al menos una vez por semana.
- El 60% de los freelancers jóvenes en Lima considera los coworkings como espacios que fomentan productividad y networking (PUCP, 2023).

#### Necesidades Clave

- Acceso flexible a espacios profesionales sin necesidad de contrato a largo plazo.
- Precios accesibles, según uso (por horas o días).
- Información clara sobre servicios incluidos (wifi, café, salas, etc.).
- Reseñas de otros usuarios para tomar decisiones confiables.

## Capítulo II: Requirements Elicitation & Analysis


## 2.1. Competidores

**WeWork:**
WeWork, fundada en 2010 en Nueva York por Adam Neumann y Miguel McKelvey, empezó como una startup de espacios de coworking. Su modelo de negocio se basaba en alquilar oficinas a largo plazo, rediseñarlas como espacios colaborativos y flexibles, y alquilarlas a empresas, freelancers y emprendedores a corto plazo.

La compañía creció rápidamente, alcanzando una valoración de $47 mil millones en 2019. Sin embargo su estruendoso intento de salir a la bolsa fracaso debido a la mala gestión y al modelo insostenible que la compañía tenia, además uno de sus fundadores renuncio. Todo esto llevo que WeWork a declararse en bancarrota en noviembre de 2023. Actualmente, bajo la nueva dirección de SoftBank, busca reestructurarse y enfocarse en rentabilidad.

**Spaces:**
Spaces fue fundada en 2008 en Ámsterdam (Países Bajos) como una marca de espacios de coworking y oficinas flexibles, enfocada en diseño innovador y comunidad. En 2016, fue adquirida por IWG plc, lo que le permitió expandirse globalmente con mayor respaldo financiero.

**CoWorker:**

Coworker.com es una plataforma global de búsqueda y comparación de espacios de coworking, fundada en 2015 por Leanne Beesley y Sam Marks . A diferencia de WeWork o Spaces, Coworker no opera sus propios espacios, sino que funciona como un marketplace que conecta a usuarios con miles de espacios de coworking en todo el mundo.

La plataforma surgió para resolver un problema clave: la falta de transparencia y acceso a información sobre espacios de trabajo flexibles. Hoy, Coworker.com lista más de 20,000 espacios en 170+ países, ofreciendo reseñas, precios y disponibilidad en tiempo real.

**Oficinas YA!**

Oficinas YA! es una plataforma líder en América Latina especializada en la búsqueda, comparación y arrendamiento de oficinas y espacios de coworking. Fue fundada en 2015 en México y se ha expandido a otros países como Colombia, Argentina y Chile, con un enfoque en facilitar el proceso de encontrar espacios de trabajo flexibles para empresas y profesionales.

### 2.1.1. Análisis competitivo

| **Competitive Analysis Landscape**        |                                                                                                                                                                                                                                                    |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **¿Por qué llevar a cabo este análisis?** | **Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.**                                                                                                                                                         |
|                                           | **Identificar que ventajas comerciales podemos obtener por parte de nuestros competidores. Funcionalidades, estrategias de marketing o productos que podriamos agregar, Gracias a esto lograr ser un competidor estable frente a estas companias** |

| **_Competidor_**          |                                                             | WorkStation                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | WeWork                                                                                                                                                                                                                                                                                                       | Spaces                                                                                                                                                                                                                 | Coworker                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Oficinas Ya!                                                                                                                                                                                                                                                                                              |
| ------------------------- | ----------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **_Logo_**                |                                                             | ![WorkStation](Imagenes/workstation.png.jpg)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | ![Wework](Imagenes/wework.png)                                                                                                                                                                                                                                                                               | ![Spaces](Imagenes/spaces.png)                                                                                                                                                                                         | ![Coworker](Imagenes/coworker.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | ![OficinasYa](Imagenes/oficinasya.png)                                                                                                                                                                                                                                                                    |
| **_Perfil_**              | Overview                                                    | Una aplicación web y móvil que ofrece servicios de su arrendaciones a empresas, freelances o startups a nivel mundial.                                                                                                                                                                                                                                                                                                                                                                                                                             | Una aplicación web y móvil que ofrece servicios de su arrendaciones a empresas, freelances o startups a nivel mundial.                                                                                                                                                                                       | Una aplicación web y móvil que ofrece servicios de su arrendaciones a empresas, freelances o startups a nivel mundial.                                                                                                 | Una aplicación web y móvil que ofrece servicios de su arrendaciones a empresas, freelances o startups a nivel mundial.                                                                                                                                                                                                                                                                                                                                                                                                        | Una aplicación web y móvil que ofrece servicios de su arrendaciones a empresas, freelances o startups a nivel mundial.                                                                                                                                                                                    |
|                           | **_Ventaja competitiva ¿Qué valor ofrece a los clientes?_** | Su propósito es conectar a freelancers, trabajadores remotos, startups y empresas de todos los tamaños con espacios de coworking disponibles en su ciudad o alrededor del mundo. La plataforma permitirá a los usuarios buscar, comparar y reservar escritorios, salas de reuniones, oficinas privadas y otros recursos disponibles en tiempo real. Cada espacio contará con información detallada como ubicación, precios, horarios, disponibilidad, fotos, servicios incluidos (Wi-Fi, café, impresoras, etc.), y valoraciones de otros usuarios | Además de servicios básicos como internet de alta velocidad, oficinas en buen estado, impresoras y cafetería ilimitada, también posee espacios flexibles y con diseños modernos, una comunidad global que permite el acceso a evento, networking y acceso a que los miembros del equipo conecten fácilmente. | Posee contratos cortos, membresías mensuales o planes flexibles que beneficien a los clientes. Oficinas con servicios adicionales, ergonómicos y decoración innovadora que ha resaltado al ganar un premio sobre eso.  | Sus funcionalidades mas resaltantes son la búsqueda inteligente que permite a los usuarios buscar y comprar precios de espacios coworking al rededor de mas de 170 paises. Ofrecen un sistema de reseñas y ratings para la comunidad. Asimismo brindan recursos para nómadas digitales, cómo guías de las ciudades de los mejores espacios coworking e información de visas o papeleo. Por ultimo, da la opción de una membresía llamada "Coworker Pass" que brinda acceso casi ilimitado a espacios y descuentos exclusivos. | Busqueda avanzada, como filtros o tipos de espacios. Asimismo birnda una visualizacion de fotos y videos 360. Ofrece oficinas virtuales, que brindan serivicio de gestion de correo y atencion personalizada de llamadas. UNa gran Flexibilidad de contratos desde horas hasta meses sin compromisos.<br> |
| **_Perfil de Marketing_** | **_Mercado objetivo_**                                      | Startups, emprendedores, freelancers, nomadas digitales o empresas tradicionales. Ademas de propietarios de inmuebles que deseen una optimizacion de ocupacion de sus ambientes.                                                                                                                                                                                                                                                                                                                                                                   | Startups, emprendedores, freelancers, nomadas digitales o empresas tradicionales.                                                                                                                                                                                                                            | Startups, emprendedores, freelancers, nómadas digitales.                                                                                                                                                               | Startups, emprendedores, freelancers, nómadas digitales o empresas tradicionales.                                                                                                                                                                                                                                                                                                                                                                                                                                             | Startups, emprendedores, freelancers, nómadas digitales o empresas tradicionales.                                                                                                                                                                                                                         |
|                           | **_Estrategias de marketing_**                              | Las propuestas que tenemos como marketing son las siguientes; anunciar la aplicación web por Google ads y redes sociales como Facebook, Instagram o en grupos de Telegram de Freelancers o Startups.                                                                                                                                                                                                                                                                                                                                               | Se promocionan por redes sociales queriendo expandir su estilo de vida creativo e innovacion en su comunidad de trabajo. Asimismo tienen eventos gracias a sus alianzas estrategicas con Microsoft y Salesforce. Por ultimo, algunos anuncios en Google Ads y SEO.                                           | Contenido en redes sociales, alianzas estratégicas, enfoque de diseño y experiencia y eventos que llaman a los clientes rápidamente.<br><br>                                                                           | La aplicación se promociona con optimización de búsquedas simples en el navegador, publica artículos y reportes acerca del coworking flexible, tiene una gran presencia en redes sociales y posee alianzas estratégicas con Selina, Outside o Airbnb for work.                                                                                                                                                                                                                                                                | Posee una presencia digital activa, con redes sociales y comunidades empresariales en Linkedin y Facebook. Tienen publicidad en Google Ads y remarketing. Por ultimo, tienen alianzas con espacios asociados en eventos conjuntos.                                                                        |
| **_Perfil de Producto_**  | **_Productos & Servicios_**                                 | Ofrecer la comunicación entre freelancers o startups con los propietarios de los inmuebles.                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Ofrecen sus propias oficinas para el uso de cualquier empresa, startup o que su mercado objetivo necesite.                                                                                                                                                                                                   | Ofrecen sus propias oficinas para el uso de cualquier empresa, startup o que su mercado objetivo necesite.                                                                                                             | Ofrecen oficinas de cualquier parte del mundo para el uso de cualquier empresa, startup o que su mercado objetivo necesite.                                                                                                                                                                                                                                                                                                                                                                                                   | Ofrecen oficinas de cualquier parte del mundo para el uso de cualquier empresa, startup o que su mercado objetivo necesite.                                                                                                                                                                               |
|                           | **_Precios & Costos_**                                      | Los precios variaran dependiendo de los propietarios, ellos decidirán el tiempo que puede estar disponible el inmueble y el precio. Asimismo, se incluirán descuentos dependiendo de las fechas o si alguno de las startups o freelancers posee una membresía con nuestra propuesta.                                                                                                                                                                                                                                                               | Los precios varian entre los diferentes paquetes que posee. Los escritorios compartidos varian entre $250 a $500. Mientras que las oficinas privadas desde $800 a $3000. Pero asimismo poseen planes de solo un dia, que varian entre $25 a $30.                                                             | Varian dependiendo de la ubicación, duracion del contrato o tipo de espacio. SIn embargo, Spaces posee una membrecia llamada "Spaces Global Pass" con acceso a multiples ubicaciones que varian desde $400 a $800.<br> | La búsqueda de espacios es gratuita y disponible para todos, sin embargo la membresía tiene un costo de $50 aproximadamente. <br><br>                                                                                                                                                                                                                                                                                                                                                                                         | La empresa cobra a los espacios una comisión del 10-20%, dependiendo del costo del inmueble.<br>                                                                                                                                                                                                          |
|                           | **_Canales de distribución (Web y/o Móvil)_**               | Los canales que usan son su aplicacion web.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Web/Móvil                                                                                                                                                                                                                                                                                                    | Los canales que usan son su aplicacion web y movil. Asimismo tienen ventas B2B, aliados coorporativos cmom aceleradoras, bancos y gremios empresariales.                                                               | Los canales que usan son su aplicacion web y movil. Sus redes de afiliados, como sus socios apoyan su distribucion.                                                                                                                                                                                                                                                                                                                                                                                                           | Los canales que usan son una aplicación web y móvil que ofrece servicios de su arrendaciones a empresas, freelances o startups a nivel mundial. Agentes telefónicos y aliados comerciales con inmobiliarias y desarrolladores de oficinas.                                                                |
| **_Análisis SWOT_**       | **_Fortalezas_**                                            | Startup innovadora, precios flexibles, diseno innovador y modelo escalable para futuras actualizaciones.                                                                                                                                                                                                                                                                                                                                                                                                                                           | Marca reconocida globalmente, flexibilidad y escalabilidad, red de comunidades profesionales y diseño innovador                                                                                                                                                                                              | Respaldo de IWG (solvencia financiera), diseño premium y experiencia de usuario, red global con sinergias (Regus, Signature) y modelo escalable y rentable                                                             | Modelo escalable sin costos de operar espacios físicos, base de datos global más amplia que competidores, ideal para nómadas digitales (mercado en crecimiento) y reseñas transparentes y comparación de precios                                                                                                                                                                                                                                                                                                              | Enfoque en Latinoamérica (conocimiento local), amplia red de espacios asociados, Asesoría personalizada sin costo y modelo sin costos fijos de operar espacios                                                                                                                                            |
|                           | **_Debilidades_**                                           | Pocos fondos, sin alianzas poderosas, bajos conocimientos del mercado y competidores mas experimentados en el rubro,                                                                                                                                                                                                                                                                                                                                                                                                                               | Dependencia de arrendamientos caros, alto endeudamiento, mala gestión financiera histórica y perdida de confianza post-bancarrota                                                                                                                                                                            | Menor reconocimiento global vs. WeWork, precios más altos que competidores locales, menor enfoque en "comunidad" que WeWork y crecimiento más lento que startups independientes                                        | Dependencia de espacios asociados (calidad variable), menor reconocimiento frente a marcas como WeWork, ingresos limitados si no aumenta volumen de reservas y Competencia con plataformas de reservas de espacios (ej. Deskpass)                                                                                                                                                                                                                                                                                             | Menor reconocimiento fuera de la región, dependencia de la calidad de los espacios listados, Competencia con plataformas globales (Coworker.com) y rentabilidad limitada si no escala el volumen de transacciones                                                                                         |
|                           | **_Oportunidades_**                                         | Expansion en un mercado emergente como lo seria Latino america, ideas frescas para revolucionar el mercado y futuras alianzas en camino.                                                                                                                                                                                                                                                                                                                                                                                                           | Modelo híbrido post-pandemia, expansión en mercados emergentes y alianzas con gobiernos para espacios públicos                                                                                                                                                                                               | Demanda de espacios híbridos post-pandemia, expansión en Asia y Latinoamérica y alianzas con grandes corporaciones                                                                                                     | Crecimiento del trabajo remoto y nómadas digitales, alianzas con gobiernos para promocionar destinos "workation" y expansión a mercados emergentes (Asia, Latinoamérica)                                                                                                                                                                                                                                                                                                                                                      | Crecimiento del trabajo híbrido en LATAM, alianzas con gobiernos para impulsar emprendimiento y expansión a ciudades secundarias con demanda creciente                                                                                                                                                    |
|                           | **_Amenazas_**                                              | Competencia, pocos recursos que no se puedan recuperar a corto plazo y cambios en tendencias laborales.                                                                                                                                                                                                                                                                                                                                                                                                                                            | Competencia (Spaces o locales independientes), crisis económicas reducen demanda y cambios en tendencias laborales (remote-first)                                                                                                                                                                            | Competencia de WeWork (reestructurada) y actores locales, recesión económica afecta demanda de espacios premium y cambio hacia el trabajo remoto permanente                                                            | Espacios que prefieren vender directamente (evitar comisiones), plataformas más grandes (ej. Airbnb) integrando coworking y saturación de marketplaces de coworking                                                                                                                                                                                                                                                                                                                                                           | Espacios que prefieren gestionar reservas directamente, entrada de competidores globales (ej. WeWork), crisis económicas que reduzcan la demanda de oficinas                                                                                                                                              |

### 2.1.2. Estrategias y tácticas frente a competidores

| **_MATRIZ FODA y C.A.M.E_**                                                   | **Oportunidades:** Modelo hibrido post pandemia                                                                                                                                               | **Amenazas:** posibles cambios a trabajo remoto permanentemente                                                                                                |
| ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Fortalezas:** Innovacion, publico objetivo más amplio y mayor escalabilidad | Debido al modelo hibrido podríamos expandirnos debido a que nuestro publico objetivo llega a ser mas amplio que otros competidores, además de poder innovar en este mercado no tan explorado. | Tener en cuenta que habran mas espacios libres para otros rubros, por lo que se podrian usar de maneras diferentes en otras actividades que puedan ser utiles. |
| **Debilidades:** Sin alianzas poderosas como los competidores.                | Utilizar la oportunidad de modelo hibrido para promocionar nuestra aplicación a otras y así poder formar alianzas que puedan apoyar al crecimiento de nuestra startup                         | Debido al posible cambio a trabajo remoto permanente, las alianzas que se puedan tener en un futuro pueden seguir utilizandolas para otros rubros.             |

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**PROPIETARIOS DE INMUEBLES**

 1. Nombre completo
 2. Edad
 3. Distrito de residencia
 4. Profesión
 5. Actualmente, ¿tiene propiedades adicionales disponibles o sin uso en su vivienda actual?
 6. ¿Qué hace con esa(s) propiedad(es)? ¿Tiene algo planeado para hacer?
 7. ¿Qué piensa de los alquileres de oficina como espacios de coworking?
 8. ¿Qué opinaría de una aplicación que conecta a dueños de espacios en alquiler con empresas que buscan alquilar estos espacios? Estaría dispuesto(a) a usarla?
 9.  Que beneficios le gustaría tener a usted dentro de el trato entre usted y la compañía que trabaje en la propiedad?
 10. Que comportamientos o hábitos no estarían dispuesto(a) a aceptar de la compañía/startup que trabaje en su propiedad?
 11. Que funcionalidades le gustaría que tenga esta aplicación web?
 12. ¿De que manera buscaría hacer este espacio uno seguro para ambos?

**FREELANCERS/STARTUPS**

 1. Nombre completo
 2. Edad
 3. Distrito de residencia
 4. Profesión
 5. Actualmente, ¿desde donde trabaja?
 6.  Cree que el lugar donde trabajan afecta la productividad de su trabajo?
 7. Que es lo que busca en un lugar de trabajo?
 8. ¿Ha escuchado hablar de los espacios de coworking?
 9. ¿Qué opinaría de alquilar un espacio destinado para trabajar?
 10. ¿Qué opinaría de una aplicación que le ofrezca la posibilidad de conectarlo con varios de estos espacios disponibles?
 11. Que funcionalidades cree que debería tener una aplicación como esta?
 12. ¿De que manera buscaría hacer este espacio uno seguro para ambas partes?

### 2.2.2. Registro de entrevistas

**Segmento 1**
Enlace del video de la entrevista:

[![Demo en YouTube](https://img.youtube.com/vi/1GPReTfneu4/0.jpg)](https://www.youtube.com/watch?v=1GPReTfneu4)

**Entrevistada:** Marjorie Luna Victoria  
**Edad:** 22 años  
**Ocupación:** Diseñadora gráfica  
**Ubicación:** Lima – Miraflores  
**Medio:** Meet  
**Entrevistador:** Jorge Díaz

🎬 **Inicio del video:** 0:04  
⏱️ **Duración:** 3 minutos y 42 segundos

Enlace del video de la entrevista:

[![Demo en YouTube](https://img.youtube.com/vi/hwdyWXskYcs/0.jpg)](https://www.youtube.com/watch?v=hwdyWXskYcs&ab_channel=NPCbas)

**Entrevistada:** Arlene Gutarra Velapatiño  
**Edad:** 22 años  
**Ocupación:** Estudiante de la carrera de Danza  
**Ubicación:** Lima – San Juan de Lurigancho  
**Medio:** Zoom  
**Entrevistador:** Sebastián Gutarra

🎬 **Inicio del video:** 0:04  
⏱️ **Duración:** 6 minutos y 23 segundos

Enlace del video de la entrevista:
[![Entrevista Danithza del Pino](Imagenes/Entrevista-Freelancer-1.png)](https://youtu.be/F3gz5at9sc4)
**Entrevistada:** Danithza del Pino
**Edad:** 28 años  
**Ocupación:** Estudiante de la carrera de Danza  
**Ubicación:** Lima – La Molina  
**Medio:** Zoom  
**Entrevistador:** Emilia Durán


**Entrevistada:** Carlos Alfredo Juarez Adanaque  
**Link de la entrevista:** [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202215623_upc_edu_pe/EdU9VOslalpKiKT-t0m66gMBmi1Xhl03H6JkroZCMl3Img?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=JREsKE)

![Img propietario2](Imagenes/Propietaria2.png)

**Entrevistada:** Alejandra Izaguirre  
**Link de la entrevista:** [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202215623_upc_edu_pe/EZQz2DANI71MkOrpc1fJq3EBIRLd8PZ4sQAEEFybRm3YOg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=t6qB71)

**Segmento 2**

![Img propietario2](Imagenes/Entrevista-Miguel.png)

**Link de la entrevista:** [Link-Entrevista](https://youtu.be/SHj6_AyGAPc)
**Entrevistado:** Miguel Quijada
**Edad:** 43 años  
**Ocupación:** Ingeniero de Software
**Ubicación:** Lima – Ate  
**Medio:** Zoom  
**Entrevistador:** Jeremy Quijada

### 2.2.3. Análisis de entrevistas

#### Freelancers

En las entrevistas para este segmento objetivo, los usuarios han utilizado con anterioridad espacios coworking para trabajar en las empresas que trabajan o de forma independiente para sus propias necesidades. Con las preguntas hemos logrado identificar que ellos estarian interesados en una aplicacion como esta y añaden que las funcionalidades que se esperan son las siguientes:

- Localicacion de espacios de trabajo
- Filtros de busqueda personalizados (Filtros como, cantidad de aforo, funcionalidad del espacio y facilidades servicios incluidos (Wi-Fi, café, impresoras, etc.))
- Valoraciones por otros usuarios
- Fotos de los inmuebles
- Calendario de disponibilidad para reservas

#### Propietarios de inmuebles

En las entrevistas de este segmento objetivo, recalcan que la aplicacion seria de mucha ayuda para encontrar a los inquilinos correctos de manera rapida, debido a que pueden decidir de una gran variedad de personas o empresas para que puedan usar estos lugares. Asimismo, Creen que la aplicacion web deberia ser de facil entendimiento para que puedan recibir los pagos adecuadamente. Algunas funcionalidades que agregaron para la aplicacion serian las siguientes:

- Contrato flexible
- Que se pueda modificar las publicaciones de manera sencilla
- Verificacion de perfiles para mas seguridad
- Sistema de pago seguro
- Chat para que haya una comunicacion activa

## 2.3. Needfinding

### 2.3.1. User Personas

Para esta sección hemos tomado en cuenta dos User Persona que corresponden a los dos segmentos objetivos nombrados anteriormente: los propietarios de inmuebles y los trabajadores independientes.

![User Persona 1](./imgs/Propietario%20de%20inmueble.png)

![User Persona 2](./imgs//Trabajador%20independiente%20_%20freelancer.png)

### 2.3.2. User Task Matrix

Estamos considerando los segmentos objetivos "Propietario de Inmueble" y "Trabajador independiente" como fueron definidos anteriormente como User Persona

|                                                    | **Propietario de Inmueble** |              | **Trabajador independiente** |              |
| -------------------------------------------------- | --------------------------- | ------------ | ---------------------------- | ------------ |
| Tarea                                              | Importancia                 | Frecuencia   | Importancia                  | Frecuencia   |
| Ofrecer su local                                   | 🔴 Alta                     | 🔴 Frecuente | ❌ N/A                       | ❌ N/A       |
| Buscar espacios de trabajo                         | ❌ N/A                      | ❌ N/A       | 🔴 Alta                      | 🔴 Frecuente |
| Comparar entre las opciones de espacios de trabajo | 🟡 Media                    | 🔵 Rara      | 🔴 Alta                      | 🔴 Frecuente |
| Contactarse el trabajador con el propietario       | 🔴 Alta                     | 🟡 Ocasional | 🔴 Alta                      | 🟡 Ocasional |
| Acordar precio y forma de pago                     | 🔴 Alta                     | 🟡 Ocasional | 🔴 Alta                      | 🟡 Ocasional |
| Observar situación final del local                 | 🟡 Media                    | 🟡 Ocasional | 🟡 Media                     | 🟡 Ocasional |
| Recomendar la experiencia                          | 🔵 Baja                     | 🔵 Rara      | 🟡 Media                     | 🟡 Ocasional |

### Leyenda:

Importancia
🔴 Alta
🟡 Media
🔵 Baja

Frecuencia
🔴 Frecuente
🟡 Ocasional
🔵 Rara

❌ N/A = No aplica para este usuario

Entre las tareas encontradas, la que ambos User Persona coinciden en que es importante y frecuente son tanto el contactarse mutuamente como el acordar precio y forma de pago, se debe a que ambos buscan que el préstamo del servicio se concrete y bajo condiciones favorables para ambos. Además, cada User Persona tiene su tarea particular: para el propietario es importante ofrecer su local y para el freelancer es importante buscar espacios de trabajo. Por último tenemos un tarea particular frecuente para el freelancer la cual es comparar diferentes ofertas de espacios de trabajo para ver lo que más se ajuste a su presupuesto y cuente con las características necesarias. Mientras que para el propietario, esto lo hace rara vez cuando desee ver qué precios ponen sus competidores.

### 2.3.3. User Journey Mapping

<p align="center">
  <img src="Imagenes/Customer Journey Map Brainstorm.png" alt="Customer Journey Map Brainstorm.png" />
</p>

### 2.3.4. Empathy Mapping

<p align="center">
  <img src="Imagenes/Empathy Map Brainstorm.png" alt="Empathy Map Brainstorm.png" />
</p>

### 2.3.5. As-is Scenario Mapping
**Freelancers**
![As-Is Freelancer](Imagenes/as-is-freelancer.jpg)

**Propietarios de Inmuebles**
![As-Is-Propietario](Imagenes/as-is-propietario.jpg)

## 2.4. Ubiquitous Language

| Término      | Definición                                                                                                  |
| ------------ | ----------------------------------------------------------------------------------------------------------- |
| Workspace    | Un espacio físico disponible para alquiler como sitio de trabajo.                                           |
| Coworking    | Una modalidad de trabajo donde personas de distintas empresas comparten un mismo workspace.                 |
| Host         | La persona que ofrece su propiedad en alquiler.                                                             |
| Renter       | La persona que alquila este espacio.                                                                        |
| Booking      | Confirmación de un alquiler hecho por un Renter de un Workspace por un periodo de tiempo.                   |
| Rate         | La tarifa por día o por semana para alquilar el Workspace.                                                  |
| Amenities    | Adicionales que ofrezca el host como parte del Workspace. Por ejemplo, WiFi, café, aire acondicionado, etc. |
| Listing      | La publicación de un Workspace disponible incluyendo detalles como ubicación, fotos, Rates y Amenities.     |
| Check-in     | El momento en que comienza el uso del Workspace.                                                            |
| Check-out    | El momento en el que finaliza el uso del Workspace.                                                         |
| Cancellation | La anulación de una reserva, por parte de Host o Renter.                                                    |
| Contract     | El contrato que se realiza entre Renter y Host.                                                             |
| Review       | Las reseñas dadas del Renter al Host después del uso del Workspace, visibles para otros usuarios.           |

# Capitulo III: Requirements Specification

## 3.1. User Stories

| User Story ID | Título                                                     | Descripción                                                                                                                                                                                    | Criterios de Aceptación                                                                                                                                                                                                                                                                                            | Epic ID |
| ------------- | ---------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------- |
| US-01         | Ubicacion de inmuebles                                     | Como freelancer, quiero encontrar la ubicacion de los inmuebles por localizacion para encontrar los lugares mas cercanos o convenientes                                                        | **Escenario 1**: Encontrar inmueble por ubicación <br><br> Dado que el freelancer busca un inmueble por ubicación <br><br> Entonces se muestra los inmuebles mas cercanos en la ubicacion <br><br>                                                                                                                 | EP-01   |
| US-02         | Disponibilidad de inmuebles                                | Como freelancer, quiero saber la disponibilidad actual del inmueble para hacer una eleccion correcta del tiempo que necesito el local                                                          | **Escenario 1**: Ver disponibilidad <br><br> Dado que el freelancer quiere ver la disponibilidad actual del inmueble, <br><br> Entonces se muestra la disponibilidad del inmueble para el freelancer                                                                                                               | EP-01   |
| US-03         | Filtros de busqueda                                        | Como freelancer quiero hacer una busqueda personalizada como cantidad de aforo, tipo de espacio y servicios disponibles para que pueda encontrar la mejor opcion para mi o mi equipo.          | **Escenario 1**: Busqueda de inmueble <br><br> Dado que el freelancer busca un tipo de espacio especifico <br><br> Entonces se muestran todas las opciones de los lugares con esas especificaciones                                                                                                                | EP-03   |
| US-04         | Valoraciones y opiniones                                   | Como freelancer quiero ver las valoraciones y opiniones de inmuebles sobre los espacios de trabajo para tomar una decisión informada.                                                          | **Escenario 1**: Review de un inmueble <br><br> Dado que el freelancer puede ver las valoraciones de otros usuarios de inmuebles. <br><br> Entonces puede tomar una mejor decision para encontrar el lugar adecuado                                                                                                | EP-02   |
| US-05         | Feeback constructivo                                       | Como propietario de inmueble, quiero recibir las opiniones o un feedback para reconocer posibles nuevas mejoras para el espacio de trabajo                                                     | **Escenario 1**: Recibe feedback <br><br> Dado que el propietario recibe recibir opiniones de los freelancers sobre su experiencia en el inmueble <br><br> Entonces puede hallar formas de mejorar su experiencia para futuros equipos o freelancers.                                                              | EP-04   |
| US-06         | Perfiles de inmuebles                                      | Como freelancer quiero encontrar la suficiente informacion para poder hacer una decision correcta detallada sobre cada inmueble, incluyendo fotos, ubicación, tarifas y servicios disponibles. | **Escenario 1**: Encontrar publicacion <br><br> Dado que el freelancer encuentra detalles como fotos, ubicación, tarifas y servicios disponibles <br><br> Entonces tendra una decision mas informada y adecuada para sus necesidades                                                                               | EP-03   |
| US-07         | Sistema de pagos seguros                                   | Como freelancer quiero tener la certeza de que la aplicacion web tenga un sistema de pago seguro                                                                                               | **Escenario 1**: Pago para la renta <br><br> Dado que el freelancer quiere pagar un mes adicional de renta <br><br> Entonces podra poder realizar el pago de manera segura a través de la aplicación                                                                                                               | EP-05   |
| US-08         | Sistema de devolucion                                      | Como freelancer, quiero tener la posibilidad de tener una devolucion de mi dinero si cancelo una reserva realizada antes del inicio de esta misma.                                             | **Escenario 1**: Devolucion de dinero dias antes de su uso registrado <br><br> Dado que el freelancer cancelo su reserva dias antes de su uso <br><br> Entonces el dinero que pago sera devuelto en los siguientes 15 dias.                                                                                        | EP-05   |
| US-09         | Publicacion de inmueble                                    | Como propietario de inmueble, quiero tener la facilidad de publicar un inmueble de manera sencilla y atractiva para que los freelancers lo encuentren llamativo                                | **Escenario 1**: Publicacion de inmueble <br><br> Dado que el propietario quiere publicar su inmueble con todos los datos necesarios <br><br> Entonces podra registrar toda la información necesaria, incluyendo fotos, descripción, ubicación, tarifas y servicios disponibles                                    | EP-04   |
| US-10         | Modificacion de inmueble                                   | Como propietario de inmueble quiero que se me permita actualizar la información de la publicación de manera sencilla y rápida para no arruinar la experiencia de freelancers.                  | **Escenario 1**: Modificacion de inmuebles <br><br> Dado que el propietario ha hecho remodelaciones en el lugar <br><br> Entonces podra modificar la informacion necesaria y de forma facil en la aplicacion web                                                                                                   | EP-04   |
| US-11         | Lugar libre de distracciones y ruidos                      | Como freelancer quiero estar en un lugar libre de distracciones y ruidos para obtener la mayor concentración y sacar provecho a mi tiempo de trabajo                                           | **Escenario 1**: Lugar libre de distracciones y ruidos<br><br>Dado que el freelancer desea aprovechar su tiempo y comodididad en el espacio alquilado<br><br>Entonces el local alquilado no tendrá ruidos molestos y si los tiene puede dejar una reseña sobre eso                                                 | EP-04   |
| US-12         | Precio altos                                               | Como freelancer, quiero comparar precios entre diferentes locales, para evitar precios y altos                                                                                                 | **Escenario 1**: Precios altos<br><br>Dado que el propietario coloca su precio que espera que le paguen<br><br> Entonces el usuario tendrá la posibilidad de comparar diferentes opciones de lugares, así obtener la que mejor le acomode                                                                          | EP-04   |
| US-13         | Alta demanda, la disponibilidad no abastece                | Como freelancer quiero saber la disponibilidad de los inmuebles, ya que hay horas de mayor necesidad                                                                                           | **Escenario 1**: Alta demanda, la disponibilidad no abastece<br><br>Dado que existe una demanda alta demanda de espacios de coworking en determinadas horas o dias<br><br> Entonces el aplicativo mostrará un cuadro donde se vea los horarios tomados y los horarios disponibles de los espacios                  | EP-04   |
| US-14         | No traigan personas externas                               | Como propietario quiero que el usuario no lleve a personas externas a mi local para que haya un uso correcto de mi local y siga las reglas                                                     | **Escenario 1**: No traigan a personas externas<br><br>Dado que el propietario no desea personas externas pues pueden causar desoren innecesario<br><br>Entonces se le reiteraría al freelancer esta reglas, o en caso contrario se le dejaría una reseña de mala conducta                                         | EP-04   |
| US-15         | Impuntualidad en pagos                                     | Como propietario quiero tener la certeza de que el usuario va a pagarme en el plazo establecido para evitar aquellos que son impuntuales                                                       | **Escenario 1**: Impuntualidad en pagos<br><br>Dado que el propietario quiere tener a tiempo el pago<br><br>Entonces se le reiteraría al freelancer esta reglas, o en caso contrario se le dejaría una reseña de impuntualidad                                                                                     | EP-04   |
| US-16         | Buena iluminación natural                                  | Como freelancer, quiero un ambiente con buena iluminación para que mejore mi rendimiento                                                                                                       | **Escenario 1**: Buena iluminación natural<br><br>Dado que el ambiente influye en el trabajo del freelancer<br><br>Entonces va a buscar un espacio que cumpla con esta característica                                                                                                                              | EP-04   |
| US-17         | Buena conexión a internet                                  | Como freelancer, quiero un ambiente con buena conexión a internet para que mejore mi rendimiento                                                                                               | **Escenario 1**: Buena conexión a internet<br><br>Dado que el freelancer quiere un tiempo de trabajo sin que el internet sea problema<br><br>Entonces el propietario va a poner claro la intensidad de los servicios telefónicas en ese local, o en lo contrario instalar wifi y ponerlo como caracteristica clave | EP-04   |
| US-18         | Tolerancia y respeto entre personas                        | Como freelancer, quiero que exista buena convivencia entre todos los que estemos en el coworking para sentirnos cómodos en el grupo                                                            | **Escenario 1**: Tolerancia y respeto entre personas<br><br>Dado que los freelancer compartirán espacios<br><br>Entonces esperan que todos estén comprometidos con cumplir normas básicas de convivencia                                                                                                           | EP-04   |
| US-19         | Fotos del estado del lugar al llegar y antes de entregarlo | Como propietario quiero que el freelancer mande una foto de cómo encontró el lugar y cómo lo está dejando para evitar malos entendidos                                                         | **Escenario 1**: Fotos del estado del lugar al llegar y al entregarlo<br><br>Dado que el propietario quiero tener la seguridad de que estén cuidadno su local<br><br>Entonces el freelancer va a mandar evidencia mediante fotos d cómo lo encontró y cómo lo está dejando                                         | EP-04   |
| US-20         | Un mapa para visualizar lugares                            | Como freelancer quiero un mapa para navegar a través de este y así elegir el distrito que más me convenga                                                                                      | **Escenario 1**: Mapa para visualizar lugares<br><br>Dado que el freelancer quiere hacer una búsqueda por distrito<br><br>Entonces implementar un mapa le va a facilitar la búsqueda porque asi puede ubicar mejor los puntos                                                                                      | EP-03   |
| US-21         | Amplitud del lugar                                         | Como freelancer quiero saber la amplitud del local a alquiler para ver si se acomodará a mis funciones a desempeñar                                                                            | **Escenario 1**: Amplitud del lugar<br><br>Dado que el freelancer tiene diferentes necesidades para sus actividades<br><br>Entonces el propietario debe especificar el tamaño, también se puede agregar un filtro de búsqueda por amplitud del local                                                               | EP-04   |
| US-22         | Fotos reales                                               | Como freelancer quiero ver imágenes de cómo se ve el local que voy a rentar para saber que es de mi agrado                                                                                     | **Escenario 1**: Fotos reales<br><br>Dado que el freelancer quiere ver de primera mano cómo es el local que va a alquilar<br><br>Entonces el propietario debe colocar fotos del local y actualizarlas periódicamente                                                                                               | EP-03   |
| US-23         | Servicios como estacionamiento, cafetería, entre otros     | Como freelancer quiero saber si el espacio de coworking cuenta con ciertos servicios para tomar una decisión en base a eso                                                                     | **Escenario 1**: Servicios como estacionamiento, cafetería, entre otros<br><br>Dado que el freelancer quiere tener algún servicio<br><br>Entonces habrá un filtro de búsqueda de los locales que sí cuenten con dicho servicio                                                                                     | EP-04   |
| US-24         | Cobro por hora, en vez de por día                          | Como propietario de inmueble quiero opciones en los horarios de alquiler de mi local para ofrecer opciones más flexibles                                                                       | **Escenario 1**: Cobro por hora, en vez de por día<br><br>Dado que el propietario quiere horarios y pagos más flexibles<br><br>Entonces se implementa la opción de alquilar el local por tiempos más pequeños y flexibles                                                                                          | EP-04   |
| US-25         | Sistema fácil de entender e intuitivo                      | Como propietario de inmuebles, quiero que esta propuesta de aplicación se fácil de entender para poder usarla a largo plazo                                                                    | **Escenario 1**: Sistema fácil de entender e intuitivo<br><br>Dado que el propietario tiene conocimientos básicos del uso de plataformas<br><br>Entonces se le brindará una plataforma que sea comprensible o algún tutorial interactivo para que se adapte                                                        | EP-01   |
| US-26         | Reserva rápida                                             | Como freelancer quiero que la aplicación tenga una carga rápida y esté actualizada para tener informacion precisa                                                                              | **Escenario 1**: Reserva rápida<br><br>Dado que el usuario quiere que su reserva se realice lo más pronto posible<br><br>Entonces la plataforma deberá procesar la solicitud de la manera más eficiente                                                                                                            | EP-02   |
| US-27         | Chat directo propietario y cliente                         | Como propietario quiero contactarme directamente con el usuario interesado para tener la certeza de que se concrete el acuerdo                                                                 | **Escenario 1**: Chat directo propietario y cliente<br><br>Dado que el propietario quiere tener una conversacion directa con quien va a alquilar su local<br><br>Entonces la plataforma deberá tener un chat directo entre propietarios y clientes                                                                 | EP-01   |
| US-28         | Calendario para ver la disponibilidad del espacio          | Como freelancer quiero ver en formato de calendario para navegar mejor a través de los días disponibles del inmueble                                                                           | **Escenario 1**: Calendario para ver la disponibilidad del espacio<br><br>Dado que el freelancer quiere tener un calendario para facilitar su búsqueda<br><br>Entonces se implemntará uno en la aplataforma al contratar el local                                                                                  | EP-01   |
| US-29         | Sistema de reseñas pra ambas partes                        | Como propietario, quiero saber opiniones de otros propietarios para estar más convencidos de alquilar mi local a ciertos usuarios                                                              | **Escenario 1**: Sistema de reseñas para ambas partes<br><br>Dado que tanto el freeelancer como el propietario quieren saber más contexto antes de hacer la contrata<br><br>Entonces la plataforma mostrará las reseñas                                                                                            | EP-03   |
| US-30         | Usuarios verficiados con LinkedIn o DNI                    | Como propietario quiero una forma de verificar la informacion del freelancer para estar informado de que su trabajo es serio y va con mis criterios                                            | **Escenario 1**: Usuarios verficiados con LinkedIn o DNI<br><br>DAdo que el porpietario quiere tener la seguridad de a quien está alquilando<br><br>Entonces la plataforma promoverá a sus usuarios a verificarse                                                                                                  | EP-05   |
| US-31         | Navegación por el landing page                             | Como usuario quiero explorar fácilmente el landing page para acceder a la información clave.                                                                                                   | **Escenario 1**: Acceso intuitivo al landing page<br><br> Dado que el usuario necesita navegar con facilidad<br><br> Entonces la página principal estará estructurada de forma simple y clara.                                                                                                                     | EP-05   |
| US-32         | Ver información del startup                                | Como usuario quiero conocer más sobre el proyecto para tomar una decisión informada.                                                                                                           | **Escenario 1**: Información sobre el startup<br><br> Dado que los usuarios desean más detalles<br><br> Entonces se incluirá una sección con datos relevantes de la startup.                                                                                                                                       | EP-05   |
| US-33         | Conocer los servicios                                      | Como usuario quiero revisar los servicios ofrecidos para decidir cuáles se ajustan a mis necesidades.                                                                                          | **Escenario 1**: Exploración de servicios<br><br> Dado que los usuarios necesitan opciones claras<br><br> Entonces la plataforma mostrará servicios categorizados.                                                                                                                                                 | EP-05   |
| US-34         | Contactar al equipo de soporte                             | Como usuario quiero una manera rápida de contactar al equipo para resolver dudas o problemas.                                                                                                  | **Escenario 1**: Contacto rápido con soporte<br><br> Dado que los usuarios pueden enfrentar problemas<br><br> Entonces se incluirá un botón de contacto directo en la interfaz.                                                                                                                                    | EP-05   |
| US-35         | Cambiar lenguaje entre Español e Inglés                    | Como usuario quiero la opción de cambiar el idioma de la plataforma para utilizar el idioma con el que me sienta más cómodo.                                                                   | **Escenario 1**: Cambio de idioma<br><br> Dado que algunos usuarios prefieren otro idioma<br><br> Entonces se incluirá un selector de idioma en la plataforma.                                                                                                                                                     | EP-05   |
| US-36         | Mostrar testimonios y casos de éxito                       | Como usuario quiero leer experiencias reales para ganar confianza en el proyecto.                                                                                                              | **Escenario 1**: Testimonios visibles<br><br> Dado que los usuarios buscan referencias confiables<br><br> Entonces se incluirán testimonios destacados en una sección dedicada.                                                                                                                                    | EP-05   |
| US-37         | Descargar información del proyecto                         | Como usuario quiero una opción para descargar un folleto informativo sobre el proyecto en formato digital.                                                                                     | **Escenario 1**: Folleto descargable<br><br> Dado que los usuarios prefieren tener información detallada<br><br> Entonces se incluirá una opción de descarga en la plataforma.                                                                                                                                     | EP-05   |
| US-38         | Registro de Propietarios                                   | Como propietario, quiero registrar mis datos para poder publicar oficinas y administrar mis espacios                                                                                           | **Escenario 1**: Registro exitoso de propietario <br><br> Dado que un nuevo propietario ingresa sus datos <br><br> Cuando envía el formulario <br><br> Entonces el sistema guarda los datos y retorna confirmación                                                                                                 | EP-02   |
| US-39         | Publicación de Oficinas                                    | Como propietario, quiero publicar detalles de mis oficinas disponibles para que los freelancers puedan verlas y reservarlas                                                                    | **Escenario 1**: Publicar una nueva oficina <br><br> Dado que el propietario tiene acceso al panel de oficinas <br><br> Cuando ingresa la información requerida <br><br> Entonces se publica la oficina con disponibilidad                                                                                         | EP-02   |
| US-40         | Mensajes entre usuarios                                    | Como usuario, quiero enviar y recibir mensajes para poder comunicarme con el propietario o el freelancer relacionado a una oficina                                                             | **Escenario 1**: Enviar un mensaje <br><br> Dado que un usuario accede a la conversación <br><br> Cuando redacta y envía un mensaje <br><br> Entonces el mensaje es visible para el receptor en tiempo real                                                                                                        | EP-02   |
| US-41         | Búsqueda avanzada de oficinas                              | Como freelancer, quiero filtrar oficinas por servicios, precio, capacidad y ubicación para encontrar la opción ideal                                                                           | **Escenario 1**: Búsqueda con filtros <br><br> Dado que el usuario ingresa criterios de búsqueda <br><br> Cuando ejecuta la búsqueda <br><br> Entonces el sistema retorna solo las oficinas que cumplen con los filtros seleccionados                                                                              | EP-02   |
| US-42         | Calificar experiencia de oficina                           | Como freelancer, quiero calificar la oficina y al propietario para ayudar a otros usuarios a tomar decisiones informadas                                                                       | **Escenario 1**: Enviar calificación <br><br> Dado que un freelancer finalizó su estancia <br><br> Cuando envía una calificación y comentario <br><br> Entonces esta se guarda y se refleja en el perfil del propietario y de la oficina                                                                           | EP-02   |

### Epics

| Epic ID | Título                      | Descripción                                                                                                                                                                 |
| ------- | --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP-01   | Desarrollo del Landing Page | Esta enfocado en la creacion de la pagina web inicial que se presentará al consumidor para luego ser redirigido a la aplicacion web                                         |
| EP-02   | Desarrollo del Backend      | Se enfoca en la lógica de negocio, estructuras de datos, endpoints y funcionalidades que permitirán las operaciones y servicios que la aplicacion web ofrece                |
| EP-03   | Desarrollo del Frontend     | Es enfocado en la interfaz de usuario, la experiencia del cliente y la implementación de las funcionalidades visuales que permitirán la interacción con la aplicación.      |
| EP-04   | Experiencia del desarrollo  | Esta enfocada en establecer las metas y la metodología de desarrollo, incluyendo las herramientas y procesos utilizados para asegurar la calidad y eficiencia del proyecto. |
| EP-05   | Seguridad de la aplicacion  | Esta enfocado en ofrecer un entorno seguro y confiable para los usuarios, garantizando la protección de datos y la privacidad en todas las transacciones.                   |

## 3.2. Impact Mapping

![ImpactMap](Imagenes/Plantilla%20de%20mapa%20de%20impacto.jpg)

## 3.3. Product Backlog

| ID  | Historia de Usuario                                                                                                                                | Prioridad |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| 1   | Como freelancer, quiero encontrar la ubicacion de los inmuebles por localizacion para encontrar los lugares mas cercanos o convenientes            | Alta      |
| 2   | Como freelancer, quiero saber la disponibilidad actual del inmueble para hacer una eleccion correcta del tiempo que necesito el local              | Alta      |
| 8   | Como freelancer, quiero tener la posibilidad de tener una devolucion de mi dinero si cancelo una reserva realizada antes del inicio de esta misma. | Media     |
| 7   | Como freelancer quiero tener la certeza de que la aplicacion web tenga un sistema de pago seguro                                                   | Alta      |
