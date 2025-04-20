<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sanjar's Profile</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        h1, h3 {
            text-align: center;
            animation: fadeIn 2s ease-in-out;
        }
        h1 {
            color: #007bff;
        }
        h3 {
            color: #555;
            margin-top: -10px;
        }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 20px;
        }
        .social-links a {
            margin: 10px;
            transition: transform 0.3s;
        }
        .social-links a:hover {
            transform: scale(1.2);
        }
        .tools {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 20px;
        }
        .tools a {
            margin: 15px;
            transition: transform 0.3s, filter 0.3s;
        }
        .tools a:hover {
            transform: scale(1.2);
            filter: brightness(1.2);
        }
        .tools img {
            width: 50px;
            height: 50px;
        }
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hi, I'm Sanjar <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35"></h1>
        <h3>I am a full stack programmer (GO, Python, PHP)</h3>

        <div class="social-links">
            <h3>Connect with me:</h3>
            <a href="https://www.instagram.com/sandjey_/" target="_blank">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" height="40" width="40" />
            </a>
        </div>

        <h3>Languages and Tools:</h3>
        <div class="tools">
            <a href="https://www.w3schools.com/css/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" /></a>
            <a href="https://git-scm.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" /></a>
            <a href="https://golang.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" /></a>
            <a href="https://www.w3.org/html/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" /></a>
            <a href="https://www.mysql.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" /></a>
            <a href="https://www.php.net" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" /></a>
            <a href="https://www.python.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" /></a>
            <a href="https://www.sqlite.org/" target="_blank"><img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" /></a>
        </div>
    </div>
</body>
</html>
