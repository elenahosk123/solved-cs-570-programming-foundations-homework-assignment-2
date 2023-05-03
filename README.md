Download Link: https://assignmentchef.com/product/solved-cs-570-programming-foundations-homework-assignment-2
<br>
<strong>Compiling and running your programs from the command-line. </strong>

In this assignment we will practice compiling and running our programs on the command-line.  By now, you should have downloaded and installed the <em>Java Standard Edition Development Kit</em> (JDK) on your computer.

JDK does not provide an editor so you will need to type your programs in a text editor (for example NotePad in Windows or TextEdit in OS X).  Once you have typed your code and saved your file with .java extension you will need to bring up and work in a Command Prompt (Windows), Terminal (OS X) or shell (Linux) window.

You will use the javac and java commands to compile and execute your programs, as we did in class.

<h1>Windows users</h1>

Here is a video tutorial that will walk you through the steps you need to follow:  <a href="https://www.youtube.com/watch?v=vobqUcnHAM8">https://www.youtube.com/watch?v=vobqUcnHAM8</a>




If you when you try to compile your program you get the error: “javac not recognized as internal or external command…..,” that means that you need to edit the PATH environment variable.  Here is a quick tutorial on how to do so: <a href="https://www.youtube.com/watch?v=paLQCfC3Ff8">https://www.youtube.com/watch?v=paLQCfC3Ff8</a>




<h1>Mac users</h1>

Here is a video tutorial that will walk you through the steps you need to follow: <a href="https://www.youtube.com/watch?v=hzQWs4O6G7A">https://www.youtube.com/watch?v=hzQWs4O6G7A</a>




<h1>Linux users</h1>

Here is a page that will walk you through the steps you need to follow:

<a href="http://introcs.cs.princeton.edu/java/15inout/linux-cmd.html">http://introcs.cs.princeton.edu/java/15inout/linux</a><a href="http://introcs.cs.princeton.edu/java/15inout/linux-cmd.html">–</a><a href="http://introcs.cs.princeton.edu/java/15inout/linux-cmd.html">cmd.html</a>

<strong> </strong>

<strong>Program 1 (50 points): </strong>




Popeye the Sailor wants to sail from Bluto’s Marina to Whimpy’s Hamburger Haven, where he will dine with his girlfriend Olive Oyl. The one-way distance for this trip is 18 Nautical Miles. Popeye wants to know how far that is in “regular miles.” A Nautical Mile is equal 1.1508 regular miles. Popeye also wants to know how long it will take to travel this distance. Popeye’s boat travels at a top speed of 5.8 Knots (Nautical Miles per hour) and an average speed of 4 Knots.




Write a program to answer Popeye’s questions. In your program, you should have a variable for the distance in nautical miles set to 18, a variable for the top speed set to 5.8, and a variable for the average speed set to 4.  Your program should compute and display the distance in regular miles, the estimated travel time in hours at top speed and the estimated travel time in hours at average speed.




Here is a sample run:




<strong>Program 2 (50 points): </strong>




Write a program that plays the following interactive “magician’s” game.

Your program should prompt a player for a four-digit number and permute

(scramble) the digits to form two numbers. For example, if a player enters 1267 then the two permutations might be 2176 and 7612. Your program should display these two numbers. Next, instruct the player to:




<ol>

 <li>Calculate the positive difference between the two numbers,</li>

 <li>Secretly choose any digit in the difference except a zero, and</li>

 <li>Enter the remaining three digits in any order.</li>

</ol>




Your program will dazzle the player by supplying the secret digit.




Here is a sample run:










<strong><em>Hint</em></strong>: The sum of the digits in the difference must be a multiple of 9. Find the remainder when the sum of those three digits is divided by 9.  That remainder plus the missing digit adds up to 9.

<strong> </strong>

<strong> </strong>

<strong>Note: </strong>




Please make sure to submit well-written programs for these programming tasks. Good identifier names, useful comments, indentation, and spacing will be some of the criteria that will be used when grading this assignment.





