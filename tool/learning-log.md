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

#### 4/12/26

* Last time when i tinkered with my tool i made a stick man so i wanted to play around with that stickman a little bit more

* i wanted to make it sink into the water so i was looking around the A-frame codes and there was an ocean and a ball in the water so i used that code

* i added the stickman to the code so it could show but for some reason it was above the water. i tried to change the position of the stickman to be under the water but it  still is not working. im pretty sure i am doing something wrong since im not good with positions

* Even though this tinker was a fail i will try to study the positions more better inorder to make the stick man to be under the  water

* That is why tinkering is good it helps you learn from your mistakes.
```css
<a-entity id="floating-objects" position="0 0 -4" animation="property: position; dir: alternate; dur: 3000; easing: easeInOutSine; loop: true; to: 0 -0.05 -4">
      <a-sphere position="0 2.5 0" radius="0.2" color="#000000"></a-sphere>
      <a-cylinder position="0 1.5 0" height="1" radius="0.05" color="#000000"></a-cylinder>
      <a-cylinder position="-0.3 2 0" height="0.5" radius="0.05" rotation="0 0 45" color="#000000"></a-cylinder>
      <a-cylinder position="0.3 2 0" height="0.5" radius="0.05" rotation="0 0 -45" color="#000000"></a-cylinder>
      <a-cylinder position="-0.2 0.75 0" height="0.75" radius="0.05" rotation="45 0 0" color="#000000"></a-cylinder>
      <a-cylinder position="0.2 0.75 0" height="0.75" radius="0.05" rotation="-45 0 0" color="#000000"></a-cylinder>
    </a-entity>
  </a-scene>
```
#### 4/16/26
* I watched YouTube videos that explained how positioning and rotation work in A-Frame. I learned that position and rotation are how we move and turn objects in 3D space. The position tells us where the object is on the screen, using x, y, z numbers. The rotation tells us how much the object is turned around each axis.

* X is left and right which means it is side to side. If I want the object to move to the right,I use a positive number like x=67. To move it left I use a negative number like x=-67.

* Y is up and down. To make the object go higher I use a positive number like y=6. To go lower I use a negative number like y=-6.
Z is forward and backward. Moving forward means a positive z like z=7. Moving backward means a negative z like z=-7.

#### 4/17/26
* I was supposed to learn motion capture today but i discoverd animation instead and i wanted to learn that. so i startedto read about it and it was really interesting and i will for sure use it in my freedom project. So animation in A-Frame lets us make objects move, change color, or do other things (like wave or jump). We do this by adding an animation component to an object. In this component we tell it what property we want to change like position or color and where we want it to go how long it should take, and what kind of movement it should have. For example if we want a red dot to move left and right, we animate its position on the x-axis. We set the starting position the position it should move to how long it should take and how it should move (like easing in and out). If we want it to keep swaying forever we set loop: true and dir: alternate, so it goes to one side and then back again. All these settings are written inside the animation attribute in the form of a string and A-Frame handles moving the object smoothly between the values.

* geometry: Shape setup
* material: Color setting
* position: Starting point
* animation: Movement magic
* property: What to change
* to: End position
* dur: Movement time
* easing: Smooth start/end
* loop: Repeat forever
* dir: Back and forth

### Example

```css
a-entity
      geometry="primitive: sphere; radius: 0.3"
      material="color: red"
      position="0 1.5 -3"
      animation="
        property: position.x;
        to: 2;
        dur: 2000;
        easing: easeInOutQuad;
        loop: true;
        dir: alternate">
    </a-entity>
```

#### 4/18/26
* I wanted to make something using my knowledge from day one and two. SInce i made a stick man before i thought it would be fun if i saw him wave and i wanted to challange myself and acually see if i could do it and if i learned soemthing these past two days. It was easier than expected.

* Here is my code:

```css
 <a-scene>

  <a-sphere position="0 2.5 -4" radius="0.2" color="black"></a-sphere>


    <a-cylinder position="0 1.5 -4" height="1" radius="0.05" color="black"></a-cylinder>

    <a-cylinder position="-0.3 1.9 -4" height="0.4" radius="0.03" color="black"
      rotation="0 0 0"
      animation="property: rotation; to: 0 0 45; dur: 1000; easing: easeInOutSine; loop: true; dir: alternate"></a-cylinder>

    <a-cylinder position="0.3 1.9 -4" height="0.4" radius="0.03" color="black"
      rotation="0 0 -45"
      animation="property: rotation; to: 0 0 45; dur: 1000; easing: easeInOutSine; loop: true; dir: alternate"></a-cylinder>


    <a-cylinder position="-0.2 0.75 -4" height="0.5" radius="0.03" color="black"
      animation="property: rotation; to: 10 0 0; dur: 1000; easing: easeInOutSine; loop: true; dir: alternate"></a-cylinder>

    <a-cylinder position="0.2 0.75 -4" height="0.5" radius="0.03" color="black"
      animation="property: rotation; to: -10 0 0; dur: 1000; easing: easeInOutSine; loop: true; dir: alternate"></a-cylinder>
  </a-scene>
```

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
