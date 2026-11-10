# Tablero Scrum — Sistema de Gestión de Archivos CONTEC

**Ingeniería de Software I · Paralelo 3 · 2026 PAO II · Grupo 4 "Nucitas"**

Este tablero es la evidencia de la metodología que seguimos para elaborar la Especificación de Requerimientos de Software (ERS). Trabajamos con Scrum adaptado a la ingeniería de requerimientos: cuatro sprints, uno por cada fase descrita en la sección 3.1 de la ERS. El backlog del producto se escribió como historias de usuario con el formato de Mike Cohn y se revisó con los criterios INVEST.

---

## 1. Equipo Scrum

| Integrante | Rol Scrum | Responsabilidad en el tablero |
|---|---|---|
| Misael José Moreira Moreno | Product Owner | Prioriza el backlog, valida las HU con el cliente CONTEC |
| Braulio Alexander Neira Villón | Scrum Master | Organiza los sprints, mantiene el tablero y las evidencias |
| Danna Stefania Urdanigo Ochoa | Diseñadora UX | Prototipo web/móvil y flujo de ventanas de cada HU |
| Kevin Fernando Maldonado Paredes | Analista QA | Criterios de aceptación, RNF y métodos de verificación |

**Cliente:** Consultoría Técnica Cía. Ltda. (CONTEC), a través de su representante y del área de IT.

---

## 2. Sprints

| Sprint | Fase (ERS §3.1) | Objetivo del sprint | Fechas |
|---|---|---|---|
| Sprint 1 | Elicitación y descubrimiento | Entender el problema de CONTEC y levantar necesidades con entrevistas y observación | dd/mm – dd/mm |
| Sprint 2 | Análisis y negociación | Convertir las necesidades en historias de usuario, priorizarlas y estimarlas | dd/mm – dd/mm |
| Sprint 3 | Especificación | Redactar RF, RNF (Sommerville), criterios de validación y prototipo | dd/mm – dd/mm |
| Sprint 4 | Validación y verificación | Revisar ERS y prototipo con el cliente y obtener el acta de conformidad | dd/mm – 09/11 |

---

## 3. Tablero Kanban de tareas del proceso

| Sprint | Tarea | Responsable | Técnica / artefacto | Estado |
|---|---|---|---|---|
| S1 | Crear el repositorio público del proyecto | Danna | Repositorio GitHub | ✅ Hecho |
| S1 | Preparar el guion de la entrevista semiestructurada | Misael, Braulio | Guion de entrevista | ✅ Hecho |
| S1 | Entrevista con el representante de CONTEC e IT | Misael | Entrevista semiestructurada | ✅ Hecho |
| S1 | Observación directa del trabajo de oficina y campo | Misael | Observación / etnografía | ✅ Hecho |
| S1 | Redactar la minuta de la reunión y subir evidencias | Braulio | Minuta, notas | ✅ Hecho |
| S2 | Redactar el backlog de historias de usuario (HU-01 a HU-10) | Todos | Historias de usuario | ✅ Hecho |
| S2 | Priorizar el backlog con MoSCoW | Misael | Priorización MoSCoW | ✅ Hecho |
| S2 | Estimar las HU en story points | Todos | Planning Poker (Fibonacci) | ✅ Hecho |
| S2 | Escribir escenarios y casos de uso | Braulio, Danna | Escenarios / casos de uso | ✅ Hecho |
| S2 | Resolver conflictos entre RF y RNF | Kevin | Negociación de requerimientos | ✅ Hecho |
| S3 | Redactar la tabla de requerimientos funcionales | Misael, Braulio | Tabla RF (IEEE 830 / 29148) | ✅ Hecho |
| S3 | Clasificar los RNF según Sommerville con criterio de validación | Kevin | Taxonomía de Sommerville | ✅ Hecho |
| S3 | Definir el método de verificación de cada requerimiento | Kevin | Prueba, inspección, análisis, demostración | ✅ Hecho |
| S3 | Prototipo del panel web y de la app móvil | Danna | Prototipo de alta fidelidad | ✅ Hecho |
| S3 | Diagrama de flujo de ventanas | Danna | Flujo de navegación | ✅ Hecho |
| S3 | Maquetar el documento ERS | Braulio | Plantilla ERS | ✅ Hecho |
| S4 | Revisar la ERS con el cliente | Misael | Revisión de requerimientos | ✅ Hecho |
| S4 | Recorrer el prototipo con el cliente | Danna, Misael | Validación con prototipo | ✅ Hecho |
| S4 | Aplicar las correcciones del cliente | Todos | Control de cambios | ✅ Hecho |
| S4 | Obtener el acta de conformidad firmada | Misael | Acta de conformidad | ✅ Hecho |
| S4 | Revisar ortografía y consistencia cruzada | Kevin | Inspección del documento | ✅ Hecho |
| S4 | Entregar en Aula Virtual | Braulio | Entrega | ✅ Hecho |

