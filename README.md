# CampusFest 🎉

CampusFest es un proyecto pensado para organizar los eventos del campus de una forma más fácil: ver cuántos cupos quedan, reservar tu lugar y que los organizadores puedan hacer cambios cuando haga falta.

Por ahora este repositorio guarda los diagramas con los que estamos planeando cómo va a funcionar todo. Todavía no hay código, primero toca tener claro el plan.

## ¿Qué se puede hacer?

- **Consultar cupos:** saber si todavía hay espacio en un evento.
- **Gestionar reservas:** apartar un lugar (o cancelarlo).
- **Modificar eventos:** cambiar los datos de un evento si algo cambia.

## ¿Qué hay en las carpetas?

Todo está en la carpeta `docs`, hecho en [draw.io](https://app.diagrams.net/):

- **`docs/CdU`**: los casos de uso, es decir, quién usa la app y para qué.
- **`docs/Analisis`**: cómo se conectan las partes por dentro:
  - `Colaboracion_General`: una vista general de cómo trabajan juntas las piezas.
  - `Clases_Entidad`: las "cosas" principales del sistema (como eventos o reservas), con y sin estereotipos.
  - `Consultar_Cupos`, `Gestionar_Reserva` y `Modificar_Evento`: el detalle de cada funcionalidad, con diagramas de colaboración, comunicación y secuencia.

## ¿Cómo abrir los diagramas?

Los archivos `.drawio` se abren gratis en [app.diagrams.net](https://app.diagrams.net/) o con la extensión de draw.io en VS Code.

