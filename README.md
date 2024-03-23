**Rock Paper Scissor Game**

To start the application you can do by<br/>
<code>npm install</code><br/>
then<br/>
<code>npm start</code>

Tech Stack Used
- MUI
- ReactJs
- IndexedDB

**Requirement Fulfill by the game Listed in Documentation**

User Authentication:
Players should be able to enter unique usernames to identify themselves. with the use of indexedDB, 
- I have created table which stores data about username and wherenever a duplicate username added it will alert that message

Game Lobby:
Display a list of available players in the game lobby.
Show a "Play" button next to each available player to initiate a game
= Once you clicked on the play game it will redirct to lobby page  where players will be listed with play or ingame as status

Leaderboard:
Display a leaderboard that shows the usernames and scores of all players.
Update the leaderboard in real-time as scores change.
- Home page consists of leaderboard which will updates if changes happen used polling instead of live socket as constraint was to use frontend tech

UI/UX:
Create a user-friendly and visually appealing interface using HTML and CSS.
Use responsive design to ensure the game works well on different screen sizes.
- made for different screen size

Gameplay:
When two players agree to play, open a game window for them.
Implement the Rock-Paper-Scissors game logic: Rock beats scissors, scissors beats paper,
paper beats rock.
- after clicking on play it will open new window with option buttons like rock paper scissor
- logic is implemented some of the edge cases are not covered because of time constarints
