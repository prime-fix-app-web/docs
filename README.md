<h2 align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="logo-upc" width="200px" height="200px" align="center">
</h2>

<h1 align="center">Universidad Peruana de Ciencias Aplicadas</h1>

<h3 align="center">
  Ingeniería de Software
  <br><br>
  Curso: Aplicaciones Web
  <br><br>
  Sección: 7452
  <br><br>
  Profesor: Hugo Allan Mori Paiva
  <br><br>
  Semestre: 2025-20
  <br><br>
  Informe del Trabajo Final
  <br><br>
  Startup: Prime-Fix
  <br><br>
  Producto: AutoFix
</h3>

<div align="center">

| <div style="width:300px">Alumno</div> | <div style="width:125px">Código</div> |
|:-------------------------------------------:|:-------------------------------------------:|
|       Cesar Augusto Arostegui Alzamora      |            u202114548                       |
|       Gianmarco Fabian Jiménez Guerra       |            u202123843                       |
|       Flor De María Contreras Leon          |            u202323243                      |
|       Giorgio Marzouk Awad Vargas           |            u20#######                       |
|       Piero Francesco Tenorio Medina        |            u202318731                       |

</div>

<div align="center"> Setiembre 2025 </div>

<hr>

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe  
---

<div align="center">

| Versión | Fecha       | Autor(es)                                                                 | Descripción de modificación |
|---------|-------------|---------------------------------------------------------------------------|------------------------------|
|   TB1   | XX/09/2025  | Gianmarco Fabian Jiménez Guerra                                           | Realicé ... |
|   TB1   | XX/09/2025  | Cesar Augusto Arostegui Alzamora                                          | Realicé ... |
|   TB1   | XX/09/2025  | Flor De María Contreras Leon                                              | Realicé ... |
|   TB1   | XX/09/2025  | Giorgio Marzouk Awad Vargas                                               | Realicé ... |
|   TB1   | XX/09/2025  | Piero Francesco Tenorio Medina                                            | Realicé ... |

</div>

# Project Report Collaboration Insights  

---

