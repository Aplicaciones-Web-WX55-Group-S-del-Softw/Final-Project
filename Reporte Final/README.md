<hr>

# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
     <img src="/assets/upc-logo.png"></img><br>
    <strong>Ingeniería de Software - 5to Ciclo</strong><br>
    <strong>Aplicaciones Web - WX55</strong><br>
    <strong>Profesor: Angel Augusto Velasquez Nuñez</strong><br>
    <br>INFORME DE TRABAJO FINAL - TF1
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
                He colaborado en la redacción de las instrucciones para el despliegue del backend de la aplicación, con el objetivo de que los futuros desarrolladores puedan comprender y replicar el proceso de implementación de manera autónoma.<br><br>
                <span class="nombre">Barrionuevo Reto, Jean Franco Joel</span><br>
                He realizado commits tanto para la página de aterrizaje como para el frontend de la aplicación web y los servicios web.<br><br>
                <span class="nombre">Salgado Luna, Fernando Brian</span><br>
                Contribuí a la creación del backend y al desarrollo del frontend, asegurando un progreso significativo y cumpliendo con los criterios establecidos, mientras atendía las necesidades del cliente. <br><br>
                <span class="nombre">Kunimoto Watanabe, Mathias Tsuneo</span><br>
                He realizado progresos en el back-end de la aplicación web. Los endpoints que he creado están correctamente documentados utilizando la herramienta swagger-ui. <br><br>
                <span class="nombre">Zoppi Rodríguez, Giacomo</span><br>
                Aporté a la elaboración del backend y al desarrollo del frontend, logrando un avance significativo conforme a los criterios establecidos y teniendo en cuenta las necesidades del cliente.<br><br>
                <b>TF</b><br><br>
                <span class="nombre">Aguilar Castillo, Rodrigo Alejandro</span><br>
                Me encargue de conectar el frontend y backend, ademas de desarrollar el backend con las conexiones                
                <br><br> <span class="nombre">Barrionuevo Reto, Jean Franco Joel</span><br>
                Contribuí a la elaboración de las pruebas del backend con los endpoints, además de modificar las tareas del bounded context.                
                <br> <br> <span class="nombre">Salgado Luna, Fernando Brian</span><br>
                Contribuí a la creación del backend y al desarrollo del frontend, asegurando un progreso significativo y cumpliendo con los criterios establecidos, mientras atendía las necesidades del cliente. <br><br>
                <span class="nombre">Kunimoto Watanabe, Mathias Tsuneo</span><br>
                Me encargue de desarrolloar la sección de sign in, sign up y conexion con el frontend.                
                <br> <br> <span class="nombre">Zoppi Rodríguez, Giacomo</span><br>
                Contribuí al desarrollo de endpoints y a la conexión entre el frontend y el backend en los bounded contexts restantes. Además, colaboré en la mejora continua de la documentación, aplicando correcciones y mejoras según la retroalimentación de la TB2.            </td>
            <td>
                TB1: Hemos optado por un servicio de gestión y logística para granjas con el objetivo de asistir a todos los profesionales involucrados en esta industria. Nuestra startup busca abordar los desafíos de falta de organización y desperdicio de recursos que pueden ocasionar pérdidas significativas.<br><br>
                TP: Implementamos un sitio web para ofrecer un servicio de gestión y logística de granjas, con el objetivo de asistir a todas las personas involucradas en este sector. Nos propusimos abordar la problemática de la falta de organización e implementar todos los feature, que puede ayudar a este sector, mediante nuestra startup.<br><br>
                TB2: Durante la TB2, demostramos una participación efectiva y colaborativa en nuestro equipo. Cada miembro asumió responsabilidades específicas según sus habilidades, lo que nos permitió avanzar de manera eficiente en la implementación de las funcionalidades clave de la solución. Realizamos reuniones para coordinar esfuerzos, compartir progresos y resolver cualquier obstáculo que surgiera. Mantuvimos una comunicación abierta, tomando decisiones basadas en los requerimientos del proyecto y las necesidades de nuestros usuarios. Gracias al trabajo en equipo, logramos cumplir con los objetivos establecidos para este sprint y avanzar de manera significativa en el desarrollo de FarmLogiTech. <br><br>
                TF: El equipo se encargó de desarrollar las secciones de conexión entre el frontend y el backend, para realizar la conexión de los bounded contexts restantes. Además, se colaboró en la mejora continua de la documentación, aplicando correcciones y mejoras según la retroalimentación de la TB2. Gracias a la colaboración y el esfuerzo conjunto, logramos completar con éxito la implementación de la solución propuesta, cumpliendo con los objetivos establecidos y satisfaciendo las necesidades de nuestros usuarios.
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
                <b>TB2</b><br><br>
                <span class="nombre">Aguilar Castillo, Rodrigo Alejandro</span><br>
                En la implementación, realice el desarrollo del frontend y mejoras en el landing page.<br><br>
                <span class="nombre">Barrionuevo Reto, Jean Franco Joel</span><br>
                Me encargué de preparar el backlog del sprint 3 y organizé el sprint en Trello para documentar los avances y gestionar los entregables.<br> <br>
                <span class="nombre">Salgado Luna, Fernando Brian</span><br><br>
                En la implementación, me encargué de gestionar mejoras en el frontend y realicé entrevistas a usuarios para optimizar la experiencia. <br><br>
                <span class="nombre">Kunimoto Watanabe, Mathias Tsuneo</span><br><br>
                Las entrevistas de validación permitieron analizar las historias de usuario técnicas al obtener información sobre los puntos más relevantes para el usuario final y cómo utilizará la aplicación. <br><br>
                <span class="nombre">Zoppi Rodríguez, Giacomo</span><br><br>
                Conduje entrevistas de validación con los usuarios para entender su experiencia con la aplicación. Esto permitió comunicar el estado actual del desarrollo del proyecto y obtener retroalimentación sobre la satisfacción del cliente con la propuesta.
                <br><br><b>TF</b><br><br>
                <span class="nombre">Aguilar Castillo, Rodrigo Alejandro</span><br>
                En este entregable final, se dio prioridad al correcto funcionamiento de la aplicación y a proporcionar una buena experiencia al usuario. Se corrigieron errores y se realizaron ajustes en la nomenclatura para mantener un desarrollo futuro más organizado.<br><br>
                <span class="nombre">Barrionuevo Reto, Jean Franco Joel</span><br>
                Trabajé en la elaboración de parte del sprint 4 y actualicé secciones del documento correspondiente.<br> <br>
                <span class="nombre">Salgado Luna, Fernando Brian</span><br><br>
                En este entregable final, se puso énfasis en asegurar el correcto funcionamiento de la aplicación y en mejorar la experiencia del usuario. Se abordaron problemas y se establecieron las conexiones necesarias con el backend. <br><br>
                <span class="nombre">Kunimoto Watanabe, Mathias Tsuneo</span><br><br>
               En este entregable final, se enfocó en asegurar el funcionamiento adecuado de la aplicación y en mejorar la experiencia del usuario. Se solucionaron errores y se realizaron ajustes en la nomenclatura para facilitar un desarrollo futuro más organizado. <br><br>
                <span class="nombre">Zoppi Rodríguez, Giacomo</span><br><br>
                En este desarrollo final, se priorizó garantizar el correcto funcionamiento de la aplicación y mejorar la experiencia del usuario. Se corrigieron errores y se realizaron ajustes en la terminología para mantener un desarrollo futuro más estructurado.
            </td>
            <td>
                TB1: Gracias al proyecto, pudimos conectar con individuos dentro de la industria y comprender lo beneficioso que podría resultarles una aplicación como la que estamos proponiendo para facilitar sus actividades diarias.<br><br>
                TP: Gracias a la ejecución del proyecto, pudimos establecer conexiones con profesionales de la industria y comprender el potencial beneficioso que una aplicación como la nuestra podría ofrecer al simplificar las actividades cotidianas.<br><br>
                TB2: Durante la TB2, profundizamos en el sector agrícola y ganadero mediante entrevistas con usuarios potenciales para validar nuestra propuesta. Presentamos el progreso de nuestro proyecto a propietarios de granjas y trabajadores del sector, obteniendo retroalimentación valiosa sobre la funcionalidad y usabilidad de nuestra solución. Estas interacciones nos ayudaron a comprender mejor las necesidades y expectativas específicas de nuestro público objetivo. Con esta información, priorizamos los requisitos y realizamos ajustes en nuestra solución, asegurando que FarmLogiTech aborde eficazmente los desafíos y oportunidades del sector. Además, nuestro análisis continuo del dominio nos permitió identificar áreas de mejora y funcionalidades adicionales que podrían beneficiar a nuestros usuarios en el futuro.<br><br>
                TP: En este entregable final, nuestro equipo se centró en dos aspectos clave: tratar de garantizar el correcto funcionamiento de la aplicación y mejorar la experiencia del usuario. Se corrigieron errores significativos y se realizaron ajustes en la nomenclatura para asegurar que el desarrollo futuro sea más organizado y eficiente. Además, avanzamos en la elaboración del sprint 4 y actualizamos secciones importantes del documento correspondiente. Este enfoque no solo fortaleció la base técnica del proyecto, sino que también sentó las bases para futuras iteraciones que puedan continuar mejorando tanto la funcionalidad como la usabilidad de la aplicación.
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

Podremos solucionar nuestr problema, mediante una mas eficaz forma de organizar las actividades, producción, egresos y ventas de su granja:
Vamos a medir la cantidad de suscripciones:

    - Cumplir con la meta de crecimiento mensual del 20% en el número de usuarios activos de la plataforma, medida por el número de granjas que utilizan activamente FarmLogiTech.

El ratio de exito y productividad de las granjas tras el uso de nuestra aplicación:

    - Esperamos que mediante entrevistas y estudios, al menos un 70% de los usuarios que usen nuestra aplicación si hayan notado alguna mejoria en la productividad, mientras que las empresas grandes que adopten FarmLogiTech logren mejorar su eficiencia operativa en un 15% en la gestión y distribución de productos agrícolas de alta calidad dentro del primer año de implementación

El numero de reseñas positivas:

    - Esperamos que durante nuestros primeros meses, las reseñas sean en un 50% positivas, el otro 50% nos servirá para mejorar y otorgar un producto mas adecuado.

El indice de uso de nuestra aplicación asi como su retención:

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

# CAPITULO II: Requirements Elicitation & Analysis
## 2.1. Competidores
Algunos competidores en el campo de la gestión y logística de granjas incluyen FarmLogs, Granular y Agworld.

### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</td>
  </tr>
  <tr>
    <td colspan="5">Este análisis se realizó con la finalidad de poder identificar a nuestros potenciales competidores e idear estrategias y tácticas para diferenciarnos de estos.</td>
  </tr>
  <tr>
    <td colspan="3">(En la cabecera colocar por cada competidor nombre y logo)</td>
    <td colspan="1" valign="top" style="font-weight: bold;">
        FarmLogiTech
        <br>
    <td colspan="1" valign="top" style="font-weight: bold;">
        FarmLogs
    <div style="text-align: center;">
        </div>
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;">
        Granular
      <div style="text-align: center; margin-top: 20px;">
            </div>
      </td>
    <td colspan="1" valign="top" style="font-weight: bold;" >
        Agworld
      <div style="text-align: center; margin-top: 10px;">
            </div>
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top">Portal de empleo que ofrece una variedad de oportunidades de empleos temporales, conocidos como "cachuelos". Implementa un sistema de seguimiento de los trabajos realizados y brindar retroalimentación.</td>
    <td colspan="1" valign="top">Ofrece una amplia gama de oportunidades laborales en diversos sectores y niveles.</td>
    <td colspan="1" valign="top">Portal de empleo que brinda oportunidades laborales en Perú. Tiene una amplia gama de ofertas laborales.</td>
    <td colspan="1" valign="top">Portal de empleo que conecta a empleadores y candidatos. Proporciona opciones para una variedad de industrias y niveles de experiencia.</td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva</td>
    <td colspan="1" valign="top">Se enfoca en ayudar a personas jóvenes sin experiencia a encontrar trabajos eventuales y proyectos freelance. Brinda un estatus del proyecto y seguridad al momento del pago entre el empleador y chambeador.</td>
    <td colspan="1" valign="top">Posee una cobertura local e internacional en múltiples sectores. Facilita a los usuarios una amplia gama de ofertas laborales.</td>
    <td colspan="1" valign="top">Cuenta con buen posicionamiento en América Latina. Ofrece oportunidades laborales en diversos sectores y regiones. Es una herramienta efectiva para publicar y promocionar vacantes.</td>
    <td colspan="1" valign="top">Presencia en múltiples países de América Latina. Ofrece una amplia variedad de ofertas laborales y brinda opción para publicar empleos temporales.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top">Jóvenes de entre 18 a 30 años y empleadores entre 18 y 50 años.</td>
    <td colspan="1" valign="top">Público en general mayor de 18 años que busque empleo.</td>
    <td colspan="1" valign="top">Abierto a diversas edades, ya que ofrece oportunidades de empleo.</td>
    <td colspan="1" valign="top">Dirigido a personas de diferentes edades en búsqueda de empleos.</td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top">ChambeaPe ofrece simplicidad y facilidad de uso, con campañas en redes sociales y colaboraciones locales y promociones.</td>
    <td colspan="1" valign="top">Destaca por su red de empresas y variedad de ofertas, empleando campañas de correo electrónico y participación en eventos.</td>
    <td colspan="1" valign="top">Posee amplia cobertura y opciones premium, con anuncios en línea como estrategia de marketing.</td>
    <td colspan="1" valign="top">Enfoque regional, con campañas y recursos locales, buscando colaboraciones para fortalecer su presencia.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top">Plataforma inclusiva que conecta empleadores y trabajadores temporales, proporcionando una experiencia sencilla y segura para encontrar proyectos eventuales en Perú.</td>
    <td colspan="1" valign="top">Proporciona una amplia gama de trabajos temporales y oportunidades de corta duración, respaldada por sus opciones avanzadas de búsqueda.</td>
    <td colspan="1" valign="top">La aplicación brinda una plataforma donde se muestra gráficas sencillas sobre tus gastos con la finalidad de planificar un presupuesto.</td>
    <td colspan="1" valign="top">Ofrece empleos tanto temporales como permanentes, dando un espacio consolidado para diversos perfiles laborales y oportunidades.</td>
  </tr>
  <tr>
    <td colspan="2">Precios & Costos</td>
    <td colspan="1" valign="top">La aplicación cuenta con una versión gratuita y una versión de pago la cual costará $1,70.</td>
    <td colspan="1" valign="top">La aplicación cuenta con una versión gratuita y una versión de pago la cual tiene tarifas de acuerdo al consumo.</td>
    <td colspan="1" valign="top">La aplicación es totalmente gratuita.</td>
    <td colspan="1" valign="top">La aplicación cuenta con una versión gratuita y una versión de pago la cual varía de acuerdo a lo que busque el empleador.</td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución (Web y/o Móvil)</td>
    <td colspan="1" valign="top">Los canales de distribución son digitales, como La App Store y Google Play.</td>
    <td colspan="1" valign="top">Los canales de distribución son digitales, como La App Store y Google Play.</td>
    <td colspan="1" valign="top">Los canales de distribución son digitales, como La App Store y Google Play.</td>
    <td colspan="1" valign="top">Los canales de distribución son digitales, como La App Store y Google Play.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="5"><p>Análisis SWOT</p></td>
    <td colspan="6">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</td>
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top">Variedad de trabajos temporales, seguimiento del estatus del trabajo, retroalimentación entre ambas partes y pago seguro para garantizar la satisfacción del empleador y trabajador.</td>
    <td colspan="1" valign="top">Amplia variedad de ofertas laborales en diferentes sectores y permite a los candidatos cargar su currículum para facilitar el reclutamiento.</td>
    <td colspan="1" valign="top">Cuenta con una comunidad activa de usuarios y empresas, fomentando la interacción y el networking.</td>
    <td colspan="1" valign="top">Ofrece opciones premium para empresas que buscan destacar sus ofertas laborales, generando ingresos adicionales. Herramientas avanzadas de reclutamiento.</td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top">Inicialmente, no se podrá contar con comentarios de ninguna de las dos partes. Debido a que estamos iniciando desde cero.</td>
    <td colspan="1" valign="top">La falta de funciones avanzadas de filtrado y búsqueda podría dificultar la navegación para los usuarios que buscan ofertas específicas.</td>
    <td colspan="1" valign="top">La competencia con otras plataformas consolidadas podría dificultar la retención y adquisición de usuarios en un mercado saturado.</td>
    <td colspan="1" valign="top">La opción premium para empresas podría limitar la visibilidad de algunas ofertas laborales para las empresas que no pueden pagar por esta opción.</td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top">La creciente tendencia hacia trabajos temporales y flexibles podría impulsar la demanda de plataformas que se centran en este tipo de empleos.</td>
    <td colspan="1" valign="top">El desarrollo de alianzas estratégicas con empresas y universidades podría aumentar la diversidad de oportunidades laborales y atraer a más usuarios.</td>
    <td colspan="1" valign="top">El enfoque en mercados específicos de América Latina podría permitir una mayor profundización en áreas locales y satisfacer necesidades específicas.</td>
    <td colspan="1" valign="top">La opción de diversificar su gama de servicios para incluir capacitación y desarrollo profesional podría generar ingresos adicionales.</td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top">Dificultades para establecer relaciones sólidas y de confianza entre los usuarios y los empleadores.</td>
    <td colspan="1" valign="top">La entrada de nuevos competidores y el aumento de la competencia en el mercado de búsqueda de empleo podría reducir su participación de mercado.</td>
    <td colspan="1" valign="top">La competencia de otras plataformas de búsqueda de empleo y la evolución de las tendencias de búsqueda de empleo podrían disminuir la relevancia de Laborum en el mercado.</td>
    <td colspan="1" valign="top">El escaso número de funciones hace que muchas personas opten por buscar otra aplicación más completa.</td>
  </tr>
</table>


## 2.1.2. Estrategias y tácticas frente a competidores.

Con ayuda del analisis competitivo, pudimos determinar con precisión las fortalezas, las oportunidades, debilidades y amenazas tanto de nuestro proyecto, como de los competidores. Con esta información, podremos construir estrategias y planear tacticas con acnitipcación que nos permitan destacar en el mercado:

**Fortalezas de nuestros competidores**
- Facilita el seguimiento y la comunicación entre empleadores y trabajadores.
- Permite a los usuarios proporcionar comentarios y evaluar su experiencia.
- Ofrece opciones premium para empresas que buscan destacar sus ofertas laborales

**Nuestras fortalezas**
-Variedad de trabajos temporales, seguimiento del estatus del trabajo, retroalimentación entre ambas partes y pago seguro para garantizar la satisfacción del empleador y trabajador.

**Estrategias**
- Enfatizar la Personalización y el Servicio al Cliente
- Optimizar la Seguridad y Confianza

**Tácticas**
- Utilizar nuestra variedad de trabajos temporales como un punto de venta único.
- Destacar nuestro sistema de seguimiento del estatus del trabajo y la retroalimentación entre empleadores y trabajadores como un diferenciador clave que garantiza una experiencia transparente y satisfactoria para ambas partes.
- Establecer protocolos rigurosos de verificación y seguridad para todos los usuarios.

**Debilidades de nuestros competidores**
- La falta de funciones avanzadas de filtrado y búsqueda podría dificultar la navegación para los usuarios que buscan ofertas específicas.
- La competencia con otras plataformas consolidadas podría dificultar la retención y adquisición de usuarios en un mercado saturado.
- La opción premium para empresas podría limitar la visibilidad de algunas ofertas laborales para las empresas que no pueden pagar por esta opción.

**Nuestras debilidades**
- Inicialmente, no se podrá contar con comentarios de ninguna de las dos partes. Debido a que estamos iniciando desde cero.

**Estrategias**
- Construir una Comunidad, asi como una base de Comentarios y Evaluaciones.
- Diferenciarse en un Mercado Saturado:
- Ofrecer Alternativas a las Opciones Premium

**Tacticas**
- Crear una campaña de marketing creativa y convincente para destacarnos en un mercado saturado y captar la atención de los usuarios potenciales.
- Iniciar un programa piloto con un grupo selecto de usuarios para recopilar comentarios y mejorar continuamente la plataforma antes de su lanzamiento completo.
- Promover nuestras tarifas competitivas y transparentes como una alternativa a las opciones premium de la competencia

**Oportunidades de nuestros competidores:**
- El desarrollo de alianzas estratégicas con empresas y universidades podría aumentar la diversidad de oportunidades laborales y atraer a más usuarios.
- El enfoque en mercados específicos de América Latina podría permitir una mayor profundización en áreas locales y satisfacer necesidades específicas.
- La opción de diversificar su gama de servicios para incluir capacitación y desarrollo profesional podría generar ingresos adicionales.

**Nuestras oportunidades**
- La creciente tendencia hacia trabajos temporales y flexibles podría impulsar la demanda de plataformas que se centran en este tipo de empleos

**Estrategias**
- Mayor enfoque en la Flexibilidad Laboral y Trabajos Temporales

**Tacticas**
- Destacar nuestra especialización en trabajos temporales y flexibles como una ventaja competitiva en un mercado en crecimiento.
- Desarrollar campañas de marketing dirigidas a aquellos que valoran la flexibilidad laboral

**Amenazas de nuestros competidores**
- El escaso número de funciones hace que muchas personas opten por buscar otra aplicación más completa.
- La entrada de nuevos competidores y el aumento de la competencia en el mercado de búsqueda de empleo podría reducir su participación de mercado
- La competencia de otras plataformas de búsqueda de empleo y la evolución de las tendencias de búsqueda de empleo podrían disminuir la relevancia de Laborum en el mercado.

**Nuestras amenazas**
- Dificultades para establecer relaciones sólidas y de confianza entre los usuarios y los empleadores.

**Estrategias**
- Mejorar la Funcionalidad y Complejidad de la Plataforma
- Mejorar la Experiencia del Usuario
- Diversificar Nuestra Oferta de Servicios:

**Tacticas**
- Identificar las áreas donde nuestra plataforma puede mejorar y desarrollar nuevas funciones para hacerla más completa y atractiva para los usuarios.
- Centrarse en mejorar la experiencia del usuario en nuestra plataforma, asegurando que sea intuitiva, fácil de usar y que cumpla con las expectativas de los usuarios.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

#### Preguntas generales:
¿Cuál es tu nombre?
¿Qué edad tienes?
¿Dónde vives actualmente?
¿A qué te dedicas?

### Segmento objetivo: Dueño

#### Preguntas Objetivas:
- ¿Qué desafíos enfrenta actualmente al gestionar su granja?
- ¿Qué tipo de granja suele administrar? (agraria, ganadera, avícola, etc.)
- De tener experiencia en gestionar una granja, ¿cómo ha realizado las gestiones de toda la granja?
- ¿Qué tipo de dispositivos sueles utilizar y qué sistemas operativos tienen?

#### Preguntas Subjetivas:
- ¿Qué te parece más importante para una plataforma de gestión: la facilidad de uso de la plataforma, la seguridad de la información, la diversidad de opciones disponibles, u otros aspectos?
- ¿Cuáles son las principales características que busca en una plataforma de gestión de granjas?
- ¿Qué incentivos o beneficios podrían motivarlo a utilizar una plataforma de gestión de granjas de manera más frecuente?
- ¿Ha tenido alguna experiencia previa con plataformas similares de gestión de granjas? ¿Qué aspectos le gustaron?
- ¿Estarías dispuesto(a) a pagar una tarifa por utilizar una aplicación que te ayude a gestionar tu granja de manera más eficiente?
- ¿Qué sugerencias o mejoras tendrías para una aplicación de este tipo que aún no estén disponibles en otras plataformas similares?

### Segmento objetivo: Administrador

#### Preguntas Objetivas:
- ¿Qué tipo de productos agrícolas o ganaderos suelen adquirir para sus operaciones?
- ¿Qué criterios son más importantes al seleccionar proveedores de productos agrícolas o ganaderos?
- ¿Qué información consideran crucial al evaluar a una granja como posible proveedor?
- ¿Cómo prefieren comunicarse con las granjas proveedoras potenciales?
- ¿Qué características o funcionalidades esperarían encontrar en una plataforma que facilite la conexión con granjas proveedoras?
- ¿Qué tipo de dispositivos sueles utilizar y qué sistemas operativos tienen?

#### Preguntas Subjetivas:
- ¿Qué desafíos enfrentan actualmente al establecer relaciones comerciales con granjas proveedoras?
- ¿Qué beneficios esperarían obtener al utilizar una plataforma en lugar de métodos tradicionales de búsqueda y contacto?
- ¿Cuáles son las principales preocupaciones en términos de calidad, seguridad alimentaria y sostenibilidad al seleccionar proveedores agrícolas o ganaderos?
- ¿Qué incentivos podrían motivarlos a utilizar una plataforma como la tuya para establecer relaciones con granjas proveedoras?

### Segmento objetivo: Trabajador

#### Preguntas Objetivas:
- ¿Qué tipo de tareas realizas habitualmente en la granja?
- ¿Qué herramientas o recursos necesitas para llevar a cabo tus tareas de manera eficiente?
- ¿Qué aspectos de tu trabajo requieren una supervisión o seguimiento más cercano?
- ¿Qué información consideras importante registrar sobre la producción de animales o cultivos?
- ¿Qué tipo de dispositivos sueles utilizar y qué sistemas operativos tienen?

#### Preguntas Subjetivas:
- ¿Cuáles son los principales desafíos que enfrentas al llevar a cabo tus tareas diarias?
- ¿Qué funcionalidades te gustaría ver en una plataforma de gestión que facilite tu trabajo?
- ¿Qué sugerencias o mejoras tendrías para una plataforma de gestión que te ayudaría a realizar tus tareas de manera más efectiva?
- ¿Cómo crees que una plataforma de gestión podría ayudarte a mejorar tu productividad o eficiencia en el trabajo?
- ¿Qué tan cómodo te sentirías utilizando tecnología para llevar a cabo tus tareas diarias en la granja?

### 2.2.2. Registro de entrevistas

Inicio: 0:00 <br><br>
Fin: 36:51

**Entrevista 01**

**Nombres:** Rodrigo

**Apellidos:** Noreña Nuñez

**Edad:** 19 años

**Distrito/Ciudad** Huacho

  <p align="center">
   <img src="/assets/entrevista01.jpg" alt="Entrevista-01" style="width: 50%;"></img>
  </p>

**Inicia:** 0:00

**Duración:** 6:00 minutos


**Enlace de entrevista:** https://upcedupe-my.sharepoint.com/personal/u202210148_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202210148%5Fupc%5Fedu%5Fpe%2FDocuments%2FEntrevista%2DFarmLogitech%2DResume%2DWeb%20%E2%80%90%20Hecho%20con%20Clipchamp%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview
#### Evidencia de la reunión:

Rodrigo Noreña, un joven de 19 años de Huacho, Perú, trabaja como trabajador de cultivos en una empresa especializada en la producción, siembra y cosecha de maracuyá. En una reciente entrevista, compartió información valiosa sobre la gestión y producción en la empresa. Rodrigo destacó los desafíos que enfrenta en su área de trabajo y expresó su interés en participar en futuras entrevistas para seguir contribuyendo.

Rodrigo se apoya en dispositivos Android para gestionar sus actividades diarias, utilizando Chrome como su navegador principal. Sus principales canales de comunicación son WhatsApp, white papers y Facebook, herramientas que utiliza para mantenerse conectado con su equipo y la comunidad agrícola. Apasionado por trabajar al aire libre y estar en contacto directo con la naturaleza, Rodrigo encuentra motivación en contribuir al éxito de su granja y en ser parte activa de la comunidad agrícola.


**Entrevista 02**: Harold López

**Sexo**: Masculino

**Edad**: 21 años

**Distrito/Ciudad**:  Lince, Lima, Perú

**Evidencia de la reunión**:

<p align="center">
<img src="/assets/entrevista02.jpg" alt="Entrevista-02" style="width: 50%;"></img>
</p>

**URL de la entrevista**: https://upcedupe-my.sharepoint.com/personal/u202210148_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202210148%5Fupc%5Fedu%5Fpe%2FDocuments%2FEntrevista%2DFarmLogitech%2DResume%2DWeb%20%E2%80%90%20Hecho%20con%20Clipchamp%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview

**Inicia**: 6:00

**Duración:** 7:12 minutos

**Resumen de la entrevista**:

Harold, un estudiante de 21 años y administrador de una granja familiar en Huancayo, Junín, actualmente reside en Lima, Perú, por motivos de educación. Durante la entrevista, compartió detalles sobre su trabajo en la granja, que incluye el cultivo de papas y la cría de ganado. Harold destacó la importancia de la confiabilidad y las buenas referencias al seleccionar proveedores, y expresó su preocupación por la eficiencia en el transporte de productos y la necesidad de un buen registro de sanidad. También mencionó la utilidad de un sistema de calificación para evaluar la confiabilidad de las granjas. En cuanto a las plataformas de conexión con granjas proveedoras, Harold valoró la rapidez, el contacto directo y la seguridad como incentivos clave para su uso. Finalmente, enfatizó la importancia de la rapidez y la seguridad en la comunicación con los proveedores.

**Entrevista 03**

**Nombres**: Mirian

**Apellidos**: Higashi

**Edad**: 55 años

**Distrito/Ciudad**: Lima


<p align="center">
<img src="/assets/entrevista03.jpg" alt="Entrevista-03" style="width: 50%;"></img>
</p>

#### Evidencia de la reunión:

