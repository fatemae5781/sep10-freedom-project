# Entry 6
##### 5/9/26

## **Content**

To start making my MVP I first created a wireframe. This was very helpful because it showed me how I wanted my website to look before I started coding. I didn't want to just jump into coding without a plan so the wireframe helped me see the layout clearly. My idea was to have a home page with a stick man waving and a welcome message. I already had some code for a waving stick man from when i was tinkering with my tool A-FRAME so I decided to use that. This saved me time because I didn't have to code the stickman from scratch. I just embedded the AFRAME scene in my webpage using an iframe like this:

```html
<div id="aframe">
  <iframe src="Aframe.html"></iframe>
</div>
```

One challenge I faced was making the AFRAME show properly on my webpage. At first I forgot to include the AFRAME library link which caused it not to display. But thanks to my friend kaitlyn she helped me realize I needed to add the link `<script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>`. After that it acually worked.
For my future technology I wanted to create a USB that looks like a memory scanner device. Making the USB was pretty hard because I didn't know how to do it in AFRAME. I struggled for about two hours using boxes and trying to add a glowing light to it. I had to search online and try different things like adding `material="emissive:#00ffcc; emissiveIntensity:0.8"` to make the light glow. I also worked on making my website look cute with CSS. I changed the color scheme to different shades of blue because blue is often associated with doctors and health. I thought it made sense for my project. I used Google Fonts (like Pacifico) to make the text look friendly and fun. I also designed boxes with a light blue background to make the content stand out and look neat. 

Here are some code snippets I used:

For the font from Google Fonts:
```html
<link href="https://fonts.googleapis.com/css2?family=Poppins&family=Pacifico&display=swap" rel="stylesheet" />
```

For the CSS color scheme:
```css
body {
  background: linear-gradient(135deg, #74c7f9, #2980b9);
  font-family: 'Pacifico', cursive;
  color: #fff;
}
```

And for the navigation bar, I used Bootstrap's navbar component:
```html
<nav class="navbar fixed-top">
  <a class="navbar-brand" href="#welcome">Medical Autopsy</a>
  <!-- links here -->
</nav>
```

**Challenges & Takeaways**

* One challenge was figuring out how to add AFRAME scenes properly. I learned that including the AFRAME script and using iframes makes it easier. Also creating the USB model was difficult because I didn't know how to make glowing lights or shapes in A-FRAME. After searching and experimenting I learned how to add materials and effects to make my models look better. 

* Another challenge was choosing the right color scheme. I wanted my website to look professional but also appealing. I changed from pink and purple to different shades of blue which made the website look more suitable for a medical theme.

* The main takeaway is that patience and research are very important. When I didn't know how to do something, I searched for tutorials or asked friends for help. Practicing different ideas and trying multiple times helped me improve my skills and make my website look better.

## **Skills** 

* For learning on my own, I spent a lot of time exploring past freedom project websites. By looking at how they were designed, I was able to get ideas and inspiration for my own project. This helped me understand different ways to structure my website and what styles look good. I also searched for coding examples online and watched videos to learn how to add features like 3D models and effects in AFRAME. These resources helped me figure out how to make my website look the way I wanted without needing a lot of help from teachers. 

* For communication, I learned how important it is to ask for help when I need it. When I was stuck on certain parts of my project I reached out to my friends and classmates. They gave me feedback, helped me fix the errors, and shared ideas. For example my friend told me that I needed to include the AFRAME library link, which was a big help. Talking to others helped me improve my project and made me feel more confident about my work.

## **Sources**

I used several sources to learn and improve my project. For example I looked at the [Bootstrap documentation](https://getbootstrap.com/docs/4.3/components/navbar/) to understand how to make a navigation bar. I also used [Google Fonts](https://fonts.google.com/specimen/Pacifico?query=Pacifico) to choose a friendly font for my website. To get inspired for color schemes, I visited [Coolors](https://coolors.co/palettes/popular/blue), which gave me different blue palettes to use.

## **Engineering Design Process**

Right now, I am in the stage of improving my MVP by adding more features like the USB model and better styling, add more detail for partB for the future technologies, change the font of the label partA and B and the color to make it stand out more, change the position of the stick man so it appears as soon as the page loads, link the medical autopsy to something in the navbar,add a carousel to partA so it wont look boring, If i have time make an aframe for the second future technology. After finishing these I plan to practice my presentation. I will prepare what I want to say so I can confidently explain my project to my classmates and teachers. 

---


[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
