⭐😊INDEX.PHP CODE
<!-- /index.php -->
<?php include 'includes/header.php'; ?>
<main>
           <h1>Welcome to My World</h1>
           <p>Explore more about Me</p>
           <section id="about-me">
           <h2>About Me</h2>
           <img src="https://i.pinimg.com/550x/69/da/63/69da631d7d76642ca52e41e15624f46b.jpg" alt="Profile Picture">
           <p>Hello! My name is Arshpreet, and I am passionate about web development. I enjoy creating dynamic and responsive websites using the latest technologies. In my spare time, I love exploring new programming languages and frameworks, as well as contributing to open-source projects. Welcome to my personal website where I share my projects and more about my journey in the tech world. Thank you for visiting!</p>
</section>
</main>
<?php include 'includes/footer.php'; ?>


⭐😊ABOUT CODE    
<!-- /about.php -->
<?php include 'includes/header.php'; ?>
<main>
    <h1>About Us</h1>
    <section id="my-goals">
        <h2>My Goals</h2>
        <p>Hello! I'm Arshpreet kaur, and I am driven by a set of personal and professional goals that guide my journey in the world of web development.</p>
        <p>One of my primary goals is to constantly improve my skills and knowledge in web development. I aim to stay updated with the latest technologies and best practices to create efficient, user-friendly, and innovative web applications.</p>
        <p>In addition to honing my technical skills, I am passionate about contributing to the tech community. I plan to engage more in open-source projects, share my knowledge through blogs and tutorials, and participate in coding bootcamps and hackathons.</p>
        <p>On a personal level, I strive to maintain a healthy work-life balance. I aim to make time for my hobbies, such as  hiking, reading, exploring new cafes creative things, and ensure that I take care of my physical and mental well-being.</p>
        <p>This website is a platform for me to share my journey, showcase my work, and connect with like-minded individuals. Thank you for visiting, and feel free to reach out if you share similar goals or have any questions.</p>
    </section>


</main>
<?php include 'includes/footer.php'; ?>


⭐😊HEADER.PHP CODE
<!-- /includes/header.php -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/styles.css">
    <title>My First PHP Website</title>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li class="<?= basename($_SERVER['PHP_SELF']) == 'index.php' ? 'active' : '' ?>">
                    <a href="index.php">Home</a>
                </li>
                <li class="<?= basename($_SERVER['PHP_SELF']) == 'about.php' ? 'active' : '' ?>">
                    <a href="about.php">About</a>
                </li>
                <!-- Add more navigation items here -->
            </ul>
        </nav>
    </header>
</body>
</html>


⭐😊CSS CODE
/* /css/styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}
 
header {
    background-color: #077272;
    color: #fff;
    padding: 10px 0;
}
 
nav ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
}
 
nav ul li {
    margin: 0 15px;
}
 
nav ul li a {
    color: #fff;
    text-decoration: none;
}
 
nav ul li.active a {
    font-weight: bold;
    text-decoration: underline;
}
 
footer {
    background-color: #09816d;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
 
main {
    padding: 20px;
    max-width: 800px;
    margin: 0 auto;
}
 
#about-me {
    margin-top: 20px;
}
 
#about-me img {
    max-width: 150px;
    border-radius: 50%;
    display: block;
    margin: 0 auto 10px;
}
 
#about-me p {
    text-align: center;
}


⭐😊FOOTER CODE
<!-- /includes/footer.php -->
<footer>
    <p>&copy; <?= date("Y") ?> My First PHP Website. All rights reserved.</p>
</footer>
    
