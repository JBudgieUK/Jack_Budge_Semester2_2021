# Semester 2 2021
## 16/02/2021
Today I have started my first Component for the assignment, which is to have a First Person script be able to pickup and drop items, which then the 3 other components will be able to work with the player script.

However I had to rewind back when making my camera movement as I had done the work in the wrong scene so had to make a whole new scene and put it inside the right folder, which meant redoing the scene. The positive outcome is I had all the code already done so it was just redoing the visuals and assigning the code.

As i was adding a new script to my scene, it seemed to duplicate a script in my folder causing issues when trying to run, so i had to go into my files and delete the script and delete the component of the script and add in my new script.

When i added in my code for the holding of a object, i mispelled a line of code making the script not work. I didnt notice this until i was showing my tutor which i noticed not long after. Once that was fixed the script was fine and able to work.

## 23/02/2021
Today i will be adding a health bar mechanic so that next week when adding a enemy attack my character has a health depletion mechanic
After i finished coding the health bar next for an example i needed to give the bar to a player script which allows me to push space which will decrease the players health, however no Errors were showing but it would not let me run the the game so i went back a few steps and followed where i went wrong.
i decided to rewrite the whole player code which didnt take to long, as i feel like i had wrote or mispelled some of the script but once i did that it wokred.

## 02/03/2021
In todays Lesson i went onto my 3rd component which is the Enemy AI which will follow a path until disturbed which it will attack a player. I have the script working but will need to test this in a scene with a player component and see if work with the first two other components.

## 09/03/2021
Today i will be doing my final component and will be writing up the documentation for each component and the tutorial of how to use this week.
i will be making a attacking component.
I started of having problems with my first person controller script, which has set me back some time, but after speaking to tutor i can use scripts used in other components to show my example so this has helped me not write out a new script.
After i finished my script and was testing my component the object wasnt destroying the Enemey, after multiple checks and changes, i couldnt figure out what it was. So after showing a friend they told me i should try adding a rigid body to the object which worked out right.

## 16/03/2021
I am starting my small game project with all the components. I will need to add all the components into the scene making them all work together. I first added in my FPS script and enemy script.

## 23/03/2021
Today i added my next two scripts which were my health and attack script. However using both the attack and pick up script caused the character to attack when picking up an object. This wasnt an error, as i will need to change the key in attack script in the small demo.
I had to add a new key in my input manager by going, Edit-Project Settings-Input Manger. I added a new key which was E and rewrote the code with E instead of Fire1. This seemed to do the job.


