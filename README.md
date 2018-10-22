# Slot Machine Project
This project is a simple slot machine that individually stops each reels and allows you to place bets.

# How Its Made
**Tech Used:** HTML5, CSS3, Javascript

This application is built with an inital balance of 100 coins for the user to start with. The slot machine will not work unless a user has enter a maximum or minimum bet. Once all conditions are met, our function will call on all three functions that start our rotation that will randomly select an image source from the global array and sets the image path to the src attribute each iteration. Each function running to randomly set each image path has a unqiue interval id. When the stop button are clicked, the function called on clears each respectively interval, sets our local variable to true and runs our condition to check if al three reels have stopped. If the condition is meet and true, the winning condition function is called and checks if the image src is the same for all three reels. If true then the user wins the pot and a message is displayed, else the pot is set back to 0 and a losing message is displayed.

## Optimization

They are too many local variables and too many functions that run the same operation. Looking for dryer code methods.

## Lesson Learned

Learning how to call on our interval method that runs a function inside its parameter and each interval running has a unqiue id that can be cleared by the clear interval method to stop each reel individual.

