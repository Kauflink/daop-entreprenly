# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

En esta sección se detallan las herramientas, frameworks y plataformas utilizadas por el equipo para el desarrollo colaborativo durante todo el ciclo de vida del producto digital. Se han considerado actividades de Project Management, Requirements Management, UX/UI Design, Software Development, Documentation y Deployment.

Para que el código funcione correctamente dentro de un archivo .md (como en GitHub o Notion), lo mejor es evitar las etiquetas <html> o <body> y usar directamente los fragmentos de las tablas. Los renderizadores de Markdown aplicarán automáticamente sus propios estilos para que se vea integrado.

Aquí tienes el código limpio, dividido por secciones:

**Project Management**

<table>
  <thead>
    <tr>
      <th>Producto</th>
      <th>Propósito de uso</th>
      <th>Ruta de Referencia / Descarga</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Jira</strong></td>
      <td>Herramienta principal para la gestión del proyecto, administración del Product Backlog y seguimiento de Sprints bajo metodología ágil.</td>
      <td><a href="https://www.atlassian.com/software/jira">https://www.atlassian.com/software/jira</a></td>
    </tr>
  </tbody>
</table>

**Requirements Management**

<table>
  <thead>
    <tr>
      <th>Producto</th>
      <th>Propósito de uso</th>
      <th>Ruta de Referencia / Descarga</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>UXPressia</strong></td>
      <td>Utilizado para la gestión de requerimientos, específicamente para la creación de User Personas, Empathy Maps e Impact Maps.</td>
      <td><a href="https://uxpressia.com/">https://uxpressia.com/</a></td>
    </tr>
  </tbody>
</table>

**Product UX/UI Design**

<table>
  <thead>
    <tr>
      <th>Producto</th>
      <th>Propósito de uso</th>
      <th>Ruta de Referencia / Descarga</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Figma</strong></td>
      <td>Herramienta de diseño UX/UI para la elaboración de Wireframes, Mock-ups y Prototipos interactivos.</td>
      <td><a href="https://www.figma.com/">https://www.figma.com/</a></td>
    </tr>
    <tr>
      <td><strong>Miro</strong></td>
      <td>Plataforma de colaboración visual empleada en las sesiones de EventStorming (Big Picture y Design-Level) para el modelado del dominio.</td>
      <td><a href="https://miro.com/">https://miro.com/</a></td>
    </tr>
  </tbody>
</table>

**Software Development**

<table>
  <thead>
    <tr>
      <th>Producto</th>
      <th>Propósito de uso</th>
      <th>Ruta de Referencia / Descarga</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Structurizr</strong></td>
      <td>Herramienta para el diseño y documentación de la arquitectura de software siguiendo el modelo C4 (Context, Container, Component, Code).</td>
      <td><a href="https://structurizr.com/">https://structurizr.com/</a></td>
    </tr>
    <tr>
      <td><strong>MySQL Workbench</strong></td>
      <td>Utilizado para el diseño de base de datos, permitiendo la creación de diagramas entidad-relación y la gestión de la persistencia de datos.</td>
      <td><a href="https://www.mysql.com/products/workbench/">https://www.mysql.com/products/workbench/</a></td>
    </tr>
    <tr>
      <td><strong>Visual Studio Code</strong></td>
      <td>Entorno de desarrollo (IDE) principal para la implementación de la Landing Page y la aplicación Frontend.</td>
      <td><a href="https://code.visualstudio.com/">https://code.visualstudio.com/</a></td>
    </tr>
    <tr>
      <td><strong>GitHub Desktop</strong></td>
      <td>Cliente de Git utilizado para facilitar el Source Code Management y la implementación del flujo de trabajo GitFlow en el equipo.</td>
      <td><a href="https://desktop.github.com/">https://desktop.github.com/</a></td>
    </tr>
    <tr>
      <td><strong>Spring Boot / Java</strong></td>
      <td>Framework y lenguaje principal para el desarrollo de los RESTful Web Services que conforman el Backend de la aplicación.</td>
      <td><a href="https://spring.io/projects/spring-boot">https://spring.io/projects/spring-boot</a></td>
    </tr>
    <tr>
      <td><strong>Angular / TypeScript</strong></td>
      <td>Framework y lenguaje utilizados para la construcción de la Frontend Web Application de la plataforma.</td>
      <td><a href="https://angular.io/">https://angular.io/</a></td>
    </tr>
    <tr>
      <td><strong>Node.js</strong></td>
      <td>Entorno de ejecución JavaScript requerido para ejecutar Angular CLI y las herramientas de build y gestión de dependencias del Frontend.</td>
      <td><a href="https://nodejs.org/">https://nodejs.org/</a></td>
    </tr>
  </tbody>
