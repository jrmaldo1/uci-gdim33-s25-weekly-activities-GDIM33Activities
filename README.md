# GDIM 33 In-Class Activities
## W1
### Activity 1
[Inspo Board Link](https://www.pinterest.com/bigpppringlecan/game-board-3/?request_params=%7B%221%22%3A%20130%2C%20%227%22%3A%206336649899603552156%2C%20%228%22%3A%20776167385720372814%2C%20%2230%22%3A%20%22game%20board%20%3A3%22%2C%20%2232%22%3A%2045%2C%20%2233%22%3A%20%5B776167317077100031%2C%20776167317077100027%2C%20776167317077100018%2C%20776167317077100017%2C%20776167317077100015%2C%20776167317077100009%2C%20776167317077100007%2C%20776167317077100006%2C%20776167317077100005%2C%20776167317077100002%2C%20776167317077100001%2C%20776167317077100000%2C%20776167317077099991%2C%20776167317077099989%2C%20776167317077099987%2C%20776167317077099982%2C%20776167317077099978%2C%20776167317077099977%2C%20776167317077099974%2C%20776167317077099973%5D%2C%20%2236%22%3A%20%5B776167385720372814%5D%2C%20%2237%22%3A%20%22game%20board%20%3A3%22%2C%20%2234%22%3A%200%2C%20%22102%22%3A%204%7D&full_feed_title=game%20board%20%3A3&view_parameter_type=3069&pins_display=3)

1. Some patterns that I noticed were emerging from my inspiration sources related to my games potential aesthetic such as cats, space, and a general 2010s futuristic feel. I noticed a lot of nyan cat inspiration, and I believe that could influence my gameplay mechanics, such as potentially having the player play as a cat venturing through space. To be more specific, perhaps the player could move up and down on the screen, to mimic flight.
2. I found that similar to me, my tablemates had an interest in the Devil May Cry game series, which I feel has a similar aesthetic to some of the images in my moodboard, as I take personal style influence from the series pretty heavily. I believe I may want to incorporate some gothic, Devil May Cry inspired pieces in my game as well.
3. After chatting with my LA, I found that we each enjoyed the cat aspect of my moodboard, and one of the other LAs noticed an emerging My Little Pony theme as well, and was a fan.


### Activity 2
4. [3D Kitty Platformer](https://docs.google.com/drawings/d/1NvAUgFmQJYhwPN1YyRDQrk8eTDtNd-WTWk8I6AfkeL0/edit?usp=sharing)

## W3
### Activity 1
1. [New Breakdown!](https://docs.google.com/drawings/d/1NvAUgFmQJYhwPN1YyRDQrk8eTDtNd-WTWk8I6AfkeL0/edit?usp=sharing)


### Activity 2
1. It is advantageous to save the event name for the explore-to-dialogue state transitions as Scene variable("clickNpcEventName") as it allows you to label the action that the transition is achieving.
2. Using a Debug.Log() allowed me to not only learn how to properly hook up the debug node, but allowed me to figure out that I had forgotten to connect my nodes to the mouse down event as the debug log was not showing up. Once it began showing up when I clicked on the walrus, I knew my nodes were working properly.
3. The Set Cursor Lock state is relevant to my vertical slice as I am both making a 3D game, and I would like my player to be able to look around the scene when playing, however I would want there to be a lock state when they are on the menu screen.
4. The concept of a "game state" is incredibly relevant to my vertical slice as I will have multiple distinct game states in both my character and my boss objects state machines, from movement to fighting animations, and effects on health.

## W4
### Activity 1
1. My playable build right now has my player model (A poptart cat) and platforms for the player to jump on. The player can move and jump onto platforms.
2. My playtesting goals are to find bugs, and observe how players feel about the environment, and whether or not the grass blocks are out of place in space.

Names of playtest team: Jacob, Zoya, Andy, Noah, Zom

3. I found that players liked the environment, and discovered that they could double jump into infinity, which occurred because I did not add an "if grounded" requirement to my jump code. The controls were intuitive to players.

### Activity 2
1. I believe a writer may be able to add more dialogue without writing any code with this setup, however, after a certain point the graph may become very large.
2. I don't believe there is a definitive limit to how many nodes a writer could create, though there may reach a point when the graph becomes rather complicated.
3. The regenerate nodes buttons allows you to update your nodes to include new scripts you have written or nodes you have added in the project settings.

## W5
### Activity 1
1. Create an Idle and Walking animation for my player model in Blender.
2. Export each animation as an FBX file.
3. Import each animation FBX into Unity.
4. Attach the Idle and Walking animations to my player model through the animator and animator controller.
 - Drag and drop each animation into the animator controller.
 - Connect the Entry node in the animator controller to the Idle animation, and then to the Walking animation.
5. Adjust the constraints of each transition until the Walking and Idle animation work properly!

### Activity 2
Today in class, I was able to fix my initial issue of being unable to set up animations for my player, I learned that I had to make my own animations in Blender to ensure that they were compatible with my rig. After I made each animation in Blender I exported them into Unity, and was able to drag them into the animator controller. From there I was able to get the animations to fire, and now have player animations. The only thing I have left to do is to fix when they fire!
## Open Source Assets:

