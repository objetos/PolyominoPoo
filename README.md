# PolyominoPoo

> The observation that there are twelve distinctive patterns (the pentominoes) that can be
> formed by five connected stones on a [Go board](https://en.wikipedia.org/wiki/Go_(game)) … is
> attributed to an ancient master of that game
> -- <cite>[Golomb][1]</cite>

[1]: https://en.wikipedia.org/wiki/Solomon_W._Golomb

## Objetivo

Emplear el paradigma de [programación orientada a objetos](https://github.com/objetos/objects) para implementar uno o varios juegos basados en [polyominoes](https://en.wikipedia.org/wiki/Polyomino), como [Pentomino puzzles](https://en.wikipedia.org/wiki/Pentomino#Constructing_rectangular_dimensions) o el [tetris](https://en.wikipedia.org/wiki/Tetris), entre otros.

## Sugerencias

* Emplear [p5.polyomino.js](https://github.com/objetos/p5.polyomino.js) como plantilla (i.e., los métodos públicos de la clase [Polyomino](https://github.com/objetos/p5.polyomino.js/blob/master/libraries/p5.polyomino.js)), adaptándola al lenguaje que se vaya a emplear, según el sea caso.
* Emplear [polimorfismos](objetos.github.io/polymorphism/) para el despligue gráfico de un polyomino y el tablero (memoria) del juego.
* Si van a generar todas las instancias de polyominos para _n_ celdas, estudiar:
    * [Algorithms for enumeration of fixed polyominoes](https://en.wikipedia.org/wiki/Polyomino#Algorithms_for_enumeration_of_fixed_polyominoes).
    * [Counting polyominos: yet another attack](https://www.sciencedirect.com/science/article/pii/0012365X81902375?via%3Dihub).
    * [Free polyominoes enumeration @rosettacode](https://rosettacode.org/wiki/Free_polyominoes_enumeration).

## Otras referencias

* [Polyomino @wolfram](https://mathworld.wolfram.com/Polyomino.html)
* [Polyomino integer sequence @oeis](https://oeis.org/A000105)