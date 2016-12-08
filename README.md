# Tech Studi Project Tutorial

## Initial thoughts
Create a cute interactive game, which is like flappy bird and use distance sensor to control it. The character of the game is a monster, and players will use sensor to control its position to avoid bombs and eating planets.
 
## Modification 
After research we found there were already lots of sensor-control games online, so we change our idea a little bit. The monster will be able to shoot fireballs to eliminate the planets. If the monster is hit by the planet, game will be over. Instead of using distance sensor, we used makey makey to control the monster’s position and shoot fireballs.  We made a gamepad and put makey makey board inside, selected soft sweets as buttons to control position.
 
## Technology
Using Creative JS library: ZIM to create game interface. Open.html is start page, game.html is game page and over.htm is the gameover page.There pages are linked together by the buttons.

## Material
Makey makey board, carton, tape, soft sweets, paper, water color pen.

##Coding Explanation
1.	Create a scrolling background

2.	Put the monster on the stage

3.	Add keyboard functions to control the monster’s position by press left, up, right, down

4.	Put planets on the stage, use setTimeout and move function to make the planet move from right side and use zim.rand to randomly change the planets

5.	Add fireball and use move function to let the monster shoot the fireballs

6.	Add keyboard function to the fireball so that users can press space to shoot the ball

7.	Make two hitTest, one for removing planets when they are hit by the ball, and another for game over when the monster is hit by the planet

8.	Add a score panel and link it to hitTest, when monster eliminate a planet the score will add up

9.	Add music to the game and link the game to the game over page.

## Controller Installation
We use soft sweets to connect to the Makey makey board. You can use whatever kind of material you like as long as it is conductive. 

1. Firstly, find a suitable box to as a container, and we made a shape like a small paw control the monster’s position by press left, up, right, down, a fireball shape control the monster shoot the fireballs.
2. Then, we made shapes attached to the box surface, and drill holes in the box surfaces so that wires can get through, and in the end we put soft sweets fixed on the top.
3. Finally, put the makey makey board into the box and finish the controller.

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Assets
All the assets are in the assets file. You can create new characters and replace them.

## Credits
Group Member: Yichen Shen, Sitong Wang, Lulu Kang, Zhen Wang

