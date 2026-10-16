# 🎾 Peña de Pádel

Clasificación, fichas de jugador, récords y jornadas. Los datos viven en `data.json`.

## Publicar (una sola vez)

1. En github.com: **+ → New repository** → nombre sin espacios (p. ej. `PenaPadel`) → **Public** → Create repository.
2. **Add file → Upload files** y sube `index.html` y `data.json` → **Commit changes**.
3. **Settings → Pages** → *Deploy from a branch* → rama `main`, carpeta `/ (root)` → Save.
4. En 1–2 minutos estará en `https://TU_USUARIO.github.io/PenaPadel/`. Ese es el enlace para el grupo.

## Acceso de administrador

1. GitHub → tu foto → **Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**.
2. *Repository access*: **Only select repositories** → tu repo. *Permissions → Contents*: **Read and write**. Genera y copia el token (solo se muestra una vez).
3. En la web, pestaña **Admin**: comprueba el repositorio (`usuario/repo`), pega el token y pulsa Entrar.
4. Cada cambio (jornadas, jugadores, ajustes, resúmenes) se guarda como un commit en `data.json`. Los demás lo ven en 1–2 minutos.

## Notas

- Nunca subas el token al repositorio ni lo compartas por canales públicos: da permiso de escritura.
- Con un repositorio público, cualquiera con el enlace puede ver nombres y resultados.
- El resumen de cada jornada ya no se genera solo: el administrador lo pega con «Añadir resumen» en la pestaña Jornadas.
- `data.json` ya incluye las 7 jornadas disputadas hasta el 15/10/2026, los 17 jugadores y los ajustes del algoritmo (escala 1300).

## Copyright

© 2026 Pádel Jueves Central. Todos los derechos reservados. Ver el archivo `LICENSE`.
