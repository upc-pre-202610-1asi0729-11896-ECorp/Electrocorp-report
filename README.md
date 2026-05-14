<div align="center">

<img src="assets/UPC_logo_transparente.png"></img><br>

<h3>Universidad Peruana de Ciencias Aplicadas</h3>
<h4>Facultad de Ingeniería</h4>
<h4>Carrera de Ingeniería de Software</h4>
<h4>Periodo 202610</h4>
<h4>1ASI0729 Desarrollo de Aplicaciones Open Source</h4>
<h4>NRC 11896</h4>
<h4>Docente: Efraín Ricardo Bautista Ubillús</h4>
<h4>Informe del Trabajo Final</h4>
<h4>Startup: ElectroCorp</h4>
<h4>Producto: Smart</h4>

| **Código** | **Apellidos y Nombres**               |
| :--------: | :------------------------------------ |
| U20241e179 | Tavara Correa, Sebastian Oswaldo      |
| U202418755 | Santiago Atanacio, Jairo Mathias      |
| U20241e014 | Cabrejos Chocco, Diego Alexander      |
| U20241e406 | Loa Rojas, Jean Franck                |

### Diciembre 2025
</div>
<div style="page-break-after: always;"></div>


## Registro de Versiones del Informe

| Versión |  Fecha   |                                       Autor                                        |                                                  Descripción de modificación                                                   |
| :-----: | :------: | :--------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------: |
|   TB1   | 03/04/2026 | Todos | Avance del trabajo: Completando el contenido del Documento |
|   TP1   |            |       |                                                            |
|   TB2   |            |       |                                                            |
|   TF1   |            |       |                                                            |

<div style="page-break-after: always;"></div>

## Project Report Collaboration Insights
A continuación, se detallan los repositorios utilizados a lo largo del proyecto:

#### Link del repositorio del Reporte:

- 

#### Link del repositorio de la Landing Page:

- 

#### Link del repositorio del Frontend:

- 

#### Link del repositorio del Backend:

- 

### **Entrega TB1:**
[text]

##### Participación por integrante:

- 

# Contenido

## Índice