---

## 4. Product Backlog — Historias de usuario

Prioridad MoSCoW: la prioridad **Alta** de la ERS corresponde a **Must**, y la **Media** a **Should**.
Story points en escala Fibonacci (1, 2, 3, 5, 8, 13).
Estado del requerimiento: `Identificada → Especificada → Prototipada → Validada con cliente`.

| ID | Historia de usuario | RF | Prioridad | SP | Responsable | Estado |
|---|---|---|---|---|---|---|
| HU-01 | Cargar archivos con sus metadatos | RF-001 | Must | 5 | Misael | Validada con cliente |
| HU-02 | Asociar y desasociar archivos con clientes o técnicos | RF-002 | Must | 5 | Misael | Validada con cliente |
| HU-03 | Buscar archivos combinando filtros | RF-003 | Must | 8 | Braulio | Validada con cliente |
| HU-04 | Ver el listado general de archivos | RF-004 | Must | 3 | Danna | Validada con cliente |
| HU-05 | Previsualizar archivos sin descargarlos | RF-005 | Should | 5 | Danna | Validada con cliente |
| HU-06 | Descargar archivos en su formato original | RF-006 | Must | 3 | Kevin | Validada con cliente |
| HU-07 | Eliminar archivos con confirmación | RF-007 | Must | 3 | Kevin | Validada con cliente |
| HU-08 | Consultar el directorio de clientes y técnicos | RF-008 | Should | 3 | Braulio | Validada con cliente |
| HU-09 | Administrar cuentas de usuario | RF-009 | Should | 5 | Misael | Validada con cliente |
| HU-10 | Configurar permisos por rol o cuenta | RF-010 | Should | 8 | Kevin | Validada con cliente |
| | | | **Total** | **48** | | |

---

## 5. Detalle de las historias de usuario

Formato: *Como <rol>, quiero <acción>, para <beneficio>*. Los criterios de aceptación están escritos en estilo **Dado / Cuando / Entonces**.

### HU-01 · Cargar archivos con sus metadatos
**Trazabilidad:** RF-001, RNF-009 · **Prioridad:** Must · **SP:** 5

> **Como** gestor de proyectos, **quiero** cargar archivos al repositorio indicando su nombre y categoría, **para** que toda la documentación del proyecto quede centralizada en un solo lugar.

**Criterios de aceptación**
1. **Dado** que estoy autenticado en la pantalla "Subir archivo", **cuando** adjunto un archivo de hasta 50 MB y completo nombre y categoría, **entonces** el archivo se guarda y la fecha de carga queda registrada automáticamente.
2. **Dado** que falta el nombre o la categoría, **cuando** intento guardar, **entonces** el sistema no guarda el archivo y señala el campo que falta.
3. **Dado** un archivo de más de 50 MB, **cuando** intento subirlo, **entonces** el sistema lo rechaza en menos de 1 segundo con un mensaje claro.

---

### HU-02 · Asociar y desasociar archivos con clientes o técnicos
**Trazabilidad:** RF-002 · **Prioridad:** Must · **SP:** 5

> **Como** gestor de proyectos, **quiero** asociar un proyecto o archivo con uno o varios clientes o técnicos, **para** saber quiénes están involucrados en cada documento.

**Criterios de aceptación**
1. **Dado** un archivo almacenado, **cuando** selecciono uno o varios clientes o técnicos registrados, **entonces** quedan asociados y aparecen en el listado del archivo.
2. **Dado** un archivo con asociaciones, **cuando** quito a una persona, **entonces** la asociación desaparece sin afectar a las demás.
3. **Dado** una cédula que no está registrada, **cuando** intento asociarla, **entonces** el sistema no lo permite e informa que la persona no existe.

