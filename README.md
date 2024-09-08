<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC">


# Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2024-02

<hr>

# <center>Arquitecturas De Software Emergentes</center>

## TB1 REPORT

**Sección:** WX82

**Profesor**: Chistian Luis De Los Rios Fernandez

**StartUp Name**: AgroTech Innovators

**Producto**: AgroTech

### Team Members:

| Member                            |    Code    |
| :-------------------------------- | :--------: |
| Checa Apolinario, Paolo Sebastián | u202112749 |
| Moreno Vergara, Johan Raúl        | u20201C105 |
| Onofre Ruiz, Carlos Jesus         | u202115590 |
| Futuri Illa, Wilfredo             | u201924361 |

<br>

Septiembre del 2023

<br><br>

</div>

# Registro de Versiones del Informe

| Versión |   Fecha    |                                                                                       Autor                                                                                        | Descripción de modificación                                                                                                                                           |
| :-----: | :--------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   TB1   | 28/08/2024 | Checa Apolinario, Paolo Sebastián <br><br> Moreno Vergara, Johan Raúl <br><br> Onofre Ruiz, Carlos Jesus <br><br>  Futuri Illa, Wilfredo| Se realizaron los capítulos: Capítulo I: Introducción, Capítulo II: Requirements Elicitation & Analysis, Capítulo III: Requirements Specification y Capítulo IV: Solution Software Design |

<br><br>

# Project Report Collaboration Insights

- **TB1:** Para esta entrega, realizamos como equipo las actividades correspondientes a los capítulos asignados en el siguiente repositorio dentro de nuestra organización de grupo: 

    <br>

    Link del repositorio del Informe Final: [Github - Informe Final GreenGrow]()

    <br>

    A continuación, se muestran las capturas de evidencia correspondientes al desarrollo de los siguientes capítulos:

    <br>

    - **Capítulo I: Introducción**
    - **Capítulo II: Requirements Elicitation & Analysis**
    - **Capítulo III: Requirements Specification**
    - **Capítulo IV: Solution Software Design**
    
    <div align=center>
        <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282154329721143296/image.png?ex=66de52c5&is=66dd0145&hm=eedb0510e42e128864d9f033c15975a6e23f34c0e27ae77405a4ae1a09aba229&"/>      
    </div>

    <div align=center>
        <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282154728792260668/image.png?ex=66de5324&is=66dd01a4&hm=a6af3754aaa5d0daa51ec828a5ba45a3de8aae2ca36f41af578f6a9e8176a69f&"/>
    </div>

<br><br>

# Contenido

## Tabla de Contenidos

### [Registro de versiones del informe](#registro-de-versiones-del-informe)

### [Project Report Collaboration Insights](#project-report-collaboration-insights)

### [Contenido](#contenido)

### [Student Outcome](#student-outcome-1)

### [Capítulo I: Introducción](#capítulo-i-introducción)

- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-description-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

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
  - [2.3.3. Empathy Mapping](#234-empathy-mapping)
  - [2.3.4. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)

- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)

