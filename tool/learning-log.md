# Tool Learning Log

## Tool: **A-frame**

---

### 3/21/26:
### Links I Used Today (Websites, Videos, etc):
* [youtube](https://www.youtube.com/playlist?list=PLWkWuhMLkR7D_VSEMkj45NIgF8i2dlUce)
* [Aframe school](https://aframe.io/aframe-school/#/)
* [Aframe document](https://aframe.io/docs/1.7.0/introduction/)

### Things I Tried, Progress I Made, etc:

* I started tinkering with basic A-Frame code to create simple 3D objects like boxes, spheres, and cylinders.
* I experimented with changing colors, positions, and rotations to see how objects move and look different.
* I learned how to create more complex shapes by combining multiple objects, like turning a sphere into a heart shape with smaller spheres and cones.
* I changed the sky color to light blue
* I used the CS50 Dev IDE http-server to refresh and view my changes instantly.

### Challenges:

* At first, I struggled to understand how to position objects in 3D space, especially with the x, y, z coordinates. And what size wouldlook good like when i was doing the heart i did two circles and a cone to give it an affect that its a heart since i do not know how to make a heart. It looked weird because the circles were small but then i chnaged the sie to make it bigger and it looked sort of a heart.

### Questions I Still Have:

* How can I make objects look more realistic with textures and lighting?
* How does the x, y, z, work? because it still confuses me


### What I'm Going to Try Next:

* I plan to experiment more with adding textures and materials to objects for better visual effects.
* I will explore more complex shapes and see how I can combine them to make my device ideas like the MEMORY SCANNER or AR GLASSES in 3D.

### 3/29/26:
* Today i have tried to make a stick man since all i have been doing were shapes.
* I was still confused with the positioning so i had to google it and see how to position the lines and the head in order to make it look good
* This was the code that i used to make the stick man

```css
  <a-entity position="0 0 0">

    <a-sphere position="0 2.5 0" radius="0.2" color="#000000"></a-sphere>

    <a-cylinder position="0 1.5 0" height="1" radius="0.05" color="#000000"></a-cylinder>

    <a-cylinder position="-0.3 2 0" height="0.5" radius="0.05" rotation="0 0 45" color="#000000"></a-cylinder>
    <
    <a-cylinder position="0.3 2 0" height="0.5" radius="0.05" rotation="0 0 -45" color="#000000"></a-cylinder>

    <a-cylinder position="-0.2 0.75 0" height="0.75" radius="0.05" rotation="45 0 0" color="#000000"></a-cylinder>

    <a-cylinder position="0.2 0.75 0" height="0.75" radius="0.05" rotation="-45 0 0" color="#000000"></a-cylinder>
  </a-entity>
</a-scene>
```

* When i check it with the http-server i couldnt find it so i thought i did something wrong. I was looking around the screen so i clicked on the down arrow and there it was.


<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
