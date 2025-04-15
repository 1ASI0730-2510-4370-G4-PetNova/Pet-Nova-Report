# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

- **Primer segmento: Médicos Veterinarios**

<br><img src="" alt="" style="width: 1000px; height: auto;" ><br>

- **Segundo segmento: Dueños de Mascotas**

<br><img src="" alt="" style="width: 1000px; height: auto;" ><br>


## 3.2. User Stories
# Gestión de Usuarios
**EP01: Como responsable del sistema, quiero administrar los usuarios para garantizar que solo personas autorizadas accedan a la plataforma.**

| User Story ID | Título                          | Descripción                                                                                                               |
|---------------|----------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| US01          | Creación de Cuenta               | Como visitante, quiero crear una cuenta en la plataforma para acceder a sus funcionalidades.                             |
| US02          | Recuperación de Acceso           | Como usuario, quiero recuperar mi contraseña en caso de olvidarla para no perder acceso a mi perfil.                     |
| US03          | Administración de Perfiles       | Como responsable, quiero gestionar los perfiles de los usuarios para asegurarme de que su información y permisos estén actualizados. |

---

# Gestión de Mascotas
**EP02: Como usuario, quiero manejar la información de mis mascotas para mantener sus datos al día.**

| User Story ID | Título                            | Descripción                                                                                                               |
|---------------|------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| US04          | Registro de Mascota                | Como usuario, quiero registrar un perfil de mi mascota para guardar su información en la plataforma.                    |
| US05          | Actualización de Datos de Mascota  | Como usuario, quiero editar el perfil de mi mascota para mantener su información actualizada.                           |
| US06          | Consulta de Perfiles de Mascotas   | Como usuario, quiero poder ver los perfiles de mis mascotas para revisar sus datos.                                     |
| US07          | Búsqueda por Identificador         | Como responsable, quiero buscar mascotas por su ID para acceder rápidamente a su información.                           |
| US08          | Administración de Perfiles de Mascotas | Como responsable, quiero gestionar los perfiles de mascotas para verificar que los datos estén correctos y actualizados. |

---

# Gestión de Citas Veterinarias
**EP03: Como usuario, quiero organizar las citas médicas de mis mascotas para asegurar su atención oportuna.**

| User Story ID | Título                         | Descripción                                                                                                               |
|---------------|---------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| US09          | Programación de Citas           | Como usuario, quiero agendar citas veterinarias para garantizar que mi mascota reciba atención médica a tiempo.         |
| US10          | Cancelación de Citas            | Como usuario, quiero cancelar una cita cuando no puedo asistir para reorganizarla si es necesario.                      |
| US11          | Control de Citas                 | Como responsable, quiero gestionar las citas para coordinar eficientemente las consultas.                               |
| US12          | Búsqueda de Citas                | Como responsable, quiero buscar citas usando su ID para acceder a sus detalles rápidamente.                             |
| US13          | Edición de Citas                 | Como responsable, quiero modificar los datos de las citas para realizar ajustes cuando se requiera.                     |

---

# Gestión de Notificaciones
**EP04: Como usuario, quiero recibir alertas sobre eventos importantes relacionados con mis mascotas para estar siempre informado.**

| User Story ID | Título                            | Descripción                                                                                                               |
|---------------|------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| US14          | Alerta de Citas Médicas            | Como usuario, quiero recibir recordatorios sobre citas veterinarias para no olvidar los compromisos.                    |
| US15          | Alerta de Actualizaciones Médicas  | Como usuario, quiero recibir notificaciones cuando se actualiza el historial médico de mi mascota.                      |
| US16          | Gestión de Alertas                 | Como responsable, quiero manejar el envío de notificaciones para asegurar que la información importante llegue a tiempo. |

---

# Navegación y Funcionalidades de la Página Principal
**EP05: Como visitante, quiero explorar la página de inicio de Pawfect Care para conocer sus servicios y funcionalidades.**

| User Story ID | Título                                        | Descripción                                                                                                               |
|---------------|------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| US17          | Menú de Navegación                             | Como visitante, quiero utilizar la barra de navegación para moverme fácilmente por las secciones del sitio.             |
| US18          | Sección “¿Por qué elegirnos?”                  | Como visitante, quiero consultar esta sección para comprender los beneficios que ofrece la plataforma.                  |
| US19          | Vista de Planes de Suscripción                 | Como visitante, quiero ver los planes disponibles para escoger el que mejor se adapte a mis necesidades.                |
| US20          | Opiniones de Clientes                          | Como visitante, quiero leer reseñas de otros usuarios para evaluar su experiencia con Pawfect Care.                     |
| US21          | Formulario de Contacto                         | Como visitante, quiero enviar un mensaje desde la landing page para comunicarme con el equipo.                          |
| US22          | Videos de Características                      | Como visitante, quiero visualizar videos explicativos para conocer más sobre los productos y servicios ofrecidos.       |

---

# Gestión de Clientes
**EP06: Como responsable, quiero manejar la información de los clientes para mantener un registro ordenado y actualizado.**

| User Story ID | Título                          | Descripción                                                                                                               |
|---------------|----------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| US24          | Alta de Clientes                 | Como responsable, quiero registrar perfiles de clientes con sus datos y mascotas asociadas.                             |
| US25          | Edición de Información del Cliente | Como responsable, quiero actualizar los perfiles para reflejar cambios en los datos personales o de contacto.           |
| US26          | Búsqueda de Clientes             | Como responsable, quiero buscar clientes mediante su ID para encontrar su información rápidamente.                      |

---

# Gestión de Eventos Veterinarios
**EP07: Como administrador o veterinario, quiero manejar los eventos veterinarios para asegurar la atención adecuada de los animales.**

| User Story ID | Título                             | Descripción                                                                                                               |
|---------------|-------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| US27          | Creación de Eventos Médicos         | Como responsable, quiero registrar eventos como vacunaciones o chequeos para mantener el historial de atención.          |
| US28          | Modificación de Eventos             | Como responsable, quiero editar eventos para corregir datos o añadir información relevante.                             |
| US29          | Localización de Eventos             | Como responsable, quiero buscar eventos por su ID para acceder fácilmente a su información.                             |
| US30          | Control del Estado de los Eventos   | Como responsable, quiero actualizar el estado de los eventos (pendiente, completado, etc.) según su avance.             |

---

# Gestión del Historial Médico de las Mascotas
**EP08: Como usuario o responsable, quiero gestionar el historial de salud de las mascotas para llevar un control de sus tratamientos.**

| User Story ID | Título                            | Descripción                                                                                                               |
|---------------|------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| US31          | Consulta del Historial Médico      | Como usuario, quiero revisar el historial médico de mi mascota para conocer su estado de salud y antecedentes.           |
| US32          | Actualización del Historial        | Como responsable o veterinario, quiero actualizar el historial médico para reflejar los tratamientos más recientes.      |

---

# Funcionalidades de Idioma en la App Web
**EP09: Como usuario, quiero cambiar el idioma de la plataforma para utilizarla en español o inglés según mi preferencia.**

| User Story ID | Título                        | Descripción                                                                                                               |
|---------------|-------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| US23          | Selector de Idioma            | Como usuario, quiero cambiar entre los idiomas disponibles para navegar cómodamente por la aplicación.                   |

<br><br>
# Historias de Usuario y Criterios de Aceptación

## **US01: Creación de Historia Clínica para una Mascota**
**Relacionado con (Epic ID):** EP01  