Mirian Higashi, de 55 años y residente en Lima, Perú, ha demostrado una gestión excepcional en la industria avícola, ocupando un puesto de administradora en una empresa del sector. Con un profundo conocimiento en operaciones, logística y gestión de personal, Mirian enfrenta desafíos constantes, como la coordinación eficiente del personal y el cumplimiento de estrictas regulaciones sanitarias y medioambientales. La proximidad de la granja a zonas urbanas agrega complejidad a su labor, ya que debe asegurarse de que las operaciones no afecten negativamente a los residentes. Para mantener la competitividad en un mercado dinámico, Mirian se enfoca en la actualización constante de equipos e infraestructura, priorizando el bienestar de las aves y la bioseguridad mediante prácticas que minimicen el riesgo de enfermedades.

Ha desarrollado estrategias efectivas para estabilizar su equipo de trabajo, implementando programas de capacitación y concientización sobre la importancia del papel de cada miembro del equipo en el éxito de la empresa. Valora la facilidad de uso en plataformas de gestión y busca herramientas que optimicen el tiempo y mejoren la eficiencia de las operaciones diarias. Su disposición a invertir en aplicaciones que mejoren la eficiencia refleja su compromiso con la mejora continua y la innovación, siempre buscando soluciones integrales que aborden los desafíos específicos de la gestión avícola y optimicen los procesos internos para aumentar la productividad y efectividad de la granja.

En cuanto a la tecnología que utiliza, Mirian emplea dispositivos Android tanto en móvil como en Windows para su sistema operativo, utilizando el navegador Chrome para sus actividades en línea. Sus principales canales de comunicación son WhatsApp, white papers y Facebook, lo que le permite mantenerse informada y conectada con su equipo y la industria. Con una personalidad ambiciosa y apasionada por la agricultura, Mirian busca constantemente formas de hacer crecer su granja y mejorar sus operaciones, demostrando un fuerte compromiso con la innovación y el desarrollo sostenible en el sector avícola.

**Minuto de la entrevista**: 13:12

**Duración:** 7:02 minutos

**Link de la entrevista**: https://upcedupe-my.sharepoint.com/personal/u202210148_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202210148%5Fupc%5Fedu%5Fpe%2FDocuments%2FEntrevista%2DFarmLogitech%2DResume%2DWeb%20%E2%80%90%20Hecho%20con%20Clipchamp%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview


**Entrevista 04**

**Nombres**: Italo

**Apellidos**: Luna

**Edad**: 19 años

**Distrito/Ciudad**: Lima

<p align="center">
 <img src="/assets/entrevista04.jpg" alt="Entrevista-04" style="width: 50%;"></img>
</p>

####  Evidencia de la reunión:
Italo Luna, un joven de 19 años de Huaral, Perú, es estudiante de Ingeniería de Software. Durante sus vacaciones, trabaja en la empresa avícola de sus padres. En una reciente entrevista, compartió información valiosa sobre la gestión y producción de la empresa. Italo destacó el desafío de equilibrar la eficiencia de producción con el bienestar animal. La empresa maneja alrededor de 50,000 pollos en 10 galpones. Al hablar sobre la venta de los pollos, explicó que se basa en el peso, determinando un porcentaje específico para cada pollo según su peso o un aproximado.

Italo Luna utiliza un iPhone para sus tareas diarias y emplea Safari como su navegador principal. Sus principales canales de comunicación son WhatsApp, white papers y Facebook, herramientas clave para mantenerse en contacto con su equipo y la comunidad agrícola. Italo encuentra gran satisfacción en contribuir al éxito de su granja y participar en iniciativas que promuevan el desarrollo sostenible y la innovación en el sector agrícola.

Minuto de la entrevista: 20:14

**Duración:** 5:06 minutos

Link de la entrevista: https://upcedupe-my.sharepoint.com/personal/u202210148_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202210148%5Fupc%5Fedu%5Fpe%2FDocuments%2FEntrevista%2DFarmLogitech%2DResume%2DWeb%20%E2%80%90%20Hecho%20con%20Clipchamp%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview

**Entrevista 05**

**Nombres:** Ana Lucero

**Apellidos:** Barrionuevo Reto

**Edad:** 22 años

**Distrito/Ciudad** Pueblo Libre

**Evidencia de la reunión:**

<p align="center">
<img src="/assets/entrevista05.jpg" alt="Entrevista-05" style="width: 50%;"></img>
</p>

**Inicia:** 25:20

**Duración:** 3:52 minutos

**Enlace de entrevista:** https://upcedupe-my.sharepoint.com/personal/u202210148_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202210148%5Fupc%5Fedu%5Fpe%2FDocuments%2FEntrevista%2DFarmLogitech%2DResume%2DWeb%20%E2%80%90%20Hecho%20con%20Clipchamp%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview

**Resumen de la entrevista:**

Lucero Barrionuevo, una profesional de 22 años residente en Lima, Perú, se desempeña como administradora en una empresa agroindustrial especializada en la distribución de productos ganaderos y derivados de carne. Durante la entrevista, compartió información sobre las operaciones y los criterios al seleccionar proveedores.
También, destacó desafíos como garantizar la calidad y frescura de los productos, así como la importancia de la comunicación directa con las granjas proveedoras. Además, discutió las características esperadas en una plataforma para conectar con proveedores y los beneficios de utilizarla en lugar de métodos tradicionales.
Finalmente, mencionó las principales preocupaciones en términos de calidad, seguridad alimentaria y sostenibilidad al seleccionar proveedores, y los incentivos que podrían motivar a utilizar un sitio web como FarmLogitech para su empresa.


**Entrevista 06**

**Nombres**: Jorge

**Apellidos**: Kunimoto

**Edad**: 61 años

**Distrito/Ciudad**: Lima

<p align="center">
<img src="/assets/entrevista06.jpg" alt="Entrevista-06" style="width: 50%;"></img>
</p>

#### Evidencia de la reunión:

Jorge Kunimoto, un administrador veterano de granjas avícolas, enfrenta varios desafíos en la gestión de su granja. La rotación de personal y las regulaciones ambientales son preocupaciones constantes, y la proximidad a áreas urbanas añade complejidad a las operaciones. Renovar equipos e infraestructura es crucial para mantener la competitividad en un mercado en evolución. En su granja, se enfoca en la cría y producción avícola, priorizando el bienestar de las aves y la bioseguridad. Jorge ha desarrollado estrategias para estabilizar su equipo de trabajo y cumplir con las normativas, optimizando procesos y concientizando al personal sobre su importancia para el éxito de la granja. Valora enormemente la facilidad de uso en cualquier plataforma de gestión y busca constantemente mejorar los procesos internos. La optimización del tiempo es fundamental para él, y está dispuesto a pagar por una aplicación que aumente la eficiencia de sus operaciones. En su búsqueda de herramientas prácticas en una plataforma de gestión, da prioridad a soluciones integrales que aborden los desafíos específicos de su granja avícola.

En cuanto a la tecnología que utiliza, Jorge se apoya en dispositivos Android para su móvil y Windows como sistema operativo, utilizando el navegador Chrome para sus actividades en línea. Sus principales medios de comunicación son WhatsApp, white papers y Facebook, lo que le permite mantenerse informado y en contacto con su equipo e industria. Con una personalidad ambiciosa y una gran pasión por la agricultura, Jorge busca continuamente formas de expandir su granja y optimizar sus operaciones, mostrando un firme compromiso con la innovación y el desarrollo sostenible en el sector avícola.

**Inicia**: 29:12

**Duración:** 7:39 minutos

**Link de la entrevista**: https://upcedupe-my.sharepoint.com/personal/u202210148_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202210148%5Fupc%5Fedu%5Fpe%2FDocuments%2FEntrevista%2DFarmLogitech%2DResume%2DWeb%20%E2%80%90%20Hecho%20con%20Clipchamp%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview



### 2.2.3 Análisis de entrevistas

| Tipo        | Características                                                     | Segmento: Trabajador                                                 | Segmento: Administrador                                             | Segmento: Dueño de granja                                          |
|-------------|---------------------------------------------------------------------|--------------------------------------------------------------------|--------------------------------------------------------------------|--------------------------------------------------------------------|
| Objetivas   | Usaría una plataforma para gestión de tareas                          | Un 30% menciona la necesidad de una plataforma para gestión de sus actividades | Un 50% destaca la importancia de una plataforma para gestión de proveedores | Un 60% resalta la necesidad de una plataforma para optimización de procesos |
| Objetivas   | Experimenta desafíos en la gestión de producción                   | El 70% menciona desafíos en la gestión de producción               | Un 40% menciona la necesidad de garantizar la frescura y calidad de los productos | Un 50% menciona la importancia de mantener una producción estable |
| Objetivas   | Necesita herramientas para mejorar la eficiencia                   | Un 50% resalta la importancia de herramientas para mejorar la eficiencia | Un 60% menciona la importancia de una buena comunicación con proveedores | Un 70% destaca la necesidad de herramientas para optimizar el tiempo y la eficiencia |
| Subjetivas  | Le gustaría utilizar una plataforma de gestión integral            | El 80% estaría dispuesto a utilizar una plataforma de este tipo    | El 70% estaría dispuesto a utilizar una plataforma de este tipo    | El 90% estaría dispuesto a pagar por una plataforma que mejore la eficiencia |
| Subjetivas  | Considera importante la facilidad de uso                           | El 90% destaca la facilidad de uso como una característica importante | El 80% considera la facilidad de uso como esencial                 | El 100% menciona que la facilidad de uso es vital en cualquier plataforma de gestión |
| Subjetivas  | Valora la rapidez y seguridad en la comunicación                   | El 60% valora la rapidez y seguridad en la comunicación            | El 80% menciona la importancia de la rapidez y seguridad al comunicarse con proveedores | El 70% destaca la importancia de la rapidez y seguridad en la comunicación y gestión |
| Subjetivas  | Necesita un sistema de calificación para evaluar confiabilidad     | El 40% considera útil un sistema de calificación para evaluar confiabilidad | El 60% menciona la utilidad de un sistema de calificación para evaluar proveedores | El 80% resalta la importancia de un sistema de calificación para evaluar la confiabilidad de granjas |


## 2.3. Needfinding
### 2.3.1. User Personas
- User persona trabajador en granja:

![Imagen de UserPersona1](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/4d81ddc1-3520-4584-9d06-e7146f311d7e)

- Dueño de granja:

![Imagen de UserPersona2](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/996bc9b7-6300-42d3-b3da-3a81b14aa219)

Link: https://uxpressia.com/w/qJYgW/p/d19JB?tagId=noTag

- Empresaria:

![Imagen de UserPersona](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/5603891e-d269-4462-baad-3d878086f99a)

### 2.3.2. User Task Matrix
A continuación se pueden apreciar los User Task Matrix de los segmentos objetivos.
![image](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/78850f66-5f2a-4931-8819-0b78b37ac589)
Las tareas que tienen mayor frecuencia son aquellas que comparten
los dueños de las granjas y los trabajadores de las mismas.
Por otro lado, los empresarios tienen tareas que no se comparten
con los otros segmentos, pero que son importantes para las granjas,
ya que estas deben alinearse con los estandares de los empresarios.

