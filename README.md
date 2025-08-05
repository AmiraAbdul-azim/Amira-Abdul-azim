<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Amira Abdulazeem - Frontend Developer</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fira+Code&display=swap">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />

    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #0d1117;
            color: #fff;
            font-family: 'Fira Code', monospace;
            text-align: center;
        }

        .typing-line {
            font-size: 2rem;
            white-space: nowrap;
            overflow: hidden;
            border-right: 3px solid #F76EEC;
            width: 0;
            text-align: center;
            display: block;
            margin: 0 auto;
        }

        #line1 {
            color: #F76EEC;
            animation: typing1 1s steps(20, end) forwards;
        }

        #line2 {
            color: #F76EEC;
            animation: typing2 2s steps(40, end) forwards;
            animation-delay: 1.5s;
            opacity: 0;
        }

        @keyframes typing1 {
            from {
                width: 0
                
            }

            to {
                width: 100px
                
            }
        }

        @keyframes typing2 {
            from {
                width: 0;
                opacity: 1
            }

            to {
                width: 430px;
                opacity: 1
            }
        }

        @keyframes blink {
            50% {
                border-color: transparent
            }
        }




        .about {
            margin-top: 40px;
            width: 80%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            text-align: left;
            background-color: #161b22;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px #F76EEC55;
        }

        .about h4 {
            color: #F76EEC;
        }

        .about ul {
            padding-left: 20px;
        }

        .about li {
            margin-bottom: 10px;
        }


        .links a {
            color: #F76EEC;
            text-decoration: none;
            border: 1px solid #F76EEC;
            padding: 8px 16px;
            border-radius: 8px;
            display: inline-block;
            margin-top: 20px;
            transition: 0.3s;
        }

        .links a:hover {
            background-color: #F76EEC;
            color: #0d1117;
        }

        .projects,
        .languages,
        .Connect {
            width: 80%;
            max-width: 600px;
            margin: 40px auto;
            background-color: #161b22;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px #F76EEC33;
            text-align: left;
        }

        .projects h4,
        .languages h4,
        .Connect h4 {
            color: #F76EEC;
            margin-bottom: 10px;
        }

        .projects ul,
        .languages ul {
            list-style: none;
            padding: 0;
        }

        .projects li,
        .languages li {
            margin: 8px 0;
        }

        .projects a {
            color: #fff;
            text-decoration: none;
            transition: color 0.3s;
        }

        .projects a:hover {
            color: #F76EEC;
        }

        .icons {
            display: flex;
            flex-wrap: wrap;
            justify-content: flex-start;
            gap: 20px;
            margin-top: 20px;
            padding-left: 20px;
        }

        .icons img {
            width: 40px;
            height: 40px;
            transition: transform 0.3s ease;

        }

        .icons img:hover {
            transform: scale(1.2);
        }

        a {
            text-decoration: none;
        }
    </style>
</head>

<body>

    <div id="line1" class="typing-line">Hi!🦋</div>
    <div id="line2" class="typing-line">I'm Amira Abdul-azim👩‍💻</div>



   

    <div class="about">
        <h4>🌟 About Me</h4>
        <ul>
            <li>🎓 3rd year student at <strong>Arab Open University</strong></li>
            <li>🏢Faculty of Computer Science (2024–2027).</li>
            <li>🖥️ Focused on <strong>Frontend Development</strong> with a creative mindset</li>
            <li>🌱 Currently learning:
                <ul>
                    <li>HTML5, CSS3, JavaScript</li>
                    <li>React, Bootstrap, Tailwind CSS</li>
                </ul>
            </li>
            <li>👩‍💻 Completed Web Development course with <strong>ICTHub</strong> (60 hours)</li>
            <li>🎯 Training in:
                <ul>
                    <li>Front-End at ITI (AOU)</li>
                    <li>Full Stack at ITI – Beni Suef</li>
                    <li>Front-End at Sef Academy</li>
                </ul>
            </li>
        </ul>
    </div>
    <div class="languages">
        <h4>🛠️ Languages & Tools I Know</h4>
        <div class="icons">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"alt="JavaScript">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="PHP">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-original.svg" alt="Laravel">
        </div>
    </div>
    <div class="projects">
        <h4>📁 My Projects</h4>
        <ul>
            <li><a href="https://amiraabdul-azim.github.io/IGym/" target="_blank">Website : IGym</a></li>
            <li><a href="https://amiraabdul-azim.github.io/Amira-Couture/" target="_blank">Website : Amira-Couture</a>
            </li>

        </ul>
    </div>

    <div class="Connect">
        <h4>🌟Connect with me</h4>
        <div class="icons">
            <a href="https://www.linkedin.com/in/amira-abdul-azim-535028354/" target="_blank">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg"alt="LinkedIn" />
            </a>
        </div>
</body>

</html>