</table>

**Software Documentation**

<table>
  <thead>
    <tr>
      <th>Producto</th>
      <th>Propósito de uso</th>
      <th>Ruta de Referencia / Descarga</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Swagger / OpenAPI</strong></td>
      <td>Empleado para la documentación técnica de los endpoints del RESTful API, permitiendo su exploración y prueba interactiva.</td>
      <td><a href="https://swagger.io/">https://swagger.io/</a></td>
    </tr>
    <tr>
      <td><strong>Markdown</strong></td>
      <td>Lenguaje de marcado utilizado para la elaboración y mantenimiento de la documentación general del proyecto alojada en GitHub.</td>
      <td><a href="https://www.markdownguide.org/">https://www.markdownguide.org/</a></td>
    </tr>
  </tbody>
</table>

**Software Deployment**

<table>
  <thead>
    <tr>
      <th>Producto</th>
      <th>Propósito de uso</th>
      <th>Ruta de Referencia / Descarga</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Google Cloud Platform</strong></td>
      <td>Proveedor de infraestructura cloud utilizado para el despliegue y hospedaje de los servicios Backend y aplicaciones en producción.</td>
      <td><a href="https://cloud.google.com/">https://cloud.google.com/</a></td>
    </tr>
    <tr>
      <td><strong>GitHub Pages</strong></td>
      <td>Servicio de hosting estático utilizado para el despliegue continuo de la Landing Page del producto.</td>
      <td><a href="https://pages.github.com/">https://pages.github.com/</a></td>
    </tr>
  </tbody>
</table>

### 5.1.2. Source Code Management

Para la gestión del código fuente y el seguimiento de modificaciones, el equipo utiliza GitHub como plataforma principal y Git como sistema de control de versiones distribuido. Se han establecido repositorios independientes para cada producto de la solución, asegurando que el repositorio de Web Services incluya tanto el proyecto como los archivos de pruebas unitarias, de integración y de aceptación.

**Repositorios del Proyecto**

| Producto | URL del Repositorio |
| :--- | :--- |
| **Landing Page** | https://github.com/Kauflink/landing-entreprenly |
| **Web Services** | https://github.com/Kauflink/daop-entreprenly-web-services | 
| **Frontend Web Application** | https://github.com/Kauflink/daop-entreprenly-web-applications |

**Estrategia de Flujo de Trabajo: GitFlow**

El equipo implementa el modelo GitFlow como workflow de control de versiones para organizar el desarrollo colaborativo de forma estructurada. Este flujo permite trabajar en múltiples funcionalidades en paralelo sin afectar la estabilidad de la rama principal.

Se han definido las siguientes ramas fundamentales:

- **main**: Es la rama principal que contiene el código fuente en estado de producción. Cada versión integrada aquí debe estar etiquetada con un número de versión.

- **develop**: Rama base para el desarrollo donde se integran todas las funcionalidades completadas para pruebas antes de un lanzamiento.

- **feature**: Ramas temporales creadas para desarrollar nuevas funcionalidades o historias de usuario específicas.

- **release**: Ramas utilizadas para preparar un nuevo lanzamiento oficial, permitiendo realizar ajustes menores y correcciones de errores finales.

- **hotfix**: Ramas de emergencia creadas directamente desde main para solucionar errores críticos detectados en el entorno de producción.

**Convenciones de Nombres para Ramas**

Para mantener la trazabilidad y el orden en los repositorios, se aplican las siguientes convenciones de nomenclatura:

