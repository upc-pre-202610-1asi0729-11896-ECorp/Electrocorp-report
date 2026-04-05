<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>

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
| Comunica oralmente con efectividad a diferentes rangos de audiencia. | Sebastian Tavara <br>TB1:<br> TP1: <br> TB2: <br> TF1: <br> <br> Diego Cabrejos <br>TB1:<br> TP1: <br> TB2: <br> TF1: <br> |	 |
| Comunica por escrito con efectividad a diferentes rangos de audiencia | Sebastian Tavara <br>TB1:<br> TP1: <br> TB2: <br> TF1: |	 |


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
| Tavara Correa, Sebastian Oswaldo      |Ingenieria de Software Universidad Peruana de Ciencias Aplicadas | foto | Soy Sebastian Oswaldo Tavara Correa estudiante de la carrera de ingeniería de software, actualmente cursando el 5to ciclo, me considero una persona estudiosa y muy colaborativa al trabajar en grupo. Me adapto rápidamente a cualquier entorno. Me interesa desarrollar soluciones tecnológicas que tengan un impacto positivo. Creo que el desarrollo de software no debe limitarse en buscar la mayor funcionalidad, sino que también en generar bienestar en la sociedad.
| Santiago Atanacio, Jairo Mathias      |carrera| foto | text
| Cabrejos Chocco, Diego Alexander      |Ingenieria de Software Universidad Peruana de Ciencias Aplicadas | foto | text
| Integrante 4      |carrera| foto | text
| Integrante 5      |carrera| foto | text

## 1.2 *Solution Profile*
### 1.2.1 Antecedentes y problemática
## 5W & 2H
## Objetivos
## Restricciones
### 1.2.2 Lean UX Process
#### 1.2.2.1 Lean UX Problem Statements
#### 1.2.2.1 Lean UX Assumptions
#### 1.2.2.1 Lean UX Hypothesis Statements
#### 1.2.2.1 Lean UX Canvas
## 1.3 Segmentos objetivo
# Capitulo II: Requirements Elicitation & Analysis
## 2.1 Competidores
### 2.1.1 Análisis Competitivo


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
    <td><b>Smart <img src="" alt="Smart" width="120" height="120" /> </b></td>
    <td><b> Sonoff Peru</b> <img src="" width="120" height="120" /> </td>
    <td><b>Xiaomi Mi Smart Plug</b> <img src="" width="120" height="120" /> </td>
    <td><b>Smart Plugs</b> <img src="Smart Plugs" width="120" height="120" /> </td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil</b></td>
    <td><b>Overview</b></td>
    <td> text </td>
    <td> Ofrece variedad en enchufes, interruptores, relés WIFI y dispositivos para automatización del hogar. Su funcionamiento es simple, se conecta directamente a la red electrica y se controla mediante la app eWeLink.</td>
    <td>Es un enchufre inteligente que convierte cualquier dispositivo electrico en un aparato “inteligente”. Permitiendo asi: encender/apagar remotamente, programar horarios y controlar el consumo electrico desde la app llamada “Xiaomi Home”.</td>
    <td>Promart entre muchos otros productos comercializa enchufes inteligentes (Smart Plugs) Con la funcion de poder encender/apagar remotamente, temporizador, conexion WIFI y control mediante la app.</td>
  </tr>
  <tr>
    <td><b>Ventaja competitiva ¿Qué valor ofrece a los clientes?</b></td>
    <td>text</td>
    <td> - Variedad en productos que se adaptan a distintos aparatos y situaciones (no solo enchufes, también interruptores y relés). <br> -Precio accesible <br> -Soporte local y venta directa en Perú.</td>
    <td> -Marca reconocida a nivel mundial por su calidad y confiabilidad<br>-Integración directa con el ecosistema Xiaomi (atractivo para personas que cuenten con dispositivos Xiaomi).</td>
    <td> -Disponibilidad, hay tiendas fisicas a nivel nacional<br>-Facilidad de compra y confianza al ser una cadena de empresas conocida en Peru.<br>-Precios competitivos en relacion a productos similares</td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil de Marketing</b></td>
    <td><b>Mercado objetivo</b></td>
    <td>text</td>
    <td>-Personas interesadas en automatizar su vivienda a bajo precio y sin necesidad de conocimientos tecnicos.<br>- Personas jovenes y familias que buscan comodidad (encender/apagar)<br>- Emprendedores pequeños (restaurantes, oficinas, talleres).</td>
    <td>-Consumidores que ya tengan productos xiami, ya sea celulares, camaras, aspiradoras)<br>-Jovenes y familias que tengan alto uso de tecnologia y preferencia por marcas reconocidas<br>- Personas que valoran la calidad y seguridad certificada.</td>
    <td>-Familias que son clientes recurrentes de Promart ya se para compras del hogar.<br>- Personas que no tienen conocimiento en tecnologia y buscan algo facil de instalar.</td>
  </tr>
  <tr>
    <td><b>Estrategias de marketing</b></td>
    <td>text.</td>
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
    <td>text</td>
    <td>-Ofrece enchufes inteligentes, interruptores WIFI, relés, sensores, etc. También ofrece soporte técnico local, tutorías y asesoría de uso básico.</td>
    <td>Su producto principal es el enchufe inteligente compacto, se integra con la app “Xiaomi Home” y con el ecosistema Xiaomi</td>
    <td>-Encufhes inteligentes importados (marcas genéricas).</td>
  </tr>
  <tr>
    <td><b>Precios y Costos</b></td>
    <td>text</td>
    <td> Enchufes desde S/ 60 – S/ 100</td>
    <td>Desde S/ 90 a S/ 130.</td>
    <td>Desde S/ 60  a S/ 100</td>
  </tr>
  <tr>
    <td><b>Canales de distribución (Web y/o móvil)</b></td>
    <td>Plataforma web y app móvil.</td>
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
    <td>text</td>
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
    <td>text</td>
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
    <td>text</td>
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
    <td>text</td>
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

### 2.1.2 Estrategias y tácticas frente a competidores

## 2.2 Entrevistas
### 2.2.1. Diseño de entrevistas
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
