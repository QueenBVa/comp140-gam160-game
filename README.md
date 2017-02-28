# comp140-gam160-game
Repository for Assignment 1 of COMP140-GAM160

#The Night Before Deadline
##The Game
It's the night before your final deadline and in a hurry to finish, you've snuck into the studios after hours. However, you're not the only one in a frantic rush to complete your assignment before morning. You must contend with sneaky students trying to copy your work and the only tool at your disposal is a simple light. By turning it on, you scare the students away for a little while and you are able to work faster although don't leave the light on too long - security is roaming around and if they see the light, it's game over.

##Core Mechanics
- Awareness of light management
- Students swarming towards the player
- Security roaming around
- Progress bar fills faster when the light is on

##Goal
The goal of the game is to fill up the progress bar before the time is up, too many enemies swarm the player or being caught by security.

#Controller
##Research
As my game revolves around the use of light, my initial decision for my alternative controller was to use a light switch since it is relatively simple and easy to implement. I conducted research into one button and switch games by using [Shake That Button](http://shakethatbutton.com/) and although I didn't find games that solely used a single switch or button, I found inspiration from similar examples.

Firstly, I looked at their [Catch Me If You Can](http://shakethatbutton.com/catch-me-if-you-can/) game, which features two buttons for each player and to win, the players must utilise fast reactions in order to be the first to press the button that matches the colour of theLED between their hands and catch up to the other player in order to win.

![alt text](http://shakethatbutton.com/wp-content/uploads/2015/12/CatchMeIfYouCan.jpg "Catch Me If You Can")

Another example I looked at was [Beatdown](http://shakethatbutton.com/beatdown/) which features players wearing foam headpieces equipped with buttons that must be struck by the opposing player when they light up.

![alt text](http://shakethatbutton.com/wp-content/uploads/2015/10/Beatdown.png "Beatdown")

The final game I looked at was [Binary Gallows](http://shakethatbutton.com/binary-gallows/) and although it features the use of multiple buttons in a Hangman style game, though they can also use a switch to submit their word or check past letters used.

![alt text](http://shakethatbutton.com/wp-content/uploads/2015/07/Binary-gallows1.jpg "Binary Gallows")

As a result, I have concluded that while just using a light switch is a good idea as it keeps the game relatively simple, it would be plain and unintuitive and so my controller would be mounted on a board which also has multiple LEDs to give feedback such as proximity of the security guard enemy as well as the completion of the progress bar.
