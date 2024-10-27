<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="styles.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Website</title>
</head>
<body>

<header>
    <img class="logo" src="collegeicon.png" alt="College Logo">
    <ul class="nav">
        <li>Home</li>
        <li>Admission</li>
        <li>Departments</li>
        <li>Facilities</li>
        <li>News</li>
        <li>Contact</li>
    </ul>
</header>

<section class="hero">
    <h1>Welcome to Our College</h1>
    <p>Your future starts here!</p>
    <button class="admis">Apply for admission</button>
</section>

<div class="content">
    <div class="feature">
        <img src="ground.png" alt="Sports Ground">
        <h2>Sports Facilities</h2>
        <p>We offer a huge ground for almost all kinds of sports.</p>
    </div>
    <div class="feature">
        <img src="library.png" alt="Library">
        <h2>Library</h2>
        <p>A vast collection of books and resources for students.</p>
    </div>
    <div class="feature">
        <img src="labs.png" alt="Laboratories">
        <h2>Laboratories</h2>
        <p>State-of-the-art labs for practical learning.</p>
    </div>
    <div class="feature">
        <img src="classrooms.png" alt="Classrooms">
        <h2>Classrooms</h2>
        <p>Modern classrooms equipped with the latest technology.</p>
    </div>
</div>

<div class="divider"></div>

<section class="about">
    <h2>About the Principal</h2>
    <img src="principal.png" alt="Principal Photo">
    <p>Dr. John Smith has dedicated his career to providing quality education and fostering a supportive environment for students. Under his leadership, the college has achieved remarkable growth and innovation in academic programs.</p>
</section>

<div class="divider"></div>

<section class="news">
    <h2>Latest News & Events</h2>
    <p>Stay tuned for our upcoming events and important announcements.</p>
    <ul>
        <li>Annual Sports Day - March 15, 2024</li>
        <li>College Fest - April 20-22, 2024</li>
        <li>Admission Open for 2024-25 - Apply Now!</li>
    </ul>
</section>

<div class="divider"></div>

<section class="testimonials">
    <h2>Student Testimonials</h2>
    <p>"This college has transformed my life. The teachers are incredibly supportive!" - Jane Doe</p>
    <p>"I love the vibrant campus and the amazing facilities." - John Smith</p>
</section>

<footer>
    <p>Follow us on:</p>
    <a href="#">Facebook</a> |
    <a href="#">Twitter</a> |
    <a href="#">Instagram</a> |
    <a href="#">LinkedIn</a>
</footer>

</body>
<style>
    body {
    margin: 0;
    font-family: 'Roboto', sans-serif;
    color: #fff;
    background: linear-gradient(to bottom, #0a0a0a, #3b3b3b), url('banner.jpg') center / cover no-repeat;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background: rgba(30, 30, 30, 0.8);
}

.logo {
    height: 90px;
}

.nav {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    gap: 15px;
}

.nav li {
    padding: 10px 20px;
    cursor: pointer;
    transition: background 0.3s, transform 0.3s;
    border-radius: 5px;
}

.nav li:hover {
    background: rgba(255, 255, 255, 0.2);
    transform: scale(1.05);
}

.hero {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
    text-align: center;
    padding: 20px;
    background: rgba(50, 50, 100, 0.7);
}

.hero h1 {
    font-size: 80px;
    margin: 0;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8);
}

.content {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 20px;
}

.feature {
    background: rgba(4, 9, 30, 0.8);
    border-radius: 10px;
    padding: 20px;
    margin: 10px;
    width: calc(25% - 40px);
    text-align: center;
    transition: transform 0.3s, box-shadow 0.3s;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
}

.feature:hover {
    transform: scale(1.05);
}

.feature img {
    width: 100%;
    border-radius: 10px;
    transition: transform 0.3s, filter 0.3s;
}

.feature:hover img {
    transform: scale(1.1);
    filter: brightness(90%);
}

.about, .news, .testimonials {
    background: rgba(20, 20, 20, 0.85);
    padding: 20px;
    margin: 20px;
    border-radius: 10px;
    text-align: center;
    width: calc(100% - 40px);
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
}

.about img {
    width: 150px;
    border-radius: 75px;
}

.divider {
    border-top: 2px solid rgba(255, 255, 255, 0.3);
    margin: 40px 0;
}

footer {
    background: rgba(0, 0, 0, 0.8);
    padding: 20px;
    text-align: center;
}

footer a {
    color: #fff;
    margin: 0 10px;
    text-decoration: none;
    transition: color 0.3s;
}

footer a:hover {
    color: #ff9900; /* Change color on hover */
}

@media (max-width: 1200px) {
    .feature {
        width: calc(33.33% - 40px);
    }
}

@media (max-width: 768px) {
    .feature {
        width: calc(50% - 40px);
    }
}

@media (max-width: 480px) {
    .hero h1 {
        font-size: 40px;
    }
    .feature {
        width: calc(100% - 40px);
    }

}
.admis
{
    background-color: red;
    padding: 20px;
    border-width: 2px;
    border: solid;
    font-family: arial;
    font-weight: bold;
    color: #fff;
    border: none;
}
.admis:hover
{
    background-color: rgb(197, 0, 0);
    padding: 20px;
    border-width: 2px;
    border: solid;
    font-family: arial;
    font-weight: bold;
    color: #fff;
    border: none;
}
.admis:active
{
    background-color: rgb(150, 0, 0);
    padding: 20px;
    border-width: 2px;
    border: solid;
    font-family: arial;
    font-weight: bold;
    color: #fff;
    border: none;
     font-size: 20px;
     
}

</style>
</html>
