# Veronika-xx.github.io
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Резюме</title>
    <link rel="stylesheet" href="css.css">
</head>
<body>
    <nav>
        <a href="#about">Обо мне</a>
        <a href="#skills">Навыки</a>
        <a href="#projects">Дополнительные факты</a>
        <a href="#contact">Контакты</a>
    </nav>
<header>
    <div class="containerr">
        <h1>Чернухина Вероника</h1>
        <p>Программист</p>
    </div>
</header>

<section id="about">
    <h2>Обо мне</h2>
    <p>Меня зовут Вероника, я начинающий программист. В данный момент учусь в НИУ ВШЭ на направлении прикладной анализ данных и искуственный интеллект. Моя цель — участвовать в создании интересных проектов и развиваться в сфере программирования.</p>
</section>

<section id="skills">
    <h2>Навыки</h2>
    <ul>
        <li><strong>Языки программирования:</strong> Python, C++</li>
        <li><strong>Инструменты разработки:</strong> Visual Studio Code, PyCharm</li>
        <li><strong>Основы алгоритмов и структур данных</strong></li>
        <li><strong>Создание простых веб-сайтов:</strong> HTML, CSS</li>
    </ul>
</section>

<section id="projects">
    <h2>Дополнительные факты</h2>
    <ul>
        <li>Окончила КГУ "Лицей №2"</li>
        <li>Знаю русский, английский и казахский языки. В данный момент изучаю китайский язык.</li>
        <li>Окончила музыкальную школу по направлению фортепиано, что поспособствовало развитию математематических способностей, памяти и внимательности.</li>
    </ul>
</section>

<section id="contact">
    <h2>Контакты</h2>
    <p>Вы можете связаться со мной по следующим каналам:</p>
    <ul>
        <li>Email: vchernukhina@edu.hse.ru</li>
        <li>Telegram <a href="https://t.me/No_mym">https://t.me/No_mym</a></li>
        
    </ul>
</section>

<footer>
    <p>&copy; 2024 Вероника - Начинающий программист</p>
</footer>

</body>
</html>

body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
    color: #333;
}


header {
    text-align: center;
    padding: 50px 0;
    background: linear-gradient(45deg, #235778, #50e3c2);
    color: white;
}
.containerг {
    width: 90%;
    margin: auto;
    max-width: 1200px;
}

header h1 {
    font-size: 48px;
    margin-bottom: 10px;
}
header p {
    font-size: 33px;
}


nav {
    display: flex;
    justify-content: center;
    background-color: #235778;
    padding: 10px 0;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

nav a {
    margin: 0 20px;
    color: #fff;
    text-decoration: none;
    font-size: 18px;
    text-transform: uppercase;
    font-weight: bold;
}

nav a:hover {
    color: #4a90e2;
    border-bottom: 2px solid #4a90e2;
}

section {
    padding: 40px 20px;
    max-width: 900px;
    margin: 20px auto;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

h2 {
    font-size: 28px;
    color: #235778;
    border-bottom: 2px solid #461b00;
    padding-bottom: 10px;
    margin-bottom: 20px;
}

ul {
    list-style: disc inside;
}

ul li {
    padding: 5px 0;
    font-size: 18px;
}


#contact a {
    color: #461b00;
    text-decoration: none;
    font-weight: bold;
}

#contact a:hover {
    text-decoration: underline;
}


footer {
    text-align: center;
    padding: 15px;
    background-color: #235778;
    color: white;
    position: fixed;
    bottom: 0;
    width: 100%;
}

footer p {
    margin: 0;
    font-size: 14px;
}

section:hover {
    transform: translateY(-5px);
    transition: transform 0.3s ease;
}
