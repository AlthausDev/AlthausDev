<h1 align="center">Sam Althaus — Backend Software Developer</h1>

<p align="center">
  <b>Java · Clean Architecture · Enterprise Applications · Integrations</b><br>
  <i>Diseño modular, patrones con propósito, refactorización y código mantenible</i>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=althausdev&label=Profile%20views&color=0e75b6&style=flat" alt="Profile Views">
</p>

---

## Sobre mí

Soy desarrollador de software centrado principalmente en **backend con Java**, mantenimiento evolutivo, integraciones y refactorización de aplicaciones empresariales.

En mi trabajo diario desarrollo sobre sistemas existentes con **Java 8, Struts 2, JSP, Maven, Oracle y servicios SOAP**, trabajando también con **WSDL/XML, Apache CXF y JAXB**. El ciclo de entrega incluye testing con **JUnit y Mockito**, control de cobertura con **JaCoCo**, análisis de calidad con **SonarQube** y despliegues mediante pipelines ya establecidos.

Actualmente también estoy incorporando **Java 17** en el desarrollo de un nuevo componente sobre un framework corporativo basado en **Spring**.

Una parte importante de mi forma de trabajar está influida por **Clean Architecture de Robert C. Martin**: separar responsabilidades, controlar la dirección de las dependencias, aislar infraestructura y mantener la lógica importante lo menos acoplada posible a frameworks, persistencia o UI.

Uso patrones cuando resuelven un problema real. Prefiero una interfaz, un repositorio, una estrategia o una capa adicional porque existe una frontera que merece representarse, no porque una plantilla diga que debe estar ahí.

Buena parte de mi trabajo profesional no puede publicarse por razones de confidencialidad, así que GitHub recoge sobre todo **proyectos personales, laboratorios de aprendizaje y proyectos de formación**.

📎 [LinkedIn — Samuel Althaus](https://www.linkedin.com/in/samuelalthaus/)

---

## Stack profesional

| Área | Tecnologías |
|---|---|
| Backend | Java 8, Java 17, Struts 2, JSP |
| Integraciones | SOAP, WSDL, XML, Apache CXF, JAXB |
| Datos | SQL, Oracle, Named Queries |
| Build | Maven |
| Testing / calidad | JUnit, Mockito, SonarQube, JaCoCo |
| Control de versiones | Git, GitLab |
| Runtime / logging | JBoss, Log4j |
| Web | HTML, mantenimiento de JavaScript existente |
| Entorno de trabajo | STS / Eclipse, IntelliJ IDEA, VS Code, JIRA |
| Entrega | Jenkins sobre pipelines existentes de análisis y despliegue |

---

## Arquitectura y diseño

A lo largo de mis proyectos he aplicado distintos enfoques y patrones según el problema:

- **Clean Architecture** como criterio de separación y dirección de dependencias.
- **Repository** y **Service Layer** para aislar persistencia y casos de uso.
- **Factory** y **Strategy** cuando creación o comportamiento necesitan variar de forma explícita.
- **Command** y **Observer / data binding** en aplicaciones de escritorio.
- **Dependency Injection** para reducir acoplamiento y hacer sustituibles las dependencias.
- **MVC** y **MVVM** en proyectos donde encajan con la interfaz y el flujo de estado.
- Refactorización orientada a extraer responsabilidades reales, no simplemente a repartir código entre más clases.

La **arquitectura hexagonal** y los **microservicios** forman parte actualmente de mi estudio práctico; los trabajo en un laboratorio separado para entender sus límites y diferencias sin presentarlos como experiencia profesional consolidada.

---

## Otras tecnologías con experiencia práctica

A través de formación, prácticas y proyectos personales también he trabajado con **Spring Boot, C#/.NET, ASP.NET Core, WPF, Kotlin/Jetpack Compose, Angular/TypeScript, MongoDB, Firebase/Firestore, REST, Python y PowerShell**.

No todas forman parte de mi stack profesional habitual. Los repositorios muestran el contexto y el nivel con el que se ha utilizado cada una.

---

## Proyectos destacados

### DesireSync

Aplicación **local-first** para crear perfiles estructurados y comparar preferencias de forma privada, sin backend ni cuenta obligatoria.

Más allá de la UI en Angular, el proyecto está orientado a mantener el **dominio independiente del framework**, con persistencia abstraída, servicios de aplicación, estrategias, validadores, migraciones versionadas y contratos explícitos para identidad y tiempo.

[12-AffinityMatrix](https://github.com/AlthausDev/12-AffinityMatrix)

### WebSocket Chat

Chat en tiempo real desarrollado como proyecto de formación con **Java 21, Spring Boot, MongoDB, WebSocket/STOMP y Angular**.

El proyecto mantiene separadas las responsabilidades de protocolo, lógica y persistencia, evitando capas decorativas que no aporten una frontera real.

[04-WebSocketChat](https://github.com/AlthausDev/04-WebSocketChat)

### Hexagonal Microservices Lab

Laboratorio de aprendizaje en **Java 21 + Spring Boot + Docker** para estudiar arquitectura hexagonal, puertos y adaptadores, comunicación entre servicios y despliegues independientes mediante ejemplos pequeños y comprobables.

[12-HexagonalMicroservicesLab](https://github.com/AlthausDev/12-HexagonalMicroservicesLab)

### Architecturae Modularis Codex (AMC)

Arquitectura modular y reproducible para **Skyrim AE**, tratada como un sistema técnico: configuración versionada, perfiles reproducibles, automatización, documentación viva, portabilidad y trazabilidad.

[11-ArchitecturaeModularisCodex](https://github.com/AlthausDev/11-ArchitecturaeModularisCodex)

---

## Trayectoria técnica

Conservo también proyectos anteriores porque muestran de dónde viene parte de mi forma de trabajar:

- **The Pilgrim's Path** — Java, Spring Boot, MVC, Service Layer, Repository y múltiples modelos de persistencia.
- **Avilesa Bus Management System** — C#/.NET, WPF, MVVM, Command y persistencia CSV.
- **CookIes** — Android/Kotlin, Jetpack Compose, MVVM, Repository, Hilt y Firebase.
- **EcoLogTracking** — proyecto de prácticas en .NET orientado a logging centralizado, middleware, REST, persistencia y administración.

Los repositorios históricos no representan necesariamente mi stack actual: los mantengo como referencia de aprendizaje y evolución.

---

## Cómo trabajo

<pre>
Problema
  ↓
Entender el flujo y las responsabilidades
  ↓
Definir fronteras y contratos cuando aportan valor
  ↓
Implementar el cambio más pequeño y comprobable
  ↓
Tests y validación
  ↓
Refactorizar sin alterar comportamiento innecesariamente
  ↓
Calidad, trazabilidad y documentación útil
</pre>

No intento introducir patrones por el simple hecho de usarlos. **La arquitectura debe explicar el sistema, no esconderlo detrás de ceremonia.**

---

## Estadísticas

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=althausdev&show_icons=true&locale=es&layout=compact&theme=transparent" alt="Top Langs">
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=althausdev&theme=transparent" alt="Profile Summary">
</p>

---

## Licencia y atribución

El contenido original de este repositorio de perfil puede reutilizarse bajo la [licencia de atribución](LICENSE). Si reutilizas una parte sustancial, cita a **Sam Althaus / AlthausDev** y, cuando sea práctico, enlaza el repositorio original.

Los iconos, badges, marcas y recursos de terceros conservan sus propios derechos y licencias.
