# Generative-UI

If you want to use this background you have to follow the next steps:


in .html you need to add

<body>

<canvas class="orb-canvas"></canvas> // <--------

//////////////////////





all your code





//////////////////////

<script type="module" src="./script.js"></script> // <-----------

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


Read the README.txt