- **Feature Branches**: feature/US-[ID-Historia]-[Nombre]
- **Release Branches**: release/v[Major.Minor.Patch]
- **Hotfix Branches**: hotfix/[Descripcion-Error]

**Versionamiento Semántico**

El equipo adopta el estándar Semantic Versioning 2.0.0 para el nombramiento de los lanzamientos. Las versiones se estructuran siguiendo el formato MAJOR.MINOR.PATCH:

1. MAJOR: Incrementado cuando se realizan cambios incompatibles en la API.
2. MINOR: Incrementado cuando se añade funcionalidad de manera retrocompatible.
3. PATCH: Incrementado cuando se realizan correcciones de errores retrocompatibles.

**Estándar de Mensajes de Commit**

Para asegurar un historial de cambios legible y facilitar la automatización, se utiliza la especificación de Conventional Commits para todos los mensajes de commit. La estructura utilizada es [tipo]:[descripción breve], empleando los siguientes prefijos:

- feat: Incorporación de una nueva funcionalidad.
- fix: Corrección de un error o bug.
- docs: Modificaciones exclusivamente en la documentación.
- style: Cambios de formato o estética que no afectan la lógica del código.
- refactor: Reestructuración de código que no añade funciones ni corrige errores.
- test: Adición o actualización de pruebas

### 5.1.3. Source Code Style Guide & Conventions

En esta sección se establecen las guías de estilo y convenciones de codificación adoptadas por el equipo de Kauflink para el desarrollo de los productos digitales que conforman la solución **Entreprenly**. El objetivo es garantizar que el código fuente sea legible, mantenible y coherente entre todos los miembros del equipo, independientemente del componente o capa de la arquitectura en la que se trabaje. Como regla general, **toda nomenclatura de elementos en el código fuente se redacta en inglés**, incluyendo nombres de variables, clases, métodos, componentes, atributos y comentarios técnicos.

Las referencias adoptadas para cada lenguaje y tecnología utilizada en la solución se detallan a continuación.

#### HTML

Para el desarrollo del Landing Page de Entreprenly, el equipo adopta como referencia principal la **HTML Style Guide and Coding Conventions** de W3Schools y la **Google HTML/CSS Style Guide**.

Las convenciones aplicadas son las siguientes:

- Se utiliza **HTML5** como estándar de marcado, declarando siempre el `DOCTYPE` al inicio del documento: `<!DOCTYPE html>`.
- Los nombres de los elementos y atributos se escriben en **minúsculas** (`<section>`, `<article>`, `class="hero-section"`).
- Los atributos se encierran siempre entre **comillas dobles**: `<img src="logo.png" alt="Entreprenly logo">`.
- Se incluyen los atributos `lang` en la etiqueta `<html>` para indicar el idioma de la página: `<html lang="en">`.
- Todas las imágenes incluyen el atributo `alt` con una descripción significativa, como parte del enfoque de accesibilidad (a11y) del proyecto.
- Se utiliza **indentación de 2 espacios** para mantener la legibilidad del árbol de elementos.
- Los elementos de bloque se escriben en líneas separadas; los elementos en línea pueden mantenerse en una misma línea si el resultado es conciso.
- Se evita el uso de estilos en línea (`style=""`); todo el estilo visual se delega a las hojas de estilo CSS externas o a las clases de Angular Material.
- Los comentarios se utilizan para delimitar secciones principales del documento: `<!-- Hero Section -->`.

#### CSS

Para el estilo visual del Landing Page de Entreprenly, el equipo adopta la **Google HTML/CSS Style Guide** como guía de referencia, complementada con las convenciones del sistema de diseño basado en **Material Design**.

Las convenciones aplicadas son las siguientes:

- Los nombres de clases se escriben en **kebab-case**: `.hero-section`, `.cta-button`, `.nav-link`.
- Se evita el uso de selectores de ID para estilos; se prefieren selectores de clase por su reutilizabilidad.
- Las propiedades dentro de cada regla se ordenan de forma **alfabética** para facilitar la lectura y comparación entre reglas.
- Se utiliza **indentación de 2 espacios**.
- Se evita el uso de `!important`; en su lugar, se gestionan las especificidades de los selectores de forma explícita.
- Las unidades `rem` y `em` se prefieren sobre `px` para valores de tipografía y espaciado, garantizando escalabilidad y accesibilidad.
- Los colores se definen usando variables CSS (`--primary-color: #1A73E8;`) centralizadas en el bloque `:root` para mantener la consistencia con el Design System.
- Cada archivo CSS tiene un alcance definido y no acumula estilos globales innecesarios.

#### JavaScript

El Landing Page de Entreprenly utiliza JavaScript para comportamientos de interacción básicos. El equipo adopta las convenciones establecidas en la **Google HTML/CSS Style Guide** para los aspectos de scripting complementarios al marcado.

Las convenciones aplicadas son las siguientes:

- Se utiliza `const` para valores que no cambian y `let` para valores que pueden reasignarse; se evita el uso de `var`.
- Los nombres de variables y funciones se escriben en **camelCase**: `getUserData`, `handleButtonClick`.
- Las funciones se declaran como **arrow functions** cuando no requieren su propio contexto `this`: `const fetchData = () => { ... }`.
- Los strings se definen usando **template literals** cuando se requiere interpolación: `` `Hello, ${userName}` ``.
- El código se organiza en funciones con una única responsabilidad, evitando bloques de lógica demasiado extensos.
- Se incluyen comentarios descriptivos en funciones no triviales, explicando el propósito y no el mecanismo.

#### TypeScript

Para el desarrollo del Frontend Web Application de Entreprenly con Angular, el equipo adopta la **Google TypeScript Style Guide** como referencia principal.

Las convenciones aplicadas son las siguientes:

- Los nombres de **clases, interfaces y enumeraciones** se escriben en **PascalCase**: `UserProfile`, `AuthService`, `PaymentStatus`.
- Los nombres de **variables, funciones y métodos** se escriben en **camelCase**: `isLoggedIn`, `fetchUserData()`.
- Los nombres de **constantes globales** se escriben en **UPPER_SNAKE_CASE**: `MAX_RETRY_ATTEMPTS`.
- Los nombres de **archivos** de componentes, servicios y módulos de Angular siguen la convención **kebab-case** con sufijo descriptivo: `user-profile.component.ts`, `auth.service.ts`, `app-routing.module.ts`.
- Se declaran **tipos explícitos** para todos los parámetros de funciones y valores de retorno; se evita el uso de `any`.
- Se utilizan **interfaces** para describir la forma de los objetos del dominio: `interface Entrepreneur { id: number; name: string; }`.
- Se prefiere el uso de **Observables** de RxJS sobre Promises para el manejo de operaciones asíncronas, coherente con el modelo reactivo de Angular.
- Se habilita el modo estricto de TypeScript (`"strict": true`) en el `tsconfig.json` del proyecto.
- Las importaciones se organizan en bloques separados: primero módulos de Angular, luego librerías de terceros y finalmente módulos internos del proyecto.

#### Angular Framework

Además de las convenciones de TypeScript, el equipo adopta la **Angular Coding Style Guide** oficial para la organización y estructura de los componentes, servicios y módulos de la aplicación.

Las convenciones aplicadas son las siguientes:

- Cada componente, servicio o módulo reside en **su propio archivo**, siguiendo el principio de una clase por archivo.
- Los nombres de **componentes** siguen el patrón `[Feature]Component`: `DashboardComponent`, `ProjectCardComponent`.
- Los nombres de **servicios** siguen el patrón `[Feature]Service`: `AuthService`, `ProjectService`.
- Los **selectores** de los componentes se escriben en **kebab-case** con un prefijo único del proyecto (`ep-` por Entreprenly): `ep-project-card`, `ep-navbar`.
- Los **módulos** de funcionalidad se organizan por bounded context o feature, evitando un único módulo monolítico.
- Los métodos del ciclo de vida de Angular (`ngOnInit`, `ngOnDestroy`) se implementan a través de sus interfaces correspondientes (`OnInit`, `OnDestroy`).

