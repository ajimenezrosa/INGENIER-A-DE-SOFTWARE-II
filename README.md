
# INGENIERÍA DE SOFTWARE II  
**Profesor:** José Alejandro Jiménez Rosa  
**Universidad Católica Santo Domingo**  
**Cuatrimestre:** Mayo - Agosto 2025  
---
#### ***Indice***

- [UNIDAD 1: INTRODUCCIÓN A LA INGENIERÍA DE SOFTWARE AVANZADA](#unidad1)
- [UNIDAD 2: ARQUITECTURA DE SOFTWARE Y ESTILOS ARQUITECTÓNICOS MODERNOS](#unidad2)
- [UNIDAD 3: DISEÑO DE SOFTWARE Y PRINCIPIOS DE BUENAS PRÁCTICAS](#unidad3)
- [UNIDAD 4: METODOLOGÍAS ÁGILES Y GESTIÓN DE PROYECTOS DE SOFTWARE](#capitulo4)
- [ UNIDAD 5: CONTROL DE CALIDAD Y PRUEBAS DE SOFTWARE](#unidad5)
- [UNIDAD 6: INTEGRACIÓN Y ENTREGA CONTINUA (CI/CD)](#unidad6)
- [UNIDAD 7: MANTENIMIENTO, EVOLUCIÓN Y REFACCIÓN DE SOFTWARE](#unidad7)

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


## Evaluación del Capítulo 3: Selección Múltiple con Respuestas y Justificación

1. ¿Cuál es el objetivo principal del diseño de software?  
a) Traducir los requisitos en soluciones técnicas mantenibles  
b) Realizar pruebas unitarias  
c) Programar funcionalidades  
d) Crear bases de datos  
<!-- ✅ **Respuesta correcta: a**  
💡 *El diseño de software convierte los requisitos funcionales y no funcionales en una estructura técnica lógica y sostenible que guiará el proceso de implementación.* -->

2. ¿Qué principio busca dividir el sistema en partes pequeñas y manejables?  
a) Acoplamiento  
b) Modularidad  
c) Abstracción  
d) Herencia  
<!-- ✅ **Respuesta correcta: b**  
💡 *La modularidad permite organizar el sistema en módulos independientes que facilitan el desarrollo, mantenimiento y pruebas.* -->

3. Un sistema con alto acoplamiento:  
a) Tiene módulos bien separados  
b) Presenta bajo nivel de dependencia  
c) Tiene componentes fuertemente dependientes entre sí  
d) Es más fácil de mantener  
<!-- ✅ **Respuesta correcta: c**  
💡 *El alto acoplamiento indica fuerte dependencia entre módulos, lo cual dificulta su mantenimiento y escalabilidad.* -->

4. La cohesión se refiere a:  
a) La dependencia entre módulos  
b) El grado en que los elementos dentro de un módulo están relacionados  
c) La relación entre clases  
d) La complejidad del código  
<!-- ✅ **Respuesta correcta: b**  
💡 *Alta cohesión implica que un módulo tiene una responsabilidad bien definida y enfocada, lo que mejora su calidad y reusabilidad.* -->

5. ¿Qué principio se basa en ocultar detalles de implementación?  
a) Abstracción  
b) Encapsulamiento  
c) Modularidad  
d) Polimorfismo  
<!-- ✅ **Respuesta correcta: a**  
💡 *La abstracción expone solo los aspectos esenciales de un módulo, ocultando detalles internos que no son relevantes para su uso.* -->

6. ¿Qué representa un diagrama de clases en UML?  
a) Estructura estática del sistema y relaciones entre clases  
b) Flujo de ejecución  
c) Casos de uso  
d) Interacción temporal  
<!-- ✅ **Respuesta correcta: a**  
💡 *El diagrama de clases muestra atributos, métodos y relaciones estáticas entre las clases del sistema.* -->

7. ¿Qué patrón pertenece a los patrones creacionales?  
a) Singleton  
b) Adapter  
c) Observer  
d) Strategy  
<!-- ✅ **Respuesta correcta: a**  
💡 *Singleton asegura que una clase tenga solo una instancia y proporciona un punto de acceso global a ella.* -->

8. ¿Cuál de los siguientes es un patrón estructural?  
a) Observer  
b) Adapter  
c) Factory Method  
d) Strategy  
<!-- ✅ **Respuesta correcta: b**  
💡 *Adapter permite que clases con interfaces incompatibles trabajen juntas adaptando su interfaz.* -->

