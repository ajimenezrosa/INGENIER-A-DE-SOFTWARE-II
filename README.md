
# INGENIERÍA DE SOFTWARE II  
**Profesor:** José Alejandro Jiménez Rosa  
**Universidad Católica Santo Domingo**  
**Cuatrimestre:** Mayo - Agosto 2025  
---
#### ***Indice***

- [UNIDAD 1: INTRODUCCIÓN A LA INGENIERÍA DE SOFTWARE AVANZADA](#unidad1)
- [UNIDAD 2: ARQUITECTURA DE SOFTWARE Y ESTILOS ARQUITECTÓNICOS MODERNOS](#unidad2)
- [UNIDAD 3: DISEÑO DE SOFTWARE Y PRINCIPIOS DE BUENAS PRÁCTICAS](#unidad3)

<!-- ✍️ Unidades propuestas a desarrollar:
✅ Unidad 3: Diseño de Software y Patrones de Diseño
Principios de diseño modular

UML: Diagramas esenciales (casos de uso, clases, secuencia)

Patrones de diseño (GOF): Singleton, Factory, Observer, etc.

Buenas prácticas de diseño

Evaluación de diseño

✅ Unidad 4: Pruebas de Software y Automatización
Tipos de pruebas: unidad, integración, sistema, aceptación

Test-Driven Development (TDD)

Herramientas: JUnit, Selenium, Postman

Automatización de pruebas

✅ Unidad 5: Integración Continua y Entrega Continua (CI/CD)
Fundamentos y beneficios

Jenkins, GitHub Actions

Pipeline típico: build, test, deploy

Práctica: configurar un flujo CI/CD básico

✅ Unidad 6: Gestión de Proyectos con Scrum y Kanban
Roles: Product Owner, Scrum Master, Developers

Ceremonias: Sprint Planning, Daily, Review, Retrospective

Artefactos: Product Backlog, Sprint Backlog, Burndown Chart

Kanban vs Scrum

Herramientas: Jira, Trello

✅ Unidad 7: Seguridad en el Desarrollo de Software (Secure SDLC)
OWASP Top 10

Autenticación y autorización

Validación de entrada

Pruebas de seguridad

Integración de seguridad en DevOps (DevSecOps)

✅ Unidad 8: Mantenimiento de Software y Calidad Técnica
Tipos de mantenimiento

Refactorización

Métricas de calidad

Control de versiones y documentación
 -->


---

## UNIDAD 1: INTRODUCCIÓN A LA INGENIERÍA DE SOFTWARE AVANZADA<a name="unidad1"></a>

### Objetivos de la unidad:

* Comprender los retos modernos del desarrollo de software.
* Identificar las diferencias entre metodologías tradicionales y modernas.
* Familiarizarse con conceptos fundamentales como DevOps, CI/CD y Clean Code.

---

### 1.1 ¿Qué es la Ingeniería de Software Avanzada?

La Ingeniería de Software Avanzada estudia las prácticas, principios y herramientas utilizadas en entornos de desarrollo modernos para crear software robusto, escalable y mantenible. A diferencia de la Ingeniería de Software I, que se enfoca en fundamentos, esta asignatura aborda soluciones reales, automatizadas y colaborativas.

### 1.2 Evolución del Ciclo de Vida del Software

El ciclo de vida tradicional (análisis → diseño → codificación → prueba → mantenimiento) ha evolucionado a modelos iterativos que permiten retroalimentación continua. Las empresas modernas emplean marcos ágiles y pipelines de integración continua para adaptarse al cambio.

### 1.3 Introducción a Metodologías Ágiles y DevOps

* **Ágil:** Fomenta entregas frecuentes, colaboración con el cliente y adaptabilidad.
* **Scrum:** Marco de trabajo que organiza el desarrollo en "sprints".
* **DevOps:** Práctica que une desarrollo (Dev) y operaciones (Ops), enfocándose en automatización, entrega continua y monitoreo.

### 1.4 Principios de Diseño: SOLID y Clean Code

* **SOLID:** Conjunto de principios para diseñar software orientado a objetos que sea más comprensible, flexible y mantenible.

  * SRP: Principio de Responsabilidad Única
  * OCP: Principio Abierto/Cerrado
  * LSP: Principio de Sustitución de Liskov
  * ISP: Principio de Segregación de Interfaces
  * DIP: Principio de Inversión de Dependencias

* **Clean Code:** Se refiere a escribir código que sea:

  * Legible y sencillo.
  * Fácil de mantener.
  * Bien estructurado.
  * Basado en buenas prácticas.

### 1.5 Introducción al Desarrollo Colaborativo y Herramientas

El desarrollo moderno no se hace de forma aislada. Se requiere colaboración y control de versiones:

* **Git y GitHub:** Para gestionar cambios y colaboración.
* **Jira:** Para planificación de tareas y sprints.
* **Jenkins / GitHub Actions:** Para pipelines de integración y entrega continua.
* **Docker:** Para estandarizar entornos de desarrollo.

---

## Evaluación del Capítulo: 15 Preguntas Tipo Test
# Ingeniería de Software II  
**Profesor:** José Alejandro Jiménez Rosa  
**Universidad Católica Santo Domingo**  
**Cuatrimestre:** Mayo - Agosto 2025  

## Unidad 1: Introducción a la Ingeniería de Software Avanzada  
### Evaluación del Capítulo – Respuestas

---
**1. ¿Cuál metodología se basa en la entrega incremental y continua de software?**  
✅ **Respuesta:** Ágil  
💡 *Ágil promueve entregas frecuentes e incrementales, fomentando la retroalimentación y la mejora continua.*

---

**2. ¿Qué herramienta se usa comúnmente para integración continua?**  
✅ **Respuesta:** Jenkins  
💡 *Jenkins permite implementar pipelines CI/CD para automatizar pruebas e implementaciones.*

---

**3. ¿Cuál es un principio de SOLID?**  
✅ **Respuesta:** Principio de Responsabilidad Única (SRP)  
💡 *Establece que una clase debe tener una sola razón para cambiar.*

---

**4. "Clean Code" significa:**  
✅ **Respuesta:** Código legible, mantenible y basado en buenas prácticas  
💡 *Facilita la comprensión y el mantenimiento del código.*

---

**5. ¿Cuál no es un rol técnico dentro de un equipo de desarrollo?**  
✅ **Respuesta:** Cliente  
💡 *El cliente aporta requisitos, pero no participa directamente en el desarrollo técnico.*

---

**6. ¿Cuál es la diferencia principal entre Waterfall y Agile?**  
✅ **Respuesta:** Waterfall es secuencial; Agile es iterativo y flexible  
💡 *Agile permite adaptarse al cambio; Waterfall no.*

---

**7. ¿Qué herramienta permite versionar y colaborar en código?**  
✅ **Respuesta:** Git  
💡 *Git gestiona versiones y permite colaboración distribuida en proyectos de software.*

---

**8. ¿Qué permite un pipeline CI/CD?**  
✅ **Respuesta:** Automatizar pruebas e implementación continua de software  
💡 *Optimiza el flujo de desarrollo desde el código hasta producción.*

---

**9. DevOps busca:**  
✅ **Respuesta:** Integrar desarrollo y operaciones mediante automatización y colaboración  
💡 *Promueve entregas rápidas y confiables.*

---

**10. ¿Cuál no es parte del ciclo de vida del software?**  
✅ **Respuesta:** Facturación  
💡 *La facturación no forma parte directa del ciclo de vida del software.*

---

**11. ¿Quién gestiona la planificación del sprint?**  
✅ **Respuesta:** Scrum Master junto al equipo y el Product Owner  
💡 *Scrum fomenta la planificación colaborativa.*

---

**12. ¿Qué caracteriza al principio de abierto/cerrado?**  
✅ **Respuesta:** Las clases deben estar abiertas a extensión pero cerradas a modificación  
💡 *Esto permite extender funcionalidades sin alterar el código base.*

---

**13. ¿Qué significa que un software sea mantenible?**  
✅ **Respuesta:** Puede modificarse fácilmente sin introducir errores  
💡 *La mantenibilidad es esencial para la evolución del software.*

---

**14. ¿Qué es Jira?**  
✅ **Respuesta:** Una herramienta para la gestión de proyectos y seguimiento de tareas  
💡 *Jira permite organizar y planificar el trabajo en metodologías ágiles.*

---

**15. ¿Qué es una "user story" en Scrum?**  
✅ **Respuesta:** Una descripción breve de una funcionalidad desde la perspectiva del usuario  
💡 *Ayuda a enfocarse en el valor que se entrega al cliente.*

---

## Lecturas y Recursos Sugeridos

* Sommerville, *Software Engineering*, 10ma Ed., Capítulo 1 y 2.
* Atlassian CI/CD: [https://www.atlassian.com/continuous-delivery](https://www.atlassian.com/continuous-delivery)
* Documentación de GitHub Actions: [https://docs.github.com/actions](https://docs.github.com/actions)
* Video: Agile vs Waterfall (YouTube)

---
# 



---

## UNIDAD 2: ARQUITECTURA DE SOFTWARE Y ESTILOS ARQUITECTÓNICOS MODERNOS<a name="unidad2"></a>

### Objetivos de la Unidad
- Comprender los principios de diseño de arquitecturas escalables y sostenibles.  
- Distinguir entre los principales estilos arquitectónicos modernos: Monolítico, MVC, Microservicios y Serverless.  
- Analizar ventajas, desventajas y casos de uso de cada enfoque.  
- Conocer patrones de diseño relacionados con arquitectura.  
- Introducir buenas prácticas en el diseño de sistemas distribuidos.

---

### 2.1 ¿Qué es la Arquitectura de Software?

La **arquitectura de software** es la estructura fundamental de un sistema, representada por sus componentes, sus relaciones, y las decisiones de diseño y evolución. Define cómo se organiza y se comunica un sistema.

> 💡 *Una buena arquitectura facilita el mantenimiento, la escalabilidad y la calidad del software a largo plazo.*

---

### 2.2 Principios de una Buena Arquitectura

- **Separación de responsabilidades**
- **Modularidad**
- **Escalabilidad**
- **Mantenibilidad**
- **Desacoplamiento**

---

### 2.3 Estilos Arquitectónicos

#### ➤ Monolítica
- Toda la funcionalidad se encuentra en una única base de código.
- **Ventaja:** Simplicidad inicial y despliegue unificado.
- **Desventaja:** Dificultad para escalar por módulos o equipos independientes.

#### ➤ MVC (Modelo-Vista-Controlador)
- Separación entre lógica de negocio (Modelo), presentación (Vista) y flujo de interacción (Controlador).
- Muy común en aplicaciones web y móviles.

#### ➤ Microservicios
- Divide el sistema en servicios pequeños, independientes y desplegables por separado.
- Usan APIs para comunicarse (REST o gRPC).
- **Ventajas:** Escalabilidad horizontal, despliegue independiente.
- **Desventajas:** Complejidad en orquestación, monitoreo y comunicación.

#### ➤ Serverless
- El código se ejecuta como funciones (FaaS), administradas por el proveedor cloud.
- No se gestionan servidores directamente.
- Útil para cargas variables, automatización, procesamiento de eventos.

---

### 2.4 Patrones de Arquitectura Comunes

- **Layered (por capas)**  
- **Event-driven**  
- **CQRS (Command Query Responsibility Segregation)**  
- **Microkernel**

---

### 2.5 Herramientas y Tecnologías Comunes

| Herramienta        | Propósito                                           |
|--------------------|-----------------------------------------------------|
| Docker             | Empaquetado de componentes                          |
| Kubernetes         | Orquestación de microservicios                      |
| AWS Lambda         | Serverless                                          |
| Spring Boot        | Creación de microservicios en Java                  |
| .NET Core          | Creación de microservicios en C#                    |
| API Gateway        | Gestión de entrada a microservicios                |
| Istio / Linkerd    | Service Mesh: seguridad, tráfico y monitoreo       |

---



## Evaluación del Capítulo: 2 Preguntas Tipo Test
1. **¿Cuál es el principal objetivo de la arquitectura de software?**  
<!-- ✅ **Respuesta:** Organizar los componentes y decisiones estructurales del sistema.  
💡 *Define cómo el sistema es construido y evolucionado.* -->

2. **¿Qué estilo arquitectónico divide la app en Modelo, Vista y Controlador?**  
<!-- ✅ **Respuesta:** MVC  
💡 *Organiza la aplicación en capas separadas de lógica.* -->

3. **¿Cuál no es una característica de los microservicios?**  
<!-- ✅ **Respuesta:** Despliegue conjunto de todos los módulos  
💡 *Cada microservicio se despliega por separado.* -->

4. **¿Qué permite Docker en una arquitectura moderna?**  
<!-- ✅ **Respuesta:** Empaquetar aplicaciones con sus dependencias  
💡 *Asegura portabilidad y consistencia.* -->

5. **¿Qué estilo arquitectónico se adapta mejor a funciones de corta duración sin servidor?**  
<!-- ✅ **Respuesta:** Serverless  
💡 *Ideal para procesos basados en eventos y bajo demanda.* -->

6. **¿Qué patrón separa comandos de consultas?**  
<!-- ✅ **Respuesta:** CQRS  
💡 *Optimiza rendimiento y escalabilidad.* -->

7. **¿Cuál no es una ventaja de los microservicios?**  
<!-- ✅ **Respuesta:** Simplicidad operativa  
💡 *Requiere herramientas avanzadas de monitoreo y orquestación.* -->

8. **¿Cuál patrón se basa en la reacción a eventos?**  
<!-- ✅ **Respuesta:** Event-driven  
💡 *Usado en sistemas asincrónicos como mensajería.* -->

9. **¿Qué herramienta orquesta contenedores a gran escala?**  
<!-- ✅ **Respuesta:** Kubernetes  
💡 *Administra despliegue, escalado y salud de contenedores.* -->

10. **¿Qué define una arquitectura por capas?**  
<!-- ✅ **Respuesta:** Separación de presentación, lógica y datos  
💡 *Mejora el mantenimiento y pruebas.* -->

11. **¿Cuál de las siguientes no es una ventaja del modelo monolítico?**  
<!-- ✅ **Respuesta:** Escalabilidad independiente por módulo  
💡 *El monolito requiere escalar todo el sistema.* -->

12. **¿Qué permite un Service Mesh?**  
<!-- ✅ **Respuesta:** Control del tráfico entre servicios  
💡 *Mejora la observabilidad y seguridad.* -->

13. **¿Qué herramienta es más usada para crear microservicios en Java?**  
<!-- ✅ **Respuesta:** Spring Boot  
💡 *Framework ligero y modular.* -->

14. **¿Qué servicio permite ejecutar funciones sin servidor en la nube de Amazon?**  
<!-- ✅ **Respuesta:** AWS Lambda  
💡 *Servicio serverless de Amazon.* -->

15. **¿Qué significa una arquitectura desacoplada?**  
<!-- ✅ **Respuesta:** Componentes independientes entre sí  
💡 *Facilita cambios y mantenimiento.* -->

---

### Lecturas y Recursos Sugeridos

- Bass, L., Clements, P., Kazman, R. *Software Architecture in Practice*  
- Fowler, M. *Patterns of Enterprise Application Architecture*  
- [Documentación oficial de Kubernetes](https://kubernetes.io/docs/)  
- [Microservices vs Monolithic (YouTube)](https://www.youtube.com/results?search_query=microservices+vs+monolithic)  
- [What is Serverless? - Serverless Blog](https://www.serverless.com/blog/what-is-serverless)

---
# 


### INGENIERÍA DE SOFTWARE II

**Profesor:** José Alejandro Jiménez Rosa  
**Universidad Católica Santo Domingo**  
**Cuatrimestre:** Mayo - Agosto 2025

---

## UNIDAD 3: DISEÑO DE SOFTWARE Y PATRONES DE DISEÑO

### Objetivos de la unidad:

- Comprender los principios del diseño modular y reutilizable.
- Aplicar diagramas de UML para modelar software.
- Identificar y aplicar patrones de diseño comunes.
- Evaluar la calidad de un diseño software.

---

### 3.1 Principios de diseño de software

El diseño de software es la etapa en la que se define cómo se organizará internamente el sistema, guiado por principios que permiten lograr soluciones eficientes y mantenibles. Algunos principios clave:

- **Modularidad:** Dividir el sistema en componentes independientes.
- **Abstracción:** Ocultar detalles internos y mostrar solo lo necesario.
- **Cohesión:** Que cada módulo tenga una única responsabilidad clara.
- **Acomplamiento:** Minimizar la dependencia entre módulos.

> Un buen diseño permite cambios locales sin afectar todo el sistema.

---

### 3.2 Diagramas UML

**UML (Lenguaje Unificado de Modelado)** permite representar visualmente la estructura y comportamiento del sistema. Diagramas comunes:

- **Caso de Uso:** Describe funcionalidades desde la perspectiva del usuario.
- **Clases:** Muestra atributos, métodos y relaciones entre clases.
- **Secuencia:** Representa la interacción entre objetos en el tiempo.

> Ejemplo: Un sistema bancario puede tener casos de uso como "Transferir dinero" y "Consultar saldo".

---

### 3.3 Origen de los patrones de diseño

Los patrones de diseño fueron popularizados por el libro *Design Patterns: Elements of Reusable Object-Oriented Software* publicado en 1994 por el llamado *Gang of Four* (Erich Gamma, Richard Helm, Ralph Johnson y John Vlissides). Inspirados en la arquitectura de edificios (Alexander, 1977), los patrones de diseño se basan en la idea de capturar soluciones probadas y efectivas que puedan reutilizarse en diferentes contextos.

Al igual que en la arquitectura civil existen soluciones estandarizadas para puertas, ventanas o escaleras, en el software se identificaron patrones recurrentes que resuelven problemas de comunicación entre objetos, creación de instancias o estructura de clases.

---

### 3.4 Patrones de diseño (GOF) y su aplicación

Los patrones GOF están organizados en tres categorías:

#### 1. Creacionales (gestión de instancias de objetos)

- **Singleton:** Asegura que una clase tenga una sola instancia. Muy usado para clases de configuración, logging o acceso a recursos compartidos.
- **Factory Method:** Permite delegar la creación de objetos a subclases. Se aplica cuando no se conoce la clase exacta del objeto hasta tiempo de ejecución.
- **Abstract Factory:** Proporciona una interfaz para crear familias de objetos relacionados.
- **Builder:** Separa la construcción compleja de objetos paso a paso.
- **Prototype:** Permite copiar objetos existentes sin depender de su clase exacta.

#### 2. Estructurales (organizan relaciones entre clases)

- **Adapter:** Permite que dos interfaces incompatibles trabajen juntas.
- **Composite:** Representa jerarquías de objetos (como árboles) donde los elementos individuales y compuestos son tratados de forma uniforme.
- **Proxy:** Controla el acceso a un objeto mediante un intermediario.
- **Decorator:** Agrega funcionalidades a un objeto en tiempo de ejecución sin modificar su clase original.
- **Facade:** Proporciona una interfaz simplificada a un conjunto de subsistemas.

#### 3. De comportamiento (controlan el flujo de la comunicación)

- **Observer:** Permite que objetos suscriptores reciban notificaciones automáticas ante cambios de otro objeto.
- **Strategy:** Permite cambiar el algoritmo usado por un objeto sin modificarlo.
- **Command:** Encapsula una petición como un objeto.
- **State:** Permite que un objeto cambie su comportamiento cuando cambia su estado interno.
- **Template Method:** Define la estructura de un algoritmo dejando algunos pasos a las subclases.

> Ejemplo: El patrón Observer se usa en interfaces gráficas donde un cambio de estado (como seleccionar un elemento) notifica a múltiples componentes (como etiquetas, menús, paneles).

---

### 3.5 Impacto de los patrones de diseño en la industria

Los patrones han transformado la forma en que los desarrolladores resuelven problemas:

- Fomentan la **reutilización** de soluciones efectivas.
- Promueven la **comunicación clara** entre equipos al usar un vocabulario compartido.
- Mejoran la **mantenibilidad** al reducir el acoplamiento entre componentes.
- Se han integrado en herramientas, marcos de trabajo y arquitecturas modernas.

En entrevistas técnicas, se evalúa frecuentemente el conocimiento de patrones como parte de las habilidades de diseño profesional.

---

### 3.6 Buenas prácticas de diseño

- Usar nombres claros y coherentes.
- Seguir los principios SOLID.
- Evitar la duplicación de código.
- Diseñar primero la interfaz y luego la implementación.
- Documentar las decisiones de diseño.
- Aplicar patrones solo cuando aportan claridad y no complejidad innecesaria.

---

### 3.7 Evaluación del diseño software

Para evaluar la calidad de un diseño se consideran:

- **Claridad:** ¿Se entiende fácilmente?
- **Flexibilidad:** ¿Permite cambios futuros sin mucho esfuerzo?
- **Reutilización:** ¿Se pueden usar partes del diseño en otros proyectos?
- **Cumplimiento de requisitos:** ¿El diseño responde a las necesidades del usuario?

> Un diseño bien estructurado es clave para el éxito a largo plazo del software.

---

## Evaluación del Capítulo: 15 Preguntas Tipo Test

1. ¿Qué principio busca dividir el sistema en partes independientes?  
2. Un ejemplo de acoplamiento bajo es:  
3. El diagrama UML que representa la interacción entre objetos es:  
4. El patrón Singleton se usa para:  
5. La modularidad ayuda a:  
6. El patrón Observer sirve para:  
7. El patrón Adapter se clasifica como:  
8. Un buen diseño debe tener:  
9. El principio de Cohesión implica:  
10. El diagrama de clases muestra:  
11. El patrón Strategy permite:  
12. Factory Method es un patrón de tipo:  
13. La evaluación del diseño debe verificar:  
14. Un beneficio de los patrones de diseño es:  
15. Diseñar primero la interfaz ayuda a:

---
 
## ✅ Evaluación del Capítulo: 15 Preguntas Tipo Test con Justificación

1. **¿Qué principio busca dividir el sistema en partes independientes?**  
   - A) Acoplamiento  
   - B) Herencia  
   - ✅ C) Modularidad  
   - D) Encapsulamiento  
   **Justificación:** La modularidad permite dividir un sistema en partes independientes, facilitando su mantenimiento, escalabilidad y reutilización.

2. **Un ejemplo de acoplamiento bajo es:**  
   - A) Una clase que usa directamente otra clase concreta  
   - ✅ B) Una clase que depende de una interfaz  
   - C) Dos clases que comparten variables globales  
   - D) Una clase que hereda de múltiples clases  
   **Justificación:** Acoplamiento bajo se logra cuando una clase depende de abstracciones (interfaces), lo que la hace menos dependiente de implementaciones concretas.

