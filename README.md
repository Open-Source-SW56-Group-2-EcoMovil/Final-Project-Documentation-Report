# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

Para elaborar el To-be Scenario Mapping, el equipo definió cómo sería el flujo de trabajo después de la implementación de nuestra solución, EcoMovil, para ambos segmentos objetivos. El propósito de este artefacto es comparar y abordar los aspectos negativos identificados en el As-is Scenario.

- Estudiante universitario que posee un vehículo menor:
  
- Usuarios que alquilan o compran vehículos a través de la aplicación:

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
        <td><b>**Como** universitario o rentador **quiero** visualizar una página web **para** conocer los servicios de la aplicación.</td>
        <td>**Escenario 1: Visualización de la Barra de Navegación**
<br>
**Dado que** el universitario o rentador se encuentre en la landing page,
**cuando** se muestra la barra de navegación, 
**entonces** podrá visualizar diversas secciones y botones.

**Escenario 2: Funcionalidad de Navegación**

**Dado** el universitario o rentador accede a la landing page y visualiza la barra de navegación,
**cuando** hace clic en cualquiera de los enlaces de la barra de navegación,
**entonces** debe ser redirigido a la sección correspondiente de la página web.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>US02</td>
        <td>Sección Hero en la Landing Page</td>
        <td>**Como** universitario o rentador, **quiero** ver una sección hero atractiva y clara al acceder a la Landing Page **para** entender el valor de la aplicación y decidir si deseo saber más sobre ella.</td>
        <td>**Escenario 1: Visualización de la Sección Hero**

**Dado que** el universitario o rentador está en la Landing Page,
**cuando** la sección hero es visible,
**entonces** debe mostrar un titular principal claro y llamativo que comunique el valor de la aplicación.

**Escenario 2: Botón de “Descubre Más”**

**Dado que** el universitario o rentador está en la Landing Page,
**Cuando** visualiza la sección hero,
**Entonces** debe estar el botón “Descubre Más” que sea claramente visible y clicable.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>US03</td>
        <td>Sección Footer en la Landing Page</td>
        <td><b>**Como** universitario o rentador, **quiero** visualizar un footer en la página web **para** acceder rápidamente a información adicional y enlaces relevantes como redes sociales.</td>
        <td>**Escenario 1: Visualización del Footer**

**Dado que** el universitario o rentador accede a la Landing Page,
**Cuando** la página se desplaza hasta el final,
**Entonces** el footer debe estar visible en la parte inferior con sus enlaces a las redes sociales.

**Escenario 2: Funcionalidad de Enlaces del Footer**

**Dado que** el universitario o rentador visualiza el footer en la Landing Page,
**Cuando** hace clic en cualquiera de los enlaces del footer,
**Entonces** debe ser redirigido a las redes sociales de la startup.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>US04</td>
        <td>Sección de Beneficios en la Landing Page</td>
        <td><b>**Como** universitario o rentador, **quiero** ver una sección de beneficios que tenga las características principales de EcoMovil, **para** entender cómo la aplicación puede mejorar mi experiencia de movilidad urbana y mi interacción con la plataforma </td>
        <td>**Escenario 1: Visualización de la Sección de Beneficios**

**Dado que** el universitario o rentador está en la Landing Page,
**Cuando** se desplaza hacia la sección de beneficios,
**Entonces** debe ver una sección destacada que contiene al menos 2 beneficios clave de la aplicación, basados en las características principales.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>US05</td>
        <td>Sección de Contacto en la Landing Page</td>
        <td>**Como** universitario o rentador, **quiero** tener acceso a una sección de contacto clara y funcional **para** poder comunicarme con el equipo de EcoMovil **para** resolver dudas, obtener soporte o hacer sugerencias</td>
        <td>**Escenario 1: Visualización de la Sección de Contacto**

**Dado que** el universitario o rentador está en la Landing Page,
**Cuando** se desplaza hacia la sección de contacto,
**Entonces** debe ver una sección claramente identificada que contenga información de contacto y opciones para comunicarse con el equipo de EcoMovil.

**Escenario 2: Información de Contacto**

**Dado que** el universitario o rentador está en la Landing Page,
**Cuando** visualiza la sección de contacto,
**Entonces** debe ver un formulario donde puedan ingresar su nombre, teléfono y correo electrónico para comunicarnos con el usuario a través de la página.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>US06</td>
        <td>Landing Page Responsive con diferentes dispositivos.</td>
        <td>**Como** universitario o rentador, **quiero** que la landing page sea responsive **para** que pueda visualizar y navegar por ella fácilmente desde cualquier dispositivo (móvil, tablet, o escritorio) sin pérdida de funcionalidad o legibilidad.</td>
        <td>**Escenario 1: Adaptación Automática a Diferentes Tamaños de Pantalla**