**Descripción:**  
Como veterinario, quiero crear una historia clínica para cada mascota que ingrese, para mantener un registro completo de su salud y tratamiento.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El veterinario crea una nueva historia clínica  
  - **Dado que** el veterinario está en la página de creación de historia clínica,  
  - **Cuando** ingresa todos los datos necesarios (nombre de la mascota, diagnóstico, tratamiento, etc.),  
  - **Entonces** el sistema debe guardar la historia clínica y mostrar un mensaje de confirmación.

- **Escenario 2:** El veterinario no puede crear una historia clínica sin los campos obligatorios  
  - **Dado que** el veterinario está en la página de creación de historia clínica,  
  - **Cuando** intenta guardar la historia clínica sin llenar los campos obligatorios,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que faltan campos obligatorios.

---

## **US02: Consulta de Historia Clínica de una Mascota**
**Relacionado con (Epic ID):** EP02  

**Descripción:**  
Como veterinario, quiero poder consultar la historia clínica de una mascota para revisar su historial médico antes de realizar una consulta.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El veterinario consulta la historia clínica de una mascota  
  - **Dado que** el veterinario está en la página de la mascota,  
  - **Cuando** selecciona la opción de ver la historia clínica,  
  - **Entonces** el sistema debe mostrar toda la información registrada de esa mascota, incluyendo diagnósticos y tratamientos previos.

- **Escenario 2:** El veterinario no puede ver historias clínicas de mascotas que no ha atendido  
  - **Dado que** el veterinario no ha atendido a una mascota,  
  - **Cuando** intenta acceder a la historia clínica de esa mascota,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que no tiene acceso a esa información.

---

## **US03: Actualización de Datos de la Mascota**
**Relacionado con (Epic ID):** EP03  

**Descripción:**  
Como propietario de la mascota, quiero poder actualizar la información de mi mascota (nombre, raza, edad, etc.), para mantener los datos correctos en la historia clínica.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El propietario actualiza la información de su mascota  
  - **Dado que** el propietario está en la página de su mascota,  
  - **Cuando** edita la información de la mascota,  
  - **Entonces** el sistema debe guardar los cambios y mostrar un mensaje de confirmación.

- **Escenario 2:** El propietario no puede actualizar la información de una mascota que no le pertenece  
  - **Dado que** el propietario no es el dueño de una mascota,  
  - **Cuando** intenta actualizar los datos de esa mascota,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que no tiene permisos.

---

## **US04: Agregar Diagnóstico y Tratamiento en la Historia Clínica**
**Relacionado con (Epic ID):** EP01  

**Descripción:**  
Como veterinario, quiero poder agregar diagnósticos y tratamientos en la historia clínica de la mascota, para mantener un registro detallado de su atención.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El veterinario agrega un diagnóstico y tratamiento  
  - **Dado que** el veterinario está en la página de la historia clínica,  
  - **Cuando** ingresa un diagnóstico y tratamiento,  
  - **Entonces** el sistema debe guardar la información y actualizar la historia clínica.

- **Escenario 2:** El veterinario no puede dejar campos obligatorios vacíos  
  - **Dado que** el veterinario está ingresando un diagnóstico y tratamiento,  
  - **Cuando** no completa los campos obligatorios,  
  - **Entonces** el sistema debe mostrar un mensaje de advertencia indicando que los campos obligatorios deben completarse.

---

## **US05: Ver Historial de Consultas Médicas**
**Relacionado con (Epic ID):** EP02  

**Descripción:**  
Como propietario de la mascota, quiero poder ver el historial de consultas médicas realizadas a mi mascota, para saber qué tratamientos ha recibido.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El propietario ve el historial médico de su mascota  
  - **Dado que** el propietario está en la página de su mascota,  
  - **Cuando** selecciona la opción de ver el historial médico,  
  - **Entonces** el sistema debe mostrar un listado con las consultas anteriores y sus detalles.

- **Escenario 2:** El propietario no puede ver el historial médico de otras mascotas  
  - **Dado que** el propietario no tiene acceso al historial de otras mascotas,  
  - **Cuando** intenta acceder al historial de otra mascota,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que no tiene permisos.

---

## **US06: Generación de Reporte de Mascotas**
**Relacionado con (Epic ID):** EP05  

**Descripción:**  
Como administrador, quiero poder generar un reporte con las mascotas que han sido atendidas en un periodo determinado, para tener un control de las consultas realizadas.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El administrador genera un reporte de mascotas atendidas  
  - **Dado que** el administrador está en la sección de reportes,  
  - **Cuando** selecciona un rango de fechas y genera el reporte,  
  - **Entonces** el sistema debe mostrar un reporte con todas las mascotas atendidas en ese periodo.

- **Escenario 2:** El administrador no puede generar un reporte sin establecer un rango de fechas  
  - **Dado que** el administrador no ha seleccionado un rango de fechas,  
  - **Cuando** intenta generar el reporte,  
  - **Entonces** el sistema debe mostrar un mensaje de advertencia indicando que debe seleccionar un rango de fechas.

---

## **US07: Registro de Vacunas en la Historia Clínica**
**Relacionado con (Epic ID):** EP01  

**Descripción:**  
Como veterinario, quiero poder registrar las vacunas aplicadas a una mascota, para mantener un control adecuado de su salud preventiva.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El veterinario registra una vacuna en la historia clínica  
  - **Dado que** el veterinario está en la página de la historia clínica de la mascota,  
  - **Cuando** agrega la vacuna aplicada,  
  - **Entonces** el sistema debe registrar la vacuna y mostrar un mensaje de confirmación.

- **Escenario 2:** El veterinario no puede registrar una vacuna sin fecha  
  - **Dado que** el veterinario está registrando una vacuna,  
  - **Cuando** no ingresa la fecha de aplicación,  
  - **Entonces** el sistema debe mostrar un mensaje de advertencia indicando que la fecha es obligatoria.

---

## **US08: Edición de Diagnóstico en la Historia Clínica**
**Relacionado con (Epic ID):** EP03  

**Descripción:**  
Como veterinario, quiero poder editar un diagnóstico previamente registrado en la historia clínica, para corregir posibles errores o actualizar la información.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El veterinario edita un diagnóstico existente  
  - **Dado que** el veterinario está en la página de la historia clínica,  
  - **Cuando** selecciona el diagnóstico a editar y realiza los cambios,  
  - **Entonces** el sistema debe actualizar el diagnóstico y mostrar un mensaje de confirmación.

- **Escenario 2:** El veterinario no puede editar un diagnóstico que ha sido cerrado  
  - **Dado que** el diagnóstico ha sido marcado como cerrado,  
  - **Cuando** el veterinario intenta editarlo,  
  - **Entonces** el sistema debe mostrar un mensaje indicando que el diagnóstico ya está cerrado y no se puede editar.

---

## **US09: Asignación de Veterinario a una Mascota**
**Relacionado con (Epic ID):** EP04  

**Descripción:**  
Como administrador, quiero poder asignar un veterinario a cada mascota, para que el veterinario sea responsable del seguimiento de su tratamiento.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El administrador asigna un veterinario a una mascota  
  - **Dado que** el administrador está en la página de detalles de la mascota,  
  - **Cuando** selecciona un veterinario para asignarle a la mascota,  
  - **Entonces** el sistema debe actualizar la información de la mascota y mostrar un mensaje de confirmación.

- **Escenario 2:** El administrador no puede asignar un veterinario si no está disponible  
  - **Dado que** el veterinario está asignado a otras mascotas o no está disponible,  
  - **Cuando** el administrador intenta asignarlo,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que el veterinario no está disponible.

