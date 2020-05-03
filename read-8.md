# Operators and Loops:
* there are many operators that linked to a condition or something same such like(==,===,!==,<,>)..etc or logical operators like !(not),&&(and),||(or).
* Example:
```
JAVASCRIPT c04/js/comparison-operator-continued.js
var scorel = 90;
var score2 = 95;
var highScorel 75;
var highScore2 = 95;
II Round 1 score
II Round 2 score
II Round 1 high score
II Round 2 high score
II Check if scores are higher than current high scores
var comparison= (score!+ score2) > (highScorel + highScore2);
II Write the message into the page
var el = document.getElementByid( 'answer');
el .textContent ='New high score:'+ comparison;
```
## Loops:
loops check conditions then excute then under a specific values 
* like for loop:
```
var scores= [24. 32, 17]; //Array of scores
var arraylength scores .l ength;// Items in array
var roundNumber = O; //Current round
var msg ''; //Message
var i ; // Counter
//Loop through the items in the array
for (i = O; i < arraylength; i++) {
//Arrays are zero based (so 0 is round 1)
//Add 1 to the current round
roundNumber = (i + l);
// Write the current round to message
msg += 'Round ' + roundNumber + ' : ';
//Get the score from the scores array
msg += scores[i] + '<br / >' ;
document .getElementByid( ' answer') .i nnerHTML msg
```
* there are many types of loop just like for,while..etc
* While loop used usaully as a easy loop to specify what do you want excatly from sites.
```
Example:
var i = l ;
var msg = ' ' ;
II Set counter to 1
II Message
II Store 5 times tabl e in a variable
while (i < 10) {
msg += i + ' x 5 = ' + (i * 5) + '<br I>';
i++;
document .getEl ementByid( ' answer') . innerHTML = msg;
``` 