# Rock, Paper, Scissors Challenge

Welcome to the Rock, Paper, Scissors Challenge! In this project, you will create a program to play Rock, Paper, Scissors against multiple bots. The goal is for your program to win at least 60% of the games in each match against four different bots. 

### Requirements:
- Your program must play matches against four different bots.
- Your program should win at least **60%** of the games in each match.
- The program's behavior should be based on the opponent's last move.

### Instructions:
1. **File Structure**:
   - **`RPS.py`**: Contains the function `player` where you define your program's behavior. 
   - **`RPS_game.py`**: Contains the game logic and predefined bots.
   - **`main.py`**: Used for testing your code by playing games.
   - **`test_module.py`**: Contains unit tests for your project.

2. **Functionality**:
   The function `player` in `RPS.py` accepts one argument:
   - **`prev_play`**: A string representing the last move of the opponent (`"R"`, `"P"`, or `"S"`).
   
   It should return a string representing your next move (`"R"`, `"P"`, or `"S"`). If it's the first game, the argument will be an empty string.

   **Example**: 
   ```python
   def player(prev_play):
       if prev_play == "R":
           return "P"  # Countering Rock with Paper
       return "R"  # Default to Rock
   ```

3. **Game Setup**:
   You are provided with a function to play the game. The `play` function allows you to play multiple games between two players. It takes the following arguments:
   - **`player1`**: The first player (your program).
   - **`player2`**: The second player (a predefined bot).
   - **`num_games`**: The number of games to play in the match.
   - **`verbose` (optional)**: Set to `True` to see the log of each game.

   Example usage:
   ```python
   play(player, quincy, 1000, verbose=True)
   ```

4. **Development Guidelines**:
   - **Do not modify** the `RPS_game.py` file.
   - Write all your code in the `RPS.py` file.
   - You can test your code in `main.py` by importing the `play` function and bots from `RPS_game.py`.

5. **Hints**:
   - Your program will need multiple strategies to beat all the bots.
   - Pay attention to the opponent's moves and adjust your strategy accordingly. 

6. **Testing**:
   - The unit tests are located in `test_module.py`. You can run them automatically by uncommenting the last line in `main.py`. The tests will run each time you execute `python main.py` in the terminal.

7. **Submitting**:
   - Once you've implemented and tested your solution, submit your project by sharing the URL to freeCodeCamp.


