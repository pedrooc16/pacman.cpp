

 - Pacman
    - Can eat ghosts if ate a super pellet
    - Eats pellets
    - Move in 4 directions (up, down, left, right) by player input
    - Animates
    - Can be eaten by ghosts
    - Lives
    - Score
 - Ghost
    - Can eat pacman if not in a vulnerable state
    - Moves in 4 directions (up, down, left, right)
    - Animates
    - Has different states it can be in (Alive, Vulnerable, Vulnerable-ending, dead)
    - Has AI
    - Has a specific spot on the level that it starts at (spawn location)
    - Has a score value for when it's eaten
 - AI
    - Chase - Each ghost has a specific personality
        - Chase (Blinky)
        - Cut off/Ambush (Pinky)
        - Pinser attack with Blinky (Inky)
        - Wander (Clyde)
    - Scatter mode
 - Level
    - Contains all the walls (maze)
    - Contains pellets
    - Wraps Pacman/Ghosts at specific locations
    - Gate the releases the ghosts
    - Single background image
 - Pellet
    - Super pellet - turns ghosts to vulnerable state if pacman eats it
    - Has a specific score value
 - Special Items
    - Different ones appear with differring score values
 - UI
    - Score
    - Lives left
    - Game over/Ready label
 - Game
 	 -Level
 	 -Pacman
 	 -Ghosts
    - Different states
        - Level starting
        - Play Game
        - Lost life
        - Game Over
 */