9. ¿Cuál patrón es de comportamiento?  
a) Decorator  
b) Builder  
c) Observer  
d) Abstract Factory  
<!-- ✅ **Respuesta correcta: c**  
💡 *Observer define una relación de dependencia entre objetos para que cuando uno cambie, los demás sean notificados automáticamente.* -->

10. ¿Qué principio indica que los módulos deben poder extenderse sin modificarse?  
a) Principio de Responsabilidad Única  
b) Principio Abierto/Cerrado  
c) Principio de Sustitución de Liskov  
d) Principio de Inversión de Dependencia  
<!-- ✅ **Respuesta correcta: b**  
💡 *El principio abierto/cerrado promueve la extensión de funcionalidades mediante herencia o composición, sin alterar el código existente.* -->

11. ¿Qué herramienta se utiliza para representar la interacción entre objetos a lo largo del tiempo?  
a) Diagrama de secuencia  
b) Diagrama de clases  
c) Diagrama de paquetes  
d) Diagrama de estados  
<!-- ✅ **Respuesta correcta: a**  
💡 *El diagrama de secuencia muestra cómo los objetos interactúan enviándose mensajes en un orden cronológico.* -->

12. ¿Qué patrón permite encapsular algoritmos en clases independientes?  
a) Observer  
b) Strategy  
c) Factory Method  
d) Command  
<!-- ✅ **Respuesta correcta: b**  
💡 *Strategy permite definir una familia de algoritmos, encapsularlos y hacerlos intercambiables entre sí.* -->

13. ¿Qué modelo UML muestra cómo se organizan y agrupan los componentes lógicamente?  
a) Diagrama de clases  
b) Diagrama de paquetes  
c) Diagrama de componentes  
d) Diagrama de casos de uso  
<!-- ✅ **Respuesta correcta: b**  
💡 *El diagrama de paquetes organiza el sistema en grupos lógicos para representar dependencias entre subsistemas.* -->

14. ¿Cuál es una ventaja de aplicar patrones de diseño?  
a) Promueven soluciones reutilizables y probadas  
b) Aumentan la complejidad  
c) Eliminan la necesidad de documentación  
d) Reemplazan a UML  
<!-- ✅ **Respuesta correcta: a**  
💡 *Los patrones de diseño son soluciones ya probadas para problemas comunes, lo que mejora la calidad y reduce el esfuerzo.* -->

15. Diseñar primero la interfaz permite:  
a) Evitar errores de compilación  
b) Definir claramente los contratos entre módulos  
c) Ignorar los detalles internos  
d) Programar más rápido  
<!-- ✅ **Respuesta correcta: b**  
💡 *Diseñar la interfaz establece las reglas de interacción entre módulos antes de escribir su implementación.* -->
--- 


# UNIDAD 4: METODOLOGÍAS ÁGILES Y GESTIÓN DE PROYECTOS DE SOFTWARE<a name="capitulo4"></a>

## 4.1 Introducción a las Metodologías de Desarrollo

El desarrollo de software ha evolucionado desde modelos rígidos y secuenciales como el modelo en cascada, hasta enfoques más iterativos, colaborativos y adaptativos, como las metodologías ágiles. Estas metodologías surgieron como una respuesta a los problemas de planificación y control en entornos de alta incertidumbre.

## 4.2 ¿Qué es la Agilidad?

La agilidad en el desarrollo de software es la capacidad de adaptarse a cambios de requisitos, reducir el tiempo de entrega y fomentar la colaboración continua con el cliente. El **Manifiesto Ágil**, publicado en 2001, establece valores y principios fundamentales que guían este enfoque:

### 4.2.1 Valores del Manifiesto Ágil

- **Individuos e interacciones** sobre procesos y herramientas  
- **Software funcionando** sobre documentación extensiva  
- **Colaboración con el cliente** sobre negociación de contratos  
- **Respuesta ante el cambio** sobre seguir un plan rígido

## 4.3 Principales Metodologías Ágiles

### 4.3.1 Scrum

Scrum es un marco de trabajo ágil centrado en la entrega incremental mediante iteraciones llamadas *sprints*. Incluye roles definidos (Product Owner, Scrum Master, Development Team) y eventos clave como Daily Scrum, Sprint Review y Sprint Retrospective.

### 4.3.2 Kanban

Kanban se enfoca en la visualización del flujo de trabajo a través de tableros y tarjetas. Permite gestionar tareas en curso, identificar cuellos de botella y mejorar continuamente el proceso.

### 4.3.3 Extreme Programming (XP)

XP enfatiza las buenas prácticas técnicas como desarrollo dirigido por pruebas (TDD), integración continua, programación en parejas y diseño simple.

