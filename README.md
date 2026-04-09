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
    Flight
        Can shoot down asteroids
        Can collect rare gems if combos the asteroid debries

//Internal comments///////////////
   {ViSUAL} is the tag for sprites and map updated
   {CODE} is the tag for any new logic within the architecture

//To do//////////////////////////
{CODE}
    Explore ways to create the character transformer
    [SCRAPPED]Trigger the transformation through collecting a specific item
        
    [EXPLORING]Trigger the transformation through a keypress
        [ONGOING]The ship_sprite is 4 sprites and needs a new 16x16 collision system
            []Exploration of a character transform using the same logic as the player collision check
               [1st TRY] Uses flr (floor) to round and snap to the grid the character
                    Gemma's explanation is 
                        So essentially, flr acts to instantly scrub away any unwanted decimal fractional values or overlaps caused by speed/gravity, forcibly "snapping" the character squarely on top of the map grid with absolute geometric precision!
    []Explore a 5 item charge ship_fuel 
    []Explore a 3 hit player_healthbar                     
    []Explore ways to navigate the Y axis on the ship
    []Explore ways to shoot down things
    []Explore ways to make the map procedually 
        Asteroid spawner with lifetime reverse counter
        Map spawner with predetermined islands
{ViSUAL}
    []player_run_anim
    []player_hurt_anim
    []player_death_anim
    []ship_fly_anim
    []ship_idle_anim
    [x]ship_destruction_anim
    [x]platform_anim
    [x]lever_anim
    [x]button_anim
    []bullet_anim
    [x]asteroid_death_anim
    [x]enemy_anim
    []enemy_shoot_anim
    [x]enemy_death_anim
    []crystals_idle_anim
    []crystals_pick-up_anim
