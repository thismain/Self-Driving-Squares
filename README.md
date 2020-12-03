# Self-Driving-Squares

November 15, 2020  
  
Demo: http://drive.x10host.com/city/selfDrivingSquares.htm  
[![screenshot](https://github.com/thismain/Self-Driving-Squares/blob/main/screenshotter.png?raw=true)](http://drive.x10host.com/city/selfDrivingSquares.htm)  
  
Tiny squares, which I refer to as cars, find their way along the streets in an image. Pan and zoom the world using your left mouse button and wheel. The cars find their way by sampling colors in the image. There are a few different street maps to try. In the game version, two squares, one red, one blue, shoot at each other, while also dodging squares. You can take control of the red square with your arrow keys.  
  
Here are the shortcut keys: 
<ul>
<li>left mouse button to pan</li>
<li>mouse wheel to zoom</li>
<li><strong>m</strong> key or double click to reset default view</li>
<li>middle mouse click to toggle fullscreen</li>
<li>arrow keys to control red flashing square</li>
<li><strong>shift</strong> key to fire</li>
<li><strong>spacebar</strong> key to stop moving</li>
<li><strong>y</strong> key to let red square control itself</li>
<li><strong>u</strong> key to toggle war game</li>
          game points: 5 wins; hit=1; get hit=-1; collide=-1</li> 
<li><strong>j</strong> key to show score</li>
<li><strong>t</strong> key to show touchscreen steering and fire controls</li>
<li><strong>n</strong> key to start new game</li>
<li><strong>v</strong> key to add 5 cars </li>
<li><strong>c</strong> key to remove 5 cars</li>
<li><strong>i</strong> key to load a new street map</li>
<li><strong>p</strong> key to pause/resume</li>
<li><strong>k</strong> key to set random car positions</li>
<li><strong>f</strong> key to show fps, click for ms, memory usage</li>
<li><strong>q</strong> key to hide the help icon</li>
<li><strong>h</strong> key to toggle this help screen</li>
</ul>
  
I am using mrdoob's stats.js: for fps:  
https://github.com/mrdoob/stats.js/  
  
I am also using images from:  
https://www.dreamstime.com/stock-images-city-seamless-vector-wallpaper-image5056574  
https://thumbs.dreamstime.com/b/city-seamless-vector-wallpaper-5056574.jpg  
and  
https://depositphotos.com/68246427/stock-illustration-minimal-city-map-for-gps.html  
https://st2.depositphotos.com/4559651/6824/v/950/depositphotos_68246427-stock-illustration-minimal-city-map-for-gps.jpg  
and  
https://depositphotos.com/9519225/stock-illustration-seamless-background-of-abstract-city.html  
https://static8.depositphotos.com/1303735/951/v/950/depositphotos_9519225-stock-illustration-seamless-background-of-abstract-city.jpg  
and  
https://www.google.com/maps/  
  
The images required some manual processing, to change the width/height ratio, and to make sure the white streets are pure white, and in come cases to mirror horizontally and vertically, for doing which I used Gimp.  
  
I am using (in the physics, non-game version) the Matter.js 2d physics library for animation and rendering of the squares:  
https://brm.io/matter-js/  
https://github.com/liabru/matter-js  
Live demo (physics version): http://drive.x10host.com/city/paths.htm  
  