## 4.4 Comparación con Modelos Tradicionales

| Aspecto                  | Modelo en Cascada       | Metodologías Ágiles      |
|--------------------------|--------------------------|---------------------------|
| Planificación inicial     | Extensa                  | Ligera y progresiva       |
| Cambios de requisitos     | Difíciles de incorporar  | Bienvenidos               |
| Entregas                 | Al final del proyecto    | Frecuentes e iterativas   |
| Participación del cliente| Limitada                 | Continua y activa         |

## 4.5 Roles en un Proyecto Ágil

- **Product Owner**: define y prioriza el backlog del producto  
- **Scrum Master**: facilita el proceso y elimina obstáculos  
- **Equipo de Desarrollo**: construye el producto  
- **Stakeholders**: usuarios, clientes o patrocinadores

## 4.6 Herramientas de Gestión Ágil

- **JIRA**  
- **Trello**  
- **Asana**  
- **ClickUp**  
Estas herramientas permiten gestionar tareas, visualizar flujos de trabajo y medir el rendimiento del equipo en tiempo real.

## 4.7 Conclusión

Las metodologías ágiles han transformado la forma en que se desarrollan los sistemas, priorizando la colaboración, la adaptabilidad y la entrega continua de valor. Su aplicación requiere un cambio cultural hacia la flexibilidad y la confianza en los equipos de desarrollo.

---

## ✏️ Práctica Asignable

**Título:** Simulación de Proyecto Ágil con Scrum  
**Objetivo:** Aplicar los conceptos de Scrum en un proyecto de software simulado.

**Instrucciones:**

1. Formar equipos de 2 a 3 estudiantes.
2. Definir un producto simple (ej. una app de notas o un sistema de reservas).
3. Crear un *Product Backlog* con al menos 10 historias de usuario.
4. Simular dos *sprints*:
   - Sprint 1: seleccionar historias, planificar y entregar resultados (puede ser en forma de prototipo o mockups).
   - Sprint 2: integrar mejoras sugeridas en la *Sprint Review*.
5. Documentar:
   - Roles asumidos (Scrum Master, Product Owner)
   - Daily meetings (resumen breve)
   - Resultados de cada sprint
   - Retrospectiva final del equipo

**Entrega:** informe en PDF o presentación con capturas, reflexiones y aprendizajes.

---

## 📝 Examen Unidad 4: Metodologías Ágiles


**Selecciona la opción correcta en cada caso.**

1. ¿Cuál es uno de los valores del Manifiesto Ágil?  
a) Documentación detallada sobre software funcionando  
b) Procesos sobre individuos  
c) Contratos sobre colaboración  
d) Software funcionando sobre documentación extensiva
<!-- ✅ **Respuesta correcta: d**  
💡 *El enfoque ágil prioriza entregar valor funcional sobre exceso de documentación.* -->

2. ¿Qué metodología ágil se basa en iteraciones llamadas sprints?  
a) XP  
b) Kanban  
c) Scrum  
d) Lean  
<!-- ✅ **Respuesta correcta: c**  
💡 *Scrum estructura el trabajo en ciclos cortos y repetitivos llamados sprints.* -->

3. ¿Cuál de los siguientes es un rol en Scrum?  
a) Coordinador general  
b) Supervisor técnico  
c) Product Owner  
d) Líder de procesos  
<!-- ✅ **Respuesta correcta: c**  
💡 *El Product Owner gestiona el backlog y prioriza tareas en Scrum.* -->

4. ¿Qué herramienta permite visualizar el flujo de trabajo de manera simple y visual?  
a) GitHub  
b) Trello  
c) Eclipse  
d) Docker  
<!-- ✅ **Respuesta correcta: b**  
💡 *Trello usa tableros para gestionar tareas visualmente.* -->

5. ¿Qué metodología enfatiza el desarrollo dirigido por pruebas (TDD)?  
a) Scrum  
b) XP  
c) Kanban  
d) SAFe  
<!-- ✅ **Respuesta correcta: b**  
💡 *Extreme Programming promueve TDD, integración continua y diseño simple.* -->

6. ¿Cuál es una diferencia entre metodologías ágiles y modelos tradicionales?  
a) Las ágiles requieren más documentación  
b) Las tradicionales permiten mayor participación del cliente  
c) Las ágiles entregan software frecuentemente  
d) Las tradicionales son iterativas  
<!-- ✅ **Respuesta correcta: c**  
💡 *Las metodologías ágiles entregan valor en ciclos cortos.* -->

