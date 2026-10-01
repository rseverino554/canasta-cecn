# Canasta CECN

Los productos con los que el CECN (Centro de Estudios Cuantitativos en Negocios,
Universidad de San Andrés) calcula el Índice de Competencia de Precios y el Pulso
Regional de Precios, a partir de los datos de SEPA (Sistema Electrónico de
Publicidad de Precios Argentinos).

- `index.html`: la canasta por grupo y categoría.
- `canasta.csv` y `canasta.xlsx`: la canasta entera, un código por fila.

| Columna | Qué es |
|---|---|
| `codigo` | EAN-13 del producto, o código interno de la cadena en el fresco por peso |
| `descripcion`, `marca` | como las publica la cadena |
| `grupo`, `categoria` | dónde está en la canasta |
| `producto_fresco` | en el fresco por peso, el producto que agrupa varios códigos de cadena (por ejemplo, "Banana"); vacío en el envasado |

Este repositorio se genera desde el proyecto de indicadores; no se edita a mano.