- [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
  - [4.1.1. Design Purpose](#411-design-purpose)
  - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
    - [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)
    - [4.1.2.2. Quality attribute Scenarios](#4122-quality-attribute-scenarios)
    - [4.1.2.3. Constraints](#4123-constraints)
  - [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)
  - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
  - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
- [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
  - [4.2.1. EventStorming](#421-eventstorming)
  - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
  - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
  - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
  - [4.2.5. Context Mapping](#425-context-mapping)
- [4.3. Software Architecture](#43-software-architecture)
  - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
  - [4.3.2. Software Architecture Context Level Diagrams](#432-software-architecture-context-level-diagrams)
  - [4.3.3. Software Architecture Container Level Diagrams](#433-software-architecture-container-level-diagrams)
  - [4.3.4. Software Architecture Deployment Diagrams](#434-software-architecture-deployment-diagrams)


### [Conclusiones](#conclusiones)

### [Bibliografía](#bibliografía)

### [Anexos](#anexos)

<br><br>

# Student Outcome

| Criterio específico | Acciones realizadas | Conclusiones |
| :------------------: | :-----------------: | :----------: |
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Paolo Sebastián Checa Apolinario** <br> **TB1** <br> Informé a nuestro equipo sobre el tema del proyecto a desarrollar, llegando a un punto en común y entendiendo de forma satisfactoria lo que desarrollaremos en la solución. <br><br> **Carlos Jesus Onofre Ruiz** <br> **TB1** <br> En las reuniones del proyecto, presenté y discutí el propósito del diseño a nivel estratégico, centrándome en cómo las entradas clave, como las historias de usuario, los escenarios de atributos de calidad y las restricciones, influyen en nuestras decisiones. <br><br> **Johan Raúl Moreno** <br> **TB1** <br> Luego de las reuniones acordamos repartirnos parte del documento donde yo me encargué de identificar, analizar y proponer estrategias frente a nuestros competidores y me aseguré que todos los miembros comprendan estos aspectos claves. Además me encargué junto a mis compañeros de elaborar el event storming. <br><br> **Wilfredo Futuro Illa** <br> **TB1** <br> Para esta entrega el equipo se reunió para definir el startup profile, problem statement, User Stories, etc. | **TB1** <br> La comunicación clara y objetiva entre los miembros del equipo permitió una adecuada alineación de ideas y la toma de decisiones estratégicas, facilitando la comprensión del proyecto y la colaboración entre diferentes especialidades y niveles jerárquicos, lo que contribuyó al éxito en el desarrollo de la solución. |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Paolo Sebastián Checa Apolinario** <br> **TB1** <br> Realicé y definí la descripción de la startup, para tener clara la idea del proyecto. Además realicé la arquitectura del software, en la que nos basaremos para el próximo desarrollo e implementación de la solución. <br><br> **Carlos Jesus Onofre Ruiz** <br> **TB1** <br> Documenté de manera detallada y accesible todo el proceso de diseño estratégico, desde la definición del propósito hasta los refinamientos de los escenarios de atributos de calidad. Los reportes incluyeron explicaciones claras sobre cómo las historias de usuario y las restricciones guiaron nuestras decisiones arquitectónicas. <br><br> **Johan Raúl Moreno Vergara** <br> **TB1** <br> Documenté el análisis de competidores, proporcionando un reporte claro sobre las estrategias a seguir para posicionar mejor nuestra solución. También participé en la redacción de las decisiones clave durante el event storming, asegurando que las ideas y resultados fueran comprensibles para los miembros de nuestro equipo y cualquier lector del trabajo. <br><br> **Wilfredo Futuro Illa** <br> **TB1** <br> Se documentó tanto en el word como en github las User Stories, product Backlog, Empathy mapping, etc. | **TB1** <br> Al generar reportes organizados y accesibles sobre la arquitectura del software, las estrategias de diseño y el análisis competitivo, se logró mantener una alineación eficaz entre todos los involucrados, independientemente de su especialidad o nivel jerárquico, garantizando así el desarrollo ordenado y coherente de la solución. |

# Capítulo I: Introducción

## 1.1. StartUp Profile

### 1.1.1. Description de la StartUp

AgroTech Innovators es una startup enfocada en revolucionar la forma en que los agricultores y aficionados acceden y utilizan la tecnología para mejorar sus prácticas agrícolas. Nuestro objetivo es ofrecer una plataforma integral que combine la monitorización avanzada de cultivos mediante sensores IoT, proporcionando a los usuarios datos en tiempo real sobre variables críticas como humedad, luz, temperatura, y más. Además, incluimos un chatbot inteligente que puede responder a preguntas específicas de los usuarios, facilitando la toma de decisiones y optimizando los procesos de cultivo.

- **Visión:** Aspiramos a ser líderes en la integración de la tecnología y la agricultura, promoviendo prácticas agrícolas más inteligentes, sostenibles y accesibles para todos, tanto en entornos rurales como urbanos.

<br>

- **Misión:** Nuestra misión es empoderar a los agricultores y aficionados con herramientas tecnológicas avanzadas, ofreciéndoles una plataforma que combine monitoreo en tiempo real, inteligencia artificial, y educación continua para optimizar la producción agrícola y fomentar la innovación en el sector.



### 1.1.2. Perfiles de integrantes del equipo

<table align="center"  border="1" width="70%" style="text-align:center;">
    <tr align="center">
        <td rowspan="4">
            <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1280758357044625559/pic_1.jpg?ex=66d93eab&is=66d7ed2b&hm=4ad8b81bc567ac185862d08ae07857a5bf19cd009a0dcd36dc3de76d22d73786&" alt="Paolo Checa" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombres y Apellidos:</b>
            <br>            
            Checa Apolinario, Paolo Sebastián 
        </td>
    </tr>    
    <tr>
        <td align="left">
        <b>Código:</b>
        <br>
        U202112749
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Descripción de carrera</b>
        <br>
        En la Ingeniería de Software uno consigue los instrumentos necesarios para poder desarrollar programas o aplicaciones. El camino para lograr aquello se basa en un proceso donde el ingeniero deberá analizar lo requerido, planificar el desarrollo del proceso y comprobar su funcionamiento correcto hasta que este se ejecute sin errores. Las estrategias usadas para simplificar y acelerar estos procesos serán clave en esta rama pues estas serán las soluciones innovadoras que el ingeniero deberá crear. 
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Conocimiento y habilidades</b>
        <br>
        Poseo conocimientos en programación en el entorno del lenguaje C++, Python y Java. Estoy dispuesto a aportar nuevas ideas al equipo, tengo fácil adaptación a los roles designados y buena organización. Soy responsable y dispongo de la capacidad para aportar ideas innovadoras en beneficio de nuestro proyecto. 
        </td>
    </tr>
    <tr align="center">
        <td rowspan="4">
            <a href="https://postimg.cc/HJ2hzWN0">
    <img src="https://i.postimg.cc/85Qg1jBY/8c97179d-30c3-47b9-831b-c220e6ae57dd.jpg" alt="Moreno Vergara, Johan Raúl" style="margin-bottom: 5px;" width="800"/>
    </a>
        </td>
        <td align="left">
            <b>Nombres y Apellidos:</b>
            <br>            
            Moreno Vergara, Johan Raúl 
        </td>
    </tr>    
    <tr>
        <td align="left">
        <b>Código:</b>
        <br>
        U20201C105
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Descripción de carrera</b>
        <br>
        En la Ingeniería de Software uno consigue los instrumentos necesarios para poder desarrollar programas o aplicaciones. El camino para lograr aquello se basa en un proceso donde el ingeniero deberá analizar lo requerido, planificar el desarrollo del proceso y comprobar su funcionamiento correcto hasta que este se ejecute sin errores. Las estrategias usadas para simplificar y acelerar estos procesos serán clave en esta rama pues estas serán las soluciones innovadoras que el ingeniero deberá crear. 
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Conocimiento y habilidades</b>
        <br>
        Me especializo en el tema de ciberseguridad, donde he obtenido algunas certificaciones y he participado en un hackathon internacional en esta área. Actualmente trabajo en el área de Auditoría TI y Ciberseguridad. Además, tengo experiencia en programación en Python, Java y C++, y en el uso de frameworks como Angular, Vue.js y Spring Boot. También manejo bases de datos de tipo SQL. Me apasiona la seguridad de la información y busco siempre aportar soluciones innovadoras en proyectos que requieran robustez y protección avanzada. 
        </td>
    </tr>
    <tr align="center">
        <td rowspan="4">
            <img src="https://media.discordapp.net/attachments/1278210566904873047/1280956831396790272/1722901561737.jpg?ex=66d9f783&is=66d8a603&hm=32514db7cb939c3a2a83275e6fa5c6b9900789ef66f5442a2eb5eaf40ecdbbca&=&format=webp&width=473&height=473" alt="Onofre Ruiz, Carlos Jesus" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombres y Apellidos:</b>
            <br>            
            Onofre Ruiz, Carlos Jesus 
        </td>
    </tr>    
    <tr>
        <td align="left">
        <b>Código:</b>
        <br>
        U202115590
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Descripción de carrera</b>
        <br>
        En la Ingeniería de Software uno consigue los instrumentos necesarios para poder desarrollar programas o aplicaciones. El camino para lograr aquello se basa en un proceso donde el ingeniero deberá analizar lo requerido, planificar el desarrollo del proceso y comprobar su funcionamiento correcto hasta que este se ejecute sin errores. Las estrategias usadas para simplificar y acelerar estos procesos serán clave en esta rama pues estas serán las soluciones innovadoras que el ingeniero deberá crear. 
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Conocimiento y habilidades</b>
        <br>
        Tengo experiencia en desarrollo de software en frontend y backend, así como en desarrollo móvil. Manejo bases de datos como MySQL. Me motiva crear soluciones eficientes y creativas que mejoren la vida de las personas y optimicen procesos. A lo largo de mis estudios y proyectos personales, he demostrado habilidades en colaboración efectiva, pensamiento crítico y liderazgo. Mi firme compromiso con cada iniciativa ha sido clave para alcanzar objetivos y superar desafíos. Estoy emocionado de aplicar lo aprendido en un entorno profesional, contribuyendo al éxito de proyectos reales y enfrentando nuevos desafíos mientras sigo creciendo en el campo de la ingeniería de software. 
        </td>
    </tr>
    <tr align="center">
        <td rowspan="4">
            <img src=https://cdn.discordapp.com/attachments/1278210566904873047/1282134223146455151/perfil_linkeing.jpeg?ex=66de400b&is=66dcee8b&hm=0840c65c51c65b6529e8f1a09ada7df55738f839a30be0f20486d4815cca4599&"" alt="Wilfredo Futuri" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombres y Apellidos:</b>
            <br>            
            Futuri Illa, Wilfredo 
        </td>
    </tr>    
    <tr>
        <td align="left">
        <b>Código:</b>
        <br>
        u201924361
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Descripción de carrera</b>
        <br>
        En la Ingeniería de Software uno consigue los instrumentos necesarios para poder desarrollar programas o aplicaciones. El camino para lograr aquello se basa en un proceso donde el ingeniero deberá analizar lo requerido, planificar el desarrollo del proceso y comprobar su funcionamiento correcto hasta que este se ejecute sin errores. Las estrategias usadas para simplificar y acelerar estos procesos serán clave en esta rama pues estas serán las soluciones innovadoras que el ingeniero deberá crear. 
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Conocimiento y habilidades</b>
        <br>
        Tengo experiencia desarrollando aplicaciones frontend y backend. Los lenguajes de programación usados fueron Angular, Js, HTML y CSS para el frontend y Java 17 con Spring boot para el lado backend y base de datos Oracle y PostgreSQL. Actualmente estoy         
        desarrollando un proyecto fullstack para mi tesis aplicando las tecnologías mencionadas. Estoy interesado en mejorar mis habilidades técnicas sobre todo aplicando buenas prácticas de software para desarrollar productos de calidad.
        </td>
    </tr>
</table>

## 1.2. Solution Profile

**Nombre del Producto:** 
Nuestro servicio se denomina “AgroTech” ya que hacemos referencia al crecimiento tanto de los cultivos que nuestros usuarios utilizarán en sus proyectos caseros, como al desarrollo personal que experimentarán al adquirir nuevos conocimientos y perfeccionar sus habilidades en el ámbito agrícola junto a nosotros.<br>

**Descripción del Producto:**
Ofrecemos un servicio innovador que permite a los usuarios gestionar y optimizar sus cultivos de manera sencilla y eficiente utilizando tecnología avanzada. A través de nuestra plataforma, los usuarios pueden monitorizar en tiempo real las condiciones de sus cultivos mediante dispositivos IoT, recibiendo datos sobre variables clave como humedad, luz y temperatura. Además, nuestra aplicación incluye un chatbot inteligente que responde a preguntas y proporciona recomendaciones personalizadas, facilitando el manejo de los cultivos desde un nivel básico hasta un nivel experto. El problema que resolveremos es la optimización de la producción de cultivos, ayudando a los usuarios a maximizar su rendimiento mediante el uso de tecnología, mejorando la eficiencia y el monitoreo de sus proyectos agrícolas.<br>

**Monetización:**
Nuestro servicio generará ingresos mediante la venta y suscripción a dispositivos IoT, que permitirán a los usuarios monitorizar y mejorar sus cultivos. Además, nuestros servicios funcionan de manera continua durante todo el día para garantizar que los usuarios puedan monitorear y continuar sus proyectos en cualquier momento. Esta combinación de productos y servicios garantiza un flujo constante de ingresos, al mismo tiempo que proporciona un valor añadido a nuestros usuarios.


### 1.2.1. Antecedentes y problemática

Para este segmento, haremos uso de la técnica 5W y 2H, que nos permitirá identificar los aspectos más importantes con respecto a nuestro proyecto.

- **Who**

Nuestros usuarios son agricultores, tanto principiantes como expertos, que buscan utilizar tecnología avanzada para mejorar sus prácticas agrícolas, ya sea en entornos urbanos o rurales.

- **What**

El principal reto que enfrentan nuestros usuarios es la dificultad para monitorear y optimizar las condiciones de sus cultivos en tiempo real, lo que puede llevar a una disminución en la eficiencia y en la producción agrícola.

- **Where**

Este problema es común en diversas regiones, especialmente en aquellas donde los agricultores no tienen acceso a tecnologías avanzadas o a información precisa para la gestión de sus cultivos.

- **When**

La problemática se presenta cada vez que los usuarios intentan manejar sus cultivos sin el apoyo de datos en tiempo real, lo que resulta en decisiones menos informadas y potencialmente menos efectivas.

- **Why**

Los usuarios suelen enfrentar desafíos al no contar con herramientas que les permitan monitorear las condiciones de sus cultivos de manera continua y precisa, lo que puede resultar en un manejo poco óptimo de los recursos y en la disminución de la productividad.

- **How**

Para solucionar este problema, hemos desarrollado una aplicación en la que se mostrará un dashboard que se conecta a dispositivos IoT, permitiendo a los usuarios monitorizar en tiempo real variables críticas como humedad y luz, y tomar decisiones basadas en datos precisos. Además, un chatbot con inteligencia artificial está disponible para responder preguntas y proporcionar recomendaciones.

- **How much**

La inversión inicial en dispositivos IoT es una consideración importante para los usuarios, sin embargo, los beneficios de una gestión más precisa y optimizada de los cultivos pueden compensar esta inversión a largo plazo mediante un aumento en la eficiencia y productividad.

<br>

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

El monitoreo en tiempo real mediante sensores IoT y la toma de decisiones basada en datos pueden reducir significativamente el desperdicio de recursos y mejorar los rendimientos. Sin embargo, muchos agricultores y aficionados encuentran desafíos al intentar integrar estas tecnologías en sus prácticas diarias debido a la falta de acceso a herramientas adecuadas y a la información técnica necesaria. La carencia de una plataforma centralizada que ofrezca tanto monitoreo en tiempo real como soporte educativo personalizado puede resultar en una curva de aprendizaje prolongada y en decisiones menos eficaces.

Por lo tanto, como startup, nuestro objetivo es abordar la siguiente cuestión: ¿Cómo podemos aplicar nuestro conocimiento en tecnología IoT y en inteligencia artificial para desarrollar un servicio innovador que proporcione a los agricultores los datos en tiempo real necesarios para optimizar sus cultivos?

#### 1.2.2.2. Lean UX Assumptions

**Business outcomes:**

- Los usuarios están interesados en utilizar tecnología avanzada, como dispositivos IoT, para mejorar la eficiencia de sus cultivos.
- Los usuarios desean acceder a datos en tiempo real sobre sus cultivos para tomar decisiones informadas.
- Los usuarios buscan una interfaz intuitiva y fácil de usar para monitorizar y analizar las condiciones de sus cultivos.
- Los usuarios necesitan poder visualizar y entender los datos de manera clara y precisa para - optimizar sus prácticas agrícolas.
- La aplicación debe ser compatible y funcionar correctamente en los navegadores y dispositivos actuales.

**User assumptions:**

**¿Quién es el usuario?**
Los usuarios interesados en nuestro servicio son agricultores, tanto principiantes como expertos, que buscan utilizar tecnología IoT para optimizar sus cultivos. Estos usuarios incluyen a personas que desean mejorar la eficiencia de su producción agrícola y a aquellos que buscan adoptar prácticas más sostenibles.

**¿Dónde encaja nuestro producto en su vida o trabajo?**
Nuestra aplicación se integra en la rutina diaria de los agricultores, permitiéndoles monitorear y gestionar sus cultivos de manera continua. Puede comenzar como una herramienta de apoyo y evolucionar hacia una parte esencial de su proceso de cultivo.

**¿Qué problema aborda nuestro producto? ¿Cómo se soluciona?**
El producto aborda la dificultad para monitorizar y gestionar eficientemente los cultivos en tiempo real. Lo resolvemos proporcionando una plataforma que conecta sensores IoT con un dashboard que permite a los usuarios ver y analizar datos críticos como humedad y luz. Además, ofrecemos un chatbot inteligente que proporciona recomendaciones y resuelve dudas.

**¿Cuándo y cómo se utiliza nuestro producto?**
Nuestro producto está diseñado para ser utilizado de forma continua a lo largo del ciclo de cultivo, permitiendo a los usuarios acceder a datos en tiempo real en cualquier momento. Los usuarios pueden utilizar el dashboard para ajustar las condiciones de sus cultivos y el chatbot para recibir asistencia inmediata.

**¿Qué características son importantes?**
Las características clave incluyen la capacidad de monitorizar variables críticas en tiempo real, la integración con dispositivos IoT, y el acceso a un chatbot inteligente para soporte y recomendaciones.

**¿Cómo debe verse y comportarse nuestro producto?**
Es esencial que nuestro producto sea fácil de usar, con una interfaz intuitiva que permita a los usuarios acceder rápidamente a los datos y análisis que necesitan. Debe ser confiable, eficiente y proporcionar una experiencia de usuario sin interrupciones.


#### 1.2.2.3. Lean UX Hypothesis Statements

En esta sección, se presentarán hipótesis que ofrecen soluciones a las problemáticas mencionadas anteriormente dentro de nuestra aplicación. Estas hipótesis serán específicas y estarán acompañadas de métricas que permitirán evaluar el éxito de manera objetiva. Las métricas empleadas se basan en promedios generales de aplicaciones existentes.

- ​​Creemos que nuestra aplicación será una herramienta valiosa para los agricultores que buscan mejorar la eficiencia de sus cultivos mediante tecnología IoT. Sabremos que hemos tenido éxito cuando más del 75% de las reseñas de los usuarios sean positivas.<br>
    **Métricas:**
    1. Número de reseñas mensuales
        - Métrica actual: 25
        - Métrica deseada: 55
    2. Calificación promedio de los cursos
        - Métrica actual: 3.5
        - Métrica deseada: 4.9

<br>

- Creemos que la integración de dispositivos IoT para el monitoreo en tiempo real será crucial para la optimización de los cultivos. Sabremos que hemos tenido éxito cuando más del 80% de los usuarios utilicen esta función regularmente.<br>
    ​**​Métricas:**
    1. Satisfacción con el chatbot
        - Métrica actual: 70%
        - Métrica deseada: 90%
    2. Número de interacciones con el chatbot
        - Métrica actual: 50 por mes
        - Métrica deseada: 150 por mes

<br>

- Creemos que nuestro chatbot impulsado por IA será un recurso clave para resolver dudas y ofrecer recomendaciones en tiempo real. Sabremos que hemos tenido éxito cuando más del 85% de los usuarios reporten que el chatbot ha sido útil.<br>
    **Métricas:**
    1. Promedio de edad de los usuarios
        - Métrica actual: 25
        - Métrica deseada: 23

<br>

- Creemos que nuestra aplicación será intuitiva y fácil de usar, permitiendo a los usuarios navegar y acceder a la información que necesitan sin complicaciones. Sabremos que hemos tenido éxito cuando más del 90% de los usuarios expresen su satisfacción en las encuestas.<br>
    **Métricas:**
    1. Usuarios satisfechos por mes
        - Métrica actual: 60
        - Métrica deseada: 200
    2. Nuevos usuarios por mes
        - Métrica actual: 30
        - Métrica deseada: 75

#### 1.2.2.4. Lean UX Canvas

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1279277386499883098/Lean_UX_Canvas_Template_3.jpg?ex=66d9ca28&is=66d878a8&hm=2e962e582f8c550629c765677c3fb25f0e8fdf612471ff5a012b40c581cdb34c&"/>
</div>

## 1.3. Segmentos objetivos

| Tipo de Usuario | Principiantes en la agricultura | Expertos en la agricultura |
| :-------------: | :------------------------------: | :-------------------------: |
| Geográfico | País: Perú <br> Zona residencial: No es relevante, ya que pueden ser de diferentes zonas del país. | País: Perú <br> Zona residencial: No es relevante, ya que pueden ser de diferentes zonas del país. |
| Psicográfico | Clase Social: Principalmente de clase media a clase media alta, interesados en aprovechar tecnologías accesibles para mejorar sus cultivos. <br> Estilo de Vida: Personas interesadas en la agricultura y sostenibilidad, que buscan aprender a utilizar tecnologías IoT para mejorar sus cultivos, pero carecen del conocimiento técnico necesario para comenzar por su cuenta. | Clase Social: Desde clase media hasta clase alta, con recursos para invertir en tecnologías avanzadas. <br> Estilo de Vida: Agricultores con experiencia que buscan optimizar sus procesos de cultivo mediante herramientas IoT. |
| Demográfico | Edad: Personas mayores de 18 años. <br> Nivel de Ingreso: Varía según la capacidad de inversión en tecnologías IoT, desde ingresos medios a altos. <br> Nacionalidad: Principalmente peruanos; extranjeros pueden acceder al servicio con identificación válida, como pasaporte. | Edad: Preferiblemente mayores de 30 años. <br> Nivel de Ingreso: Ingresos medios a altos, con capacidad para invertir en tecnología avanzada. <br> Nacionalidad: Principalmente peruanos; extranjeros deben identificarse con pasaporte. <br> Estudios: Secundaria completa o estudios superiores, idealmente con formación en agricultura o tecnología.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

Después de realizar un análisis en el mercado peruano, hemos identificado tres proyectos similares a AgroTech que consideramos como posibles competidores. Estos son:

* **Hidroponika:** 

Es una plataforma en línea que ofrece una amplia gama de productos y servicios de calidad relacionados con la hidroponía. Proporciona soluciones nutritivas para una variedad de plantas, así como recursos y herramientas para el establecimiento y mantenimiento de huertos hidropónicos en el hogar. Además, ofrece asesoramiento personalizado y una comunidad activa para entusiastas de la hidrocultura.

* **Intagri:**

Es un portal que brinda información detallada sobre diversos cultivos agrícolas, así como conferencias y cursos dirigidos por expertos en el campo de la agricultura. Su enfoque se centra en la educación y el asesoramiento para agricultores de todos los niveles de experiencia, proporcionando recursos prácticos y actualizados sobre técnicas de cultivo y gestión agrícola.

* **Mundo Hidroponía:**

Es una plataforma en línea que ofrece una amplia variedad de productos para la hidroponía, incluyendo nutrientes, sistemas de cultivo, semillas y más. Además de su tienda en línea, proporcionan servicios de envío para sus productos y recursos educativos para ayudar a los usuarios a comenzar y mantener sus propios proyectos de hidroponía en casa.
  

### 2.1.1. Análisis competitivo

<table>
   <tr>
        <th colspan="6" style="text-align: center;">Competitive Analysis Landscape</th>
    </tr>
    <tr>
        <td colspan="2">¿Por qué llevar a cabo este análisis?</td>
        <td colspan="4" style="text-align: left;">Este análisis tiene como objetivo identificar a nuestros competidores potenciales y desarrollar estrategias para diferenciarnos en el mercado.</td>
    </tr>
    <tr>
        <th colspan="2">Nuestro Producto / Competidores</th>
        <td>AgroTech</td>
        <td>Hidroponika</td>
        <td>Intagri</td>
        <td>Mundo hidroponía</td>
    </tr>
    <tr>
        <th rowspan="2">Perfil</th>
        <td colspan="1">Overview
        </td>
        <td>Plataforma web que ofrece información sobre hidroponía, actualización diaria sobre temas relacionados y cursos interactivos para aprender técnicas y materiales.	</td>
        <td>Página web con una amplia gama de productos y servicios de calidad relacionados con la hidroponía, además de cursos introductorios.	</td>
        <td>Portal web que ofrece información detallada sobre agricultura, incluyendo cursos y capacitaciones presenciales y virtuales.	</td>
        <td>Plataforma en línea que ofrece una variedad de productos para la hidroponía, desde nutrientes hasta huertos prefabricados.
</td>
    </tr>
    <tr>
        <td colspan="1">Ventaja Competitiva</td>
        <td>Diversificación de productos adaptados a diferentes presupuestos y regiones de Perú, además de un servicio al cliente personalizado.	</td>
        <td>Amplia variedad de productos, packs y soluciones para la hidroponía, con una interfaz sólida que destaca los beneficios de sus servicios.	</td>
        <td>Destaca por su extenso catálogo de cursos sobre agricultura, atrayendo a diversos usuarios interesados en aprender.	</td>
        <td>Ofrece una amplia gama de semillas, nutrientes y huertos hidropónicos, convirtiéndose en un destino popular para los entusiastas de la hidroponía.
</td>
    </tr>
    <tr>
        <th rowspan="2">Perfil de Marketing</th>
        <td colspan="1">Mercado Objetivo
        </td>
        <td>Personas interesadas en iniciarse en la hidroponía o mejorar sus cultivos en hogares o espacios alternativos en Perú.	</td>
        <td>Público en general interesado en iniciarse en la hidroponía o mejorar sus conocimientos y suministros para cultivos en Perú.	</td>
        <td>Individuos interesados en profundizar en temas agrícolas, dispuestos a asistir a cursos presenciales o virtuales.	</td>
        <td>Usuarios dedicados a la hidroponía en busca de suministros y productos de calidad.
</td>
    </tr>
    <tr>
        <td colspan="1">Estrategias de Marketing</td>
        <td>Uso de redes sociales para publicidad y promoción.	</td>
        <td>Publicidad en redes sociales y colaboraciones con empresas aliadas para alcanzar un mayor público.	</td>
        <td>Publicidad en redes sociales y participación en eventos agrícolas para promover sus cursos.	</td>
        <td>Campañas publicitarias en redes sociales y participación en ferias de jardinería para atraer clientes.
</td>
    </tr>
    <tr>
        <th rowspan="3">Perfil de Producto</th>
        <td colspan="1">Productos & Servicios
        </td>
        <td>Información detallada sobre hidroponía, cursos interactivos y comunidades para compartir experiencias.	</td>
        <td>Amplio catálogo de productos, desde nutrientes hasta huertos hidropónicos de diferentes tamaños y para diversas plantas.	</td>
        <td>Cursos y capacitaciones presenciales y virtuales sobre agricultura y métodos de cultivo.	</td>
        <td>Variedad de productos para hidroponía, incluyendo semillas, nutrientes y huertos prefabricados.
</td>
    </tr>
    <tr>
        <td colspan="1">Precios y Costos</td>
        <td>Precios accesibles para cursos, mostrados en la pantalla de compra.	</td>
        <td>Variedad de precios para productos, desde soluciones económicas hasta huertos más costosos.	</td>
        <td>Costos variables según el tipo de curso, desde cursos básicos hasta diplomados internacionales.	</td>
        <td>Precios variados para productos, dependiendo de la calidad y tamaño del huerto.
</td>
    </tr>
    <tr>
        <td colspan="1">Canales de Dsitribución</td>
        <td>Página web con envíos a todo el Perú a través de distribuidores de courier.</td>
        <td>Ventas en línea con envíos a todo Perú mediante empresas de courier.</td>
        <td>Distribución de cursos presenciales y virtuales, así como venta de productsos a través e la web.</td>
        <td>Ventas en línea con envío nacional de Hidroponía.</td>
    </tr>
    <tr>
        <th rowspan="4">Análisis SWOT</th>
        <td colspan="1">Fortaleza
        </td>
        <td>Validación de información por especialistas y comunicación continua con clientes.	</td>
        <td>Amplia oferta de productos y cursos, así como variedad en capacitaciones presenciales.	</td>
        <td>Reconocimiento por la oferta de una amplia variedad de cursos y capacitaciones, así como prestigio por eventos presenciales.</td>
        <td>Variedad de productos y servicios que satisfacen las necesidades de los clientes en hidroponía.
    </td>
    </tr>
    <tr>
        <td colspan="1">Debilidades</td>
        <td>Falta de reconocimiento como startup nueva y posible demora en la comunicación con clientes.</td>
        <td>Dificultad para enfocarse en temas específicos debido al amplio catálogo de cursos.	</td>
        <td>Posible dificultad para asesorar a clientes sobre productos más adecuados para sus necesidades específicas.	</td>
        <td>Dependencia del mercado en línea y posibles limitaciones logísticas en envíos.
    </td>
    </tr>
    <tr>
        <td colspan="1">Oportunidades</td>
        <td>Ausencia de información especializada en hidroponía, así como carencia de plataformas de alcance nacional.</td>
        <td>Mercado en crecimiento y demanda creciente de productos y cursos relacionados con la hidroponía.</td>
        <td>Interés creciente en temas agrícolas y disponibilidad de participación en eventos presenciales.	</td>
        <td>Creciente interés en la hidroponía y disponibilidad de compras en línea en el mercado peruano.
    </td>
    </tr>
    <tr>
        <td colspan="1">Amenazas</td>
        <td>Desconfianza inicial por ser una nueva empresa y posibles dificultades económicas en el arranque.	</td>
        <td>Limitaciones en comunicación directa con clientes y posibles restricciones presupuestarias de algunos usuarios.	</td>
        <td>Competencia en oferta de cursos presenciales y limitaciones logísticas para algunos usuarios.	</td>
        <td>Competencia en línea y posibles fluctuaciones en el mercado de productos para hidroponía.
    </td>
    </tr>
</table>



### 2.1.2. Estrategias y tácticas frente a competidores

Debido a la amplia gama de opciones disponibles para los usuarios en busca de soluciones relacionadas con la hidroponía y con el fin de mantenernos competitivos en el mercado, hemos desarrollado las siguientes estrategias y tácticas:

* **Liderazgo en costes:**

Nos distinguiremos al ofrecer nuestro producto de manera gratuita, sin restricciones en sus funcionalidades principales. Además, brindaremos una variedad de cursos a precios asequibles, asegurando su accesibilidad para todos los usuarios. Nuestro enfoque principal será satisfacer a quienes buscan información e investigación sobre hidroponía.

* **Estrategia de diferenciación:**

Para sobresalir frente a la competencia, implementaremos características únicas y mejoradas en nuestra plataforma, que no se encuentran en otras aplicaciones. Esto incluirá un extenso catálogo de temas, opiniones y estudios avalados por especialistas en el campo. Asimismo, ofreceremos una amplia gama de cursos en línea impartidos por expertos, consolidando nuestra plataforma como una fuente confiable de información.

* **Estrategia de enfoque:**

Reconociendo la creciente demanda de servicios de gestión agrícola impulsada por el aumento del uso de tecnología, nos centraremos en proporcionar una plataforma web accesible desde dispositivos móviles y computadoras, permitiendo a los usuarios investigar y aprender sobre hidroponía desde la comodidad de sus hogares.

* **Táctica de expansión:**

Aunque nuestra aplicación se ofrece de forma gratuita, evitaremos la sobrecarga de anuncios para no comprometer la experiencia del usuario. En su lugar, planeamos expandir nuestra base de usuarios a través de calificaciones positivas y publicidad estratégica.


### 2.2.2. Registro de entrevistas

**Segmento 1: Principiantes en la agricultura**

**Entrevista 1:**

- Apellidos y nombre: Miguel Ybañez
- Edad: 21 años
- Ubicación: Lima
- Evidencia de la reunión:

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282161502396088361/image.png?ex=66de5973&is=66dd07f3&hm=7967c792f7c53feeed8e42f7e1509dce57fb09eb18a6b043c36e10e2e11cd467&"/>
</div>

- Inicio: 00:06
- Fin: 03:18
- Enlace de Entrevista: [Entrevistas - Needfinding](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EcJtHnth9C9Ls3Sq7QScadwBZdwewvvmoD5FX3d7AU5q7g?e=kTKEyC&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
- Resumen de la entrevista: Miguel Ybañez mostró un gran interés en la agricultura sostenible y en aprender a cultivar sus propios alimentos, lo que está alineado con los objetivos de nuestro proyecto, que busca facilitar la gestión agrícola mediante tecnología IoT y un chatbot. Aunque no ha utilizado IoT por desconocimiento y costos, ve la propuesta como una solución viable para superar estos retos. Identificó la falta de experiencia en monitoreo de cultivos como un desafío, destacando que un sistema que proporcione alertas y recomendaciones en tiempo real mejoraría la salud de sus plantas. Además, considera valiosa la interacción con una comunidad de agricultores para compartir experiencias y aprender. Las funcionalidades clave que resaltó como necesarias son las alertas automáticas, un dashboard sencillo, recomendaciones personalizadas y un chatbot que coinciden perfectamente con los pilares de nuestro proyecto, validando su enfoque y utilidad para usuarios principiantes.
<br>

**Entrevista 2:**

- Apellidos y nombre: Angel Luis Ramos Orosco
- Edad: 25 años
- Ubicación: Miraflores
- Evidencia de la reunión:

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282162253533020202/image.png?ex=66de5a26&is=66dd08a6&hm=21cebf972b0b45c0d2308ec4ccb05eced858edd5b7f809ec77315edc43e5d6f5&"/>
</div>

- Inicio: 03:19
- Fin: 08:02 
- Enlace de Entrevista: [Entrevistas - Needfinding](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EcJtHnth9C9Ls3Sq7QScadwBZdwewvvmoD5FX3d7AU5q7g?e=kTKEyC&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
- Resumen de la entrevista: Angel ha iniciado sus actividades en un terreno agrícola y, aunque aún es nuevo en este ámbito, se encuentra motivado para expandir sus conocimientos. Al abordar el tema de la tecnología IoT, indicó que, si bien no ha implementado esta tecnología, le resulta interesante explorar su aplicación en la agricultura. Considera que nuestro proyecto podría representar una solución adecuada para sus necesidades. Además, manifestó su interés en contar con un chatbot que le permita consultar directamente sus dudas con expertos en el área.
<br>

**Entrevista 3:**

- Apellidos y nombre: Jorge Enrique Gonzales Carrión
- Edad: 22 años
- Ubicación: Ahuac, Junín
- Evidencia de la reunión:

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282082982873534524/image.png?ex=66de1053&is=66dcbed3&hm=712b041d776745079707aa954f50cf1d41243017e707556c00082bc2aa53551c&"/>
</div>

- Inicio: 08:03
- Fin: 13:19
- Enlace de Entrevista: [Entrevistas - Needfinding](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EcJtHnth9C9Ls3Sq7QScadwBZdwewvvmoD5FX3d7AU5q7g?e=kTKEyC&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
- Resumen de la entrevista: Nuestro entrevistado fue Jorge Gonzales, un joven universitario que ayuda a su familia en las labores de agricultura en sus tiempos libres. Mencionó que iniciaría un proyecto personal porque está relacionado con su carrera, la cual es Ingeniería Ambiental, además se le facilitaría ya que su familia cuenta con el terreno necesario. Comentó que tiene conocimiento sobre algunas herramientas IOT, como aspersores inteligentes. Considera que tener una herramienta que le permita visualizar los datos de los cultivos en tiempo real le sería de mucha utilidad, y de esa manera poder mejorar la producción de la cosecha.
<br><br>

**Segmento 2: Expertos en la agricultura**

**Entrevista 1:**

- Apellidos y nombre: Luis Atmed Ramos Rios
- Edad: 30 años
- Ubicación: Piura
- Evidencia de la reunión:

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282163388314550344/image.png?ex=66de5b35&is=66dd09b5&hm=a6972f50ae63ea739278f786c296130633548378c549034bf99a7bd12f2d9978&"/>
</div>

- Inicio: 13:23
- Fin: 23:04
- Enlace de Entrevista: [Entrevistas - Needfinding](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EcJtHnth9C9Ls3Sq7QScadwBZdwewvvmoD5FX3d7AU5q7g?e=kTKEyC&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
- Resumen de la entrevista: Luis, quien cultiva uvas en Piura y se dedica a la producción de vino en el marco de un negocio familiar, nos ha compartido que su proceso de cultivo sigue un enfoque tradicional, sin la implementación de maquinaria avanzada o tecnología IoT. Actualmente, solo disponen de un sistema para gestionar sus gastos. Sin embargo, nuestra propuesta le resultó sumamente atractiva, pues está consciente del crecimiento de la tecnología y su potencial para aumentar la eficiencia. Luis, debido a sus frecuentes viajes por razones de venta, está particularmente interesado en automatizar sus procesos de cultivo y contar con la capacidad de monitorear todo en tiempo real. Considera fundamental poder acceder a información sobre la humedad, temperatura y condiciones climáticas, lo cual contribuiría significativamente al éxito de su cosecha de uvas.
<br>

**Entrevista 2:**

- Apellidos y nombre: Marjorie Huamani Atuncar
- Edad: 25 años
- Ubicación: Nazca
- Evidencia de la reunión:

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282134223460892752/image.png?ex=66de400b&is=66dcee8b&hm=ae48120833517067e3a6a238fc71261de7446c7ac3c49a24f6c18f4372a306c4&"/>
</div>

- Inicio: 23:06
- Fin: 29:15
- Enlace de Entrevista: [Entrevistas - Needfinding](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EcJtHnth9C9Ls3Sq7QScadwBZdwewvvmoD5FX3d7AU5q7g?e=kTKEyC&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
- Resumen de la entrevista: Maryorie Huamani, junto con su familia, gestiona un fundo de 10 hectáreas en Nazca donde cultivan palta y arándanos. Han intentado integrar tecnología IoT para mejorar la gestión de sus cultivos, pero han encontrado varios desafíos. La implementación resultó ser complicada debido a la complejidad tecnológica y los altos costos, y no encontraron soluciones que se ajustaran a su presupuesto. Actualmente, gestionan sus cultivos de manera tradicional y buscan soluciones más accesibles y fáciles de usar que les permitan beneficiarse de los datos en tiempo real. La necesidad de una aplicación con monitoreo eficaz y soporte técnico, así como una comunidad agrícola activa, es fundamental para mejorar la gestión y eficiencia de sus prácticas agrícolas.
<br>

**Entrevista 3:**

- Apellidos y nombre: Paolo Laguerre
- Edad: 28 años
- Ubicación: Ate, Lima
- Evidencia de la reunión:

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282095795763675251/image.png?ex=66de1c41&is=66dccac1&hm=f1872e7b5d2da1bb053bd35126cd7f0cb3f129b5021660d165f7de9c568ed7b0&"/>
</div>

- Inicio: 29:15
- Fin: 32:41
- Enlace de Entrevista: [Entrevistas - Needfinding](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EcJtHnth9C9Ls3Sq7QScadwBZdwewvvmoD5FX3d7AU5q7g?e=kTKEyC&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
- Resumen de la entrevista: Nuestro entrevistado fue Paolo Laguerre, agricultor experto con varios años en el sector. Hace uso de tecnología IOT en sus cultivos, y mencionó que al principio fue complejo usar estas herramientas, pero con la práctica se volvió más manejable. Mencionó que uno de los principales desafíos para el cultivo es la falta de infraestructura, además la falta de capacitación para los iniciantes. Comentó que le sería de ayuda tener una herramienta que le permita tener los datos en tiempo real de sus cultivos, para poder reaccionar rápidamente en los distintos escenarios posibles. Le facilitaría que la interfaz sea sencilla y fácil de manejar para los usuarios.
<br>

### 2.2.3. Análisis de entrevistas

Las entrevistas realizadas revelan una clara demanda de soluciones tecnológicas accesibles y fáciles de usar en la agricultura, tanto por parte de principiantes como de expertos. Los principiantes, como Miguel, Ángel y Jorge, destacan su interés en tecnologías como IoT y la posibilidad de recibir alertas y recomendaciones en tiempo real, además de valorizar herramientas como chatbots para mejorar su aprendizaje. Sin embargo, su falta de experiencia y el desconocimiento de estas tecnologías representan desafíos importantes. Por otro lado, los expertos, como Luis, Maryorie y Paolo, reconocen el potencial de la tecnología IoT para optimizar sus cultivos, pero subrayan las dificultades en su implementación debido a costos, falta de infraestructura y capacitación. En general, tanto principiantes como expertos coinciden en la necesidad de herramientas intuitivas y económicas que permitan monitorear y automatizar sus procesos agrícolas, lo que valida el enfoque del proyecto hacia la inclusión tecnológica y la eficiencia en la gestión agrícola.

## 2.3. Needfinding

### 2.3.1. User Personas

El proyecto "AgroTech Innovators" depende en gran medida de la correcta identificación de las User Personas, ya que estas permiten una comprensión profunda y específica de las necesidades, deseos, frustraciones y comportamientos clave de los usuarios. Estos perfiles detallados permiten diseñar una plataforma altamente personalizada y enfocada en brindar soluciones efectivas a los diferentes segmentos objetivos: desde proporcionar herramientas claras y accesibles para principiantes en la agricultura, hasta ofrecer funcionalidades avanzadas para expertos que desean optimizar y compartir su conocimiento.

**User persona del segmento: Principiantes en agricultura**

[![User-Persona-Principiantes.jpg](https://i.postimg.cc/xqr0htpX/Edit-org-design-07-09-19-28-1.jpg)](https://postimg.cc/ctmy8MSW)


**User persona del segmento: Expertos en agricultura**

[![User-Persona-Expertos.jpg](https://i.postimg.cc/3rk2MNbh/User-Persona-Expertos.jpg)](https://postimg.cc/XX0rdjb1)

### 2.3.2. User Task Matrix

En esta Matriz de Tareas de Usuario, se detallan las tareas típicas realizadas por los dos segmentos de usuarios: principiantes interesados en mejorar sus cultivos mediante la agricultura sostenible y expertos que buscan optimizar sus procesos agrícolas utilizando tecnología IoT. Se evalúa la frecuencia y la severidad de cada tarea, lo que ayuda a priorizar y comprender las áreas clave en las que el producto AgroTech podría intervenir para satisfacer las necesidades y objetivos de ambos segmentos.

**User Task Matrix para Principiantes en Agricultura**

<table border="1">
  <tr>
    <th style-text:center>Tarea</th>
    <th>Frecuencia</th>
    <th>Severidad</th>
  </tr>
  <tr>
    <td>Investigar sobre técnicas agrícolas y cultivos</td>
    <td>Casi Siempre</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Buscar recursos en línea sobre el manejo de cultivos</td>
    <td>Casi Siempre</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Consultar con amigos o expertos en agricultura</td>
    <td>A veces</td>
    <td>Baja</td>
  </tr>
  <tr>
    <td>Adquirir suministros y equipos agrícolas</td>
    <td>A veces</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Monitorear la humedad y temperatura del suelo</td>
    <td>Casi Siempre</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Ajustar el riego manualmente</td>
    <td>Casi Siempre</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Solucionar problemas (plagas, nutrientes, etc.)</td>
    <td>A veces</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Participar en una comunidad de aprendizaje</td>
    <td>A veces</td>
    <td>Baja</td>
  </tr>
  <tr>
    <td>Consultar al chatbot sobre preguntas básicas</td>
    <td>A veces</td>
    <td>Baja</td>
  </tr>
  <tr>
    <td>Evaluar el éxito de los cultivos</td>
    <td>Casi Siempre</td>
    <td>Media</td>
  </tr>
</table>

**User Task Matrix para Expertos en Agricultura**

<table border="1">
  <tr>
    <th>Tarea</th>
    <th>Frecuencia</th>
    <th>Severidad</th>
  </tr>
  <tr>
    <td>Monitorear cultivos a través de dispositivos IoT</td>
    <td>Casi Siempre</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Analizar los datos de temperatura y humedad</td>
    <td>A veces</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Ajustar configuraciones del sistema de riego automático</td>
    <td>A veces</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Implementar estrategias de cultivo basadas en datos</td>
    <td>Casi Siempre</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Consultar al chatbot sobre preguntas avanzadas</td>
    <td>A veces</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Gestionar varios cultivos y su monitoreo en paralelo</td>
    <td>Casi Siempre</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Optimizar recursos (agua, fertilizantes) mediante datos</td>
    <td>Casi Siempre</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Evaluar la producción agrícola en base a métricas históricas</td>
    <td>Casi Siempre</td>
    <td>Alta</td>
  </tr>
</table>

### 2.3.3. Empathy Mapping

El Empathy Mapping es una herramienta clave para nuestro proyecto AgroTech, ayudándonos a comprender profundamente las percepciones y experiencias tanto de principiantes como de expertos en la agricultura. Captura las necesidades, deseos, frustraciones y motivaciones de nuestros usuarios, proporcionando una visión clara sobre cómo diseñar soluciones tecnológicas efectivas y centradas en ellos.

**Empathy Map para Principiantes en Agricultura**

[![Empathy-Map-Principiantes.png](https://i.postimg.cc/8kxMTGq6/Empathy-Map-Principiantes.png)](https://postimg.cc/xqycPwjf)

**Empathy Map para Expertos en Agricultura**

[![Empathy-Map-Expertos.png](https://i.postimg.cc/DyssZDTY/Empathy-Map-Expertos.png)](https://postimg.cc/fJzkq8kx)

### 2.3.4. As-is Scenario Mapping

En el As-is Scenario Mapping de nuestro proyecto AgroTech, analizamos cómo interactúan actualmente los usuarios, tanto principiantes como expertos en agricultura, con sus sistemas de gestión de cultivos. Este análisis nos permite identificar puntos de fricción y áreas donde nuestra solución puede agregar valor. Al comprender los desafíos actuales, como la falta de monitoreo en tiempo real o la necesidad de optimizar recursos, podemos diseñar un sistema más eficiente que se ajuste a las necesidades reales de los usuarios. Esto nos guiará en la creación de una plataforma que automatice procesos y facilite la toma de decisiones en el campo agrícola.

**Segmento 1: Principiantes en agricultura**

[![As-Is-Scenario-Mapping-Principiantes.png](https://i.postimg.cc/P5JjKG5S/As-Is-Scenario-Mapping-Principiantes.png)](https://postimg.cc/JGfv42JX)

**Segmento 2: Expertos en agricultura**

[![As-Is-Scenario-Mapping-Experto.png](https://i.postimg.cc/sgLRNnBs/As-Is-Scenario-Mapping-Experto.png)](https://postimg.cc/k2WZVvFp)

## 2.4. Ubiquitous Language

En el Ubiquitous Language de AgroTech, definimos los términos clave del dominio agrícola para garantizar una comunicación clara y evitar malentendidos, facilitando el desarrollo y la alineación del equipo en cada etapa del proyecto.

**1. Crop Monitoring (Monitoreo de Cultivos):**
Sistema que permite observar y analizar en tiempo real el estado de los cultivos, utilizando datos como la humedad, temperatura y luz a través de sensores IoT.

**2. Smart Irrigation (Riego Inteligente):**
Sistema automatizado que ajusta el riego de los cultivos en función de datos en tiempo real, optimizando el uso de agua según las necesidades del suelo.

**3. IoT Devices (Dispositivos IoT):**
Sensores conectados que recopilan y transmiten datos sobre el estado de los cultivos y el entorno, permitiendo un monitoreo constante y en tiempo real.

**4. Real-Time Alerts (Alertas en Tiempo Real):**
Notificaciones automáticas enviadas al agricultor cuando se detectan condiciones críticas en el cultivo, como humedad baja o presencia de plagas.

**5. Yield Optimization (Optimización del Rendimiento):**
Estrategias para mejorar la producción de los cultivos mediante el uso eficiente de recursos y datos provenientes de dispositivos IoT.

**6. Fertilization Recommendations (Recomendaciones de Fertilización):**
Sugerencias generadas por el sistema para indicar cuándo y cuánto fertilizante aplicar para maximizar el crecimiento y la salud de los cultivos.

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

Es esencial visualizar cómo serán las operaciones y las experiencias de los usuarios en el futuro deseado. En este contexto, presentamos el segmento de To-Be Scenario Map, que representa la visión optimizada y mejorada de nuestro proceso actual. Esta herramienta nos guiará hacia un futuro donde nuestras operaciones sean más eficientes, nuestras experiencias de usuario sean más satisfactorias y nuestro impacto en el mercado sea aún más significativo. A través de esta visualización del estado futuro deseado, delineamos los pasos clave, las interacciones y los resultados esperados que nos llevarán a alcanzar nuestras metas y superar las expectativas de nuestros usuarios y partes interesadas.

####  Segmento 1: Principiantes en la agricultura
<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282134223800635465/To-Be_Scenario_Mapping_principiante.png?ex=66de400b&is=66dcee8b&hm=e800b8c18f5bec94c717ffcbfcfbde700b6e0a13130c01a3339dd23613cbeab8&"/>
</div>

### Segmento 2: Expertos en la agricultura
<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282134224144437300/To-Be_Scenario_Mapping_Avanzado.png?ex=66de400b&is=66dcee8b&hm=e8b7a61928332df02691482d711a3235a46e2b17cc52fc525437a77dea5957ca&"/>
</div>

**Requisitos Funcionales:**

**1. Registro de Usuarios:** Permitir a los usuarios crear una cuenta proporcionando información básica como nombre, dirección de correo electrónico y contraseña.
  
**2. Inicio de sesión de Usuarios:** Permitir a los usuarios iniciar sesión en sus cuentas utilizando su dirección de correo electrónico y contraseña.
  
**3. Recuperación de contraseña:** Proporcionar a los usuarios la opción de restablecer su contraseña en caso de olvido.
  
**4. Gestión de Perfil:** Permitir a los usuarios ver y editar su perfil, actualizando sus datos inicialmente registrados.
  
**5. Visualización de Dispositivos IoT:** Permitir a los usuarios visualizar todos los dispositivos IOT que están conectados en sus cultivos.
  
**6. Visualizar un Dashboard de Análisis:** Permite a los usuarios tener un dashboard de los análisis de temperatura, humedad y luz de todos los cultivos.
  
**7. Chatbot con IA:** Permite a los usuarios interactuar con el chatbot para que pueda responder todas sus dudas respecto a la agricultura, y los dispositivos IOT.
  
**8. Participación en comunidades:** Permitir a los usuarios comunicarse entre ellos mediante las comunidades para compartir sus experiencias y/o soluciones en caso tengan alguna duda o recomendación.
  
**9. Reseñas de cursos:** Permitir a los usuarios publicar reseñas sobre los cursos adquiridos.
  
**10. Notificación de alerta:** Se enviará una notificación de alerta cuando la temperatura o humedad superen los rangos óptimos establecidos.
  

**Requisitos No Funcionales:**

**1. Disponibilidad:** Asegurar que la aplicación esté disponible para su uso de lunes a viernes, desde las 08:00 hasta las 22:00 horas.
**2. Usabilidad:** Diseñar una interfaz de usuario intuitiva y fácil de usar que permita a los usuarios disfrutar la aplicación sin dificultades ni confusiones, que se podrá aprender a usar en un tiempo no mayor a 40 minutos.
**3. Compatibilidad:** Asegurar que la aplicación sea compatible con los navegadores web y dispositivos móviles actuales para garantizar una experiencia uniforme para todos los usuarios, específicamente: Edge, Chrome, Opera y Mozilla para los navegadores, y dispositivos móviles que utilicen Android y iOS.
  
**4. Escalabilidad:** Diseñar la aplicación de manera que pueda escalar fácilmente para manejar un aumento en el número de usuarios y la carga de trabajo sin comprometer el rendimiento o la disponibilidad.
  
**5. Eficiencia:** El sistema debe ser capaz de funcionar correctamente con hasta 100 usuarios conectados a la vez.

## 3.2. User Stories

En este segmento presentamos los User Stories, una herramienta poderosa que nos ayudará a comprender y documentar los requisitos desde la perspectiva del usuario en forma de historias simples y centradas en el usuario. Cada User Story representa un objetivo específico que un usuario desea alcanzar al interactuar con nuestro producto o servicio, lo que nos permite enfocarnos en las funcionalidades y características que realmente importan para nuestros usuarios.

| Epic ID | Título de Épica | Descripción de la épica |
|---------|-----------------|-------------------------|
| EP001 | Definición de estructura del landing page | Como principiante y experto, quiero disponer de un landing page con información pertinente para conocer todo acerca del producto. |
| EP002 | Definición de estructura del Front-End | Como principiante y experto, quiero disponer de una aplicación web funcional para poder registrarme y utilizar los distintos servicios que esta ofrece. | 
| EP003 | Implementación del sistema de monitoreo IoT | Como principiante y experto, quiero un sistema de monitoreo IoT que me permita visualizar en tiempo real las condiciones de mis cultivos para optimizar su cuidado y manejo. |
| EP004 | Integración de chatbot con IA | Como principiante y experto, quiero tener acceso a un chatbot inteligente que responda a mis preguntas sobre agricultura para recibir soporte inmediato y personalizado. | 
| EP005 | Implementación de servicio de asistencia continua | Como principiante y experto, quiero disponer de un servicio de asistencia disponible en todo momento para resolver cualquier inconveniente con el sistema de monitoreo o el chatbot de manera inmediata. |

<br>

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|-----------------|--------|-------------|------------------------|---------------------------|
| US01 | Registro de Usuario | Como principiante y/o experto, Quiero registrarme en la página Para observar todo lo que ofrece el servicio. | Escenario 1: Crear una cuenta <br> Dado que el principiante y/o experto ingresa a la página web, Cuando el usuario no se encuentra registrado en la página Entonces podrá registrarse ingresando sus datos. <br> Escenario 2: Rellenado de datos correctamente <br> Dado que el principiante y/o experto desea registrarse en la página, Cuando rellene toda la información requerida con sus datos, Entonces el sistema registra sus datos ingresados a la base de datos. <br> Escenario 3: Rellenado de datos incorrectamente. <br> Dado que el principiante y/o experto desea registrarse en la página, Cuando no ingresa los datos correctamente, Entonces el sistema le indicará que “Está incorrecto” o “Falta rellenar este dato”. | EP002 |
| US02 | Visualización del Landing Page | Como principiante y/o experto Quiero visualizar toda la información de las funcionalidades del servicio Para conocer a fondo los beneficios para mis cultivos | Escenario 1: El invitado visualiza la sección landing page <br> Dado que el principiante y/o experto desea información del producto inteligente, Cuando ingrese a nuestra landing page Entonces verá toda la información que ofrece nuestro producto inteligente. <br> Escenario 2: El invitado no puede visualizar la sección landing page <br> Dado que el aficionado y/o experto desea información del producto inteligente, Cuando ingrese a nuestra landing page y no pueda visualizarlo por algún error interno Entonces será redirigido a una página predeterminada que indique que la página no está disponible temporalmente. | EP001 |
| US03 | Visualización de Dashboard | Como principiante y/o experto registrado Quiero visualizar el dashboard de mi cuenta Para monitorear el estado de mis cultivos en tiempo real | Escenario 1: Visualización de datos del simulador IoT Dado que el principiante y/o experto ha iniciado sesión, Cuando accede al dashboard, Entonces debe poder ver los datos actuales como humedad, luz, y otros parámetros de los cultivos. <br> Escenario 2: Actualización automática de datos Dado que el principiante y/o experto está en el dashboard, Cuando los datos del simulador cambian, Entonces el dashboard debe actualizarse automáticamente en tiempo real. | EP003 |
| US04 | Consulta de Asesoría | Como principiante y/o experto registrado Quiero consultar al chatbot Para resolver dudas sobre el manejo de mis cultivos | Escenario 1: Realización de preguntas al chatbot <br> Dado que el principiante y/o experto tiene una duda sobre sus cultivos, Cuando accede al chatbot, Entonces debe poder realizar su consulta y recibir una respuesta inmediata. <br> Escenario 2: Recomendaciones personalizadas <br> Dado que el principiante y/o experto consulta al chatbot, Cuando proporciona información detallada sobre sus cultivos, Entonces el chatbot debe ofrecer recomendaciones personalizadas basadas en los datos del simulador. <br> Escenario 3: Interacciones continuas <br> Dado que el principiante y/o experto desea continuar consultando al chatbot, Cuando finaliza una consulta, Entonces el sistema debe permitirle iniciar una nueva conversación sin necesidad de volver a iniciar sesión. | EP004 |
| US05 | Gestión de Contenidos de Información | Como administrador Quiero gestionar los contenidos informativos del landing page Para mantener la información actualizada y relevante para los usuarios | Escenario 1: Actualización de textos e imágenes <br> Dado que el administrador desea actualizar el landing page, Cuando accede al panel de gestión de contenidos, Entonces debe poder modificar textos, imágenes y otros elementos del landing page. <br> Escenario 2: Previsualización de cambios <br> Dado que el administrador realiza cambios en el landing page, Cuando presiona "Previsualizar", Entonces el sistema debe mostrar una vista previa del landing page con las modificaciones antes de guardarlas. <br> Escenario 3: Publicación de contenidos Dado que el administrador está satisfecho con los cambios, Cuando presiona "Publicar", Entonces el sistema debe actualizar el landing page y hacer los cambios visibles para todos los usuarios. | EP001 |
| US06 | Visualización de los servicios que ofrecen en el landing page | Como principiante y/o experto Quiero visualizar los beneficios de la página, Para entender los servicios que esta ofrece | Escenario 1: El invitado visualiza la sección de servicios <br> Dado que el principiante y/o experto desea saber los servicios de la página web Cuando lea la información brindada de la landing page, Entonces podrá informarse acerca de todos los servicios que ofrecerá nuestra página. <br> Escenario 2: El invitado no puede visualizar la sección de servicios <br> Dado que el principiante y/o experto desea saber los servicios de la página web Cuando ingrese a la landing page y no puede visualizar el contenido por un error interno Entonces se mostrará un mensaje indicando que los servicios no están disponibles temporalmente. | EP001 |
| US07 | Visualización de los testimonios de personas sobre la landing page | Como principiante y/o experto Quiero visualizar los testimonios de distintas personas acerca de la aplicación web para saber si es lo que busco o no. | Escenario 1: El invitado visualiza la sección Testimonios. <br> Dado que el principiante y/o experto desea saber la el testimonio de personas que han usado la aplicación web Cuando ingrese a la landing page Entonces podrá informarse acerca de todos los testimonios de personas acerca de nuestra página <br> Escenario 2: El invitado no puede visualizar la sección Testimonios. <br> Dado que el principiante y/o experto desea saber la el testimonio de personas que han usado la aplicación web Cuando ingrese a la landing page no puede visualizar el contenido por algún error Entonces no podrá informarse acerca de todos los testimonios de personas acerca de nuestra página | EP001 |
| US08 | Seguridad de datos | Como principiante y/o experto, quiero asegurarme de que mis datos personales y de cultivos están protegidos contra accesos no autorizados. | Escenario 1: Seguridad de datos personales <br> Dado que el principiante y/o experto ingresa datos personales, cuando completa su perfil, entonces el sistema debe garantizar la protección de esos datos. <br> Escenario 2: Seguridad de datos de cultivos <br> Dado que el principiante y/o experto monitorea cultivos, cuando el sistema almacena datos, entonces deben ser accesibles solo por el usuario autenticado. <br> | EP002 |
| US09 | Visualización de datos en gráficos | Como principiante y/o experto, quiero visualizar los datos de mis cultivos en gráficos intuitivos para comprender mejor la información. | Escenario 1: Acceso a gráficos <br> Dado que el principiante y/o experto accede a la sección de visualización de datos, cuando selecciona un tipo de gráfico, entonces los datos deben mostrarse en el formato elegido (líneas, barras, etc.). <br> Escenario 2: Comparación visual <br> Dado que el principiante y/o experto selecciona varios conjuntos de datos, cuando se visualizan juntos, entonces el gráfico debe mostrar claramente las diferencias o similitudes. | EP003 |
| US10 | Actualización de datos IoT | Como principiante y/o experto Quiero que los datos de mis cultivos se actualicen automáticamente Para tener la información más reciente disponible en mi dashboard | Escenario 1: Actualización automática <br> Dado que el principiante y/o experto está en el dashboard, Cuando el sistema IoT recoge nuevos datos, Entonces el dashboard debe actualizarse automáticamente sin necesidad de refrescar la página. <br> Escenario 2: Notificación de cambios significativos <br> Dado que los datos del cultivo cambian significativamente, Cuando el sistema lo detecta, Entonces debe enviar una notificación al principiante y/o experto. <br> Escenario 3: Revisión de históricos Dado que el principiante y/o experto desea ver los datos anteriores, Cuando selecciona la opción de "Histórico", Entonces el sistema debe mostrar los datos históricos del cultivo de manera clara y organizada. | EP003 |
| US11 | Notificaciones de Alertas Críticas | Como principiante y/o experto Quiero recibir notificaciones inmediatas de alertas críticas Para poder tomar acciones rápidas y evitar daños en mis cultivos | Escenario 1: Configuración de alertas <br> Dado que el principiante y/o experto desea recibir alertas, Cuando accede a la configuración de alertas, Entonces debe poder seleccionar qué tipos de alertas desea recibir y cómo. <br> Escenario 2: Recepción de alertas <br> Dado que el sistema detecta una situación crítica, Cuando los datos de IoT indican un problema (p. ej., falta de agua), Entonces debe enviar una notificación al usuario inmediatamente. | EP003 |
| US12 | Recomendación sobre fertilizantes | Como agricultor, quiero que el chatbot me ayude a identificar enfermedades comunes en los cultivos a partir de una foto. | Escenario 1: Recomendación de fertilizantes <br> Dado que el agricultor pregunta sobre fertilización, Cuando el chatbot recibe la consulta, Entonces proporciona información específica para el tipo de cultivo del usuario. | EP004 |
| US13 | Respuesta a preguntas frecuentes | Como agricultor, quiero que el chatbot responda a preguntas frecuentes sobre el uso de la plataforma. | Escenario 1: Respuesta a preguntas frecuentes. <br> Dado que el agricultor tiene una pregunta frecuente, Cuando el chatbot recibe la consulta, Entonces responde con la información correspondiente de la base de conocimientos. | EP004 |
| US14 | Notificación de humedad | Como agricultor, quiero recibir notificaciones cuando la humedad del suelo esté por debajo del umbral establecido para poder regar mis cultivos a tiempo | Escenario 1: Notificación de la humedad. <br> Dado que el agricultor ha configurado un umbral de humedad, Cuando la humedad del suelo cae por debajo de este umbral, Entonces el agricultor recibe una notificación en la aplicación. | EP003 |
| US15 | Visualizar historial de sensores | Como agricultor, quiero poder ver el historial de sensores para identificar tendencias a lo largo del tiempo. | Escenario 1: Selección de rango de fechas. <br> Dado que el agricultor accede al historial de sensores, Cuando selecciona un rango de fechas, Entonces se muestra el historial de datos recopilados durante ese período. | EP003 |
| US16 | Notificación de alertas de Temperatura | Como agricultor, quiero recibir alertas si la temperatura de mis cultivos se desvía significativamente de los valores óptimos para poder regar los cultivos en caso la temperatura este muy caliente. | Escenario 1: Alerta recibida <br> Dado que se han establecido valores óptimos de temperatura, Cuando la temperatura se desvía de estos valores, Entonces el agricultor recibe una alerta. | EP003 |
| US17 | Programación de Riego Automatizado | Como principiante y/o experto Quiero programar el sistema de riego automatizado Para optimizar el uso de agua y asegurar que mis cultivos reciban la cantidad adecuada de riego | Escenario 1: Configuración de riego automatizado <br> Dado que el principiante y/o experto desea optimizar el riego, Cuando accede a la configuración de riego, Entonces debe poder establecer horarios y condiciones específicas para la activación automática del sistema de riego. <br> Escenario 2: Monitoreo de riego automatizado <br> Dado que el riego automatizado está activo, Cuando el sistema realiza un ciclo de riego, Entonces debe registrar el evento y notificar al usuario. <br> Escenario 3: Ajustes basados en datos de sensores Dado que el sistema de riego está automatizado, Cuando los sensores detectan cambios en la humedad del suelo, Entonces el sistema debe ajustar automáticamente la programación del riego para evitar un exceso o falta de agua. | EP003 |
| US18 | Generación de Reportes de Desempeño | Como experto Quiero generar reportes detallados sobre el desempeño de mis cultivos Para analizar su evolución y tomar decisiones informadas | Escenario 1: Creación de reportes personalizados <br> Dado que el experto desea conocer el desempeño de sus cultivos, Cuando accede a la sección de reportes, Entonces debe poder seleccionar los parámetros y periodo para generar un reporte personalizado. <br> Escenario 2: Comparación de reportes <br> Dado que el experto ha generado múltiples reportes, Cuando selecciona la opción de comparación, Entonces el sistema debe mostrar una comparación visual entre los reportes seleccionados. <br> Escenario 3: Exportación de reportes Dado que el experto ha generado un reporte, Cuando selecciona la opción de exportar, Entonces debe poder descargar el reporte en formato PDF o Excel. | EP003 |
| US19 | Asistencia en la Optimización de Recursos | Como principiante o experto Quiero recibir asistencia para optimizar el uso de recursos agrícolas Para reducir costos y mejorar la eficiencia de mi producción | Escenario 1: Evaluación del uso de recursos <br> Dado que el principiante o experto desea optimizar el uso de recursos, Cuando accede a la sección de recursos, Entonces debe poder ver el consumo actual y recibir sugerencias de optimización. <br> Escenario 2: Alertas de uso excesivo <br> Dado que el principiante o experto ha establecido umbrales de consumo, Cuando se excede un umbral, Entonces el sistema debe enviar una alerta con recomendaciones para reducir el uso. <br> Escenario 3: Análisis de eficiencia <br> Dado que el principiante o experto desea mejorar la eficiencia, Cuando accede a la sección de análisis, Entonces el sistema debe proporcionar un informe sobre el uso de recursos y sugerencias para optimizar el consumo basado en los datos históricos y actuales. | EP003 |
| US20 | Registro de Actividades de Mantenimiento | Como principiante o experto Quiero registrar las actividades de mantenimiento realizadas en los cultivos Para llevar un control detallado y planificar futuros trabajos | Escenario 1: Registro de nuevas actividades <br> Dado que el principiante o experto realiza una actividad de mantenimiento, Cuando accede a la sección de actividades, Entonces debe poder registrar los detalles de la actividad (p. ej., fecha, tipo de trabajo, duración). <br> Escenario 2: Consulta de historial de actividades Dado que el principiante o experto ha registrado varias actividades, Cuando accede al historial, Entonces debe poder visualizar un listado con las actividades realizadas y detalles de cada una. <br> Escenario 3: Programación de futuras actividades <br> Dado que el principiante o experto desea planificar actividades de mantenimiento, Cuando accede a la programación, Entonces debe poder establecer fechas y recordatorios para futuras tareas de mantenimiento. | EP002 |

## 3.3. Impact Mapping
Presentamos el segmento de Impact Map, una herramienta estratégica que nos permite visualizar y comunicar el impacto deseado de nuestras iniciativas y proyectos, el cual nos ayuda a trazar un camino claro desde nuestras actividades y entregables hasta los resultados finales que buscamos lograr, identificando los principales impulsores de valor y las métricas clave que nos indicarán nuestro progreso hacia el éxito. A través de esta visualización estructurada y centrada en los resultados, podemos alinear eficazmente nuestros esfuerzos con nuestra visión estratégica, involucrar a las partes interesadas pertinentes y tomar decisiones informadas que impulsen el crecimiento y la innovación en nuestra organización.

### Principiante en agricultura

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282134224933224470/image.png?ex=66de400c&is=66dcee8c&hm=16af77f820f794e87a7a1bf2fc5be91739644df9ff55edf2cdf6e05ea5e2ced8&"/>
</div>

### Experto en agricultura

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282134506328948838/image.png?ex=66de404f&is=66dceecf&hm=bcdc326737ac4e01336a67c3fb556d1a098ec69e380ba3f5561cf653ffcfb2f8&"/>
</div>

## 3.4. Product Backlog

| #Orden | User Story Id | Título | Descripción | Story Points (1/2/3/5/8) |
|--------|---------------|--------|-------------|--------------------------|
| 1 | US01 | Registro de Usuario | Como principiante y/o experto, Quiero registrarme en la página Para observar todo lo que ofrece el servicio. | 3 |
| 2 | US02 | Visualización del Landing Page | Como principiante y/o experto Quiero visualizar toda la información de las funcionalidades del servicio Para conocer a fondo los beneficios para mis cultivos | 2 |
| 3 | US06 | Visualización de los servicios que ofrecen en el landing page | Como principiante y/o experto Quiero visualizar los beneficios de la página, Para entender los servicios que esta ofrece | 2 |
| 4 | US07 | Visualización de los testimonios de personas sobre la landing page | Como principiante y/o experto Quiero visualizar los testimonios de distintas personas acerca de la aplicación web para saber si es lo que busco o no. | 2 |
| 5 | US03 | Visualización de Dashboard | Como principiante y/o experto registrado Quiero visualizar el dashboard de mi cuenta Para monitorear el estado de mis cultivos en tiempo real | 5 |
| 6 | US09 | Visualización de datos en gráficos | Como principiante y/o experto, quiero visualizar los datos de mis cultivos en gráficos intuitivos para comprender mejor la información. | 5 |
| 7 | US04 | Consulta de Asesoría | Como principiante y/o experto registrado Quiero consultar al chatbot Para resolver dudas sobre el manejo de mis cultivos | 5 |
| 8 | US05 | Gestión de Contenidos de Información | Como administrador Quiero gestionar los contenidos informativos del landing page Para mantener la información actualizada y relevante para los usuarios | 2 |
| 9 | US08 | Seguridad de datos | Como principiante y/o experto, quiero asegurarme de que mis datos personales y de cultivos están protegidos contra accesos no autorizados. | 3 |
| 10 | US10 | Actualización de datos IoT | Como principiante y/o experto Quiero que los datos de mis cultivos se actualicen automáticamente Para tener la información más reciente disponible en mi dashboard | 5 |
| 11 | US11 | Notificaciones de Alertas Críticas | Como principiante y/o experto Quiero recibir notificaciones inmediatas de alertas críticas Para poder tomar acciones rápidas y evitar daños en mis cultivos | 5 |
| 12 | US12 | Recomendación sobre fertilizantes | Como agricultor, quiero que el chatbot me ayude a identificar enfermedades comunes en los cultivos a partir de una foto. | 3 |
| 13 | US14 | Notificación de humedad | Como agricultor, quiero recibir notificaciones cuando la humedad del suelo esté por debajo del umbral establecido para poder regar mis cultivos a tiempo | 5 |
| 14 | US15 | Visualizar historial de sensores | Como agricultor, quiero poder ver el historial de sensores para identificar tendencias a lo largo del tiempo. | 3 |
| 15 | US13 | Respuesta a preguntas frecuentes | Como agricultor, quiero que el chatbot responda a preguntas frecuentes sobre el uso de la plataforma. | 3 |
| 16 | US16 | Notificación de alertas de Temperatura | Como agricultor, quiero recibir alertas si la temperatura de mis cultivos se desvía significativamente de los valores óptimos para poder regar los cultivos en caso la temperatura este muy caliente. | 5 |
| 17 | US17 | Programación de Riego Automatizado | Como principiante y/o experto Quiero programar el sistema de riego automatizado Para optimizar el uso de agua y asegurar que mis cultivos reciban la cantidad adecuada de riego | 8 |
| 18 | US18 | Generación de Reportes de Desempeño | Como experto Quiero generar reportes detallados sobre el desempeño de mis cultivos Para analizar su evolución y tomar decisiones informadas | 5 |
| 19 | US019 | Asistencia en la Optimización de Recursos | Como principiante o experto Quiero recibir asistencia para optimizar el uso de recursos agrícolas Para reducir costos y mejorar la eficiencia de mi producción | 8 |
| 20 | US020 | Registro de Actividades de Mantenimiento | Como principiante o experto Quiero registrar las actividades de mantenimiento realizadas en los cultivos Para llevar un control detallado y planificar futuros trabajos | 5 |

# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design

### 4.1.1. Design Purpose

El propósito de nuestro diseño es mejorar las prácticas agrícolas al integrar tecnologías avanzadas en el cultivo. Queremos ofrecer una plataforma que use sensores IoT para monitorear aspectos clave como humedad, luz y temperatura en tiempo real, junto con un chatbot inteligente que brinda asistencia instantánea. Esto ayuda a los usuarios a tomar decisiones más precisas y a optimizar sus métodos de cultivo. Nuestro objetivo es promover prácticas agrícolas más inteligentes y sostenibles, haciendo la tecnología más accesible para todos y contribuyendo a una producción más eficiente e innovadora.

### 4.1.2. Attribute-Driven Design Inputs

En esta sección abordaremos los inputs esenciales para el diseño basado en atributos, incluyendo funcionalidades principales, escenarios de atributos de calidad y restricciones. Estos elementos son clave para desarrollar una solución efectiva y alineada con los objetivos del proyecto.

#### 4.1.2.1. Primary Functionality (Primary User Stories)

| Epic / User Story ID | Título                           | Descripción                                                                                 | Criterios de Aceptación                                                                                                                                                 | Relacionado con (Epic ID) |
|----------------------|----------------------------------|---------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------|
| US01                 | Registro de Usuario              | Como principiante y/o experto, quiero registrarme en la página para observar todo lo que ofrece el servicio. | - **Escenario 1**: Crear una cuenta. Dado que el principiante y/o experto ingresa a la página web, cuando el usuario no se encuentra registrado en la página, entonces podrá registrarse ingresando sus datos.<br>- **Escenario 2**: Rellenado de datos correctamente. Dado que el principiante y/o experto desea registrarse en la página, cuando rellene toda la información requerida con sus datos, entonces el sistema registra sus datos ingresados a la base de datos.<br>- **Escenario 3**: Rellenado de datos incorrectamente. Dado que el principiante y/o experto desea registrarse en la página, cuando no ingresa los datos correctamente, entonces el sistema le indicará que “Está incorrecto” o “Falta rellenar este dato.” | EP002                     |
| US03                 | Visualización de Dashboard       | Como principiante y/o experto registrado, quiero visualizar el dashboard de mi cuenta para monitorear el estado de mis cultivos en tiempo real. | - **Escenario 1**: Visualización de datos del simulador IoT. Dado que el principiante y/o experto ha iniciado sesión, cuando accede al dashboard, entonces debe poder ver los datos actuales como humedad, luz, y otros parámetros de los cultivos.<br>- **Escenario 2**: Actualización automática de datos. Dado que el principiante y/o experto está en el dashboard, cuando los datos del simulador cambian, entonces el dashboard debe actualizarse automáticamente en tiempo real. | EP003                     |
| US04                 | Consulta de Asesoría             | Como usuario registrado, quiero consultar al chatbot para resolver dudas sobre el manejo de mis cultivos. | - **Escenario 1**: Realización de preguntas al chatbot. Dado que el usuario tiene una duda sobre sus cultivos, cuando accede al chatbot, entonces debe poder realizar su consulta y recibir una respuesta inmediata.<br>- **Escenario 2**: Recomendaciones personalizadas. Dado que el usuario consulta al chatbot, cuando proporciona información detallada sobre sus cultivos, entonces el chatbot debe ofrecer recomendaciones personalizadas basadas en los datos del simulador.<br>- **Escenario 3**: Interacciones continuas. Dado que el usuario desea continuar consultando al chatbot, cuando finaliza una consulta, entonces el sistema debe permitirle iniciar una nueva conversación sin necesidad de volver a iniciar sesión. | EP004                     |
| US05                 | Gestión de Contenidos de Información | Como administrador, quiero gestionar los contenidos informativos del landing page para mantener la información actualizada y relevante para los usuarios. | - **Escenario 1**: Actualización de textos e imágenes. Dado que el administrador desea actualizar el landing page, cuando accede al panel de gestión de contenidos, entonces debe poder modificar textos, imágenes y otros elementos del landing page.<br>- **Escenario 2**: Previsualización de cambios. Dado que el administrador realiza cambios en el landing page, cuando presiona "Previsualizar", entonces el sistema debe mostrar una vista previa del landing page con las modificaciones antes de guardarlas.<br>- **Escenario 3**: Publicación de contenidos. Dado que el administrador está satisfecho con los cambios, cuando presiona "Publicar", entonces el sistema debe actualizar el landing page y hacer los cambios visibles para todos los usuarios. | EP001                     |
| US008                | Seguridad de datos               | Como principiante y/o experto, quiero asegurarme de que mis datos personales y de cultivos están protegidos contra accesos no autorizados. | - **Escenario 1**: Seguridad de datos personales. Dado que el principiante y/o experto ingresa datos personales, cuando completa su perfil, entonces el sistema debe garantizar la protección de esos datos.<br>- **Escenario 2**: Seguridad de datos de cultivos. Dado que el principiante y/o experto monitorea cultivos, cuando el sistema almacena datos, entonces deben ser accesibles solo por el usuario autenticado. | EP002                     |
| US010                | Actualización de datos IoT       | Como usuario, quiero que los datos de mis cultivos se actualicen automáticamente para tener la información más reciente disponible en mi dashboard. | - **Escenario 1**: Actualización automática. Dado que el usuario está en el dashboard, cuando el sistema IoT recoge nuevos datos, entonces el dashboard debe actualizarse automáticamente sin necesidad de refrescar la página.<br>- **Escenario 2**: Notificación de cambios significativos. Dado que los datos del cultivo cambian significativamente, cuando el sistema lo detecta, entonces debe enviar una notificación al usuario.<br>- **Escenario 3**: Revisión de históricos. Dado que el usuario desea ver los datos anteriores, cuando selecciona la opción de "Histórico", entonces el sistema debe mostrar los datos históricos del cultivo de manera clara y organizada. | EP003                     |
| US011                | Notificaciones de Alertas Críticas | Como usuario, quiero recibir notificaciones inmediatas de alertas críticas para poder tomar acciones rápidas y evitar daños en mis cultivos. | - **Escenario 1**: Configuración de alertas. Dado que el usuario desea recibir alertas, cuando accede a la configuración de alertas, entonces debe poder seleccionar qué tipos de alertas desea recibir y cómo.<br>- **Escenario 2**: Recepción de alertas. Dado que el sistema detecta una situación crítica, cuando los datos de IoT indican un problema (p. ej., falta de agua), entonces debe enviar una notificación al usuario inmediatamente. | EP003                     |
| US017                | Programación de Riego Automatizado | Como principiante y/o experto, quiero programar el sistema de riego automatizado para optimizar el uso de agua y asegurar que mis cultivos reciban la cantidad adecuada de riego. | - **Escenario 1**: Configuración de Riego Automatizado. Dado que el usuario está utilizando la aplicación, cuando el usuario accede a la sección de riego automatizado, entonces el sistema muestra las opciones para programar riegos, incluyendo la selección de días, horarios y la cantidad de agua a utilizar.<br>- **Escenario 2**: Ejecución de Riego Programado. Dado que el usuario ha configurado el riego automatizado, cuando el riego programado debe iniciar según la configuración, entonces el sistema ejecuta el riego y envía una notificación al usuario confirmando la ejecución.<br>- **Escenario 3**: Notificación de Fallos en el Riego. Dado que el riego automatizado está en curso, cuando ocurre un fallo o interrupción en el sistema de riego, entonces el sistema debe alertar al usuario inmediatamente y ofrecer opciones de solución o reprogramación del riego. | EP001                     |
| US019                | Asistencia en la Optimización de Recursos | Como principiante o experto, quiero recibir asistencia para optimizar el uso de recursos agrícolas para reducir costos y mejorar la eficiencia de mi producción. | - **Escenario 1**: Generación de Recomendaciones de Optimización. Dado que el usuario ha ingresado sus cultivos y recursos en la aplicación, cuando el usuario solicita recomendaciones para optimizar el uso de recursos, entonces el sistema analiza los datos ingresados y genera sugerencias específicas para mejorar la eficiencia en el uso de agua, fertilizantes, y otros insumos.<br>- **Escenario 2**: Implementación y Seguimiento de Sugerencias. Dado que el usuario recibe recomendaciones del sistema, cuando el usuario sigue las recomendaciones sugeridas, entonces el sistema debe permitir el seguimiento de los resultados y ofrecer retroalimentación adicional en base a los datos recolectados post-implementación.<br>- **Escenario 3**: Ajuste de Recomendaciones por Cambios. Dado que el usuario ha implementado parcialmente las sugerencias, cuando se producen cambios en las condiciones de cultivo o recursos, entonces el sistema debe ajustar las recomendaciones y notificar al usuario de cualquier nueva optimización posible. | EP002                     |

#### 4.1.2.2. Quality attribute Scenarios

En esta sección se describen los escenarios de atributos de calidad más relevantes que afectan la arquitectura de la solución. Estos escenarios sirven como base para guiar el proceso de diseño y asegurar que se cumplan los requisitos de calidad definidos. A continuación, se presentan los escenarios iniciales identificados:

| Atributo     | Fuente           | Estímulo                                           | Artefacto             | Entorno           | Respuesta                                          | Medida                               |
|--------------|------------------|----------------------------------------------------|-----------------------|-------------------|---------------------------------------------------|--------------------------------------|
| Disponibilidad | Usuario          | Se produce un error de conexión al intentar acceder a la plataforma | Servidor de la plataforma | Operación normal  | El sistema redirige a una página de error con un mensaje y trata de reconectar | Tiempo de reconexión en segundos     |
| Desempeño     | Usuario          | Actualización de datos en el dashboard en tiempo real | Dashboard             | Operación normal  | El sistema actualiza los datos de sensores en tiempo real | Tiempo de actualización en milisegundos |
| Seguridad     | Usuario no autorizado | Intento de acceso a datos personales o de cultivos | Base de datos         | Intento de intrusión | El sistema deniega el acceso y registra el intento | Número de intentos fallidos registrados |
| Escalabilidad | Usuario          | Aumento en la cantidad de usuarios concurrentes   | Plataforma en general | Alta demanda      | El sistema maneja la carga sin degradación del servicio | Número máximo de usuarios concurrentes |
| Usabilidad    | Usuario          | El usuario intenta realizar una consulta al chatbot | Chatbot               | Operación normal  | El sistema responde con información relevante en tiempo adecuado | Tiempo de respuesta del chatbot en segundos |
| Fiabilidad    | Usuario          | Notificación de una alerta crítica sobre las condiciones del cultivo | Sistema de notificaciones | Operación crítica | El sistema envía la notificación sin fallos | Tasa de entrega de notificaciones (%)  |

#### 4.1.2.3. Constraints

En esta sección se detallan las restricciones que deben ser consideradas en el diseño y desarrollo de la solución. Estas restricciones no son negociables y están definidas por el cliente o el negocio para asegurar que el producto final cumpla con las expectativas. A continuación, se listan las restricciones clave:

| Technical Story ID | Título                     | Descripción                                                                                          | Criterios de Aceptación                                                                                                                           | Relacionado con (Epic ID) |
|--------------------|----------------------------|------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------|
| TS01               | Seguridad de Datos         | La plataforma debe garantizar la protección de la información personal y de cultivos de los usuarios. | Dado que un usuario ingresa sus datos personales, cuando completa su perfil o monitorea cultivos, entonces el sistema debe encriptar los datos y permitir el acceso solo a usuarios autenticados. | EP02                      |
| TS02               | Compatibilidad Multiplataforma | La solución debe ser accesible y funcional tanto en dispositivos móviles como en escritorio.       | Dado que un usuario accede a la plataforma, cuando lo hace desde diferentes dispositivos, entonces el sistema debe funcionar correctamente en iOS, Android, Windows y macOS. | EP01, EP03                |
| TS03               | Integración con Dispositivos IoT | La plataforma debe conectarse y recibir datos en tiempo real de dispositivos IoT para la monitorización de cultivos. | Dado que un dispositivo IoT se conecta a la plataforma, cuando este transmite datos, entonces la plataforma debe recibir y procesar la información en tiempo real. | EP03                      |
| TS04               | Escalabilidad              | El sistema debe ser capaz de manejar un incremento en el número de usuarios y dispositivos conectados sin afectar el rendimiento. | Dado que aumenta la cantidad de usuarios y dispositivos conectados, cuando el sistema experimenta esta carga, entonces debe soportar al menos 1000 usuarios y 500 dispositivos IoT simultáneamente. | EP03                      |
| TS05               | Actualización de Contenidos | Los administradores deben poder actualizar el contenido de la plataforma sin requerir soporte técnico. | Dado que un administrador realiza cambios en el contenido, cuando los publica, entonces estos deben reflejarse inmediatamente en la plataforma. | EP01                      |
| TS06               | Notificaciones Rápidas     | Las alertas críticas deben ser enviadas a los usuarios rápidamente para permitir una respuesta inmediata a cualquier problema. | Dado que el sistema detecta una situación crítica, cuando se activa una alerta, entonces la notificación debe enviarse al usuario en menos de 5 segundos. | EP03                      |

### 4.1.3. Architectural Drivers Backlog

En esta sección se presenta el conjunto de Architectural Drivers acordados por el equipo, resultado de un proceso iterativo en el Quality Attribute Workshop. El equipo se centró en identificar los drivers que tienen la mayor relevancia para los stakeholders y el mayor impacto en la complejidad técnica de la arquitectura. A continuación, se presenta el Architectural Drivers Backlog, priorizando aquellos de alta importancia y alto impacto.

| Driver ID | Título de Driver             | Descripción                                                                                          | Importancia para Stakeholders | Impacto en Architecture Technical Complexity |
|-----------|------------------------------|------------------------------------------------------------------------------------------------------|-------------------------------|----------------------------------------------|
| FD01      | Monitoreo en Tiempo Real     | La capacidad de la plataforma para ofrecer datos de cultivos en tiempo real, esenciales para la toma de decisiones. | High                          | High                                         |
| QD01      | Seguridad de Datos           | Protección de los datos personales y de cultivos, asegurando que solo los usuarios autenticados tengan acceso. | High                          | High                                         |
| FD02      | Compatibilidad Multiplataforma | Asegurar que la plataforma funcione de manera óptima en dispositivos móviles y de escritorio.       | High                          | Medium                                       |
| QD02      | Escalabilidad                | Capacidad del sistema para manejar un número creciente de usuarios y dispositivos IoT sin pérdida de rendimiento. | High                          | High                                         |
| CD01      | Integración con IoT          | Garantizar la integración fluida y en tiempo real con dispositivos IoT para la monitorización de cultivos. | High                          | High                                         |
| CD02      | Actualización de Contenidos  | Facilitar que los administradores actualicen el contenido de la plataforma sin asistencia técnica. | High                          | High                                         |
| QD03      | Notificaciones Rápidas       | Envío inmediato de alertas críticas para permitir respuestas rápidas a situaciones adversas.       | High                          | Medium                                       |
| FD03      | Consulta de Asesoría         | Provisión de un chatbot inteligente que brinde asesoría y recomendaciones personalizadas a los usuarios. | Medium                        | Medium                                       |
| CD03      | Actualización Automática     | Automatización de la actualización de datos en el dashboard para reflejar cambios en tiempo real.  | Medium                        | High                                         |
| CD04      | Visualización de Datos       | Mostrar los datos de los cultivos en gráficos intuitivos que faciliten la comprensión por parte del usuario. | Medium                        | Medium                                       |

### 4.1.4. Architectural Design Decisions

En esta sección, resumimos las decisiones de diseño tomadas durante el Quality Attribute Workshop. Explicamos cómo evaluamos cada Architectural Driver, los patrones arquitectónicos considerados y los criterios utilizados para seleccionar las mejores opciones. A continuación, se presenta la Candidate Pattern Evaluation Matrix para ilustrar cómo se evaluaron los patrones arquitectónicos relevantes.

| Driver ID | Título de Driver            | MVC |                                      | Capas |                                      | Cliente-Servidor |                                      |
|-----------|-----------------------------|-----|--------------------------------------|-------|--------------------------------------|------------------|--------------------------------------|
|           |                             | Pro | Con                                  | Pro   | Con                                  | Pro              | Con                                  |
| FD01      | Monitoreo en Tiempo Real    | Separación clara entre la lógica de negocio, la interfaz de usuario y el control de datos en tiempo real. | Puede añadir complejidad innecesaria para aplicaciones simples. | Permite la separación de la lógica de negocio, la presentación y el acceso a datos, facilitando el monitoreo en tiempo real. | La comunicación entre capas puede introducir latencia. | Ideal para la comunicación en tiempo real entre clientes y servidores, manejando datos en vivo eficientemente. | Depende de la red y del servidor para la actualización en tiempo real. |
| QD01      | Seguridad de Datos          | Facilita la implementación de medidas de seguridad en la capa de acceso a datos y control de acceso. | La seguridad debe ser cuidadosamente implementada en cada componente. | Permite la implementación de medidas de seguridad en la capa de acceso a datos y en la capa de negocio. | La seguridad puede ser compleja de gestionar si no está bien definida. | Facilita la implementación de seguridad en el servidor centralizado, asegurando datos de clientes. | La seguridad depende de la protección del servidor y la comunicación segura. |
| FD02      | Compatibilidad Multiplataforma | Ofrece una separación clara que puede facilitar la adaptación a diferentes plataformas. | Puede requerir ajustes adicionales para cada plataforma. | La separación en capas facilita la adaptación y compatibilidad con diferentes plataformas. | La complejidad de las capas puede aumentar al soportar múltiples plataformas. | Permite que diferentes clientes interactúen con un servidor central, facilitando la compatibilidad multiplataforma. | Dependencia de la capacidad del servidor para manejar múltiples plataformas. |
| QD02      | Escalabilidad               | Permite una buena escalabilidad mediante la separación de preocupaciones. | Puede ser limitado si la infraestructura no está diseñada para escalar. | La modularidad de las capas permite escalar el sistema al agregar más capas o mejorar las existentes. | Escalar puede requerir ajustes en la comunicación entre capas. | Facilita la escalabilidad al permitir que el servidor se escale independientemente de los clientes. | Requiere una infraestructura robusta para manejar la carga de trabajo adicional. |
| CD01      | Integración con IoT         | Puede gestionar la integración de datos de IoT en el modelo de datos. | La integración directa puede ser compleja. | Permite una integración estructurada y modular con sistemas IoT. | La integración puede introducir complejidad adicional en la comunicación entre capas. | Ideal para manejar datos de dispositivos IoT a través de un servidor centralizado. | Requiere una robusta infraestructura de servidor para soportar la integración IoT. |
| CD02      | Actualización de Contenidos | Facilita la actualización de contenido en la capa de vista. | La lógica de actualización puede necesitar sincronización entre componentes. | Permite una actualización organizada del contenido en diferentes capas. | La actualización puede requerir coordinación entre capas. | Centraliza la gestión y actualización del contenido en el servidor, simplificando la sincronización. | La actualización del servidor debe ser eficiente para evitar impactos en el rendimiento. |
| QD03      | Notificaciones Rápidas      | Puede gestionar notificaciones a través del controlador. | Requiere una integración efectiva entre el controlador y la vista. | Permite la implementación de notificaciones en una capa dedicada. | La comunicación entre capas puede introducir latencia. | Ideal para enviar notificaciones rápidas desde el servidor a los clientes. | Depende de la infraestructura del servidor para el manejo eficiente de notificaciones. |
| FD03      | Consulta de Asesoría        | Facilita la separación entre la lógica de negocio del chatbot y la interfaz de usuario. | Puede requerir coordinación entre el modelo, la vista y el controlador. | Permite una separación clara de la lógica del chatbot y la interfaz de usuario. | La integración entre capas puede ser compleja. | Ideal para manejar consultas y respuestas del chatbot centralizado en el servidor. | Depende de la capacidad del servidor para gestionar consultas simultáneas. |
| CD03      | Actualización Automática    | Puede facilitar la actualización automática a través del controlador. | Requiere una integración efectiva entre componentes. | Permite la implementación de actualizaciones automáticas en una capa dedicada. | La sincronización entre capas puede ser compleja. | Permite la actualización automática de datos desde el servidor a los clientes sin necesidad de intervención del usuario. | Requiere una infraestructura robusta para gestionar actualizaciones automáticas. |
| CD04      | Visualización de Datos      | Facilita la visualización de datos a través de la separación entre el modelo de datos y la vista. | Puede ser complejo si la lógica de visualización es extensa. | Permite una visualización estructurada de los datos mediante la separación en capas. | La integración entre capas puede requerir ajustes adicionales. | Ideal para gestionar la visualización de datos centralizada y asegurar la consistencia entre diferentes clientes. | La carga del servidor puede aumentar con la visualización de grandes volúmenes de datos. |

### 4.1.5. Quality Attribute Scenario Refinements

En esta sección, se presentan los escenarios refinados para los atributos de calidad más relevantes, tras el proceso de Quality Attribute Workshop. Cada escenario ha sido priorizado en función de su impacto en el sistema y su alineación con los objetivos del negocio. A continuación, se detalla cada escenario con su estructura refinada.

| Scenario Refinement for Scenario 1 | |
|------------------------------------|-|
| **Scenario(s):** | Actualización Automática de Datos IoT |
| **Business Goals:**                | Asegurar que los datos de cultivos en el dashboard se actualicen en tiempo real para proporcionar información precisa y actualizada. |
| **Relevant Quality Attributes:**   | Monitoreo en Tiempo Real, Escalabilidad |
| **Scenario Components**            | **Stimulus:** Actualización de nuevos datos de sensores IoT.<br>**Stimulus Source:** Sistema IoT.<br>**Environment:** Dashboard de la aplicación mientras el usuario está activo.<br>**Artifact (if Known):** Interfaz de usuario del dashboard.<br>**Response:** El dashboard se actualiza automáticamente para reflejar los datos más recientes.<br>**Response Measure:** Tiempo de actualización de datos no superior a 5 segundos. |
| **Questions:**                     | ¿Cómo se maneja la carga de datos cuando hay un alto volumen de actualizaciones simultáneas?<br>¿Qué mecanismos se implementan para garantizar la consistencia de datos durante la actualización? |
| **Issues:**                        | La latencia en la actualización puede afectar la experiencia del usuario si los datos no se reflejan en tiempo real. |

| Scenario Refinement for Scenario 2 | |
|------------------------------------|-|
| **Scenario(s):** | Seguridad de Datos Personales y de Cultivos |
| **Business Goals:**                | Proteger los datos personales y los datos de cultivos de accesos no autorizados para mantener la confidencialidad y la integridad de la información. |
| **Relevant Quality Attributes:**   | Seguridad de Datos |
| **Scenario Components**            | **Stimulus:** Intentos de acceso no autorizado a datos personales o de cultivos.<br>**Stimulus Source:** Usuario no autenticado o sistema externo.<br>**Environment:** Sistema de almacenamiento de datos y mecanismos de autenticación.<br>**Artifact (if Known):** Base de datos y sistema de autenticación.<br>**Response:** El sistema bloquea el acceso y notifica al administrador sobre el intento de acceso no autorizado.<br>**Response Measure:** El tiempo de respuesta al intento de acceso no autorizado debe ser menor a 2 segundos. |
| **Questions:**                     | ¿Qué medidas de seguridad se implementan para prevenir accesos no autorizados?<br>¿Cómo se gestionan y responden las brechas de seguridad detectadas? |
| **Issues:**                        | La necesidad de equilibrar la seguridad con el rendimiento del sistema para evitar impactos negativos en la experiencia del usuario. |

| Scenario Refinement for Scenario 3 | |
|------------------------------------|-|
| **Scenario(s):** | Consulta de Asesoría |
| **Business Goals:**                | Proporcionar asistencia instantánea a los usuarios a través de un chatbot. |
| **Relevant Quality Attributes:**   | Consulta de Asesoría |
| **Scenario Components**            | **Stimulus:** Consulta realizada por un usuario al chatbot.<br>**Stimulus Source:** Usuario registrado.<br>**Environment:** Interfaz del chatbot.<br>**Artifact (if Known):** Sistema de chatbot.<br>**Response:** El chatbot debe responder a la consulta del usuario de manera precisa y oportuna.<br>**Response Measure:** El tiempo de respuesta del chatbot debe ser inferior a 5 segundos y la precisión de las respuestas superior al 90%.|
| **Questions:**                     | ¿Cómo se garantiza que el chatbot proporcione respuestas precisas?<br>¿Qué mecanismos se utilizan para mejorar la interacción del usuario con el chatbot? |
| **Issues:**                        | La necesidad de mantener la calidad de las respuestas mientras se maneja un alto volumen de consultas. |

## 4.2. Strategic-Level Domain-Driven Design

### 4.2.1. EventStorming

En el contexto de AgroTech Innovators, un proyecto que combina tecnologías avanzadas como IoT y chatbots inteligentes para optimizar las prácticas agrícolas, es crucial mapear y entender a fondo los procesos que sustentan la plataforma. Para lograrlo, utilizaremos la técnica de EventStorming, una metodología colaborativa que nos permitirá desglosar y visualizar de manera detallada todos los eventos clave dentro de nuestro dominio de negocio.

**4.2.1.1. Unstructured Exploration (Exploración No Estructurada)**

Identificaremos todos los eventos relevantes en "AgroTech Innovators", como "Sensor Activado" o "Respuesta del Chatbot Generada", mediante una lluvia de ideas con el equipo. Este paso nos permitirá capturar una visión completa de los eventos que ocurren en el sistema sin preocuparse aún por su secuencia.

**4.2.1.2. Timelines (Líneas de Tiempo)**

Organizaremos los eventos identificados en una línea de tiempo que refleje el flujo lógico del sistema, comenzando por el "happy path". Esto nos permitirá visualizar cómo los eventos se desarrollan cronológicamente en la plataforma, desde la activación de sensores hasta la asistencia brindada por el chatbot.


**4.2.1.3. Paint Points (Puntos de Dolor)**

Revisaremos la línea de tiempo para identificar posibles cuellos de botella o problemas, como demoras en la respuesta del chatbot o fallos en la conectividad de los sensores. Esto nos ayudará a detectar y priorizar las áreas del sistema que necesitan optimización.


**4.2.1.4. Pivotal Points (Puntos Clave)**

Identificamos eventos críticos que marcan un cambio importante en el proceso, como la transición de la recolección de datos a la generación de recomendaciones por el chatbot. Estos puntos nos permitirán dividir el flujo de trabajo en fases claramente definidas.


**4.2.1.5. Commands (Comandos)**

Definiremos los comandos necesarios para desencadenar los eventos en AgroTech Innovators, como "Enviar Datos" o "Generar Recomendación". Estos comandos representan las acciones que impulsan el flujo de eventos en el sistema.


**4.2.1.6. Policies (Políticas)**

Identificaremos políticas de automatización que permitan ejecutar comandos automáticamente cuando ocurren ciertos eventos, como "Enviar Alerta" después de detectar una anomalía en los datos del cultivo. Esto nos ayudará a automatizar procesos y mejorar la eficiencia operativa.


**4.2.1.7. Read Models (Modelos de Lectura)**

Definiremos los modelos de lectura que los usuarios utilizarán para tomar decisiones, como dashboards que muestran los datos de los sensores IoT o el historial de interacciones con el chatbot. Estos modelos asegurarán que los usuarios tengan acceso a la información necesaria de manera clara y precisa.


**4.2.1.8. External Systems (Sistemas Externos)**

Identificaremos e incorporaremos sistemas externos que interactúan con AgroTech Innovators, como APIs de terceros para obtener datos meteorológicos o bases de datos externas que almacenan información adicional sobre los cultivos. Esto nos permitirá entender las dependencias externas y su impacto en el sistema.


**4.2.1.9. Aggregates (Agregados)**

Agruparemos eventos y comandos relacionados en agregados que representen entidades clave dentro del sistema, como "Cultivo", "Sensor" o "Usuario". Esto nos permitirá organizar el sistema en unidades manejables y coherentes.


**4.2.1.10. Bounded Contexts (Contextos Delimitados)**

Identificaremos los contextos delimitados en el sistema, agrupando agregados relacionados. Esto nos permitirá definir límites claros dentro del sistema, como "Gestión de Sensores" o "Interacción con el Chatbot", asegurando la coherencia y facilitando el desarrollo y mantenimiento del sistema.


### 4.2.2. Candidate Context Discovery

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282134832922759240/image.png?ex=66de409d&is=66dcef1d&hm=4acea4ce1d785b35c651b850db94ac731a370a04466c2768b14133513529de24&"/>
</div>

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282134947867394108/image.png?ex=66de40b8&is=66dcef38&hm=4cf9ca8183bbe38014d7165465b5d5fa0e250f0892d1418c72479e6fe7834663&"/>
</div>

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282134948261793812/image.png?ex=66de40b8&is=66dcef38&hm=9f379fa5d8430c4ea058e0319987ed12c77f0bf36c68cbff91194b792d3fba36&"/>
</div>

### 4.2.3. Domain Message Flows Modeling

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282135068269088809/image.png?ex=66de40d5&is=66dcef55&hm=9a3779d49a4706b5dd0e5645fe522d7346a1abfff53f8cb3aefa5acd8db741c3&"/>
</div>

### 4.2.4. Bounded Context Canvases

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282135289434996796/image.png?ex=66de4109&is=66dcef89&hm=27077886af711b62ed46d0f4dbb10eb9230ce1835a2d669e3ccea126b0dfbb23&"/>
</div>

### 4.2.5. Context Mapping

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282135499221368903/image.png?ex=66de413b&is=66dcefbb&hm=6b83e33cb817c1fe361c361964704a8fec56b28fd85f8567d80fb483331ca97f&"/>
</div>


## 4.3. Software Architecture

En esta sección mostraremos los diagramas C4 donde se visualiza la arquitectura de nuestra solución.

### 4.3.1. Software Architecture System Landscape Diagram

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1279653231277899796/arqui1.png?ex=66d9d6b1&is=66d88531&hm=d30e990240f1d9a68c447304ca2eb132a9187a5a520b0e299c41c01176153e8b&"/>
</div>

### 4.3.2. Software Architecture Context Level Diagrams

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1279653231835873370/arqui2.png?ex=66d9d6b1&is=66d88531&hm=df2ccead1e550866cf3a3aa8215377133b4ef0af560b42199d29e2f74c280334&"/>
</div>

### 4.3.3. Software Architecture Container Level Diagrams

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1279653232519675934/arqui3.png?ex=66d9d6b1&is=66d88531&hm=c918493a09b3ced995b3f810d0a5913d293f84d5768147533a00854f475ec9ce&"/>
</div>

### 4.3.4. Software Architecture Deployment Diagrams

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1279653230422392832/arqui4.png?ex=66d9d6b0&is=66d88530&hm=fec0f0fee9a5c869b9a218e9961d48af7034e78146600af9ebe6bd684f054803&"/>
</div>

# Conclusiones

- A través de la descripción de la solución se establecen las bases para comprender cómo la tecnología IoT y los chatbots pueden optimizar la producción agrícola y resolver problemáticas clave para los usuarios, posicionando la propuesta de valor de manera sólida.
<br>

- La evaluación de competidores, junto con la creación de user personas y mapas de empatía, permite entender mejor las necesidades de los segmentos objetivo y ofrecer una solución diferenciada que no solo responde a esas demandas, sino que también se adapta a distintos niveles de experticia en el manejo de cultivos.
<br>

- La elaboración de historias de usuario, junto con el mapeo de escenarios "As-is" y "To-be", facilita la transición de los usuarios desde su estado actual hacia uno optimizado mediante el uso de la plataforma, reflejando una visión clara y detallada de cómo evolucionará su experiencia.
<br>

- El enfoque en el diseño estratégico del software, a través de prácticas como el "Attribute-Driven Design" y el "Domain-Driven Design", asegura que la solución no solo cumplirá con las funcionalidades principales, sino que también será adaptable, escalable y eficiente en términos de calidad del sistema.

# Bibliografía

Arbaiza, C. (2022). Internet de las cosas (iot) en un sistema autónomo de riego por goteo y el estrés hídrico en las zonas agrícolas, Perú 2022. Recuperado de https://hdl.handle.net/20.500.12952/7071 [Consulta: 06/09/2024]
<br>

Belupú, C. (2023). Propuesta de una plataforma de agricultura inteligente basada en IoT para el monitoreo de las condiciones climáticas del cultivo de banano. Universidad de Piura. Recuperado de https://hdl.handle.net/11042/6143 [Consulta: 05/09/2024]
<br>

Castillo, M. (2021). LA AGRICULTURA PERUANA, Situación Post COVID-19 y Perspectivas. Recuperado de https://library.fes.de/pdf-files/bueros/peru/18971.pdf [Consulta: 06/09/2024]
<br>

# Anexos

<div align="center">
    <img src="https://cdn.discordapp.com/attachments/1278210566904873047/1282169552515502142/logo.png?ex=66de60f2&is=66dd0f72&hm=6f8233e66a06b2ff475fc76e874da62b91f43a89349bbc448c871d72d9d12d0f&" alt="logo" style="margin-bottom: 5px;" width="500"/>
<div>