#### Java y Spring Boot

Para el desarrollo de los RESTful Web Services de Entreprenly, el equipo adopta la **Google Java Style Guide** y las convenciones de **Spring Boot Features** como referencias principales.

Las convenciones aplicadas son las siguientes:

- Los nombres de **clases** se escriben en **PascalCase**: `ProjectController`, `UserRepository`, `AuthenticationService`.
- Los nombres de **métodos y variables** se escriben en **camelCase**: `findProjectById()`, `currentUser`.
- Los nombres de **constantes** se escriben en **UPPER_SNAKE_CASE**: `DEFAULT_PAGE_SIZE`.
- Los nombres de **paquetes** se escriben en **minúsculas** y se organizan por bounded context, siguiendo la estructura: `com.kauflink.entreprenly.[boundedcontext].[layer]`. Por ejemplo: `com.kauflink.entreprenly.projects.interfaces`, `com.kauflink.entreprenly.auth.domain`.
- La arquitectura interna de cada bounded context sigue el patrón de capas: `interfaces` (controllers), `application` (services, command handlers), `domain` (entities, value objects, repositories interfaces) e `infrastructure` (JPA repositories, external adapters).
- Los **endpoints** de los controladores REST se nombran en **kebab-case** y en plural para recursos: `/api/v1/projects`, `/api/v1/users`.
- Los **métodos HTTP** se emplean de acuerdo con su semántica RESTful: `GET` para consultas, `POST` para creación, `PUT` para actualización completa, `PATCH` para actualización parcial y `DELETE` para eliminación.
- Se utilizan **anotaciones estándar** de Spring Boot: `@RestController`, `@Service`, `@Repository`, `@Entity`, `@Value`, entre otras.
- Se aplica **indentación de 4 espacios** de acuerdo con la Google Java Style Guide.
- Los **comentarios Javadoc** se incluyen en todas las clases públicas y en los métodos cuya lógica no sea autoexplicativa.


#### Gherkin (Acceptance Criteria)

Para la redacción de los criterios de aceptación de las User Stories y los escenarios de prueba de aceptación de los RESTful Web Services, el equipo adopta las **Gherkin Conventions for Readable Specifications**.

Las convenciones aplicadas son las siguientes:

- Cada escenario se redacta en inglés, en **tiempo presente y tercera persona**.
- La estructura `Given – When – Then` se respeta estrictamente: `Given` define el contexto inicial, `When` describe la acción del usuario o del sistema y `Then` especifica el resultado esperado.
- Se utiliza `And` para añadir condiciones adicionales dentro de un mismo bloque, evitando repetir la palabra clave principal.
- Los nombres de los escenarios son descriptivos y comunican el comportamiento esperado sin referirse a detalles de implementación.
- Se evita la lógica condicional dentro de un mismo escenario; cada escenario cubre un único camino de ejecución (happy path o unhappy path).

**Ejemplo de escenario para un endpoint de la API:**

```gherkin
Scenario: Developer retrieves an existing project successfully
  Given a project with id 1 exists in the system
  When the developer sends a GET request to "/api/v1/projects/1"
  Then the response status code should be 200
  And the response body should contain the project details
```

### 5.1.4. Software Deployment Configuration

*Contenido por agregar.*

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

*Contenido por agregar.*

#### 5.2.1.2. Aspect Leaders and Collaborators

*Contenido por agregar.*

#### 5.2.1.3. Sprint Backlog 1

*Contenido por agregar.*

#### 5.2.1.4. Development Evidence for Sprint Review

*Contenido por agregar.*

#### 5.2.1.5. Execution Evidence for Sprint Review

*Contenido por agregar.*

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

*Contenido por agregar.*

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

*Contenido por agregar.*

#### 5.2.1.8. Team Collaboration Insights during Sprint

*Contenido por agregar.*

## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

*Contenido por agregar.*

### 5.3.2. Registro de Entrevistas

*Contenido por agregar.*

### 5.3.3. Evaluaciones según heurísticas

*Contenido por agregar.*

## 5.4. Video About-the-Product

*Contenido por agregar.*