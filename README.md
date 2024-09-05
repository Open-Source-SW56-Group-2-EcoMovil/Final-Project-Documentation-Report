# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

Para elaborar el To-be Scenario Mapping, el equipo definió cómo sería el flujo de trabajo después de la implementación de nuestra solución, EcoMovil, para ambos segmentos objetivos. El propósito de este artefacto es comparar y abordar los aspectos negativos identificados en el As-is Scenario.

- Segmento Universitarios:

![ImpactMapping1](/assets/sprint1/TobemappingSegmento2.jpg)

- Segmento Adquiriente:

![ToBeMapping2](/assets/sprint1/Tobemappingsegmento1.jpg)

## 3.2. User Stories

Las user stories son una manera de transformar el lenguaje informal de los clientes en requisitos de software que deben ser considerados durante el desarrollo del sistema. Una user story bien elaborada proporciona al desarrollador una explicación clara de la funcionalidad que se está construyendo, su propósito y el valor que ofrece al usuario. Para el producto EcoMovil, EcoMovil Squad presenta un conjunto de user stories para el desarrollo de la Landing Page, la aplicación web y user stories técnicas.

<table >
    <tr>
        <th>User Story ID</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Criterios de Aceptación</th>
        <th>Relacionado con (Epic ID)</th>
    </tr>
  <tr>
        <td>US01</td>
        <td>Barra de navegación en la Landing Page</td>
        <td>
    
<b>**Como** universitario o adquiriente **quiero** visualizar una landing page **para** conocer las funciones de la aplicación.</td>
        <td>**Escenario 1: Visualización de la Barra de Navegación**
<br>

**Dado que** el universitario o adquiriente se encuentre en la landing page,
**cuando** se muestra la barra de navegación, 
**entonces** podrá visualizar diversas secciones y botones.

**Escenario 2: Funcionalidad de Navegación**

**Dado que** el universitario o adquiriente accede a la landing page y visualice la barra de navegación,
**cuando** hace clic en cualquiera de los enlaces de la barra de navegación,
**entonces** debe ser redirigido a la sección correspondiente de la aplicación.</td>
        <td>1</td>
    </tr>
<tr>
    <td>US02</td>
    <td>Sección Hero en la Landing Page</td>
    <td>
<b>**Como** universitario o adquiriente **quiero** ver una sección hero atractiva y clara al acceder a la Landing Page **para** entender el valor de la aplicación y decidir si deseo saber más sobre ella.</td>
    <td>
**Escenario 1: Visualización de la Sección Hero**

**Dado que** el universitario o adquiriente se encuentre en la landing page,  
**cuando** se carga la página,  
**entonces** la sección hero debe ser visible en la parte superior de la página con un diseño atractivo y claro.
    </td>
    <td>1</td>
</tr>
<tr>
    <td>US03</td>
    <td>Sección Footer en la Landing Page</td>
    <td><b>Como</b> universitario o adquiriente <b>quiero</b> visualizar un footer en la landing page <b>para</b> acceder a información adicional.</td>
    <td>
**Escenario 1: Visualización de la Sección Footer**

**Dado que** el universitario o adquiriente se encuentre en la landing page,  
**cuando** se carga la página,  
**entonces** la sección footer debe ser visible en la parte inferior de la página con términos de servicio y políticas de privacidad.
    </td>
    <td>1</td>
</tr>
<tr>
    <td>US04</td>
    <td>Sección de Beneficios en la Landing Page</td>
    <td><b>Como</b> universitario o adquiriente <b>quiero</b> ver una sección de cómo funciona EcoMovil, <b>para</b> entender cómo la aplicación puede mejorar mi experiencia ecológica y mi interacción con la aplicación.</td>
    <td>
**Escenario 1: Visualización de la Sección de Beneficios**

**Dado que** el universitario o adquiriente se encuentre en la landing page,  
**cuando** se carga la página,  
**entonces** la sección de “Cómo funciona”  debe ser visible en la página con una descripción clara y atractiva de cómo EcoMovil puede mejorar la experiencia ecológica y la interacción con la aplicación.
    </td>
    <td>1</td>
</tr>
<tr>
    <td>US05</td>
    <td>Sección de Contacto en la Landing Page</td>
    <td><b>Como</b> universitario o adquiriente <b>quiero</b> tener acceso a una sección de contacto clara y funcional <b>para</b> poder unirme a EcoMovil para comenzar la experiencia.</td>
    <td>
**Escenario 1: Visualización de la Sección de Contacto**

