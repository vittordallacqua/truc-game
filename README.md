### Truc Game in Java

The project is structured using OOP principles, with separate 
classes for different game components, promoting modularity and 
reusability. The game interacts with the user via the console, 
prompting for inputs and displaying game states. The codebase is 
designed to be extensible, allowing for future enhancements such 
as GUI integration or networked multiplayer support.

The game is able to randomly shuffles and deals cards to players
at the start of each round. The players take turns playing cards, 
with the game determining the winner of each hand. It Implements 
the "Truco" challenge mechanism, allowing players to raise the 
stakes. It keeps track of each player's score, determining the 
winner when a player reaches the target score, and ensures that 
all game rules are followed, including valid card plays and 
responses to "Truco" calls.

How to run:
  
  ```
  > git clone https://github.com/vittordallacqua/truc-game.git
  > cd truc-game
  > javac src/**/*.java
  > java -cp src Main
  ```

Using VS Code:

* Make sure you have the "Extension Pack for Java" by Microsoft 
installed. This includes Language Support for Java™, Debugger for 
Java, Maven for Java, Project Manager for Java, and Test Runner for 
Java.
  
This project is licensed under the MIT License.