**Dado que** el universitario o rentador accede a la Landing Page,
**Cuando** utiliza un dispositivo con cualquier tamaño de pantalla (móvil, tablet o escritorio),
**Entonces** el contenido de la página debe ajustarse automáticamente para adaptarse al tamaño de la pantalla, asegurando una presentación clara y coherente.

**Escenario 2: Navegación y Menús Responsive**

**Dado** el visitante accede a la Landing Page desde un dispositivo móvil,
**Cuando** la página se carga completamente,
**Entonces** el menú de navegación debe convertirse en un menú hamburguesa, y al hacer clic, debe desplegarse de forma fluida sin solaparse con otros elementos de la página.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>US07</td>
        <td>Registro a la pagina</td>
        <td>**Como** universitario o rentador, **quiero** registrarme en la aplicación fácilmente **para** poder acceder a vehículos en alquiler y/o venderlos.
</td>
        <td>
            <br/>
        <td>1</td>
    </tr>
    <tr>
        <td>US08</td>
        <td>Búsqueda de vehiculos disponibles</td>
        <td>**Como** Rentador, **quiero** buscar vehículos disponibles usando filtros avanzados, como tipo de vehículo, precio y ubicación, **para** encontrar el más adecuado para mis necesidades.</td>
        <td>
            <br/>
        <td>2</td>
    </tr>
    <tr>
        <td>US09</td>
        <td>Valoracion de los Vehículos</td>
        <td>**Como** Rentador, **quiero** ver valoraciones y reseñas de otros usuarios sobre los vehículos y propietarios **para** tomar decisiones informadas.</td>
        <td>
            <br/>
        <td>2</td>
    </tr>
    <tr>
        <td>US10</td>
        <td>Alquiler de vehiculo</td>
        <td>**Como** Rentador, **quiero** alquilar un vehículo rápidamente a través de la aplicación **para** moverme por la ciudad cuando lo necesite.</td>
        <td>
            <br/>
        <td>2</td>
    </tr>
    <tr>
        <td>US11</td>
        <td>Recomendaciones</td>
        <td>**Como** Rentador, **quiero** recibir recomendaciones de vehículos basadas en mis preferencias y búsquedas anteriores **para** facilitar mi elección.
</td>
        <td>
            <br/>
        <td></td>
    </tr>
    <tr>
        <td>US12</td>
        <td>Recibir Notificaciones</td>
        <td>**Como** Rentador, **quiero** recibir notificaciones cuando mi alquiler esté próximo a vencer **para** devolver el vehículo a tiempo sin penalidades y nuevas publicaciones de vehículos en alquiler que coincidan con mis preferencias</td>
        <td>
            <br/>
        <td>2</td>
    </tr>
    <tr>
        <td>US13</td>
        <td>Acceso al Historial</td>
        <td>**Como** Rentador, **quiero** acceder a un historial de mis alquileres anteriores **para** revisar mis actividades y gastos.</td>
        <td>
            <br/>
        <td>2</td>
    </tr>
    <tr>
        <td>US14</td>
        <td>Mapa Interactivo</td>
        <td>**Como** Rentador, **quiero** utilizar un mapa interactivo **para** localizar los puntos de recogida y 
devolución de vehículos cercanos a mi ubicación.
</td>
        <td>
            <br/>
        <td>2</td>
    </tr>
    <tr>
        <td>US15</td>
        <td>Pagos en Línea</td>
        <td>**Como** Rentador, **quiero** tener la opción de pagar en línea de manera segura a través de la aplicación **para** mayor comodidad.</td>
        <td>
            <br/>
        <td>2</td>
    </tr>
    <tr>
        <td>US16</td>
        <td>Contacto al propietario</td>
        <td>**Como** Rentador, **quiero** poder contactar al propietario antes de alquilar un vehículo **para** aclarar dudas o detalles específicos.
</td>
        <td>
           <br/>
        <td>2</td>
    </tr>
    <tr>
        <td>US17</td>
        <td>visualización de Ofertas</td>
        <td>**Como** Rentador, **quiero** acceder a ofertas especiales o descuentos en vehículos destacados **para** ahorrar en mis alquileres.
