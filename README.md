Download Link: https://assignmentchef.com/product/solved-assignment-2-cse110
<br>
<em>Topics</em>

<ul>

 <li>To declare and use variables</li>

 <li>Arithmetic Expressions</li>

 <li>Using the Scanner class to get the input from the user</li>

 <li>Use selection statements to find a maximum value</li>

</ul>

<em>Coding Guidelines:</em>

<ul>

 <li>Give identifiers semantic meaning and make them easy to read (examples numStudents, grossPay, etc).</li>

 <li>Keep identifiers to a reasonably short length.</li>

 <li>User upper case for constants. Use title case (first letter is upper case) for classes. Use lower case with uppercase word separators for all other identifiers (variables, methods, objects).</li>

 <li>Use tabs or spaces to indent code within blocks (code surrounded by braces). This includes classes, methods, and code associated with ifs, switches and loops. Be consistent with the number of spaces or tabs that you use to indent.</li>

 <li>Use white space to make your program more readable.</li>

</ul>

<em>Important Note</em>

All submitted assignments must begin with the descriptive comment block. To avoid losing trivial points, make sure this comment header is included in every assignment you submit, and that it is updated accordingly from assignment to assignment. Reasonably good amount of comments should be added in your program so that it is easy for other people to understand it. Please see the comment style in the textbook.

<em>Part #1: Written Exercises (5 pts)</em>

<ol>

 <li>(2 pts.) What do the following expressions evaluate to in Java given int x = 3, y = 6;

  <ol>

   <li>x == y / 2</li>

   <li>x % 2 == 0 || y % 2 != 0</li>

   <li>x – y &lt; 0 &amp;&amp; !(x &gt;= y)</li>

   <li>x + 6 != y || x / y &lt;= 0</li>

  </ol></li>

 <li>(1 pt.) Write statements to prompt for and read the user?s full name using a Scanner</li>

 <li>(2 pts.) What does the following statement sequence print? (page 63)</li>

</ol>

String str = “Harry”; int n = str.length();

String mystery = str.substring(0,1) + str.substring(n-1, n);

System.out.println(mystery);

<em>Part #2 – Programming (15 pts)</em>

<em>Overview</em>

Write a complete Java program in a source file to be named Assignment2.java. The program prints out the following menu to a user, using ’t’ (tabs) and ’
’ (newline), and print or println methods of System.out:

Welcome to the In-N-Out Burger menu:

——————————————————

Hamburger $2.75

Cheeseburger $3.25

French Fries $2.50

Shake &amp; Beverage: $1.50

Then prompts the user:

How many hamburger(s) would you like to buy? and read in the number. Then prompts the user:

<h1><a name="_Toc536210993"></a>How many cheeseburger(s) would you like to buy?</h1>

and read in the number. Then prompts the user:

<h1><a name="_Toc536210994"></a>How many French fries would you like to buy?</h1>

and read in the number. Then prompts the user:

<h1><a name="_Toc536210995"></a>How many drinks would you like to buy?</h1>

and read in the number. Then the program computes and prints the following:

<ul>

 <li>The total cost for the hamburger(s)</li>

 <li>The total cost for the cheeseburger(s)</li>

 <li>The total cost for fries</li>

 <li>The total cost for drink(s)</li>

 <li>Which item had the highest total cost</li>

 <li>The total cost for the order</li>

 <li>The total number of hamburgers, cheeseburgers, French fries, and drinks ordered</li>

</ul>

<strong>Hint</strong>

One way to find which item has the highest total cost is to create a String variable to hold the name of that item and then use comparisons to check if the cost of hamburgers is greater than the other prices (using &amp;&amp;) then set the String to “hamburgers”. You would need a similar check to see if the other total costs are the largest. Then you could output the highest String when needed (see sample output below).

<strong>To earn full points on this assignment you will have to:</strong>

<ul>

 <li>Use constant doubles for price of a Hamburgers, Cheeseburger, French Fries and Drinks.

  <ul>

   <li>For example, you would have to use a constant for the price of hamburgers similar to</li>

  </ul></li>

</ul>

∗ final double HAMBURGER_PRICE = 2.75;

<ul>

 <li>and then use that constant where needed in the program. Be sure to follow naming conventions (ALL CAPS) when naming constants.</li>

</ul>

<ul>

 <li>Use the NumberFormat class to format dollar amounts to be printed.

  <ul>

   <li>The NumberFormat class is defined in (and needs to be imported from) the text.NumberFormat package.</li>

   <li>See the example video of java posted on the course website under “Week 1” → “Lectures: Chapter 2” → “NumberFormat Example”).</li>

  </ul></li>

</ul>

<em>Output Sample 1</em>

(user input is in bold)

Welcome to the In-N-Out Menu:

———————————————–

Hamburger: $2.75

Cheeseburger: $3.25

French Fries: $2.50

Shakes &amp; Beverages: $1.50

How many hamburger(s) would you like to buy? <strong>3</strong>

How many cheeseburger(s) would you like to buy? <strong>4</strong>

How many French fries would you like to buy? <strong>3</strong>

How many drink(s) would you like to buy? <strong>3</strong>

Total cost for the hamburger(s): $8.25

Total cost for the cheeseburger(s): $13.00

Total cost for the fries: $7.50

Total cost for the drink(s): $4.50

The cheeseburgers had the highest total cost.

Total cost for your order: $33.25

Total number of item(s) ordered: 13

<em>Output Sample 2</em>

(user input is in bold)

Welcome to the In-N-Out Menu: ———————————————–

Hamburger: $2.75

Cheeseburger: $3.25

French Fries: $2.50

Shakes &amp; Beverages: $1.50

How many hamburger(s) would you like to buy? <strong>2</strong>

<a href="#_Toc536210993">How many cheeseburger(s) would you like to buy?  2</a>

<a href="#_Toc536210994">How many French fries would you like to buy?  2</a>

<a href="#_Toc536210995">How many drinks would you like to buy?  2</a>




Total cost for the hamburger(s): $5.50

Total cost for the cheeseburger(s): $3.25

Total cost for the fries: $7.50 Total cost for the drink(s): $4.50 The fries had the highest total cost.

Total cost for your order: $20.75

Total number of item(s) ordered: 9


