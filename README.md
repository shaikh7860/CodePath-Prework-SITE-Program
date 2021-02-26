# CodePath-Prework-SITE-Program: Link to my Glitch Project https://glitch.com/edit/#!/light-and-memory-sound-game-ali-shaikh

SITE Pre-Work Submission Name: Ali Shaikh

**If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. YOUR ANSWER HERE]**

-https://www.rapidtables.com/web/css/css-color.html#gray (Assisted me with changing colors)

-https://developer.mozilla.org/en-us/docs/web/javascript/reference/global_objects/math/random (Assisted me with optional step #3)

-https://www.w3schools.com/tags/tag_img.asp (Assisted me with optional step #5)

**What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) [YOUR ANSWER HERE]**

During the process of completing the prework, I came across two different challenges. The first challenge I had was with optional step number two. I was attempting to increase the speed of the clue playback to make the turn harder as it goes on. An issue I came across was that the variable clueHoldTime would not reset with each game. So if I played multiple games in a row, the speed of the clue playback would be too fast to even see the clue. To solve this issue, I printed to the console using console.log() what value the variable clueHoldTime possessed at different points in my program. I saw that the variable clueHoldTime was never being reset to its original value. To address this problem, I reset the variable clueHoldTime to its original value in the functions loseGame() and winGame(). So every time a game ended, the variable clueHoldTime would reset to its original value. Another challenge I came across was with optional step number three. I was attempting to generate a random pattern at the beginning of each game. At first, I was unsure of how I would implement this feature into my game. However, after reading some documentation on the Math.random() function from Mozilla web documents, I was able to determine the best technique to generate a random pattern with the process of trial and error. I decided to create a getRandom() function and then call this function in the startGame() function. I proceeded to call the getRandom() function to generate a random value for each value in the array that created the game’s pattern.

**What questions about web development do you have after completing your submission? (recommended 100 - 300 words) [YOUR ANSWER HERE]**

After completing my submission, I saw that we were able to build and compile this game in Glitch, however, I am curious about the next steps required for this game to be published on the internet. More specifically, I am curious what else is needed to create a game that other people can play online from their own device. In addition, I am curious about how could I create a feature where people would have accounts to keep track of their progress. For example, how do games such as Surviv.io track the data of a user and their progress? What would the process look like to build an option that allows a user to create an account to keep track of their progress?

**If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)**

If I had a few more hours, an additional feature I would like to implement is creating multiple levels based on difficulty. More specifically, I would create an easy, medium, and hard level. As the levels increase in difficulty, the speed that the pattern is played would increase and the length of the pattern would also increase. This would give the opportunity to users to be able to choose how much they would like to challenge themselves. Another feature I would like to implement is to make a more friendly user interface. I would create a separate page for the landing screen when you enter the game, a separate page for the game itself, and a separate page for the exit screen. The beginning screen would include the instructions and a play button. The game screen would include the tiles and a stop button to take you back to the beginning screen. The exit screen would be dependent on if the user wins or loses the game. If the users win the game, they would be redirected to a page with confetti that states “Congrats. You won!” and there would be a button to play again. If the user loses, they would be redirected to a page that states, “You lost. Try again!” and there would be a try again button that would redirect the user to the game page.

![](https://i.imgur.com/sTANgFh.gif)

![](https://i.imgur.com/O44Sz6F.gif)

![](https://i.imgur.com/vUx3YFD.gif)
