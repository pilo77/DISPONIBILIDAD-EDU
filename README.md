# Sistema de Gestión de Horarios

## Objetivo

El objetivo de este proyecto es desarrollar una aplicación web que permita gestionar de manera eficiente los horarios de clases de una institución educativa. El sistema facilita la asignación de docentes, salones y horarios, evitando conflictos de horarios y mejorando la organización. Además, proporciona notificaciones automáticas a los profesores por correo electrónico y WhatsApp, permitiendo que reciban sus horarios de forma clara y oportuna.

## Problemática

La institución educativa enfrenta problemas para organizar los horarios de clases debido al uso de hojas de cálculo. Este método no les permite llevar un buen control sobre las horas de trabajo de los profesores, los salones disponibles ni las asignaturas asignadas, lo que genera conflictos de horarios y una gestión ineficiente. Esta situación causa confusión tanto para los profesores como para los encargados de la administración y provoca una considerable pérdida de tiempo.

## Solución

El sistema proporcionará una página web que permitirá a los encargados gestionar de forma eficiente los horarios de clases, tomando en cuenta la disponibilidad de los salones, los horarios de los docentes y sus roles contractuales. El sistema enviará los horarios a los profesores por correo electrónico y WhatsApp, asegurando que la información sea clara y fácilmente accesible. Además, se podrán exportar e imprimir los horarios en formato PDF. Los salones ocupados no podrán ser asignados a otros profesores en el mismo bloque de tiempo, y se verificará que tanto el profesor como el salón estén disponibles antes de hacer la asignación.

## Requerimientos Funcionales

- **RF1: Gestión de Docentes y Carga Académica**
  - **Historia de Usuario**: El director del programa debe poder gestionar la carga académica de los docentes, considerando los diferentes tipos de contratos (TC-40, MT-26, C-16).
  - **Criterios de Aceptación**: El sistema debe permitir ingresar información de los docentes, calcular automáticamente sus horas de trabajo según su tipo de contrato y actualizar la carga horaria en tiempo real.
  - **Prioridad**: Alta

- **RF2: Gestión de Salones y Bloques**
  - **Historia de Usuario**: El director del programa debe poder asignar salones por bloques de tiempo, evitando conflictos de horarios.
  - **Criterios de Aceptación**: El sistema debe permitir la asignación manual o automática de salones (A, B, C, con capacidad para 30 estudiantes), verificando que los salones no estén ocupados en el mismo horario.
  - **Prioridad**: Alta

- **RF3: Asignación de Horarios y Evitación de Cruces**
  - **Historia de Usuario**: El director del programa debe poder asignar los horarios de los docentes de acuerdo con su disponibilidad, evitando cruces o sobrecargas horarias.
  - **Criterios de Aceptación**: Asignación automática de horarios basada en la disponibilidad de los profesores, verificando que el profesor y el salón estén disponibles en el horario seleccionado, evitando conflictos con otras clases.
  - **Prioridad**: Alta

- **RF4: Gestión de Asignaturas**
  - **Historia de Usuario**: El director del programa debe poder asignar materias a los docentes y organizarlas en el sistema para su planificación.
  - **Criterios de Aceptación**: El sistema debe permitir gestionar las asignaturas y vincularlas con los docentes y los salones. La asignación de clases debe respetar la disponibilidad de los profesores y los salones.
  - **Prioridad**: Alta

- **RF5: Exportación e Impresión de Horarios**
  - **Historia de Usuario**: El director del programa debe poder exportar los horarios en un formato estandarizado para impresión o distribución.
  - **Criterios de Aceptación**: Exportación de horarios en formato PDF para su impresión.
  - **Prioridad**: Media

- **RF6: Envío de Horarios por Email y WhatsApp**
  - **Historia de Usuario**: Los profesores deben recibir automáticamente sus horarios por correo electrónico o WhatsApp.
  - **Criterios de Aceptación**: Envío automático de horarios y confirmación de recepción.
  - **Prioridad**: Media

- **RF7: Notificaciones Automáticas**
  - **Historia de Usuario**: Los profesores deben recibir notificaciones automáticas en caso de que haya cambios o actualizaciones en sus horarios.
  - **Criterios de Aceptación**: Envío de notificaciones automáticas por correo electrónico o WhatsApp cuando se realicen cambios en los horarios.
  - **Prioridad**: Alta

## Requerimientos No Funcionales

