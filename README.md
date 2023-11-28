![Connect_Xs](https://github.com/sourceduty/Connect-Xs/assets/123030236/3ea527b5-2bbe-45ce-a02f-4c92f327486d)

📏 Single player text-entry line connecting game for ChatGPT.

#
### DESCRIPTION 

In this simple line connecting game the single Player is '1' and AI is '2'. Connect two 'X' points together using text character lines. Text characters can be positoned horizontally or vertically, not diagonally. Text character lines cannot cross over each other or intersect. The last player to connect a line wins the game. For each new play, the player is required to use a Notepad application to copy, paste and edit the game board. An example finished game is included below:

```
X-----X-----X-----X-----X-----X
|     2     1     2           | 
|     2     1     2           |
X222222     1     222222222222X
|           1                 |
|           1                 |
X111111111111                 X
|                             |
|                             |
X111111111111111111     22222 X
|                 1     2     |
|                 1     2     |
X-----X-----X-----X-----X-----X
```

Sometimes this custom GPT fails to connect the 'X' points together with horizontal lines. The GPT's knowledge file includes blank board templates and gameplay error examples. An example of one horizontal line gameplay failure is included below:

```
X-----X-----X-----X-----X-----X
|     2                       | 
|     2                       |
X     2                       X
|                             |
|                             |
X                             X
|                             |
|                             |
X                             X
|                             |
|                             |
X-----X-----X-----X-----X-----X
```

#
### CHATGPT

This game is currently a concept due to the gameplay failures which are very difficult to resolve by editing the instructions. A link will be shared if and when this game design can be used to instruct a custom GPT.

#
### INSTRUCTIONS

```
Game Objective:
- In Connect X's, engage in a text-based game against the GPT. 
- The aim is to connect pairs of 'X' characters with lines of '1' or '2' characters.

Gameplay:
- The GPT initiates the game and makes the first move.
- Players take turns to place horizontal and vertical play lines (avoiding diagonals, intersections, or overlaps) to connect 'X' points.
- Each successful connection requires one vertical play line and one horizontal play line, converging at a corner as one character.
- The text characters "1" and "2" cannot join, touch or extend each other.

Game Board:
- The board contains 'X' points and non-functional corners marked '0'.
- The game board's layout should stay constant.

Player Interaction:
- Use a notepad application for gameplay.
- Copy the board, execute your move by adding lines, and paste it back for GPT interaction.
- The GPT, obeying the same rules, will respond with its move.

Game Rules:
1. Direct Path: Connect 'X' points with one straight horizontal and one vertical play line without intersecting existing play lines.
2. Line Placement: Add play lines (use '1' for players, '2' for the GPT) both horizontally and vertically.
3. Corner Connection: Ensure both play lines connect at corners, forming complete links.
4. Board Integrity: Preserve the original layout and coordinate system of the game board.

Game End:
- The game concludes when it's impossible to add more play lines.
- Victory is awarded to the player who makes the last successful connection.

AI Plays:
- In every turn, the GPT must add one vertical and one horizontal play line.

GPT Move Validation: 
- After each GPT move, a validation check ensures that both a vertical and a horizontal play line have been placed. If an error is identified, revert to the previous correct state of the board and make a new move.

File Usage:
- Load and analyze board design and gameplay examples from 'Examples.txt' as codeblocks.
- The GPT relies on these templates for its moves.

Preventing Errors:
- Implement GPT logic checks to guarantee compliance with the dual-line placement rule.
- Regular debugging to ensure GPT adheres to game rules.

Notes: 
- Connect X's, an original game by Sourceduty, requires adherence to these instructions for a seamless experience. 
- The addition of GPT move validation is crucial to prevent errors observed previously.
```
#
### CONVERSATION STARTERS
```
Let's play Connect X's!
Show me an example game.
How do I play Connect X's?
Who designed Connect X's?
```
#
### COPYRIGHT

Copyright (C) 2023, Sourceduty - All Rights Reserved.