- [Registro de versiones del informe](#registro-de-versiones-del-informe)

- [Project Report Collaboration Insights](#project-report-collaboration-insights)

- [Contenido](#contenido)

- [Student Outcome](#student-outcome-1)

- [Capítulo I: Introducción](#capitulo-i-introduccion)
  - [1.1. StartUp Profile](#11-startup-profile)
    - [1.1.1. Descripción de la StartUp](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de Integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y Problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hyphotesis Statements](#1223-lean-ux-hyphotesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis]()
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Persona](#231-user-persona)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.4 Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5 Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification]()
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design]()
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
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation & Deployment]()
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
    - [5.2.2. Sprint 2](#522-sprint-2)
      - [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
      - [5.2.2.2. Aspect Leaders and Collaborators](#5222-aspect-leaders-and-collaborators)
      - [5.2.2.3. Sprint Backlog 2](#5223-sprint-backlog-2)
      - [5.2.2.4. Development Evidence for Sprint Review](#5224-development-evidence-for-sprint-review)
      - [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
      - [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
      - [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
      - [5.2.2.8. Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)
    - [5.2.3. Sprint 3](#523-sprint-3)
      - [5.2.3.1. Sprint Planning 3](#5231-sprint-planning-3)
      - [5.2.3.2. Aspect Leaders and Collaborators](#5232-aspect-leaders-and-collaborators)
      - [5.2.3.3. Sprint Backlog 3](#5233-sprint-backlog-3)
      - [5.2.3.4. Development Evidence for Sprint Review](#5234-development-evidence-for-sprint-review)
      - [5.2.3.5. Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)
      - [5.2.3.6. Services Documentation Evidence for Sprint Review](#5236-services-documentation-evidence-for-sprint-review)
      - [5.2.3.7. Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)
      - [5.2.3.8. Team Collaboration Insights during Sprint](#5238-team-collaboration-insights-during-sprint)
    - [5.2.4. Sprint 4](#524-sprint-4)
      - [5.2.4.1. Sprint Planning 4](#5241-sprint-planning-4)
      - [5.2.4.2. Aspect Leaders and Collaborators](#5242-aspect-leaders-and-collaborators)
      - [5.2.4.3. Sprint Backlog 4](#5243-sprint-backlog-4)
      - [5.2.4.4. Development Evidence for Sprint Review](#5244-development-evidence-for-sprint-review)
      - [5.2.4.5. Execution Evidence for Sprint Review](#5245-execution-evidence-for-sprint-review)
      - [5.2.4.6. Services Documentation Evidence for Sprint Review](#5246-services-documentation-evidence-for-sprint-review)
      - [5.2.4.7. Software Deployment Evidence for Sprint Review](#5247-software-deployment-evidence-for-sprint-review)
      - [5.2.4.8. Team Collaboration Insights during Sprint](#5248-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews]()
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heuristicas](#533-evaluaciones-segun-heuristicas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<div style="page-break-after: always;"></div>

## Student Outcome

Objetivo general, ABET – EAC - Student Outcome 3: Capacidad de comunicarse efectivamente con un rango de audiencias.
| Criterio Especifico | Acciones realizadas | Conclusiones |
|--|--|--|
| Comunica oralmente con efectividad a diferentes rangos de audiencia. | Sebastian Tavara <br>TB1:<br> TP1: <br> TB2: <br> TF1: <br> <br> Diego Cabrejos <br>TB1:<br> TP1: <br> TB2: <br> TF1: <br> <br> Jean Loa <br> TB1: <br> TP1: <br> TB2: <br> TF1: |	 |
| Comunica por escrito con efectividad a diferentes rangos de audiencia | Sebastian Tavara <br>TB1:<br> TP1: <br> TB2: <br> TF1: <br> <br> Diego Cabrejos <br>TB1:<br> TP1: <br> TB2: <br> TF1: <br> <br> Jean Loa <br> TB1: <br> TP1: <br> TB2: <br> TF1: |	 |


# Capitulo I: Introducción

## 1.1. StartUp Profile

### 1.1.1. Descripción de la StartUp
Es una startup de tecnologia enfocada en democratizar la domótica y la eficiencia energética para los hogares peruanos. 
<br><br>
Actualmesnte, el convertir una casa tradicional en un "hogar inteligente" es percibido como un lujo costoso, que requiere modificar el cableado eléctrico, contratar técnicos especializados y lidiar con aplicaciones genéricas que no reflejan la realidad del consumo local o que simplemente son complicados de comprender. Además, los altos costos de energía eléctrica son una preocupación constante para las familias y negocios nuevos.
<br><br>
Hemos desarrollado un ecosistema IoT (Internet de las Cosas) plug-and-play que se instala en minutos sobre los interruptores y enchufes existentes, sin necesidad de romper paredes, quebrar techos, ni alterar la red eléctrica. A través de nuestra plataforma web y móvil, los usuarios pueden controlar sus electrodomésticos de forma remota, podran programar horarios de encendido y monitorear el consumo de energia de su hogar en tiempo real.

---

## Misión

Nuestra misión es brindar a las familias peruanas soluciones de domótica accesibles y de fácil instalación que les permitan tomar el control de su consumo eléctrico, optimizando su presupuesto mediante tecnología inteligente.

---

## Visión

Queremos que ElectroCorp sea el referente en el Perú en gestión energética residencial, transformando los hogares tradicionales en espacios eficientes y sostenibles que alivien la economía familiar y contribuyan al cuidado del medio ambiente.

### 1.1.2. Perfiles de integrantes del equipo
| **Nombre Completo del integrante**    |	**Descripcion de la carrera** | **Fotografia** | **Conocimientos y habilidades**
| :------------------------------------ |:------------------------------------ |:------------------------------------ |:------------------------------------ |
| Tavara Correa, Sebastian Oswaldo      |Ingeniería de Software Universidad Peruana de Ciencias Aplicadas | <img src="assets/foto-carnet-sebastian-tavara.jpg"> | Soy Sebastian Oswaldo Tavara Correa estudiante de la carrera de ingeniería de software, actualmente cursando el 5to ciclo, me considero una persona estudiosa y muy colaborativa al trabajar en grupo. Me adapto rápidamente a cualquier entorno. Me interesa desarrollar soluciones tecnológicas que tengan un impacto positivo. Creo que el desarrollo de software no debe limitarse en buscar la mayor funcionalidad, sino que también en generar bienestar en la sociedad.
| Santiago Atanacio, Jairo Mathias      |Ingeniería de Software Universidad Peruana de Ciencias Aplicadas| <img src="assets/Jairo_Santiago.png"> | Soy Jairo Mathias Santiago Atanacio, estudiante de 5to ciclo de Ingeniería de Software. Cuento con una base sólida en el desarrollo de algoritmos en C++ y la creación de interfaces web interactivas mediante HTML, CSS y JavaScript. Me apasiona transformar problemas complejos en soluciones de software eficientes y escalables. Mi enfoque combina la rigurosidad técnica con habilidades blandas como la proactividad y la empatía, lo que me permite integrarme fácilmente en equipos colaborativos bajo metodologías ágiles.
| Cabrejos Chocco, Diego Alexander      |Ingeniería de Software Universidad Peruana de Ciencias Aplicadas | foto | Soy Diego Alexander Cabrejos Chocco estudiante de la carrera de ingeniería de software, actualmente cursando el 5to ciclo, soy una persona sociable, creativa, que trabaja bien en equipo y busco que todo el equipo participe en las actividades activamente. Me adapto rapidamente a la modalidad de trabajo. Mi meta es poder crear y desarrollar proyectos tecnologicos que tenga un impacto positivo y que sea entretenido. Lo mas interesante de la Software es que cada vez se va expandiendo, y las opciones para poder desarrollar algun proyecto por mas interesante o loco que paresca el tema, no es impedimento para desarrollar lo que desees. (claro que siempre siguiendo el tema legal)
| Loa Rojas, Jean Franck      |Ingeniería de Software Universidad Peruana de Ciencias Aplicadas| foto | Soy Jean Franck Loa Rojas, estudiante de 5to ciclo de la carrera de Ingeniería de Software. Actualmente estoy abierto a oportunidades laborales para emplear mis conocimientos en programación y obtener experiencia trabajando de la mano con conocedores y profesionales de mi rubro académico. Estoy emocionado por todo lo que puede venir en el futuro, y las colaboraciones tecnológicas entre países para compartir conocimiento y prosperar una nación unida y pacífica.
| Integrante 5      |carrera| foto | text

## 1.2 *Solution Profile*
### 1.2.1 Antecedentes y problemática
La energía eléctrica, es uno de los recursos más importantes de nuestra sociedad actual, ayudándonos a desarrollar multiplicidad de tareas, ya sea en el hogar, escuelas, universidades, calles, empresas, trabajos, congreso, etc. Actualmente existen enchufes inteligentes que ayudan al gestionamiento de la energía eléctrica en casas de lujo, hoteles y demás zonas de alto prestigio y valor económico. Pero qué sucede con aquellas personas o familias que quieren gestionar su electricidad o controlar su energía en casa, pero que no cuentan con los recursos necesarios para poder costearse estos lujos.

## 5W & 2H
## Objetivos
## Restricciones
### 1.2.2 Lean UX Process
#### 1.2.2.1 Lean UX Problem Statements
Los hogares urbanos y pequeños negocios en el Perú enfrentan grandes dificultades para modernizar su infraestructura eléctrica y adoptar tecnologías de domótica. Actualmente, convertir una vivienda tradicional en un "hogar inteligente" es percibido como un lujo costoso que requiere modificaciones invasivas en el cableado, la ruptura de paredes y la contratación de técnicos especializados. Esta situación limita el acceso a la tecnología y mantiene una preocupación constante por los altos costos de energía eléctrica, los cuales afectan directamente la economía de las familias de clase media y la rentabilidad de los nuevos emprendimientos.

El problema central es que los propietarios y administradores carecen de una herramienta digital accesible y adaptada a la realidad de las viviendas con más de 10 años de antigüedad, que les permita monitorear y controlar el consumo de energía de manera sencilla. Las soluciones actuales en el mercado son complejas de configurar o utilizan aplicaciones genéricas que no reflejan el gasto real en moneda local (Soles). La ausencia de un control eficiente contribuye a desperdicios energéticos y sobrecostos significativos en los recibos de luz, representando una carga económica que impacta el presupuesto mensual de los usuarios.

ElectroCorp responde a esta necesidad con un ecosistema IoT plug-and-play diseñado para instalarse en minutos sobre interruptores y enchufes existentes, sin necesidad de alterar la red eléctrica ni realizar obras civiles. A través de nuestra plataforma web y móvil intuitiva, facilitamos el control remoto de dispositivos, la programación de horarios y el monitoreo del consumo en tiempo real. Esto no solo democratiza el acceso a la domótica en el Perú, sino que empodera al usuario para optimizar su gasto energético y transformar su entorno en un espacio eficiente y sostenible.

#### 1.2.2.1 Lean UX Assumptions

###### ¿Quién es el usuario?

Los usuarios de ElectroCorp se dividen en dos grupos principales. Primero, los usuarios residenciales, conformados por familias de clase media que viven en zonas urbanas con viviendas de infraestructura antigua y buscan reducir su gasto mensual de luz sin realizar obras civiles. Segundo, los usuarios comerciales, que incluyen dueños y administradores de pequeños negocios (talleres, oficinas y restaurantes) que necesitan optimizar sus costos operativos y asegurar que sus equipos eléctricos funcionen de manera eficiente y segura.

###### ¿Dónde encaja nuestro producto, en su trabajo o en su vida?

En el ámbito residencial, ElectroCorp se integra en la vida diaria y en la planificación financiera del hogar, permitiendo a los usuarios gestionar su entorno de manera remota y consciente. En el ámbito comercial, se convierte en una herramienta estratégica de gestión operativa que ayuda a los dueños de negocios a controlar el gasto energético de sus locales y mejorar la seguridad al finalizar la jornada laboral.

###### ¿Qué problema resuelve nuestro producto?

ElectroCorp soluciona la alta barrera de entrada a la domótica en el Perú, eliminando la necesidad de modificar el cableado eléctrico o realizar costosas remodelaciones. Resuelve la falta de visibilidad sobre el consumo energético real, permitiendo a los usuarios identificar qué dispositivos generan un gasto excesivo y tomar medidas preventivas para reducir el monto de sus recibos de luz en moneda local.

###### ¿Cuándo y cómo se utiliza nuestro producto?

La plataforma se utiliza de forma continua mediante el monitoreo en tiempo real desde dispositivos móviles o web. Los usuarios interactúan con ella principalmente al salir de casa o del negocio para verificar que todo esté apagado, al programar horarios automáticos para electrodomésticos de alto consumo (como termas o maquinaria) y al recibir notificaciones de alerta cuando se detectan picos de consumo inusuales.

###### ¿Qué características son importantes?

- Instalación física no invasiva (Plug & Play) sobre interruptores y enchufes existentes.

- Monitoreo del consumo eléctrico traducido directamente a Soles (S/).

- Control remoto y programación de horarios desde una interfaz web y móvil sencilla.

- Sistema de alertas preventivas ante consumos elevados o dispositivos encendidos innecesariamente.

- Interfaz en español diseñada para ser comprendida por usuarios sin conocimientos técnicos avanzados.

###### ¿Cómo debe verse y comportarse nuestro producto?

ElectroCorp debe proyectar una imagen de modernidad, eficiencia y simplicidad. La interfaz debe ser intuitiva y fluida, con indicadores visuales claros (gráficos de consumo) que faciliten la interpretación de los datos financieros. El comportamiento del sistema debe ser altamente confiable y seguro, transmitiendo al usuario la tranquilidad de tener el control total de su infraestructura eléctrica en la palma de su mano.


#### 1.2.2.1 Lean UX Hypothesis Statements

###### Hipótesis 1:

Creemos que al ofrecer dispositivos IoT que no requieren modificar el cableado eléctrico ni realizar obras civiles, lograremos una adopción masiva en hogares urbanos con infraestructura antigua. Esto será posible gracias a un sistema de instalación externa que se coloca sobre los interruptores existentes, eliminando la necesidad de técnicos especializados.

**Business Outcome:** Alta penetración en el mercado de viviendas antiguas y reducción de barreras de entrada para nuevos clientes.  
**Users:** Familias de clase media en viviendas urbanas antiguas e inquilinos que no pueden modificar su infraestructura.  
**User Outcome:** Automatización inmediata del hogar sin costos de instalación profesional ni daños a la propiedad.  
**Feature:** Hardware IoT plug-and-play adaptable a interruptores y enchufes tradicionales.

###### Hipótesis 2:

Consideramos que si proporcionamos una plataforma digital (web y móvil) intuitiva, en español y adaptada al contexto local, los usuarios tendrán mayor confianza y utilizarán el sistema de manera regular para gestionar sus hogares y negocios.

**Business Outcome:** Incremento en la retención de usuarios activos y fidelización de marca mediante una experiencia de uso simplificada.  
**Users:** Usuarios residenciales y dueños de pequeños negocios con diversos niveles de habilidades tecnológicas.  
**User Outcome:** Acceso sencillo y seguro al control de dispositivos eléctricos sin barreras de idioma o complejidad técnica.  
**Feature:** Interfaz de usuario (UI) intuitiva con guías de configuración integradas en español.

###### Hipótesis 3:

Suponemos que al demostrar un ahorro tangible en el recibo de luz mediante el monitoreo del consumo en Soles (S/) en tiempo real, los clientes estarán dispuestos a pagar por el producto y recomendarlo activamente en su entorno.

**Business Outcome:** Crecimiento sostenido de ventas basado en el retorno de inversión (ROI) positivo para el cliente y recomendaciones boca a boca.  
**Users:** Jefes de hogar y administradores de pequeños negocios preocupados por los altos costos fijos de energía.  
**User Outcome:** Reducción del gasto mensual de energía y optimización del presupuesto familiar o comercial. 
**Feature:** Panel de monitoreo de consumo en tiempo real con conversión automática de Watts a Soles (S/).

#### 1.2.2.1 Lean UX Canvas


<table>  
<tr>  
<td>  
<h2>Business Problem</h2>  
- La mayoría de las soluciones de domótica requieren modificar la infraestructura eléctrica, lo que encarece su implementación.  <br>
- Los hogares en el Perú no están diseñados para la automatización, generando barreras técnicas.  <br>
- Existe poca accesibilidad a soluciones IoT económicas para familias de ingresos medios y bajos.
</td>  
<td>  
<h2>Solutions</h2>  
-   Módulo IoT "No-Neutro" ultracompacto: Un dispositivo basado en ESP32 y relé que sea lo suficientemente pequeño para caber en las cajas eléctricas estándar de las paredes peruanas sin requerir el cable neutro. <br>
-   Interruptores _Plug & Play_: Placas de interruptores táctiles o físicos que ya traigan el módulo inteligente integrado y se instalen exactamente igual que un interruptor tradicional. <br>
-  Kits de inicio pre-configurados:** Paquetes como "Kit Habitación" o "Kit Sala" donde los dispositivos ya vienen emparejados entre sí, listos para instalar sin configuraciones complejas.
</td>  
<td>  
<h2>Business Outcomes</h2>  
- Incrementar la adopción de hogares inteligentes en sectores urbanos y semiurbanos.  <br>
- Reducir los costos energéticos en hogares y pequeños negocios mediante control eficiente. <br>  
- Posicionar a SmartHome Control como solución peruana innovadora y accesible.
</td>  
</tr>  
<tr>  
<td>  
<h2>Users</h2>  
- Familias de clase media en zonas urbanas que buscan comodidad y ahorro energético. <br>
- Propietarios de pequeños negocios y oficinas que desean optimizar consumo eléctrico.
</td>  
<td></td>  
<td>  
<h2>User Outcomes & Benefits</h2>  
- Automatizar el control de luces y dispositivos sin hacer modificaciones costosas.  <br>
- Gestionar sus electrodomésticos desde el celular o la computadora, en tiempo real.  <br>
- Obtener reportes o alertas sobre el estado de los dispositivos para mayor seguridad y eficiencia.
</td>  
</tr>  
<tr>  
<td>  
<h2>Hypotheses</h2>  
- Dispositivos sin obras facilitarán la adopción masiva en viviendas antiguas. <br>
- Una app intuitiva en español generará mayor confianza y uso regular. <br>
- Visualizar el ahorro económico en soles (S/) mediante el monitoreo en tiempo real motivará la compra.
</td>  
<td>  
<h2>What’s the most important thing we need to learn first?</h2>  
- Validar la confianza del usuario en la seguridad del hardware no invasivo. <br>
- Confirmar si el monitoreo en Soles (S/) es un factor decisivo de compra. <br>
- Verificar la estabilidad de la conexión Wi-Fi en viviendas de infraestructura antigua.
</td>  
<td>  
<h2>What’s the least amount of work we need to do to learn the next most important thing?</h2>  
- Lanzar una Landing Page con video demostrativo y lista de espera.  <br>
- Realizar entrevistas a profundidad con dueños de hogares y pequeñas empresas.  <br>
- Crear un Mock-up interactivo del panel de control de ahorro en Soles.
</td>  
</tr>  
</table>

## 1.3 Segmentos objetivo
El proyecto busca atender a usuarios que requieren soluciones de automatización accesibles y no invasivas, con un enfoque en dos segmentos principales:

- Hogares urbanos con viviendas antiguas (más de 10 años de construcción).  
Este segmento comprende familias de clase media que residen en departamentos y casas en zonas urbanas, donde la infraestructura eléctrica fue instalada hace más de una década y no está diseñada para la domótica. Según el Censo Nacional 2017 del INEI, aproximadamente 79,3 % de la población peruana vive en áreas urbanas (INEI, 2017). Dada la antigüedad de gran parte de estas viviendas, existe una alta necesidad de modernización mediante soluciones que no requieran remodelaciones eléctricas costosas. Nuestro producto responde directamente a esta problemática al ofrecer automatización sin modificaciones en el cableado.
- Pequeños negocios y talleres en zonas urbanas.  
Este segmento incluye comercios, oficinas, talleres y restaurantes que buscan optimizar el uso de sus dispositivos eléctricos, reducir costos operativos y mejorar la seguridad. En el Perú, las micro y pequeñas empresas representan el 99,2 % del tejido empresarial nacional (Ministerio de la Producción, 2023) y más del 91 % de ellas operan en zonas urbanas (ComexPerú, 2022). Estos negocios generalmente se establecen en locales con instalaciones tradicionales, lo que dificulta la implementación de domótica. SmartHome Control ofrece una solución práctica y económica, adaptada a su infraestructura y a sus necesidades de ahorro energético.
# Capitulo II: Requirements Elicitation & Analysis
## 2.1 Competidores
En este apartado, examinamos el ecosistema de soluciones existentes en el mercado peruano que ofrecen servicios de automatización residencial y gestión de dispositivos eléctricos. 
### 2.1.1 Análisis Competitivo
A través de esta comparativa, buscamos determinar el valor diferencial de ElectroCorp frente a las alternativas globales. El análisis se enfoca en detectar necesidades no resueltas por las grandes marcas, especialmente en lo que respecta a la adaptabilidad a la infraestructura eléctrica peruana (instalación sin obra civil) y la interpretación financiera del consumo energético en moneda local.

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="6"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td>¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5"> Queremos saber cómo está posicionado cada posible competidor con nuestro producto, así podemos detectar ventajas competitivas y diferenciar nuestra propuesta de valor.</td>
  </tr>
  <tr>
    <td colspan="2">Nombre y logo de competidor</td>
    <td><b>ElectroCorp <img src="assets/logo_electrocorp.jpeg" alt="Smart" width="120" height="120" /> </b></td>
    <td><b> Sonoff Peru</b> <img src="assets/sonoff.png" width="120" height="120" /> </td>
    <td><b>Xiaomi Mi Smart Plug</b> <img src="assets/xiaomi.png" width="120" height="120" /> </td>
    <td><b>Smart Plugs</b> <img src="assets/promart.png" width="120" height="120" /> </td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil</b></td>
    <td><b>Overview</b></td>
    <td> Startup peruana de tecnología enfocada en democratizar la domótica mediante un ecosistema IoT plug-and-play que se instala sobre interruptores y enchufes existentes sin modificar el cableado eléctrico. </td>
    <td> Ofrece variedad en enchufes, interruptores, relés WIFI y dispositivos para automatización del hogar. Su funcionamiento es simple, se conecta directamente a la red electrica y se controla mediante la app eWeLink.</td>
    <td>Es un enchufre inteligente que convierte cualquier dispositivo electrico en un aparato “inteligente”. Permitiendo asi: encender/apagar remotamente, programar horarios y controlar el consumo electrico desde la app llamada “Xiaomi Home”.</td>
    <td>Promart entre muchos otros productos comercializa enchufes inteligentes (Smart Plugs) Con la funcion de poder encender/apagar remotamente, temporizador, conexion WIFI y control mediante la app.</td>
  </tr>
  <tr>
    <td><b>Ventaja competitiva ¿Qué valor ofrece a los clientes?</b></td>
    <td> - Instalación no invasiva (sin técnicos ni obras civiles).<br> - Monitoreo de consumo en Soles (S/) en tiempo real<br>- Una plataforma diseñada específicamente para la realidad del consumo eléctrico en Perú. </td>
    <td> - Variedad en productos que se adaptan a distintos aparatos y situaciones (no solo enchufes, también interruptores y relés). <br> -Precio accesible <br> -Soporte local y venta directa en Perú.</td>
    <td> -Marca reconocida a nivel mundial por su calidad y confiabilidad<br>-Integración directa con el ecosistema Xiaomi (atractivo para personas que cuenten con dispositivos Xiaomi).</td>
    <td> -Disponibilidad, hay tiendas fisicas a nivel nacional<br>-Facilidad de compra y confianza al ser una cadena de empresas conocida en Peru.<br>-Precios competitivos en relacion a productos similares</td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil de Marketing</b></td>
    <td><b>Mercado objetivo</b></td>
    <td>- Familias de clase media en zonas urbanas con viviendas de más de 10 años de antigüedad.<br>- Micro/pequeñas empresas (talleres, restaurantes) que buscan reducir costos operativos.</td>
    <td>-Personas interesadas en automatizar su vivienda a bajo precio y sin necesidad de conocimientos tecnicos.<br>- Personas jovenes y familias que buscan comodidad (encender/apagar)<br>- Emprendedores pequeños (restaurantes, oficinas, talleres).</td>
    <td>-Consumidores que ya tengan productos xiami, ya sea celulares, camaras, aspiradoras)<br>-Jovenes y familias que tengan alto uso de tecnologia y preferencia por marcas reconocidas<br>- Personas que valoran la calidad y seguridad certificada.</td>
    <td>-Familias que son clientes recurrentes de Promart ya se para compras del hogar.<br>- Personas que no tienen conocimiento en tecnologia y buscan algo facil de instalar.</td>
  </tr>
  <tr>
    <td><b>Estrategias de marketing</b></td>
    <td>- Marketing de contenidos sobre ahorro energético.<br>- Enfoque en la facilidad de autoinstalación ("Hazlo tú mismo").<br>- Presencia activa en canales digitales dirigidos a emprendedores y jefes de hogar.</td>
    <td>-Venta directa online en su tienda web.<br>- Marketing digital por medio de redes sociales (Facebook, Instagram).<br>- Estrategia de precios accesibles al consumidor.</td>
    <td>-Integracion de un dispositivo mas al ecosistema de Xiaomi<br>
- Branding Fuerte, Xiaomi al ser una marca con reconocimiento global, hace transmitir confianza al cliente.</td>
    <td>
-Presencia de tiendas Promart a nivel nacional, lo que da confianza al cliente.<br>
- Promociones y descuentos por temporadas.<br>
- Estrategia de Conveniencia: facil de conseguir, comprar y devolver en casos de problemas.</td>
  </tr>
  <tr>
    <td rowspan="3"><b>Perfil de Producto</b></td>
    <td><b>Productos y Servicios</b></td>
    <td>- Adaptadores IoT para interruptores y enchufes, aplicación móvil en español y plataforma web para programación de horarios y gestión de eficiencia energética. </td>
    <td>-Ofrece enchufes inteligentes, interruptores WIFI, relés, sensores, etc. También ofrece soporte técnico local, tutorías y asesoría de uso básico.</td>
    <td>Su producto principal es el enchufe inteligente compacto, se integra con la app “Xiaomi Home” y con el ecosistema Xiaomi</td>
    <td>-Encufhes inteligentes importados (marcas genéricas).</td>
  </tr>
  <tr>
    <td><b>Precios y Costos</b></td>
    <td> Rango de precios accesible para la clase media (aprox. S/ 70 - S/ 120), posicionándose como una inversión de rápido retorno mediante el ahorro de luz.</td>
    <td> Enchufes desde S/ 60 – S/ 100</td>
    <td>Desde S/ 90 a S/ 130.</td>
    <td>Desde S/ 60  a S/ 100</td>
  </tr>
  <tr>
    <td><b>Canales de distribución (Web y/o móvil)</b></td>
    <td>- Plataforma web oficial.<br>- Aplicación móvil propia y posibles alianzas estratégicas con ferreterías locales.</td>
    <td>-Web Principal (sonoffperu.com)<br>
- Distribución en redes sociales y Marketplace peruano</td>
    <td>
-Tiendas Online Oficiales (ShopMi.pe, Linio, MercadoLibre)<br>
-Tiendas fisicas (malls).</td>
    <td>
-Tiendas fisicas Promart. <br>
-Tienda online Promart.pe<br>
- App movil de Promart.</td>
  </tr>
  <tr>
    <td rowspan="5"><b>Análisis SWOT</b></td>
    <td colspan="5">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</td>
  </tr>
  <tr>
    <td><b>Fortalezas</b></td>
    <td>- Instalación simple sin obra civil.<br>- Conocimiento profundo del mercado local (tarifas en Soles).<br> - Solución adaptada a infraestructura antigua.</td>
    <td>- Variedad de productos. <br>
    - Precios accesibles<br>
- Soporte tecnico y garantia local<br>
- Compatibilidad con ecosistemas como Google y Alexa</td>
    <td>
- Marca reconocida globalmente.<br>
- Ecosistema bien consolidado<br>
- Fuerte presencia en retail y e-commerce peruanos.</td>
    <td>
- Muchas tiendas fisicas en Peru.<br>
- Disponibilidad inmediata y confianza en la compra.</td>
  </tr>
  <tr>
    <td><b>Debilidades</b></td>
    <td>- Marca nueva con presupuesto limitado para publicidad masiva frente a gigantes globales.</td>
    <td>- Depende de importacion (no produce localmente)</td>
    <td>
- Precios más altos que competidores locales.<br>
- Dependencia del ecosistema Xiaomi.</td>
    <td>
- Productos genericos con poca diferenciacion.<br>
- Sin ecosistema propio.<br>
- Dependencia de proveedores externos.</td>
  </tr>
  <tr>
    <td><b>Oportunidades</b></td>
    <td>- Incremento constante de las tarifas eléctricas en el mercado peruano.<br> - Gran volumen de viviendas urbanas que necesitan modernización.</td>
    <td>
- Mercado local con poca competencia especializada<br>
- Posibilidad de diferenciarse ofreciendo instalación y soporte</td>
    <td>
- Posibilidad de cross-selling para maximizar ganancias.<br>
- Tendencia global hacia la domótica segura y certificada.</td>
  <td>
- Captar al consumidor no especializado que busca soluciones rápidas.<br>
- Posibilidad de aliarse con marcas reconocidas para diferenciar su oferta.</td>
  </tr>
  <tr>
    <td><b>Amenazas</b></td>
    <td>- Ingreso de nuevos dispositivos genéricos de bajo costo.<br> - Inestabilidad en los precios de componentes electrónicos y módulos Wi-Fi importados.</td>
    <td>
- Competencia de marcas globales con mayor presupuesto de marketing<br>
- Cambios en regulaciones eléctricas o certificaciones necesarias.</td>
    <td>
- Productos genéricos más baratos que cumplen funciones similares<br>
- Cambios en restricciones de importación o alzas en costos logísticos.</td>
    <td>
- Competidores Online que ofrecen más variedad.<br>
- Clientes que buscan marcas con ecosistemas establecidos.</td>
  </tr>
</table>

### **2.1.2 Estrategias y tácticas frente a competidores**
A partir del análisis competitivo realizado, se han definido las siguientes estrategias y tácticas para posicionar a ElectroCorp en el mercado peruano y afrontar las fortalezas de la competencia.

##### **1. Aprovechar la Fortaleza: Instalación No Invasiva y Enfoque en Hogares Peruanos**
**Estrategia**

Posicionarse como la única alternativa de automatización que no requiere modificaciones en el cableado eléctrico ni contratar técnicos especializados, diferenciándose de competidores como Sonoff que exigen instalaciones complejas.

**Tácticas**

- **Guías de Autoinstalación:** Producción de tutoriales en video enfocados en la instalación del sistema sobre interruptores y enchufes estándar de viviendas peruanas.
- **Kits para Departamentos Alquilados:** Desarrollo de paquetes de dispositivos diseñados específicamente para usuarios que no tienen permiso para romper paredes o techos.
- **Demostraciones en Tiendas Locales:** Realización de exhibiciones en ferreterías para mostrar que el hardware se instala en minutos sobre la red eléctrica existente.

**Valor Añadido**

- Eliminación de costos adicionales por contratación de electricistas o técnicos externos.
- Facilidad para retirar los dispositivos y llevarlos a una nueva vivienda sin dejar daños en la infraestructura.

##### **2.  Aprovechar la Oportunidad: Incremento de Tarifas Eléctricas y Necesidad de Ahorro**
**Estrategia**

Centrar la propuesta de valor en el control del presupuesto familiar mediante el monitoreo del consumo de energía en tiempo real y en moneda local (Soles).

**Tácticas**

- **Panel de Control en Soles:** Implementación de una interfaz en la aplicación que traduzca el consumo de Watts a Soles basándose en el pliego tarifario local.
- **Sistema de Alertas de Presupuesto:** Configuración de notificaciones móviles que avisen al usuario cuando el consumo se acerque a un límite de gasto mensual establecido.
- **Reportes de Consumo Real:** Generación de resúmenes semanales que identifiquen qué electrodomésticos generan el mayor gasto energético en el hogar.

**Valor Añadido**

- Gestión eficiente de la economía del hogar mediante información financiera clara y directa.
- Capacidad de tomar acciones preventivas para reducir el monto del recibo de luz antes de que termine el mes.

##### **3.  Afrontar la Amenaza: Presencia de Marcas Globales y Soluciones Genéricas**
**Estrategia**

Mitigar la desconfianza hacia los productos importados mediante la oferta de soporte técnico local y una plataforma adaptada a la realidad del consumo peruano.

**Tácticas**

- **Soporte Técnico por WhatsApp:** Establecimiento de un canal de atención directa en español para resolver dudas sobre la configuración inicial de la plataforma.
- **Garantía de Reemplazo Inmediato:** Implementación de un servicio de cambio de hardware rápido en Lima ante cualquier falla de fábrica, evitando esperas de importación.
- **Actualizaciones Basadas en el Usuario:** Desarrollo de nuevas funcionalidades en la plataforma web y móvil a partir de las sugerencias de los clientes locales.

**Valor Añadido**

- Respaldo y seguridad de una marca con presencia física y técnica en el país.
- Reducción de la incertidumbre al configurar dispositivos inteligentes gracias al acompañamiento personalizado.
## 2.2 Entrevistas
### 2.2.1. Diseño de entrevistas

##### Preguntas Generales

- ¿Cuál es su nombre?
- ¿Cuántos años tiene usted?
- ¿En qué ciudad y distrito reside?
- ¿A qué se dedica y cuál es su formación académica?
- ¿Qué dispositivos electrónicos utiliza con mayor frecuencia (smartphone, laptop, otros)?  
- ¿Qué aplicaciones o redes sociales utiliza para informarse sobre tecnología o mejoras para el hogar/negocio
- ¿Qué marcas de tecnología o electrodomésticos prefiere por su confiabilidad?
- ¿Se considera una persona que se adapta rápido a la tecnología o prefiere lo tradicional?
##### Preguntas Específicas

###### Segmento 1: Hogares urbanos con viviendas antiguas (mayor a 10 años de construcción)

1. ¿Cómo es el estado de las instalaciones eléctricas en su hogar actualmente?
2. ¿Qué tan seguido revisa su recibo de luz y qué siente al ver el monto final?
3. ¿Ha intentado implementar soluciones de "hogar inteligente"?
4. ¿Cuál es su mayor temor al pensar en contratar a un técnico para remodelar su casa?
5. ¿Qué electrodoméstico le gustaría poder apagar desde su celular si olvida hacerlo al salir?
6. ¿Cuánto tiempo estaría dispuesto a invertir en instalar una solución por su cuenta si no requiere herramientas?
7. ¿Le interesaría ver su consumo de energía traducido a Soles en tiempo real?
8. ¿Qué características buscaría en una aplicación para que sea fácil de usar para toda su familia?

###### Segmento 2: Pequeños negocios y talleres en zonas urbanas

1. ¿Qué equipos eléctricos son críticos para la operación diaria de su negocio o taller?
2. ¿Cómo asegura que todos los equipos queden apagados al cerrar el local?
3. ¿Qué impacto económico tiene el recibo de luz en la rentabilidad de su negocio o taller (bajo, moderado, crítico)?
4. ¿Ha tenido problemas por dejar equipos encendidos accidentalmente después del horario de cierre?
5. ¿Qué canales digitales utiliza para gestionar o promover su negocio actualmente?
6. ¿Qué funciones le darían más tranquilidad: programar horarios de encendido o recibir alertas de sobrecosto?
7. ¿Estaría dispuesto a invertir en una solución tecnológica que no requiera detener sus actividades para su instalación?
8. ¿Cuánto valoraría contar con un reporte que identifique los puntos críticos de desperdicio de energía en su local?


### 2.2.2. Registro de entrevistas 
### 2.2.3. Análisis de entrevistas 
## 2.3. Needfinding
### 2.3.1. User Personas 
### 2.3.2. User Task Matrix 
### 2.3.3. User Journey Mapping 
### 2.3.4. Empathy Mapping
## 2.4. Big Picture Event Storming
## 2.5. Ubiquitous Language
# Capitulo III: Requirements Specification
## 3.1. User Stories
## 3.2. Impact Mapping
## 3.3. Product Backlog
# Capitulo IV: Product Design
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
### 4.8.1. Database Diagrams.
# Capitulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration
## 5.2. Landing Page, Services & Applications Implementation
### 5.2.X. Sprint n 
#### 5.2.X.1. Sprint Planning n
#### 5.2.X.2. Aspect Leaders and Collaborators
#### 5.2.X.3. Sprint Backlog n. 
#### 5.2.X.4. Development Evidence for Sprint Review
#### 5.2.X.5. Execution Evidence for Sprint Review
#### 5.2.X.6. Services Documentation Evidence for Sprint Review
#### 5.2.X.7. Software Deployment Evidence for Sprint Review
#### 5.2.X.8. Team Collaboration Insights during Sprint.
## 5.3. Validation Interviews
### 5.3.1. Diseño de Entrevistas
### 5.3.2. Registro de Entrevistas
### 5.3.3. Evaluaciones según heurísticas
## 5.4. Video About-the-Product.
# Conclusiones
## Conclusiones y recomendaciones
## Video About-the-Team.
# Bibliografía 
# Anexos
