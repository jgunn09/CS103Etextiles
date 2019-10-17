---
layout: post
title: You Would Not Believe Your Eyes
tags: [fireflies]
image: /img/flash.png
comments: true
---

![flash](https://jgunn09.github.io/CS103Etextiles/img/flash.png)
![synchronous](https://jgunn09.github.io/CS103Etextiles/img/synchronous.png)
![dipper](https://jgunn09.github.io/CS103Etextiles/img/dipper.JPG)

This code alters the LED of the arduino lilypad having three different LEDs light up differently.  
The first picture is of the flash led which flashes on for half a second before turning off for four seconds.  
The second is of the synchronous which flashes briefly three times before turning off for 10 seconds.  
Finally is the big dipper which fades on for a little over a second before turning off for three seconds.  
A tip I would give is that getting the delay command is kind of tricky so pseudocode is useful in finding where to put it. Also you have to reset analogwrite as just setting brightness to 0 doesn't send it to the arduino.
