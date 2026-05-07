# snake-game-project
A simple browser-based Snake Game developed using HTML, CSS, and JavaScript with score tracking, sound effects, and responsive gameplay.

## Feature:
- Snake movement using arrow keys
- Food generation system
- Score and high-score tracking
- Background music and sound effects
- Collision detection
- Browser local storage support

## Technologies Used:
- HTML5
- CSS3
- JavaScript

## Project Structure:
File Name              	      Description

index.html             	      Main webpage containing the game structure

style.css              	      Styling file for game design and layout

index.js	                    Main JavaScript file containing game logic

bg.jpg	                      Background image used in the game

food.mp3	                    Sound played when food is eaten

move.mp3	                    Sound played during movement

gameover.mp3	                Sound played when game ends

music.mp3                   	Background game music

REPORT.docx                  	Project report/documentation

Demo.vid.mp4	                Game demonstration video

Resources.txt	                References and resources used

Working of the Project
Step-by-Step Working
1. Game Start
When the webpage loads, the game initializes the snake position, score, sounds, and game board.
2. Snake Movement
The snake moves according to keyboard arrow key inputs:
Arrow Up
Arrow Down
Arrow Left
Arrow Right
3. Food Generation
Food appears at random positions on the board. When the snake eats the food:
Score increases
Snake length increases
New food is generated randomly
4. Collision Detection
The game checks:
If the snake hits the wall
If the snake touches its own body
If a collision occurs:
Game-over sound plays
Score resets
Snake returns to starting position
5. High Score System
The project uses localStorage to save the highest score even after refreshing the browser.

## Game Controls
| Key | Function |
| ↑ | Move Up |
| ↓ | Move Down |
| ← | Move Left |
| → | Move Right |

## Game Rules
- Eat food to increase score.
- Avoid touching the walls.
- Avoid colliding with the snake body.
- Game resets after collision.

## Future Enhancements
- Mobile controls
- Multiple levels
- Online leaderboard
- Pause/Resume feature
- Improved graphics

## Conclusion
The Snake Mania project is a browser-based game developed using HTML, CSS, and JavaScript. It demonstrates important programming concepts such as arrays, loops, collision detection, event handling, animation, and local storage.This project is an excellent example for students learning web development and beginner-level game programming.

## Author
Developed as a university semester project.
