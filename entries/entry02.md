# Entry 2
##### 12/12/22

### Content
I have learned a lot about my tool. I learned how to create a score system where a value of 1 is added whenever the sprite collects/gets a coin. I learned this from one of GDevelop's beginner tutorial which is about variables: https://www.youtube.com/watch?v=MFvAd-96LWo&list=PL3YlZTdKiS89Kj7IQVPoNElJCWrjZaCC8&index=4. To create a score system I need to use `variables` which are used whenever you want to store some information about your game such as player's health or player's score. A variable exists in three spaces of Gdevelop: scene, object, and global. Scene variables are useful for things such as score levels for a particular scene. Object variables are useful for things such as enemy health that exists just for that enemy/object(sprite). And finally, global variables are used for things such as player selected username that exists everywhere within the project. For a score system, I would need a scene variable (I think that I would need a global variable if we were to create new scenes). <br>

Now to add a score system to my game I first need to go to [scene properties](https://user-images.githubusercontent.com/73482933/207411670-1169fe78-1840-4d7f-a41f-6cd2df7e6ccf.png) <br>
Next I will click on scene properties and then name the variable `Score`, make it hold a `number` and set it to 0. [Here is the image:](https://user-images.githubusercontent.com/73482933/208219714-77f21646-3b64-49cf-840c-3e1118a30c9f.png) <br>
Now I can use the `score` variable in my events (events work the same way as if-statements, if something is true, something will run. If something isn't true then the code won't run). So when my character (an object), gets a coin (or collides into a coin), `score` gets added by 1. [Here is the image:](https://user-images.githubusercontent.com/73482933/208336319-0b0e12ff-f324-4e4d-a430-fa7f60d75c46.png) <br>

I also learned how to make a slime enemy (using the same YouTube video) which moves and sends the player to the starting point when it comes into contact with the slime. [(Image)](https://user-images.githubusercontent.com/73482933/208224434-aa086bfc-ac4e-4195-b63d-b028f59579d3.png) <br>
As you can see there is two object called `leftMarker`and `rightMarker`. These two object (they are arrow-shaped) are separate from each other while the slime is in the middle of them. When the scene runs, the slime first moves to the right and when it hits the `rightMarker` it reverses its direction and moves left towards the `leftMarker`. Now when it collides with the `leftMarker` it reverses direction and goes towards the right or the `rightMarker`. This process repeats, allowing the slime to move back and forth, and giving the player an obstacle to cross. So now when the player hits the slime, the player's position is set to the beginning of the platform. <br>

And finally I learned how to add lives using another [Youtube tutorial](https://www.google.com/search?q=gdevelop+making+lives&rlz=1CAHVCY_enUS975&source=lnms&tbm=vid&sa=X&ved=2ahUKEwjp35GVi-P7AhXEpXIEHV05DLoQ_AUoAXoECAIQAw&biw=1366&bih=617&dpr=1&safe=active&ssui=on#fpstate=ive&vld=cid:df356592,vid:RMLJjq1z3YU). To add lives, I need to create an object called `emptyHearts` and drag 3 of them onto the screen. Then I create 3 more objects and name them `life1`, `life2`, and `life3`. Each of the lives are resized to be the same size as the `emptyHearts` and are in the same position. [(Image)](https://user-images.githubusercontent.com/73482933/208224988-1fccba8c-d6ad-4c9f-922f-d25514fb12be.png) <br>
Then I will make a scenes variable called `lives` and set its value to 3. Now when the player collides or hits the slime, not only does the player's position get set back to the beginning of the platform, `lives` decreases by 1 and `life3` is now hidden showing an `emptyHeart`. `life2` hides when `lives` becomes 1 and `life3` hides when `lives` become `1`. [(Image)](https://user-images.githubusercontent.com/73482933/208225684-fc5869ea-1aac-4c71-ad55-58b63646a5a4.png)
<br>

My goal for winter break is finish Gdvelop's beginner course (https://www.youtube.com/playlist?list=PL3YlZTdKiS89Kj7IQVPoNElJCWrjZaCC8) and go on to the intermediate course (https://www.youtube.com/playlist?list=PL3YlZTdKiS89LrdlHcHo5vePN3O3UhGwm). I will also try to plan out the questions we should put for the first three units and make a rock, paper, scissors mini game which I found a tutorial for: https://www.youtube.com/watch?v=3f2Wpog-ZwI.


### EDP
The Engineering Design Process we are at are Step 3 (brainstrom possible solutions) and Step 4 (plan the most promising solution). After I learn everything I need to learn to make the game, me and my group mates can now plan what questions we should ask, where the minigames should be placed, how we can make the game interactive, etc. I also want to add some obstacles to each level so it makes the game more engaging which I will also need to plan out with my groupmates; maybe there will be slime enemies, maybe the player has to break through some walls to get to the answer choices, etc.


### Skills
One skill I need to use is time management because we still need to learn a lot more about our tool. There are still 2 and a half playlists to go through and I still need to learn how to create different levels. This means that I will need to watch around 3-5 videos in a week and budget my time wisely so me and my group mates would have at least 1-2 months of coding our game. Another skill I need to use is consideration because we want to have a balance of Java questions and mini games so our game is both educational and fun. We also need to consider what questions to put for each unit, how to organize the questions, how to put the answer choices and what kind of way the user can interact with the question choices.

[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)
