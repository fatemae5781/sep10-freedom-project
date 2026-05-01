# Entry 5
##### 4/26/26

**Context**

Over the past few weeks, I have been working with a tool called A-Frame. It is a web framework that helps you create 3D objects and scenes that you can view in a browser. I learned a lot about how to make simple shapes like boxes, spheres, cylinders, and even more complicated things like a stick man. I also learned how to change their colors, positions, and rotations to make them look more interesting. For example, I experimented with creating a heart shape by combining small spheres and cones, and I changed the sky color to light blue to make my scene look better. I learned how to use the CS50 Dev IDE http-server to view my work instantly after making changes. At first I struggled with understanding how to position objects in 3D space especially using the x, y, and z coordinates. It was confusing, but I kept practicing and researching online especially watching YouTube videos about positioning and rotation in A-Frame. These videos helped me understand that the x-axis is left and right, y-axis is up and down, and z-axis is forward and backward. Now I feel more confident in moving objects around in my scene. I also explored animations in A-Frame which was very exciting. I learned that animations allow objects to move, change color, or do other things like waving or jumping. I used the animation component to make a stick man wave by rotating his arms back and forth. It was easier than I thought, and I even made a small scene where my stick man waves. Here is an example of the code I used to make his arm wave:

```html
<a-cylinder position="-0.3 1.9 -4" height="0.4" radius="0.03" 
rotation="0 0 0" 
animation="property: rotation; to: 0 0 45; dur: 1000; easing: easeInOutSine; loop: true; dir: alternate"></a-cylinder>
```

Another example I used for animation is to make a sphere sway back and forth:

```html
<a-entity geometry="primitive: sphere; radius: 0.3" 
material="color: red" 
position="0 1.5 -3"
animation="property: position.x; to: 2; dur: 2000; easing: easeInOutQuad; loop: true; dir: alternate"></a-entity>
```

One of the challenges I faced was trying to make my stick man sink into the water scene I added later. I wanted him to be underwater but even when i changed his position he stayed above the water. I realized I needed to learn more about how positioning works in A-Frame so I started to study the position values more carefully (Thats when i looked up videos up to learn how xyz work). Throughout the process of learning A-frame I used many resources to help me learn. I watched [YouTube tutorials](https://www.youtube.com/playlist?list=PLWkWuhMLkR7D_VSEMkj45NIgF8i2dlUce), read the [A-Frame documentation](https://aframe.io/docs/1.7.0/introduction/), and looked up codes online when I was stuck. This helped me whenever i wass stuck with my codes such as how the animation worked.


**Skills I Gained**

One important skill I developed is learning by myself. Since I chose to work with A-Frame i had to do a lot of research, try things out, and figure out how to make my scenes look better. I had to learn how to code in A-Frame on my own, fix errors, and improve my work without much help. This skill of self-learning is very useful because it teaches me to be independent and not just ask for help when not needed. Try it learn on my own first but when ii still can not figure it out i then ask for help.

Another skill I gained is searching for information. Whenever my code didn’t work, I searched for videos, tutorials, and similar codes online to find solutions. For example when I didn’t understand how to position objects in 3D space, I looked up tutorials about x, y, and z coordinates. I also learned about animation by searching up how to make objects move in A-Frame. This ability to find the right information quickly and understand it is very helpful not only for this project but also for learning new things in the future.

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
