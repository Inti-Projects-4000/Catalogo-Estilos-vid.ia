# Catalogo-Estilos-vid.ia

Catálogo de estilos para VID.IA. La app lee `indice.json` y desde la Biblioteca instala cada estilo de la carpeta `estilos/`.

Cada estilo conserva el nombre de su autor y se publica con su permiso.

## Agregar un estilo

1. En VID.IA, exporta el estilo como archivo `.sloth-estilo` y ponlo en `estilos/`.
2. Agrega su entrada a `indice.json`: `id`, `titulo`, `descripcion`, `autor`, `icono` y `archivo` (por ejemplo `estilos/mi-estilo.sloth-estilo`).
3. Sube los cambios. Los clientes lo ven al abrir la Biblioteca, sin reinstalar la app.
