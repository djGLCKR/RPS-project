# RPS-project
Rock-Paper-Scissors JS project for "The Odin Project"

We’re going to make a simple implementation of grade-school classic “rock paper scissors”. If you don’t know what that is check the [wikipedia article](https://en.wikipedia.org/wiki/Rock%E2%80%93paper%E2%80%93scissors) or [this ridiculous step-by-step](https://www.wikihow.com/Play-Rock,-Paper,-Scissors). For the moment we’re just going to play the game from the browser console, but we will revisit it and add a front end later so don’t forget to keep the code on GitHub! You might notice some ‘view in browser’ links in the student solutions - this is coming in a later lesson. When you get there don’t forget to come back and add your link!

Assignment:

  1. Start a new git repo for your project.
  2. Create a blank HTML document with a script tag. This game is going to be played completely from the console, so don't worry about putting anything else in there.
  3. Your game is going to play against the computer, so begin with a function called `computerPlay` that will randomly return either "Rock", "Paper" or "Scissors". We'll use this function in the game to make the computer's play.
  4. Write a function that plays a single round of RPS. The function should take two parameters - the `playerSelection` and `computerSelection` - and then return a string that declares the winner of the round like so: "You lose! Paper beats Rock!"
     - Make your function case insensitive, so users can input rock, ROCK, RocK, or any other variation.
     - **IMPORTANT NOTE**: You want to `return` the results of this function call, not `console.log()` them.
  5. Write a NEW function called `game()`. Use the previous function _inside_ of this one to play a 5 round game that keeps score and reports a winner or loser at the end.
     - At this point you should still just be using `console.log()` to display the results of each round and the winner at the end.
     - Use `prompt()` to get input from the user.
     - Feel free to re-work your previous functions if you need to. Specifically, you might want to change the return value to something more useful.
     - Feel free to create more "helper" functions if you think it would be useful.
