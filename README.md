# Proyecto de Desarrollo con Extreme Programming (XP)

## Descripción

Este proyecto sigue la metodología **Extreme Programming (XP)**, que se centra en mejorar la calidad del software y la capacidad de respuesta a las necesidades cambiantes del cliente. XP fomenta una comunicación continua, la mejora de los procesos y el desarrollo iterativo, enfocado en la simplicidad y la retroalimentación rápida.

## Definición de XP

**Extreme Programming (XP)** es una metodología ágil de desarrollo de software que se enfoca en la satisfacción del cliente a través de la entrega continua de software funcional y de alta calidad. A diferencia de otras metodologías, XP favorece un enfoque adaptable, iterativo e incremental, donde la colaboración constante con el cliente y el equipo de desarrollo es clave.

XP se enfoca en valores como:

- **Comunicación**
- **Retroalimentación**
- **Simplicidad**
- **Coraje**
- **Respeto**

## Levantamiento de Requisitos

En XP, el proceso de levantamiento de requisitos se realiza de manera continua y colaborativa. A través de **historias de usuario**, el cliente comunica las necesidades del sistema. Estas historias de usuario son simples descripciones de la funcionalidad que el sistema debe cumplir desde la perspectiva del usuario final.

### Pasos en el Levantamiento:

1. **Reunión con el cliente**: Se realizan reuniones frecuentes con el cliente para obtener las historias de usuario y aclarar los requisitos.
2. **Definición de historias de usuario**: Los requisitos se definen en pequeños bloques de trabajo que representan funciones específicas.
3. **Priorización**: El cliente prioriza las historias de usuario según su importancia.
4. **Iteraciones rápidas**: Cada ciclo de desarrollo trabaja en las historias más prioritarias, entregando funcionalidad al final de cada iteración.

## Requerimientos Funcionales

Los **requerimientos funcionales** describen las funcionalidades específicas que el sistema debe implementar para cumplir con las expectativas del usuario. Estos requerimientos se extraen directamente de las historias de usuario y se adaptan conforme avanza el proyecto.

### Lista de Requerimientos Funcionales:

1. **Registro de Usuarios**: El sistema debe permitir que los usuarios se registren proporcionando información básica como nombre, correo electrónico y contraseña. 
   
2. **Autenticación y Autorización**: Los usuarios deben poder iniciar sesión y solo aquellos con las credenciales correctas podrán acceder a las áreas protegidas del sistema.

3. **Gestión de Perfiles de Usuario**: Los usuarios deben poder actualizar su perfil personal, cambiar su contraseña y gestionar sus preferencias.

4. **Creación de Contenido**: Los usuarios autenticados deben poder crear, editar y eliminar contenido dentro del sistema, como artículos, publicaciones o comentarios.

5. **Búsqueda de Contenido**: El sistema debe permitir la búsqueda de contenido relevante basado en palabras clave, categorías o etiquetas.

6. **Notificaciones en Tiempo Real**: Los usuarios recibirán notificaciones sobre eventos relevantes, como comentarios en sus publicaciones o menciones por otros usuarios.

7. **Sistema de Roles**: El sistema debe tener distintos niveles de acceso según el rol del usuario (administrador, editor, usuario regular), cada uno con diferentes permisos para interactuar con el contenido.

8. **Generación de Reportes**: Los administradores del sistema deben poder generar reportes personalizados sobre el uso del sistema, estadísticas de usuarios y contenido.

9. **Integración con Redes Sociales**: Los usuarios deben poder compartir contenido fácilmente en plataformas sociales como Twitter y Facebook.

10. **Soporte para Múltiples Idiomas**: El sistema debe permitir la selección de idioma para que los usuarios puedan utilizarlo en el idioma que prefieran.

### Prioridad y Iteraciones

Los requerimientos funcionales se implementan por orden de prioridad, según las necesidades del cliente. Cada iteración del proyecto incluye una serie de estos requerimientos, que se integran, prueban y entregan al cliente para obtener retroalimentación continua.

## Ceremonias en XP

En XP se priorizan las **iteraciones cortas** y las entregas frecuentes de software funcional. Las ceremonias clave son:

1. **Planning Game**: Similar a la planificación del sprint en otras metodologías, el equipo y el cliente se reúnen al comienzo de cada iteración para planificar las tareas a realizar basándose en las historias de usuario.
   
2. **Stand-ups**: Reuniones diarias cortas donde cada miembro del equipo comenta en qué está trabajando, qué ha completado y qué bloqueos enfrenta.

3. **Pair Programming**: En XP, los desarrolladores trabajan en parejas, compartiendo una única estación de trabajo. Uno escribe el código mientras el otro revisa, y ambos intercambian roles continuamente.

4. **Continuous Integration**: Se practica la integración continua, donde los cambios en el código se integran y prueban de forma automática para evitar problemas de integración.

5. **Retrospectivas**: Al finalizar cada iteración, el equipo reflexiona sobre lo que salió bien y lo que puede mejorar para la siguiente iteración.

## Actores Clave

En XP, hay varios roles importantes:

- **Cliente**: El cliente tiene un rol activo en todo el proceso. Está presente en las reuniones de planificación y proporciona retroalimentación constante. Define las historias de usuario y prioriza las entregas.

- **Desarrollador**: Los desarrolladores implementan las historias de usuario siguiendo prácticas como la programación en pareja (Pair Programming) y la integración continua. También son responsables de escribir pruebas automatizadas que validen el funcionamiento del software.

- **Coach**: Ayuda a mantener la disciplina dentro del equipo, asegurando que las prácticas de XP se sigan correctamente.

- **Tracker**: Persona que monitorea el progreso del equipo y mide la velocidad del proyecto para ayudar en la planificación.

## Diseño de Software en XP

El diseño en XP sigue los principios de **diseño simple**. La idea es crear el software con la estructura más simple posible que permita que funcione. En lugar de planificar todo desde el principio, el diseño evoluciona durante el desarrollo. Se ajusta continuamente conforme se aprende más sobre el sistema y se reciben más requisitos del cliente.

Principios de diseño en XP:
- **No añadir funcionalidad antes de que sea necesaria**: Se implementa solo lo que el cliente ha solicitado.
- **Refactorización continua**: Se mejora el código existente regularmente para mantener su calidad y evitar que se vuelva ineficiente o difícil de entender.
- **Diseño emergente**: A medida que se avanza en el proyecto, el diseño del sistema puede cambiar para mejorarlo o adaptarlo a nuevas condiciones.
