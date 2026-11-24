# Curso de Preparación · Henry

Repositorio de materias, ejemplos y homework del módulo de preparación (Prep) de Henry. Está organizado por unidades, con consignas, material de apoyo y tests ejecutables por homework.

<img src="./logo.png" height="70" alt="Henry" />

## Contenido

- [Módulos](#módulos)
- [Conceptos](#conceptos)
- [Clases de repaso](#clases-de-repaso)
- [Homeworks y tests](#homeworks-y-tests)
- [La carrera](#la-carrera)

## Módulos

| # | Unidad | Contenido |
| :-: | --- | --- |
| 00 | [Primeros pasos](./00-PrimerosPasos) | Herramientas, editor, terminal y configuración inicial |
| 01 | [Git](./01-Git) | Repositorios, estados, snapshots y GitHub |
| 02 | [JS I](./02-JS-I) | Variables, tipos de datos y funciones |
| 03 | [JS II](./03-JS-II) | Flujos de control, operadores de comparación y bucles `for` |
| 04 | [JS III](./04-JS-III) | Bucles `for` y arrays |
| 05 | [JS IV](./05-JS-IV) | Objetos |
| 06 | [JS V](./06-JS-V) | Clases y prototype |
| 07 | [JS VI](./07-JS-VI) | Callbacks |
| 08 | [HTML](./08-HTML) | Estructura y box model |
| 09 | [CSS Positioning](./09-CSS-Positioning) | Posicionamiento y layout |

¿Querés rendir el challenge? [Inscribite acá](https://challenge.prep.soyhenry.com/).

## Conceptos

- [Expressions vs Statements](./JS-conceptos/Statements-Expressions/)

## Clases de repaso

Estudiantes más avanzados de la carrera resuelven los ejercicios en vivo en formato webinar. [Acá podés ver](https://docs.google.com/spreadsheets/d/e/2PACX-1vQwV-pEgWuxqI1B3pdVI0lbeqPB0a6LHPk6-DQlifDdX9Rue_Ul4YTOxoOg-hhofv6U0f32OoXOU2Wf/pubhtml) el calendario y las grabaciones.

## Homeworks y tests

Para ejecutar los tests, parate en la raíz del repositorio (donde está este `README.md`) e instalá las dependencias una sola vez:

```bash
npm install
```

Después, cada vez que quieras ver cuántos tests pasaste:

```bash
npm test {nombre-del-homework}.test.js
```

Ejemplos:

```bash
npm test JSII.test.js   # homework 02
npm test JSI.test.js    # homework 01
```

No todos los homeworks tienen tests; está detallado en la descripción de cada uno.

## La carrera

Si querés saber más sobre el programa, mirá este video:

<iframe src="https://player.vimeo.com/video/426051769" width="640" height="360" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
