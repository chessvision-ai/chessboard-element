# chessvision-extension-chessboard-element

It is a fork of the wonderful [chessboard-element] component, renaming its main component so that it can be appended to the DOM of websites using the [chessboard-element] or the [chessboard.js] without affecting the already presents chessboards components.

## Usage

It can be used just like the [chessboard-element] except that the main component is renamed from `<chess-board>` to `<chessvision-extension-chess-board>`.

## Where is it useful?

One of such examples is when one tries to append [chessboard-element] to the DOM of http://chess.com/analysis. Doing it affects the chessboard already present on the site and messes its styles to the point that it is not usable. However, appending the renamed element separates it from the already present chessboard and makes both to be rendered as expected.


## License

[MIT License](LICENSE.md)

[chessboard-element]: (https://justinfagnani.github.io/chessboard-element/)
[chessboard.js]: (https://github.com/oakmac/chessboardjs)
