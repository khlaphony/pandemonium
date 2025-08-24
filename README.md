# project pandemonium

## description
CLI turn based card RPG written in C for algorithm practice. 
Heavily inspired by SMT's Devil Survivor series for the 3DS, Slay the Spire
and Granblue Fantasy. 

## to do 
- rewrite the code using C++ (or java ig,,,) and implement the GUI using MVC.

## (1) main menu 

### (1.1) Play Game

### (1.2) Loading File Progress

### (1.3) Change Difficulty

### (1.4) Quit 

## (2) map generation

### (2.1) level checking
- Identifies what level the player is on based on the level they're in atm.

### (2.2) area bound creation
- Every match contains a randomly generated map using dynamically allocated jagged arrays.
This function must not create maps that are either too small or too big. A separate function
should display this map to the CLI. 

### (2.3) enemy spawning 


## (3) preparation phase 
- Cards depend on the character chosen. 

- Movement Cards
-- Switch/Enemy, Switch/Ally
-- Switch/Obstacle
-- Bishop (Only Move Diagonally --for one turn)
-- Knight (Only Move in L Direction)
-- Rook (Only Move Straight) 

- Build Cards
-- Throw (Creates an Obstacle in a set range)
-- Destroy (
-- 

--------------------------------

- Combat Cards
-- Increase Strength 
-- Increase Defense 

-- 
--
-- 

- Tech Cards
-- 
-- 

--------------------------------

- Curse Cards 
--

- Break Cards
-- 

### (3.1) base character 



## (4) gameplay loop

### (4.1) movement 
- The player is able to move around the board using a preset set of cards chosen from the
preparation phase. 
- The cards should be displayed in sorted order depending on movement type. 

### (4.2) combat
- An unlimited number of cards can be played at any turn before the player decides to attack. Once the player attacks, presses end, or plays a card that ends their turn, the players turn ends and is passed to their opponent. 


- If an enemy is defeated, the player regains all cards that were used against that enemy. 



- The cards should be displayed depending in sorted order depending on combat type. 
    - aa


### (4.3) enemy
- Using a shortest path algorithm, enemies must be able to identify and 
move towards the player when it is their turn. 
- Enemies have their own properties but for this implementation there's only one.
- 

### (4.4) saving
- Must make use of binary I/O for saving data
- 

## other things to make your life harder after rewriting the code
- more enemies, bosses, more playable characters,,,
- obstacles depending on stage levels 
- difficulty scaling depending on rounds
- map generation to include patterns and tiles
- have 3-4 characters on each team per match.

- 


- deal mechanic. 
-- stats of the player character are attributed to major demons (may be replaced).
By increasing these stats, buffs and new cards are given to the player. But it also 
causes the major demon that was chosen to get even stronger. Effects include : new enemies, 
new abilities to pre-existing enemies, higher damage, higher speed, etc. 

- (experimental) -breaker mechanic
-- new cards dont change, but the player is allowed to change their stats at any point before
a match. --> 


- actually decide on the visual style so you can start the GUI (me no no wanna)
    - my idea for this atm is to base it off the divine machinery aesthetic and
    have enemies as machine depictions of angels and demons . That and/or maybe mix
    divine machinery with chi mythology and/or filo mythology ala SMT and hades.
    - idfk 

