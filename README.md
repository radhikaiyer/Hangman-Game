Overview

In this assignment, I created Hangman. This app will run in the browser, and feature dynamically updated HTML and CSS powered by JavaScript code.


Before You Begin


Create a new GitHub repo called Hangman-Game, in accordance with the assignment you choose to complete. Then, clone it to your computer.
Inside your local git repository, create an index.html. For this assignment, we've given you a starter template in the 'Unsolved' folder.
While still in your local git repo, create a directory called assets.
cd your way into the assets folder, then make three additional folders: javascript, css and images.



In the javascript folder, make a file called game.js. Use the src attribute of the script tag to link to this file, rather than embedding the code directly in your HTML document.
In the css folder, make a file called style.css.
Also in the css folder, make a file called reset.css. Paste into it the code from the Meyerweb reset stylesheet. If you opt to use Bootstrap instead of writing your own CSS, skip this step, and simply include a link to Bootstrap via CDN.
In the images folder, save whatever images you plan on using.




Choose a theme for your game! In the demo, we picked an 80s theme: 80s questions, 80s sound and an 80s aesthetic. You can choose any subject for your theme, though so be creative!
Use key events to listen for the letters that your players will type.
Display the following on the page:
Press any key to get started!
Wins: (# of times user guessed the word correctly).



If the word is madonna, display it like this when the game starts: _ _ _ _ _ _ _.
As the user guesses the correct letters, reveal them: m a d o _  _ a.



Number of Guesses Remaining: (# of guesses remaining for the user).
Letters Already Guessed: (Letters the user has guessed, displayed like L Z Y H).
After the user wins/loses the game should automatically choose another word and make the user play it.



