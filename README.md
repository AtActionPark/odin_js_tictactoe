# [Project: Tic Tac Toe in Javascript](http://www.theodinproject.com/javascript-and-jquery/tic-tac-toe)

If you went through the [Ruby course](/ruby-programming), you had a chance to build Tic Tac Toe to test your OOP skills.  If you did, you'll have a leg up because you'll be building those project now for the browser.

## Tic Tac Toe

Remember Tic Tac Toe? See [Wikipedia](http://en.wikipedia.org/wiki/Tic-tac-toe) if you haven't.  It involves a couple of players, a simple board, checking for victory at each turn... Let's build it!

### Your Task

Build a tic-tac-toe game in the browser where two human players can play against each other.  

1. Set up a Github Repo for this project.  Follow the instructions atop the [Google Homepage project](/web-development-101/html-css) if you need help.
1. Set up a blank HTML document
1. Think about how you would set up the different elements within the game.  What objects and functions will you need? A few minutes of thought can save you from wasting an hour of coding.
2. Create a basic 3x3 board object in Javascript that lists the current item in each space on the board (e.g. "X", "O", or " ").
3. Create a `render()` function which cycles through that board object and creates the appropriate HTML elements.  Style them to look like a real tic-tac-toe board.
4. Build the main game logic (we won't give too many hints here).  When the user clicks on a blank square, it should show the current player's symbol.  This can be triggered by listening for a click event on the appropriate div.  It may be helpful to give each div a `data` attribute or `id` based on its position so you can identify it in your JS code.
3. The game logic should then check whether the game is over -- if any player has achieved victory or if there are no more turns available.  In the event of victory or defeat, display an appropriate message on the screen.
4. Optional -- switch out the "X" and "O" letters with appropriate (or funny) images.
3. Push your solution to Github and post the link to it below.