3. **El diagrama UML que representa la interacción entre objetos es:**  
   - A) Diagrama de clases  
   - ✅ B) Diagrama de secuencia  
   - C) Diagrama de casos de uso  
   - D) Diagrama de paquetes  
   **Justificación:** El diagrama de secuencia muestra cómo los objetos interactúan en el tiempo, representando el flujo de mensajes entre ellos.

4. **El patrón Singleton se usa para:**  
   - A) Crear muchas instancias de una clase  
   - ✅ B) Garantizar que solo exista una instancia  
   - C) Heredar de múltiples clases  
   - D) Agregar interfaces en tiempo de ejecución  
   **Justificación:** Singleton restringe la creación de objetos a una sola instancia, útil para configuraciones, logging y acceso global controlado.

5. **La modularidad ayuda a:**  
   - A) Hacer el sistema más lento  
   - B) Duplicar código  
   - ✅ C) Separar responsabilidades  
   - D) Aumentar el acoplamiento  
   **Justificación:** La modularidad organiza el sistema en unidades con funciones específicas, facilitando el mantenimiento y la evolución del software.

6. **El patrón Observer sirve para:**  
   - A) Ejecutar algoritmos en paralelo  
   - ✅ B) Notificar múltiples objetos sobre un cambio  
   - C) Convertir interfaces incompatibles  
   - D) Asegurar la herencia múltiple  
   **Justificación:** Observer permite la suscripción de múltiples objetos a eventos generados por otro objeto (el sujeto), promoviendo la desacoplación.

