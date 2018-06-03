# TRON Game  v0.0.1
This will be a reimagination of the Light Cycle Chase from Tron Legacy.
This game is intended to be an executable on Windows and Android. (I don't know how to do that yet; I'll figure that out on the way.)
This game is ultimately intended to have a simultaneous four player control system, the keyboard bindings of which can be changed through an option in the main menu. For now the game mechanics and graphics will be focussed upon, featuring a single player.
The game will have a sprite based graphics, the sprites for which are being designed at the moment. They will be uploaded as soon as they are complete.
The game will also have sounds and soundtracks. The inclusion of which will be confirmed as soon as the techniques will be learnt.
The game will also have background images for single player levels, multiplayer arenas and every screen it shows.
The game is intended to have a modular level writing systemsystem similar to Sokoban, so that updating and adding new single player levels is extremely easy and efficient.
The game is expected to have a single player levels of increasing difficulty, whilst having separate sections for each new powerup type.

The layout of the game will be:
   
   1. Intro/Title Screen:
   
   2. Main Menu:
        2.1. Single Player: This will be a platform based puzzle game where the goal is to reach the exit avoiding one's own trail and the obstacles. Additionaly, there are several elements which are used as plot points to solve each level. It is also intended that there be a boss level at the end of all levels.
            2.1.1 Level 1
            2.1.2 Level 2...
        
        2.2. Multiplayer: This will be a simultaneous PvP match to defeat the opponent by making them hit one's or their own trail, or the on the arena. It is also intended to feature multiple arenas with different positions of walls.
            2.2.1 2 Players
            2.2.2 3 Players
            2.2.3 4 Players
        2.3. Controls: This will allow users to change keyboard bindings for each of the four users and set their own player names
        2.4. Credits: To give due credits to all those involved in the development of the game.
        2.5. Exit: Exits the game right away.
    
Game Elements:
    
    1. Light Cycle:
    2. Trail:
    3. Wall:
    4. Powerup Disk:
    5. Floor:
    6. Entry Door:
    7. Exit Door:
    
Colour Elements:
Possible Player Colours:
        
        1. Red
        2. Blue
        3. Green
        4. Yellow
    
Possible Powerup Colours
        
        1. Pink/Purple
        2. Cyan/Teal
        3. Orange
        4. Neon/Lemon
        5. White
    
Types of Powerups:
    These power ups are intended to be for limited time only and a cool animation for the starting and timeup of thses colours is desired (Maybe a blinking sprite to indicate that the powerup is going to end, or a bar which shows how much time of powerup is left.)
        
        1. Speed Up
        2. Slow Down
        3. Increase the length of trail
        4. Decrease the length of trail
        5. Phase through walls
     
For the multiplayer battle, the game is intended to have multiple lives and losing one battle results in the loss of a life. The winner is determined when the other players lose their lives.
It is also intended that multiplayer mode have powerups lying around on the arena floor so that players can pick the powerups and use them for a limited amount of time.

Game Mechanics Required
    Collision Detection
    An Object of bike type which stores:
        A dynamic queue which stores the player's bike coordinates and trail coordinates, along with sprites and methods to render them
        Speed values for the bike
        Directon of movement of the bike
        colour of the bike and associated properties and actions
        methods to act upon keyboard bindings
        methods to inherently update the bike and trail's position each iteration
        collision detection for each sprite of the bike and also of the trails