7. En Kanban, ¿qué representa una tarjeta en el tablero?  
a) Un error técnico  
b) Un paso del proceso  
c) Una tarea específica  
d) Un ciclo de desarrollo  
<!-- ✅ **Respuesta correcta: c**  
💡 *Cada tarjeta representa una tarea o historia de usuario.* -->

8. ¿Qué herramienta NO está orientada a metodologías ágiles?  
a) Trello  
b) JIRA  
c) Visual Studio  
d) ClickUp  
<!-- ✅ **Respuesta correcta: c**  
💡 *Visual Studio es un entorno de desarrollo, no de gestión ágil.* -->

9. ¿Qué evento ocurre diariamente en Scrum para sincronizar al equipo?  
a) Sprint Planning  
b) Retrospective  
c) Daily Scrum  
d) Demo Review  
<!-- ✅ **Respuesta correcta: c**  
💡 *Daily Scrum es una reunión diaria rápida para alineación.* -->

10. ¿Qué rol ayuda a remover obstáculos en Scrum?  
a) Product Owner  
b) Scrum Master  
c) Programador líder  
d) Tester  
<!-- ✅ **Respuesta correcta: b**  
💡 *El Scrum Master facilita y protege al equipo del ruido externo.* -->

11. ¿Qué se evalúa durante la retrospectiva de un sprint?  
a) Las métricas de desempeño  
b) Los errores de compilación  
c) El diseño visual  
d) El proceso y la colaboración del equipo  
<!-- ✅ **Respuesta correcta: d**  
💡 *En la retrospectiva se analizan mejoras para el próximo sprint.* -->

12. ¿Cuál es el primer paso antes de iniciar un sprint?  
a) Daily meeting  
b) Sprint Review  
c) Sprint Planning  
d) Sprint Retrospective  
<!-- ✅ **Respuesta correcta: c**  
💡 *Sprint Planning define el alcance del trabajo que se hará.* -->

13. ¿Qué se prioriza en el desarrollo ágil?  
a) Planificación detallada  
b) Acuerdos contractuales  
c) Resultados funcionales frecuentes  
d) Evaluaciones finales  
<!-- ✅ **Respuesta correcta: c**  
💡 *El enfoque ágil busca entregar valor continuamente.* -->

14. ¿Qué función cumple el Product Backlog?  
a) Mostrar errores  
b) Registrar tareas completadas  
c) Listar historias de usuario priorizadas  
d) Guardar documentación  
<!-- ✅ **Respuesta correcta: c**  
💡 *El Product Backlog contiene los requerimientos del producto ordenados por valor.* -->

15. ¿Qué ventaja ofrecen las metodologías ágiles?  
a) Reducción total de errores  
b) Eliminación del rol del cliente  
c) Flexibilidad ante el cambio  
d) Rigidez en los procesos  
<!-- ✅ **Respuesta correcta: c**  
💡 *La adaptabilidad es clave en entornos cambiantes.* -->


# 

# UNIDAD 5: CONTROL DE CALIDAD Y PRUEBAS DE SOFTWARE

## 5.1 Introducción al Control de Calidad de Software<a name="unidad5"></a>

El control de calidad en el desarrollo de software se refiere al conjunto de actividades destinadas a garantizar que el producto cumpla con los estándares de calidad previamente establecidos. A diferencia del aseguramiento de calidad, que busca prevenir errores mediante procesos bien definidos, el control de calidad se enfoca en detectar y corregir defectos en el producto final.

**Objetivos del control de calidad:**
- Verificar que el software funcione según lo esperado.
- Detectar defectos antes de la entrega al cliente.
- Validar que se cumplen los requerimientos funcionales y no funcionales.

**Verificación vs Validación:**
- **Verificación:** ¿Estamos construyendo el producto correctamente?
- **Validación:** ¿Estamos construyendo el producto correcto?

---

## 5.2 Tipos de Pruebas de Software

Las pruebas de software se clasifican en diferentes tipos según su propósito y momento de aplicación en el ciclo de vida del software.

### Pruebas según el nivel de abstracción:
- **Pruebas Unitarias:** Verifican el correcto funcionamiento de unidades pequeñas e independientes de código, como funciones o métodos.
- **Pruebas de Integración:** Evalúan la interacción entre varios módulos o componentes.
- **Pruebas de Sistema:** Validan el sistema completo como una unidad funcional.
- **Pruebas de Aceptación:** Aseguran que el producto cumple con los requerimientos del cliente.

### Pruebas según la naturaleza:
- **Pruebas Funcionales:** Validan las funcionalidades del sistema según los requisitos especificados.
- **Pruebas No Funcionales:** Evalúan características como rendimiento, usabilidad, confiabilidad, escalabilidad, etc.

