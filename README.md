# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

Para elaborar el To-be Scenario Mapping, el equipo definió cómo sería el flujo de trabajo después de la implementación de nuestra solución, EcoMovil, para ambos segmentos objetivos. El propósito de este artefacto es comparar y abordar los aspectos negativos identificados en el As-is Scenario.

- Segmento Universitarios:

![ImpactMapping1](/assets/sprint1/TobemappingSegmento2.jpg)

- Segmento Compradores/Rentadores:

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
    
<b>**Como** universitario o comprador/rentador **quiero** visualizar una aplicación web **para** conocer los servicios de la aplicación.</td>
        <td>**Escenario 1: Visualización de la Barra de Navegación**
<br>

**Dado que** el universitario o comprador/rentador se encuentre en la landing page,
**cuando** se muestra la barra de navegación, 
**entonces** podrá visualizar diversas secciones y botones.

**Escenario 2: Funcionalidad de Navegación**

**Dado que** el universitario o comprador/rentador accede a la landing page y visualice la barra de navegación,
**cuando** hace clic en cualquiera de los enlaces de la barra de navegación,
**entonces** debe ser redirigido a la sección correspondiente de la aplicación.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>US02</td>
        <td>Sección Hero en la Landing Page</td>
        <td>**Como** universitario o comprador/rentador, **quiero** ver una sección hero atractiva y clara al acceder a la landing page **para** entender el valor de la aplicación y decidir si deseo saber más sobre ella.</td>
        <td>**Escenario 1: Visualización de la Sección Hero**

**Dado que** el universitario o comprador/rentador está en la landing page,
**cuando** la sección hero es visible,
**entonces** debe mostrar un titular principal claro y llamativo que comunique el valor de la aplicación.

**Escenario 2: Botón de “Descubre Más”**

**Dado que** el universitario o comprador/rentador está en la landing page,
**cuando** visualiza la sección hero,
**entonces** debe estar el botón “Descubre Más” que sea claramente visible.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>US03</td>
        <td>Sección Footer en la Landing Page</td>
        <td><b>**Como** universitario o comprador/rentador, **quiero** visualizar un footer en la aplicación **para** acceder rápidamente a información adicional y enlaces relevantes como redes sociales.</td>
        <td>**Escenario 1: Visualización del Footer**

**Dado que** el universitario o comprador/rentador accede a la landing page,
**cuando** la aplicación se desplaza hasta el final,
**entonces** el footer debe estar visible en la parte inferior con sus enlaces a las redes sociales.

**Escenario 2: Funcionalidad de Enlaces del Footer**

**Dado que** el universitario o comprador/rentador visualiza el footer en la landing page,
**cuando** hace clic en cualquiera de los enlaces del footer,
**entonces** debe ser redirigido a las redes sociales de la startup.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>US04</td>
        <td>Sección de Beneficios en la Landing Page</td>
        <td><b>**Como** universitario o comprador/rentador, **quiero** ver una sección de beneficios que tenga las características principales de EcoMovil, **para** entender cómo la aplicación puede mejorar mi experiencia de movilidad urbana y mi interacción con la aplicación.</td>
        <td>**Escenario 1: Visualización de la Sección de Beneficios**

**Dado que** el universitario o comprador/rentador está en la landing page,
**cuando** se desplaza hacia la sección de beneficios,
**entonces** debe ver una sección destacada que contiene al menos 2 beneficios clave de la aplicación, basados en las características principales.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>US05</td>
        <td>Sección de Contacto en la Landing Page</td>
        <td>**Como** universitario o comprador/rentador, **quiero** tener acceso a una sección de contacto clara y funcional **para** poder comunicarme con el equipo de EcoMovil **para** resolver dudas, obtener soporte o hacer sugerencias.</td>
        <td>**Escenario 1: Visualización de la Sección de Contacto**

**Dado que** el universitario o comprador/rentador está en la landing page,
**cuando** se desplaza hacia la sección de contacto,
**entonces** debe ver una sección claramente identificada que contenga información de contacto y opciones para comunicarse con el equipo de EcoMovil.

