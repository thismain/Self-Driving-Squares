# Self-Driving-Squares

November 15, 2020
Live demo: http://drive.x10host.com/city/paths.htm  
[![screenshot](https://github.com/thismain/Self-Driving-Squares/blob/main/screenshot2.png?raw=true)](http://drive.x10host.com/city/paths.htm)  
  
Tiny squares, which I refer to as cars, find their way along the streets in an image. You can pan and zoom the world using your left mouse button and wheel. The cars find their way by sampling the colors in the image. You can also control one of the squares with your arrow keys. There are a few different images to try out. Here are the shortcut keys: 
<ul>
<li>left mouse button to pan<BR>'+
<li>mouse wheel to zoom in and out, centered on the cursor</li>
<li>middle mouse click to toggle fullscreen</li>
<li>double click to reset to default view (after panning and zooming)</li>
<li>arrow keys to steer controllable square (fast black one)</li>
<li>**v** key to add 50 cars</li>
<li>**c** key to remove 50 cars</li>
<li>**i** key to load a new street map</li>
<li>**p** key to pause/resume</li>
<li>**f** key to show fps</li>
<li>**n** key to increase sim rate</li>
<li>**b** key to decrease sim rate</li>
<li>**q** key to hide the question mark</li>
</ul>
  
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
  