7. **El patrón Adapter se clasifica como:**  
   - A) Creacional  
   - ✅ B) Estructural  
   - C) De comportamiento  
   - D) De control  
   **Justificación:** Adapter adapta una interfaz a otra para permitir compatibilidad entre clases, siendo un patrón que estructura cómo interactúan las clases.

8. **Un buen diseño debe tener:**  
   - A) Muchas dependencias  
   - ✅ B) Bajo acoplamiento y alta cohesión  
   - C) Código duplicado para seguridad  
   - D) Todas las clases en un solo archivo  
   **Justificación:** Un diseño sólido busca mantener las clases independientes entre sí (bajo acoplamiento) y enfocadas en tareas específicas (alta cohesión).

9. **El principio de Cohesión implica:**  
   - A) Que una clase tenga muchas funciones sin relación  
   - ✅ B) Que una clase tenga una responsabilidad clara  
   - C) Que una clase dependa de muchas otras  
   - D) Que una clase use variables globales  
   **Justificación:** La cohesión mide qué tan relacionadas están las tareas de una clase. Alta cohesión implica claridad y propósito único.

10. **El diagrama de clases muestra:**  
    - A) Reglas de negocio  
    - B) Código fuente  
    - ✅ C) Atributos, métodos y relaciones  
    - D) Interacciones temporales  
    **Justificación:** El diagrama de clases representa la estructura estática del sistema: qué atributos y métodos tiene cada clase y cómo se relacionan.

