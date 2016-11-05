# Fancy.css

### Useful. Fun. Often quite weird.

Fancy.css is a growing library of animations focused on giving icons the unique interactivity often seen on other page elements.

Sometimes wacky, often unnecessary, and on rare occasions... useful, Fancy.css is CSS only (no JavaScript!) and very simple to implement.

While Fancy.css will work on any icon, I suggest using the FontAwesome library of icons.

---

###Basic Use
To animate your icon:
1. Reference the *fancy.css* file from your index.html (or other root file).
  * <link href="fancy.css" rel="stylesheet">

2. Assign a class to your icon that contains the word *fancy* and the name of the animation.
  * <i class="fancy orbit"></i>

That's it!

---
###Advanced Use
- Animation Duration
The majority of *Fancy.css* animations run for a duration of 2 seconds (2s).
There are many exceptions, of course, with durations ranging from .5s to 3s.

To override the duration of any animation, include some css code containing the following:
  * .fancy
  * .[animation name]
  * animation-duration override.

Example:
.fancy.cliff {
  -webkit-animation-duration: 1.5s;
  animation-duration: 1.5s;
}

- Infinite Animations
To make the animation repeat indefinitely, simple include the word *infinite* along with the class declarations *fancy* and [*animation-name*].

Example
* <i class="fancy infinite orbit"></i>

---
There are other like it, but this one is mine.

*Created by Marshall Murphy (2016) and licensed under MIT.*
