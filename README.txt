Animate-Your-Name
==================
Tạo tên sinh động với code JavaScript.


In our code, we're using document.write() simply to display the string of your name in the preview window.
The important stuff is inside the parentheses, so let's just focus on that.
To discover the length of a string, write the string within quotes.
Then write a period (full stop) and the word length like this:  
  *Example:
    "Ryan".length.
   
Great job! Now, let's do some math. You can add, subtract, multiply, and divide numbers in JavaScript, like this:
    Addition: 2 + 3
    Subtraction: 6 - 3
    Multiplication: 3 * 4
    Division: 10 / 5

Booleans
Nice job! Next let's look at Boolean expressions. A Boolean expression is either true or false.
  *For example, comparing two numbers returns a true or false result:
    23 > 10 is true
    5 < 4 is false


What we'll do
In the previous section, we started learning the JavaScript programming language. So far we've used:
    strings (e.g. "dogs go woof!")
    numbers (e.g. 4, 10)
    booleans (e.g. false, 5 > 4)
In this section, we'll write a program to animate your name.
Move your mouse over "Codecademy" in the preview window.

You're going to make this!


*Code HTML:
<!DOCTYPE html>
<html>
  <head>
    <script type="text/javascript" src="//code.jquery.com/jquery-1.10.2.min.js"></script>
    <script type="text/javascript" src="http://s3.amazonaws.com/codecademy-content/courses/hour-of-code/js/alphabet.js"></script>
  </head>
  <body>
    <canvas id="myCanvas"></canvas>
    <script type="text/javascript" src="http://s3.amazonaws.com/codecademy-content/courses/hour-of-code/js/bubbles.js"></script>
    <script type="text/javascript" src="main.js"></script>
  </body>
</html>
