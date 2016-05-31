# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](http://searchsoftwarequality.techtarget.com/definition/user-story)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to these in this file via a pull request.

-   A wireframe of what your game project will look like.
I created a wireframe via Balsamiq
-   The data structure you plan to use.
I plan to have a file that updates an array with each move made during a game,
that can also track multiple games (including wins/losses/ties)
-   How you will take the markup of the game board and represent it in JS
I will have a table where each cell can be accessed as a number in an array,
I will use jQuery to change the visual appearance of the cell when someone
selects it during game play.
-   How you plan to approach this project.
I plan to start with the basic HTML, then start to style it a bit with CSS, then
plot out my game logic in JS and use AJAX to connect with the back end, and add
in jQuery to manipulate the DOM.
-   4-8 user stories for your game project.
As a User I want to create an account so that I can play Tic Tac Toe.
As a User I want to select a square to place my token, and I do not want
my opponent to be able to override this so that we can play Tic Tac Toe.
As a User I want to be able to view all of the spaces on the board that are
currently open so that I can choose where to make my next move.
As a User I want to know when me or my opponent has won the game so that I can
start another one.
-   How you plan to keep your code modular.
I plan to build separate files for HTML, CSS, my game logic in JS, an events
file to write my event handlers, an api file to hold my AJAX requests and a UI
file that determines what happens to the DOM once my AJAX requests are complete.
-   What creative spin will you add to your project.
I want to allow my Users to select what image they will use as their token
when playing the game!
-   How you will use version control to backup / track your project.
I will make many small commits as I progress with the project so I can always
revert back if something goes wrong.
-   Do you plan to attempt any of the bonuses.
I plan to attempt to allow two users on separate devices to play the game.
