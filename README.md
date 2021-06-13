# game-of-life-loader
  <object data="https://robertpage.github.io/game-of-life-loader/cgl.min.svg" type="image/svg+xml">
    <div>Couldn't get loading icon</div>
  </object>
A 7kb SVG loading icon that plays Conway's Game of Life on a 10x10 grid

## Description
I realized I hadn't ever made Conway's Game of Life so I built in in an SVG that can be used as a loading icon. The code was built with performance in mind for the most part. It was also a very rush job so there is a lot more that could be done to clean it up and make it more efficient.

## Usage
You can either put the code inline, or reference from an external file using the <object> tag:
  <pre><code>
    <object data="/cgl.min.svg" type="image/svg+xml">
      <div>Couldn't get loading icon</div>
    </object>
  </code></pre>

## TODO
- Replace setTimeout with request animation frame. 
- Scope JS
