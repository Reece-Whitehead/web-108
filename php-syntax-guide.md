# Single Line Comment
// This is how you write a single-line comment

# Multi-Line Comment
/*
   This is how you
   write a multi-line comment
*/

# PHP Variables
$variable_name = "Variable information goes here"; // Don't forget the semicolon at the end

# PHP Echo / Print
echo "Place what you want to see printed to the screen here";
print "Place what you want to see printed to your screen here";
// Remember that echo has no value, whereas print always returns 1
// Echo can be used with multiple parameters separated by commas, and print can only take 1

# PHP Data Types
PHP supports several data types, including:
- Integer: $integerVar = 42;
- Float: $floatVar = 3.14;
- String: $stringVar = "Hello, PHP!";
- Boolean: $boolVar = true;
- Array: $colors = array("red", "green", "blue");
- Object: $person = array(
    "name" => "John",
    "age" => 25,
    "city" => "New York"
);
- NULL: $nullVar = null;

# PHP Strings
// Strings are essentially a bunch of letters put together; they can be completely arbitrary but are typically used to write words.
$stringName = "This is a string, this is also a string -> thfgshfufgd";
// Take note of the quotations surrounding the string.

# PHP Numbers
In PHP, you can use both regular integers and floats. They can be stored like this:
$integer = 21; $float = 43.89;
// Notice that there are no quotes around numbers; if we added quotes, we would be creating strings.

# PHP Constants
Constants are similar to variables, except once declared, they cannot be changed. This is to ensure you don't accidentally redefine something you want to stay the same throughout.
define("special_Number", 22);
// If we echoed special_Number, it would return 22.

# PHP Operators
Much like regular math, PHP supports many operators like arithmetic, comparison, and logical operators.
$a = 5;
$b = 10;
$sum = $a + $b; // Addition
$diff = $a - $b; // Subtraction
$product = $a * $b; // Multiplication
$quotient = $a / $b; // Division

# PHP if & else & elseif
We can use conditional statements to perform different actions when different conditions are met or not met. They might look like this:
$number = 15;
if ($number > 10) {
    echo "This number is larger than 10";
} elseif ($number == 10) {
    echo "The number is equal to 10";
} else {
    echo "The number is less than 10";
}
// By using conditional statements like above, we can decide whether something meets our condition and perform an action or not perform an action depending on our desired output.

# PHP Functions
In PHP, the main goal for functions is to create reusable code. We can group this code into a block that might look something like this:
function greet($name) {
    echo "Hello, $name";
}
// Now if we were to call that function like this:
greet("Reece"); // PHP would output Hello, Reece.

# PHP Arrays
Arrays are a very powerful tool in coding. We can use them to store all kinds of information.
$cars = array("BMW", "Pontiac", "Chevy");
$numbers = array(1, 2, 3);
$fruits = array("Oranges", "Apples", "Bananas");
// There are many different types of data we can store in arrays, including integers, floats, strings, booleans, null, arrays (nested arrays), objects, and mixed arrays.

# PHP Loops
The most common loops are for loops and while loops. For loops are used to execute a block of code a certain number of times, and while loops execute a block of code repeatedly while a condition is true. We use for loops when we know how many times we want something to loop and while loops when we want to loop something the entire time a condition is true.
Example of For Loop:
for ($i = 0; $i < 5; $i++) {
    echo "Iteration $i <br>";
}
// This will loop until $i reaches 5.

Example of While Loop:
$counter = 0;
while ($counter < 5) {
    echo "Count: $counter <br>";
    $counter++;
}
// This will loop while $counter is less than 5.
