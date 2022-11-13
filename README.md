# Generative-UI

in .html you need to add

<body>

<canvas class="orb-canvas"></canvas> //FIRST

//////////////////////





all your code





//////////////////////

<script type="module" src="./script.js"></script> //LAST

</body>


------------------------------------------------------------------

in .css file add:

.orb-canvas {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: -1;
}

-------------------------------------------------------------------

in the script.js file you can change range of colors changing this numbers in this.hue:

setColors() {

    this.hue = ~~random(220, 360); 

	or

    this.hue = ~~random(120, 260); 

etc....