11. **El patrón Strategy permite:**  
    - ✅ A) Cambiar el algoritmo sin modificar la clase  
    - B) Crear árboles de objetos  
    - C) Heredar de varias estrategias  
    - D) Eliminar interfaces  
    **Justificación:** Strategy encapsula algoritmos intercambiables dentro de objetos, facilitando la selección del comportamiento en tiempo de ejecución.

12. **Factory Method es un patrón de tipo:**  
    - A) Estructural  
    - ✅ B) Creacional  
    - C) De comportamiento  
    - D) De flujo  
    **Justificación:** Factory Method es un patrón creacional porque define cómo instanciar objetos sin especificar su clase concreta.

13. **La evaluación del diseño debe verificar:**  
    - A) Velocidad del servidor  
    - ✅ B) Claridad, flexibilidad y reutilización  
    - C) Tiempos de compilación  
    - D) Cantidad de líneas de código  
    **Justificación:** Evaluar un diseño implica revisar si es claro para otros desarrolladores, flexible a cambios y si sus componentes se pueden reutilizar.

14. **Un beneficio de los patrones de diseño es:**  
    - A) Obligar a usar programación funcional  
    - B) Reducir la velocidad del sistema  
    - ✅ C) Reutilizar soluciones comprobadas  
    - D) Aumentar la complejidad del diseño  
    **Justificación:** Los patrones son soluciones genéricas a problemas comunes. Reutilizarlos ahorra tiempo y reduce errores al aplicar buenas prácticas.

