## Javascript unit testing with Mocha & Chai

A [Treehouse Course](https://teamtreehouse.com/library/javascript-unit-testing) using [Mocha](http://mochajs.org/) & [Chai](http://chaijs.com/) to test and build a battleship game engine

### Outline of game engine testing

#### Using Mocha & Chai to track

1. Current player and winner
2. Number of ships 
3. Position of ships
4. Position of multiple 
5. Status as active or sunk

#### 3 test functions have been declared within [ship_text.js](https://github.com/chrisj-skinner/javascript-unit-testing-mocha-chai/blob/master/test/ship_test.js) so far.

`checkForShip, function(){ ...`

	Checking the position of a ship by reporting:
		- a given ship at a given players coordinate
		- a given ship NOT at a given players coordinate
		- ships located at more than one coordinate
		- checking multiple ships

`damageShip, function(){ ...`
	
	Log damage on a given ship at a given location


`fireShot, function(){ ...`

	Log damage if a ship is located at a given coordinate
	Not log damage if a ship is located at a given coordinate

`fireShot` combines both the `checkForShip` and `damageShip` function to reach the required output. See [ship_methods.js](https://github.com/chrisj-skinner/javascript-unit-testing-mocha-chai/blob/master/game_logic/ship_methods.js) for more details.
