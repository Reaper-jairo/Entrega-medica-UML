**Correcion diagrama caso de uso**

1.Se elimnino el apartado de "ver historial de otras personas"ya que esta inflingiendo la privacidad y segurudad de las demas personas.

2.Se cambio el apartdado de "ver disponibilidad externa" a solo "ver disponibilidad"ya que esto es parte interna del sistema por lo cual no se le debe decir lo que se esta haciendo al usuario.

3.“Cancelar reserva” extiende a “Agregar motivo de cancelación”.

Estos son comportamientos opcionales o condicionales, no acciones independientes. Usar <<extend>> indica que estas funciones solo ocurren bajo ciertas condiciones, como cuando el usuario elige eliminar o cancelar.


**Correcion diagrama de clases:**

El diagrama original del profesor presentaba clases aisladas y sin relaciones claras, como Reserva, que no indicaba ni usuario ni sala asociada. Se corrigió añadiendo asociaciones clave y atributos como hora de inicio , hora de final y un menú para EstadoReserva. También se conectó la clase con la de SistemaReservas con el sistema de notificaciones. Se agregaron cardinalidades a todas las relaciones para evitar ambigüedades. Además, se hicieron explícitas las interacciones entre clases mediante dependencias, mejorando así la claridad.


**Correcion digrama de secuencia:**
El diagrama presenta alto acoplamiento en el “Sistema de Gestión de Reservas”, falta claridad en las relaciones (tipo de interacción) y un nivel de detalle inconsistente. Se recomienda modularizar responsabilidades, etiquetar las flechas con estereotipos claros y unificar el nivel de abstracción para mejorar legibilidad y mantenibilidad.

