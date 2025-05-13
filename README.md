```php
<?php

$meriemDev = [
    "fullName" => "Meriem El mecaniqui",
    "profession" => "Full Stack Web Developer",
    "experience" => "junior",
    "location" => "Nador, Morocco"
];

function sayHello($dev) {
    echo "Hello, I'm {$dev['fullName']}, a {$dev['experience']} {$dev['profession']} from {$dev['location']}.\n";
    echo "I'm passionate about building simple and beautiful websites, and I can't wait to learn more every day! 💻✨\n";
}


sayHello($meriemDev);

?>
