# memoflip
A simple implementation of the <a href="https://en.wikipedia.org/wiki/Concentration_(card_game)">Concentration</a> game done using Vue.js to explore and learn the basics of the framework.
The interface of the application is fairly self-explanatory.

The process is as follows:
<ul>
  <li>Click on any tile, and it flips over to show you the picture on the other side.</li>
  <li>Click on the next, and it will do likewise.</li>
  <li>If the two images are the same, the tiles go away.</li>
  <li>If they are different, they flip back and you continue guessing.</li>
</ul>

The number on the left keeps track of the number of clicks you've made in solving the board. Note that clicking on a tile multiple times will register multiple clicks as will clicking on an area where a tile used to be.

The two icons above the counter reset the board and change the number of tiles to either 16 or 24 tiles. This also resets the counter.

To return to the original 20 tile board, simply refresh the page.
