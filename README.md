## Universidad Peruana de Ciencias Aplicadas - Informe de Trabajo Final

![Logo UPC](https://github.com/Grupo5-AppWeb/Informe/blob/Garayar-U202014115/resources/upc-logo.png "Logo UPC")

## Aplicaciones Web - SW52

### Integrantes:
- Holguin Gamarra, Hardie Alfonso - U202220250
- Huapaya Cuevas, Anthony Martin - U202220235
- Belahonia Miranda, Fabrisio Andre - U202220219
- Marzál Pérez, Jamir Ángel - U201824409
- Arce Huaman Luis Andres - U20201A300
- Garayar Mori, Oscar Nathaniel - U202014115



### Tabla de Contenidos

- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint n](#521-sprint-n)
      - [5.2.1.1. Sprint Planning n](#5211-sprint-planning-n)
      - [5.2.1.2. Sprint Backlog n](#5212-sprint-backlog-n)
      - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
      - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)




### Registro de Versiones del Informe



### Student Outcome



## Capítulo I: Introducción


### 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

#### RestauMaster: Simplificando la Operación de Restaurantes

RestauMaster es una startup que busca transformar la manera en que los restaurantes gestionan sus operaciones diarias. Nos especializamos en ofrecer una plataforma integral que conecta todas las áreas clave de un restaurante, desde la gestión de mesas y reservas hasta la administración de cocina, ventas, y stock. Nuestro objetivo es automatizar y optimizar procesos operativos para mejorar la eficiencia y la experiencia del cliente. En RestauMaster, estamos comprometidos con la innovación en la industria gastronómica, proporcionando herramientas que facilitan la operación diaria, reducen costos y elevan los estándares de servicio en los restaurantes del siglo XXI.

### 1.1.2. Perfiles de integrantes del equipo

| **Oscar Nathaniel Garayar Mori - U202014115**                       | **Foto**                             |
|---------------------------------------------------------------------|--------------------------------------|
| Mi nombre es Oscar Garayar, estudiante de Ing. de software. Voy cursando el 6to ciclo de mi carrera, y me considero alguien responsable que, a pesar de las complicaciones, encontrará una forma de seguir adelante. Tengo experiencia con los lenguajes C++, Python y Java. | ![Foto de Oscar](https://github.com/Grupo5-AppWeb/Informe/blob/Garayar-U202014115/resources/integrantes/Oscar.jpg "Foto de Oscar") |

| **Luis Andres Arce Huaman - U20201A300**                       | **Foto**                             |
|---------------------------------------------------------------------|--------------------------------------|
|Mi nombre es Luis Arce, soy estudiante de la carrera de Ing de Software cursando mi 6to ciclo de mi carrera , me gusta el arte la danza y la tecnologia. He estudiado diversos lenguajes de programación en el transcurso de mi carrera y por mi mismo. Soy una persona confiable y muy tolerante. | ![Foto de Luis](https://github.com/Grupo5-AppWeb/Informe/blob/Garayar-U202014115/resources/integrantes/Luis.png "Foto de Luis") |

| **Jamir Ángel Marzál Pérez - U201824409**                       | **Foto**                             |
|---------------------------------------------------------------------|--------------------------------------|
|Me llamo Jamir, soy estudiante de la carrera de Ingeniería de Software. Mis principales cualidades son el trabajo en equipo, la escucha activa, ética, creatividad, eficacia y responsabilidad. Tengo conocimientos en lenguajes de  programación C++, C# y Python | ![Foto de Jamir](https://github.com/Grupo5-AppWeb/Informe/blob/Garayar-U202014115/resources/integrantes/Jamir.jpg "Foto de Jamir") |

| **Fabrisio Andre Belahonia Miranda - U202220219**                       | **Foto**                             |
|---------------------------------------------------------------------|--------------------------------------|
| Mi nombre es Fabrisio Belahonia, estudiante de Ing. de software. Voy cursando el 5to ciclo de mi carrera, y me considero una persona responsable, ordenado, empático. Me interesa el área de Ciberseguridad y tengo experiencia con Linux, Redes, Cloud, etc.| ![Foto de Fabrisio](/Informe/resources/integrantes/Fabrisio.jpg "Foto de Fabrisio") |

| **Anthony Martin Huapaya Cuevas - U202220235**                       | **Foto**                             |
|---------------------------------------------------------------------|--------------------------------------|
| Mi nombre es Anthony Huapaya, soy estudiante de Ing. De Software y voy cursando el 5to ciclo. Me considero alguien que se adapta a la situación que se presenta, tengo buena comunicación con los integrantes del grupo. Mi experiencia con los lenguajes son C++ y un poco de Python.| ![Foto de Anthony](https://github.com/Grupo5-AppWeb/Informe/blob/Garayar-U202014115/resources/integrantes/Anthony.jpg "Foto de Anthony") |

| **Hardie Alfonso Holguin Gamarra - U202220250**                       | **Foto**                             |
|---------------------------------------------------------------------|--------------------------------------|
| Soy Hardie Holguín, Estudio la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas (UPC). Soy una persona disciplinada y organizada. En mi tiempo libre me gusta entrenar en el gimnasio y jugar futbol.| ![Foto de Hardie](/Informe/resources/integrantes/Hardie.jpg "Foto de Hardie") |


### 1.2. Solution Profile

En el competitivo mundo de la gastronomía, la gestión eficiente de las operaciones se ha convertido en un pilar fundamental para asegurar un servicio de alta calidad y una experiencia excepcional para los clientes. Sin embargo, los métodos tradicionales de administración de restaurantes, desde la gestión de mesas y reservas hasta el control de inventarios y la coordinación con proveedores, pueden ser complejos, lentos y propensos a errores. Esta realidad ha generado una necesidad urgente de encontrar soluciones innovadoras que permitan a los restaurantes optimizar estos procesos críticos de manera más eficiente y efectiva.

En este contexto, surge una nueva era en la gestión de restaurantes, donde la tecnología y la inteligencia operativa se combinan para ofrecer soluciones integrales, ágiles y precisas. La búsqueda de métodos más inteligentes para coordinar la operación de los restaurantes se ha convertido en una prioridad para los profesionales que buscan maximizar la eficiencia, reducir costos y mejorar la experiencia del cliente. RestauMaster se posiciona a la vanguardia de esta transformación, proporcionando herramientas tecnológicas que simplifican la gestión diaria y permiten a los restaurantes enfocarse en lo más importante: brindar una experiencia gastronómica inolvidable.

### 1.2.1 Antecedentes y problemática

##### What

- Los métodos tradicionales de gestión en restaurantes, como la organización de mesas, reservas y control de inventarios, suelen ser laboriosos, costosos y propensos a errores.
- Los gerentes y personal del restaurante deben coordinar múltiples tareas manualmente, lo que puede llevar a ineficiencias operativas y problemas de comunicación.
- Esto puede resultar en pérdida de clientes, insatisfacción y aumento de costos debido a errores humanos y procedimientos ineficientes.

##### Who

- Gerentes de restaurantes y personal de servicio se ven afectados por la complejidad y la carga de trabajo que implican los métodos tradicionales de gestión.
- Clientes enfrentan retrasos y errores en sus reservas y pedidos, lo que afecta su experiencia general en el restaurante.

##### Where

- Esta problemática es común en restaurantes de cualquier tamaño, desde pequeños locales hasta grandes cadenas, donde la eficiencia operativa es crucial para el éxito del negocio.

###### When

- La problemática surge en el día a día de las operaciones del restaurante, especialmente durante los periodos de alta demanda, como las horas pico y eventos especiales, donde la coordinación y eficiencia son esenciales.

##### Why

- La falta de automatización y herramientas integradas para la gestión de operaciones dificulta la eficiencia y aumenta la probabilidad de errores.
- La falta de visibilidad en tiempo real sobre el inventario, las reservas y los pedidos lleva a decisiones menos informadas y puede generar desperdicio de recursos y pérdidas financieras.


##### How

- En un restaurante típico, el personal puede requerir mucho tiempo para coordinar manualmente las reservas, gestionar las mesas, controlar el inventario y comunicarse con la cocina y los proveedores. - Con "RestauMaster", este proceso se agiliza significativamente, permitiendo una gestión más fluida y eficiente de todas las áreas del restaurante en cuestión de minutos.
- El problema sigue un patrón de ineficiencia y desorganización en la gestión diaria. El personal a menudo se ve abrumado por la cantidad de tareas operativas y la falta de herramientas eficientes para manejarlas de manera rápida y precisa.

##### How Much

- En un día, un restaurante puede perder ingresos significativos debido a la ineficiencia en la gestión de reservas, pedidos y stock. Con "RestauMaster", estas pérdidas pueden reducirse en un 50%.
- En términos de pérdida de ingresos y eficiencia operativa, un restaurante sin automatización adecuada podría estar perdiendo el equivalente a miles de soles mensuales debido a errores en la gestión y desperdicio de recursos. Con "RestauMaster", se pueden minimizar estos retrasos y optimizar el uso de recursos en todas las áreas del restaurante.

### 1.2.2 Lean UX Process.
### 1.2.2.1. Lean UX Problem Statements.
### 1.2.2.2. Lean UX Assumptions.
### 1.2.2.3. Lean UX Hypothesis Statements.
### 1.2.2.4. Lean UX Canvas.
### 1.3. Segmentos objetivo.
## Capítulo II: Requirements Elicitation & Analysis
### 2.1. Competidores.
### 2.1.1. Análisis competitivo.
### 2.1.2. Estrategias y tácticas frente a competidores.
### 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
### 2.2.2. Registro de entrevistas.
### 2.2.3. Análisis de entrevistas.
### 2.3. Needfinding.
### 2.3.1. User Personas.
### 2.3.2. User Task Matrix.
### 2.3.3. User Journey Mapping.
### 2.3.4. Empathy Mapping.
### 2.3.5. As-is Scenario Mapping.
### 2.4. Ubiquitous Language.
### Capítulo III: Requirements Specification
### 3.1. To-Be Scenario Mapping.
### 3.2. User Stories.
### 3.3. Impact Mapping.
### 3.4. Product Backlog.
## Capítulo IV: Product Design
### 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.

El diseño de la página de destino de RestauMaster encarna los principios de eficiencia, innovación y apoyo en la gestión de operaciones para restaurantes. Los elementos visuales se eligen para respaldar estos valores fundamentales y ofrecer una experiencia amigable para el usuario.

- **Branding**:  
  RestauMaster refleja una marca comprometida con proporcionar soluciones integrales que optimizan la gestión de restaurantes. La esencia de la marca es la innovación y la eficiencia, orientadas a mejorar la experiencia del cliente.

- **Logo**:  
  El logotipo de RestauMaster combina colores vibrantes y un diseño moderno, representando efectivamente el enfoque de la empresa en la innovación y soluciones centradas en el cliente. La simplicidad del logo y su relevancia para la industria de restaurantes refuerzan la identidad de la marca.

- **Colors**:
  - **Azul Oscuro (#004080)**: Utilizado para el encabezado, pie de página y elementos de navegación para transmitir confianza y profesionalismo.
  - **Naranja (#ff7300)**: Utilizado en los botones de llamada a la acción y elementos destacados, este color añade dinamismo y dirige la atención del usuario hacia las acciones esenciales.
  - **Blanco (#FFFFFF)**: Empleado como color de fondo predominante para garantizar claridad y un diseño limpio y organizado.
  - **Gris (#333, #555)**: Utilizado para texto secundario y detalles menores, proporcionando buena legibilidad mientras mantiene una presencia visual sutil.

- **Typography**:
  - **Fuentes Usadas**: 'Roboto' y 'Varela Round' se emplean para proporcionar una estética moderna y accesible. Estas fuentes son adecuadas para una amplia audiencia y aseguran consistencia visual a través de diferentes dispositivos.
  - **Estilos y Tamaños**:
    - **Títulos**: Grandes y en negrita para captar la atención.
    - **Texto del Cuerpo**: Tamaños moderados para asegurar legibilidad y una experiencia de usuario cómoda.

- **Communication Tones**

  - **Formal/Approachable**: El estilo de comunicación es profesional pero accesible, entregando la información de manera clara y atractiva.
  - **Respectful/Enthusiastic**: El tono mantiene una postura respetuosa y empática mientras combina entusiasmo para promover la plataforma y sus beneficios.

### 4.1.2. Web Style Guidelines.

- **Fonts**:
  - **Roboto** y **Varela Round**: Estas fuentes son elegidas por su apariencia moderna y limpia, mejorando la legibilidad y manteniendo un estilo consistente en todo el sitio web. 'Roboto' se utiliza principalmente para el texto del cuerpo debido a su claridad, mientras que 'Varela Round' añade un toque de amabilidad a los títulos y subtítulos.

- **Colors**:
  - **Azul Oscuro (#004080)**: Utilizado para el encabezado, pie de página y elementos de navegación, este color transmite confianza y profesionalismo, proporcionando un fondo estable que complementa los acentos dinámicos.
  - **Naranja (#ff7300)**: Este color vibrante se utiliza para los botones de llamada a la acción y los aspectos destacados importantes. Llama la atención y guía a los usuarios hacia acciones deseadas, como "Solicitar una Demo" o "Comprar Ahora."
  - **Blanco (#FFFFFF)**: Predominantemente usado como color de fondo para mantener una interfaz limpia y despejada, mejorando la legibilidad del texto y el confort visual.
  - **Gris (#333, #555)**: Empleado para elementos de texto secundarios, este color mantiene la legibilidad mientras contrasta sutilmente con el fondo blanco.

- **Graphics**:
  - **Logo**: Posicionado de manera prominente en el encabezado, el logo refuerza la identidad de la marca. El diseño limpio y sencillo se alinea con la estética general del sitio.
  - **Background Images**: Diferentes secciones, como Hero, Features, y Contact Us, utilizan imágenes de fondo temáticas que se alinean con su contenido respectivo, añadiendo interés visual y contexto.
  - **Icons**: Los iconos de redes sociales y otros elementos gráficos se utilizan para facilitar la participación del usuario y la navegación. Los iconos de Facebook, Twitter e Instagram se muestran claramente en el pie de página.

- **Components**:
  - **Buttons**: Los botones de llamada a la acción (CTA) son audaces y claramente definidos, con bordes redondeados y un color naranja brillante para asegurar que se destaquen contra los colores de fondo más oscuros. Se aplican efectos hover para mejorar la interactividad.
  - **Sliders and Carousels**: Utilizados para mostrar múltiples características o testimonios de clientes de manera dinámica, proporcionando una forma más atractiva de presentar la información.
  - **Text Fields and Forms**: Los formularios de contacto son sencillos y fáciles de usar, con etiquetas claras y suficiente espacio para facilitar la entrada del usuario.
  - **Plan Cards**: Los planes de precios se presentan en formato de tarjetas con bordes distintos y efectos hover, facilitando a los usuarios la comparación de opciones y la toma de decisiones.


### **4.2 Information Architecture**

**4.2.1 Organization Systems**

| **Página/Sección**                 | **Descripción**                                                                                                                                                     |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Dashboard Principal**            | Proporciona una vista general de las métricas clave del restaurante, incluyendo reservas, inventario, ventas, y rendimiento operativo.                                |
| **Gestión de Reservas**            | Permite la gestión de reservas en tiempo real, incluyendo la creación, modificación y cancelación de reservas, así como la gestión de listas de espera y disposición de mesas. |
| **Control de Inventario**          | Monitorea los niveles de inventario, proporcionando alertas para artículos de bajo stock y reportes de consumo.                                                       |
| **Pedidos y Facturación**          | Automatiza el proceso de pedidos y facturación, integrándose con el sistema de punto de venta (POS) para sincronizar órdenes y pagos.                                 |
| **Gestión de Proveedores**         | Facilita la coordinación con proveedores para realizar pedidos, gestionar contratos y automatizar el flujo de trabajo de abastecimiento.                              |
| **Análisis y Reportes**            | Proporciona reportes detallados sobre el rendimiento del restaurante, incluyendo ventas, costos operativos, y satisfacción del cliente.                                |
| **Configuración y Personalización**| Permite a los usuarios personalizar la interfaz de usuario, gestionar roles de usuario y configurar parámetros del restaurante.                                        |

**4.2.2 Labeling Systems**

| **Etiqueta**                | **Descripción**                                                                                      |
|-----------------------------|------------------------------------------------------------------------------------------------------|
| **Dashboard**               | Panel de Control con métricas y estadísticas clave del restaurante.                                   |
| **Reservations**            | Gestión de reservas y mesas.                                                                          |
| **Inventory**               | Control y seguimiento de inventarios de ingredientes y suministros.                                   |
| **Orders and Billing**      | Gestión de pedidos y facturación automatizada.                                                        |
| **Suppliers Management**    | Coordinación con proveedores y gestión de suministros.                                                |
| **Analytics**               | Generación de reportes y análisis de datos operativos.                                                |
| **Settings**                | Personalización de la interfaz y configuración del restaurante.                                       |
| **User Management**         | Gestión de roles y permisos de usuarios.                                                              |

**4.2.3 SEO Tags and Meta Tags**

Para mejorar la visibilidad de la aplicación web de RE-Grill en motores de búsqueda y facilitar su descubrimiento, se han implementado las siguientes etiquetas SEO y meta:

- **Title**: RE-Grill | Gestión Integral para Restaurantes
- **Description**: Plataforma de RE-Grill - Solución avanzada para la gestión eficiente de reservas, inventarios, pedidos, y proveedores en restaurantes.
- **Keywords**: Gestión de restaurantes, reservas online, control de inventarios, pedidos automatizados, análisis de datos, software para restaurantes.
- **Author**: Equipo de RE-Grill
- **Canonical**: https://app.regrill.com/

**4.2.4 Searching Systems**

| **Sistema de Búsqueda**     | **Descripción**                                                                                      |
|-----------------------------|------------------------------------------------------------------------------------------------------|
| **Búsqueda Global**         | Permite a los usuarios buscar términos clave en todas las secciones de la aplicación.                |
| **Filtros Avanzados**       | Ofrece opciones para filtrar resultados por categorías como reservas, inventario, pedidos, y análisis.|
| **Sugerencias de Búsqueda** | Muestra sugerencias automáticas basadas en las búsquedas más frecuentes y populares.                 |
| **Resultados Relevantes**   | Prioriza los resultados más relevantes basados en el historial de búsqueda y comportamiento del usuario. |

**4.2.5 Navigation Systems**

| **Sistema de Navegación**   | **Descripción**                                                                                      |
|-----------------------------|------------------------------------------------------------------------------------------------------|
| **Menú Lateral Fijo**       | Proporciona acceso rápido a todas las secciones principales de la aplicación desde cualquier página.  |
| **Breadcrumbs**             | Ayuda a los usuarios a entender la estructura jerárquica del sitio y regresar a páginas anteriores fácilmente. |
| **Barra de Navegación Superior** | Incluye opciones adicionales como ajustes de cuenta, notificaciones, y perfil de usuario.                   |


### 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
### 4.3.2. Landing Page Mock-up.
### 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.2. Web Applications Mock-ups.
### 4.4.3. Web Applications User Flow Diagrams.
### 4.5. Web Applications Prototyping.
### 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.
### 4.6.2. Software Architecture Container Diagrams.
### 4.6.3. Software Architecture Components Diagrams.
### 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
### 4.7.2. Class Dictionary.
### 4.8. Database Design.
### 4.8.1. Database Diagram.
## Capítulo V: Product Implementation, Validation & Deployment
### 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
### 5.1.2. Source Code Management.
### 5.1.3. Source Code Style Guide & Conventions.
### 5.1.4. Software Deployment Configuration.
### 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint n
### 5.2.1.1. Sprint Planning n.
### 5.2.1.2. Sprint Backlog n.
### 5.2.1.3. Development Evidence for Sprint Review.
### 5.2.1.4. Testing Suite Evidence for Sprint Review.
### 5.2.1.5. Execution Evidence for Sprint Review.
### 5.2.1.6. Services Documentation Evidence for Sprint Review.
### 5.2.1.7. Software Deployment Evidence for Sprint Review.
### 5.2.1.8. Team Collaboration Insights during Sprint.
### 5.3. Validation Interviews.
### 5.3.1. Diseño de Entrevistas.
### 5.3.2. Registro de Entrevistas.
### 5.3.3. Evaluaciones según heurísticas.
### 5.4. Video About-the-Product.
###  
### Conclusiones
### Conclusiones y recomendaciones.
### Video About-the-Team.
### Bibliografía
### Anexos
