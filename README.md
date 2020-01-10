*Animated background squares implemented with canvas*

####Features
- [x] Simple random squares
- [ ] Interactive squares – Mouse & Touch (WIP)
- [ ] Patterns

<!--####Options
* Background size
* Block size
* Color function
* Grid customizations

-->

####Usage
Add the canvas element to your html page

    <canvas id='grid'></canvas>

Include `lodash.js` and `anim-squares.js` before the `</body>` tag.

Add the following snippet to you javascript code,

    var sqrs = new Squares(document.getElementById('grid'));
    sqrs.tick();
