# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

**Requirements Management**

1. Trello: Es una herramienta para gestionar proyectos, especialmente aquellos basados en metodologías ágiles. Facilita la visualización y actualización del progreso de tareas e historias de usuario dentro de un sprint en desarrollo.

Ruta de referencia: https://trello.com/es

**User Experience Design (UX/UI)**

1. Figma: Herramienta para la creación de prototipos y diseño gráfico, principalmente empleada en el ámbito digital. En este proyecto, servirá para desarrollar prototipos de la aplicación y sus versiones para navegadores en escritorio y móviles.

Ruta de referencia: https://www.figma.com/login

2. Lucidchart: Aplicación para la creación de diagramas de flujo. Se utilizará para el diseño de wireflows, user-flows y el diagrama de clases asociado con la aplicación.

Ruta de referencia: https://www.lucidchart.com

**Software Testing**

1. Gherkin: Gherkin es un lenguaje usado para definir los criterios de aceptación de una historia de usuario de forma estructurada. Proporciona una forma estandarizada de escribir escenarios en un formato legible tanto para equipos técnicos como no técnicos. Para más información.

Ruta de referencia: https://cucumber.io/docs/gherkin/

**Software Development**

1. Visual Studio Code: Entorno de desarrollo integrado seleccionado para la creación y compilación del código, debido al dominio del equipo con esta herramienta. Este IDE aporta valor al proyecto por su capacidad para añadir extensiones útiles, soportar edición de texto en varios lenguajes de programación y estar disponible en diferentes sistemas operativos, entre otras ventajas.

Ruta de referencia: https://code.visualstudio.com/

2. HTML5: Lenguaje de marcado para la estructura de páginas web. Se utilizará en el proyecto para organizar y presentar el contenido de la aplicación.
   
Ruta de referencia: https://www.w3schools.com/html/html5_syntax.asp

4. CSS: Hojas de Estilo en Cascada, un lenguaje que controla el diseño y la apariencia de las páginas web, complementando a HTML.

Ruta de referencia: https://google.github.io/styleguide/htmlcssguide.html

4. Angular: Framework de desarrollo para aplicaciones web de una sola página (SPA) que utiliza TypeScript. Desarrollado por Google, facilita la creación de aplicaciones web dinámicas y eficientes.

Ruta de referencia: https://angular.io/

5. TypeScript: Lenguaje de programación que extiende JavaScript añadiendo tipado estático y otras características avanzadas, mejorando el desarrollo de aplicaciones complejas y a gran escala.

Ruta de referencia: https://www.typescriptlang.org/

**Software Deployment**

1. Git: Sistema de control de versiones que facilita el registro y la gestión de las diversas versiones del código. Servirá para mantener un historial de modificaciones y simplificar la resolución de errores. El equipo accederá a través de la línea de comandos en sus equipos locales.

Ruta de referencia: https://git-scm.com/

**Software Documentation and Project Management**

1. GitHub: Plataforma en la nube que almacenará los repositorios del proyecto, permitiendo la colaboración en tiempo real y la revisión de las aportaciones de cada miembro del equipo. El acceso se realizará a través de los navegadores web.

Ruta de referencia: https://github.com/

### 5.1.2. Source Code Management

El proyecto implementará el modelo **GitFlow** como estándar para el control de versiones, utilizando **GitHub** como plataforma principal. Este enfoque permitirá una gestión estructurada y ordenada de las ramas, facilitando el desarrollo colaborativo. A continuación, se presenta cómo se integrará GitFlow en el flujo de trabajo y los enlaces a los repositorios de GitHub correspondientes:

**GitFlow Workflow:**
- Ramas principales: `main` y `develop` para producción y desarrollo.
- Ramas de características (features) para el desarrollo de nuevas funcionalidades.
- Ramas de corrección (hotfix) para soluciones rápidas en producción.

**Repositorios de GitHub:**
- Enlace a la organización en GitHub: https://github.com/orgs/Open-Source-SW56-Group-2-EcoMovil/repositories
- Enlace al repositorio de la **Landing Page**: https://open-source-sw56-group-2-ecomovil.github.io/Landing-Page-EcoMovil/
<br>

![gitflow](assets/chapter-5/gitflow.png)

**Estructura de Ramas (Branches) en GitFlow:**

1. **Rama Master (Principal):** Es la rama principal del proyecto, donde se mantendrán versiones estables y finales de la aplicación. Solo se permitirán cambios que hayan sido previamente probados y verificados en otras ramas.

2. **Rama Develop (Desarrollo):** Su función es mantener el progreso continuo del proyecto. Es aquí donde el equipo colaborará en las nuevas funcionalidades antes de que sean incorporadas a la rama principal.

3. **Ramas de Funcionalidad (Feature branches):** Cada nueva característica del proyecto se desarrollará en su propia rama. Una vez completada y probada, se fusionará en la rama de desarrollo. Las ramas seguirán un patrón de nombres descriptivo, por ejemplo, `feature/nombre-de-la-funcionalidad`.

4. **Ramas de Lanzamiento (Release branches):** Estas ramas se crearán cuando una versión esté lista para ser lanzada. Se utilizará el **versionamiento semántico** para asignar un número de versión a cada release.

5. **Ramas de Corrección (Hotfix branches):** Estas ramas se usarán para aplicar correcciones urgentes a la rama principal, generalmente errores críticos que afecten a la experiencia del usuario.

**Convenciones de Commits:**
Se adoptará la especificación **Conventional Commits**, basada en las directrices de **Angular Commit Guidelines**.

### 5.1.3. Source Code Style Guide & Conventions

En EcoMovil se han implementado diversas convenciones de estilo para el desarrollo en varios lenguajes.

#### Tecnologías utilizadas:

**HTML y CSS (Guía de Estilo de Google HTML/CSS):**
- El documento comienza con `!DOCTYPE html`.
- Se incluyen meta etiquetas necesarias y el elemento `title` dentro de `head`.
- Se usa una indentación de dos espacios y minúsculas para elementos, atributos y selectores.
- Los atributos se escriben entre comillas y todos los elementos tienen su etiqueta de cierre.
- Se evita el uso de líneas demasiado largas y las imágenes incluyen especificaciones de tamaño y texto alternativo (`alt`).
- Los atributos de las imágenes incluyen dimensiones `width` y `height` para mejorar la accesibilidad (ej: `<img src="abc.img" alt="image name" style="width:128px;height:128px">`).

**TypeScript:**
- Se emplean clases e interfaces, se agregan comentarios y se controlan flujos lógicos.
- Se usan nombres descriptivos para las variables y funciones.

**Gherkin (Convenciones de Gherkin para especificaciones legibles):**
- Se utilizan las palabras clave "Given", "When", "Then" y "And" para describir los pasos de los escenarios.
- Se indentan los pasos con "And", añadiendo líneas en blanco entre pasos y escenarios.
- Los parámetros se rodean con comillas simples.

**Java:**
- Se usan clases, métodos y variables, siguiendo convenciones funcionales.

**Angular:**
- Los nombres siguen la convención PascalCase.
- Los componentes, servicios y clases están en archivos separados.
- Las plantillas y hojas de estilo se manejan en archivos distintos, con el uso de decoradores como `@Component`, `@Injectable` y `@Input`.
- Se emplea inyección de dependencias para gestionar servicios y las convenciones de código se centran en nombres claros.

**Gherkin**:
- Busca mejorar la comunicación entre negocio y técnico con BDD, organizando los escenarios mediante saltos de línea y palabras clave ("Given", "When", "Then", "And") para estructurar escenarios. Los saltos de línea ayudan a distinguir entre los distintos tipos de escenarios, mejorando la legibilidad y organización.

### 5.1.4. Software Deployment Configuration

**Landing Page Deployment**

Para desplegar la landing page, es necesario cumplir con ciertos requisitos previos, como disponer de una cuenta personal, una organización y un repositorio donde se alojarán los archivos. Con esto listo, se puede comenzar el despliegue. Los pasos son los siguientes:

1. Crear una carpeta llamada "docs" que contendrá la landing page.
2. Verificar que los archivos estén correctamente nombrados: "index.html" para la página principal, "style.css" para los estilos, y una carpeta "img" para las imágenes.
3. Subir los archivos al repositorio con un commit.
4. Dirigirse a Settings > Pages y seleccionar la rama correspondiente, usualmente "main" o "master".
5. Definir la carpeta "docs" como la ubicación de la página.
6. Esperar a que GitHub finalice las comprobaciones. Al terminar, se generará un enlace que permitirá acceder a la landing page publicada.

Este proceso permite el despliegue automático de la landing page utilizando GitHub Pages.

A continuación, se detallarán las acciones llevadas a cabo para alcanzar este propósito.

Lo primero es garantizar que el repositorio esté configurado de manera adecuada.

![Merged-Picture](assets/chapter-5/merged1.png)

En este caso, se ha utilizado Angular para desarrollar una Landing Page, optando por la herramienta angular-cli-pages, que simplifica tanto la actualización de la página como su despliegue en GitHub Pages.

![Angular-Cli](assets/chapter-5/angular-cli.png)

A continuación, se utiliza la herramienta "ngh" para crear una nueva rama llamada "gh-pages", que contendrá los archivos de despliegue y recibe su nombre de la herramienta mencionada.

![Dist](assets/chapter-5/dist.png)

Usamos "ngh" para crear una nueva rama llamada "gh-pages", que almacenará todos los archivos necesarios para el despliegue. El nombre de la rama proviene de la herramienta que estamos utilizando.

![gh-pages](assets/chapter-5/gh.png)

Una vez que los archivos se han publicado en la rama correspondiente, accedemos a "Settings" y, en la sección "Pages", seleccionamos la rama "gh-pages" y la opción / (root). Después de guardar los cambios y esperar un momento, podremos ver la página publicada.

![publish](assets/chapter-5/publish.png)

Así es cómo se verá la página final.

![page](assets/chapter-5/ecomo1.png)

Enlace del Landing Page EcoMovil: https://open-source-sw56-group-2-ecomovil.github.io/Landing-Page-EcoMovil/

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

Un Sprint en el contexto de Scrum es un periodo de tiempo fijo y breve en el que el equipo se enfoca en realizar todas las tareas necesarias para lograr el objetivo del producto definido, denominado "Product Goal" (Scrum Alliance, 2024).

### 5.2.1.1. Sprint Planning 1

Un sprint es un intervalo breve y definido durante el cual se completan tareas o actividades específicas dentro de un proyecto, como se aplica en metodologías ágiles como Scrum. El Sprint #1, que comienza el 14 de agosto de 2024, tiene como objetivo diseñar una landing page atractiva para EcoMovil. Esta página debe captar la atención de los visitantes y resaltar los principales beneficios de nuestro producto.

<table>
     <tr> 
        <th>  Sprint #  </th>
        <th> Sprint 1 </th>
     </tr>
     <tr> 
        <td style="font-weight: bold;" colspan="7"> Sprint Planing Background</td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Date </td>
       <td>  14/08/2024 </td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Time </td>
       <td> 17:00 horas (GMT-5) </td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Location </td>
       <td> Modalidad remota a través de Discord <td>
     </tr>
      <tr>
        <td style="font-weight: bold;"> Prepared By </td>
        <td> Oneglio De Paz, Beth Shantal <td>
     </tr>
        <tr>
        <td style="font-weight: bold;"> Attendees (to planning meeting) </td>
        <td> 
            <br>
             Calisaya Sánchez, Juan Jesús
            <br>
             Gallo Quintana, David Ivanoff
            <br>
            Hidalgo Lopez, Mathias Adriano
            <br>
             Oneglio De Paz, Beth Shantal
            <br>
            Vasquez Goicochea, Erick Alessander
        <td>
     </tr>
     <tr>
        <td style="font-weight: bold;"> Sprint 0 Review Summary </td>
        <td> Dado que este es nuestro primer sprint de desarrollo, no hay un resumen de revisión del sprint disponible. <td>
     </tr>
     <tr>
        <td style="font-weight: bold;"> Sprint 0 Retrospective Summary </td>
        <td> Dado que este es nuestro primer sprint de desarrollo, aún no hemos identificado planes de mejora.<td>
     </tr>
     <tr> 
        <td style="font-weight: bold;" colspan="7"> Sprint Goal & User Stories</td>
     </tr>
       <tr>
          <td style="font-weight: bold;"> Sprint 1 Goal</td>
          <td>  En este sprint, se planea implementar la landing page con las secciones de inicio de sesión, hero y elementos de orientación para el usuario, como el footer y "About". Al finalizar el sprint, la landing page debe estar desplegada en GitHub, y cualquier usuario debería poder acceder y ver la página mediante un enlace. <td>
      </tr>
       <tr>
          <td style="font-weight: bold;"> Sprint 1 Velocity </td>
          <td>  26  <td>
      </tr>
      <tr>
          <td style="font-weight: bold;"> Sum of Story Points </td>
          <td> 26 <td>
      </tr>


  </table>

### 5.2.1.2. Sprint Backlog 1

En el primer sprint backlog, el equipo se propuso comenzar y finalizar la landing page. Para organizar y gestionar a los miembros del equipo, se utilizó Trello, una herramienta que permitió dividir las user stories en tareas manejables y asignarlas a los miembros según sus habilidades. El objetivo principal del sprint era desarrollar completamente la landing page, asegurando que fuera tanto atractiva como funcional.

![Trello](assets/chapter-5/Sprint-1.png)

<table style="width:100%; height:auto; border-collapse: collapse;">
   <tr>
      <th colspan="4"> Sprint # </th>
      <th colspan="7"> Sprint 1 </th>
   </tr>
   <tr>
     <th colspan="4"> User Story </th>
     <th colspan="7"> Work-Item / Task </th>
   </tr>
   <tr>
     <th> Id </th>
     <th colspan="3"> Title </th>
     <th> Id </th>
     <th> Title </th>
     <th> Description </th>
     <th> Estimation (Hours) </th>
     <th> Assigned To </th>
     <th> Status (To-do / In-Process / To-Review / Done) </th>
   </tr>
   <tr>
      <th> US01 </th>
     <th colspan="3"> Barra de navegación en la Landing Page </th>
      <th> UT01 </th>
     <th> Sección de la barra de navegación </th>
     <th> Desarrollar el navbar de la landing page de EcoMovil y asegurar que las opciones de navegación sean intuitivas </th>
     <th> 1 </th>
     <th> Erick Vasquez </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US01 </th>
     <th colspan="3"> Barra de navegación en la Landing Page </th>
      <th> UT02</th>
     <th> Mejoras en la barra de navegación </th>
     <th> Mejorar la interacción del usuario con el navbar añadiendo animaciones o transiciones suaves </th>
     <th> 5 </th>
     <th> Erick Vasquez </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US02 </th>
     <th colspan="3"> Sección Hero en la Landing Page </th>
      <th> UT03</th>
     <th> Sección de Hero </th>
     <th> Crear una sección destacada con una imagen impactante y un título atractivo en la landing page </th>
     <th> 8 </th>
     <th> David Gallo </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US02 </th>
     <th colspan="3"> Sección Hero en la Landing Page </th>
      <th> UT04 </th>
     <th> Ajustes de la sección de Hero </th>
     <th> Ajustar el diseño y la responsividad de la sección hero para diferentes tamaños de pantalla </th>
     <th> 4 </th>
     <th> David Gallo </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US03 </th>
     <th colspan="3"> Sección Footer en la Landing Page </th>
      <th> UT05 </th>
     <th> Sección de pie de página </th>
     <th> Desarrollar la sección del pie de página con enlaces a la información sobre el equipo y los términos de uso </th>
     <th> 2 </th>
     <th> Beth Oneglio </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US03 </th>
     <th colspan="3"> Sección Footer en la Landing Page </th>
      <th> UT06 </th>
     <th> Funcionalidad del pie de página </th>
     <th> Asegurar que los enlaces en el pie de página sean funcionales y estén correctamente organizados </th>
     <th> 5 </th>
     <th> Beth Oneglio </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US04 </th>
     <th colspan="3"> Sección "About Us" en la Landing Page </th>
      <th> UT07 </th>
     <th> Sobre nosotros sección </th>
     <th> Implementar la sección "About us" para ofrecer detalles sobre el equipo y la misión de la empresa </th>
     <th> 8 </th>
     <th> Beth Oneglio </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US04 </th>
     <th colspan="3"> Sección "About Us" en la Landing Page </th>
      <th> UT08 </th>
     <th> Sobre nosotras Contenido de la sección </th>
     <th> Agregar contenido detallado sobre la historia y misión de la empresa en la sección "About us" </th>
     <th> 7 </th>
     <th> Beth Oneglio </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US05 </th>
     <th colspan="3"> Sección de Beneficios en la Landing Page </th>
      <th> UT09</th>
     <th> Sección Beneficios </th>
     <th> Desarrollar una sección que resuma las características clave y beneficios de EcoMovil </th>
     <th> 7 </th>
     <th> Mathias Hidalgo </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US05 </th>
     <th colspan="3"> Sección de Beneficios en la Landing Page </th>
      <th> UT10 </th>
     <th> Disposición de la sección de beneficios </th>
     <th> Ajustar el diseño y los elementos visuales para una mejor presentación de los beneficios </th>
     <th> 6 </th>
     <th> Mathias Hidalgo </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US06 </th>
     <th colspan="3"> Sección de Contacto en la Landing Page </th>
      <th> UT11 </th>
     <th> Sección de contacto </th>
     <th> Agregar la información de contacto del equipo para facilitar la comunicación con los usuarios </th>
     <th> 5 </th>
     <th> Mathias Hidalgo </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US06 </th>
     <th colspan="3"> Sección de Contacto en la Landing Page </th>
      <th> UT12 </th>
     <th> Formulario de contacto </th>
     <th> Implementar un formulario de contacto funcional en la sección </th>
     <th> 5 </th>
     <th> Mathias Hidalgo </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US07 </th>
     <th colspan="3"> Landing Page Responsive con diferentes dispositivos </th>
      <th> UT13 </th>
     <th> Página de destino adaptable </th>
     <th> Asegurar que la landing page sea completamente funcional y visualmente adecuada en diferentes dispositivos y tamaños de pantalla </th>
     <th> 6 </th>
     <th> Juan Calisaya </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US07 </th>
     <th colspan="3"> Landing Page Responsive con diferentes dispositivos </th>
      <th> UT14 </th>
     <th> Optimización para dispositivos móviles </th>
     <th> Optimizar el diseño de la página para una mejor experiencia en dispositivos móviles </th>
     <th> 4 </th>
     <th> Juan Calisaya </th> 
     <th> Done </th>
   </tr>
