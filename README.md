<h2 align="center">Cricket Scoreboard Tracker</h2>

 
  <a href="https://harshjaiswal1302.github.io/Cricket_Scoreboard/"><strong>➥ Live Demo</strong></a>


Cricket Scoreboard Tracker
Overview
The Cricket Scoreboard Tracker is a web application designed to track the progress of a cricket match, ball by ball, over by over. It allows users to input runs, wickets, and extras (such as wide balls and no balls) and keeps track of the score for both teams. The application can declare the winner at the end of the match.

Features
Track balls, runs, wickets, wide balls, and no balls.
Display current score, including total runs and wickets.
Display cumulative score for each over.
Handle two innings and declare the winner.
Clear the scoreboard and reset for a new match.
Store scores locally (using localStorage) to persist data across page reloads.
Installation
To run the Cricket Scoreboard Tracker locally, follow these steps:

Clone the repository:
bash
Copy code
git clone https://github.com/harshjaiswal1302/cricket-scoreboard-tracker.git
Navigate to the project directory:
bash
Copy code
cd cricket-scoreboard-tracker
Open index.html in your web browser to view and use the application.
Usage
Start the Application:

Open index.html in your preferred web browser.
Track the Match:

Use the buttons to input runs, wickets, wide balls, and no balls.
Each button click updates the score and displays the ball's result.
End an Over:

The over ends automatically after 6 valid balls (excluding extras).
The score for the over is displayed in the cumulative score section.
End the Innings:

After 20 overs or 10 wickets, the innings will end automatically.
The application will reset for the second team.
Declare the Winner:

The application will automatically declare the winner based on the scores after the second innings.
File Structure
index.html: The main HTML file that contains the structure of the application.
style.css: The CSS file that styles the application.
script.js: The JavaScript file that contains the logic for tracking and displaying the score.
Scripts
script.js
addBall(type): Adds a ball of a specified type (e.g., run, dot, wicket) to the current over.
addExtraBall(type): Adds an extra ball (wide or no ball) to the current over.
displayCurrentScore(): Displays the current score.
updateTeamScore(): Updates the team score.
endOver(): Ends the current over and prepares for the next one.
endInnings(): Ends the current innings and resets for the next team.
resetForNextTeam(): Resets the scoreboard for the next team.
declareWinner(winningTeam, margin, unit): Declares the winner of the match.
disableButtons(): Disables all input buttons.
showNewOverButton(): Shows the button to start a new over.
resetOver(): Resets the over display for a new over.
updateLocalStorage(): Updates the local storage with the current scores.
addBallAndCheckWinner(type): Adds a ball and checks if there is a winner.
addExtraBallAndCheckWinner(type): Adds an extra ball and checks if there is a winner.
checkWinner(): Checks if there is a winner based on the scores.
Styles
style.css
Basic reset for margins and paddings.
Styling for the main container, buttons, and score displays.
Custom styles for individual balls and buttons, including hover effects and disabled states.
Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.



Feel free to reach out with any questions or feedback. Enjoy tracking your cricket matches with the Cricket Scoreboard Tracker!