**Dado que** el universitario o adquiriente se encuentre en la landing page,  
**cuando** se carga la página,  
**entonces** la sección de Contacto debe ser visible en la página con información clara sobre cómo comunicarse con el equipo de EcoMovil.
    </td>
    <td>1</td>
</tr>
<tr>
    <td>US06</td>
    <td>Landing Page Responsive con diferentes dispositivos</td>
    <td><b>Como</b> universitario o adquiriente <b>quiero</b> que la landing page sea responsive <b>para</b> que pueda visualizar y navegar por ella fácilmente desde cualquier dispositivo (móvil, tablet, o escritorio) sin pérdida de funcionalidad o legibilidad.</td>
    <td>
**Escenario 1: Visualización en Diferentes Dispositivos**

**Dado que** el universitario o adquiriente acceda a la landing page desde un dispositivo móvil, tablet o escritorio,  
**cuando** se carga la página,  
**entonces** la landing page debe ajustarse adecuadamente al tamaño de pantalla del dispositivo, manteniendo la funcionalidad completa y la legibilidad del contenido sin necesidad de hacer zoom o desplazamiento horizontal.
    </td>
    <td>1</td>
</tr>
<tr>
    <td>US07</td>
    <td>Sección de planes en la Landing Page</td>
    <td><b>Como</b> universitario o adquiriente <b>quiero</b> acceder a una sección de planes <b>para</b> poder elegir un plan y unirme a EcoMovil para comenzar la experiencia.</td>
    <td>
**Escenario 1: Visualización de la Sección de Planes**

**Dado que** el universitario o adquiriente se encuentre en la landing page,  
**cuando** se carga la página,  
**entonces** la sección de planes debe ser visible y accesible, mostrando claramente los diferentes planes disponibles con descripciones y precios, permitiendo al usuario seleccionar el plan que desee y seguir el proceso para unirse a EcoMovil.
    </td>
    <td>1</td>
</tr>
<tr>
    <td>US08</td>
    <td>Sección de acerca de en la Landing Page</td>
    <td><b>Como</b> universitario o adquiriente <b>quiero</b> tener acceso a una sección de “Acerca de” clara y funcional <b>para</b> conocer la historia y misión de EcoMovil.</td>
    <td>
**Escenario 1: Visualización de la Sección de Acerca de**

**Dado que** el universitario o adquiriente se encuentre en la landing page,  
**cuando** se carga la página,  
**entonces** la sección de “Acerca de” debe ser visible y accesible, mostrando claramente la historia y misión de EcoMovil con una descripción concisa y atractiva.
    </td>
    <td>1</td>
</tr>
<tr>
    <td>US09</td>
    <td>Sección de unirse en la Landing Page</td>
    <td><b>Como</b> universitario o adquiriente <b>quiero</b> acceder a una sección para unirme a EcoMovil <b>para</b> poder registrar mi correo electrónico e inscribirme en EcoMovil.</td>
    <td>
**Escenario 1: Visualización de la Sección de Unirse**

**Dado que** el universitario o adquiriente se encuentre en la landing page,  
**cuando** se carga la página,  
**entonces** la sección de “Unirse” debe ser visible y accesible para registrarse en EcoMovil.
    </td>
    <td>1</td>
</tr>
<tr>
    <td>US10</td>
    <td>Sección de inscribirse en la Landing Page</td>
    <td><b>Como</b> universitario o adquiriente <b>quiero</b> tener acceso a una sección de inscripción <b>para</b> poder ingresar a la aplicación de EcoMovil.</td>
    <td>
**Escenario 1: Visualización de la Sección de Inscripción**

**Dado que** el universitario o adquiriente se encuentre en la landing page,  
**cuando** se carga la página,  
**entonces** la sección de “Inscribirse” debe ser visible y accesible.
    </td>
    <td>1</td>
</tr>
<tr>
    <td>US11</td>
    <td>Sección de universitario en la Landing Page</td>
    <td><b>Como</b> universitario, <b>quiero</b> acceder a una sección dedicada a universitarios <b>para</b> unirme como universitario a EcoMovil.</td>
    <td>
**Escenario 1: Visualización de la Sección de Universitario**

**Dado que** el universitario se encuentre en la landing page,  
**cuando** se carga la página,  
**entonces** la sección dedicada a universitarios debe ser visible y accesible, mostrando información específica para universitarios.
    </td>
    <td>1</td>
</tr>
<tr>
    <td>US12</td>
    <td>Sección de conozca más sobre nosotros en la Landing Page</td>
    <td><b>Como</b> universitario o adquiriente, <b>quiero</b> acceder a una sección de “Conozca más sobre nosotros” <b>para</b> obtener información detallada sobre EcoMovil.</td>
    <td>
