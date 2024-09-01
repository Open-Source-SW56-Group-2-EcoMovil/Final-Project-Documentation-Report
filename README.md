v# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

Para elaborar el To-be Scenario Mapping, el equipo definió cómo sería el flujo de trabajo después de la implementación de nuestra solución, EcoMovil, para ambos segmentos objetivos. El propósito de este artefacto es comparar y abordar los aspectos negativos identificados en el As-is Scenario.

- Estudiante universitario que posee un vehículo menor:


![ImpactMapping1](/assets/sprint1/TobemappingSegmento2.jpg)


- Usuarios que alquilan o compran vehículos a través de la aplicación:


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
    
<b>**Como** universitario o rentador **quiero** visualizar una página web **para** conocer los servicios de la aplicación.</td>
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
</td>      <td>
  
  **Escenario 1: Registro en la plataforma** 
**Dado** que el usuario está en la pantalla de registro,
**Cuando** ingresa un nombre completo, correo electrónico único, una contraseña válida, y selecciona el tipo de usuario,
**Entonces** el sistema debe mostrar un mensaje indicando "el registro fue exitoso" y enviar un correo de confirmación.         
</td>
        <td>1</td>
    </tr>
    <tr>
        <td>US08</td>
        <td>Búsqueda de vehiculos disponibles</td>
        <td>
   
**Como** Rentador, **quiero** buscar vehículos disponibles usando filtros avanzados, como tipo de vehículo, precio y ubicación, **para** encontrar el más adecuado para mis necesidades.</td>
        <td>
**Escenario 1: Busqueda de vehiculos**

**Dado** que el rentador está en la pantalla de búsqueda de vehículos,
**Cuando** el rentador presiona el botón de búsqueda,
**Entonces** el sistema debe mostrar una lista de todos los vehículos disponibles.

**Escenario 2: Busqueda de vehiculos con filtro**

**Dado** que el rentador está en la pantalla de búsqueda de vehículos,
**Cuando** el rentador selecciona un vehiculo de su preferencia (bicicletas, scooters, patines, etc) y presiona el botón de búsqueda,
**Entonces** el sistema debe mostrar solo la lista de todos los vehículos disponibles que selecciono.
  </td>
        <td>2</td>
    </tr>
    <tr>
        <td>US09</td>
        <td>Valoracion de los Vehículos</td>
        <td>
          
**Como** Rentador, **quiero** ver valoraciones y reseñas de otros usuarios sobre los vehículos y propietarios **para** tomar decisiones informadas.</td>
       
  <td>
    
**Escenario 1: Ver Reseñas Detalladas de los Vehículos**
**Dado** que el rentador está en la página de detalles de un vehículo,
**Cuando** hace clic en el enlace o botón para ver todas las reseñas,
**Entonces** el sistema debe mostrar una lista de todas las reseñas con texto descriptivo, calificación, y el nombre del usuario que la hizo.

  </td>
        <td>2</td>
    </tr>
    <tr>
        <td>US10</td>
        <td>Alquiler de vehiculo</td>
        <td>
          
  **Como** Rentador, **quiero** alquilar un vehículo rápidamente a través de la aplicación **para** moverme por la ciudad cuando lo necesite.</td>
        <td>**Escenario 1: Búsqueda y Selección Rápida de Vehículo**
        
**Dado** que el rentador está en la pantalla de búsqueda de vehículos,
**Cuando** ingresa la ubicación actual y selecciona un tipo de vehículo,
**Entonces** el sistema debe mostrar una lista de vehículos disponibles cerca de esa ubicación.
**Y** el rentador selecciona un vehículo de la lista para ver más detalles.


**Escenario 2: Proceso de Alquiler y Confirmación**

**Dado** que el rentador está en la página de detalles de un vehículo,
**Cuando** hace clic en el botón "Alquilar Ahora" y elige la duración del alquiler,
**Entonces** el sistema debe mostrar un resumen del alquiler, incluyendo el costo total estimado.
**Y** el rentador confirma el alquiler.
Entonces el sistema debe enviar una notificación de confirmación con los detalles de la reserva y un código de confirmación al rentador. 
        
  </td>
        <td>2</td>
    </tr>
    <tr>
        <td>US11</td>
        <td>Recomendaciones</td>
        <td>
          
**Como** Rentador, **quiero** recibir recomendaciones de vehículos basadas en mis preferencias y búsquedas anteriores **para** facilitar mi elección.
</td>
        <td>
          
**Escenario 1: Ver Recomendaciones Basadas en Preferencias**

**Dado** que el rentador está en la pantalla principal de la aplicación,
**Cuando** accede a la sección de recomendaciones personalizadas,
**Entonces** el sistema debe mostrar una lista de vehículos recomendados basados en las preferencias establecidas por el rentador (tipo de vehículo, rango de precio, ubicación).
</td>
        <td></td>
    </tr>
    <tr>
        <td>US12</td>
        <td>Recibir Notificaciones</td>
        <td>