**Escenario 2: Información de Contacto**

**Dado que** el universitario o comprador/rentador está en la landing page,
**cuando** visualiza la sección de contacto,
**entonces** debe ver un formulario donde puedan ingresar su nombre, teléfono y correo electrónico para comunicarnos con el usuario a través de la aplicación.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>US06</td>
        <td>Landing Page Responsive con diferentes dispositivos</td>
        <td>**Como** universitario o comprador/rentador, **quiero** que la landing page sea responsive **para** que pueda visualizar y navegar por ella fácilmente desde cualquier dispositivo (móvil, tablet, o escritorio) sin pérdida de funcionalidad o legibilidad.</td>
        <td>**Escenario 1: Adaptación Automática a Diferentes Tamaños de Pantalla**

**Dado que** el universitario o rentador accede a la landing page,
**cuando** utiliza un dispositivo con cualquier tamaño de pantalla (móvil, tablet o escritorio),
**entonces** el contenido de la aplicación debe ajustarse automáticamente para adaptarse al tamaño de la pantalla, asegurando una presentación clara y coherente.

**Escenario 2: Navegación y Menús Responsive**

**Dado que** el visitante accede a la landing page desde un dispositivo móvil,
**cuando** la aplicación se carga completamente,
**entonces** el menú de navegación debe convertirse en un menú hamburguesa, y al hacer clic, debe desplegarse de forma fluida sin solaparse con otros elementos de la aplicación.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>US07</td>
        <td>Registro a la aplicación</td>
        <td>**Como** universitario o comprador/rentador, **quiero** registrarme en la aplicación fácilmente **para** poder acceder a vehículos en renta y/o venderlos.
</td>      <td>
  
  **Escenario 1: Registro en la aplicación EcoMovil** 
  <br>
**Dado que** el usuario está en la pantalla de registro,
**cuando** ingresa un nombre completo, correo electrónico único, una contraseña válida, y selecciona el tipo de usuario,
**entonces** el sistema debe mostrar un mensaje indicando "El registro fue exitoso." y enviar un correo de confirmación.         
</td>
        <td>1</td>
    </tr>
    <tr>
        <td>US08</td>
        <td>Búsqueda de vehículos disponibles</td>
        <td>
   
**Como** comprador/rentador, **quiero** buscar vehículos disponibles usando filtros avanzados, como tipo de vehículo, precio y ubicación, **para** encontrar el más adecuado para mis necesidades.</td>
        <td>
**Escenario 1: Búsqueda de vehículos**

**Dado** que el comprador/rentador está en la pantalla de búsqueda de vehículos,
**cuando** el comprador/rentador presiona el botón de búsqueda,
**entonces** el sistema debe mostrar una lista de todos los vehículos disponibles.

**Escenario 2: Búsqueda de vehículos con filtro**

**Dado que** el comprador/rentador está en la pantalla de búsqueda de vehículos,
**cuando** el comprador/rentador selecciona un vehículo de su preferencia (bicicletas, scooters, patines, etc.) y presiona el botón de búsqueda,
**entonces** el sistema debe mostrar solo la lista de todos los vehículos disponibles que seleccionó.
  </td>
        <td>2</td>
    </tr>
    <tr>
        <td>US09</td>
        <td>Valoración de los Vehículos</td>
        <td>
          
**Como** comprador/rentador, **quiero** ver valoraciones y reseñas de otros usuarios sobre los vehículos y universitarios **para** tomar decisiones informadas.</td>
       
  <td>
    
**Escenario 1: Ver Reseñas Detalladas de los Vehículos**
<br>

**Dado** que el comprador/rentador está en la aplicación de detalles de un vehículo,
**cuando** hace clic en el enlace o botón para ver todas las reseñas,
**entonces** el sistema debe mostrar una lista de todas las reseñas con texto descriptivo, calificación, y el nombre del usuario que realizó.

  </td>
        <td>2</td>
    </tr>
    <tr>
        <td>US10</td>
        <td>Alquiler de vehículo</td>
        <td>
          
  **Como** comprador/rentador, **quiero** rentar o comprar un vehículo rápidamente a través de la aplicación **para** moverme por la ciudad cuando lo necesite.</td>
        <td>**Escenario 1: Búsqueda y Selección Rápida de Vehículo**
        
