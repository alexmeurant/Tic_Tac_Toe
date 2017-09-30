# Tic_Tac_Toe
A Udacity project from the "Intro to Java" course.

In this project, I was required to complete the code for a Tic-Tac-Toe game. The source code of the game GUI and computer logic was provided by Udacity. While you can start compiling and playing straight away, the code is not complete because the game never detects the winner!

# Rules of the Game
Tic-Tac-Toe is a 2 player board game. One player is X and the other player is O. The game starts with an empty 3x3 grid with 9 cells. The players take turns marking each cell with either an X or an O. The goal for the X player is to get 3 X’s in one line either vertically, horizontally or diagonally. The goal for the O player is to get 3 O’s in one line either vertically, horizontally or diagonally.

![tic_tac_toe_owin](https://user-images.githubusercontent.com/18213190/31043267-587a54ae-a5b9-11e7-8d33-3cf522d0e7cd.png)![tic_tac_toe_xwin](https://user-images.githubusercontent.com/18213190/31043268-5cdec264-a5b9-11e7-8760-ae2c9199845c.png)![tic_tac_toe_tie](https://user-images.githubusercontent.com/18213190/31043269-5fa2ff10-a5b9-11e7-9adb-23456fd0572c.png)

# Run the game!

### 1. Import the project in your IDE.

### 2. Edit Run Configurations:
To tell it to run Game.java, you need to go to Run > Edit Configurations, and set up a New configuration.

Then in the Run Configurations window, click the + button at the top left of this window to add a new configuration, and select Application.

Then you'll see the configurations window, and the first thing you want to do is to name your configuration, and I'll name this Run Game.

Then you'll see the four fields that we've seen before:

- The main class that we want to run.
- The project directory for Project 1 - TicTacToe.
- The classpath of the module.
- The version of Java you're using.

You'll want to make sure these are all set to the correct fields before moving on and running the game. You'll also need to select the correct main class and module; the project directory and version of Java should be automatically chosen by your IDE.

So, after changing the name, the first thing you should select is the Main class by clicking the ... to the side of the Main class field. Then, a window will prompt you to select the Game class. Select this and click Okay.

Next select the correct module by using the drop-down menu to the right of this field, and choose the Tic_Tac_Toe_main module. Make sure you select the main module and not the test or default project modules.

After you've named and set your configuration to run Game.java, click Apply then Okay to get back to your program.

Click Apply... then Okay!

### 3. Play the game:
After your run configuration is set up, you should see it's name appear in the top right of your screen next to the Run button. Now, you can simply click this button and Game.java will run.

Run Game button.
When you click Run, you should see a tic tac toe grid appear!

Tic Tac Toe!
You can even play a one or two player game of Tic Tac Toe, but this game code does not yet detect when a player wins!
