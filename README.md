# go-bootstrap
Go bootstrap with board, pieces, plays and captures.

## TL;DR

Copy `index.html` and `css/style.css` to your own project and have fun!

## CodePen original project

In order to play around and try some features got to Code Pen original source: 

[Click here](https://codepen.io/ricalamino/pen/zawmdL) to see the original project on Code Pen.

## Examples

### Boards

Drawing a board without coordinates:

```HTML
<div class="board-default board-19">
</div>
```

Drawing a board _with_ coordinates:

```HTML
<div class="board-default board-19 board-coordinates">
  <div class="col-coordinates-top"> <!-- FOR COORDINATES ON TOP -->
    <span>A</span>
    <span>B</span>
    <span>C</span>
    <span>D</span>
    <span>E</span>
    <span>F</span>
    <span>G</span>
    <span>H</span>
    <span>J</span>
    <span>K</span>
    <span>L</span>
    <span>M</span>
    <span>N</span>
    <span>O</span>
    <span>P</span>
    <span>Q</span>
    <span>R</span>
    <span>S</span>
    <span>T</span>
  </div>
  <div class="col-coordinates-bottom"> <!-- FOR COORDINATES ON BOTTOM -->
    <span>A</span>
    <span>B</span>
    <span>C</span>
    <span>D</span>
    <span>E</span>
    <span>F</span>
    <span>G</span>
    <span>H</span>
    <span>J</span>
    <span>K</span>
    <span>L</span>
    <span>M</span>
    <span>N</span>
    <span>O</span>
    <span>P</span>
    <span>Q</span>
    <span>R</span>
    <span>S</span>
    <span>T</span>
  </div>
  <div class="row-coordinates-left"> <!-- FOR COORDINATES ON LEFT SIDE -->
    <p>19</p>
    <p>18</p>
    <p>17</p>
    <p>16</p>
    <p>15</p>
    <p>14</p>
    <p>13</p>
    <p>12</p>
    <p>11</p>
    <p>10</p>
    <p>9</p>
    <p>8</p>
    <p>7</p>
    <p>6</p>
    <p>5</p>
    <p>4</p>
    <p>3</p>
    <p>2</p>
    <p>1</p>
  </div>
  <div class="row-coordinates-right"> <!-- FOR COORDINATES ON RIGHT SIDE -->
    <p>19</p>
    <p>18</p>
    <p>17</p>
    <p>16</p>
    <p>15</p>
    <p>14</p>
    <p>13</p>
    <p>12</p>
    <p>11</p>
    <p>10</p>
    <p>9</p>
    <p>8</p>
    <p>7</p>
    <p>6</p>
    <p>5</p>
    <p>4</p>
    <p>3</p>
    <p>2</p>
    <p>1</p>
  </div>
</div>
```

### Pieces and letters

Drawing pieces and letters on a board:

```HTML
<div class="board-default board-19">
  <div class="piece piece-black row-6 col-a"><p>180</p></div> <!-- Numbered piece -->
  <div class="piece piece-white row-5 col-c"><p>&Delta;</p></div> <!-- Symbol piece -->
  <div class="piece piece-white row-5 col-e"></div> <!-- Not numbered piece -->

  <div class="piece letter row-6 col-h"><p>a</p></div>
  <div class="piece letter row-6 col-j"><p>&Delta;</p></div>
  <div class="piece letter row-7 col-j"><p>h</p></div>
  
  <div class="piece letter row-1 col-a"><p>5</p></div>
  <div class="piece letter row-2 col-a"><p>6</p></div>
  <div class="piece letter row-2 col-b"><p>7</p></div>
  <div class="piece letter row-1 col-b"><p>8</p></div>
</div>
```
![Example above](https://github.com/ricalamino/go-bootstrap/blob/master/examples/assets/example_1.png "Result of the above code")




