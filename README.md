# Capítulo IV: Product Design

Este capítulo cubre todos los aspectos relacionados con el diseño de la solución, incluyendo el estilo visual, los diagramas C4, los diagramas de clases y los modelos de base de datos.

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

Es un conjunto de normas y directrices que determinan cómo se deben redactar, diseñar o presentar documentos, contenido en línea, software u otros trabajos creativos. A continuación, se detallan los parámetros implementados en la estructura del proyecto.

**Branding:**

**Brand Overview:**

**EcoMovil** es una plataforma que ofrece una alternativa ágil y ecológica para la movilidad urbana, conectando a usuarios que desean alquilar o comprar vehículos sostenibles como bicicletas, scooters, skateboards y motos eléctricas con quienes los tienen disponibles. La aplicación facilita el proceso de alquiler o compra, apoyando también a estudiantes en la generación de ingresos flexibles. Entre sus características clave se incluyen un sistema de valoraciones y reseñas con estrellas, búsqueda avanzada con filtros, un historial de transacciones, un mapa interactivo de puntos de recepción y entrega, inclusión de IGV en las transacciones, elementos de gamificación con logros y recompensas, y la opción de adquirir un seguro temporal durante el alquiler. EcoMovil promueve una movilidad sostenible y un estilo de vida activo y responsable con el medio ambiente.

- **Misión:** Facilitar el acceso a una movilidad urbana sostenible, conectando a las personas con vehículos ecológicos a través de una plataforma digital eficiente, contribuyendo a la reducción de la contaminación, y brindando oportunidades de ingresos para estudiantes universitarios.

- **Visión:** Convertirnos en una plataforma líder en movilidad urbana sostenible, facilitando el acceso a vehículos ecológicos y promoviendo un estilo de vida más saludable y consciente con el medio ambiente.

**Brand Name:**

EcoMovil es una solución que surge de la combinación de "Eco", representando ecología y sostenibilidad, y "Movil", destacando la movilidad urbana. Esta aplicación está diseñada para fomentar el emprendimiento universitario y la sostenibilidad en Perú, brindando a los estudiantes la oportunidad de generar ingresos alquilando o vendiendo vehículos ecológicos. Al mismo tiempo, contribuye a reducir la contaminación y promueve un estilo de vida más activo.

<img src="/assets/perfil/ecomovil.jpg">

**Colores:**

Los colores desempeñan un papel fundamental en la primera impresión que los usuarios tienen de la plataforma. Basándose en los principios de la psicología del color, se ha seleccionado el verde como el color principal de la paleta cromática. Este color simboliza crecimiento y creatividad, que son valores esenciales de la startup. Además, el verde está asociado con la ecología, que es el enfoque principal de la plataforma, y con la armonía, un concepto que buscamos reflejar en la interacción con el servicio. Las tonalidades secundarias elegidas abarcan distintos matices de verde claro, verde oscuro y verde pálido. Como colores secundarios, también se incluyen variantes de verde fosforescente, crema claro y anaranjado amarillo.

<img src="/assets/perfil/primaryandsecondary.png">
<img src="/assets/perfil/wireframeandtext.png">
<img src="/assets/perfil/gradient.png">

**Tipografia:**

La tipografía juega un papel crucial en establecer la jerarquía entre los diferentes grupos de contenido en la página, además de guiar al usuario a través de la interfaz. Para el proyecto, se ha elegido la fuente "Alata" en sus estilos Medium y Normal, para asegurar una mayor legibilidad. Además, la organización tipográfica se estructura en cuatro niveles para los elementos del diseño web (body y heading), lo que ayuda a mantener una disposición clara y coherente del contenido.

La estructura tipográfica del proyecto se organiza en cuatro niveles de jerarquía para los encabezados:

- Heading 01: Tamaño de 34px.
- Heading 02: Tamaño de 22px.
- Heading 03: Tamaño de 17px.
- Heading 04: Tamaño de 15px.

<img src="/assets/perfil/typography2.png">

### 4.1.2. Web Style Guidelines

