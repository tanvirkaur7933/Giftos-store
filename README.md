# Giftos-Winipeg
Week 1: HTML Basics

Day 1: Introduction to HTML

• Topics Covered: What is HTML? Basic structure of an HTML document.

• Activities: Created a simple HTML page with headings, paragraphs, and lists.

• Reflection: I learned how to structure a webpage using tags like <html>, <head>, and <body>.

Day 2: HTML Elements

• Topics Covered: Common HTML elements (images, links, tables).

• Activities: Added images and hyperlinks to my HTML page.

Day 3: Forms in HTML

• Topics Covered: Creating forms and input elements.

• Activities: Built a contact form with text inputs, radio buttons, and a submit button.

• Reflection: Forms are essential for user interaction; I need to learn more about form validation.
Day 4: Semantic HTML

• Topics Covered: Importance of semantic elements (<header>, <footer>, <article>, etc.).

• Activities: Refactored my previous HTML page to use semantic tags.

• Reflection: Using semantic tags improves accessibility and SEO.

Day 5: Multimedia in HTML

• Topics Covered: Embedding audio and video.

• Activities: Added a video and audio player to my webpage.

• Reflection: Multimedia can make websites more engaging.

Day 6: Review and Practice

• Activities: Reviewed all topics covered this week and practiced building a personal webpage.

Day 7: Project Day

• Project: Created a simple portfolio page using what I learned in HTML.

Week 2: CSS Basics

Day 8: Introduction to CSS

• Topics Covered: What is CSS? How to link CSS to HTML.

• Activities: Styled my HTML page with basic CSS.

Day 9: CSS Selectors

• Topics Covered: Different types of selectors (class, ID, element).

• Activities: Experimented with various selectors to style elements differently.
Day 10: Box Model

• Topics Covered: Understanding margins, borders, padding, and content.

• Activities: Adjusted the layout of my page using the box model.

Day 11: Flexbox

• Topics Covered: Introduction to Flexbox for layout design.

• Activities: Created a responsive navigation bar using Flexbox.

• Reflection: Flexbox simplifies complex layouts; I need more practice.

Day 12: CSS Grid

• Topics Covered: Introduction to CSS Grid for two-dimensional layouts.

• Activities: Built a grid layout for my portfolio page.
Week 3: Php Basics
. Installation

To get started with PHP, you need to have a server environment. You can set up PHP on your local machine using software stacks like:

• XAMPP: Includes Apache, MySQL, and PHP.

• MAMP: Mac-specific, includes Apache, MySQL, and PHP.

• WAMP: Windows-specific, includes Apache, MySQL, and PHP.

. Basic Syntax

• PHP code is embedded in HTML using the <?php ... ?> tags.
  
<?php
echo "Hello, World!";
?>


• The echo statement is used to output text to the browser.

3. Variables

• Variables in PHP start with the $ sign followed by the variable name.

$name = "John";
$age = 30;
echo "My name is $name and I am $age years old.";
4. Data Types

PHP supports several data types:

• String: Text enclosed in quotes.

• Integer: Whole numbers.

• Float: Decimal numbers.

• Boolean: true or false.

• Array: A collection of values.

• Object: An instance of a class.

• NULL: A variable with no value.

5. Control Structures

Conditional Statements

if ($age >= 18) {
    echo "You are an adult.";
} else {
    echo "You are a minor.";
}
Loops

• For Loop

for ($i = 0; $i < 5; $i++) {
    echo $i;
}


• While Loop

$i = 0;
while ($i < 5) {
    echo $i;
    $i++;
}
week-4
6. Functions

Functions are reusable blocks of code. You can define a function using the function keyword.

function greet($name) {
    return "Hello, $name!";
}

echo greet("Alice");


7. Arrays

PHP supports both indexed and associative arrays.

Indexed Array

$fruits = array("Apple", "Banana", "Cherry");
echo $fruits[1]; // Outputs: Banana


Associative Array
$person = array("name" => "John", "age" => 30);
echo $person["name"]; // Outputs: John


▎8. Superglobals

PHP has several built-in superglobal arrays that are accessible from any scope:

• $_GET: Used to collect data sent in the URL query string.

• $_POST: Used to collect data sent via HTTP POST method.

• $_SESSION: Used to store session variables.

• $_COOKIE: Used to retrieve cookie variables.

9. File Handling

PHP provides functions to handle files, such as reading from and writing to files.

$file = fopen("example.txt", "w");
fwrite($file, "Hello, World!");
fclose($file);


10. Database Interaction

PHP often interacts with databases using extensions like MySQLi or PDO.

$mysqli = new mysqli("localhost", "user", "password", "database");
 #Check connection
if ($mysqli->connect_error) {
    die("Connection failed: " . $mysqli->connect_error);
}

$result = $mysqli->query("SELECT * FROM users");
while ($row = $result->fetch_assoc()) {
    echo $row['username'];
}
$mysqli->close();





























   
 
