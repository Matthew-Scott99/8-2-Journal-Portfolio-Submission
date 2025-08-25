CLIENT AND REQUEST

Client: The Gaming Room
Goal: Plan a web-based version of Draw It or Lose It that runs on many platforms
Key needs: one game service in memory, unique names for games and teams, teams with multiple players, works in desktop and mobile browsers


WHAT I DID WELL
Clear, short design write-up
Base Entity class for shared id and name
Singleton for the game service
Checks for unique names to avoid duplicates


WHAT HELPED DURING CODING
Writing the design first made class choices simple
The domain model kept the code small and easy to follow
Fixed rules (one instance, unique names) removed guesswork


WHAT I WOULD REVISE
Add a few non-functional targets like “image loads under 200 ms”
Add a tiny sequence sketch for start game → show image → guess
List a couple of test cases right in the doc


HOW I USED USER NEEDS
Turned needs into rules and patterns: one service, unique names, teams and players
This keeps the app stable for players and reduces rework later


MY DESIGN APPROACH
Start with requirements
Draw a small domain model
Use simple patterns (Singleton, Iterator where needed)
Build a small prototype and test
Next time add quick performance goals, a short security checklist, and a brief deploy note


REPO NOTES
This repo is for my portfolio
Instructor has access
The design doc is the main artifact for this course entry