</table>

### 5.2.1.3. Development Evidence for Sprint Review

| Repository   | Branch                                      | Commit Id | Commit Message                   | User | Commited on (Date) |
| ------------ | ------------------------------------------- | --------- | -------------------------------- | ------------------- | ------------------ |
| landing-page | main       | b863a40         |        | David Gallo | Aug 29, 2024         | 
| landing-page | main       | 36fec62         | feat: add file | Mathias Hidalgo | Aug 29, 2024    |
| landing-page | main       | f827944         | feat: added plans section | Juan Calisaya | Aug 29, 2024       |
| landing-page | main       | cf2b26c   |feat: Added about section         | Beth Oneglio| Aug 30, 2024                |
| landing-page | main       | 8404774             |  feat: Added footer section                     | Beth Oneglio|  Aug 30, 2024 |
| landing-page | main       | b360e5b              |    feat: added header             | Erick Vasquez|      Aug 30, 2024 |
| landing-page | main       | ad8ad4c  |  feat: added how-it-work component     | Erick Vasquez|  Aug 30, 2024 |
| landing-page | main       | 0eb6e8d  |   feat(feature/join): Added join component  | David Gallo|   Sep 1, 2024|
| landing-page | main       | 4aa9478  |  feat(feature/main): added main component  | David Gallo | Sep 1, 2024|
| landing-page | main       | 50b12a4  |  "feat Merge branch 'feature/plans' into develop"| David Gallo | Sep 1, 2024|
| landing-page | main       | b795e73   |  feat: Merged main into develop   | David Gallo | Sep 1, 2024|
| landing-page | main       | c0e34a3    |     feat: merged how-it-works into develop | David Gallo| Sep 1, 2024 |
| landing-page | main       | 80d39b9 |        feat: merged header into develop   | David Gallo |  Sep 1, 2024 |
| landing-page | main       | fc17166 |        feat: merged footer into develop   | David Gallo | Sep 1, 2024 |
| landing-page | main       | db8f49d  |   feat: merged about into develop         | David Gallo | Sep 1, 2024 |
| landing-page | main       | d64296f   |      Create jekyll-gh-pages.yml          | David Gallo |  Sep 1, 2024 |
| landing-page | main       | e4b6d2a |    feat: refactor index.html         | David Gallo| Sep 1, 2024  |
| landing-page | main       | 5721546 |        feat: merged footer into develop | David Gallo |    Sep 1, 2024 |
| landing-page | main       | 06db9c8 |  Merge remote-tracking branch 'refs/remotes/origin/main'  | David Gallo |Sep 1, 2024|
| landing-page | main       | 3274f7d |      feat: added index.html          | David Gallo |  Sep 1, 2024 |
| landing-page | main       | 8842140 |   Create CNAME         | Beth Oneglio |   Sep 4, 2024 |
| landing-page | main       | f5961b4 |   Delete CNAME         | Beth Oneglio |   Sep 4, 2024  |
| landing-page | develop       | b863a40         |         | David Gallo | Aug 29, 2024         | 
| landing-page | develop       | 36fec62         | feat: add file | Mathias Hidalgo | Aug 29, 2024    |
| landing-page | develop       | f827944         | feat: added plans section | Juan Calisaya | Aug 29, 2024       |
| landing-page | develop       | cf2b26c          |   feat: Added about section         | Beth Oneglio|   Aug 30, 2024  |
| landing-page | develop       | 8404774          |   feat: Added footer section        | Beth Oneglio|   Aug 30, 2024  |
| landing-page | develop       | b360e5b          |   feat: added header         | Erick Vasquez|   Aug 30, 2024  |
| landing-page | develop       | ad8ad4c          |   feat: added how-it-work component         | Erick Vasquez|   Aug 30, 2024  |
| landing-page | develop       | 0eb6e8d          |   feat(feature/join): Added join component         | David Gallo|   Sep 1, 2024  |
| landing-page | develop       | 4aa9478          |   feat(feature/main): added main component         | David Gallo|   Sep 1, 2024  |
| landing-page | develop       | 50b12a4          |   "feat Merge branch 'feature/plans' into develop"         | David Gallo|   Sep 1, 2024  |
| landing-page | develop       | b795e73          |   feat: Merged main into develop         | David Gallo|   Sep 1, 2024  |
| landing-page | develop       | c0e34a3          |   feat: merged how-it-works into develop         | David Gallo|   Sep 1, 2024 |
| landing-page | develop       | 80d39b9          |   feat: merged header into develop        | David Gallo|   Sep 1, 2024 |
| landing-page | develop       | fc17166          |   feat: merged footer into develop        | David Gallo|   Sep 1, 2024  |
| landing-page | develop       | db8f49d          |   feat: merged about into develop | David Gallo|   Sep 1, 2024  |
| landing-page | develop       | e6fa6b4          |   feat: added scroll event         | David Gallo|  Sep 1, 2024  |
| landing-page | feature/about       | b863a40         |         | David Gallo | Aug 29, 2024         | 
| landing-page | feature/about       | 36fec62         | feat: add file | Mathias Hidalgo | Aug 29, 2024    |
| landing-page | feature/about       | cf2b26c         |   feat: Added about section         | Beth Oneglio |   Aug 30, 2024  |
| landing-page | feature/footer      | b863a40          |           | David Gallo |   Aug 29, 2024  |
| landing-page | feature/footer      | 36fec62          |   feat: add file         | Mathias Hidalgo |   Aug 29, 2024  |
| landing-page | feature/footer      | 8404774          |   feat: Added footer section         | Beth Oneglio |   Aug 30, 2024  |
| landing-page | feature/header      | b863a40          |           | David Gallo |   Aug 29, 2024  |
| landing-page | feature/header      | 36fec62          |   feat: add file         | Mathias Hidalgo |   Aug 29, 2024  |
| landing-page | feature/header      | b360e5b          |   feat: added header        | Erick Vasquez |   Aug 30, 2024  |
| landing-page | feature/how-it-works       | b863a40          |            | David Gallo |   Aug 29, 2024  |
| landing-page | feature/how-it-works       | 36fec62          |   feat: add file         | Mathias Hidalgo |   Aug 29, 2024  |
| landing-page | feature/how-it-works       | ad8ad4c          |   feat: added how-it-work component         | Erick Vasquez|   Aug 30, 2024  |
| landing-page | feature/join       | b863a40          |            | David Gallo |   Aug 29, 2024  |
| landing-page | feature/join       | 36fec62          |   feat: add file         | Mathias Hidalgo |   Aug 29, 2024  |
| landing-page | feature/join       | 0eb6e8d          |   eat(feature/join): Added join component         | David Gallo |   Aug 30, 2024  |
| landing-page | feature/main       | b863a40          |            | David Gallo |   Aug 29, 2024  |
| landing-page | feature/main       | 36fec62          |   feat: add file         | Mathias Hidalgo |   Aug 29, 2024  |
| landing-page | feature/main       | 4aa9478          |   feat(feature/main): added main component         | David Gallo |   Aug 30, 2024  |
| landing-page | feature/plans       | b863a40          |            | David Gallo |   Aug 29, 2024  |
| landing-page | feature/plans       | 36fec62          |   feat: add file         | Mathias Hidalgo |   Aug 29, 2024  |
| landing-page | feature/plans       | f827944          |   feat: added plans section         | Juan Calisaya |   Aug 29, 2024  |
| landing-page | gh-pages       | f8695f0          |   Auto-generated commit         | David Gallo |   Sep 1, 2024  |
| landing-page | gh-pages       | c74bd50          |   Auto-generated commit         | David Gallo |   Sep 1, 2024  |

### 5.2.1.4. Testing Suite Evidence for Sprint Review

Para la entrega del Sprint 1, nos enfocamos en lograr el desarrollo completo, la implementación y el despliegue del Landing Page. Por lo tanto, la sección de "Testing" se enfocó en la implementación de las necesidades de los usuarios, priorizando secciones fáciles de entender e intuitivas.

