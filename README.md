# matrix rain

The famous Matrix rain effect of falling green characters in a terminal with node.

## Installation

```
npm install -g matrix-rain
```

## Usage

```
usage: matrix-rain [-h] [-v] [-d {h,v}]
                [-c {green,red,blue,yellow,magenta,cyan,white}]
                [-k {ascii,binary,braille,emoji,katakana}] [-f FILEPATH]
The famous Matrix rain effect of falling green characters as a cli command
Optional arguments:
  -h, --help            Show this help message and exit.
  -d, --direction {h,v}
                        Change direction of rain. h=horizontal, v=vertical
  -c , --color {green,red,blue,yellow,magenta,cyan,white}
                        Rain color. NOTE: droplet start is always white
  -k, --char-range {ascii,binary,braille,emoji,katakana}
                        Use rain characters from char-range
  -f, --file-path FILEPATH
                        Read characters from a file instead of random
                        characters from char-range
```
## Screenshots

![Vertical Matrix](https://vsgif.com/gif/2169588)

![Horizontal Matrix](https://www.pinterest.com/pin/437834395018314476/)

Node's process.stdout has a columns and rows property. It also fires resize events like the browser. With escape codes I can treat the terminal as a canvas and paint on it. I discovered a new medium to show my art.

In general its very possible to build interactive terminal apps with great UX that are lightweight and blazing fast. I'm on that journey.
