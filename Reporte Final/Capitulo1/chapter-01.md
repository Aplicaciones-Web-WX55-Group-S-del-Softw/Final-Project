<hr>

# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
     <img src="/assets/upc-logo.png"></img><br>
    <strong>Ingeniería de Software - 5to Ciclo</strong><br>
    <strong>Aplicaciones Web - WX55</strong><br>
    <strong>Profesor: Angel Augusto Velasquez Nuñez</strong><br>
    <br>INFORME DE TRABAJO FINAL - TF
</p>

<p align="center">
    <strong>Startup: FarmLogitech</strong><br>
    <strong>Producto:FarmLogitech</strong>
</p>
<h3>Team Members:</h3>
<div>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
                <td>Aguilar Castillo, Rodrigo Alejandro</td>
            <td>U202210584</td>
        </tr>
        <tr>
            <td>Barrionuevo Reto, Jean Franco Joel </td>
            <td>U202219284</td>
        </tr>
        <tr>
            <td>Salgado Luna, Fernando Brian</td>
            <td>U202212023</td>
        </tr>
        <tr>
            <td>Kunimoto Watanabe, Mathias Tsuneo</td>
            <td>U202210148</td>
        </tr>   
    <tr>
            <td>Zoppi Rodríguez, Giacomo </td>
            <td>U202210029</td>
        </tr>
    </table>
</div>
<br>

# Registro de Versiones del Informe

| Versión |   Fecha    | Autor | Descripción de modificación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 
|:-------:|:----------:|:-----:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| 
|TB1| 02/04/2024 |Todos los integrantes del equipo| TB1: El equipo colaboró en la definición de la solución propuesta a través de un análisis Lean UX e identificación del segmento objetivo. Se recopilaron todos los requisitos necesarios, incluidos User Person, Product Backlog, Impact Mapping, entre otros. Luego se diseñaron maquetas y prototipos wireframe y mockups en base a la información recopilada. Finalmente, implementamos la landing page utilizando el sprint backlog para garantizar un control efectivo del progreso realizado.| 
|TP| 02/05/2024 |Todos los integrantes del equipo| TP: El equipo colaboró corrigiendo errores y puliendo detalles de la entrega anterior. Luego, diseñamos nuestro Web Application Service, con el uso de Angular y sus componentes. | 
|TB2| 05/06/2024 |Todos los integrantes del equipo| TB2: El equipo desarrolló una versión inicial de nuestro backend, asi como terminó de unir y pulir detalles de nuestro frontend | 
|TF| 23/06/2024 |Todos los integrantes del equipo| TF: El equipo colaboró corrigiendo errores y puliendo detalles de la entrega anterior. Unimos frontend y backend y terminamos el desarollo de este ultimo. | 

<br><br>

# Project Report Collaboration Insights

Para nuestra entrega del TB1 
![image](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/816b7521-6643-4983-94c5-a3b38d23789a)

Para nuestra entrega del Trabajo Parcial:
![image](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/e81122b7-abbb-4bf6-956c-acc077792c2b)
![image](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/306bfa3c-af5e-4427-86eb-a61386249468)

Para nuestra entrega del TB2: 

![image](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/77b1d1e9-37b6-4457-bebf-0aaa12382307)
![image](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/9c248b2a-7e76-4936-8d9f-ee56c13c6fa0)

Para nuestra entrega del Trabajo Final:
![image](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/f129c1a3-609e-40d5-ad1c-243fe471e4ac)




