# Welcome to my GitHub! 👋

Hi, I'm **Meriem El mecaniqui**, a passionate **Full Stack Web Developer** from **Nador, Morocco**. I specialize in building beautiful, functional, and responsive websites. I'm constantly learning and improving my skills.

Feel free to explore my projects and don't hesitate to reach out if you have any questions or suggestions!

![https://www.pinterest.com/pin/3166662232696181/)  <!-- Replace with an actual photo -->

## 🌱 Technologies I work with:

- **Front-End:** HTML, CSS, JavaScript
- **Back-End:** PHP, Laravel
- **Databases:** MySQL
- **Tools:** Git, Jira, Figma

---

## 🔧 PHP Example

Here's an example of how you can use PHP to display your information:

```php
<?php

$meriemDev = [
    "fullName" => "Meriem El mecaniqui",
    "profession" => "Full Stack Web Developer",
    "experience" => "junior",
    "location" => "Nador, Morocco",
    "email" => "your-email@example.com",
    "linkedin" => "https://www.linkedin.com/in/meriem-el-mecaniqui/"
];

function sayHello($dev) {
    echo "Hello, I'm {$dev['fullName']}, a {$dev['experience']} {$dev['profession']} from {$dev['location']}.\n";
    echo "I'm passionate about building simple and beautiful websites, and I can't wait to learn more every day! 💻✨\n";
    echo "\nContact me: \n";
    echo "📧 Email: {$dev['email']}\n";
    echo "🔗 LinkedIn: {$dev['linkedin']}\n";
}

sayHello($meriemDev);

?>