---
## **US10: Registro de Resultados de Análisis Clínicos**
**Relacionado con (Epic ID):** EP01  

**Descripción:**  
Como veterinario, quiero registrar los resultados de los análisis clínicos realizados a una mascota, para tener un historial completo y actualizado de su salud.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El veterinario registra los resultados de un análisis  
  - **Dado que** el veterinario está en la página de la historia clínica,  
  - **Cuando** ingresa los resultados de un análisis clínico,  
  - **Entonces** el sistema debe guardar los resultados y actualizar la historia clínica de la mascota.

- **Escenario 2:** El veterinario no puede dejar campos de los resultados en blanco  
  - **Dado que** el veterinario está registrando los resultados de un análisis,  
  - **Cuando** no ingresa todos los datos requeridos,  
  - **Entonces** el sistema debe mostrar un mensaje de advertencia indicando que los campos no pueden estar vacíos.

---

## **US11: Notificación de Próxima Cita**
**Relacionado con (Epic ID):** EP06  

**Descripción:**  
Como propietario de una mascota, quiero recibir notificaciones de la próxima cita médica de mi mascota, para asegurarme de que no olvido la cita.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El propietario recibe una notificación de cita  
  - **Dado que** la cita está programada,  
  - **Cuando** la fecha de la cita se acerca,  
  - **Entonces** el sistema debe enviar una notificación al propietario.

- **Escenario 2:** El propietario no recibe una notificación si la cita está cancelada  
  - **Dado que** la cita fue cancelada,  
  - **Cuando** la fecha de la cita se acerca,  
  - **Entonces** el sistema no debe enviar una notificación.

---

## **US12: Generación de Factura para Consultas**
**Relacionado con (Epic ID):** EP05  

**Descripción:**  
Como administrador, quiero generar una factura para cada consulta realizada, para llevar un control de los pagos y servicios prestados.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El administrador genera una factura  
  - **Dado que** la consulta ha sido completada,  
  - **Cuando** el administrador selecciona la opción de generar factura,  
  - **Entonces** el sistema debe generar y mostrar la factura correspondiente.

- **Escenario 2:** El administrador no puede generar una factura sin información de pago  
  - **Dado que** el pago de la consulta no ha sido registrado,  
  - **Cuando** el administrador intenta generar la factura,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que no puede generarse la factura sin los datos de pago.

---

## **US13: Búsqueda de Mascota por Nombre**
**Relacionado con (Epic ID):** EP02  

**Descripción:**  
Como veterinario, quiero poder buscar la historia clínica de una mascota por su nombre, para acceder rápidamente a su información.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El veterinario busca una mascota por su nombre  
  - **Dado que** el veterinario está en la página de búsqueda,  
  - **Cuando** ingresa el nombre de la mascota,  
  - **Entonces** el sistema debe mostrar las coincidencias relevantes.

- **Escenario 2:** El veterinario no encuentra mascotas con un nombre incorrecto  
  - **Dado que** el veterinario está buscando una mascota por su nombre,  
  - **Cuando** ingresa un nombre incorrecto o inexistente,  
  - **Entonces** el sistema debe mostrar un mensaje indicando que no se encontraron resultados.

---

## **US14: Actualización de Información de Propietario**
**Relacionado con (Epic ID):** EP03  

**Descripción:**  
Como propietario de una mascota, quiero poder actualizar mi información de contacto, para asegurarme de que el veterinario pueda contactarme si es necesario.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El propietario actualiza su información de contacto  
  - **Dado que** el propietario está en la página de su perfil,  
  - **Cuando** edita sus datos de contacto,  
  - **Entonces** el sistema debe guardar los cambios y mostrar un mensaje de confirmación.

- **Escenario 2:** El propietario no puede dejar el campo de correo electrónico vacío  
  - **Dado que** el propietario está actualizando su información,  
  - **Cuando** no ingresa una dirección de correo electrónico válida,  
  - **Entonces** el sistema debe mostrar un mensaje de advertencia indicando que el correo electrónico es obligatorio.

---

## **US15: Asignación de Horarios de Citas a Veterinarios**
**Relacionado con (Epic ID):** EP04  

**Descripción:**  
Como administrador, quiero asignar horarios de citas a los veterinarios, para organizar mejor la disponibilidad de atención.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El administrador asigna un horario de citas a un veterinario  
  - **Dado que** el administrador está en la página de gestión de horarios,  
  - **Cuando** selecciona un veterinario y asigna un horario,  
  - **Entonces** el sistema debe actualizar la disponibilidad y mostrar un mensaje de confirmación.

- **Escenario 2:** El administrador no puede asignar un horario fuera de las horas laborales  
  - **Dado que** el horario asignado está fuera del horario laboral establecido,  
  - **Cuando** el administrador intenta asignar el horario,  
  - **Entonces** el sistema debe mostrar un mensaje indicando que el horario no es válido.

---

## **US16: Revisión de Citas Pendientes**
**Relacionado con (Epic ID):** EP07  

**Descripción:**  
Como veterinario, quiero poder revisar todas las citas pendientes para organizar mi agenda de atención.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El veterinario ve las citas pendientes  
  - **Dado que** el veterinario está en la página de citas,  
  - **Cuando** selecciona la opción de ver citas pendientes,  
  - **Entonces** el sistema debe mostrar una lista con todas las citas programadas y no atendidas.

- **Escenario 2:** El veterinario no puede ver citas de otros veterinarios  
  - **Dado que** el veterinario solo tiene acceso a sus propias citas,  
  - **Cuando** intenta ver citas de otros veterinarios,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que no tiene acceso a esa información.

---

## **US17: Cancelación de Cita**
**Relacionado con (Epic ID):** EP07  

**Descripción:**  
Como propietario de la mascota, quiero poder cancelar una cita programada, en caso de que no pueda asistir.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El propietario cancela una cita programada  
  - **Dado que** el propietario está en la página de sus citas,  
  - **Cuando** selecciona la opción de cancelar la cita,  
  - **Entonces** el sistema debe cancelar la cita y mostrar un mensaje de confirmación.

- **Escenario 2:** El propietario no puede cancelar una cita ya atendida  
  - **Dado que** la cita ya ha sido atendida,  
  - **Cuando** el propietario intenta cancelarla,  
  - **Entonces** el sistema debe mostrar un mensaje indicando que no se puede cancelar una cita ya realizada.

---

## **US18: Generación de Historial Médico de una Mascota**
**Relacionado con (Epic ID):** EP02  

**Descripción:**  
Como propietario de la mascota, quiero poder generar un historial médico completo de mi mascota, para tener una copia de su historia clínica.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El propietario genera el historial médico completo de su mascota  
  - **Dado que** el propietario está en la página de la mascota,  
  - **Cuando** selecciona la opción de generar historial médico,  
  - **Entonces** el sistema debe generar un archivo PDF con toda la información de la historia clínica.

- **Escenario 2:** El propietario no puede generar el historial de una mascota que no tiene registros  
  - **Dado que** la mascota no tiene historial médico,  
  - **Cuando** el propietario intenta generar el historial,  
  - **Entonces** el sistema debe mostrar un mensaje indicando que no hay registros disponibles.

---
## **US19: Actualización de Estado de Salud de Mascota**
**Relacionado con (Epic ID):** EP01  

**Descripción:**  
Como veterinario, quiero poder actualizar el estado de salud de una mascota, para mantener el historial médico actualizado.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El veterinario actualiza el estado de salud de la mascota  
  - **Dado que** el veterinario está en la página de la historia clínica de la mascota,  
  - **Cuando** selecciona la opción de actualizar el estado de salud,  
  - **Entonces** el sistema debe guardar el nuevo estado de salud y mostrar un mensaje de confirmación.