- **RNF1: Protección de Datos y Seguridad**
  - **Descripción**: Garantizar la seguridad de la información y la protección contra accesos no autorizados.
  - **Criterios de Evaluación**: Implementación de medidas de autenticación robustas, cifrado de datos en tránsito y en reposo, y gestión adecuada de permisos de usuario.
  - **Prioridad**: Alta

- **RNF2: Escalabilidad y Capacidad de Manejo de Carga**
  - **Descripción**: Asegurar que el sistema pueda manejar un número creciente de usuarios y operaciones sin degradación en el rendimiento.
  - **Criterios de Evaluación**: Evaluación de la capacidad del sistema para manejar múltiples solicitudes concurrentes, optimización del rendimiento de bases de datos, y capacidad para distribuir la carga entre servidores si es necesario.
  - **Prioridad**: Alta

- **RNF3: Usabilidad y Experiencia del Usuario**
  - **Descripción**: Proporcionar una interfaz intuitiva y fácil de usar que se adapte a diferentes dispositivos y resoluciones de pantalla.
  - **Criterios de Evaluación**: Pruebas de usabilidad para asegurar una navegación fluida, diseño responsive que se adapte a dispositivos móviles y de escritorio, y cumplimiento de principios de diseño accesible.
  - **Prioridad**: Media

- **RNF4: Alta Disponibilidad y Fiabilidad**
  - **Descripción**: Garantizar que el sistema tenga un tiempo de actividad cercano al 100%, minimizando los tiempos de inactividad y asegurando la continuidad del servicio.
  - **Criterios de Evaluación**: Implementación de estrategias de alta disponibilidad, planes de contingencia para fallos del sistema, y programación de mantenimientos en horarios de menor impacto.
  - **Prioridad**: Alta

- **RNF5: Soporte Técnico y Actualizaciones**
  - **Descripción**: Proveer un plan integral para el soporte técnico y la actualización continua del sistema.
  - **Criterios de Evaluación**: Disponibilidad de soporte técnico para resolver problemas, procedimientos para aplicar parches de seguridad y actualizaciones periódicas para mejorar el sistema.
  - **Prioridad**: Media
  
## Levantamiento de Requerimientos

En XP, el levantamiento de los requerimientos es un proceso iterativo y colaborativo. El cliente (en este caso, el director del programa) trabaja de la mano con el equipo de desarrollo para crear **historias de usuario**, que describen las necesidades del sistema desde la perspectiva del usuario final. Estas historias se priorizan y se desarrollan en ciclos cortos, permitiendo la entrega continua de valor.

### Proceso:

1. **Reuniones frecuentes**: El equipo de desarrollo y el cliente se reúnen regularmente para definir, aclarar y priorizar las historias de usuario.
2. **Historias de usuario detalladas**: Se documentan las funciones requeridas por el cliente de forma sencilla y comprensible.
3. **Iteraciones rápidas**: Se trabaja en ciclos cortos donde se implementan las historias de usuario más prioritarias.
4. **Retroalimentación continua**: El cliente revisa el software al final de cada iteración, permitiendo ajustes o cambios según lo requerido.

## Ceremonias en XP

XP utiliza una serie de ceremonias para mantener al equipo enfocado en la entrega de valor y en la mejora continua. Las principales ceremonias son:

1. **Planning Game**: Es el momento en que el equipo y el cliente se reúnen para planificar las historias de usuario que se implementarán en la próxima iteración. Se identifican las prioridades y el equipo estima el esfuerzo necesario.
   
2. **Stand-ups**: Reuniones diarias cortas donde cada miembro del equipo comparte su progreso, dificultades y planes para el día. Estas reuniones permiten detectar obstáculos y coordinar esfuerzos.

3. **Pair Programming**: Dos desarrolladores trabajan juntos en una misma estación de trabajo. Uno escribe el código mientras el otro lo revisa en tiempo real, asegurando alta calidad en la implementación.

4. **Continuous Integration (CI)**: El código se integra de forma continua al sistema principal, lo que permite detectar rápidamente errores de integración y garantizar la coherencia del proyecto.

5. **Retrospectivas**: Después de cada iteración, el equipo reflexiona sobre lo que funcionó bien y lo que debe mejorar. Esta práctica permite ajustar los procesos y mejorar continuamente.

## Actores Clave en XP

En XP, los roles clave son más flexibles y colaborativos que en otras metodologías. Los actores principales son:

- **Cliente (Director del programa)**: Participa activamente en el desarrollo del proyecto. Define los requerimientos, prioriza las funcionalidades y da retroalimentación constante sobre los avances.
  
