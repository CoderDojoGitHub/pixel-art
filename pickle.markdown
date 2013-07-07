---
layout: tutorial
title:  "Pickle Tutorial"
---

#Pickle Tutorial
This tutorial will cover the main features of Pickle, a pixel art editor for Mac and PC. We'll show you how to create a character spritesheet, and give you some tips for importing existing spritesheets used for characters and maps. 

##Setup

Download Pickle from [Pickleeditor.com][Pickle].
(You may need to install Adobe Flex to run this application.)

Save [helicopterman.png][Helicopter] to your computer (right click on the image and choose 'save as')

###Step 1: setting up a new animation
Open Pickle and open the image helicopterman.png from where you saved it on your computer.

![](../images/pickle1.png)

Set to: ANIMATION

![](../images/pickle2.png)

You should see this: 

![](../images/pickle3.png)

Make sure Frames are set to: ANIMATE ALL

![](../images/pickle4.png)

###Step 2: copying and pasting
Click COPY FRAME

![](../images/pickle5.png)

Add a new frame by clicking the plus button (+)

![](../images/pickle6.png)

Select Frame 2

![](../images/pickle7.png)

Click PASTE FRAME

![](../images/pickle8.png)

You should see this:

![](../images/pickle9.png)

###Step 3: building the animation
Increase the zoom to 4x or more so that you can easily see changes to the animation as you build it.

![](../images/pickle10.png)

Select the paint brush tool

![](../images/pickle11.png)

Make sure the color BLACK #000000 is selected

![](../images/pickle12.png)

Fill in this pixel:

![](../images/pickle13.png)

Select the Eraser

![](../images/pickle14.png)

Erase these 3 pixels:

![](../images/pickle15.png)

Using the paintbrush, eraser and copy and paste tools, create the 3 frames below:

![](../images/pickle16.png)

###Step 4: Saving your spritesheet

Click EXPORT and SAVE PNG

![](../images/pickle17.png)

You should have a spritesheet that looks like the one below. Each frame is a 32 x 32 pixels.

![](../images/pickle18.png)


##Importing a spritesheet
To edit an existing character spritesheet such as the one below, you need to know how big each frame is. For the character below it is 32 by 32 pixels.

![](../images/pickle-example-character.png)

Open the spritesheet and set the tile width and height to 32 pixels. Make sure the Image Settings are set to ANIMATION.

![](../images/pickle-importing-character.png)

If you want to edit a spritesheet for a map set the Image Settings to TILE. For this map each map tile is 16 x 16 pixels.

![](../images/pickle-importing-tiles.png)


[Pickle]: https://pickleeditor.com
[Helicopter]: http://bit.ly/dojosprite1

