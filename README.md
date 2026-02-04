# ReadMe
The start of C S 260
# Startup Specification
## Elevator pitch
A classic acrade game remade into an app to be plaed anywhere and anytime. Pinball can be played and anyone can get the rush of dopamine that comes from bright lights, lively noises and the score rising. You can even compare your score to other players and see who is the best. Simply tap to move the paddles and hit the ball to get points.
## Key features 
- A simple start screen with an options for volume included
- Very simple controls where you tap to move the paddles and hit the ball
- A score board that keeps score
- A global leaderboard that can be seen after a round of pinball
## How features are used
- HTML: able to login and create a name that will put a leaderboard all can see
- CSS: allows the score to be counted and the ball to move with reason
- React: allows the login and leaderboard to exist
- Service: allows the leaderboard to update when a new score comes in
- DB: stores leaderboard
- Websocket: changes all players leaderboard when one updates
## Sketches
<img width="3024" height="4032" alt="Unknown png" src="https://github.com/user-attachments/assets/9266be86-82c2-4e4d-8967-1632794a9139" />

## Start up AWS Assignment
- http://mediocorepinball.click/


## HTML deliverable
For this deliverable I built out the structure of my application using HTML.

- I completed the prerequisites for this deliverable (Simon deployed, GitHub link, Git commits)
- HTML pages - Two HTML page that represent the ability to login and vote.
- Proper HTML element usage - I just used div elements for everything.
- Links - The login page automatically links to the voter page. The voter page contains links for every voting choice.
- Text - Each of the voting choices is represented by a textual description.
- 3rd party API placeholder - Placeholder for calls to OpenAI.
- Images - I couldn't figure out how to include an image and so I didn't do this. 😔
- DB/Login - Input box and submit button for login. The voting choices represent data pulled from the database.
- WebSocket - The count of voting results represent the tally of realtime votes.