**Como** Rentador, **quiero** recibir notificaciones cuando mi alquiler esté próximo a vencer **para** devolver el vehículo a tiempo sin penalidades.</td>
        <td>**Escenario 1: Notificación de Vencimiento Próximo de Alquiler**

**Dado** que el rentador tiene un vehículo alquilado cuya devolución es inminente,
**Cuando** faltan 30 minutos para que venza el alquiler,
**Entonces** el sistema debe enviar una notificación al rentador recordándole devolver el vehículo a tiempo para evitar penalidades.

</td>
        <td>2</td>
    </tr>
    <tr>
        <td>US13</td>
        <td>Acceso al Historial</td>
        <td>
            
**Como** Rentador, **quiero** acceder a un historial de mis alquileres anteriores **para** revisar mis actividades y gastos.</td>
<td>

**Escenario 1: Acceso y Visualización del Historial de Alquileres**

**Dado** que el rentador está en la pantalla principal de la aplicación,
**Cuando** selecciona la opción de "Historial de Alquileres" desde el menú,
**Entonces** el sistema debe mostrar una lista de todos los alquileres anteriores del rentador con detalles básicos como tipo de vehículo, fechas de alquiler, y costo total.
</td>
        <td>2</td>
    </tr>
    <tr>
        <td>US14</td>
        <td>Mapa Interactivo</td>
        <td>
            
**Como** Rentador, **quiero** utilizar un mapa interactivo **para** localizar los puntos de recogida y devolución de vehículos cercanos a mi ubicación.
</td>
        <td>
            
**Escenario 1: Visualización de Puntos de Recogida y Devolución Cercanos**

**Dado** que el rentador está en la pantalla principal de la aplicación,
**Cuando** selecciona la opción de "Mapa Interactivo",
**Entonces** el sistema debe mostrar un mapa centrado en la ubicación actual del rentador con marcadores de los puntos de recogida y devolución de vehículos cercanos.

**Escenario 2: Obtener Detalles de un Punto de Recogida**

**Dado** que el rentador está utilizando el mapa interactivo,
**Cuando** hace clic en un marcador de un punto de recogida en el mapa,
**Entonces** el sistema debe mostrar detalles adicionales sobre el punto de recogida, como la dirección, la cantidad de vehículos disponibles, y los tipos de vehículos.
</td>
        <td>2</td>
    </tr>
    <tr>
        <td>US15</td>
        <td>Pagos en Línea</td>
        <td>

**Como** Rentador, **quiero** tener la opción de pagar en línea de manera segura a través de la aplicación **para** mayor comodidad.</td>
        <td>**Escenario 1: Pago en Línea con Tarjeta de Crédito**

**Dado** que el rentador ha seleccionado un vehículo para alquilar,
**Cuando** el rentador elige la opción de pagar en línea con tarjeta de crédito y completa los campos requeridos (número de tarjeta, fecha de vencimiento, CVV),
**Entonces** el sistema debe procesar el pago de manera segura y mostrar una confirmación del pago exitoso.

**Escenario 2: Selección y Confirmación de Método de Pago**

**Dado** que el rentador está en la página de confirmación del alquiler,
**Cuando** selecciona su método de pago preferido (por ejemplo, billetera digital),
**Entonces** el sistema debe mostrar un flujo de pago correspondiente al método seleccionado y, tras la finalización del pago, debe enviar una notificación de confirmación con los detalles de la transacción.
        
</td>
        <td>2</td>
    </tr>
    <tr>
        <td>US16</td>
        <td>Contacto al propietario</td>
        <td>
        
**Como** Rentador, **quiero** poder contactar al propietario antes de alquilar un vehículo **para** aclarar dudas o detalles específicos.
</td>
        <td>Escenario 1: Enviar Mensaje al Propietario desde la Página de Detalles del Vehículo


Dado que el rentador está viendo los detalles de un vehículo que le interesa alquilar,
Cuando hace clic en el botón "Contactar al Propietario",
Entonces el sistema debe mostrar un formulario de mensaje para que el rentador escriba su pregunta o duda,
Y al enviar el mensaje, el propietario debe recibir una notificación de que ha recibido un nuevo mensaje.

Escenario 2: Recibir Respuesta del Propietario

Dado que el rentador ha enviado un mensaje al propietario desde la aplicación,
Cuando el propietario responde al mensaje del rentador,
Entonces el sistema debe enviar una notificación al rentador informándole que ha recibido una respuesta,
Y la respuesta debe aparecer en la sección de "Mensajes" o "Contacto" de la aplicación.
           
</td>
        <td>2</td>
    </tr>
    <tr>
        <td>US17</td>
        <td>visualización de Ofertas</td>
        <td>
            
**Como** Rentador, **quiero** acceder a ofertas especiales o descuentos en vehículos destacados **para** ahorrar en mis alquileres.
</td>
        <td>Escenario 1: Visualización de Vehículos con Ofertas Especiales en la Pantalla Principal

