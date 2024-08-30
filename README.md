<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Govardhan's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #007acc;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        #main {
            padding: 20px;
        }
        img {
            display: block;
            margin: 20px auto;
            border-radius: 50%;
            width: 150px;
            height: 150px;
        }
        h1, h2 {
            color: #007acc;
        }
        p {
            line-height: 1.6;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            background: #007acc;
            color: white;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }
        footer {
            background-color: #007acc;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .project-description {
            background-color: #e6e6e6;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 15px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Govardhan's Portfolio</h1>
        <p>Email: <a href="mailto:manubolu611@gmail.com" style="color: white;">manubolu611@gmail.com</a></p>
    </header>

    <div class="container" id="main">
        <img src=
        "C:\Users\eswar\Downloads\WhatsApp Image 2024-08-30 at 16.45.41_92178b59.jpg"alt="Govardhan">
        <h2>About Me</h2>
        <p>Hello! I am Govardhan, a software engineer with experience in developing machine learning algorithms and working with various technologies. My passion lies in solving complex problems and creating innovative solutions using technology.</p>

        <h2>Projects</h2>
        
        <div class="project-description">
            <h3>Network Anomaly Detection Using Machine Learning Algorithms</h3>
            <p>This project involves designing and implementing a machine learning model to detect anomalies in network traffic. By analyzing patterns in the network data, the model can identify unusual behaviors that may indicate security threats or other issues. The project leverages techniques such as clustering and classification algorithms, providing a robust solution for real-time network monitoring and security.</p>
        </div>

        <div class="project-description">
            <h3>Background Removal Using Python</h3>
            <p>In this project, I developed a Python application that can automatically remove the background from images. The application uses image processing libraries like OpenCV and deep learning models to accurately separate the foreground object from the background. This tool is useful in various applications, such as e-commerce, photography, and graphic design, where clean and professional images are required.</p>
        </div>

        <h2>Skills</h2>
        <ul>
            <li>Python</li>
            <li>SQL</li>
            <li>AWS</li>
            <li>HTML</li>
            <li>CSS</li>
        </ul>
    </div>

    <footer>
        <p>&copy; 2024 Govardhan</p>
    </footer>
</body>
</html>
