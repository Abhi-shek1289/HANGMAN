Hangman - A Classic Word-Guessing Game 🎯
Hangman is a fun and interactive JavaScript-based word-guessing game where players attempt to reveal a hidden word by selecting letters. With each incorrect guess, a part of the stick figure is drawn on the canvas. The game ends when the word is guessed correctly or when the hangman is fully drawn.

🚀 Features
✅ Multiple Categories – Choose words from Fruits, Animals, and Countries
✅ Dynamic Word Generation – Randomly selects a word from the chosen category
✅ User-Friendly Interface – Intuitive buttons for letter selection
✅ Canvas Drawing – A stick figure is drawn for incorrect guesses
✅ Win/Lose Messages – Shows whether the player wins or loses
✅ New Game Button – Easily restart a new round
✅ Responsive Design – Works well on both desktop and mobile devices

📂 Project Structure
bash
Copy
Edit
Hangman/
│── index.html      # Main HTML structure
│── style.css       # CSS for styling the game
│── script.js       # JavaScript logic for game functionality
│── README.md       # Project documentation
📜 How It Works
1️⃣ Game Initialization
The game starts by displaying three category buttons (Fruits, Animals, Countries).
Once a category is selected, a random word from that category is chosen.
The word is displayed as underscores (_ _ _ _) representing each letter.
A keyboard with A-Z buttons appears for letter selection.
2️⃣ Gameplay Mechanics
The player clicks a letter to guess.
If the letter exists in the word, it replaces the underscore.
If the letter is incorrect, a part of the Hangman is drawn on the canvas.
The game continues until either:
The player guesses all letters correctly → Victory! 🎉
The Hangman is fully drawn (6 mistakes) → Game Over 😢
3️⃣ End of the Game
Winning Message: If the player guesses the word, a "You Win!!" message is displayed.
Losing Message: If the hangman is completed, the "You Lose!!" message appears along with the correct word.
The "New Game" button allows the player to start a fresh round.
📜 Code Breakdown
1️⃣ HTML (index.html)
The HTML structure consists of:

A container for the category selection buttons.
A letter selection keyboard (A-Z).
A user input section to display the guessed word.
A canvas for drawing the Hangman.
A "New Game" popup for restarting.
2️⃣ CSS (style.css)
The CSS provides:

A modern, clean UI with a yellow theme.
Stylish buttons for categories and letters.
Animations and transitions for smooth interactions.
Responsive design, ensuring it works well on different screen sizes.
3️⃣ JavaScript (script.js)

🎨 Future Improvements
🔹 Sound Effects for correct and incorrect guesses.
🔹 Hint System for players to get a clue.
🔹 High Score Tracker for multiple rounds.
🔹 More Categories (Movies, Cities, Famous People).

💻 Technologies Used
HTML for the game structure.
CSS for styling and responsiveness.
JavaScript for the game logic and interactivity.
📜 Conclusion
This Hangman Game is a fun and interactive way to challenge your vocabulary and problem-solving skills. Feel free to contribute, improve, and expand the game! 🎉🚀
