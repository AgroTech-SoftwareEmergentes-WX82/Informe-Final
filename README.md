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
        <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149369808740163625/image.png"/>      
    </div>

    <div align=center>
        <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149370395296813166/image.png"/>
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
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Carlos Jesus Onofre Ruiz** <br> **TB1** <br> En las reuniones del proyecto, presenté y discutí el propósito del diseño a nivel estratégico, centrándome en cómo las entradas clave, como las historias de usuario, los escenarios de atributos de calidad y las restricciones, influyen en nuestras decisiones. | |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Carlos Jesus Onofre Ruiz** <br> **TB1** <br> Documenté de manera detallada y accesible todo el proceso de diseño estratégico, desde la definición del propósito hasta los refinamientos de los escenarios de atributos de calidad. Los reportes incluyeron explicaciones claras sobre cómo las historias de usuario y las restricciones guiaron nuestras decisiones arquitectónicas. | |

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
            <img src="" alt="Moreno Vergara, Johan Raúl" style="margin-bottom: 5px;" width="800"/>
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
            <img src="" alt="Wilfredo Futuri" style="margin-bottom: 5px;" width="800"/>
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
        -
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Conocimiento y habilidades</b>
        <br>
        - 
        </td>
    </tr>
</table>

## 1.2. Solution Profile

**Nombre del Producto:** 

**Descripción del Producto:** 

**Monetización:** 

### 1.2.1. Antecedentes y problemática



- **Who**



- **What**



- **Where**



- **When**



- **Why**



- **How**



- **How much**



<br>

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements



#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements



#### 1.2.2.4. Lean UX Canvas



<div align="center">
    <img src=""/>
</div>

## 1.3. Segmentos objetivos


# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. Empathy Mapping

### 2.3.4. As-is Scenario Mapping

## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories


## 3.3. Impact Mapping

## 3.4. Product Backlog


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

### 4.2.2. Candidate Context Discovery

### 4.2.3. Domain Message Flows Modeling

### 4.2.4. Bounded Context Canvases

### 4.2.5. Context Mapping

## 4.3. Software Architecture

### 4.3.1. Software Architecture System Landscape Diagram

### 4.3.2. Software Architecture Context Level Diagrams

### 4.3.3. Software Architecture Container Level Diagrams

### 4.3.4. Software Architecture Deployment Diagrams

# Conclusiones

# Bibliografía

# Anexos