</td>
        <td>
            <br/>
        <td>EP03</td>
    </tr>
    <tr>
        <td>US18</td>
        <td>Tiempo de llegada</td>
        <td>**Como** Rentador, **quiero** ver el tiempo estimado **para** llegar a un punto de recogida de vehículos en el mapa interactivo.</td>
        <td>
           <br/>
        <td>2</td>
    </tr>
    <tr>
        <td>US19</td>
        <td>Calificación de Alquiler</td>
        <td>**Como** Rentador, **quiero** poder calificar al propietario después de cada alquiler **para** ayudar a otros usuarios a conocer su reputación</td>
        <td>
            <br/>
        <td>2</td>
    </tr>
    <tr>
        <td>US20</td>
        <td>Extensión de tiempo de Alquiler</td>
        <td>**Como Rentador**, **quiero** poder extender el tiempo de mi alquiler si necesito usar el vehículo por más tiempo del planeado.</td>
        <td>
            <br/>
        <td>2</td>
    </tr>
    <tr>
        <td>US21</td>
        <td>Publicación de Vehículos</td>
        <td>**Como** Propietario, **quiero** publicar mis vehículos de manera rápida y sencilla **para** que los rentadores puedan verlos y contactarme.</td>
        <td>
            <br/>
        <td>3</td>
    </tr>
    <tr>
        <td>US22</td>
        <td>Notificaciones de alquiler de vehiculo</td>
        <td> Como Propietario, quiero recibir notificaciones cuando alguien esté interesado en alquilar o comprar mi vehículo para no perder oportunidades y sobre el estado de mis publicaciones, como expiraciones o renovaciones, para mantenerlas actualizadas.
</td>
        <td>
             <br/>
        <td>3</td>
    </tr>
    <tr>
        <td>US23</td>
        <td>Historial de alquiler y venta</td>
        <td>Como Propietario, quiero acceder a un historial de mis alquileres y ventas para llevar un control detallado de mis ingresos.
</td>
        <td>
            <br/>
        <td>3</td>
    </tr>
    <tr>
        <td>US24</td>
        <td>Brindar soporte de ayuda</td>
        <td>Como Propietario, quiero recibir soporte prioritario si tengo problemas con la plataforma para resolverlos rápidamente.
</td>
        <td>
            <br/>
        <td></td>
    </tr>
    <tr>
        <td>US25</td>
        <td>Peronalizar publicaciones</td>
        <td>Como Propietario, quiero personalizar la descripción y las fotos de mis publicaciones para hacerlas más atractivas a los rentadores</td>
        <td>
            <br/>
        <td></td>
    </tr>
    <tr>
        <td>US26</td>
        <td>Recordatorio de vencimiento de membresia</td>
        <td>Como Propietario, quiero recibir recordatorios cuando mi suscripción esté próxima a vencerse para renovarla y evitar interrupciones en mis publicaciones.
</td>
        <td>
            <br/>
        <td></td>
    </tr>
    <tr>
</table>


## 3.3. Impact Mapping

## 3.4. Product Backlog

[![Sprint1](/assets/sprint1/sprint1.png)](https://trello.com/invite/b/661b0a12e3392a7cd56479b3/ATTIe08b35a362a9b35b5e0152e660a454e79586C6AA/ecomovil-product-backlog-tb1 )
Enlace del Product Backlog: https://trello.com/invite/b/661b0a12e3392a7cd56479b3/ATTIe08b35a362a9b35b5e0152e660a454e79586C6AA/ecomovil-product-backlog-tb1 

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
            <td><b>Como</b> universitario o rentador <b>quiero</b> visualizar una página web <b>para</b> conocer los servicios de la aplicación</td>
            <td>3</td>
        </tr>
        <tr>
            <td>2</td>
            <td>US02</td>
            <td>Sección Hero en la Landing Page</td>
            <td><b>Como</b> universitario o rentador, <b>quiero</b> ver una sección hero atractiva y clara al acceder a la Landing Page <b>para</b> entender el valor de la aplicación y decidir si deseo saber más sobre ella.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>3</td>
            <td>US03</td>
            <td>Sección Footer en la Landing Page</td>
            <td><b>Como</b> universitario o rentador, <b>quiero</b> visualizar un footer en la página web <b>para</b> acceder rápidamente a información adicional y enlaces relevantes como redes sociales.</td>
            <td>2</td>
        </tr>
        <tr>
            <td>4</td>
            <td>US04</td>
            <td>Sección de Beneficios en la Landing Page</td>
            <td><b>**Como**</b> universitario o rentador, <b>**quiero**</b> ver una sección de beneficios que tenga las características principales de EcoMovil, <b>**para**</b> entender cómo la aplicación puede mejorar mi experiencia de movilidad urbana y mi interacción con la plataforma.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>5</td>
            <td>US05</td>
            <td>Sección de Contacto en la Landing Page</td>
            <td><b>Como</b> universitario o rentador, <b>quiero</b> tener acceso a una sección de contacto clara y funcional <b>para</b> poder comunicarme con el equipo de EcoMovil para resolver dudas, obtener soporte o hacer sugerencias.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>6</td>
            <td>US06</td>
            <td>Landing Page Responsive con diferentes dispositivos</td>
            <td><b>Como</b> universitario o rentador, <b>quiero</b> que la landing page sea responsive <b>para</b> que pueda visualizar y navegar por ella fácilmente desde cualquier dispositivo (móvil, tablet, o escritorio) sin pérdida de funcionalidad o legibilidad.</td>
            <td>8</td>
        </tr>
    </tbody>
</table>
