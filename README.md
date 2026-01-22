## Dungeon-Escape-Adventure-1-
---
- ### A simple adventure game where:
---

### You explore a dungeon with 3 rooms. Each room gives you a choice. Your choices decide if you escape, find treasure, or get caught. Uses: functions, loops, input checking, randomness, and branching story paths
.
---
### HOW THE GAME WORKS- EASY EXPLANATION
1. slow_print()function
Makes text appear letter-by-letter like in story games.
Uses time.sleep(0.02) for a typing animation.
---
2. start_game()
Prints the intro.
Moves the player to the first choice: the doors

3. choose_door()
Shows door options (1,2,3).
Wait for valid input.
Sends the player to the room they chose.
---
4. Each room = its own function
room _monster()
room_treasure()
room_escape()
Each room has:
Dialog.
Choices.
Random events (random.randint()).
Game over or win conditions.
Sometimes sends you back to the doors.
---
5. Randomness
The game uses:
python
random.randint.(1,3)
This makes each playthrough different, like:
Fight the monster.
Opening a chest.
Running through a tunnel.
---
## _Sometimes you win, somestimes you lose.__
---
6. Ending the game
A win or game over message appears depending on your choices.





