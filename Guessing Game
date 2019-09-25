<!DOCTYPE html>
<html>
<head>
<title>Vaughn Mamugay's Number Guessing Game</title>
</head>

<body>
<h1>Number guessing game</h1>
<p>Random number is selected between 1-10.</p>
<p id="lastResult"></p>
<p id="lowOrHi"></p>

<div class="form"> 
    <label for="guessField">Enter a guess: </label> 
    <input type = "text" id = "guessField" class = "guessField"> 
    <input type = "submit" value = "Submit guess" 
           class = "guessSubmit" id = "submitguess"> 
</div> 
  
<script type = "text/javascript"> 
  
var y = Math.floor(Math.random() * 10 + 1); 
var guess = 1; 

document.getElementById("submitguess").onclick = function(){ 
      
var x = document.getElementById("guessField").value; 
  
if(x == y) 
{     
alert("YOU RIGHT! YOU RIGHT! YOU RIGHT! YOU IS RIGHT!"
          + guess + " GUESSES "); 
} 
else if(x > y) /* if guessed number is greater 
than actual number*/ 
{     
guess++; 
alert("GO LOWER"); 
} 
else
{ 
guess++; 
alert("GO HIGHER") 
   } 
} 
</script> 
</body> 
</html>