---

### HU-03 · Buscar archivos combinando filtros
**Trazabilidad:** RF-003, RNF-005 · **Prioridad:** Must · **SP:** 8

> **Como** técnico de campo, **quiero** buscar archivos combinando nombre, cédula asociada, categoría y rango de fechas, **para** encontrar rápido el documento que necesito sin revisar todo el repositorio.

**Criterios de aceptación**
1. **Dado** que aplico dos o más filtros, **cuando** ejecuto la búsqueda, **entonces** solo aparecen los archivos que cumplen todos los criterios a la vez.
2. **Dado** que ningún archivo cumple los filtros, **cuando** busco, **entonces** el sistema muestra "No se encontraron resultados".
3. **Dado** un rango en el que la fecha inicial es posterior a la final, **cuando** busco, **entonces** el sistema muestra un error y no ejecuta la búsqueda.
4. **Dado** un catálogo de hasta 100 000 registros, **cuando** busco, **entonces** los resultados aparecen en 1,5 segundos o menos.

---

### HU-04 · Ver el listado general de archivos
**Trazabilidad:** RF-004 · **Prioridad:** Must · **SP:** 3

> **Como** directivo, **quiero** ver en una tabla todos los archivos almacenados con sus datos principales, **para** tener una visión general de la documentación de los proyectos.

**Criterios de aceptación**
1. **Dado** que entro al módulo de archivos, **cuando** carga la pantalla, **entonces** veo una tabla con nombre, categoría, fecha de carga y entidades asociadas.
2. **Dado** un archivo eliminado (HU-07), **cuando** veo el listado, **entonces** ese archivo ya no aparece.

---

### HU-05 · Previsualizar archivos sin descargarlos
**Trazabilidad:** RF-005 · **Prioridad:** Should · **SP:** 5

> **Como** gestor de proyectos, **quiero** previsualizar los archivos en el navegador, **para** revisar su contenido rápido sin tener que descargarlos.

**Criterios de aceptación**
1. **Dado** un archivo de formato compatible (por ejemplo PDF o imagen), **cuando** pulso "Previsualizar", **entonces** se abre en un visor dentro del sistema.
2. **Dado** un archivo de formato no compatible, **cuando** pulso "Previsualizar", **entonces** el sistema informa que no se puede previsualizar y ofrece descargarlo.

---

### HU-06 · Descargar archivos en su formato original
**Trazabilidad:** RF-006, RNF-003, RNF-006 · **Prioridad:** Must · **SP:** 3

> **Como** técnico autorizado, **quiero** descargar una copia del archivo en su formato original, **para** trabajar con él en mi equipo o en campo.

**Criterios de aceptación**
1. **Dado** que tengo permiso de descarga, **cuando** pulso "Descargar", **entonces** recibo el archivo con su nombre y extensión originales.
2. **Dado** un archivo descargado, **cuando** comparo su hash SHA-256 con el almacenado en el servidor, **entonces** los dos son idénticos.
3. **Dado** un usuario sin permiso de descarga, **cuando** intenta acceder a la URL directa del archivo, **entonces** el sistema responde 403 Forbidden.

---

### HU-07 · Eliminar archivos con confirmación
**Trazabilidad:** RF-007 · **Prioridad:** Must · **SP:** 3

> **Como** gestor de proyectos autorizado, **quiero** eliminar archivos confirmando antes la acción, **para** limpiar el repositorio sin borrar documentos por accidente.

**Criterios de aceptación**
1. **Dado** que pulso "Eliminar", **cuando** aparece el diálogo de confirmación y pulso "Cancelar", **entonces** el archivo no cambia.
2. **Dado** que confirmo la eliminación, **cuando** termina la acción, **entonces** el archivo deja de aparecer en el listado y en las búsquedas, pero su registro se conserva en la base de datos marcado como eliminado (eliminación lógica).

---

### HU-08 · Consultar el directorio de clientes y técnicos
**Trazabilidad:** RF-008 · **Prioridad:** Should · **SP:** 3

