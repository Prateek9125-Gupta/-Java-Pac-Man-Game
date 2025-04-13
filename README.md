# Java-Pac-Man-Game
A classic Pac-Man clone built in Java using the Swing GUI toolkit. Control Pac-Man with your keyboard, eat all the pellets, avoid ghosts, and survive as long as you can!

🎮 Features
. Full 2D game with tile-based grid movement

. Ghost AI with basic random movement

. Food collection and scoring system

. Lives system and Game Over handling

. Level reset on food completion

. Directional Pac-Man sprite animations

. Classic maze design loaded from a character map

🧱 Technologies Used
. Java (JDK 8+)

. Swing (JPanel, JFrame, Timer)

. Object-Oriented Programming

. Basic collision detection logic

📁 Project Structure

/PacManGame

│

├── Main.java            
├── PacMan.java          
├── wall.png             
├── pacmanUp.png         
├── pacmanDown.png       
├── pacmanLeft.png       
├── pacmanRight.png      
├── blueGhost.png        
├── orangeGhost.png      
├── pinkGhost.png        
└── redGhost.png 

🕹️ Controls

 Key                    	    Action
↑ Arrow      	                Move Up
↓ Arrow	                      Move Down
← Arrow	                      Move Left
→ Arrow	                      Move Right
(Any key after Game Over)     Restart game

🚀 How to Run
▶️ Using an IDE (IntelliJ / Eclipse)
1. Clone/download the project.

2. Open in your IDE.

3. Make sure all image files are in the same directory as PacMan.java.

4. Run Main.java.

5. Click the game window to focus it, and start playing with arrow keys!

💻 Using Terminal
javac PacMan.java Main.java
java Main

📌 Game Map Representation
The tilemap in the code uses symbols to represent game elements:

java

X = Wall

P = Pac-Man start position

b/o/p/r = Ghosts (blue, orange, pink, red)

(space) = Food pellet

O = Skip tile (empty area)

📸 Screenshot
![Screenshot 2025-04-13 182339](https://github.com/user-attachments/assets/72f2842a-77c4-4e67-8d43-f3aaf2a8cb41)

📸 Video

https://github.com/user-attachments/assets/f5847aa6-02c1-41f8-a5c2-b5a459b7bbb0