- **Escenario 2:** El veterinario no puede actualizar el estado sin una descripción detallada  
  - **Dado que** el veterinario está actualizando el estado de salud,  
  - **Cuando** no ingresa una descripción detallada,  
  - **Entonces** el sistema debe mostrar un mensaje indicando que la descripción es obligatoria.

---

## **US20: Asignación de Prioridad a Casos de Emergencia**
**Relacionado con (Epic ID):** EP04  

**Descripción:**  
Como administrador, quiero asignar prioridad a los casos de emergencia, para asegurarme de que reciban atención inmediata.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El administrador asigna prioridad a un caso de emergencia  
  - **Dado que** el administrador está gestionando las citas,  
  - **Cuando** selecciona la opción de asignar prioridad a un caso,  
  - **Entonces** el sistema debe marcar el caso como urgente y asignar un horario prioritario.

- **Escenario 2:** El administrador no puede cambiar la prioridad de un caso que ya está atendido  
  - **Dado que** el caso ya ha sido atendido,  
  - **Cuando** el administrador intenta cambiar la prioridad,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que no es posible cambiar la prioridad de una cita ya atendida.

---

## **US21: Generación de Reportes de Actividad**
**Relacionado con (Epic ID):** EP05  

**Descripción:**  
Como administrador, quiero generar reportes de la actividad en la clínica (consultas, citas, pagos), para llevar un control del desempeño y resultados.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El administrador genera un reporte de actividad  
  - **Dado que** el administrador está en la página de reportes,  
  - **Cuando** selecciona los filtros de actividad (fechas, tipo de actividad, etc.),  
  - **Entonces** el sistema debe generar un reporte con la información solicitada.

- **Escenario 2:** El administrador no puede generar un reporte con datos faltantes  
  - **Dado que** el administrador ha seleccionado filtros incompletos,  
  - **Cuando** intenta generar el reporte,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que faltan filtros obligatorios.

---

## **US22: Filtrado de Citas por Veterinario**
**Relacionado con (Epic ID):** EP06  

**Descripción:**  
Como administrador, quiero poder filtrar las citas programadas por veterinario, para ver las citas asignadas a cada uno de ellos.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El administrador filtra citas por veterinario  
  - **Dado que** el administrador está en la página de citas,  
  - **Cuando** selecciona un veterinario en el filtro,  
  - **Entonces** el sistema debe mostrar solo las citas asignadas a ese veterinario.

- **Escenario 2:** El administrador no puede filtrar por un veterinario sin citas asignadas  
  - **Dado que** el veterinario seleccionado no tiene citas programadas,  
  - **Cuando** el administrador intenta ver las citas de ese veterinario,  
  - **Entonces** el sistema debe mostrar un mensaje indicando que no hay citas para ese veterinario.

---

## **US23: Recordatorio de Medicación para Mascotas**
**Relacionado con (Epic ID):** EP08  

**Descripción:**  
Como propietario de una mascota, quiero recibir recordatorios de medicación para mi mascota, para asegurarme de que no se me olvida administrarle la medicina.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El propietario recibe un recordatorio de medicación  
  - **Dado que** el propietario ha registrado un tratamiento para su mascota,  
  - **Cuando** llega la hora de administrar la medicación,  
  - **Entonces** el sistema debe enviar un recordatorio al propietario.

- **Escenario 2:** El propietario no recibe recordatorio si ya ha marcado la medicación como administrada  
  - **Dado que** el propietario ha marcado la medicación como administrada,  
  - **Cuando** llega la hora del recordatorio,  
  - **Entonces** el sistema no debe enviar el recordatorio.

---

## **US24: Visualización de Historial de Consultas por Propietario**
**Relacionado con (Epic ID):** EP02  

**Descripción:**  
Como propietario de una mascota, quiero poder ver un historial completo de todas las consultas realizadas a mi mascota, para conocer el tratamiento recibido y el progreso de su salud.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El propietario visualiza el historial de consultas  
  - **Dado que** el propietario está en la página de su mascota,  
  - **Cuando** selecciona la opción de ver el historial de consultas,  
  - **Entonces** el sistema debe mostrar una lista con todas las consultas realizadas.

- **Escenario 2:** El propietario no puede ver el historial de consultas de otras mascotas  
  - **Dado que** el propietario solo tiene acceso a la información de su propia mascota,  
  - **Cuando** intenta ver el historial de otra mascota,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que no tiene acceso a esa información.

---

## **US25: Notificación de Pago Pendiente**
**Relacionado con (Epic ID):** EP05  

**Descripción:**  
Como propietario de una mascota, quiero recibir una notificación si tengo un pago pendiente, para asegurarme de que pago a tiempo.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El propietario recibe una notificación de pago pendiente  
  - **Dado que** el propietario tiene un pago pendiente,  
  - **Cuando** el pago no se ha completado,  
  - **Entonces** el sistema debe enviar una notificación recordatorio al propietario.

- **Escenario 2:** El propietario no recibe una notificación después de haber realizado el pago  
  - **Dado que** el propietario ha completado el pago,  
  - **Cuando** el sistema verifica el pago,  
  - **Entonces** no debe enviar una notificación de pago pendiente.

---

## **US26: Registro de Información Adicional de Propietario**
**Relacionado con (Epic ID):** EP03  

**Descripción:**  
Como veterinario, quiero poder registrar información adicional sobre el propietario (como alergias o condiciones médicas), para tener un perfil más completo y ofrecer mejor atención a la mascota.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El veterinario agrega información adicional del propietario  
  - **Dado que** el veterinario está en la página de registro del propietario,  
  - **Cuando** ingresa datos adicionales como alergias o condiciones médicas,  
  - **Entonces** el sistema debe guardar esta información y asociarla al propietario.

- **Escenario 2:** El veterinario no puede dejar campos de información adicional vacíos  
  - **Dado que** el veterinario está ingresando información adicional,  
  - **Cuando** no ingresa datos obligatorios,  
  - **Entonces** el sistema debe mostrar un mensaje de advertencia indicando que esos campos no pueden estar vacíos.

---
## **US27: Programación de Recordatorios para Citas**
**Relacionado con (Epic ID):** EP07  

**Descripción:**  
Como propietario de una mascota, quiero poder programar recordatorios para las citas veterinarias, para no olvidarlas.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El propietario programa un recordatorio para una cita  
  - **Dado que** el propietario está agendando una cita para su mascota,  
  - **Cuando** selecciona la opción de programar un recordatorio,  
  - **Entonces** el sistema debe enviar un recordatorio antes de la cita.

- **Escenario 2:** El propietario no puede programar un recordatorio sin una fecha de cita válida  
  - **Dado que** el propietario está programando un recordatorio,  
  - **Cuando** la fecha de la cita no es válida,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que la cita no puede programarse.

---

## **US28: Historial de Pago de Propietario**
**Relacionado con (Epic ID):** EP05  

**Descripción:**  
Como administrador, quiero poder acceder al historial de pagos de un propietario, para revisar si ha pagado correctamente todas las consultas.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El administrador consulta el historial de pagos de un propietario  
  - **Dado que** el administrador está en la página del propietario,  
  - **Cuando** selecciona la opción de ver historial de pagos,  
  - **Entonces** el sistema debe mostrar todos los pagos realizados por ese propietario.

