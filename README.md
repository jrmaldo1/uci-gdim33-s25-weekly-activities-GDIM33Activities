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

## W6

### Activity 1
[Itch Link](https://julianamaldonado.itch.io/playtest-2)
1. For my playtesting goal, I would like to discover any new bugs, alongside figuring out how platform difficulty feels to players. I would like to know if the platforms feel too easy, to far, or too close together.
2. Since milestone 1, I have addedmore objects with rendered features (distant glowing planets), fixed the double jump, and created and imported animations, added a state machine for animations (which is still a work-in-progress), and made lighting changes to the game.
3. Playtest Notes: The first player liked environment, did not need guidance, and wanted dialogue/story, or perhaps a beacon to go towards as a guide. Player difficulty felt just right, especially with the current inverted controls. The second player hoped to see a high score UI in the future, and found the controls to be a bit too difficult. She thought the environment was really pretty.

### Activity 2
1. The multiply setting of the blend makes the resulting color less saturated because multiplying their values causes the hue to increase, becoming darker.
2. If we use Multiply to combine Alpha values, the resulting value be less translucent than either of the original values if one of them is smaller, and more translucent if one of the values is larger, as the alpha value will be multiplied, and thus increased or decreased accordingly.
3. The shader gets the UV values from the mesh's UV map.
4. Manipulating colors with math seems super interesting to me, especially now since I have an idea of how to do it, and the fact it works similarly to Blender's texture nodes!


## W7

### Devlog Questions 1-7
1. The data for the Vertex Color node's data comes from the mesh.
2.The color on our shiba from step (2) is blended at the edges of different regions of color because the color node can only approximate the space in between polygon vertices, unlike a texture map which has information for each specific vertex.
3. The shiba from step (3) is less detailed than the shiba we rendered with a texture in last week's activity because, unlike the texture, the vertex color can only approximate where color can exist within polygons, and between vertices. Vertex color may be useful for shading objects as either a solid color, or as a tint which doesn't cause the color to warp the texture map's data. 
4. Based on the color of the shiba in step (3),  the mesh's vertex normals appear to not have anything wrong with them.
5. Another piece of vertex data I can imagine testing with a debug shader like this may be camera direction, and I believe this may be useful as cameras often point towards players (if the game is third person) or towards the direction of objects away from players, and I feel applying this debug to either the player or other objects may help with positioning them.
6. There is an error in the lighting in step (4) on the back of the shiba because the vector of the light direction is pointing towards the shiba, but the shiba's normal vectors are pointing away from itself.
7. We set the Blend Mode to Additive for the fire effect in step (5) as it allows the brighter areas of the texture to become more opaque and darker areas more transparent through the nodes nature of the additive mode which adds to the value of the bright areas of the texture.

## W8

### Playtest Devlog:
- Since my Milestone 2 Submission, I have made tweaks to the aspect ratio of my UI, which would scale weirdly on Itch.io, especially when full-screened, but looked fine in Unity. I also changed how one of my respawn beacons worked as one of the beacons previously would not trigger a change in respawn location.
- [Playtest Link:](https://julianamaldonado.itch.io/playtest-4)
- My playtesting goals for this playtest are to test how the players feel about the new respawn beacon that directs players, and serves as a checkpoint, alongside their interaction with TacNayn. I'm curious as to how players will react to having their respawn point changed, and how they will feel about the glowy effects of the beacon, alongside the changed UI.

### Playtest Notes
- One playtester thought the game was really cute!
- They thought it was a bit difficult to tell which direction to go after respawning, and requested adding an arrow pointing towards the direction that you should go.
- Other playtester wanted to be able to look down, alongside an effect for the star to indicate bounce, and liked the boss.

## Open Source Assets:

