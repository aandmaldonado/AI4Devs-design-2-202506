# User Stories - LTI ATS 🚀

---

## User Story 1: Creación y Publicación Inteligente de Vacantes 📝🤖

**Como** HR Manager o Recruiter,
**quiero** crear y publicar vacantes optimizadas con ayuda de IA,
**para** atraer candidatos adecuados de manera eficiente y rápida.

**Descripción:**
El usuario puede crear una nueva vacante, recibir sugerencias automáticas para la descripción y requisitos, y publicar la vacante en múltiples canales con seguimiento de desempeño.

**Criterios de Aceptación:**

- ✅ Dado que el usuario accede al módulo de creación de vacantes,
  cuando inicia el proceso,
  entonces el sistema sugiere automáticamente una job description optimizada.
- ✅ Dado que la vacante está lista para publicar,
  cuando el usuario selecciona los canales de publicación,
  entonces el sistema publica automáticamente en los canales elegidos y comienza el tracking de desempeño.

**Prioridad:** 🔥 Alta

**Notas adicionales:**

- 🤓 La IA debe aprender de vacantes previas y optimizar sugerencias.
- 📊 El tracking debe mostrar métricas por canal.

**Tareas:**

- 🛠️ Implementar formulario de creación de vacantes.
- 🤖 Integrar motor de sugerencias IA para descripciones y requisitos.
- 🌐 Desarrollar lógica de publicación multicanal.
- 📈 Implementar dashboard de tracking de desempeño.

---

## User Story 2: Screening y Priorización Automática de Candidatos 🕵️‍♂️⚡

**Como** Recruiter,
**quiero** recibir una lista priorizada de candidatos basada en análisis automático de CVs,
**para** enfocar mi tiempo en los perfiles más adecuados.

**Descripción:**
El sistema analiza automáticamente los CVs recibidos, asigna un matching score y categoriza a los candidatos, generando una shortlist priorizada.

**Criterios de Aceptación:**

- ✅ Dado que un candidato aplica a una vacante,
  cuando el sistema recibe el CV,
  entonces la IA analiza el perfil y asigna un matching score visible para el recruiter.
- ✅ Dado que existen múltiples candidatos,
  cuando el recruiter accede a la lista de aplicaciones,
  entonces el sistema muestra la lista priorizada y categorizada (A/B/C).

**Prioridad:** 🔥 Alta

**Notas adicionales:**

- 🧐 El matching score debe ser transparente y explicable.
- 🔄 La categorización debe poder ajustarse según feedback del recruiter.

**Tareas:**

- 🤖 Integrar motor de análisis automático de CVs.
- 🧮 Implementar lógica de matching score y categorización.
- 🖥️ Desarrollar interfaz de visualización de shortlist.
- 📝 Permitir feedback para ajuste de IA.

---

## User Story 3: Colaboración en Decisiones de Contratación 🤝💬

**Como** miembro del Hiring Team (Recruiter, Hiring Manager, Stakeholder),
**quiero** colaborar y dar feedback sobre candidatos en un workspace compartido,
**para** tomar decisiones informadas y transparentes.

**Descripción:**
El equipo puede compartir candidatos, dejar feedback y scores, y la IA sugiere decisiones basadas en criterios definidos. Todo el proceso queda registrado y notificado.

**Criterios de Aceptación:**

- ✅ Dado que un recruiter comparte un candidato,
  cuando los stakeholders acceden al workspace,
  entonces pueden dejar feedback y puntuaciones visibles para el equipo.
- ✅ Dado que hay suficiente feedback,
  cuando la IA analiza los datos,
  entonces sugiere una decisión y la registra en el sistema.

**Prioridad:** 🔥 Alta

**Notas adicionales:**

- 🗂️ El feedback debe ser estructurado y auditable.
- 🤖 Las sugerencias de IA deben poder ser aceptadas o modificadas manualmente.

**Tareas:**

- 🏢 Crear workspace colaborativo por vacante.
- 📝 Implementar sistema de feedback y scoring.
- 🤖 Integrar motor de sugerencias IA para decisiones.
- 🔔 Desarrollar sistema de notificaciones y registro de decisiones.

---

