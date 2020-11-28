# Self-Driving-Squares

November 15, 2020  
Live demo: http://drive.x10host.com/city/paths.htm  
No Physics Version demo: http://drive.x10host.com/city/paths_no_physics.htm  
[![screenshot](https://github.com/thismain/Self-Driving-Squares/blob/main/screenshot8.png?raw=true)](http://drive.x10host.com/city/paths.htm)  
  
Tiny squares, which I refer to as cars, find their way along the streets in an image. Pan and zoom the world using your left mouse button and wheel. The cars find their way by sampling colors in the image. There are a few different street maps to try. Here are the shortcut keys: 
<ul>
<li><strong>h</strong> key for help</li>
<li>left mouse button to pan</li>
<li>mouse wheel to zoom in and out, centered on the cursor</li>
<li>middle mouse click to toggle fullscreen</li>
<li>arrow keys to steer controllable square (the flashing one)</li>
<li><strong>m</strong> key or double click to reset to default view</li>
<li><strong>v</strong> key to add 50 cars</li>
<li><strong>c</strong> key to remove 50 cars</li>
<li><strong>i</strong> key to load a new street map</li>
<li><strong>p</strong> key to pause/resume</li>
<li><strong>k</strong> key to set random car positions</li>
<li><strong>f</strong> key to show fps, click fps to see ms, and memory usage</li>
<li><strong>q</strong> key to hide the question mark</li>
</ul>
  
I am using mrdoob's stats.js: for fps:  
https://github.com/mrdoob/stats.js/  
  
I am using the Matter.js  2d physics library for animation and rendering of the squares:  
https://brm.io/matter-js/  
https://github.com/liabru/matter-js  
  
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
  
The images required some manual processing, to change the width/height ratio, and to remove the non-white pixels from the streets, for doing which I used Gimp.  
  
