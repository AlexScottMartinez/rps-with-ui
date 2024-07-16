# rps-with-ui
Rock Paper Scissors with GUI
   - Similar to the previous project of 'rps', but this one will have a graphical user interface (gui) to it.

## In our UI, the player should be able to play the game by clicking on buttons rather than typing their answer in a prompt.
1. For now, remove the logic that plays exactly five rounds.
2. Create three buttons, one for each selection. Add an event listener to the buttons that call your `playRound` function with the correct `playerSelection` every time a button is clicked. (you can keep the `console.log`s for this step)
3. Add a `div` for displaying results and change all of your `console.log`s into DOM methods.
4. Display the running score, and announce a winner of the game once one player reaches 5 points.
5. You will likely have to refactor (rework/rewrite) your original code to make it work for this. That’s OK! Reworking old code is an important part of a programmer’s life.