## User Story 4: Programación y Automatización de Entrevistas 📅🤝

**Como** Recruiter,
**quiero** que el sistema programe entrevistas automáticamente con los candidatos seleccionados,
**para** ahorrar tiempo y evitar errores de coordinación.

**Descripción:**
El sistema coordina automáticamente la agenda de entrevistas, notifica a los participantes y permite reprogramaciones sencillas.

**Criterios de Aceptación:**

- ✅ Dado que un candidato es seleccionado para entrevista,
  cuando el recruiter lo indica en el sistema,
  entonces la plataforma propone horarios y agenda la entrevista automáticamente.
- ✅ Dado que la entrevista está agendada,
  cuando se acerca la fecha,
  entonces el sistema envía recordatorios automáticos a todos los participantes.

**Prioridad:** 🟡 Media

**Notas adicionales:**

- 🔗 Debe integrarse con calendarios externos (Google, Outlook).
- 🔄 Permitir reprogramaciones y cancelaciones fáciles.

**Tareas:**

- 🔌 Integrar APIs de calendarios externos.
- 🤖 Desarrollar lógica de programación automática.
- 🔔 Implementar sistema de notificaciones y recordatorios.
- 🔄 Crear interfaz para reprogramar/cancelar entrevistas.

---

## User Story 5: Analytics y Reporting de KPIs 📊📈

**Como** HR Manager,
**quiero** acceder a dashboards con KPIs clave del proceso de reclutamiento,
**para** tomar decisiones basadas en datos y mejorar continuamente.

**Descripción:**
El sistema muestra dashboards con métricas como tiempo de contratación, calidad, conversión y engagement, además de insights predictivos.

**Criterios de Aceptación:**

- ✅ Dado que el usuario accede al módulo de analytics,
  cuando selecciona un periodo o vacante,
  entonces el sistema muestra los KPIs relevantes y recomendaciones de mejora.

**Prioridad:** 🟡 Media

**Notas adicionales:**

- 🛠️ Los dashboards deben ser personalizables.
- 🔮 Los insights predictivos deben ser accionables.

**Tareas:**

- 📊 Implementar dashboards de KPIs.
- 🔮 Integrar motor de insights predictivos.
- 🗂️ Permitir filtros y personalización de vistas.

---

## User Story 6: Experiencia de Candidato Personalizada 👤✨

**Como** Candidato,
**quiero** recibir comunicación transparente y feedback automatizado sobre mi proceso,
**para** sentirme informado y valorado durante el reclutamiento.

**Descripción:**
El candidato puede ver el estado de su postulación en tiempo real, recibir notificaciones y feedback automatizado en cada etapa.

**Criterios de Aceptación:**

- ✅ Dado que el candidato aplica a una vacante,
  cuando su estatus cambia,
  entonces recibe una notificación y puede consultar el estado en la plataforma.
- ✅ Dado que el proceso avanza,
  cuando el candidato es rechazado o seleccionado,
  entonces recibe feedback automatizado y recomendaciones.

**Prioridad:** 🟡 Media

**Notas adicionales:**

- 💬 El feedback debe ser claro y constructivo.
- 📱 La comunicación debe ser multicanal (email, plataforma, SMS).

**Tareas:**

- 🔔 Implementar sistema de notificaciones y feedback automatizado.
- 👀 Desarrollar vista de estado de postulación para candidatos.
- 🔗 Integrar canales de comunicación externos.

---

## User Story 7: Gestión de Usuarios y Roles 🛡️👥

**Como** Administrador de la plataforma,
**quiero** gestionar usuarios y asignar roles (Recruiter, Hiring Manager, Stakeholder, Candidato),
**para** controlar el acceso y las responsabilidades dentro del sistema.

**Descripción:**
El administrador puede crear, editar y eliminar usuarios, así como asignar roles y permisos específicos.

**Criterios de Aceptación:**

- ✅ Dado que el administrador accede al módulo de usuarios,
  cuando crea o edita un usuario,
  entonces puede asignar un rol y definir permisos.
- ✅ Dado que un usuario cambia de rol,
  cuando el administrador lo actualiza,
  entonces los permisos se actualizan automáticamente.

**Prioridad:** 🟡 Media