**Escenario 1: Visualización de la Sección “Conozca Más Sobre Nosotros”**

**Dado que** el universitario o adquiriente se encuentre en la landing page,  
**cuando** se carga la página,  
**entonces** la sección “Conozca más sobre nosotros” debe ser visible y accesible, mostrando información detallada sobre la aplicación.
    </td>
    <td>1</td>
</tr>
<tr>
    <td>US13</td>
    <td>Botón de empieza tu viaje en la Landing Page</td>
    <td><b>Como</b> universitario o adquiriente, <b>quiero</b> encontrar un botón <b>para</b> empezar mi viaje en EcoMovil. </td>
    <td>
**Escenario 1: Visualización del Botón "Empieza tu viaje"**

**Dado que** el universitario o adquiriente se encuentre en la landing page,  
**cuando** se carga la página,  
**entonces** el botón “Empieza tu viaje” debe ser visible y accesible, destacándose en la página con un diseño atractivo que motive a los usuarios a comenzar su experiencia en EcoMovil.
    </td>
    <td>1</td>
</tr>
<tr>
    <td>US14</td>
    <td>Sección de todos los derechos reservados en la Landing Page</td>
    <td><b>Como</b> universitario o adquiriente, <b>quiero</b> ver una sección de derechos reservados <b>para</b> estar seguro de que EcoMovil protege mis derechos. </td>
    <td>
**Escenario 1: Visualización de la Sección "Todos los derechos reservados"**

**Dado que** el universitario o adquiriente se encuentre en la landing page,  
**cuando** se carga la página,  
**entonces** la sección de “Todos los derechos reservados” debe ser visible al final de la página, mostrando de forma clara que los derechos del usuario están protegidos por EcoMovil.
    </td>
    <td>1</td>
</tr>
<tr>
    <td>US15</td>
    <td>Sección de adquiriente en la Landing Page</td>
    <td><b>Como</b> adquiriente, <b>quiero</b> ver una sección de derechos reservados <b>para</b> estar seguro de que EcoMovil protege mis derechos. </td>
    <td>
**Escenario 1: Visualización de la Sección "Todos los derechos reservados"**

**Dado que** el adquiriente se encuentre en la landing page,  
**cuando** se carga la página,  
**entonces** la sección de “Todos los derechos reservados” debe ser visible al final de la página, mostrando de forma clara que los derechos del usuario están protegidos por EcoMovil.
    </td>
    <td>1</td>
</tr>
 </tbody>
</table>

## 3.3. Impact Mapping

En esta sección, presentamos el **Impact Mapping** para el proyecto de **EcoMovil**, cuyo objetivo es desarrollar e implementar un mapa interactivo que facilite la localización. Este mapa es esencial para optimizar la experiencia de nuestros usuarios y alcanzar los objetivos comerciales.

El **Impact Mapping** ofrece una visión clara de cómo los objetivos de negocio, las necesidades de los usuarios y las funcionalidades propuestas se interconectan. Asegura que cada elemento del desarrollo esté alineado con nuestras metas, contribuyendo al éxito de **EcoMovil** y mejorando tanto la experiencia de los universitarios como la de los adquirientes.

![ImpactMapping](/assets/sprint1/Impactmap1.png)

## 3.4. Product Backlog

