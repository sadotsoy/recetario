<!-- link internal -->
<a name="botanas"></a>

# Recetario

Recetario lleno de amor, libertad y sabor.

**v1.0.0**

<!-- page break for pandoc converter or html converter -->
\pagebreak
<div style="page-break-after: always;"></div>

## Índice

- [`Botanas Github`](./recetario/botanas/index.md)

- [`Botanas pdf`](#botanas)

## Contribuir

Recetas nuevas son bienvenidas, a través de issues para discutir, purgar, filtrar dicha receta.

## Convertir a PDF

La forma que yo estoy usando para convertir todo en un pdf: (v1.0.0)

1. Convierto todo los `*.md` en uno solo con cat:
  ```bash
   $ cat **/.* recetario.md
  ```
  1.1 Modifico el recetario para borrar los links de Github
  1.2 Modifico el recetario para acomodar los indices de cada sección
2. Uso [Pandoc](https://pandoc.org) para convertir el archivo de todo en uno `recetario.md` en un pdf usando:
```
  $ pandoc recetario.md -o recetario.pdf
```

## Licencia
[MIT](https://choosealicense.com/licenses/mit/)