**Notas adicionales:**

- 📝 Debe existir trazabilidad de cambios de roles y permisos.
- 🏢 Los roles deben ser personalizables para empresas grandes.

**Tareas:**

- 🛠️ Implementar CRUD de usuarios y roles.
- 🧩 Desarrollar lógica de permisos y trazabilidad.
- 🏢 Permitir personalización de roles por empresa.

---

## User Story 8: Integración con Canales de Publicación y Herramientas Externas 🌐🔌

**Como** Recruiter,
**quiero** integrar la plataforma con portales de empleo y herramientas externas,
**para** ampliar el alcance de mis vacantes y centralizar la gestión.

**Descripción:**
El sistema permite conectar con portales como LinkedIn, Indeed, y herramientas de correo/calendario, facilitando la publicación y seguimiento desde un solo lugar.

**Criterios de Aceptación:**

- ✅ Dado que el usuario accede a la configuración de integraciones,
  cuando conecta un canal externo,
  entonces puede publicar vacantes y recibir aplicaciones desde ese canal.

**Prioridad:** 🟢 Baja

**Notas adicionales:**

- 🔒 Las integraciones deben ser seguras y auditables.
- ➕ Permitir agregar nuevos canales fácilmente.

**Tareas:**

- 🔌 Desarrollar módulo de integraciones.
- 🌐 Implementar conectores para portales y herramientas clave.
- 📝 Crear sistema de logs y auditoría de integraciones.

---

## User Story 9: Detección y Reducción de Sesgos en el Proceso de Selección ⚖️🤖

**Como** HR Manager,
**quiero** que la IA detecte posibles sesgos en el proceso de selección,
**para** asegurar contrataciones justas y diversas.

**Descripción:**
El sistema analiza los datos y decisiones tomadas para identificar patrones de sesgo y sugiere acciones correctivas.

**Criterios de Aceptación:**

- ✅ Dado que el proceso de selección avanza,
  cuando la IA detecta un posible sesgo,
  entonces notifica al HR Manager y sugiere acciones para mitigarlo.

**Prioridad:** 🟢 Baja

**Notas adicionales:**

- 🔍 El análisis de sesgos debe ser transparente y explicable.
- 📝 Las sugerencias deben poder ser auditadas y documentadas.

**Tareas:**

- 🤖 Integrar motor de detección de sesgos.
- 🔔 Desarrollar sistema de notificaciones y sugerencias.
- 🗂️ Implementar módulo de auditoría de decisiones.

---

## User Story 10: Seguridad y Privacidad de Datos 🔒🛡️

**Como** usuario de la plataforma,
**quiero** que mis datos estén protegidos y se cumplan las normativas de privacidad,
**para** confiar en el uso del sistema.

**Descripción:**
El sistema debe garantizar la seguridad de la información, el cumplimiento de normativas (GDPR, etc.) y la gestión de consentimientos.

**Criterios de Aceptación:**

- ✅ Dado que un usuario utiliza la plataforma,
  cuando ingresa o actualiza datos personales,
  entonces el sistema asegura el cifrado y la protección de la información.
- ✅ Dado que existen normativas aplicables,
  cuando se requiere consentimiento,
  entonces el sistema solicita y registra el consentimiento del usuario.

**Prioridad:** 🔥 Alta

**Notas adicionales:**

- 📝 Debe existir registro de accesos y cambios de datos.
- 🌍 Cumplimiento de normativas internacionales.

**Tareas:**

- 🔒 Implementar cifrado de datos en tránsito y reposo.
- 📝 Desarrollar sistema de gestión de consentimientos.
- 📜 Crear logs de acceso y cambios de datos.

---

## Product Backlog - LTI ATS 📋

## Metodología de Priorización: MoSCoW 🏷️

