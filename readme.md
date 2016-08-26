<!--
Creator: <Name>
Location: SF
-->

![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)

# Racing Game

### User Stories & Game Mechanics
1. A user can see a horizontal (possibly curvy) road with two vehicles at the 'Start' line.  
2. A user can be player one or two which will correlate with a specific key press event as well as top/bottom of the screen.
3. As the key press event is clicked for each user, the car will move by a certain, even amount across the screen. (Maybe through bootstrap(?) by percentage amounts across two rows)
4. Whichever user hits the finish line (100% or px amount at the line) wins. A message will be displayed stating which vehicle reached the finish line first.

### Data Structures for "Racing Game"

**Car**
  - `car1` (image)
  - `car2` (image)

**Player**

  -'player1' Keypress event A
  -'player2' Keypress event L


**Game**

  -'constructor' (Function - constructor, create the structure for how the cars will get across the 'road'
  - `reset()` (Function - resets the game!)
  - `hasWon()` (Function - check if the game has been won!)
  - `celebrate()` (Function - display a win message)


### Development Stories

1. A user can see a horizontal (possibly curvy) road with two vehicles at the 'Start' line.  
  * Create two rows with Bootstrap(?)
    - Or download background image
  * Two vehicle images placed at 'Start Line' (Downloaded image/written in).  The vehicles would be placed at the same pixel point, or percentage as the start of the road/screen.

2. A user can be player one or two and each player will have their own vehicle.  
  * Add keypress event listener that:
     - correlates to each car (key A for player 1 and key L for player 2)

3. Two users can race their vehicles across the screen at the same time.

  * (Maybe through bootstrap(?) by percentage amounts across two rows)
    -Each keypress event will move the image vehicles by a certain amount - percentage or pixels.  
    -The amounts will be even for both the users so it's a race of how fast they can push each keypress.  

4. Whichever user hits the finish line (100% or px amount at the line) wins. A message will be displayed stating which vehicle reached the finish line first.
  * 100% width at the finish line(?) or it could match up with the exact pixel of the finish line.
    -Function would celebrate the winning vehicle.
    -Possibly a timer would show how long it took for the winning and losing car to get to the finish line(?)


###Potential Challenges / Development Questions

1. Can images be moved across the screen by pixel amounts through a function?
2. How to connect the keypress event with the function that's moving the vehicles?
3. Can there be set points on the 'road' that the image will know to move to or will they be set as separate pixel amounts?
4. Can I use bootstrap to create the road or would I just use a solid background image?
5. Cool animation or background stuff?

### Deliverable

Design user stories, data structures, development stories, and potential challenges for a **racing game** in which two players use the keyboard to control "cars" that race across the screen.

Here are some popular bonus features that would affect your data structure plan:

1. How would you make your player's "cars" use custom images?
2. Can a player type in their name to see custom win messages?
3. Can you enable a reset button to restart the race?
4. How about a win counter that spans across multiple races?

As you work, you can edit this README to add a section at the top with your name, a link to the original repository, and a 3-5 sentence reflection on completing this assignment. Push your updates to GitHub and add a link to the repo to the "My Work" section of your website!
