

# Stick Hero Game

Welcome to Stick Hero! This document will guide you through running the project and understanding the game rules.

## How to Run the Project

1. **Using Terminal:**
    - Open the project folder in your terminal.
    - Run the following command:
      ```bash
      mvn javafx:run
      ```
    - **Note:** This command critically requires the `pom.xml` file. If the project has been set up without this file, the command might fail. In that case, follow the instructions below.

2. **Using IntelliJ IDEA:**
    - Open the project in IntelliJ IDEA.
    - Use the "Play" button to run the project.

3. **Handling File Path Errors:**
    - The game uses three files: `HScore.txt`, `CherryCnt.txt`, and `Score.txt`, which are referenced between lines 74 to 110 in the code.
    - If the runtime environment fails to locate these files due to path errors, replace the relative paths with absolute paths to ensure they are correctly accessed.

## Game Rules

### Objective

Guide the Stick Hero through obstacles, consisting of pillars and challenges, while collecting cherries to increase your score. Precision and timing are key to successfully extending the stick and crossing the gaps between pillars.

### Controls

- **Space Bar (or 'A' Key):** Hold to extend the stick; release to stop. The height of the stick determines the distance between pillars.
- **Up Arrow Key:** Move the hero upwards.
- **Down Arrow Key:** Move the hero downwards.

### Gameplay

1. **Pillars:**
    - Navigate through the pillars by extending the stick at the right moment.
    - The gap between pillars varies, so adjust the stick height accordingly.

2. **Cherries:**
    - Collect cherries to increase your score.
    - Cherries are strategically placed between or near pillars.

3. **Timing:**
    - Precise timing is crucial for successful crossings.
    - Extend the stick too early or too late, and the Stick Hero may fall.

4. **Obstacles:**
    - Watch out for falling obstacles and other challenges.
    - Colliding with obstacles may result in a decrease in score or the end of the game.

### Scoring

- **Score:**
    - Earn points for successfully crossing pillars.
    - Collect cherries for additional points.
    - The longer the distance between pillars, the higher the score.

- **Cherries:**
    - Cherries can be used to revive the hero.

### Challenges

- **Stick Length:**
    - Managing the stick length is essential. Extend it wisely to conquer varying pillar distances.

- **Timing is Key:**
    - Master the art of timing to ensure successful pillar crossings.

- **Avoid Collisions:**
    - Collisions with pillars or obstacles may lead to a score deduction or game over.

### High Score

- **Beat Your Record:**
    - The game keeps track of your high score.
    - Challenge yourself to surpass your previous best.

### Extra Features

- **Unique Placement of Cherries:**
    - Cherries can be placed at any y-coordinate, adding an extra layer of challenge.
  
- **Vertical Unrestricted Movement of Stick Hero:**
    - The hero can move vertically to collect cherries.

### Design Patterns Used

- **Singleton:**
    - Ensures only one instance of the hero exists.

- **Decorator:**
    - Used for file handling (e.g., BufferedReader and FileReader) to manage data efficiently.

## Have Fun!

Stick Hero is an exciting adventure that tests your reflexes and decision-making skills. Embrace the challenge, enjoy the journey, and strive for greatness in the Stick Hero world!

---