<table>
    <thead>
        <tr>
            <th># Orden</th>
            <th>User Story ID</th>
            <th>Título</th>
            <th>Descripción</th>
            <th>Story Points</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>US01</td>
            <td>Barra de navegación en la Landing Page</td>
            <td><b>Como</b> universitario o adquiriente <b>quiero</b> visualizar una landing page<b>para</b> conocer las funciones de la aplicación.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>2</td>
            <td>US02</td>
            <td>Sección Hero en la Landing Page</td>
            <td><b>Como</b> universitario o adquiriente, <b>quiero</b> ver una sección hero atractiva y clara al acceder a la Landing Page <b>para</b> entender el valor de la aplicación y decidir si deseo saber más sobre ella.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>3</td>
            <td>US03</td>
            <td>Sección Footer en la Landing Page</td>
            <td><b>Como</b> universitario o adquiriente, <b>quiero</b> visualizar un footer en la landing page <b>para</b> acceder rápidamente a información adicional.</td>
            <td>2</td>
        </tr>
        <tr>
            <td>4</td>
            <td>US04</td>
            <td>Sección de Beneficios en la Landing Page</td>
            <td><b>Como</b> universitario o adquiriente, <b>quiero</b> ver una sección de cómo funciona EcoMovil, <b>para</b> entender cómo la aplicación puede mejorar mi experiencia ecológica y mi interacción con la aplicación.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>5</td>
            <td>US05</td>
            <td>Sección de Contacto en la Landing Page</td>
            <td><b>Como</b> universitario o adquiriente, <b>quiero</b> tener acceso a una sección de contacto clara y funcional <b>para</b> poder unirme a EcoMovil para comenzar la experiencia.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>6</td>
            <td>US06</td>
            <td>Landing Page Responsive con diferentes dispositivos</td>
            <td><b>Como</b> universitario o adquiriente, <b>quiero</b> que la landing page sea responsive <b>para</b> que pueda visualizar y navegar por ella fácilmente desde cualquier dispositivo (móvil, tablet, o escritorio) sin pérdida de funcionalidad o legibilidad.</td>
            <td>7</td>
        </tr>
        <tr>
            <td>7</td>
            <td>US07</td>
            <td>Sección de planes en la Landing Page</td>
            <td><b>Como</b> universitario o adquiriente, <b>quiero</b> acceder a una sección de planes <b>para</b> poder elegir un plan y unirme a EcoMovil para comenzar la experiencia.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>8</td>
            <td>US08</td>
            <td>Sección de acerca de en la Landing Page</td>
            <td><b>Como</b> universitario o adquiriente, <b>quiero</b> tener acceso a una sección de "Acerca de" clara y funcional <b>para</b> conocer la historia y misión de EcoMovil.</td>
            <td>4</td>
        </tr>
        <tr>
            <td>9</td>
            <td>US09</td>
            <td>Sección de unirse en la Landing Page</td>
            <td><b>Como</b> universitario o adquiriente, <b>quiero</b> acceder a una sección para unirme a EcoMovil <b>para</b> poder registrar mi correo electrónico e inscribirme en EcoMovil.</td>
            <td>4</td>
        </tr>
        <tr>
            <td>10</td>
            <td>US10</td>
            <td>Sección de inscribirse en la Landing Page</td>
            <td><b>Como</b> universitario o adquiriente, <b>quiero</b> tener acceso a una sección de inscripción <b>para</b> poder ingresar a la aplicación de EcoMovil.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>11</td>
            <td>US11</td>
            <td>Sección de universitario en la Landing Page</td>
            <td><b>Como</b> universitario, <b>quiero</b> acceder a una sección dedicada a universitarios <b>para</b> unirme como universitario a EcoMovil.</td>
            <td>4</td>
        </tr>
        <tr>
            <td>12</td>
            <td>US12</td>
            <td>Sección de conozca más sobre nosotros en la Landing Page</td>
            <td><b>Como</b> universitario o adquiriente, <b>quiero</b> acceder a una sección de "Conozca más sobre nosotros" <b>para</b> ingresar a EcoMovil.</td>
            <td>4</td>
        </tr>
        <tr>
            <td>13</td>
            <td>US13</td>
            <td>Botón de empieza tu viaje en la Landing Page</td>
            <td><b>Como</b> universitario o adquiriente, <b>quiero</b> encontrar un botón <b>para</b> empezar mi viaje en EcoMovil. </td>
            <td>3</td>
        </tr>
        <tr>
            <td>14</td>
            <td>US14</td>
            <td>Sección de todos los derechos reservados en la Landing Page</td>
            <td><b>Como</b> universitario o adquiriente, <b>quiero</b> ver una sección de derechos reservados <b>para</b> estar seguro de que EcoMovil protege mis derechos.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>15</td>
            <td>US15</td>
            <td>Sección de adquiriente en la Landing Page</td>
            <td><b>Como</b> adquiriente, <b>quiero</b> acceder a una sección dedicada a adquirientes <b>para</b> comprar, vender, alquilar o rentar en EcoMovil.</td>
            <td>5</td>
        </tr>
    </tbody>
</table>
<br>

[![Backlog](/assets/sprint1/trello1.png)](https://trello.com/invite/b/661b0a12e3392a7cd56479b3/ATTIe08b35a362a9b35b5e0152e660a454e79586C6AA/ecomovil-product-backlog-tb1 )

[![Backlog](/assets/sprint1/trello2.png)](https://trello.com/invite/b/661b0a12e3392a7cd56479b3/ATTIe08b35a362a9b35b5e0152e660a454e79586C6AA/ecomovil-product-backlog-tb1 )

Enlace del Product Backlog: https://trello.com/invite/b/661b0a12e3392a7cd56479b3/ATTIe08b35a362a9b35b5e0152e660a454e79586C6AA/ecomovil-product-backlog-tb1 
