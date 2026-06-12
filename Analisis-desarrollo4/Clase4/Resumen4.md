# Clase 4: Documentación de Requisitos — El Contrato del Proyecto



## 1. Introducción: El Propósito de Documentar (Módulo 1)
La documentación de requisitos es el proceso de traducir las necesidades, conversaciones e ideas del cliente en especificaciones técnicas formales, permanentes y sin ambigüedades. Funciona como el contrato oficial e inmutable entre el cliente y el equipo de desarrollo.
* **Protección del Alcance:** Evita el *Scope Creep* (crecimiento descontrolado y desmedido del proyecto).
* **Reglas de Redacción:** Se debe usar un lenguaje claro, conciso, en tiempo presente y eliminar por completo adjetivos subjetivos como "rápido", "fácil", "eficiente" o "bonito".



## 2. Estructura Padrón y Artefactos (Módulos 2, 3 y 4)

### A. El Documento SRS / ERS (Especificación de Requisitos de Software)
Es el formato tradicional y estructurado regido por el estándar internacional **IEEE 830**.
* **Secciones Clave:** Introducción y objetivos, descripción general del sistema, catálogo detallado de requisitos funcionales, requisitos no funcionales (restrições) y un glossario técnico.

### B. Historias de Usuario (User Stories)
Es el artefacto moderno de las metodologías ágiles que documenta los requerimientos desde la perspectiva del usuario final.
* **Estructura Obligatoria:** "Como **[Rol/Actor]**, quiero **[Funcionalidad/Acción]**, para **[Beneficio/Valor]**."
* **Criterios de Aceptación:** Reglas explícitas e independientes que validan cuándo la historia está terminada (Formato: "Dado que... Cuando... Entonces...").

### C. Matriz de Rastreabilidad
Es una tabla de control que vincula cada requisito desde su origen (la entrevista), pasando por el diseño, el código fuente escrito, hasta su plan de pruebas correspondiente, asegurando la cobertura total del sistema.



## 3. Técnicas de Validación y Calidad (Módulos 5 y 6)
* **Inspección Técnica de Requisitos:** Revisiones grupales formales donde se busca detectar contradicciones, duplicaciones o vacíos de información dentro del documento.
* **Atomicidade (Requisitos Atómicos):** Garantizar que cada requisito describa una única función indivisible, facilitando las pruebas unitarias y las estimaciones de tiempo de desarrollo.



## 4. El Reto Final: Tu Primera Especificación Oficial (Módulo 7)
El módulo concluye con un laboratorio práctico donde debes documentar formalmente la solución al problema detectado en la entrevista de la clase anterior.

###  Entregables del Reto:
1. **Ficha del Proyecto:** Nombre del sistema, versión, autores y descripción de objetivos generales.
2. **Especificación Ágil:** Redacción de 3 Historias de Usuario completas con la sintaxis correcta.
3. **Criterios de Validación:** Definir un mínimo de 2 criterios de aceptación claros para cada una de las historias.
4. **Restricciones Técnicas:** Redactar 2 requisitos no funcionales SMART enfocados en la seguridad o el rendimiento del sistema.
5. **Autoevaluación:** Una reflexión escrita sobre la complejidad de traducir el lenguaje informal de un usuario común a una especificación de ingeniería formal.