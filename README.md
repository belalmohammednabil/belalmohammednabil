<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YourName's Awesome README</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background: linear-gradient(135deg, #1e1e2f, #2a2a4a);
            color: #e0e0e0;
            transition: background 0.3s, color 0.3s;
        }
        .light-theme {
            background: linear-gradient(135deg, #f5f7fa, #c3cfe2);
            color: #333;
        }
        h2 {
            color: #6ab0f3;
            border-bottom: 2px solid #6ab0f3;
            padding-bottom: 10px;
            animation: fadeIn 1s ease-in;
        }
        a {
            color: #ff79c6;
            text-decoration: none;
            transition: color 0.3s;
        }
        a:hover {
            color: #bd93f9;
        }
        .badge {
            margin: 5px;
            transition: transform 0.2s;
        }
        .badge:hover {
            transform: scale(1.1);
        }
        .tool-icon {
            margin: 5px;
            transition: transform 0.2s;
        }
        .tool-icon:hover {
            transform: rotate(360deg);
        }
        ul {
            list-style: none;
            padding: 0;
        }
        li {
            margin: 10px 0;
            animation: slideIn 0.5s ease-in;
        }
        details {
            background: #2a2a4a;
            padding: 10px;
            border-radius: 8px;
            margin: 10px 0;
        }
        summary {
            cursor: pointer;
            font-weight: bold;
        }
        .theme-toggle {
            position: fixed;
            top: 20px;
            right: 20px;
            background: #6ab0f3;
            color: #fff;
            border: none;
            padding: 10px;
            border-radius: 50%;
            cursor: pointer;
            transition: background 0.3s;
        }
        .theme-toggle:hover {
            background: #ff79c6;
        }
        .gif {
            float: right;
            margin-left: 20px;
            border-radius: 8px;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideIn {
            from { transform: translateX(-20px); opacity: 0; }
            to { transform: translateX(0); opacity: 1; }
        }
        @media (max-width: 600px) {
            body {
                padding: 10px;
            }
            .gif {
                float: none;
                margin: 10px auto;
                display: block;
            }
        }
    </style>
</head>
<body>
    <button class="theme-toggle" onclick="toggleTheme()">🌙</button>
    <h2>Hey 👋, I'm <a href="https://yourwebsite.com">YourName</a></h2>
    <p>
        I'm a passionate software engineer at <strong><a href="https://yourcompany.com">YourCompany</a></strong> based in 🌍 YourCity. 
        Currently, I'm building awesome Flutter apps, cooking some delicious recipes, and mastering strategies in my favorite games! 🚀
    </p>
    <p>
        <a href="https://yourwebsite.com"><img class="badge" src="https://img.shields.io/badge/-yourwebsite.com-4E69C8?style=flat-square&labelColor=4E69C8&logo=Firefox&link=https://yourwebsite.com" alt="Website Badge"></a>
        <a href="https://medium.com/@yourusername"><img class="badge" src="https://img.shields.io/badge/-@yourusername-14c767?style=flat-square&labelColor=14c767&logo=Medium&link=https://medium.com/@yourusername" alt="Medium Badge"></a>
        <a href="https://www.linkedin.com/in/yourusername/"><img class="badge" src="https://img.shields.io/badge/-@yourusername-0077B5?style=flat-square&labelColor=0077B5&logo=LinkedIn&link=https://www.linkedin.com/in/yourusername/" alt="LinkedIn Badge"></a>
        <a href="https://dev.to/yourusername"><img class="badge" src="https://img.shields.io/badge/-@yourusername-0A0A0A?style=flat-square&labelColor=0A0A0A&logo=dev.to&link=https://dev.to/yourusername" alt="DevTo Badge"></a>
        <a href="https://open.spotify.com/user/yourusername"><img class="badge" src="https://img.shields.io/badge/-@YourName-1ED760?style=flat-square&labelColor=fff&logo=Spotify&link=https://open.spotify.com/user/yourusername" alt="Spotify Badge"></a>
    </p>
    <p>🍎 Keep coding and stay awesome! 🍎</p>
    <img class="gif" src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif" width="150" alt="Coding GIF" />
    
    <h2>⚡️ A Few Quick Facts</h2>
    <ul>
        <li>🔭 I’m currently working on <a href="https://github.com/yourusername/yourproject">YourProject</a>.</li>
        <li>🧐 Learning about <strong>Flutter</strong>, <strong>Distributed Systems</strong>, and <strong>Machine Learning</strong>.</li>
        <li>👨‍💻 Check out my projects on <a href="https://github.com/yourusername">GitHub</a>.</li>
        <li>📝 I occasionally write on <a href="https://blog.yourwebsite.com">my blog</a>.</li>
        <li>💬 Talk to me about <strong>Flutter, Dart, cloud computing, and game dev</strong>.</li>
        <li>📙 View my <a href="https://yourwebsite.com/resume.pdf">resume</a>.</li>
        <li>🎉 Fun Fact: أنا بتكلم عربي كمان! 😎</li>
    </ul>
    
    <h2>✒️ Recent Posts</h2>
    <details>
        <summary>Explore</summary>
        <ul>
            <li><a target="_blank" href="https://blog.yourwebsite.com/post1">Building Awesome Flutter Apps — October 15, 2025</a></li>
            <li><a target="_blank" href="https://blog.yourwebsite.com/post2">Dart Tips and Tricks — September 20, 2025</a></li>
            <li><a target="_blank" href="https://blog.yourwebsite.com/post3">Cloud Computing Made Simple — August 10, 2025</a></li>
            <li><a target="_blank" href="https://blog.yourwebsite.com/post4">Game Dev with Unity — July 5, 2025</a></li>
            <li><a target="_blank" href="https://blog.yourwebsite.com/post5">Why I Love Coding — June 1, 2025</a></li>
        </ul>
    </details>
    <p><a target="_blank" href="https://blog.yourwebsite.com">Read More</a></p>
    
    <h2>🚀 Some Tools I Use</h2>
    <p align="left">
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flutter/flutter-original.svg" alt="flutter" width="25" height="25" />
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dart/dart-original.svg" alt="dart" width="25" height="25" />
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="25" height="25" />
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="c++" width="25" height="25" />
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ruby/ruby-original.svg" alt="ruby" width="25" height="25" />
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="25" height="25" />
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="25" height="25" />
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original-wordmark.svg" alt="python" width="25" height="25" />
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original-wordmark.svg" alt="java" width="25" height="25" />
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="mongodb" width="25" height="25" />
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="25" height="25" />
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="docker" width="25" height="25" />
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-original.svg" alt="kubernetes" width="25" height="25" />
        <img class="tool-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/aws/aws-original.svg" alt="aws" width="25" height="25" />
        <!-- Add more icons here based on your input -->
    </p>
    
    <p>
        <img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&count_private=true&theme=radical" alt="yourusername" />
    </p>
    <p>
        <a href="http://hits.dwyl.com/yourusername/yourusername.svg?style=flat-square">
            <img src="http://hits.dwyl.com/yourusername/yourusername.svg?style=flat-square" alt="HitCount">
        </a>
    </p>

    <script>
        function toggleTheme() {
            document.body.classList.toggle('light-theme');
        }
    </script>
</body>
</html>
