Fucntion getComputerChoice
    1. create variable of randomNumber which creates a random number with Math.random 
    but to make it a whole number use Math.floor and then multiple it by 3 to get 3 numbers
     to apply strings to.
     2.Using if else if statements. Associate numbers 1-3 to strings of rock, paper or scissors for the game. 

playRound
    1. takes in two parameters. playerSelection and computerSelection.
    2. useing if else if and nested if else statements.
    3. if playerSelection and computerSelection both equal the same string, then return "It's a tie!"
    4. followed by else if statements for the different playerSelction. 

game function
    1. This function will call the playRound funcion and will play a 5 round game and keeps score and reports a winner or loser at the end.
    2. using a for loop to call the playRound function for 5 times.
    3.