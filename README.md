<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC">


# Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2024-01

<hr>

# <center>Desarrollo de Aplicaciones Open Source</center>

## TB1 REPORT

**Sección:** WX54

**Profesor**: Alberto Wilmer Sanchez Seña

**StartUp Name**: DeMentes

**Producto**: PetCare

### Team Members:

| Member                            |    Code    |
| :-------------------------------- | :--------: |
| Garcia Moscoso, Andrea Joselyn    | u201921060 |
| Solis Solis, Leonardo Jose        | u20211G163 |
| Mejia Aliaga, Katherine Maryory   | u20221a118 |
| Conde Isla, Camila Alessandra     | u202114309 |
| Pasquale Barrenechea, Gianluca Santino     | u202112078 |

<br>
<br></br>

# Registro de Versiones del Informe

| Versión |  Fecha    |                                                                                       Autor                                                                                        | Descripción de modificación                                                                                                                                           |
| :-----: | :--------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   TB1   | 06/09/2023 | Garcia Moscoso, Andrea Joselyn <br><br> Solis Solis, Leonardo Jose <br><br> Mejia Aliaga, Katherine Maryory  <br><br> Conde Isla, Camila Alessandra <br><br> Pasquale Barrenechea, Gianluca Santino | Se realizaron los Capítulos I: Introducción, Capítulo II: Requirements Elicitation & Analysis, Capítulo III: Requirements Specification y Capítulo IV: Product Design |

<br></br>

# Contenido

## Tabla de Contenidos

### [Registro de versiones del informe](#registro-de-versiones-del-informe)

### [Project Report Collaboration Insights](#project-report-collaboration-insights)

### [Contenido](#contenido)

### [Student Outcome](#student-outcome-1)

### [Capítulo I: Introducción](#capítulo-i-introducción)

