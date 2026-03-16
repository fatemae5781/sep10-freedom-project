# Entry 4
##### 3/14/26

---
# Content
I tinkered with a lot of tools such as Sass, Skeleton, and AnimationCSS, and I watched many videos about them. However, I chose A-Frame because it caught my attention the most. When we started selecting tools for our freedom project, many options seemed good, but A-Frame stood out to me. I believe this tool will help me bring my ideas for new devices to life, like the MEMORY SCANNER DEVICE, AR GLASSES FOR AUTOPSY, BODY TEMPERATURE AND TIME DEVICE, FROZEN INSIDE BODY SCANNER, and ROBOTIC AUTOPSY ASSISTANT. These are the ideas I came up with, and with A-Frame, I will be able to code and make them look exactly how I imagine.  

I chose A-Frame because I found out that I can create 3D objects and design devices in a virtual space, which I thought was really cool. It would allow people to see my ideas clearly. To learn more about the code i used [A-frame school](https://aframe.io/aframe-school/#/) to show me the codes and how to use them and it was very helpful. To learn more, I went to the CS50 Dev IDE and experimented with the code. I added the code that was presented to me first from [A-frame document](https://aframe.io/docs/1.7.0/introduction/) to the ide. I tried changing the color, position, and rotation of objects to see how they affected the scene. For example, I changed the color of an object to purple, blue, and pink, and I adjusted the position and rotation to make shapes like a heart and a diamond and to see the changes that i made i typed http-server in the ide. Everytime i made a change to the code i just refreshed the page and it showed me the changes so that was very helpful  
 
## Here is an example of how I tinkered with the code:  

**Before:**
  ```html        
  <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
```

**After:**  
 ```html
  <a-box position="1 1.5 -4" rotation="0 45 0" color="#800080"></a-box>
 ```
## Example two:

**Before:**  
```html
<a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
```  

**After (circle turned into a heart, pink color):**  
```html
<a-entity position="0 1.25 -3">
  <!-- Top left of heart -->
  <a-sphere position="-0.3 0.2 0" radius="0.2" color="#FFC0CB"></a-sphere>
  <!-- Top right of heart -->
  <a-sphere position="0.3 0.2 0" radius="0.2" color="#FFC0CB"></a-sphere>
  <!-- Bottom point of heart -->
  <a-cone position="0 -0.5 0" radius-bottom="0.3" height="0.5" rotation="0 0 180" color="#FFC0CB"></a-cone>
</a-entity>
```
## Example three:

**Before:**  
```html
<a-cylinder position="2 1 -5" radius="0.5" height="1.5" color="#00BFFF"></a-cylinder>
```  

**After (cylinder turned into a diamond, blue color, different position):**  
```html
<a-entity position="3 1.5 -6" geometry="primitive: tetrahedron" material="color: #0000FF"></a-entity>
```  

I moved the diamond to a different position and changed the shape from a cylinder to a tetrahedron (diamond shape), with a blue color.  

## Example four:

**Sky Turned Blue:**  
```html
<a-sky color="#0000FF"></a-sky>
```  
I changed the sky color to blue, giving the scene a more calming and immersive look.  

Watching videos in [Youtube](https://www.youtube.com/playlist?list=PLWkWuhMLkR7D_VSEMkj45NIgF8i2dlUce) about A-Frame helped me understand how it works, and seeing examples gave me ideas for creating my own 3D images.

# Skills:

The skills I gained include learning on my own because we had to try out many tools to pick the one we wanted to use. I had to learn what each tool does, watch videos, and code with them to understand how they work. By doing this, I gained a little knowledge about each tool. I chose A-Frame because it caught my attention and seemed easy to use for making 3D objects.  

Another skill I developed is problem-solving. While tinkering with the code, I faced challenges like changing shapes or colors and making objects look right. For example, when I was changing the color of the sky to blue, I initially made it the same blue as a shape in my scene. It blended in too much and looked bad. So, I had to change the sky color to light blue, which made everything look much better. This experience taught me how to fix problems and find solutions, which is useful outside of my project as well.

I also learned creativity because I had to think about what colors to use, what colors would look good, and what position and shape would be better. For example, when I was trying to make a heart shape, I didn’t know how to do it at first. So, I had to be creative and come up with my own way. I made two circles on top to represent the curves of the heart and added a cone at the bottom to look like the point. This helped me create a simple but recognizable heart shape in A-Frame.  

---


[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
