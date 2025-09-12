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

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
  - [Contenido](#contenido)
      - [Tabla de contenidos](#tabla-de-contenidos)
  - [Student Outcome](#student-outcome)
  - [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [Descripción de la Problemática](#descripción-de-la-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [Dominio del Problema](#dominio-del-problema)
      - [Segmentos de Cliente](#segmentos-de-cliente)
      - [Puntos de Dolor](#puntos-de-dolor)
      - [Brecha Detectada](#brecha-detectada)
      - [Visión y Estrategia](#visión-y-estrategia)
      - [Segmento Inicial](#segmento-inicial)
      - [1.2.2.2. Lean UX Problem Assumptions](#1222-lean-ux-problem-assumptions)
      - [1.2.2.3. Lean UX Problem Hypothesis Statements](#1223-lean-ux-problem-hypothesis-statements)
      - [1.2.2.4. Lean UX Problem Canvas](#1224-lean-ux-problem-canvas)
      - [1. Business Problem](#1-business-problem)
      - [2. Business Outcomes](#2-business-outcomes)
      - [3. Users](#3-users)
      - [4. User Benefits](#4-user-benefits)
      - [5. Solutions](#5-solutions)
      - [6. Hypotheses](#6-hypotheses)
      - [7. What’s the most important thing we need to learn first?](#7-whats-the-most-important-thing-we-need-to-learn-first)
      - [8. What’s the least amount of work we need to do to learn the next most important thing?](#8-whats-the-least-amount-of-work-we-need-to-do-to-learn-the-next-most-important-thing)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
    - [Propietarios de Inmuebles (Coworkings)](#propietarios-de-inmuebles-coworkings)
      - [Características Demográficas](#características-demográficas)
      - [Datos Relevantes](#datos-relevantes)
      - [Necesidades Clave](#necesidades-clave)
    - [Freelancers y Startups](#freelancers-y-startups)
      - [Características Demográficas](#características-demográficas-1)
      - [Datos Relevantes](#datos-relevantes-1)
      - [Necesidades Clave](#necesidades-clave-1)
  - [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
      - [Freelancers](#freelancers)
      - [Propietarios de inmuebles](#propietarios-de-inmuebles)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [Leyenda:](#leyenda)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capitulo III: Requirements Specification](#capitulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
    - [Epics](#epics)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)


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

| User Story ID | Título | Descripción | Criterios de Aceptación | Epic ID |
| :---- | :---- | :---- | :---- | :---- |
| US-01 | Búsqueda por ubicación | Como freelancer, quiero buscar espacios por ciudad, distrito o cercanía (geolocalización) para encontrar lugares cercanos o convenientes. | "Escenario 1: Búsqueda por texto Dado que estoy en la búsqueda y escribo una ciudad/distrito, Cuando presiono Buscar, Entonces la lista y el mapa muestran espacios dentro del radio configurado ordenados por distancia. Escenario 2: Usar mi ubicación Dado que concedí permisos de geolocalización, Cuando activo “Usar mi ubicación”, Entonces veo resultados cercanos actualizados y puedo ajustar el radio."  | EP-03 |
| US-02 | Disponibilidad en tiempo real | Como freelancer, quiero filtrar por capacidad, tipo de espacio y servicios para encontrar la mejor opción para mí o mi equipo. | "Escenario 1: Ver calendario Dado la ficha de un espacio, Cuando selecciono fecha y hora, Entonces se muestran slots libres/ocupados en tiempo real evitando doble reserva. Escenario 2: Selección inválida Dado un slot ya reservado, Cuando intento elegirlo, Entonces el sistema lo bloquea y sugiere horarios disponibles."  | EP-02 |
| US-03 | Filtros avanzados | Como freelancer, quiero filtrar por capacidad, tipo de espacio y servicios para encontrar la mejor opción para mí o mi equipo. |  "Escenario 1: Filtros combinados Dado los filtros de capacidad/amenities/precio, Cuando aplico varios, Entonces la lista y el mapa se actualizan mostrando el conteo de resultados. Escenario 2: Limpiar filtros Dado que hay filtros activos, Cuando presiono Limpiar, Entonces se restablecen los resultados completos."  | EP-03 |
| US-04 | Ver reseñas y calificaciones | Como freelancer, quiero ver las reseñas y calificaciones de otros usuarios para tomar una decisión informada. | "Escenario 1: Ver reseñas Dado un espacio con reseñas, Cuando abro su ficha, Entonces veo rating promedio, cantidad y comentarios más útiles. Escenario 2: Sin reseñas Dado un espacio sin reseñas, Cuando abro su ficha, Entonces veo el estado “Aún sin reseñas” e invitación a ser el primero en opinar."  | EP-02 |
| US-05 | Responder feedback | Como propietario, quiero recibir reseñas y poder responderlas para mejorar el espacio y la experiencia |  "Escenario 1: Responder reseña Dado que recibí una reseña, Cuando la abro en mi panel, Entonces puedo responder una vez de forma pública. Escenario 2: Moderación Dado una respuesta enviada, Cuando incumple políticas, Entonces se oculta y se notifica el motivo al propietario."  | EP-02 |
| US-06 | Ficha completa del espacio | Como freelancer, quiero ver fotos, mapa, precios, horarios, amenities, reglas y política de cancelación para evaluar si el espacio cumple mis necesidades. |  "Escenario 1: Información completa Dado la ficha del espacio, Cuando la visito, Entonces veo al menos 5 fotos, mapa, tarifas por hora/día, horarios, amenities, reglas y política de cancelación. Escenario 2: Política visible Dado que estoy en el checkout, Cuando reviso condiciones, Entonces la política de cancelación está visible y enlaza a detalle."  | EP-03 |
| US-07 | Pagos seguros | Como freelancer, quiero pagar con métodos seguros y recibir comprobante para tener confianza en la transacción. | "Escenario 1: Pago exitoso Dado el checkout, Cuando ingreso un método válido, Entonces el pago se procesa por pasarela segura y recibo comprobante. Escenario 2: Pago fallido Dado un medio rechazado, Cuando intento pagar, Entonces se informa el error y la reserva no se confirma."  | EP-05 |
| US-08 | Reembolsos según política | Como freelancer, quiero obtener devolución si cancelo dentro de la política para reducir el riesgo de la reserva. | "Escenario 1: Cancelación dentro de plazo Dado una reserva vigente, Cuando cancelo dentro de la ventana permitida, Entonces se calcula el porcentaje y se inicia reembolso al mismo método. Escenario 2: Fuera de plazo Dado que superé el plazo, Cuando cancelo, Entonces no corresponde reembolso y se muestra la política aplicada."  | EP-02 |
| US-09 | Publicar espacio | Como propietario, quiero registrar un espacio con todos los datos requeridos para que los freelancers lo encuentren y reserven. | "Escenario 1: Publicar espacio Dado el formulario de alta, Cuando completo campos obligatorios (título, dirección, fotos, tarifas, horarios, amenities y reglas), Entonces puedo previsualizar y publicar. Escenario 2: Validación de fotos Dado un intento de publicar sin fotos mínimas, Cuando envío, Entonces se bloquea y se indica el requisito."  | EP-02 |
| US-10 | Editar publicación | Como propietario, quiero actualizar información de mi publicación para mantener la información correcta | "Escenario 1: Editar publicación Dado una publicación existente, Cuando actualizo tarifas o detalles, Entonces los cambios se guardan con versión. Escenario 2: Integridad histórica Dado reservas pasadas, Cuando edito la publicación, Entonces los comprobantes y reservas históricas permanecen intactos."  | EP-02 |
| US-11 | Filtro por nivel de ruido | Como freelancer, quiero filtrar por espacios silenciosos para maximizar mi concentración |  "Escenario 1: Filtro silencioso Dado la búsqueda, Cuando activo el filtro “silencioso”, Entonces solo aparecen espacios etiquetados como silenciosos o con rating de ruido ≥ umbral. Escenario 2: Ver indicador Dado la ficha del espacio, Cuando consulto Ambiente, Entonces veo el indicador/etiqueta de nivel de ruido."  | EP-03 |
| US-12 | Comparación de precios | Como freelancer, quiero comparar precios por hora/día con cargos incluidos para evitar pagar de más. | "Escenario 1: Ordenar por precio Dado una búsqueda, Cuando ordeno por precio, Entonces los resultados se listan de menor a mayor total estimado. Escenario 2: Total transparente Dado el comparador, Cuando abro 2–3 espacios, Entonces veo el total con impuestos y comisiones incluidos."  | EP-03 |
| US-13 | Horas pico en calendario | Como freelancer, quiero ver horas de alta demanda en el calendario para planificar mejor mi reserva. | "Escenario 1: Horas pico Dado el calendario, Cuando abro una fecha, Entonces se resaltan horas con ocupación \>80%. Escenario 2: Sugerencias Dado horas pico, Cuando no hay disponibilidad, Entonces se sugieren horarios alternativos cercanos."  | EP-02 |
| US-14 | Reglas sobre invitados | Como propietario, quiero definir si se permiten personas externas para cuidar el orden del local. | "Escenario 1: Aceptación de reglas Dado el checkout, Cuando voy a confirmar, Entonces debo aceptar las reglas sobre invitados. Escenario 2: Reporte de incumplimiento Dado una reserva finalizada, Cuando reporto ingreso de externos no permitidos, Entonces queda registro para revisión."  | EP-02 |
| US-15 | Política de cobro y puntualidad | Como propietario, quiero asegurar pagos a tiempo para evitar impagos. |  "Escenario 1: Cobro garantizado Dado el checkout, Cuando confirmo, Entonces se captura el pago o se preautoriza garantía según política. Escenario 2: Pago tardío Dado que el cobro falla por retraso, Cuando reintento fuera de plazo, Entonces se aplica la penalidad definida."  | EP-02 |
| US-16 | Filtro por iluminación natural | Como freelancer, quiero filtrar por calidad de iluminación para mejorar mi rendimiento. | "Escenario 1: Filtrar por iluminación Dado la búsqueda, Cuando activo “buena iluminación”, Entonces veo espacios con esa característica. Escenario 2: Evidencia visual Dado la ficha del espacio, Cuando reviso fotos, Entonces encuentro evidencia de iluminación natural."  | EP-03 |
| US-17 | Conectividad a internet | Como freelancer, quiero ver velocidad/estabilidad de internet y filtrar por Mbps para evitar interrupciones. | "Escenario 1: Filtro por Mbps Dado la búsqueda, Cuando fijo “≥ 50 Mbps”, Entonces solo veo espacios que cumplen o superan ese valor. Escenario 2: Ver conectividad Dado la ficha, Cuando abro conectividad, Entonces veo tipo de conexión y velocidad declarada."  | EP-03 |
| US-18 | Código de convivencia | Como freelancer, quiero aceptar normas de convivencia en espacios compartidos para garantizar respeto. |  "Escenario 1: Aceptar convivencia Dado el proceso de reserva, Cuando avanzo al pago, Entonces debo aceptar el código de convivencia. Escenario 2: Reportar incidente Dado una reserva, Cuando reporto un incidente, Entonces se genera ticket asociado a la reserva."  | EP-02 |
| US-19 | Fotos de check‑in/checkout | Como propietario, quiero que el usuario suba fotos al llegar y al salir para evitar malos entendidos por daños. |  "Escenario 1: Check‑in con fotos Dado una reserva activa, Cuando ingreso al local, Entonces puedo subir hasta 5 fotos con sello de fecha/hora. Escenario 2: Check‑out con fotos Dado que finalizo, Cuando adjunto fotos de salida, Entonces ambas partes las visualizan en el detalle."  | EP-02 |
| US-20 | Mapa interactivo | Como freelancer, quiero explorar resultados en un mapa interactivo para ubicar mejor los espacios por zona. | "Escenario 1: Sincronía mapa‑lista Dado resultados en mapa, Cuando hago pan/zoom, Entonces la lista se sincroniza con el área visible. Escenario 2: Clustering Dado múltiples puntos cercanos, Cuando hago zoom, Entonces los clústeres se expanden en marcadores individuales."  | EP-03 |
| US-21 | Capacidad y tamaño (m²) | Como freelancer, quiero conocer m² y aforo del espacio y filtrarlos para ver si se ajusta a mis actividades | "Escenario 1: Ver m² y aforo Dado la ficha, Cuando abro Detalles, Entonces se muestran m² y aforo del espacio. Escenario 2: Filtrar por capacidad Dado la búsqueda, Cuando indico aforo mínimo, Entonces solo aparecen espacios que lo cumplen."  | EP-03 |
| US-22 | Galería de fotos reales | Como freelancer, quiero ver imágenes reales y claras del espacio para saber si es de mi agrado. | "Escenario 1: Galería mínima Dado una publicación, Cuando la abro, Entonces veo al menos 5 fotos nítidas. Escenario 2: Reporte de foto Dado una foto inapropiada, Cuando la reporto, Entonces entra a revisión de moderación."  | EP-03 |
| US-23 | Servicios/Amenities | Como freelancer, quiero saber qué servicios incluye el espacio y filtrarlos para decidir en base a mis necesidades. | "Escenario 1: Ver amenities Dado una ficha, Cuando abro Servicios, Entonces veo la lista de amenities disponibles. Escenario 2: Filtrar por amenity Dado la búsqueda, Cuando activo un amenity, Entonces solo se muestran espacios que lo incluyen."  | EP-03 |
| US-24 | Tarifas por hora/día/mes | Como propietario, quiero configurar tarifas por hora/día/mes y duración mínima para ofrecer opciones flexibles. | "Escenario 1: Unidad de tarifa Dado la publicación, Cuando configuro hora/día/mes y mínimos, Entonces el total del checkout se calcula correctamente. Escenario 2: Validación de mínimo Dado un intento bajo el mínimo, Cuando confirmo, Entonces el sistema impide continuar y muestra el requisito."  | EP-02 |
| US-25 | Interfaz intuitiva (onboarding) | Como propietario, quiero un onboarding e interfaz intuitiva para publicar mi primer espacio con facilidad. | "Escenario 1: Onboarding guiado Dado un propietario nuevo, Cuando inicia el asistente, Entonces completa la publicación en ≤20 minutos gracias a ayudas contextuales. Escenario 2: Validaciones de campo Dado formularios incompletos, Cuando intento avanzar, Entonces se muestran mensajes de validación claros."  | EP-04 |
| US-26 | Reserva en ≤3 pasos | Como freelancer, quiero completar la reserva en pocos pasos para ahorrar tiempo. |  "Escenario 1: Flujo corto Dado que elegí espacio y horario, Cuando voy al checkout, Entonces finalizo en ≤3 pasos y recibo confirmación ≤60s. Escenario 2: Datos faltantes Dado información incompleta, Cuando intento continuar, Entonces se señala el campo faltante sin perder progreso."  | EP-03 |
| US-27 | Chat propietario‑cliente | Como propietario, quiero mensajería directa con el interesado para aclarar dudas y cerrar la reserva. | "Escenario 1: Notificación de mensaje Dado una conversación, Cuando envío un mensaje, Entonces el receptor recibe notificación en tiempo real. Escenario 2: Lectura Dado mensajes enviados, Cuando el receptor los lee, Entonces veo indicador de leído."  | EP-02 |
| US-28 | Calendario de disponibilidad | Como freelancer, quiero ver un calendario navegable por días y horas para facilitar mi búsqueda. | "Escenario 1: Slots bloqueados Dado el calendario, Cuando una franja ya está reservada, Entonces aparece deshabilitada. Escenario 2: Zona horaria Dado mi perfil, Cuando veo el calendario, Entonces los horarios se muestran en mi zona horaria."  | EP-03 |
| US-29 | Reseñas de ambas partes | Como propietario, quiero que ambas partes puedan dejar y ver reseñas para tomar mejores decisiones. | "Escenario 1: Ventana de reseñas Dado una reserva finalizada, Cuando estoy dentro de 14 días, Entonces puedo calificar y comentar. Escenario 2: Publicación bilateral Dado reseñas de ambas partes, Cuando se envían, Entonces se publican y afectan el rating promedio."  | EP-02 |
| US-30 | Usuarios verificados (DNI/LinkedIn) | Como propietario, quiero verificación de usuarios por DNI o LinkedIn para tener mayor seguridad. | "Escenario 1: Verificación exitosa Dado un usuario, Cuando completa verificación por DNI/LinkedIn, Entonces su perfil muestra insignia 'Verificado'. Escenario 2: Requisito para reservas altas Dado una reserva de alto valor, Cuando no estoy verificado, Entonces se solicita verificación antes de pagar."  | EP-05 |
| US-31 | Navegación en landing | Como usuario, quiero explorar fácilmente la landing page para acceder a información clave. | "Escenario 1: Navegación clara Dado la landing, Cuando uso el menú, Entonces accedo a 'Cómo funciona', 'Publicar mi espacio' y 'Soporte' con CTAs visibles. Escenario 2: Responsive Dado un móvil, Cuando abro la landing, Entonces la estructura se adapta correctamente."  | EP-01 |
| US-32 | Información de la startup | Como usuario, quiero conocer misión, equipo y políticas del proyecto para tomar una decisión informada. | "Escenario 1: Sección Acerca de Dado la landing, Cuando abro 'Acerca de', Entonces veo misión, equipo y valores. Escenario 2: Políticas Dado necesito detalles legales, Cuando abro enlaces, Entonces veo Términos y Privacidad vigentes."  | EP-01 |
| US-33 | Explorar servicios en landing | Como usuario, quiero revisar los servicios ofrecidos en la landing para decidir cuáles se ajustan a mí. | "Escenario 1: Ver servicios Dado la landing, Cuando abro 'Servicios', Entonces veo categorías con descripciones. Escenario 2: Ir a resultados Dado una categoría, Cuando hago clic, Entonces se abre la búsqueda con filtros preaplicados."  |  EP-01  |
| US-34 | Acceso a soporte | Como usuario, quiero contactar rápidamente al equipo de soporte para resolver dudas o problemas. | "Escenario 1: Abrir ticket Dado la sección Soporte, Cuando creo un ticket, Entonces recibo número de caso y correo de confirmación. Escenario 2: Chat Dado el botón de chat, Cuando lo inicio, Entonces puedo conversar con el equipo o bot y recibir transcripción."  | EP-01 |
| US-35 | Selector de idioma ES/EN | Como usuario, quiero cambiar el idioma de la interfaz (ES/EN) para usar la plataforma en mi idioma. | "Escenario 1: Cambiar a EN/ES Dado el selector de idioma, Cuando elijo EN o ES, Entonces toda la UI cambia de idioma. Escenario 2: Persistencia Dado que ya elegí idioma, Cuando vuelvo a entrar, Entonces se recuerda mi preferencia."  | EP-01 |
| US-36 | Testimonios y casos de éxito | Como usuario, quiero ver testimonios y casos de éxito para ganar confianza. |  "Escenario 1: Ver testimonios Dado la sección Testimonios, Cuando la abro, Entonces veo citas con nombre y foto verificados. Escenario 2: Reporte Dado un testimonio cuestionable, Cuando lo reporto, Entonces se oculta tras revisión si incumple políticas."  | EP-01 |
| US-37 | Descargar folleto del proyecto | Como usuario, quiero descargar un folleto informativo en PDF para guardar detalles del proyecto o compartirlos. | "Escenario 1: Descargar PDF Dado la landing, Cuando hago clic en 'Descargar folleto', Entonces se descarga el PDF actualizado. Escenario 2: Metadatos Dado el archivo, Cuando lo abro, Entonces muestra fecha de versión y datos de contacto."  |  EP-01  |
| US-38 | Registro de propietarios | Como propietario, quiero crear mi cuenta y registrar datos legales y de pago para publicar oficinas y administrarlas. | "Escenario 1: Registro de propietario Dado el formulario, Cuando ingreso datos personales/legales y acepto términos, Entonces se crea mi cuenta y recibo correo de verificación. Escenario 2: Datos de cobro Dado mi nueva cuenta, Cuando configuro cuenta bancaria/pasarela, Entonces queda habilitada la publicación."  | EP-02 |
| US-39 | Wizard para publicar oficinas | Como propietario, quiero publicar una oficina con un asistente paso a paso para acelerar la publicación y evitar errores. | "Escenario 1: Asistente paso a paso Dado el panel, Cuando inicio 'Nueva oficina', Entonces completo secciones con validación por paso hasta publicar. Escenario 2: Duplicar publicación Dado una oficina existente, Cuando elijo Duplicar, Entonces se crea un borrador editable con la información copiada."  | EP-02 |
| US-40 | Mensajería entre usuarios | Como usuario, quiero enviar y recibir mensajes con el propietario o freelancer para coordinar detalles de una oficina. | "Escenario 1: Mensaje en conversación Dado una publicación/reserva, Cuando envío un mensaje, Entonces el receptor lo ve en tiempo real. Escenario 2: Denunciar mensaje Dado un mensaje ofensivo, Cuando lo denuncio, Entonces queda marcado para moderación."  |  EP-02  |
| US-41 | Búsqueda avanzada de oficinas | Como freelancer, quiero una búsqueda avanzada por servicios, precio, capacidad y ubicación para encontrar la opción ideal. | "Escenario 1: Búsqueda avanzada Dado que ingreso criterios múltiples, Cuando ejecuto la búsqueda, Entonces retorne solo oficinas que cumplen. Escenario 2: Ordenamiento Dado la lista, Cuando ordeno por precio/rating/distancia, Entonces cambia el orden acorde."  | EP-03 |
| US-42 | Calificar la experiencia | Como freelancer, quiero calificar la oficina y al propietario con un comentario para ayudar a otros a decidir mejor. | "Escenario 1: Calificar con comentario Dado una reserva finalizada, Cuando califico 1–5 y comento, Entonces se publica la reseña. Escenario 2: Edición limitada Dado mi reseña, Cuando deseo corregir, Entonces puedo editarla una vez dentro de 48h."  | EP-02 |
| US-43 | Favoritos (wishlist) | Como freelancer, quiero guardar espacios en una lista de favoritos para revisarlos y reservar más tarde. |  "Escenario 1: Guardar favorito Dado una ficha, Cuando pulso Guardar, Entonces el espacio queda en mi lista de favoritos. Escenario 2: Ver/compartir favoritos Dado mi lista, Cuando la abro, Entonces puedo ver, quitar y compartir enlaces."  | EP-03 |
| US-44 | Alertas de búsqueda | Como freelancer, quiero recibir alertas cuando haya nuevas opciones o bajadas de precio para no perder oportunidades. |  "Escenario 1: Guardar búsqueda Dado criterios, Cuando guardo la búsqueda, Entonces queda disponible en mi perfil. Escenario 2: Notificación Dado una búsqueda guardada, Cuando aparece un espacio nuevo o baja de precio, Entonces recibo email/push."  | EP-02 |
| US-45 | Multi‑moneda | Como usuario, quiero ver precios en mi moneda local con conversión automática para comprender el costo real. | "Escenario 1: Moneda local Dado mi país, Cuando navego, Entonces los precios se muestran en mi moneda. Escenario 2: Tipo de cambio Dado el checkout, Cuando selecciono pagar, Entonces se aplica el tipo de cambio del día y se muestra el total final."  | EP-02 |
| US-46 | Localización completa | Como usuario, quiero que la plataforma esté localizada (idioma, fechas y formatos) para evitar confusiones. |  "Escenario 1: Formatos locales Dado mi configuración, Cuando veo fechas y números, Entonces se muestran en el formato local. Escenario 2: Horario 12/24h Dado mi región, Cuando veo horas, Entonces se respeta el formato 12/24h correspondiente."  | EP-03 |
| US-47 | Cupones y créditos | Como usuario, quiero aplicar cupones o créditos en el checkout para ahorrar en la reserva. | "Escenario 1: Aplicar cupón Dado el checkout, Cuando ingreso un cupón válido, Entonces el total se actualiza y queda registrado. Escenario 2: Cupón inválido/expirado Dado un código no elegible, Cuando lo aplico, Entonces se muestra error y no se descuenta."  | EP-02 |
| US-48 | Centro de ayuda y tickets | Como usuario, quiero un centro de ayuda con artículos y tickets para resolver problemas. | "Escenario 1: Buscar ayuda Dado el Centro de ayuda, Cuando busco un término, Entonces veo artículos relevantes. Escenario 2: Crear ticket Dado que no encontré solución, Cuando creo un ticket, Entonces recibo confirmación y puedo ver su estado."  | EP-02 |
| US-49 | Calendario externo (Google/Outlook) | Como freelancer, quiero agregar mi reserva a Google/Outlook (iCal) para organizar mi agenda. | "Escenario 1: Agregar al calendario Dado una reserva confirmada, Cuando pulso “Agregar al calendario”, Entonces se crea un evento con dirección y horario. Escenario 2: Suscripción iCal Dado que me suscribo al feed, Cuando cambie la reserva, Entonces el evento se actualiza/cancela automáticamente."  | EP-02 |
| US-50 | Plan corporativo (wallet) | Como empresa, quiero asignar saldo o asientos a empleados con políticas para controlar gasto y uso. | "Escenario 1: Invitar y asignar límites Dado un plan corporativo, Cuando invito usuarios y defino reglas, Entonces solo pueden reservar dentro de esas políticas. Escenario 2: Reportes de uso Dado reservas realizadas, Cuando abro Analítica corporativa, Entonces veo gasto por usuario y centro."  | EP-02 |
| US-51 | Facturación con RUC/razón social | Como usuario, quiero facturación con RUC/razón social para cumplir obligaciones tributarias. | "Escenario 1: Emitir comprobante Dado el checkout, Cuando ingreso RUC/razón social, Entonces se emite comprobante electrónico. Escenario 2: Historial de comprobantes Dado mi perfil, Cuando abro Pagos, Entonces puedo descargar el PDF (y XML si aplica)."  | EP-02 |
| US-52 | Reglas por tipo de sala | Como propietario, quiero configurar reglas específicas por tipo de sala para alinear expectativas. | "Escenario 1: Reglas por sala Dado la edición de sala, Cuando defino reglas específicas, Entonces aparecen en la ficha. Escenario 2: Aceptación Dado el checkout, Cuando confirmo, Entonces debo aceptar esas reglas para continuar."  | EP-02 |
| US-53 | Precios dinámicos | Como propietario, quiero activar precios dinámicos según demanda para mejorar la ocupación e ingresos. | "Escenario 1: Configurar dinámica Dado precios dinámicos activados, Cuando defino límites y horarios, Entonces las nuevas reservas usan la tarifa calculada. Escenario 2: Simulador Dado el panel de precios, Cuando pruebo un escenario, Entonces veo el impacto proyectado antes de aplicar."  | EP-02 |
| US-54 | Moderación de contenido | Como operaciones, quiero moderar fotos y descripciones antes de publicar para evitar contenido inapropiado. | "Escenario 1: Moderar contenido Dado una publicación nueva o editada, Cuando entra a revisión, Entonces un moderador puede aprobar/rechazar con comentarios. Escenario 2: Auditoría Dado acciones de moderación, Cuando consulto el registro, Entonces veo quién, cuándo y qué cambio hizo."  | EP-02 |
| US-55 | Aprobación de publicaciones | Como operaciones, quiero aprobar o pausar listados que no cumplan políticas para mantener la calidad del catálogo. | "Escenario 1: Pausar/activar listado Dado el panel de administración, Cuando pauso una publicación, Entonces deja de mostrarse en la búsqueda. Escenario 2: Notificar propietario Dado una acción de pausa/rechazo, Cuando la ejecuto, Entonces el propietario recibe notificación con motivos."  | EP-02 |
| US-56 | Analítica para propietarios | Como propietario, quiero ver analítica de ocupación, ingresos y reseñas para optimizar mi oferta. | "Escenario 1: KPIs visibles Dado mi panel, Cuando abro Analítica, Entonces veo ocupación, revenue, rating y tendencias por periodo. Escenario 2: Exportar datos Dado la vista de analítica, Cuando exporto, Entonces descargo un CSV del periodo seleccionado."  | EP-02 |
| US-57 | Check‑in con QR y No‑Show | Como propietario, quiero validar check-in con QR y registrar no-shows para aplicar políticas de cancelación. | "Escenario 1: Check‑in con QR Dado una reserva activa, Cuando escaneo el QR del local, Entonces la reserva cambia a estado 'En curso'. Escenario 2: No‑show Dado que no se registró check‑in, Cuando vence el tiempo de tolerancia, Entonces se marca no‑show y se aplica la política."  | EP-02 |
| US-58 |  PWA y notificaciones push  | Como usuario, quiero instalar la app como PWA y recibir notificaciones push para enterarme de cambios o mensajes. | "Escenario 1: Instalar PWA Dado que uso la web en móvil, Cuando acepto instalar, Entonces la app PWA queda disponible en el dispositivo. Escenario 2: Push de eventos Dado que tengo permisos, Cuando hay un nuevo mensaje o cambio de reserva, Entonces recibo una notificación push."  | EP-03 |
| US-59 | Accesibilidad (WCAG 2.1 AA) | Como usuario, quiero que la plataforma cumpla accesibilidad WCAG 2.1 AA para poder usarla con lector de pantalla y teclado | "Escenario 1: Accesibilidad de navegación Dado la UI, Cuando navego solo con teclado/lector de pantalla, Entonces puedo alcanzar y operar todos los controles (ARIA correcta). Escenario 2: Contraste y tamaño Dado los estilos, Cuando corro validaciones, Entonces el contraste cumple ≥4.5:1 y el texto es escalable (WCAG 2.1 AA)."  | EP-04 |
| US-60 | Desempeño de búsqueda  | Como usuario, quiero que la búsqueda cargue rápido aun con filtros para no perder tiempo. | "Escenario 1: Tiempos de respuesta Dado una búsqueda típica, Cuando cargo resultados iniciales, Entonces el p95 es \<2s en red 4G estándar. Escenario 2: Interacciones de filtros Dado filtros activos, Cuando agrego/quito un filtro, Entonces la actualización p95 es \<1s mediante carga incremental/caché."  | EP-04 |

### Epics

| Epic ID | Título | Descripción |
| :---- | :---- | :---- |
| EP-01 | Desarrollo del Landing Page | Diseñar, implementar y optimizar la página pública que comunica la propuesta de valor, capta leads y redirige a la app. Incluye navegación clara, contenido (Acerca de, Servicios, Testimonios), descarga de folleto PDF, SEO y respuesta móvil. |
| EP-02 | Desarrollo del Backend | Implementar la lógica de negocio y servicios: catálogo y perfiles de espacios, disponibilidad, motor de reservas, pagos/reembolsos, reseñas, mensajería, verificación de usuarios, pricing/tarifas, facturación, analítica, moderación y APIs para integraciones (pasarela, iCal). |
| EP-03 | Desarrollo del Frontend | Construir la app web (SPA/PWA) para usuarios y propietarios: búsqueda con mapa y filtros, fichas completas, calendario, comparador/precios, checkout rápido, panel de propietario y experiencia responsive, accesible e internacionalizada. |
| EP-04 | Experiencia del desarrollo | Definir prácticas y herramientas para entregar con calidad: arquitectura, CI/CD, pruebas unitarias/integración/E2E, observabilidad, performance, accesibilidad, guías de diseño/UX, documentación, DoR/DoD y gestión del backlog. |
| EP-05 | Seguridad de la aplicación | Garantizar confidencialidad, integridad y disponibilidad: autenticación y autorización, verificación de identidad (KYC/KYB), cifrado de datos, cumplimiento PCI-DSS/privacidad, gestión de secretos, prevención de fraude/no-show y auditoría. |

## 3.2. Impact Mapping

![ImpactMap](Imagenes/Impac1.png)
![ImpactMap](Imagenes/Impac2.png)


## 3.3. Product Backlog

| ID  | Historia de Usuario                                                                                                                                | Prioridad |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| 1   | Como freelancer, quiero encontrar la ubicacion de los inmuebles por localizacion para encontrar los lugares mas cercanos o convenientes            | Alta      |
| 2   | Como freelancer, quiero saber la disponibilidad actual del inmueble para hacer una eleccion correcta del tiempo que necesito el local              | Alta      |
| 8   | Como freelancer, quiero tener la posibilidad de tener una devolucion de mi dinero si cancelo una reserva realizada antes del inicio de esta misma. | Media     |
| 7   | Como freelancer quiero tener la certeza de que la aplicacion web tenga un sistema de pago seguro                                                   | Alta      |
