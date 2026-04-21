# DnD Dice Rolling Program

A command-line dice rolling tool written in Python, designed for tabletop games such as Dungeons and Dragons. The program allows users to input standard dice notation (e..g 3d10, 2d6, etc.) and generates roll results

## Features
- Supports standard tabletop dice notation (e.g. 1d20, 2d6, 5d4, etc.)
- Allows the user to specify both the number of dice and number of sides
- Randomised dice rolling using Python's random module.
- Input validation to handle incorrect formats
- Option to repeat rolls or exit the program

## How It Works
The user inputs a dice roll in the format `XdY`, where:
- `X` = number of dice
- `Y` = number of sides per die

The program parses the input, validates the values and simulates rolling the dice by generating random numbers within the specified range.

The program then displays:
- Each individual roll
- The total value of all dice rolled

After each roll, the user is prompted to either exit the program or roll again.

## How to Run
1. Download the Python file
2. Run using Python, via terminal or an IDE
3. Enter a dice roll (e.g. 3d6)
4. Follow on-screen prompts

## Technologies Used
- Python
- random module

## Future Improvements
- Add support for modifiers (e.g. 2d6+3)
- Implement roll history tracking
- Improve command handling (e.g. help menu)
- Add advanced mechanics (e.g. advantage/disadvantage)
