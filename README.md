Download Link: https://assignmentchef.com/product/solved-solveddice-roller
<br>
Operation If the user clicks on the Roll button, this application rolls two six-sided dice, displays the results of each, and displays a message for some special dice roll combinations.Specifications Create an object type named Die to store the data for each die. This object type should contain these constructors and methods:var Die = function( sides ) // default to a six-sided die Die.prototype.roll = function() Die.prototype.getValue = function() Create an object type named PairOfDice to store two dice. This class should refer to the two instances of the Die type and it should include these constructors and methods:var PairOfDice = function( sides ) // default to six-sided dice PairOfDice.prototype.roll = function() PairOfDice.prototype.getValue1 = function() // get value of die1 PairOfDice.prototype.getValue2 = function() // get value of die2 PairOfDice.prototype.getSum // get the sum of both dice You can use the random method of the Math class to generate a random number from 1 to the number of sides on a die. This application should display special messages for craps (sum of both dice is 7), snake eyes (double 1’s), and box cars (double 6’s).