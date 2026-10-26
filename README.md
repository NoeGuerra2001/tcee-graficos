# tcee-graficos

Gráficos interactivos del temario TCEE para insertar en Obsidian con un `<iframe>`.

- `edgeworth.html` — caja de Edgeworth (3A21). Configuraciones: `#walras`, `#neg`, `#sim`, `#eff`.
- `tecnologia.html` — tecnología de la empresa (3A11). Vistas: `#corto`, `#largo`.
- `keynes.html` — Keynes: trabajo, bienes y dinero (3A4). Vistas: `#trabajo`, `#bienes`, `#dinero`.
- `marshall.html` — Marshall: periodos de oferta y cuasi-rentas (3A3). Plazo inicial: `#mc`, `#cp`, `#lp`, `#mlp`.
- `islm.html` — el IS-LM según las escuelas (3A5, Anexo 3). Pestaña inicial: `#pend`, `#hicks`, `#clas`, `#key`, `#sin`, `#mon`, `#nc`, `#nk`.

Parámetros: `?compacto=1` oculta la cabecera; `?tema=claro|oscuro` fuerza el tema.

Ejemplo en una nota de Obsidian:

```html
<iframe src="https://noeguerra2001.github.io/tcee-graficos/edgeworth.html?compacto=1#neg" width="100%" height="1500" style="border:0"></iframe>
```
