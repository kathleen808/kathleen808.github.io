---
layout: project
type: project
image: images/MathMashPic.png
title: Math Mash
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2017-12-31
labels:
  - Java
summary: A simple quiz type game designed to test elementary school students' knowledge of simple arithmetic equations. 
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

Math Mash is a simple math game constructed using GUI's in the Java programming language. I came up with the game design and built a primitive version using MIT App Inventor during my senior year in high school. During my first semester in college, I had the opportunity to rebuild the game in my first Introductory Java course (ICS 111) as an extra credit project. 

Here is some code that illustrates how we read values from the line sensors:

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



