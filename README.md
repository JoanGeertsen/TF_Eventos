# Trabajo Práctico - JavaScript y DOM

## Descripción
Este proyecto consiste en crear una página web que permita **registrar diversos eventos** utilizando JavaScript y manipulando el DOM. Los datos de los eventos se guardarán en un arreglo de objetos, lo que permitirá su recuperación rápida y eficiente.

## Requisitos
La página debe ser monolítica (todo en una misma página) y debe tener un diseño atractivo. Los eventos que se registren tendrán los siguientes campos:

### Datos a ingresar:
- **Nombre del evento**: El título o nombre del evento.
- **Tipo de evento**: Seleccionar entre concierto, exposición o feria (utilizando radiobuttons).
- **Fecha del evento**: Campo para ingresar la fecha en que ocurrió el evento.
- **Dirección**: Dirección del lugar donde se llevó a cabo el evento.
- **Ciudad**: Ciudad donde se realizará (seleccionar entre varias opciones predefinidas usando un combobox).
- **Capacidad del evento**: Cantidad de asistencia permitida.
- **Evento gratuito**: Opción para tildar si el evento es gratuito.
- **Costo de entrada**: Precio de la entrada, o mensaje de evento gratuito si aplica.
- **Valoración del evento**: Sistema de puntuación (1 a 5 estrellas) o una escala numérica.
- **Observaciones**: Notas adicionales sobre el evento.

## Funcionalidades
### Botones a implementar:
- **CARGAR**:
  - Valida los datos ingresados (los campos obligatorios se deben marcar como requeridos).
  - La validación incluye chequear que el nombre del evento no esté previamente registrado.
  - Si todos los datos son correctos, los guarda en el arreglo de eventos y asigna un número de evento usando la función "próximo" (vista en clase).
  - Muestra un mensaje de confirmación con los detalles del evento registrado.

- **RESETEAR**: Limpia todos los campos del formulario.

- **LISTAR**: Lista todos los nombres de los eventos registrados.

- **BUSCAR**: Permite buscar un evento por su nombre y mostrar todos sus datos en un mensaje.

- **FILTRAR**: Permite filtrar los eventos registrados por ciudad y mostrar todos los eventos de esa ciudad en un mensaje (usando `filter`).

- **Función adicional**: Agregar un botón con una funcionalidad extra no mencionada anteriormente.

## Instrucciones
1. Completa los datos en el formulario de la página para registrar un nuevo evento.
2. Utiliza los botones para interactuar con los eventos registrados.
