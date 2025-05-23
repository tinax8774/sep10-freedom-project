# Tool Learning Log

## Tool: **Animate.CSS**

---

### 3/7/2025:
* Watched half of [Animate.CSS](https://www.youtube.com/watch?v=VzbBcVRquYA&t=145s) video
    * Helped me understand how to make the animation work
    * Helped me understand the code that was being shown on the website
* After watching the video I changed the animation that was used and the time of delay.
    * `<h1 class="animate__animated animate__flash animate__delay-1s">Hello</h1>` used to make a animation of flash and delay it by 1 second when first entered into the website.
    * Could add more than one animation just need to add another line of code for it.
* Some challenges were typing the code correctly
    * When writing the class there was always a double _ and I kept forgetting it.
    * Remembering that the delay goes along with the animation in the same line of code.
* Next Step:
    * Continuing to figure out what the other code do on the website.
    * Find a way to use it on my freedom project.


### 3/10/2025:
* watch the other half of the [Animate.CSS](https://www.youtube.com/watch?v=VzbBcVRquYA&t=145s) video
    * Helped me write the code with the delay code
* After watching the video I changed the animation and the time of the animation multiple time.
    * `<h1 class="animate__animated animate__backInDown animate__delay-4s">Hello</h1>` was written in order to make the animation go in back then down and the delay of four second.
    * I can make multiple animated element in order to make them move at different ways
* Some challenges were typing the code
    * Trying to remember spelling the name of the animation correctly
    * Remembering the closing tags of each heading
* Next Step:
    * Continuing learning the tool
    * Learning the other things on the website.

### 3/22/2025
* Uses the information on the website to learn how to use animation
    * I tried out the following CSS codes and HTML codes:
``` CSS
.animate__animated {
  --animate-duration: 5s;
}
```

``` HTML
<h1 class="animate__animated animate__backInDown animate__faster animate__infinite infinite animate__delay-4s">Hello</h1>
```
* I learned how to controlt he animation
    * I learned how to control how long the animation last
    * I found out how to control the speed
    * I learned how to control how many times the animation occurs
* Some challenges were trying to control it
    * While having it at infinite it got really annoying looking at it
    * I didn't realize I could control the duration
* Next Step:
    * Continuing to see what else I could do with it
    * Trying out more things with it.

### 3/24/2025
* This week I basically finished off the code that was on the website. No video was used.
    * Below was the HTML code that I used:
```HTML
<h1 class="animate__animated animate__flip animate__slower animate__repeat-3 3 animate__delay-1s">Hello</h1>
```

* Along with the HTML code I used the following CSS code:
```CSS
.animate__animated {
  display: inline-block;
  margin: 0, 0.5rem;

  --animate-duration: 4s;
}
```
* It was used to control the animations


* I learned to use different animations
    * With this I learned how to make the words that are being animated to be a inline-block.
    * I learned how to put margins between the edge of the screen and the words.
* There weren't much challenges this time except
    * Trying to get the animation to work as I had a hard time figuring out the class of the animation as there was so much code piles there.
    * Trying to figure out a perfect speed for the animation to run as sometimes it was too fast and sometimes it was way too slow.

Notes:
* `<h1 class="animate__animated animate__bounce">An animated element</h1>` is used to set a certain element to have the animation of bounce and in this case the element is a  `h1` that says An animated element.
* `<h1 class="animate__animated animate__bounce animate__delay-2s">An animated element</h1>` is similar to the previous code but with the `animate__delay` element it causes a delay when you load the page.
* `<h1 class="animate__animated animate__bounce animate__delay-2s animate__faster">An animated element</h1>` is used to make the animation faster than it normally is but still maintaining the delay in the animation.
* `<h1 class="animate__animated animate__bounce animate__delay-2s animate__repeat-2">An animated element</h1>` is used to make the animation repeat twice, delay for 2 seconds and the animation is still bounce.

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