| Repository                                                  | Branch         | Commit ID | Commit Message                  | Commited on (Date) |
|-------------------------------------------------------------|----------------|-----------|----------------------------------|--------------------|
| [https://github.com/Open-Source-SW56-Group-2-EcoMovil/Landing-Page-EcoMovil.git](https://github.com/Open-Source-SW56-Group-2-EcoMovil/Landing-Page-EcoMovil.git) | LandingPage | adebcba  | feat: added project landing page  | 29/08/24           |

### 5.2.1.5. Execution Evidence for Sprint Review

En el sprint 1 se logró un avance parcial en la implementación y despliegue de la landing page. Esta página presenta varias secciones donde el usuario puede encontrar información relevante sobre el producto y la startup. A continuación, se presentan algunas evidencias:

![page](assets/chapter-5/ecomo1.png)

![page](assets/chapter-5/ecomo2.png)

![page](assets/chapter-5/ecomo3.png)

![page](assets/chapter-5/ecomo4.png)

![page](assets/chapter-5/ecomo5.png)

![page](assets/chapter-5/ecomo6.png)

### 5.2.1.6. Services Documentation Evidence for Sprint Review

En este Sprint 1, el enfoque principal ha sido la creación del Landing Page de la aplicación EcoMovil, por lo que no se ha avanzado en la documentación de los servicios. No obstante, está previsto que la documentación de los servicios se desarrolle en los próximos sprints.

### 5.2.1.7. Software Deployment Evidence for Sprint Review

En la entrega del segundo sprint, se desplegó un Landing Page completamente funcional, cumpliendo con las user stories asignadas para este entregable. Durante el Sprint 1, se lanzó la primera versión del Landing Page, que fue alojada en GitHub Pages. A continuación, se presentan las evidencias del despliegue del Landing Page.

- Instrucciones para acceder al Landing Page:

Finalizando la implementación de los cambios y fusionándolos en la rama principal (`main`).

![Main-Capture](assets/chapter-5/main.png)

Nos dirigimos a la sección de "Settings" del repositorio y seleccionamos el apartado de "Pages".

![Seeting-Capture](assets/chapter-5/settingandpages.png)

Seleccionamos la rama `gh-pages` como fuente de despliegue, luego hacemos clic en "Save" para ejecutar el deploy.

![GhPages-Capture](assets/chapter-5/ghpages.png)

Accedemos al dominio del Landing Page, verificamos que todo esté correctamente configurado y hacemos clic en "Guardar" para finalizar el proceso.

- Imágenes de la pantalla del Landing Page:

![page](assets/chapter-5/ecomo1.png)

![page](assets/chapter-5/ecomo2.png)

![page](assets/chapter-5/ecomo3.png)

![page](assets/chapter-5/ecomo4.png)

![page](assets/chapter-5/ecomo5.png)

![page](assets/chapter-5/ecomo6.png)

### 5.2.1.8. Team Collaboration Insights during Sprint

En esta sección, presentaremos los hallazgos de nuestro equipo para evaluar los resultados del trabajo realizado y la actividad generada.

| Alumno | Actividad | 
|-----------|-----------|
| Calisaya Sánchez, Juan Jesús | Elaboración de las secciones de "Planes" ("plans"). | 
| Gallo Quintana, David Ivanoff | Diseño de la sección "Únete" ("join") y la sección principal ("main"). | 
| Hidalgo Lopez, Mathias Adriano | Desarrollo de la sección "Quién Puede Usar" ("who-can-use"). | 
| Oneglio De Paz, Beth Shantal | Desarrollo de la sección "Acerca de" y el pie de página ("footer") de la página de inicio. | 
| Vasquez Goicochea, Erick Alessander | Creación del encabezado ("header") y la sección "Cómo Funciona" ("how-it-works"). | 

### 5.2.2. Sprint 2

En Scrum, un Sprint es un intervalo de tiempo corto y determinado durante el cual el equipo se dedica a completar todas las tareas requeridas para alcanzar el objetivo del producto, conocido como "Product Goal" (Scrum Alliance, 2024).

### 5.2.2.1. Sprint Planning 2

El Sprint #2, que inicia el 12 de septiembre de 2024, se centrará en el diseño del front-end, concretamente en la creación de la landing page de EcoMovil. El objetivo es permitir que nuestro público pueda visualizar e interactuar con la página web una vez esté desplegada, siguiendo el enfoque ágil de metodologías como Scrum, donde un sprint es un período corto y definido para completar tareas clave del proyecto.

<table>
     <tr> 
        <th>  Sprint #  </th>
        <th> Sprint 2 </th>
     </tr>
     <tr> 
        <td style="font-weight: bold;" colspan="7"> Sprint Planing Background</td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Date </td>
       <td>  19/09/2024 </td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Time </td>
       <td> 17:00 horas (GMT-5) </td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Location </td>
       <td> Modalidad remota a través de Discord <td>
     </tr>
      <tr>
        <td style="font-weight: bold;"> Prepared By </td>
        <td> Oneglio De Paz, Beth Shantal <td>
     </tr>
        <tr>
        <td style="font-weight: bold;"> Attendees (to planning meeting) </td>
        <td> 
            <br>
             Calisaya Sánchez, Juan Jesús
            <br>
             Gallo Quintana, David Ivanoff
            <br>
            Hidalgo Lopez, Mathias Adriano
            <br>
             Oneglio De Paz, Beth Shantal
            <br>
            Vasquez Goicochea, Erick Alessander
        <td>
     </tr>
     <tr>
        <td style="font-weight: bold;"> Sprint 1 Review Summary </td>
        <td> Dado que este es nuestro primer sprint de desarrollo, no hay un resumen de revisión del sprint disponible. <td>
     </tr>
     <tr>
        <td style="font-weight: bold;"> Sprint 1 Retrospective Summary </td>
        <td> Dado que este es nuestro primer sprint de desarrollo, aún no hemos identificado planes de mejora.<td>
     </tr>
     <tr> 
        <td style="font-weight: bold;" colspan="7"> Sprint Goal & User Stories</td>
     </tr>
       <tr>
          <td style="font-weight: bold;"> Sprint 2 Goal</td>
          <td>  Detectamos algunas áreas que pueden optimizarse en las funcionalidades existentes y también planeamos incorporar la funcionalidad de i18n en la landing page. Además, desarrollaremos el front-end de la aplicación web para que sea tanto atractiva como funcional. <td>
      </tr>
       <tr>
          <td style="font-weight: bold;"> Sprint 2 Velocity </td>
          <td>  26  </td>
      </tr>
      <tr>
          <td style="font-weight: bold;"> Sum of Story Points </td>
          <td> 26 <td>
      </tr>
  </table>

### 5.2.2.2. Sprint Backlog 2

En el backlog del segundo sprint, el equipo se comprometió a iniciar y completar la creación y despliegue del front-end. Para coordinar y gestionar al equipo, se utilizó Trello, una herramienta que facilitó la división de las user stories en tareas más manejables, asignándolas a los miembros según sus habilidades. El objetivo principal del sprint fue desarrollar y desplegar un front-end que fuera tanto atractivo como funcional.

![Trello](assets/chapter-5/Sprint-2.png)

Link del Trello: https://trello.com/b/48W0tEjF/ecomovil-product-backlog-tp

<table style="width:400px; height:100px;"> 
   <tr>
      <th colspan="4"> Sprint # </th>
      <th colspan="7"> Sprint 2 </th>
   </tr>
   <tr >
     <th colspan="4"> User Story </th>
     <th colspan="7"> Work-Item /Task</th>
   </tr>
   <tr>
     <th > Id </th>
     <th colspan="3"> Title </th>
     <th> Id </th>
     <th > Title </th>
     <th> Description </th>
     <th> Estimation (Hours) </th>
     <th> Assigned To </th> 
     <th> Status (To-do / In-Process / To- Review / Done) </th>
   </tr>
   <tr>
      <th> US16 </th>
     <th colspan="3"> Sección Crear una cuenta en EcoMovil </th>
      <th> TK01  </th>
     <th> Sección de creación de usuarios</th>
     <th> Desarrollar el Create-User de nuestro front-end de EcoMovil nos permite que el usuario pueda registrarse en la página. </th>
     <th> 1  </th>
     <th> Beth Oneglio </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> </th>
     <th colspan="3"></th>
      <th> TK02 </th>
     <th> Validación de formulario </th>
     <th> Implementar validaciones de los formularios para garantizar que la información ingresada sea correcta antes de registrarse. </th>
     <th> 5 </th>
     <th> Beth Oneglio </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US17 </th>
     <th colspan="3"> Sección Inicio de sesión en EcoMovil </th>
      <th> TK03  </th>
     <th> Sección de inicio de sesión</th>
     <th> Implementar el inicio de sesión en nuestro front-end ayuda a que el usuario pueda entrar con su cuenta ya creada. </th>
     <th> 8  </th>
     <th> Beth Oneglio </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> </th>
     <th colspan="3"></th>
      <th> TK04 </th>
     <th> Persistencia de la sesión </th>
     <th> Implementar la persistencia de sesión para mantener al usuario logueado mientras navega en la aplicación. </th>
     <th> 4 </th>
     <th> Beth Oneglio </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US18 </th>
     <th colspan="3"> Sección Botón “Elija un plan” </th>
      <th> TK05  </th>
     <th> Botón Sección "Elija un plan" </th>
     <th> La implementación del botón es para que los universitarios puedan comprar una suscripción y registrar sus vehículos menores para que los usuarios puedan alquilarlos. </th>
     <th> 2  </th>
     <th> Erick </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> </th>
     <th colspan="3"></th>
      <th> TK06 </th>
     <th> Flujo de suscripción </th>
     <th> Implementar el flujo de suscripción para que los usuarios puedan seleccionar un plan y proceder con el pago. </th>
     <th> 7 </th>
     <th> Erick </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US19</th>
     <th colspan="3"> Sección Mensaje de “Pago exitoso” </th>
      <th> TK07  </th>
     <th> Mensaje Sección "Pago exitoso" </th>
     <th> Implementar el mensaje es para confirmar al usuario que su pago se realizó correctamente. </th>
     <th> 8  </th>
     <th> Erick </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> </th>
     <th colspan="3"></th>
      <th> TK08</th>
     <th>Confirmación de pago </th>
     <th> Implementar la lógica de confirmación de pago para asegurar que el usuario reciba un mensaje tras completar su transacción. </th>
     <th> 5 </th>
     <th> Erick </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US20</th>
     <th colspan="3"> Implementación de API para Búsqueda Geolocalizada de Vehículos</th>
      <th> TK09  </th>
     <th> Sección de geolocalización </th>
     <th> Implementar una API para Búsqueda Geolocalizada de Vehículos permite que los clientes puedan visualizar en qué punto están los vehículos alquilados. </th>
     <th> 7  </th>
     <th> David </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> </th>
     <th colspan="3"></th>
      <th>TK10 </th>
     <th> Precisión de geolocalización </th>
     <th> Mejorar la precisión de la geolocalización para garantizar que los usuarios puedan ver la ubicación exacta de los vehículos. </th>
     <th> 1 </th>
     <th> David </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> US21 </th>
     <th colspan="3"> Sección Historial de Vehículos </th>
      <th> TK11  </th>
     <th> Sección de Historia del Vehículo </th>
     <th> Agregar un historial de vehículos permite visualizar todos los vehículos que tiene un universitario en alquiler y por alquilar. </th>
     <th> 5 </th>
     <th> Juan Calisaya </th> 
     <th> Done </th>
   </tr>
   <tr>
      <th> </th>
     <th colspan="3"></th>
      <th>TK12 </th>
     <th> Filtros de historial </th>
     <th> Implementar filtros de búsqueda para que los usuarios puedan ordenar su historial de vehículos por fecha, estado o tipo de vehículo. </th>
     <th> 4 </th>
     <th> Juan Calisaya </th> 
     <th> Done </th>
   </tr>
   <tr>
        <th> US23 </th>
         <th colspan="3"> Foro de Contactos </th>
          <th> TK13  </th>
         <th> Sección del foro de contacto </th>
         <th> Implementar el foro de contacto ayuda a visualizar las opiniones que tienen los clientes sobre los vehículos. </th>
         <th> 5 </th>
         <th> Mathias Hidalgo </th> 
         <th> Done </th>
    </tr>
   <tr>
      <th> </th>
     <th colspan="3"></th>
      <th> TK14 </th>
     <th>Interacción en el foro </th>
     <th> Mejorar la interacción en el foro permitiendo que los usuarios puedan responder y valorar los comentarios. </th>
     <th> 2 </th>
     <th> Mathias Hidalgo </th> 
     <th> Done </th>
   </tr>
</table>

### 5.2.2.3. Development Evidence for Sprint Review

Como evidencia del sprint review, se presenta una tabla que muestra los commits realizados durante este segundo sprint. Dado que se acordó trabajar en los ajustes finales de la landing page y en el frontend de la aplicación web, se incluyen commits de varios repositorios en los que se realizaron dichas tareas.

| Repository   | Branch                                      | Commit Id | Commit Message                   | User | Commited on (Date) |
| ------------ | ------------------------------------------- | --------- | -------------------------------- | ------------------- | ------------------ |
| Front-End-Ecomovil | main       | bfd8076         | initial commit       | David Gallo | Sep 16, 2024         | 
| Front-End-Ecomovil | main       | e01d04a         | feat(main): Added packages for Angular Material, primeflex, tailwindcss and i18n | David Gallo | Sep 16, 2024    |
| Front-End-Ecomovil | main       | cfad3b1         | feat: added header component for acquirer and Student | David Gallo| Sep 16, 2024       |
| Front-End-Ecomovil | main       | 7d81c3f   |feat(vehicle-section): add vehicle-section component         | David Gallo| Sep 16, 2024                |
| Front-End-Ecomovil | main       | 0f88d27             |  feat(fake-api): setup fake api configuration.                   | David Gallo|  Sep 18, 2024 |
| Front-End-Ecomovil | contact-forum       | aa74bd2              |    feat: add feactures-contact-forum          | Mathias Hidalgo |      Sep 20, 2024 |
| Front-End-Ecomovil | log-in       | 43fee81  |  feat: add log in     | Beth Oneglio |  Sep 19, 2024 |
| Front-End-Ecomovil | planes-profileAcquirer      | 3920ff8  |   feat: add dashboard component  | Erick Vasquez |   Sep 23, 2024|
| Front-End-Ecomovil | planes-profileAcquirer       | 570aaef  |  feat: add profileAcquirer component  | Erick Vasquez | Sep 23, 2024|
| Front-End-Ecomovil | planes-profileAcquirer       | df680b1  |  feat: add confirmation component| Erick Vasquez | Sep 23, 2024|
| Front-End-Ecomovil | planes-profileAcquirer       | e832ad4   |  feat: update db.json   | Erick Vasquez | Sep 23, 2024|
| Front-End-Ecomovil | planes-profileAcquirer       | 0f960b4    |     feat: add profile-page component | Erick Vasquez | Sep 23, 2024 |
| Front-End-Ecomovil | planes-profileAcquirer       | 98d085e |        feat: update routes  | Erick Vasquez |  Sep 23, 2024 |
| Front-End-Ecomovil | planes-profileAcquirer      | 2a22d45 |   fix: delete unused imports   | Erick Vasquez | Sep 23, 2024 |
| Front-End-Ecomovil | planes-profileAcquirer       | 6ae8312  |   feature: update routes       | Erick Vasquez | Sep 23, 2024 |
| Front-End-Ecomovil | planes-profileAcquirer       | 736f5a9   |     fix: delete unused imports         | Erick Vasquez |  Sep 23, 2024 |
| Front-End-Ecomovil | planes-profileAcquirer       | 5f46c1a |   feature: add plan-item & plan-list components      | Erick Vasquez | Sep 23, 2024  |
| Front-End-Ecomovil | planes-profileAcquirer      | f7a7f0d |     feature: add payment component | Erick Vasquez |    Sep 23, 2024 |
| Front-End-Ecomovil | planes-profileAcquirer       | aa7233d |  feature: add payment Service Shared  | Erick Vasquez |Sep 23, 2024|
| Front-End-Ecomovil | planes-profileAcquirer      | db9fd87 |   feature: add planes-page component      | Erick Vasquez |  Sep 23, 2024 |
| Front-End-Ecomovil | planes-profileAcquirer     | 0b65553|  feature: add global variables      | Erick Vasquez |   Sep 23, 2024 |
| Front-End-Ecomovil | planes-profileAcquirer       | 09d5c98 | feature: update routes        | Erick Vasquez |   Sep 23, 2024  |
| Front-End-Ecomovil | planes-profileAcquirer       | db7ddf9        |   feature: add payment-page.component      | Erick Vasquez | Sep 23, 2024         | 
| Front-End-Ecomovil | planes-profileAcquirer       | e578368        | feature: add paypal script | Erick Vasquez | Sep 23, 2024    |
| Front-End-Ecomovil | planes-profileAcquirer       | 8949cce      | feature: update routes | Erick Vasquez | Sep 23, 2024       |
| Front-End-Ecomovil | planes-profileAcquirer      | 0e4e6a5      |  feature: update db.json   | Erick Vasquez |   Sep 23, 2024  |
| Front-End-Ecomovil | planes-profileAcquirer     | d03086c         |  feature: add validation to profile form     | Erick Vasquez |   Sep 23, 2024  |
| Front-End-Ecomovil | profile-university-student       | 7da6ae    |  feat: added markers        | David Gallo |   Sep 19, 2024  |
| Front-End-Ecomovil | profile-university-student       | 81c37bd      |  feat(interactive-map): Added more markers and new values to entity    | David Gallo| Sep 19, 2024  |
| Front-End-Ecomovil | profile-university-student       | 0f0c36d|  feat(interactive-map): add router       | David Gallo |   Sep 19, 2024  |
| Front-End-Ecomovil | profile-university-student       | dd1d6b0|  feat: added localization to vehicle post component       | David Gallo|   Sep 19, 2024  |
| Front-End-Ecomovil | profile-university-student     | 99bb5ed   |  eat(vehicle-post): add commentaries   | David Gallo|   Sep 19, 2024  |
| Front-End-Ecomovil | profile-university-student       | 14d53d4     |   feat(vehicle-details): add vehicle-details component        | David Gallo|   Sep 19, 2024  |
| Front-End-Ecomovil | profile-university-student       | 8fa0f80       |   featvehicle-details: added stars component for vehicle details    | David Gallo|   Sep 19, 2024 |
| Front-End-Ecomovil | profile-university-student       | 07dc164  | feat(vehicle-details): change stars review distribution  | David Gallo|   Sep 19, 2024 |
| Front-End-Ecomovil | register-acquirer      | e35baed       |      feat: add register acquirer.      | Beth Oneglio |  Sep 19, 2024  |
| Front-End-Ecomovil | register-university-student      | b6f895  |   feat: add register university page component.| Beth Oneglio |   Sep 19, 2024  |
| Front-End-Ecomovil | vehicles-choose    | d13329 |  feat: add vehiclesAcquirers component| Erick Vasquez|   Sep 24, 2024  |
| Front-End-Ecomovil | profile-university-student    | 4680ab7 |feat(profile): update db.json with university student and acquirer profiles |Juan Calisaya|   Sep 24, 2024  |
| Front-End-Ecomovil | profile-university-student    | 297c474 |feat(auth): create class user.entity |Juan Calisaya|   Sep 24, 2024  |
| Front-End-Ecomovil | profile-university-student    | 69d5443 |feat(user): implemented user service |Juan Calisaya|   Sep 24, 2024  |
| Front-End-Ecomovil | profile-university-student    | ca74814 |feat(pages): implemented profile university component |Juan Calisaya|   Sep 24, 2024  |
| Front-End-Ecomovil | profile-university-student    | 32ac7a4 |feat(profile): add path profile in router |Juan Calisaya|   Sep 24, 2024  |
| Front-End-Ecomovil | filter-acquirer    | 2711518 | feat(server): update db.json for filter |Juan Calisaya|   Sep 24, 2024  |
| Front-End-Ecomovil | filter-acquirer    | bc48403 | feat(server): update db.json for filter(2) |Juan Calisaya|   Sep 24, 2024  |
| Front-End-Ecomovil | filter-acquirer    | d604484 | feat(filter): implement filter acquirer component |Juan Calisaya|   Sep 24, 2024  |

### 5.2.2.4. Testing Suite Evidence for Sprint Review

Para la entrega del Sprint 2, nos enfocamos en lograr el desarrollo completo, la implementación y el despliegue del Landing Page. Por lo tanto, la sección de "Testing" se enfocó en la implementación de las necesidades de los usuarios, priorizando secciones fáciles de entender e intuitivas.

| Repository                                    | Branch    | Commit Id      | Commit Message                              | Commit Message Body                   | Committed on (Date) |
|-----------------------------------------------|-----------|----------------|---------------------------------------------|---------------------------------------|----------------------|
| https://github.com/Open-Source-SW56-Group-2-EcoMovil/Acceptance-Tests | Epic/Acceptance-Tests/epic-02 | 700b47e7810dc889051eec663b8447fcef58ca98 | feat: add epic 2 and 3 | | 18/11/2024 |

### 5.2.2.5. Execution Evidence for Sprint Review

En el sprint 2, se logró un avance parcial en la implementación y despliegue del front-end. Se desarrollaron varias secciones clave donde el usuario puede interactuar con las funcionalidades principales del sistema. A continuación, se presentan algunas evidencias:

![page](assets/chapter-5/Capture6.png)

![page](assets/chapter-5/Capture7.png)

![page](assets/chapter-5/Capture8.png)

![page](assets/chapter-5/Capture9.png)

![page](assets/chapter-5/Capture10.png)

![page](assets/chapter-5/Capture11.png)

![page](assets/chapter-5/Capture12.png)

![page](assets/chapter-5/Capture13.png)

![page](assets/chapter-5/Capture14.png)

![page](assets/chapter-5/Capture15.png)

![page](assets/chapter-5/Capture16.png)

![page](assets/chapter-5/Capture17.png)

### 5.2.2.6. Services Documentation Evidence for Sprint Review

En este Sprint 2, el enfoque principal ha sido la creación del front-end de la aplicación, con todos sus componentes, servicios respectivos. Sin embargo, está previsto que se realicen mejoras en la gestión de rutas y validaciones.

### 5.2.2.7. Software Deployment Evidence for Sprint Review

En la entrega del segundo sprint, se lanzó el landing page completamente funcional, cumpliendo con los user stories correspondientes al entregable. De igual manera, se desplegó la aplicación web de manera parcial, ya que aún presenta algunos errores que serán solucionados en el próximo sprint.

**Landing Page**:  

El despliegue de la página de destino en GitHub Pages se actualizó, lo que permitió actualizar la implementación de la página de destino.

![LandingPage](assets/chapter-5/deployment-landing-page.png) 

**Capturas de pantalla de la Landing Page**:

![page](assets/chapter-5/ecomo1.png)

![page](assets/chapter-5/ecomo2.png)

![page](assets/chapter-5/ecomo3.png)

![page](assets/chapter-5/ecomo4.png)

![page](assets/chapter-5/ecomo5.png)

![page](assets/chapter-5/ecomo6.png)

**Web Applications**: 

Se certifica la correcta implementación del frontend de la aplicación web en Azure.

Enlace del Deployment: https://happy-tree-09edbd910.5.azurestaticapps.net/

![page](assets/chapter-5/deployment-front-end-1.jpg)

![page](assets/chapter-5/deployment-front-end-2.jpg)

![page](assets/chapter-5/deployment-front-end-3.jpg)

![page](assets/chapter-5/deployment-front-end-4.jpg)

![page](assets/chapter-5/deployment-front-end-5.jpg)

![page](assets/chapter-5/deployment-front-end-6.jpg)

![page](assets/chapter-5/deployment-front-end-7.jpg)

### 5.2.2.8. Team Collaboration Insights during Sprint

En esta sección, presentaremos los hallazgos de nuestro equipo para evaluar los resultados del trabajo realizado y la actividad generada.

| Alumno | Actividad | 
| ------------ | ------------------------------------------- | 
| Calisaya Sánchez, Juan Jesús | Elaborar componente profile Universitario, componente filter Adquiriente. | 
| Gallo Quintana, David Ivanoff | Elaborar componente my vehicles, componente badges, componente interactive map.  | 
| Hidalgo Lopez, Mathias Adriano | Despliegue de la aplicación. Conectar landing page con aplicación. Elaborar componente browsing history, componente contact forum. | 
| Oneglio De Paz, Beth Shantal | Elaborar componente register, componente log in. | 
| Vasquez Goicochea, Erick Alessander | Elaborar componente plans, componente checkout, componente menu. | 

Repositorio Web-Application-EcoMovil:

![Insights](assets/chapter-5/insights-front-end.png) 

### 5.2.3. Sprint 3 

El Sprint #3, que inicia el 17 de octubre de 2024, se centrará en el diseño del front-end de EcoMovil. El objetivo es permitir que nuestro público pueda visualizar e interactuar con la aplicación web una vez esté desplegada, siguiendo el enfoque ágil de metodologías como Scrum, donde un sprint es un período corto y definido para completar tareas clave del proyecto.

Durante este sprint, nuestro equipo completó los aspectos finales del front-end y comenzó a establecer la estructura del back-end.

### 5.2.3.1. Sprint Planning 3

<table>
     <tr> 
        <th>  Sprint #  </th>
        <th> Sprint 3 </th>
     </tr>
     <tr> 
        <td style="font-weight: bold;" colspan="7"> Sprint Planing Background</td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Date </td>
       <td>  28/09/2024 </td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Time </td>
       <td> 17:00 horas (GMT-5) </td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Location </td>
       <td> Modalidad remota a través de Discord <td>
     </tr>
      <tr>
        <td style="font-weight: bold;"> Prepared By </td>
        <td> Oneglio De Paz, Beth Shantal <td>
     </tr>
        <tr>
        <td style="font-weight: bold;"> Attendees (to planning meeting) </td>
        <td> 
            <br>
             Calisaya Sánchez, Juan Jesús
            <br>
             Gallo Quintana, David Ivanoff
            <br>
            Hidalgo Lopez, Mathias Adriano
            <br>
             Oneglio De Paz, Beth Shantal
            <br>
            Vasquez Goicochea, Erick Alessander
        <td>
     </tr>
     <tr>
        <td style="font-weight: bold;"> Sprint 2 Review Summary </td>
        <td> Durante el desarrollo del Sprint 2, se logró implementar con éxito el frontend de EcoMovil y se realizó el despliegue utilizando GitHub Pages. Se cumplió con todos los requisitos funcionales establecidos para el sprint. <td>
     </tr>
     <tr>
        <td style="font-weight: bold;"> Sprint 2 Retrospective Summary </td>
        <td> El Sprint 2 fue satisfactorio. Como mejora, haremos el merge anticipadamente y mantendremos una comunicación más constante con el líder para evitar conflictos en el desarrollo del frontend y informe.<td>
     </tr>
     <tr> 
        <td style="font-weight: bold;" colspan="7"> Sprint Goal & User Stories</td>
     </tr>
       <tr>
          <td style="font-weight: bold;"> Sprint 3 Goal</td>
          <td>  Nuestro equipo logró avances significativos en el desarrollo del front-end y en la estructuración del back-end. Se estableció una arquitectura sólida, implementando distintos bounded contexts con sus respectivos aggregate roots, así como la división adecuada entre entidades y value objects. Esta organización permite una clara separación de responsabilidades y facilita la gestión de tareas dentro del proyecto.  Se aplicó parcialmente giel patrón CQRS (Command Query Responsibility Segregation) para separar las operaciones de lectura y escritura en el sistema. <td>
      </tr>
       <tr>
          <td style="font-weight: bold;"> Sprint 3 Velocity </td>
          <td>  34  </td>
      </tr>
      <tr>
          <td style="font-weight: bold;"> Sum of Story Points </td>
          <td> 34 <td>
      </tr>
  </table>
  
### 5.2.3.2. Sprint Backlog 3

En el backlog del tercer sprint, el equipo se comprometió a iniciar y completar la creación y despliegue del back-end. Para coordinar y gestionar al equipo, se utilizó Trello, una herramienta que facilitó la división de las user stories en tareas más manejables, asignándolas a los miembros según sus habilidades. El objetivo principal del sprint fue desarrollar y desplegar un front-end que fuera tanto atractivo como funcional.

<table style="width: 100%; border-collapse: collapse;">
   <thead>
      <tr>
         <th colspan="1">Sprint #</th>
         <th colspan="7">Sprint 3</th>
      </tr>
      <tr>
         <th colspan="2">User Story</th>
         <th colspan="6">Work-Item / Task</th>
      </tr>
      <tr>
         <th>Id</th>
         <th>Title</th>         
         <th>Id</th>
         <th>Title</th>
         <th>Description</th>
         <th>Estimation (Hours)</th>
         <th>Assigned To</th>
         <th>Status (To-do / In-Process / To-Review / Done)</th>
      </tr>
   </thead>
<tbody>
   <tr>
      <tr>
         <td rowspan="3">US18</td>
         <td rowspan="3">Bot&oacute;n &ldquo;Elija un plan&rdquo;</td>
      </tr>
      <tr>
         <td>TK17</td>
         <td>Endpoint para redirecci&oacute;n de planes</td>
         <td>Configurar endpoint que gestione la redirecci&oacute;n del bot&oacute;n para mostrar detalles de pago.</td>
         <td>4</td>
         <td>Erick V&aacute;squez</td>
         <td>Done</td>            
      </tr>   
      <tr>
         <td>TK18</td>
         <td>L&oacute;gica de control para selecci&oacute;n de planes</td>
         <td>Implementar l&oacute;gica de backend para almacenar selecci&oacute;n de planes en la base de datos.</td>
         <td>8</td>
         <td>Erick V&aacute;squez</td>
         <td>Done</td>            
      </tr>      
   </tr>
   <tr>
      <tr>
         <td rowspan="3">US20</td>
         <td rowspan="3">Bot&oacute;n &ldquo;Agregar veh&iacute;culo&rdquo;</td>
      </tr>
      <tr>
         <td>TK19</td>
         <td>Servicio para publicar veh&iacute;culos</td>
         <td>Crear servicio que gestione la publicaci&oacute;n de veh&iacute;culos en la plataforma.</td>
         <td>6</td>
         <td>Juan Calisaya</td>
         <td>Done</td>
      </tr>   
      <tr>
         <td>TK20</td>            
         <td>Validaci&oacute;n de datos para veh&iacute;culo</td>
         <td>Implementar validaci&oacute;n en backend para datos de publicaci&oacute;n de veh&iacute;culo.</td>
         <td>6</td>
         <td>Juan Calisaya</td>
         <td>Done</td>          
      </tr>      
   </tr>
   <tr>
      <tr>
         <td rowspan="3">US26</td>
         <td rowspan="3">B&uacute;squeda de veh&iacute;culos</td>
      </tr>
      <tr>
         <td>TK21</td>
         <td>Filtrar veh&iacute;culos por tipo</td>
         <td>Desarrollar l&oacute;gica de backend para filtrar veh&iacute;culos por tipo.</td>
         <td>6</td>
         <td>Juan Calisaya</td>
         <td>Done</td>
      </tr>   
      <tr>
         <td>TK22</td>            
         <td>Filtrar veh&iacute;culos por ubicaci&oacute;n</td>
         <td>Implementar l&oacute;gica para filtrar veh&iacute;culos por ubicaci&oacute;n en el backend.</td>
         <td>5</td>
         <td>Mathias Hidalgo</td>
         <td>Done</td>          
      </tr>      
   </tr>
   <tr>
      <tr>
         <td rowspan="3">US27</td>
         <td rowspan="3">Crear discusi&oacute;n en el foro</td>
      </tr>
      <tr>
         <td>TK23</td>
         <td>API para creaci&oacute;n de discusiones en foro</td>
         <td>Desarrollar endpoint que permita crear discusiones en el foro.</td>
         <td>6</td>
         <td>Beth Oneglio</td>
         <td>Done</td>
      </tr>   
      <tr>
         <td>TK24</td>            
         <td>Notificaci&oacute;n de respuestas en foro</td>
         <td>Implementar notificaciones en backend para alertar al usuario sobre respuestas.</td>
         <td>5</td>
         <td>Beth Oneglio</td>
         <td>Done</td>          
      </tr>      
   </tr>
   <tr>
      <tr>
         <td rowspan="3">US28</td>
         <td rowspan="3">Actualizar perfil</td>
      </tr>
      <tr>
         <td>TK25</td>
         <td>API para actualizaci&oacute;n de perfil</td>
         <td>Crear servicio para permitir a usuarios actualizar sus datos de perfil.</td>
         <td>8</td>
         <td>David Gallo</td>
         <td>Done</td>
      </tr>   
      <tr>
         <td>TK26</td>            
         <td>Validaci&oacute;n en backend de perfil de usuario</td>
         <td>Incluir validaci&oacute;n de campos en la actualizaci&oacute;n del perfil desde backend.</td>
         <td>6</td>
         <td>David Gallo</td>
         <td>Done</td>          
      </tr>      
   </tr>
</tbody>
</table>

![Trello](assets/chapter-5/Sprint-3.png)

Enlace del Sprint 3: https://trello.com/invite/b/6723f3fa38d9a3b46f930233/ATTI49b7970eb0dbb929c08c831aa8e5a1deCEE8E93E/ecomovil-product-backlog-tb2-sprint-3

Link del Trello: https://trello.com/b/Wi4vZd7O/ecomovil-product-backlog-sprint-3

### 5.2.3.3. Development Evidence for Sprint Review

Como evidencia del sprint review, se presenta una tabla que muestra los commits realizados durante este tercer sprint. Dado que se acordó trabajar en los ajustes finales del backend de la aplicación web, se incluyen commits de varios repositorios en los que se realizaron dichas tareas.

| Repository   | Branch                                      | Commit Id | Commit Message                   | User | Commited on (Date) |
| ------------ | ------------------------------------------- | --------- | -------------------------------- | ------------------- | ------------------ |
| Back-End-Ecomovil | main       | fd74c6a         | initial commit       | Beth Oneglio | Sep 19, 2024         | 
| Back-End-Ecomovil | main       | aa5f5cc        | Delete REAME.md | Juan Calisaya | Oct 22, 2024    |
| Back-End-Ecomovil | main       | 841182a         | fchore: initial commit |Juan Calisaya| Oct 30, 2024       |
| Back-End-Ecomovil | main       | dc4a276   | feat(shared): add domain layer for shared bounded context         | Juan Calisaya| Oct 31, 2024                |
| Back-End-Ecomovil | main       | 335568a             |  feat(shared): add domain layer for shared bounded context.                   | Juan Calisaya|  Oct 31, 2024 |
| Back-End-Ecomovil | main       | adc5904              |    feat(shared): add interface layer for shared bounded context.| Juan Calisaya |      Oct 31, 2024 |
| Back-End-Ecomovil | main       | 6a3dd36  |  Merge branch 'master'     | Juan Calisaya |  Oct 31, 2024 |
| Back-End-Ecomovil | feature bounded context forum      | 7d4d26f  |   feat(forum): add forum bounded context  | Beth Oneglio |   Nov 1, 2024|
| Back-End-Ecomovil | feature bounded context forum       | c68621d  |  feat(forum): add forum bounded context  | Beth Oneglio | Nov 1, 2024|
| Back-End-Ecomovil | feature bounded context plans       | 39f6ca1  |  feat: Model| Erick Vasquez | Nov 1, 2024|
| Back-End-Ecomovil | feature bounded context plans       | ad03479  |  feat: Model| Erick Vasquez | Nov 1, 2024|
| Back-End-Ecomovil | feature bounded context plans       | e622c26  |  feat: Patron CQRS | Erick Vasquez | Nov 1, 2024|
| Back-End-Ecomovil | feature bounded context plans       | ea9d328  |  feat:add Controller and Reposiotory | Erick Vasquez | Nov 1, 2024|
| Back-End-Ecomovil | feature bounded context profile      | 6d9042d |   feat: Added profile bounded context and acquirer entity  | Mathias Hidalgo | Nov 1, 2024 |
| Back-End-Ecomovil | feature bounded context profile      | e6313ba |   feat: Added profile bounded context and acquirer entity  | Mathias Hidalgo | Nov 1, 2024 |
| Back-End-Ecomovil | feature bounded context profile      | db4d6a7 |   feat: Added profile bounded context and acquirer entity  | Mathias Hidalgo | Nov 1, 2024 |
| Back-End-Ecomovil | feature bounded context profile      | fe2a576 |   feat: Added profile bounded context and acquirer entity  | Mathias Hidalgo | Nov 1, 2024 |
| Back-End-Ecomovil | feature bounded context profile      | 50ad053 |   feat: Added profile bounded context and acquirer entity  | Mathias Hidalgo | Nov 1, 2024 |
| Back-End-Ecomovil | feature bounded context profile      | 643f56c |   feat: Added profile bounded context and acquirer entity  | Mathias Hidalgo | Nov 1, 2024 |
| Back-End-Ecomovil | feature bounded context profile      | 33692c7 |   feat: Added profile bounded context and acquirer entity  | Mathias Hidalgo | Nov 1, 2024 |
| Back-End-Ecomovil | feature bounded context profile      | bfbe237 |   feat: Added profile bounded context and acquirer entity  | Mathias Hidalgo | Nov 1, 2024 |
| Back-End-Ecomovil | feature bounded context profile      | d79a22f |   feat: Added profile bounded context and acquirer entity  | Mathias Hidalgo | Nov 1, 2024 |
| Back-End-Ecomovil | feature bounded context profile      | 6623725 |   feat: Added profile bounded context and acquirer entity  | Mathias Hidalgo | Nov 1, 2024 |
| Back-End-Ecomovil | feature bounded context profile      | d5f4961 |   feat: fixed acquirer bounded context | David Gallo | Nov 1, 2024 |
| Back-End-Ecomovil | feature bounded context vehicle      | 61c4082  |   feat(domain): add CreateVehicleCommand to handle vehicle creation commands      | Juan Calisaya|  Oct 31, 2024 |
| Back-End-Ecomovil | feature bounded context vehicle       | c8e42d9   |  feat(domain): add Vehicle entity to represent vehicle data in domain  | | Juan Calisaya |  Oct 31, 2024 |
| Back-End-Ecomovil | feature bounded context vehicle       | fbb9fb2 |   feat(application): add VehicleCommandService to process vehicle commands | Juan Calisaya|  Oct 31, 2024 |
| Back-End-Ecomovil | feature bounded context vehicle      | 5cf45ae |feat(interfaces): add VehicleController for REST endpoints | Juan Calisaya|  Oct 31, 2024 |
| Back-End-Ecomovil | feature bounded context vehicle       | a117207 | feat(application): add VehicleQueryService to handle vehicle queries | Juan Calisaya|  Oct 31, 2024 |
| Back-End-Ecomovil | feature bounded context vehicle      | 7da53dc |   feat(infrastructure): add VehicleRepository for database operations  | Juan Calisaya|  Oct 31, 2024 |
| Back-End-Ecomovil | feature bounded context vehicle     | 4ff53a1 |  ffix(vehicle): correct vehicle controller logic | Juan Calisaya|  Oct 31, 2024 |


### 5.2.3.4. Testing Suite Evidence for Sprint Review 
Para la entrega del Sprint 3, nos centramos en alcanzar un desarrollo casi completo. Por ello, la fase de "Testing" se orientó a implementar las necesidades de los usuarios, priorizando secciones que fueran intuitivas y fáciles de comprender.

| Repository                                    | Branch    | Commit Id      | Commit Message                              | Commit Message Body                   | Committed on (Date) |
|-----------------------------------------------|-----------|----------------|---------------------------------------------|---------------------------------------|----------------------|
| https://github.com/Open-Source-SW56-Group-2-EcoMovil/Acceptance-Tests | Epic/Acceptance-Tests/epic-03 | 700b47e7810dc889051eec663b8447fcef58ca98 | feat: add epic 2 and 3 | | 18/11/2024 |

### 5.2.3.5. Execution Evidence for Sprint Review 

En el sprint 3, se logró un avance parcial en el desarrollo del frontend y backend de la aplicación. Este progreso incluye nuevas vistas relevantes sobre el producto y la startup, además de su versión responsive. A continuación, se presentan algunas evidencias.

![page](assets/chapter-5/Capture6.png)

![page](assets/chapter-5/Capture7.png)

![page](assets/chapter-5/Capture8.png)

![page](assets/chapter-5/Capture9.png)

![page](assets/chapter-5/Capture10.png)

![page](assets/chapter-5/Capture11.png)

![page](assets/chapter-5/Capture12.png)

![page](assets/chapter-5/Capture13.png)

![page](assets/chapter-5/Capture14.png)

![page](assets/chapter-5/Capture15.png)

![page](assets/chapter-5/Capture16.png)

![page](assets/chapter-5/Capture17.png)

![bounded-context-profile](/assets/chapter-5/profile-boundedcontext.png)

![bounded-context-plan](/assets/chapter-5/plan-boundedcontext.png)

![bounded-context-vehicle](/assets/chapter-5/vehicle-bounded-context.png)

![bounded-context-post](/assets/chapter-5/post-bounded-context.png)

### 5.2.3.6. Services Documentation Evidence for Sprint Review 

En este Sprint 3, el enfoque principal ha sido la creación del back-end de la aplicación, con todos sus componentes, servicios respectivos.
A continuación se incluiran las imágenes de los endpoints generados durante este sprint.

![bounded-context-profile](/assets/chapter-5/profile-boundedcontext.png)
![bounded-context-plan](/assets/chapter-5/plan-boundedcontext.png)
![bounded-context-vehicle](/assets/chapter-5/vehicle-bounded-context.png)
![bounded-context-post](/assets/chapter-5/post-bounded-context.png)

### 5.2.3.7. Software Deployment Evidence for Sprint Review

Durante el presente sprint hemos logrado desplegar el back-end, usando SQLServer y Azure.

![deployment-evidence](/assets/chapter-5/deployment.png)

Url: https://ecomovil-back3.azurewebsites.net/swagger-ui/index.html#/

### 5.2.3.8. Team Collaboration Insights during Sprint 

En esta sección, presentaremos los hallazgos de nuestro equipo para evaluar los resultados del trabajo realizado y la actividad generada.

| Alumno | Actividad | 
| ------------ | ------------------------------------------- | 
| Calisaya Sánchez, Juan Jesús | Elaborar bounded context Vehicle | 
| Gallo Quintana, David Ivanoff | Elaborar bounded context Profile y despliegue  | 
| Hidalgo Lopez, Mathias Adriano | Elaborar bounded context Profile | 
| Oneglio De Paz, Beth Shantal | Elaborar bounded context Forum | 
| Vasquez Goicochea, Erick Alessander | Elaborar bounded context Plans | 

Repositorio Web-Application-EcoMovil:

![Insights](assets/chapter-5/insight-back.png) 

### 5.2.4. Sprint 4

### 5.2.4.1. Sprint Planning 4

El Sprint #4 comienza el 13/11/2024 y tiene como objetivo completar, integrar y lanzar tanto el Front-end como el Back-end de la aplicación.

<table>
     <tr> 
        <th>  Sprint #  </th>
        <th> Sprint 4 </th>
     </tr>
     <tr> 
        <td style="font-weight: bold;" colspan="3"> Sprint Planning Background</td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Date </td>
       <td>  13/11/2024 </td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Time </td>
       <td> 11:00 A.M. </td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Location </td>
       <td> Modalidad remota a través de Discord <td>
     </tr>
      <tr>
        <td style="font-weight: bold;"> Prepared By </td>
        <td> Oneglio De Paz, Beth Shantal <td>
     </tr>
        <tr>
        <td style="font-weight: bold;"> Attendees (to planning meeting) </td>
        <td> 
            <br>
             Calisaya Sánchez, Juan Jesús
            <br>
             Gallo Quintana, David Ivanoff
            <br>
            Hidalgo Lopez, Mathias Adriano
            <br>
             Oneglio De Paz, Beth Shantal
            <br>
            Vasquez Goicochea, Erick Alessander
        <td>
     </tr>
     <tr>
        <td style="font-weight: bold;"> Sprint 4 Review Summary </td>
        <td> El sprint anterior planteó seguir avanzando en el desarrollo del Front-end de la aplicación y lanzar una versión inicial del Back-end con endpoints operativos. Se ha comprobado que el equipo alcanzó todos los objetivos establecidos. <td>
     </tr>
     <tr>
        <td style="font-weight: bold;"> Sprint 4 Retrospective Summary </td>
        <td> Los story points no fueron completamente apropiados. Aunque la comunicación constante mantuvo al equipo al tanto, las historias de usuario fueron poco claras. Es necesario mejorar la documentación del testing y hacer las historias de usuario más simples para que los desarrolladores las comprendan fácilmente. <td>
     </tr>
     <tr> 
        <td style="font-weight: bold;" colspan="3"> Sprint Goal & User Stories</td>
     </tr>
       <tr>
          <td style="font-weight: bold;"> Sprint 4 Goal</td>
          <td>  Nuestro equipo logró importantes avances durante este sprint: completamos la landing page, finalizamos el i18n en el front end y la adaptación responsive, desarrollamos los endpoints, y terminamos el testing. Los próximos pasos incluyen conectar el front end con el back end y realizar el despliegue final. <td>
      </tr>
       <tr>
          <td style="font-weight: bold;"> Sprint 4 Velocity </td>
          <td>  33  </td>
      </tr>
      <tr>
          <td style="font-weight: bold;"> Sum of Story Points </td>
          <td> 33 <td>
      </tr>
  </table>

### 5.2.4.2. Sprint Backlog 4

En el backlog del cuarto sprint, el equipo finalizó tanto el front end como el back end de la aplicación web. Para organizar y gestionar al equipo se utilizó Trello, que facilitó dividir las historias de usuario en tareas manejables y asignarlas a los distintos miembros según sus habilidades.

![Sprint-4](assets/chapter-5/Sprint_4.png) 

Enlace del Trello: https://trello.com/invite/b/6735240cb8e0131932666410/ATTIfbe9369ef45e8ff47bfdc01816f4e798ABCAD3B0/ecomovil-product-backlog-sprint-4

<table style="width: 100%; border-collapse: collapse; border: 1px solid black;">
   <thead>
      <tr>
         <th style="border: 1px solid black;" colspan="1">Sprint #</th>
         <th style="border: 1px solid black;" colspan="7">Sprint 4</th>
      </tr>
      <tr>
         <th style="border: 1px solid black;" colspan="2">User Story</th>
         <th style="border: 1px solid black;" colspan="6">Work-Item / Task</th>
      </tr>
      <tr>
         <th style="border: 1px solid black;">Id</th>
         <th style="border: 1px solid black;">Title</th>         
         <th style="border: 1px solid black;">Id</th>
         <th style="border: 1px solid black;">Title</th>
         <th style="border: 1px solid black;">Description</th>
         <th style="border: 1px solid black;">Estimation (Hours)</th>
         <th style="border: 1px solid black;">Assigned To</th>
         <th style="border: 1px solid black;">Status (To-do / In-Process / To-Review / Done)</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td rowspan="2" style="border: 1px solid black;">US32</td>
         <td rowspan="2" style="border: 1px solid black;">Implementar una sección de video para "About the Product"</td>
         <td style="border: 1px solid black;">TK28</td>
         <td style="border: 1px solid black;">Crear sección "About Product"</td>
         <td style="border: 1px solid black;">Crear un componente modular en Angular para la sección "About the Product"</td>
         <td style="border: 1px solid black;">4</td>
         <td style="border: 1px solid black;">David Gallo</td>
         <td style="border: 1px solid black;">Done</td>
      </tr>
      <tr>
         <td style="border: 1px solid black;">TK29</td>
         <td style="border: 1px solid black;">Refinar diseño responsivo</td>
         <td style="border: 1px solid black;">Ajustar los estilos CSS del componente para que sea completamente responsivo en diferentes dispositivos</td>
         <td style="border: 1px solid black;">2</td>
         <td style="border: 1px solid black;">David Gallo</td>
         <td style="border: 1px solid black;">Done</td>
      </tr>
      <tr>
         <td rowspan="2" style="border: 1px solid black;">US31</td>
         <td rowspan="2" style="border: 1px solid black;">Implementar una sección de video para "About the Team"</td>
         <td style="border: 1px solid black;">TK30</td>
         <td style="border: 1px solid black;">Crear sección "About the Team"</td>
         <td style="border: 1px solid black;">Crear un componente modular en Angular para la sección "About the Team"</td>
         <td style="border: 1px solid black;">4</td>
         <td style="border: 1px solid black;">Beth Oneglio</td>
         <td style="border: 1px solid black;">Done</td>
      </tr>
      <tr>
         <td style="border: 1px solid black;">TK31</td>
         <td style="border: 1px solid black;">Refinar diseño responsivo</td>
         <td style="border: 1px solid black;">Ajustar los estilos CSS del componente para que sea completamente responsivo en diferentes dispositivos</td>
         <td style="border: 1px solid black;">2</td>
         <td style="border: 1px solid black;">Beth Oneglio</td>
         <td style="border: 1px solid black;">Done</td>
      </tr>
      <tr>
         <td rowspan="2" style="border: 1px solid black;">US30</td>
         <td rowspan="2" style="border: 1px solid black;">Implementar la internacionalización de la Aplicación</td>
         <td style="border: 1px solid black;">TK32</td>
         <td style="border: 1px solid black;">Configuración e integración del selector de idioma</td>
         <td style="border: 1px solid black;">Implementar la configuración de internacionalización usando @ngx-translate/core. Integrar el componente de selección de idioma y conectar la lógica para cambiar y persistir dinámicamente el idioma.</td>
         <td style="border: 1px solid black;">2</td>
         <td style="border: 1px solid black;">Juan Calisaya</td>
         <td style="border: 1px solid black;">Done</td>
      </tr>
      <tr>
         <td style="border: 1px solid black;">TK33</td>
         <td style="border: 1px solid black;">Implementar traducciones en toda la aplicación</td>
         <td style="border: 1px solid black;">Reemplaza los textos estáticos de la aplicación con claves de traducción de los archivos JSON, asegurando que todas las páginas y componentes reflejen el idioma seleccionado.</td>
         <td style="border: 1px solid black;">7</td>
         <td style="border: 1px solid black;">Mathias Hidalgo</td>
         <td style="border: 1px solid black;">Done</td>
      </tr>
      <tr>
         <td rowspan="3" style="border: 1px solid black;">US26</td>
         <td rowspan="3" style="border: 1px solid black;">Buscar vehículos (API)</td>
         <td style="border: 1px solid black;">TK34</td>
         <td style="border: 1px solid black;">Implementar lógica de búsqueda y filtrado en el servicio</td>
         <td style="border: 1px solid black;">Diseña y ajusta la entidad Vehicle con atributos como tipo, precio, ubicación y disponibilidad. Configura el repositorio con métodos personalizados para búsquedas avanzadas usando Spring Data JPA.</td>
         <td style="border: 1px solid black;">6</td>
         <td style="border: 1px solid black;">David Gallo</td>
         <td style="border: 1px solid black;">Done</td>
      </tr>
      <tr>
         <td style="border: 1px solid black;">TK35</td>
         <td style="border: 1px solid black;">Crear endpoints RESTful para buscar vehículos</td>
         <td style="border: 1px solid black;">Implementa controladores RESTful con endpoints para buscar y filtrar vehículos, incluyendo parámetros de consulta (tipo, precioMin, precioMax, ubicación) y valida las entradas de los usuarios.</td>
         <td style="border: 1px solid black;">5</td>
         <td style="border: 1px solid black;">David Gallo</td>
         <td style="border: 1px solid black;">Done</td>
      </tr>
      <tr>
         <td style="border: 1px solid black;">TK36</td>
         <td style="border: 1px solid black;">Implementar pruebas unitarias y de integración</td>
         <td style="border: 1px solid black;">Crea pruebas unitarias para el servicio y pruebas de integración para los endpoints. Simula escenarios con datos de ejemplo y valida que los resultados sean precisos para las combinaciones de filtros aplicados.</td>
         <td style="border: 1px solid black;">8</td>
         <td style="border: 1px solid black;">Juan Calisaya</td>
         <td style="border: 1px solid black;">Done</td>
      </tr>
      <tr>
         <td rowspan="3" style="border: 1px solid black;">US16</td>
         <td rowspan="3" style="border: 1px solid black;">Crear una cuenta en EcoMovil</td>
         <td style="border: 1px solid black;">TK37</td>
         <td style="border: 1px solid black;">Implementar el agregado User en la Domain Layer</td>
         <td style="border: 1px solid black;">Crear el agregado User con atributos como id, nombre, email, password (encriptado) y role. Implementar lógica de negocio, como validaciones de datos y reglas para crear nuevos usuarios.</td>
         <td style="border: 1px solid black;">5</td>
         <td style="border: 1px solid black;">David Gallo</td>
         <td style="border: 1px solid black;">Done</td>
      </tr>
      <tr>
         <td style="border: 1px solid black;">TK38</td>
         <td style="border: 1px solid black;">Crear el servicio de registro en la Application Layer</td>
         <td style="border: 1px solid black;">Implementar un servicio en la capa de aplicación para manejar la lógica del registro de usuarios, incluyendo validaciones y uso del repositorio para persistencia.</td>
         <td style="border: 1px solid black;">5</td>
         <td style="border: 1px solid black;">David Gallo</td>
         <td style="border: 1px solid black;">Done</td>
      </tr>
      <tr>
         <td style="border: 1px solid black;">TK39</td>
         <td style="border: 1px solid black;">Crear el endpoint de registro en la Interfaces Layer</td>
         <td style="border: 1px solid black;">Exponer un endpoint RESTful para que los usuarios puedan registrarse enviando su nombre, email y contraseña. Manejar errores como email duplicado o entradas inválidas.</td>
         <td style="border: 1px solid black;">4</td>
         <td style="border: 1px solid black;">David Gallo</td>
         <td style="border: 1px solid black;">Done</td>
      </tr>
      <tr>
         <td rowspan="3" style="border: 1px solid black;">US17</td>
         <td rowspan="3" style="border: 1px solid black;">Inicio de sesión en EcoMovil</td>
         <td style="border: 1px solid black;">TK40</td>
         <td style="border: 1px solid black;">Crear el servicio de autenticación en la Application Layer</td>
         <td style="border: 1px solid black;">Implementar un servicio que valide las credenciales del usuario contra los datos almacenados. Generar un token JWT para los usuarios autenticados.</td>
         <td style="border: 1px solid black;">5</td>
         <td style="border: 1px solid black;">David Gallo</td>
         <td style="border: 1px solid black;">Done</td>
      </tr>
      <tr>
         <td style="border: 1px solid black;">TK41</td>
         <td style="border: 1px solid black;">Crear el endpoint de inicio de sesión en la Interfaces Layer</td>
         <td style="border: 1px solid black;">Exponer un endpoint RESTful para que los usuarios inicien sesión enviando su email y contraseña. Manejar respuestas para credenciales inválidas o usuarios no registrados.</td>
         <td style="border: 1px solid black;">5</td>
         <td style="border: 1px solid black;">David Gallo</td>
         <td style="border: 1px solid black;">Done</td>
      </tr>
      <tr>
         <td style="border: 1px solid black;">TK42</td>
         <td style="border: 1px solid black;">Crear pruebas unitarias y de integración para autenticación</td>
         <td style="border: 1px solid black;">Implementar pruebas unitarias para los servicios de autenticación y pruebas de integración para los endpoints de inicio de sesión y acceso a rutas protegidas.</td>
         <td style="border: 1px solid black;">8</td>
         <td style="border: 1px solid black;">Beth Oneglio</td>
         <td style="border: 1px solid black;">Done</td>
      </tr>
   </tbody>
</table>

5.2.4.3. Development Evidence for Sprint Review

Como evidencia del Sprint Review, se muestra una tabla de commits realizados en este tercer sprint, abarcando los repositorios de frontend y backend de la aplicación web.

| Repository   | Branch                                      | Commit Id | Commit Message                   | User | Commited on (Date) |
| ------------ | ------------------------------------------- | --------- | -------------------------------- | ------------------- | ------------------ |
| Front-End-Ecomovil | feature/i18n-internationalization       | 432c543         | feat: add i18n-internationalization       | Juan Calisaya | Nov 14, 2024         | 
| Front-End-Ecomovil | feature/i18n-internationalization       | d962d1f         | feat: add i18n-internationalization | Juan Calisaya | Nov 14, 2024    |
| Front-End-Ecomovil | feature/i18n-internationalization       | fb74fc1         | feat: updated package.json | Juan Calisaya | Nov 14, 2024       |
| Front-End-Ecomovil | feature/i18n-internationalization       | 64c41c0   | chore: configure providers for http client and translate service.  | Juan Calisaya | Nov 14, 2024   |
| Front-End-Ecomovil | feature/i18n-internationalization       | 389ac85             |  feat(fake-api): setup fake api configuration.                   | Juan Calisaya |  Nov 14, 2024 |
| Front-End-Ecomovil | feature/i18n-internationalization       | 8b29671              |    feat: updated i18n          | Juan Calisaya |      Nov 15, 2024 |
| Front-End-Ecomovil | feature/i18n-internationalization       | af1fb28  |  feat: updated i18n-internationalization     | Juan Calisaya |  Nov 16, 2024 |
| Front-End-Ecomovil | develop       | 432c543         | feat: add i18n-internationalization       | Juan Calisaya | Nov 14, 2024         | 
| Front-End-Ecomovil | develop       | d962d1f         | feat: add i18n-internationalization | Juan Calisaya | Nov 14, 2024    |
| Front-End-Ecomovil | develop       | fb74fc1         | feat: updated package.json | Juan Calisaya | Nov 14, 2024       |
| Front-End-Ecomovil | develop       | 64c41c0   | chore: configure providers for http client and translate service.  | Juan Calisaya | Nov 14, 2024                |
| Front-End-Ecomovil | develop       | 389ac85             |  feat(fake-api): setup fake api configuration.                   | Juan Calisaya |  Nov 14, 2024 |
| Front-End-Ecomovil | develop       | 8b29671              |    feat: updated i18n          | Juan Calisaya |      Nov 15, 2024 |
| Front-End-Ecomovil | develop       | af1fb28  |  feat: updated i18n-internationalization     | Juan Calisaya |  Nov 16, 2024 |
| Back-End-Ecomovil | develop       | 3b9b52b  |   feat: added information for deployment  | David Gallo |    Nov 13, 2024 |
| Back-End-Ecomovil | develop       | 10b6576  |  feat: added vehicles  | David Gallo |  Nov 13, 2024 |
| Back-End-Ecomovil | develop       | 080bc99  |  feat: add vehicle| David Gallo |  Nov 13, 2024 |
| Back-End-Ecomovil | develop       | 4b931fe  |  feat: added type, name, year   | David Gallo |  Nov 13, 2024 |
| Back-End-Ecomovil | develop       | cf207f2  |     feat: added price | David Gallo |  Nov 13, 2024 |
| Back-End-Ecomovil | develop       | aac51e0  |        feat: finished vehicles  | David Gallo |   Nov 13, 2024 |
| Back-End-Ecomovil | develop       | ce45beb  |   feat: fixed endpoints   | David Gallo |  Nov 13, 2024 |
| Back-End-Ecomovil | develop       | c770a5d  |   feat: plan2       | David Gallo |  Nov 13, 2024 |
| Back-End-Ecomovil | develop       | c16cb7e  |     feat: added iam without swagger token config         | David Gallo |  Nov 14, 2024 |
| Back-End-Ecomovil | develop       | 8a4774c  |   feat: deleted iam      | David Gallo | Nov 14, 2024  |
| Back-End-Ecomovil | develop       | 416416f  |     feat: added iam | David Gallo |    Nov 14, 2024 |
| Back-End-Ecomovil | develop       | e2788d0  |  feat: added facade for Plan  | David Gallo |Nov 15, 2024|
| Back-End-Ecomovil | develop       | 631e20f  |   feat: added getAllStudentsByPlanId      | David Gallo | Nov 15, 20244 |
| Back-End-Ecomovil | develop       | aedaa88  |  feat: added student facade to connect with vehicle      | David Gallo |   Nov 15, 2024 |
| Back-End-Ecomovil | develop       | 9c7a41b  | feat: added reservations        | David Gallo |   Nov 15, 2024  |
| Back-End-Ecomovil | develop       | 6c1c30d  |   feat: added reservations conection with vehicles     | David Gallo | Nov 15, 2024         | 
| Back-End-Ecomovil | develop       | 186a5e5  | feat: added ExternalProfileService to forum bounded context | David Gallo | Nov 15, 2024    |
| Back-End-Ecomovil | develop       | 7d10993  | feat: added update reservation | David Gallo | Nov 15, 2024       |
| Back-End-Ecomovil | develop       | 5ee3027  |  feat: added update to plan   | David Gallo |    Nov 16, 2024  |
| Back-End-Ecomovil | develop       | 492a1a1  |  test(auth): add unit tests for JWT-based login functionality     | Beth Oneglio |    Nov 16, 2024  |
| Back-End-Ecomovil | develop       | 52f9ef   |  test(auth): add unit tests for JWT-based login functionality       | Beth Oneglio |    Nov 16, 2024  |

5.2.4.4. Testing Suite Evidence for Sprint Review

Para la entrega del Sprint 4, nos centramos en alcanzar un desarrollo completo. Por ello, la fase de "Testing" se orientó a implementar las necesidades de los usuarios, priorizando secciones que fueran intuitivas y fáciles de comprender.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
| https://github.com/Open-Source-SW56-Group-2-EcoMovil/Back-End-EcoMovil | "develop" | test(auth) | test(auth): add unit tests for JWT-based login functionality | 16/11/2024 |                     |

![](assets/chapter-5/Testing_1.jpg) 

![](assets/chapter-5/Testing_2.jpg) 

5.2.4.5. Execution Evidence for Sprint Review

En el Sprint 4, se completó el desarrollo tanto del frontend como del backend de la aplicación web, incluyendo su versión responsiva, en español e inglés. A continuación, se presentan algunas evidencias.

- US24:

![US24](assets/chapter-5/US_24.jpg) 

- US28:

![US28](assets/chapter-5/US_28.jpg) 

![](assets/chapter-5/Backend_1.jpg) 

![](assets/chapter-5/Backend_2.jpg) 

![](assets/chapter-5/Backend_3.jpg) 

![](assets/chapter-5/Backend_4.jpg) 

Enlace para ver el video que explica los logros alcanzados en el Sprint: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213423_upc_edu_pe/EWRFicbfLOBCmMH02n9CBJEBKMKGdXdYpHIIOLWwqFlFPg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=n50lwC 

5.2.4.6. Services Documentation Evidence for Sprint Review

Para el Sprint 4, se planificó desarrollar únicamente el front-end y back-end. Inicialmente, se utilizó un servidor JSON local. El back-end fue creado y está vinculado al front-end para realizar consultas y obtener datos.

- Web Service:

- Universitario:
  
| **Endpoint**      | **Operaciones**    | **Parametros**  | **URL**  |
|-------------------|-------------------|------------------|-----------|
| **Profile**       | GET               | {id}           | api/v1/profiles/{id}    |
|                   | POST              | No tiene.      | api/v1/profiles    |
|                   | PUT               | {id}           | api/v1/profiles/{id}    |
| **Reservation**   | GET               | No tiene.      | api/v1/reservations   |
|                   | GET               | {ProfileId}    | api/v1/reservations/{ProfileId}    |
|                   | POST              | No tiene.      | api/v1/reservations    |
|                   | PUT               | {id}           | api/v1/reservations?ProfileId={id}    |
|                   | DELETE            | {id}           | api/v1/reservations/{id}    |
| **Posts**         | GET               | No tiene.      | api/v1/posts    |
|                   | GET               | {name}         | api/v1/posts/{name}    |
|                   | POST              | No tiene.      | api/v1/posts    |
|                   | PUT               | {id}           | api/v1/posts/{id}   |
|                   | DELETE            | {id}           | api/v1/posts/{id}   |
               
- Adquiriente:

| **Endpoint**      | **Operaciones**    | **Parametros**  | **URL**  |
|-------------------|-------------------|------------------|-----------|
| **Vehicles**       | GET               | No tiene.      | api/v1/vehicles                           |
|                    | GET               | {id}           | api/v1/vehicles/{id}                           |
|                    | POST              | No tiene.      | api/v1/vehicles                           |
|                    | PUT               | {id}           | api/v1/vehicles/{id}                           |
|                    | DELETE            | {id}           | api/v1/vehicles/{id}                           |
| **Profile**        | GET               | {id}           | api/v1/profiles/{id}                           |
|                    | POST              | No tiene.      | api/v1/profiles                           |
|                    | PUT               | {id}           | api/v1/profiles/{id}                           |
| **Reservation**    | GET               | No tiene.      | api/v1/reservations                           |
|                    | GET               | {ProfileId}    | api/v1/reservations/{ProfileId}                           |
|                    | POST              | No tiene.      | api/v1/reservations                           |
|                    | PUT               | {id}           | api/v1/reservations?ProfileId={id}                           |
|                    | DELETE            | {id}           | api/v1/reservations/{id}                           |
| **Posts**          | GET               | No tiene.      | api/v1/posts                           |
|                    | GET               | {word}         | api/v1/posts/{word}                           |
|                    | POST              | No tiene.      | api/v1/posts                           |
|                    | PUT               | {id}           | api/v1/posts/{id}                           |
|                    | DELETE            | {id}           | api/v1/posts/{id}                    |

- Web Service Images:

![](assets/chapter-5/Backend_1.jpg) 

![](assets/chapter-5/Backend_2.jpg) 

![](assets/chapter-5/Backend_3.jpg) 

![](assets/chapter-5/Backend_4.jpg) 

Enlace del repositorio: https://github.com/Open-Source-SW56-Group-2-EcoMovil/Front-End-EcoMovil

- Web Service Commit Details:

| Repository   | Branch                                      | Commit Id | Commit Message                   | User | Commited Message Body | Commited on (Date) |
| ------------ | ------------------------------------------- | --------- | -------------------------------- | ------------------- | ------------------- | ------------------ |
| Back-End-Ecomovil | main       | fd74c6a         | Initial commit       | Beth Oneglio |    | Sep 19, 2024         | 
| Back-End-Ecomovil | main       | aa5f5cc         | Delete README.md | Juan Calisaya |     | Oct 22, 2024    |
| Back-End-Ecomovil | main       | 841182a         | chore: initial commit | Juan Calisaya |    | Oct 30, 2024      |
| Back-End-Ecomovil | main       | dc4a276   | feat(shared): add infrastructure layer for shared bounded context.  | Juan Calisaya |    | Oct 31, 2024   |
| Back-End-Ecomovil | main       | 335568a             |  feat(shared): add domain layer for shared bounded context.              | Juan Calisaya |    |  Oct 31, 2024 |
| Back-End-Ecomovil | main       | adc5904              |    feat(shared): add interface layer for shared bounded context.          | Juan Calisaya |     |     Oct 31, 2024 |
| Back-End-Ecomovil | main       | 6a3dd36  |  Merge branch 'master'     | Juan Calisaya |     | Oct 31, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-forum       | 7d4d26f      | feat(forum): add forum bounded context.       | Beth Oneglio |    |  Nov 1, 2024         | 
| Back-End-Ecomovil | feacture/bounded-context-forum       | c68621d       | feat(forum): add forum bounded context.  | Beth Oneglio |     | Nov 1, 2024    |
| Back-End-Ecomovil | feacture/bounded-context-plans       | 39f6ca1       | feat: Model | Erick Vasquez |    |  Nov 1, 2024       |
| Back-End-Ecomovil | feacture/bounded-context-plans       | ad03479       | feat: Model   | Erick Vasqueza |    |  Nov 1, 2024                |
| Back-End-Ecomovil | feacture/bounded-context-plans       | e622c26        |  feat: Patron CQRS       | Erick Vasquez |    |   Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-plans       | ea9d328       |    feat:add Controller and Reposiotory       | Erick Vasquez |     |    Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-vehicle     | 61c4082  | feat(domain): add CreateVehicleCommand to handle vehicle creation commands | Juan Calisaya |     |  Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-vehicle     | c8e42d9  | feat(domain): add Vehicle entity to represent vehicle data in domain     | Juan Calisaya |     |  Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-vehicle     | fbb9fb2  | feat(application): add VehicleCommandService to process vehicle commands     | Juan Calisaya |     |  Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-vehicle     | 5cf45ae  | feat(interfaces): add VehicleController for REST endpoints     | Juan Calisaya |     |  Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-vehicle     | a117207  | feat(application): add VehicleQueryService to handle vehicle queries     | Juan Calisaya |     |  Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-vehicle     | 7da53dc  | feat(infrastructure): add VehicleRepository for database operations     | Juan Calisaya |     |  Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-vehicle     | 4ff53a1  | fix(vehicle): correct vehicle controller logic     | Juan Calisaya |     |  Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-profile     | cf54f3a  | feat: Added profile bounded context and student entity      | David Gallo |     | Oct 31, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-profile     | 6d9042d  | feat: Added profile bounded context and acquirer entity     | Mathias Hidalgo |     | Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-profile     | e6313ba  | feat: Added profile bounded context and acquirer entity     | Mathias Hidalgo |     | Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-profile     | db4d6a7  | feat: Added profile bounded context and acquirer entity     | Mathias Hidalgo |     | Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-profile     | fe2a576  | feat: Added profile bounded context and acquirer entity     | Mathias Hidalgo |     | Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-profile     | 50ad053  | feat: Added profile bounded context and acquirer entity     | Mathias Hidalgo |     | Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-profile     | 643f56c  | feat: Added profile bounded context and acquirer entity     | Mathias Hidalgo |     | Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-profile     | 33692c7  | feat: Added profile bounded context and acquirer entity     | Mathias Hidalgo |     | Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-profile     | bfbe237  | feat: Added profile bounded context and acquirer entity     | Mathias Hidalgo |     | Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-profile     | d79a22f  | feat: Added profile bounded context and acquirer entity     | Mathias Hidalgo |     | Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-profile     | 6623725  | feat: Added profile bounded context and acquirer entity     | Mathias Hidalgo |     | Nov 1, 2024 |
| Back-End-Ecomovil | feacture/bounded-context-profile     | d5f4961  | feat: fixed acquirer bounded context     | David Gallo |     | Nov 1, 2024 |
| Back-End-Ecomovil | develop       | 3b9b52b  |   feat: added information for deployment  | David Gallo |     |   Nov 13, 2024 |
| Back-End-Ecomovil | develop       | 10b6576  |  feat: added vehicles  | David Gallo |     | Nov 13, 2024 |
| Back-End-Ecomovil | develop       | 080bc99  |  feat: add vehicle| David Gallo |     | Nov 13, 2024 |
| Back-End-Ecomovil | develop       | 4b931fe  |  feat: added type, name, year   | David Gallo |    |  Nov 13, 2024 |
| Back-End-Ecomovil | develop       | cf207f2  |     feat: added price | David Gallo |     | Nov 13, 2024 |
| Back-End-Ecomovil | develop       | aac51e0  |        feat: finished vehicles  | David Gallo |    |   Nov 13, 2024 |
| Back-End-Ecomovil | develop       | ce45beb  |   feat: fixed endpoints   | David Gallo |     | Nov 13, 2024 |
| Back-End-Ecomovil | develop       | c770a5d  |   feat: plan2       | David Gallo |     | Nov 13, 2024 |
| Back-End-Ecomovil | develop       | c16cb7e  |     feat: added iam without swagger token config         | David Gallo |     | Nov 14, 2024 |
| Back-End-Ecomovil | develop       | 8a4774c  |   feat: deleted iam      | David Gallo |     | Nov 14, 2024  |
| Back-End-Ecomovil | develop       | 416416f  |     feat: added iam | David Gallo |      |  Nov 14, 2024 |
| Back-End-Ecomovil | develop       | e2788d0  |  feat: added facade for Plan  | David Gallo |     | Nov 15, 2024|
| Back-End-Ecomovil | develop       | 631e20f  |   feat: added getAllStudentsByPlanId      | David Gallo |     | Nov 15, 20244 |
| Back-End-Ecomovil | develop       | aedaa88  |  feat: added student facade to connect with vehicle      | David Gallo |     |  Nov 15, 2024 |
| Back-End-Ecomovil | develop       | 9c7a41b  | feat: added reservations        | David Gallo |     |  Nov 15, 2024  |
| Back-End-Ecomovil | develop       | 6c1c30d  |   feat: added reservations conection with vehicles     | David Gallo |     | Nov 15, 2024         | 
| Back-End-Ecomovil | develop       | 186a5e5  | feat: added ExternalProfileService to forum bounded context | David Gallo |     | Nov 15, 2024    |
| Back-End-Ecomovil | develop       | 7d10993  | feat: added update reservation | David Gallo |     | Nov 15, 2024       |
| Back-End-Ecomovil | develop       | 5ee3027  |  feat: added update to plan   | David Gallo |     |    Nov 16, 2024  |
| Back-End-Ecomovil | develop       | 492a1a1  |  test(auth): add unit tests for JWT-based login functionality     | Beth Oneglio |      |  Nov 16, 2024  |
| Back-End-Ecomovil | develop       | 52f9ef   |  test(auth): add unit tests for JWT-based login functionality       | Beth Oneglio |      |  Nov 16, 2024  |

5.2.4.7. Software Deployment Evidence for Sprint Review

En la entrega del cuarto sprint, se completó y desplegó el landing page funcional, cumpliendo con las user stories establecidas. Además, se desplegaron tanto la aplicación web como el back-end en su totalidad.

- Capturas de la pantalla Landing Page:

![](assets/chapter-5/Landing_1.jpg) 

![](assets/chapter-5/Landing_2.jpg) 

![](assets/chapter-5/Landing_3.jpg) 

![](assets/chapter-5/Landing_4.jpg) 

 - Web Application Front-end:

Enlace del Front-end: https://happy-tree-09edbd910.5.azurestaticapps.net/login

![](assets/chapter-5/Imagen_1.jpg) 

![](assets/chapter-5/Imagen_2.jpg) 

![](assets/chapter-5/Imagen_3.jpg) 

![](assets/chapter-5/Imagen_4.jpg) 

![](assets/chapter-5/Imagen_5.jpg) 

![](assets/chapter-5/Imagen_6.jpg) 

![](assets/chapter-5/Imagen_7.jpg) 

![](assets/chapter-5/Imagen_8.jpg) 

![](assets/chapter-5/Imagen_9.jpg) 

![](assets/chapter-5/Imagen_10.jpg) 

![](assets/chapter-5/Imagen_11.jpg) 

![](assets/chapter-5/Imagen_12.jpg) 

![](assets/chapter-5/Imagen_13.jpg) 

- Web Services Back-end:

Ultimo despliegue del Web Service: 

Enlace del Back-end: https://back-end-ecomovil-deploy-production.up.railway.app/swagger-ui/index.html#/

- Capturas de pantalla del Web Application:

![](assets/chapter-5/Backend_1.jpg) 

![](assets/chapter-5/Backend_2.jpg) 

![](assets/chapter-5/Backend_3.jpg) 

![](assets/chapter-5/Backend_4.jpg) 

5.2.4.8. Team Collaboration Insights during Sprint

En esta sección, presentaremos los hallazgos de nuestro equipo para evaluar los resultados del trabajo realizado y la actividad generada.

| Alumno | Actividad | 
| ------------ | ------------------------------------------- | 
| Calisaya Sánchez, Juan Jesús | Elaborar el testing | 
| Gallo Quintana, David Ivanoff | Elaborar el despliegue del Back-end  | 
| Hidalgo Lopez, Mathias Adriano | Implementar el i18n y el responsive en el Front-end | 
| Oneglio De Paz, Beth Shantal | Elaborar el testing y el informe | 
| Vasquez Goicochea, Erick Alessander | Implementar la conexión del Front-end y Back-end | 

Repositorio Web-Application-EcoMovil:

-Repositorio Landing:

![](assets/chapter-5/Landing_1.png) 

-Repositorio Back-end:

![](assets/chapter-5/Frontend_Person.png) 

## 5.3. Validation Interviews 

En la sección "Validation Interviews" de nuestro proyecto, el propósito es mejorar la aplicación mediante una interacción directa con nuestros usuarios principales: universitarios y adquirientes. Mediante entrevistas estructuradas, buscamos recopilar sus opiniones y sugerencias, garantizando así que la aplicación no solo cumpla con los estándares técnicos, sino que también se ajuste a las necesidades operativas y expectativas de los usuarios. A continuación, se describen los objetivos de usuario necesarios para llevar a cabo estas entrevistas.

### 5.3.1. Diseño de Entrevistas 

### Segmento Universitario

#### Preguntas Generales

- ¿Cuál es tu nombre?
- ¿Cuántos años tienes?
- ¿Dónde resides actualmente?
- ¿A qué te dedicas?

#### Preguntas para el Segmento de Propietarios

- ¿Crees que alguna función o característica necesita mejoras? ¿Qué elementos podrían optimizarse para ofrecer una mejor experiencia?
-  ¿Cómo percibes el diseño y funcionalidad de las herramientas de gestión de planes? ¿Te parecieron intuitivas y sencillas de usar?
- ¿Cómo evalúas la opción de publicar y editar tus vehículos en la plataforma? ¿Qué tan fácil o complicado te resultó?
- ¿Te gustó la experiencia de editar tu perfil y personalizarlo? ¿Consideras útiles las opciones de personalización?
- ¿Qué te pareció la facilidad para administrar tu historial de vehículos (alquileres o ventas)? ¿Crees que esta herramienta cumple tus expectativas?
- ¿La interfaz de usuario para actualizar y gestionar tus datos personales te resultó cómoda y funcional?

### Segmento Adquiriente

#### Preguntas Generales

- ¿Cuál es tu nombre?
- ¿Cuántos años tienes?
- ¿Dónde resides actualmente?
- ¿A qué te dedicas?

#### Preguntas para el Segmento de Adquirientes

- ¿Considerarías utilizar nuestra aplicación? ¿Por qué?
- ¿Qué opinas de la calidad de los vehículos y la legibilidad de la tipografía al ver la ubicación en la sección de mapa? ¿Te resultó fácil de usar o crees que se necesitan ajustes?
- ¿Piensas que la aplicación ofrece una buena variedad de vehículos detallados?
- ¿Qué te pareció la experiencia de navegación al buscar vehículos? ¿Fue fácil encontrar lo que buscabas?
- ¿Consideras que la información de los vehículos es clara y suficiente para tomar una decisión de compra o alquiler?
- ¿Qué opinas sobre las opciones de personalización de la búsqueda (por tipo de vehículo, precio)? ¿Te parecieron adecuadas?
- ¿Qué te pareció la opción de gamificación en la aplicación? ¿Consideras que incentiva el uso de la aplicación?
- ¿Crees que la aplicación cumple con tus expectativas en cuanto a la variedad y disponibilidad de vehículos sostenibles?

---

### User Goals

**User Goal:** Iniciar sesión

**User Persona:** Universitarios y Adquirientes  

**Explicación del flujo:**  
Primero, el usuario accede a la aplicación desplegada y visualiza el formulario de inicio de sesión. Aquí, ingresa su correo electrónico y contraseña, ya sea como universitario o adquiriente. Si las credenciales son correctas, el sistema valida la información y redirige al usuario a su dashboard personal.

**User Goal:** Navegar por el dashboard  

**User Persona:** Adquiriente  

**Explicación del flujo:**  
Una vez que el usuario ha iniciado sesión, es redirigido a la sección “Home”, donde puede ver una lista de publicaciones de universitarios que ofrecen vehículos en venta o renta.

**User Goal:** Encontrar vehículos menores para comprar o rentar  

**User Persona:** Adquiriente  

**Explicación del flujo:**  
Al iniciar sesión, el usuario puede acceder a la sección “Map” para visualizar un mapa con los vehículos disponibles cerca de su ubicación.

**User Goal:** Filtro de búsqueda  

**User Persona:** Adquiriente  

**Explicación del flujo:**  
El usuario puede ver los filtros de búsqueda para vehículos, ajustando criterios como el tipo y el precio (ordenados de menor a mayor). Al seleccionar una opción, se despliegan los vehículos que cumplen con los filtros aplicados.

**User Goal:** Ver detalles del vehículo  

**User Persona:** Adquiriente  

**Explicación del flujo:**  
El usuario puede seleccionar un vehículo para ver sus detalles específicos. Además, tiene la opción de iniciar un chat por WhatsApp con el propietario al hacer clic en el enlace, lo que abre WhatsApp para ponerse en contacto.

**User Goal:** Mi Perfil  

**User Persona:** Universitario y Adquiriente  

**Explicación del flujo:**  
Una vez iniciada la sesión, el usuario puede ingresar a la sección “My Profile” para ver la información de su perfil.

**User Goal:** Editar Perfil  
**User Persona:** Universitario y Adquiriente  
**Explicación del flujo:**  
En la sección “My Profile”, el usuario puede hacer clic en “Editar perfil” para acceder a una página donde puede modificar su información personal y su foto.

**User Goal:** Ver mis Planes  

**User Persona:** Universitario  

**Explicación del flujo:**  
Al iniciar sesión, el usuario es redirigido a la sección de planes, donde puede elegir entre tres opciones disponibles. Al seleccionar un plan, es redirigido a PayPal para registrar su tarjeta y completar el pago.

**User Goal:** Ver mis vehículos  

**User Persona:** Universitario  

**Explicación del flujo:**  
Tras pagar uno de los planes, el usuario puede ver los vehículos que otros universitarios han publicado. Debajo de esta lista, puede hacer clic en “Add +” para subir sus propios vehículos con la información correspondiente.

### 5.3.2. Registro de Entrevistas 

**Entrevista a Universitarios.**

Entrevista de validaciones usuarios Universitarios.

| **Entrevista 1**        | **Abel Andrés Valle Zuta**         | 
|:-------------------:|:-------------------:|
| <center>Edad</center>  | <center>19 Años</center>  |
| <center>Distrito</center>  | <center>Miraflores</center>  | 
| <center>![Andres_Valle](assets/chapter-5/validation_valle.png)</center>  | <center>Abel Valle considera que la aplicación cumple con los requisitos sin necesidad de mejoras o funciones adicionales. En la sección de visualización de vehículos, aprecia ver los vehículos claramente y encuentra el diseño intuitivo, sin necesidad de guías para orientarse en los pasos. Sugiere agregar detalles sobre el propietario de cada vehículo publicado. Le agrada la disposición distribuida de los vehículos y percibe la interfaz como funcional y visualmente atractiva.</center>  | 
| <center>Timing: 0:05 </center>  | <center>URL: https://acortar.link/UZ35w3 </center>  | 
| **Entrevista 2**        | **Rodrigo André García Yauri**         | 
| <center>Edad</center>  | <center>21 Años</center>  |
| <center>Distrito</center>  | <center>Molina</center>  | 
| <center>![Rodrigo_Garcia](assets/chapter-5/validation_garcia.png)</center>  | <center>Rodrigo García ha explorado la aplicación y la encuentra completa en general. Le gustaría que el sistema de rastreo fuera más eficiente. Considera que la aplicación es muy intuitiva y aprecia los detalles de cada vehículo, lo que le brinda una experiencia más personalizada y distintiva en comparación con otras aplicaciones similares. Para él, esta personalización es clave para visualizar los vehículos publicados. También le agradó la interfaz de la aplicación.</center>  | 
| <center>Timing: 4:19 </center>  | <center>URL: https://acortar.link/UZ35w3</center>  | 
| **Entrevista 3**        | **Brissa Arakemi Hoyos Arevalo**         | 
| <center>Edad</center>  | <center>19 Años</center>  |
| <center>Distrito</center>  | <center>Rímac</center>  | 
| <center>![Brissa_Hoyos](assets/chapter-5/validation_hoyos.png)</center>  | <center>A Brissa Hoyos le gustó la página y considera que tiene una estructura muy organizada. Destaca la eficiencia y lo completa que es, ya que facilita encontrar cada sección. Le gustaría añadir una función de comunicación directa con el cliente y no eliminaría ningún elemento de la aplicación.</center>  | 
| <center>Timing: 8:02 </center>  | <center>URL: https://acortar.link/UZ35w3 </center>  | 
 
**Entrevista a Adquirientes.**

Entrevista de validaciones usuarios Adquirientes.

| **Entrevista 1** | **Camila de Jesus Perez Novoa** | 
|:---------------:|:-------------------------------:|
| <center>Edad</center> | <center>22 Años</center> |
| <center>Distrito</center> | <center>Barcelona</center> |
| <center>![Camila_Perez](assets/chapter-5/validation_perez.png)</center> | <center>Camila Pérez opina que la calidad de los vehículos y la tipografía son adecuadas, siendo comprensibles y bien presentadas. Encuentra que la aplicación es fácil de usar y valora la variedad de vehículos disponibles. Considera que la información sobre el alquiler o la venta es clara, pero le gustaría que se incluyeran comentarios, sugiriendo un apartado de reseñas para guiar a los usuarios.</center> |
| <center>Timing: 12:48 </center> | <center>URL: https://acortar.link/UZ35w3</center> |
| **Entrevista 2** | **Paola Andrea Vasquez Goicochea** | 
| <center>Edad</center> | <center>27 Años</center> |
| <center>Distrito</center> | <center>Independencia</center> |
| <center>![Paola_Vasquez](assets/chapter-5/validation_vasquez.png)</center> | <center>Paola Vásquez considera que la aplicación es útil y le gusta poder seleccionar vehículos según sus necesidades, promoviendo la sostenibilidad e innovando en ecología. Describe la experiencia como fácil y manejable, cumpliendo con lo esperado. También le agrada la personalización en la búsqueda, especialmente los filtros, que encuentra muy útiles para satisfacer las necesidades tanto de los usuarios como de los vehículos disponibles.</center> |
| <center>Timing: 19:09 </center> | <center>URL: https://acortar.link/UZ35w3</center> |
| **Entrevista 3** | **Silvia Alexandra Flores Garcia** | 
| <center>Edad</center> | <center>19 Años</center> |
| <center>Distrito</center> | <center>San Martín</center> |
| <center>![Silvia_Flores](assets/chapter-5/validation_flores.png)</center> | <center>Silvia Flores considera que la aplicación es muy interactiva y le agrada su diseño ecológico. Opina que la usaría, ya que le parece innovadora, especialmente por los filtros que facilitan la búsqueda de distintos modelos. Sugeriría hacer más visibles los filtros, aunque en general se entiende bien su uso. También señala que la aplicación se adapta a los distintos gustos de cada persona, con variedad en precios y modelos, lo que le parece alineado con la innovación y el enfoque ecológico.</center> |
| <center>Timing: 23:05 </center> | <center>URL: https://acortar.link/UZ35w3</center> |

### 5.3.3. Evaluaciones según heurísticas 

### UX Heuristics & Principles Evaluation
### Usability – Inclusive Design – Information Architecture

**CARRERA** : Ingeniería de Software  
**CURSO** : Desarrollo de Aplicaciones Open Source  
**SECCIÓN** : SW56 

**PROFESORES** : Efraín Ricardo Bautista Ubillús  
**AUDITOR** : EcoMovil Squad  
**CLIENTE(S)** : SkillsSapInc

#### SITE o APP A EVALUAR:

EcoMovil

**Propósito:** El objetivo principal de esta evaluación es identificar problemas presentes en la aplicación EcoMovil.  

**Método:** Los descubrimientos en la aplicación se lograrán utilizando la lista de principios heurísticos elaborada por Jakob Nielsen, fundamentada en su investigación original.

#### TAREAS A EVALUAR

#### Evaluación para Landing Page y Aplicación Web

**Landing Page**

1. Se proporciona información detallada sobre la aplicación, destacando sus funcionalidades principales.
2. Se presentan los planes de pago y precios de la aplicación.
3. Incluye un header y footer adecuados, optimizados para la página de inicio.
4. La página principal permite una interacción fluida entre el usuario y la aplicación.

**Aplicación Web**

1. Ingreso a la aplicación para usuarios registrados.
2. Indicadores claros que muestran el progreso o estado de los procesos.
3. Uso de iconos consistentes y comprensibles, alineados con el entorno real.
4. Mensajes de error precisos que indican errores en el registro de datos.
5. Evaluación de patrones de diseño o navegación efectivos.
6. Interfaz de usuario con elementos coherentes y homogéneos.
7. Pestañas de navegación bien organizadas.
8. Botones interactivos, intuitivos y fáciles de utilizar.
9. Navegación fluida y orientación clara dentro de la aplicación.
10. Visualización del perfil de usuario.
11. Visualización del perfil de la organización.
12. Interfaz visualmente atractiva y agradable.

**Tareas Excluidas de la Evaluación Actual**

**Landing Page**

1. Inclusión de enlaces a redes sociales del startup.
2. Política de privacidad y condiciones de uso.

**Aplicación Web**

1. Registro para nuevos usuarios.
2. Funciones de documentación y exportación de registros.
3. Accesibilidad a través de atajos de teclado.
4. Acceso a recursos de ayuda dentro de la aplicación.
5. Inclusión de la política de privacidad y condiciones de uso.
6. Opción de cambio de idioma.

**ESCALA DE SEVERIDAD:**  
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad

| Nivel | Descripción |
|-------|-------------|
| 1     | Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poco frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| 2     | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja para resolverlo de cara al siguiente release. |
| 3     | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta. |
| 4     | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento. |

**TABLA RESUMEN:**

Desktop Landing Page

| #  | Problema                                                                                                          | Escala de severidad | Heurística/Principio violada(o)                            |
|----|-------------------------------------------------------------------------------------------------------------------|---------------------|-----------------------------------------------------------|
| 1  | Falta un video de introducción sobre el equipo, lo que podría ayudar a los usuarios a conocer mejor al equipo detrás de la aplicación y generar confianza. | 2                   | Usability: Coincidencia entre el sistema y el mundo real   |
| 2  | Hay un apóstrofe incorrecto en una palabra de la Landing Page, lo que afecta la profesionalidad y la claridad del mensaje. | 2                   | Usability: Diseño estético y minimalista                   |
| 3  | Falta la internacionalización (i18n) en la plataforma, lo que limita la accesibilidad para usuarios de diferentes idiomas. | 1                   | Usability: Flexibilidad y eficiencia de uso               |
| 4  | El texto en el botón “Regístrate” carece de tilde, lo cual afecta la consistencia y la corrección gramatical en la interfaz. | 2                   | Usability: Estética y diseño minimalista                  |
| 5  | Hay un botón innecesario que no aporta funcionalidad adicional, lo que contribuye al desorden visual y dificulta la navegación. | 2                   | Usability: Diseño estético y minimalista                  |

#### DESCRIPCIÓN DE PROBLEMAS:

**PROBLEMA #1**: Falta un video de introducción sobre el equipo, lo que podría ayudar a los usuarios a conocer mejor al equipo detrás de la aplicación y generar confianza.

- **Severidad**: 2
- **Heurística violada**: Usability: Coincidencia entre el sistema y el mundo real

#### Problema:
Actualmente, la aplicación carece de un video de introducción que presente al equipo detrás de la aplicación. Esto limita la posibilidad de que los usuarios conozcan mejor a quienes desarrollan el producto, afectando su percepción de confianza y conexión.

![Landing_1](assets/chapter-5/problema_1.png)

#### Recomendación:
Incluir un video breve en la página "Acerca de nosotros" donde el equipo se presente y explique su misión y valores en relación con la aplicación. Esto permitirá a los usuarios sentirse más conectados y confiados en el servicio ofrecido, al ver quiénes están detrás y cómo comparten sus intereses o preocupaciones.

**PROBLEMA #2**: Hay un apóstrofe incorrecto en una palabra de la Landing Page, lo que afecta la profesionalidad y la claridad del mensaje.

- **Severidad**: 2
- **Heurística violada**: Usabilidad - Diseño estético y minimalista

#### Problema:
En la Landing Page, se ha utilizado un apóstrofe incorrecto en una palabra, lo que puede dar una impresión negativa al usuario al percibirse como un error de redacción. Esto afecta la claridad del mensaje y reduce la percepción de profesionalidad de la página, pudiendo generar desconfianza en algunos usuarios.

![Landing_2](assets/chapter-5/problema_2.png)

#### Recomendación:
Revisar cuidadosamente el texto de la Landing Page y corregir el apóstrofe incorrecto. Es recomendable hacer una revisión ortográfica completa para evitar errores similares en el futuro y asegurar que el contenido sea claro, profesional y de fácil lectura para los usuarios.

**PROBLEMA #3**: Falta la internacionalización (i18n) en la aplicación, lo que limita la accesibilidad para usuarios de diferentes idiomas.

- **Severidad**: 1
- **Heurística violada**: Usabilidad - Flexibilidad y eficiencia de uso

#### Problema:
La aplicación actualmente solo está disponible en un idioma, lo que dificulta el acceso para usuarios que no hablan ese idioma. Esto limita la usabilidad y accesibilidad del sitio, restringiendo su alcance y la posibilidad de atraer a un público más amplio de diferentes países o regiones. La falta de soporte multilingüe puede generar frustración en los usuarios que no comprenden el idioma principal de la plataforma.

![Landing_3](assets/chapter-5/problema_3.png)

#### Recomendación:
Implementar un sistema de internacionalización (i18n) en la aplicación que permita seleccionar el idioma preferido del usuario. Esto incluiría traducciones precisas de todos los textos de la interfaz, botones y mensajes, asegurando una experiencia de usuario coherente en cada idioma. También se recomienda agregar una opción visible de cambio de idioma en el menú principal o en la cabecera para mejorar la accesibilidad y facilitar el uso de la aplicación para usuarios de diferentes regiones.

**PROBLEMA #4**: El texto en el botón “Regístrate” carece de tilde, lo cual afecta la consistencia y la corrección gramatical en la interfaz.

- **Severidad**: 2
- **Heurística violada**: Usability: Estética y diseño minimalista

#### Problema:
El botón de registro en la interfaz muestra la palabra "Regístrate" sin tilde, apareciendo como "Registrate". Esto representa un error ortográfico que puede afectar la percepción de profesionalidad y cuidado en los detalles de la aplicación. Los errores gramaticales en la interfaz pueden reducir la confianza del usuario en la aplicación, al parecer descuidada o poco profesional.

![Landing_4](assets/chapter-5/problema_4.png)

#### Recomendación:
Corregir el texto del botón para incluir la tilde en “Regístrate”. Además, es recomendable hacer una revisión completa de la ortografía y gramática en toda la interfaz para garantizar la consistencia y corrección en todos los elementos de texto. Esto contribuirá a una mejor experiencia de usuario y a una percepción más profesional de la plataforma.

**PROBLEMA #5**: Hay un botón innecesario que no aporta funcionalidad adicional, lo que contribuye al desorden visual y dificulta la navegación.

- **Severidad**: 2
- **Heurística violada**: Usability: Diseño estético y minimalista 

#### Problema:
La interfaz contiene un botón que no ofrece ninguna funcionalidad adicional ni necesaria para el flujo de usuario. Este botón innecesario crea desorden visual, distrae al usuario y complica la navegación, ya que añade elementos superfluos en la interfaz. La presencia de componentes sin función específica rompe con el principio de minimalismo en el diseño, afectando la claridad y la eficiencia de uso.

![Landing_5](assets/chapter-5/problema_5.png)

#### Recomendación:
Eliminar el botón innecesario para simplificar la interfaz y mejorar la experiencia de usuario. Revisar la aplicación para identificar otros posibles elementos redundantes o superfluos y mantener únicamente aquellos componentes que aporten valor o funcionalidad clara al usuario. Esto ayudará a lograr un diseño más limpio y fácil de navegar.

Web Application

| #  | Problema                                                                                                               | Escala de severidad | Heurística/Principio violada(o)                           |
|----|------------------------------------------------------------------------------------------------------------------------|---------------------|----------------------------------------------------------|
| 1  | Los botones de "Log In" están demasiado próximos, lo que dificulta su uso correcto                                     | 2                   | Usability - Consistencia y estándares                    |
| 2  | El mapa no se ajusta adecuadamente en dispositivos móviles o pantallas pequeñas                                        | 2                   | Usability - Estética y diseño minimalista                |
| 3  | Los botones de "Rent" y "Buy" carecen de funcionalidad                                                                 | 1                   | Usability - Flexibilidad y eficiencia de uso             |
| 4  | La función de clic para acceder al alquiler o compra de un vehículo específico no está activa                          | 2                   | Usability - Control y Libertad del usuario               |

**PROBLEMA #1**: Los botones de "Log In" están demasiado próximos, lo que dificulta su uso correcto.

- **Severidad**: 2
- **Heurística violada**: Usability - Consistencia y estándares

#### Problema:
La proximidad entre los botones de "Log In" en la interfaz puede llevar a errores al usarlos, dificultando que el usuario seleccione el botón correcto con facilidad. Esta falta de espacio adecuado entre los elementos afecta la usabilidad al no seguir los estándares de diseño consistentes que faciliten la interacción.

![Frontend_1](assets/chapter-5/frontend_1.png)

#### Recomendación:
Aumentar la separación entre los botones de "Log In" para reducir la posibilidad de errores de clic y mejorar la precisión en la interacción. Mantener una distancia adecuada entre los elementos interactivos siguiendo las pautas de diseño de usabilidad para mejorar la experiencia del usuario.

**PROBLEMA #2**: El mapa no se ajusta adecuadamente en dispositivos móviles o pantallas pequeñas.

- **Severidad**: 2
- **Heurística violada**: Usability - Estética y diseño minimalista

#### Problema:
La interfaz del mapa no es responsiva, lo que genera problemas de visualización en dispositivos móviles y pantallas pequeñas. Este problema afecta la accesibilidad y estética del diseño, ya que los usuarios no pueden visualizar ni interactuar con el mapa de forma eficiente en diferentes tamaños de pantalla.

![Frontend_2](assets/chapter-5/frontend_2.png)

#### Recomendación:
Optimizar el diseño del mapa para que se adapte correctamente a pantallas de diferentes tamaños, especialmente en dispositivos móviles. Implementar un diseño responsivo y minimalista que mantenga la funcionalidad del mapa sin comprometer la claridad visual.

**PROBLEMA #3**: Los botones de "Rent" y "Buy" carecen de funcionalidad.

- **Severidad**: 1
- **Heurística violada**: Usability - Flexibilidad y eficiencia de uso

#### Problema:
Los botones de "Rent" y "Buy" en la interfaz no están habilitados o no realizan ninguna acción al ser seleccionados, lo que afecta la eficiencia de uso y genera confusión en el usuario, al no cumplir con las expectativas de navegación y funcionalidad en la aplicación.

![Frontend_3](assets/chapter-5/frontend_3.png)

#### Recomendación:
Activar la funcionalidad de los botones de "Rent" y "Buy" para que cumplan con el propósito esperado y mejoren la experiencia de usuario. Asegurarse de que todos los botones en la interfaz tengan una función clara y accesible.

**PROBLEMA #4**: La función de clic para acceder al alquiler o compra de un vehículo específico no está activa.

- **Severidad**: 2
- **Heurística violada**: Usability - Control y Libertad del usuario

#### Problema:
Al intentar hacer clic para acceder a la información de alquiler o compra de un vehículo específico, el enlace o botón no responde, limitando el control y la libertad del usuario para explorar opciones. Esto genera frustración al no poder navegar fluidamente en la plataforma.

![Frontend_4](assets/chapter-5/frontend_4.png)

#### Recomendación:
Activar la función de clic para acceder a la información de alquiler o compra de cada vehículo. Verificar que todos los enlaces y botones críticos estén operativos para facilitar la navegación y otorgar al usuario el control necesario para explorar opciones.

### 5.4. Video About-the-Product

A continuación, se muestra el video "Video About-the-Product", que destaca el propósito, las ventajas y las características clave de la aplicación. 

![product](assets/chapter-5/image_the_product.png)

Enlace del video publicado en YouTube: https://www.youtube.com/watch?v=Na3BHmdkkm0

Enlace del video publicado en Stream: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213423_upc_edu_pe/ET7rrgNghS5NoT7rOt1_kJABDnptt1hQNpeiDSNtXfs94g?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=DW0IbK 

### Video About-the-Team

A continuación, se muestra el video "Video About-the-Team".

![Video_About_the_Team](assets/chapter-5/video_about_the_team.png)

Enlace del video publicado en YouTube: https://youtu.be/UFqRGq8VyIg

Enlace del video publicado en Stream: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213423_upc_edu_pe/ESVmq7eIuTdMisUnHizweHUBMSJujUcv6CZkeGVkeDSAeA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=KRoi8C

# Conclusiones

Las tareas asignadas para la entrega TB1 han sido completadas y documentadas en el repositorio de GitHub del equipo. Durante la elaboración del informe, se redactaron y graficaron los contenidos en formato Markdown, se realizaron commits para monitorear el progreso, se generaron los artefactos necesarios con las herramientas del proyecto y se organizaron reuniones para asignar tareas y coordinar el avance del informe.

En cuanto a la entrega del TP1, se implementó y validó el producto utilizando un enfoque ágil, dividido en sprints manejables que permitieron una rápida iteración e integración continua de retroalimentación. La gestión de la configuración del software aseguró un entorno de desarrollo optimizado y bien gestionado, y la implementación de la página de inicio, los servicios y las aplicaciones se realizó de forma eficiente y organizada, con sprints planificados y ejecutados de manera transparente. Durante el desarrollo de la aplicación web, se aplicó la arquitectura de DDD (Domain-Driven Design), que permitió identificar y modelar los dominios de negocio, estableciendo límites claros entre ellos para asegurar una adecuada separación de responsabilidades. Esto facilitó la creación de un sistema robusto y flexible, favoreciendo tanto el mantenimiento como la evolución del software.

Para la entrega TB2 y el trabajo final, se concluye que es fundamental establecer una base sólida de diseño antes de comenzar a escribir el código. En este sentido, la creación de un diagrama de clases adecuado ayuda a visualizar cómo se interrelacionan las entidades implementadas.

La redacción de los criterios de aceptación en lenguaje Gherkin para las historias de usuario en este sprint asegura que se cubran los posibles escenarios de interacción entre el usuario y la plataforma, lo que ayuda a eliminar resultados no deseados y garantizar el correcto funcionamiento de las funcionalidades.

Es importante considerar tiempo adicional para cada sprint con el fin de corregir las historias de usuario pendientes o no planificadas. Este sprint presentó restricciones de tiempo debido a imprevistos.

Finalmente, la documentación de los módulos y artefactos facilita la comprensión de las funcionalidades disponibles, proporcionando ejemplos prácticos e interactivos.

Recomendaciones para optimizar el proceso:

- Establecer metas claras para cada miembro del equipo y asegurar que comprendan los objetivos del Sprint.
- Mantener una documentación precisa y actualizada en el repositorio para una fácil referencia.
- Programar revisiones periódicas para evaluar y ajustar el progreso del informe.
- Fomentar una comunicación constante y abierta dentro del equipo para resolver problemas rápidamente.

Estas recomendaciones contribuirán a un proceso más eficiente y a la entrega de un informe de alta calidad.

Las tareas asignadas para el TB2 incluyeron mejoras en la aplicación, validaciones de usuario y revisiones críticas. También se organizó la diagramación en función del "Backend" propuesto por el equipo para desarrollar una actividad más avanzada de acuerdo con la entrega. Se implementaron configuraciones eficientes que favorecieron una buena dinámica y un mayor entendimiento del proyecto. Los sprints del tercer ciclo se organizaron y ejecutaron de manera eficiente, lo que contribuyó a un mejor dominio del negocio.

# Bibliografía

Restrepo, M. E., & Carvajal, J. A. (2021). La calidad de vida en el contexto de la resiliencia en el servicio de salud integral. Revista Latinoamericana de Sistemas e Informática, 19(1), 152-163. http://www.scielo.org.co/pdf/rlsi/v19n1/1794-4449-rlsi-19-01-152.pdf

Blog de la Universidad de San Ignacio de Loyola. (2021). Créditos educativos: Una alternativa para poner fin a la deserción universitaria. Recuperado de https://blogs.usil.edu.pe/novedades/creditos-educativos-una-alternativa-para-poner-fin-la-desercion-universitaria#:~:text=Según%20el%20Ministerio%20de%20Educación,2019%20a%2023.2%20%%20en%202021

Angular. (n.d.). Routing overview. Recuperado de https://v17.angular.io/guide/routing-overview

FontAwesome. (n.d.). FontAwesome documentation. Recuperado de https://docs.fontawesome.com/

Tailwind CSS. (n.d.). Tailwind CSS documentation. Recuperado de https://v2.tailwindcss.com/docs

# Anexos

To-Be Mapping: https://miro.com/welcomeonboard/ZmlsbFNLbkZuM3Q1NlBVd3ZqcUMzZWFsbGxKaFZRUGJmWjJBUWo0VnlOQUVROThlc0t5SzZEcVh0SWdYWjVJVXwzMDc0NDU3MzQ5NjI2ODA0NjMyfDI=?share_link_id=116933273053

Enlace del Lean Ux Canvas: https://www.canva.com/design/DAGOEXan6rE/pJTlXgHJBmfhVfeAe3pFgA/editutm_content=DAGOEXan6rE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

Enlace de Entrevistas: https://acortar.link/uMdFvk

Enlace Web Applications UX/UI Design: https://www.figma.com/design/WATKX4mlDctquazhZwgUB9/Mock-ups?node-id=0-1&t=XIYVHrHcrTEoUWbN-1

Enlace General Style Guidelines: https://www.figma.com/design/GnGrty8UpoDQsPbgKYdQ7E/EcoMovil?node-id=0-1&t=MRGVDtnKEXSGH8Cy-1

Enlace Landing Page Mock-up: https://github.com/orgs/Open-Source-SW56-Group-2-EcoMovil/repositories

Enlace Landing Page Wireframes: https://github.com/orgs/Open-Source-SW56-Group-2-EcoMovil/repositories

Enlace del Backlog 1: https://trello.com/b/Z7J4iU6N/ecomovil-sprint-1

Enlace del Backlog 2: https://trello.com/b/48W0tEjF/ecomovil-product-backlog-tp

Enlace del Backlog 3: https://trello.com/b/asdWkojU/ruedarent-sprint-3

Enlace del Backlog 4: https://trello.com/invite/b/6735240cb8e0131932666410/ATTIfbe9369ef45e8ff47bfdc01816f4e798ABCAD3B0/ecomovil-product-backlog-sprint-4

Enlace Video About the Team: https://youtu.be/UFqRGq8VyIg

Enlace Video About the Product: https://www.youtube.com/watch?v=Na3BHmdkkm0 

Enlace My JSON Server: https://my-json-server.typicode.com/Open-Source-SW56-Group-2-EcoMovil/Json-Server-EcoMovil

Enlace de la organización en GitHub: https://github.com/orgs/Open-Source-SW56-Group-2-EcoMovil/repositories

Enlace del Frontend: https://happy-tree-09edbd910.5.azurestaticapps.net/login

Enlace del Landing Page: https://open-source-sw56-group-2-ecomovil.github.io/Landing-Page-EcoMovil/

Enlace del Backend: https://back-end-ecomovil-deploy-production.up.railway.app/swagger-ui/index.html#/

Enlace del Diagrama de Base de Datos: https://lucid.app/lucidchart/e06db2ed-90a9-4d18-9e17-cdc374991f9c/edit?viewport_loc=415%2C329%2C2176%2C904%2C0_0&invitationId=inv_9c243997-a36f-4661-8b63-4d07191632d1

Enlace del video del trabajo final: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213423_upc_edu_pe/EWRFicbfLOBCmMH02n9CBJEBKMKGdXdYpHIIOLWwqFlFPg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=RvrmLV
