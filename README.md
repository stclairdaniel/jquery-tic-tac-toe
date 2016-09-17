# Towers of Hanoi

[Live][link]

[link]: https://stclairdaniel.github.io/jquery-tic-tac-toe/

Tic Tac Toe is written using JavaScript ES5, jQuery, CSS, and HTMl. It has a sleek, minimalist design.

<img src="http://i.imgur.com/ErJvMqv.png" style="width: 150px;height: auto"/>

## How To Play

It's Tic Tac Toe! X goes first. Try to get three in a row before your opponent.

## Technical details

The TTT grid is made entirely using CSS3 Flexbox. Upon click, a simple move validator runs and alerts if the move is invalid, otherwise performs it. A setUpBoard function assigns each of 9 squares a row/col coordinate pair using modulo arithmetic, and a bindEvents function handles clicks by checking if a move is valid, performing it if so, and checking for a win condition.
