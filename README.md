# Python Project = Tic Tac Toe

How I broke it down,
Display something visual to the user
Let the user update through an interaction
Update variables in the program
Display visual updates.


First off, make sure you understand the project scope. What needs to happen?

We need to print a board.
Take in player input.
Place their input on the board.
Check if the game is won, tied, lost, or ongoing.
Repeat c and d until the game has been won or tied.
Ask if players want to play again.

Step one

Create a board with a clear a output function followed by a test board as seen.

![image](https://github.com/JimSchell/Python-Projects/assets/165466444/83b89d29-3605-474d-bdb6-a7aca777623d)

Next step was to write a function that can take in a players input and assign their choice as ‘X’ or ‘O’, while also creating a while loop to continuously ask until a correct answer is input. This method will also allow my to use tuple unpacking. 

![image](https://github.com/JimSchell/Python-Projects/assets/165466444/2ba419da-262e-4cb7-bf8c-70189aa30142)

Next step was write a function that takes in the board list object, a marker ‘X’ or ‘O’ and a desired position (1-9) and assign it to the board.

![image](https://github.com/JimSchell/Python-Projects/assets/165466444/ae86aa71-04ad-4ad8-a7f3-9fd286318656)

Next step was to identify the winner, so this needed to understand what it takes to win tic tac toe.
So there are four possible outcomes, 
Check – All the rows and check if they share the same marker
Check – All the Columns if they have the same marker
Check – both diagonals if they have the same marker

![image](https://github.com/JimSchell/Python-Projects/assets/165466444/7290f03e-59c6-49d2-bf14-6d36277cd299)

Next stage was to write a function to determine who would go first, using a random integer function.

![image](https://github.com/JimSchell/Python-Projects/assets/165466444/4f0a8191-f145-4425-a533-1ab1f5ed7b76)

Next step is to determine two things, firstly, if there is a free space on the board and secondly to check when the board is full using a Boolean return.

![image](https://github.com/JimSchell/Python-Projects/assets/165466444/f5fde9df-9566-4f42-81e3-ea4ddadad56b)

Next step was to write a function asking for a players next move while checking on the previous function making sure the space is still free.

![image](https://github.com/JimSchell/Python-Projects/assets/165466444/de767d48-c6cf-4222-a962-06c76202cd70)

After this I wrote a replay function asking if  the player wants to play again and return it in a Boolean.

![image](https://github.com/JimSchell/Python-Projects/assets/165466444/c96407ce-e436-43b7-8971-84b588eae438)

The last step was the hardest, this is where all the code had to come together and I used while loops to keep the game rotating. 

![image](https://github.com/JimSchell/Python-Projects/assets/165466444/732530c9-6667-4db0-848f-9a2566c53096)
![image](https://github.com/JimSchell/Python-Projects/assets/165466444/f9a97e68-829f-43e9-8a76-2d3a81d673b4)
![image](https://github.com/JimSchell/Python-Projects/assets/165466444/40b7f3f5-9581-4181-85e1-67a0f1ebd2bc)









