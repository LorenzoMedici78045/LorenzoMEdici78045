 <!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мое Портфолио</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #415a77;
            color: #333;
        }
        header {
            background: #415a77;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background: #415a77;
            color: #fff;
            padding: 0.5rem;
            text-align: center;
        }
        nav a {
            color: #415a77;
            margin: 0 10px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
            max-width: 800px;
            margin: auto;
            background:#415a77;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .project {
            margin-bottom: 20px;
        }
        .project h3 {
            margin: 0;
            color: #415a77;
        }
        .project p {
            margin: 5px 0;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #415a77;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Мое Портфолио</h1>
    </header>
    <div class="container">
        <section id="about">
            <h2>Обо мне</h2>
            <p> В данный момент я занимаюсь Java-разработкой. Люблю изучение новых технологий, поездки на природу, хороших свет для фотографий на мой Pentax, а также тренировки.
.</p>
        </section>
        
        <section id="contact">
            <h2>Контакты</h2>
            <p>Свяжись со мной:</p>
            <ul>
                <li>Email: <a href="mailto:твой_email@example.com">твой_email@example.com</a></li>
                <li>GitHub: <a href="https://github.com/твой_ник" target="_blank">github.com/твой_ник</a></li>
                <li>LinkedIn: <a href="https://linkedin.com/in/твой_профиль" target="_blank">linkedin.com/in/твой_профиль</a></li>
            </ul>
        </section>
    </div>
    <input type="image" src="https://github.com/user-attachments/assets/8c90739b-7de2-4c35-b09d-f5ac7a6efb7c" name="myButton" height="800" width="400">
</body>
</html>
