# nephei-pluto

[pluto.nephei.org](https://pluto.nephei.org): una campaña completamente seria para que Plutón vuelva a ser planeta.

## Estructura

- `public/`: lo que se publica tal cual. Una sola página, sin dependencias salvo las fuentes de Google Fonts.
- `wrangler.jsonc`: configuración del Worker `nephei-pluto` (solo assets estáticos, sin código de servidor).

## Despliegue

El repositorio está conectado al Worker `nephei-pluto` con Workers Builds: cada push a `main` lo despliega en `pluto.nephei.org`.
