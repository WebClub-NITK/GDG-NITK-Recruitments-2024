## Task ID: Chessly

#### `Web Application`, `PWA`

Mentors: [J Hariharan](https://github.com/j-hariharan/) ([+91 8050030224](https://wa.me/8050030224)), [Harshit Gupta](https://github.com/hgupta12/) ([+91 8583905686](https://wa.me/8583905686))

Difficulty: `Medium/Hard`

### Description

Develop a Chess PWA from scratch - allow two players to play on a single, offline, fully-featured chessboard! The game can be played on the same device, and should provide valid move indicators, winner detection, takebacks (undos), reset board, and saving the same on the local device. The user should be able to install the app as a [Progressive Web App](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps) (for bonus feature only).

Follow the steps below to complete this challenge:

1. Build a simple board using HTML and CSS, with 64 alternating black and white squares. Try to insert pieces into these squares.
2. Use ReactJS, Svelte, or any of your favourite frontend framework to manage states and make a working board.
3. Add the [chess.js](https://github.com/jhlywa/chess.js/) engine to manage board state, find valid moves, detect checks and checkmates, piece positions, etc.
4. Add a column for users to see the moves they have made, and undo/takeback the last move.
5. Satisfy the necessary conditions to make the app a PWA, so that the user can add it as an app on their phone or computer.

Bonus Feature ( Optional ):

_Implementing both the bonus features will make the task count as `Hard`, otherwise it will be `Medium`_

1. Animate the pieces when they move from one square to another.
2. Store the board state to [local storage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) so that the user can continue the game later on.

### Note:
- No chess libraries other than **chess.js** should be used to create this platform. 
- You are free to use any generic frontend framework and libraries to achieve state management and animations.
- There is no need to add online multiplayer capability to the platform. Both players will play from the same device turn-wise.


### Useful resources:

- [Progressive Web Apps](https://youtu.be/sFsRylCQblw?si=MEm9xAFhiy1jMWen)
- [chess.js](https://github.com/jhlywa/chess.js/)
- [Introduction to Svelte](https://learn.svelte.dev/tutorial/welcome-to-svelte)
- [ReactJS](https://react.dev/)
- [Add Animations to React](https://www.framer.com/motion/)

---