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


# Conclusiones

- En conclusión, creemos que el proyecto FarmLogiTech es una aplicación que tiene un gran potencial para ayudar a los dueños de granja a gestionar sus granjas de manera eficiente y sostenible. A través de la implementación de una landing page atractiva y funcional, hemos logrado comunicar de manera efectiva los beneficios de la aplicación y atraer a los visitantes. Durante el Sprint 1, el equipo ha trabajado de manera colaborativa y eficiente para cumplir con los objetivos establecidos. A través de la implementación de las Historias de Usuario y la realización de pruebas de aceptación, hemos logrado desarrollar una landing page que cumple con los requerimientos del cliente. En el próximo Sprint, nos enfocaremos en el desarrollo de la aplicación y en la implementación de nuevas funcionalidades para mejorar la experiencia del usuario.
  <br/>
   <br/>
- En resumen, creemos que FarmLogiTech tiene un enorme potencial para ayudar a los propietarios de granjas a administrar sus operaciones de manera eficiente y sostenible. Mediante la creación de una websitre, hemos logrado de manera efectiva aplicar los beneficios de la aplicación y atraer visitantes. Durante el segundo sprint, el equipo ha trabajado de manera colaborativa y eficiente para alcanzar los objetivos establecidos. Gracias a la implementación de historias de usuario y pruebas de aceptación, hemos desarrollado un sitio web que satisface los requisitos del cliente. En el próximo sprint, nos centraremos en el desarrollo de la aplicación y en la introducción de nuevas funcionalidades para mejorar la experiencia del usuario.
### Video de exposición

[Video de exposición]()
<br/>
[Link del Landing page]  
(https://aplicaciones-web-wx55-group-s-del-softw.github.io/landing-page/)

[Link del Website]  
(https://farmlogitech-aw.web.app/)

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
