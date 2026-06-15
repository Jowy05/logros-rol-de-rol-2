# 📖 Guía del DM — Logros de "Rol de Rol 2"

Panel de logros de la campaña. **Esta guía solo la ves tú (Didac)** y puedes editarla con el botón **✏️ Editar** de arriba; al guardar, se actualiza en la nube.

## Cómo entran los jugadores
- Cada uno entra con su **nombre** y su **contraseña**.
- Jugadores (**Joel, Cristina, Carol, Leomar, Oriol**) → contraseña `RoldeRol2Campaña`.
- **Didac (DM)** → tu contraseña de máster (distinta).

## Cómo funciona el progreso
- **Cada jugador lleva SU propio progreso**: lo que marca uno es suyo.
- Al **marcar** un logro hay **animación + sonido** de "¡Logro desbloqueado!", se **guarda solo en la nube** y queda con la **fecha** en que se consiguió.
- Cada tarjeta muestra **👥 cuántos jugadores** lo han conseguido.
- Arriba tienes **buscador** y **filtro** (Todos / Pendientes / Conseguidos).

## Recompensas
- Cada logro tiene una **recompensa** (🎁). Por defecto: los de grupo/personaje → *"Punto de inspiración"*; los genéricos → *"XP extra"*.
- **Tú decides** qué da cada una: cámbialas en modo edición y pon lo que quieras (p. ej. "500 XP").

## Modo edición (solo DM)
Activa **"✏️ Modo edición"**. Podrás:
- **Editar** el nombre, la descripción y la recompensa de cada logro (escribiendo en sus campos).
- **Añadir** logros nuevos (formulario arriba; se añaden a la pestaña en la que estés: Grupo, Para todos o un personaje).
- **Borrar** logros (🗑).
- **Reordenar**: arrastra una tarjeta a otra posición, o usa las flechas **▲▼**.
- Todo se **guarda solo** para todo el grupo.

## Resumen de campaña 📊
Con el botón **"📊 Resumen"** ves el progreso de cada jugador (cuántos logros lleva) y cuántos se han conseguido en total en la campaña.

## Notas técnicas
- Los datos (logros, progreso y esta guía) viven en **Firebase** (la nube) y se guardan automáticamente.
- En el repositorio quedan `logros.json` y `progreso.json` como **copia de seguridad de solo lectura** por si Firebase fallara.
- Las contraseñas se guardan como **hash** en el código (`index.html`, bloque `USERS`); para cambiarlas, mira la nota de ahí.
