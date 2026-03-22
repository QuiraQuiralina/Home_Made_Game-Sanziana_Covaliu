# Home_Made_Game-Sanziana_Covaliu
Project for the Game Development Classes

//Description///////////////////////
    A 2D pixelart surfer-platformer game about a space explorer character that has a miniship that they can board and travel sections of the map shooting down asteroids with it.

//Character/////////////////////////

    Human
        Basic character control + Dodge, sprint, double-jump
        The human character responds to gravity while the ship does not (hence the flight). 
    Ship
        The ship form is conditioned and timed by a fuel bar that can be filled via collecting an item named 'crystals' while in human form
            There is a condition for transforming = They have the fuel bar above or equal to 50%.
                When they run low on fuel there's a warining sigh (a red vignette that pops and where it gets to 0% they are forced back to human form)
            --to be determined if on buttonpress or item collection
        The spaceship can also shoot down obstacles while in the human form, the player cound not pass them. The bullets are infinite and activated by a simple button press.
    

//Environment//////////////////////
    Ground
        Has some plant enemies (they do not move)
        Has some collectibles
        Has a power up that enhances jump
    Flight
        Can shoot down asteroids
        Can collect rare gems if combos the asteroid debries

//Internal comments///////////////
    1st commit included an empty .p8 file.
    Repository is create within game files not Pico8 carts

//To do//////////////////////////
    Fix colisions left and right
    Explore ways to create the character transformer
    - Trigger the transformation through collecting a specific item
    - Trigger the transformation through a keypress