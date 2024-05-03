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

![image](https://github.com/Aplicaciones-Web-WX55-Group-S-del-Softw/Final-Project/assets/129527802/4240422a-2a10-4af5-859b-70264740f023)

https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210029_upc_edu_pe/ETbEAdlXL0tKlVXCRvmGMdkB0HOmvtODaS1FOnFVQ3XQLA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=aLRsaQ 



# 4.6. Domain-Driven Software Architecture
El Domain Driven Design (DDD) tiene como objetivo llegar a un entendimiento compartido del dominio que abarca el espacio del problema. En el caso de “FarmLogitech”, este dominio es la gestión de granjas y la colaboración entre agricultores y empresas. Gracias a la perspectiva brindada por este enfoque, es posible mejorar la colaboración entre los desarrolladores y los expertos del dominio.


## 4.6.1. Software Architecture Context Diagram
El diagrama de contexto muestra una vista de alto nivel de las relaciones entre el sistema de software “FarmLogitech”, los usuarios y, si es el caso, de otros sistemas externos.
<div align=center>
<img src="/assets/img-system-diagram.jpeg" alt="System diagram"></img>
</div>

## 4.6.2. Software Architecture Container Diagram
El diagrama de contenedores muestra una vista de alto nivel de las relaciones entre las aplicaciones y fuentes de datos que son parte de la ejecución del sistema de software “FarmLogitech”.

<div align=center>
<img src="/assets/img-container-diagram.png" alt="Container diagram"></img>
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
   <img src="/assets/img-class-diagram.png" alt="Diagrama de clase"></img>
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

<img src="/assets/img-database.jpeg" alt="Diagrama-database"></img>