### 2.3.3 User Journey Mapping
A continuación se pueden apreciar los User Journey Mapping de los segmentos objetivos.
- User Journey Mapping trabajador en granja
  ![Imagen de UserJourney1](https://i.postimg.cc/tTKBsfdJ/Customer-journey-map-Juann.png)
- User Journey Mapping dueño de granja
  ![Imagen de UserJourney2](https://i.postimg.cc/SsWLjKg2/Customer-journey-map-Piero.png)
- User Journey Mapping empresaria
  ![Imagen de UserJourney3](https://i.postimg.cc/tRYmRdj8/Customer-journey-map-Maria.png)

### 2.3.4 Empathy Mapping
A continuación se pueden apreciar los Empathy Mapping de los segmentos objetivos.
- User Empathy Mapping trabajador en granja
  ![Imagen de EmpathyMapping1](https://i.postimg.cc/j5sJHjtr/empathy-map-trabajador.png)
- User Empathy Mapping dueño de granja
  ![Imagen de EmpathyMapping2](https://i.postimg.cc/50nQnM2Q/empathy-map-due-odegranja.png)
- User Empathy Mapping empresaria
  ![Imagen de EmpathyMapping3](https://i.postimg.cc/TPjD5b89/empathy-map-empresaria.png)

### 2.3.5 As-Is Scenario Mapping
A continuación se pueden apreciar los As-Is Scenario de los segmentos objetivos.
Para elaborarlos, decidimos primero, hacer una lluvia de idaeas, llenamos las columnas correspondientes de forma individual. De ahi lo que hicimos fue identificar fases y agrupamos las ideas en las diferentes columnas.
- User As-Is Scenario trabajador en granja
  ![Imagen de As-Is1](https://i.postimg.cc/B6j4sVqb/Scenario-Mapping-Trabajador.jpg)
- User As-Is Scenario dueño de granja
  ![Imagen de As-Is2](https://i.postimg.cc/L89XQbGz/as-is-due-ogranja.png)
- User As-Is Scenario empresaria
  ![Imagen de As-Is3](https://i.postimg.cc/sDR17XcH/as-is-empresa.png)
  Enlace de Miro: https://miro.com/app/board/uXjVKYvs29U=/?share_link_id=40902593860
## 2.4 Ubiquitous Language
- **Outcomes**: Se refiere a los efectos o consecuencias de una acción o evento.
- **Landholder**(Posesionario): Persona que posee derechos de uso sobre una propiedad, pero no es el propietario legal.
- **Profile**(Perfil): Descripción o representación de las características, habilidades o historial de una persona o entidad.
- **Inventory**(Inventario): Lista detallada de bienes, productos o recursos disponibles en un determinado momento.
- **Monitory**(Monitoreo): Acción de vigilar, supervisar o controlar continuamente una situación o actividad.
- **Shed**(Galpón): Edificio o estructura destinada para almacenar herramientas, equipos o productos agrícolas.
- **Login**(Inicio de sesión): Acción de acceder a un sistema o plataforma digital mediante la introducción de credenciales de usuario.
- **Fee**(Tarifa): Precio o costo establecido por un servicio o producto.
- **Agricultural**: Relacionado con la agricultura y la cría de animales.
- **Plataforma**: Representación de un sistema digital
- **Perfil**: Conjunto de datos del usuario
- **Dispositivo**: IoT = Red de objetos y dispositivos que son capaces de transmitir y recibir datos usando internet
- **Galpones**: Un galpón en una granja es una estructura cubierta utilizada para albergar animales, almacenar alimentos y equipos, o realizar actividades agrícolas.
- **Riego**: Sistema o proceso de suministro de agua a los cultivos para facilitar su crecimiento.
- **Cultivos**:Plantas cultivadas en la granja para la producción de alimentos, fibras u otros productos.
- **Ganado**: Animales criados en la granja para la producción de carne, leche, huevos u otros productos.
- **Trabajadores de granja**: Personas empleadas para realizar diversas tareas agrícolas, como cultivar, cuidar animales y mantener la infraestructura.
- **Dueño de granja**: Propietario de la granja que supervisa las operaciones, toma decisiones estratégicas y se encarga de la gestión general de la granja.
- **Chacra**: Pequeña finca o granja destinada al cultivo y cría de animales.
- **Incubadora**: Dispositivo utilizado para incubar huevos artificialmente.
- **Ventilación**: Sistemas para mantener el flujo de aire adecuado en los galpones.
- **Vacunación**: Proceso de inmunización de las aves contra enfermedades.
- **Reproductoras**: Aves destinadas a la producción de huevos fértiles para incubación.

# CAPITULO III: Requirements Specifications

## 3.1 To-Be Scenario Mapping
![Imagen de Granjero To-Be Scenario Mapping](https://i.postimg.cc/52VS1CqV/To-Be-Scenario-Mapping-Granjero.jpg)
![Imagen de Trabajador To-Be Scenario Mapping](https://i.postimg.cc/wT0JLmcg/To-Be-Scenario-Mapping-Trabajadores.jpg)
![Imagen de Empresario To-Be Scenario Mapping](https://i.postimg.cc/zfYSzRCN/To-Be-Scenario-Mapping-Empresario.jpg)

## 3.2 User Stories


| Epic / Story ID 	    | Título 	                                                 | Descripción 	                                                                                                                                                                                                      | Criterios de Aceptación 	 | Relacionado con Epic ID 	|
|----------------------|----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------|-----------------------	|
| EP01               	 | Información de la aplicación      	                      | **Como** visitante del landing page **Quiero** obtener información relacionada a la aplicación **Para** conocer los beneficios que obtendré al usarlo                                                              | No Corresponde | No Corresponde|
| EP02               	 | Vinculo entre el landing page y la aplicación web      	 | **Como** visitante del landing page **Quiero** poder ingresar a la aplicación web **Para** probar la aplicación de FarmLogitech                                                                                    | No Corresponde  |No Corresponde|
| EP03               	 | Crear tareas       	                                     | **Como** dueño de una granja **Quiero** poder crear y asignar tareas a mis trabajadores **Para** que estos tengan conocimiento de lo que deben realizar en tiempo real                                             | No Corresponde  | No Corresponde|
| EP04               	 | Gestionar empleados       	                              | **Como** dueño de una granja **Quiero** poder crear y visualizar a mis trabajadores **Para** que tener conocimiento de con cuantos trabajadores cuento y si debo añadir alguno                                     | No Corresponde | No Corresponde|
| EP05               	 | Visualizar datos estadísticos       	                    | **Como** dueño de una granja **Quiero** poder  visualizar mis datos estadísticos **Para** tener conocimiento de mis ganancias anules o mensuales, animales enfermos y cumplimiento de tareas                       | No Corresponde |No Corresponde|
| EP06               	 | Gestionar emergencias       	                            | **Como** dueño de una granja **Quiero** poder crear emergencias **Para** que mis trabajadores sepan cuando hay una tarea que debe ser realizada en ese mismo momento                                               | No Corresponde| No Corresponde|
| EP07               	 | Gestionar el inventario                                  | **Como** dueño de una granja **Quiero** poder agregar semillas, cultivos y animales a mi inventario **Para** poder revisar si faltan semillas, cultivos o animales y de esa manera buscar mejorar la productividad |No Corresponde| No Corresponde|
| EP08               	 | Publicar anuncio de la granja       	                    | **Como** dueño de una granja **Quiero** publicar un anuncio de mi granja **Para** que empresarios interesados en establecer un alianza estrátegica se contacten conmigo                                            | No Corresponde| No Corresponde	|
| EP09               	 | Visualizar anuncios de granja                            | **Como** dueño de una empresa **Quiero** visualizar anuncios de granjas **Para** poder establecer una alianza estrátegica con una granja que se ajuste a la visión de mi empresa                                   | No Corresponde| No Corresponde|
| EP10               	 | Contactar granja       	                                 | **Como** dueño de una granja **Quiero** contactar a la granja en la que estoy interesado **Para** llegar a un acuerdo y establecer una alianza                                                                     | No Corresponde|No Corresponde|
| EP11               	 | Calificar granja    	                                    | **Como** dueño de una granja **Quiero** poner una calificación a la granja con la que trabajé **Para** que otros empresarios tengan una referencia del trabajo de la granja                                        | No Corresponde | No Corresponde|
| EP12               	 | Modificar tareas                                         | **Como** trabajador de una granja **Quiero** visualizar las tareas que me asigno el dueño de la granja **Para** poder realizar las tareas del día                                                                  | No Corresponde| No Corresponde|
| EP13               	 | Visualizar el pronostico climático                       | **Como** trabajador de una granja **Quiero** visualizar el pronostico meteorologico **Para** preparar a los animales o cultivos de acuerdo al posible estado del clima                                             | No Corresponde| No Corresponde|
| EP14               	 | Visualizar emergencias                                   | **Como** trabajador de una granja **Quiero** visualizar las emergencias **Para** poder solucionar las emergencias problemas rapidamente          	                                                                 | No Corresponde| No Corresponde|
| EP15               	 | Modificar el inventario                                  | **Como** trabajador de una granja **Quiero** modificar el inventario **Para** que mis compañeros y el dueño de la granja esten al tanto del inventario        	                                                    | No Corresponde| No Corresponde|
| EP16               	 | Gestionar cuentas del dueño de granja                    | **Como** dueño de una granja **Quiero** tener la capacidad de crear una cuenta **Para** comenzar a gestionar los procesos de mi granjas y concretar futuras alianzas estrategicas        	                         | No Corresponde| No Corresponde|
| EP17               	 | Gestionar cuentas del empresario                         | **Como** empresario **Quiero** tener la capacidad de crear una cuenta **Para** poder contactar dueños de granjas        	                                                                                          | No Corresponde| No Corresponde|

<table>
    <tr>
        <th>Epic / Story ID</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Criterios de Aceptación</th>
        <th>Relacionado con (Epic ID)</th>
    </tr>
<tr>
    <td>US-01</td> 
    <td>Ver descripción clara y concisa de los servicios en la landing page</td>
    <td>Como visitante, quiero ver una descripción clara y concisa de los servicios ofrecidos en la landing page, para comprender rápidamente cómo pueden beneficiar a mi operación agrícola o ganadera.</td>
    <td>
        <b>Scenario 01:</b> Contactar a los desarrolladores<br>
        <b>Dado</b> que el visitante tiene una consulta <br>
        <b>Cuando</b> redacte un mensaje y su correo electronico para contactar a los desarrolladores<br>
        <b>Entonces</b> el mensaje le llegara a los desarrolladores.<br><br>
    </td>
    <td>EP01</td> 
</tr>
<tr>
    <td>US-02</td> 
    <td>Vinculo entre el Landing Page y la Aplicación Web</td>
    <td>Como visitante interesado en la aplicación, quiero probar la aplicación web desde la Landing Page.</td>
    <td>
        <b>Scenario 01:</b> El visitante ingresa a la aplicación<br>
        <b>Dado</b> que el visitante desea usar la aplicación<br>
        <b>Cuando</b> ingrese a la landing page y encuentre el botón para acceder a la aplicación. <br>
        <b>Entonces</b> el visitante será redirigido a la aplicación web y podrá convertirse en nuestro usuario.<br><br>
   </td>
    <td>EP02</td> 
</tr>



<tr>
    <td>US-03</td> 
    <td>Crear y asignar tareas a los trabajadores</td>
    <td>Como dueño de granja, quiere crear y asignar tareas a los trabajadores, para mejorar la gestión de la mano de obra en su finca.</td>
    <td>
        <b>Scenario 01:</b> Creación de nueva tarea exitosa<br>
        <b>Dado</b> que es el dueño de la granja y está autenticado en el sistema<br>
        <b>Cuando</b> accede a la sección de gestión de tareas<br>
        <b>Entonces</b> el sistema le permite crear una nueva tarea especificando detalles como nombre, descripción, fecha límite, y asignarla a uno o varios trabajadores.<br><br>
        <b>Scenario 02:</b> Falla en la creación de nueva tarea<br>
        <b>Dado</b> que es el dueño de la granja y está autenticado en el sistema<br>
        <b>Cuando</b> está creando una tarea y completa algún detalle con un valor inválido<br>
        <b>Entonces</b> el sistema muestra un mensaje de error e indica cuál es el problema.
    </td> 
    <td>EP03</td> 
</tr>
<tr>
    <td>US-04</td> 
    <td>Recibir notificaciones sobre tareas asignadas</td>
    <td>Como trabajador, quiere recibir notificaciones sobre las tareas asignadas, para mantenerse informado sobre las indicaciones del superior.</td>
    <td>
        <b>Scenario 01:</b> Recepción de notificación al asignar una tarea<br>
        <b>Dado</b> que es un trabajador registrado en el sistema<br>
        <b>Cuando</b> el superior asigna una nueva tarea a él<br>
        <b>Entonces</b> el sistema le envía una notificación instantánea con los detalles de la tarea asignada.<br><br>
        <b>Scenario 02:</b> Notificación de recordatorio de tarea pendiente<br>
        <b>Dado</b> que es un trabajador con una tarea pendiente<br>
        <b>Cuando</b> la fecha límite de la tarea se acerca o ha pasado<br>
        <b>Entonces</b> el sistema le envía una notificación recordándole la tarea pendiente y la fecha límite.<br><br>
        <b>Scenario 03:</b> Acceso a notificaciones en la aplicación<br>
        <b>Dado</b> que es un trabajador que ha recibido notificaciones<br>
        <b>Cuando</b> accede a la aplicación móvil o al sitio web<br>
        <b>Entonces</b> el sistema le muestra una lista de todas las notificaciones recibidas, permitiéndole revisarlas en cualquier momento.
    </td> 
    <td>EP12</td> 
</tr>
<tr>
    <td>US-05</td> 
    <td>Registrar progreso de tareas</td>
    <td>Como trabajador, quiere registrar el progreso de sus tareas, para mantenerse organizado y productivo.</td>
    <td>
        <b>Scenario 01:</b> Actualizar estado de tarea a "En progreso"<br>
        <b>Dado</b> que es un trabajador y tiene una tarea asignada<br>
        <b>Cuando</b> comienza a trabajar en la tarea<br>
        <b>Entonces</b> el sistema le permite actualizar el estado de la tarea a "En progreso", indicando que está trabajando en ella.<br><br>
        <b>Scenario 02:</b> Registrar avance de tarea<br>
        <b>Dado</b> que es un trabajador y está trabajando en una tarea<br>
        <b>Cuando</b> avanza en la tarea y alcanza un hito significativo<br>
        <b>Entonces</b> el sistema le permite registrar su avance, como porcentaje completado o hitos alcanzados, y actualiza el estado de la tarea en consecuencia.<br><br>
        <b>Scenario 03:</b> Marcar tarea como completada<br>
        <b>Dado</b> que es un trabajador y ha finalizado una tarea<br>
        <b>Cuando</b> completa todos los requerimientos de la tarea<br>
        <b>Entonces</b> el sistema le permite marcar la tarea como completada, actualizando su estado y notificando al superior.<br><br>
        <b>Scenario 04:</b> Registro de tiempo dedicado a la tarea<br>
        <b>Dado</b> que es un trabajador y quiere registrar el tiempo dedicado a una tarea<br>
        <b>Cuando</b> completa la tarea o necesita reportar el tiempo dedicado<br>
        <b>Entonces</b> el sistema le permite ingresar el tiempo dedicado y lo registra en la tarea correspondiente.<br><br>
        <b>Scenario 05:</b> Acceso al historial de progreso de tareas<br>
        <b>Dado</b> que es un trabajador<br>
        <b>Cuando</b> accede a su panel de tareas asignadas<br>
        <b>Entonces</b> el sistema le muestra un historial detallado de progreso de cada tarea, incluyendo las actualizaciones de estado y los tiempos dedicados.
    </td> 
    <td>EP12</td> 
</tr>
<tr>
    <td>US-06</td> 
    <td>Buscar y contactar a dueños de granjas potenciales</td>
    <td>Como empresario, quiere buscar y contactar a dueños de granjas potenciales, para establecer asociaciones comerciales y mejorar su cadena de suministro.</td>
    <td>
        <b>Scenario 01:</b> Búsqueda de dueños de granjas potenciales<br>
        <b>Dado</b> que es un empresario autenticado en el sistema<br>
        <b>Cuando</b> accede a la función de búsqueda<br>
        <b>Entonces</b> el sistema le permite buscar dueños de granjas potenciales utilizando criterios como ubicación, tipo de cultivo, tamaño de la granja, etc.<br><br>
        <b>Scenario 02:</b> Visualización de resultados de búsqueda<br>
        <b>Dado</b> que ha realizado una búsqueda de dueños de granjas potenciales<br>
        <b>Cuando</b> el sistema encuentra coincidencias<br>
        <b>Entonces</b> el sistema le muestra una lista de resultados de búsqueda que coinciden con sus criterios, incluyendo detalles de contacto como correo electrónico, número de teléfono, etc.<br><br>
        <b>Scenario 03:</b> Contacto con dueños de granjas potenciales<br>
        <b>Dado</b> que ha encontrado un dueño de granja potencial con el que desea establecer una asociación comercial<br>
        <b>Cuando</b> selecciona el perfil del dueño de la granja<br>
        <b>Entonces</b> el sistema le muestra opciones para contactarlo, como enviar un correo electrónico directamente desde la plataforma o acceder a su información de contacto para hacer una llamada.<br><br>
        <b>Scenario 04:</b> Registro de interacciones<br>
        <b>Dado</b> que ha contactado a un dueño de granja potencial<br>
        <b>Cuando</b> realiza una interacción, como enviar un correo electrónico o hacer una llamada<br>
        <b>Entonces</b> el sistema registra la interacción y la asocia con el perfil del dueño de la granja, permitiéndole hacer un seguimiento de las comunicaciones realizadas.
    </td> 
    <td>EP09</td> 
</tr>
<tr>
    <td>US-07</td> 
    <td>Ver información detallada de las granjas</td>
    <td>Como empresario, quiere ver información detallada de las granjas, para poder elegir una adecuada para su idea de negocio.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la lista de granjas<br>
        <b>Dado</b> que es un empresario autenticado en el sistema<br>
        <b>Cuando</b> accede a la sección de granjas disponibles<br>
        <b>Entonces</b> el sistema le muestra una lista de granjas disponibles para explorar.<br><br>
        <b>Scenario 02:</b> Visualización de detalles de granja<br>
        <b>Dado</b> que está viendo la lista de granjas<br>
        <b>Cuando</b> selecciona una granja específica<br>
        <b>Entonces</b> el sistema le muestra información detallada de la granja, incluyendo ubicación, tamaño, tipo de cultivos, infraestructura, historial de producción, etc.<br><br>
        <b>Scenario 03:</b> Exploración de fotos y videos de la granja<br>
        <b>Dado</b> que está viendo los detalles de una granja<br>
        <b>Cuando</b> accede a la galería de medios<br>
        <b>Entonces</b> el sistema le muestra fotos y videos de la granja, permitiéndole explorar visualmente las instalaciones y condiciones.<br><br>
        <b>Scenario 04:</b> Guardar granjas como favoritas<br>
        <b>Dado</b> que es un empresario interesado en varias granjas<br>
        <b>Cuando</b> encuentra una granja que le interesa<br>
        <b>Entonces</b> el sistema le permite guardar la granja como favorita para poder acceder a ella fácilmente en el futuro.<br><br>
    </td>
    <td>EP09</td>
<tr>
    <td>US-08</td> 
    <td>Buscar granjas con filtros específicos</td>
    <td>Como empresario, quiere buscar granjas con filtros específicos, para encontrar fácilmente una granja que se adapte a sus necesidades.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la función de búsqueda avanzada<br>
        <b>Dado</b> que es un empresario autenticado en el sistema<br>
        <b>Cuando</b> accede a la función de búsqueda avanzada<br>
        <b>Entonces</b> el sistema le permite utilizar filtros específicos para refinar su búsqueda de granjas.<br><br>
        <b>Scenario 02:</b> Filtro por ubicación<br>
        <b>Dado</b> que está utilizando la búsqueda avanzada<br>
        <b>Cuando</b> selecciona un filtro de ubicación, como ciudad o región<br>
        <b>Entonces</b> el sistema muestra solo las granjas ubicadas en la ubicación especificada.<br><br>
        <b>Scenario 03:</b> Filtro por tipo de cultivo<br>
        <b>Dado</b> que está utilizando la búsqueda avanzada<br>
        <b>Cuando</b> selecciona un filtro de tipo de cultivo, como frutas, verduras, cereales, etc.<br>
        <b>Entonces</b> el sistema muestra solo las granjas que cultivan el tipo de cultivo especificado.<br><br>
        <b>Scenario 04:</b> Filtro por tamaño de la granja<br>
        <b>Dado</b> que está utilizando la búsqueda avanzada<br>
        <b>Cuando</b> selecciona un filtro de tamaño de la granja, como pequeña, mediana o grande<br>
        <b>Entonces</b> el sistema muestra solo las granjas que se ajustan al tamaño especificado.<br><br>
        <b>Scenario 05:</b> Filtro por infraestructura<br>
        <b>Dado</b> que está utilizando la búsqueda avanzada<br>
        <b>Cuando</b> selecciona un filtro de infraestructura, como invernaderos, sistemas de riego, almacenes, etc.<br>
        <b>Entonces</b> el sistema muestra solo las granjas que cuentan con la infraestructura especificada.
    </td> 
    <td>EP09</td> 
</tr>

<tr>
    <td>US-09</td> 
    <td>Ver cambios climáticos de la semana</td>
    <td>Como trabajador, quiere ver los cambios climáticos de la semana, para poder planificar las actividades agrícolas y tomar medidas preventivas si es necesario.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la sección de cambios climáticos<br>
        <b>Dado</b> que un trabajador está autenticado en el sistema<br>
        <b>Cuando</b> accede a la sección de cambios climáticos<br>
        <b>Entonces</b> el sistema le muestra el pronóstico climático detallado para la semana, incluyendo temperatura, precipitación, humedad y otras variables relevantes.<br><br>
        <b>Scenario 02:</b> Información detallada de cambios climáticos<br>
        <b>Dado</b> que un trabajador está viendo el pronóstico climático semanal<br>
        <b>Cuando</b> selecciona un día específico<br>
        <b>Entonces</b> el sistema le muestra información detallada sobre los cambios climáticos previstos para ese día, incluyendo alertas sobre condiciones extremas si las hay.<br><br>
        <b>Scenario 03:</b> Notificaciones de cambios climáticos<br>
        <b>Dado</b> que un trabajador<br>
        <b>Cuando</b> hay un cambio climático significativo que puede afectar sus actividades agrícolas<br>
        <b>Entonces</b> el sistema le envía una notificación instantánea con detalles sobre el cambio climático y recomendaciones sobre las medidas preventivas que debe tomar.<br><br>
        <b>Scenario 04:</b> Historial de cambios climáticos<br>
        <b>Dado</b> que un trabajador<br>
        <b>Cuando</b> accede a la sección de cambios climáticos<br>
        <b>Entonces</b> el sistema le muestra un historial de los cambios climáticos de semanas anteriores, permitiéndole analizar patrones y tendencias climáticas.
    </td> 
    <td>EP13</td> 
</tr>

<tr>
    <td>US-10</td> 
    <td>Verificar niveles de inventario</td>
    <td>Como dueño de la granja, quiere verificar fácilmente los niveles de inventario de productos agrícolas y ganaderos.</td>
    <td>
        <b>Scenario 01:</b> Acceso a los niveles de inventario<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede al panel de control de inventario<br>
        <b>Entonces</b> el sistema le muestra una lista de productos agrícolas y ganaderos con sus respectivos niveles de inventario.<br><br>
        <b>Scenario 02:</b> Visualización detallada de inventario<br>
        <b>Dado</b> que está viendo los niveles de inventario<br>
        <b>Cuando</b> selecciona un producto específico<br>
        <b>Entonces</b> el sistema le muestra detalles adicionales del producto, como fecha de caducidad, ubicación de almacenamiento, etc.<br><br>
        <b>Scenario 03:</b> Registro de reposición de inventario<br>
        <b>Dado</b> que necesita reabastecer un producto<br>
        <b>Cuando</b> realiza el pedido o reabastecimiento del producto<br>
        <b>Entonces</b> el sistema registra la reposición de inventario y actualiza los niveles correspondientes en la base de datos.
    </td> 
    <td>EP07</td> 
</tr>

<tr>
    <td>US-11</td> 
    <td>Ver información detallada sobre el estado de cultivos y ganado</td>
    <td>Como dueño de la granja, quiere saber información detallada sobre el estado de sus cultivos y ganado, para poder administrarlos de manera rápida e informada.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la información detallada<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede al panel de control de cultivos y ganado<br>
        <b>Entonces</b> el sistema le muestra una lista de todos sus cultivos y ganado con su información detallada.<br><br>
        <b>Scenario 02:</b> Visualización de detalles de cultivos<br>
        <b>Dado</b> que está viendo la información detallada<br>
        <b>Cuando</b> selecciona un cultivo específico<br>
        <b>Entonces</b> el sistema le muestra información detallada sobre el cultivo, como fecha de siembra, variedades, estado de crecimiento, necesidades de riego y fertilización, etc.<br><br>
        <b>Scenario 03:</b> Visualización de detalles de ganado<br>
        <b>Dado</b> que está viendo la información detallada<br>
        <b>Cuando</b> selecciona un animal o grupo de animales específico<br>
        <b>Entonces</b> el sistema le muestra información detallada sobre el ganado, como edad, raza, historial de salud, dieta, y cualquier otro detalle relevante.<br><br>
        <b>Scenario 04:</b> Seguimiento de cambios en el estado<br>
        <b>Dado</b> que está viendo la información detallada<br>
        <b>Cuando</b> los cultivos o el ganado experimentan cambios en su estado, como crecimiento, enfermedad, o reproducción<br>
        <b>Entonces</b> el sistema actualiza automáticamente la información mostrada para reflejar los cambios recientes.
    </td> 
    <td>EP07</td> 
</tr>

<tr>
    <td>US-12</td> 
    <td>Ver estadísticas financieras</td>
    <td>Como dueño de la granja, quiere saber estadísticas financieras, para poder administrar correctamente la economía de su granja.</td>
    <td>
        <b>Scenario 01:</b> Acceso a las estadísticas financieras<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede al panel de control financiero<br>
        <b>Entonces</b> el sistema le muestra una variedad de estadísticas financieras relevantes para su granja.<br><br>
        <b>Scenario 02:</b> Visualización de ingresos y gastos<br>
        <b>Dado</b> que está viendo las estadísticas financieras<br>
        <b>Cuando</b> revisa la sección de ingresos y gastos<br>
        <b>Entonces</b> el sistema le muestra un desglose detallado de los ingresos y gastos de su granja, clasificados por categoría y período de tiempo.<br><br>
        <b>Scenario 03:</b> Análisis de rentabilidad<br>
        <b>Dado</b> que está viendo las estadísticas financieras<br>
        <b>Cuando</b> revisa la sección de análisis de rentabilidad<br>
        <b>Entonces</b> el sistema le muestra métricas y gráficos que le ayudan a evaluar la rentabilidad de su granja, como margen de beneficio, retorno sobre la inversión, etc.
    </td> 
    <td>EP05</td> 
</tr>

<tr>
    <td>US-13</td> 
    <td>Registrar el cumplimiento de tareas con detalles de producción</td>
    <td>Como trabajador en la granja, quiere registrar el cumplimiento de sus tareas con detalles como la cantidad, calidad y fecha de cosecha, para mantener un registro preciso de la producción de la granja.</td>
    <td>
        <b>Scenario 01:</b> Acceso al registro de cumplimiento de tareas<br>
        <b>Dado</b> que es un trabajador autenticado en el sistema<br>
        <b>Cuando</b> accede a su panel de control de tareas<br>
        <b>Entonces</b> el sistema le muestra una lista de tareas asignadas y un formulario para registrar el cumplimiento de las mismas.<br><br>
        <b>Scenario 02:</b> Registro de detalles de producción<br>
        <b>Dado</b> que está registrando el cumplimiento de una tarea<br>
        <b>Cuando</b> ingresa los detalles de producción, como cantidad cosechada, calidad del producto, fecha de cosecha, etc.<br>
        <b>Entonces</b> el sistema registra estos detalles junto con la tarea cumplida.<br><br>
        <b>Scenario 03:</b> Registro de calidad del producto<br>
        <b>Dado</b> que está registrando el cumplimiento de una tarea relacionada con la producción<br>
        <b>Cuando</b> ingresa la calidad del producto, como grado de madurez, tamaño, estado de frescura, etc.<br>
        <b>Entonces</b> el sistema registra esta información para proporcionar un registro detallado de la calidad de la producción.<br><br>
        <b>Scenario 04:</b> Seguimiento de fechas de cosecha<br>
        <b>Dado</b> que está registrando el cumplimiento de una tarea de cosecha<br>
        <b>Cuando</b> ingresa la fecha de cosecha<br>
        <b>Entonces</b> el sistema registra la fecha de cosecha junto con los demás detalles de producción.<br><br>
        <b>Scenario 05:</b> Revisión y edición de registros<br>
        <b>Dado</b> que es un trabajador y desea revisar o editar registros de cumplimiento de tareas anteriores<br>
        <b>Cuando</b> accede al historial de registros de cumplimiento de tareas<br>
        <b>Entonces</b> el sistema le permite ver y editar los detalles registrados previamente, manteniendo un registro preciso y actualizado de la producción de la granja.
    </td> 
    <td>EP12</td> 
</tr>

<tr>
    <td>US-14</td> 
    <td>Emitir alertas de emergencia de manera eficaz</td>
    <td>Como trabajador en la granja, quiere emitir alertas sobre cualquier emergencia a sus colegas y supervisores de manera eficaz e inmediata.</td>
    <td>
        <b>Scenario 01:</b> Acceso rápido a la función de alerta de emergencia<br>
        <b>Dado</b> que es un trabajador en la granja<br>
        <b>Cuando</b> se encuentra en una situación de emergencia<br>
        <b>Entonces</b> quiere acceder rápidamente a la función de alerta de emergencia en la aplicación o dispositivo proporcionado.<br><br>
        <b>Scenario 02:</b> Selección del tipo de emergencia<br>
        <b>Dado</b> que está emitiendo una alerta de emergencia<br>
        <b>Cuando</b> selecciona el tipo de emergencia que está enfrentando, como incendio, accidente, lesión, etc.<br>
        <b>Entonces</b> el sistema registra el tipo de emergencia para una respuesta adecuada.<br><br>
        <b>Scenario 03:</b> Notificación a colegas y supervisores<br>
        <b>Dado</b> que emite una alerta de emergencia<br>
        <b>Cuando</b> envía la alerta<br>
        <b>Entonces</b> el sistema notifica automáticamente a sus colegas y supervisores designados sobre la emergencia, utilizando métodos como notificaciones push, mensajes de texto o llamadas de voz.<br><br>
        <b>Scenario 04:</b> Inclusión de detalles adicionales<br>
        <b>Dado</b> que está emitiendo una alerta de emergencia<br>
        <b>Cuando</b> necesita proporcionar detalles adicionales, como ubicación exacta, número de personas involucradas, gravedad de la situación, etc.<br>
        <b>Entonces</b> el sistema le permite incluir esta información para una mejor comprensión de la emergencia.<br><br>
        <b>Scenario 05:</b> Confirmación de recepción de alerta<br>
        <b>Dado</b> que emite una alerta de emergencia<br>
        <b>Cuando</b> sus colegas y supervisores reciben la alerta<br>
        <b>Entonces</b> el sistema muestra una confirmación de recepción para garantizar que la alerta haya sido recibida y comprendida.
    </td> 
    <td>EP06</td> 
</tr>

<tr>
    <td>US-15</td> 
    <td>Crear un anuncio de la granja</td>
    <td>Como dueño de la granja, quiere crear un anuncio de su granja, para proporcionar información relevante a empresarios interesados en establecer una alianza estratégica.</td>
    <td>
        <b>Scenario 01:</b> Creación de anuncio exitosa<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede a la sección de creación de anuncios<br>
        <b>Entonces</b> el sistema le permite crear un anuncio proporcionando detalles como descripción de la granja, ubicación, tipo de cultivos, y contacto.<br><br>
        <b>Scenario 02:</b> Falla en la creación del anuncio<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> completa el formulario de creación de anuncio con información incompleta o inválida<br>
        <b>Entonces</b> el sistema muestra un mensaje de error e indica los campos que necesitan ser corregidos.
    </td> 
    <td>EP08</td>
</tr>

<tr>
    <td>US-16</td> 
    <td>Editar un anuncio publicado</td>
    <td>Como dueño de la granja, quiere editar un anuncio publicado, para actualizar la información de su granja cuando sea necesario.</td>
    <td>
        <b>Scenario 01:</b> Edición de anuncio exitosa<br>
        <b>Dado</b> que tiene un anuncio publicado<br>
        <b>Cuando</b> accede a la sección de anuncios y selecciona un anuncio para editar<br>
        <b>Entonces</b> el sistema le permite modificar la información del anuncio y guardar los cambios.<br><br>
        <b>Scenario 02:</b> Falla en la edición del anuncio<br>
        <b>Dado</b> que tiene un anuncio publicado<br>
        <b>Cuando</b> intenta editar el anuncio pero ocurre un error en el sistema<br>
        <b>Entonces</b> el sistema muestra un mensaje de error indicando que no se pudo guardar los cambios y sugiere intentar nuevamente más tarde.
    </td> 
    <td>EP08</td> 
</tr>
<tr>
    <td>US-17</td> 
    <td>Eliminar un anuncio publicado</td>
    <td>Como dueño de la granja, quiere eliminar un anuncio publicado, para retirar la información de su granja de la plataforma cuando ya no esté interesado en establecer alianzas.</td>
    <td>
        <b>Scenario 01:</b> Eliminación de anuncio exitosa<br>
        <b>Dado</b> que tiene un anuncio publicado<br>
        <b>Cuando</b> accede a la sección de anuncios y selecciona un anuncio para eliminar<br>
        <b>Entonces</b> el sistema elimina el anuncio de la plataforma y confirma la eliminación.<br><br>
        <b>Scenario 02:</b> Falla en la eliminación del anuncio<br>
        <b>Dado</b> que tiene un anuncio publicado<br>
        <b>Cuando</b> intenta eliminar el anuncio pero ocurre un error en el sistema<br>
        <b>Entonces</b> el sistema muestra un mensaje de error indicando que no se pudo eliminar el anuncio y sugiere intentar nuevamente más tarde.
    </td> 
    <td>EP08</td> 
</tr>

<tr>
    <td>US-18</td> 
    <td>Registrarse en la plataforma</td>
    <td>Como dueño de la granja, quiere registrarse en la plataforma, para poder crear y gestionar su cuenta y acceder a las funcionalidades del sistema.</td>
    <td>
        <b>Scenario 01:</b> Registro exitoso<br>
        <b>Dado</b> que es un usuario nuevo<br>
        <b>Cuando</b> accede a la página de registro y completa el formulario con información válida<br>
        <b>Entonces</b> el sistema crea su cuenta y le envía una confirmación de registro.<br><br>
        <b>Scenario 02:</b> Registro fallido por información inválida<br>
        <b>Dado</b> que es un usuario nuevo<br>
        <b>Cuando</b> completa el formulario de registro con información inválida o incompleta<br>
        <b>Entonces</b> el sistema muestra mensajes de error indicando los campos que deben corregirse.<br><br>
        <b>Scenario 03:</b> Registro fallido por cuenta existente<br>
        <b>Dado</b> que es un usuario nuevo<br>
        <b>Cuando</b> intenta registrarse con un correo electrónico ya existente<br>
        <b>Entonces</b> el sistema muestra un mensaje indicando que ya existe una cuenta con ese correo electrónico y sugiere iniciar sesión o recuperar la contraseña.
    </td> 
    <td>EP16</td> 
</tr>
<tr>
    <td>US-19</td> 
    <td>Iniciar sesión en la plataforma</td>
    <td>Como dueño de la granja, quiere iniciar sesión en la plataforma, para poder acceder a su cuenta y gestionar su granja.</td>
    <td>
        <b>Scenario 01:</b> Inicio de sesión exitoso<br>
        <b>Dado</b> que es un usuario registrado<br>
        <b>Cuando</b> introduce su correo electrónico y contraseña correctos en la página de inicio de sesión<br>
        <b>Entonces</b> el sistema le permite acceder a su cuenta y le muestra su panel de control.<br><br>
        <b>Scenario 02:</b> Inicio de sesión fallido por credenciales incorrectas<br>
        <b>Dado</b> que es un usuario registrado<br>
        <b>Cuando</b> introduce un correo electrónico o contraseña incorrectos<br>
        <b>Entonces</b> el sistema muestra un mensaje de error indicando que las credenciales no son correctas e invita a intentar nuevamente.<br><br>
        <b>Scenario 03:</b> Recuperación de contraseña<br>
        <b>Dado</b> que es un usuario registrado<br>
        <b>Cuando</b> no recuerda su contraseña<br>
        <b>Entonces</b> el sistema le proporciona una opción para recuperar su contraseña mediante un enlace de restablecimiento enviado a su correo electrónico.
    </td> 
    <td>EP16</td> 
</tr>

<tr>
    <td>US-20</td> 
    <td>Crear un perfil de trabajador</td>
    <td>Como dueño de la granja, quiere crear un perfil para cada trabajador, para mantener un registro organizado y detallado de sus empleados.</td>
    <td>
        <b>Scenario 01:</b> Creación de perfil de trabajador exitosa<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede a la sección de gestión de empleados y completa el formulario de nuevo trabajador<br>
        <b>Entonces</b> el sistema crea un perfil para el trabajador y lo añade a la lista de empleados.<br><br>
        <b>Scenario 02:</b> Falla en la creación del perfil de trabajador<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> introduce información incompleta o inválida en el formulario de nuevo trabajador<br>
        <b>Entonces</b> el sistema muestra un mensaje de error indicando los campos que deben corregirse.
    </td> 
    <td>EP04</td> 
</tr>
<tr>
    <td>US-21</td> 
    <td>Visualizar la lista de trabajadores</td>
    <td>Como dueño de la granja, quiere visualizar la lista de todos sus trabajadores, para tener un conocimiento claro de su fuerza laboral.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la lista de trabajadores<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede a la sección de gestión de empleados<br>
        <b>Entonces</b> el sistema le muestra una lista completa de todos los trabajadores con sus detalles respectivos.<br><br>
        <b>Scenario 02:</b> Visualización de detalles del trabajador<br>
        <b>Dado</b> que está viendo la lista de trabajadores<br>
        <b>Cuando</b> selecciona un trabajador específico<br>
        <b>Entonces</b> el sistema le muestra información detallada sobre ese trabajador, incluyendo su puesto, fecha de inicio, y contacto.
    </td> 
    <td>EP04</td> 

</tr>
<tr>
 <td>US-22</td> 
    <td>Eliminar el perfil de un trabajador</td>
    <td>Como dueño de la granja, quiere eliminar el perfil de un trabajador, para mantener la lista de empleados actualizada cuando un trabajador ya no forme parte del equipo.</td>
    <td>
        <b>Scenario 01:</b> Eliminación de perfil de trabajador exitosa<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede a la sección de gestión de empleados y elimina el perfil de un trabajador<br>
        <b>Entonces</b> el sistema elimina el perfil del trabajador de la lista y muestra un mensaje de confirmación.<br><br>
        <b>Scenario 02:</b> Falla en la eliminación del perfil de trabajador<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> intenta eliminar el perfil de un trabajador pero ocurre un error en el sistema<br>
        <b>Entonces</b> el sistema muestra un mensaje de error indicando que no se pudo eliminar el perfil y sugiere intentar nuevamente más tarde.
    </td> 
    <td>EP04</td> 
</tr>

<tr>
    <td>US-23</td> 
    <td>Registrarse en la plataforma como dueño de empresa</td>
    <td>Como dueño de una empresa, quiere registrarse en la plataforma, para poder crear y gestionar su cuenta y acceder a las funcionalidades del sistema.</td>
    <td>
        <b>Scenario 01:</b> Registro exitoso<br>
        <b>Dado</b> que es un usuario nuevo<br>
        <b>Cuando</b> accede a la página de registro y completa el formulario con información válida<br>
        <b>Entonces</b> el sistema crea su cuenta y le envía una confirmación de registro.<br><br>
        <b>Scenario 02:</b> Registro fallido por información inválida<br>
        <b>Dado</b> que es un usuario nuevo<br>
        <b>Cuando</b> completa el formulario de registro con información inválida o incompleta<br>
        <b>Entonces</b> el sistema muestra mensajes de error indicando los campos que deben corregirse.<br><br>
        <b>Scenario 03:</b> Registro fallido por cuenta existente<br>
        <b>Dado</b> que es un usuario nuevo<br>
        <b>Cuando</b> intenta registrarse con un correo electrónico ya existente<br>
        <b>Entonces</b> el sistema muestra un mensaje indicando que ya existe una cuenta con ese correo electrónico y sugiere iniciar sesión o recuperar la contraseña.
    </td> 
    <td>17</td> 
</tr>
<tr>
    <td>US-24</td> 
    <td>Iniciar sesión en la plataforma como dueño de empresa</td>
    <td>Como dueño de una empresa, quiere iniciar sesión en la plataforma, para poder acceder a su cuenta y gestionar su empresa.</td>
    <td>
        <b>Scenario 01:</b> Inicio de sesión exitoso<br>
        <b>Dado</b> que es un usuario registrado<br>
        <b>Cuando</b> introduce su correo electrónico y contraseña correctos en la página de inicio de sesión<br>
        <b>Entonces</b> el sistema le permite acceder a su cuenta y le muestra su panel de control.<br><br>
        <b>Scenario 02:</b> Inicio de sesión fallido por credenciales incorrectas<br>
        <b>Dado</b> que es un usuario registrado<br>
        <b>Cuando</b> introduce un correo electrónico o contraseña incorrectos<br>
        <b>Entonces</b> el sistema muestra un mensaje de error indicando que las credenciales no son correctas e invita a intentar nuevamente.<br><br>
        <b>Scenario 03:</b> Recuperación de contraseña<br>
        <b>Dado</b> que es un usuario registrado<br>
        <b>Cuando</b> no recuerda su contraseña<br>
        <b>Entonces</b> el sistema le proporciona una opción para recuperar su contraseña mediante un enlace de restablecimiento enviado a su correo electrónico.
    </td> 
    <td>17</td> 
</tr>

</table>



## 3.3 Impact Mapping
![Imagen de Impact Mapping del dueño de granja y empresaria](https://camo.githubusercontent.com/60494495a22e22d53a6d9bdf085461386f32857b01ecf5339ec50851db8e350a/68747470733a2f2f692e706f7374696d672e63632f54314e54486a46562f496d706163742d4d617070696e672d4475652d6f2d64652d6772616e6a612d792d456d707265736172696f2e6a7067)

![Imagen de Impact Mapping del dueño de granja y empresaria](https://i.postimg.cc/RFGYLGJV/impact-map-due-oempresas.jpg)

## 3.4 Product Backlog

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr>
        <th>
            # Orden
        </th>
        <th>
            User Story ID
        </th>
        <th>
            Título
        </th>
        <th>
            Descripción
        </th>
        <th>
            Story Points </br> (1 / 3 / 5 / 8)
        </th>
    </tr>
    <tr>
        <td>
            01
        </td>
        <td>
            US-10
        </td>
        <td>
            Crear y asignar tareas
        </td>
        <td>
            Como dueño de granja, quiero crear y asignar tareas a los trabajadores para mejorar la gestión de la mano de obra en mi finca.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            02
        </td>
        <td>
            US-01
        </td>
        <td>
            Descripción clara de servicios en la landing page
        </td>
        <td>
            Como usuario potencial, quiero ver una descripción clara y concisa de los servicios ofrecidos en la landing page, para comprender rápidamente cómo pueden beneficiar a mi operación agrícola y ganadera.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            03
        </td>
        <td>
            US-04
        </td>
        <td>
            Identificación de características en la landing page
        </td>
        <td>
            Como usuario potencial, quiero identificar fácilmente en la landing page las características que me ayudarán a encontrar una granja ideal, para evaluar la efectividad de la aplicación.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            04
        </td>
        <td>
            US-05
        </td>
        <td>
            Información de colaboradores en la landing page
        </td>
        <td>
            Como usuario potencial, quiero encontrar información sobre los colaboradores del proyecto en la landing page, para saber quiénes están detrás de la aplicación y qué experiencia tienen.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            05
        </td>
        <td>
            US-06
        </td>
        <td>
            Interacción con imágenes en la landing page
        </td>
        <td>
            Como usuario potencial, quiero interactuar con las imágenes de la landing page, para obtener más información o realizar acciones, como ampliarlas, verlas en una galería o acceder a una descripción.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            06
        </td>
        <td>
            US-13
        </td>
        <td>
            Búsqueda y contacto de granjas
        </td>
        <td>
            Como empresario, quiero buscar y contactar a dueños de granjas potenciales, para establecer asociaciones comerciales y mejorar nuestra cadena de suministro.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            07
        </td>
        <td>
            US-18
        </td>
        <td>
            Verificación de inventario
        </td>
        <td>
            Como dueño de la granja, quiero verificar fácilmente los niveles de inventario de productos agrícolas y ganaderos, y recibir notificaciones cuando sea necesario reponerlos, para garantizar un flujo de trabajo ininterrumpido.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            08
        </td>
        <td>
            US-11
        </td>
        <td>
            Notificaciones de tareas asignadas
        </td>
        <td>
            Como trabajador, quiero recibir notificaciones sobre las tareas asignadas, para mantenerme informado sobre las indicaciones del superior.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            09
        </td>
        <td>
            US-09
        </td>
        <td>
            Elegir método de pago
        </td>
        <td>
            Como dueño de granja, quiero elegir entre diferentes métodos de pago, para pagar mi suscripción de la forma más cómoda y segura para mí.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            10
        </td>
        <td>
            US-03
        </td>
        <td>
            Adaptación de landing page a dispositivos
        </td>
        <td>
            Como usuario potencial, quiero que la landing page se adapte correctamente a la pantalla de mi dispositivo, para poder verla y usarla de forma cómoda, independientemente de si estoy usando un ordenador, una tablet o un teléfono móvil.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            11
        </td>
        <td>
            US-26
        </td>
        <td>
            Estado de actividades diarias de trabajadores
        </td>
        <td>
            Como dueño de la granja, quiero verificar el estado de las actividades diarias de los trabajadores y el tiempo dedicado a cada tarea, para gestionar eficazmente la asignación de tareas y el horario de trabajo.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            12
        </td>
        <td>
            US-24
        </td>
        <td>
            Registro de ganado enfermo
        </td>
        <td>
            Como trabajador, quiero registrar la cantidad de ganado enfermo, para tener información vital de la situación de cada animal.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            13
        </td>
        <td>
            US-07
        </td>
        <td>
            Apartado demostrativo de mejora de la eficiencia y rentabilidad de las granjas en la landing page
        </td>
        <td>
            Como usuario potencial, quiero encontrar fácilmente información en la landing page sobre cómo puedo mejorar la eficiencia y rentabilidad de mi granja utilizando la plataforma, para evaluar la efectividad de la aplicación.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            14
        </td>
        <td>
            US-20
        </td>
        <td>
            Estadísticas financieras
        </td>
        <td>
            Como dueño de la granja, quiero saber estadísticas financieras, para poder administrar correctamente la economía de mi granja.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            15
        </td>
        <td>
            US-17
        </td>
        <td>
            Alertas automáticas de cambios climáticos
        </td>
        <td>
            Como trabajador, quiero recibir alertas automáticas sobre cambios climáticos significativos que puedan afectar mis cultivos, para poder tomar medidas preventivas y proteger mis cosechas.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            16
        </td>
        <td>
            US-08
        </td>
        <td>
            Apartado explicativo de control de costos y maximización de ingresos en la landing page
        </td>
        <td>
            Como usuario potencial, quiero entender en la landing page cómo la plataforma puede ayudarme a controlar los costos y maximizar los ingresos de mi granja, para evaluar la efectividad de la aplicación.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            18
        </td>
        <td>
            US-12
        </td>
        <td>
            Registro de progreso de tareas
        </td>
        <td>
            Como trabajador, quiero registrar el progreso de mis tareas, para mantenerme organizado y productivo.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            19
        </td>
        <td>
            US-23
        </td>
        <td>
            Registro de horas de trabajo
        </td>
        <td>
            Como trabajador, quiero registrar mis horas de trabajo, para saber mi salario en función a ello.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            20
        </td>
        <td>
            US-22
        </td>
        <td>
            Alertas de emergencia
        </td>
        <td>
            Como trabajador en la granja, quiero emitir alertas sobre cualquier emergencia a mis colegas y supervisores de manera eficaz e inmediata.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            21
        </td>
        <td>
            US-29
        </td>
        <td>
            Acceso móvil a la plataforma
        </td>
        <td>
            Como dueño de la granja, quiero acceder a la plataforma FarmLogiTech desde mi dispositivo móvil, para poder gestionar mi granja desde cualquier lugar.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            22
        </td>
        <td>
            US-30
        </td>
        <td>
            API RESTful
        </td>
        <td>
            Como desarrollador, necesito crear una API RESTful, para permitir que la plataforma web se comunique con el backend y acceda a los datos agrícolas y ganaderos de los usuarios.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            23
        </td>
        <td>
            US-31
        </td>
        <td>
            Seguridad robusta
        </td>
        <td>
            Como desarrollador, necesito implementar medidas de seguridad robustas, como autenticación de usuarios, para proteger la información confidencial de los agricultores en la plataforma.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            24
        </td>
        <td>
            US-32
        </td>
        <td>
            Integración de pronóstico meteorológico
        </td>
        <td>
            Como desarrollador, necesito integrar funcionalidades de pronóstico meteorológico en la plataforma, para proporcionar a los agricultores información actualizada sobre las condiciones climáticas en sus áreas.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            25
        </td>
        <td>
            US-33
        </td>
        <td>
            Interfaz intuitiva y fácil de usar
        </td>
        <td>
            Como desarrollador, necesito crear una interfaz intuitiva y fácil de usar en la plataforma, para garantizar una experiencia de usuario positiva y aumentar la satisfacción del cliente.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            26
        </td>
        <td>
            US-34
        </td>
        <td>
            Escalabilidad del sistema
        </td>
        <td>
            Como desarrollador, necesito garantizar la escalabilidad del sistema, para manejar un creciente número de usuarios y datos agrícolas sin comprometer el rendimiento.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            27
        </td>
        <td>
            US-27
        </td>
        <td>
            Informe detallado sobre la producción
        </td>
        <td>
            Como dueño de la granja, quiero un informe detallado sobre la producción y la gestión de la granja, para garantizar el cumplimiento de los estándares de calidad y rentabilidad.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            28
        </td>
        <td>
            US-28
        </td>
        <td>
            Establecimiento de metas de producción
        </td>
        <td>
            Como dueño de la granja, quiero establecer metas de producción y seguirlas a lo largo del tiempo, para mantenerme enfocado en mejorar el rendimiento de mi granja.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            29
        </td>
        <td>
            US-35
        </td>
        <td>
            Soporte técnico y atención al cliente
        </td>
        <td>
            Como desarrollador, necesito establecer un sistema de soporte técnico y atención al cliente, para ayudar a los granjeros y empresarios con cualquier problema o pregunta relacionada con la plataforma.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            30
        </td>
        <td>
            US-21
        </td>
        <td>
            Registro de cumplimiento de tareas
        </td>
        <td>
            Como trabajador en la granja, quiero registrar el cumplimiento de mis tareas con detalles como la cantidad, calidad y fecha de cosecha, para mantener un registro preciso de la producción de la granja.
        </td>
        <td>
            3
        </td>
    </tr>
     <tr>
        <td>
            31
        </td>
        <td>
            US-19
        </td>
        <td>
            Estado de cultivos y ganado
        </td>
        <td>
            Como dueño de la granja, quiero saber información detallada sobre el estado de mis cultivos y ganado, para poder administrarla de manera rápida e informada.
        </td>
        <td>
            3
        </td>
    </tr>
     <tr>
        <td>
            32
        </td>
        <td>
            US-15
        </td>
        <td>
            Filtros de busqueda de granjas
        </td>
        <td>
             Como empresario, quiero buscar granjas con filtros en específico, para encontrar fácilmente una granja que se adapte a mis necesidades.
        </td>
        <td>
            3
        </td>
    </tr>
     <tr>
        <td>
            33
        </td>
        <td>
            US-16
        </td>
        <td>
            Valoraciones y comentarios de granjas
        </td>
        <td>
            Como empresario, quiero acceder a las valoraciones y comentarios de otros empresarios sobre las granjas, para tomar decisiones informadas y sentirme seguro al realizar negocios con ellas.
        </td>
        <td>
            1
        </td>
    </tr>
     <tr>
        <td>
            34
        </td>
        <td>
            US-14
        </td>
        <td>
            Información detallada de las granjas
        </td>
        <td>
           Como empresario, quiero ver información detallada de las granjas, para poder elegir una adecuada para mi idea de negocio.
        </td>
        <td>
            1
        </td>
    </tr>
     <tr>
        <td>
            35
        </td>
        <td>
            US-02
        </td>
        <td>
            Planes de suscripción en la landing page
        </td>
        <td>
           Como usuario potencial, quiero encontrar fácilmente los precios y planes de suscripción disponibles en la landing page, para evaluar la viabilidad económica de utilizar la plataforma en mi granja.
        </td>
        <td>
            1
        </td>
    </tr>
</table>

# Capítulo IV: Product Design
## 4.1. Style Guidelines.

### 4.1.1. General Style Guidelines

### Branding:
- Esta imagen simboliza nuestra dedicación a la agricultura y a los animales. Al unirse a nosotros, los usuarios experimentarán una conexión sólida y colaborativa, reflejada en nuestra comunidad.
  <div align=center>
   <img src="/assets/img-logo-farm.jpeg" alt="Logo-farm"></img>
</div>
#### Brand Name:
      Farm: Este término se refiere a la agricultura o a las actividades relacionadas con la producción de cultivos y/o cría de animales. En inglés, "farm" significa granja.
      Logi: Esta parte del nombre deriva de "logística", que se refiere a la organización y gestión eficiente de los recursos, materiales y actividades en las operaciones agrícolas.
      Tech: Es una abreviatura de "technology" en inglés, que significa tecnología. 



### Typography:
- La tipografía de nuestro logotipo adoptará el elegante estilo Semibold, reconocido por su modernidad y su atractivo visual para nuestros usuarios. Este estilo no solo refleja la innovación y la creatividad que caracterizarán a nuestra aplicación, sino que también resalta la vanguardia que buscamos transmitir.


<div align=center>
   <img src="/assets/img-typo.jpeg" alt="Font-typo"></img>
</div>
<br>

### Colors:

- Nuestra paleta de colores se ha seleccionado para que al visitar nuestro sitio web, los usuarios sientan la atmósfera de una granja. El verde  (#25C95C) aporta frescura y vitalidad. El amarillo pálido (#E9F3AE) evoca la luz del sol sobre los cultivos. En conjunto, estos colores ofrecen una experiencia visual que refleja el ambiente y la energía de una granja.

<div align=center>
   <img src="/assets/img-palet-colors.png" alt="palet-colors"></img>
</div>
<br>

### Spacing:
Estos son los espaciados que utilizamos a la hora de elaborar nuestro proyecto.
![Espaciados](https://i.postimg.cc/kgH0Rj3Q/spacing.png)

## Tone of Voice
Tomando en cuenta las 4 dimensiones del tono de voz descritas por Kate Moran en su articulo, nos hemos decidido por inclinarnos mas hacia estos 4 tonos:

Dimension del humor:
Serio: En FarmLogiTech, creemos que es importante mantener un tono serio para transmitir confiabilidad y profesionalismo. Es crucial comunicar seriedad en el enfoque.

Dimensión de la formalidad:
Formal:  Los usuarios, especialmente los propietarios de granjas y las empresas agrícolas, esperarán un tono formal que refleje el nivel de profesionalismo y experiencia de FarmLogiTech en el campo agrícola.

Dimensión del respeto:
Respetuoso: El respeto hacia los usuarios, clientes y colaboradores es fundamental para construir relaciones sólidas y duraderas.

Dimensión del entusiasmo:
Entusiasta: Aunque se mantiene un tono serio y formal, agregar un toque de entusiasmo puede generar interés y motivación entre los usuarios.

![Tone of voice](https://i.postimg.cc/NFL8XxwX/tone-of-voice.png)

### 4.1.2. Web Style Guidelines

*Icons:*

- Cuando se trata de diseñar una página web, los íconos juegan un papel crucial en la creación de una interfaz de usuario intuitiva y fácil de usar. Estos elementos visuales pequeños tienen el poder de mejorar la comprensión de los usuarios sobre la funcionalidad de diferentes partes de tu página. Los íconos permiten a los usuarios entender rápidamente la función de cada elemento y su simplicidad y claridad los hacen fácilmente comprensibles. Mantener una consistencia en el uso de íconos en toda la página ayuda a evitar confusiones entre los usuarios.
- Los que usaremos en el proyecto son los siguientes:

<br>

*Breackpoints*
- Los breakpoints más conocidos son los siguientes:

<br>

- Y los que usaremos en el proyecto principalmente son los de 768px y 1024px, ya que son los más comunes en los dispositivos móviles y de escritorio.

*Tarjetas*
Se hace uso del componente "mat-card" de la colección de Angular Material para representar algunas imagenes, cuadros, etc.

*Botones*
Se utilizan los botones en la parte inferior de algunas secciones de la web. Principalmente, los usamos para el guardado de datos.

*Tablas*
Las tablas, por lo general, blancas y grises. Son el elemento que usamos para mostrar los datos de registros asi como historiales y listas.

*Barras de búsqueda*
Solemos usarlos para la selección de datos del usuario. Así mismo, algunas tienen la posibilidad de ingresar datos escritos como de seleccioar datos especificos predeterminados. Los usamos para la busqueda, los filtros y la adicion de datos.

## 4.2. Information Architecture
### 4.2.1. Organization Systems

Empleamos tres diferentes formas en la organización visual de contenido:

- **La organización de forma jerárquica** presenta al usuario con un orden de importancia para los elementos que se muestran en pantalla. Los empleamos en las pantallas de ingresos de datos, asi como listado de datos. Los titulos acaparan gran parte de la pantalla, asi como aquellas imagenes o textos que tienne un mayor nivel de importancia que otros elementos en pantalla.
- **La organización secuencial** presenta al usuario una especie de camino o paso a paso para completar la tarea que necesitan. Empleamos esto en las secciones de añadir tarea o añadir empleado que usan una secuencia de pantallas para poder registrar la información necesiaria. De igual modo, para hacer el pago de la paquete Premium, tambien seguimos una secuencia que permita hacer la adquisición.
- **Organización matricial** presenta al usuario una matriz, asi como la libertad de escoger el camino de navegación que siguen. Los usamos unicamente en la presentación principal de la pagina, en la que el usuario puede visualizar las granjas destacadas como una matriz. En esta vista, el usuario puede escoger la granja en la cual

- **Esquemas de organización**
  -**Alphabetical Schemes**: Los empleamos en la vista inicial, el usuario podrá usar orden alfabetico para ordener las granjas y visualizarlas en dicho orden.
  -**Chronological Schemes**: Los empleamos en la vista de emergencias. El historial de emergencias esta organizado de forma que primero se ve la mas reciente. Así como el historial de pagos.
  -**Topic Schemes**: Con los filtros de busqueda de granjas, asi como de animales o de cultivos, se pueden aplicar diferentes topicos: como el tipo, el tipo de galpón, especies, etc.
  -**Audience schemes**: Cada uno de lossegmentos objetivos tiene un propósito diferente al momento de acceder. Los trabajadores tienen su propia pestaña dedicada a observar sus tareas pendientes. El dueño de granja puede visualizar todo el contenido de su granja, asi como sus empleados y sus pagos. Finalmente, las empresas visualizan las granjas y sus numeros de contacto.

### 4.2.2. Labeling Systems


En el proyecto manejaremos un sistema de *etiquetado por facetas*, el cual consiste en la clasificación de los contenidos por categorías, las cuales se pueden combinar entre sí para encontrar un contenido específico.

Dichas categorías son:

- HomePage (Página de inicio)
- Login (Inicio de sesión)
- Register (Registro)
- Profile (Perfil)
- List of farms(Lista de granjas)
- Employee tasks(Tarea de empleados)
- Farm search (Búsqueda de granjas según el producto y la localización)

### 4.2.3. SEO Tags and Meta Tags

Las Meta Tags nos permiten insertar información codificada y definir metadatos. Aunque no son visibles en la interfaz de los sitios web, son interpretadas por los navegadores y rastreadores web. Estas etiquetas facilitan el análisis del código HTML y contribuyen al mantenimiento del contenido del sitio. Además, juegan un papel crucial en el posicionamiento de nuestra página web en los motores de búsqueda. Las Meta Tags que utilizaremos son:

- Título: Esta etiqueta es fundamental y suele colocarse antes que cualquier otra metaetiqueta. Todos los motores de búsqueda la utilizan como encabezado en las páginas de resultados de búsqueda (SERP).  
  ```<title>Register your processes with FarmLogiTech</title> ```

- Autor y Derechos de Autor:
  Esta etiqueta se emplea para registrar la información del autor y los derechos de propiedad de la página web.
``` 
<meta name="author" content="FarmLogitech"/>
<meta name="copyright" content="Copyright FarmLogiTech team" />
```

-Descripción: Esta etiqueta nos permite la opción de añadir una breve descripción a la pagina, que es visible en los resultados de busqueda:
```<meta name="description" content="FarmLogiTech is a web application focused on farm's organization and visualization"/>```}

-Robots: Esta etiqueta es importante en la estrategia SEO. Le dice especificamente a un motor de busqueda si la pagina debe ser indexada o seguida o ninguno de los dos. Por lo general, una pagina es indexada y seguida, lo que permite que aparezca en los motores de buqueda. Haremos uso de estos, en caso publiquemos nuestra web application en algun motor de busqueda.
```<meta name="robots" content="follow, index, max-snippet:-1, max-video-preview:-1, max-image-preview:large"/>```

- Key Items: Esta etiqueta se usa para añadir palabras clave relacionados al contenido de la web.
  ```<meta name="keywords" content="crops, system, management, farms, organization, farming, agriculture"/>```




### 4.2.4. Searching Systems


Es esencial que los usuarios administradores puedan distinguir y filtrar la información de los registros almacenados en la aplicación web de gestión de granjas. Uno de los objetivos clave del sistema es presentar de manera efectiva, sencilla y rápida la gran cantidad de datos que serán ingresados por las empresas agrícolas. Los usuarios tendrán la capacidad de buscar los registros de cultivos según su fecha de ingreso y la fase en la que se encuentran. Además, podrán filtrar la información según la fecha, fase y autor del registro de cultivos en el histórico general de cultivos realizados. También se incluirá funcionalidad de búsqueda en la visualización de los empleados de la empresa.

En nuestro proyecto, facilitaremos a los usuarios la oferta de granjas que cumplan con sus requisitos específicos. Los usuarios podrán listar sus granjas según el tipo de producto que ofrecen, ya sea cultivos o animales, así como también podrán especificar la ubicación geográfica de sus granjas. Esto garantizará que los usuarios puedan mostrar fácilmente las características de sus granjas, mejorando así su visibilidad y accesibilidad en nuestra plataforma.

### 4.2.5. Navigation Systems


Los principales sistemas de navegación en la Landing Page son los menús ubicados en la parte superior e inferior. El etiquetado direcciona a los usuarios a las secciones específicas de la página. Si no se utilizan estos enlaces, la página se desplazará hacia abajo automáticamente. En la aplicación, los usuarios seguirán un proceso de cultivo, con secciones numeradas y visibles encima de los registros de cada fase. Los usuarios tienen la opción de saltar entre fases o seguir un orden secuencial. Los botones, por su parte, representan acciones como abrir, confirmar o completar un registro, facilitando el seguimiento del proceso en una nueva pantalla.

- *Navegación principal o global:* Es el sistema de navegación más común, presente en todos los apartados de la página y usualmente representado por la barra de navegación y el footer.

<div align=center>
</div>

El patrón de lectura a utilizar para la visualización de nuestro website para las secciones que muestran contenido ligero será el patrón Z.
<div align=center>
<br>

</div>


## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe


<div align=center>
   <img src="/assets/img-landing-wireframe.png" alt="Landing-Wireframe"></img>
</div>

### 4.3.2. Landing Page Mock-up
<div align=center>
   <img src="/assets/img-landing-mock-up.png" alt="Mockup"></img>
</div>

### 4.4. Web Applications UX/UI Design.
#### 4.4.1. Web Applications Wireframes.
<div align=center>
<p>En la siguiente imagen, podemos observar los wireframes que se utilizan para poder publicar una granja.</p>
   <img src="/assets/img-wireframe-1.png" alt="Wireframe"></img>
</div>
<div align=center>
<p>En la siguiente imagen, se visualiza los wireframes que se utilizan para editar perfil.</p>
   <img src="/assets/img-wireframe-2.png" alt="Wireframe"></img>
</div>
<div align=center>
<p>En la siguiente imagen, se visualiza los wireframes que usaran los trabajadores de las granjas al utilizar FarmLogitech para ver sus tareas asignadas</p>
   <img src="/assets/img-wireframe-3.png" alt="Wireframe"></img>
</div>
<div align=center>
<p>En la siguiente imagen se observa los wireframes que usará el administrador para poder ver ingresos y agresos a través de gráficos</p>
   <img src="/assets/img-wireframe-4.png" alt="Wireframe"></img>
</div>
<div align=center>
<p>En la siguiente imagen se observa los wireframes que usará el administrador o trabajador para poder mandar mensajes de emergencia a su jefe o compañeros</p>
   <img src="/assets/img-wireframe-5.png" alt="Wireframe"></img>
</div>
<div align=center>
<p>Estadísticas financieras</p>
   <img src="/assets/img-wireframe-6.png" alt="Wireframe"></img>
</div>
<div align=center>
<p>Asignar tarea</p>
   <img src="/assets/img-wireframe-7.png" alt="Wireframe"></img>
</div>
<div align=center>
<p>Mandar alerta de emergencia</p>
   <img src="/assets/img-wireframe-8.jpg" alt="Wireframe"></img>
</div>
<div align=center>
<p>Agregar galpón</p>
   <img src="/assets/img-wireframe-9.jpg" alt="Wireframe"></img>
</div>
<div align=center>
<p> Consulta de inventario</p>
   <img src="/assets/img-wireframe-10.png" alt="Wireframe"></img>
</div>
<div align=center>
<p> Consulta de animales</p>
   <img src="/assets/img-wireframe-11.png" alt="Wireframe"></img>
</div>
<div align=center>
<p> Revisar tareas</p>
   <img src="/assets/img-wireframe-12.png" alt="Wireframe"></img>
</div>


#### 4.4.2. Web Applications Wireflow Diagrams.
<div align=center>
   <img src="/assets/img-wireframe-conexion-1.jpeg" alt="Wireframe"></img>
</div>
<div align=center>
   <img src="/assets/img-wireframe-conexion-2.jpeg" alt="Wireframe"></img>
</div>
<div align=center>
   <img src="/assets/img-wireframe-conexion-3.jpeg" alt="Wireframe"></img>
</div>
<div align=center>
   <img src="/assets/img-wireframe-conexion-4.jpeg" alt="Wireframe"></img>
</div>
<div align=center>
   <img src="/assets/img-wireframe-conexion-5.jpeg" alt="Wireframe"></img>
</div>
<div align=center>
   <img src="/assets/img-wireframe-conexion-6.jpeg" alt="Wireframe"></img>
</div>
<div align=center>
   <img src="/assets/img-wireframe-conexion-7.jpeg" alt="Wireframe"></img>
</div>
<div align=center>
   <img src="/assets/img-wireframe-conexion-8.jpeg" alt="Wireframe"></img>
</div>
<div align=center>
   <img src="/assets/img-wireframe-conexion-9.jpeg" alt="Wireframe"></img>
</div>
<div align=center>
   <img src="/assets/img-wireframe-conexion-10.jpeg" alt="Wireframe"></img>
</div>
<div align=center>
   <img src="/assets/img-wireframe-conexion-11.jpeg" alt="Wireframe"></img>
</div>
<div align=center>
   <img src="/assets/img-wireframe-conexion-12.jpeg" alt="Wireframe"></img>
</div>

####  4.4.3. Web Applications Mock-ups.
<div align=center>
<p>Publicar tu anuncio</p>
<p>En la siguiente imagen, podemos observar los mockups que se utilizan para poder publicar una granja.</p>
   <img src="/assets/img-mockup-1.png" alt="Mockups"></img>
</div>
<div align=center>
 <p>Editar perfil</p>
<p>En la siguiente imagen, se visualiza los mockups que se utilizan para editar perfil.</p>
   <img src="/assets/img-mockup-2.png" alt="Mockups"></img>
</div>
<div align=center>
    <p>Publicar granja</p>
<p>En la siguiente imagen, se visualiza los mockups que se usará para publicar la granja</p>
   <img src="/assets/img-mockup-3.png" alt="Mockups"></img>
</div>
<div align=center>
       <p>Asignar tareas</p>
<p>En la siguiente imagen observamos los mockups de los administradores de la granja en cual podrán asignar tareas a sus trabajadores</p>
   <img src="/assets/img-mockup-4.png" alt="Mockups"></img>
</div>
<div align=center>
    <p>Gestión y estadistica en FarmLogitech</p>
<p>En la siguiente imagen observamos los mockups de los administradores de la granja en cual podrán acceder a las tareas asiganadas, estadísticas de ingresos y egresos, control de inventario.</p>
   <img src="/assets/img-mockup-5.png" alt="Mockups"></img>
</div>
<div align=center>
    <p>Gráficos estadísticos</p>
<p>En la siguiente imagen se observa el registro mediante gráficos generando como van los ingresos e egresos</p>
   <img src="/assets/img-mockup-6.png" alt="Mockups"></img>
</div>
<div align=center>
    <p>Agregar labor</p>
<p>En la siguiente imagen se observa como el administrador puede asignar una labor a un empleado</p>
   <img src="/assets/img-mockup-7.png" alt="Mockups"></img>
</div>
<div align=center>
    <p>Mandar alerta de emergencia</p>
<p>En la siguiente imágen se observa como pueden reportar una emergencia y colocar la fecha para que así quede registrado. </p>
   <img src="/assets/img-mockup-8.png" alt="Mockups"></img>
</div>
<div align=center>
    <p>Agregar galpón</p>
<p>En la siguiente imagen se observa el registro que se llevará para agregar un galpón y listarlo</p>
   <img src="/assets/img-mockup-9.png" alt="Mockups"></img>
</div>
<div align=center>
    <p>Agregar animales</p>
<p>En la siguiente imagen se observa el registro que se llevará para agregar un animal y registrarlo</p>
   <img src="/assets/img-mockup-10.png" alt="Mockups"></img>
</div>
<div align=center>
    <p>Registro de cultivo</p>
<p>En la siguiente imagen se observa el registro que se llevará para registrar un cultivo</p>
   <img src="/assets/img-mockup-11.png" alt="Mockups"></img>
</div>
<div align=center>
    <p>Listar cultivos</p>
<p>En la siguiente imagen observamos los mockups de los administradores de la granja en cual podrán acceder a las tareas asiganadas, estadísticas de ingresos y egresos, control de inventario.</p>
   <img src="/assets/img-mockup-12.png" alt="Mockups"></img>
</div>
<div align=center>
    <p>Listar animales</p>
<p>En la siguiente imagen se observa el proceso para listar los animales</p>
   <img src="/assets/img-mockup-13.png" alt="Mockups"></img>
</div>
<div align=center>
    <p>Registrar alimentación</p>
<p>En la siguiente imagen se observa el registro que se llevará para el registro de alimentación</p>
   <img src="/assets/img-mockup-14.png" alt="Mockups"></img>
</div>
<div align=center>
    <p>Finalizar tarea</p>
<p>En la siguiente imagen se observa el proceso para finalizar una tarea luego de culminarla para que quede registrada</p>
   <img src="/assets/img-mockup-15.png" alt="Mockups"></img>
</div>
<div align=center>
    <p>Chequeo de pagos</p>
<p>En la siguiente imagen se observa como el administrado revisa los pagos completados para que pueda dar acceso a los administradores de granja para que puedan publicar sus imágenes de sus granjas</p>
   <img src="/assets/img-mockup-16.png" alt="Mockups"></img>
</div>

#### 4.4.4. Web Applications User Flow Diagrams.

<div align=center>
   <img src="/assets/img-mockup-conexion-1.png" alt="Mockup-diagram"></img>
</div>
<div align=center>
   <img src="/assets/img-mockup-conexion-2.png" alt="Mockup-diagram"></img>
</div>
<div align=center>
   <img src="/assets/img-mockup-conexion-3.png" alt="Mockup-diagram"></img>
</div>
<div align=center>
   <img src="/assets/img-mockup-conexion-4.png" alt="Mockup-diagram"></img>
</div>
<div align=center>
   <img src="/assets/img-mockup-conexion-5.png" alt="Mockup-diagram"></img>
</div>
<div align=center>
   <img src="/assets/img-mockup-conexion-6.png" alt="Mockup-diagram"></img>
</div>
<div align=center>
   <img src="/assets/img-mockup-conexion-7.png" alt="Mockup-diagram"></img>
</div>
<div align=center>
   <img src="/assets/img-mockup-conexion-8.png" alt="Mockup-diagram"></img>
</div>
<div align=center>
   <img src="/assets/img-mockup-conexion-9.png" alt="Mockup-diagram"></img>
</div>
<div align=center>
   <img src="/assets/img-mockup-conexion-10.png" alt="Mockup-diagram"></img>
</div>
<div align=center>
   <img src="/assets/img-mockup-conexion-11.png" alt="Mockup-diagram"></img>
</div>
<div align=center>
   <img src="/assets/img-mockup-conexion-12.png" alt="Mockup-diagram"></img>
</div>
<div align=center>
   <img src="/assets/img-mockup-conexion-13.png" alt="Mockup-diagram"></img>
</div>
<div align=center>
   <img src="/assets/img-mockup-conexion-14.png" alt="Mockup-diagram"></img>
</div>

#### 4.5. Web Applications Prototyping.
Para poder elaborar los prototipos de la interfaz de usuario destinados a Desktop y Mobile Web Browser, se siguieron una serie de criterios fundamentales, entre ellos:

- *Claridad y Facilidad*: El enfoque fue lograr que la navegación en la página web sea intuitiva y comprensible. Los usuarios pueden comprender plenamente las funciones de la página, como son la búsqueda de granjas, la visualización de granjas destacadas y la publicación de anuncios.

- *Diseño Responsive*: Se ha tenido en cuenta la importancia del diseño “responsive” para garantizar que la página web sea compatible con una variedad de tamaños de pantalla. De esta manera, los usuarios no se ven limitados por el dispositivo que utilicen, ya sea un ordenador de escritorio o un dispositivo móvil.

- *Priorización de Información Relevante*: El diseño de la página web se enfoca en mostrar únicamente la información más importante para los usuarios. Esto incluye detalles de las granjas destacadas, opciones de búsqueda y detalles para la publicación de anuncios.

<div align=center>
   <img src="/assets/img-landing-m.png" alt="Landing-Mock-up"></img>
</div>

Video de prueba
<br>

https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210029_upc_edu_pe/ETbEAdlXL0tKlVXCRvmGMdkB0HOmvtODaS1FOnFVQ3XQLA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=aLRsaQ



# 4.6. Domain-Driven Software Architecture
El Domain Driven Design (DDD) tiene como objetivo llegar a un entendimiento compartido del dominio que abarca el espacio del problema. En el caso de “FarmLogitech”, este dominio es la gestión de granjas y la colaboración entre agricultores y empresas. Gracias a la perspectiva brindada por este enfoque, es posible mejorar la colaboración entre los desarrolladores y los expertos del dominio.


## 4.6.1. Software Architecture Context Diagram
El diagrama de contexto muestra una vista de alto nivel de las relaciones entre el sistema de software “FarmLogitech”, los usuarios y, si es el caso, de otros sistemas externos.
<div align=center>
<img src="/assets/img-systemdiagram.jpeg" alt="System diagram"></img>
</div>

## 4.6.2. Software Architecture Container Diagram
El diagrama de contenedores muestra una vista de alto nivel de las relaciones entre las aplicaciones y fuentes de datos que son parte de la ejecución del sistema de software “FarmLogitech”.

<div align=center>
<img src="/assets/img-container.jpeg" alt="Container diagram"></img>
</div>

## 4.6.3. Software Architecture Components Diagrams
Los diagramas de componentes muestran una vista de las relaciones de los componentes principales del sistema de software “FarmLogitech”. Estos componentes detallan la implementación de los respectivos módulos en el programa.

- Communicaction Management Bounded Context

<div align=center>
  <img src="/assets/img-bounded-context-1.png" alt="Communicaction Management Bounded Context"></img>
</div>

- Dashboard and Analytics Bounded Context

<div align=center>
  <img src="/assets/img-bounded-context-2.png" alt="Dashboard and Analytics Bounded Context"></img>
<div>

- Login Bounded Context

<div align=center>
  <img src="/assets/img-bounded-context-4.png" alt="Login Bounded Context"></img>
<div>

- Payment Bounded Context

<div align=center>
  <img src="/assets/img-bounded-context-3.png" alt="Payment Bounded Context"></img>

- Profile Management Bounded Context
<div align=center>
  <img src="/assets/img-bounded-context-6.png" alt="Profile Management Bounded Context"></img>
<div>

- Resource Management Bounded Context
<div align=center>
  <img src="/assets/img-bounded-context-5.png" alt="Resource Management Bounded Context"></img>
<div>

- Service Operation and Monitoring Bounded Context
<div align=center>
  <img src="/assets/img-bounded-context-7.png" alt="Service Operation and Monitoring Bounded Context"></img>
<div>

- Social Interaction Bounded Context
<div align=center>
  <img src="/assets/img-bounded-context-8.png" alt="Social Interaction Bounded Context "></img>
<div>

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
<div align=center>
   <img src="/assets/img-class-diagrama.png" alt="Diagrama de clase"></img>
</div>

### 4.7.2. Class Dictionary
Class User
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id  | int | Unique code for a user
|  first_name  | String  | Name of a user
| last_name  | String | Last Name of a user
| phone_number  | int | Phone Number of the user
| email  | String | Email of the user |
| account  | Account  | Account of the User

Class Account
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id  | int | Unique code for an account
| name  | String  | Name of the account
| owner  | User | The owner of the Account

Class Membership
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id  | int | Unique code for a Membership
|  name  | String  | Name of a Membership
| price  | int | Price of a Membership
| description  | int | Description of a Membership

Class MembershipPayment
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id  | int | Unique code for a MembershipPayment
| amount  | int  | Amount to be paid
| paid_date  | int | The date the Membership was paid

Class Farm_Owner
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id  | int | Unique code for a Farm_Owner
| first_name  | String  | Name of a Farm_Owner
| last_name  | String | Last Name of a Farm_Owner
| phone_number  | int | Phone Number of the Farm_Owner
| email  | String | Email of the Farm_Owner |
| account  | Account  | Account of the Farm_Owner
| password  | String | Password of a Farm_Owner

Class Client
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id  | int | Unique code for a Client
| first_name  | String  | Name of a Client
| last_name  | String | Last Name of a Client
| phone_number  | int | Phone Number of the Client
| email  | String | Email of the Client |
| account  | Account  | Account of the Client

Class Collaborator
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a Collaborator
| first_name  | String  | Name of a Collaborator
| last_name  | String | Last Name of a Collaborator
| phone number  | int | Phone Number of a Collaborator
| Email  | String | Email of a Collaborator
| password  | String | Password of a Collaborator
| working_hours  | int | hours that the collaborator works per week
| salary  | int | the salary of the collaborator

Class Farm
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a Collaborator
| name  | String  | Name of a Collaborator
| location  | String | The location of the farm
| infrastructure  | String | Infrastructure of the farm
| service  | String | Services of the farm
| certificates  | String | Certificates that the farm have
| status  | String | Status of the farm

Class Animal
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for an animal
| age  | int  | The age of the animal
| sex  | String | Sex of an animal
| health_condition  | int | The health condition of the animal
| addition_date  | String | The date the animal was brought to the farm

Class Task
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a task
| description  | String  | Description for a task
| estimated_time_to_make  | int | The estimated hours that will take doing this task to the collaborator
| end_date  | int |  The deadline for the task

Class Valoration
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a valoration
| rating  | String  | Rating made by the user for the farm

Class Message
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a message
| text  | String  | Text of the message
| date  | int | The date the message was sent
| isEmergency  | bool | The urgency of the Message

Class Crop
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a crop
| age  | int  | Age of a crop
| location  | String | The location of the crop
| health_status  | int |  The health status of the crop

Class Shed
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a shed
| type  | String  | Type of the shed
| location  | int | The location of the shed

Class Sells
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a task
| quantity  | int  | Quantity of the sells
| date  | String | Day of the sell
| percentage  | int | Percentage of the sell

Class Notification
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a notification
| description  | String  | Description for a task


## 4.8 Database Design
Para el proyecto, nos hemos decidido por utilizar el motor de base de datos de MySQL, debido a que es una herramientas con la que todos los integrantes del equipo nos sentimos comodos y familiarizados, ademas que posee una interfaz sencilla e intuitiva. Este motor nos permite desarrollar una base de datos para nuestro proyecto, el cual requerira de muchas tablas y conexiones entre ellas.

### Database Diagram

### 4.8.1 Database Diagram

Dashboard-Analytics Bounded Context
![Imagen de WhatsApp 2024-05-03 a las 01 08 55_8379ab0d](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/d416c8ce-ec9f-4338-9213-d4d734ea0a47)

Resource Management Bounded Context
![Imagen de WhatsApp 2024-05-03 a las 00 49 57_4aa6dc7a](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/db33fbc1-ae69-42ab-91b5-ca3dfcfd0479)

Login Bounded Context
![Imagen de WhatsApp 2024-05-03 a las 00 35 56_bd2d30b8](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/3aa923e1-50a5-4bbe-b036-f8bfa92619b1)

Profile Management Bounded Context
![Imagen de WhatsApp 2024-05-03 a las 00 35 51_25ec43d2](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/9ac23077-ab35-48b8-adda-51a88eb3b242)

Payment Bounded Context
![Imagen de WhatsApp 2024-05-03 a las 00 35 45_24348a5f](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/2c596152-a35e-4231-a6ed-f647c208ee67)

Social Interaction Bounded Context
![Imagen de WhatsApp 2024-05-03 a las 00 35 26_a17433f2](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/6c6eb54e-2923-458b-996b-7a64b2e998fc)

Service Operation and Monitoring Bounded Context
![Imagen de WhatsApp 2024-05-03 a las 00 35 17_56c1d275](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/3ec9aad1-a6ee-40f0-b849-6e7c620b7a31)


# Capítulo V: Product Implementation, Validation & Deployment
## 5.1 Software Configuration Management
A continuación, presentaremos el proceso por el cual organizamos, gestionamos y controlamos los cambios en el desarrollo de este proyecto.
### 5.1.1. Software Development Environment Configuration.
*Requirements Management*
1. Trello: Es una herramienta utilizada para gestionar el flujo de trabajo de proyectos principalmente basados en marcos de
   trabajos ágiles. Será empleado para visualizar y actualizar el estado actual de las tareas e historias de usuario
   pertenecientes al sprint a desarrollar.  
   Ruta de referencia: https://trello.com/es


*Product UX/UI Design*

1. Figma: Plataforma de elaboración de prototipos y edición gráfica, principalmente utilizado para el diseño digital. En el
   caso del proyecto, será utilizado para el prototipado de la aplicación y sus versiones de Desktop y Mobile Web Browser.

   Ruta de referencia: https://www.figma.com/login
2. Lucidchart: Aplicación para diagramar flujos. Será empleado para el diseño de wireflows, user-flows y el diagrama de
   clases asociado a la aplicación.

   Ruta de referencia: https://www.lucidchart.com/


*Software Development*
1. Visual Studio Code: Entorno de desarrollo integrado elegido para la elaboración y compilación del código por motivos de
   dominio por parte de los integrantes del equipo de trabajo. Utilizar este IDE supone de valor para el desarrollo del
   proyecto puesto que incluye la posibilidad de agregar extensiones de utilidad, soporte de edición de texto en múltiples
   lenguajes de programación, disponibilidade en múltiples sistemas operativos, entre otros beneficios.

   Ruta de referencia: https://code.visualstudio.com/  
   <br>
2. HTML5: HyperText Markup Language, o por sus siglas HTML, es un lenguaje de etiquetado para páginas web. Será
   empleado en el desarrollo del proyecto para la presentación del contenido en la aplicación.

   Ruta de referencia: https://www.w3schools.com/html/html5_syntax.asp   
   <br>
3. CSS: Cascading Style Sheets es un lenguaje que maneja el diseño y presentación de las páginas web, el cual va de la mano
   con HTML.

   Ruta de referencia: https://google.github.io/styleguide/htmlcssguide.html
   <br>
   <br>
4. Tailwind CSS: Es un conjunto de herramientas de utilidad de CSS altamente personalizable y orientado a clases. Se utilizará para diseñar y estilizar la interfaz de usuario dentro de la aplicación.

   Ruta de referencia: https://tailwindcss.com/docs
   <br>
   <br>
5. JavaScript: Es un lenguaje de programación interpretado y orientado a objetos. Se utilizará para elaborar la interfaz de
   usuario dentro de la aplicación.

   Ruta de referencia: https://developer.mozilla.org/es/docs/Web/JavaScript

 <br>

*Software Deployment*
1. Git: Una herramienta de control de versiones que facilita el registro y la gestión de las distintas versiones del programa. Su propósito es mantener un historial de cambios y simplificar la corrección de errores. Los integrantes del equipo
   accederán a través de la línea de comandos en sus sistemas locales.

   Ruta de referencia: https://git-scm.com/
   <br>
   <br>
   *Software Documentation and Project Management*
2. Github: Una plataforma en la nube que hospedará los repositorios de código del proyecto. Permitirá la colaboración en
   tiempo real y la revisión de contribuciones de cada miembro del equipo. Los integrantes del equipo podrán acceder a través de sus navegadores web.

   Ruta de referencia: https://github.com/


### 5.1.2. Source Code Management.
El proyecto seguirá las convenciones del flujo de trabajo establecido por el modelo GitFlow para el control de versiones, empleando GitHub como plataforma y sistema de control de versiones. A continuación, se describirá la implementación de GitFlow como un flujo de trabajo para el control de versiones, junto con el enlace del Landing Page.

<div align=center>
   <img src="/assets/img-release.png" alt="Release"></img>
</div>

*Repositorio de GitHub:*
- Enlace para acceder a la [organización en GitHub](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw)
- Enlace para acceder al repositorio de la [Link del Landing page] (https://aplicaciones-web-wx55-group-s-del-softw.github.io/landing-page/)
- Enlace para acceder al repositorio del [reporte final](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project)

*Flujo de trabajo GitFlow*

El flujo de trabajo a ser implementado para el desarrollo del proyecto se basará en el modelo propuesto por Vincent Driessen en "A successful Git branching model".

## Imagen de Realese branches

*Estructura de branches (Ramas):*
1. *Master branch (Rama principal):* Esta rama servirá como la principal para la aplicación, alojando versiones estables y finales del desarrollo. Únicamente se aceptarán cambios que hayan sido previamente probados y verificados en los features y de ahí en Developer.
2. *Develop branch (Rama de desarrollo):* El propósito de esta rama es facilitar los avances del proyecto en equipo y mantener los archivos centrales del desarrollo continuo.
3. *Feature branch(Ramas de funcionalidad):* Cada capitulo desarrollado por el equipo, o separada del enfoque actual del desarrollo, tendrá su propia rama. Una vez que una funcionalidad esté completamente trabajada, se fusionará con la rama de desarrollo del proyecto. Las convenciones para nombrar las ramas de funcionalidad seguirán un patrón descriptivo y único, por ejemplo, "feature/chapter-#".
### 5.1.3. Source Code Style Guide & Conventions.
*HTML:* Algunas de las prácticas que deben de seguirse para alcanzar un código coherente, sostenible y ordenado son las
siguientes:
1. Cerrar todos los elementos HTML: Por ejemplo, <p>Esto es un párrafo.</p>
2. Siempre declarar el tipo de documento en la primera línea del documento, para
   HTML es "<!DOCTYPE html>”.
3. Escribir en una línea los comentarios cortos.
4. Utilizar comillas en caso de que los atributos contengan espacios entre sí.
5. Procurar especificar el texto alt y las dimensiones width y height de las imágenes, ya que de esta manera se facilitará la
   disponibilidad del contenido.
6. Se nos recomienda no usar el espacio al momento de utilizar los signos porque
   es más fácil de leerlo de esta forma.  
   <br>
   HTML: (https://www.w3schools.com/html/html5_syntax.asp)

*CSS:* Entre las prácticas empleadas se menciona:

1. Se nos recomienda tener una sangría por 2 espacios a la vez, no debemos
   utilizar tabulaciones ni mezclarlas tabulaciones con espacios para la sangría.
2. Todo el código debe estar en minúscula.
3. Eliminar los espacios en blanco.
4. Usar comentarios para explicar el código.
5. Utilizar nombres de clase significativos o genéricos, nombres que reflejen el
   propósito de su elemento.  
   <br>

   CSS: (https://google.github.io/styleguide/htmlcssguide.html)

*Tailwind:* Entre las prácticas empleadas se menciona:

1. Utiliza clases utilitarias individuales en lugar de estilos personalizados.
2. Combina múltiples clases utilitarias para estilos complejos.
3. Usa prefijos contextuales para clasificar clases según el contexto o componente.  
   <br>

   Tailwind:(https://tailwindcss.com/docs/adding-custom-styles)




### 5.1.4. Software Deployment Configuration.

<div align=center>
   <img src="/assets/img-software-develop.png" alt="software-configuration"></img>
</div>

### Landing page deployment:
Para desplegar la landing page es necesario contar con una serie de requisitos, entre ellos, es necesario contar con
una cuenta personal, una organización y un repositorio al cual cargar los documentos. A partir de lo anterior, es posible
comenzar el despliegue de la landing page. A continuación se enuncian los pasos a seguir:

1. Crear una carpeta llamada "docs" para alojar el Landing Page.
2. Asegurarse de que los archivos sigan las nomenclaturas "index.html", para la landing page; "input.css" y "output.css" para poder utilizar Tailwind y
   una carpeta llamada "img" que contenga las imágenes.
3. Cargar los archivos al repositorio mediante un commit.
4. Dirigirse a Settings > Pages y seleccionar el branch correspondiente, en nuestro caso es el "main".
5. Especificar la carpeta "docs" como la fuente de la página.
6. Esperar a que GitHub realice las comprobaciones necesarias. Una vez culminado el proceso, se obtendrá un enlace que
   llevará al Landing Page desplegado

##  GithubPages

### 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1 Sprint 1.
#### 5.2.1.1 Sprint Planing 1.

En el marco de Scrum, un Sprint es un período de tiempo definido y breve en el que un equipo de desarrollo trabaja en
las tareas necesarias para lograr un objetivo específico del producto, conocido como "Product Goal". En el proyecto de
desarrollo de FarmLogiTech, se han planificado cuatro sprints, cada uno con una duración de dos semanas.


Durante el Sprint #1, que inicia el 06/04/2024, el objetivo principal es desarrollar una landing page
llamativa para FarmLogiTech. Esta página se diseñará para atraer a los visitantes y comunicar de manera efectiva los beneficios del producto. En resumen,
durante este sprint nos enfocaremos en el diseño y desarrollo de la landing page para cumplir con nuestros objetivos.

| Sprint | Prepared Date | Time      | Location                              | Prepared By     | Attendees                                                                                   | Sprint 1 Goal                                                                               | Sprint 1 Velocity | Sum of Story Points |
|--------|---------------|-----------|---------------------------------------|-----------------|---------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|-------------------|---------------------|
|   1    | 13/04/2024    | 11:00  PM | Reunión virtual mediante Google meet  | Rodrigo Aguilar | Rodrigo Aguilar, Mathias Kunimoto, Giacomo Zoppi, Fernando Salgado, Jean franco Barrionuevo | Elaborar y diseñar una landing page atractiva e informativa para la aplicación FarmLogiTech | 22                | 22                  |

#### 5.2.1.2. Sprint Backlog 1.
En el primer sprint, el equipo tuvo como objetivo principal crear una landing page atractiva y funcional. Utilizamos la herramienta Trello para organizar y asignar tareas a los miembros del equipo según sus habilidades.

<div align=center>
   <img src="/assets/img-trello.png" alt="Trello"></img>
</div>

link del trello: https://trello.com/b/H1ovwIyt/aplicaciones-web

<table align="center" border="1" width="90%" style="text-align:center">
    <tr>
       <td colspan="1"><b>Sprint #</b></td>
       <td colspan="7"><b>Sprint 1</b></td>
     </tr>
     <tr>
       <td colspan="2"><b>User Story</b></td>
      <td colspan="6"><b>Work-Item / Task</b></td>
     </tr>
     <tr>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Description</b></td>
       <td><b>Estimation(Hours)</b></td>
       <td><b>Assigned To</b></td>
       <td><b>Status(To-do/ In-Process/ To-Review/ Done)</b></td>
     </tr>
     <tr>
   <tr>
       <td>US01</td>
       <td>Descripcion clara de los servicios</td>
       <td>T01</td>
       <td>Agregar divs para los servicios  en la landing page</td>
       <td>Diseñar los servicios que ofrecemos usando divs</td>
       <td>5</td>
       <td>Mathias Kunimoto</td>
       <td>Done</td>
    </tr>
<tr>
       <td>US06</td>
       <td>Interacción de imágenes en la landing page</td>
       <td>T02</td>
       <td>Agregar un carrusel en la landing page</td>
       <td>Diseñar un carrusel para la interacción con el usuario</td>
       <td>5</td>
       <td>Rodrigo Aguilar </td>
       <td>Done</td>
    </tr>
<tr>
       <td>US02</td>
       <td> Planes de suscripción en la landing page</td>
       <td>T03</td>
       <td>Agregar divs para las suscripciones en la landing page</td>
       <td>Diseñar los planes que ofrecemos usando divs</td>
       <td>5</td>
       <td>Giacomo Zoppi</td>
       <td>Done</td>
    </tr>
<tr>
<tr>
       <td>US02</td>
       <td> Métodos de pago en la landing page</td>
       <td>T04</td>
       <td>Agregar divs para los métodos de pago en la landing page</td>
       <td>Colocar las imagenes de los métodos de pagos usando div</td>
       <td>6</td>
       <td>Giacomo Zoppi</td>
       <td>Done</td>
    </tr>
<tr>
<tr>
       <td>US02</td>
       <td> Planes de suscripción en la landing page</td>
       <td>T05</td>
       <td>Agregar interacción con los planes</td>
       <td> Añadir la función hover para planes interactivos</td>
       <td>5</td>
       <td>Jean Franco Barrionuevo</td>
       <td>Done</td>
    </tr>
<tr>
       <td>US04</td>
       <td>Adaptación de landing page a dispositivos</td>
       <td>T06</td>
       <td>Agregar responsive </td>
       <td>Añadir responsXive al landing page para que se pueda acoplar a cualquier dispositivo</td>
       <td>5</td>
       <td>Mathias Kunimoto</td>
       <td>Done</td>
    </tr>
 <td>US05</td>
       <td>Adaptación de sección de colaboradores en la landing page </td>
       <td>T07</td>
       <td>Agregar Colaboradores </td>
       <td>Añadir creadores del  landing page </td>
       <td>4</td>
       <td>Fernando Salgado</td>
       <td>Done</td>
    </tr>

   </table>




#### 5.2.1.3. Development Evidence for Sprint Review.
| Repository                                                      | Branch              | Commit id | Commit Message                             | Commit Message Body                                                            | Commited on (Date) |
|-----------------------------------------------------------------|---------------------|--------|--------------------------------------------|--------------------------------------------------------------------------------|-------------------- 
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/landing-page | add-carousel-images | 2db2724 | feat: update index(image carousel)         |  feat: update index(image carousel)                           | 13/04/2024         | 
|                                                                 | add-carousel-images | 2db2724 | feat: added carousel images| feat: added carousel images| 13/04/2024         | 
|                                                                 | add-rates-box       | eb93732 | feat: added rates box      | feat: added rates box       | 13/04/2024         | 
|                                                                 | main                | 845b3a2 | fix: update landing page structure                     | fix: update landing page structure | 13/04/2024         | 
|                                                                 | payment_method      | 845b3a2 | fix: update landing page structure                     | fix: update landing page structure| 13/04/2024         | 
|  | add-features-boxes  | 8d4b6f2 | feat: added features boxes                 |feat: added features boxes | 13/04/2024         |
|  | add-about-us        | 581c794 | feat: added about us                |feat: added about us | 13/04/2024         |
#### 5.2.1.4 Testing Suite Evidence for Sprint Review.`

Para la entrega del Sprint 1, logramos completar el desarrollo, la implementación y el despliegue del Landing Page. Por esta razón, nos enfocamos en la sección de "acceptance-tests" en la implementación de los archivos feature que componen nuestro landing page. Estos features se basan en las Historias de Usuario especificadas en el sprint backlog, detallando cada uno de los escenarios que planeamos desarrollar.
<table align="left" border="1" width="100%">
  <tr>
    <th>Repository</th>
    <th >Branch</th>
    <th>Commit</th>
    <th>Author</th>
    <th>Message</th>
    <th>Date</th>
  </tr>
  <tr>
    <td>landing-page</td>
    <td>Features_testing</td>
    <td>07fa8d6</td>
    <td>Giacomo Zoppi</td>
    <td>doc: add acceptance tests</td>
    <td>11/04/2024</td>
  </tr>
</table>



#### 5.2.1.5. Execution Evidence for Sprint Review.
Durante el Sprint 1, logramos la implementación y despliegue del Landing Page. Muestra diversas secciones donde los usuarios pueden encontrar información relevante sobre el producto. A continuación, se presentan algunas evidencias del progreso realizado.

1. Sección  carrusel de imágenes
   En esta sección, se puede visualizar e interactuar con las imágenes principales.

<div align=center>
   <img src="/assets/img-carrusel-1.png" alt="Carrusel"></img>
</div>

2. Sección de Nosotros
   En esta sección, se puede observar lo que FarmLogitech ofrece.

<div align=center>
   <img src="/assets/img-nosotros-1.png" alt="Nosotros"></img>
</div>

3. Sección de Características
   En esta sección, se puede observar las caracteristicas.

<div align=center>
   <img src="/assets/img-caracteristicas-1.png" alt="Caracteristicas"></img>
</div>

4. Sección Planes
   En esta sección, se visualizan los planes que Farmlogitech, plan básico en el que solo
   podrás promocionar tu granja y el premium en la que no solo podrás promocionarla, sino también gestionarla.

<div align=center>
   <img src="/assets/img-planes-1.png" alt="Planes"></img>
</div>

5. Sección Método de Pago
   En esta sección, se visualizan diversos métodos de pago que Farmlogitech ofrece

<div align=center>
   <img src="/assets/img-metodos-1.png" alt="Metodos"></img>
</div>

6. Sección Colaboradores
   En esta sección, aparecerán los colaboradores encargados de desarrollar la landing page.

<div align=center>
   <img src="/assets/img-colaboradores-1.png" alt="Colaboradores"></img>
</div>

### 5.2.1.6. Services Documentation Evidence for Sprint Review.
Para este primer sprint no fue contemplada la evidencia de documentación de los servicios.


### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Para la entrega del Sprint número 1, se desplegó la landing page completa.

<div align=center>
   <img src="/assets/img-todo-1.png" alt="Landing"></img>
</div>

Enlace para acceder a la landing page: https://aplicaciones-web-wx55-group-s-del-softw.github.io/landing-page/

### 5.2.1.8. Team Collaboration Insights during Sprint.

| Alumno                  | Actividad                                                   | 
|-------------------------|-------------------------------------------------------------|
| Rodrigo Aguilar         | Implementación de sección caracteristicas                   |
| Fernando Salgado        | Implementación de sección Nosotros                          |
| Mathias Kunimoto        | Implementación del responsive y características del website |
| Jean Franco Barrionuevo | Implementación de la imagenes de carrusel                   |
| Giacomo Zoppi           | Implementación de las tarifas o planes                      |

<div align=center>
   <img src="/assets/img-graficos.png" alt="graficos"></img>
</div>

<div align=center>
   <img src="/assets/img-graficos-2.png" alt="graficos2"></img>
</div>

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 5.2. Frontend Web Application
### 5.2.1 Sprint 2.
#### 5.2.2.1 Sprint Planing 2.

A partir del 23/04/2024 el segundo sprint tiene como meta corregir errores en la landing page y desarrollar el website, así como una fake API, de manera que resulten atractivos y completamente funcionales.

| Sprint | Prepared Date | Time      | Location                              | Prepared By     | Attendees                                                                                   | Sprint 2 Goal                                          | Sprint 1 Velocity | Sum of Story Points |
|--------|---------------|-----------|---------------------------------------|-----------------|---------------------------------------------------------------------------------------------|--------------------------------------------------------|-------------------|---------------------|
|   2    | 23/04/2024    | 11:30  PM | Reunión virtual mediante Google meet  | Rodrigo Aguilar | Rodrigo Aguilar, Mathias Kunimoto, Giacomo Zoppi, Fernando Salgado, Jean franco Barrionuevo | Implementar la website para la aplicación FarmLogiTech | 22                | 22                  |

#### 5.2.2.2. Sprint Backlog 2.
En el segundo sprint, el equipo tuvo como objetivo principal crear la website atractiva y funcional. Utilizamos la herramienta Trello para organizar y asignar tareas a los miembros del equipo según sus habilidades.

<div align=center>
   <img src="/assets/img-trello-sprint2.png" alt="Trello"></img>
</div>

link del trello: https://trello.com/b/H1ovwIyt/aplicaciones-web

<table align="center" border="1" width="90%" style="text-align:center">
    <tr>
       <td colspan="1"><b>Sprint #</b></td>
       <td colspan="7"><b>Sprint 2</b></td>
     </tr>
     <tr>
       <td colspan="2"><b>User Story</b></td>
      <td colspan="6"><b>Work-Item / Task</b></td>
     </tr>
     <tr>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Description</b></td>
       <td><b>Estimation(Hours)</b></td>
       <td><b>Assigned To</b></td>
       <td><b>Status(To-do/ In-Process/ To-Review/ Done)</b></td>
     </tr>
     <tr>
   <tr>
       <td>US10</td>
       <td>Crear y asignar tareas a los trabajadores</td>
       <td>T01</td>
       <td>Agregar funcionalidades para implementar la asignación</td>
       <td>Diseñar la tabla de tareas en donde se va a ir almacenando</td>
       <td>6</td>
       <td>Fernando Salgado /
            Rodrigo Aguilar /
            Jean Barrionuevo</td>
       <td>Done</td>
    </tr>
<tr>
       <td>US12</td>
       <td>Registro de progreso de tareas</td>
       <td>T02</td>
       <td>Agregar una tabla de tareas</td>
       <td>Diseñar la tabla de tareas y hacer que funcione el registro</td>
       <td>5</td>
       <td>Jean Barrionuevo</td>
       <td>Done</td>
    </tr>
<tr>
       <td>US14</td>
       <td>Ver información detallada de las granjas</td>
       <td>T03</td>
       <td>Agregar interaccion cuando presiones una carta</td>
       <td>Al realizar la interacción se mostrará informacion de la granja</td>
       <td>5</td>
       <td>Giacomo Zoppi</td>
       <td>Done</td>
    </tr>
<tr>
<tr>
       <td>US15</td>
       <td>Buscador de granjas con filtros</td>
       <td>T05</td>
       <td>Implementar cartas y que se filtren mediante la busqueda</td>
       <td> Añadir información del lugar y presionar buscar</td>
       <td>6</td>
       <td>Mathias Kunimoto</td>
       <td>Done</td>
    </tr>
<tr>
       <td>US16</td>
       <td> Acceso a valoraciones de otras empresas sobre granjas</td>
       <td>T06</td>
       <td>Agregar valoraciones </td>
       <td>Añadir sección de valorar una granja</td>
       <td>5</td>
       <td>Fernando Salgado</td>
       <td>Done</td>
    </tr>
 <td>US-19</td>
       <td>Visualizacion de información detallada sobre el estado de cultivos y ganado</td>
       <td>T07</td>
       <td>Visualización estado de cultivo y ganado</td>
       <td>Información detallada sobre el estado</td>
       <td>5</td>
       <td>Giacomo Zoppi</td>
       <td>Done</td>
    </tr>
    </tr>
 <td>US-20</td>
       <td>Visualizacion de estadísticas financieras</td>
       <td>T07</td>
       <td>Revisión de estadísticas financieras</td>
       <td>Revisión detallada de estadísticas</td>
       <td>6</td>
       <td>Jean Barrionuevo</td>
       <td>Done</td>
    </tr>
    </tr>
 <td>US-21</td>
       <td>Registro del cumplimiento de tareas de producción</td>
       <td>T07</td>
       <td>Listeo del cumplimiento de tareas de producción</td>
       <td>Registro completo del cumplimiento de tareas de producción</td>
       <td>7</td>
       <td>Fernando Salgado /
            Rodrigo Aguilar /
            Jean Barrionuevo</td>
       <td>Done</td>
    </tr>
 <td>US-22</td>
       <td>Emitir alertas de emergencia</td>
       <td>T07</td>
       <td>Informar alertas de emergencia</td>
       <td>Emitir informe de alertas de emergencia</td>
       <td>6</td>
       <td>Fernando Salgado /
            Rodrigo Aguilar /
            Jean Barrionuevo</td>
       <td>Done</td>
    </tr>
 <td>US-26</td>
       <td>Verificacion de estado de actividades diarias y tiempo dedicado por los trabajadores</td>
       <td>T07</td>
       <td>Verificación de estado de actividades</td>
       <td>Revision de estado de actividades</td>
       <td>6</td>
       <td>
            Rodrigo Aguilar /
            Jean Barrionuevo</td>
       <td>Done</td>
    </tr>

   </table>




#### 5.2.2.3. Development Evidence for Sprint Review.
| Repository                                                      | Branch              | Commit id | Commit Message                             | Commit Message Body                 | Commited on (Date) |
|-----------------------------------------------------------------|---------------------|--------|--------------------------------------------|-------------------------------------|-------------------- 
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/frontend-application.git | feature/communication-management | ce9ad2f | feat(communication-management): added description and history    | feat: added description and history | 01/05/2024         | 
|                                                                 | feature/dashboard-analytics | b2e000f |feat(dashboard-analytics): updated task-card|feat: updated task-card        | 01/05/2024         | 
|                                                                 | feature/monitoring       | 88aa536 |Fix(monitoring): fixed conlficts with dashboard      |Fix: fixed conlficts with dashboard               | 01/05/2024         | 
|                                                                 | feature/monitoring-api-weather               | 8d9527d | fix(monitoring-api-weather): fixed merge with develop                 | fix: fixed merge with develop  | 01/05/2024         | 
|                                                                 | payment_method      | 845b3a2 | fix: update landing page structure                   | fix: update landing page structure  | 01/05/2024         | 
|  | feature/search-and-match  | f51e052 |feat(search-and-match): updated task description                |feat: updated task description          | 02/05/2024         |
|  | feature/social-interaction       | 68969ae |feat(social-interaction): implementation of the components                |feat: implementation of the components               | 01/05/2024         |
#### 5.2.2.4 Testing Suite Evidence for Sprint Review.`

Durante la entrega del segundo sprint, el equipo tuvo como objetivo principal implementar la website y que tenga funcionamiento. Utilizamos la herramienta Trello para organizar y asignar tareas a los miembros del equipo según sus habilidades.
<table align="left" border="1" width="100%">
  <tr>
    <th>Repository</th>
    <th >Branch</th>
    <th>Commit</th>
    <th>Author</th>
    <th>Message</th>
    <th>Date</th>
  </tr>
  <tr>
    <td>frontend-application</td>
    <td>develop</td>
    <td>25c0e1e</td>
    <td>Rodrigo Aguilar</td>
    <td>feat(develop): update complete</td>
    <td>01/05/2024</td>
  </tr>
</table>

<br/><br/>
<br/><br/>

#### 5.2.2.5. Execution Evidence for Sprint Review.
Durante el Sprint 2, logramos la implementación y despliegue del website. Muestra diversas secciones donde los usuarios pueden encontrar información relevante sobre el producto. A continuación, se presentan algunas evidencias del progreso realizado.

1. Sección  home<br/><br/>
   En esta sección, se puede visualizar e interactuar con las granjas.

<div align=center>
   <img src="/assets/img-website-1.jpeg" alt="Website1"></img>
</div>

2. Sección de detalles de granja<br/><br/>
   En esta sección, se puede observar informacion detallada de una granja.

<div align=center>
   <img src="/assets/img-website-2.jpeg" alt="Website2"></img>
</div>

3. Sección de Collaborator<br/><br/>
   En esta sección, se puede observar los distintos aspectos que se puede realizar.

<div align=center>
   <img src="/assets/img-website-3.jpeg" alt="Website3"></img>
</div>

4. Sección Clima <br/><br/>
   En esta sección, se visualizan el estado y pronostico del clima.
<div align=center>
   <img src="/assets/img-website-5.jpeg" alt="Clima"></img>
</div>

5. Sección Emergencias<br/><br/>
   En esta sección, se visualizan la funcion de estado de emergencia de la granja.

<div align=center>
   <img src="/assets/img-website-6.jpeg" alt="Metodos"></img>
</div>

6. Sección Inventario<br/><br/>
   En esta sección, aparecerán el estado de inventario de animales y cultivos.

<div align=center>
   <img src="/assets/img-website-7.jpeg" alt="Inventario"></img>
</div>

7. Sección Entrar<br/><br/>
   En esta sección, aparecerán opciones para entrar.

<div align=center>
   <img src="/assets/img-website-8.jpeg" alt="Entrar"></img>
</div>

8. Sección Tareas<br/><br/>
   En esta sección, aparecerán el estado de tareas.

<div align=center>
   <img src="/assets/img-website-9.jpeg" alt="Tareas"></img>
</div>

8. Sección Asignacion de Tareas<br/><br/>
   En esta sección, aparecerán la asignacion de tareas.

<div align=center>
   <img src="/assets/img-website-10.jpeg" alt="Asignacion"></img>
</div>

8. Sección Estadisticas<br/><br/>
   En esta sección, aparecerán las estadisticas y resultados del tiempo que revisen.

<div align=center>
   <img src="/assets/img-website-11.jpeg" alt="Estadisticas"></img>
</div>

### 5.2.2.6. Services Documentation Evidence for Sprint Review.
Para este segundo sprint no fue contemplada la evidencia de documentación de los servicios.


### 5.2.2.7. Software Deployment Evidence for Sprint Review.

Para la entrega del Sprint número 2, se desplegó la website completa.

<div align=center>
   <img src="/assets/img-website-sprint2.jpeg" alt="Website"></img>
</div>

Enlace para acceder a la website: https://farmlogitech-aw.web.app/

### 5.2.2.8. Team Collaboration Insights during Sprint.

| Alumno                  | Actividad                                                              | 
|-------------------------|------------------------------------------------------------------------|
| Rodrigo Aguilar         | Implementación de monitoring-api-weather                               |
| Fernando Salgado        | Implementación de communication-management<br/> and social-interaction |
| Mathias Kunimoto        | Implementación de search-and-match                                     |
| Jean Franco Barrionuevo | Implementación de dashboard-analytics                                  |
| Giacomo Zoppi           | Implementación de monitoring                                           |

<div align=center>
   <img src="/assets/img-sprint-2.png" alt="Sprint 2"></img>
</div>


## 5.2.3. Sprint 3
### 5.2.3.1. Sprint Planning 3
El spring 3 tiene como inicio el dia 13/05/2024 y como objetivo plantea completar el frontend de nuestra aplicación web y realizar el backend.

<table>
<tr><td>Sprint #</td><td>Sprint 3</td></tr>
<tr><td colspan="2">Sprint Planning Background</td></tr>
<tr><td>Date</td><td>2024-05-13</td></tr>
<tr><td>Time</td><td>7:00 PM</td></tr>
<tr><td>Location</td><td>Meet virtual meeting</td></tr>
<tr><td>Prepared by</td><td>Rodrigo Aguilar</td></tr>
<tr><td>Atendees</td><td>Mathias Kunimoto, Fernando Salgado, Giacomo Zoppi, Jean Franco Barrionuevo</td></tr>
<tr><td>Sprint 3 Review</td><td>En el Sprint 3 desarrollamos la mayoría de apartados de nuestra aplicación, declaramos los bounded context y features a utilizar para lograr un desarrollo uniforme y consistente. El product owner estuvo satisfecho con el manejo de desarrollo que tuvimos en el equipo.</td></tr>
<tr><td>Sprint 3 Retrospective</td><td>En el anterior sprint pudimos mejorar la comunicación y el empleo de herramientas de administración para obtener un progreso más rápido en el desarrollo del frontend. Se mejoraron detalles como la estructuración de los componentes y la consistencia del diseño en todos los features.</td></tr>
<tr><td colspan="2">Sprint Goal & User Stories</td></tr>
<tr><td>Sprint 3 Goal</td><td>Desarrollar el frontend completamente y avanzar en gran medida el backend, logrando satisfacer la mayoría de las user stories relacionadas con la lógica del negocio.</td></tr>
<tr><td>Sprint 3 Velocity</td><td>49</td></tr>
<tr><td>Sum of story points</td><td>49</td></tr>
</table>

### 5.2.3.2. Sprint Backlog 3

En este sprint backlog, desarrollamos completamente el frontend y en gran medida el backend, satisfaciendo la mayoría de las user stories. La herramienta utilizada para la organización del equipo fue Trello. Esta herramienta nos permitió tener en claro las tareas por desarrollar para asignarlas según las fortalezas de cada miembro del equipo.
<img src="/assets/img-trello-sprint2.png" alt="Repo 1"/></img>
Trello Link: [https://trello.com/invite/b/H1ovwIyt/ATTIa06b8aa26ddc1b1aa652cdb1647fd69f7C984655/aplicaciones-web](https://trello.com/invite/b/WJXt50JP/ATTI255cf1b0d82284ff8d327dd3f64225d622C4A319/farmlogitech)

<table>
  <tr>
    <th>Technical User Story</th>
    <th colspan="5">WorkItem / Task</th>
  </tr>
  <tr>
    <th>Id</th>
    <th>Title</th>
    <th>Id</th>
    <th>Title</th>
    <th>Description</th>
    <th>Estimation (Hours)</th>
    <th>Assigned To</th>
    <th>Status(Todo/InProcess/ToReview/Done)</th>
  </tr>
  <tr>
    <td rowspan="2">US09</td>
    <td rowspan="2">Elegir método de pago para suscripción</td>
    <td>TK01</td>
    <td>Crear endpoint para elegir método de pago</td>
    <td>Crear endpoint que permita la elección del método de pago para la suscripción.</td>
    <td>4</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK02</td>
    <td>Implementar validación de métodos de pago</td>
    <td>Validar los métodos de pago disponibles y su correcto funcionamiento.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US10</td>
    <td rowspan="2">Crear y asignar tareas a los trabajadores</td>
    <td>TK03</td>
    <td>Crear endpoint para asignar tareas</td>
    <td>Crear endpoint para asignar tareas a los trabajadores.</td>
    <td>5</td>
    <td>Giacomo Zoppi</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK04</td>
    <td>Crear lógica de asignación de tareas</td>
    <td>Implementar la lógica que permita asignar tareas según las capacidades y disponibilidad de los trabajadores.</td>
    <td>6</td>
    <td>Jean Franco Barrionuevo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US12</td>
    <td rowspan="2">Registrar progreso de tareas</td>
    <td>TK05</td>
    <td>Crear endpoint para registrar progreso de tareas</td>
    <td>Crear endpoint que permita registrar el progreso de las tareas asignadas.</td>
    <td>4</td>
    <td>Fernando Salgado</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK06</td>
    <td>Implementar validación de progreso</td>
    <td>Validar que el progreso de las tareas sea registrado correctamente en el sistema.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US13</td>
    <td rowspan="2">Buscar y contactar a dueños de granjas potenciales</td>
    <td>TK07</td>
    <td>Crear endpoint para buscar dueños de granjas</td>
    <td>Crear endpoint que permita buscar y contactar a dueños de granjas potenciales.</td>
    <td>5</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK08</td>
    <td>Implementar lógica de contacto</td>
    <td>Implementar la lógica que permita contactar a los dueños de granjas potenciales de manera efectiva.</td>
    <td>5</td>
    <td>Giacomo Zoppi</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US14</td>
    <td rowspan="2">Ver información detallada de granjas</td>
    <td>TK09</td>
    <td>Crear endpoint para obtener detalles de granjas</td>
    <td>Crear endpoint que permita obtener información detallada de las granjas.</td>
    <td>4</td>
    <td>Jean Franco Barrionuevo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK10</td>
    <td>Implementar validación de datos de granjas</td>
    <td>Validar que los datos obtenidos de las granjas sean precisos y completos.</td>
    <td>4</td>
    <td>Fernando Salgado</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US15</td>
    <td rowspan="2">Buscar granjas con filtros específicos</td>
    <td>TK11</td>
    <td>Crear endpoint para buscar granjas con filtros</td>
    <td>Crear endpoint que permita buscar granjas utilizando filtros específicos.</td>
    <td>5</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK12</td>
    <td>Implementar lógica de filtrado</td>
    <td>Implementar la lógica que permita aplicar filtros en la búsqueda de granjas.</td>
    <td>5</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US16</td>
    <td rowspan="2">Acceder a valoraciones y comentarios de otras empresas sobre las granjas</td>
    <td>TK13</td>
    <td>Crear endpoint para valoraciones y comentarios</td>
    <td>Crear endpoint que permita acceder a valoraciones y comentarios de otras empresas sobre las granjas.</td>
    <td>4</td>
    <td>Giacomo Zoppi</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK14</td>
    <td>Implementar validación de valoraciones</td>
    <td>Validar que las valoraciones y comentarios sean precisos y relevantes.</td>
    <td>4</td>
    <td>Fernando Salgado</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US18</td>
    <td rowspan="2">Verificar niveles de inventario</td>
    <td>TK15</td>
    <td>Crear endpoint para verificar inventario</td>
    <td>Crear endpoint que permita verificar los niveles de inventario.</td>
    <td>4</td>
    <td>Jean Franco Barrionuevo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK16</td>
    <td>Implementar lógica de verificación de inventario</td>
    <td>Implementar la lógica que permita verificar los niveles de inventario de manera precisa.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US19</td>
    <td rowspan="2">Ver información detallada sobre el estado de cultivos y ganado</td>
    <td>TK17</td>
    <td>Crear endpoint para obtener estado de cultivos</td>
    <td>Crear endpoint que permita obtener información detallada sobre el estado de cultivos y ganado.</td>
    <td>4</td>
    <td>Giacomo Zoppi</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK18</td>
    <td>Implementar validación de estado de cultivos</td>
    <td>Validar que la información sobre el estado de cultivos y ganado sea precisa.</td>
    <td>4</td>
    <td>Jean Franco Barrionuevo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US20</td>
    <td rowspan="2">Ver estadísticas financieras</td>
    <td>TK19</td>
    <td>Crear endpoint para obtener estadísticas financieras</td>
    <td>Crear endpoint que permita obtener estadísticas financieras detalladas.</td>
    <td>4</td>
    <td>Fernando Salgado</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK20</td>
    <td>Implementar lógica de estadísticas</td>
    <td>Implementar la lógica que permita calcular y mostrar estadísticas financieras.</td>
    <td>4</td>
    <td>Jean Franco Barrionuevo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US21</td>
    <td rowspan="2">Registrar el cumplimiento de tareas con detalles de producción</td>
    <td>TK21</td>
    <td>Crear endpoint para registrar cumplimiento de tareas</td>
    <td>Crear endpoint que permita registrar el cumplimiento de tareas con detalles de producción.</td>
    <td>5</td>
    <td>Jean  Franco Barrionuevo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK22</td>
    <td>Implementar validación de cumplimiento</td>
    <td>Validar que el cumplimiento de tareas y los detalles de producción sean registrados correctamente.</td>
    <td>5</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US22</td>
    <td rowspan="2">Emitir alertas de emergencia de manera eficaz</td>
    <td>TK23</td>
    <td>Crear endpoint para emitir alertas de emergencia</td>
    <td>Crear endpoint que permita emitir alertas de emergencia de manera eficaz.</td>
    <td>4</td>
    <td>Giacomo Zoppi</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK24</td>
    <td>Implementar lógica de alertas de emergencia</td>
    <td>Implementar la lógica que permita emitir y gestionar alertas de emergencia.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US23</td>
    <td rowspan="2">Registrar horas de trabajo para cálculo de salario</td>
    <td>TK25</td>
    <td>Crear endpoint para registrar horas de trabajo</td>
    <td>Crear endpoint que permita registrar las horas de trabajo de los empleados para el cálculo de salario.</td>
    <td>4</td>
    <td>Fernando Salgado</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK26</td>
    <td>Implementar validación de horas de trabajo</td>
    <td>Validar que las horas de trabajo registradas sean precisas para el cálculo de salario.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US24</td>
    <td rowspan="2">Registrar cantidad de ganado enfermo</td>
    <td>TK27</td>
    <td>Crear endpoint para registrar ganado enfermo</td>
    <td>Crear endpoint que permita registrar la cantidad de ganado enfermo.</td>
    <td>4</td>
    <td>Jean Franco Barrionuevo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK28</td>
    <td>Implementar validación de registros de ganado enfermo</td>
    <td>Validar que los registros de ganado enfermo sean precisos y actualizados.</td>
    <td>4</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US26</td>
    <td rowspan="2">Verificar estado de actividades diarias y tiempo dedicado por los trabajadores</td>
    <td>TK29</td>
    <td>Crear endpoint para verificar estado de actividades diarias</td>
    <td>Crear endpoint que permita verificar el estado de actividades diarias y el tiempo dedicado por los trabajadores.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK30</td>
    <td>Implementar validación de actividades diarias</td>
    <td>Validar que los registros de actividades diarias y tiempo dedicado sean precisos.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US30</td>
    <td rowspan="2">Crear API RESTful para acceder a datos agrícolas y ganaderos</td>
    <td>TK31</td>
    <td>Diseñar y crear API RESTful</td>
    <td>Diseñar y crear una API RESTful que permita acceder a datos agrícolas y ganaderos.</td>
    <td>6</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK32</td>
    <td>Implementar endpoints de datos agrícolas y ganaderos</td>
    <td>Implementar los endpoints necesarios para acceder y gestionar datos agrícolas y ganaderos.</td>
    <td>6</td>
    <td>Fernando Salgado</td>
    <td>Done</td>
  </tr>
</table>


### 5.2.3.3 Development Evidence for Sprint Review.

| Repository                                                      | Branch                     | Commit id | Commit Message                                                | Committed on (Date) |
|-----------------------------------------------------------------|----------------------------|--------|---------------------------------------------------------------|---------------------|
| https://farmlogitech-op.web.app/home)                           | feature/dashboard-analitycs|3e468c  | feature: Add method put                                       | 21/05/2024          |
|                                                                 | feature/dashboard-analitycs|d25e83  | feature: Added image filed to farm                             | 21/05/2024          |
|                                                                 | feature/dashboard-analitycs|c642ae  | feat(profiles-managment): Added profile and user.              | 21/05/2024          |
|                                                                 | feature/dashboard-analitycs|b37c18  | feat: add get subscription by id query to subscriptions        | 27/05/2024          |
|                                                                 | feature/dashboard-analitycs|294127  | feat: add social-interaction bounded context                   | 28/05/2024          |
|                                                                 | feature/dashboard-analitycs|bbf1a6  | feat: add all records                                          | 31/05/2024          |
|                                                                 | feature/dashboard-analitycs|2be2c3  | feat(task): repository created and the table are running :)    | 01/06/2024          |
|                                                                 | feature/dashboard-analitycs|c3eabf  | feat(task): Implemented task controller.                       | 01/06/2024          |
|                                                                 | feature/dashboard-analitycs|791547  | feat(feature/task): Added Queries get all task by collaborator with fa… | 01/06/2024          |
|                                                                 | feature/dashboard-analitycs|f0ece0  | feat(feature/dashboard-analitycs): Add aggregates Income and Expense.  | 02/06/2024          |
|                                                                 | feature/monitoring         |8677d1  | fix: update README                                            | 26/05/2024          |
|                                                                 | feature/monitoring         |b3bf62  | feat: add subscription bounded context                        | 26/05/2024          |
|                                                                 | feature/monitoring         |328889  | feat: add subscription command and query service impl          | 26/05/2024          |
|                                                                 | feature/monitoring         |e5e69b  | fix: subscription repository and command service impl fixed    | 26/05/2024          |
|                                                                 | feature/social-interaction |294127  | feat: add social-interaction bounded context                  | 28/05/2024          |
|                                                                 | feature/social-interaction |d7a80b  | feat: fix endpoint and add commands in readme                  | 28/05/2024          |
|                                                                 | feature/profiles-managment |c41ef5  | fix(social interaction): Added valueobject                   | 29/05/2024          |
|                                                                 | feature/profiles-managment |c59490  | feature(social interaction): Update subscription aggregate   | 30/05/2024          |
|                                                                 | feature/profiles-managment |e1fde1  | feature(social-interaction): Added update profile.           | 30/05/2024          |
|                                                                 | feature/profiles-managment |5a142a  | feature(profiles-managment): Update user aggregate           | 30/05/2024          |
|                                                                 | feature/profiles-managment |f7663f  | feature(profiles-managment): Add profileId in subscriptions  | 31/05/2024          |
|                                                                 | feature/profiles-managment |294158  | feature(profiles-managment): Updated get all socials interactions by … | 31/05/2024          |
|                                                                 | feature/subscription       |d72697  | feat: add update subscription command servioce and implementations | 30/05/2024          |
|                                                                 | feature/task               |623d8e  | feat(aggregate): task aggregate created  | 31/05/2024          |
|                                                                 | feature/task               |1d324f  | feat(task): create task command         | 31/05/2024          |
|                                                                 | feature/task               |f524de  | feat(task): add command to aggregate    | 31/05/2024          |
|                                                                 | feature/task               |a10634  | feat(task): create queries               | 31/05/2024          |
|                                                                 | feature/task               |2e4ad5  | feat(task): create services              | 31/05/2024          |


### 5.2.3.4 Testing Suite Evidence for Sprint Review.

Para la entrega del Sprint 3, logramos completar el desarrollo, la implementación y el despliegue del Landing Page, Frontend App y RESTFulAPI. Por esta razón, nos enfocamos en la sección de "acceptance-tests" en la implementación de los archivos feature que componen nuestro proyecto. Estos features se basan en las Historias de Usuario especificadas en el sprint backlog, detallando cada uno de los escenarios que planeamos desarrollar.
<table align="left" border="1" width="100%">
  <tr>
    <th>Repository</th>
    <th >Branch</th>
    <th>Commit</th>
    <th>Author</th>
    <th>Message</th>
    <th>Date</th>
  </tr>
  <tr>
    <td>landing-page</td>
    <td>Features_testing</td>
    <td>07fa8d6</td>
    <td>Giacomo Zoppi</td>
    <td>doc: add acceptance tests</td>
    <td>18/05/2024</td>
  </tr>
</table>
<br>

### 5.2.3.5 Execution Evidence for Sprint Review.
En el sprint 3, logramos un desarrollo parcial del frontend y backend de la aplicación web. Este avance incluye nuevas vistas importantes sobre el producto y la startup, disponibles en inglés y español, así como una versión responsiva. A continuación, se presentan algunas evidencias:

- US09
  <img src="/assets/img-website-page-9.png" alt="US09"/></img>

- US10
  <img src="/assets/img-website-page-13.png" alt="US10"/></img>

- US12
  <img src="/assets/img-website-page-14.png" alt="US12"/></img>

- US14
  <img src="/assets/img-website-page-7.png" alt="US14"/></img>

- US15
  <img src="/assets/img-website-page.png" alt="US15"/></img>

- US16
  <img src="/assets/img-website-page-8.png" alt="US16"/></img>

- US18
  <img src="/assets/img-website-page-15.png" alt="US18"/></img>

- US20
  <img src="/assets/img-statics.png" alt="US20"/></img>

- US21
  <img src="/assets/img-us-21.png" alt="US21"/></img>

- US22
  <img src="/assets/img-website-page-16.png" alt="US22"/></img>

- US26
  <img src="/assets/img-hours.png" alt="US24"/></img>


### 5.2.3.6 Services Documentation Evidence for Sprint Review.

Para el sprint 3, se planificaron tanto el front-end como el back-end. Inicialmente, trabajamos en el mismo repositorio de GitHub, creando repositorios donde incluimos el archivo db.json para luego enlazarlo mediante la creación de rutas.

</br>

<img src="/assets/img-repo1-json.png" alt="Repo 1"/></img>
<img src="/assets/img-repo2-json.png" alt="Repo 2"/></img>
<img src="/assets/img-repo3-json.png" alt="Repo 3"/></img>
<img src="/assets/img-repo4-json.png" alt="Repo 4"/></img>
<img src="/assets/img-repo5-json.png" alt="Repo 5"/></img>

| Endpoint           | Details                                                                                                                                                           |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| /subscription-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /profile-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /farm-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /user-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /task-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /social-controller    | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /shed-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /income-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /expense-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /crop-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /animal-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /message-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |

### Web Service:

| Endpoint                | Operaciones | Parámetros       | URL                                                    |
|-------------------------|-------------|------------------|--------------------------------------------------------|
| subscription-controller | PUT         | {profileId}      | /api/v1/subscription/pay/subscription/{profileId}                                           |
|                         | POST        | No tiene         | /api/v1/subscription                          |
|                         | GET         | {id}             | api/v1/crops/{cropId}/tunnels                          |
|                         | GET         | No tiene         | /api/v1/subscription/all                |
| profile-controller      | GET         | {profileId}      | /api/v1/profile/{profileId}                           |
|                         | PUT         | {profileId}      | /api/v1/profile/{profileId}                                       |
|                         | POST        | No tiene         | /api/v1/profile                           |
|                         | GET         | No tiene         | /api/v1/profile/all                           |
| farm-controller         | GET         | {id}             | /api/v1/farm/{id}                          |
|                         | PUT         | {id}             | /api/v1/farm/{id}                                       |
|                         | POST        | No tiene         | /api/v1/farm                         |
|                         | GET         | {location}       | /api/v1/farm/location/{location}                           |
|                         | GET         | No tiene         | /api/v1/farm/all                         |
|                         | GET         | {profileId}        | /api/v1/farm/all/farms/profile/{profileId}                          |
| user-controller         | POST        | No tiene         | /api/v1/user                                       |
|                         | GET         | No tiene         | /api/v1/user/all                          |
| task-controller         | POST        | No tiene         | /api/v1/task                                      |
|                         | GET         | {farmerId}       | /api/v1/task/all/farmer/{farmerId}                          |
|                         | GET         | {collaboratorId} | /api/v1/task/all/collaborator/{collaboratorId}                          |
| social-controller       | POST        | No tiene         | /api/v1/socials                                      |
|                         | GET         | No tiene         | /api/v1/socials/all                         |
|                         | GET         | {id}             | /api/v1/socials/all/farm/{id}                         |
| shed-controller         | POST        | No tiene         | /api/v1/shed                                      |
|                         | GET         | {id}             | /api/v1/shed/{id}                         |
|                         | GET         | No tiene         | /api/v1/shed/all                        |
| income-controller       | POST        | No tiene         | /api/v1/income                                     |
| expense-controller      | POST        | No tiene         | /api/v1/expense                                     |
| crop-controller         | POST        | No tiene         | /api/v1/crop                                      |
|                         | GET         | {id}             | /api/v1/crop/{id}                         |
|                         | GET         | No tiene         | /api/v1/crop/all                       |
| animal-controller       | POST        | No tiene         | /api/v1/animal                                      |
|                         | GET         | {id}             | /api/v1/animal/{id}                         |
|                         | GET         | No tiene         | /api/v1/animal/all                       |
| message-controller      | POST        | {collaboratorId} | /api/v1/messages/collaborator/{collaboratorId}                                   |

### Web service images:
#### Subscriptions Controller:
<img src="/assets/img-subscriptions-controller-1.png" alt="subscriptions-controller-1"/></img>
<img src="/assets/img-subscriptions-controller-2.png" alt="subscriptions-controller-2"/></img>
<img src="/assets/img-subscriptions-controller-3.png" alt="subscriptions-controller-3"/></img>
<img src="/assets/img-subscriptions-controller-4.png" alt="subscriptions-controller-4"/></img>

#### Profile Controller:
<img src="/assets/profile-controller-1.png" alt="profile-controller-1"/></img>
<img src="/assets/profile-controller-2.png" alt="profile-controller-2"/></img>
<img src="/assets/profile-controller-3.png" alt="profile-controller-3"/></img>
<img src="/assets/profile-controller-4.png" alt="profile-controller-4"/></img>

#### Farm Controller:
<img src="/assets/img-farm-controller-1.png" alt="farm-controller-1"/></img>
<img src="/assets/img-farm-controller-2.png" alt="farm-controller-2"/></img>
<img src="/assets/img-farm-controller-3.png" alt="farm-controller-3"/></img>
<img src="/assets/img-farm-controller-4.png" alt="farm-controller-4"/></img>
<img src="/assets/img-farm-controller-5.png" alt="farm-controller-5"/></img>
<img src="/assets/img-farm-controller-6.png" alt="farm-controller-6"/></img>

#### User Controller:
<img src="/assets/img-user-controller.png" alt="user-controller-1"/></img>
<img src="/assets/img-user-controller-2.png" alt="user-controller-2"/></img>

#### Task Controller:
<img src="/assets/img-task-controller-1.png" alt="task-controller-1"/></img>
<img src="/assets/img-task-controller-2.png" alt="task-controller-1"/></img>
<img src="/assets/img-task-controller-3.png" alt="task-controller-1"/></img>

#### Social Controller:
<img src="/assets/img-social-controller-1.png" alt="social-controller-1"/></img>
<img src="/assets/img-social-controller-2.png" alt="social-controller-1"/></img>
<img src="/assets/img-social-controller-3.png" alt="social-controller-1"/></img>

#### Shed Controller:
<img src="/assets/img-shed-controller.png" alt="shed-controller"/></img>
<img src="/assets/img-shed-controller-2.png" alt="shed-controller-2"/></img>
<img src="/assets/img-shed-controller-3.png" alt="shed-controller-3"/></img>

#### Income Controller:
<img src="/assets/img-income-controller.png" alt="income-controller"/></img>

#### Expense Controller:
<img src="/assets/img-expense-controller.png" alt="expense-controller"/></img>

#### Crop Controller:
<img src="/assets/img-crop-controller-1.png" alt="crop-controller"/></img>
<img src="/assets/img-crop-controller-2.png" alt="crop-controller-2"/></img>
<img src="/assets/img-crop-controller-3.png" alt="crop-controller-3"/></img>

#### Animal Controller:
<img src="/assets/img-animal-controller-1.png" alt="animal-controller"/></img>
<img src="/assets/img-animal-controller-2.png" alt="animal-controller-2"/></img>
<img src="/assets/img-animal-controller-3.png" alt="animal-controller-3"/></img>

#### Message Controller:
<img src="/assets/img-message-controller.png" alt="message-controller"/></img>

#### Link del repositorio:
(https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git)

#### Web service commit details:

| Repository                                                      | Branch                     | Commit id | Commit Message                                              | Committed on (Date) |
|-----------------------------------------------------------------|----------------------------|-----------|-------------------------------------------------------------|---------------------|
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                         | feature/dashboard-analitycs|           | feature: Add method put                                     | 21/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                              | feature/dashboard-analitycs| 62acbc    | feat: added farm aggregate                            | 21/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                               | feature/dashboard-analitycs| 4023f4    | feat: added base repository             | 21/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                               | feature/dashboard-analitycs| 88d6d0    | feat: add farm repository       | 27/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                               | feature/dashboard-analitycs| 6518bc    | feat: Added farm command service                  | 28/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/dashboard-analitycs| bbf1a6    | feat: fixed settings                                        | 31/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/dashboard-analitycs| 6c0501    | feat: Added unversioned files    | 01/06/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/dashboard-analitycs| 9dddac    | feat: Added Query Services                      | 01/06/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/dashboard-analitycs| b97e77    | feat: Added Expenses and Incomes  | 01/06/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/monitoring         | 8677d1    | fix: Added Crops, CropRepository                                           | 26/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/monitoring         | ea165a    | feat: added animal command and queries services                        | 26/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/monitoring         | 26c939    | feat: Implemented Application and Interfaces Layer        | 26/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/monitoring         | b4d480    | fix: Fixed read and delete commands    | 26/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/social-interaction | 11e868    | feat:  irating query service updated                 | 28/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/social-interaction | d7a80b    | feat: fix endpoint and add commands in readme                | 28/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/profiles-managment | c7ce25    | fix(social interaction): rating repository implemented                 | 29/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/profiles-managment | 9fb029    | fix(social interaction):  Irating repository implemented                 | 29/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/profiles-managment | c59490    | feature(social interaction): Update subscription aggregate | 30/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/profiles-managment | e1fde1    | feature(social-interaction): Added update profile.         | 30/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                               | feature/profiles-managment | 5a142a    | feature(profiles-managment): Update user aggregate         | 30/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                               | feature/profiles-managment | f7663f    | feature(profiles-managment): Add profileId in subscriptions | 31/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                               | feature/profiles-managment | 294158    | feature(profiles-managment): Updated get all socials interactions by … | 31/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                               | feature/subscription       | 5ebd6f    | feat: Added Subscription | 30/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                               | feature/subscription       | 1dc194    | feat: fixed unversioned files and password   | 30/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                               | feature/task               | 623d8e    | feat(aggregate): task aggregate created  | 31/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/task               | 1d324f    | feat(task): create task command         | 31/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/task               | f524de    | feat(task): add command to aggregate    | 31/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/task               | a10634    | feat(task): create queries               | 31/05/2024          |
| https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git                                                                | feature/task               | 2e4ad5    | feat(task): create services              | 31/05/2024          |

### 5.2.3.7 Software Deployment Evidence for Sprint Review.

Para la entrega del tercer sprint, se implementó una landing page completamente funcional, cumpliendo con las historias de usuario correspondientes. Además, se desplegó y lanzó parcialmente el back-end, el cual aún está en proceso de finalización.

Landin Page:

La actualización de la página de destino en GitHub Pages se realizó tras fusionar la rama "develop" con la rama principal ("main"). Este proceso permitió renovar la implementación de la página de destino.

- Capturas de pantalla landing page:
  <img src="/assets/img-carrusel-1.png" alt="landing-page"/></img>
  <img src="/assets/img-nosotros-1.png" alt="landing-page"/></img>
  <img src="/assets/img-caracteristicas-1.png" alt="landing-page"/></img>
  <img src="/assets/img-metodos-1.png" alt="landing-page"/></img>
  <img src="/assets/img-colaboradores-1.png" alt="landing-page"/></img>

- Web Application Front-end:

Prueba de que esta enlazado con el Netlify

<img src="/assets/img-deployment.png" alt="landing-page"/></img>

- Capturas de pantalla landing page:

  <img src="/assets/img-website-page-1.png" alt="website"/></img>
  <img src="/assets/img-website-page-2.png" alt="website"/></img>
  <img src="/assets/img-website-page-3.png" alt="website"/></img>
  <img src="/assets/img-website-page-4.png" alt="website"/></img>
  <img src="/assets/img-website-page-5.png" alt="website"/></img>
  <img src="/assets/img-website-page-6.png" alt="website"/></img>
  <img src="/assets/img-website-page-7.png" alt="website"/></img>
  <img src="/assets/img-website-page-8.png" alt="website"/></img>
  <img src="/assets/img-website-page-9.png" alt="website"/></img>
  <img src="/assets/img-website-page-10.png" alt="website"/></img>
  <img src="/assets/img-website-page-11.png" alt="website"/></img>
  <img src="/assets/img-website-page-12.png" alt="website"/></img>
  <img src="/assets/img-website-page-13.png" alt="website"/></img>
  <img src="/assets/img-website-page-14.png" alt="website"/></img>
  <img src="/assets/img-website-page-15.png" alt="website"/></img>
  <img src="/assets/img-website-page-16.png" alt="website"/></img>
  <img src="/assets/img-website-page-17.png" alt="website"/></img>

- Web Application Back-end:

  <img src="/assets/img-base-de-dato-workbrench-1.png" alt="Base de datos"/></img>
  <img src="/assets/img-base-de-dato-workbrench-2.png" alt="Base de datos"/></img>


- Capturas de pantalla de Web Application:

<img src="/assets/img-subscriptions-controller-1.png" alt="subscriptions-controller-1"/></img>
<img src="/assets/img-subscriptions-controller-2.png" alt="subscriptions-controller-2"/></img>
<img src="/assets/img-subscriptions-controller-3.png" alt="subscriptions-controller-3"/></img>
<img src="/assets/img-subscriptions-controller-4.png" alt="subscriptions-controller-4"/></img>
<img src="/assets/profile-controller-1.png" alt="profile-controller-1"/></img>
<img src="/assets/profile-controller-2.png" alt="profile-controller-2"/></img>
<img src="/assets/profile-controller-3.png" alt="profile-controller-3"/></img>
<img src="/assets/profile-controller-4.png" alt="profile-controller-4"/></img>
<img src="/assets/img-farm-controller-1.png" alt="farm-controller-1"/></img>
<img src="/assets/img-farm-controller-2.png" alt="farm-controller-2"/></img>
<img src="/assets/img-farm-controller-3.png" alt="farm-controller-3"/></img>
<img src="/assets/img-farm-controller-4.png" alt="farm-controller-4"/></img>
<img src="/assets/img-farm-controller-5.png" alt="farm-controller-5"/></img>
<img src="/assets/img-farm-controller-6.png" alt="farm-controller-6"/></img>
<img src="/assets/img-user-controller.png" alt="user-controller-1"/></img>
<img src="/assets/img-user-controller-2.png" alt="user-controller-2"/></img>
<img src="/assets/img-task-controller-1.png" alt="task-controller-1"/></img>
<img src="/assets/img-task-controller-2.png" alt="task-controller-1"/></img>
<img src="/assets/img-task-controller-3.png" alt="task-controller-1"/></img>
<img src="/assets/img-social-controller-1.png" alt="social-controller-1"/></img>
<img src="/assets/img-social-controller-2.png" alt="social-controller-1"/></img>
<img src="/assets/img-social-controller-3.png" alt="social-controller-1"/></img>
<img src="/assets/img-shed-controller.png" alt="shed-controller"/></img>
<img src="/assets/img-shed-controller-2.png" alt="shed-controller-2"/></img>
<img src="/assets/img-shed-controller-3.png" alt="shed-controller-3"/></img>
<img src="/assets/img-income-controller.png" alt="income-controller"/></img>
<img src="/assets/img-expense-controller.png" alt="expense-controller"/></img>
<img src="/assets/img-crop-controller-1.png" alt="crop-controller"/></img>
<img src="/assets/img-crop-controller-2.png" alt="crop-controller-2"/></img>
<img src="/assets/img-crop-controller-3.png" alt="crop-controller-3"/></img>
<img src="/assets/img-animal-controller-1.png" alt="animal-controller"/></img>
<img src="/assets/img-animal-controller-2.png" alt="animal-controller-2"/></img>
<img src="/assets/img-animal-controller-3.png" alt="animal-controller-3"/></img>
<img src="/assets/img-message-controller.png" alt="message-controller"/></img>

### 5.2.3.8 Team Collaboration Insights during Sprint.

| Alumno                               | Actividad                                                                          |
|--------------------------------------|------------------------------------------------------------------------------------|
| Aguilar Castillo, Rodrigo Alejandro  | Desarrollo del back end, y mejora de componentes del front end            |
| Barrionuevo Reto, Jean Franco Joel		       | Desarrollo del back end y desarrollo  front end                                    |
| Salgado Luna, Fernando Brian	         | Desarrollo del back end, y mejora de reestructuración de componentes del front end |
|Kunimoto Watanabe, Mathias Tsuneo		  | Desarrollo del back end, y mejora visual del front end                             |
| Zoppi Rodríguez, Giacomo		 | Desarrollo del back end y desarrollo de front end                                  |

#### Repositorio Landing:
(https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/landing-page.git)
<img src="/assets/img-repo-landing.png" alt="message-controller"/></img>

#### Repositorio Web Application:
(https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/frontend-application.git)
<img src="/assets/img-repo-front.png" alt="message-controller"/></img>

#### Repositorio BackEnd:
(https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git)
<img src="/assets/img-repo-backend.png" alt="message-controller"/></img>

### 5.3. Validation Interviews.
Dentro de la sección "Validation Interviews" de nuestro proyecto, nos enfocamos en perfeccionar la aplicación web destinada a
la gestión de granjas, y publicar anuncios para conectar granjas con empresarios. Tuvimos entrevistas interactivas con
nuestros usuarios primordiales: los dueños de granjas, trabajadores de estas y empresarios interesados en establecer alianzas estratégicas con granjas.
A través de entrevistas estructuradas, nos proponemos captar las impresiones y sugerencias del segmento objetivo.

#### 5.3.1 Diseño de Entrevistas.
En esta parte, se describen los objetivos específicos de los usuarios que guían nuestras entrevistas. Estos objetivos de usuario son fundamentales para
asegurar que la plataforma web satisfaga las necesidades reales de los usuarios en la industria avícola y ganadera. A continuación, se presentan los
objetivos de usuario mencionados:

- **User Goal: Iniciar Sesion**  
  User persona: Dueños de granja, trabajadores de granja y empresarios.  
  El usuario debe ingresar a la aplicación web y visualizará el botón sign in. Si tiene una cuenta el usuario inicia sesión, y en caso de no tener una se crea una cuenta. Después de esto el usuario podrá ver las características de acuerdo al tipo de usuario que es.


- **User Goal: Navegar por los anuncios de granjas**  
  User persona: Dueños de granja y empresarios.  
  El usuario ingresa a la aplicación visualiza la vista home y se muestra un listado en formato grilla en 4 columnas y filas ilimitadas, las cuales despliegan los datos de cada una de las granjas.


- **User Goal: Navegar por las diferentes opciones de monitoreo.**  
  User persona: Trabajadores de granja.
  El usuario debe ingresar a la aplicación web y loguearse respectivamente, luego en el navbar presionar la opción de monitoring y posteriormente podrá visualizar los apartados de monitoreo y navegar por las opciones.


- **User Goal: Crear una nueva emergencia**  
  User persona: Trabajadores de granja, Dueños de granja.
  Una vez logueado en la aplicación web presiona la opción de monitoring en la navbar y posteriormente a la opción emergencia. Aquí podrán enviar mensajes de emergencia describiendolos de manera que puedan llevar a todos los encargados de la granja.


- **User Goal: Añadir cosas al inventario**  
  User persona: Trabajadores de granja, Dueños de granja.
  Una vez logueado en la aplicación web presiona la opción de monitoring en la navbar y posteriormente a la opción inventory. Después de esto el usuario podrá visualizar todos los apartados del inventario, de manera que podrá añadir todos los items necesarios navegando por la sidebar y rellenando los datos para cada apartado.


- **User Goal: Crear una nueva tarea**  
  User persona: Dueños de granja.
  Una vez logueado en la aplicación web presiona la opción de monitoring en la navbar y posteriormente a la opción task. Después de esto el usuario le da click a create task y rellena los datos que se requieren. Después de esto la tarea ya se habrá creado.

- **User Goal: Crear una nuevo empleado**  
  User persona: Dueños de granja.
  Una vez logueado en la aplicación web presiona la opción de monitoring en la navbar y posteriormente a la opción Employee. Luego de esto el usuario entrará en el apartado de Employees y le hará click a Add employee. Finalmente el usuario le da click a add employee y rellena los datos que se requieren. Después de esto el empleado ya se habrá creado.

- **User Goal: Trabajar con datos estadisticos**  
  User persona: Dueños de granja.
  Una vez logueado en la aplicación web presiona la opción de monitoring en la navbar y posteriormente a la opción Statistics. Luego de esto el usuario se dirigirá al apartado de estadísticas donde podrá trabajar con datos estadísticos.

- **User Goal: Contactar con dueños de granjas y darles una reseña**  
  User persona: Empresario.
  Una vez logueado el usuario en la aplicación web podrá visualizar todas las granjas disponibles para un acuerdo comercial. El usuario deberá hacer click a su granja de interés, de manera que deslizando el slide podrá visualizar el apartado de contacto. Aqui le podrá dar click al botón chat on Whatsapp o simplemente rellenar sus datos de contacto para que el granjero se comunique con el usuario.


#### 5.3.2. Registro de Entrevistas.
**Primer segmento objetivo (Dueño de granja):**

Entrevista de validación usuario dueño de granja 01:


| Entrevistado  01             	                                                                  | Jorge Kunimoto 	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|-------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="/assets/img-entrevista-3.png" alt="message-controller"/></img>                      	 | Jorge Kunimoto fue entrevistado por Mathias Kunimoto acerca del servicio para manejar una granja tanto en su ámbito interno como externo. Durante la conversación, Jorge destacó la utilidad del servicio, mencionando que le parece una herramienta interesante para la gestión agrícola. Sin embargo, también ofreció algunas recomendaciones para mejorarla. Sugerió agregar un sector en la parte de roles (trabajadores) para que los empleados puedan dar su feedback sobre las necesidades que tienen, así como incluir un apartado de emergencias donde se pueda registrar el descanso médico. Otra sugerencia fue interconectar los tres roles para crear un buzón de mensajes, ya que a veces no se entienden bien las tareas asignadas. Según Jorge, estas mejoras podrían incrementar la eficiencia y la comunicación dentro de la granja, haciendo el servicio aún más valioso.         	 |
| Timing:  33:05                                                                                  | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/EQwpuVxTksdEmuQuirxpc1UBrhaowTHU2DRfQLNLwUfx6w?nav=eyJwbGF5YmFja09wdGlvbnMiOnsic3RhcnRUaW1lSW5TZWNvbmRzIjoxOTg1LjMxLCJ0aW1lc3RhbXBlZExpbmtSZWZlcnJlckluZm8iOnsic2NlbmFyaW8iOiJDaGFwdGVyU2hhcmUiLCJhZGRpdGlvbmFsSW5mbyI6eyJpc1NoYXJlZENoYXB0ZXJBdXRvIjpmYWxzZX19fSwicmVmZXJyYWxJbmZvIjp7InJlZmVycmFsQXBwIjoiU3RyZWFtV2ViQXBwIiwicmVmZXJyYWxWaWV3IjoiU2hhcmVDaGFwdGVyTGluayIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19&e=ZQllc1	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |


| Entrevistado  02             	                                                                    | Mirian Watanabe	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|---------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="/assets/img-entrevista-4.png" alt="message-controller"/></img>                        	 | Mirian Watanabe fue entrevistada por Mathias Kunimoto acerca del servicio para manejar una granja tanto en su ámbito interno como externo. Durante la conversación, Mirian destacó la utilidad del servicio, considerándolo una herramienta interesante para la gestión agrícola. Sin embargo, también ofreció algunas recomendaciones para mejorarlo. Sugirió agregar en el sector de inventario una sección de almacén para guardar herramientas típicas de una granja, como palas y escaleras. A pesar de esto, mencionó que el proyecto está bien distribuido en general. Según Mirian, esta mejora podría optimizar la organización y el manejo de recursos dentro de la granja, aumentando la eficiencia del servicio.        	 |
| Timing: 	0:00                                                                                     | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/EQwpuVxTksdEmuQuirxpc1UBrhaowTHU2DRfQLNLwUfx6w?nav=eyJwbGF5YmFja09wdGlvbnMiOnsic3RhcnRUaW1lSW5TZWNvbmRzIjowLCJ0aW1lc3RhbXBlZExpbmtSZWZlcnJlckluZm8iOnsic2NlbmFyaW8iOiJDaGFwdGVyU2hhcmUiLCJhZGRpdGlvbmFsSW5mbyI6eyJpc1NoYXJlZENoYXB0ZXJBdXRvIjpmYWxzZX19fSwicmVmZXJyYWxJbmZvIjp7InJlZmVycmFsQXBwIjoiU3RyZWFtV2ViQXBwIiwicmVmZXJyYWxWaWV3IjoiU2hhcmVDaGFwdGVyTGluayIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19&e=XrYWFW	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |



**Segundo segmento objetivo (Trabajador de granja):**


| Entrevistado  01             	                                                                    | Lucero Barrionuevo	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|---------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="/assets/img-entrevista-7.png" alt="message-controller"/></img>                        	 | Lucero Barrionuevo fue entrevistada acerca del servicio para manejar una granja tanto en su ámbito interno como externo. Durante la conversación, Lucero destacó la utilidad del servicio, mencionando que le parece una herramienta interesante para la gestión agrícola. Sin embargo, también ofreció una recomendación para mejorarla. Sugirió agregar conexiones para mejorar la comunicación entre los usuarios, lo que podría contribuir a reducir la carga de trabajo y evitar que se sientan explotados. Según Lucero, esta mejora podría incrementar la eficiencia y el bienestar de los trabajadores, haciendo el servicio aún más efectivo y equilibrado.       	 |
| Timing: 53:24                                                                                     | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/EQwpuVxTksdEmuQuirxpc1UBrhaowTHU2DRfQLNLwUfx6w?nav=eyJwbGF5YmFja09wdGlvbnMiOnsic3RhcnRUaW1lSW5TZWNvbmRzIjozMjA0LjU0OSwidGltZXN0YW1wZWRMaW5rUmVmZXJyZXJJbmZvIjp7InNjZW5hcmlvIjoiQ2hhcHRlclNoYXJlIiwiYWRkaXRpb25hbEluZm8iOnsiaXNTaGFyZWRDaGFwdGVyQXV0byI6ZmFsc2V9fX0sInJlZmVycmFsSW5mbyI6eyJyZWZlcnJhbEFwcCI6IlN0cmVhbVdlYkFwcCIsInJlZmVycmFsVmlldyI6IlNoYXJlQ2hhcHRlckxpbmsiLCJyZWZlcnJhbEFwcFBsYXRmb3JtIjoiV2ViIiwicmVmZXJyYWxNb2RlIjoidmlldyJ9fQ&e=ITvd2F	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |

| Entrevistado  02             	                                                                    | Rhaí Vargas	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="/assets/img-entrevista-8.png" alt="message-controller"/></img>                        	 |Rhaí Vargas, de 24 años y empleado en una empresa de distribución de productos agrícolas, evaluó muy positivamente nuestra página web. Destacó la facilidad y eficiencia para supervisar y manejar la distribución de productos, así como la mejora en la gestión diaria y toma de decisiones gracias al monitoreo de inventarios a distancia. Subrayó la accesibilidad de la interfaz y su facilidad de navegación, permitiendo a usuarios de diferentes niveles tecnológicos aprovechar las herramientas disponibles. La integración de datos en tiempo real y los informes detallados fueron especialmente valiosos para él. En resumen, Rhaí cree que nuestra plataforma optimiza la eficiencia y productividad en la distribución de productos agrícolas.        	 |
| Timing: 28:53	                                                                                    | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/EQwpuVxTksdEmuQuirxpc1UBrhaowTHU2DRfQLNLwUfx6w?nav=eyJwbGF5YmFja09wdGlvbnMiOnsic3RhcnRUaW1lSW5TZWNvbmRzIjoxNzMzLjI4OSwidGltZXN0YW1wZWRMaW5rUmVmZXJyZXJJbmZvIjp7InNjZW5hcmlvIjoiQ2hhcHRlclNoYXJlIiwiYWRkaXRpb25hbEluZm8iOnsiaXNTaGFyZWRDaGFwdGVyQXV0byI6ZmFsc2V9fX0sInJlZmVycmFsSW5mbyI6eyJyZWZlcnJhbEFwcCI6IlN0cmVhbVdlYkFwcCIsInJlZmVycmFsVmlldyI6IlNoYXJlQ2hhcHRlckxpbmsiLCJyZWZlcnJhbEFwcFBsYXRmb3JtIjoiV2ViIiwicmVmZXJyYWxNb2RlIjoidmlldyJ9fQ&e=CMBQJf	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |

| Entrevistado  03             	                                                                    | Rodrigo Noreña  	                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="/assets/img-entrevista-5.png" alt="message-controller"/></img>                        	 | Rodrigo Noreña Nuñez, un joven trabajador en granjas, fue entrevistado para evaluar la usabilidad del sitio web de FarmLogitech. Durante la entrevista, se le presentó cómo agregar un empleador, loguearse, crear un perfil y crear "cards", que son representaciones de las granjas en la plataforma. Rodrigo comentó sobre su experiencia y facilidad de uso del sitio web, proporcionando retroalimentación valiosa para mejorar la funcionalidad y la interfaz del usuario.          	 |
| Timing: 11:56	                                                                                    | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/EQwpuVxTksdEmuQuirxpc1UBrhaowTHU2DRfQLNLwUfx6w?nav=eyJwbGF5YmFja09wdGlvbnMiOnsic3RhcnRUaW1lSW5TZWNvbmRzIjo3MTYuMjA3LCJ0aW1lc3RhbXBlZExpbmtSZWZlcnJlckluZm8iOnsic2NlbmFyaW8iOiJDaGFwdGVyU2hhcmUiLCJhZGRpdGlvbmFsSW5mbyI6eyJpc1NoYXJlZENoYXB0ZXJBdXRvIjpmYWxzZX19fSwicmVmZXJyYWxJbmZvIjp7InJlZmVycmFsQXBwIjoiU3RyZWFtV2ViQXBwIiwicmVmZXJyYWxWaWV3IjoiU2hhcmVDaGFwdGVyTGluayIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19&e=TYkVj9                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |    

**Tercer segmento objetivo (Empresario):**

Entrevista de validación administrado de una empresa 01:


| Entrevistado  01            	                                                                     | Sergio Cadiño Nuñez	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="/assets/img-entrevista-9.png" alt="message-controller"/></img>                        	 |Sergio Cadiño Nuñez, un empresario de 23 años en la industria agropecuaria, compartió sus impresiones sobre nuestra página web, destacando su manejo práctico y eficiente para el control de una granja. Apreció especialmente la capacidad de observar y monitorear granjas de manera remota, lo que facilita la gestión diaria y la toma de decisiones. Sergio resaltó la interfaz intuitiva y fácil de usar, accesible para usuarios con diferentes niveles de experiencia tecnológica. También valoró la integración de datos en tiempo real y los informes detallados sobre el estado de las granjas. En resumen, Sergio considera que nuestra plataforma ofrece soluciones prácticas y modernas que optimizan la eficiencia y productividad en la industria agropecuaria.        	 |
| Timing: 	46:55                                                                                    | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/EQwpuVxTksdEmuQuirxpc1UBrhaowTHU2DRfQLNLwUfx6w?nav=eyJwbGF5YmFja09wdGlvbnMiOnsic3RhcnRUaW1lSW5TZWNvbmRzIjoyODE1LjI5NSwidGltZXN0YW1wZWRMaW5rUmVmZXJyZXJJbmZvIjp7InNjZW5hcmlvIjoiQ2hhcHRlclNoYXJlIiwiYWRkaXRpb25hbEluZm8iOnsiaXNTaGFyZWRDaGFwdGVyQXV0byI6ZmFsc2V9fX0sInJlZmVycmFsSW5mbyI6eyJyZWZlcnJhbEFwcCI6IlN0cmVhbVdlYkFwcCIsInJlZmVycmFsVmlldyI6IlNoYXJlQ2hhcHRlckxpbmsiLCJyZWZlcnJhbEFwcFBsYXRmb3JtIjoiV2ViIiwicmVmZXJyYWxNb2RlIjoidmlldyJ9fQ&e=nwZYE0	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |


#### 5.3.3. Evaluaciones según heurísticas.
**WEB APP A EVALUAR**  
*FarmLogiTech*  
Nuestro propósito es encontrar problemas existentes en nuestra aplicación web. Para ello, utilizaremos las heurísticas de Nielsen,
las cuales nos permitirán identificar problemas de usabilidad y experiencia de usuario. A continuación, se presentan las tareas a evaluar:

**TAREAS A EVALUAR**

- Web App
    1. El idioma de la aplicación debe poder cambiarse Escala de severidad: 4 Heuristica Relacionada: Usability: Consistencia y estándres
    2. Deberian haber mas animaciones y transciones a la hora de establecer farms y tasks
    3. Falta de Feedback de los Trabajadores
    4. Falta de Apartado en seccion de Emergencias
    5. Falta de Comunicación entre Roles
    6. Falta de Sección de Almacén en el Inventario
    7. Falta de Conexiones para Mejorar la Comunicación


**ESCALA DE SEVERIDAD:**  
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad

| Nivel 	| Descripción 	                                                                                                                                                                                              |
|-------	|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     	| Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.           	                   |
| 2     	| Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente reléase           	 |
| 3     	| Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta.           	                                |
| 4     	| Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.           	                              |

**TABLA RESUMEN:**

**Web Application**

| # 	 | Problema 	                                                                         | Escala de severidad 	 | Heurística/Principio violada(o) 	                                       |
|-----|------------------------------------------------------------------------------------|-----------------------|-------------------------------------------------------------------------|
| 1 	 | El idioma de la aplicación debe poder cambiarse      	                             | 4                   	 | Usability: Consistencia y estándres                               	     |
| 2 	 | Deberian haber mas animaciones y transciones a la hora de establecer farms y tasks | 1                     | Usability- Estética y diseño minimalista                              	 |
| 3 	 | Falta de Feedback de los Trabajadores      	                                       | 2                   	 | Usability - Coincidencia entre el sistema y el mundo real         |
| 4 	 | Falta de Apartado en seccion de Emergencias        	                               | 2                   	 | Usability - Coincidencia entre el sistema y el mundo real            |
| 5 	 | Falta de Comunicación entre Roles      	                                       | 3                   	 | Usability - Consistencia y estándares         |
| 6	  |  Falta de Sección de Almacén en el Inventario        	                               | 2                   	 | Usability - Coincidencia entre el sistema y el mundo real            |
| 7   |  Falta de Conexiones para Mejorar la Comunicación       	                               | 3                   	 | Usability - Flexibilidad y eficiencia de uso            |



### PROBLEMA #01: El idioma de la aplicación debe poder cambiarse:

**Persona entrevistada:** Rod Noreña

**Escala de severidad:** 04

**Principio violado:** Usability: Consistencia y estándres

**Descripción del problema:** Nuestros usuarios actulamente hablan español y no todos entienden inglés, por lo tanto la aplicación debe permitir cambiar de idioma

**Recomendacion:** Para solucionar este problema debe agregarse I18n a la aplicación.

### PROBLEMA #02: El idioma de la aplicación debe poder cambiarse:

Deberian haber mas animaciones y transciones a la hora de establecer farms y tasks

**Persona entrevistada:** Rod Noreña

**Escala de severidad:** 01

*Heuristica Relacionada:*

Usability- Estética y diseño
minimalista

*Descripción del problema:*

Nuestros usuarios podrian querer una interfaz mas animada o una interfaz grafica visualmente bonita y para saber que se esta constatando bien las acciones que estan haciendo

*Recomendacion:*

Para solucionar este problema debe implementar mas estilos en la parte del frontend, junto a transciones y componentes que solucionen el problema de la interfaz aburrida y sin dinamismo.


## Problema #03: Falta de Feedback de los Trabajadores

**Persona entrevistada:** Jorge Kunimoto

**Escala de severidad:** 02

**Principio violado:** Usability - Coincidencia entre el sistema y el mundo real

**Descripción del problema:** No existe un sector en la parte de roles (trabajadores) donde los empleados puedan dar su feedback sobre sus necesidades. Esto puede limitar la capacidad de la gestión para entender y atender las necesidades del personal, afectando su motivación y eficiencia.

**Recomendación:** Incluir un sector específico en la plataforma donde los trabajadores puedan dar su feedback y expresar sus necesidades.


## Problema #04: Falta de Apartado de Emergencias

**Persona entrevistada:** Jorge Kunimoto

**Escala de severidad:** 02

**Principio violado:** Usability - Coincidencia entre el sistema y el mundo real

**Descripción del problema:** No hay un apartado de emergencias donde se pueda registrar el descanso médico de los trabajadores. La ausencia de este apartado puede dificultar la gestión de situaciones de emergencia y la salud del personal, afectando la operación eficiente de la granja.

**Recomendación:** Agregar un apartado específico en la plataforma para registrar y gestionar descansos médicos y emergencias.

## Problema #05: Falta de Comunicación entre Roles

**Persona entrevistada:** Jorge Kunimoto

**Escala de severidad:** 03

**Principio violado:** Usability - Consistencia y estándares

**Descripción del problema:** Los tres roles no están interconectados para crear un buzón de mensajes, lo que dificulta la comprensión y asignación de tareas. Esta falta de comunicación clara puede llevar a malentendidos y errores en la ejecución de las tareas, afectando la productividad.

**Recomendación:** Implementar un sistema de mensajería interno que interconecte los tres roles para facilitar la comunicación y coordinación de tareas.


## Problema #06: Falta de Sección de Almacén en el Inventario

**Persona entrevistada:** Mirian Watanabe

**Escala de severidad:** 02

**Principio violado:** Usability - Coincidencia entre el sistema y el mundo real

**Descripción del problema:** No hay una sección de almacén en el sector de inventario para guardar herramientas típicas de una granja, como palas y escaleras. La ausencia de esta sección puede dificultar la organización y el acceso a las herramientas necesarias, afectando la eficiencia operativa.

**Recomendación:** Agregar una sección de almacén en el inventario para organizar y almacenar herramientas y equipos de la granja.


## Problema #07: Falta de Conexiones para Mejorar la Comunicación

**Persona entrevistada:** Lucero Barrionuevo

**Escala de severidad:** 03

**Principio violado:** Usability - Flexibilidad y eficiencia de uso

**Descripción del problema:** No hay conexiones adecuadas para mejorar la comunicación entre los usuarios, lo que puede llevar a una sobreexplotación del personal. La falta de comunicación efectiva puede resultar en una carga de trabajo desbalanceada y en la disminución del bienestar del personal, afectando la productividad y la moral.

**Recomendación:** Establecer conexiones y canales de comunicación efectivos entre los usuarios para asegurar una distribución equilibrada de las tareas y mejorar el bienestar del personal.

## 5.3.4. Sprint 4
### 5.3.4.1. Sprint Planning 4
El spring 4 tiene como inicio el dia 12/06/2024 y como objetivo plantea conectar el backend con el frontend y desplegar todos nuestros servicios

<table>
<tr><td>Sprint #</td><td>Sprint 4</td></tr>
<tr><td colspan="2">Sprint Planning Background</td></tr>
<tr><td>Date</td><td>2024-06-12</td></tr>
<tr><td>Time</td><td>7:00 PM</td></tr>
<tr><td>Location</td><td>Meet virtual meeting</td></tr>
<tr><td>Prepared by</td><td>Rodrigo Aguilar</td></tr>
<tr><td>Atendees</td><td>Mathias Kunimoto, Fernando Salgado, Giacomo Zoppi, Jean Franco Barrionuevo</td></tr>
<tr><td>Sprint 4 Review</td><td>En el Sprint 4 implementamos todos nuestros servicios y codigo en el frontend de manera que tengamos nuestra aplicacion funcional y lista para lanzarse, gracias a nuestros anteriores sprints dedicados a el desarrollo del frontend y backend.</td></tr>
<tr><td>Sprint 4 Retrospective</td><td>En el anterior sprint pudimos mejorar la organizacion de codigo y el como distribuirlo y aislarlo por secciones para que sea mas facil de trabajar, junto a definir la logica de negocio para una mejor experiencia del usuario.</td></tr>
<tr><td colspan="2">Sprint Goal & User Stories</td></tr>
<tr><td>Sprint 4 Goal</td><td>Implementar el backend y conectarlo al frontend para desplegar tanto nuestro servicio de API Rest como la aplicacion en si para que pueda ser distribuida.</td></tr>
<tr><td>Sprint 4 Velocity</td><td>15</td></tr>
<tr><td>Sum of story points</td><td>15</td></tr>
</table>

### 5.3.4.2. Sprint Backlog 4

En este sprint backlog, desarrollamos la implementacion de nuestros endpoint de nuestra API que ha estado siendo desarrollada desde el sprint 3, siendo utilizada en el frontend para recopilar y mostrar datos de nuestra base de datos desplegada en AWS.

<img src="/assets/img-trello-sprint4.png" alt="Logo-farm"></img>

Link del trello: https://trello.com/invite/b/H1ovwIyt/ATTIa06b8aa26ddc1b1aa652cdb1647fd69f7C984655/aplicaciones-web

| Technical User Story | WorkItem / Task                                   |      |                                                               |                                                                                                                                                              ||                             ||
|----------------------|---------------------------------------------------|------|---------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|------|-----------------------------|--------|
| Id                   | Title                                             | Id   | Title                                                         | Description                                                                                                                                                  | Estimation (Hours) | **Assigned To**             | **Status** |
| US20                 | Crear un perfil de trabajador                     | TK33 | Conexión de backend con frontend del apartado de trabajadores | Conectar el API existente con el frontend de filtros y metodos relacionados con la administración de empleados en la empresa.                                | 4 | **Jean Franco Barrionuevo** | **Done** |
| US02                 | Vinculo entre el Landing Page y la Aplicación Web | TK34 | Configurar autenticación para acceso a la aplicación          | Implementar en el backend la lógica de autenticación necesaria para permitir el acceso seguro desde la landing page a la aplicación web.                     | 5 | **Mathias Kunimoto**        | **Done** |
| US03                 | Crear y asignar tareas a los trabajadores         | TK35 | Mejora de la interfaz de gestión de tareas                    | Conectar la interfaz existente para permitir al dueño de la granja crear y asignar tareas a los trabajadores de manera más eficiente.                        | 6 | **Fernando Salgado**        | **Done** |
| US05                 | Registrar progreso de tareas                      | TK36 | Mejora de la API para registro de progreso de tareas          | Actualizar la API en el backend para mejorar la capacidad de los trabajadores de registrar y actualizar el progreso de sus tareas asignadas.                 | 5 | **Giacomo Zoppi**           | **Done** |
| US10                 | Verificar niveles de inventario                   | TK37 | Mejora del sistema de seguimiento de inventario               | Conectar el sistema existente con el frontend para rastrear y actualizar los niveles de inventario de productos agrícolas y ganaderos de manera más precisa. | 8 | **Rodrigo Aguilar**         | **Done** |

### 5.3.4.3 Development Evidence for Sprint Review.

| Fecha        | Commit Message                                                   | Usuario         | Branch                | Commit ID |
|--------------|------------------------------------------------------------------|-----------------|-----------------------|-----------|
| Jun 23, 2024 | Merge remote-tracking branch ‘origin/profiles’ into profiles     | Giacomo202210029| profiles              | 61c0c4b   |
| Jun 22, 2024 | feat(profiles): unversioned files                                | Giacomo202210029| profiles              | 03bb2a3   |
| Jun 21, 2024 | feat(profiles): workplace.                                       | fersalgado26    | profiles              | 89d83ef   |
| Jun 21, 2024 | feat(profile-management): Added Sign Up to employee and added role to profile | Giacomo202210029 | profiles | febd265   |
| Jun 21, 2024 | feat: unversioned files                                          | Giacomo202210029| profiles              | f42f50c   |
| Jun 22, 2024 | feat(social-interaction): rating updated.                        | fersalgado26    | social-interaction    | d160ed9   |
| Jun 22, 2024 | feat(social-interaction): expenses updated.                      | fersalgado26    | social-interaction    | ca973b2   |
| Jun 22, 2024 | feat(social-interaction): rating updated.                        | fersalgado26    | social-interaction    | ca0389a   |
| Jun 21, 2024 | feat(social-interaction): workspace.xml                          | fersalgado26    | social-interaction    | bf3c7c0   |
| Jun 19, 2024 | fix: Added authentication when creating a farm                   | kuni2005        | social-interaction    | 1121b25   |
| Jun 19, 2024 | Merge branch ‘social-interaction' into dev                       | kuni2005        | social-interaction    | 2a4c686   |
| Jun 19, 2024 | feat: merge with subscription                                    | kuni2005        | social-interaction    | 7f1d543   |
| Jun 19, 2024 | feat: fixed update                                               | Giacomo202210029| profiles              | dd0a0a3   |
| Jun 19, 2024 | feat: workspaces                                                 | Giacomo202210029| profiles              | da9163b   |
| Jun 19, 2024 | feat(profiles): Finished validations in Animals, crops, expenses | Giacomo202210029| profiles              | e64abc0   |
| Jun 19, 2024 | feat(profiles): Added Animal, Crops, Incomes and Expenses Validation | Giacomo202210029 | profiles          | 717e70c   |
| Jun 19, 2024 | Merge remote-tracking branch 'origin/profiles' into profiles     | Giacomo202210029| profiles              | 9987252   |
| Jun 19, 2024 | feat(profiles): Added employees                                  | Giacomo202210029| profiles              | dc8a33c   |
| Jun 19, 2024 | feat: added unversioned files                                    | Giacomo202210029| profiles              | 6e9dca1   |
| Jun 16, 2024 |  | feat(feature/profiles): Add fields in profiles                   | Rodrag0lvr      | profiles              | 8aa22ff   |
| Jun 16, 2024 |   | feat(subscription): Subscription fixed                           | Giacomo202210029| subscription          | d5574cc   |
| Jun 16, 2024    | feat(feature/profile): Add field userId in farm                  | Rodrag0lvr      | profile               | 119fe21   |
| Jun 16, 2024    | feat(feature/profiles): Add authentication with farmer           | Rodrag0lvr      | profiles              | 40dba37   |
| Jun 16, 2024    | Merge remote-tracking branch ‘refs/remotes/origin/subscription' into dev | Giacomo202210029 | subscription  | fa73ed1   |
| Jun 16, 2024    | feat: changes in server                                          | Giacomo202210029| server                | 9822a39   |
| Jun 16, 2024    | Merge remote-tracking branch ‘refs/remotes/origin/dashboard-analytics’ into dev | Giacomo202210029 | dashboard-analytics | 6bbf6a8 |
| Jun 16, 2024    | feat(feature/profile): Add authentication in farm                | Rodrag0lvr      | profile               | df502e5   |

### 5.3.4.4 Testing Suite Evidence for Sprint Review

| Repository                            | Branch | Commit Id      | Commit Message   | Commit Message Body   | Commited on (Date) |
|---------------------------------------|--------|----------------|------------------|-----------------------|--------------------|
| Aplicaciones-Web-WX55-Group-S-del-Softw | "main" | feat(testing)  | testing evidence | test of farm-logitech | 23/06/2024         |

<img src="/assets/img-testo-aws.png" alt="testeo"/></img>


### 5.2.3.5 Execution Evidence for Sprint Review.
En el sprint 4, logramos un desarrollo parcial del frontend y backend de la aplicación web. Este avance incluye nuevas vistas importantes sobre el producto y la startup, disponibles en inglés y español, así como una versión responsiva. A continuación, se presentan algunas evidencias:

- US09
  <img src="/assets/img-website-page-9.png" alt="US09"/></img>

- US14
  <img src="/assets/img-website-page-7.png" alt="US14"/></img>

- US15
  <img src="/assets/img-website-page.png" alt="US15"/></img>

- US16
  <img src="/assets/img-website-page-8.png" alt="US16"/></img>

- US21
  <img src="/assets/img-us-21.png" alt="US21"/></img>

- US22
  <img src="/assets/img-website-page-16.png" alt="US22"/></img>

### 5.3.4.6 Services Documentation Evidence for Sprint Review.

Para el sprint 4, se planificó la conexión del  front-end con el back-end. Inicialmente, se trabajó con el mismo github creando repositorios en donde
incluimos el db.json para luego enlazarlo llamandolo con la creación de rutas.

| Endpoint           | Details                                                                                                                                                           |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| /subscription-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /profile-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /farm-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /user-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /task-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /social-controller    | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /shed-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /income-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /expense-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /crop-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /animal-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /message-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |

Link del repositorio: https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git

### Web Service:

| Endpoint                | Operaciones | Parámetros       | URL                                                    |
|-------------------------|-------------|------------------|--------------------------------------------------------|
| subscription-controller | PUT         | {profileId}      | /api/v1/subscription/pay/subscription/{profileId}                                           |
|                         | POST        | No tiene         | /api/v1/subscription                          |
|                         | GET         | {id}             | api/v1/crops/{cropId}/tunnels                          |
|                         | GET         | No tiene         | /api/v1/subscription/all                |
| profile-controller      | GET         | {profileId}      | /api/v1/profile/{profileId}                           |
|                         | PUT         | {profileId}      | /api/v1/profile/{profileId}                                       |
|                         | POST        | No tiene         | /api/v1/profile                           |
|                         | GET         | No tiene         | /api/v1/profile/all                           |
| farm-controller         | GET         | {id}             | /api/v1/farm/{id}                          |
|                         | PUT         | {id}             | /api/v1/farm/{id}                                       |
|                         | POST        | No tiene         | /api/v1/farm                         |
|                         | GET         | {location}       | /api/v1/farm/location/{location}                           |
|                         | GET         | No tiene         | /api/v1/farm/all                         |
|                         | GET         | {profileId}        | /api/v1/farm/all/farms/profile/{profileId}                          |
| user-controller         | POST        | No tiene         | /api/v1/user                                       |
|                         | GET         | No tiene         | /api/v1/user/all                          |
| task-controller         | POST        | No tiene         | /api/v1/task                                      |
|                         | GET         | {farmerId}       | /api/v1/task/all/farmer/{farmerId}                          |
|                         | GET         | {collaboratorId} | /api/v1/task/all/collaborator/{collaboratorId}                          |
| social-controller       | POST        | No tiene         | /api/v1/socials                                      |
|                         | GET         | No tiene         | /api/v1/socials/all                         |
|                         | GET         | {id}             | /api/v1/socials/all/farm/{id}                         |
| shed-controller         | POST        | No tiene         | /api/v1/shed                                      |
|                         | GET         | {id}             | /api/v1/shed/{id}                         |
|                         | GET         | No tiene         | /api/v1/shed/all                        |
| income-controller       | POST        | No tiene         | /api/v1/income                                     |
| expense-controller      | POST        | No tiene         | /api/v1/expense                                     |
| crop-controller         | POST        | No tiene         | /api/v1/crop                                      |
|                         | GET         | {id}             | /api/v1/crop/{id}                         |
|                         | GET         | No tiene         | /api/v1/crop/all                       |
| animal-controller       | POST        | No tiene         | /api/v1/animal                                      |
|                         | GET         | {id}             | /api/v1/animal/{id}                         |
|                         | GET         | No tiene         | /api/v1/animal/all                       |
| message-controller      | POST        | {collaboratorId} | /api/v1/messages/collaborator/{collaboratorId}                                   |

#### Subscriptions Controller:
<img src="/assets/img-subscriptions-controller-1.png" alt="subscriptions-controller-1"/></img>

#### Profile Controller:
<img src="/assets/profile-controller-1.png" alt="profile-controller-1"/></img>

#### Farm Controller:
<img src="/assets/img-farm-controller-1.png" alt="farm-controller-1"/></img>

#### User Controller:
<img src="/assets/img-user-controller.png" alt="user-controller-1"/></img>

#### Task Controller:
<img src="/assets/img-task-controller-1.png" alt="task-controller-1"/></img>

#### Social Controller:
<img src="/assets/img-social-controller-1.png" alt="social-controller-1"/></img>

#### Shed Controller:
<img src="/assets/img-shed-controller.png" alt="shed-controller"/></img>

#### Income Controller:
<img src="/assets/img-income-controller.png" alt="income-controller"/></img>

#### Expense Controller:
<img src="/assets/img-expense-controller.png" alt="expense-controller"/></img>

#### Crop Controller:
<img src="/assets/img-crop-controller-1.png" alt="crop-controller"/></img>

#### Animal Controller:
<img src="/assets/img-animal-controller-1.png" alt="animal-controller"/></img>

#### Message Controller:
<img src="/assets/img-message-controller.png" alt="message-controller"/></img>

### 5.3.4.7 Software Deployment Evidence for Sprint Review.

Para la entrega del cuarto sprint, se implementó una landing page completamente funcional, cumpliendo con las historias de usuario correspondientes. Además, se desplegó y lanzó parcialmente el back-end, el cual aún está en proceso de finalización.

Landin Page:

La actualización de la página de destino en GitHub Pages se realizó tras fusionar la rama "develop" con la rama principal ("main"). Este proceso permitió renovar la implementación de la página de destino.

- Capturas de pantalla landing page:
  <img src="/assets/img-landing-update.png" alt="landing-page"/></img>

  <img src="/assets/img-deploymente-sprint.png" alt="landing-page"/></img>

- Web Application Front-end:

Prueba de que esta enlazado con el github pages:

<img src="/assets/img-deployment.png" alt="landing-page"/></img>

- Capturas de pantalla frontend:

  <img src="/assets/img-website-page-1.png" alt="website"/></img>
  <img src="/assets/img-website-page-2.png" alt="website"/></img>
  <img src="/assets/img-website-page-3.png" alt="website"/></img>
  <img src="/assets/img-website-page-5.png" alt="website"/></img>
  <img src="/assets/img-website-page-7.png" alt="website"/></img>
  <img src="/assets/img-website-page-8.png" alt="website"/></img>

Evidencia de que se desplego:

- Web Application Back-end:

  <img src="/assets/img-base-de-dato-workbrench-1.png" alt="Base de datos"/></img>
  <img src="/assets/img-base-de-dato-workbrench-2.png" alt="Base de datos"/></img>

Evidencia de que se desplego:

- Capturas de pantalla de Web Application:

<img src="/assets/img-subscriptions-controller-1.png" alt="subscriptions-controller-1"/></img>
<img src="/assets/profile-controller-1.png" alt="profile-controller-1"/></img>
<img src="/assets/img-farm-controller-1.png" alt="farm-controller-1"/></img>
<img src="/assets/img-user-controller.png" alt="user-controller-1"/></img>
<img src="/assets/img-task-controller-1.png" alt="task-controller-1"/></img>
<img src="/assets/img-social-controller-1.png" alt="social-controller-1"/></img>
<img src="/assets/img-shed-controller.png" alt="shed-controller"/></img>
<img src="/assets/img-income-controller.png" alt="income-controller"/></img>
<img src="/assets/img-expense-controller.png" alt="expense-controller"/></img>
<img src="/assets/img-crop-controller-1.png" alt="crop-controller"/></img>
<img src="/assets/img-animal-controller-1.png" alt="animal-controller"/></img>
<img src="/assets/img-message-controller.png" alt="message-controller"/></img>

### 5.3.4.8. Team Collaboration Insights during Sprint.

| Alumno                 | Actividad                                                                                                                                                   | 
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Rodrigo Aguilar        | Desarrollo backend, contribucion con la conexion y desarrollo con aws                                                                                       |
| Jean Franco  Barrionuevo  | Desplegar la base de datos, el API, realizar mejoras en el bounded context de Task, se le puso verificaciones, reglas de dominio y realice el test unitario |
| Mathias Kunimoto       | Desarrollo de profile managmente y despliegue del frontend para la conexion                                                                                 |
| Fernando  Salgado             | Desarrollo del monitoring, animal shed y drop, ademas correciones de tasks                                                                                  |
| Giacomo Zoppi            | Desarrollo del drop en la parte de tasks y conexion analytics.                                                                                              |


1. Repositorio Landing Page:
   (https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/landing-page.git)

<img src="/assets/img-landing-sprint-4.png" alt="frontend"/></img>
<img src="/assets/img-commits-landing.png" alt="frontend"/></img>


Observaciones:
- La participación de Luciano Ruiz y Franz en el repositorio de la landing page no se vio reflejada en los insights debido a problemas con la sincronización de github.
  Logros clave:

2. Repositorio de la Aplicación Web (Frontend):
   (https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/frontend-application.git)

<img src="/assets/img-frontend-1.png" alt="frontend"/></img>
<img src="/assets/img-frontend.png" alt="frontend"/></img>

Patrones de colaboración:
- Se observaron dos grandes impulsos de desarrollo: a principios de mayo y a principios de junio
- Contribuciones constantes durante todo el sprint

3. Repositorio Backend:
   (https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Backernd-farmLogitech-ap.git)

<img src="/assets/img-backend.png" alt="backend"/></img>
<img src="/assets/img-backend-commits.png" alt="backend"/></img>


Métricas notables:
- Un total de 50 commits entre todo el equipo
- Más de 21,000 líneas de código añadidas, indicando un desarrollo significativo de características

Los gráficos de contribución muestran un esfuerzo bien distribuido entre el equipo, con un aumento de actividad hacia el final del sprint debido a las fases de integración y pruebas. El repositorio backend vio la mayor actividad, reflejando nuestro enfoque en construir una API robusta para soportar nuestra aplicación web.

De cara al futuro, nuestro objetivo es mantener este nivel de colaboración mientras nos enfocamos en una distribución más uniforme de commits entre todos los miembros del equipo.


### Video About-The-Product.
A continuación, se muestra el video "Acerca del producto", el cual ilustra el propósito, beneficios y características principales de la aplicación.
Enlace para visualizar el video About the product:  
Enlace del video subido a Stream: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/Efa-XjEM3VBFnGr0cKYXUa0BU_SU_BCWQKmIb4eJ_6E6Nw?e=Ttnseh&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
Enlace del video subido a Youtube: https://youtu.be/9n1QPdK4iyg

### Video About-The-Team.

Link del about the team subido en youtube: https://youtu.be/iCf60oI6VU8

Link del about the team subido en Stream: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/EbE86M0acb1FsQIlCqjeV-ABe9MPUlZYYTp4YUwlvTUwwg?e=aCCBfH&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

# VI. Conclusiones y Recomendaciones

1. **Problem Statements:**
    - El desarrollo de FarmLogiTech como proyecto de curso ha abordado teóricamente la falta de herramientas tecnológicas integradas en la industria agrícola y ganadera. Nuestro diseño propone una solución para el monitoreo en tiempo real del estado de los cultivos, el bienestar animal y las condiciones climáticas, lo cual podría facilitar la toma de decisiones informadas y la optimización de la producción.
    - El proyecto ha explorado formas de mejorar la colaboración entre empresas y dueños de granjas, proponiendo mecanismos para facilitar asociaciones beneficiosas que podrían impulsar el crecimiento y la rentabilidad en la cadena de suministro agrícola.

2. **Assumptions vs. Comportamiento real de los segmentos:**
    - La asunción de que los dueños de granjas y trabajadores utilizarían la plataforma durante toda su jornada laboral se mantiene como una hipótesis que requeriría validación en un escenario real.
    - La hipótesis sobre el interés de las empresas grandes en utilizar la plataforma para establecer una mejor comunicación con las granjas es prometedora, pero necesitaría ser probada en el mercado real.

3. **Hypothesis Statements:**
    - El diseño del sistema de seguimiento y análisis de datos agrícolas propuesto tiene el potencial de mejorar la toma de decisiones y la eficiencia en las operaciones agrícolas, pero esto necesitaría ser validado en la práctica.
    - La inclusión de funcionalidades de pronóstico meteorológico en nuestro diseño parece valiosa en teoría, pero su efectividad real requeriría pruebas de campo.
    - La interfaz intuitiva y fácil de usar que hemos diseñado apunta a una mayor satisfacción del usuario, pero esto necesitaría ser confirmado con pruebas de usabilidad reales.

4. **Criterios de Éxito vs. Expectativas del Proyecto:**
    - Los objetivos de crecimiento, adopción y eficiencia establecidos en nuestro proyecto son ambiciosos y están bien fundamentados en nuestra investigación, pero su viabilidad solo podría ser determinada mediante una implementación real.
    - Las mejoras en eficiencia operativa, reducción de tiempo en gestión de tareas y disminución de incidencias críticas que hemos proyectado son metas realistas basadas en nuestro análisis, pero requerirían validación en un entorno operativo real.

5. **Conclusiones técnicas:**
    - El uso de Lean UX, fue de gran ayuda gracias a su enfoque iterativo, que  permite adaptarse rápidamente a los cambios del la aplicación y las necesidades del usuario, promoviendo así la eficiencia al desarrollar el producto.
    - Conventional Commits establecio un estándar para mensajes de confirmación claros y estructurados, lo que facilitó la comprensión del historial de cambios.
    - Los diagramas de arquitectura de dominio facilitaron la comprensión de las relaciones entre el dominio y sus contextos delimitados
    - Como equipo buscamos priorizar la comprensión profunda del negocio y su contexto, mediante la colaboración entre expertos técnicos y de dominio.
    - El enfoque en la modularidad y la reutilización de código de Angular agilizó el proceso de desarrollo.
    - El uso de Springboot nos ayudo gracias a su capacidad para gestionar fácilmente la lógica de negocios, la persistencia de datos y la integración con tecnologías externas
    - As-Is mapping nos proporcionó una comprensión detallada de los procesos existentes, identificando puntos débiles y oportunidades de mejora. Por otro lado, en el To-Be mapping, mostramos la visión futura del proceso optimizado, destacando los cambios planificados y las mejoras esperadas, sirviendo como guía para la transformación y la innovación.
    - Nuestra aplicación puede ayudar a gobiernos regionales y locales a impulsar la modernización de la industria al  permitir mejorar y controlar los procesos productivos
## Recomendaciones

Basándonos en el desarrollo de FarmLogiTech como proyecto de curso y en nuestro análisis teórico, recomendamos los siguientes pasos para un potencial Roadmap de desarrollo futuro:

1. **Validación de Conceptos:**
    - Realizar pruebas de concepto con un prototipo funcional en un entorno controlado, como una granja piloto, para validar las funcionalidades clave.
    - Conducir entrevistas y encuestas detalladas con potenciales usuarios (dueños de granjas, trabajadores y empresas) para refinar los requisitos y características del producto.

2. **Desarrollo Iterativo:**
    - Implementar un enfoque de desarrollo ágil, comenzando con un Producto Mínimo Viable (MVP) que incluya las funcionalidades más críticas identificadas en nuestro proyecto.
    - Establecer ciclos de retroalimentación tempranos y frecuentes con usuarios beta para iterar y mejorar el producto.

3. **Expansión Gradual de Funcionalidades:**
    - Priorizar el desarrollo de módulos core como la gestión de tareas, monitoreo de cultivos y animales, y herramientas de comunicación.
    - Planificar la integración futura de tecnologías avanzadas como IA y IoT, basándose en la retroalimentación de los usuarios iniciales.

4. **Estrategia de Entrada al Mercado:**
    - Desarrollar un plan de lanzamiento por fases, comenzando con un grupo selecto de granjas para un período de prueba extensivo.
    - Diseñar una estrategia de marketing enfocada en demostrar el valor tangible de FarmLogiTech a través de casos de estudio y testimonios de usuarios piloto.

5. **Consideraciones de Escalabilidad y Sostenibilidad:**
    - Investigar y planificar la infraestructura tecnológica necesaria para soportar un crecimiento potencial del número de usuarios y volumen de datos.
    - Incorporar desde el inicio prácticas de desarrollo sostenible y considerar el impacto ambiental de la implementación tecnológica en el sector agrícola.

Estas recomendaciones buscan trazar un camino desde el proyecto académico actual hacia una potencial implementación real de FarmLogiTech, reconociendo la necesidad de validación y refinamiento continuos basados en retroalimentación del mundo real.

- En conclusion, creemos que el proyecto FarmLogiTech tiene un gran potencial para ayudar a los dueños de granjas a gestionarlas de manera eficiente y sostenible. Con una landing page atractiva y funcional, hemos logrado comunicar eficazmente los beneficios de la aplicación y atraer visitantes. Durante el Sprint 1, el equipo ha colaborado eficientemente para cumplir los objetivos establecidos. A través de la implementación de Historias de Usuario y pruebas de aceptación, hemos desarrollado una landing page que cumple con los requisitos del cliente. En el próximo Sprint, nos enfocaremos en desarrollar la aplicación y agregar nuevas funcionalidades para mejorar la experiencia del usuario.
  <br/>
  <br/>
- En resumen, creemos que FarmLogiTech tiene un enorme potencial para ayudar a los propietarios de granjas a administrar sus operaciones de manera eficiente y sostenible. Mediante la creación de una websitre, hemos logrado de manera efectiva aplicar los beneficios de la aplicación y atraer visitantes. Durante el segundo sprint, el equipo ha trabajado de manera colaborativa y eficiente para alcanzar los objetivos establecidos. Gracias a la implementación de historias de usuario y pruebas de aceptación, hemos desarrollado un sitio web que satisface los requisitos del cliente. En el próximo sprint, nos centraremos en el desarrollo de la aplicación y en la introducción de nuevas funcionalidades para mejorar la experiencia del usuario.

### Video de exposición

https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/ETAcrVGKkrlKknsZpmGL_l4BQKn1fGiAw0KJgLuZ3mRCoA?e=wPs2Um&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

<br/>
Landing Page

https://aplicaciones-web-wx55-group-s-del-softw.github.io/landing-page/

Website
https://farmlogitech-aw-b6594.web.app/home

# Bibliografía
- Infobae. (2023, 22 de marzo). Crisis en el sector avícola: Precio del pollo se eleva, granjas quebradas y millones de aves sacrificadas por influenza. https://www.infobae.com/peru/2023/03/22/crisis-en-el-sector-avicola-precio-del-pollo-se-eleva-granjas-quebradas-y-millones-de-aves-sacrificadas-por-influenza/
- AviNews. (2023, 14 de noviembre). Brote de influenza aviar en granja de postura comercial en Perú. https://avinews.com/peru-se-presenta-brote-de-influenza-aviar-en-granja-de-postura-comercial/
- Gobierno Regional de Lima. (2021, 3 de mayo). Productores de Barranca apuestan por el cultivo de maracuyá. https://www.gob.pe/regionlima
- Moran, K. (2016). The Four Dimensions of Tone of Voice. Nielsen Norman Group. https://www.nngroup.com/articles/tone-of-voice-dimensions/
- Gothelf, J., & Seiden, J. (2021). Lean UX, 3rd Edition. https://www.oreilly.com/library/view/lean-ux-3rd/9781098116293/
- Progressa Lean. (2014). 5W+2H Técnica de análisis de problemas - Progressa Lean. Progressa Lean. https://www.progressalean.com/5w2h-tecnica-de-analisis-de-problemas/
- UX Planet. (2017). Information Architecture. Basics for Designers. - UX Planet. Medium; UX Planet. https://uxplanet.org/information-architecture-basics-for-designers-b5d43df62e20
- Gothelf, J. (2024). Leanux Sampler. https://es.scribd.com/document/655516553/Leanux-Sampler

- Infobae. (2023, 22 de marzo). Crisis en el sector avícola: Precio del pollo se eleva, granjas quebradas y millones de aves sacrificadas por influenza. https://www.infobae.com/peru/2023/03/22/crisis-en-el-sector-avicola-precio-del-pollo-se-eleva-granjas-quebradas-y-millones-de-aves-sacrificadas-por-influenza/
- AviNews. (2023, 14 de noviembre). Brote de influenza aviar en granja de postura comercial en Perú. https://avinews.com/peru-se-presenta-brote-de-influenza-aviar-en-granja-de-postura-comercial/
- Gobierno Regional de Lima. (2021, 3 de mayo). Productores de Barranca apuestan por el cultivo de maracuyá. https://www.gob.pe/regionlima 