El enfoque de la aplicación web "EcoMovil" se basa en la eficiencia, la formación y la ecología en todos los procesos. Las diferentes etapas y formularios necesarios están organizados en secciones clave: Página principal, Acerca de nosotros, Inscríbase, Vehículos, Beneficios y Contacto, que ocupan la mayor parte de la pantalla para facilitar la navegación y ofrecer una experiencia de usuario fluida y coherente.

- **Imágenes:**<br>
En el diseño web de "EcoMovil", se utilizarán imágenes descriptivas de manera estratégica. Las imágenes de vehículos menores y de la empresa estarán en la página de inicio, con el logo de la empresa ubicado en la parte superior izquierda para facilitar su identificación. Además, cada sección principal contará con imágenes representativas de los vehículos menores, reforzando la visión ecológica para el usuario. Para optimizar la experiencia en aplicaciones de escritorio, se evitarán imágenes de fondo, optando en su lugar por imágenes laterales que guíen al usuario a través de la interfaz de manera funcional.

- **Botones:**<br>
Los botones en la aplicación web "EcoMovil" siguen las especificaciones establecidas en las General Style Guidelines. Generalmente, estos botones se encuentran en la parte inferior de la sección principal de la pantalla, permitiendo al usuario realizar acciones que se reflejan en la vista superior. Para acciones que inicien nuevos procesos o afecten el funcionamiento general de la página, se incluyen botones de confirmación. Todos los botones están diseñados con un estilo distintivo y un alto contraste en comparación con el resto de la aplicación, asegurando que sean fácilmente visibles. Además, se aplica la teoría del color en los botones, donde los colores específicos indican acciones que eliminan procesos o los concluyen.

- **Pantallas Emergentes:**<br>
Las pantallas emergentes en "EcoMovil" están diseñadas para confirmar acciones clave que son cruciales para el funcionamiento del negocio y tienen un impacto significativo en el mismo. Estas pantallas emergentes enfatizan la importancia de resolver el asunto en cuestión antes de que el usuario pueda continuar navegando por la aplicación, subrayando la necesidad de tomar decisiones informadas en momentos críticos.

## 4.2. Information Architecture

Dado que EcoMovil gestiona un flujo funcional esencial para el negocio, es fundamental que el usuario tenga claridad sobre las etapas y procesos involucrados. La información está estructurada de manera categórica y secuencial, permitiendo al usuario avanzar a través de un módulo que representa el proceso general, ya sea un ingreso o una ganancia. A medida que el usuario registra las diferentes fases del vehículo, estas se reflejan en varias pantallas de la web. Además, la vista del "Panel de Control" proporciona una visión general de las funcionalidades clave de la aplicación, facilitando la supervisión y gestión de los procesos.

### 4.2.1. Organization System

El sistema de organización de la página de "EcoMovil" está diseñado para estructurar visualmente el contenido y facilitar la navegación. La página principal se divide en secciones clave: Página principal, Acerca de nosotros, Inscríbase, Vehículos, Beneficios y Contacto.

- **Up-Section**: En la parte superior de la página principal, se encuentran las opciones de navegación a otras secciones, siguiendo un patrón de diseño F que subraya la importancia de que los usuarios conozcan la empresa y su oferta. Los botones de registro e inicio de sesión están situados en el extremo derecho. Además, hay un botón de modo oscuro para ajustar el tema visual según las preferencias del usuario y un botón para cambiar el idioma entre Español e Inglés, mejorando la accesibilidad.

### 4.2.2. Labeling System
En nuestra aplicación EcoMovil, el sistema de etiquetas estará bien organizado y representado para que el usuario pueda identificar y usar las distintas funciones brindadas, que sirve para encontrar la información, de una manera intuitiva y sencilla.

Etiquetas:

Home 

Suscripciones

...

### 4.2.3. SEO Tags and Meta Tags
En este apartado abordaremos las etiquetas SEO y Meta, que sirven para proporcionar información sobre nuestras páginas web a los motores de búsqueda y para optimizar estas búsquedas y su relevancia.

Landing page:

Aplicación web:

