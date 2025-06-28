# Welcome to my GitHub! 👋
![image](https://github.com/user-attachments/assets/3acb6f50-38c6-45d8-a020-3fbbb3c78f3d)

Hi, I'm **Meriem El mecaniqui**, a passionate **Full Stack Web Developer** from **Nador, Morocco**. I specialize in building beautiful, functional, and responsive websites. I'm constantly learning and improving my skills.

Feel free to explore my projects and don't hesitate to reach out if you have any questions or suggestions!


## 🌱 Technologies I work with:

- **Front-End:** HTML, CSS, JavaScript
- **Back-End:** PHP, Laravel
- **Databases:** MySQL
- **Tools:** Git, Jira, Figma

---





```php
<?php

$meriemDev = [
    "fullName" => "Meriem El mecaniqui",
    "profession" => "Full Stack Web Developer",
    "experience" => "junior",
    "location" => "Nador, Morocco",
    "email" => "melmecaniqui@example.com",
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