15. **Diseñar primero la interfaz ayuda a:**  
    - A) Olvidar los detalles internos  
    - B) Empezar a codificar más rápido  
    - ✅ C) Separar lo que hace un módulo de cómo lo hace  
    - D) Repetir código innecesario  
    **Justificación:** Al diseñar primero la interfaz (contrato), se define el comportamiento esperado sin comprometerse con una implementación específica.



## Lecturas y Recursos Sugeridos

- *Design Patterns: Elements of Reusable Object-Oriented Software* (Gamma, Helm, Johnson, Vlissides)  
- Documentación UML: [https://www.uml-diagrams.org/](https://www.uml-diagrams.org/)  
- Catálogo de patrones de diseño: [https://refactoring.guru/](https://refactoring.guru/)  
- Video: "Patrones de Diseño explicados" (YouTube)  
- Curso recomendado: "Design Patterns in Java" en Udemy o Coursera

---

# UNIDAD 3: DISEÑO DE SOFTWARE Y PRINCIPIOS DE BUENAS PRÁCTICAS<a name="unidad3"></a>

## 3.1 Introducción al Diseño de Software

El diseño de software es una etapa clave del proceso de desarrollo, en la cual se definen las estructuras, componentes y patrones que darán forma a la solución final. Esta fase se basa en los requisitos previamente recopilados y busca garantizar que el software sea eficiente, mantenible, reutilizable y escalable.

El diseño actúa como un puente entre el análisis de requisitos y la codificación, permitiendo visualizar la solución en abstracto antes de escribir código. Además, facilita la comunicación entre los miembros del equipo y promueve la calidad desde las primeras etapas del desarrollo.

## 3.2 Objetivos del Diseño de Software

- Traducir los requisitos en representaciones técnicas comprensibles.
- Establecer la estructura global del sistema.
- Promover la reutilización mediante patrones y componentes modulares.
- Minimizar la complejidad del sistema.
- Mejorar la mantenibilidad y escalabilidad del producto final.

## 3.3 Principios de Buen Diseño

### 3.3.1 Modularidad

Dividir el sistema en módulos o componentes independientes permite un desarrollo más organizado, pruebas más sencillas y mayor facilidad para realizar cambios o añadir nuevas funcionalidades.

### 3.3.2 Abstracción

Consiste en ocultar los detalles de implementación y mostrar solo lo necesario para el uso del componente o módulo. Esto facilita la comprensión y el mantenimiento del software.

### 3.3.3 Acoplamiento y Cohesión

- **Acoplamiento**: mide el grado de dependencia entre módulos. Se busca un **bajo acoplamiento**, donde los módulos se relacionen lo mínimo posible.
- **Cohesión**: mide el grado en que los elementos dentro de un módulo están relacionados entre sí. Se busca una **alta cohesión**, lo que indica que el módulo realiza una única tarea bien definida.

### 3.3.4 Separación de Responsabilidades

Cada componente debe tener una única responsabilidad bien definida. Este principio evita que un módulo realice tareas múltiples y facilita su comprensión y mantenimiento.

### 3.3.5 Principio de Abierto/Cerrado (Open/Closed)

Los módulos deben estar **abiertos para extensión** pero **cerrados para modificación**, permitiendo agregar nuevas funcionalidades sin cambiar el código existente.

## 3.4 Patrones de Diseño

Los patrones de diseño son soluciones probadas a problemas comunes en el desarrollo de software. Se clasifican principalmente en:

- **Patrones Creacionales**: controlan la creación de objetos (por ejemplo: Singleton, Factory Method).
- **Patrones Estructurales**: organizan clases y objetos (por ejemplo: Adapter, Decorator).
- **Patrones de Comportamiento**: definen la comunicación entre objetos (por ejemplo: Observer, Strategy).

Estos patrones mejoran la reutilización, flexibilidad y comprensión del código.

## 3.5 Herramientas y Modelos UML para el Diseño

El diseño se apoya en modelos y herramientas visuales como UML (Lenguaje Unificado de Modelado), que permiten representar diferentes aspectos del sistema:

- **Diagrama de clases**: estructura estática de las clases y sus relaciones.
- **Diagrama de secuencia**: interacción entre objetos a lo largo del tiempo.
- **Diagrama de componentes**: organización y dependencias de los módulos del sistema.
- **Diagrama de paquetes**: organización lógica del sistema en grupos de clases.

## 3.6 Evaluación del Diseño

Un buen diseño se evalúa considerando:

- Claridad y simplicidad.
- Cumplimiento de principios de diseño.
- Facilidad de mantenimiento y extensión.
- Uso adecuado de patrones y buenas prácticas.
- Documentación clara y comprensible.

## 3.7 Conclusión

El diseño de software es una disciplina que requiere conocimientos técnicos, visión sistémica y capacidad de abstracción. Aplicar principios de buen diseño y patrones reconocidos es fundamental para construir sistemas robustos, escalables y fáciles de mantener. Un diseño bien realizado es clave para el éxito a largo plazo del proyecto.

---

## Evaluación del Capítulo 3: 15 Preguntas Tipo Test

1. ¿Cuál es el objetivo principal del diseño de software?  
   ✅ **a) Traducir los requisitos en soluciones técnicas mantenibles**  
   💡 *El diseño busca convertir requisitos en una estructura organizada y comprensible para ser implementada eficientemente.*

2. ¿Qué principio busca dividir el sistema en partes pequeñas y manejables?  
   ✅ **b) Modularidad**  
   💡 *La modularidad permite crear componentes independientes y reutilizables.*

