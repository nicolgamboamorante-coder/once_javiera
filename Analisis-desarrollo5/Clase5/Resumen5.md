# Clase 5: Introducción al Diseño 



## 1. El Puente entre Requerimientos y Código (Módulo 1)
El diseño de software es la fase del ciclo de vida donde las especificaciones del usuario (el *QUÉ*) se transforman en planos e instrucciones técnicas estructuradas (el *CÓMO*). 
* **Propósito Fundamental:** Reducir la complejidad antes de que se escriba la primera línea de código, sirviendo como guía inequívoca para los desarrolladores.
* **La Premisa del Diseñador:** Construir código sin un plano previo genera deudas técnicas, software frágil, problemas de rendimiento y sobrecostos por reestructuración (*refactorización*).



## 2. Niveles de Diseño en Ingeniería de Software (Módulos 2 y 3)

El diseño arquitectónico se divide de manera jerárquica en dos grandes niveles de abstracción:

### A. Diseño de Alto Nivel (Diseño Arquitectónico)
Define la estructura global del sistema y cómo interactúan sus bloques principales.
* **Componentes:** Selección de la arquitectura base (Monolítica, Microservicios, Capas o Cliente-Servidor).
* **Decisiones Críticas:** Elección del motor de base de datos, sistemas de mensajería, flujos de datos globales e infraestructura de red/nube.

### B. Diseño de Bajo Nivel (Diseño de Detalle)
Baja al detalle atómico de cada componente definido en el alto nivel.
* **Componentes:** Estructura de clases, definición precisa de métodos, variables, firmas de funciones, lógica de algoritmos internos y esquemas relacionales de tablas.
* **Modelado Común:** Creación de diagramas de clases UML y diagramas de secuencia detallados.



## 3. Principios Fundamentales del Buen Diseño (Módulos 4, 5 y 6)

Para evaluar si los planos de un sistema garantizan un software escalable, se miden tres propiedades de ingeniería fundamentales:

### 1. Acoplamiento (Buscar: Acoplamiento Bajo)
Mide el grado de dependencia interconectada entre los diferentes módulos del software.
* **Acoplamiento Alto (Malo):** Si modificar el módulo A rompe por accidente el módulo B y C. El código es rígido.
* **Acoplamiento Bajo (Ideal):** Los módulos son independientes. Se comunican por interfaces limpias y cambiar uno no afecta al resto.

### 2. Cohesión (Buscar: Cohesión Alta)
Mide qué tan enfocadas están las responsabilidades dentro de un mismo módulo o clase.
* **Cohesión Baja (Mala):** Clases "Dios" u "Objeto Todopoderoso" que validan usuarios, conectan a la base de datos y envían correos al mismo tiempo.
* **Cohesión Alta (Ideal):** Una clase hace **una sola cosa bien** (Ej: la clase `Autenticador` solo valida credenciales). Cumple el Principio de Responsabilidad Única.

### 3. Modularidad
La capacidad de dividir un sistema de software complejo en bloques o componentes lógicos más pequeños, manejables, testeables y reutilizables de forma independiente.



## 4. El Reto Final: Tus Primeros Planos Arquitectónicos (Módulo 7)
La clase concluye con un laboratorio donde debes tomar los requerimientos documentados en la unidad anterior y transformarlos en planos técnicos formales antes de la fase de construcción.

### Entregables del Reto:
1. **Definición de la Arquitectura Global:** Declarar qué patrón arquitectónico se utilizará (Ej: Arquitectura en 3 Capas: Presentación, Lógica de Negocio y Datos) justificando la decisión.
2. **Esquema de Datos Inicial:** Diseñar el modelo entidad-relación preliminar (tablas, atributos clave y llaves primarias) para persistir la información de las Historias de Usuario elegidas.
3. **Contrato de Interfaces (APIs / Componentes):** Definir la firma de al menos 2 funciones o servicios esenciales (Nombre de la función, parámetros de entrada con tipo de dato y valor esperado de retorno).
4. **Análisis de Impacto de Cambios:** Explicar cómo el diseño propuesto mantiene un *bajo acoplamiento* frente a un cambio hipotético del cliente (Ej: cambiar la base de datos de MySQL a PostgreSQL).
5. **Autoevaluación:** Una reflexión escrita sobre el cambio de mentalidad necesario para pasar de pensar en términos de negocio (lenguaje del cliente) a pensar en términos de componentes estructurados y abstractos.