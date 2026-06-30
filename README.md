# CMPT276F25_Group8 - Zombiefied Hamlet 

# Table of Contents
- [Overview](#overview)
- [Video Tutorial](#video-tutorial)
- [How To Play The Game](#how-to-play-the-game)
  - [Running the Game](#running-the-game)
  - [Controls](#controls)
- [Running Tests](#running-tests)
- [References](#references)

## Overwiew 
Zombified Hamlet is a tile-based survival game where players navigate through a zombie-infested hamlet while avoiding deadly zombies that reduce your health. The objective is to survive the undead horde, gather essential items such as food to increase your health, and escape through the trap door before your lives run out.

## Video Tutorial 
Here's the link to our video - https://www.youtube.com/watch?v=JwpMLy3zHMU

## How To Play The Game

### Running the Game
```bash
mvn clean compile
mvn exec:java
```

Press **H** to access the User Manual or press `ENTER` to start the game.

### 🎮 Controls

**Start Screen:**
- Press `ENTER` to begin your adventure
- Use `ARROW KEYS` to pick your level
- Press `ENTER` again to dive in
- Press `SPACEBAR` on level screen to quit

**In Game:**
- Move around with `ARROW KEYS`
- Press `P` to pause or resume the action
- Press `SPACEBAR` to quit

**Game End Screen(Win pr Loose):**
- Press `ENTER` to try again
- Press `ESC` to go back to level select
- Press `SPACEBAR` to quit anytime

## Running Tests
```bash
# Compile the project
mvn clean compile

# Run tests
mvn test

# View coverage results
open target/site/jacoco/index.html

# Generate and view Javadoc
mvn javadoc:javadoc && open target/reports/apidocs/index.html

# For JAR files and to run our tests & the game 
mvn clean package && java -jar target/ZombieGame-1.0-SNAPSHOT.jar

# Created an Artifacts folder which has our jar file + index.html ( for javadoc )
To check javadoc - Artifacts→ Javadoc →reports→apidocs→index.html or open Artifacts/Javadoc/reports/apidocs/index.html
To check JAR file and to run our game -  open Artifacts/Jar/ZombieGame-1.0-SNAPSHOT.jar
```

## References

* Fireship. (2021). *Docker in 100 Seconds*. YouTube. https://www.youtube.com/watch?v=om59cwR7psI
* Graphable.ai. (2024). *Pathfinding Algorithms*. https://graphable.ai/blog/pathfinding-algorithms/
* Game Assets: [Grass and wall tiles](https://drive.google.com/drive/folders/1dtaCKBy9qWhetQi5PWWOHqcuDjXI0Fh-)
* Audio Tool: [BeepBox](https://www.beepbox.co) (2025)
* Youtube Playlist for guidance: https://youtube.com/playlist?list=PL_QPQmz5C6WUF-pOQDsbsKbaBZqXj4qSq&si=gEnZ7Rh-4UT5NFjB