3. Un sistema con alto acoplamiento:  
   ✅ **c) Tiene componentes fuertemente dependientes entre sí**  
   💡 *El alto acoplamiento indica que los módulos están estrechamente vinculados, lo que dificulta el mantenimiento.*

4. La cohesión se refiere a:  
   ✅ **b) El grado en que los elementos dentro de un módulo están relacionados**  
   💡 *Una alta cohesión indica que un módulo tiene una única responsabilidad bien definida.*

5. ¿Qué principio se basa en ocultar detalles de implementación?  
   ✅ **a) Abstracción**  
   💡 *La abstracción se enfoca en mostrar solo lo esencial, ocultando lo complejo.*

6. ¿Qué representa un diagrama de clases en UML?  
   ✅ **a) Estructura estática del sistema y relaciones entre clases**  
   💡 *Los diagramas de clase son fundamentales para mostrar la arquitectura orientada a objetos.*

7. ¿Qué patrón pertenece a los patrones creacionales?  
   ✅ **a) Singleton**  
   💡 *Singleton controla la creación de una única instancia de una clase.*

8. ¿Cuál de los siguientes es un patrón estructural?  
   ✅ **b) Adapter**  
   💡 *Adapter permite que interfaces incompatibles trabajen juntas.*

9. ¿Cuál patrón es de comportamiento?  
   ✅ **c) Observer**  
   💡 *Observer define una dependencia uno a muchos entre objetos.*

