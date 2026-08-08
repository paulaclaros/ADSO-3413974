|# Pruebas de Usabilidad - Sistema de Gestión de Horarios SENA

## Objetivo

Realizar una evaluación del sistema desde la perspectiva de los
diferentes roles de usuario, identificando oportunidades de mejora que
permitan optimizar la experiencia de uso, la organización de la
información y la eficiencia de las tareas diarias.

------------------------------------------------------------------------

# Rol: Coordinador Académico

## Observación 1: Agregar autocompletado en el campo "Nombre"

Durante la prueba del módulo **Horarios**, se identificó que el campo
**Nombre** requiere que el coordinador académico escriba manualmente el
nombre completo del programa y el trimestre, por ejemplo: **ADSO
Trimestre III**.

Como usuario, considero que este proceso resulta más lento cuando se
deben registrar o consultar varios horarios. Una mejora sería
implementar un campo con autocompletado o un menú desplegable de
sugerencias.

### Beneficios

-   Reduce el tiempo de búsqueda y registro.
-   Evita errores de digitación.
-|   Mantiene la información estandarizada.
-   Mejora la experiencia del coordinador académico.

## Observación 2: Incorporar filtros por ficha en las notificaciones

Durante la prueba del módulo **Notificaciones**, se observó que todas
las notificaciones se presentan en una única lista.

Como usuario, considero que sería útil implementar un filtro por ficha
para visualizar únicamente las notificaciones relacionadas con un grupo
específico de aprendices.

### Beneficios

-   Facilita la búsqueda de información.
-   Mejora la organización.
-   Reduce el tiempo de consulta.
-   Optimiza la gestión de varias fichas.

## Observación 3: Separar la disponibilidad de ambientes e instructores

Durante la prueba del módulo **Disponibilidad**, se observó que la
información de ambientes e instructores se encuentra agrupada.

Como usuario, considero que sería más práctico contar con dos apartados
independientes.

### Beneficios

-   Facilita la consulta.
-   Mejora la organización.
-   Reduce el tiempo de búsqueda.
-   Evita confusiones.

## Observación 4: Implementar un menú desplegable en la búsqueda de fichas

Durante la prueba del módulo **Fichas**, se observó que la búsqueda de
un programa debe realizarse escribiendo manualmente el nombre completo.

Como usuario, considero que sería más eficiente incorporar un menú
desplegable con autocompletado.

### Beneficios

-   Agiliza la búsqueda.
-   Reduce errores de escritura.
-   Facilita la gestión de programas.
-   Mejora la experiencia del usuario.

------------------------------------------------------------------------

# Rol: Instructor

## Observación 1: Permitir adjuntar soportes de incapacidad o justificación

Durante la prueba del módulo **Mi Disponibilidad**, se observó que en la
sección **Incapacidades** no existe una opción para adjuntar documentos
que respalden la ausencia del instructor.

### Beneficios

-   Centraliza la información.
-   Facilita la validación.
-   Mantiene un historial de soportes.

## Observación 2: Mejorar la claridad de los indicadores del módulo de Seguimiento

Durante la prueba del módulo **Seguimiento**, se observó que algunos
indicadores no son lo suficientemente claros para el usuario.

Como instructor, sería útil incluir explicaciones o íconos de ayuda
sobre cada indicador.

### Beneficios

-   Facilita la comprensión.
-   Reduce la confusión.
-   Mejora la experiencia de uso.

## Observación 3: Completar la visualización de todos los días en el horario

Durante la prueba del módulo **Mi horario**, se observó que la
programación no contempla claramente todos los días de la semana.

Como instructor, el horario debería incluir también sábados y domingos
para los programas que tienen formación esos días.

### Beneficios

-   Permite visualizar toda la programación.
-   Facilita la planificación.
-   Evita confusiones.

------------------------------------------------------------------------

# Rol: Aprendiz

## Observación 1: Adaptar el estado de las notificaciones al rol de Aprendiz

Durante la prueba del módulo **Notificaciones**, se observó que el
estado mostrado no corresponde al rol del aprendiz.

Como usuario, sería más útil visualizar estados como **Leída**, **No
leída** o **Pendiente**.

### Beneficios

-   Información acorde al rol.
-   Evita confusiones.
-   Mejora la experiencia de usuario.

## Observación 2: Mostrar el estado de la clase en la vista principal del horario

Durante la prueba del módulo **Horario**, se observó que el estado de la
clase solo puede consultarse al ingresar en **Ver detalles**.

Como usuario, el estado debería mostrarse directamente en la vista
principal mediante etiquetas como **Activa**, **Cancelada**,
**Reprogramada** o **Finalizada**.

### Beneficios

-   Permite conocer el estado rápidamente.
-   Reduce el tiempo de consulta.
-   Evita confusiones.

------------------------------------------------------------------------

# Rol: Director de Centro

## Observación 1: Aclarar la función "Modo revisión · Cambiar rol"

Durante la prueba del sistema, se observó que esta opción puede generar
confusión.

Como usuario, sería recomendable incluir una breve explicación o cambiar
el nombre por uno más descriptivo, como **Vista previa de roles** o
**Simular rol**.

### Beneficios

-   Reduce la confusión.
-   Facilita la navegación.
-   Mejora la experiencia de usuario.

## Observación 2: Aclarar la edición del código del centro

Durante la prueba del módulo **Datos de referencia**, se observó que el
campo **Código del centro** no permite modificar su valor, pero la
interfaz no lo comunica.

Como usuario, el campo debería mostrarse como **solo lectura** o indicar
que no es editable.

### Beneficios

-   Evita intentos innecesarios de edición.
-   Reduce la confusión.
-   Hace la interfaz más intuitiva.

------------------------------------------------------------------------

# Conclusión

En general, el sistema presenta una interfaz organizada y fácil de
utilizar. Las mejoras propuestas buscan optimizar la usabilidad,
facilitar la interpretación de la información y agilizar las tareas de
cada rol.