Dado que el rentador está en la pantalla principal de la aplicación,
Cuando hay vehículos destacados con ofertas especiales o descuentos disponibles,
Entonces el sistema debe mostrar estos vehículos en una sección dedicada o un banner visible, indicando claramente el porcentaje de descuento o la oferta especial.
    
</td>
        <td>2</td>
    </tr>
    <tr>
        <td>US18</td>
        <td>Tiempo de llegada</td>
        <td>
            
**Como** Rentador, **quiero** ver el tiempo estimado **para** llegar a un punto de recogida de vehículos en el mapa interactivo.</td>
        <td>**Escenario 1: Ver Tiempo Estimado en el Mapa Interactivo**

**Dado** que el rentador está en la pantalla del mapa interactivo y ha seleccionado un punto de recogida,
**Cuando** el sistema calcula el tiempo estimado para llegar desde la ubicación actual del rentador,
**Entonces** debe mostrar el tiempo estimado claramente en el mapa, junto con una indicación de la ruta sugerida.

**Escenario 2: Selección de Ruta Alternativa**

**Dado** que el rentador ha seleccionado un punto de recogida y el sistema muestra varias rutas alternativas,
**Cuando** el rentador elige una ruta alternativa,
**Entonces** el sistema debe mostrar el tiempo estimado para esa ruta y actualizar el mapa en consecuencia.
</td>
        <td>2</td>
    </tr>
    <tr>
        <td>US19</td>
        <td>Calificación de Alquiler</td>
        <td>
            
**Como** Rentador, **quiero** poder calificar al propietario después de cada alquiler **para** ayudar a otros usuarios a conocer su reputación</td>
        <td>Escenario 1: Calificación al Propietario al Finalizar el Alquiler

Dado que el alquiler ha terminado y el rentador ha devuelto el vehículo,
Cuando el rentador accede a la sección de "Historial de Alquileres" o recibe una notificación de finalización de alquiler,
Entonces debe ver una opción para calificar al propietario,
Y el rentador debe poder seleccionar una calificación en estrellas y dejar un comentario opcional.
            
</td>
        <td>2</td>
    </tr>
    <tr>
        <td>US20</td>
        <td>Extensión de tiempo de Alquiler</td>
        <td>
            
**Como Rentador**, **quiero** poder extender el tiempo de mi alquiler si necesito usar el vehículo por más tiempo del planeado.</td>
        <td>Escenario 1: Solicitud de Extensión de Alquiler

Dado que el rentador está en la sección de "Mis Alquileres" y el período de alquiler actual está próximo a finalizar,
Cuando el rentador selecciona la opción para extender el alquiler y elige el nuevo período deseado,
Entonces el sistema debe verificar la disponibilidad del vehículo y mostrar el costo adicional,
Y si el vehículo está disponible, el rentador debe confirmar la extensión y recibir una notificación de confirmación con los nuevos detalles del alquiler.

Escenario 2: Imposibilidad de Extensión

Dado que el rentador ha solicitado una extensión del alquiler,
Cuando el sistema verifica la disponibilidad del vehículo y encuentra que no está disponible para el nuevo período,
Entonces el rentador debe recibir una notificación indicando que la extensión no es posible,
Y el sistema debe proporcionar opciones alternativas si están disponibles, como otro vehículo o una nueva fecha y hora.

Escenario 3: Confirmación de Extensión del Alquiler

Dado que el rentador ha confirmado la extensión del alquiler,
Cuando el sistema actualiza el período del alquiler,
Entonces el rentador debe recibir una notificación con la confirmación de la extensión, incluyendo los nuevos detalles del período de alquiler y el costo adicional,
Y el perfil del rentador debe reflejar la nueva fecha y hora de finalización del alquiler.
            
</td>
        <td>2</td>
    </tr>
    <tr>
        <td>US21</td>
        <td>Publicación de Vehículos</td>
        <td>
            
**Como** Propietario, **quiero** publicar mis vehículos de manera rápida y sencilla **para** que los rentadores puedan verlos y contactarme.</td>
        <td>
            
</td>
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

En esta sección, presentamos el Impact Mapping para el proyecto de EcoMovil, con el objetivo de desarrollar e implementar un mapa interactivo que facilite la localización de puntos de recogida y devolución de vehículos. Este mapa es crucial para mejorar la experiencia de nuestros usuarios y alcanzar nuestros objetivos de negocio.

![ImpactMapping](/assets/sprint1/Impactmap1.png)

Este Impact Mapping proporciona una visión clara de cómo los objetivos de negocio, las necesidades de los usuarios y las funcionalidades propuestas se interrelacionan. Asegura que cada aspecto del desarrollo esté alineado con nuestras metas y contribuya al éxito del proyecto EcoMovil, mejorando tanto la experiencia de los propietarios como la de los usuarios de vehículos.

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
            <td><b>Como</b> universitario o rentador, <b>quiero</b> ver una sección de beneficios que tenga las características principales de EcoMovil, <b>para</b> entender cómo la aplicación puede mejorar mi experiencia de movilidad urbana y mi interacción con la plataforma.</td>
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
