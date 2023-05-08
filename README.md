Download Link: https://assignmentchef.com/product/solved-solvedcreate-a-program-that-reads-position-velocity-and-acceleration-data-from-a-file
<br>
For this project, you will create a program that reads position, velocity, and acceleration data from a file, and determines if two objects will collide.Requirements:1. Your solution must include a function that will:a. take four doubles as arguments: initial position, initial velocity, acceleration, and current time.b. return a double: the current position, given by the formula: x = x0 + v0 t + ½ a t22. Your solution must include a function that performs a unit test of that function. It should include 5 test cases, that include at least one zero, and at least one negative value for x0, v0, or a.3. The program will: a) Prompt the user to enter the filename. b) Open the file, or if the file does not exist, print an error message and quit. c) Process each line of the file. The file format is given on the next page. If the program encounters an error, it should print an error message and quit. d) Close the file. e). Starting at a time of 0 seconds, until the maximum requested time is reached, in steps of 1.0 seconds: i)calculate the positions of the two objects. ii) print the time and positions of the objects. iii) if they collide within the tolerance, print a collision message, reporting the time of collision, and exit the program. f) If the objects do not collide withing the specified time frame, report that there was no collision. 4) As always, use good programming style. ( commenting)File format:-Each line of the file contains one item, in a specific order.-The lines are formatted so that the number is ***** followed by comment (which can be ignored by the program).-Sample file (situation1.txt): 100 // max time 0.5 // tolearance 10.0 // x0 for first object 0.0 // vx0 0.0 // ax 0.0 // x0 for second object 1.0 // vx0 0.0 // ax // second object should catch first in 10 seconds! -Another sample file (situation2.txt): 50 // max time 0.5 // tolearance 10.0 // x0 for first object 2.0 // vx0 0.0 // ax 0.0 // x0 for second object 1.0 // vx0 0.0 // ax // will never catch it-Sample files are available on Canvas. You can also create your own test files.-Hints: Be sure to place the input files in the same directory as your cpp file. Remember to tell CLion where to look for input files. To do this: Run → Edit Configurations → Click on the … next to the Working Directory label, and select the directory where the input files are located (and where your cpp is located).-Extra credit: If you receive 90% or above on the above requirements, you can add the capability to use both x and y coordinates to determine collisions. Up to 4% extra credit can be earned.