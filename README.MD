# Jelly, Roll!
Jelly, Roll! is a smooth scroller game controlled by the Leap Motion Sensor built by myself, Avika, Kathy and Corbin. The player takes the blob on a magic carpet ride by moving his/her hand to control the height of the platform. The ultimate goal is to make it through all three levels without falling off the platform and successfully guide the Jelly to the hospital!

We used the LeapMotion library created Michael Heuer to help control hand gestures and Fisica, a processing library that provides wrappers for Box 2D functions, to power our game. Our game was featured in NYU Computer Science Showcase!

Jelly, Roll! was created by Avika Narula, Adithep Narula, Katy Herrick, and Corbin Lee

# Gifs of Jelly, Roll!

![gameplay](/readme/gameplay.gif)
User moves his/her hand to control the height of the platform

![level1](/readme/level1.gif)
There are three levels in Jelly, Roll! This is level 1.

![level2](/readme/level2.gif)
Level 2 of Jelly, Roll!

![level3](/readme/level3.gif)
Level 3 of Jelly, Roll!

![win](/readme/win.gif)
The winning page after user completes level 3. Jelly finally arrives at the hospital! 

#### For a full video of Jelly, Roll! please visit http://www.adithep.com/jellyroll.html

# Architecture and Technologies

### Processing IDE
* programming environment based on Java
* makes it easier to construct visual software
* contains many libraries for interactivity

### Leap Motion Sensor
* We imported the LeapMotion by Michael Heuer, which comes in with built in gestures detectors
* We used simple gestures such as "swipe" and to pull simple height and hand roll values to maximize the reliability of the game

### Fisica
* Processing library that provides a wrapper around Box 2D functions, which powers our whole game
* Takes care of collision detection between the character and obstacles
* Gravity of the world pulled nonstatic objects down without any explicit programming
* The only two static objects in this game are soccer balls and platform
