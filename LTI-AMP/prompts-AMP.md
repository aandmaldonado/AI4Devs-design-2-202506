# Historial de prompts 📑

> **LLM utilizado:** OpenAI GPT-4.1 (2024) 🤖

---

## **Prompt 1:** 📝

Eres un product manager.

Necesitas mejorar el @LTI-AMP.md dandole un enfoque de negocio y no tan tecnico.

haz la mejoras necesarias para que posteriormente pueda ser utilizado para generar User Stories, Backlog de producto, Tickets de trabajo, estimacion de esfuerzo.

de momento solo enfocate en mejorar @PRD-AMP.md.

realizalo directamente, pero creando otro archivo PRD-LTI.md y anexa @LTI-AMP.md para no perder el detalle tecnico.

![LTI ATS System](LTI-AMP.md)

---

## **Prompt 2:** 📝

Según lo indicado en @ReadMe.md detalla como lo harías y como utilizarás los recursos @PRD-AMP.md y @LTI-AMP.md para tal proposito

---

## **Prompt 3:** 📝🏷️

Solo redacta las User Stories en @UserStories-AMP.md  siguiendo una plantilla común, asegurando que incluyan: título, descripción, criterios de aceptación, prioridad y cualquier detalle relevante.

usa el siguiente ejemplo:

Estructura basica de una User Story

Formato estándar: "Como [tipo de usuario], quiero [realizar una acción] para [obtener un beneficio]".

Descripción: Una descripción concisa y en lenguaje natural de la funcionalidad que el usuario desea.

Criterios de Aceptación: Condiciones específicas que deben cumplirse para considerar la User Story como "terminada", éstos deberian de seguir un formato similar a “Dado que” [contexto inicial], "cuando” [acción realizada], “entonces” [resultado esperado].

Notas adicionales:  Notas que puedan ayudar al desarrollo de la historia

Tareas: Lista de tareas y subtareas para que esta historia pueda ser completada

No te limites al minimo solicitado, escribe todas las que estimes conveniente par lograr el objetivo a cabalidad

---

## **Prompt 4:** 📝

Arma el Backlog de producto con las User Stories generadas anteriormente, agrega otra sección en @UserStories-AMP.md

Priorizalas como estimes conveniente acorde a alguna metodología concreta (debes agregar el nombre de la metodologia usada y la razon de su selcción).

---

## **Prompt 5:** 📏

Considera el backlog de producto creado anteriormente. considera todas las user stories

Estima por cada item en el backlog (genera una tabla markdown):

- Impacto en el usuario y valor del negocio.
- Urgencia basada en tendencias del mercado y feedback de usuarios.
- Complejidad y esfuerzo estimado de implementación.
- Riesgos y dependencias entre tareas.

---

## **Prompt 6:** 📏

mejora la tabla estimando el esfuerzo de los tickets de trabajo usando la metodología tallas de camiseta y unidades en puntos de historia.

---

## **Prompt 7:** 🏷️🛠️

Elige la User Story mas compleja, para sacar mayor provecho al ejercicio, y genera los Tickets de trabajo correspondientes. Aterrízalos técnicamente, tal y como se hace en las sprint planning.

Apoyate en @PRD-LTI.md y @LTI-AMP.md

agrega otra seccion en @UserStories-AMP.md

el formato de redaccion para el ticket de trabajo debe ser el siguiente:

1. Título Claro y Conciso: Un resumen breve que refleje la esencia de la tarea. Debe ser lo suficientemente descriptivo para que cualquier miembro del equipo entienda rápidamente de qué se trata el ticket.

2. Descripción Detallada: Propósito: Explicación de por qué es necesaria la tarea y qué problema resuelve. Detalles Específicos: Información adicional sobre requerimientos específicos, restricciones, o condiciones necesarias para la realización de la tarea.

3. Criterios de Aceptación: Expectativas Claras: Lista detallada de condiciones que deben cumplirse para que el trabajo en el ticket se considere completado. Pruebas de Validación: Pasos o pruebas específicas que se deben realizar para verificar que la tarea se ha completado correctamente.

4. Prioridad: Una clasificación de la importancia y la urgencia de la tarea, lo cual ayuda a determinar el orden en que deben ser abordadas las tareas dentro del backlog.

5. Estimación de Esfuerzo: Puntos de Historia o Tiempo Estimado: Una evaluación del tiempo o esfuerzo que se espera que tome completar el ticket. Esto es esencial para la planificación y gestión del tiempo del equipo.

6. Asignación: Quién o qué equipo será responsable de completar la tarea. Esto asegura que todos los involucrados entiendan quién está a cargo de cada parte del proyecto.

7. Etiquetas o Tags: Categorización: Etiquetas que ayudan a clasificar el ticket por tipo (bug, mejora, tarea, etc.), por características del producto (UI, backend, etc.), o por sprint/versión.

8. Comentarios y Notas: Colaboración: Espacio para que los miembros del equipo agreguen información relevante, hagan preguntas, o proporcionen actualizaciones sobre el progreso de la tarea.

