# Blackjack
https://blackjackwastaken.netlify.app/

A classic Blackjack (21) game built with HTML, CSS, and vanilla JavaScript. This project provides a clean, modern user interface and a fully functional game logic where the player competes against an automated dealer.

<img width="1918" height="805" alt="image" src="https://github.com/user-attachments/assets/2c547aa2-0623-4ac7-980f-27371d0fac13" />


***

## About The Project

This project is a web-based implementation of the popular casino card game, Blackjack. The goal is simple: have a hand value closer to 21 than the dealer's, without going over. It was built with fundamental web technologies, making it a great example of DOM manipulation and game logic implementation in JavaScript.

***

## Features

- **Classic Blackjack Rules**: Player vs. automated dealer.
- **Interactive UI**: Clean and intuitive interface for placing bets and making moves.
- **Hit & Stand**: Players can choose to "hit" (take another card) or "stand" (keep their current hand).
- **Automated Dealer**: The dealer plays according to standard casino rules (hits on 16 or less, stands on 17 or more).
- **Win/Loss/Push Logic**: The game automatically determines the outcome and displays the result.
- **Play Again**: Seamlessly start a new round after a game ends.
- **Responsive Design**: The layout is designed to be usable on various screen sizes.

***

## Getting Started

To get a local copy up and running, follow these simple steps.

### Installation

1.  **Clone the repo (or download the files)**
    ```sh
    git clone [https://github.com/leoperator/blackjack.git](https://github.com/leoperator/blackjack.git)
    ```
2.  **Navigate to the project directory**

3.  **Open `index.html` in your browser**

***

## File Structure

The project is organized into the following files and directories:

/|-- index.html      # The main HTML file for the game structure.|-- styles.css      # The CSS file for all styling and layout.|-- script.js       # The JavaScript file containing all game logic.|-- /cards/         # Directory containing card images (e.g., 'A-S.png', 'K-H.png', 'BACK.png').
-   **`index.html`**: Contains the semantic structure of the web page, including containers for the dealer's hand, player's hand, and action buttons.
-   **`styles.css`**: Defines the visual appearance of the game, including the "casino felt" background, card styling, button design, and overall layout.
-   **`script.js`**: This is the core of the game. It handles:
    -   Building and shuffling the deck.
    -   Dealing cards to the player and dealer.
    -   Calculating hand values (including Ace logic).
    -   Handling player actions (`hit` and `stand`).
    -   Executing the dealer's turn.
    -   Determining the game's outcome.
-   **`cards/`**: This folder must contain 53 images: one for each card in a standard deck (e.g., `2-C.png` for the 2 of Clubs) and one for the back of the cards (`BACK.png`).

***

## How to Play

1.  The game starts automatically when the page loads. The player is dealt two cards face up, and the dealer is dealt one card face up and one card face down.
2.  Your current hand value is displayed below your cards.
3.  You have two options:
    -   **Hit**: Take another card to increase your hand's value. Be careful not to go over 21!
    -   **Stand**: Keep your current hand and end your turn.
4.  If your hand value exceeds 21, you "bust" and lose the round immediately.
5.  Once you stand, the dealer reveals their face-down card and will hit until their hand value is 17 or higher.
6.  The winner is determined:
    -   If the dealer busts, you win.
    -   If your hand is closer to 21 than the dealer's, you win.
    -   If the dealer's hand is closer to 21, you lose.
    -   If you and the dealer have the same hand value, it's a "push" (a tie).
7.  Click the **"Play Again"** button to start a new round.

***

## Future Improvements

-   [ ] **Betting System**: Implement a system for players to bet chips.
-   [ ] **Double Down & Split**: Add advanced Blackjack moves.
-   [ ] **Animations**: Add smooth animations for card dealing and flipping.
***
