# Entry 4
##### 2/24/25

## Content
The tool that I chose to use after tinkering with the different choices of tools was **animation**. In the beginning I tried to do A-frame and tinkered with it on my ide but I found out that it was challenging and hard to understand. So testing out my other options that I chose out of my three I found one that I was comfortable with and when I tinkered with it. This tool was just perfect for me because it was not too easy and not too hard for me. Webistes that I used to learn and tinker with was [animate.css](https://animate.style/), [pickcode](https://app.pickcode.io/project/cm7qtmnmun5h0emhdxs2rt1y0) and also **free code camp** lessons. 

----
I tinkered with animate the css by changing around the numbers for things like the ```animation-iteration-count``` and the ```animation-duration``` by testing and trying out different numbers. The beginning code looked like 

```CSS
 .ball {
    width: 100px;
    height: 100px;
    margin: 50px auto;
    position: relative;
    border-radius: 100%;
    background: linear-gradient(
      35deg,
      #ccffff,
      #ffcccc
    );
    animation-name: bounce;
    animation-duration: 2s;
    animation-iteration-count: 3s;
  }

  @keyframes bounce{
    0% {
      top: 0px;
    }
    50% {
      top: 249px;
      width: 130px;
      height: 70px;
    }
    100% {
      top: 0px;
    }
  }
```
---

This part was the orignial code and after changing some code around on pickcode to check how the code would change when I alter things and adding some new code that I learned from free code camp lessons this is what it looked like 

```CSS
.ball {
    width: 100px;
    height: 100px;
    margin: 50px auto;
    position: relative;
    border-radius: 5%;
    background: linear-gradient(
      35deg,
      #ccffff,
      #ffcccc
    );
    animation-name: bounce;
    animation-duration: 0.5s;
    animation-iteration-count: infinite;
  }
```

---

I changed the border radius animtaion duration and iteration. After altering the radius the shape turned from a circle to a sort of square and when it bounces it goes to a rectangle, the iteration count I changed the three second to infinite which is what I learned on free code camp lessons. This made it so that the animation would play a infinite amount of times. The last thing i changed around was the animtaion duration, in the beginning I thought it was too slow so I chnaged it to a faster speed using 0.5s instead of three seconds. 

--- 

Another part that I changed from the orignal code was the keyframes. At first I did not know what they really were but by changing the numbers around I was able to figure out what the keyframes do. This is what the code for the keyframes look like after I changed the numbers inside the keyframe. 





