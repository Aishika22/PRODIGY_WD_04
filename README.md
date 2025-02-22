<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            font-size: 1.5em;
        }
        .container {
            width: 80%;
            margin: 20px auto;
        }
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-top: 20px;
        }
        .section {
            background: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>Welcome to My Portfolio</header>
    <div class="container">
        <img src="profile.jpg" alt="Profile Picture" class="profile-img">
        <h2>John Doe</h2>
        <p>Web Developer | Frontend Enthusiast | Problem Solver</p>
        
        <div class="section">
            <h3>About Me</h3>
            <p>Passionate web developer with a strong background in HTML, CSS, JavaScript, and modern frameworks.</p>
        </div>
        
        <div class="section">
            <h3>Projects</h3>
            <ul>
                <li>Project 1 - <a href="#">E-commerce Website</a></li>
                <li>Project 2 - <a href="#">Portfolio Website</a></li>
                <li>Project 3 - <a href="#">Task Management App</a></li>
            </ul>
        </div>

        <div class="section">
            <h3>Contact</h3>
            <p>Email: johndoe@example.com</p>
            <p>LinkedIn: <a href="#">linkedin.com/in/johndoe</a></p>
        </div>
    </div>
</body>
</html>
