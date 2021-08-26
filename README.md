Javascript 3D RacingRiot
==========================

An Outrun-style pseudo-3d racing game in HTML5 and Javascript, this version made by Hadi. J.

 * [play the game](https://lightorg.neocities.org/)

A note on performance
=====================

The performance of this game is **very** machine/browser dependent. It works quite well in modern
browsers, especially those with GPU canvas acceleration, but a bad graphics driver can kill it stone
dead. So your mileage may vary. There are controls provided to change the rendering resolution
and the draw distance to scale to fit your machine.

Currently supported browsers include:

 * Firefox (v12+) works great, 60fps at high res - Nice!
 * Chrome (v19+) works great, 60fps at high res... provided you don't have a bad GPU driver
 * IE9 - ok, 30fps at medium res... not great, but at least it works

The current state of mobile browser performance is pretty dismal. Dont expect this to be playable on
any mobile device.

>> _NOTE: I havent actually spent anytime optimizing for performance yet. So it might be possible to
   make it play well on older browsers, but that's not really what this project is about._

A note on code structure
========================

This project is implemented in javascript (because its easy for prototyping) but
is not intended to demonstrate javascript techniques or best practices. In fact, in order to
keep it simple to understand it embeds the javascript for each example directly in the HTML
page (horror!) and, even worse, uses global variables and functions (OMG!).

FUTURE
======

It's quite astounding what it takes to actually finish
a game, even a simple one. And this is not a project that I plan on polishing into a finished state. It should
really be considered just how to get started with a pseudo-3d racing game.

If we were to try to turn it into a real game we would have to consider:

 * car sound fx
 * better synchronized music
 * full screen mode
 * HUD fx (flash on fastest lap, confetti, color coded speedometer, etc)
 * more accurate sprite collision
 * better car AI (steering, braking etc)
 * an actual crash when colliding at high speed
 * more bounce when car is off road
 * screen shake when off-road or collision
 * throw up dirt particles when off road
 * more dynamic camera (lower at faster speed, swoop over hills etc)
 * automatic resolution & drawDistance detection
 * projection based curves ? x,y rotation
 * sub-pixel aliasing artifacts on curves
 * smarter fog to cover sprites (blue against sky, cover sprites)
 * multiple stages, different maps
 * a lap map, with current position indicator
 * road splits and joins
 * day/night cycle
 * weather effects
 * tunnels, bridges, clouds, walls, buildings
 * city, desert, ocean
 * add city of seattle and space needle to background
 * 'bad guys' - add some competetor drivers to race against as well as the 'traffic'
 * different game modes - fastest lap, 1-on-1 racing, collect coins ? shoot bad guys ?
 * a whole lot of gameplay tuning
 * ...
 * ...


