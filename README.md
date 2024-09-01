# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

### 5.1.2. Source Code Management

### 5.1.3. Source Code Style Guide & Conventions

En Ecomovil hemos optado varias convenciones de estilos para el desarrollo de código en diferentes lenguajes.

#### Tecnologías usadas

*HTML y CSS (Google HTLM/CSS Style Guide)*
- Se declara el tipo de documento al principio del archivo con !DOCTYPE html.
- Se incluyen los meta tags pertinentes.
- El elemento title se coloca dentro de las etiquetas head.
- Se utiliza una indentación de dos espacios.
- Se emplean minúsculas para los elementos HTML, atributos, propiedades, valores y selectores CSS.
- Los atributos de los elementos HTML se encierran entre comillas.
- Cada elemento HTML debe tener su etiqueta de cierre.
- Se evitan líneas de código excesivamente largas.
- Se especifica el ancho y alto de las imágenes, junto con un texto alternativo (alt).

*TypeScript*
- Uso de Clases e interfaces
- Uso de Comentarios
- Control de Flujos
- Uso de nombres descriptivos

*Gherkin (Gherkin Conventions for Readable Specifications)
- Se emplean las palabras "Given", "When", "Then" y "And" para describir los pasos del escenario.
- Los pasos que comienzan con "And" se indentan.
- Se añaden líneas en blanco entre pasos.
- Los parámetros se encierran entre comillas simples.
- Se utiliza un comentario separador y dos líneas en blanco entre cada escenario.

*Java*
- Uso de Clases, Métodos y Variables
- Uso de programacion funcional
- Convenciones con clases

*Angular*
- Los nombres deben de seguir la convención PascalCase
- Cada componente, servicio y clase debe estar en su propio archivo
- Utilización de plantillas y hojas de estilo en archivos separados.
- Uso de Decoradores como @Componente, @Injectable e @Input.
- Inyección de Dependencias para gestioanr servicios
- Convenciones de codigo con nombres que describan claramente su propósito.



### 5.1.4. Software Deployment Configuration
En esta sección, abordaremos el despliegue de nuestra Landing Page mediante el servicio automatizado en GitHub Pages. A continuación, se describirán los pasos que se realizaron para lograr este objetivo.

- Primeramente, es indispensable verificar que el repositorio este configurado correctamente.
![Merged-Picture](./assets/perfil/merged1.png)

- Debido a que en este caso se creo un Landing Page con angular se ha optado por hacer uso de la herramienta angular-cli-pages, esta ayudará a actualizar la página y llevarla a github pages.
![Angular-Cli](./assets/perfil/angular-cli.png)

- Luego de esto debemos de crear una carpeta dist la cual contendrá todos los archivos necesarios para el despliegue.
![Dist](./assets/perfil/dist.png)

- Después de, esto hacemos uso de ngh para que se cree una nueva rama que contendrá los archivos para el despliegue, esta rama se llamara gh-pages nombrada asi por la herramienta anteriormente mencionada.
![gh-pages](./assets/perfil/gh.png)

- Finalmente una vez todos los archivos hayan sido publicados en una rama, en el apartado de "Settings" en "Pages" en la sección de Branch colocamos gh-pages y /(root), al guardar y esperar un momento podremos ver la página publicada.
![publish](./assets/perfil/publish.png)

- De esta manera se visualizaría asi la página.
![page](./assets/perfil/page.png)

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

### 5.2.1.1. Sprint Planning 1

### 5.2.1.2. Sprint Backlog 1

### 5.2.1.3. Development Evidence for Sprint Review

### 5.2.1.4. Testing Suite Evidence for Sprint Review

### 5.2.1.5. Execution Evidence for Sprint Review

### 5.2.1.6. Services Documentation Evidence for Sprint Review

### 5.2.1.7. Software Deployment Evidence for Sprint Review

### 5.2.1.8. Team Collaboration Insights during Sprint
