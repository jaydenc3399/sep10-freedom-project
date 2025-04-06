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

---
### Some things that I am going to try next is maybe rotation and some harder animations that have more action to it and also find out the rest of the basics of animation like animation direction and fill-mode and more.

# 3/13/25
## [CSS Borders](https://www.youtube.com/watch?v=ezP4kbOvs_E)
* CSS Borders add a box or border around your element depending on color preference
```
.card {
  content: '';
  position:absolute;
  height:100%;
  width:100%;
  background:linear-gradient;
  top:50%;
  left:50%;
  translate: -50% -50%;
  z-index: -1;
  padding:3px;
  border-radius: 10px;
}
```
* In this code I changed the `background:linear-gradient;` to something new I found on [Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/conic-gradient)

* Instead of `linear-gradient` I put something new which was `Conic-gradient`
* `Conic-gradient`  creates an image consisting of a gradient with color transitions rotated around a center point
* I added different types of colors in the `conic-gradient` creating a colorful border

---

## Some things that I am going to try next is maybe some new types of animations like from a video I skimmed before, the title had different commands I was interested in like.
`h1::after;` `h2::before;`

# 3/22/25
# [Display Property](https://www.youtube.com/watch?v=Qf-wVa9y9V4)
* The `display` property specifies the display behavior

```CSS
.box {
    height:200px;
    width: 200px;
    background-color: lightblue;
    font-size: 30px;
}

body {
    border:8px solid;
}
```
* Added the `display` property adding it to the body using `display: flex;`
*	Displayed the boxes in a block-level flex container in a line

---
# [CSS display Property](https://www.w3schools.com/cssref/pr_class_display.php)

* This website contained property values that can be placed on `display`

```CSS
body {
    border:8px solid;
    display:flex;
}
```
* Changed `display:flex;` to `display:inline;`
* Nothing happened, reverted back to normal
* `display:inline;` is default
* Height and width properties will have no effect

---

## Some things that I am going to try next is maybe more basic things so taht I can get a grasp of what CSS is and the basics of it before I jump into all the cool aniamtion things like changing border colors and more.


# 3/24/25
## [Before and After::](https://www.youtube.com/watch?v=dIUOWdwwZBw)

## `After::`  `Before::`

* Using `before::` places an empty element before text content
* `after::` places an empty element before content
# Content
* Its a **pseudo element** so you have to define everything on your own
* Need to set **content** first
* Without content it wont work

---

* If used for design purposes use ''; , leave it empty
* No content makes the element 0 or not visible.
* `position:absolute;` and `position:relative;` on h1 to make it visibile

# Testing/tinkering
* Pickcode tried to use before and after elements
* Added different types of code to `::after`
```CSS
h1::after {
    content: 'hello';
    background-color: blue;
    margin:20px;
    border-radius: 100px
    height: 4px;
    position: absolute;
    bottom: 0px;
    top: 50%
}
```
---

### Tested out both before and after and added them together

```CSS
h1::before {
    content: 'bye';
    background-color: aqua;
    margin: 20px;
    bottom: 20%;
}

h1::after {
    content: 'hello';
    background-color: blue;
    margin:20px;
    border-radius: 100px
    height: 4px;
    position: absolute;
    bottom: 0px;
    top: 50%
}
```

---

## Some new things that I am going to try is maybe just tinkering around with different types of codes like `animation-play-state` and looking at some lessons of Free Code camp so I can learn more new codes for animation.

# 3/27
## [FCC Keyframe Lesson](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/learn-how-the-css-keyframes-and-animation-properties-work) and [Youtube Video](https://www.youtube.com/watch?v=_OEUbgLTWH0&t=77s)

# Keyframes

* #### Must state the `animation-name` for the keyframes to work
* #### Keyframes name must match the `animation name`
* #### Allows detail specifications of an animations behavior at various points

```CSS
@keyframes bounce {
    0% {
      top: 0px;
    }
    100% {
      top: 249px;
    }
```
* I added took this keyframes from FCC and edited it around
* I added changes to different percentages like 25% and 50%.
* Also made some specifications to the width and the height at 25% and 50%.

---

```CSS
@keyframes bounce {
    0% {
      top: 0px;
    }
    25% {
        width: 10px;
        background: red;
    }
    50% {
        height: 50px;
        background: yellow
    }
    100% {
      top: 249px;
      background: green;
    }
  }
  ```
  * I watched how the shape changed and the color changed at each percent in the animation

---

## I am going to maybe try to practice with keyframes more and using it on different shapes and learning different animations so I can use that to apply it to my keyframes also.

# 4/5
# [Transition Property](https://www.youtube.com/watch?v=xdap5e3-DwM) [CSS Transitions](https://www.w3schools.com/css/css3_transitions.asp)

## *Transform Properties*

* `Transtiion-Property:;` defines which proeprty the transition effect should apply to

* `transition-duration:;` How long the transition effect takes

* `transition-timing-function:;` Specifies the speed curve of the transition effect

* `transition-delay:;` 	Specifies a delay (in seconds) for the transition effect

---

 # `Animation-timing-function`
* ### Ease- specifies a transition effect with a slow start, then fast, then end slowly (this is default)
* ### linear - specifies a transition effect with the same speed from start to end
* ### ease-in - specifies a transition effect with a slow start
* ### ease-out - specifies a transition effect with a slow end

```CSS
    transition-property: width;
    transition-duration: 2s;
    animation-timing-function: ease;
```
* I tried changing the animation-duration to inifnite
* Instead of taking two seconds it jsut went instantly and took up the width
```CSS
transition-property: height;
```
* #### I changed the width property here to height
* #### The height started to change instead of the width now
* #### It went up to down instead of going left to right

---

## Some questions I still have about this is this transition property the same thing as the animation timing function because it shares the same ending jsut the fron is different instead of saying animation it says tranistion so is there a difference really?

<!--
* Links you used today (websites, videos, etc)
* Things hyou tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
