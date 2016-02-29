# chess
A simple Chess UI written in Elm.

I wanted to learn Elm and I've been meaning to write a chess UI/program
for a while some this is my attempt to kill two birds with the one stone.

To simplify the UI, I leverage the [Unicode chess pieces] (https://en.wikipedia.org/wiki/Chess_symbols_in_Unicode).

The first goal is to build a UI that allows you to play through any legal game.

## Done

- piece moves (and captures)
- pawns moves (and captures)
- double pawn moves
- en passant
- castling
- check detection

##To-do

- handle getting out of check
- enforce kings can't meet
- checks that result from castling
- can't castle through check
