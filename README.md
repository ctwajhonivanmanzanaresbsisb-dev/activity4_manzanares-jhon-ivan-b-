# activity4_manzanares-jhon-ivan-b-
<?php

// Jhon

/*
Name: Jhon Ivan Manzanares
Age: 22
Course: BSIS
School: Your School Name
*/

// Declare associative array
$me = array(
    "name" => "Jhon Ivan Manzanares",
    "age" => 22,
    "address" => "Philippines",
    "hobbies" => "Playing games and listening to music",
    "dream_job" => "Software Developer",
    "course" => "BSIS",
    "school" => "Your School Name"
);

// Using echo with HTML tags
echo "<h1>My Basic Information</h1>";

echo "<p><b>Name:</b> " . $me["name"] . "</p>";
echo "<p><b>Age:</b> " . $me["age"] . "</p>";
echo "<p><b>Address:</b> " . $me["address"] . "</p>";
echo "<p><b>Hobbies:</b> " . $me["hobbies"] . "</p>";
echo "<p><b>Dream Job:</b> " . $me["dream_job"] . "</p>";
echo "<p><b>Course:</b> " . $me["course"] . "</p>";
echo "<p><b>School:</b> " . $me["school"] . "</p>";

// Using print and concatenation operator
print "I am " . $me["name"] . ", a " . $me["course"] . " student of " . $me["school"] . ".";

?>