- **Escenario 2:** El administrador no puede acceder al historial de pagos de otro propietario  
  - **Dado que** el administrador solo tiene acceso al historial de pagos de sus clientes,  
  - **Cuando** intenta ver el historial de pagos de un propietario diferente,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que no tiene permiso para acceder a esa información.

---

## **US29: Eliminación de Registro de Mascota**
**Relacionado con (Epic ID):** EP02  

**Descripción:**  
Como veterinario, quiero poder eliminar el registro de una mascota en el sistema, para cuando ya no se necesite.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El veterinario elimina el registro de una mascota  
  - **Dado que** el veterinario está en la página de la mascota,  
  - **Cuando** selecciona la opción de eliminar,  
  - **Entonces** el sistema debe borrar permanentemente el registro de la mascota.

- **Escenario 2:** El veterinario no puede eliminar un registro de una mascota si tiene citas pendientes  
  - **Dado que** la mascota tiene citas programadas,  
  - **Cuando** el veterinario intenta eliminar el registro,  
  - **Entonces** el sistema debe mostrar un mensaje indicando que no es posible eliminar la mascota con citas pendientes.

---

## **US30: Carga de Documento Médico de Mascota**
**Relacionado con (Epic ID):** EP01  

**Descripción:**  
Como veterinario, quiero cargar documentos médicos relacionados con la mascota, para mantener un registro completo de su historial médico.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El veterinario carga un documento médico  
  - **Dado que** el veterinario está en la página de la mascota,  
  - **Cuando** selecciona la opción de cargar un documento médico,  
  - **Entonces** el sistema debe permitirle cargar el archivo y asociarlo a la mascota.

- **Escenario 2:** El veterinario no puede cargar un archivo con formato incorrecto  
  - **Dado que** el veterinario intenta cargar un archivo,  
  - **Cuando** el archivo no es un formato permitido,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que el archivo no es válido.

---

## **US31: Filtrado de Mascotas por Tipo**
**Relacionado con (Epic ID):** EP02  

**Descripción:**  
Como veterinario, quiero poder filtrar las mascotas por tipo (perro, gato, etc.), para organizar mejor los registros.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El veterinario filtra las mascotas por tipo  
  - **Dado que** el veterinario está en la página de mascotas,  
  - **Cuando** selecciona un tipo de mascota (por ejemplo, gato),  
  - **Entonces** el sistema debe mostrar solo las mascotas de ese tipo.

- **Escenario 2:** El veterinario no puede filtrar sin haber seleccionado un tipo  
  - **Dado que** el veterinario no ha seleccionado un tipo de mascota,  
  - **Cuando** intenta realizar un filtro,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que debe seleccionar un tipo.

---

## **US32: Programación de Vacunación**
**Relacionado con (Epic ID):** EP08  

**Descripción:**  
Como propietario, quiero poder programar las fechas de vacunación de mi mascota, para asegurarme de que se apliquen en tiempo y forma.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El propietario programa la vacunación de su mascota  
  - **Dado que** el propietario está en la página de la mascota,  
  - **Cuando** selecciona la opción de programar una vacunación,  
  - **Entonces** el sistema debe permitirle seleccionar la fecha y la vacuna.

- **Escenario 2:** El propietario no puede programar una vacunación sin seleccionar la vacuna adecuada  
  - **Dado que** el propietario intenta programar una vacunación,  
  - **Cuando** no selecciona la vacuna,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que debe seleccionar una vacuna.

---

## **US33: Actualización de Información de Propietario**
**Relacionado con (Epic ID):** EP03  

**Descripción:**  
Como propietario, quiero poder actualizar mi información de contacto y otros detalles, para que la clínica siempre tenga mi información actualizada.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El propietario actualiza su información  
  - **Dado que** el propietario está en su página de perfil,  
  - **Cuando** actualiza su dirección o número de teléfono,  
  - **Entonces** el sistema debe guardar los cambios correctamente.

- **Escenario 2:** El propietario no puede dejar campos obligatorios vacíos  
  - **Dado que** el propietario está actualizando su información,  
  - **Cuando** deja campos obligatorios vacíos,  
  - **Entonces** el sistema debe mostrar un mensaje indicando que esos campos son obligatorios.

---

## **US34: Generación de Informe de Diagnóstico**
**Relacionado con (Epic ID):** EP01  

**Descripción:**  
Como veterinario, quiero generar un informe de diagnóstico para la mascota, para documentar su condición y el tratamiento recomendado.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El veterinario genera un informe de diagnóstico  
  - **Dado que** el veterinario ha realizado el diagnóstico,  
  - **Cuando** selecciona la opción de generar informe,  
  - **Entonces** el sistema debe crear un documento con los detalles del diagnóstico y tratamiento.

- **Escenario 2:** El veterinario no puede generar un informe sin haber completado el diagnóstico  
  - **Dado que** el veterinario no ha completado el diagnóstico,  
  - **Cuando** intenta generar el informe,  
  - **Entonces** el sistema debe mostrar un mensaje de advertencia indicando que debe completar el diagnóstico primero.

---

## **US35: Notificación de Disponibilidad de Cita**
**Relacionado con (Epic ID):** EP04  

**Descripción:**  
Como propietario, quiero recibir una notificación cuando haya disponibilidad para una cita, si inicialmente estaba en espera, para poder agendarla.  

### **Criterios de Aceptación:**  
- **Escenario 1:** El propietario recibe una notificación cuando se dispone de una cita  
  - **Dado que** el propietario estaba en espera para una cita,  
  - **Cuando** hay disponibilidad en la agenda,  
  - **Entonces** el sistema debe enviar una notificación al propietario.

- **Escenario 2:** El propietario no recibe una notificación si no estaba en espera  
  - **Dado que** el propietario no estaba en espera,  
  - **Cuando** hay disponibilidad en la agenda,  
  - **Entonces** el sistema no debe enviar la notificación.


## 3.3. Impact Mapping.

Este Impact Map ilustra cómo Pawfect Care vincula sus metas comerciales con los resultados esperados. Describe los entregables clave y las historias de usuario que abordan estos resultados, garantizando que cada parte del desarrollo de la plataforma optimice tanto la eficiencia como la experiencia del usuario.


<br><img src="" alt="" style="width: 1000px; height: auto;" ><br>

## 3.4. Product Backlog.

Para reducir la complejidad de las tareas, hemos adoptado la escala de Fibonacci (1/2/3/5/8) para estructurar nuestro product backlog.  
Historia de usuario principal:  
Partimos de la referencia de US06: Como usuario, quiero agendar citas para que mi mascota reciba atención veterinaria a tiempo (con 3 puntos de historia).  
Además, usamos la herramienta “Planning Poker Online” para realizar votaciones grupales y determinar la dificultad de cada historia de usuario, tomando como referencia intermedia la Historia de Usuario 06.

