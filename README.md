# Campus YaskCode — vista de pruebas

Este repositorio publica una copia de la rama `experiment/campus-loading-flip-cards` de `yaskelly/yaskelly.github.io`.

El Campus oficial permanece en https://yaskelly.github.io/ y no se modifica desde este repositorio.

## Primera prueba

- Base de producción: `27daa48a0a1f8a98c8893b7693d8502ef797b1de`.
- Prueba de carga eager: `c37889ecc8f40dba1b3cb9557f59e92341fa4252`.
- Mismas imágenes, posiciones, textos e interacciones; solo cambia lazy por eager en las imágenes del mapa.
- Referencia inicial del usuario: 26,9 MB, 19 solicitudes, Finish entre 8,64 y 8,86 s, sin caché y sin limitación de red, pantalla 388 × 877.
- No se han implementado tarjetas giratorias.

## Publicación

Configurar Settings → Pages → Source: GitHub Actions. Ejecutar manualmente el workflow Campus Preview desde main.

El workflow adapta únicamente las rutas para `/campus-yaskcode-preview/`, marca la copia como no indexable y comprueba los recursos locales del HTML generado.