**Dado** que el comprador/rentador está en la pantalla de búsqueda de vehículos,
**cuando** ingresa la ubicación actual y selecciona un tipo de vehículo,
**entonces** el sistema debe mostrar una lista de vehículos disponibles cerca de esa ubicación.
**Y** el rentador selecciona un vehículo de la lista para ver más detalles.


**Escenario 2: Proceso de Alquiler y Confirmación**

**Dado** que el rentador está en la página de detalles de un vehículo,
**cuando** hace clic en el botón "Rentar ahora" y elige la duración del alquiler,
**Entonces** el sistema debe mostrar un resumen del alquiler, incluyendo el costo total estimado.
**Y** el rentador confirma el alquiler.
Entonces el sistema debe enviar una notificación de confirmación con los detalles de la reserva. 
        
  </td>
        <td>2</td>
    </tr>
    <tr>
        <td>US11</td>
        <td>Recomendaciones</td>
        <td>
          
**Como** comprador/rentador, **quiero** recibir recomendaciones de vehículos basadas en mis preferencias y búsquedas anteriores **para** facilitar mi elección.
</td>
        <td>
          
**Escenario 1: Ver Recomendaciones Basadas en Preferencias**

**Dado** que el comprador/rentador está en la pantalla principal de la aplicación,
**cuando** accede a la sección de recomendaciones personalizadas,
**entonces** el sistema debe mostrar una lista de vehículos recomendados basados en las preferencias establecidas por el comprador/rentador. (tipo de vehículo, rango de precio, ubicación)
</td>
        <td></td>
    </tr>
    <tr>
        <td>US12</td>
        <td>Recibir Notificaciones</td>
        <td>

**Como** rentador, **quiero** recibir notificaciones cuando mi alquiler esté próximo a vencer **para** devolver el vehículo a tiempo sin penalidades.</td>
        <td>**Escenario 1: Notificación de Vencimiento Próximo de Alquiler**

**Dado** que el rentador tiene un vehículo alquilado cuya devolución es inminente,
**cuando** faltan 30 minutos para que venza el alquiler,
**entonces** el sistema debe enviar una notificación al rentador recordándole devolver el vehículo a tiempo para evitar penalidades.

</td>
        <td>2</td>
    </tr>
    <tr>
        <td>US13</td>
        <td>Acceso al Historial</td>
        <td>
            
**Como** Rentador, **quiero** acceder a un historial de mis rentas anteriores **para** revisar mis actividades y gastos.</td>
<td>

**Escenario 1: Acceso y Visualización del Historial de Alquileres**

**Dado** que el rentador está en la pantalla principal de la aplicación,
**cuando** selecciona la opción de "Historial de Alquileres",
**entonces** el sistema debe mostrar una lista de todos los alquileres anteriores del rentador con detalles básicos como tipo de vehículo, fechas de alquiler, y costo total.
</td>
        <td>2</td>
    </tr>
    <tr>
        <td>US14</td>
        <td>Mapa Interactivo</td>
        <td>
            
**Como** comprador/rentador, **quiero** utilizar un mapa interactivo **para** localizar los puntos de vehículos cercanos a mi ubicación.
</td>
        <td>
            
**Escenario 1: Visualización de Puntos de Recogida y Devolución Cercanos**

**Dado** que el comprador/rentador está en la pantalla principal de la aplicación,
**cuando** selecciona la opción de "Mapa Interactivo",
**entonces** el sistema debe mostrar un mapa centrado en la ubicación actual del rentador con marcadores de los puntos de recogida y devolución de vehículos cercanos.

**Escenario 2: Obtener Detalles de un Punto de Recogida**

**Dado que** el comprador/rentador está utilizando el mapa interactivo,
**cuando** hace clic en un marcador de un punto de recogida en el mapa,
**entonces** el sistema debe mostrar detalles adicionales.
</td>
        <td>2</td>
    </tr>
    <tr>
        <td>US15</td>
        <td>Pagos en Línea</td>
        <td>