<table>
  <thead>
    <tr>
      <th># Orden</th>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points (1/2/3/5/8)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>US01</td>
      <td>Registro de Usuario</td>
      <td>Como administrador, deseo permitir a los usuarios registrarse para que puedan acceder al sistema.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>2</td>
      <td>US06</td>
      <td>Agendamiento de Citas</td>
      <td>Como usuario, deseo gestionar las citas veterinarias de mis mascotas para asegurarme de que reciban atención médica a tiempo.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>3</td>
      <td>US12</td>
      <td>Barra de navegación en la Landing Page</td>
      <td>Como usuario, quiero un menú para ver las secciones de la aplicación.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>4</td>
      <td>US13</td>
      <td>Sección "Why Choose Us?"</td>
      <td>Como usuario, quiero una sección que explique por qué debo elegir Pawfect Care para entender los beneficios y características de la plataforma.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>5</td>
      <td>US02</td>
      <td>Recuperación de Contraseña</td>
      <td>Como administrador, deseo que los usuarios puedan recuperar sus contraseñas en caso de olvido.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>6</td>
      <td>US05</td>
      <td>Edición de Perfil de Mascota</td>
      <td>Como usuario, deseo gestionar la información de mis mascotas para mantener sus datos actualizados.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>7</td>
      <td>US03</td>
      <td>Gestión de Perfiles de Usuarios</td>
      <td>Como administrador, deseo gestionar los perfiles de los usuarios para asegurar que solo personas autorizadas tengan acceso.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>8</td>
      <td>US04</td>
      <td>Creación de Perfil de Mascota</td>
      <td>Como usuario, deseo crear un perfil de mascota para mantener sus datos organizados.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>9</td>
      <td>US07</td>
      <td>Cancelación de Citas</td>
      <td>Como usuario, deseo cancelar las citas veterinarias de mis mascotas cuando sea necesario.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>10</td>
      <td>US08</td>
      <td>Notificaciones de Citas</td>
      <td>Como usuario, deseo recibir notificaciones sobre eventos importantes relacionados con las citas de mis mascotas.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>11</td>
      <td>US14</td>
      <td>Sección de suscripciones</td>
      <td>Como usuario, quiero una sección de suscripciones para entender las opciones de pago y los beneficios asociados.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>12</td>
      <td>US15</td>
      <td>Reseñas de clientes</td>
      <td>Como usuario, quiero leer reseñas de otros clientes para evaluar la calidad del servicio antes de usar la plataforma.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>13</td>
      <td>US099</td>
      <td>Notificaciones de Historial Médico</td>
      <td>Como usuario, deseo recibir notificaciones sobre actualizaciones en el historial médico de mis mascotas.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>14</td>
      <td>US10</td>
      <td>Publicación en el Foro</td>
      <td>Como usuario, deseo publicar en un foro comunitario para intercambiar experiencias y consejos con otros dueños de mascotas.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>15</td>
      <td>US11</td>
      <td>Moderación del Foro</td>
      <td>Como usuario, deseo moderar el foro para asegurar que las discusiones sean respetuosas y relevantes.</td>
      <td>8</td>
    </tr>
  </tbody>
</table>


---

## 3.1. To-Be Scenario Mapping.

- **Primer segmento: Médicos Veterinarios**

<br><img src="" alt="To Be Scenario Map 1" style="width: 1000px; height: auto;" ><br>

- **Segundo segmento: Dueños de Mascotas**

<br><img src="" alt="To Be Scenario Map 2" style="width: 1000px; height: auto;" ><br>


## 3.2. User Stories.

<!-- Tabla para Epic01 -->
<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Gestión de Usuarios
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Epic01</td>
      <td>Como administrador, deseo gestionar los usuarios para asegurar que solo personas autorizadas tengan acceso al sistema.</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US01</td>
      <td>Registro de Usuario</td>
    </tr>
    <tr>
      <td>US02</td>
      <td>Recuperación de Contraseña</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Gestión de Perfiles de Usuarios</td>
    </tr>
  </tbody>
</table>

<!-- Tabla para Epic02 -->
<br>
<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Gestión de Mascotas</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Epic02</td>
      <td>Como usuario, deseo gestionar la información de mis mascotas para mantener sus datos actualizados.</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US04</td>
      <td>Creación de Perfil de Mascota</td>
    </tr>
    <tr>
      <td>US05</td>
      <td>Edición de Perfil de Mascota</td>
    </tr>
    <tr>
      <td>US06</td>
      <td>Visualización de Perfiles de Mascotas</td>
    </tr>
    <tr>
      <td>US07</td>
      <td> Búsqueda de Mascotas por ID</td>
    </tr>
    <tr>
      <td>US08</td>
      <td>Gestión de Perfiles de Mascotas</td>
    </tr>
  </tbody>
</table>

<br>
<!-- Tabla para Epic03 -->
<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Gestión de Citas Veterinarias</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Epic03</td>
      <td>Como usuario, deseo gestionar las citas veterinarias de mis mascotas para asegurarme de que reciban atención médica a tiempo.</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US09</td>
      <td>Agendamiento de Citas</td>
    </tr>
    <tr>
      <td>US10</td>
      <td>Cancelación de Citas</td>
    </tr>
    <tr>
      <td>US11</td>
      <td>Gestión de Citas Veterinarias</td>
    </tr>
    <tr>
      <td>US12</td>
      <td>Búsqueda de Citas por ID</td>
    </tr>
    <tr>
      <td>US13</td>
      <td>Edición de Citas Veterinarias</td>
    </tr>
  </tbody>
</table>

<br>
<!-- Tabla para Epic04 -->
<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Gestión de Notificaciones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Epic04</td>
      <td>Como usuario, deseo recibir notificaciones sobre eventos importantes relacionados con mis mascotas para estar siempre informado.</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US14</td>
      <td>Notificaciones de Citas</td>
    </tr>
    <tr>
      <td>US15</td>
      <td>Notificaciones de Historial Médico</td>
    </tr>
    <tr>
      <td>US16</td>
      <td>Gestión de Notificaciones</td>
    </tr>
  </tbody>
</table>

<!-- Tabla para Epic05 -->
<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Navegación y Funcionalidades de la Landing Page</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Epic05</td>
      <td>Como usuario, deseo explorar la página principal de Pawfect Care para entender los servicios y características que ofrece la plataforma.</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US17</td>
      <td>Barra de Navegación en la Landing Page</td>
    </tr>
    <tr>
      <td>US18</td>
      <td>Visualización de la Sección "Why Choose Us?"</td>
    </tr>
    <tr>
      <td>US19</td>
      <td>Gestión de Suscripciones en la Landing Page</td>
    </tr>
    <tr>
      <td>US20</td>
      <td>Revisión de Reseñas de Clientes</td>
    </tr>
    <tr>
      <td>US21</td>
      <td>Envío de Mensajes de Contacto</td>
    </tr>
    <tr>
      <td>US22</td>
      <td>Visualización de Videos en la Sección de Características</td>
    </tr>
  </tbody>
</table>

<!-- Tabla para Epic06 -->
<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Gestión de Clientes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Epic06</td>
      <td>Como administrador, deseo gestionar la información de los clientes para mantener los datos actualizados y organizados.</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US24</td>
      <td>Creación de Perfiles de Clientes</td>
    </tr>
    <tr>
      <td>US25</td>
      <td>Edición de Perfiles de Clientes</td>
    </tr>
    <tr>
      <td>US26</td>
      <td>Búsqueda de Clientes por ID</td>
    </tr>
  </tbody>
</table>

<!-- Tabla para Epic07 -->
<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Gestión de Eventos Veterinarios</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Epic07</td>
      <td>Como administrador o doctor veterinario, deseo gestionar los eventos veterinarios para asegurarme de que las mascotas reciban la atención adecuada.</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US27</td>
      <td>Creación de Eventos Veterinarios</td>
    </tr>
    <tr>
      <td>US28</td>
      <td>Edición de Eventos Veterinarios</td>
    </tr>
    <tr>
      <td>US29</td>
      <td>Búsqueda de Eventos por ID</td>
    </tr>
    <tr>
      <td>US30</td>
      <td>Gestión del Estado de los Eventos</td>
    </tr>
  </tbody>
</table>

