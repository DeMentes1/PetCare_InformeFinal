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
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis-1)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [Capítulo IV: Product Design](#capítulo-iv-product-design-1)
  - [4.1. Style Guidelines.](#41-style-guidelines)
    - [4.1.1. General Style Guidelines.](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture.](#42-information-architecture)
    - [4.2.1. Organization Systems.](#421-organization-systems)
    - [4.2.2. Labeling Systems.](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems.](#424-searching-systems)
    - [4.2.5. Navigation Systems.](#425-navigation-systems)
  - [4.3. Landing Page UI Design.](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe.](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up.](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design.](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes.](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams.](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups.](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams.](#444-web-applications-user-flow-diagrams)
    - [4.5. Web Applications Prototyping.](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture.](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram.](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams.](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams.](#463-software-architecture-components-diagrams)
    - [4.7.2. Class Dictionary.](#472-class-dictionary)
  - [4.8. Database Design.](#48-database-design)
    - [4.8.1. Database Diagram.](#481-database-diagram)

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
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis-1)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [Capítulo IV: Product Design](#capítulo-iv-product-design-1)
  - [4.1. Style Guidelines.](#41-style-guidelines)
    - [4.1.1. General Style Guidelines.](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture.](#42-information-architecture)
    - [4.2.1. Organization Systems.](#421-organization-systems)
    - [4.2.2. Labeling Systems.](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems.](#424-searching-systems)
    - [4.2.5. Navigation Systems.](#425-navigation-systems)
  - [4.3. Landing Page UI Design.](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe.](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up.](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design.](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes.](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams.](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups.](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams.](#444-web-applications-user-flow-diagrams)
    - [4.5. Web Applications Prototyping.](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture.](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram.](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams.](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams.](#463-software-architecture-components-diagrams)
    - [4.7.2. Class Dictionary.](#472-class-dictionary)
  - [4.8. Database Design.](#48-database-design)
    - [4.8.1. Database Diagram.](#481-database-diagram)

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

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores


### 2.1.1. Análisis competitivo

<table>
<tbody><tr><th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th></tr><tr><td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td><td colspan="5">Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</td></tr><tr><td colspan="5">Comprender mejor el panorama competitivo en el mercado de servicios veterinarios en Lima, Perú, identificando fortalezas, debilidades, oportunidades y amenazas de mi startup y sus competidores.</td></tr><tr><td colspan="3">Nuestro Producto / Competidores</td><td colspan="1" valign="top" style="font-weight: bold;">PetCare<br><img src="" alt="PetCare" width="70px"></td><td colspan="1" valign="top" style="font-weight: bold;">PetShop<br><img src="" alt="PetShop" width="60px"></td><td colspan="1" valign="top" style="font-weight: bold;">Digivet<br><img src="" alt="Digivet" width="60px"></td><td colspan="1" valign="top" style="font-weight: bold;">Petly<br><img src="" alt="Petly" width="60px"></td></tr><tr><td colspan="1" rowspan="2">Perfil</td><td colspan="2">Overview</td><td colspan="1" valign="top">Aplicación móvil para reservar citas veterinarias con facilidad.Ventaja Competitiva: Conveniencia y eficiencia en la gestión de servicios veterinarios.</td><td colspan="1" valign="top">Ofrece servicios de consulta veterinaria en línea a través de su sitio web.</td><td colspan="1" valign="top">Plataforma que ofrece consultas veterinarias en línea mediante su aplicación móvil y sitio web.</td><td colspan="1" valign="top">Ofrece servicios de teleconsultas veterinarias a través de su plataforma en línea.</td></tr><tr><td colspan="2">Ventaja competitiva</td><td colspan="1" valign="top">Conveniencia y eficiencia en la gestión de servicios veterinarios.</td><td colspan="1" valign="top">Una gran cantidad de productos, packs, soluciones y demás para la hidroponia. Tiene una sólida interfaz donde explican los servicios que ofrece la empresa y los beneficios de realizar hidroponia.</td><td colspan="1" valign="top">Amplia variedad de productos para mascotas además de servicios de consulta veterinaria.</td><td colspan="1" valign="top">Enfoque en tecnología para brindar un servicio de consulta veterinaria eficiente y de calidad.</td></tr><tr><td colspan="1" rowspan="2">Perfil de Marketing</td><td colspan="2">Mercado objetivo</td><td colspan="1" valign="top">Dueños de mascotas urbanos en Lima.</td><td colspan="1" valign="top">Dueños de mascotas urbanos en Lima.</td><td colspan="1" valign="top">Dueños de mascotas urbanos en Lima.</td><td colspan="1" valign="top">Dueños de mascotas urbanos en Lima.</td></tr><tr><td colspan="2">Estrategias de marketing</td><td colspan="1" valign="top">Promoción en redes sociales, marketing de contenido.</td><td colspan="1" valign="top">Promoción en redes sociales, marketing de contenido.</td><td colspan="1" valign="top">Publicidad en redes sociales, promociones en línea.</td><td colspan="1" valign="top">Publicidad en redes sociales, colaboraciones con influenciadores.</td></tr><tr><td colspan="1" rowspan="3">Perfil de Producto</td><td colspan="2">Productos &amp; Servicios</td><td colspan="1" valign="top">Reserva de citas veterinarias, características premium.</td><td colspan="1" valign="top">Consultas veterinarias en línea, productos para mascotas.</td><td colspan="1" valign="top">Consultas veterinarias en línea.</td><td colspan="1" valign="top">Teleconsultas veterinarias.</td></tr><tr><td colspan="2">Precios &amp; Costos</td><td colspan="1" valign="top">Modelo freemium, ingresos por características premium.</td><td colspan="1" valign="top">Tarifas por consulta.</td><td colspan="1" valign="top">Tarifas por consulta.</td><td colspan="1" valign="top">Tarifas por consulta.</td></tr><tr><td colspan="2">Canales de distribución (Web y/o Móvil)</td><td colspan="1" valign="top">Aplicación web. </td><td colspan="1" valign="top">Sitio web.</td><td colspan="1" valign="top">Aplicación móvil, sitio web.</td><td colspan="1" valign="top">Sitio web.</td><tr></tr><td colspan="1" rowspan="5">Análisis SWOT</td></td></tr><tr><td colspan="2">Fortalezas</td><td colspan="1" valign="top">Plataforma digital conveniente y fácil de usar.</td><td colspan="1" valign="top">Amplia gama de productos y servicios.</td><td colspan="1" valign="top">Enfoque en tecnología y experiencia en consultas veterinarias en línea.</td><td colspan="1" valign="top">Enfoque especializado en teleconsultas veterinarias</td></tr><tr><td colspan="2">Debilidades</td><td colspan="1" valign="top">Dependencia de la adopción por parte de las clínicas veterinarias</td><td colspan="1" valign="top">Poca especialización en servicios veterinarios.</td><td colspan="1" valign="top">Competencia de otras plataformas similares.</td><td colspan="1" valign="top">Posible limitación en la oferta de servicios adicionales.
</td></tr><tr><td colspan="2">Oportunidades</td><td colspan="1" valign="top">Aumento de la conciencia sobre el cuidado de mascotas en Lima.</td><td colspan="1" valign="top">Expansión de servicios veterinarios.</td><td colspan="1" valign="top">Crecimiento del mercado de consultas veterinarias en línea.</td><td colspan="1" valign="top">Aumento de la demanda de servicios de telemedicina veterinaria</td></tr><tr><td colspan="2">Amenazas</td><td colspan="1" valign="top">Competencia de otras aplicaciones similares y la resistencia al cambio en el sector.</td><td colspan="1" valign="top">Competencia de servicios veterinarios especializados.</td><td colspan="1" valign="top">Cambios en la regulación o competencia de servicios tradicionales.</td><td colspan="1" valign="top">Competencia de otras plataformas similares y servicios tradicionales.</td></tr></tbody></table>
<br></br>

### 2.1.2. Estrategias y tácticas frente a competidores

1. Estrategias frente a Competidores:
  - Desarrollar una ventaja competitiva clara destacando la conveniencia y eficiencia de la plataforma de reservas de citas veterinarias.
  - Diferenciarse mediante la oferta de características únicas y valor agregado, como recordatorios de citas, seguimiento de historiales médicos y atención al cliente personalizada.
2. Tácticas frente a Competidores:
  - Mejorar continuamente la experiencia del usuario en la aplicación móvil, centrándose en la usabilidad y la interfaz intuitiva.
  - Ofrecer promociones y descuentos para atraer nuevos usuarios y fomentar la fidelidad de los clientes existentes.
  - Colaborar con clínicas veterinarias locales para ampliar la red de servicios disponibles y aumentar la confianza de los usuarios en la plataforma.
  - Monitorear activamente las estrategias de marketing y promoción de los competidores para identificar oportunidades de mejora y diferenciación.
  - Mantenerse actualizado con las tendencias del mercado y las preferencias de los usuarios para adaptar las estrategias y tácticas según sea necesario.


## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Preguntas para segmentos objetivos de cliente**

- ¿Cómo se llama? 
- ¿Cuántas mascotas tiene? 
- ¿Realiza constantes chequeos, baños o tratamientos a su mascota?
- ¿Con qué frecuencia lleva a su mascota a una veterinaria?
- ¿Tiene alguna veterinaria preferida o que tenga su total confianza?
- ¿Cuánto tiempo se tardó en encontrar una veterinaria que se acomode a - su presupuesto y que tenga su confianza?
- ¿Qué tipo de servicios busca en una veterinaria?
- ¿Qué es lo que le transmite confianza de algún servicio veterinario?
- ¿Tienes alguna mala experiencia en alguna veterinaria?
- ¿Qué tipo de monitoreo de tratamiento valora más? (Citas por llamadas, - preguntas por mensaje, terapias en casa o en la veterinaria, - internamiento)
- ¿Qué tan difícil es conseguir los productos para el cuidado de la - mascota?
- ¿Cuánto tarda en agendar una cita para su mascota?
- ¿Consideraría que se debe automatizar algún proceso de registro - médico? (Historial, resultados de análisis, recetas, historial de - citas o baños, etc)
- ¿ Qué tipo de información sobre las veterinarias le gustaría recibir? - (Campañas, costos, tips, talleres, nuevos servicios o productos)
- ¿De qué manera lleva el control de prevención de su mascota? ¿Qué - funcionalidad en una aplicación web podría ayudarle?
- ¿Que opina de usar una aplicación web para mejorar su experiencia con - los servicios que le puede brindar su veterinaria de confianza?


**Preguntas para segmentos objetivos de clínicas veterinarias independientes**

- ¿Qué servicios ofrecen actualmente en su clínica veterinaria?
- ¿Qué estrategias de marketing utilizan actualmente para promocionar su - clínica?
- ¿Cómo gestionan actualmente el seguimiento y recordatorio de citas - para sus clientes?
- ¿Cuáles son los principales desafíos que enfrenta en la gestión de - citas y servicios en su clínica?
- ¿Qué aspectos considera más importantes al elegir una plataforma - digital para su clínica?
- ¿Cuál es su principal objetivo al asociarse con plataformas digitales - como Petcare?
- ¿Cómo cree que una plataforma como Petcare puede ayudar a mejorar la - eficiencia operativa de su clínica?
- ¿Qué canales de comunicación prefieren sus clientes para programar - citas o hacer consultas?
- ¿Cómo evaluaría el nivel de satisfacción de sus clientes con los - servicios ofrecidos en su clínica?
- ¿Qué piensan sobre la posibilidad de recibir comentarios y reseñas de - sus clientes a través de una plataforma digital?
- ¿Cómo manejan actualmente la comunicación con los clientes, como - recordatorios de citas o seguimiento posterior a la consulta?
<br></br>

## 2.3. Needfinding

### 2.3.1. User Personas

**User Persona del segmento: Personas que deseen iniciar en la hidroponía**

<div align="center">

  <img src="https://imgur.com/yZPAqBA.png">

</div>

**User Persona del segmento: Expertos que desean brindar sus conocimientos a los principiantes**

<div align="center">

  <img src="https://imgur.com/8huJaCb.png">

</div>
<br>

### 2.3.2. User Task Matrix

Las tareas más importantes para el segmento objetivo de las veterinarias que se identificaron son “Llevar un registro de historial y de pacientes”, en este apartado de la aplicación web se registran las visitas de los clientes además de subir su historial veterinario; “Dar una buena atención” se refiere a un buen trato tanto a la persona como a la mascota y “Mantener la correcta limpieza y orden” nos parece una de las más importantes ya que al tener visitas de varios animales en un mismo día, podría haber la ocasión de presencia de insectos o parásitos por lo que una buena limpieza es clave.

**Segmento Objetivo:** Dueño de veterinaria

|                   Tarea                    |  Frecuencia  | Severidad |
| :----------------------------------------: | :----------: | :-------: |
|       Analizar la competencia.             | A menudo |   Alta    |
|          Tener apoyo de varios veterinarios calificados        | A menudo |   Alta   |
|      Promocionar las campañas o servicios que brindan       |   Ocasionalmente    |   Intermedia    |
|       Llevar un correcto control de historial y registro de los pacientes       |   Siempre    |   Alta   |
|       Conseguir los productos necesarios.       |   A menudo    |   Alta    |
|       Dar una buena atención al dueño como a su mascota.        |   Siempre    |   Alta   |
|      Llevar el control de cada solicitud de baño para cada mascota.       | A menudo |   Alta    |
| Mantener la correcta limpieza y orden.  |   Siempre    |   Alta   |

**Segmento Objetivo:** Clientes

|                     Tarea                     |  Frecuencia  | Severidad |
| :-------------------------------------------: | :----------: | :-------: |
| Buscar una veterinaria licenciada, de confianza y con buena atención.| Siempre |   Alta    |
|      Llevar el control de prevención de sus mascotas.      |   A menudo    |   Alta   |
|        Buscar comidas o productos adecuados para su mascota.|   A menudo    |   Alta    |
|    Lleva a su mascota a sus baños y chequeos correspondientes.    |   A menudo    |   Altas   |
| Comenta con otros amantes de animales sobre servicios o campañas que ayudan a las mascotas. |   Ocasionalmente    |   Intermedia    |
|         Está atento a descuentos en productos para su mascota que pueda necesitar.          |   A menudo   |   Intermedia    |

### 2.3.3. User Journey Mapping

<div align="center">

  <img src="https://imgur.com/LAVwbOI.png">

</div>

<div align="center">

  <img src="https://imgur.com/UfvflP0.png">

</div>


### 2.3.4. Empathy Mapping

**Empathy Map del segmento: Veterinarias**

<div align="center">

  <img src="https://imgur.com/hMjmPeN.png">

</div>

**Empathy Map del segmento: Dueños de mascotas**

<div align="center">

  <img src="https://imgur.com/k7jS4pm.png">

</div>

### 2.3.5. As-is Scenario Mapping

**As-is Scenario Map del segmento: Veterinarias**

<div align="center">

  <img src="https://imgur.com/Gjcm6Vo.png">

</div>

**As-is Scenario Map del segmento: Dueños de mascotas**

<div align="center">

  <img src="https://imgur.com/ETAX9M3.png">

</div>

<br></br>

# Capítulo III: Requirements Specification 

## 3.1. To-Be Scenario Mapping

- To-Be Scenario Mapping para Clínicas Veterinarias Independientes
  
<div align="center">

  <img src="https://imgur.com/ElgRVBY.png">

</div>    
    

- To-Be Scenario Mapping para Dueños de Mascotas Urbanas
<div align="center">

  <img src="https://imgur.com/uSgxGrU.png">

</div>   

## 3.2. User Stories

| Epic / Story ID | Título | Descripción |Criterios de Aceptación |Relacionado con (Epic ID)|
|:---------|:---------|:--------|:--------|:------|
|**US01**|Registro de Usuario |Como usuario deseo poder saber cuales son los artículos actuales con una mejor puntuación y de igual manera con los cursos que ofrecen.Como visitante dueño de mascota, deseo registrarme en la aplicación para acceder a todas sus funcionalidades|- Al acceder a la aplicación como usuario nuevo, debería ver la opción de registro.<br> - Al completar el formulario de registro con información válida, debo recibir un correo de confirmación.|01|
|**US02**|Iniciar sesión |Como usuario registrado, deseo poder iniciar sesión en la aplicación para acceder a mi cuenta.|- Al acceder a la aplicación como usuario registrado, debería ver la opción de iniciar sesión.<br> - Al ingresar las credenciales correctas, debo ser redirigido a mi perfil.|02|
|**US03**|Agendar cita veterinaria |Como dueño de mascota, deseo poder agendar una cita veterinaria a través de la aplicación para garantizar la atención adecuada para mis mascotas.|- Al acceder a la aplicación, debería ver la opción de agendar cita veterinaria.<br>- Al seleccionar la fecha y hora deseada, debo recibir una confirmación de la cita programad|03|
|**US04**|Buscar clínicas veterinarias|Como usuario, deseo poder buscar clínicas veterinarias cercanas para encontrar la mejor opción para las necesidades de mis mascotas.	|- Al acceder a la aplicación, debería ver la opción de búsqueda de clínicas veterinarias.<br>- Al ingresar mi ubicación o preferencias, debo recibir una lista de clínicas cercanas con detalles relevantes.|04|
|**US05**|Visualizar perfiles de clínicas|Como usuario, deseo poder ver el perfil de las clínicas veterinarias para tomar una decisión informada sobre la atención de mis mascotas.|- Al seleccionar una clínica de la lista, debería ver su perfil con información detallada. <br>- Al visualizar el perfil de la clínica, debo poder acceder a información como servicios ofrecidos, horarios y ubicación.|05|
|**US06**|Pagos y facturación |Como usuario, deseo poder realizar pagos y recibir facturas de los servicios veterinarios utilizados a través de la aplicación para garantizar un proceso de pago transparente y conveniente.|- Al acceder a la aplicación, debería ver la opción de realizar pagos por servicios utilizados.<br>- Al completar el proceso de pago, debo recibir una factura detallada.|06|
|**US07**|Crear perfil de clínica veterinaria |Como propietario de una clínica veterinaria, deseo poder crear un perfil en la aplicación para aumentar la visibilidad de mi negocio y atraer a potenciales clientes.|- Al acceder a la aplicación como propietario de una clínica, debería ver la opción de crear un perfil. <br>- Al completar la información del perfil, debo recibir una confirmación de registro y ver mi perfil publicado.	|07|

### Technical User 

| Story ID  | Título | Descripción | 
|:---|:-----|:-----|
|TS01|POST User|Como desarrollador a cargo de la parte frontend, quiero registrar a un nuevo usuario para visualizar las afiliaciones e información básica.|
||GET User|Como desarrollador a cargo de la parte frontend, quiero utilizar una API que almacene los registros para utilizar los datos en personalización de cuenta.|
|TS02|POST Pet|Como desarrollador a cargo de la parte frontend, quiero registrar una mascota que herede las propiedades de User.|
||GET Pet|Como desarrollador a cargo de la parte frontend, quiero utilizar el registro de la mascota para cuando sea necesario.|
|TS03|POST Owner|Como desarrollador a cargo de la parte frontend, quiero que el dueño de la mascota herede las propiedades de User para identificar las personas de contacto de la mascota.|
||GET Owner|Como desarrollador a cargo de la parte frontend, quiero utilizar el registro del dueño para asociarlo con la información de la mascota.|
|TS04|POST Service|Como desarrollador a cargo de la parte frontend, quiero añadir nuevos servicios para mostrarlo como opciones a elegir.|
||GET Service by Vet ID|Como desarrollador a cargo de la parte frontend, quiero obtener los servicios que brinda cada veterinaria para mostrarlas en un filtrado.|
|TS05|POST Vet|Como desarrollador a cargo de la parte frontend, quiero registrar una nueva veterinaria para tener varias opciones a elegir en la aplicación.|
||GET Vet|Como desarrollador a cargo de la parte frontend, quiero obtener los datos de registro de una veterinaria para mostrarla entre las recomendaciones de la aplicación.|
|TS06|POST Appointment|Como desarrollador a cargo de la parte frontend, quiero registrar una nueva cita médica para programar un recordatorio.|
||GET Appointment by Pet Id|Como desarrollador a cargo de la parte frontend, quiero obtener las próximas citas que tenga la mascota para mostrarla en citas programadas.|
|TS07|POST Prevention|Como desarrollador a cargo de la parte frontend, quiero registrar una fecha de tratamiento para programar un recordatorio para un mes después.|
||GET Preventation by Vet ID|Como desarrollador a cargo de la parte frontend, quiero obtener las dosis dadas por cada mascota para visualizar un historial de estas.|
|TS08|POST Review|Como desarrollador a cargo de la parte frontend, quiero que se visualicen todas las reseñas para dar a conocer la experiencia de otras personas. |
||GET Review by Vet ID|Como desarrollador a cargo de la parte frontend, quiero obtener todas las reseñas de cada veterinaria según su ID para poder filtrar la información.|

## 3.3. Impact Mapping
#### Impact Mapping para Dueños de Mascotas 

<div align="center">

  <img src="https://imgur.com/jU6TGhx.png">

</div>   


#### Impact Mapping para Clínicas Veterinarias Independientes

<div align="center">

  <img src="https://imgur.com/MLU4CNK.png">

</div>   


## 3.4. Product Backlog
| #Orden | User Story ID | Título  |Descripción  |Story Points (1 / 2 / 3 / 5 /8)|
|:---------|:---------|:--------|:--------|:------|
|**1**|US01 |Registro de usuarios|Como usuario nuevo, deseo poder registrarme en la aplicación para acceder a todas sus funcionalidades.|3|
|**2**|US02 |Iniciar sesión|Como usuario registrado, deseo poder iniciar sesión en la aplicación para acceder a mi cuenta.|3|
|**3**|US03 |Agendar cita veterinaria|Como dueño de mascota, deseo poder agendar una cita veterinaria a través de la aplicación para garantizar la atención adecuada para mis mascotas.|5|
|**4**|US04 |Buscar clínicas veterinarias|Como usuario, deseo poder buscar clínicas veterinarias cercanas para encontrar la mejor opción para las necesidades de mis mascotas.|5|
|**5**|US05 |Visualizar perfiles de clínicas|Como usuario, deseo poder ver el perfil de las clínicas veterinarias para tomar una decisión informada sobre la atención de mis mascotas.|5|
|**6**|US06 |Pagos y facturación|Como usuario, deseo poder realizar pagos y recibir facturas de los servicios veterinarios utilizados a través de la aplicación para garantizar un proceso de pago transparente y conveniente.|8|
|**7**|US07 |Crear perfil de clínica veterinaria|Como propietario de una clínica veterinaria, deseo poder crear un perfil en la aplicación para aumentar la visibilidad de mi negocio y atraer a potenciales clientes.|8|
<br></br>

<br></br>

# Capítulo IV: Product Design

## 4.1. Style Guidelines.

### 4.1.1. General Style Guidelines.

Lo que buscamos como startup, es que la aplicación PetCare tenga una interfaz que refleje hacia los usuarios simplicidad a la vez que profesionalidad. Queremos que los dueños de mascotas perciban el poder gestionar atención veterinaria de manera rápida, eficaz y sin complicaciones.

**Brand Overview:**

Nuestro producto nace de la necesidad de los dueños de mascotas de encontrar una solución eficiente para la correcta gestión de la atención veterinaria de sus compañeros, ofreciendo un agendamiento de citas de forma fácil y confiable, respaldados siempre por expertos del cuidado animal.

**Brand Name:**

El nombre de nuestro producto es "PetCare", este mismo encapsula la dedicación al cuidado y bienestar de las mascotas. Buscamos reflejar la importancia de brindar atención y servicios veterinarios confiables.

**Colores Empleados**

| Color | Descripción |
| :---: |--------------------------------------------------------------------------------------------------------------------------- |
| Color Primario | Nuestro color primario es un verde azulado (Teal) el cual representa un sentimiento de tranquilidad y simbolizando confianza y profesionalismo. <br> <p style = 'text-align:center;'> <img src="https://imgur.com/AsvGHWx.png" alt="color1"> </p> |
| Color Secundario | El color secundario es un color gris (Gray), para un mejor contraste en los textos y fondos. <br> <p style = 'text-align:center;'> <img src="https://imgur.com/FO2ISDA.png" alt="color2"> </p> |
| Color Terciario | Nuestro color terciario vendría a ser un azul claro (Light Blue), para reflejar una sensación de limpieza y aseo. <p style = 'text-align:center;'> <img src="https://imgur.com/2bDWuHN.png" alt="color3"> </p> | 

**Tipografia**

| Tipografía | Fuente | Ejemplo |
| :---: | :---: | :---: |
| Tipografía principal | Fuente: Montserrat <br> Tamaño: 22 px - 48 px | <img src="https://imgur.com/YP7o5j6.png" alt="ejemploTipografia" style="margin-bottom: 5px;" width="250"/> | 

### 4.1.2. Web Style Guidelines

**Landing Page:** Para nuestra landing page, estamos empleando el patrón Z en la estructura. El uso de este patrón se debe a su diseño que guía al usuario a través de la página de una manera natural a la par que efectiva. En la parte superior se podrá ver una barra de navegación con tonos de verde azulado. Esta barra contendrá el logo y secciones tales como "Inicio", "Quienes somos", "Beneficios", "Suscripción" y "Contacto". En el resto del cuerpo, utilizamos tonos de color azul claro, representando un color asociado a las veterinarias, y tambien un color blanco con fines de sumar contraste a nuestros demas colores.

<br>

## 4.2. Information Architecture.

### 4.2.1. Organization Systems.

**Segmento Objetivo: Dueños de mascotas urbanas**
- Jerárquica:
Mediante la aplicación de filtros (calificación, tipo de servicio requerido, etc), las veterinarias podrán aparecer con el debido orden, es decir, se mostrarán los resultados con mayor coincidencia en primer lugar y asi sucesivamente. El usuario entonces podrá elegir el resultado que mas prefiera.
- Secuencial:
Cuando se requiera agendar un cita con un veterinario, se mostrará la guía paso a paso a completar, incluyendo aspectos como la fecha de reserva, el nombre del dueño, los motivos de la cita, que tipo de servicio requerirá y detalles adicionales a detallar por el dueño.

**Segmento Objetivo: Veterinarias independientes**
- Jerárquica:
Resaltar características como la gestión de citas, actualizar información clínica y el acceso a los registros médicos de la mascota en un dashboard.
- Secuencial:
Incluir una vista de gestión de citas, viendo las que están más cercanas, nuevas reservas y actualizar estatus de cita.

### 4.2.2. Labeling Systems.

Tenemos los siguientes encabezados:
- **Inicio**: En esta sección se muestra la sección inicial de la landing page, donde se recibe a los usuarios con una frase representando a nuestro proyecto.
- **Servicios**: En esta sección se muestran qué tipos de servicios normalmente ofrecen las veterinarias asociadas.
- **Veterinarias**: En esta sección se podrán ver todas las veterinarias cercanas a tu ubicación además de tener una opción de filtros para poder descartar.
- **Productos**: En esta sección podrás ver la lista de artículos que ofrecemos en asociación con las veterinarias, así como también una barra de búsqueda y la opción de filtros.
- **Citas**: En esta sección se mostrarán las citas que ya han sido reservadas, mostrando también que veterinaria es, el horario y quien atenderá la consulta.
- **Contactanos**: En esta sección, se mostrará un formulario donde podrán registrarse datos como tus nombres y la consulta/problema que quieras reportar hacia nosotros.


### 4.2.3. SEO Tags and Meta Tags

- **Title**: "Petcare - Donde cada huella deja una marca en nuestros corazones."
- **Meta Description**: "Reserve citas veterinarias y acceda a servicios de cuidado de mascotas con facilidad. Petcare brinda comodidad y tranquilidad a los dueños de mascotas y a los centros veterinarios independientes."
- **Keywords**: "Petcare, veterinary appointments, pet care services, pet health, animal clinic, pet grooming"
- **Author**: DeMentes Team

### 4.2.4. Searching Systems.

Un sistema de búsqueda efectivo es esencial para permitir a los usuarios encontrar información específica dentro de la aplicación web. La búsqueda debe ser rápida, precisa y capaz de manejar consultas complejas. Además, podría considerarse la implementación de filtros y opciones avanzadas de búsqueda para refinar los resultados.

- **Landing Page**: Los usuarios podrán hacer uso de la barra de navegación ubicada en la parte superior, para poder ubicarse en los distintos apartados en los que está dividido nuestra página, siendo una forma didáctica para interactuar con esta.
- **Aplicación Web**: Por parte de los principiantes, tendrán la opción de realizar búsquedas de información específica para ellos, por medio de aplicar los filtros necesarios. Los resultados serán mostrados de acuerdo a la coincidencia con la búsqueda establecida.

### 4.2.5. Navigation Systems.

Los sistemas de navegación son cómo los usuarios se desplazan por la aplicación web. Esto incluye menús, barras de navegación y enlaces contextuales. Una navegación clara y coherente es esencial para que los usuarios puedan moverse sin esfuerzo entre las diferentes secciones de la aplicación. La navegación debe ser intuitiva y brindar una experiencia fluida, permitiendo a los usuarios acceder rápidamente a la información que están buscando.
En nuestro Landing Page, encontramos la sección de la barra de navegación en la parte superior, la cual nos permite navegar directamente a un apartado dentro de la página. Esta barra de navegación será visible en todo momento, para que el usuario pueda dirigirse a otra sección que desee visualizar. De esta manera, generamos una navegación más fluida y dinámica para el usuario. En nuestra aplicación web, utilizaremos un proceso similar al descrito, con diversas opciones que variarán de acuerdo al segmento objetivo que esté utilizando el servicio. Estos podrán hacer uso de filtros para poder encontrar de mejor manera la información precisa que necesiten.

## 4.3. Landing Page UI Design.

### 4.3.1. Landing Page Wireframe.

Link al Figma: [Figma Wireframe](https://www.figma.com/file/KWmTfK9QsF0ukBsA6KQpPU/Wireframe-Kit-🚀-(Community)?type=design&node-id=202-1391&mode=design&t=x2ls8eSCSPFh3WUp-0)

<p style = 'text-align:center;'>
  <img src="https://imgur.com/r88faUj.png" width="1000">
</p>
<br>


<p style = 'text-align:center;'>
  <img src="https://imgur.com/FOMFwbO.png" width="1000">
</p>
<br>


<p style = 'text-align:center;'>
  <img src="https://imgur.com/jE46S2c.png" width="1000">
</p>
<br>


<p style = 'text-align:center;'>
  <img src="https://imgur.com/bzJWiAo.png" width="1000">
</p>
<br>


<p style = 'text-align:center;'>
  <img src="https://imgur.com/mbHqMg8.png" width="1000">
</p>
<br>

### 4.3.2. Landing Page Mock-up.

<p style = 'text-align:center;'>
  <img src="https://imgur.com/QPH2isg.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/VOneDut.png" width="1000">
</p>
<br>


<p style = 'text-align:center;'>
  <img src="https://imgur.com/wM8zfse.png" width="1000">
</p>
<br>


<p style = 'text-align:center;'>
  <img src="https://imgur.com/fuSe2qv.png" width="1000">
</p>
<br>


<p style = 'text-align:center;'>
  <img src="https://imgur.com/Mm7POwf.png" width="1000">
</p>
<br>
<br>
<br>

## 4.4. Web Applications UX/UI Design.

### 4.4.1. Web Applications Wireframes.

<p style = 'text-align:center;'>
  <img src="https://imgur.com/0S1lqzS.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/KLzJMp8.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/WvzgRKZ.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/Jg13iWg.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/IKYMdPp.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/e2Iak4w.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/wJ7mwi8.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/etOLR0t.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/9lFak7L.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/341Z8bM.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/8FvxOPf" width="1000">
</p>
<br>

### 4.4.2. Web Applications Wireflow Diagrams.

Enlace del diagrama: [Ver Web Applications Wireflow Diagrams en Figma](https://lucid.app/lucidchart/fc61b12e-193d-4f6d-b4b7-c8455e39480f/edit?invitationId=inv_fc0fd6b3-d2f3-4c97-be81-4f43a41d6a7b&page=0_0#)

**User goal:** Ingresar a la pantalla principal de la aplicación
<p style = 'text-align:center;'>
  <img src="https://imgur.com/p3IsXtu.png" width="1000">
</p>
<br>

**User goal:** Agendar una cita en la aplicación
<p style = 'text-align:center;'>
  <img src="https://imgur.com/Rxo84N3.png" width="1000">
</p>
<br>

**User goal:** Comprar una suscripción como usuario registrado
<p style = 'text-align:center;'>
  <img src="https://imgur.com/YkzQQRJ.png" width="1000">
</p>
<br>

### 4.4.3. Web Applications Mock-ups.

Los "Web Applications Mock-ups" son una etapa avanzada en el desarrollo de nuestra aplicación web. Durante esta fase, damos vida a la apariencia final de nuestra aplicación web, mostrando una vista más realista de cómo se verá y funcionará. 

<p style = 'text-align:center;'>
  <img src="https://imgur.com/XQWAq48.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/2vTwdVE.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/E6iAe1y.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/D6dJS2N.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/ksBjJUS.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/1PKUrEl.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://imgur.com/f2bD4OS.png" width="1000">
</p>
<br>

### 4.4.4. Web Applications User Flow Diagrams.

- **User Goal:** Ingresar a la pantalla principal de la aplicación

<p style = 'text-align:center;'>
  <img src="https://imgur.com/a3vXDdU.png">
</p>
<br>

- **User Goal:** Agendar una cita en la aplicación

<p style = 'text-align:center;'>
  <img src="https://imgur.com/lldNXTP.png">
</p>
<br>

- **User Goal:** Comprar una suscripción como usuario registrado

<p style = 'text-align:center;'>
  <img src="https://imgur.com/p7P8eSm.png">
</p>
<br>

Enlace al diagrama: [Ver Diagramas en Figma](https://lucid.app/lucidchart/7253a405-a874-42df-8fe9-a1c1c2c32d8d/edit?viewport_loc=-2625%2C5173%2C5514%2C2517%2C0_0&invitationId=inv_433b6fbd-5443-4ee4-addf-bca94865f412)

<br>

### 4.5. Web Applications Prototyping.

<p style = 'text-align:center;'>
  <img src="https://imgur.com/gnJPLRV.png" width="1000">
</p>
<br>


Enlace del Prototipo:[Ver Prototipo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a118_upc_edu_pe/EYvzbHQ0kv9Nr2tX87OsP5gBHQzpUnf0Qmvq3YEYvW92CA?e=J6s9Ex&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

## 4.6. Domain-Driven Software Architecture.

### 4.6.1. Software Architecture Context Diagram.

<p style = 'text-align:center;'>
  <img src="https://imgur.com/nuz8Pep.png" width="1000">
</p>
<br>

### 4.6.2. Software Architecture Container Diagrams.

<p style = 'text-align:center;'>
  <img src="https://imgur.com/oJQn8fH.png" width="1000">
</p>
<br>

### 4.6.3. Software Architecture Components Diagrams.

<p style = 'text-align:center;'>
  <img src="https://imgur.com/G4dqC7M.png" width="1000">
</p>
<br>

### 4.7.2. Class Dictionary.
En el presente diccionario; se mostrarán la utilidad de las clases diseñadas y presentadas en el apartado anterior:
- User: La clase usuario permite gestionar los usuarios de la aplicación. Ellos pueden registrar mascotas, acceder a suscripciones y relacionarse con los centros veterinarios y sus servicios. La clase User sirve como Clase base para la clase Pet.
- Pet: Permite gestionar la información de las mascotas registradas por los usuarios.
- Subscription: La clase subscription sirve como clase padre para las clases Premium y PlanSalud.
- Premium: Proporciona características como acumulación de puntos y descuentos.
- PlanSalud: Ofrece un plan de salud con cobertura específica para servicios veterinarios.
- PetCenter: Permite gestionar los centros veterinarios y servicios que ofrecen, está asociado a la clase Service.
- Service: Representa a los servicios disponibles en los centros veterinarios, está en una relación de agregación con los servicios específicos.
- CitasBaños: Está clase presenta los detalles de los baños, como el precio que tiene y su descripción que dependerá del centro veterinario.
- CitaMedica: Está clase presenta los detalles de las citas médicas, como el precio que tiene y su descripción que dependerá del centro veterinario.
- CitaPlacas: Está clase presenta los detalles de las placas, como el precio que tiene, el tipo de placa y su descripción que dependerá del centro veterinario.
- CompraProducto: Está clase presenta los detalles de los productos en venta, como el precio que tiene y su descripción que dependerá del centro veterinario.

## 4.8. Database Design.

### 4.8.1. Database Diagram.

<p style = 'text-align:center;'>
  <img src="https://imgur.com/cQAVYxF.png">
</p>
<br>
