---
layout: tutorial
title:  "physics-animation"
---

#Using physics in animation
In this tutorial we'll take a look at how physics can help you create more realistic animations using some basic animation principles. Here we have the pixelcat with a drip of water dripping from it's tale and splashing on the ground.


###The drip
In real life water starts to build up into a buldge before it drips from an object, as you can see in the dripping tap image.

![](images/animated-drip.gif)

We only have some big square pixels to play with but we can imitate the effect in our animation. To do this we make the water drop grow bigger before it leaves the tail.

![](images/splash-drip1.png)

The drip also creates anticipation, it prepares the audience for the action (the drip) that is about to happen.


###Dripping
Once a drop of water leaves an object it moves fast. Rather than moving the water drop through every pixel in a row, we do every other pixel to give it the appearance of moving fast.

![](images/splash-drip2.png)

###Splash
To create the effect of a splash we need to use more pixels of water than the drop. This is so we can show pixels travelling through the splash. We also use another shade of blue for 2 reasons: to show the impact of the drop hitting the ground; and to give the water a shimmering effect - in real life water looks different shades of blue when light bounces off it.

![](images/splash-drip3.png)

###Pause
If you watch a dripping tap, the water takes a while to collect a drip of water before it drips again. To create this affect we add a few frames without the water and then a few with the drip not moving.

![](images/splash-drip4.png)

###The speed
With each animation you can set the Frames Per Second (FPS). This is the time it takes between showing each frame of the animation. For this animation we don't want it to move too fast so we get the effect of the drip building up and the pause. The FPS is set to 6fps for this animation.

![](images/pixelcat-splash.gif)


###Create your own animation!
If you want to have a go and making the animation above download the [pixelcat](http://coderdojosf.github.io/pixel-art/images/pixelcat-64.gif) and use either [Pickle](http://www.pickleeditor.com/) or [Pixen](http://pixenapp.com/) to create the animation.

You could also try something different like making an animation of fire. Have a look at how the flames flicker in the image below and see if you can create an animation that feels realistic.

![](images/fire.gif)
