<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f4f8;
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            text-align: center;
        }
        h1 {
            color: #4b8b3b;
        }
        .technologies {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        .technology-icon {
            width: 50px;
            height: 50px;
        }
        a {
            text-decoration: none;
            color: #4b8b3b;
            font-weight: bold;
        }
        .contact-link {
            color: #2196F3;
        }
    </style>
</head>
<body>
    <h1>✨ About Me</h1>
    <ul>
        <li>😀 My name is Nguyễn Thành Trung</li>
        <li>❤️ I love writing C#</li>
        <li>💬 Ask me about anything <a href="https://github.com/nguyenthanhtrung001/information/issues" class="contact-link">here</a></li>
    </ul>

    <h1>⚙ Technologies</h1>
    <div class="technologies">
        <a href="https://skillicons.dev" target="_blank">
            <img src="https://skillicons.dev/icons?i=java,go,py,cs,c++,php,nodejs,nextjs,mongo,postgres,mysql,sqlserver,visualstudio,vscode,eclipse,intellij,springboot,laragon&perline=7" class="technology-icon" />
        </a>
    </div>
</body>
</html>
