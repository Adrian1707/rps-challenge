# Rock, Paper, Scissors

Game Logic
-------
* This is a simple Rock, Paper, Scissors game built in Ruby with the Sinatra framework, tested with Rspec and deployed on Heroku at https://glacial-refuge-4338.herokuapp.com/?
* There is a single class called 'Game' with a selection of 6 methods. One method requests the users choice, one sets the computers choice, 3 methods together decide if it's a win, lose or draw. 1 method displays the result.
* The game logic works as follows in irb:
  *   game = Game.new
  *   game.user_choice("scissors")
  *   game.comp_decision
  *   game.result
* Enter the project directory and type in 'rackup' to create a server, visit the local    host in your browser via the port specified, or play the game online at https://glacial-refuge-4338.herokuapp.com/?
