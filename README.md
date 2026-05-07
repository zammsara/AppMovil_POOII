# NombreDelProyecto-Pendiente

Aplicación móvil desarrollada en Android Studio como proyecto final de la asignatura **Programación Orientada a Objetos II**.

El proyecto consiste en una aplicación móvil para la gestión de eventos universitarios, actividades de clubes, voluntariados y control de asistencia estudiantil mediante códigos QR. La app permitirá que los estudiantes consulten actividades disponibles, se inscriban, registren su asistencia y lleven un historial de participación dentro de la universidad.

## Tecnologías utilizadas

- Kotlin
- Android Studio
- Jetpack Compose
- Git y GitHub

## Objetivo del proyecto

Desarrollar una aplicación móvil aplicando los principios de Programación Orientada a Objetos, buenas prácticas de desarrollo y diseño de interfaces modernas, con el propósito de organizar la participación estudiantil en eventos, clubes y actividades universitarias.

## Funcionalidades principales

- Consulta de eventos universitarios activos.
- Inscripción de estudiantes a eventos.
- Registro de asistencia mediante código QR/código único.
- Validación del horario permitido para marcar asistencia.
- Gestión de clubes universitarios.
- Creación de actividades exclusivas para miembros de clubes.
- Registro de participación estudiantil.
- Visualización de historial de eventos asistidos.
- Gestión de beneficios como horas laborales, voluntariado o constancias.

## Módulos principales

| Módulo | Descripción |
|---|---|
| Eventos | Permite consultar, crear y administrar eventos universitarios. |
| Inscripción | Permite que los estudiantes se registren en actividades disponibles. |
| Asistencia QR | Registra la asistencia del estudiante mediante un código QR único por evento. |
| Clubes | Permite administrar clubes, miembros y actividades internas. |
| Participación | Guarda el historial de actividades asistidas por cada estudiante. |
| Beneficios | Registra beneficios asociados a eventos, como horas laborales o constancias. |

## Módulo de clubes

El módulo de clubes permitirá administrar clubes universitarios dentro de la aplicación. Cada club podrá tener miembros, actividades internas y administradores autorizados.

Los líderes de clubes serán estudiantes, por lo que deberán ser aprobados por coordinación para poder administrar un club. Una vez aprobados, podrán gestionar miembros y crear actividades exclusivas para los integrantes de su club.

## Check-in mediante QR/código único

Cuando se cree un evento, el sistema generará un código QR único asociado a esa actividad. El estudiante podrá escanearlo el día del evento para registrar su asistencia.

El QR solo permitirá marcar asistencia dentro de un rango de tiempo definido, por ejemplo, 30 minutos antes y 15 minutos después de la hora de inicio del evento.

## Conceptos de POO aplicados

El proyecto permitirá aplicar conceptos como:

- Clases y objetos
- Encapsulamiento
- Herencia
- Polimorfismo
- Composición
- Relaciones entre clases
- Métodos de validación

Algunas clases propuestas son:

- Usuario
- Estudiante
- Evento
- Club
- Inscripcion
- Asistencia
- Beneficio
- AdministradorClub

## Integrantes

| Integrante | Rol |
|---|---|
| Arelys Obando | Desarrollador Backend |
| Solieth Trejos | Diseñador |
| Sara Zambrana | Desarrollador Android |

## Estado del proyecto

🚧 En desarrollo
