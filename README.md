# Project 1

For this project you will work with one or two other people to create a tic-tac-toe game using a 2D array.

## Specifications

Use a 2D array to create your board. Then, display the board. Each "empty" space should show a number 1-9 that corresponds to the space.
The board should also have the "look" of a tic-tac-toe board. Look below for an example.

You may choose to do a 2 player game (human vs. human) or 1 player game (human vs. computer). You should also ask for the name(s) of the human(s). Once you can display a grid, make it possible to place pieces (X's and O's).

Make sure you use at least 2 classes. No logic should be done in `main`. Three classes would be ideal for this project (a runner class, a player class, and a game/board class).

### Helpful Conversions

Convert int to String: Integer.toString(num)

Convert String to int: Integer.parseInt(str)

### Sample Outputs

```
Tic-Tac-Toe!

Enter name of player 1: Joe
Enter name of player 2: Jose

1    |    2    |    3    
------------------------
4    |    5    |    6    
------------------------
7    |    8    |    9    

Joe's turn: 5

1    |    2    |    3    
------------------------
4    |    x    |    6    
------------------------
7    |    8    |    9    

Jose's turn: 1

o    |    2    |    3    
------------------------
4    |    x    |    6    
------------------------
7    |    8    |    9    

Joe's turn: 2

o    |    x    |    3    
------------------------
4    |    x    |    6    
------------------------
7    |    8    |    9    

Jose's turn: 8

o    |    x    |    3    
------------------------
4    |    x    |    6    
------------------------
7    |    o    |    9    

Joe's turn: 4

o    |    x    |    3    
------------------------
x    |    x    |    6    
------------------------
7    |    o    |    9    

Jose's turn: 7

o    |    x    |    3    
------------------------
x    |    x    |    6    
------------------------
o    |    o    |    9    

Joe's turn: 6

o    |    x    |    3    
------------------------
X    |    X    |    X    
------------------------
o    |    o    |    9  

Joe wins!
```

### Class Design

In your team you will be required to map out your class design and present your proposal to Mr. King before you start any coding. These are the major parts that must be included:

1. The classes you will have and what their main purposes are.

2. Methods that each class will have.

3. What each method will do.


## Project Rubric

| Scoring Rubric | 6                                          | 4         | 1       |
| -------------- |------------------------------------------- | --------- |-------- |
| Code Style     | Good indentation and braces; easy to read. | Pretty easy to read, occasional error with indentation or braces, comments lacking. | Not easy to read, style conventions are not followed. |
| Functionality  | Program compiles and executes according to specifications. | Program compiles, but a few details of the specification have not been met. | Program does not compile and/or does not achieve desired results according to specifications. |
| Robustness     | Edge cases are accounted for; no unexpected execution (negative length/weight, etc.). | Not all edge cases are accounted for, but no major consequences result. | None or very few of the edge cases have been considered and cause issues with the program. |
| Collaboration  | All teams members contribute code to the project and work well as a team. | All team members contribute code, but distribution may be uneven and/or team members have trouble agreeing on ideas. | Distribution of work is severely uneven and/or team members struggle to agree on ideas. |

**All team members should be working on the code, not just watching one person code.**

**Codeshare.io is an online editor that everyone can edit at the same time like Google Docs. Github is a good place to keep "master" files for people to edit, although it is not a live editor like Codeshare or Google Docs.**

## Submission

Please have Mr. King run your code before turning it in. Make sure you have tested it thoroughly because he will find a way to break it, if possible!

At the top of your Runner class file put the team members' first and last names and give a brief explanation of what they did to contribute to the project and code.

Please have **ONE** team member submit the project to Google Classroom.