- **Equipo de Desarrollo**: Encargado de la implementación de las historias de usuario. Trabaja de manera colaborativa y en pares, asegurando la calidad del código y la entrega de valor continuo.

- **Coach**: El coach se encarga de guiar al equipo en la implementación correcta de las prácticas de XP, asegurándose de que se mantenga el enfoque en los valores y principios de la metodología.

- **Tracker**: Este rol supervisa el progreso del proyecto y se asegura de que el equipo cumpla con los tiempos estimados, ayudando a identificar obstáculos que puedan retrasar las entregas.

## Valores Fundamentales de XP

En el desarrollo de este proyecto, nos guiamos por los valores fundamentales de **Extreme Programming (XP)** para asegurar la calidad y efectividad del sistema. Estos valores son:

- **Comunicación**: Mantendremos una comunicación constante y clara entre todos los miembros del equipo y el cliente. Utilizaremos reuniones diarias y sesiones de revisión para asegurar que todos estén alineados con los objetivos del proyecto.

- **Simplicidad**: Adoptaremos un enfoque de desarrollo que prioriza soluciones simples y elegantes. Implementaremos solo las funcionalidades necesarias y realizaremos refactorizaciones para mantener la simplicidad del sistema.

- **Feedback**: Buscaremos retroalimentación continua del cliente y de las pruebas realizadas para ajustar y mejorar el sistema. Realizaremos revisiones de iteración y aplicaremos pruebas automatizadas para garantizar que el producto cumpla con las expectativas.

- **Coraje**: Enfrentaremos desafíos técnicos y tomaremos decisiones difíciles con determinación. Aplicaremos prácticas como el desarrollo guiado por pruebas (TDD) y la refactorización para mantener la calidad del código y la adaptabilidad del sistema.

- **Respeto**: Fomentaremos un ambiente de respeto y colaboración entre todos los miembros del equipo. Practicaremos el trabajo en pareja y colaboraremos en la planificación y ejecución de tareas para asegurar un trabajo en equipo efectivo y respetuoso.

Estos valores no solo guían nuestras prácticas, sino que también aseguran que el proyecto avance de manera eficiente y cumpla con los requisitos del cliente de la mejor manera posible.

## Ciclo de Desarrollo en XP

El ciclo de desarrollo en **Extreme Programming (XP)** se compone de las siguientes fases, que se repiten en cada iteración:

1. **Exploración**: Se identifican y definen los requisitos del cliente. El equipo trabaja estrechamente con el cliente para comprender las necesidades y establecer las prioridades para la iteración.

2. **Planeación**: Basado en los requisitos identificados, el equipo planifica las tareas y define los objetivos para la iteración. Se estima el tiempo y el esfuerzo necesario para cada tarea.

3. **Desarrollo**: Se implementan las funcionalidades planificadas. El equipo realiza programación en pareja, utiliza desarrollo guiado por pruebas (TDD) y mantiene el código simple y bien estructurado.

4. **Pruebas**: El sistema se somete a pruebas rigurosas para asegurar que cumple con los requisitos y funciona correctamente. Se realizan pruebas automatizadas y de integración para verificar la funcionalidad.

5. **Revisión**: Al final de la iteración, el equipo presenta el trabajo completado al cliente para obtener retroalimentación. Se revisa el progreso y se ajustan los requisitos y la planificación según sea necesario

## Diseño de Software en XP

El enfoque de diseño en XP se basa en el principio de **simplicidad**. Esto implica que el sistema se construya con la mínima complejidad necesaria para que funcione correctamente, permitiendo mejoras y cambios de forma constante. En lugar de realizar un diseño exhaustivo al inicio del proyecto, el diseño evoluciona conforme se obtienen más conocimientos y se comprenden mejor los requisitos.

### Principios de diseño:

- **YAGNI (You Aren’t Gonna Need It)**: Se implementa solo lo necesario para cumplir con los requerimientos actuales.
- **Refactorización continua**: El código se mejora de manera regular para mantener su simplicidad y claridad.
- **Diseño emergente**: El diseño del sistema cambia y mejora conforme se desarrollan nuevas funcionalidades.


## Ver Documentación
La documentación mas detallada del proyecto en el marco de trabajo para desarrollo ágil de Software Scrum, se puede ver en el siguiente enlace redireccionado al Drive:

### [Documento](https://docs.google.com/document/d/1OV6Yk-lWfgobOcHDnXjiGqmO7jfshhHu/edit?usp=sharing&ouid=109014329295797922250&rtpof=true&sd=true)
![Portada](d)