> **Como** gestor de proyectos, **quiero** buscar clientes y técnicos por cédula o especialidad, **para** encontrar y asignar a la persona adecuada para cada proyecto.

**Criterios de aceptación**
1. **Dado** una cédula registrada, **cuando** la busco, **entonces** el sistema muestra los datos de esa persona.
2. **Dado** una especialidad, **cuando** la busco, **entonces** aparecen todas las personas con esa especialidad.
3. **Dado** una cédula con formato inválido, **cuando** la busco, **entonces** el sistema indica que el formato es incorrecto.

---

### HU-09 · Administrar cuentas de usuario
**Trazabilidad:** RF-009, RNF-002 · **Prioridad:** Should · **SP:** 5

> **Como** administrador, **quiero** registrar, consultar, modificar, activar y desactivar cuentas de usuario, **para** controlar quién usa el sistema.

**Criterios de aceptación**
1. **Dado** el formulario de nuevo usuario con los datos obligatorios completos, **cuando** guardo, **entonces** se crea la cuenta y la contraseña queda almacenada cifrada con hash y sal.
2. **Dado** una cuenta activa, **cuando** la desactivo, **entonces** ese usuario ya no puede iniciar sesión.
3. **Dado** una cuenta desactivada, **cuando** la reactivo, **entonces** el usuario puede volver a iniciar sesión.
4. **Dado** un correo o cédula que ya está registrado, **cuando** intento crear otra cuenta con él, **entonces** el sistema no lo permite.

---

### HU-10 · Configurar permisos por rol o cuenta
**Trazabilidad:** RF-010, RNF-003 · **Prioridad:** Should · **SP:** 8

> **Como** administrador, **quiero** asignar y revocar permisos de acceso a cada rol o cuenta, **para** que cada persona solo pueda hacer lo que le corresponde.

**Criterios de aceptación**
1. **Dado** un rol, **cuando** le asigno un permiso (por ejemplo "eliminar archivos"), **entonces** los usuarios con ese rol ven y pueden usar esa función.
2. **Dado** que revoco un permiso, **cuando** el usuario intenta usar esa función o su URL directa, **entonces** la opción ya no aparece y el sistema responde 403 Forbidden.

---

## 6. Definition of Ready (DoR)

Una historia de usuario entra a un sprint de especificación solo si:
- [ ] Sigue el formato *Como / quiero / para* e identifica el rol de CONTEC.
- [ ] Cumple INVEST: independiente, negociable, valiosa, estimable, pequeña y testeable.
- [ ] Tiene prioridad MoSCoW asignada por el Product Owner.
- [ ] Tiene una estimación en story points.

## 7. Definition of Done (DoD)

Una historia de usuario está terminada cuando:
- [ ] Tiene al menos dos criterios de aceptación verificables.
- [ ] Está trazada a un RF de la ERS y a los RNF relacionados.
- [ ] Tiene un método de verificación definido.
- [ ] Tiene pantalla en el prototipo y aparece en el flujo de ventanas.
- [ ] Fue revisada y aceptada por el cliente CONTEC.

---

## 8. Matriz de trazabilidad

| HU | RF | RNF relacionados | Pantalla del prototipo |
|---|---|---|---|
| HU-01 | RF-001 | RNF-009 | Subir archivo |
| HU-02 | RF-002 | — | Detalle de archivo / asociaciones |
| HU-03 | RF-003 | RNF-005 | Búsqueda y filtros |
| HU-04 | RF-004 | RNF-007 | Listado de archivos |
| HU-05 | RF-005 | — | Visor de archivo |
| HU-06 | RF-006 | RNF-003, RNF-006 | Listado / visor (botón Descargar) |
| HU-07 | RF-007 | — | Diálogo de confirmación |
| HU-08 | RF-008 | — | Directorio de clientes y técnicos |
| HU-09 | RF-009 | RNF-002 | Administración de usuarios |
| HU-10 | RF-010 | RNF-003 | Administración de roles y permisos |
| Todas | — | RNF-001, RNF-004, RNF-008, RNF-010 | Transversal (sesión, usabilidad, HTTPS, disponibilidad) |

> La numeración de RNF usada aquí es la de la **Tabla 2** de la ERS.