**Razón de selección:**
La metodología MoSCoW (Must have, Should have, Could have, Won't have for now) es ampliamente utilizada en gestión ágil de productos para priorizar funcionalidades según su impacto en el éxito del MVP y la satisfacción del usuario. Permite distinguir claramente entre lo esencial, lo importante y lo deseable, facilitando la toma de decisiones y la planificación iterativa.

## Backlog Priorizado

### Must Have (Imprescindibles) 🚩

- **User Story 1:** Creación y Publicación Inteligente de Vacantes 📝🤖
- **User Story 2:** Screening y Priorización Automática de Candidatos 🕵️‍♂️⚡
- **User Story 3:** Colaboración en Decisiones de Contratación 🤝💬
- **User Story 10:** Seguridad y Privacidad de Datos 🔒🛡️

### Should Have (Importantes) 🟡

- **User Story 4:** Programación y Automatización de Entrevistas 📅🤝
- **User Story 5:** Analytics y Reporting de KPIs 📊📈
- **User Story 6:** Experiencia de Candidato Personalizada 👤✨
- **User Story 7:** Gestión de Usuarios y Roles 🛡️👥

### Could Have (Deseables) 🟢

- **User Story 8:** Integración con Canales de Publicación y Herramientas Externas 🌐🔌
- **User Story 9:** Detección y Reducción de Sesgos en el Proceso de Selección ⚖️🤖

---

## Estimación de User Stories (Impacto, Urgencia, Complejidad, Riesgos y Esfuerzo) 📏

| User Story                                                                 | Impacto en usuario y negocio         | Urgencia (mercado/feedback) | Complejidad/Esfuerzo         | Riesgos y dependencias                                                                                   | Talla camiseta | Puntos de historia |
|----------------------------------------------------------------------------|--------------------------------------|-----------------------------|------------------------------|----------------------------------------------------------------------------------------------------------|---------------|--------------------|
| 1. Creación y Publicación Inteligente de Vacantes 📝🤖                      | Alto. Es el punto de entrada clave.  | Alta. Fundamental para MVP. | Alta. IA, multicanal, UX.    | Depende de integración IA y canales externos. Riesgo: calidad de sugerencias IA.                        | XL            | 13                 |
| 2. Screening y Priorización Automática de Candidatos 🕵️‍♂️⚡               | Muy alto. Ahorra tiempo y mejora calidad. | Alta. Diferenciador de mercado. | Alta. IA, matching, feedback. | Depende de motor IA y feedback de usuarios. Riesgo: sesgos, explicabilidad del score.                   | XL            | 13                 |
| 3. Colaboración en Decisiones de Contratación 🤝💬                          | Alto. Mejora transparencia y decisiones. | Media-Alta. Tendencia colaborativa. | Media. Workspace, feedback.  | Depende de gestión de usuarios y feedback estructurado. Riesgo: adopción por stakeholders.              | L             | 8                  |
| 4. Programación y Automatización de Entrevistas 📅🤝                        | Medio. Optimiza logística.           | Media. Competencia lo ofrece. | Media. Integraciones externas. | Depende de APIs de calendario. Riesgo: fallos en integración, zonas horarias.                           | L             | 8                  |
| 5. Analytics y Reporting de KPIs 📊📈                                       | Alto. Permite mejora continua.       | Media. Valor para managers.  | Media. Dashboards, datos.     | Depende de datos de otros módulos. Riesgo: calidad de datos, visualización.                             | L             | 8                  |
| 6. Experiencia de Candidato Personalizada 👤✨                              | Alto. Mejora NPS y marca empleadora. | Media. Tendencia creciente. | Media. Notificaciones, feedback. | Depende de estados de proceso y canales de comunicación. Riesgo: saturación de notificaciones.          | M             | 5                  |
| 7. Gestión de Usuarios y Roles 🛡️👥                                        | Medio. Necesario para control y seguridad. | Media. Requisito estándar. | Media. CRUD, permisos.        | Dependencia transversal. Riesgo: errores en permisos afectan seguridad y experiencia.                   | M             | 5                  |
| 8. Integración con Canales de Publicación y Herramientas Externas 🌐🔌      | Medio. Amplía alcance y eficiencia.  | Baja-Media. Valor agregado. | Alta. Múltiples APIs.         | Depende de disponibilidad y cambios en APIs externas. Riesgo: mantenimiento y soporte.                  | XL            | 13                 |
| 9. Detección y Reducción de Sesgos en el Proceso de Selección ⚖️🤖         | Alto (estratégico, reputacional).    | Baja-Media. Tendencia ética. | Alta. IA avanzada, auditoría. | Depende de motor IA y feedback. Riesgo: falsos positivos/negativos, cumplimiento normativo.             | XL            | 13                 |
| 10. Seguridad y Privacidad de Datos 🔒🛡️                                   | Muy alto. Confianza y cumplimiento.  | Alta. Obligatorio (GDPR, etc.) | Alta. Cifrado, logs, consentimientos. | Dependencia transversal. Riesgo: multas, pérdida de confianza, requiere actualización constante.        | XL            | 13                 |

**Notas:**

- 🧵 Tallas de camiseta: XS (1), S (2), M (5), L (8), XL (13+)
- 📏 Los puntos de historia son relativos y pueden ajustarse según la experiencia del equipo.

---

## Tickets Técnicos - User Story 2: Screening y Priorización Automática de Candidatos 🕵️‍♂️⚡

### Ticket 1: Implementar Motor de Análisis Automático de CVs con IA 🤖📄

**Descripción:**
Desarrollar el componente backend que reciba CVs de candidatos, procese la información relevante y la analice utilizando modelos de IA para extraer datos clave (experiencia, habilidades, educación, etc.). Este motor será la base para el cálculo del matching score y la categorización automática.

- **Propósito:** Automatizar el análisis de CVs para reducir el tiempo manual y mejorar la precisión del screening.
- **Detalles Específicos:**
  - 🧠 Integrar librerías de procesamiento de lenguaje natural (NLP).
  - 📄 Soportar formatos PDF y DOCX.
  - 🗃️ Extraer y normalizar datos estructurados.
  - 🧮 Preparar la información para el cálculo de matching score.

**Criterios de Aceptación:**

- ✅ El sistema debe aceptar y procesar CVs en PDF y DOCX.
- ✅ Los datos extraídos deben estar disponibles en formato estructurado (JSON).
- ✅ El análisis debe ejecutarse automáticamente al recibir un nuevo CV.
- 🧪 Pruebas unitarias cubren al menos 80% del código.

**Prioridad:** 🔥 Alta

**Estimación:** 8 puntos de historia (L)

**Asignado a:** Equipo de Backend / IA

**Etiquetas:** Backend, IA, NLP, Sprint 1

**Comentarios:**

- 🚀 Considerar la escalabilidad para grandes volúmenes de CVs.
- 📝 Revisar ejemplos de CVs reales para ajustar el parser.

**Enlaces:**

- [PRD-LTI.md](./PRD-LTI.md)
- [LTI-AMP.md](./LTI-AMP.md)

**Historial de Cambios:**

- 10/06/2024: Creado por [AI Assistant]

---

### Ticket 2: Cálculo y Exposición del Matching Score de Candidatos 🧮⭐

**Descripción:**
Implementar el algoritmo que, a partir de los datos extraídos del CV y los requisitos de la vacante, calcule un matching score para cada candidato. El score debe ser transparente y explicable para los recruiters.

- **Propósito:** Priorizar candidatos de acuerdo a su ajuste con la vacante, facilitando la toma de decisiones.
- **Detalles Específicos:**
  - 📝 Definir los criterios de matching (habilidades, experiencia, educación, etc.).
  - 👁️‍🗨️ El score debe ser visible y auditable.
  - 📚 Documentar la lógica de cálculo.

**Criterios de Aceptación:**

- ✅ El sistema muestra el matching score para cada candidato.
- ✅ El score es reproducible y explicable.
- 🧪 Pruebas de integración con el motor de análisis de CVs.

**Prioridad:** 🔥 Alta

**Estimación:** 5 puntos de historia (M)

**Asignado a:** Equipo de Backend / IA

**Etiquetas:** Backend, IA, Algoritmo, Sprint 1

**Comentarios:**

- 🧑‍💼 Validar el score con casos reales y feedback de recruiters.

**Enlaces:**

- [PRD-LTI.md](./PRD-LTI.md)
- [LTI-AMP.md](./LTI-AMP.md)

**Historial de Cambios:**

- 10/06/2024: Creado por [AI Assistant]

---

### Ticket 3: Implementar Categorización y Shortlist Automática de Candidatos 🏅📋

**Descripción:**
Desarrollar la lógica que, usando el matching score, categorice automáticamente a los candidatos (A/B/C) y genere una shortlist priorizada para el recruiter.

- **Propósito:** Facilitar la selección rápida de los mejores perfiles.
- **Detalles Específicos:**
  - 🏷️ Definir umbrales para categorías A/B/C.
  - ✋ Permitir ajustes manuales por parte del recruiter.
  - 🖥️ Mostrar la shortlist en la interfaz de usuario.

**Criterios de Aceptación:**

- ✅ El sistema categoriza automáticamente a los candidatos.
- ✅ La shortlist es visible y editable por el recruiter.
- 🧪 Pruebas de usuario con feedback positivo (>80% satisfacción).

**Prioridad:** 🔥 Alta

**Estimación:** 5 puntos de historia (M)

**Asignado a:** Equipo de Backend / Frontend

**Etiquetas:** Backend, Frontend, Algoritmo, Sprint 2

**Comentarios:**

- 🤝 Alinear la experiencia de usuario con el flujo de trabajo de recruiters.

**Enlaces:**

- [PRD-LTI.md](./PRD-LTI.md)
- [LTI-AMP.md](./LTI-AMP.md)

**Historial de Cambios:**

- 10/06/2024: Creado por [AI Assistant]

---

### Ticket 4: Interfaz de Visualización y Feedback de Shortlist para Recruiters 🖥️💬

**Descripción:**
Diseñar e implementar la interfaz de usuario donde los recruiters puedan visualizar la shortlist, los scores y categorías, y proporcionar feedback para mejorar el sistema.

- **Propósito:** Hacer accesible y usable la información priorizada, permitiendo interacción y mejora continua del sistema.
- **Detalles Específicos:**
  - 📋 Mostrar lista priorizada, scores y categorías.
  - 💬 Permitir feedback y ajustes manuales.
  - 🔔 Integrar notificaciones de nuevos candidatos.

**Criterios de Aceptación:**

- ✅ La interfaz es intuitiva y responsiva.
- ✅ El recruiter puede dejar feedback y ajustar la shortlist.
- 🧪 Pruebas de usabilidad con resultados satisfactorios (>80% satisfacción).

**Prioridad:** 🔥 Alta

**Estimación:** 8 puntos de historia (L)

**Asignado a:** Equipo de Frontend

**Etiquetas:** Frontend, UI/UX, Sprint 2

**Comentarios:**

- 🧑‍💻 Validar el diseño con usuarios finales antes de desarrollo completo.

**Enlaces:**

- [PRD-LTI.md](./PRD-LTI.md)
- [LTI-AMP.md](./LTI-AMP.md)

**Historial de Cambios:**

- 10/06/2024: Creado por [AI Assistant]

---

### Ticket 5: Integración y Pruebas de Todo el Flujo de Screening Automático 🔗🧪

**Descripción:**
Realizar la integración de todos los componentes desarrollados (análisis de CVs, matching score, categorización, interfaz) y ejecutar pruebas end-to-end para asegurar el correcto funcionamiento del flujo completo de screening automático.

- **Propósito:** Garantizar que el proceso de screening automático funcione de manera robusta y confiable en condiciones reales.
- **Detalles Específicos:**
  - 🧪 Pruebas de integración y validación de datos.
  - 🧑‍💻 Simulación de flujos reales con datos de prueba.
  - 📄 Documentar resultados y posibles mejoras.

**Criterios de Aceptación:**

- ✅ El flujo completo funciona sin errores críticos.
- ✅ Los resultados cumplen con los criterios de negocio y usuario.
- 📄 Reporte de pruebas documentado y compartido con el equipo.

**Prioridad:** 🔥 Alta

**Estimación:** 8 puntos de historia (L)

**Asignado a:** Equipo de QA / Backend / Frontend

**Etiquetas:** QA, Integración, Sprint 3

**Comentarios:**

- 🧑‍💼 Incluir feedback de usuarios reales en la validación final.

**Enlaces:**

- [PRD-LTI.md](./PRD-LTI.md)
- [LTI-AMP.md](./LTI-AMP.md)

**Historial de Cambios:**

- 10/06/2024: Creado por [AI Assistant]
