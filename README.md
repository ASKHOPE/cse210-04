# Greed
Greed is a game in which the player seeks to gather as many falling gems as possible. The game continues as long as the player wants more!


## Rules
Greed is played according to the following rules.

Gems ( * , $$ , & ) and rocks (0) randomly appear and fall from the top of the screen.
The player (#) can move left or right along the bottom of the screen.
If the player touches a gem they earn 1 point for (*), and 3 points for ($$), and  2 points for (&) respectively .
If the player touches a rock they lose 1 point.
Gems and rocks are removed when the player touches them.
The game continues until the player closes the window.

## Getting Started
---
Make sure you have Python 3.8.0 or newer and Raylib Python CFFI 3.7 installed and running on your machine. You can install Raylib Python CFFI by opening a terminal and running the following command.
```
python3 -m pip install raylib
```
After you've installed the required libraries, open a terminal and browse to the project's root folder. Start the program by running the following command.
```
python greed 
```
You can also run the program from an IDE like Visual Studio Code. Start your IDE and open the 
project folder. Select the main module inside the hunter folder and click the "run" icon.

## Project Structure
---
The project files and folders are organized as follows:
```
root                    (project root folder)
+-- greed                 (source code for game)
  +-- data              (data files for game)
  +-- game              (specific game classes)
  +-- __main__.py       (entry point for program)
+-- README.md           (general info)
```

## Required Software
---
* Python 3.8.0
* Raylib Python CFFI 3.7

## Authors & Contributions
---
* Arnold Sujan Katru (kat21015@byui.edu) - Falling Artifacts & Player Movement
* Sandra Asamoah Adeleye (ade21006@byui.edu) - Score Manager (Collect the score and process it)
* Marcus Blanc (bla21011@byui.edu) - Create Repository & Readme file & Removing the artifact on contact.
* Karrass Phiri (phi21020@byui.edu) - Create Artifacts (Rocks & Gems) With different Shapes and Score values.
