# Entry 5
# 4/1/25

# Content
From the last blog entry I just finished choosing my freedom project tool which was animation. Now with my chosen tool I have been tinkering on many different websites and also watching various videos that will help me with my tool animation. Creating a sort of day by day plan so that I know what to do everyday in class and also outside of class. Some websites that I used to help aid me was [Free Code Camp](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/use-the-css-transform-property-skewx-to-skew-an-element-along-the-x-axis) and [W3Schools](https://www.w3schools.com/) also going on youtube for videos. I took some notes and processed things that I learned into my ide, in the learning log and also in my notes. I used various websites to tinker with the new code and information that I got. Using pick code, this is what I tinkered with in [Pickcode](https://app.pickcode.io/project/cm8rnww353pjx13zd9bvggzu7) and also jsbin. These were just some of the ways that I tinkered with my tool to get a better understanding of animation so that I can use it in the freedom project later on. 

---
# Pickcode 

---

After learning more about keyframes and translation I put my understanding of the two together, the code below is what I created  

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

@keyframes fly {
    0% {
        transform: translateX(0px);
        background-color: black;
    }

    100% {
        transform: translateX(300px);
        background: lightskyblue;
        width: 20px;
        height: 20px;
    }
}
```
I combined my understanding of keyframes and other things that I learned here like the trasnform property and translate. These keyframes created a change in the animation at different points into the animation as seen in the percentage tiles at 100% it turns blue and the width and height changes at that specific time, the `translateX` moves the shape along a x plane like in math. 

--- 

## Notes of Keyframes and Translation: 
* `Transtiion-Property:;` defines which proeprty the transition effect should apply to
* `transition-duration:;` How long the transition effect takes
* `transition-timing-function:;` Specifies the speed curve of the transition effect
* `transition-delay:;` 	Specifies a delay (in seconds) for the transition effect

  ---
  
* Must state the `animation-name` for the keyframes to work
* Keyframes name must match the `animation name
* Allows detail specifications of an animations behavior at various points

---

## Another topic I learned about in animation was the `before::` and `after::` properties. Some notes that I took down from the [::Before and ::After Youtube Video](https://www.youtube.com/watch?v=dIUOWdwwZBw) was...

--- 

# `After::` `Before::`

* Allows detail specifications of an animations behavior at various points
* `after::` places an empty element before content
* using `before::` places an empty element before text content
* Its a **pseudo element** so you have to define everything on your own
* Need to set **content** first or else it won't work.

  ---

 ### After I finished taking notes I went to [my pickcode](https://app.pickcode.io/project/cm8ndgdil1jmp12gzhk3pgw0j) and started tinkering over there to make sure that I get a understanding of these two different properties. At first I only tried using the the before element so that I can see what it does and it looked like this

```CSS
h1::before {
    content: 'BYE';
    background-color: aqua;
    margin: 20px; 
    bottom: 20%; 
}
```
This code here put the text that was inside my content before my heading which was My Website Project. With the code here, my content inside was BYE, so before the My Website Project it put the word BYE. Then after I tried to combine my learning of both the before and after propertys and I added the after property, it looked like this. 

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
I editied the postion here and highlighted a diffrent color so that I could differentiate the difference between the two. As the name suggests the after property just puts animations, code, or text after whatever text or code you have in the beginning. This time the BYE My Website porject was still here but the new text that I added was hello which went after the orignial text and since I changed dimensions it landed on the bottom. 

---

# Skills 

---

# Time Management
I am able to manage my time on the tight schedule that im on. Right now I do some sports outside of school along with some new clubs that I joined recently. I also do some voulenterring outside of school and some SAT prep classes on the weekends. Along with all of this I have created a plan on my phone, a list of tasks so that I dont forget what I need to do when I go home because I go home at a late time around 7-7:30🕥. With the list that I created I am able to prioritize the important tasks that I have so that when I go home I do those important tasks and the ones that the deadline is almost due. I have some free time at the end of all of this and I work on some tasks that are due soon on a different date or I take some time to relax and take a break. 

# Overcoming Challenges/ Embracing Failure
Learning on my own for my freedom project has led to some problems that I had to solve on my own. Some of the code was difficult for me to understand and some people didn't do the lessons that I was doing so it was different. So I took it upon myself to fix my own mistakes and searched online for solutions to my problems no matter how many times I got the code wrongg and it didn't work, I still kepy going.. These were some setbacks that I faced and also in my life when playing sports sometimes I was able to win the games however sometimes my team would drag me down a little and that would upset me but I never gave up there and just continued to keep going and continue practicing so that I can become better. I also overcame some mental things like when I don't want to do homework but I still push myself to do it no matter how boring it is. I still find a way to push myself. Also one test, I got a really low grade on my chemsitry test but after studying more and putting more work in I was able to bring my grade up and also get a better grade on my next test. 






[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
