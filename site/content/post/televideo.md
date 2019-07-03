+++
Categories = ["Conversion"]
Description = "The keyboard that launched a thousand shipments"
Tags = ["Space Invaders", "Hi-Tek", "NMB", "Televideo"]
date = "2018-11-12T20:01:49-06:00"
title = "Televideo"
[menu.main]
weight = 7

+++
A lot has happened since I last posted here several months ago.

Keyboard-wise, I've gotten very much into learning more about designing and building converters.  This prompted me to order about 40 Televideo 925-style keyboards from [elecplus](https://www.elecshopper.com) with the goal of converting and reselling them.

![](/uploads/2018/11/13/9vsVurD.jpg)

Fixing these up turned out to be a **TON** of work but quite a bit of fun as well.  I wanted to share a bit about the process I've been taking each board through.  Usually I'm doing a few at a time, grouping like boards together.

**Before:**

**![](/uploads/2018/11/13/4qhXXo2.jpg)**

**![](/uploads/2018/11/13/J3X4GY7.jpg)**

**![](/uploads/2018/11/13/wRhxP9k.jpg)**

**Step 1: Map out PCB**  
Using a multimeter set to continuity check mode to check which pins correspond to the rows and columns. I mark the pins with a permanent marker.  

<iframe width="560" height="315" src="//www.youtube.com/embed/yPhYl9d0aT4" frameborder="0"></iframe>

![](/uploads/2018/11/13/zvI3Ksh.jpg)

**Step 2: Remove keycaps**  
Space invaders can be a little bit tricky to remove the caps. I use a sideways prying motion to pop them off.  

<iframe width="560" height="315" src="//www.youtube.com/embed/QH4V0FRlAKE" frameborder="0"></iframe>

**Step 3: Remove unnecessary components**  
Removed all of the unnecessary passive components like resistors which can pull the signal down and give weird key presses.  

<iframe width="560" height="315" src="//www.youtube.com/embed/b8yiJeq__Q8" frameborder="0"></iframe>

**Step 4: Desolder ICs**  
Since we're replacing the controller, these aren't needed any longer  

<iframe width="560" height="315" src="//www.youtube.com/embed/pUmhFwTYnSQ" frameborder="0"></iframe>

**Step 5: Dust the life out of it**  
This thing is awesome. So much better than canned air and it's paid for itself several times over  

<iframe width="560" height="315" src="//www.youtube.com/embed/0Vl1v7aWt" frameborder="0"></iframe>

**Step 6: Clean the keycaps**  

![](/uploads/2018/11/13/flx4938.jpg)

First I soak them with dish soap then run them through an ultrasonic jewelry cleaner a few times.  

<iframe width="560" height="315" src="//www.youtube.com/embed/PFmSPkZSclE" frameborder="0"></iframe>

**Step 7: Clean the case**    
![](/uploads/2018/11/13/it6R51L.jpg)

![](/uploads/2018/11/13/a6mcyvK.jpg)

I use a mr clean magic eraser which gets off all of the marks with minimal elbow grease 

<iframe width="560" height="315" src="//www.youtube.com/embed/_D4XndCVvpo" frameborder="0"></iframe>

**Step 8: Solder pins onto teensy**  
I use a breadboard to keep things in place while I solder the pins.  

<iframe width="560" height="315" src="//www.youtube.com/embed/cINft-kRwOg" frameborder="0"></iframe>

![](/uploads/2018/11/13/mQ5fClV.jpg)**Step 9: Solder teensy to board**  
Thought about socketing it but my pins were a bit too fat to fit.  

<iframe width="560" height="315" src="//www.youtube.com/embed/TZySneDo8PU" frameborder="0"></iframe>

**Step 10: Replace keycaps**  
Luckily I have lots of boards to use as a reference.  

<iframe width="560" height="315" src="//www.youtube.com/embed/QVNZmDjuIWI" frameborder="0"></iframe>

**Step 11: Test matrix**  
Just making sure everything was traced out correctly.

<iframe width="560" height="315" src="//www.youtube.com/embed/LYZ4V-qsiGw" frameborder="0"></iframe>  

**Step 12: Map matrix**  
I have a little arduino sketch I wrote which prints the row and column for each key. Makes this job a lot easier

<iframe width="560" height="315" src="//www.youtube.com/embed/K4vam7BEAFk" frameborder="0"></iframe>  

**Step 13: Program TMK**  
I love TMK! Looks tricky but it's fairly straight forward once you've done it a couple times.  

<iframe width="560" height="315" src="//www.youtube.com/embed/ZdMXK2EPlSY" frameborder="0"></iframe>  

**Step 14: LED**  
Forgot about the LED so I had to do it after the fact.  

<iframe width="560" height="315" src="//www.youtube.com/embed/3PvySfgF4xY" frameborder="0"></iframe>  

**Step 15: Compile and flash**  
Fingers crossed.... IT COMPILES!!!!!  

<iframe width="560" height="315" src="//www.youtube.com/embed/AmnffJUmizQ" frameborder="0"></iframe>  

**After:**

![](/uploads/2018/11/13/2FAkqfU.jpg)