# Contenido
## Tabla de Contenidos
### [Registro de versiones del informe](#registro-de-versiones-del-informe)
### [Project Report Collaboration Insights](#project-report-collaboration-insights)
### [Contenido](#contenido)
### [Student Outcome](#student-outcome-1)
### [Capítulo I: Introducción](#capc3adtulo-i-introduccic3b3n-1)
- [COURSE PROJECT](#course-project)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
  - [Tabla de Contenidos](#tabla-de-contenidos)
    - [Registro de versiones del informe](#registro-de-versiones-del-informe-1)
    - [Project Report Collaboration Insights](#project-report-collaboration-insights-1)
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
- [Student Outcome](#student-outcome-1)
- [Capítulo I: Introducción](#capítulo-i-introducción-1)
  - [1.1. StartUp Profile](#11-startup-profile)
    - [1.1.1. Description de la StartUp](#111-description-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos Objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capc3adtulo-ii-requirements-elicitation--analysis-1)
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

### [Capítulo III: Requirements Specification](#capc3adtulo-iii-requirements-specification-1)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Product Design](#capc3adtulo-iv-product-design-1)
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

### [Capítulo V: Product Implementation, Validation & Deployment](#capc3adtulo-v-product-implementation-validation--deployment-1)
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

### [Conclusiones](#conclusiones-1)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

### [Bibliografía](#bibliografc3ada-1)
### [Anexos](#anexos-1)

# Student Outcome
Criterio: Trabaja efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo; crea un entorno colaborativo e inclusivo y establece metas, planifica tareas y cumple objetivos.

En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5.


<body>
    <table>
        <tr>
            <th>Criterio específico</th>
            <th>Acciones realizadas</th>
            <th>Conclusiones</th>
        </tr>
        <tr>
            <td><b>Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software.</b></td>
            <td> 
                <b>TB1</b><br>
                <span class="nombre">Aguilar Castillo, Rodrigo Alejandro</span><br>
                En esta entrega, se realizaron los diseños del Web Applications UX/UI tales como wireframes y mockups usando la herramienta figma. Me encargué de la elaboración de las preguntas objetivas y subjetivas para poder entrevistar a nuestro segmento objetivo posteriormente. Asimismo, estuve al tanto del equipo y sus avances.<br><br>
                <span class="nombre">Barrionuevo Reto, Jean Franco Joel</span><br>
                Para el trabajo se hizo uso de github para documentar el trabajo de modo que se aprendió a utilizar conventional commits y gitflow de modo que se pueda tener una correcta comunicación escrita en lo que corresponde a la documentación del proyecto, además de aprender a utiizar el lenguaje markdown para comunicarlo mediante github en un archivo README.md.<br><br>
                <span class="nombre">Salgado Luna, Fernando Brian</span><br>
                En esta entrega se realicé el diseño de la experiencia de usuario (UX) y la interfaz de usuario (UI) para aplicaciones web. Una característica destacada de este diseño es el enfoque en la usabilidad y la accesibilidad para garantizar que los usuarios puedan interactuar de manera efectiva con la aplicación.<br><br>
                <span class="nombre">Kunimoto Watanabe, Mathias Tsuneo</span><br>
                Encargado de llevar a cabo entrevistas con un grupo específico de personas, también encabezó la sección del landing page y capitulo 1. Además, colaboró en la creación de la página de aterrizaje utilizando los diseños proporcionados en Figma.<br><br>
                <span class="nombre">Zoppi Rodríguez, Giacomo</span><br>
                En esta entrega, me encargue de realizar y apoyar en la creación de los diagramas de clase y de base de datos, así como su diccionario. También, desarrollé parte del capitulo 5 y el landing page.<br><br>
                <b>TP</b><br>
                <span class="nombre">Aguilar Castillo, Rodrigo Alejandro</span><br>
                Durante esta entrega, llevamos a cabo la implementación completa de los features relacionados con las suscripciones y los métodos de pago.<br><br>
                <span class="nombre">Barrionuevo Reto, Jean Franco Joel</span><br>
                Durante esta fase de desarrollo, hemos completado la implementación total de las funcionalidades vinculadas al dashboard analytics y c4 model.<br><br>
                <span class="nombre">Salgado Luna, Fernando Brian</span><br>
                En esta etapa del desarrollo, hemos finalizado la implementación completa de todas las funciones relacionadas con el social-interaction y el communication management.<br><br>
                <span class="nombre">Kunimoto Watanabe, Mathias Tsuneo</span><br>
                Mediante la implementacion de esta entrega, hemos completado integrar las funcionalidades relacionadas con las búsquedas y encontrar granjas en la plataforma.<br><br>
                <span class="nombre">Zoppi Rodríguez, Giacomo</span><br>
                Durante esta fase de desarrollo, hemos completado la implementación total de todas las funcionalidades relacionadas con el monitoreo, la corrección del diagrama de clases, los mapas de empatía y el lenguaje ubiquitous.<br><br>
                <b>TB2</b><br>
                <span class="nombre">Aguilar Castillo, Rodrigo Alejandro</span><br>
                <span class="nombre">Barrionuevo Reto, Jean Franco Joel</span><br>
                <span class="nombre">Salgado Luna, Fernando Brian</span><br>
                <span class="nombre">Kunimoto Watanabe, Mathias Tsuneo</span><br>
                <span class="nombre">Zoppi Rodríguez, Giacomo</span><br>
            </td>
            <td>
                TB1: Hemos optado por un servicio de gestión y logística para granjas con el objetivo de asistir a todos los profesionales involucrados en esta industria. Nuestra startup busca abordar los desafíos de falta de organización y desperdicio de recursos que pueden ocasionar pérdidas significativas.<br><br>
                TP: Implementamos un sitio web para ofrecer un servicio de gestión y logística de granjas, con el objetivo de asistir a todas las personas involucradas en este sector. Nos propusimos abordar la problemática de la falta de organización e implementar todos los feature, que puede ayudar a este sector, mediante nuestra startup.<br><br>
                TB2: Durante la TB2, demostramos una participación efectiva y colaborativa en nuestro equipo. Cada miembro asumió responsabilidades específicas según sus habilidades, lo que nos permitió avanzar de manera eficiente en la implementación de las funcionalidades clave de la solución. Realizamos reuniones para coordinar esfuerzos, compartir progresos y resolver cualquier obstáculo que surgiera. Mantuvimos una comunicación abierta, tomando decisiones basadas en los requerimientos del proyecto y las necesidades de nuestros usuarios. Gracias al trabajo en equipo, logramos cumplir con los objetivos establecidos para este sprint y avanzar de manera significativa en el desarrollo de FarmLogiTech.
            </td>
        </tr>
        <tr>
            <td><b>Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.</b></td>
            <td>
                <b>TB1</b><br>
                <span class="nombre">Aguilar Castillo, Rodrigo Alejandro</span><br>
                Encargado de realizar entrevistas a un segmento objetivo, también realizó la sección de sprint, en la cuál está el sprint backlog y sprint planning. Asimismo, apoyó con la elaboración de la landing page utilizando los diseños de figma.<br><br>
                <span class="nombre">Barrionuevo Reto, Jean Franco Joel</span><br>
                Encargado de los diagramas C4, que son una parte integral del proceso de DDD, también conocido como Domain Driven Design. Un aspecto distintivo de este enfoque es la implementación del lenguaje ubicuo. Este lenguaje facilita la comprensión de los detalles técnicos a un nivel superior para todos los interesados, tanto internos como externos del proyecto, a través de la visualización de los diagramas.<br><br>
                <span class="nombre">Salgado Luna, Fernando Brian</span><br>
                Durante la ejecución del proyecto, fue fundamental mantener una comunicación constante con nuestro público objetivo para definir claramente nuestra solución. También se priorizó una comunicación efectiva y una organización adecuada a través de reuniones regulares.<br><br>
                <span class="nombre">Kunimoto Watanabe, Mathias Tsuneo</span><br>
                Encargado de llevar a cabo entrevistas con un grupo específico de personas, también dirigió la sección de sprint, que incluye la lista de tareas pendientes y la planificación del mismo. Además, contribuyó en la creación de la página de inicio utilizando los diseños proporcionados en Figma.<br><br>
                <span class="nombre">Zoppi Rodríguez, Giacomo</span><br>
                Me encargué de el diseño de las base de datos y diagrama de clases, que son parte esencial de la implementación de una landing page y un proyecto de Aplicacion Web.<br><br>
                <b>TP</b><br>
                <span class="nombre">Aguilar Castillo, Rodrigo Alejandro</span><br>
                En la implementación, gestioné la asignación de tareas al grupo de desarrollo para su implementación durante el sprint 2. También estuve a cargo de coordinar y ejecutar exitosamente el proceso de merge entre los diferentes branches y la rama principal del repositorio.<br><br>
                <span class="nombre">Barrionuevo Reto, Jean Franco Joel</span><br>
                Durante esta fase de desarrollo, logré completar totalmente la implementación de las funcionalidades asociadas al dashboard analytics y al modelo C4.<br><br>
                <span class="nombre">Salgado Luna, Fernando Brian</span><br>
                En la implementación, realice la gestión relacionada con la social-interaction y el communication management.<br><br>
                <span class="nombre">Kunimoto Watanabe, Mathias Tsuneo</span><br>
                Además de realizar la implementación, coordiné la asignación de tareas al equipo de desarrollo para su ejecución durante el sprint 2. También tuve la responsabilidad de corregir y llevar a cabo de manera efectiva como arreglar el código.<br><br>
                <span class="nombre">Zoppi Rodríguez, Giacomo</span><br>
                En la implementación, lideré la gestión relacionada con el monitoreo, la corrección del diagrama de clases, la elaboración de mapas de empatía y el establecimiento del lenguaje ubiquitous.<br><br>
                <b>TB2</b><br>
                <span class="nombre">Aguilar Castillo, Rodrigo Alejandro</span><br>
                <span class="nombre">Barrionuevo Reto, Jean Franco Joel</span><br>
                <span class="nombre">Salgado Luna, Fernando Brian</span><br>
                <span class="nombre">Kunimoto Watanabe, Mathias Tsuneo</span><br>
                <span class="nombre">Zoppi Rodríguez, Giacomo</span><br>
            </td>
            <td>
                TB1: Gracias al proyecto, pudimos conectar con individuos dentro de la industria y comprender lo beneficioso que podría resultarles una aplicación como la que estamos proponiendo para facilitar sus actividades diarias.<br><br>
                TP: Gracias a la ejecución del proyecto, pudimos establecer conexiones con profesionales de la industria y comprender el potencial beneficioso que una aplicación como la nuestra podría ofrecer al simplificar las actividades cotidianas.<br><br>
                TB2: Durante la TB2, profundizamos en el sector agrícola y ganadero mediante entrevistas con usuarios potenciales para validar nuestra propuesta. Presentamos el progreso de nuestro proyecto a propietarios de granjas y trabajadores del sector, obteniendo retroalimentación valiosa sobre la funcionalidad y usabilidad de nuestra solución. Estas interacciones nos ayudaron a comprender mejor las necesidades y expectativas específicas de nuestro público objetivo. Con esta información, priorizamos los requisitos y realizamos ajustes en nuestra solución, asegurando que FarmLogiTech aborde eficazmente los desafíos y oportunidades del sector. Además, nuestro análisis continuo del dominio nos permitió identificar áreas de mejora y funcionalidades adicionales que podrían beneficiar a nuestros usuarios en el futuro.
            </td>
        </tr>
    </table>
</body>

# Capítulo I: Introducción
## 1.1. StartUp Profile
### 1.1.1. Description de la StartUp
FarmLogiTech es una plataforma fundada el 22 de marzo de 2024 por un equipo de cinco estudiantes. El propósito es brindar soluciones completas para la administración agrícola, promoviendo la cooperación entre corporaciones, propietarios de granjas y trabajadores del campo.

**Misión**: Nuestra misión en FarmLogiTech es revolucionar la industria agrícola al proporcionar soluciones tecnológicas integrales que optimicen la gestión de las actividades agrícolas, promoviendo la colaboración y la eficiencia en toda la cadena de valor. Nos esforzamos por empoderar a los agricultores, corporaciones y trabajadores del campo al ofrecer herramientas innovadoras que impulsen el crecimiento sostenible, la productividad y el bienestar tanto de las personas como del medio ambiente.

**Visión**: En FarmLogiTech, visualizamos un futuro donde la tecnología agrícola transforma radicalmente la forma en que se cultiva, gestiona y distribuye la comida en todo el mundo. Nos vemos como líderes en la vanguardia de esta transformación, siendo reconocidos por nuestra capacidad para conectar a los diferentes actores del sector agrícola y proporcionar soluciones que aborden los desafíos más apremiantes de la agricultura moderna. Aspiramos a crear un ecosistema agrícola global más colaborativo, eficiente y sostenible, donde la innovación tecnológica impulse el progreso y mejore la calidad de vida de las comunidades agrícolas en todo el planeta.
### 1.1.2. Perfiles de integrantes del equipo

<table align="center" border="1" width="70%" style="text-align:center;">
    <tr align="center">
        <td rowspan="3">
            <img src="/assets/integrante-Mathias.jpg" width="250px" height="300px"></img>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Mathias Tsuneo Kunimoto Watanabe
        </td>
    </tr>
    <tr>
        <td align="left">
            <b>Código de estudiantes: </b>
            <br>
            u202210148
        </td>
    </tr>
    <tr>
        <td align="left">
            <b>Descripción de carrera: </b>
            <br>
            Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
            <b>Acerca de:</b>
            <br>
            Soy Mathias Kunimoto, estudiante de la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas UPC. El camino que quiero llegar, es en convertirme en un desarrollador full stack pero mas orientado en el frontend.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="/assets/integrante-rodrigo.jpg" width="250px" height="300px"></img>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Rodrigo Alejandro Aguilar Castillo
        </td>
    </tr>
    <tr>
        <td align="left">
            <b>Código de estudiantes: </b>
            <br>
            u202210584
        </td>
    </tr>
    <tr>
        <td align="left">
            <b>Descripción de carrera: </b>
            <br>
            Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
            <b>Acerca de:</b>
            <br>
            Soy Rodrigo Aguilar, estudiante de la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas UPC. Me llama mucho la atención la tecnología y los dispositivos electrónicos. Uno de mis pasatiempos es programar.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="/assets/integrante-Fernando.jpg" width="270px" height="300px"></img>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Fernando Brian Salgado Luna
        </td>
    </tr>
    <tr>
        <td align="left">
            <b>Código de estudiantes: </b>
            <br>
            u202212023
        </td>
    </tr>
    <tr>
        <td align="left">
            <b>Descripción de carrera: </b>
            <br>
            Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
            <b>Acerca de:</b>
            <br>
            Mi nombre es Fernando Salgado, actualmente me encuentro cursando el quinto ciclo de la carrera de Ingeniería de Software. Soy bueno colaborando de manera armoniosa y productiva con otros miembros del equipo, aportando ideas y contribuyendo al logro de objetivos comunes.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="/assets/integrante-jean.jpg" width="250px" height="300px"></img>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Jean Franco Joel Barrionuevo Reto
        </td>
    </tr>
    <tr>
        <td align="left">
            <b>Código de estudiantes: </b>
            <br>
            u202219284
        </td>
    </tr>
    <tr>
        <td align="left">
            <b>Descripción de carrera: </b>
            <br>
            Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
            <b>Acerca de:</b>
            <br>
            Mi nombre es Jean Franco Barrionuevo, me encuentro en el 5to ciclo de Ingeniería de Software. Decidí estudiar esta carrera porque siempre me ha apasionado el mundo de la tecnología y software en particular.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="/assets/integrante-giacomo.jpg" width="250px" height="300px"></img>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Giacomo Zoppi Rodríguez
        </td>
    </tr>
    <tr>
        <td align="left">
            <b>Código de estudiantes: </b>
            <br>
            u202210029
        </td>
    </tr>
    <tr>
        <td align="left">
            <b>Descripción de carrera: </b>
            <br>
            Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
            <b>Acerca de:</b>
            <br>
            Mi nombre es Giacomo Zoppi, me encuentro en el quinto ciclo de Ingeniería de Software. Me destaco en el trabajo en equipo, la elaboración de ideas y el análisis de datos.
        </td>
    </tr>
</table>


## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
La industria agrícola y ganadera enfrenta desafíos significativos en términos de mejorar la producción, calidad y gestión de cultivos y ganado. Los agricultores y ganaderos se ven presionados por el crecimiento de la población mundial y los cambios en las demandas del mercado, pero enfrentan obstáculos como la falta de herramientas tecnológicas, la coordinación ineficiente entre granjasy la escasez de información en tiempo real sobre el estado de los cultivos, condiciones climáticas y bienestar animal. Según un informe de Rizia, Ana (2020) publicado en la página del MBA USP, muchos ganaderos pueden carecer de la capacitación necesaria en gestión agrícola y comercialización, lo que dificulta la toma de decisiones informadas y eficientes. Además, la falta de un control financiero adecuado puede llevar a dificultades económicas y poner en riesgo la viabilidad de la granja a largo plazo.

Siguiendo la estructura propuesta

-   **What?**

    La industria  enfrenta desafíos significativos en la gestión eficiente de las granjas, debido a la falta de herramientas tecnológicas adecuadas y la presión para aumentar la producción y calidad de los cultivos.


-   **When?**
    ¿Cuando estamos viendo el problema? 
    Este problema ha ido aumentando en los últimos años, especialmente con el crecimiento de la población y los cambios en las demandas del mercado agrícola.
    
    ¿En que momento del día y/o del proceso en cuestión?
    Durante las horas de trabajo y en el proceso de organización de tareas.  

-   **Where?**
      ¿Donde estamos viendo los problemas?¿En que parte/lugar del producto/proceso estamos viendo el problema?
    Este problema es global y afecta a las granjas en diversas regiones del mundo, tanto en países desarrollados como en desarrollo.

-   **Who?**
      ¿A quien le sucede? ¿El problema está relacionado con las habilitades de las personas?
    Los agricultores, tanto pequeños como grandes, están directamente involucrados en estas dificultades, ya que son responsables de la producción agrícola y deben enfrentar las demandas del mercado. Asi que sí, esta relacionado con sus habilidades en cuanto a teconologia y organización se refiere. 

- **Why?**
    ¿Por qué sucede el problema? ¿Cual es la causa?
  Es crucial abordar esta problemática porque la agricultura desempeña un papel fundamental en la alimentación de la creciente población mundial y en la economía global.

-   **How?**
    ¿Como se diferencia el problema del estado normal(optimo)? ¿La tendencia en la que aparece el problema es aleatoria o sigue un patrón?
    El problema genera que muchas veces el sistema de organización resulte ineficaz. En su lugar, si el sistema fuera optimo, las tareas serian claras y la producción seria mucho mas         eficiente.
    
    ¿Como se utilizará el producto? 
    Permitirá a los agricultores optimizar sus operaciones, mejorar la calidad de los cultivos y aumentar su competitividad en el mercado agrícola.
    
-   **How much?**
    ¿Cuantos problemas se dan en un dia? ¿En una semana? ¿En un mes?
    Esto genera dificultades en el dia a dia de los dueños de granjas y agricultores independientes.
    
    ¿Cuanto dinero están implicando?
    El costo de implementar estas soluciones tecnológicas puede variar dependiendo de la escala de la granja y los recursos disponibles para la adopción de tecnología agrícola.

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

Siguiendo la estructura propuesta por Jeff Gothelf y Josh Seiden, en su libro "Lean Ux":

- El estado actual de la industria agricola se ha centrado en la administación de tareas agricolas con herramientas anticuadas y poco eficaces . Estos pain points incluyen desafios en las operaciones de granja como la organización del trabajo. 

Lo que los productos existentes no logran abordar es la implementación de herramientras eficientes de organización de granjas, lo que afecta la rentabilidad en toda la cadena de suministro agrícola.

Nuestro producto/servicio abordará esta brecha al proporcionar una plataforma integral para optimizar la gestión de tareas. 

Nuestro enfoque inicial estará en involucrar a grandes empresas agrícolas, propietarios de granjas y personal de campo que buscan optimizar sus operaciones.

Sabremos que hemos tenido éxito cuando veamos un aumento en la adopción de nuestra plataforma entre nuestro público objetivo, lo que llevará a una mayor eficiencia en las operaciones de las granjas. 

- El estado actual de la industria agricola  se ha centrado en la colaboración de grandes empresas y propietarios de granjas mediante intermediarios o medios de comunicación poco eficaces .Estos pain points incluyen desafios en las operaciones de granja como problemas con la comunicación entre dueños de granjas  y empresas.

Lo que los productos existentes no logran abordar es la implementación de herramientras eficientes de organización y visualización de granjas, lo que dificulta la facilitación de asociaciones beneficiosas que impulsen el crecimiento de la industria. 

Nuestro producto/servicio abordará esta brecha al proporcionar una plataforma integral para fomentar una colaboración fluida entre empresas agrícolas y propietarios de granjas.

Nuestro enfoque inicial estará en involucrar a grandes empresas agrícolas y propietarios de granjas que buscan optimizar sus operaciones y mejorar la colaboración para beneficio mutuo.

Sabremos que hemos tenido éxito cuando veamos un aumento en la adopción de nuestra plataforma entre nuestro público objetivo y una mayor fortaleza en las asociaciones dentro del ecosistema agrícola.


#### 1.2.2.2. Lean UX Assumptions

**Business Outcomes:**

Extraído de el libro Lean UX, 3rd Edition (Gothelf, 2021)

**¿Como podremos solucionar nuestro problema de negocio? ¿Que vamos a medir?**

Podremos solucionar nuestr problema, mediante una mas eficaz forma de organizar las actividades, producción, egresos y ventas de su granja.
Vamos a medir la cantidad de suscripciones:
    - Cumplir con la meta de crecimiento mensual del 20% en el número de usuarios activos de la plataforma, medida por el número de granjas que utilizan activamente FarmLogiTech.
    
el ratio de exito y productividad de las granjas tras el uso de nuestra aplicación:
    - Esperamos que mediante entrevistas y estudios, al menos un 70% de los usuarios que usen nuestra aplicación si hayan notado alguna mejoria en la productividad, mientras que las empresas grandes que adopten FarmLogiTech logren mejorar su eficiencia operativa en un 15% en la gestión y distribución de productos agrícolas de alta calidad dentro del primer año de implementación

el numero de reseñas positivas
    - Esperamos que durante nuestros primeros meses, las reseñas sean en un 50% positivas, el otro 50% nos servirá para mejorar y otorgar un producto mas adecuado.

, el indice de uso de nuestra aplicación asi como su retención, etc. 
- Renovación de suscripciones del 70% al final del primer año, indicando la satisfacción y la retención de clientes.


1. **Creemos que nuestros usuarios necesitan**: Una forma mas eficaz de organizar las actividades, producción, egresos y ventas de su granja. Así como facilitar la comunicación entre empresas y granjas. 

2. **Estas necesidades se pueden satisfacer**: Con la creación de un proyecto que les permita acceder a estas funcionalidades desde su telefono movil u ordenador. 

3. **Nuestros clientes iniciales serán**: Los dueños de granjas, trabajadores de granjas y empresas. 

4. **El valor #1 que un cliente quiere de nuestro servicio es:** registrar y organizar la producción de su granja
   **Los clientes tambien pueden obtener:** la visualización, promoción y facil asociacion con empresas. 

5. **Vamos a obtener la mayoria de los clientes mediante** publicidad en linea y campañas en internet o televisión. 

6. **Vamos a hacer dinero mediante** las suscripciones premium, esperamos lograr en el primer año, la cantidad de 200 suscripciones a nuestro servicio premium. Solo de este modo, creemos que sera rentable. 

7. **Nuestra competencia en el mercado serán** las plataformas dedicadas tambien a la organización de actividades de granja. 
    **Vamos a tener ventaja frente a nuestra competencia debido a**que ofrecemos un registro de animales, cultivos, galpones, asi como una promoción de granjas. 

8. **El mayor riesgo de producción es** que el segmento objetivo, en especial los trabajadores de granja o dueños de granja no se encuentren dispuestos a cambiar su modus operandi y adaptarse al avance tecnologico. 
   **Lo resolvemos realizando**una promoción adecuada que logre cautivar a nuestro segmento obejtivo. Así como una interfaz accesible y facil de utilizar. 

9. **Que otros assumptions tenemos, que si son probados como falsos, podria ocasionar que nuestro proyecto fracase:**Las empresas grandes no usen nuestra aplicación para comunicarse con los dueños de granjas. En ese caso, perderiamos gran parte de nuestro segmento, así como la funcionalidad de promoción de granjas y asociación con empresas.


User Assumptions
**1. ¿Quien es el usuario?**
   - Empresas Grandes
   - Dueños de Granjas
   - Trabajadores de Granjas

**2. ¿Donde entra nuestro producto en su trabajo o su vida?**
   - Entra en su trabajo directamente. Encaja en la mejora de la gestión de procesos en una granja, lo que culmina en una mayor rentabilidad, así como un mejor funcionamiento de las granjas.
     
**3. ¿Cual es el problema que nuestro producto soluciona?**
   - La dificil comunicación que puede resultar entre granjas y empresas. Así, como la desconfianza que puede haber en los productos de la granja. Además abre la puerta a negocios nuevos en un mercado saturado.
   - Problemas de optimización en las operaciones, asi como de organización y de promoción. 
   - Necesitan herramientas para facilitar la realización de tareas diarias y mejorar su eficiencia.
     
**4. ¿Como y cuando nuestro producto es usado?**
   El servicio será usado por los dueños y trabajadores de granja durante su jornada laboral o antes, para poder designar las tareas con anticipación o registrar el ingreso de nuevos animales o cultivos. Mientras que, por las empresas podrá ser utilizado cuando surja la necesidad de encontrar nuevos proveedores y formar alianzas estratégicas con agricultores. 

**5. ¿Que caracteristicas son importantes?**
    - Un correcto funcionamiento
    - Organización de tareas y actividades de granja
    - Registro y organización de empleados.
    - Asignación de tareas a empleados
    - Registro y organización de animales, cultivos y galpones.
    - Promoción, publicación y rating de granjas. 

**6. ¿Como deberia nuestro producto verse o comportarse?**
    El producto debe verse con una interfaz simple, interactiva, atractiva e inclusiva. Debe poder comportarse correctamente, ser capaz de llamar la atención de quien la use, pero tambien otorgar una experiencia innovadora y acogedora a nuestro segmento objetivo.
    


**User Outcomes:**

¿Que está intentando conseguir el usuario?
- Empresas Grandes:Quiero poder entablecer una mejor comunicación con granjas
- Trabajadores de Granjas y Dueños de granja: Quiero poder aumentar la productividad y mejorar la organizacion de mi granja

¿Como se quiere sentir el usuario?
- Trabajadores de Granjas y Dueños de granja: Quiero sentir que mi trabajo esta dando frutos y estoy sacandole el maximo provecho. Quiero que mi trabajo sea rentable.
- Empresas Grandes: Quiero sentir que mi trabajo es mas sencillo y mas accesible.

¿Como nuestro producto lo acerca a su objetivo?
- Trabajadores de Granjas y Dueños de granja: Le ayuda a aumentar su productividad, a aumentar su rentabilidad, seguir el progreso de sus ingresos y egresos asi como monitorear sus tareas y su granja.
- Empresas Grandes: Le permite convertir una tarea tan compleja y poco accesible como es contactar con dueños de granjas en algo mucho mas sencillo y facil de utilizar. 

¿Por que nuestros usuarios se interesarian por nuestro producto? ¿Que beneficio podrian obtener?
- Empresas Grandes: Acceso a productos agrícolas de alta calidad y mejora en la eficiencia de su cadena de suministro.
- Dueños de Granjas: Mayor eficiencia en la gestión de las operaciones agrícolas y aumento en la rentabilidad.
- Trabajadores de Granjas: Facilidad para realizar tareas diarias y mejora en su eficiencia laboral.

¿Que cambio en su comportamiento veremos que nos dira que nuestro objetivo ha sido logrado?

- Trabajadores de Granjas y Dueños de granja: Esperamos que nuestros usuarios hagan uso de nuestra aplicación durante toda su jornada laboral, para tanto la organización como para el control de las actividades de la granja. Si vemos que, mediante entrevistas o estudios, podemos determinar que su productividad ha aumentado en un 200%, podremos decir que nuestro logro ha sido conseguido con creces. 
- Empresas Grandes: De igual, forma dirigido para las empresas, esperamos que el ratio de retención sea de digamos por ejemplo, en un mes, esperamos la cantidad de 200 nuevos clientes. Restandole al numero de clientes al final este periodo (300 usuarios ) el numero de clientes adquiridos durante este periodo (200 usuarios) y dividirlo entre el numero total de clientes al inicio del periodo(200 usuarios), tendriamos aproximdamente un 50% de retención de audiencia.



**Feature Assumptions**
- **Creemos que** el producto debe contar con planes estandares y premium que se adapten a lo que necesite el usuario, ofreciendo así una mayor flexibilidad y un valor agregado.
- **Creemos que** el producto debe podar hacer uso del catálogo de granjas para alianzas empresariales.
- **Creemos que** el producto debe poder ofrecer la funcionalidad de valoración y contacto de granja.
- **Creemos que** el producto debe ofrecer un sistema de seguimiento en tiempo real del estado de los cultivos y el bienestar animal en la plataforma,
- **Creemos que** el prodcuto debe implementar características de comunicación en tiempo real y herramientas de colaboración para mejorar la coordinación entre propietarios de granjas  y trabajadores agrícolas.
- **Creemos que** el producto debe ofrecer una plataforma tecnológica completa para la gestión eficaz de actividades agrícolas y ganaderas


#### 1.2.2.3. Lean UX Hypothesis Statements

Siguiendo el siguiente formato, extraido del libro "Lean Ux, 3rd edition", escrito por Jeff Gothelf y Josh Seiden: "We believe that [business outcome] will be achieved if [user] attains [user benefit] with [feature]".


1. Nosotros creemos que el aumento de  la adopción y fidelización  de usuarios  será conseguido si los dueños de granja y agricultores independientes tienen una mejora en la gestión de operaciones agrícolas y en la calidad de los productos con la implementación de planes estándar y premium que se adapten a lo que necesite el usuario, ofreciendo así una mayor flexibilidad y un valor agregado.


2. Nosotros creemos que el establecimiento de alianzas estratégicas entre empresas y granjas será conseguido si las empresas agrícolas y ganaderas interesadas en asociarse con granjas tienen una facilitación en la visualización  y colaboración entre granjas y empresas con el uso del catálogo de granjas para alianzas empresariales. 

3. Nosotros creemos que el establecimiento de alianzas estratégicas entre empresas y granjas será conseguido si los dueños de granjas y agricultores independientes tienen una facilitación en la visualización y colaboración entre granjas y empresas con la funcionalidad de valoración y contacto de granja.

4. Nosotros creemos que la reducción de pérdidas económicas y de productos será conseguido si los dueños de granjas y agricultores independientes tienen una mejora en la gestión de operaciones agrícolas y en la calidad de productos con un sistema de seguimiento en tiempo real del estado de los cultivos y el bienestar animal en la plataforma.

5.Nosotros creemos que la reducción de pérdidas económicas y calidad de productos será conseguida si los trabajadores agrícolas y personal de granja tienen una mayor eficiencia y productividad en las tareas de la granja con la implementación de características de comunicación en tiempo real y herramientas de colaboración para mejorar la coordinación entre propietarios de granjas  y trabajadores agrícolas.

6. Nosotros creemos que la reducción de pérdidas económicas y calidad de productos será conseguida si los dueños de granja y agricultores independientes tienen una mejora en la gestión de operaciones agrícolas y en la calidad de productos con una plataforma tecnológica completa para la gestión eficaz de actividades agrícolas y ganaderas

#### 1.2.2.4. Lean UX Canvas

![modelo_canvas](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/eef04133-7c88-45f7-80b2-011204f9b328)


## 1.3. Segmentos Objetivo



**Dueños de Granjas y Agricultores Independientes:**

Los propietarios de granjas y agricultores independientes representan una diversidad de tipos de granjas, incluyendo ganado y cultivos. La mayoría, aproximadamente el 80%, se dedican principalmente a la venta de sus productos, aunque un segmento significativo, el 20%, también los destina al autoconsumo. Predominantemente masculino, con un 64.88%, y con niveles educativos variados, donde un 36.9% ha culminado la secundaria y un 44.6% solo cuenta con educación primaria. Mayormente operan en granjas de pequeña escala, con un 92.7% poseyendo menos de 10 hectáreas (Santisteban,2022). Su principal fuente de ingresos proviene de actividades agrarias, y aunque la mayoría posee un celular, solo un pequeño porcentaje recibe asistencia técnica. Buscan activamente herramientas tecnológicas para mejorar la gestión de sus operaciones agrícolas o ganaderas, con un interés claro en optimizar la eficiencia, productividad y rentabilidad de sus cultivos y ganado.

**Trabajadores de Granja:**

Los trabajadores de granja desempeñan tareas esenciales en las operaciones diarias, como siembra, riego, cosecha y cuidado del ganado. Este grupo necesita herramientas prácticas y de fácil uso para realizar sus labores de manera eficiente y colaborativa. Gran parte de los trabajadores de granja no son dueños, sino que tienen roles comunitarios, como comuneros o poseesionarios, por lo que cumplen con una serie de responsabilidades y tareas guiadas por una persona con un rol superior; sin embargo, tan solo un 0.41% utiliza tecnología para poder elaborar su trabajo (Santisteban,2022). Su objetivo principal es mejorar la productividad y contribuir al éxito general de la granja y predomina el género masculino. 

**Empresas y Corporaciones del Sector Agrícola y Ganadero:**

Las empresas y corporaciones en este sector abarcan una amplia gama, desde empresas agrícolas hasta procesadores de alimentos y distribuidores. Están interesadas en establecer asociaciones estratégicas con granjas para mejorar la cadena de suministro y obtener productos de alta calidad. Un dato relevante es que el 70% de los alimentos consumidos por los 32 millones de peruanos proviene de la agricultura familiar, lo que indica la importancia económica de la industria alimentaria. Estas empresas también pueden estar interesadas en alquilar o comprar granjas para expandir sus operaciones. 

Stakeholders internos: 
- El equipo de FarmLogiTech y el resto del equipo de desarrollo.

Stakeholders externos: 
- Dueños de granjas. Posesionarios de granjas. Empresas agropecuarias. Trabajadores y comuneros de granjas. 