### Pruebas según el método:
- **Pruebas Manuales:** Ejecutadas por un tester sin el uso de herramientas automatizadas.
- **Pruebas Automatizadas:** Implementadas con scripts y herramientas que ejecutan pruebas automáticamente.

---

## 5.3 Herramientas y Entornos de Pruebas

En la actualidad, existen múltiples herramientas para facilitar el proceso de pruebas en las distintas etapas del desarrollo de software.

**Pruebas unitarias:**
- **JUnit** (Java)
- **NUnit** (.NET)
- **PyTest** (Python)

**Automatización de pruebas funcionales:**
- **Selenium**: Automatización de pruebas web.
- **Cypress**: Pruebas modernas de frontend.
- **TestCafe**: Pruebas E2E rápidas para aplicaciones web.

**Pruebas de carga y rendimiento:**
- **JMeter**: Pruebas de estrés y carga.
- **Gatling**: Rendimiento y escalabilidad.

**CI/CD con integración de pruebas:**
- **GitHub Actions**
- **GitLab CI**
- **Jenkins**

---

## 5.4 Estrategias de Pruebas y Cobertura de Código

**Caja blanca:**  
El tester conoce la estructura interna del código. Se enfoca en la lógica de programación y las estructuras de control.

**Caja negra:**  
El tester no conoce el código fuente y se enfoca en entradas y salidas esperadas.

**Cobertura de código:**  
Métrica utilizada para determinar qué porcentaje del código fuente es ejecutado por las pruebas. Puede incluir:
- Cobertura de líneas
- Cobertura de funciones/métodos
- Cobertura de condiciones y decisiones

Las herramientas modernas permiten integrar análisis de cobertura en los pipelines de CI/CD, ayudando a mantener altos niveles de calidad.

---

## 5.5 Gestión de Defectos y Reporte de Errores

La correcta gestión de errores es esencial para el éxito de los proyectos. Esto incluye la identificación, registro, seguimiento, priorización y resolución de los defectos.

**Flujo típico de un bug:**
1. Detección y reporte del error.
2. Asignación al equipo correspondiente.
3. Reproducción y análisis del defecto.
4. Corrección y validación de la solución.
5. Cierre del incidente.

**Herramientas populares:**
- **Jira**
- **Bugzilla**
- **Azure DevOps**
- **Redmine**

**Priorización:**
- **Crítico:** Impide el funcionamiento del sistema.
- **Alto:** Afecta funciones clave.
- **Medio:** No afecta el uso principal, pero debe corregirse.
- **Bajo:** No interfiere significativamente, puede postergarse.

---

## 🛠️ Práctica Sugerida

Desarrolla una aplicación sencilla (por ejemplo, una calculadora) y realiza lo siguiente:

1. Crea pruebas unitarias para las operaciones básicas.
2. Integra pruebas automatizadas usando una herramienta como JUnit o PyTest.
3. Configura un reporte de cobertura de código.
4. Simula un ciclo de reporte y gestión de errores en Jira.
5. Crea un pipeline de CI que ejecute las pruebas automáticamente al hacer un commit.

---

## 🧠 Examen Tipo Test

**1. ¿Cuál es la diferencia principal entre pruebas funcionales y no funcionales?**  
a) Las funcionales se ejecutan manualmente y las no funcionales automáticamente  
b) Las funcionales validan funcionalidades y las no funcionales evalúan atributos del sistema ✅  
c) Las funcionales prueban el código y las no funcionales la base de datos  
d) No existe diferencia

**2. ¿Qué herramienta se utiliza comúnmente para pruebas unitarias en Java?**  
a) Selenium  
b) JMeter  
c) JUnit ✅  
d) SonarQube

**3. ¿Qué representa una cobertura de código del 80%?**  
a) Que el 80% de los usuarios están cubiertos por las pruebas  
b) Que el 80% del código fue ejecutado al menos una vez por las pruebas ✅  
c) Que el 80% del equipo escribió pruebas  
d) Que el 80% de los errores se han resuelto

**4. ¿Cuál de las siguientes herramientas se utiliza para pruebas de carga?**  
a) Jenkins  
b) Selenium  
c) JMeter ✅  
d) Git

**5. En el control de calidad de software, ¿qué significa validación?**  
a) Verificar que el sistema no tenga errores de sintaxis  
b) Confirmar que el software cumple los requerimientos del cliente ✅  
c) Confirmar que el código se ejecuta sin errores  
d) Validar que la base de datos esté conectada