<!-- Tabla para Epic08 -->
<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Gestión de Historial Médico de las Mascotas</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Epic08</td>
      <td>Como usuario o administrador, deseo gestionar el historial médico de las mascotas para llevar un registro de sus atenciones y tratamientos.</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US31</td>
      <td>Visualización del Historial Médico</td>
    </tr>
    <tr>
      <td>US32</td>
      <td>Actualización del Historial Médico</td>
    </tr>
  </tbody>
</table>

<!-- Tabla para Epic09 -->
<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Funcionalidades de Idioma en la App Web</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Epic09</td>
      <td>Como usuario, deseo cambiar el idioma de la plataforma para navegar entre las versiones en inglés y español de la app web.</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US23</td>
      <td>Cambio de Idioma en la App Web</td>
    </tr>
  </tbody>
</table>

---
# Epic y User Stories Parafraseados

## Epic01: Gestión de Usuarios
**Descripción:**  
Como administrador, necesito gestionar usuarios para garantizar que únicamente personas autorizadas accedan al sistema.

### User Stories Relacionadas:

#### US01: Registro de Usuario  
**Descripción:**  
Como administrador, debo asegurar que los usuarios puedan registrarse correctamente para acceder al sistema.  

**Criterios de Aceptación:**  
- **Escenario 1:** Registro exitoso  
  - **Dado que** el usuario está en la página de registro,  
  - **Cuando** completa todos los campos obligatorios (nombre, teléfono, correo, dirección, contraseña),  
  - **Entonces** el sistema crea la cuenta y muestra confirmación.  

- **Escenario 2:** Correo duplicado  
  - **Dado que** el usuario ingresa un correo ya registrado,  
  - **Cuando** envía el formulario,  
  - **Entonces** el sistema muestra un error.  

- **Escenario 3:** Campos incompletos  
  - **Dado que** el usuario omite campos obligatorios,  
  - **Cuando** intenta registrarse,  
  - **Entonces** el sistema solicita completar los datos.  

---

#### US02: Recuperación de Contraseña  
**Descripción:**  
Como administrador, debo permitir a los usuarios recuperar contraseñas olvidadas.  

**Criterios de Aceptación:**  
- **Escenario 1:** Solicitud de recuperación  
  - **Dado que** el usuario olvidó su contraseña,  
  - **Cuando** solicita recuperarla,  
  - **Entonces** recibe un enlace por correo.  

- **Escenario 2:** Restablecimiento exitoso  
  - **Dado que** el usuario recibió el enlace,  
  - **Cuando** establece una nueva contraseña,  
  - **Entonces** el sistema actualiza sus credenciales.  

---

#### US03: Gestión de Perfiles  
**Descripción:**  
Como administrador, debo mantener actualizados los perfiles de los usuarios.  

**Criterios de Aceptación:**  
- **Escenario 1:** Edición de perfil  
  - **Dado que** el usuario está en su perfil,  
  - **Cuando** modifica sus datos,  
  - **Entonces** el sistema guarda los cambios.  

- **Escenario 2:** Visualización de perfil  
  - **Dado que** el usuario accede a su cuenta,  
  - **Cuando** selecciona "Perfil",  
  - **Entonces** ve su información actual.  

---

## Epic02: Gestión de Mascotas  
**Descripción:**  
Como usuario, necesito gestionar la información de mis mascotas para mantener sus datos al día.  

### User Stories Relacionadas:

#### US04: Creación de Perfil de Mascota  
**Descripción:**  
Como usuario, quiero crear perfiles para mis mascotas.  

**Criterios de Aceptación:**  
- **Escenario 1:** Perfil creado  
  - **Dado que** el usuario está registrado,  
  - **Cuando** completa los campos requeridos (nombre, raza, edad),  
  - **Entonces** el sistema genera el perfil.  

---

#### US05: Edición de Perfil de Mascota  
**Descripción:**  
Como usuario, necesito actualizar la información de mis mascotas.  

**Criterios de Aceptación:**  
- **Escenario 1:** Datos modificados  
  - **Dado que** existe un perfil de mascota,  
  - **Cuando** el usuario edita los campos,  
  - **Entonces** el sistema guarda los cambios.  

---

## Epic03: Gestión de Citas Veterinarias  
**Descripción:**  
Como usuario, deseo agendar citas para asegurar la atención médica de mis mascotas.  

### User Stories Relacionadas:

#### US06: Agendamiento de Citas  
**Descripción:**  
Como usuario, quiero programar citas veterinarias.  

**Criterios de Aceptación:**  
- **Escenario 1:** Cita agendada  
  - **Dado que** el usuario necesita una consulta,  
  - **Cuando** selecciona fecha, hora y servicio,  
  - **Entonces** el sistema confirma la cita.  

---

#### US07: Cancelación de Citas  
**Descripción:**  
Como usuario, necesito cancelar citas si no puedo asistir.  

**Criterios de Aceptación:**  
- **Escenario 1:** Cita cancelada  
  - **Dado que** el usuario tiene una cita agendada,  
  - **Cuando** la cancela,  
  - **Entonces** el sistema envía una notificación.  

---

## Epic04: Gestión de Notificaciones  
**Descripción:**  
Como usuario, quiero recibir alertas sobre eventos importantes de mis mascotas.  

### User Stories Relacionadas:

#### US08: Notificaciones de Citas  
**Descripción:**  
Como usuario, necesito recordatorios de citas.  

**Criterios de Aceptación:**  
- **Escenario 1:** Notificación enviada  
  - **Dado que** hay una cita próxima,  
  - **Cuando** se acerca la fecha,  
  - **Entonces** el usuario recibe un aviso.  

---

#### US09: Notificaciones de Historial Médico  
**Descripción:**  
Como usuario, deseo estar informado sobre cambios en el historial médico.  

**Criterios de Aceptación:**  
- **Escenario 1:** Actualización notificada  
  - **Dado que** el veterinario modifica el historial,  
  - **Cuando** se guardan los cambios,  
  - **Entonces** el usuario recibe una alerta.  

---

## Epic05: Landing Page  
**Descripción:**  
Como usuario, quiero explorar la página principal para entender los servicios ofrecidos.  

### User Stories Relacionadas:

#### US12: Barra de Navegación  
**Descripción:**  
Como usuario, necesito un menú para acceder a las secciones.  

**Criterios de Aceptación:**  
- **Escenario 1:** Navegación funcional  
  - **Dado que** el usuario está en la Landing Page,  
  - **Cuando** usa la barra de navegación,  
  - **Entonces** accede a las secciones deseadas.  

---

#### US13: Sección "Why Choose Us?"  
**Descripción:**  
Como usuario, quiero conocer las ventajas de la plataforma.  

**Criterios de Aceptación:**  
- **Escenario 1:** Beneficios visibles  
  - **Dado que** el usuario explora la página,  
  - **Cuando** llega a "Why Choose Us?",  
  - **Entonces** ve una lista clara de ventajas.  

---

#### US14: Suscripciones  
**Descripción:**  
Como usuario, necesito comparar planes de suscripción.  

**Criterios de Aceptación:**  
- **Escenario 1:** Planes mostrados  
  - **Dado que** el usuario está en la sección,  
  - **Cuando** revisa las opciones,  
  - **Entonces** puede seleccionar un plan.  

---

#### US15: Reseñas de Clientes  
**Descripción:**  
Como usuario, quiero evaluar la confiabilidad del servicio.  

**Criterios de Aceptación:**  
- **Escenario 1:** Reseñas accesibles  
  - **Dado que** el usuario ve la sección,  
  - **Cuando** lee las opiniones,  
  - **Entonces** toma una decisión informada.  
## 3.3. Impact Mapping.

