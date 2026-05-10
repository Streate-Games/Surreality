# Surreality

## Use Steam to connect with your friend, or open two instances on the same device.

Surreality is a 3D Isometric Co-op Puzzle game focusing on the story of 2 girls living in a mysterious world. Will they uncover the secrets behind the World's Core?  

### Download:
Download from Releases.

### Video Presentation:

[YouTube link](https://www.youtube.com/watch?v=UNX4i8bDW1M)

Update: added "steam_appid.txt" in the packaged build.  
Project files were NOT changed.


## FiiCode Final:

### Core Idea behind the mechanic: 
Dimensional Drift. The characters must switch places between two fractured versions of the same world, each different in certain ways. The switch happens by opening a "Door of Oblivion". The two characters are always in separate dimensions and can not see each other. Using a Door of Oblivion will swap the dimension of ALL players.

### Why cooperation is mandatory: 
Because the two worlds are so different, many things can be in different places, including doors of oblivion themselves. This means that whenever a player is stuck and can't advance, the other player can use a door of oblivion to switch places and progress. The stages using this mechanic are built in such a way that players take diverging paths so when the dimensions swap, they are rarely in the other player's path.

### Technical Implementation
This mechanic was implemented by using a double game map system. Using custom helper tools to aid development, a single instance of the map was build, then cloned and edited in order to offer different paths and puzzles along the way. The two players are spawned on different maps initially. They will encounter a "Door of Oblivion" which teleports them to the relative coordinates of the other map, keeping rotation and scale independent upon interaction. The system implements visual and sound effects, paired with precise timings to make the experience as immersive as possible.

[Link to the final presentation on YouTube](https://youtu.be/NgUH3YkaCkU)