---

## 📚 Conclusión

El control de calidad y las pruebas de software son elementos fundamentales en cualquier proceso de desarrollo moderno. Implementar estrategias de pruebas adecuadas, seleccionar herramientas eficientes y gestionar los defectos correctamente son prácticas que elevan la confiabilidad y mantenibilidad del software. Esta unidad establece los cimientos necesarios para que los futuros ingenieros de software comprendan la importancia de la calidad y su rol crítico en el ciclo de vida del desarrollo.

---

# 

# UNIDAD 6: INTEGRACIÓN Y ENTREGA CONTINUA (CI/CD)<a name="unidad6"></a>

## 6.1 Introducción al DevOps y CI/CD

El desarrollo de software moderno requiere velocidad, eficiencia y confiabilidad. Para lograrlo, surge la filosofía **DevOps**, que promueve la colaboración entre los equipos de desarrollo (Dev) y operaciones (Ops) para automatizar y mejorar continuamente la entrega de software.

Uno de los pilares fundamentales de DevOps es la adopción de prácticas de **Integración Continua (CI)** y **Entrega Continua (CD)**, que permiten validar, integrar y desplegar software de manera rápida, segura y repetible.

**Beneficios clave de CI/CD:**
- Reducción del tiempo de entrega.
- Mayor calidad y consistencia en las versiones.
- Detección temprana de errores.
- Automatización de procesos repetitivos.

---

## 6.2 Integración Continua (CI)

La **Integración Continua (CI)** consiste en integrar los cambios del código frecuentemente (varias veces al día), validando automáticamente cada integración mediante compilación, pruebas unitarias y otros análisis.

### Componentes de CI:
- **Repositorio de código fuente:** Git, GitHub, GitLab, Bitbucket.
- **Servidor de CI:** Jenkins, GitHub Actions, GitLab CI/CD, Azure Pipelines.
- **Ejecución automática de pruebas:** Unitarias, de integración, de cobertura.
- **Notificaciones:** Slack, correo, dashboards.

### Buenas prácticas:
- Confirmar commits frecuentemente con cambios pequeños.
- Mantener el repositorio limpio y funcional.
- Ejecutar pruebas en cada push.
- Corregir fallos de compilación o pruebas de inmediato.

### Ejemplo básico en GitHub Actions:

```yaml
name: CI Pipeline

on:
  push:
    branches: [ main ]

jobs:
  build-and-test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Instalar dependencias
        run: npm install
      - name: Ejecutar pruebas
        run: npm test
````

---

## 6.3 Entrega Continua (CD)

La **Entrega Continua (CD)** extiende la integración continua automatizando también el proceso de entrega del software a entornos de prueba o producción. El objetivo es que cada cambio que pase las pruebas pueda ser desplegado automáticamente.

### Ventajas de la entrega continua:

* Reducción de errores en producción.
* Despliegues más rápidos y seguros.
* Entrega de valor al cliente de forma constante.

### Proceso típico de CD:

1. Validación del código.
2. Pruebas automatizadas.
3. Construcción del artefacto.
4. Despliegue automático a entornos (QA, staging, producción).

### Herramientas para CD:

* Jenkins
* GitHub Actions
* GitLab CI/CD
* CircleCI
* Azure DevOps

---

## 6.4 Infraestructura como Código (IaC)

La **Infraestructura como Código (IaC)** permite definir, versionar y desplegar entornos completos de infraestructura usando archivos de configuración.

### Herramientas comunes:

* **Terraform:** Gestión de infraestructura multiplataforma (AWS, Azure, GCP).
* **Ansible:** Automatización de configuración y despliegue.
* **Docker:** Contenerización de aplicaciones.
* **Kubernetes:** Orquestación de contenedores a gran escala.

### Beneficios:

* Reproducibilidad de entornos.
* Versionamiento y trazabilidad.
* Despliegues consistentes.
* Reducción de errores humanos.

### Ejemplo básico de Dockerfile:

```Dockerfile
FROM node:18
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
CMD ["npm", "start"]
```

---

## 6.5 Buenas Prácticas y Seguridad en CI/CD

En un entorno de CI/CD, la seguridad debe ser parte integral del proceso. Esto se conoce como **DevSecOps**: integrar la seguridad desde el inicio del desarrollo.

### Buenas prácticas:

* **Manejo seguro de secretos:** No almacenar contraseñas en el repositorio; usar vaults o variables de entorno.
* **Escaneo automático de vulnerabilidades:** Usar herramientas como SonarQube, Snyk, OWASP ZAP.
* **Control de acceso a pipelines:** Autenticación multifactor y permisos mínimos.
* **Auditoría y trazabilidad:** Mantener registros de los despliegues y cambios.

---

## 🛠️ Práctica Sugerida

1. Crea un repositorio en GitHub con una aplicación básica (API o web).
2. Configura un pipeline de CI en GitHub Actions que:

   * Instale dependencias.
   * Ejecute pruebas unitarias.
   * Genere reporte de cobertura.
3. Agrega una etapa de entrega continua que despliegue a un entorno de staging (puede ser un servidor local o remoto vía SSH).
4. Usa Docker para contenerizar la aplicación.
5. Agrega escaneo de seguridad en las dependencias del proyecto.

---

## 🧠 Examen Tipo Test

**1. ¿Qué objetivo tiene la Integración Continua (CI)?**
a) Compilar el código una vez por semana
b) Ejecutar pruebas manuales en cada despliegue
c) Integrar y probar los cambios de código frecuentemente ✅
d) Instalar dependencias de los servidores

**2. ¿Qué herramienta permite definir infraestructura como código?**
a) Selenium
b) Terraform ✅
c) GitHub
d) Jira

**3. ¿Qué comando inicia una aplicación definida en un Dockerfile?**
a) `node app.js`
b) `npm install`
c) `docker build`
d) `npm start` ✅

**4. ¿Cuál es una ventaja de la entrega continua?**
a) Despliegue manual de software
b) Eliminar la automatización
c) Publicar versiones de forma segura y frecuente ✅
d) Incrementar el tiempo de pruebas

**5. ¿Qué representa IaC en el contexto de DevOps?**
a) Control de interfaces de usuario
b) Automatización de bases de datos
c) Infraestructura como Código ✅
d) Integración con arquitecturas clásicas

---

## 📚 Conclusión

La automatización de los procesos de desarrollo, pruebas y despliegue mediante CI/CD ha transformado la forma en que se construyen y entregan soluciones de software. Los ingenieros de software deben dominar estas prácticas modernas no solo para ser competitivos, sino para garantizar la calidad, velocidad y confiabilidad en los proyectos. Esta unidad proporciona los conocimientos fundamentales para construir pipelines eficientes, seguros y escalables, listos para ambientes empresariales y de producción.

---

# 

# UNIDAD 7: MANTENIMIENTO, EVOLUCIÓN Y REFACCIÓN DE SOFTWARE<a name="unidad7"></a>

## 7.1 Ciclo de Vida del Software en Producción

El desarrollo de un sistema no finaliza con su implementación. Una parte crucial del ciclo de vida del software es su **mantenimiento** una vez ha sido desplegado. A medida que cambian los requisitos del negocio, evolucionan las tecnologías y se identifican defectos, el software necesita adaptarse constantemente.

### Tipos de mantenimiento:
- **Correctivo:** Corrección de errores encontrados después del despliegue.
- **Adaptativo:** Ajustes necesarios para que el software funcione con nuevos entornos (SO, hardware, dependencias).
- **Perfectivo:** Mejoras en funcionalidades existentes o en la interfaz de usuario.
- **Preventivo:** Cambios que mejoran la mantenibilidad del software para evitar futuros problemas.

El mantenimiento consume una gran parte del costo total de un sistema a lo largo de su vida útil, por lo que es vital estructurarlo correctamente desde las fases iniciales de desarrollo.

---

## 7.2 Refactorización de Código

La **refactorización** es el proceso de modificar el código fuente para mejorar su estructura interna sin cambiar su comportamiento externo.

### Objetivos de la refactorización:
- Mejorar la legibilidad.
- Reducir la complejidad.
- Aumentar la reutilización y mantenibilidad.
- Eliminar duplicaciones y código innecesario.

### Principales técnicas de refactorización:
- Extraer método (`Extract Method`)
- Renombrar variable (`Rename Variable`)
- Reemplazar código duplicado con abstracciones
- Introducir objetos o clases auxiliares

### Buenas prácticas:
- Refactorizar siempre con pruebas automatizadas disponibles.
- Realizar pequeños cambios con commits frecuentes.
- Documentar los motivos del cambio.

### Herramientas de refactorización:
- IDEs como IntelliJ, Visual Studio, VS Code, Eclipse.
- Linters y analizadores estáticos como ESLint, SonarQube.

---

## 7.3 Gestión de la Deuda Técnica

La **deuda técnica** representa las decisiones rápidas o subóptimas tomadas durante el desarrollo que comprometen la calidad interna del software a cambio de entregar más rápido. Aunque en el corto plazo puede parecer beneficiosa, a largo plazo eleva los costos de mantenimiento y dificulta la evolución del sistema.

### Causas comunes:
- Código no documentado ni comentado.
- Arquitectura mal diseñada.
- Falta de pruebas automatizadas.
- Dependencias obsoletas o mal gestionadas.

### Gestión efectiva:
- Identificar la deuda mediante revisiones de código.
- Priorizar su pago en el backlog del proyecto.
- Establecer métricas de calidad como:
  - Complejidad ciclomática
  - Duplicación de código
  - Cobertura de pruebas

---

## 7.4 Migración y Modernización de Sistemas

A medida que el software envejece o se transforma el entorno tecnológico, puede ser necesario realizar una **migración** o **modernización** del sistema. Esto implica actualizar tecnologías, patrones arquitectónicos o incluso lenguajes de programación.

### Tipos de migración:
- **Tecnológica:** Migrar a un nuevo framework, base de datos o entorno de ejecución.
- **Funcional:** Reescritura o rediseño de módulos clave.
- **Arquitectónica:** Pasar de monolitos a microservicios o a arquitecturas en la nube.

### Consideraciones clave:
- Evaluar el impacto de los cambios.
- Ejecutar pruebas de regresión.
- Mantener la trazabilidad de versiones.
- Asegurar compatibilidad con sistemas externos.

### Enfoques comunes:
- Estrategia **Big Bang:** Migrar todo el sistema en un solo evento.
- Estrategia **Incremental:** Migrar por módulos o servicios.

---

## 7.5 Gestión de la Configuración del Software

La **gestión de configuración** consiste en controlar y registrar todos los cambios realizados al software, asegurando la integridad y trazabilidad del producto a lo largo del tiempo.

### Actividades principales:
- Control de versiones del código fuente.
- Registro de cambios y motivos de modificaciones.
- Mantenimiento de configuraciones por ambiente (dev, QA, prod).
- Reversiones en caso de errores.

### Herramientas de control de versiones:
- **Git:** El más popular y distribuido.
- **SVN:** Sistema centralizado.
- **Mercurial:** Alternativa moderna a SVN.

### Buenas prácticas con Git:
- Usar ramas para separar funcionalidades.
- Escribir mensajes de commit descriptivos.
- Hacer `merge` o `rebase` con control y revisión.
- Aplicar estrategias como Git Flow o Trunk-Based Development.

---

## 🛠️ Práctica Sugerida

Desarrolla un módulo sencillo y:

1. Identifica oportunidades de refactorización.
2. Aplica al menos tres técnicas de refactorización distintas.
3. Documenta los cambios realizados.
4. Simula deuda técnica introduciendo errores intencionales, y luego planifica su corrección.
5. Usa Git para versionar cada paso con mensajes claros y estructurados.
6. Realiza un pequeño plan de migración de una tecnología obsoleta a una más moderna (por ejemplo, de jQuery a React).

---

## 🧠 Examen Tipo Test

**1. ¿Cuál de los siguientes es un tipo de mantenimiento de software?**  
a) Activo  
b) Correctivo ✅  
c) Progresivo  
d) Iterativo

**2. ¿Qué es la refactorización?**  
a) Reescribir una aplicación desde cero  
b) Cambiar la arquitectura sin modificar el código  
c) Modificar el código sin alterar su comportamiento externo ✅  
d) Eliminar módulos antiguos del sistema

**3. ¿Qué representa la deuda técnica?**  
a) Horas no pagadas al equipo de desarrollo  
b) Código que debe eliminarse completamente  
c) Decisiones que reducen calidad interna a corto plazo ✅  
d) Errores del sistema sin documentación

**4. ¿Qué herramienta se usa comúnmente para control de versiones?**  
a) Docker  
b) Jenkins  
c) Git ✅  
d) Jira

**5. ¿Qué estrategia de migración consiste en cambiar todo el sistema en una sola operación?**  
a) Migración por etapas  
b) Refactorización controlada  
c) Enfoque Big Bang ✅  
d) Microservicios paralelos

---

## 📚 Conclusión

El mantenimiento y evolución del software son etapas permanentes que determinan el éxito o fracaso de un sistema a largo plazo. Aprender a refactorizar, controlar la configuración, gestionar la deuda técnica y planificar adecuadamente las migraciones permite a los ingenieros de software entregar productos sostenibles, robustos y alineados con las necesidades cambiantes del negocio. Esta unidad brinda las herramientas conceptuales y prácticas necesarias para dominar estas tareas clave en la ingeniería de software avanzada.

---