**Como** comprador/rentador **quiero** tener la opción de pagar en línea de manera segura a través de la aplicación **para** mayor comodidad.</td>
        <td>**Escenario 1: Pago en Línea con Tarjeta**

**Dado** que el comprador/rentador ha seleccionado un vehículo para alquilar,
**cuando** el comprador/rentador elige la opción de pagar en línea con tarjeta y completa los campos requeridos (número de tarjeta, fecha de vencimiento, CVV),
**entonces** el sistema debe procesar el pago de manera segura y mostrar una confirmación del pago exitoso.

**Escenario 2: Selección y Confirmación de Método de Pago**

**Dado que** el comprador/rentador está en la aplicación de confirmación del alquiler,
**cuando** selecciona su método de pago,
**entonces** el sistema debe mostrar un flujo de pago correspondiente al método seleccionado y, tras la finalización del pago, debe enviar una notificación de confirmación con los detalles de la transacción.
        
</td>
        <td>2</td>
    </tr>
    <tr>
        <td>US16</td>
        <td>Calificación de compra o alquiler</td>
        <td>
            
**Como** comprador/rentador, **quiero** poder calificar al propietario después de cada compra o alquiler **para** ayudar a otros usuarios a conocer su reputación.</td>
        <td>**Escenario 1: Calificación al Propietario al Finalizar la compra o alquiler**

**Dado que** la compra o alquiler ha terminado y el rentador o comprador ha devuelto el vehículo,
**cuando** el comprador/rentador accede a la sección de "Historial de Alquileres o Compras" o recibe una notificación de finalización de alquiler o compra,
**entonces** debe ver una opción para calificar al propietario,
**y** el rentador debe poder seleccionar una calificación en estrellas y dejar un comentario opcional.
            
</td>
        <td>2</td>
    </tr>
    <tr>
        <td>US17</td>
        <td>Publicación de Vehículos</td>
        <td>
            
**Como** propietario, **quiero** publicar mis vehículos de manera rápida y sencilla **para** que los compradores/rentadores puedan verlos y logren contactarme.</td>
        <td>**Escenario 1: Publicación Rápida del Vehículo**

**Dado** que el propietario está en la sección "Mis Vehículos" de la aplicación,
**Cuando** hace clic en el botón "Publicar Nuevo Vehículo",
Y completa los campos obligatorios del formulario de publicación (tipo de vehículo, marca, modelo, año, precio de alquiler, disponibilidad),
**Entonces** debe poder subir imágenes del vehículo,
Y revisar toda la información antes de publicar.
            
</td>

 <br/>
        <td>3</td>
    </tr>
    <tr>
        <td>US18</td>
        <td>Historial de Alquiler y Venta</td>
        <td>Como propietario, quiero acceder a un historial de mis alquileres y ventas para llevar un control detallado de mis ingresos.
</td>
        <td>
            
**Escenario 1: Visualización del Historial de Transacciones**

**Dado** que el propietario está en el panel principal de la aplicación,
**Cuando** selecciona la opción de "Historial de Transacciones",
**Entonces** debe poder ver una lista detallada de todas sus transacciones de alquileres y ventas,
Y cada transacción debe mostrar información como fecha, tipo de transacción, vehículo y monto recibido.

     
</td>
        <td>3</td>
    </tr>
    <tr>
        <td>US19</td>
        <td>PerSonalizar Publicaciones</td>
        <td>
            
**Como** propietario, **quiero** personalizar la descripción y las fotos de mis publicaciones para hacerlas más atractivas a los rentadores</td>
        <td>**Escenario 1: Edición de la Descripción de una Publicación**

**Dado** que el propietario desea mejorar la presentación de su vehículo,
**Cuando** accede a la sección "Mis vehículos" y selecciona una publicación específica,
**Entonces** debe poder editar la descripción del vehículo utilizando texto enriquecido,
Y después de realizar los cambios, debe poder guardar la descripción actualizada.

**Escenario 2: Subida y Organización de Fotos**

