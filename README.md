# Elevens-Lab-Activity8

1. All three games have the same foundation of adding cards together to each games respective number (10, 11, and 13). In each game you match pairs of cards to reach the desired product. The differences of the games most notably are the three different desired products of the games. Furthermore, each game has a separate combination of face cards that the player can match in order to remove them from the board. Finally, the last difference between the games is the amount of cards that can be on the board at a time.

2. ElevensBoard inherits Board and an ElevensBoard object is created with parameters that correlate to Board and through this ElevensBoard is able to obtain all of the instance variables that Board has. The mechanism is Inheritance.

3. The abstract methods in Board are isLegal and anotherPlayIsPossible. They do not cover all of the differences because these two methods only pertain to the game Elevens and not to the other two games. Their rules won't work with these methods.