Este Impact Map muestra cómo Pawfect Care alinea sus objetivos de negocio con los impactos deseados. Detalla los entregables específicos y las user stories que abordan estos impactos, asegurando que cada aspecto del desarrollo de la plataforma mejore la eficiencia y la experiencia del usuario.


<br><img src="./assets/Chapter03/Impactmap.png" alt="Impact Map" style="width: 1000px; height: auto;" ><br>

## 3.4. Product Backlog.

Con el fin de simplificar la complejidad de las tareas, hemos utilizado la escala de Fibonacci (1/2/3/5/8) para crear nuestro product backlog.
Historia de usuario base:
Tomamos como referencia US06: Como usuario, quiero agendar citas para que mi mascota reciba atención veterinaria a tiempo. (Posee 3 puntos de historia).
Asimismo, utilizamos la herramienta “Planning Poker Online” para poder votar en grupo y decidir la dificultad de cada historia de usuario, tomando como punto intermedio el User Story 06

<table>
  <thead>
    <tr>
      <th># Orden</th>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points (1/2/3/5/8)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>US01</td>
      <td>Registro de Usuario</td>
      <td>Como administrador, deseo permitir a los usuarios registrarse para que puedan acceder al sistema.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>2</td>
      <td>US02</td>
      <td>Recuperación de Contraseña</td>
      <td>Como administrador, deseo que los usuarios puedan recuperar sus contraseñas en caso de olvido.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>3</td>
      <td>US03</td>
      <td>Gestión de Perfiles de Usuarios</td>
      <td>Como administrador, deseo gestionar los perfiles de los usuarios para asegurar que solo personas autorizadas tengan acceso.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>4</td>
      <td>US04</td>
      <td>Creación de Perfil de Mascota</td>
      <td>Como usuario, deseo crear un perfil de mascota para mantener sus datos organizados.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>5</td>
      <td>US05</td>
      <td>Edición de Perfil de Mascota</td>
      <td>Como usuario, deseo gestionar la información de mis mascotas para mantener sus datos actualizados.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>6</td>
      <td>US06</td>
      <td>Agendamiento de Citas</td>
      <td>Como usuario, deseo gestionar las citas veterinarias de mis mascotas para asegurarme de que reciban atención médica a tiempo.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>7</td>
      <td>US07</td>
      <td>Cancelación de Citas</td>
      <td>Como usuario, deseo cancelar las citas veterinarias de mis mascotas cuando sea necesario.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>8</td>
      <td>US08</td>
      <td>Notificaciones de Citas</td>
      <td>Como usuario, deseo recibir notificaciones sobre eventos importantes relacionados con las citas de mis mascotas.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>9</td>
      <td>US09</td>
      <td>Sección "About Us"</td>
      <td>Como usuario, quiero una sección que explique quiénes somos para entender mejor nuestra misión y valores.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>10</td>
      <td>US10</td>
      <td>Publicación en el Foro</td>
      <td>Como usuario, deseo publicar en un foro comunitario para intercambiar experiencias y consejos con otros dueños de mascotas.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>11</td>
      <td>US11</td>
      <td>Moderación del Foro</td>
      <td>Como usuario, deseo moderar el foro para asegurar que las discusiones sean respetuosas y relevantes.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>12</td>
      <td>US12</td>
      <td>Barra de navegación en la Landing Page</td>
      <td>Como usuario, quiero un menú para ver las secciones de la aplicación.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>13</td>
      <td>US13</td>
      <td>Sección "Why Choose Us?"</td>
      <td>Como usuario, quiero una sección que explique por qué debo elegir Pawfect Care para entender los beneficios y características de la plataforma.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>14</td>
      <td>US14</td>
      <td>Sección de suscripciones</td>
      <td>Como usuario, quiero una sección de suscripciones para entender las opciones de pago y los beneficios asociados.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>15</td>
      <td>US15</td>
      <td>Reseñas de clientes</td>
      <td>Como usuario, quiero leer reseñas de otros clientes para evaluar la calidad del servicio antes de usar la plataforma.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>16</td>
      <td>US16</td>
      <td>Notificaciones de Historial Médico</td>
      <td>Como usuario, deseo recibir notificaciones sobre actualizaciones en el historial médico de mis mascotas.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>17</td>
      <td>US17</td>
      <td>Integración de Pagos</td>
      <td>Como usuario, deseo realizar pagos en línea para las citas y servicios veterinarios de manera segura.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>18</td>
      <td>US18</td>
      <td>Perfil de Veterinario</td>
      <td>Como usuario, deseo ver los perfiles de los veterinarios disponibles para elegir a quién llevar a mis mascotas.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>19</td>
      <td>US19</td>
      <td>Historial Médico de Mascotas</td>
      <td>Como usuario, quiero acceder al historial médico de mis mascotas para tener toda la información disponible en un solo lugar.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>20</td>
      <td>US20</td>
      <td>Sección de Preguntas Frecuentes (FAQ)</td>
      <td>Como usuario, quiero tener acceso a una sección de preguntas frecuentes para resolver mis dudas rápidamente.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>21</td>
      <td>US21</td>
      <td>Informes de Citas</td>
      <td>Como administrador, deseo generar informes sobre las citas para analizar la utilización de los servicios veterinarios.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>22</td>
      <td>US22</td>
      <td>Alertas de Salud para Mascotas</td>
      <td>Como usuario, deseo recibir alertas sobre la salud y el bienestar de mis mascotas basadas en su historial médico.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>23</td>
      <td>US23</td>
      <td>Funciones de Búsqueda Avanzada</td>
      <td>Como usuario, deseo poder buscar información sobre servicios veterinarios, veterinarios disponibles y más de manera eficiente.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>24</td>
      <td>US24</td>
      <td>Integración con Redes Sociales</td>
      <td>Como usuario, deseo poder compartir mis experiencias en redes sociales para fomentar la comunidad.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>25</td>
      <td>US25</td>
      <td>Aplicación Móvil</td>
      <td>Como usuario, deseo tener una aplicación móvil para gestionar mis citas y servicios desde mi dispositivo.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>26</td>
      <td>US26</td>
      <td>Chat de Soporte</td>
      <td>Como usuario, deseo tener acceso a un chat de soporte en línea para resolver mis problemas en tiempo real.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>27</td>
      <td>US27</td>
      <td>Notificaciones Push</td>
      <td>Como usuario, deseo recibir notificaciones push para estar al tanto de recordatorios y actualizaciones importantes.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>28</td>
      <td>US28</td>
      <td>Rastreo de Servicios</td>
      <td>Como usuario, deseo rastrear el estado de mis servicios veterinarios para saber en qué etapa se encuentran.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>29</td>
      <td>US29</td>
      <td>Sección de Testimonios</td>
      <td>Como usuario, quiero ver testimonios de otros dueños de mascotas para saber cómo les ha ido con el servicio.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>30</td>
      <td>US30</td>
      <td>Programa de Lealtad</td>
      <td>Como usuario, deseo un programa de lealtad que me recompense por utilizar los servicios con regularidad.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>31</td>
      <td>US31</td>
      <td>Encuestas de Satisfacción</td>
      <td>Como administrador, deseo enviar encuestas de satisfacción a los usuarios para mejorar los servicios ofrecidos.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>32</td>
      <td>US32</td>
      <td>Integración con Sistemas Externos</td>
      <td>Como administrador, deseo integrar el sistema con otros servicios externos para mejorar la funcionalidad de la aplicación.</td>
      <td>8</td>
    </tr>
  </tbody>
</table>


---