- [Universidad Peruana de Ciencias Aplicadas](#universidad-peruana-de-ciencias-aplicadas)
- [Desarrollo de Aplicaciones Open Source](#desarrollo-de-aplicaciones-open-source)
  - [TB1 REPORT](#tb1-report)
    - [Team Members:](#team-members)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Contenido](#contenido)
  - [Tabla de Contenidos](#tabla-de-contenidos)
    - [Registro de versiones del informe](#registro-de-versiones-del-informe-1)
    - [Project Report Collaboration Insights](#project-report-collaboration-insights)
    - [Contenido](#contenido-1)
    - [Student Outcome](#student-outcome)
    - [Capítulo I: Introducción](#capítulo-i-introducción)
    - [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
    - [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
    - [Conclusiones](#conclusiones)
    - [Bibliografía](#bibliografía)
    - [Anexos](#anexos)
- [Capítulo I: Introducción](#capítulo-i-introducción-1)
  - [1.1. StartUp Profile](#11-startup-profile)
    - [1.1.1. Description de la StartUp](#111-description-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos Objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

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

### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)

- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Product Design](#capítulo-iv-product-design)

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

### [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)

- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)

    - [5.2.1. Sprint 1](#521-sprint-1)
        - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
        - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
        - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
        - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
        - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
        - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
        - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
        - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
### [Conclusiones](#conclusiones)

### [Bibliografía](#bibliografía)

### [Anexos](#anexos)

<br></br>

# Capítulo I: Introducción

## 1.1. StartUp Profile

### 1.1.1. Description de la StartUp

Petcare, es una aplicación móvil que contará con su landing page, donde permitirá a los usuarios agendar citas médicas de baño o de algún otro servicio que ofrecen las veterinarias registradas. Nuestro primer segmento objetivo son los dueños de las mascotas que deseen buscar una facilidad y eficiencia al requerir servicios médicos veterinarios, el segundo son los centros veterinarios que busquen ampliar su negocio. El modelo de negocio que seguiremos será el de suscripción.


### 1.1.2. Perfiles de integrantes del equipo

<table align="center"  border="1" width="70%" style="text-align:center;">
    <tr align="center">
        <td rowspan="3">
            <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1156251884647092394/WIN_20230926_09_34_37_Pro.jpg" alt="Garcia Moscoso, Andrea Joselyn" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
             Andrea Joselyn Garcia Moscoso 
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Descripcion aqui
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148059889537662976/pic_1.jpg" alt="Solis Leonardo" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
             Leonardo Jose Solis Solis
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        descripcion aqui
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148303043629162647/054020181E187.jpg" alt="Mejia Aliaga, Katherine Maryory" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Katherine Maryory Mejia Aliaga
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        descripcion
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148370399395074108/Diseno_sin_titulo.png" alt="Camila Conde"  style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Camila Alessandra Conde Isla
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        descrinpcio
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148239074021351464/intranet_2020.jpg" alt="Gianluca Pasquale"  style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Gianluca Santino Pasquale Barrenechea
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        descrinpcio
        </td>
    </tr>
</table>

<br></br>

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

- **What?** <br><br>

  Petcare es una aplicación web que ofrece la posibilidad de agendar citas médicas para servicios como baños y otros servicios veterinarios ofrecidos por las clínicas registradas. Además, cuenta con una landing page para promover sus servicios.<br><br>

- **When?** <br><br>

  La aplicación estará disponible para su uso en cualquier momento una vez lanzada al mercado. Las citas pueden ser programadas según la disponibilidad de las veterinarias registradas. <br><br>

- **Where?** <br><br>

  La aplicación estará disponible en dispositivos web, accesible desde cualquier lugar donde los usuarios tengan conexión a internet. Inicialmente, se centrará en un mercado local o regional específico donde se encuentren las veterinarias registradas. <br><br>

- **Why?** <br><br>

  El propósito de Petcare es ofrecer una solución conveniente y eficiente para los dueños de mascotas que necesitan acceder a servicios médicos veterinarios. Además, busca ayudar a las clínicas veterinarias a expandir su alcance y servicios, optimizando sus operaciones.<br><br>

- **How?** <br><br>

  La aplicación funcionará mediante un modelo de suscripción, donde los usuarios podrán acceder a funciones básicas de búsqueda y reserva de citas de forma gratuita, mientras que se ofrecerán funciones premium con características adicionales a través de una suscripción o pagos por servicio. <br><br>

- **How much?** <br><br>

  El costo de la aplicación para los usuarios finales y el precio de las características premium dependerá del tipo de suscripción o los pagos por servicio que elijan los usuarios. El costo para las clínicas veterinarias registradas puede variar según el acuerdo de asociación o afiliación con Petcare.<br><br>

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

- Domain: En el mercado de servicios veterinarios, los dueños de mascotas experimentan dificultades para encontrar y reservar citas médicas de manera rápida y conveniente.
- Customer Segments: Dueños de mascotas de todas las edades y niveles socioeconómicos.
- Pain Points: La dificultad para encontrar citas médicas disponibles, largos tiempos de espera en las clínicas veterinarias, falta de información sobre servicios y precios, y la necesidad de adaptarse a horarios ocupados.
- Gap: Existe una brecha entre la demanda de servicios veterinarios y la disponibilidad de recursos para satisfacer esta demanda de manera eficiente.
- Visión/Strategy: Facilitar la búsqueda y reserva de servicios veterinarios a través de una plataforma digital, ofreciendo conveniencia y eficiencia a los usuarios.
- Initial Segment: Dueños de mascotas urbanos que valoran la comodidad y la rapidez en la gestión de los cuidados de sus animales.

#### 1.2.2.2. Lean UX Assumptions

- Assumption 1:
Creemos que los dueños de mascotas prefieren la conveniencia de reservar citas médicas veterinarias a través de una aplicación móvil en lugar de hacerlo por teléfono o en persona.
- Assumption 2:
Suponemos que las clínicas veterinarias estarán dispuestas a registrarse en nuestra plataforma para ampliar su clientela y mejorar la gestión de sus citas y servicios.
- Assumption 3:
Creemos que los usuarios estarán dispuestos a pagar por características premium que agreguen valor y conveniencia a su experiencia de reserva de servicios veterinarios.


#### 1.2.2.3. Lean UX Hypothesis Statements

- Hypothesis Statement 1:
Si proporcionamos a los usuarios una aplicación móvil fácil de usar para buscar y reservar citas veterinarias, entonces aumentará la frecuencia de uso y la satisfacción del usuario.
- Hypothesis Statement 2:
Si logramos asociarnos con un número significativo de clínicas veterinarias locales, entonces aumentará la variedad de opciones de servicios disponibles para los usuarios, lo que a su vez aumentará la retención de usuarios y la fidelidad a la plataforma.
- Hypothesis Statement 3:
Sí ofrecemos características premium que mejoren la experiencia del usuario, como recordatorios de citas, seguimiento de historiales médicos y atención al cliente prioritaria, entonces los usuarios estarán dispuestos a pagar por estas funciones adicionales, lo que generará ingresos recurrentes para la empresa.

#### 1.2.2.4. Lean UX Canvas

- Problem:
Los dueños de mascotas experimentan dificultades para encontrar y reservar citas médicas veterinarias de manera rápida y conveniente.
- Solution:
Desarrollar una aplicación web que permita a los usuarios buscar y reservar citas veterinarias de forma fácil y eficiente.
- Key Metrics:
    - Número de usuarios activos mensuales.
    - Tasa de conversión de búsqueda a reserva de citas.
    - Retención de usuarios después de la primera reserva.
    - Nivel de satisfacción del usuario.
- Unique Value Proposition:
Una plataforma todo en uno para encontrar y reservar citas veterinarias con facilidad y conveniencia, mejorando la experiencia tanto para los dueños de mascotas como para las clínicas veterinarias.
- Unfair Advantage:
    - Conexiones previas con clínicas veterinarias locales.
    - Experiencia previa en desarrollo de aplicaciones móviles y plataformas de reserva.
- Channels:
    - Publicidad en redes sociales dirigida a dueños de mascotas.
    - Asociaciones con clínicas veterinarias para promover la plataforma entre sus clientes.
    - Presencia en ferias y eventos relacionados con mascotas.
- Customer Segments:
    - Dueños de mascotas urbanos con horarios ocupados.
    - Clínicas veterinarias independientes que buscan expandir su clientela.
- Early Adopters:
    - Dueños de mascotas que ya utilizan servicios de reserva en línea para otros fines (como reservar citas médicas para ellos mismos).
- Cost Structure:
    - Desarrollo y mantenimiento de la aplicación móvil.
    - Marketing y publicidad.
    - Soporte al cliente.
    - Posibles costos de asociación con clínicas veterinarias.
-Revenue Streams:
    - Ingresos por características premium en la aplicación.
    - Posibles comisiones por cada reserva realizada a través de la plataforma.
    - Acuerdos de suscripción con clínicas veterinarias para promover sus servicios destacados.


## 1.3. Segmentos Objetivo

- Segmento Objetivo 1: Dueños de Mascotas Urbanos
    - Características Demográficas: Dueños de mascotas que viven en áreas urbanas.
    - Información Estadística: Este segmento puede incluir individuos de diferentes edades y niveles socioeconómicos, pero comparten la característica de vivir en entornos urbanos donde la oferta de servicios veterinarios puede ser amplia pero también competitiva. 
    - Este segmento busca conveniencia y eficiencia en la búsqueda y reserva de servicios veterinarios para sus mascotas debido a sus horarios ocupados y la necesidad de adaptarse a un estilo de vida urbano acelerado.

- Segmento Objetivo 2: Clínicas Veterinarias Independientes
    - Características Demográficas: Propietarios o administradores de clínicas veterinarias independientes.
    - Información Estadística: Este segmento está formado por veterinarios emprendedores o pequeñas clínicas que buscan ampliar su clientela y mejorar su eficiencia operativa. Pueden estar ubicados tanto en áreas urbanas como suburbanas. Estos negocios pueden beneficiarse de la asociación con una plataforma como 
  Petcare para aumentar su visibilidad, atraer nuevos clientes y optimizar la gestión de citas y servicios.                       |

<br><br>

