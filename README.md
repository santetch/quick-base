# Bowling Game Kata: 

This kata from https://kata-log.rocks/bowling-game-kata is made in order to practice some principles from SOLID, TDD, Outside-In

##Credits
Inspired by Uncle Bob

##Bowling Rules
The game consists of 10 frames. In each frame the player has two rolls to knock down 10 pins. The score for the frame is the total number of pins knocked down, plus bonuses for strikes and spares.

A spare is when the player knocks down all 10 pins in two rolls. The bonus for that frame is the number of pins knocked down by the next roll.

A strike is when the player knocks down all 10 pins on his first roll. The frame is then completed with a single roll. The bonus for that frame is the value of the next two rolls.

In the tenth frame a player who rolls a spare or strike is allowed to roll the extra balls to complete the frame. However no more than three balls can be rolled in tenth frame.

##Requirements
Write a class Game that has two methods

void roll(int) is called each time the player rolls a ball. The argument is the number of pins knocked down.
int score() returns the total score for that game.
Starting Points
C++, C#, Elixir, Java, JavaScript, PHP, Python, Ruby, Scala

Clojure, CoffeeScript, C++, C#, Erlang, Groovy, Intercal, Java, JavaScript, Lisp, PHP, Ruby, Scala

##Follow up
Read this article “Engineer Notebook: An Extreme Programming Episode” by Robert C. Martin, where he describes solving this kata together with Robert S. Koss. Follow along in your editor. Does he do the kata the same way as you would? butunclebob.com/files/downloads/Bowling%20Game%20Kata.ppt

##Image credits
Image by Rachel M. Carmena for Kata-Log. It represents a greeting of respect and gratitude made at the beginning and at the end of a kata. Please, feel free to use this image in case you want to contribute with a kata, but you don’t have another image. It’s not necessary to include this credit again.