9. Enlaces o Referencias: Documentación Relacionada: Enlaces a documentos, diseños, especificaciones o tickets relacionados que proporcionen contexto adicional o información necesaria para la ejecución de la tarea.

10. Historial de Cambios: Rastreo de Modificaciones: Un registro de todos los cambios realizados en el ticket, incluyendo actualizaciones de estado, reasignaciones y modificaciones en los detalles o prioridades.

aqui tienes un ejemplo de ticket de trabajo bien estructurado:

Título: Implementación de Autenticación de Dos Factores (2FA)

Descripción: Añadir autenticación de dos factores para mejorar la seguridad del login de usuarios. Debe soportar aplicaciones de autenticación como Authenticator y mensajes SMS.

Criterios de Aceptación:

Los usuarios pueden seleccionar 2FA desde su perfil.
Soporte para Google Authenticator y SMS.
Los usuarios deben confirmar el dispositivo 2FA durante la configuración.
Prioridad: Alta

Estimación: 8 puntos de historia

Asignado a: Equipo de Backend

Etiquetas: Seguridad, Backend, Sprint 10

Comentarios: Verificar la compatibilidad con la base de usuarios internacionales para el envío de SMS.

Enlaces: Documento de Especificación de Requerimientos de Seguridad

Historial de Cambios:

01/10/2023: Creado por [nombre]
05/10/2023: Prioridad actualizada a Alta por [nombre]

---

## **Prompt 8:**

genera una seccion de estadistica de prompts, categoriza los prompts e indica cantidad en cada categoria y cual categoria fue la mas utilizada. apoyate en emojis para tener mejor visualizacion

---

## 🏁 Conclusiones sobre Prompts de Backlog y Estimación

### Prompts Seleccionados

- **Prompt 4:** 📝 Arma el Backlog de producto con las User Stories generadas anteriormente, agrega otra sección en @UserStories-AMP.md. Priorizalas como estimes conveniente acorde a alguna metodología concreta (debes agregar el nombre de la metodologia usada y la razon de su selcción).
- **Prompt 5:** 📏 Considera el backlog de producto creado anteriormente. considera todas las user stories. Estima por cada item en el backlog (genera una tabla markdown): impacto, urgencia, complejidad, riesgos y dependencias.
- **Prompt 6:** 📏 Mejora la tabla estimando el esfuerzo de los tickets de trabajo usando la metodología tallas de camiseta y unidades en puntos de historia.

### Prompt que dio mejores resultados

⭐ **Prompt 6** fue el más efectivo.

### Detalle y razones de efectividad

- **Claridad y especificidad:** Prompt 6 solicita explícitamente una mejora sobre la tabla de estimación, pidiendo el uso de una metodología concreta (tallas de camiseta) y una unidad de medida ágil (puntos de historia). Esto reduce ambigüedades y orienta la respuesta hacia un estándar profesional de equipos ágiles.
- **Valor para la planificación:** La combinación de tallas de camiseta y puntos de historia facilita la discusión y el consenso en equipos multidisciplinarios, permitiendo comparar rápidamente el esfuerzo relativo entre historias y tickets.
- **Facilita la toma de decisiones:** Al estandarizar la estimación, el equipo puede priorizar, planificar sprints y comunicar el alcance de manera más efectiva con stakeholders.
- **Mejora incremental:** Prompt 6 parte de una base ya generada (la tabla del prompt 5) y la lleva a un nivel superior de utilidad, mostrando cómo los prompts encadenados pueden refinar el resultado.

**En resumen:** Prompt 6 fue el más efectivo porque permitió obtener una estimación clara, visual y alineada con las mejores prácticas ágiles, facilitando la planificación y la comunicación dentro del equipo de desarrollo y con el negocio.

---

## 📊 Estadística de Prompts Utilizados

A continuación se presenta un resumen estadístico de los prompts empleados durante el desarrollo del proyecto, categorizados según su propósito:

| Categoría                  | Descripción                                         | Prompts | Ejemplos de Prompts         |
|----------------------------|-----------------------------------------------------|---------|-----------------------------|
| Generación de Documentos   | Creación o mejora de PRD, User Stories, Backlog     | 3       | 1, 3, 4                     |
| Detalle y Formato          | Solicitud de plantillas, estructura, formato tickets| 2       | 3, 7                        |
| Estimación y Priorización  | Estimación de esfuerzo, priorización, tablas        | 2       | 5, 6                        |
| Ejecución Técnica          | Generación de tickets técnicos detallados           | 1       | 7                           |

### 🔝 Categoría más utilizada

📝 **Generación de Documentos** (3 prompts)

**Resumen visual:**

- 📝 Generación de Documentos: 3
- 🏷️ Detalle y Formato: 2
- 📏 Estimación y Priorización: 2
- 🛠️ Ejecución Técnica: 1

> Total de prompts analizados: 8