10. ¿Qué principio indica que los módulos deben poder extenderse sin modificarse?  
    ✅ **b) Principio Abierto/Cerrado**  
    💡 *Este principio fomenta la extensión del comportamiento sin alterar el código fuente existente.*

11. ¿Qué herramienta se utiliza para representar la interacción entre objetos a lo largo del tiempo?  
    ✅ **a) Diagrama de secuencia**  
    💡 *Los diagramas de secuencia muestran el orden y flujo de mensajes entre objetos.*

12. ¿Qué patrón permite encapsular algoritmos en clases independientes?  
    ✅ **b) Strategy**  
    💡 *Strategy define una familia de algoritmos y los hace intercambiables.*

13. ¿Qué modelo UML muestra cómo se organizan y agrupan los componentes lógicamente?  
    ✅ **b) Diagrama de paquetes**  
    💡 *El diagrama de paquetes agrupa clases o componentes con funcionalidades comunes.*

14. ¿Cuál es una ventaja de aplicar patrones de diseño?  
    ✅ **a) Promueven soluciones reutilizables y probadas**  
    💡 *Los patrones ayudan a resolver problemas comunes de forma eficiente y estructurada.*

15. Diseñar primero la interfaz permite:  
    ✅ **b) Definir claramente los contratos entre módulos**  
    💡 *Una interfaz bien definida permite a los desarrolladores trabajar en paralelo y cumplir con especificaciones sin conocer la implementación.*





**Fin de la Unidad 3**




# 