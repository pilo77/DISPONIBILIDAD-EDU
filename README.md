# Sistema de Gestión de Horarios - Proyecto XP

## Necesidad del Cliente

La institución educativa enfrenta dificultades en la organización de horarios de clases debido al uso de hojas de cálculo, lo que genera desorden en la asignación de clases y problemas con la disponibilidad de profesores y salones. Esto resulta en confusión, conflictos de horarios y pérdida de tiempo, afectando tanto a los docentes como a los encargados de la planificación.

## Objetivo

Desarrollar una página web que facilite la gestión de los horarios de clases, optimizando la distribución de salones y horas de trabajo de los profesores. Esta herramienta mejorará la planificación, eliminando los problemas de conflictos de horarios y mejorando la comunicación con los profesores mediante la posibilidad de imprimir y enviar los horarios por correo electrónico o WhatsApp.

## Requerimientos Funcionales

### RF1: Gestión de Docentes y Carga Académica
**Historia de Usuario**: El director del programa debe gestionar la carga académica de los docentes según su contrato.
- **Criterios de Aceptación**: Ingreso de información de docentes, cálculo automático de horas según el contrato, registro y actualización automática de la carga horaria.
- **Prioridad**: Alta

### RF2: Gestión de Salones y Bloques
**Historia de Usuario**: El director organiza la asignación de salones y horarios de clases, evitando conflictos de disponibilidad.
- **Criterios de Aceptación**: Asignación de salones de forma manual o automática sin solapamientos.
- **Prioridad**: Alta

### RF3: Asignación de Horarios y Evitación de Cruces
**Historia de Usuario**: El director asigna horarios a los docentes, asegurándose de que no haya cruces o sobrecargas horarias.
- **Criterios de Aceptación**: Asignación de horarios respetando disponibilidad de profesores y evitando conflictos de horario.
- **Prioridad**: Alta

### RF4: Exportación e Impresión de Horarios
**Historia de Usuario**: El director debe imprimir los horarios de clases en un formato estandarizado.
- **Criterios de Aceptación**: Exportación de horarios en formato PDF listo para impresión.
- **Prioridad**: Media

### RF5: Envío de Horarios por Email y WhatsApp
**Historia de Usuario**: El director del programa envía los horarios a los profesores por correo electrónico o WhatsApp.
- **Criterios de Aceptación**: Envío automático de horarios con confirmación de recepción.
- **Prioridad**: Media

## Requerimientos No Funcionales

### RNF1: Seguridad del Sistema
**Descripción**: Protección de credenciales y datos sensibles de docentes y salones.
- **Criterios de Evaluación**: Autenticación segura, cifrado de datos y validación de permisos de acceso.
- **Prioridad**: Alta

### RNF2: Escalabilidad y Rendimiento
**Descripción**: El sistema debe soportar múltiples usuarios simultáneos sin afectarse el rendimiento.
- **Criterios de Evaluación**: Manejo de concurrencia, optimización de bases de datos, distribución de carga eficiente.
- **Prioridad**: Alta

### RNF3: Interfaz de Usuario (UI/UX)
**Descripción**: El sistema debe ser fácil de usar y accesible desde distintos dispositivos.
- **Criterios de Evaluación**: Adaptación a diferentes resoluciones y dispositivos móviles.
- **Prioridad**: Media

### RNF4: Disponibilidad del Sistema
**Descripción**: El sistema debe estar disponible el 99.9% del tiempo, con mantenimientos fuera de horarios críticos.
- **Criterios de Evaluación**: Monitoreo constante y planificación de tiempos de inactividad.
- **Prioridad**: Alta

### RNF5: Mantenimiento y Soporte
**Descripción**: Plan de soporte y mantenimiento continuo del sistema.
- **Criterios de Evaluación**: Actualizaciones periódicas, corrección de errores y mejoras de funcionalidad.
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

## Diseño de Software en XP

El enfoque de diseño en XP se basa en el principio de **simplicidad**. Esto implica que el sistema se construya con la mínima complejidad necesaria para que funcione correctamente, permitiendo mejoras y cambios de forma constante. En lugar de realizar un diseño exhaustivo al inicio del proyecto, el diseño evoluciona conforme se obtienen más conocimientos y se comprenden mejor los requisitos.

### Principios de diseño:

- **YAGNI (You Aren’t Gonna Need It)**: Se implementa solo lo necesario para cumplir con los requerimientos actuales.
- **Refactorización continua**: El código se mejora de manera regular para mantener su simplicidad y claridad.
- **Diseño emergente**: El diseño del sistema cambia y mejora conforme se desarrollan nuevas funcionalidades.

## Repositorio Git

Este proyecto se gestiona utilizando **Git** como sistema de control de versiones. Los cambios en el código se integran de manera continua para asegurar la estabilidad y coherencia del proyecto.

### Clonar el repositorio

Para obtener una copia local del proyecto, usa el siguiente comando:

```bash
git clone https://github.com/usuario/nombre-del-repositorio.git
