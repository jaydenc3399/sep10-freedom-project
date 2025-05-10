# Entry 6
## 5/9/25

# Content 
From my last blog entry where I started learning my tool animation and gathering eveyrthing that I needed to make my freedom project. I have curretnly made a MVP( Minimum Viable Prodcut) for my project and it started off in the beginning by planning out what my website would look like and I did that by creating wireframes. I created two seperate wireframes one which was a layout of what my website would look like on my phone, [Mobile Wireframe](Mobile-Wireframe.png) and another which was my [Computer Wireframe](Computer-Wireframe.png) which was what the layout of my website would look like on a computer, different viewpoerts. I started working on my MVP and now I have a mostly everything that I need done for my website. I created my code by appplying all that I know about this class and what I learned on my own including things like `containers,` `container fluids`, lessons on my tool animation. An important tool or material that I used was my [Sep Notes](https://docs.google.com/document/d/1n9YZLqsv50YrUhVFN-iwL44YH_rncWpJEAocTKbw2i0/edit?tab=t.0) which helped me a lot to remmeber all the past code that we have done and I forgot about and holding my information forboth par ta nad b of my website. By utilizing all my materials that i learned about animation I was able to apply it to my website thanks to helpful tools and notes that I took on my learning log. For some of the animation code I looked on [Animation.css](https://animate.style) which helped me to apply my took into my website. 


# Challenges 
One challenge that I faced when working on my MVP was with the [getbootstrap website](https://getbootstrap.com). When I was working with my first carousel and putting the pictures into the carousel code, when I tried to click it didnt let me and the pictures werent really showing either. After taking another closer look I found out the reason taht my code for the carousel wasnt working was because I did not import the carousel code from the correct bootstrap version. Instead of using the version 5.3 which was the updated one I was using 5.2. the codes or the two of them were very different in length. For the v2.3 one it looked like this 

```html
<div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="..." class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="..." class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="..." class="d-block w-100" alt="...">
    </div>
  </div>
</div>
```
and for the version 5.3 which is the newer version it looked like this 

```html
<div id="carouselExample" class="carousel slide">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="..." class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="..." class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="..." class="d-block w-100" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
```
The code for the 5.3 looked a lot more different and I made this mistake back then but I did it again, this time I made sure to remind myself whenever I do another project and put it in bold inside my notes. 

Another challenge that i had was trying to get the cards in my website to be in the same line or next to one another. I tried to use `container` becasue I thought that it would put the cards together right next to one another but it didnt. Instead it just stacked the cards one on the top and one on the bottom which was not what I wanted. 

[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
