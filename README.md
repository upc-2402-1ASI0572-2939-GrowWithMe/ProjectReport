# <p align="center" id="caratula"> Universidad Peruana de Ciencias Aplicadas </p>

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC">
</div>

### <p align="center"> Informe de TB1 </p>

<br>
<div align="center">
  <p> Carrera: Ingeniería de Software </p>
  <br>
  <p> Ciclo: 2025-01 </p>
  <br>
  <p> Curso: Desarrollo de soluciones IoT </p>
  <br>
  <p> NRC: 2939 </p>
  <br>
  <p> Profesor: León Baca, Marco Antonio </p>
  <br>
  <p> Nombre del Startup: Cup of Tech </p>
  <br>
  <p> Nombre del Producto: Grow With Me </p>
  <br>
  <p> Relación de Integrantes: </p>
  <p>  - Acuña Gomez, Diego Jose (u20201c794) </p>
  <p>  - Landeo Simeón, Favio Sebastián (u202119588) </p>
  <p>  - Morin Fuentes, Jean Pierre (u202115348) </p>
  <p>  - Noriega Suschenko, Anatoly Andrey (u202211813) </p>
  <p>  - Oneglio De Paz, Beth Shantal (u202213423) </p>
  <p>  - Tongo Alejandro, Milagros Salet (u20216078)</p>
  <br>
  <p> Mes y Año: Abril del 2025 </p>
</div>

---

# Registro de Versiones del Informe

<table>
  <tr>
    <th style="text-align:center;">Versión</th>
    <th style="text-align:center;">Fecha</th>
    <th style="text-align:center;">Autor</th>
    <th style="text-align:center;">Descripción de la modificación</th>
  </tr>
  <tr>
    <td align="center">TB1</td>
    <td>21/04/2025</td>
    <td> Diego Acuña <br> Favio Landeo <br> Jean Morin <br> Analoty Noriega <br> Beth Oneglio <br> Milagros Tongo </td>
    <td> Realizamos los capítulos 1, 2, 3 y 4 según la rúbrica de manera conjunta y eficiente.  </td>
  </tr>
</table>

---

# Project Report Collaboration Insights

TB1: Las tareas asignadas para la entrega TB1 se han completado y están documentadas en el repositorio de Github.

- Se escribieron y diagramaron los contenidos asignados a cada miembro en formato Markdown, seguido de commits para asegurar el progreso en el repositorio.

---

# Tabla de contenidos

