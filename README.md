# CSS & JS Clock
 
Vanilla JavaScript Clock that shows real time with the help of JS Date object.

new Date() creates a new date object with the current date and time.

From there we can get seconds, minutes and hours for each of the 3 hands.

I had to assign a certain number of degrees for each second, minute and hour for a proper rotation.

Since there is a transition style for each hand and I set them vertically (90deg) for zero seconds, the transition caused a small glitch every time the seconds hit zero.

It had to be resolved with an if/else statement within my setDate function, where the transition style is removed for all hands on zero seconds.