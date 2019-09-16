### GRADED 8/24: See comments below and ask for clarification as needed.
* The displayed game resembles some aspects of the examples, however in your CSS you are styling  the play area using CSS FlexBox *not* Grid. We did not cover FlexBox in class. 
* Your HTML is using inline 'onclick' handlers as opposed to addeventListener() and are pointing to JavaScript function 'myfunction' which does not exist in your JavaScript.
* Your JavaScript is based totally on jQuery, including jQuery features we didn't cover in class, and reference IDs of elements that do not appear in your HTML (#counter, #update). This suggests that some of the code may have come from a similar program(s) found online. Referring to other's code is fine, as long as you understand their approach and then code up your own version that you fully understand. However, please refrain from just copying in code directly from external sources. The more code you personally write, the better you get at it. Copying in existing code doesn't teach you anything, even if it happens to work, so resist the urge to do so.

# frontend-halfDay1_b

### Button Clicking Game

Create a two player game similar to the image attached. When one player takes the lead, show that in the middle area.

<strong>Notes:</strong>
* PUT COMMENTS IN YOUR JAVASCRIPT
* The bottom portion of the attached image is the bonus.
* The general sizes of each button is below
* * Player Score font size is 200px
* * Button font size is 48px
* * Winner area font size is 24px
* * Footer font size is 24px

#### Step 1: (1 point)
Create an HTML and use CSS Grid to create a page similar to step1.png. If you are still working on this step after 1:45p ask for help!!!

#### Step 2: (1 point)
Create an HTML and use CSS Grid to create a page similar to step2.png.

#### Step 3: (2 points)
Create an HTML and use CSS Grid to create a page similar to step3.png.

#### Step 4: (2 points)
In a JavaScript file, once the P1 button is pressed increase the text above it by 1. Do the same for P2.

#### Step 5: (3 points)
Create a function that will print update the winner label if one player has a higher score than the other. If the have the same score, make the label say "Tied".

#### Step 6: (1 point)
Figure out where to put the function.

<hr>

## CHALLENGES

### Challenge1
Once a player reaches 15, alert the winner then restart the game.

### Challenge2
Toggle background colors on and off.

### Challenge3
Make keyboard and mouse options. Disable and stop events from counting the points when the option is not chosen. 