- [ Universidad Peruana de Ciencias Aplicadas ](#-universidad-peruana-de-ciencias-aplicadas-)
    - [ Informe de Trabajo Final ](#-informe-de-trabajo-final-)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Tabla de contenidos](#tabla-de-contenidos)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1 Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3 Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1 Competidores](#21-competidores)
    - [2.1.1 Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3 Needfinding](#23-needfinding)
    - [2.3.1 User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4 Empathy Mapping](#234-empathy-mapping)
    - [2.3.5 As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4 Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2 User Stories](#32-user-stories)
  - [3.3 Impact Mapping](#33-impact-mapping)
  - [3.4 Product Backlog](#34-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1 Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1 EventStorming](#411-eventstorming)
      - [4.1.1.1 Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2 Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3 Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2 Context Mapping](#412-context-mapping)
    - [4.1.3 Software Architecture](#413-software-architecture)
      - [4.1.3.1 Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      - [4.1.3.2 Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      - [4.1.3.3 Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
  - [4.2 Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.1 Bounded Context: Profiles](#421-bounded-context-bounded-profiles)
      - [4.2.1.1 Domain Layer](#4211-domain-layer)
      - [4.2.1.2 Interface Layer](#4212-interface-layer)
      - [4.2.1.3 Application Layer](#4213-application-layer)
      - [4.2.1.4 Infrastructure Layer](#4214-infrastructure-layer)
      - [4.2.1.5 Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.1.6 Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.1.6.1 Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
      - [4.2.1.6.2 Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
    - [4.2.2 Bounded Context: Crops](#422-bounded-context-another-bounded-crops)
      - [4.2.2.1 Domain Layer](#4221-domain-layer)
      - [4.2.2.2 Interface Layer](#4222-interface-layer)
      - [4.2.2.3 Application Layer](#4223-application-layer)
      - [4.2.2.4 Infrastructure Layer](#4224-infrastructure-layer)
      - [4.2.2.5 Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.2.6 Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.2.6.1 Bounded Context Domain Layer Class Diagrams](#42261-bounded-context-domain-layer-class-diagrams)
      - [4.2.2.6.2 Bounded Context Database Design Diagram](#42262-bounded-context-database-design-diagram)
    - [4.2.3 Bounded Context: Devices](#423-bounded-context-third-bounded-devices)
      - [4.2.3.1 Domain Layer](#4231-domain-layer)
      - [4.2.3.2 Interface Layer](#4232-interface-layer)
      - [4.2.3.3 Application Layer](#4233-application-layer)
      - [4.2.3.4 Infrastructure Layer](#4234-infrastructure-layer)
      - [4.2.3.5 Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.3.6 Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.3.6.1 Bounded Context Domain Layer Class Diagrams](#42361-bounded-context-domain-layer-class-diagrams)
      - [4.2.3.6.2 Bounded Context Database Design Diagram](#42362-bounded-context-database-design-diagram)
    - [4.2.4 Bounded Context: Notifications](#423-bounded-context-third-bounded-notifications)
      - [4.2.4.1 Domain Layer](#4231-domain-layer)
      - [4.2.4.2 Interface Layer](#4232-interface-layer)
      - [4.2.4.3 Application Layer](#4233-application-layer)
      - [4.2.4.4 Infrastructure Layer](#4234-infrastructure-layer)
      - [4.2.4.5 Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.4.6 Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.4.6.1 Bounded Context Domain Layer Class Diagrams](#42361-bounded-context-domain-layer-class-diagrams)
      - [4.2.4.6.2 Bounded Context Database Design Diagram](#42362-bounded-context-database-design-diagram)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

---

# Student Outcome

**ABET – EAC - Student Outcome 5**
La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos. <br>

<table>
    <tr>
        <th style="text-align:center;">Criterio específico</th>
        <th style="text-align:center;">Acciones realizadas</th>
        <th style="text-align:center;">Conclusiones</th>
    </tr>
    <tr>
        <td align="center">Trabaja en equipo para proporcionar liderazgo en forma conjunta</td>
        <td>
            <strong>Acuña Gomez, Diego Jose</strong> <br>
            TB1 <br> Morbi vel tortor id eros dictum venenatis id dui. Mauris quis tellus eu nunc hendrerit vehicula ac id mauris. Pellentesque volutpat tellus non ligula blandit ullamcorper quis sodales erat.
            <br>
            TP1 <br>A lo largo del desarrollo de este proyecto, he trabajado promoviendo un entorno colaborativo donde cada integrante pudo aportar desde su experiencia. He contribuido activamente en la elaboración y definición de las User Stories, organizando reuniones clave para debatir el alcance del negocio y asegurar una visión compartida. Gracias a esta dinámica de trabajo conjunto, logramos completar con éxito las User Stories y desarrollar los 10 pasos del Event Storming
            <br><br>
            <strong>Landeo Simeón, Favio Sebastián</strong> <br>
            TB1 <br> Durante el desarrollo del proyecto colaboré activamente para lograr los objetivos grupales planeados. Gracias a ello logramos terminar exitosamente las User Stories, los 10 pasos del Event Storming y una Entrevista del segundo segmento objetivo.
            <br>
            TP1 <br> ...
            <br><br>
            <strong>Morin Fuentes, Jean Pierre</strong> <br>
            TB1 <br> Morbi vel tortor id eros dictum venenatis id dui. Mauris quis tellus eu nunc hendrerit vehicula ac id mauris. Pellentesque volutpat tellus non ligula blandit ullamcorper quis sodales erat.
            <br>
            TP1 <br> ...
            <br><br>
            <strong>Noriega Suschenko, Anatoly Andrey</strong> <br>
            TB1 <br> Durante el desarrollo de nuestro proyecto colaboré activamente a lo largo del mismo desarrollando las primeras versiones de las historias de usuario y el product backlog, el impact mapping, una de las entrevistas y los diagramas c4 Model contribuyendo con mi participación al equipo y desarrollar de manera eficaz y eficiente el proyecto.
            <br>
            TP1 <br> ...
            <br><br>
            <strong>Oneglio De Paz, Beth Shantal</strong> <br>
            TB1 <br> Colaboré activamente en equipo, asumiendo un rol de liderazgo compartido, lo que me permitió fortalecer mis habilidades blandas en organización. Gracias a ello, logramos concluir satisfactoriamente la Entrevista del primer segmento, el To-Be Scenario Mapping, las User Stories y el Product Backlog.
            <br>
            TP1 <br> ...
            <br><br>
            <strong>Tongo Alejandro, Milagros Salet</strong> <br>
            TB1 <br> Como parte del equipo, me encargué de realizar entrevistas y gestionar los bounded context canvas, contribuyendo activamente al liderazgo compartido y a la toma de decisiones grupales, lo que permitió avanzar de manera eficaz en el proyecto.
            <br>
            TP1 <br> ...
        </td>
        <td>
            Fusce cursus dolor et nulla suscipit, sit amet ullamcorper nibh vestibulum. Nam ornare massa eu lobortis porttitor. Nam ut erat feugiat libero pretium semper ac metus. Sed et eros dapibus, fermentum quam ut, bibendum lacus. Curabitur eget orci eget urna varius commodo.
        </td>
    </tr>
    <tr>
        <td align="center">Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</td>
        <td>
            <strong>Acuña Gomez, Diego Jose</strong> <br>
            TB1 <br> Durante este proyecto, me enfoqué en crear un entorno colaborativo e inclusivo donde todas las voces fueran escuchadas y valoradas. Establecí metas claras junto al equipo, planificamos tareas de forma estratégica y distribuimos responsabilidades de manera equitativa. Gracias a esta organización, pudimos avanzar de forma eficiente y cumplir los objetivos planteados, manteniendo siempre una comunicación abierta y un compromiso constante por parte de todos los miembros.
            <br>
            <br> 
            <br><br>
            <strong>Landeo Simeón, Favio Sebastián</strong> <br>
            TB1 <br> A través del proceso de desarrollo de este proyecto he ayudado a crear un entorno colaborativo para lograr cumplir el objetivo en común. Es por eso que hemos logrado concluir las User Stories, los 10 pasos del Event Storming y una entrevista del segundo segmento objetivo.
            <br>
            <br>
            <br><br>
            <strong>Morin Fuentes, Jean Pierre</strong> <br>
            TB1 <br> Cras est diam suscipit, malesuada ex rutrum, fringilla orci. Vestibulum in nunc quis elit suscipit sollicitudin.
            <br>
            <br>
            <br><br>
            <strong>Noriega Suschenko, Anatoly Andrey</strong> <br>
            TB1 <br> A lo largo del trabajo del proyecto he fomentado un entorno colaborativo e inclusivo dentro del equipo participando activamente en las tareas y revisando que ciertos puntos del trabajo fueran concretado aportando con las entrevistas  y digagramas del proyecto.
            <br>
            <br> 
            <br><br>
            <strong>Oneglio De Paz, Beth Shantal</strong> <br>
            TB1 <br> Fomenté un entorno colaborativo e inclusivo dentro del equipo, estableciendo metas claras, planificando tareas de manera estratégica y cumpliendo los objetivos propuestos. Esta experiencia fortaleció mis habilidades blandas en organización y liderazgo compartido, y permitió culminar con éxito el Entrevista del primer segmento, el To-Be Scenario Mapping, las User Stories y el Product Backlog.
            <br>
            <br>
            <br><br>
            <strong>Tongo Alejandro, Milagros Salet</strong> <br>
            TB1 <br> Colaboré en la creación de un ambiente inclusivo y organizado, donde establecí metas claras, planifiqué tareas específicas y aseguré que se cumplieran los objetivos, trabajando de cerca con el equipo y revisando constantemente los avances.
            <br>
            <br>
        </td>
        <td>
            Fusce mattis augue a nisl bibendum, quis fringilla neque scelerisque. Vivamus commodo libero eget venenatis imperdiet. Etiam imperdiet quam condimentum velit tempor porttitor. Suspendisse blandit nisl quis mauris vehicula faucibus.
        </td>
    </tr>
</table>

---

# Capítulo I: Introducción

## 1.1 Startup Profile

Nuestro proyecto se centra en proporcionar una solución que optimice la gestión de productos agrícolas, mejore la calidad de la producción y facilite las operaciones para los productores en la industria agrícola.

### 1.1.1 Descripción de la Startup

Nuestro proyecto agrícola surge a partir de la identificación de una necesidad no satisfecha en la gestión de productos agrícolas, ya que los productores enfrentan desafíos significativos en la supervisión y optimización de sus operaciones. La falta de herramientas precisas para el monitoreo y la toma de decisiones relacionadas con el riego, la conservación del suelo y la gestión de recursos agrícolas genera ineficiencias en sus procesos. Ante esta situación, hemos identificado una oportunidad para implementar una solución tecnológica que permita mejorar la eficiencia operativa y la calidad de los cultivos. Este software, a través del uso de dispositivos de monitoreo y análisis en tiempo real, proporcionará a los agricultores datos precisos sobre las condiciones de sus cultivos, optimizando decisiones clave y permitiendo un manejo más sostenible y rentable de sus recursos.

**Misión**  
Impulsar la transformación del sector agrícola mediante soluciones tecnológicas accesibles e innovadoras que optimicen la gestión de cultivos, mejoren la toma de decisiones y promuevan una agricultura más sostenible, eficiente y rentable para los productores.

**Visión**  
Ser la plataforma líder en innovación agrícola en Latinoamérica, reconocida por empoderar a los productores con herramientas inteligentes que revolucionan la forma en que cultivan, cuidan y gestionan sus recursos.


### 1.1.2 Perfiles de integrantes del equipo

#### - Diego Jose Acuña Gomez
Mi nombre es Diego Jose Acuña Gomez, tengo 23 años y actualmente estudio en la UPC, donde curso el noveno ciclo de Ingeniería de Software. Me especializo en desarrollo FrontEnd, con experiencia sólida en Angular, y me interesa mucho el enfoque ágil para colaborar eficientemente en equipo y construir productos de valor. Además, estoy explorando el mundo de la ciberseguridad como parte de mi formación profesional.
<img src="./assets/Diego.png" width="300"/>

#### - Favio Sebastián Landeo Simeón

Tengo 20 años y actualmente estoy cursando el noveno ciclo de la carrera de Ingeniería de Software. Estoy disponible para ayudar siempre a mis compañeros y además tiendo a generar buenas relaciones sociales con diferentes tipos de personas gracias a mi tolerancia y capacidad de trabajo en equipo. En mis tiempos libres me gusta escuchar música, jugar videojuegos y editar videos.

<img src="./assets/Favio.jpg" width="300"/>

#### - Jean Pierre Morin Fuentes
Mi nombre es Jean Pierre Morin Fuentes tengo 21 años, estoy  el noveno ciclo de la carrera ingenieria de software. Durante la carrera he podido conocer distintas herramientas, frameworks y lenguajes de programacion, de los cuales manejo, C++, Python, C#, Java, HTML entre otros.

<img src="./assets/Jean.jpeg" width="300"/>

#### - Anatoly Andrey Noriega Suschenko

Mi nombre es Anatoly Andrey Noriega Suschenko y soy muy apasionado a los videojuegos y a la programación en general. Actualmente tengo 20 años y estoy cursando el séptimo ciclo de mi carrera. Tengo cierto conocimiento y habilidad con los frameworks de Angular, Flutter y Vue. Domino lenguajes como C++, Python, Java, C#, HTML, CSS, GML, Javascript, entre otros.

<img src="./assets/Anatoly.png" width="300"/>

#### - Beth Shantal Oneglio De Paz

Mi nombre es Beth Shantal Oneglio De Paz - u202213423, tengo 20 años y estudio Ingeniería de Software en la UPC. Disfruto trabajar en equipo y resolver problemas digitales. Estoy capacitada para enfrentar situaciones estresantes con responsabilidad y liderazgo. Poseo conocimientos avanzados en gestión y programación, adquiridos en ciclos anteriores. Manejo lenguajes y tecnologías como Python, C++, HTML5, CSS3, .NET, Vue.js, C#, JavaScript, PHP, MongoDB, MySQL, entre otras.

<img src="./assets/Beth Foto.jpg" width="300"/>

#### - Milagros Salet Tongo Alejandro

Mi nombre es Milagros Salet Tongo Alejandro. Soy estudiante de Ingeniería de Software, en el séptimo ciclo, con experiencia en frontend y backend. Manejo frameworks como Angular y Vue, lo que me ha permitido desarrollar proyectos completos. Me considero una persona sociable y generosa, disfruto trabajando en equipo y creo que aprender de los demás es fundamental para mejorar tanto profesional como personalmente.

<img src="./assets/Milagros.jpg" width="300"/>

## 1.2 Solution Profile

Se encuentra compuesta por 2 secciones:

- Antecedentes y Problemática: Esta sección describe el problema que el proyecto tiene como objetivo resolver. En este se incluyen el enunciado del problema, una descripción de los puntos más importantes que debe resolver la solución, los objetivos y restricciones del proyecto.

- Lean UX Process: Esta sección aplica el Lean UX Process y describe de manera detallada cómo se resolverá el problema mediante el modelo de negocio.

### 1.2.1 Antecedentes y problemática

### Antecedentes

-Creciente demanda de alimentos debido al aumento de la población mundial.

-Necesidad de aumentar la productividad agrícola para satisfacer esta demanda.

-Desafíos asociados con el cambio climático y la sostenibilidad.

-Dificultad para monitorear y optimizar el crecimiento de los cultivos.

-Preocupaciones sobre la calidad y seguridad de los productos.

### Problemática (5Ws y 2Hs)

### What/Qué

#### ¿Cuál es el problema?

La gestión de productos agrícolas y la optimización de operaciones para productores en la industria agrícola.

### Where / Dónde

#### ¿Dónde está el usuario cuando usa el producto?

En áreas rurales y regiones agrícolas, campos de cultivos o huertas.

#### ¿Dónde surge el problema?

En las grandes y pequeñas empreas agricolas , asi como agricolas independientes.

### Why / Por Qué

#### ¿Cuál es la causa del problema?

Debido a la creciente demanda de alimentos, la necesidad de aumentar la productividad agrícola y los desafíos asociados con el cambio climático y la sostenibilidad.

### When / Cuándo

#### ¿Cuándo sucede el problema?

Cuando la población mundial está en constante crecimiento y la presión sobre la producción agrícola es cada vez mayor debido a factores como el cambio climático

### Who / Quién

#### ¿Quiénes están involucrados?

Productores agrícolas, empresas grandes y pequeñas del sector agroindustrial.

### How / Cómo

#### ¿En qué condiciones los usuarios usan nuestro producto?

Utilizando celulares, tablets, donde tienen colaboraciones con expertos en agricultura y desarrollo de soluciones personalizadas.

#### ¿Cómo nos conoceran los usuarios?

Los usuarios pueden conocer nuestra plataforma a través de diversas vías. Algunas de las más comunes incluyen:

- Boca a boca: La recomendación de amigos, familiares o colegas que ya han utilizado la plataforma y han tenido experiencias positivas.
- Redes sociales: Publicaciones, anuncios o menciones en plataformas como Facebook, Twitter, Instagram, entre otras.
- Colaboraciones con influencers: Asociaciones con figuras prominentes en el mundo de la literatura y el arte que promueven la plataforma a sus seguidores.

### How much / Cuánto

El impacto económico puede variar según el alcance y la implementación de las soluciones propuestas, pero el potencial de mejora en eficiencia y calidad es significativo.

### 1.2.2 Lean UX Process

#### 1.2.2.1 Lean UX Problem Statements

El desafío de los agricultores esta en la monitorización del crecimiento de cultivos, ya que la falta de herramientas efectivas para monitorear el crecimiento de los cultivos dificulta la identificación temprana de problemas, como condiciones climáticas adversas, lo que resulta en pérdidas de cosechas y disminución de la calidad de los productos, por otro lado Los productores agrícolas luchan por optimizar sus operaciones debido a la falta de herramientas, desde la planificación de cultivos hasta la gestión de la mano de obra y la logística, lo que limita su capacidad para aumentar la eficiencia y la productividad

#### 1.2.2.2 Lean UX Assumptions

#### Features

- Herramientas de monitorización del crecimiento de cultivos: Sensores agrícolas para recopilar datos sobre condiciones ambientales, humedad del suelo, y salud de los cultivos.
- Plataforma integrada de gestión agrícola: Suite de herramientas que abarca la planificación de cultivos, gestión de la mano de obra, monitoreo de inventario, programación de riego, y seguimiento de costos y funcionalidades de análisis de datos para identificar áreas de mejora y optimizar la eficiencia operativa en todas las etapas de la producción agrícola.

#### Business Outcomes

- Mejora de la eficiencia operativa: Reducción de los tiempos de inactividad y los costos asociados con la gestión manual de inventario y la resolución de problemas en la cadena de suministro y optimización de los procesos agrícolas mediante la automatización y la aplicación de datos en tiempo real para la toma de decisiones.

- Aumento de la rentabilidad: Reducción de las pérdidas debido a errores en la gestión de inventario, enfermedades de cultivos no detectadas y problemas logísticos y mejora de la productividad y la calidad de los productos agrícolas, lo que puede traducirse en mayores márgenes de beneficio para los productores.
- Reducción de riesgos y cumplimiento normativo: Mayor capacidad para responder rápidamente a problemas emergentes, como brotes de enfermedades o eventos climáticos extremos, minimizando el impacto en la producción y la distribución.

#### Users

Los usuarios son productores agrícolas, empresas agroindustriales grandes y pequeñas y expertos en agricultura.

#### User Outcomes & Benefits

- Productores agrícolas: Granjas y agrícolas que cultivan una variedad de productos, desde cultivos básicos hasta productos de especialidad

- Empresas agroindustriales grandes y pequeñas: Empresas dedicadas al procesamiento, envasado y distribución de productos agrícolas, incluyendo cooperativas y asociaciones de productores.

- Expertos en agricultura: Agrónomos, investigadores y consultores que proporcionan asesoramiento técnico y estratégico a los productores agrícolas para mejorar sus prácticas y rendimiento.

#### User assumptions

#### ¿Quién es el usuario?

El usuario es típicamente un productor agrícola o un gerente de una empresa agroindustrial que busca mejorar la eficiencia y calidad de la producción agrícola.

#### ¿Dónde encaja nuestro producto en sus trabajos o vidas?

Nuestro producto encaja en su día a día al facilitar la gestión de productos agrícolas, desde el cultivo hasta la distribución, optimizando operaciones y mejorando la calidad del producto final.

#### ¿Qué problema resuelve nuestro producto?

Nuestro producto resuelve problemas como la ineficiencia en la gestión de inventario, y la dificultad para monitorear el crecimiento de cultivos, mejorando la eficiencia operativa y la calidad de la producción agrícola.

#### ¿Cuándo y cómo es usado nuestro producto?

Nuestro producto es utilizado a lo largo de todo el ciclo de producción agrícola, desde la planificación de cultivos hasta la distribución, a través de una plataforma digital accesible desde dispositivos móviles o computadoras.

#### ¿Qué características son importantes?

Las caracteristicas de seguimiento de la cadena de suministro en tiempo real, gestión automatizada de inventario, herramientas de monitorización de cultivos, trazabilidad de productos, y análisis de datos para la toma de decisiones informadas.

#### ¿Cómo debería verse y comportarse nuestro producto?

Nuestro producto debe ser una interfaz intuitiva y fácil de usar, con visualizaciones claras de datos y herramientas de análisis poderosas. Debería ser confiable, escalable y adaptable a las necesidades específicas de cada usuario.

#### Business Assumptions

1. **Creemos que nuestros clientes necesitan** una solución que les permita gestionar eficientemente sus operaciones agrícolas, desde el cultivo hasta la distribución, mejorando la eficiencia y la calidad de la producción.
2. **Estas necesidades se pueden resolver con una** plataforma digital que integre funciones de seguimiento del clima, gestión de inventario, monitorización de cultivos y análisis de datos, proporcionando herramientas poderosas para la toma de decisiones informadas.
3. **El valor #1 que mi cliente quiere de mi servicio** es la mejora en la eficiencia operativa y la calidad de la producción agrícola, lo que les permite maximizar los rendimientos y la rentabilidad.
4. **El cliente también puede obtener beneficios adicionales como** un mejor manejo de sus cultivos ya que estaran atentos del clima y plagas y sabran como tratarlas.
5. **Voy a adquirir la mayoría de mis clientes** a través de campañas de marketing dirigidas a productores agrícolas y redes sociales.
6. **Haré dinero a través de** modelos de suscripción mensual o anual por el uso de nuestra plataforma.
7. **Mi competencia principal en el mercado** son otras soluciones de gestión agrícola existentes, tanto tradicionales como digitales.
8. **Los venceremos debido a la simplicidad** .y facilidad de uso de nuestra plataforma, así como a su capacidad para ofrecer una solución integral y altamente personalizable que se adapte a las necesidades específicas de cada cliente
9. **El mayor riesgo es que** los clientes no adopten nuestra solución debido a la resistencia al cambio o a la falta de conocimiento tecnollogico.
10. **Resolveremos esto a través de** demostraciones y pruebas gratuitas de nuestra plataforma, y proporcionando un sólido soporte al cliente para garantizar una implementación exitosa y una experiencia positiva del usuario.

#### 1.2.2.3 Lean UX Hypothesis Statements

### Hipótesis 1

**Creemos que** al implementar un sistema de seguimiento en tiempo real de la cadena de suministro agrícola
**Sabremos que** los productores podrán mejorar la visibilidad y la eficiencia de sus operaciones, reduciendo los tiempos de inactividad y los costos asociados

### Hipótesis 2

**Creemos** que al proporcionar herramientas de monitorización de cultivos basadas en datos en tiempo real
**Sabremos que** los productores podrán identificar y abordar de manera proactiva problemas de salud de los cultivos, mejorando así el rendimiento y la calidad de la cosecha

### Hipótesis 3

**Creemos que** al proporcionar análisis de datos avanzados y recomendaciones personalizadas para la gestión agrícola
**Sabremos que** los productores podrán tomar decisiones más informadas y estratégicas, mejorando la productividad y la rentabilidad de sus operaciones agrícolas.

#### 1.2.2.4 Lean UX Canvas

<TABLE BORDER>
	<TR>
		<TD ROWSPAN=2>
    Lean UX Canvas
    </TD>
	  <TD ROWSPAN=2></TD>
    <TD>Fecha: 6/04/2025</TD>
	</TR>
	<TR>
		<TD>Iteración 1

</TD> 
	</TR>
  <TR>
		<TD ROWSPAN>
      1. Problema de negocios: Los productores agrícolas enfrentan dificultades para gestionar eficientemente sus operaciones debido a los cambios climaticos y plagas , lo que resulta en ineficiencias en la cadena de suministro, pérdidas de cultivos y productos, y una falta de transparencia en la trazabilidad de los productos agrícolas.
    </TD>
	  <TD ROWSPAN=2>
      5. Ideas de solución: Desarrollar una aplicacion que integre seguimiento en tiempo real , monitorización del clima, y aviso de plagas.
    </TD> 
    <TD ROWSPAN=2>
      2. Resultados comerciales:
      <p> Mejora en la calidad del producto
      <p Reducción de pérdidas y desperdicios
      <p> Aumento de la satisfacción del cliente
    </TD>
	</TR>
	<TR>
		<TD>     
      3. Usuarios y Clientes: Pequeñas empresas y grandes empresas agrícolas.
    </TD> 
	</TR>
  <TR>
		<TD ROWSPAN=2>
      6. Hipótesis
      <p> Hipótesis 1:
      Creemos que al implementar un sistema de seguimiento en tiempo real de la cadena de suministro agrícola.
      Sabremos que los productores podrán mejorar la visibilidad y la eficiencia de sus operaciones, reduciendo los tiempos de inactividad y los costos asociados.
      <p> Hipótesis 2:
      Creemos que al proporcionar herramientas de monitorización de cultivos basadas en datos en tiempo real.
      Sabremos que los productores podrán identificar y abordar de manera proactiva problemas de salud de los cultivos, mejorando así el rendimiento y la calidad de la cosecha.
      <p> Hipótesis 3:
      Creemos que al proporcionar análisis de datos avanzados y recomendaciones personalizadas para la gestión agrícola.
      Sabremos que los productores podrán tomar decisiones más informadas y estratégicas, mejorando la productividad y la rentabilidad de sus operaciones agrícolas.
    </TD>
    <TD ROWSPAN=2>
      7. ¿Qué es lo más importante que debemos aprender primero?
      <p> Lo más importante que debemos aprender primero es comprender a fondo las necesidades y desafíos específicos de nuestros usuarios y clientes en la industria agrícola. Esto incluye entender sus procesos operativos, identificar los problemas más urgentes que enfrentan en la gestión de cultivos y conocer sus expectativas y prioridades en cuanto a soluciones tecnológicas.
    </TD>
    <TD>
      4. Beneficios del usuario:
      <p> - Mejora de la eficiencia operativa y la rentabilidad para los productores agrícolas.
      <p> - Reducción de pérdidas de cultivos y productos debido a una gestión más eficiente de la cadena de suministro.
    </TD>
	</TR>
	<TR>
		<TD>
      8. ¿Cuál es la menor cantidad de trabajo que necesitamos para resolver las dudas y para hacer lo siguiente más importante?
      <p> La menor cantidad de trabajo que necesitamos para resolver las dudas y avanzar en lo siguiente más importante es realizar una investigación inicial centrada en los usuarios y clientes potenciales. Esto puede incluir , encuestas u otros métodos de investigación para comprender mejor sus necesidades, desafíos y expectativas. 
      <p> Una vez que tengamos una comprensión sólida de las necesidades de los usuarios, podemos priorizar el desarrollo de características y funcionalidades de nuestra solución que aborden directamente esos problemas identificados. Esto nos permitirá enfocarnos en lo más importante para nuestros usuarios y garantizar que nuestra solución sea relevante y útil desde el principio
    </TD>
  </TR>
</TABLE>

---

## 1.3 Segmentos objetivo

<TABLE BORDER>
  <TR>
    <TD><strong>Tipo de usuario</strong></TD>
    <TD><strong>Geográfico</strong></TD>
    <TD><strong>Psicográfico</strong></TD> 
    <TD><strong>Demográfico</strong></TD>
  </TR>
  <TR>
    <TD>Pequeños y Grandes Agricultores</TD> 
    <TD>Puede estar ubicado en cualquier campo o zona de cultivo.</TD> 
    <TD>
      - Busca mejorar la eficiencia y calidad de su producción.<br>
      - Creativo y curioso.<br>
      - Desea apoyo en su cultivo.
    </TD> 
    <TD>
      - Edad: desde adultos jóvenes hasta adultos mayores.
    </TD>
  </TR>
  <TR>
    <TD>Consultores</TD> 
    <TD>Especializados en el rubro agrícola.</TD> 
    <TD>
      - Quiere ayudar a las empresas pequeñas y grandes a tener un mejor cuidado con sus plantas.<br>
      - Desea estar atento a las peticiones de contrato y ayuda de los clientes.<br>
      - Le gusta ver que sus clientes salgan satisfechos con sus consejos.
    </TD> 
    <TD>
      - Edad: Desde adultos jóvenes hasta adultos mayores.
    </TD>
  </TR>
</TABLE>


# Capítulo II: Requirements Elicitation & Analysis

## 2.1 Competidores

Dentro del mercado al que planeamos brindar una solución, pudimos identificar varios competidores que ofrecen una solución con un enfoque similar para la gestión agrícola. A continuación, resumiremos su solución de Software:

**Agrobit:** Agrobit es una herramienta de gestión de gestión agrícola y ganadera que busca nuevas formas de producir alimentos de manera sustentable y rentable. Esta solución tiene como enfoque las grandes empresas. Su plataforma cuenta con funciones como, control de actividades, evolución de cultivos y monitoreo predictivo y trazabilidad y huella de carbono. <br>
**Efemis:** Efemis es una plataforma digital para la gestión agricola, utiliza imagenes satelitales, predicciones del clima y sensores para controlar los costes y optimizar los costes de operaciones agricolas. Es una iniciativa creada por hispatec que cuenta con soluciones diferentes para el sector agrícola para tareas más especificas, sin embargo, Efemis es la principal.<br>
**Agri:** Agri es un software especializado en el sector agrícola que permite gestionar órdenes de aplicación, control de faenas, cosecha y riego, entre otras funciones. Para acceder a sus servicios, el territorio agrícola debe ser revisado y categorizado por el tamaño del mismo, posteriormente se hace un cobro mensual que va desde 320 dólares para las pequeñas empresas agrícolas hasta 715 dólares para las empresas agrícolas grandes.<br>

### 2.1.1 Análisis competitivo

¿Por qué llevar a cabo este análisis?
Debemos llevar a cabo este análisis para poder saber en que se especializan nuestros competidores directos y poder encontrar algún aspecto en el que podamos destacar y llamar la atención del mercado objetivo.
| Nombre                   | [GrowWithMe]                                                                                                                                                                                                                 | [Agrobit]                                                                                                                                                                                                                                                                                                                          | [Efemis]                                                                                                                                                  | [Agri]                                                                                                                      |
| ------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Overview                 | Software de gestión agricola centrado en la capacitación del usuario que puede adaptarse a sus necesidades                                                                                                                   | Software enfocado en la gestión de procesos agrícolas y ganaderos con ayuda de herramientas de alta gama                                                                                                                                                                                                                           | Software de hispatec que gestiona procesos agrícolas utilizando herramientas de alta gama                                                                 | Agri es una solución de software latina que permite gestionar campos de cultivo de forma centralizada                       |
| Ventaja Competitiva      | Esta aplicación está entrada en el usuario y su adaptabilidad, brindandole a este una opción cómoda al alcane de sus manos                                                                                                   | Uso de herramientas de alta gama como imagenes satelitales que son una alternativa que brinda una seguridad total                                                                                                                                                                                                                  | Este software modular, está diseñado para que el usuario quiera añadir más funcionalidades que se acoplen a sus necesidades                               | Empresa latinoamericana con la que los usuarios se sienten más cómodos                                                      |
| Mercado Objetivo         | Nos enfocaremos en los pequeños y grandes agricultores que no hayan implementado tecnología para aligerar su carga laboral                                                                                                   | Se centra en el sector ganadero y agrícola que buscan implementar una solucion tecnológica con herramientas de gama alta, como imagenes satelitales                                                                                                                                                                                | Sector agrícola grande que busca una solución de software para agilizar procesos                                                                          | Está centrado en pequeñas, medianas y grandes empresas agrícolas                                                            |
| Estrategias de marketing | Nos acercaremos a los empresarios agrícolas que no confían en la tecnología para que podamos demostrar la eficacia de esta                                                                                                   | Se promociona mediante publicidad como google ads, correos,etc.                                                                                                                                                                                                                                                                    | Utiliza publicidad y estrategias de marketing                                                                                                             | Agri usa sus redes sociales como Instagram y Linkedin para poder difundir sus propuestas de valor                           |
| Productos y Servicios    | Ofrecemos una amplia variedad de recursos para el usuario como, control de inventario, predicciones del clima, sensores de humedad y temperatura, monitoreo de ventas, predicciones para las cosechas y un control de ventas | Cuenta con dos versiones, la ECO, una versión dedicada para una producción netamente sostenible, y la Enterprise, dedicada a conseguir el mayor beneficio económico para la empresa. Ambas opciones cuentan con planes de pago diferentes que varían, dandole a las grandes empresas agricolas más ventajas que a las más pequeñas | Efemis cuenta con un control de costos de operaciones, monitoreos de cumplimiento de normativas,gestion de actividades, tratamientos y riegos,entre otras | Agri cuenta con controles de faenas, compras y bodegaje, control de riego, entre otros.                                     |
| Precios y Costos         | Planeamos cobrar una comisión por venta de productos, los usuarios podrán acceder a nuestros servicios sin mayor problema                                                                                                    | Agrobit cuenta con planes mensuales que rondan los 250 hasta los 1100 dólares                                                                                                                                                                                                                                                      | Cuenta con planes principalmente desde los 300 hasta los 900 euros mensuales                                                                              | Cuenta con 3 planes para los pequeños, medianos y grandes agricultores cuyos costos van desde los 320 hasta los 750 dólares |
| Fortalezas               | Contamos con un software ágil, que se verá sujetos a cambios rápidos para acomodarnos a las necesidades del usuario                                                                                                          | Cuenta con una reputación y una clientela fiel                                                                                                                                                                                                                                                                                     | Es parte de una corporación grande que facilita acceso a herramientas de gama alta                                                                        | Cuenta con clientes en todo latinoamerica sobre todo Chile y Perú                                                           |
| Debilidades              | Sujeta a pruebas                                                                                                                                                                                                             | Está cerrada a sus clientes habituales y los clientes nuevos no parecen interesados en su producto                                                                                                                                                                                                                                 | No cuenta con una gran cantidad de clientes, las reseñas no son buenas y está siendo dejada de lado                                                       | No parece querer modernizarse más allá de su estado actual                                                                  |
| Oportunidades            | Muchas de las gestiones agrícolas en nuestro país son deficientes y gran parte de las cosechas son desperdiciadas, por ello el Perú es un país ideal para implementar GrowWithMe                                             | Dadas sus herramientas presenta una estabilidad que les permitiría desarrollarse más                                                                                                                                                                                                                                               | Cuenta con acceso a herramientas de gama alta que permiten el recopilado de información detallada para beneficio del usuario                              | Cuenta con el apoyo de clientes de más de un país por ello pueden expandirse por todo latinoamerica                         |
| Amenazas                 | La implementación de herramientas costosas por parte de la competencia                                                                                                                                                       | Dado que el proceso de cotización es lento, muchos clientes prefieren buscar otras opciones                                                                                                                                                                                                                                        | Sus ventas se han visto reducidas                                                                                                                         | La creciente tecnología y el uso de la inteligencia artificial puede desplazar a muchas soluciones de software              |

### 2.1.2 Estrategias y tácticas frente a competidores

Nos enfocaremos en el sector que no cuenta con tecnología, brindando una solución accesible e intuitiva para que personas que no están familiarizadas con el apartado tecnológico puedan dominar para el uso eficiente de sus recursos.
<br><br>
**Estrategia general**: Diferenciacición <br>
**Objetivo principal:** Destacar ante la competencia enfocandonos en hacer un producto que pueda satisfacer necesidades específicas de nuestros segmentos objetivos.
<br> <br>
**Estrategias Clave:**<br>

<ul>
    <li>Enfoque al usuario: Concentrarse en hacer mejoras basadas en lo que nuestros clientes soliciten </li>
    <li>Control de usuarios: Nuestra aplicación contará con una red interconectada de usuarios en las que se puede llevar un control de los trabajadores bajo el mando del usuario administrador</li>
</ul>

## 2.2 Entrevistas

### 2.2.1 Diseño de entrevistas

**Segmento 1: Agricultores y pymes agrícolas**<br>
1. ¿Cuáles son los cultivos principales que gestionas y qué factores consideras más importantes al tomar decisiones sobre su riego?
2. ¿Cuáles son los mayores desafíos que enfrentas en la gestión del riego en tus cultivos?
3. ¿Qué herramientas o tecnologías utilizas actualmente para gestionar el riego y cómo impactan en la eficiencia de tus cultivos?
4. ¿Cómo tomas decisiones sobre cuándo regar tus cultivos y qué herramientas usas para ello?
5. ¿Qué factores (como la humedad del suelo, las condiciones climáticas o el tipo de cultivo) consideras al programar el riego?
6. ¿Has utilizado alguna vez sensores o dispositivos para monitorear las condiciones de tus cultivos? Si es así, ¿cómo te han ayudado?
7. ¿Qué opinas sobre el uso de una aplicación móvil que te ayude a gestionar el riego y otros aspectos de tus cultivos?
8. ¿Cuál consideras que es la principal barrera para adoptar nuevas tecnologías de monitoreo y automatización en el riego?
9. ¿Qué beneficios esperarías de una solución que te ayude a gestionar el riego de manera más precisa y optimizada según las condiciones reales de tus cultivos?
10. ¿Te gustaría que la solución te ayudara también con la gestión de otros recursos agrícolas, como fertilizantes o control de plagas?

**Segmento 2: Consultores agrícolas**<br>
1. ¿Cómo crees que la tecnología puede mejorar la gestión del riego en los cultivos?
2. ¿Qué desafíos has identificado en el sector agrícola con respecto a la eficiencia del uso del agua y el riego?
3. ¿Qué tecnologías o soluciones actuales ves como más prometedoras para mejorar el manejo del riego en la agricultura?
4. ¿Cómo crees que una aplicación que utilice datos sobre la humedad del suelo y otros parámetros podría cambiar las prácticas de riego?
5. ¿Cuál es tu opinión sobre el uso de tecnologías automáticas para tomar decisiones más precisas sobre el riego y cómo impactaría esto en la productividad?
6. ¿Qué beneficios ofrecería una solución que te ayude a gestionar los recursos de manera más eficiente en cultivos agrícolas?
7. ¿Consideras que los agricultores están preparados para adoptar tecnologías como los sensores para el riego? ¿Por qué?
8. ¿Qué tipo de capacitación o soporte sería necesario para que los agricultores adopten nuevas soluciones tecnológicas para el riego?
9. ¿Cómo evaluarías el impacto de una solución tecnológica en la sostenibilidad de las prácticas agrícolas?
10. ¿Qué aspectos adicionales consideras importantes al desarrollar una solución para la gestión del riego y otros recursos agrícolas?

### 2.2.2 Registro de entrevistas
 
**Segmento 1: Agricultores y pymes agrícolas**

Todas la entrevistas se encuentran en el siguiente URL: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202116078_upc_edu_pe/EUjElqA2GVNOuGcMu_3hJJYBPi5VQ-bHC4DnneCE9LZhDw?e=x9rtA0&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>

|                             **Entrevista 1**                              |                                                                                                                                                                                                                                                              **Juan Jesús Calisaya Sánchez**                                                                                                                                                                                                                                                              |
| :-----------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                           <center>Edad</center>                           |                                                                                                                                                                                                                                                                 <center>21 Años</center>                                                                                                                                                                                                                                                                  |
|                         <center>Distrito</center>                         |                                                                                                                                                                                                                                                                   <center>Lima</center>                                                                                                                                                                                                                                                                   |
| <center> <img src="./assets/Entrevista Juan.png" width="600"/> </center>  |                                 <center>Juan cultiva papa, choclo y hortalizas. Decide cuándo regar observando las plantas, el clima y la humedad del suelo. Los desafíos incluyen la escasez de agua y el riego desigual. Aunque usa herramientas tradicionales, está interesado en una aplicación móvil de riego si es fácil y económica. La principal barrera para adoptar nuevas tecnologías es el costo y la falta de conocimiento. Le gustaría que la solución también gestionara fertilizantes y plagas.</center>                                  |
|                         <center>Timing: </center>                         |                                                                                                                                                                                                                                                                  <center>URL: </center>                                                                                                                                                                                                                                                                   |
|                             **Entrevista 2**                              |                                                                                                                                                                                                                                                               **Aaron Elias Acuña Alarcon**                                                                                                                                                                                                                                                               |
|                           <center>Edad</center>                           |                                                                                                                                                                                                                                                                 <center>21 Años</center>                                                                                                                                                                                                                                                                  |
|                         <center>Distrito</center>                         |                                                                                                                                                                                                                                                                   <center>Lima</center>                                                                                                                                                                                                                                                                   |
| <center> <img src="./assets/Entrevista Aaron.png" width="600"/> </center> | <center>Aaron cultiva papa, maíz, zanahoria y lechuga. Toma decisiones de riego basándose en el clima, la humedad del suelo y el estado visual de las plantas. Entre los principales desafíos menciona el riego ineficiente y la dificultad para coordinarlo entre diferentes cultivos. Actualmente usa métodos tradicionales y aplicaciones de clima, pero no cuenta con sensores. Está interesado en una aplicación móvil sencilla que lo ayude con el riego. Le gustaría que la solución también le ayude a gestionar fertilizantes y plagas.</center> |
|                         <center>Timing: </center>                         |                                                                                                                                                                                                                                                                  <center>URL: </center>                                                                                                                                                                                                                                                                   |
|                             **Entrevista 3**                              |                                                                                                                                                                                                                                                                           ****                                                                                                                                                                                                                                                                            |
|                           <center>Edad</center>                           |                                                                                                                                                                                                                                                                    <center> </center>                                                                                                                                                                                                                                                                     |
|                         <center>Distrito</center>                         |                                                                                                                                                                                                                                                                    <center> </center>                                                                                                                                                                                                                                                                     |
|                            <center> </center>                             |                                                                                                                                                                                                                                                                    <center> </center>                                                                                                                                                                                                                                                                     |
|                         <center>Timing: </center>                         |                                                                                                                                                                                                                                                                  <center>URL: </center>                                                                                                                                                                                                                                                                   |

**Segmento 2: Consultores agrícolas**

|                              **Entrevista 1**                              |                                                                                                                                                                                                                                                                                                                                                 **Jeyson Alejandro Rocca**                                                                                                                                                                                                                                                                                                                                                  |
| :------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                           <center>Edad</center>                            |                                                                                                                                                                                                                                                                                                                                                  <center>25 Años</center>                                                                                                                                                                                                                                                                                                                                                   |
|                         <center>Distrito</center>                          |                                                                                                                                                                                                                                                                                                                                                    <center>Lima</center>                                                                                                                                                                                                                                                                                                                                                    |
| <center> <img src="./assets/Entrevista Jeyson.png" width="600"/> </center> | <center>Jeyson, ingeniero agrónomo, destacó que la automatización de procesos y la optimización del uso de recursos, especialmente el agua, son claves para mejorar la gestión del riego en la agricultura. Señaló que los desafíos del sector están en la eficiencia del riego y el uso adecuado de los recursos. Considera que tecnologías como sensores y aplicaciones basadas en datos del ambiente y del suelo podrían facilitar estos procesos. Sin embargo, subrayó que, aunque en Lima existe mayor acceso a estas tecnologías, en las provincias los agricultores no están tan capacitados para adoptarlas, por lo que las soluciones deben ser intuitivas y fáciles de usar para garantizar su adopción.</center> |
|                         <center>Timing: </center>                          |                                                                                                                                                                                                                                                                                                                                                   <center>URL: </center>                                                                                                                                                                                                                                                                                                                                                    |
|                              **Entrevista 2**                              |                                                                                                                                                                                                                                                                                                                                                **Mario Jesús Estrada Ruiz**                                                                                                                                                                                                                                                                                                                                                 |
|                           <center>Edad</center>                            |                                                                                                                                                                                                                                                                                                                                                  <center>25 Años </center>                                                                                                                                                                                                                                                                                                                                                  |
|                         <center>Distrito</center>                          |                                                                                                                                                                                                                                                                                                                                                   <center>Lima </center>                                                                                                                                                                                                                                                                                                                                                    |
| <center> <img src="./assets/Entrevista Mario.png" width="600"/> </center>  |                              <center>Mario Estrada trabaja como practicante en una empresa en el rubro agrícola, estudiante de la carrera de Ingeniería Ambiental. Se puede destacar que desde su experiencia las herramientas IoT ya están siendo implementadas. Además, también puntúa que los recursos se podrían manejar de manera más eficiente dentro del ámbito empresarial, él propondría incluir más tecnología en poder detectar deficiencias en el óptimo uso de los recursos como el agua, la electricidad, etc. Por último señaló que cualquier persona con capacitación podría utilizar los dispositivos IoT que se requieren para una buena gestión de los cultivos. </center>                               |
|                         <center>Timing: </center>                          |                                                                                                                                                                                                                                                                                                                                                   <center>URL: </center>                                                                                                                                                                                                                                                                                                                                                    |
|                              **Entrevista 3**                              |                                                                                                                                                                                                                                                                                                                                                **Camila Pinedo**                                                                                                                                                                                                                                                                                                                                                 |
|                           <center>Edad</center>                            |                                                                                                                                                                                                                                                                                                                                                  <center>29 Años </center>                                                                                                                                                                                                                                                                                                                                                  |
|                         <center>Distrito</center>                          |                                                                                                                                                                                                                                                                                                                                                   <center>Lima </center>                                                                                                                                                                                                                                                                                                                                                    |
| <center> <img src="" width="600"/> </center>  |                              <center>Camila Pinedo señala que la tecnología puede optimizar el riego agrícola al hacerlo más preciso y eficiente. Identifica como principales retos la falta de acceso, capacitación y resistencia al cambio. Destaca el potencial de sensores, automatización e inteligencia artificial para mejorar el manejo del agua. Considera que una app con datos del suelo y clima facilitaría decisiones más acertadas. Aunque algunos agricultores están preparados, muchos necesitan capacitación y soporte. Finalmente, resalta que toda solución debe ser simple, adaptable y diseñada con enfoque local. </center>                               |
|                         <center>Timing: </center>                          |                                                                                                                                                                                                                                                                                                                                                   <center>URL: </center>                                                                                                                                                                                                                                                                                                                                                    |

## 2.3 Needfinding

### 2.3.1 User Personas

![UserPersonFarmer](assets/UserPersonaFarmer.png)
![UserPersonaConsultant](assets/UserPersonaConsultant.png)

### 2.3.2 User Task Matrix

| **User Task Matrix**                           | **Aldo Gómez (Agricultor)** |                  | **Antonio Herrera (Consultor)** |                  |
|------------------------------------|------------------------------|------------------|----------------------------------|------------------|
|                                    | **Frecuencia**               | **Importancia**  | **Frecuencia**                   | **Importancia**  |
| Planificar el cultivo de la temporada | Media                       | Alta             | Media                            | Alta             |
| Comunicarse con trabajadores       | Media                        | Alta             | Media                            | Alta             |
| Seguimiento de cultivos            | Alta                         | Alta             | Alta                             | Alta             |
| Revisión de pronóstico del clima   | Media             | Media            | Media                            | Alta             |
| Riego de plantas                   | Baja          | Alta             | Baja                             | Alta             |
| Identificación de pestes           | Baja          | Alta             | Media                            | Alta             |
| Peaje de cosechas                  | Baja                         | Alta             | Baja                             | Alta             |

### 2.3.3 User Journey Mapping

**Segmento 1: Agricultores y pymes agrícolas** <br>
![UserJourneyFarmer](assets/UserJourneyFarmer.png) <br>
**Segmento 2: Consultores agrícolas** <br>
![UserJourneyConsultant](assets/UserJourneyConsultant.png)

### 2.3.4 Empathy Mapping

**Segmento 1: Agricultores y pymes agrícolas** <br>
![EmpathyMapFarmer](assets/EmpathyMapFarmer.png) <br>
**Segmento 2: Consultores agrícolas** <br>
![EmpathyMapConsultant](assets/EmpathyMapConsultant.png)

### 2.3.5 As-is Scenario Mapping

**Segmento 1: Agricultores y pymes agrícolas** <br>
![AsIsMapFarmer](assets/AsIsMapFarmer.png)
**Segmento 2: Consultores agrícolas** <br>
![AsIsMapConsultant](assets/AsIsMapConsultant.png)

## 2.4 Ubiquitous Language

Ubiquitous language o lenguaje ubicuo hace referencia al lenguaje que puede ser entendido en cualquier parte, esta sección tiene como intención permitirle a personas sin vocabulario de un Ingeniero de software puedan entender. A continuación, mostraremos un glosario con contenido de este proyecto:

<ul>
  <li> Crop: El significado literal es cultivo y usaremos el término como entidad, servicio y componente durante el desarrollo del código. </li>
  <li> Employee: Significa empleado y lo estaremos usando para realizar entidades, servicios y componentes. </li>
  <li> Harvest: El proceso de recoger cultivos madurados de los campos de cultivo. </li>
  <li> Irrigation: La aplicación artificial de agua a la tierra para ayudar en la producción de cultivos. </li>
  <li> Fertilizer: Sustancias que se aplican al suelo del cultivo para incrementar su fertilidad y rendimiento. </li>
  <li> Pesticide: Son químicos utilizados para controlar, repeler y/o eliminar pestes del cultivo. </li>
  <li> Crop rotation: Es la práctica de cultivar diferentes tipos de plantas al mismo tiempo en el mismo área en estaciones secuenciales. </li>
  <li> Fumigation: Es un método de control de pestes o de eliminar microorganismos dañinos en un área específico mediante gases pesticidas. </li>
  <li> Germination: Significa el comienzo del crecimiento, ya sea de una semilla, espora o brote, en respuesta a la temperatura correcta y agua. </li>
</ul>

---

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

Para elaborar el To-be Scenario Mapping, el equipo definió cómo sería el flujo de trabajo después de la implementación de nuestra solución, GrowWithMe, para ambos segmentos objetivos. El propósito de este artefacto es comparar y abordar los aspectos negativos identificados en el As-is Scenario.

**Segmento 1: Agricultores y pymes agrícolas**

<img src="./assets/To Be Agricultores.png" width="600"/>

**Segmento 2: Consultores agrícolas**

<img src="./assets/To Be Consultores.png" width="600"/>

Enlace del Miro: [To-Be Scenario Mapping](https://miro.com/welcomeonboard/bno3SFQ0ajhWdW9HaXpPTkxuZENJUjVFaEtMdDJ2UVBKaUZYNzhTNEx6Y3dCK2hPNThHbUVDZ3dKbS80dTBGVzkxcjh3WG1rWGZUQTh6QWl2VEhUSnpzMHQ2Zi9lU0JoMzVDdmExc0NDYXQ5VDlySlRwWXE3d3BoSmJvNnI1VElNakdSWkpBejJWRjJhRnhhb1UwcS9BPT0hdjE=?share_link_id=96167492984)

## 3.2. User Stories

| **User/Technical Story ID** | **Título**                           | **Descripción**                                                                                      | **Criterios de Aceptación**                                                                                                                                                                | **Relacionado con (Epic ID)**      |
|---------------------|--------------------------------------|------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------|
| EPIC01      | Experiencia del Visitante en la Landing Page       | Como visitante de la plataforma, quiero ver de manera clara y simple cómo el sistema IoT puede ayudar a los agricultores, con ejemplos, imágenes e información relevante, para entender su utilidad y beneficios. | No corresponde. | No corresponde. |
| EPIC02      | Gestión de Cultivos                                | Como agricultor, quiero gestionar mis cultivos para mantener un control eficiente.                                                              | No corresponde. | No corresponde. |
| EPIC03      | Dispositivos IoT                                   | Como agricultor, quiero gestionar mis dispositivos IoT para automatizar el monitoreo.                                                           | No corresponde. | No corresponde. |
| EPIC04      | Configuración de perfil                            | Como agricultor, quiero personalizar mi perfil para mantenerlo actualizado.                                                                     | No corresponde. | No corresponde. |
| EPIC05      | Dashboard de datos                                 | Como agricultor, quiero exportar los datos de mis cultivos para analizarlos externamente.                                                       | No corresponde. | No corresponde. |
| EPIC06      | Notificaciones al agricultor                       | Como agricultor, quiero recibir y gestionar notificaciones importantes sobre mis cultivos.                                                      | No corresponde. | No corresponde. |
| EPIC07      | Interacción Consultor-Agricultor                   | Como consultor, quiero interactuar con los agricultores para darles asistencia técnica.                                                         | No corresponde. | No corresponde. |
| EPIC08      | Desarrollo de una API REST para la gestión de la agricultura | Como equipo, queremos tener una API REST completa para que me permita gestionar eficientemente todas las operaciones agrícolas de los agricultores, consultores y dispositivos IoT. | No corresponde. | No corresponde. |
| US01 | Diseño informativo y atractivo | Como visitante, quiero una landing page clara y atractiva que explique los beneficios del sistema IoT para la agricultura, con ejemplos e imágenes, para entender su utilidad y beneficios. | **Escenario 1: Visualización clara y completa de la landing page**<br>Dado que un visitante accede a la landing page, cuando la página carga completamente, entonces se muestra una interfaz organizada con secciones de beneficios, ejemplos e imágenes y la información es presentada de manera sencilla y comprensible. | EPIC01 |
| US02 | Funcionalidad de botones Call-to-Action | Como visitante, quiero disponer de botones y enlaces estratégicos para acceder a más información, facilitando mi interacción con el producto. | **Escenario 1: Funcionamiento correcto de los botones de llamada a la acción**<br>Dado que un visitante visualiza la landing page, cuando hace clic en alguno de los botones del header para buscar más información, entonces es redirigido a la sección o página correspondiente sin errores y la transición es rápida y clara. | EPIC01 |
| US03 | Registrar cultivos | Como agricultor, quiero registrar mis cultivos para tener un control personalizado. | **Escenario 1: Registro de cultivo exitoso** <br> Dado que estoy en la sección "Mis Cultivos", cuando ingreso un nuevo cultivo con todos los campos obligatorios, entonces debería guardarse exitosamente. <br> **Escenario 2: Registro de cultivo fallido** <br> Dado que no completo los campos requeridos, cuando intento registrar un cultivo, entonces debería mostrarse un mensaje de error. | EPIC02 |
| US04 | Gestionar cultivos | Como agricultor, quiero editar y eliminar cultivos para mantener mi información actualizada. | **Escenario 1: Edición o eliminación exitosa** <br> Dado que estoy en la vista de mis cultivos, cuando edito o elimino uno correctamente, entonces los cambios deberían reflejarse. <br> **Escenario 2: Eliminación no confirmada** <br> Dado que intento eliminar un cultivo, cuando no confirmo la acción, entonces no debería eliminarse. | EPIC02 |
| US05 | Añadir actividad al calendario | Como agricultor, quiero añadir actividades a mi calendario para planificar mis tareas de cultivo. | **Escenario 1: Actividad añadida exitosamente**  <br> Dado que accedo a "Mis Cultivos" y luego a "Calendario de actividades", cuando ingreso una nueva actividad con todos los datos requeridos, entonces debe añadirse correctamente. <br> **Escenario 2: Datos incompletos** <br> Dado que dejo campos vacíos, cuando intento guardar la actividad, entonces debe mostrarse un mensaje de error. | EPIC02 |
| US06 | Ver calendario de actividades | Como agricultor, quiero ver un calendario con riegos, siembras y cosechas para planificarme. | **Escenario 1: Visualización con actividades** <br> Dado que tengo actividades registradas, cuando accedo al calendario, entonces deberían mostrarse organizadas por fecha. <br> **Escenario 2: Calendario vacío** <br> Dado que no hay actividades registradas, cuando ingreso al calendario, entonces debe mostrarse un mensaje informativo. | EPIC02 |
| US07 | Conectar dispositivos IoT | Como agricultor, quiero conectar mis dispositivos IoT para monitorear datos en tiempo real. | **Escenario 1: Conexión exitosa** <br> Dado que ingreso correctamente las credenciales del dispositivo, cuando presiono "Conectar", entonces el sistema debería mostrar una confirmación de éxito. <br> **Escenario 2: Conexión fallida** <br> Dado que las credenciales son incorrectas, cuando intento conectar, entonces debe mostrarse un mensaje de error. | EPIC03 |
| US08 | Desconectar dispositivos | Como agricultor, quiero desconectar dispositivos cuando ya no los necesite conectados para ahorrar energía. | **Escenario 1: Desconexión exitosa** <br> Dado que tengo un dispositivo conectado, cuando presiono "Desconectar", entonces el dispositivo debería quedar inactivo. <br> **Escenario 2: Error técnico al desconectar** <br> Dado que ocurre un error técnico, cuando intento desconectar el dispositivo, entonces debería mostrarse una alerta al usuario. | EPIC03 |
| US09 | Cambiar foto de perfil | Como agricultor, quiero cambiar mi foto de perfil para personalizar mi cuenta. | **Escenario 1: Imagen válida** <br> Dado que estoy en la configuración del perfil, cuando selecciono una imagen válida, entonces mi foto de perfil debería actualizarse. <br> **Escenario 2: Imagen no válida** <br> Dado que subo un archivo no válido, cuando intento cambiar la imagen, entonces debe mostrarse un mensaje de error. | EPIC04 |
| US10 | Cambiar contraseña | Como agricultor, quiero cambiar mi contraseña para mantener segura mi cuenta. | **Escenario 1: Cambio exitoso** <br> Dado que ingreso correctamente la contraseña actual y la nueva, cuando presiono "Guardar", entonces el sistema debería confirmar el cambio. <br> **Escenario 2: Contraseña no válida** <br> Dado que la nueva contraseña no cumple con los requisitos, cuando intento cambiarla, entonces debería mostrarse un mensaje de validación. | EPIC04 |
| US11 | Visualizar dashboard por cultivo | Como agricultor, quiero visualizar el dashboard de datos de sensores por cultivo para analizar sus condiciones específicas. | **Escenario 1: Dashboard cargado exitosamente** <br> Dado que selecciono un cultivo en "Mis Cultivos", cuando accedo a un cultivo deseado y luego a ingreso a su dashboard, entonces deben mostrarse sus datos de sensores. <br> **Escenario 2: Error al cargar datos** <br> Dado que ocurre un error de conexión, cuando intento ver el dashboard, entonces debe mostrarse un mensaje de error. | EPIC05 |
| US12 | Exportar dashboards de cultivos | Como agricultor, quiero exportar dashboards con los datos de sensores de mis cultivos en formato PDF para analizarlos y tener una mejora continua. | **Escenario 1: Exportación exitosa** <br> Dado que estoy en "Mis Cultivos" y selecciono uno, cuando accedo a su dashboard y presiono "Exportar", entonces el archivo PDF debe descargarse correctamente. <br> **Escenario 2: Error de red** <br> Dado que ocurre un error de conexión, cuando intento exportar, entonces debe mostrarse un mensaje de error. | EPIC05 |
| US13 | Ver notificaciones | Como agricultor, quiero ver mis notificaciones recibidas para estar informado. | **Escenario 1: Visualización de notificaciones** <br> Dado que tengo notificaciones pendientes, cuando ingreso a la sección de notificaciones, entonces deben mostrarse ordenadas por fecha. <br> **Escenario 2: Sin notificaciones** <br> Dado que no hay notificaciones, cuando ingreso a la sección, entonces debe mostrarse un mensaje indicando que no hay contenido. | EPIC06 |
| US14 | Confirmar/Marcar como vistas | Como agricultor, quiero confirmar que leí las notificaciones para llevar un registro. | **Escenario 1: Marcado exitoso** <br> Dado que estoy en la lista de notificaciones, cuando marco una como leída, entonces su estado debería cambiar. <br> **Escenario 2: Error al marcar como leída** <br> Dado que hay un fallo en la acción, cuando intento marcar como leída, entonces debe mostrarse un mensaje de error. | EPIC06 |
| US15 | Borrar notificaciones | Como agricultor, quiero eliminar notificaciones antiguas para mantener mi bandeja ordenada. | **Escenario 1: Eliminación exitosa** <br> Dado que selecciono una notificación, cuando presiono "Eliminar", entonces debe desaparecer de la lista. <br> **Escenario 2: Error al eliminar** <br> Dado que ocurre un fallo, cuando intento eliminar, entonces debe mostrarse un mensaje de error. | EPIC06 |
| US16 | Enviar consultas a consultor | Como agricultor, quiero enviar consultas a un consultor desde la sección "Mi Consultor" para absolver mis dudas. | **Escenario 1: Envío exitoso** <br> Dado que ingreso una consulta en la vista "Mi Consultor", cuando relleno el formulario de consulta correctamente, entonces la consulta se envía al consultor. <br> **Escenario 2: Error en el envío** <br> Dado que hay un problema técnico, cuando intento enviar la consulta, entonces debe mostrarse un mensaje de error. | EPIC07 |
| US17 | Ver historial de consultas | Como agricultor, quiero ver el historial de mis consultas anteriores con los consultores para tener un registro detallado. | **Escenario 1: Historial disponible** <br> Dado que he realizado consultas, cuando accedo al historial en "Mi Consultor", entonces deberían mostrarse ordenadas por fecha. <br> **Escenario 2: Historial vacío** <br> Dado que no he realizado consultas, cuando accedo al historial, entonces debe mostrarse un mensaje informativo. | EPIC07 |
| US18 | Ver lista de agricultores | Como consultor, quiero ver una lista de agricultores para tener acceso a sus datos. | **Escenario 1: Lista disponible** <br> Dado que tengo agricultores asignados, cuando accedo a la vista "Agricultores", entonces deben mostrarse con sus datos. <br> **Escenario 2: Lista vacía** <br> Dado que no hay agricultores disponibles, cuando ingreso a la lista, entonces debe mostrarse un mensaje informativo. | EPIC07 |
| US19 | Enviar recomendaciones a agricultor | Como consultor, quiero enviar recomendaciones a los agricultores para absolver sus dudas. | **Escenario 1: Envío exitoso** <br> Dado que estoy quiero rellenar el formulario de recomendación, cuando la redacto correctamente, entonces la recomendación se envía exitosamente. <br> **Escenario 2: Error en el envío** <br> Dado que hay un error de envío, cuando intento enviar la recomendación, entonces debe mostrarse un mensaje de error. | EPIC07 |
| US20 | Ver calendario de un agricultor | Como consultor, quiero ver el calendario de un agricultor seleccionado para realizar una recomendación más acertada. | **Escenario 1: Calendario accesible** <br> Dado que selecciono un agricultor en la vista "Agricultores", cuando accedo a su perfil y entro a la sección de calendario, entonces debo visualizar sus actividades programadas. <br> **Escenario 2: Agricultor sin actividades** <br> Dado que el agricultor no tiene actividades registradas, cuando accedo a su calendario, entonces debe mostrarse un mensaje informativo. | EPIC07 |
| US21 | Recibir dashboards de agricultores | Como consultor, quiero ver dashboards de los cultivos del agricultor para realizar un mejor análisis. | **Escenario 1: Dashboard disponible** <br> Dado que selecciono un agricultor, cuando accedo a un cultivo y luego a su dashboard, entonces debe mostrarse los datos de los sensores actualizados. <br> **Escenario 2: Error al acceder al dashboard** <br> Dado que hay problemas de conexión, cuando accedo al dashboard, entonces debe mostrarse un mensaje de error. | EPIC07 |
| US22 | Exportar dashboards de cultivos del agricultor | Como consultor, quiero exportar dashboards de los datos de sensores del cultivo de un agricultor seleccionado en formato PDF para realizar un análisis eficiente. | **Escenario 1: Exportación exitosa** <br> Dado que estoy en "Agricultores" y selecciono uno, cuando accedo a su dashboard y presiono "Exportar", entonces el archivo PDF debe descargarse correctamente. <br> **Escenario 2: Error de red** <br> Dado que ocurre un error de conexión, cuando intento exportar, entonces debe mostrarse un mensaje de error. | EPIC07 |
| TS01 | Endpoint de Agricultor  | Como desarrollador, quiero implementar un endpoint de Farmer en nuestra API REST, para que los agricultores puedan registrarse, actualizar su información y gestionar sus propios perfiles. | Dado que un agricultor desea registrarse, cuando envía una solicitud POST con sus datos personales al endpoint de Farmer, entonces su cuenta debería crearse correctamente. <br> Dado que un agricultor necesita actualizar su información, cuando envía una solicitud PUT con los datos modificados, entonces los cambios deberían reflejarse en su perfil. <br> Dado que un agricultor necesita eliminar su cuenta, cuando envía una solicitud DELETE con su ID, entonces su cuenta debería eliminarse de forma segura. <br> Dado que un agricultor desea consultar su perfil, cuando envía una solicitud GET con su ID, entonces debería obtener sus datos completos. | EPIC08 |
| TS02 | Endpoint de Consultor | Como desarrollador, quiero implementar un endpoint de Consultor en nuestra API REST para que los consultores puedan acceder y gestionar datos relacionados con los agricultores asignados. | Dado que un consultor necesita ver su lista de agricultores, cuando envía una solicitud GET al endpoint de Consultor, entonces debería recibir una lista con los datos de los agricultores. <br> Dado que un consultor necesita enviar una consulta, cuando envía una solicitud POST al endpoint de Consultor con el contenido de la consulta, entonces el agricultor correspondiente debería recibir una notificación. <br> Dado que un consultor desea acceder a dashboards, cuando realiza una solicitud GET con el ID del agricultor, entonces debería obtener el dashboard correspondiente. | EPIC08 |
| TS03 | Endpoint de Cultivos     | Como desarrollador, quiero implementar un endpoint de Crops en nuestra API REST, para que los agricultores puedan gestionar información sobre sus cultivos. | Dado que un agricultor necesita registrar un nuevo cultivo, cuando envía una solicitud POST al endpoint de Crops con una nueva entrada de cultivo en el cuerpo de la solicitud, entonces la entrada de cultivo debería ser añadida a la base de datos. <br> Dado que un agricultor necesita actualizar una entrada de cultivo existente, cuando envía una solicitud PUT al endpoint de Crops con la entrada de cultivo actualizada, entonces los cambios deberían reflejarse. <br> Dado que un agricultor necesita eliminar una entrada, cuando envía una solicitud DELETE con el ID, entonces debería eliminarse. <br> Dado que un agricultor necesita consultar todas sus entradas, cuando envía una solicitud GET, entonces debería obtener una lista de sus cultivos. <br> Dado que un agricultor necesita consultar una entrada específica, cuando envía una solicitud GET con el ID, entonces debería obtener los detalles correspondientes. | EPIC08 |
| TS04 | Endpoint de Dispositivos | Como desarrollador, quiero implementar un endpoint de Devices en nuestra API REST, para que los agricultores puedan gestionar y monitorear los dispositivos IoT asociados a sus cultivos. | Dado que un agricultor necesita registrar un nuevo dispositivo, cuando envía una solicitud POST al endpoint de Devices con la información del dispositivo, entonces este debería ser guardado correctamente en la base de datos. <br> Dado que un agricultor necesita actualizar la información de un dispositivo, cuando envía una solicitud PUT con los datos actualizados, entonces los cambios deberían guardarse correctamente. <br> Dado que un agricultor necesita eliminar un dispositivo, cuando envía una solicitud DELETE con el ID del dispositivo, entonces este debería ser eliminado. <br> Dado que un agricultor desea ver la lista de dispositivos, cuando envía una solicitud GET, entonces debería recibir un listado completo. <br> Dado que un agricultor necesita consultar un dispositivo específico, cuando envía una solicitud GET con el ID, entonces debería obtener los detalles correspondientes. | EPIC08 |
| TS05 | Endpoint de Notificaciones    | Como desarrollador, quiero implementar un endpoint de Notifications en nuestra API REST, para que los agricultores y consultores puedan recibir, consultar y eliminar notificaciones importantes. | Dado que un usuario recibe una nueva notificación, cuando el sistema genera una alerta (por ejemplo, por condiciones ambientales o respuestas a consultas), entonces esta debe almacenarse mediante una solicitud POST al endpoint de Notificaciones. <br> Dado que un usuario desea ver sus notificaciones, cuando envía una solicitud GET al endpoint de Notificaciones con su ID, entonces debe recibir una lista completa de notificaciones. <br> Dado que un usuario desea eliminar una notificación, cuando envía una solicitud DELETE con el ID de la notificación, entonces esta debe ser eliminada de la base de datos. <br> Dado que un usuario desea marcar una notificación como leída, cuando envía una solicitud PUT con el estado actualizado, entonces esta debe actualizarse correctamente. | EPIC08                        |


## 3.3. Impact Mapping

**Segmento 1: Agricultores y pymes agrícolas** <br>
![ImpactMapAgricultor](assets/ImpactMapAgricultor.png) <br>
**Segmento 2: Consultores agrícolas** <br>
![ImpactMapConsultor](assets/ImpactMapConsultor.png) <br>

## 3.4. Product Backlog

| # Orden | User/Technical Story ID | Título                           | Descripción                                                                                      | Story Points (1/2/3/5/8) |
|---------|-------------------------|----------------------------------|--------------------------------------------------------------------------------------------------|--------------------------|
| 1       | US01                    | Diseño informativo y atractivo   | Como visitante, quiero una landing page clara y atractiva que explique los beneficios del sistema IoT para la agricultura, con ejemplos e imágenes, para entender su utilidad y beneficios. | 2 |
| 2       | US02                    | Funcionalidad de botones Call-to-Action | Como visitante, quiero disponer de botones y enlaces estratégicos para acceder a más información, facilitando mi interacción con el producto. | 2 |
| 3       | US03                    | Registrar cultivos               | Como agricultor, quiero registrar mis cultivos para tener un control personalizado. | 3 |
| 4       | US04                    | Gestionar cultivos               | Como agricultor, quiero editar y eliminar cultivos para mantener mi información actualizada. | 3 |
| 5       | US05                    | Añadir actividad al calendario   | Como agricultor, quiero añadir actividades a mi calendario para planificar mis tareas de cultivo. | 5 |
| 6       | US06                    | Ver calendario de actividades    | Como agricultor, quiero ver un calendario con riegos, siembras y cosechas para planificarme. | 3 |
| 7       | US07                    | Conectar dispositivos IoT        | Como agricultor, quiero conectar mis dispositivos IoT para monitorear datos en tiempo real. | 8 |
| 8       | US08                    | Desconectar dispositivos         | Como agricultor, quiero desconectar dispositivos cuando ya no los necesite conectados para ahorrar energía. | 3 |
| 9       | US09                    | Cambiar foto de perfil           | Como agricultor, quiero cambiar mi foto de perfil para personalizar mi cuenta. | 2 |
| 10      | US10                    | Cambiar contraseña               | Como agricultor, quiero cambiar mi contraseña para mantener segura mi cuenta. | 3 |
| 11      | US11                    | Visualizar dashboard por cultivo | Como agricultor, quiero visualizar el dashboard de datos de sensores por cultivo para analizar sus condiciones específicas. | 8 |
| 12      | US12                    | Exportar dashboards de cultivos  | Como agricultor, quiero exportar dashboards con los datos de sensores de mis cultivos en formato PDF para analizarlos y tener una mejora continua. | 5 |
| 13      | US13                    | Ver notificaciones               | Como agricultor, quiero ver mis notificaciones recibidas para estar informado. | 2 |
| 14      | US14                    | Confirmar/Marcar como vistas     | Como agricultor, quiero confirmar que leí las notificaciones para llevar un registro. | 3 |
| 15      | US15                    | Borrar notificaciones            | Como agricultor, quiero eliminar notificaciones antiguas para mantener mi bandeja ordenada. | 2 |
| 16      | US16                    | Enviar consultas a consultor     | Como agricultor, quiero enviar consultas a un consultor desde la sección "Mi Consultor" para absolver mis dudas. | 5 |
| 17      | US17                    | Ver historial de consultas       | Como agricultor, quiero ver el historial de mis consultas anteriores con los consultores para tener un registro detallado. | 3 |
| 18      | US18                    | Ver lista de agricultores        | Como consultor, quiero ver una lista de agricultores para tener acceso a sus datos. | 3 |
| 19      | US19                    | Enviar recomendaciones a agricultor | Como consultor, quiero enviar recomendaciones a los agricultores para absolver sus dudas. | 5 |
| 20      | US20                    | Ver calendario de un agricultor  | Como consultor, quiero ver el calendario de un agricultor seleccionado para realizar una recomendación más acertada. | 5 |
| 21      | US21                    | Recibir dashboards de agricultores | Como consultor, quiero ver dashboards de los cultivos del agricultor para realizar un mejor análisis. | 5 |
| 22      | US22                    | Exportar dashboards de cultivos del agricultor | Como consultor, quiero exportar dashboards de los datos de sensores del cultivo de un agricultor seleccionado en formato PDF para realizar un análisis eficiente. | 3 |
| 23      | TS01                    | Endpoint de Agricultor           | Como desarrollador, quiero implementar un endpoint de Farmer en nuestra API REST, para que los agricultores puedan registrarse, actualizar su información y gestionar sus propios perfiles. | 5 |
| 24      | TS02                    | Endpoint de Consultor            | Como desarrollador, quiero implementar un endpoint de Consultor en nuestra API REST para que los consultores puedan acceder y gestionar datos relacionados con los agricultores asignados. | 5 |
| 25      | TS03                    | Endpoint de Cultivos             | Como desarrollador, quiero implementar un endpoint de Crops en nuestra API REST, para que los agricultores puedan gestionar información sobre sus cultivos. | 8 |
| 26      | TS04                    | Endpoint de Dispositivos         | Como desarrollador, quiero implementar un endpoint de Devices en nuestra API REST, para que los agricultores puedan gestionar y monitorear los dispositivos IoT asociados a sus cultivos. | 8 |
| 27      | TS05                    | Endpoint de Notificaciones       | Como desarrollador, quiero implementar un endpoint de Notifications en nuestra API REST, para que los agricultores y consultores puedan recibir, consultar y eliminar notificaciones importantes. | 5 |

---

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming

Para la sesión de event storming nosotros tuvimos una reunión donde expusimos nuestras ideas acerca de este segmento. Con el transcurso de la sesión pudimos encontrar ideas las cuales son muy importantes para nuestra aplicación, además de poder tener las primeras versiones para los bounded context.

Aquí mostraremos como fue nuestro desarrollo del event storming realizado mediante la herramienta Miro.

URL: https://miro.com/welcomeonboard/SlNLYy9Sakh3MVJRQWxGaC85bjFVU24xWFBFSUNXTytseHp0clVIdS9vcEdqWEp4Y2VXWHJac0lkbFlVVzFPWTg4ZjBiR2hOeHo3MWZkenIvd01NdGFCb1FxZEVieThFekJjNzNkVXhjMUtieWhUL1NPdisrdFE0MnV1UWJHTCtyVmtkMG5hNDA3dVlncnBvRVB2ZXBnPT0hdjE=?share_link_id=322623245739

**STEP 1**

![Step1](assets/Step1.png)

En esta etapa, se identificaron los eventos clave que representan las acciones significativas dentro del sistema. Estos eventos se agruparon según los diferentes segmentos de usuarios y las funcionalidades principales de la aplicación.

**STEP 2: TIMELINES**

![Step2](assets/Step2.png)

Durante esta fase, los eventos identificados fueron agrupados en subgrupos liderados por un evento general que encapsula la función principal del grupo. Cada subgrupo incluyó tanto los happy paths, que representan los caminos ideales o exitosos de ejecución de los eventos, como los unhappy paths, que muestran los posibles problemas o situaciones no deseadas que pudieran surgir. Esto ayudó a estructurar los eventos de manera coherente y a comprender mejor las diferentes secuencias de acciones dentro del sistema.

**Step 3: PAINT POINTS**

![Step3](assets/Step3.png)

Durante el proceso, se identificaron los pain points o puntos problemáticos, que son áreas donde los usuarios pueden experimentar dificultades o fricciones en su interacción con la aplicación. Estos puntos son cruciales para mejorar la experiencia del usuario y optimizar el diseño del sistema.

**Step 4: PIVOTAL POINTS**

![Step4](assets/Step4.png)

Se señalaron los pivotal points o puntos clave, que son eventos críticos que marcan hitos importantes en el flujo de trabajo del sistema. Estos eventos suelen tener un impacto significativo en el comportamiento del sistema o en la experiencia del usuario.

**Step 5: COMMANDS**

![Step5](assets/Step5.png)

Cada evento se asoció con un comando específico que lo desencadena y un actor que lo realiza. Esto ayudó a clarificar quién es responsable de iniciar cada acción y cómo interactúan los diferentes usuarios con el sistema

**Step 6: POLICIES**

![Step6](assets/Step6.png)

Durante esta etapa, se identifican y definen las políticas relevantes para cada contexto del sistema. Estas políticas pueden incluir restricciones de negocio, reglas de validación o comportamientos específicos que deben seguirse en determinadas 

**Step 7: READ MODELS**

![Step7](assets/Step7.png)

Durante esta fase, se diseñan y desarrollan los modelos de lectura para cada contexto del sistema, asegurando que proporcionen la información necesaria de manera eficiente y coherente

**Step 8: EXTERNAL SYSTEMS**

![Step8](assets/Step8.png)

Durante esta etapa, se identifican los sistemas externos relevantes para cada contexto del sistema y se establecen las interfaces y comunicaciones necesarias para integrarlos de manera efectiva.

**Step 9: AGGREGATES**

![Step9](assets/Step9.png)

Durante esta etapa, se definen y diseñan los agregados para cada contexto del sistema, asegurando que representen correctamente las transacciones y operaciones coherentes dentro del sistema.

#### 4.1.1.1 Candidate Context Discovery

En este proceso, se utilizó la técnica de start-with-value para identificar los valores clave del negocio y los bounded contexts más importantes del sistema agrícola. Primero, se analizó cómo los sensores IoT, la gestión de cultivos y la consultoría agrícola son esenciales para mejorar la eficiencia y la productividad del agricultor.

- **Identificación de Valores del Negocio:** El sistema busca optimizar los recursos agrícolas utilizando sensores IoT para medir variables clave, facilitando decisiones informadas y mejorando la productividad, con apoyo de consultores remotos para brindar estrategias personalizadas.

- **Identificación de Funcionalidades Clave:** El sistema permite gestionar cultivos, monitorear en tiempo real con sensores IoT, activar acciones automáticas como el riego, enviar alertas sobre cambios críticos y ofrecer consultoría remota basada en datos.
  
- **Priorización de Contextos:** Se priorizan los contextos de sensores IoT para asegurar datos precisos, gestión de cultivos para facilitar la toma de decisiones, notificaciones claras y efectivas, y consultoría remota para brindar apoyo experto a los agricultores.

##### Candidate para Bounded Context: Profiles

![CandidateProfiles](assets/CandidateProfiles.png)  

##### Candidate para Bounded Context: Crops

![CandidateCrops](assets/CandidateCrops.png)     

##### Candidate para Bounded Context: Devices

![CandidateDevices](assets/CandidateDevices.png) 

##### Candidate para Bounded Context: Notifications

![CandidateNotifications](assets/CandidateNotifications.png) 

##### Diagrama completo

![CandidateC](assets/CandidateC.png) 

#### 4.1.1.2 Domain Message Flows Modeling

**Agricultor**

Scenario: El agricultor desea registrar un cultivo y recibir notificación

![](assets/FlowsModeling1.png)

**Consultor**

Scenario: El consultor gestiona las consultas de los agricultores y genera recomendaciones

![](assets/FlowsModeling2.png)


#### 4.1.1.3 Bounded Context Canvases

**Profile**

![](assets/Profile.png)

**Crops**

![](assets/Crops.png)

**Notification**

![](assets/Notification.png)

**IOT Devices**

![](assets/Devices.png)

Link: <https://miro.com/welcomeonboard/THQrMlgxMFliRW85VUt4enR0bW1MbUZ2TmtGNmJwU2svbFZtS01uSHljRW9jcDMwNFE2b1I0Q252Z0pxRkx6bnY0aG8zVDB3RnpkSVdIRTN4Tk9uNktCb1FxZEVieThFekJjNzNkVXhjMUtrM1hZbFhCL1VFYnlXQVUxaC90TFZBS2NFMDFkcUNFSnM0d3FEN050ekl3PT0hdjE=?share_link_id=145713520841>

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

![LandscapeDiagram](assets/LandscapeDiagram.png)

#### 4.1.3.2. Software Architecture Context Level Diagrams

![ContextDiagram](assets/ContextDiagram.png)

#### 4.1.3.3. Software Architecture Container Level Diagrams

![ContainerDiagram](assets/ContainerDiagram.png)

#### 4.1.3.4. Software Architecture Deployment Diagrams 

![DeploymentDiagram](assets/DeploymentDiagram.png)

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.1. Bounded Context: Profiles

#### 4.2.1.1. Domain Layer

### Aggregate: Profile

- **Categoría**: Entity/Aggregate
- **Propósito**: Representa al agricultor dentro del sistema, gestionando su información personal y preferencias relacionadas con los cultivos.

#### Atributos

| Nombre      | Tipo de dato | Visibilidad | Descripción                                                      |
|-------------|--------------|-------------|------------------------------------------------------------------|
| id          | Long         | Private     | Identificador único del perfil del agricultor.                    |
| userName    | String       | Private     | Nombre de usuario del agricultor.                                 |
| name        | String       | Private     | Nombre completo del agricultor.                                   |
| email       | String       | Private     | Correo electrónico del agricultor.                                |
| preferences | String       | Private     | Preferencias del agricultor en cuanto a cultivos.                 |
| history     | Set          | Private     | Lista de eventos o interacciones pasadas con el sistema.          |

#### Métodos

| Nombre           | Tipo de retorno | Visibilidad | Descripción                                                |
|------------------|-----------------|-------------|------------------------------------------------------------|
| Constructor      | Void            | Public      | Constructor para inicializar un perfil de usuario.         |
| updateProfile()  | Void            | Public      | Actualiza los datos del perfil del agricultor.              |
| getProfile()     | Perfil          | Public      | Retorna los datos del perfil del agricultor.                |
| getHistory()     | Set             | Public      | Recupera el historial de interacciones y recomendaciones.   |


#### 4.2.1.2. Interface Layer

- **Propósito**: La capa de interfaz se encarga de recibir las solicitudes de los usuarios y gestionarlas, enviando las respuestas adecuadas.

#### Métodos / Componentes

| Método          | Tipo de retorno | Descripción                                                  |
|-----------------|-----------------|--------------------------------------------------------------|
| getProfile()    | Perfil          | Retorna los datos completos del perfil del agricultor.        |
| updateProfile() | Void            | Actualiza los datos del perfil del agricultor.                |
| getHistory()    | Set             | Recupera el historial de interacciones y actividades pasadas. |

#### Controlador

- **PerfilController**: Controlador que maneja las solicitudes HTTP para crear, actualizar y consultar perfiles de usuarios.

#### 4.2.1.3. Application Layer

- **Propósito**: La capa de aplicación coordina la lógica entre el dominio y la interfaz. Aquí se gestionan las transacciones y las operaciones de negocio.

#### Servicios

| Servicio         | Métodos                              | Descripción                                                            |
|------------------|--------------------------------------|------------------------------------------------------------------------|
| ProfileService   | updateProfile(), getProfile()        | Gestiona la lógica de negocio para consultar y actualizar perfiles.     |
| HistoryService   | getHistory()                         | Permite acceder al historial de actividades del agricultor.             |


#### 4.2.1.4. Infrastructure Layer

- **Propósito**: La capa de infraestructura se ocupa de la persistencia de datos y de los servicios que soportan la aplicación.

#### Componentes

| Componente           | Descripción                                                   |
|----------------------|---------------------------------------------------------------|
| Base de Datos        | Almacena los datos de los perfiles de usuario, incluyendo la información personal, preferencias y el historial. |
| Servicio de Almacenamiento | Gestiona el acceso y persistencia de los datos de los perfiles en la base de datos. |

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

![ProfileComponentDiagram](assets/ProfileComponentDiagram.png)

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

![ProfileDomainLayerClassDiagrams](assets/ProfileDiagram.png)

##### 4.2.1.6.2. Bounded Context Database Design Diagram

![ProfileDatabaseDesignDiagram](assets/BoundedContextDatabaseDesignDiagramProfiles.png)

### 4.2.2. Bounded Context: Crops

#### 4.2.2.1. Domain Layer

### Aggregate: Crop

- **Categoría**: Entity/Aggregate
- **Propósito**: Representa un cultivo específico, incluyendo su tipo, fecha de siembra, necesidades de riego y otras condiciones de crecimiento.

#### Atributos

| Nombre           | Tipo de dato | Visibilidad | Descripción                                                   |
|------------------|--------------|-------------|---------------------------------------------------------------|
| id               | Long         | Private     | Identificador único del cultivo.                              |
| type             | String       | Private     | Tipo de cultivo (ej. maíz, arroz).                            |
| sowingDate       | Date         | Private     | Fecha en la que se sembró el cultivo.                         |
| irrigationNeed   | String       | Private     | Necesidad de riego del cultivo.                               |
| temperatureRange | String       | Private     | Rango de temperatura recomendado para el cultivo.             |
| growthStage      | String       | Private     | Etapa actual del cultivo.                                     |

#### Métodos

| Nombre             | Tipo de retorno | Visibilidad | Descripción                                                      |
|--------------------|-----------------|-------------|------------------------------------------------------------------|
| Constructor        | Void            | Public      | Constructor para inicializar el cultivo.                        |
| updateCrop()       | Void            | Public      | Actualiza la información del cultivo.                           |
| getCrop()          | Cultivo         | Public      | Retorna los datos completos del cultivo.                        |
| getIrrigationStatus() | String        | Public      | Retorna el estado del riego del cultivo. 

#### 4.2.2.2. Interface Layer

- **Propósito**: Recibe las solicitudes del agricultor para gestionar los cultivos, actualizar su estado y consultar datos relacionados.

### Métodos / Componentes

| Método            | Tipo de retorno | Descripción                                                    |
|-------------------|-----------------|---------------------------------------------------------------|
| getCrop()         | Cultivo         | Retorna los datos completos del cultivo.                       |
| updateCrop()      | Void            | Actualiza los datos de un cultivo específico.                  |
| getIrrigationStatus() | String       | Verifica y retorna el estado del riego de un cultivo.          |

### Controlador

- **CropController**: Controlador que maneja las solicitudes HTTP para la creación, consulta y actualización de cultivos.

#### 4.2.2.3. Application Layer

- **Propósito**: Gestiona las operaciones y la lógica de negocio asociada con los cultivos, coordinando las acciones entre el **Domain Layer** y la **Interface Layer**.

#### Servicios

| Servicio          | Métodos                              | Descripción                                                            |
|-------------------|--------------------------------------|------------------------------------------------------------------------|
| CropService       | updateCrop(), getCrop()              | Lógica de negocio para gestionar cultivos, como crear, actualizar y consultar cultivos. |
| IrrigationService | getIrrigationStatus()                | Calcula y gestiona las necesidades de riego del cultivo.                |

#### 4.2.2.4. Infrastructure Layer

- **Propósito**: Se encarga de la persistencia y el soporte tecnológico de la gestión de cultivos, como la base de datos y la conexión con dispositivos IoT.

#### Componentes

| Componente                  | Descripción                                                        |
|-----------------------------|--------------------------------------------------------------------|
| Base de Datos de Cultivos   | Almacena todos los cultivos y sus datos asociados.                 |
| Conexión con Dispositivos IoT | Interfaz para obtener datos de los dispositivos IoT, como humedad, temperatura y otros parámetros. |

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams

![CropsComponentDiagram](assets/CropsComponentDiagram.png)

#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams

![CropsDomainLayerClassDiagrams](assets/CropsDiagram.png)

##### 4.2.2.6.2. Bounded Context Database Design Diagram

![CropsDatabaseDesignDiagram](assets/BoundedContextDatabaseDesignDiagramCrops.png)

### 4.2.3. Bounded Context: Devices

#### 4.2.3.1. Domain Layer

### Aggregate: IoT Device

- **Categoría**: Entity/Aggregate
- **Propósito**: Representa los dispositivos IoT que monitorean y controlan las condiciones del cultivo, como la humedad, temperatura, entre otros.

#### Atributos

| Nombre       | Tipo de dato | Visibilidad | Descripción                                                     |
|--------------|--------------|-------------|-----------------------------------------------------------------|
| id           | Long         | Private     | Identificador único del dispositivo IoT.                        |
| type         | String       | Private     | Tipo de dispositivo IoT (ej. sensor de humedad).                |
| status       | String       | Private     | Estado del dispositivo (activo, inactivo).                      |
| lastRead     | Date         | Private     | Fecha de la última lectura del dispositivo.                     |

#### Métodos

| Nombre               | Tipo de retorno | Visibilidad | Descripción                                                     |
|----------------------|-----------------|-------------|-----------------------------------------------------------------|
| Constructor          | Void            | Public      | Constructor para inicializar el dispositivo IoT.                |
| connectDevice()      | Void            | Public      | Conecta el dispositivo IoT al sistema.                          |
| getDeviceStatus()    | String          | Public      | Retorna el estado actual del dispositivo IoT.                   |
| sendData()           | Void            | Public      | Envia los datos recopilados por el dispositivo IoT.             |


#### 4.2.3.2. Interface Layer

- **Propósito**: Facilita la conexión y la comunicación con los dispositivos IoT, permitiendo al agricultor interactuar con ellos.

#### Métodos / Componentes

| Método              | Tipo de retorno | Descripción                                                     |
|---------------------|-----------------|-----------------------------------------------------------------|
| connectDevice()      | Void            | Conecta un dispositivo IoT al sistema.                          |
| getDeviceStatus()    | String          | Verifica el estado actual del dispositivo IoT.                  |
| sendData()           | Void            | Envía los datos recopilados por el dispositivo IoT al sistema.  |

#### Controlador

- **DeviceController**: Controlador que maneja las solicitudes de conexión, desconexión y estado de los dispositivos IoT.

#### 4.2.3.3. Application Layer

- **Propósito**: Coordina la interacción entre los dispositivos IoT y el resto del sistema, gestionando las operaciones de activación y lectura de sensores.

#### Servicios

| Servicio            | Métodos                             | Descripción                                                         |
|---------------------|-------------------------------------|---------------------------------------------------------------------|
| DeviceService       | connectDevice(), sendData()         | Maneja las operaciones de conexión y desconexión de los dispositivos IoT. |
| SensorDataService  | sendData()                          | Procesa los datos provenientes de los sensores y los envía al sistema. |

#### 4.2.3.4. Infrastructure Layer

- **Propósito**: Proporciona la infraestructura para la gestión y almacenamiento de los dispositivos IoT.

#### Componentes

| Componente                    | Descripción                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| Base de Datos de Dispositivos IoT | Almacena la configuración y el estado de los dispositivos IoT.               |
| Plataforma de Conexión IoT     | Facilita la comunicación entre los dispositivos IoT y el sistema.           |

#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

![DevicesComponentDiagram](assets/DevicesComponentDiagram.png)

#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams
![DevicesDomainLayerClassDiagrams](assets/DevicesDiagram.png)

##### 4.2.3.6.2. Bounded Context Database Design Diagram

![DevicesDatabaseDesignDiagram](assets/BoundedContextDatabaseDesignDiagramDevices.png)

### 4.2.4. Bounded Context: Notifications
#### 4.2.4.1. Domain Layer

### Aggregate: Notification

- **Categoría**: Entity/Aggregate
- **Propósito**: Representa las notificaciones enviadas al agricultor, tales como alertas de riego, condiciones climáticas y recomendaciones del sistema.

#### Atributos

| Nombre     | Tipo de dato | Visibilidad | Descripción                                                   |
|------------|--------------|-------------|---------------------------------------------------------------|
| id         | Long         | Private     | Identificador único de la notificación.                        |
| message    | String       | Private     | Contenido del mensaje de la notificación.                     |
| type       | String       | Private     | Tipo de notificación (alerta, recomendación).                 |
| timestamp  | Date         | Private     | Fecha y hora en que se envió la notificación.                  |

#### Métodos

| Nombre               | Tipo de retorno    | Visibilidad | Descripción                                                      |
|----------------------|--------------------|-------------|------------------------------------------------------------------|
| Constructor          | Void               | Public      | Constructor para crear una notificación.                        |
| sendNotification()   | Void               | Public      | Envia una notificación al agricultor.                            |
| getNotifications()   | List<Notificación> | Public      | Recupera todas las notificaciones enviadas.                      |

#### 4.2.4.2. Interface Layer

- **Propósito**: Gestiona las interacciones con el agricultor para enviarle notificaciones, como alertas sobre los cultivos, recomendaciones y actualizaciones.

#### Métodos / Componentes

| Método               | Tipo de retorno     | Descripción                                                     |
|----------------------|---------------------|-----------------------------------------------------------------|
| sendNotification()    | Void                | Envia una notificación al agricultor.                           |
| getNotifications()    | List<Notificación>  | Recupera todas las notificaciones enviadas al agricultor.       |

#### Controlador

- **NotificationController**: Controlador que maneja las solicitudes para generar y mostrar notificaciones.

#### 4.2.4.3. Application Layer

- **Propósito**: Se encarga de la lógica para crear las notificaciones y enviarlas al agricultor.

#### Servicios

| Servicio            | Métodos               | Descripción                                                         |
|---------------------|-----------------------|---------------------------------------------------------------------|
| NotificationService | sendNotification()     | Gestiona la creación y el envío de notificaciones.                  |
| AlertService        | sendAlert()            | Genera alertas basadas en eventos, como la necesidad de riego o cambios de temperatura. |


#### 4.2.4.4. Infrastructure Layer

- **Propósito**: Proporciona la infraestructura para enviar las notificaciones y almacenarlas.

#### Componentes

| Componente                    | Descripción                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| Servicio de Envío de Notificaciones | Facilita el envío de notificaciones a través de correo electrónico, SMS, etc. |
| Base de Datos de Notificaciones | Almacena las notificaciones generadas y su estado.                           |

#### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams

![NotificationComponentDiagram](assets/NotificationComponentDiagram.png)

#### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams
![NotificationDomainLayerClassDiagrams](assets/NotificationsDiagram.png)

##### 4.2.4.6.2. Bounded Context Database Design Diagram

![NotificationsDatabaseDesignDiagram](assets/BoundedContextDatabaseDesignDiagramNotifications.png)

---
# Conclusiones

---

# Bibliografía

---

# Anexos

**Video de exposición TB1:**
