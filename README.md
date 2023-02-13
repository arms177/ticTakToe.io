# ticTakToe.io

Roadmap of Future Improvements

Feature 1 - I would add a state in the board component that would set a state for the wining combination by ids. The changing of this state would trigger a re-rendering of the squares, if we pass a long the newly created state to the square component, each time it renders it can check to see if it exists and if it does, then check if the id exists on that square and set the className if it contains the id. 

Feature 2 - Create a new state array to hold filled values. Each time a square on click is rendered and updates the board component with the takeTurn method, update this state array and see of all 9 elements have values. If so and checkForWinner returns false, generate an alert message stating the round ended with a draw.
