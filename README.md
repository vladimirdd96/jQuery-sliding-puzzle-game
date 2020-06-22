# jQuery-sliding-puzzle-game
The idea is this,
We will make 15 divas, dividing the photo into 15 equal pieces. I use 1 whole photo divided into 2 equal parts. To get the given image (on the right) I assemble the two puzzles, which complement each other.
We will use the given image as a background, but with different positions, keeping in mind that one div must be left blank.
We will then simulate the required number of random clicks to move each div to complete state(it is possible to return some of them to the original position)
When we click on a div, it will check if there is an empty div
• On the left
• On the right
•	On top
• Below,
and if there is an empty one, they will just swap places.
(In more detail: 
When we find the row and column, on each selected piece and on the blank too, we can check if something still needs to be moved. The only way to move the 2 pieces is possible if they are in the same row or column.)
