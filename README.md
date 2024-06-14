# Score-Keeper
HTML (index.html): The HTML document structures the web application using Bulma, a CSS framework. It includes a card with a header, content, and footer. The header contains the title “Score Keeper”. The content displays the scores of two players, which are initially set to 0, and a dropdown select element that allows users to choose the winning score from 3 to 10. The footer contains three buttons: “+1 Player One”, “+1 Player Two”, and “Reset”.

JavaScript (app.js): The JavaScript adds functionality to the web application. It starts by selecting necessary HTML elements using their IDs and initializing score variables (p1Score, p2Score) and a boolean variable isGameOver to keep track of the game state.

Player One Button: When the Player One button is clicked, if the game is not over, Player One’s score is increased by 1. If Player One’s score equals the winning score, the game is set to over, the appropriate classes are added to the score displays to indicate the winner and loser, and the Player One and Player Two buttons are disabled.

Player Two Button: Similar to the Player One button, when the Player Two button is clicked, if the game is not over, Player Two’s score is increased by 1. If Player Two’s score equals the winning score, the game is set to over, the appropriate classes are added to the score displays to indicate the winner and loser, and the Player One and Player Two buttons are disabled.

Winning Score Select: When the selected value changes, the winning score is updated to this value and the game is reset.

Reset Button: When the Reset button is clicked, the reset function is called. This function resets the game by setting isGameOver to false, resetting the scores to 0, updating the score displays, removing the “winner” and “loser” classes from the score displays, and enabling the Player One and Player Two buttons.

This is a simple yet functional score keeping application that could be used for various games. The use of Bulma for styling makes it visually appealing and responsive, and the JavaScript provides the necessary interactivity.
