# Welcome to my GitHub! 👋

Hi, I'm **Meriem El mecaniqui**, a passionate **Full Stack Web Developer** from **Nador, Morocco**. I specialize in building beautiful, functional, and responsive websites. I'm constantly learning and improving my skills.

Feel free to explore my projects and don't hesitate to reach out if you have any questions or suggestions!

## Technologies I work with:
- Front-End: HTML, CSS, JavaScript
- Back-End: PHP, Laravel, Node.js
- Databases: MySQL, MongoDB
- Tools: Git, Docker, AWS

## Projects

### 1. **Merylowers** 🌸
An e-commerce platform for buying and selling flowers with a modern, user-friendly design. Features include:
- Product listing with search and filters
- Secure user registration and login
- Shopping cart and order management

Technologies: **PHP**, **Laravel**, **Tailwind CSS**, **MySQL**

[View Project](https://github.com/yourusername/merylowers)

### 2. **YouQuote** 📜
An API for managing quotes, allowing users to create, share, and like quotes. Features include:
- User authentication and roles
- Quotes categorization and tagging
- Likes and favorites system

Technologies: **Laravel**, **MySQL**, **JWT Authentication**

[View Project](https://github.com/yourusername/youquote)

## Contact

Feel free to get in touch with me via:

### 📧 Email:
[Send an email](mailto:your-email@example.com)

### 🔗 LinkedIn:
[Connect on LinkedIn](https://www.linkedin.com/in/meriem-el-mecaniqui)

---

## PHP Example

Here's an example of how you can use PHP to display your information:

```php
<?php

$meriemDev = [
    "fullName" => "Meriem El mecaniqui",
    "profession" => "Full Stack Web Developer",
    "experience" => "junior",
    "location" => "Nador, Morocco",
    "email" => "your-email@example.com",
    "linkedin" => "https://www.linkedin.com/in/meriem-el-mecaniqui"
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
