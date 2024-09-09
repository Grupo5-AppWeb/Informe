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

- [Universidad Peruana de Ciencias Aplicadas - Informe de Trabajo Final](#universidad-peruana-de-ciencias-aplicadas---informe-de-trabajo-final)
- [Aplicaciones Web - SW52](#aplicaciones-web---sw52)
  - [Integrantes:](#integrantes)
  - [Tabla de Contenidos](#tabla-de-contenidos)
  - [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
  - [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [RestauMaster: Simplificando la Operación de Restaurantes](#restaumaster-simplificando-la-operación-de-restaurantes)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
      - [What](#what)
      - [Who](#who)
      - [Where](#where)
        - [When](#when)
      - [Why](#why)
      - [How](#how)
      - [How Much](#how-much)
  - [1.2.2 Lean UX Process.](#122-lean-ux-process)
  - [1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)
  - [1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)
  - [1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)
  - [1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo.](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores.](#21-competidores)
  - [2.1.1. Análisis competitivo.](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores.](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas.](#22-entrevistas)
  - [2.2.1. Diseño de entrevistas.](#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas.](#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas.](#223-análisis-de-entrevistas)
  - [2.3. Needfinding.](#23-needfinding)
  - [2.3.1. User Personas.](#231-user-personas)
  - [2.3.2. User Task Matrix.](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping.](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping.](#234-empathy-mapping)
  - [2.3.5. As-is Scenario Mapping.](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language.](#24-ubiquitous-language)
  - [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping.](#31-to-be-scenario-mapping)
  - [3.2. User Stories.](#32-user-stories)
  - [3.3. Impact Mapping.](#33-impact-mapping)
  - [3.4. Product Backlog.](#34-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines.](#41-style-guidelines)
  - [4.1.1. General Style Guidelines.](#411-general-style-guidelines)
  - [4.1.2. Web Style Guidelines.](#412-web-style-guidelines)
  - [**4.2 Information Architecture**](#42-information-architecture)
  - [4.3. Landing Page UI Design.](#43-landing-page-ui-design)
  - [4.3.1. Landing Page Wireframe.](#431-landing-page-wireframe)
  - [4.3.2. Landing Page Mock-up.](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design.](#44-web-applications-uxui-design)
  - [4.4.1. Web Applications Wireframes.](#441-web-applications-wireframes)
  - [4.4.2. Web Applications Wireflow Diagrams.](#442-web-applications-wireflow-diagrams)
  - [4.4.2. Web Applications Mock-ups.](#442-web-applications-mock-ups)
  - [4.4.3. Web Applications User Flow Diagrams.](#443-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping.](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture.](#46-domain-driven-software-architecture)
  - [4.6.1. Software Architecture Context Diagram.](#461-software-architecture-context-diagram)
  - [4.6.2. Software Architecture Container Diagrams.](#462-software-architecture-container-diagrams)
  - [4.6.3. Software Architecture Components Diagrams.](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design.](#47-software-object-oriented-design)
  - [4.7.1. Class Diagrams.](#471-class-diagrams)
  - [4.7.2. Class Dictionary.](#472-class-dictionary)
  - [4.8. Database Design.](#48-database-design)
  - [4.8.1. Database Diagram.](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management.](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration.](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management.](#512-source-code-management)
  - [5.1.3. Source Code Style Guide \& Conventions.](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration.](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation.](#52-landing-page-services--applications-implementation)
  - [5.2.1. Sprint n](#521-sprint-n)
  - [5.2.1.1. Sprint Planning n.](#5211-sprint-planning-n)
  - [5.2.1.2. Sprint Backlog n.](#5212-sprint-backlog-n)
  - [5.2.1.3. Development Evidence for Sprint Review.](#5213-development-evidence-for-sprint-review)
  - [5.2.1.4. Testing Suite Evidence for Sprint Review.](#5214-testing-suite-evidence-for-sprint-review)
  - [5.2.1.5. Execution Evidence for Sprint Review.](#5215-execution-evidence-for-sprint-review)
  - [5.2.1.6. Services Documentation Evidence for Sprint Review.](#5216-services-documentation-evidence-for-sprint-review)
  - [5.2.1.7. Software Deployment Evidence for Sprint Review.](#5217-software-deployment-evidence-for-sprint-review)
  - [5.2.1.8. Team Collaboration Insights during Sprint.](#5218-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews.](#53-validation-interviews)
  - [5.3.1. Diseño de Entrevistas.](#531-diseño-de-entrevistas)
  - [5.3.2. Registro de Entrevistas.](#532-registro-de-entrevistas)
  - [5.3.3. Evaluaciones según heurísticas.](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product.](#54-video-about-the-product)
  - [](#)
  - [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones.](#conclusiones-y-recomendaciones)
  - [Video About-the-Team.](#video-about-the-team)
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
| Mi nombre es Oscar Garayar, estudiante de Ing. de software. Voy cursando el 6to ciclo de mi carrera, y me considero alguien responsable que, a pesar de las complicaciones, encontrará una forma de seguir adelante. Tengo experiencia con los lenguajes C++, Python y Java. | ![Foto de Oscar](https://github.com/Grupo5-AppWeb/Informe/blob/main/resources/integrantes/Oscar.jpg "Foto de Oscar") |

| **Luis Andres Arce Huaman - U20201A300**                       | **Foto**                             |
|---------------------------------------------------------------------|--------------------------------------|
|Mi nombre es Luis Arce, soy estudiante de la carrera de Ing de Software cursando mi 6to ciclo de mi carrera , me gusta el arte la danza y la tecnologia. He estudiado diversos lenguajes de programación en el transcurso de mi carrera y por mi mismo. Soy una persona confiable y muy tolerante. | ![Foto de Luis](https://github.com/Grupo5-AppWeb/Informe/blob/main/resources/integrantes/Luis.png "Foto de Luis") |

| **Jamir Ángel Marzál Pérez - U201824409**                       | **Foto**                             |
|---------------------------------------------------------------------|--------------------------------------|
|Me llamo Jamir, soy estudiante de la carrera de Ingeniería de Software. Mis principales cualidades son el trabajo en equipo, la escucha activa, ética, creatividad, eficacia y responsabilidad. Tengo conocimientos en lenguajes de  programación C++, C# y Python | ![Foto de Jamir](https://github.com/Grupo5-AppWeb/Informe/blob/main/resources/integrantes/Jamir.jpg "Foto de Jamir") |

| **Fabrisio Andre Belahonia Miranda - U202220219**                       | **Foto**                             |
|---------------------------------------------------------------------|--------------------------------------|
| Mi nombre es Fabrisio Belahonia, estudiante de Ing. de software. Voy cursando el 5to ciclo de mi carrera, y me considero una persona responsable, ordenado, empático. Me interesa el área de Ciberseguridad y tengo experiencia con Linux, Redes, Cloud, etc.| ![Foto de Fabrisio](https://github.com/Grupo5-AppWeb/Informe/blob/main/resources/integrantes/Fabrisio.jpg "Foto de Fabrisio") |

| **Anthony Martin Huapaya Cuevas - U202220235**                       | **Foto**                             |
|---------------------------------------------------------------------|--------------------------------------|
| Mi nombre es Anthony Huapaya, soy estudiante de Ing. De Software y voy cursando el 5to ciclo. Me considero alguien que se adapta a la situación que se presenta, tengo buena comunicación con los integrantes del grupo. Mi experiencia con los lenguajes son C++ y un poco de Python.| ![Foto de Anthony](https://github.com/Grupo5-AppWeb/Informe/blob/main/resources/integrantes/Anthony.jpg "Foto de Anthony") |

| **Hardie Alfonso Holguin Gamarra - U202220250**                       | **Foto**                             |
|---------------------------------------------------------------------|--------------------------------------|
| Soy Hardie Holguín, Estudio la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas (UPC). Soy una persona disciplinada y organizada. En mi tiempo libre me gusta entrenar en el gimnasio y jugar futbol.| ![Foto de Hardie](https://github.com/Grupo5-AppWeb/Informe/blob/main/resources/integrantes/Hardie.jpg "Foto de Hardie") |


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
- Hemos detectado problemas al momento de gestionar los recursos que se tienen en un restaurante, donde hay problemas con respecto a las cantidades que se tienen en el momento y las mermas que se hacen.
- Se detectaron problemas al momento de contactarse con los proveedores para reponer los productos que están a punto de agotarse el stock para su pronta preparación de las comidas.
### 1.2.2.2. Lean UX Assumptions.
**Assumptions Worksheet**<br>
**¿Quién es el usuario?**
- La parte administrativa de un restaurante
- Los proveedores de restaurantes

**¿Qué problemas tiene nuestro producto? ¿Resolver?**
- Gestión con los productos que se tienen en el restaurante
- Comunicación con los proveedores de alimentos para los ingredientes de sus platillos a la carta

**¿Qué características son importantes?**
- Una mejor forma de contactarse entre la parte administrativa y el proveedor para la reponer los productos
- Mejorar la atención del cliente con los platillos que se encuentran disponibles en dicho momento.
- Organización de las cantidades de los productos, ya sea comestibles o de mantenimiento.
- Interfaz amigable para cualquier usuario que lo use.

**¿Dónde encaja nuestro producto en su trabajo o vida?**
- Para la administración, nuestro producto les ayudará a gestionar los ingredientes de los platos que cocinan, además de conocer los desperdicios que hay al momento de cocinar y las cantidades de mesas, sillas, entre otros.
- Para los proveedores, el producto los ayudará en mejorar la comunicación entre ellos y la administración del restaurante, además de brindar las cantidades exactas que necesita el restaurante.

**¿Cuándo y cómo es nuestro producto? ¿Usado?**
- El producto será utilizado cuando la administración del restaurante comienza a gestionar el inventario que posee actualmente, además de ver si las cantidades son las suficientes para las preparaciones al momento de atender.
- El producto será usado por algunos proveedores de restaurantes, donde podrán visualizar los distintos restaurantes que necesitan contactarse con algún proveedor de algún consumible.
- El producto será a través de una aplicación web mediante algún dispositivo que usa internet y un navegador como Chrome.

**¿Cómo debe verse nuestro producto y cómo comportarse?**
- El diseño de nuestro producto debe ser atractivo y coherente con respecto al diseño del restaurante.
- La plataforma debe cargar de manera rápida las respuestas a las acciones del usuario para que no se frustre.
- La navegación de la plataforma debe ser intuitiva y comprensible, donde los usuarios pueden ver los filtros necesarios y las distintas opciones que tiene.
- Debe mostrar a los clientes con gráficos y una pequeña descripción acerca del plato de comida que busca.
- Esta plataforma debe ser compatible con algunos dispositivos de dimensiones distintas, como celulares, laptops, tablets y computadoras, donde se usa un diseño responsive.

**Business Outcomes**<br>
- Convertir nuestro producto como una plataforma indispensable para la gestión de restaurantes, ya sea en la manera de reponer el inventario, organización del mismo local y la atención de los clientes.
- Un 75% de los usuarios que usaron la página han logrado gestionar de mejor manera los restaurantes.
- Un 20% de los clientes de restaurantes se muestran insatisfechos con la atención que brinda los restaurantes.

**User Benefits**<br>
- Ahorro de tiempo por la manera de gestionar el inventario.
- Facilidad en buscar los productos faltantes o desperdiciados.
- Mejor comunicación entre el proveedor y la administración.

**Assumptions Steps**<br>
**a. Creo que mis clientes necesitan:**
  - Visualización de disponibilidad de platillos.
  - Expresar de manera intuitiva el inventario que se lleva en el local
  - Comunicarse de manera eficiente con otro tipo de usuario

**b. Estas necesidades se pueden resolver con:**
  - Un sistema que calcula lo que hay en el inventario en general y lo que se usa al día.
  - Una base de datos que se actualiza cada vez que cambia y se use parte de lo que hay en el inventario.
  - Un diseño que sea muy atractivo visualmente y a la vez entendible para gestionar el restaurante.
  - Accesibilidad para su uso en distintos dispositivos según lo que el usuario usará.

**c. Mis clientes iniciales son (o serán):**
  - La parte administrativa de un restaurante.
  - Los proveedores o vendedores de alimentos para los restaurantes.

**d. El valor #1 que un cliente quiere de mi producto es veracidad (utilidad, funcionalidades que le resuelven el problema)**
  - La garantía de que no habrá problemas en las cantidades con respecto al inventario por la base de datos.
  - La comunicación de manera directa con el proveedor con respecto a la necesidad del restaurante.

**e. El cliente también puede obtener estos beneficios adicionales:**
  - Obtener las cantidades de la merma que se obtiene al hacer un plato.
  - Mejorar la administración del restaurante.          

**f. Voy a adquirir la mayoría de mis clientes a través de:**
  - Colaboración con un restaurante conocido.
  - Estrategias de marketing digital con el enfoque en los distintos restaurantes.

**g. Haré dinero a través de:**
  - Membresías premium con acceso exclusivo y funciones adicionales

**h. Mi competencia principal en el mercado:**
  - Tiendas virtuales de restaurantes que se enfocan en las ventas.
  - Páginas de gestión de restaurantes.

**i. Los venceremos debido a:**
  - El diseño es atractivo y accesible para cualquier tipo de usuario ya sea la administración o el proveedor.
  - La base de datos actualizada constantemente con respecto a la necesidad del usuario.

**j. Mi mayor riesgo del producto es:**
  - La desconfianza por parte de los restaurantes con respecto a la correcta función del programa al momento de tener días especiales.
  - El mal cálculo del inventario al momento de mostrar las cantidades de cada producto que se encuentra disponible.

**k. Resolveremos esto a través de:**
  - Mostrando pruebas funcionales de esto y su adaptabilidad ante algún problema que se muestra de manera sorpresiva.
  - Las constantes verificaciones que se realizará al momento de que se haga alguna compra.

**l. ¿Qué otras suposiciones tenemos? ¿Eso, si se prueba que es falso, causará que nuestro negocio / proyecto no funcione?**
  - Podrá ser que las estrategias de marketing que se usa podrán ayudar a obtener más compañías que le darán uso de la aplicación. En caso se muestre el contrario, podría afectar de manera negativa la inversión del negocio.
  - Las ventas de las suscripciones para obtener más funciones que les será muy útil para mejorar su experiencia con la página. Si se prueba que es falso, afectaría de manera directa con la generación de ingresos y sostenibilidad del negocio.

### 1.2.2.3. Lean UX Hypothesis Statements.
**Hypothesis 1:**

Creemos que al tener suscripciones de pago ayudará a que los usuarios puedan obtener algunas herramientas de manera exclusiva que los regulares, además de ayudarnos a evaluar sobre el interés que existe sobre su uso.
Sabremos que hemos tenido éxito
Cuando veamos un aumento significativo con los números de clientes que usan suscripciones premium.

**Hypothesis 2:**

Creemos que al optimizar y mejorar la manera de gestionar el inventario de los administradores de un restaurante podrá mejorar la eficiencia con respecto a las cantidades de ventas que produzca
Sabremos que hemos tenido éxito
Cuando veamos el incremento de ventas del restaurante con platos que antes no se vendía tanto por la falta de ingredientes que tienen, además de un aumento de clientes.

**Hypothesis 3:**

Creemos que al implementar un sistema que ayuda a los proveedores vender sus productos a los restaurantes afiliados a nuestra plataforma y que necesita algo de ello
Sabremos que hemos tenido éxito
Cuando aumenta más las cantidades de proveedores que venden a distintos restaurantes por los productos que necesitan estos.

### 1.2.2.4. Lean UX Canvas.
<table border="1" style="text-align: left;">  
  <tr>
    <th style="text-align: center;">Business Problem</th>
    <th style="text-align: center;">Solution Ideas</th>
    <th style="text-align: center;">Business Outcomes</th>
  </tr>
  <tr>
    <td>
        <ul>
            <li>Gestión de recursos en un restaurante por las cantidades que hay en el inventario.</li>
            <li>Contacto entre la administración de un restaurante y los proveedores de estos.</li>
        </ul>
    </td>
    <td rowspan="2">
        <ul>
            <li>Cuando veamos un aumento significativo con los números de clientes que usan suscripciones premium.</li>
            <li>Cuando veamos el incremento de ventas del restaurante con platos que antes no se vendía tanto por la falta de ingredientes que tienen, además de un aumento de clientes.</li>
            <li>Cuando aumenta más las cantidades de proveedores que venden a distintos restaurantes por los productos que necesitan estos.</li>
        </ul>
    </td>
    <td>
        <ul>
            <li>Convertir nuestro producto como una plataforma indispensable para la gestión de restaurantes, ya sea en la manera de reponer el inventario, organización del mismo local y la atención de los clientes.</li>
            <li>Un 75% de los usuarios que usaron la página han logrado gestionar de mejor manera los restaurantes.</li>
            <li>Un 20% de los clientes de restaurantes se muestran insatisfechos con la atención que brinda los restaurantes.</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th style="text-align: center;">Users</th>
    <th style="text-align: center;">User Benefits</th>
  </tr>
  <tr>
    <td>
        <ul>
            <li>Administración del restaurante</li>
            <li>Proveedores de restaurantes</li>
        </ul>
    </td>
    <th style="text-align: center;">What’s the most important thing we need to learn first?</th>
    <td>
        <ul>
            <li>Ahorro de tiempo por la manera de gestionar el inventario.</li>
            <li>Facilidad en buscar los productos faltantes o desperdiciados.</li>
            <li>Mejor comunicación entre el proveedor y la administración.</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th style="text-align: center;">Hypotheses</th>
    <td rowspan="2">
        <ul>
            <li>Entender de mejor manera los problemas de gestión con los inventarios que administra los restaurantes.</li>
            <li>Comprender el funcionamiento de los sistemas de suscripciones con respecto al tema de los restaurantes</li>
        </ul>
    </td>
    <th style="text-align: center;">What’s the least amount of work we need to do learn the next most important thing?</th>
  </tr>
  <tr>
    <td>
        <ul>
            <li>Creemos que al tener suscripciones de pago ayudará a que los usuarios puedan obtener algunas herramientas de manera exclusiva que los regulares, además de ayudarnos a evaluar sobre el interés que existe sobre su uso.</li>
            <li>Creemos que al optimizar y mejorar la manera de gestionar el inventario de los administradores de un restaurante podrá mejorar la eficiencia con respecto a las cantidades de ventas que produzca.</li>
            <li>Creemos que al implementar un sistema que ayuda a los proveedores vender sus productos a los restaurantes afiliados a nuestra plataforma y que necesita algo de ello.</li>
        </ul>
    </td>
    <td>
        <ul>
            <li>Entrevistar a los distintos administradores de restaurantes y cómo se comunica con los proveedores.</li>
            <li>Constantes feedback con respecto al manejo de la página, ya sea por algunos de nuestros principales usuarios.</li>
        </ul>
    </td>
  </tr>
</table>

### 1.3. Segmentos objetivo.
- **Segmento objetivo 1:** Administradores de restaurantes<br>
  **Geografía:** Perú<br>
  **Demografía:** Entre 20 a 35 años con experiencia en administración
- **Segmento objetivo 2:** Proveedores<br>
  **Geografía:** Perú<br>
  **Demografía:** Entre 20 a 40 años, vendedores de alimentos

## Capítulo II: Requirements Elicitation & Analysis
### 2.1. Competidores.

**Toast POS**

Toast es un sistema de punto de venta (POS) todo en uno diseñado específicamente para la industria de la restauración. Ofrece funcionalidades para la gestión de pedidos, pagos, inventario y análisis de datos, además de herramientas para la gestión de mesas y reservas. También incluye capacidades para pedidos en línea y delivery. Sus puntos fuertes incluyen ser una plataforma integral con herramientas avanzadas de análisis y reportes, y la integración con servicios de delivery y pedidos en línea.

**Square for Restaurants**

Square for Restaurants es un sistema POS que ofrece soluciones completas para la gestión de restaurantes, incluyendo la administración de mesas, pedidos, facturación, inventario y análisis. Se destaca por su facilidad de uso, la integración con otras herramientas de Square, y su flexibilidad y escalabilidad, adaptándose tanto a pequeños cafés como a grandes cadenas de restaurantes.

**Upserve by Lightspeed**

Upserve es una plataforma de gestión de restaurantes que ofrece un sistema POS robusto con capacidades avanzadas de gestión de inventarios, reportes de ventas y análisis de comportamiento de los clientes. Incluye funciones para la administración de mesas y reservas, y está diseñado para mejorar la eficiencia operativa. Sus puntos fuertes son los análisis detallados y herramientas de optimización, la integración con servicios de terceros, y el soporte especializado en la industria restaurantera.


### 2.1.1. Análisis competitivo.

<table border="1" style="text-align: left;">
  <tr>
    <th style="text-align: center;">Restaurante</th>
    <th style="text-align: center;">Baratie</th>
    <th style="text-align: center;">Toast POS</th>
    <th style="text-align: center;">Square</th>
    <th style="text-align: center;">Upserve</th>
  </tr>
  <tr>
    <th style="text-align: center;">Perfil</th>
    <td>Plataforma integral que gestiona mesas, reservas, cocina, ventas, inventarios, merma, y pedidos de insumos con conexión directa a proveedores para una coordinación eficiente.</td>
    <td>Sistema POS todo en uno para restaurantes, que cubre pedidos, pagos, inventario, mesas, reservas, y pedidos en línea, con análisis avanzado y servicios de delivery.</td>
    <td>Sistema POS flexible para la gestión completa de restaurantes, incluyendo administración de mesas, pedidos, facturación, inventario y análisis, con fácil escalabilidad.</td>
    <td>Sistema POS avanzado para restaurantes, con capacidades de gestión de inventarios, reportes de ventas y análisis del comportamiento del cliente, para mejorar la eficiencia operativa.</td>
  </tr>
  <tr>
    <th style="text-align: center;">Ventaja competitiva</th>
    <td>Ofrece una solución completa con integración directa a proveedores, optimizando la gestión interna y la cadena de suministro, facilitando la coordinación y reduciendo los costos operativos.</td>
    <td>Integra herramientas avanzadas de análisis y reportes, junto con capacidades robustas para delivery y pedidos en línea, mejorando la eficiencia operativa y el servicio al cliente.</td>
    <td>Ofrece facilidad de uso y flexibilidad, con integración fluida con otras herramientas de Square y escalabilidad para adaptarse al crecimiento del negocio.</td>
    <td>Proporciona análisis detallados y herramientas de optimización, integraciones con terceros y soporte especializado, ayudando a mejorar la eficiencia y la toma de decisiones.</td>
  </tr>
  <tr>
    <th style="text-align: center;">Perfil de Marketing</th>
    <th colspan="4" style="text-align: center;"></th>
  </tr>
  <tr>
    <th style="text-align: center;">Mercado Objetivo</th>
    <td>Restaurantes y proveedores de insumos</td>
    <td>Restaurantes</td>
    <td>Restaurantes</td>
    <td>Restaurantes</td>
  </tr>
  <tr>
    <th style="text-align: center;">Estrategias de Marketing</th>
    <td>Marketing de contenidos, testimonios de éxito, asociaciones estratégicas, publicidad digital</td>
    <td>Publicidad digital, marketing de referencia, eventos y ferias del sector</td>
    <td>Publicidad digital, demostraciones en directo, ofertas promocionales, colaboraciones estratégicas</td>
    <td>Publicidad digital, demostraciones personalizadas, eventos y ferias del sector</td>
  </tr>
  <tr>
    <th style="text-align: center;">Perfil de Producto</th>
    <th colspan="4" style="text-align: center;"></th>
  </tr>
  <tr>
    <th style="text-align: center;">Productos & Servicios</th>
    <td>Sistema de gestión integral para restaurantes con conexión a proveedores de insumos</td>
    <td>Un sistema todo en uno para la industria de la restauración</td>
    <td>Un sistema flexible y escalable diseñado para la gestión completa de restaurantes</td>
    <td>Un sistema flexible y escalable diseñado para la gestión completa de restaurantes</td>
  </tr>
  <tr>
    <th style="text-align: center;">Precios & Costos</th>
    <td>Variados</td>
    <td>Variados</td>
    <td>Variados</td>
    <td>Variados</td>
  </tr>
  <tr>
    <th style="text-align: center;">Canales de Distribución</th>
    <td>Web</td>
    <td>Web/Móvil</td>
    <td>Móvil</td>
    <td>Web/Móvil</td>
  </tr>
  <tr>
    <th style="text-align: center;">Análisis SWOT</th>
    <th colspan="4" style="text-align: center;"></th>
  </tr>
  <tr>
    <th style="text-align: center;">Fortalezas</th>
    <td>Conexión directa entre proveedores y restaurante, automatización de procesos, capacidades avanzadas en gestión de inventarios y reportes.</td>
    <td>Herramientas avanzadas de análisis y reportes. Integración con servicios de delivery y pedidos en línea. Personalización y soporte técnico especializado.</td>
    <td>Facilidad de uso y rápida implementación. Flexibilidad y escalabilidad para adaptarse a diferentes tamaños de negocios. Costos iniciales bajos y estructura de precios transparente.</td>
    <td>Capacidades avanzadas en gestión de inventarios y reportes. Análisis detallado del comportamiento de clientes y optimización operativa. Integración con servicios de terceros y soporte especializado en la industria restaurantera.</td>
  </tr>
  <tr>
    <th style="text-align: center;">Debilidades</th>
    <td>Dependencia de internet y posibles problemas de conectividad.</td>
    <td>Costos relativamente altos, lo que puede ser una barrera para pequeños negocios. Dependencia de una conexión a internet estable para funcionar óptimamente.</td>
    <td>Funcionalidades avanzadas pueden ser limitadas en comparación con competidores más especializados. Menor personalización en comparación con plataformas más robustas.</td>
    <td>Costos relativamente altos, especialmente para negocios pequeños. Complejidad en la configuración inicial y curva de aprendizaje para nuevos usuarios. Dependencia de la conexión a internet para la funcionalidad completa del sistema.</td>
  </tr>
  <tr>
    <th style="text-align: center;">Oportunidades</th>
    <td>Creciente demanda del mercado. Expansión en mercados internacionales.</td>
    <td>Expansión en mercados internacionales. Aumento en la demanda de soluciones para pedidos en línea y delivery.</td>
    <td>Expansión a mercados de tamaño medio y grande que buscan soluciones flexibles. Mejora de características y funciones mediante actualizaciones y adquisiciones.</td>
    <td>Creciente demanda de soluciones de análisis de datos. Expansión en mercados internacionales.</td>
  </tr>
  <tr>
    <th style="text-align: center;">Amenazas</th>
    <td>Competencia con mercados similares. Cambios en las necesidades del mercado.</td>
    <td>Competencia con mercados similares. Cambios en las necesidades del mercado.</td>
    <td>Competencia con mercados similares. Cambios en las necesidades del mercado.</td>
    <td>Competencia con mercados similares. Cambios en las necesidades del mercado.</td>
  </tr>
</table>



### 2.1.2. Estrategias y tácticas frente a competidores.

Incorporar Tecnología de Vanguardia
Inviertir en tecnologías emergentes como inteligencia artificial (IA) y análisis predictivo para mejorar la precisión en la gestión de inventarios y la previsión de demanda. Destacar estas características avanzadas en los esfuerzos de marketing y asegurarse de mantener la plataforma actualizada con las últimas innovaciones tecnológicas.

Marketing
Organizar eventos y webinars que resalten cómo Baratie utiliza tecnología avanzada para optimizar la cadena de suministro. Invitar a expertos en tecnología y clientes satisfechos para compartir sus experiencias y demostrar el valor de la plataforma.

Demuestra la Tecnología Avanzada en Marketing
Crear contenido educativo, como blogs, videos y webinars, que ilustre cómo Baratie optimiza la cadena de suministro mediante tecnología avanzada. Destacar el uso de algoritmos de previsión de demanda, análisis en tiempo real y automatización para aumentar la eficiencia. Publicar estudios de caso que evidencien la reducción de costos y la mejora en la gestión de inventarios. Utilizar testimonios en video para resaltar estos beneficios de manera efectiva.

Formación en Optimización
Ofrecer capacitación especializada sobre cómo utilizar la tecnología avanzada de Baratie para optimizar la cadena de suministro. Esto no solo ayudará a tus clientes a maximizar el uso de la plataforma, sino que también posicionará a Baratie como un experto.

### 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.

**Preguntas para administradores**

¿Cuáles son sus principales responsabilidades en la gestión diaria del restaurante?<br>
¿Cómo gestiona actualmente el inventario de insumos y la supervisión de la merma?<br>
¿Qué desafíos enfrenta al controlar la disponibilidad de mesas y la cantidad de sillas?<br>
¿Cómo se asegura de que las reservas estén correctamente asignadas a las mesas disponibles?<br>
¿Cómo maneja la conexión entre los módulos de ventas, cocina, y stock?<br>
¿Cuál es su opinión sobre la automatización de procesos entre estos módulos?<br>
¿Cómo realiza los pedidos de insumos a los proveedores actualmente?<br>
¿Qué estrategias utiliza para reducir la merma en la cocina?<br>
¿Cómo registra y analiza las pérdidas de insumos debido a vencimientos o accidentes?<br>
¿Qué tipo de reportes son más útiles para usted al analizar el rendimiento del restaurante?<br>

Información Complementaria:

¿Cuál es tu género?<br>
¿Cuál es tu edad?<br>
¿En qué distrito resides actualmente?<br>
¿Cuál es tu estado civil?<br>
¿Cómo describirías tu familia (tamaño, composición, etc.)?<br>
¿Cuál es tu ocupación actual?<br>
¿Cómo describirías tu personalidad en términos generales?<br>
¿Qué habilidades consideras que son tus fortalezas principales?<br>
¿Qué lo motivó a dedicarse a su oficio?<br>
¿Qué marcas o influencias consideras importantes en tu vida profesional o personal?<br>
¿Qué dispositivos tecnológicos prefieres usar para tu trabajo o estudios?<br>
¿Qué canales digitales utilizas con mayor frecuencia para interactuar profesionalmente?<br>
¿Cuáles son tus principales objetivos profesionales y personales?<br>
¿Qué frustraciones encuentras en tu práctica educativa o en tu trabajo actual?<br>

**Preguntas para proveedores**

¿Cómo describiría su relación actual con los restaurantes a los que provee insumos?<br>
¿Cómo prefiere que los restaurantes realicen sus pedidos de insumos?<br>
¿Qué métodos de comunicación prefiere para coordinar la entrega de los pedidos?<br>
¿Qué tan cómodo se siente utilizando una interfaz digital para gestionar sus tratos con los restaurantes?<br>
¿Qué funcionalidades le gustaría tener para mejorar la negociación y coordinación con los administradores?<br>
¿Cómo gestiona la oferta de insumos cuando la demanda del restaurante cambia rápidamente?<br>
¿Qué tipo de información adicional le sería útil para ajustar sus ofertas?<br>
¿Qué elementos son clave para asegurar que los restaurantes estén satisfechos con su servicio y cómo mide esa satisfacción?<br>
¿Cuáles son los mayores desafíos que enfrenta como proveedor al trabajar con restaurantes?<br>
Si pudiera solicitar una mejora específica en la plataforma digital, ¿cuál sería y cómo beneficiaría su relación con los restaurantes?<br>

Información Complementaria:

¿Cuál es tu género?<br>
¿Cuál es tu edad?<br>
¿En qué distrito resides actualmente?<br>
¿Cuál es tu estado civil?<br>
¿Cómo describirías tu familia (tamaño, composición, etc.)?<br>
¿Cuál es tu ocupación actual?<br>
¿Cómo describirías tu personalidad en términos generales?<br>
¿Qué habilidades consideras que son tus fortalezas principales?<br>
¿Qué lo motivó a dedicarse a su oficio?<br>
¿Qué marcas o influencias consideras importantes en tu vida profesional o personal?<br>
¿Qué dispositivos tecnológicos prefieres usar para tu trabajo o estudios?<br>
¿Qué canales digitales utilizas con mayor frecuencia para interactuar profesionalmente?<br>
¿Cuáles son tus principales objetivos profesionales y personales?<br>
¿Qué frustraciones encuentras en tu práctica educativa o en tu trabajo actual?<br>

### 2.2.2. Registro de entrevistas.


**Sección administrador**
| Entrevistado 1 | Keyner Hancco  |
| ------ | -- |
| Edad | 26 |
| Distrito de residencia | Santa Anita |
<img src="resources/entrevistado-1.jpeg"> | Hardy, administrador de un restaurante, destaca la importancia de la consistencia, calidad, servicio e innovación para el éxito. Utiliza tecnología como un POS, software de gestión de inventarios y plataformas de reservas, aunque se frustra por la falta de integración entre ellas. Es adaptable y mantiene un enfoque analítico, utilizando redes sociales, blogs y ferias para mantenerse al día con las tendencias. Sus principales desafíos incluyen la previsión de demanda, rotación del personal y asegurar la llegada puntual de insumos. Busca automatizar la gestión de reservas, mesas e inventarios, priorizando la rapidez y calidad en el servicio al cliente.|
| Timing:   | URL: |

| Entrevistado 2 | Anghelo Basauri |
| ------ | -- |
| Edad | 26 |
| Distrito de residencia | Rimac |
<img src="resources/entrevistado-2.jpeg"> |El entrevistado, administrador de restaurante, subraya que un software de gestión esencial debe integrar funciones como la gestión de mesas y reservas, control de inventario, seguimiento de ventas, y gestión de pedidos en cocina. También considera crucial la integración con proveedores y capacidades de análisis financiero para automatizar procesos y optimizar operaciones diarias. Prefiere herramientas que faciliten la toma de decisiones mediante reportes detallados y análisis de datos, y busca mejorar la intuitividad del software y la fluidez en la integración con proveedores. Esto refleja su necesidad de un sistema eficiente que simplifique la gestión y mejore la precisión operativa.|
| Timing:   | URL: |

| Entrevistado 3 | Luis Osorio alza |
| ------ | -- |
| Edad | 23 |
| Distrito de residencia | Surco |
<img src="resources/entrevistado-3.jpeg"> | Luis Fernando, de 22 años, es estudiante de ingeniería con seis meses de experiencia en cocina. Es responsable, organizado y enfocado en la eficiencia operativa, destacando en la gestión de inventario y reutilización de insumos. Utiliza Excel para controlar reservas, reflejando un uso básico de tecnología. Su trabajo implica interacciones presenciales y telefónicas con clientes y proveedores. Busca optimizar procesos en la cocina, pero se frustra con la imprevisibilidad de la demanda de clientes y la falta de información precisa de proveedores. Su experiencia práctica le ha permitido desarrollar habilidades clave para enfrentar desafíos en la industria alimentaria. |
| Timing:   | URL: |

**Sección provedores**

| Entrevistado 4 | Eliana Rodríguez   |
| ------ | -- |
| Edad | |
| Distrito de residencia |  |
<img src="resources/entrevistado-4-eliana.jpeg"> | Eliana Rodríguez es proveedora de alimentos, principalmente verduras, para restaurantes, un negocio que inició durante la pandemia. Utiliza WhatsApp para coordinar pedidos y destaca por su puntualidad, la frescura de sus productos y la honestidad en el peso de sus entregas. A pesar de esto, enfrenta dificultades con el tráfico y siente que WhatsApp tiene limitaciones, especialmente en la gestión de pagos. Le gustaría una aplicación más avanzada que le permita gestionar pedidos de manera más eficiente, con listas fijas y sin restricciones en los montos de pago, facilitando su trabajo y mejorando la relación con sus clientes.|
| Timing:   | URL: |

| Entrevistado 5 | Bruno Minaya  |
| ------ | -- |
| Edad | 28 |
| Distrito de residencia | Surquillo  |
<img src="resources/entrevistado-5.jpeg"> | El entrevistado, de 29 años y soltero, reside en San Isidro, Lima. Es importador de comestibles para restaurantes, motivado por su pasión por la gastronomía desde joven. Se describe como empático y responsable, destacando su habilidad para generar confianza. Utiliza principalmente su celular y canales digitales como WhatsApp, Telegram y Zoom para su trabajo. Su principal objetivo es ampliar su cobertura de mercado y adaptarse a nuevos sistemas. Enfrenta frustraciones con la comunicación constante y la gestión de cambios en la demanda. Usa encuestas para medir la satisfacción del cliente y busca mejorar la gestión con aplicaciones más específicas.|
| Timing:   | URL: |

| Entrevistado 6 | Elizabeth Huanaco   |
| ------ | -- |
| Edad | 19 |
| Distrito de residencia | San Juan de Lurigancho |
<img src="resources/entrevistado-6.jpeg"> | Elis Deaco es proveedora de insumos para restaurantes y ayuda en el negocio familiar. Se caracteriza por ser organizada, responsable y hábil en negociación. Utiliza Notion para gestionar pedidos y WhatsApp para comunicarse con los clientes, prefiriendo su laptop y celular. Influenciada por marcas como Gloria y Nestlé, busca expandir su red de clientes y equilibrar su vida laboral y estudiantil. Sus frustraciones incluyen problemas de comunicación y coordinación de pedidos, así como la gestión del inventario. Desea una plataforma digital intuitiva para mejorar el seguimiento de pedidos, gestionar promociones y mantener un inventario flexible.|
| Timing:   | URL: |



### 2.2.3. Análisis de entrevistas.

<p>Las entrevistas revelan una necesidad común de integración tecnológica y optimización operativa en la industria gastronómica. Tanto administradores como proveedores enfrentan problemas con la previsión de demanda, la gestión de inventarios, y la falta de integración entre sistemas. Además, los proveedores mencionan la limitación de herramientas como WhatsApp para gestionar pedidos y pagos, mientras los administradores destacan la importancia de reportes y análisis de datos para la toma de decisiones. La solución ideal sería una plataforma integral e intuitiva que centralice la gestión, optimice la comunicación, y automatice procesos clave.</p>

### 2.3. Needfinding.
### 2.3.1. User Personas.

- Administrador de restaurante:

  <img src="./resources/user personas/Carlos Rodríguez.png" alt="Carlos Rodríguez"/>

- Proveedor:

  <img src="./resources/user personas/Ana Pérez.png" alt="Ana Pérez"/>

### 2.3.2. User Task Matrix.

<table border="1" style="text-align: center;">
	<tbody>
		<tr>
			<td colspan="1" rowspan="2">User Tax Matrix</td>
            <td colspan="2" rowspan="1">Segmento Objetivo 1</td>
            <td colspan="2" rowspan="1">Segmento Objetivo 2</td>
		</tr>
		<tr>
			<td colspan="1">Frecuencia</td>
            <td colspan="1">Importancia</td>
            <td colspan="1">Frecuencia</td>
            <td colspan="1">Importancia</td>
		</tr>
        <tr>
			<td colspan="1">Gestionar inventarios</td>
			<td colspan="1">multiple</td>
            <td colspan="1">alta</td>
            <td colspan="1">multiple</td>
            <td colspan="1">alta</td>
		</tr>
        <tr>
			<td colspan="1">Comunicarse con proveedores</td>
			<td colspan="1">multiple</td>
            <td colspan="1">alta</td>
            <td colspan="1">nunca</td>
            <td colspan="1">baja</td>
		</tr>
        <tr>
			<td colspan="1">Realizar pedidos de insumos</td>
			<td colspan="1">multiple</td>
            <td colspan="1">alta</td>
            <td colspan="1">nunca</td>
            <td colspan="1">baja</td>
		</tr>
        <tr>
			<td colspan="1">Revisar reportes de ventas y costos</td>
			<td colspan="1">multiple</td>
            <td colspan="1">alta</td>
            <td colspan="1">multiple</td>
            <td colspan="1">alta</td>
		</tr>
        <tr>
			<td colspan="1">Actualizar menú según disponibilidad</td>
			<td colspan="1">multiple</td>
            <td colspan="1">alta</td>
            <td colspan="1">nunca</td>
            <td colspan="1">baja</td>
		</tr>
        <tr>
			<td colspan="1">Recibir y procesar pedidos de restaurantes</td>
			<td colspan="1">nunca</td>
            <td colspan="1">baja</td>
            <td colspan="1">multiple</td>
            <td colspan="1">alta</td>
		</tr>
        <tr>
			<td colspan="1">Coordinar envíos</td>
			<td colspan="1">nunca</td>
            <td colspan="1">baja</td>
            <td colspan="1">multiple</td>
            <td colspan="1">alta</td>
		</tr>
        <tr>
			<td colspan="1">Negociar precios</td>
            <td colspan="1">nunca</td>
            <td colspan="1">baja</td>
            <td colspan="1">multiple</td>
            <td colspan="1">alta</td>
		</tr>
        <tr>
			<td colspan="1">Actualizar catálogo de productos</td>
			<td colspan="1">nunca</td>
            <td colspan="1">baja</td>
            <td colspan="1">multiple</td>
            <td colspan="1">alta</td>
		</tr>        
	</tbody>
</table>

### 2.3.3. User Journey Mapping.

- Administrador de restaurante:

  <img src="./resources/user journey/UJM Restaurante.png" alt="Carlos Rodríguez"/>

- Proveedor:

  <img src="./resources/user journey/UJM Proveedores.png" alt="Ana Pérez"/>

### 2.3.4. Empathy Mapping.

- Administrador de restaurante:

  <img src="./resources/emphaty mapping/Empathy map restaurante.png" alt="Carlos Rodríguez"/>

- Proveedor:

  <img src="./resources/emphaty mapping/Empathy map proveedor.png" alt="Ana Pérez"/>

### 2.3.5. As-is Scenario Mapping.

- Administrador de restaurante:

  <img src="./resources/as is/as is restaurante.png" alt="Carlos Rodríguez"/>

- Proveedor:

  <img src="./resources/as is/as is proovedor.png" alt="Ana Pérez"/>

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

En esta sección se mostrará el desarrollo visual del Landing Page. Para ello, se usuará la herramienta de diseño web Figma, debido a sus funciones y plugins que nos permite desarrollar el prototipo sin dificultades. Asimismo se evidenciará el uso de los Style Guidelines e Information architecture.

### 4.3.1. Landing Page Wireframe.

Trabajando con los wireframes anteriormente mostrados, luego se aplicó los Style Guidelines para el uso de los colores. Como se aprecia, estos tienen un contraste llamativo en cada sección de la landing page.

- Desktop:
  
  <img src="./resources/wireframes/desktop.png" alt="wireframe desktop"/>

- Mobile:

  <img src="./resources/wireframes/mobile.png" alt="wireframe mobile"/>

### 4.3.2. Landing Page Mock-up.

Después de haber trabajado con los wireframes previamente diseñados, se procedió a aplicar los Style Guidelines para definir la paleta de colores a utilizar. Se puede observar que estos colores presentan un contraste llamativo en cada sección de la landing page, lo que contribuye a destacar visualmente los distintos elementos y mejorar la legibilidad y la estética general del diseño.

<img src="./resources/mockup/mockup.png" alt="mockup"/>

[Link Figma](https://www.figma.com/design/wFyfD3jahh7mqHvwN2Vgst/Landing-Page-Wireframe-re-gril?node-id=0-1&t=Y6wxyMupDN9tDuuE-1)

### 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.2. Web Applications Mock-ups.
### 4.4.3. Web Applications User Flow Diagrams.
### 4.5. Web Applications Prototyping.
### 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.
<img src="resources/c4 diagram/contexto.png" alt="Context Diagram">

### 4.6.2. Software Architecture Container Diagrams.
<img src="resources/c4 diagram/contenedor.png" alt="Context Diagram">

### 4.6.3. Software Architecture Components Diagrams.
<ul>
  <li>
    <p>Usuarios</p>
    <img src="resources/c4 diagram/usuario.png" alt="Component Usuarios">
  </li>
  <li>
    <p>Ventas</p>
    <img src="resources/c4 diagram/ventas.png" alt="Component Ventas">
  </li>
  <li>
    <p>Reservas</p>
    <img src="resources/c4 diagram/reserva.png" alt="Component Reservas">
  </li>
  <li>
    <p>Rendimiento</p>
    <img src="resources/c4 diagram/rendimiento.png" alt="Component Rendimiento">
  </li>
  <li>
    <p>Inventario</p>
    <img src="resources/c4 diagram/inventario.png" alt="Component Inventario">
  </li>
  <li>
    <p>Gestor de proveedores</p>
    <img src="resources/c4 diagram/gestor.png" alt="Component Gestor">
  </li>
  <li>
    <p>Ajustes</p>
    <img src="resources/c4 diagram/ajustes.png" alt="Component Ajustes">
  </li>
</ul>

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