# Contenido
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
  - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)
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
    - [4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)
    - [4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
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

# Student Outcome  

---

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
Prime-Fix es una startup especializada en el desarrollo de soluciones tecnológicas aplicadas a la web, cuyo propósito es transofrmar la forma en que los usuarios acceden a servicios de mantenimiento y reparación automotriz.
Con Prime-Fix nace AutoFix, una plataforma digital cuyo objetivo es facilitar el contacto entre talleres de vehículos y dueños de los mismos implementando una serie de funcionalidades que permitirán a ambos usuarios, obtener una experiencia de gestión clara.

<b>Misión: </b> Nuestra misión es acercar a los dueños de vehículos a talleres confiables por medio de una plataforma accesible y amigable. De esta manera, modernizamos el sector automotriz y optimizamos de toda la experiencia de este tipo de  servicios.

<b>Visión: </b> Tenemos como objetivo posicionarnos como la plataforma líder en Perú para la gestión digital de servicios automotrices, considerando una posible expansión hacia toda América Latina. A su vez, en el futuro se buscará integrar a este proyecto aplicaciones móviles y dispositivos IoT que permitan un mantenmiento inteligente para los vehículos.

### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
En el Perú, miles de dueños de vehículos enfrentan a diario la dificultad de acceder a servicios de mantenimiento y reparación de manera confiable y eficiente. La búsqueda de talleres suele convertirse en un proceso poco claro y desgastante, donde predominan la informalidad, la falta de información sobre disponibilidad y la ausencia de canales digitales que faciliten la comunicación. Como consecuencia, muchos conductores pierden tiempo llamando o visitando distintos talleres, enfrentan largas esperas y experimentan desconfianza frente a la calidad y transparencia del servicio recibido.

Al mismo tiempo, los talleres y mecánicos independientes cargan con limitaciones importantes. La gestión de citas se realiza de manera tradicional, mediante llamadas, mensajes o visitas presenciales, lo que genera desorden, sobrecarga de trabajo y pérdida de oportunidades de negocio. La falta de herramientas digitales para organizar horarios, técnicos y clientes impide que los talleres optimicen sus recursos y ofrezcan una experiencia más clara y moderna.

Las entrevistas realizadas revelan que tanto dueños de vehículos como mecánicos perciben esta situación como una limitación significativa y manifiestan el deseo de contar con una plataforma accesible, confiable y estructurada que facilite la comunicación, optimice la gestión de servicios y brinde mayor transparencia a todo el proceso de mantenimiento automotriz.

#### 1.2.2.2. Lean UX Assumptions

##### Suposiciones sobre dueños de vehículos
- Suponemos que los dueños de vehículos buscan talleres confiables y accesibles, pero actualmente enfrentan dificultades para encontrarlos de manera rápida y transparente.


- Suponemos que valoran la posibilidad de conocer horarios y disponibilidad en tiempo real antes de decidir a qué taller acudir.


- Suponemos que prefieren una experiencia digital sencilla, visual y clara, que les ahorre llamadas, visitas y pérdidas de tiempo.


- Suponemos que se sienten más seguros cuando reciben notificaciones y pueden dar seguimiento al servicio solicitado.


- Suponemos que confían más en una plataforma si les brinda transparencia en costos, tiempos y calidad del trabajo.

##### Suposiciones sobre mecánicos / talleres
- Suponemos que los talleres y mecánicos desean atraer más clientes sin sobrecargar sus canales de atención tradicionales.


- Suponemos que necesitan herramientas digitales para organizar técnicos, horarios y disponibilidad de manera eficiente.


- Suponemos que estarían dispuestos a usar una plataforma si esta facilita la comunicación con clientes y reduce la pérdida de citas o confusiones.


- Suponemos que valoran un sistema que les ayude a fidelizar clientes y mejorar su reputación en el mercado.


- Suponemos que los administradores de talleres aceptarían registrar técnicos y disponibilidad si esto aumenta su visibilidad y confianza frente a potenciales clientes.


##### Suposiciones sobre el entorno digital
- Suponemos que la plataforma debe ser accesible desde web y móvil, con una interfaz amigable y moderna.


- Suponemos que las notificaciones automáticas y formularios dinámicos son claves para la interacción fluida entre cliente y taller.


- Suponemos que un modelo freemium o por suscripción podría incentivar a los talleres a sumarse, mientras que la gratuidad inicial para clientes facilitaría la adopción.


- Suponemos que la inclusión de un sistema de reseñas y calificaciones generará confianza y motivará el uso frecuente.



------------



##### User Outcomes
- Que los dueños de vehículos puedan agendar servicios de manera rápida, segura y transparente.


- Que confíen en los talleres registrados y logren ahorrar tiempo en la gestión de mantenimiento y reparación.


- Que los talleres logren digitalizar su gestión interna, mejorando la organización y optimización de recursos.


- Que los mecánicos establezcan una relación más clara y confiable con los clientes, incrementando su fidelización.


##### Business Outcomes
- Lograr una alta adopción inicial entre dueños de vehículos y talleres mecánicos en Lima y posteriormente en otras ciudades del Perú.


- Generar confianza en el mercado automotriz como la primera plataforma digital que centraliza la gestión de citas y servicios.


- Incrementar la conversión de talleres gratuitos a planes de pago mediante funcionalidades premium (ej. mayor visibilidad, métricas de clientes, gestión avanzada de recursos).
  
#### 1.2.2.3. Lean UX Hypothesis Statements

A partir de nuestras asunciones, formulamos las siguientes hipótesis que deben ser validadas con usuarios reales:

1. **Creemos que los dueños de vehículos necesitan una forma confiable y rápida de agendar servicios de mantenimiento o reparación** porque actualmente enfrentan pérdida de tiempo, falta de transparencia y desconfianza en los talleres,entonces, si les ofrecemos una plataforma digital con agenda en línea, disponibilidad en tiempo real y notificaciones  aumentará su confianza y la frecuencia con la que solicitan servicios.


2. **Creemos que los talleres necesitan una herramienta para organizar técnicos, horarios y citas** porque ahora trabajan con sistemas manuales, llamadas y mensajes dispersos, entonces, si les damos un panel de gestión con registro de técnicos, agenda y comunicación integrada podrán atender más clientes de manera ordenada y mejorar su reputación.

3. **Creemos que una plataforma visual, intuitiva y accesible desde web o móvil motivará a los dueños de vehículos a usarla** porque están acostumbrados a aplicaciones simples y rápidas en su vida diaria,entonces, si Prome Fix ofrece una experiencia fluida y amigable, se incrementará la adopción y retención de usuarios.


4. **Creemos que permitir a los dueños de vehículos ver reseñas, calificaciones y disponibilidad en tiempo real aumentará la confianza en los talleres** porque actualmente sienten inseguridad respecto a la calidad y tiempos de atención entonces, si ofrecemos funciones de reseñas y visibilidad de horarios,los usuarios elegirán talleres a través de la plataforma en lugar de buscar por canales informales.


5. **Creemos que un modelo free con funciones básicas gratuitas para talleres y clientes permitirá captar más usuarios porque reduce la barrera de entrada y genera valor desde el primer uso**,entonces, si ofrecemos planes premium con mayor visibilidad, métricas y herramientas avanzadas,lograremos convertir talleres gratuitos en clientes de pago y sostener el crecimiento de la plataforma.
Estas hipótesis serán validadas mediante pruebas con usuarios, entrevistas, prototipos de la plataforma y análisis de métricas de uso.

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

**Segmento 1: Dueños de vehículos**
**Aspectos Demográficos:**

* Sexo: Masculino y Femenino
* Edades: Entre 22 y 50 años

**Aspectos Geográficos:**

* Zona Geográfica en la que viven: Urbana, ciudad altamente transitada por vehículos.


**Aspectos Psicográficos:**

* Valoran el buen servicio y la eficacia.
* Tienen interés en la calidad del servicio que se le brinda a su vehiculo. 


**Segmento 2: Administrador de taller automotriz**
**Aspectos Demográficos:**

* Sexo: Masculino y Femenino
* Edades: Entre 30 y 50 años
* Ocupación: Dueño o administrador de un taller automotriz

**Aspectos Geográficos:**

* Zona Geográfica en la que viven: Urbana, ciudad altamente transitada por vehículos.
* Ubicacion del taller: Cercana a avenidas transitadas, zonas industriales o barrios con alta circulación vehicular.

**Aspectos Psicográficos:**

* Valoran la organizacion y eficiencia en la gestión de clientes.
* Interés en fidelizar clientes y mejroar la reputación de su taller.
* Buscan soluciones tecnológicas que les permitan optimizar el tiempo y reducir errores dentro del taller.

---

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

Segmento #1: Dueños de vehículos<br>
"Buenos días/tardes/noches 'Nombre del entrevistado'. Mi nombre es 'Nombre del entrevistador' de la startup Prime-Fix. Nos encontramos desarrollando una plataforma para que los dueños de vehículos tengan la facilidad de programar sus visitas a talleres de reparación de autos, hacer seguimiento al servicio y ver el diagnóstico de la falla detectada. En base a ello, tengo preparadas una lista de preguntas para conocer su punto de vista sobre algunos temas importantes para nuestra plataforma."

Preguntas:
1. ¿Ha realizado la búsqueda de algún taller durante los últimos meses? De ser así, ¿Podría comentarnos su experiencia?
2. ¿Qué plataformas o medios utiliza para realizar la búsqueda de talleres cuando su vehículo necesita reparación?
3. ¿Qué aspectos valora más en un servicio de taller (distancia, disponibilidad, costo)?
4. ¿Ha tenido experiencias negativas con talleres? De ser así, ¿Le hubiera gustado registrar dichas experiencias de manera pública?
5. ¿Usted mantiene un registro de su vehículo y del mantenimiento que le ha brindado durante todo este tiempo?
6. ¿Ha dejado su vehículo en un taller durante días u horas?¿Cómo se le avisa que su vehículo ya está listo?
7. ¿Estaría interesado en usar una plataforma que le permita agendar visita en talleres de su zoma? ¿Por qué?
8. ¿Qué funcionalidades cree que harían que esta plataforma sea útil para el día a día?
9. ¿Se sentiría cómodo recibiendo algunos recordatorios de mantenimiento preventivo desde una app?
10. ¿Le gustaría hacer seguimiento al estado de su vehículo mientras este se encuentra en mantenimiento?

Segmento #2: Administrador de taller automotriz<br>
"Buenos días/tardes/noches 'Nombre del entrevistado'. Mi nombre es 'Nombre del entrevistador' de la startup Prime-Fix. Nos encontramos desarrollando una plataforma para que los talleres tengan la facilidad de agendar y hacer seguimiento a las visitas de posibles clientes que solicitan la reparación de sus autos. En base a ello, tengo preparadas una lista de preguntas para conocer su punto de vista sobre algunos temas importantes para nuestra plataforma."

Preguntas:
1. ¿Cómo consigue actualmente a sus clientes para el taller?
2. ¿En qué medio promociona sus servicios?
3. ¿Encuentra dificultades al competir con talleres más grandes? De ser así ¿Podrías describirlas?
4. ¿Cómo gestiona los pedidos o solicitudes de servicios de reparación? (ej. llamadas, WhatsApp o visitas directas)
5. ¿Ha tenido algún reclamo sobre el desempeño de los téncnicos? ¿Podría detallar más la experiencia?
6. ¿Cómo maneja la información sobre lso técnicos? ¿Tienen una base de datos?
7. ¿Qué tan importante consideraría mostrar la disponibilidad de sus técnicos en tiempo real?
8. ¿Qué tanto te ayudaría una plataforma donde puedas registrar tu taller, tus técnicos y mostrar reseñas de clientes?
9. ¿Qué funcionalidades le añadirías a la plataforma?
10. ¿Le parece importante que el cliente sepa en qué estado se encuentra su vehículo y cuál es su diagnóstico final?
11. ¿Estaría interesado en una plataforma que notifique al cliente el momento en que puede recoger su vehículo?

### 2.2.2. Registro de entrevistas

##### Segmento 1: Dueños de Vehiculos

##### Entrevista N°1: Dionisio Rodriguez

- Sexo: Maculino
- Edad:25 años
- Direccion: Lima, Av Arequipa Miraflores.

| ![Entrevista Dionisio Segmento 1](Assets/chapter-II/Entrevista_Dionisio_Rodriguez.png) |
|-------------------------------------------------------------------------------------------------------------------|
|** Link De la Entrevista:** |
|Duracion:**00:05:02**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Inicio:**00:00:31**&nbsp;&nbsp;&nbsp;&nbsp;Final:**00:05:02**|
| Dionisio Rodríguez, de 25 años, es conductor de automóvil y comentó que al momento de elegir un taller prioriza la confianza en el servicio, incluso si esto implica desplazarse a zonas más lejanas. Para ubicar opciones suele utilizar Google Maps, aunque reconoce que no siempre refleja la calidad real del taller. Señaló que en una ocasión tuvo una experiencia negativa, pues su vehículo fue dañado en un taller y los responsables no asumieron la reparación, lo que generó desconfianza y la necesidad de contar con mecanismos de referencia más seguros.Asimismo, resaltó que le resultaría valioso contar con una plataforma que permita no solo agendar visitas a talleres, sino también hacer seguimiento en tiempo real al estado del vehículo mientras se encuentra en mantenimiento. Además, considera importante que los usuarios puedan registrar y compartir públicamente sus experiencias, ya que esto ofrecería mayor transparencia y ayudaría a otros conductores a tomar mejores decisiones.|
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
### 2.3.1. User Personas
Esta sección presenta dos arquetipos desarrollados para representar a los segmentos objetivos de Prime-Fix: Conductores de Autos y Administradores de talleres automotriz.

#### User Persona - Segmento 1 : Dueño de vehículo

- **Nombre: **José Ramírez
- **Edad:** 29 años
- **Género:** Masculino
- **Ocupación:** Analista de marketing digital
- **Ubicación: **Lima, Perú
- **Acceso digital:** Smartphone con conexión de datos móviles, laptop con internet en casa


![User_Person_Segmento1](Assets/chapter-II/User_Person_Segmento1.jpg)

**Objetivos y necesidades**

- Encontrar talleres confiables que garanticen un buen servicio.

- Poder agendar citas de manera rápida y sin pérdida de tiempo.

- Hacer seguimiento al estado de su vehículo mientras está en reparación.

- Tener transparencia en costos, tiempos y disponibilidad.

- Consultar reseñas reales de otros clientes antes de elegir un taller.

**Frustraciones**

- Pérdida de tiempo al llamar o visitar talleres para preguntar disponibilidad.

- Desconfianza hacia talleres informales por malas experiencias.

- Falta de seguimiento y comunicación clara sobre el estado del vehículo.

- No tener un historial organizado de mantenimientos realizados.

**Comportamientos digitales**

- Usa Google Maps y WhatsApp para buscar y comunicarse con talleres.

- Confía en reseñas en línea, pero reconoce que no siempre son fiables.

- Prefiere plataformas móviles rápidas y fáciles de usar.

**Frase representativa**

"Quiero un taller en el que pueda confiar y que me ahorre tiempo en llamadas innecesarias."


------------
#### User Persona - Segmento 2: Administrador de taller automotriz

- **Nombre: **Jorge Salazar
- **Edad:** 38 años
- **Sexo:** Masculino
- **Ocupación:** Administrador y dueño de un taller automotriz en Lima (zona industrial)
- **Ubicación:** Lima – Cercado de Lima

![User_Person_Segmento2](Assets/chapter-II/User_Person_Segmento2.jpg)

**Objetivos y necesidades**

- Organizar mejor las citas y disponibilidad de sus técnicos.

- Ofrecer a sus clientes un servicio más moderno y confiable.

- Aumentar la visibilidad del taller en internet para captar nuevos clientes.

- Fidelizar clientes con transparencia y comunicación constante.

- Reducir los reclamos por falta de información o retrasos.

**Frustraciones**

- No contar con una base de datos centralizada de clientes y técnicos.

- Pérdida de clientes por saturación de horarios y mala organización.

- Dificultad para competir con talleres grandes que tienen más visibilidad.

- Manejo desordenado de la información en medios dispersos (llamadas, mensajes, hojas).

**Comportamientos digitales**

- Usa Facebook y WhatsApp para promocionar su taller.

- Maneja citas en cuadernos y hojas de cálculo básicas.

- Tiene interés en soluciones digitales, pero necesita que sean simples y rápidas de implementar.

**Frase representativa**

"Necesito una herramienta que me ayude a organizar mi taller y mostrarle a los clientes que somos confiables."
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping

## 2.4. Big Picture Event Storming
## 2.5. Ubiquitous Language

---

# Capítulo III: Requirements Specification
## 3.1 To-Be Scenario Mapping
## 3.2. User Stories
## 3.3. Impact Mapping
## 3.4. Product Backlog

---

# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.2. Web Applications Mock-ups
### 4.4.3. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Design-Level Event Storming
### 4.6.2. Software Architecture Context Diagram
### 4.6.3. Software Architecture Container Diagrams
### 4.6.4. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams

## 4.8. Database Design
### 4.8.1. Database Diagrams

---

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
#### 5.2.1.2. Aspect Leaders and Collaborators
#### 5.2.1.3. Sprint Backlog 1
#### 5.2.1.4. Development Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint

## 5.3. Validation Interviews
### 5.3.1. Diseño de Entrevistas
### 5.3.2. Registro de Entrevistas
### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product

---

# Conclusiones
# Conclusiones y recomendaciones
# Video About-the-Team
# Bibliografía
# Anexos

