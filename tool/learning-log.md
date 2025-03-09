# Tool Learning Log

## Tool: **Animate CSS**

---

### 3/3/25:
## [Free code camp](https://www.freecodecamp.org/learn/responsive-web-design/#applied-visual-design)
* `Hover` allows animations when you move your mouse over an object
 ```CSS
button:hover {
 animation-name: background-color;
 animation-duration: 500ms;
 background-color: yellow;
  }
```
* Here I changed the `background-color: yellow;` to different colors
* I found on [CSS colors](https://www.w3schools.com/cssref/css_colors.php). I chose to use the color teal ```background-color: #00FFFF;```
* When I hover over the circle the color turns teal instead of yellow now

---
# Opacity
*  `opacity` this animation allows the shape or object to fade
```CSS
 @keyframes fade {
    50% {
      left: 60%;
        opacity: 0.1;
    }
  }
 ```
 * I changed the opacity number to a higher number one
 * I found out that any number higher than 0.6 the fade cant really be seen
 * Numbers 0.5 and below has a fade where the shape vanishes
 * I tested out negative numbers also like -1
 * Negative number have a stronger fade than 0.1

---
### 3/7/25
## [Youtube video](https://www.youtube.com/watch?v=z2LQYsZhsFw)
# Box shadow
* adds a shadow effect behind your shape and you can choose the color you want or you can also make it transparent

```CSS
.fullCard {
    width: 245px;
    border: 1px solid #ccc;
    border-radius: 5px;
    margin: 10px 5px;
    padding: 4px;
    box-shadow: 10px 5px 5px ;
}
```
* I wondered if I could add a color to the box shadow
* I added the color red to the end of the `box-shadow` and the shadow turned red
* I then wondered if I could create two differnt shadow colors
```CSS
box-shadow: 3px 3px red, -1em 0 .4em
```
* I typed this online and a yellowish color was on the left and red was on the right 

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