### 4.2.4. Searching Systems
El sistema de búsqueda en EcoMovil es una funcionalidad que permitirá a los usuarios encontrar rápidamente los vehículos que desean alquilar o comprar según sus necesidades. Este ofrecerá una búsqueda fluida y eficiente. Sus principales funciones será la búsqueda por palabras claves para poder buscar vehículos en específico, la opción de filtros avanzados para una búsqueda de acuerdo a ciertos criterios y la existencia de un historial de búsquedas recientes para que se pueda acceder rápidamente a las búsquedas que ya se han realizado.
### 4.2.5. Navigation Systems
El Sistema de navegación es importante para lograr que los usuarios puedan navegar a través de la aplicación de una manera más sencilla. Esto es crucial para lograr una experiencia de usuario satisfactoria.
En la aplicación web se tendrá una barra de navegación que contará con diversas opciones que guiarán al usuario al apartado de su interés.

![Navegation_Bar](/assets/chapter-4/NavegationBar.png)

También contaremos con un footer, que será el pie de página. Este contará con enlaces adicionales a distintas secciones como Sobre Nosotros (información sobre nuestra visión y el equipo detrás de la aplicación), Contacto (formulario para poder contactarnos), etc.

![Footer](/assets/chapter-4/Footer.png)

## 4.3. Landing Page UI Design

Se diseñó esta interfaz con simplicidad en mente, utilizando colores claros como el verde para reflejar nuestro compromiso con el medio ambiente. También se diseñó para que los usuarios se sientan cómodos leyendo en cualquier dispositivo, manteniendo un tamaño de letra adecuado (F). Además, la interfaz es totalmente responsive, lo que significa que se adaptará a cualquier dispositivo con dimensiones adecuadas para una experiencia de usuario óptima.

### 4.3.1. Landing Page Wireframe
![wireframe_landingpage_1](/assets/chapter-4/wireframe-L1.png)
![wireframe_landingpage_2](/assets/chapter-4/wireframe-L2.png)
![wireframe_landingpage_3](/assets/chapter-4/wireframe-L3.png)
![wireframe_landingpage_4](/assets/chapter-4/wireframe-L4.png)
![wireframe_landingpage_5](/assets/chapter-4/wireframe-L5.png)
![wireframe_landingpage_6](/assets/chapter-4/wireframe-L6.png)
Enlace de los Wireframes: https://www.figma.com/design/H7sRaG5gHgvp1CHmqDntxF/ECOMOVIL?node-id=0-1&t=bSUEvCSyLGZG4S0L-1

### 4.3.2. Landing Page Mockup

![mock_uplanding1](/assets/chapter-4/landing1.png)
![mock_uplanding2](/assets/chapter-4/landing2.png)
![mock_uplanding3](/assets/chapter-4/landing3.png)
![mock_uplanding4](/assets/chapter-4/landing4.png)
![mock_uplanding5](/assets/chapter-4/landing5.png)
![mock_uplanding6](/assets/chapter-4/landing6.png)
![mock_uplanding7](/assets/chapter-4/landing7.png)
Enlace del mock-up: https://www.figma.com/design/H7sRaG5gHgvp1CHmqDntxF/ECOMOVIL?node-id=0-1&t=bSUEvCSyLGZG4S0L-1

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

### 4.4.2. Web Applications Wireflow Diagrams

### 4.4.3. Web Applications Mock-ups

### 4.4.4. Web Applications User Flow Diagrams 

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Arquitecture
En esta sección, se mostrarán los distintos diagramas elaborados que representan la arquitectura de software que se utilizará para el proyecto.

### 4.6.1. Software Architecture Context Diagram 
![C4_Context](./assets/chapter-4/c41.png)

### 4.6.2. Software Architecture Container Diagram
![C4_Container](./assets/chapter-4/c42.png)
### 4.6.3. Software Architecture Component Diagram
- En esta primera sección se muestran los requerimientos no funcionales de la aplicación.
![C4_Component_Profile](./assets/chapter-4/c43.png)

- Aqui se muestran los componentes de perfil
![C4_Component_Profile2](./assets/chapter-4/c45.png)

- Aqui se muestran los componentes de vehicle
![C4_Component_Profile3](./assets/chapter-4/c44.png)

- Aqui se muestran los componentes de autenticación
![C4_Component_Profile4](./assets/chapter-4/c46.png)

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams

### 4.7.2. Class Dictionary

## 4.8. Database Design

### 4.8.1. Database Diagram
