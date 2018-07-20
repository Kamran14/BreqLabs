# BreqLabs Inc.
## How to use the controller as input on Unity

1) In your scene, make an empty GameObject Called 
`BreqLabsConnectionManager`. Click on the Tag option and create a new 
tag called `GloveConnectionManager`. Make sure the Tag under 
BreqLabsConnectionManager is set to `GloveConnectionManager`.

2) Head over to your Project Tab and go into the Following Directory; 
`BreqLabs-> Scripts`.

3) Once there, you will need to click and drag the 
`BreqLabsConnectionManager` script onto your GameObject created in step 
1.

4) Click on your `BreqLabsConnectionManager` GameObject and an Inspector 
tab should appear to the right of the screen. Under the `BreqLabs 
Connection Manager` Script, set the values to correspond with this 
image: ![Click to Enlarge](https://github.com/Kamran14/BreqLabs/blob/master/img/1.png)

5) Find the parent that holds your right and left GameObjects that will be moved by the controllers and attach the `BreqLabs Reader` Script onto it.

6) Stay in the GameObject that contains your `BreqLabs Reader` Script and drag your right controller objects into: `Or_PALM`, `Or_ARM`, `Or_FOREARM`, `Or_REF_SPINE` and `Parent Enable Right`. Do the same for the left one, but place the objects inside `Ol_PALM`, `OL_ARM`, `Ol_FOREARM` and `Parent Enable Left`; ![Click to Enlarge](https://github.com/Kamran14/BreqLabs/blob/master/img/2.png

*OPTIONAL* If you want to use the BreqLabsConnectionManager in other scenes,  do this step. Click on the parent of your character GameObject and drag it into the Prefabs folder located under the BreqLabs folder in the Project Tab. Now click the BreqLabsConnectionManager GameObject and add drag that under the Prefabs folder as well. That will handle the movement part of the controller.
