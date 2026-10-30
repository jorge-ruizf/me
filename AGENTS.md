# AGENTS.md

## Antes de tocar estilos

Lee `steering/design.md` por ruta explícita antes de modificar cualquier
archivo de `css/` o el marcado visual de `index.html`. No dependas de `glob`,
`grep` ni búsquedas del editor: `steering/` está ignorado por git y esas
herramientas pueden ocultarlo.

`steering/` es memoria de diseño privada. No lo borres, no lo muevas y no lo
incluyas en commits.

## Reglas del proyecto

- HTML + CSS + JS mínimo, sin build, sin frameworks y sin dependencias externas.
- El sitio se publica en `https://jorge-ruizf.github.io/me/`: todas las rutas
  deben ser relativas (`css/...`, `assets/...`), nunca con `/` inicial.
- La página contiene únicamente el nombre y la información de los proyectos.
  No agregar teléfono, correo, dirección, educación, habilidades ni secciones
  personales.
- Mantener `lang="es"`, un solo `h1`, un `h2` por proyecto, foco visible,
  contraste AA y soporte para `prefers-reduced-motion` y
  `prefers-reduced-transparency`.
- Si cambia una decisión de diseño, actualiza `steering/design.md` en la misma
  sesión.
