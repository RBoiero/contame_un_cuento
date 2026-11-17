# Contame un cuento

Prueba pública del visor de cuentos interactivos de Pintando Juntos.

Sitio previsto: https://rboiero.github.io/contame_un_cuento/

Este repositorio conserva únicamente una copia compilada del visor: catálogo,
lector, decisiones e ilustraciones. No incluye coloreado, panel administrativo,
editor de cuentos, backend ni base de datos. El progreso se guarda en este
navegador; no se comparte entre dispositivos.

El cuento actual, **Dante y el dragón del bosque**, sigue en construcción:
algunos caminos terminan en «Continuará» o «Camino por contar».

## Desarrollo y futuras pruebas

Esta copia corresponde sólo a la prueba pública autorizada. El proyecto
completo, el desarrollo y las siguientes pruebas de cuentos continúan en
[Coloreando](https://github.com/RBoiero/Coloreando). No hay sincronización
automática desde ese repositorio hacia éste.

## Publicación

El sitio se publica directamente desde los archivos compilados de `main`, sin
instalar dependencias ni ejecutar un backend. Para activarlo una sola vez:

1. Abrir **Settings → Pages → Build and deployment**.
2. Elegir **Source: Deploy from a branch**.
3. Elegir **Branch: main**, carpeta **/ (root)** y pulsar **Save**.

GitHub publicará el sitio en la dirección indicada arriba. El archivo
`.nojekyll` permite servir directamente los archivos estáticos de Next.js.
No se necesita configurar secretos o credenciales para el hosting.

No cambiar el nombre del repositorio sin volver a compilar: enlaces e imágenes
usan el prefijo `/contame_un_cuento`. Para actualizar esta copia se requiere
una nueva exportación revisada y una publicación explícitamente autorizada.

Para volver a una publicación anterior, revertir el cambio del snapshot en
`main` y dejar que GitHub Pages publique esa revisión. También se puede desactivar
GitHub Pages desde Settings. No hay datos de servidor que migrar.