**Dado** que el propietario quiere actualizar las fotos de su vehículo para hacerlo más atractivo,
**Cuando** selecciona la opción para editar una publicación,
**Entonces** debe poder subir nuevas fotos desde su dispositivo,
Y después de realizar los cambios, debe poder guardar la nueva configuración de fotos.

**Escenario 3: Confirmación y Publicación de Cambios**

**Dado** que el propietario está satisfecho con los cambios realizados en la descripción y fotos de su publicación,
**Cuando** selecciona la opción de "Confirmar",
**Entonces** los cambios deben reflejarse inmediatamente en la plataforma para los compradores/rentadores,
Y cualquier comprador/rentador interesado debe recibir una notificación de que la publicación ha sido actualizada.
            
 <td>3</td>
    </tr>
</table>

## 3.3. Impact Mapping

En esta sección, presentamos el **Impact Mapping** para el proyecto de **EcoMovil**, cuyo objetivo es desarrollar e implementar un mapa interactivo que facilite la localización. Este mapa es esencial para optimizar la experiencia de nuestros usuarios y alcanzar los objetivos comerciales.

El **Impact Mapping** ofrece una visión clara de cómo los objetivos de negocio, las necesidades de los usuarios y las funcionalidades propuestas se interconectan. Asegura que cada elemento del desarrollo esté alineado con nuestras metas, contribuyendo al éxito de **EcoMovil** y mejorando tanto la experiencia de los universitarios como la de los compradores/rentadores.

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
            <td><b>Como</b> universitario o commprador/rentador <b>quiero</b> visualizar una aplicación web <b>para</b> conocer los servicios de la aplicación</td>
            <td>3</td>
        </tr>
        <tr>
            <td>2</td>
            <td>US02</td>
            <td>Sección Hero en la Landing Page</td>
            <td><b>Como</b> universitario o comprador/rentador, <b>quiero</b> ver una sección hero atractiva y clara al acceder a la Landing Page <b>para</b> entender el valor de la aplicación y decidir si deseo saber más sobre ella.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>3</td>
            <td>US03</td>
            <td>Sección Footer en la Landing Page</td>
            <td><b>Como</b> universitario o comprador/rentador, <b>quiero</b> visualizar un footer en la aplicación web <b>para</b> acceder rápidamente a información adicional y enlaces relevantes como redes sociales.</td>
            <td>2</td>
        </tr>
        <tr>
            <td>4</td>
            <td>US04</td>
            <td>Sección de Beneficios en la Landing Page</td>
            <td><b>Como</b> universitario o comprador/rentador, <b>quiero</b> ver una sección de beneficios que tenga las características principales de EcoMovil, <b>para</b> entender cómo la aplicación puede mejorar mi experiencia de movilidad urbana y mi interacción con la aplicación.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>5</td>
            <td>US05</td>
            <td>Sección de Contacto en la Landing Page</td>
            <td><b>Como</b> universitario o comprador/rentador, <b>quiero</b> tener acceso a una sección de contacto clara y funcional <b>para</b> poder comunicarme con el equipo de EcoMovil para resolver dudas, obtener soporte o hacer sugerencias.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>6</td>
            <td>US06</td>
            <td>Landing Page Responsive con diferentes dispositivos</td>
            <td><b>Como</b> universitario o comprador/rentador, <b>quiero</b> que la landing page sea responsive <b>para</b> que pueda visualizar y navegar por ella fácilmente desde cualquier dispositivo (móvil, tablet, o escritorio) sin pérdida de funcionalidad o legibilidad.</td>
            <td>8</td>
        </tr>
    </tbody>
</table>
<br>

[![Sprint1](/assets/sprint1/sprint1.png)](https://trello.com/invite/b/661b0a12e3392a7cd56479b3/ATTIe08b35a362a9b35b5e0152e660a454e79586C6AA/ecomovil-product-backlog-tb1 )

Enlace del Product Backlog: https://trello.com/invite/b/661b0a12e3392a7cd56479b3/ATTIe08b35a362a9b35b5e0152e660a454e79586C6AA/ecomovil-product-backlog-tb1 
