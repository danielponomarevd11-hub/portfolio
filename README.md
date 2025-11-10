# portfolio
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Портфолио Даниила Пономарева</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #121212;
      color: #fff;
    }

    header {
      background-color: #1e1e1e;
      padding: 20px;
      text-align: center;
    }

    h1 {
      margin: 0;
      font-size: 2.5em;
    }

    nav {
      background-color: #212121;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: #bb86fc;
      text-decoration: none;
      padding: 10px 20px;
      display: inline-block;
    }

    nav a:hover {
      background-color: #bb86fc;
      color: #121212;
    }

    section {
      padding: 20px;
      margin: 20px;
      background-color: #1e1e1e;
      border-radius: 8px;
    }

    h2 {
      font-size: 2em;
      margin-top: 0;
    }

    .portfolio {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }

    .portfolio-item {
      width: 300px;
      margin-bottom: 20px;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
      background-color: #2a2a2a;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .portfolio-item img {
      width: 100%;
      height: auto;
      display: block;
      transition: transform 0.3s ease;
      border-bottom: 1px solid #444;
    }

    .portfolio-item img:hover {
      transform: scale(1.1);
    }

    .caption {
      padding: 10px;
      text-align: center;
      font-size: 1em;
      color: #ccc;
    }

    .contact-info {
      list-style: none;
      padding: 0;
    }

    .contact-info li {
      margin-bottom: 10px;
    }

    footer {
      background-color: #1e1e1e;
      text-align: center;
      padding: 10px;
      font-size: 0.8em;
    }

    /* Адаптивность */
    @media (max-width: 768px) {
      .portfolio-item {
        width: 100%;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Даниил Пономарев</h1>
    <p>Дизайнер среды и интерьеров</p>
  </header>

  <nav>
    <a href="#about">Обо мне</a>
    <a href="#portfolio">Портфолио</a>
    <a href="#contact">Контакты</a>
  </nav>

  <section id="about">
    <h2>Обо мне</h2>
    <p>Мужчина, 22 года.</p>
    <p><strong>Образование:</strong></p>
    <ul>
      <li>2023г. Невский институт дизайна, Университет при МПА ЕврАзЭС, бакалавриат по программе «Дизайн среды».</li>
      <li>2019г.-2023г. ГАПОУ СО «Нижнетагильский строительный колледж», отделение: строительства и дизайна, специальности «Дизайн по отраслям».</li>
      <li>2016г.-2019г. МБУ ДО «Верхнесалдинская детская школа искусств».</li>
    </ul>
    <p><strong>Личные качества:</strong> Трудолюбие, исполнительность, саморазвитие, большая целеустремлённость, усидчивость, настойчивость, отзывчивость.</p>
    <p><strong>Дополнительные награды:</strong></p>
    <ul>
      <li>2025г. «Архитектурные сезоны»</li>
      <li>2025г. «Международный конкурс курсовых проектов»</li>
      <li>2022г. «ВСЕРОССИЙСКИЙ ФЕСТЕВАЛЬ ГОРОДСКОЕ ПРОСТРАНСТВО»</li>
      <li>2013г. «Давай раскрасим вместе мир».</li>
    </ul>
    <p><strong>Хобби:</strong> Спорт, видеомонтаж, увлекаюсь музыкой.</p>
    <p>Готовность к переездам и командировкам.</p>
  </section>

  <section id="portfolio">
    <h2>Портфолио</h2>
    <div class="portfolio">
      <div class="portfolio-item">
        <img src="https://i.imgur.com/FGEVqO5.png" alt="Проект 1" />
        <div class="caption">Проект 1: Современный интерьер жилого пространства</div>
      </div>
      <div class="portfolio-item">
        <img src="https://i.imgur.com/OHwxlXc.png" alt="Проект 2" />
        <div class="caption">Проект 2: Офисное пространство в минималистском стиле</div>
      </div>
      <div class="portfolio-item">
        <img src="https://i.imgur.com/05NBZap.png" alt="Проект 3" />
        <div class="caption">Проект 3: Креативное оформление общественной зоны</div>
      </div>
      <div class="portfolio-item">
        <img src="https://i.imgur.com/cTDUfcL.png" alt="Проект 4" />
        <div class="caption">Проект 4: Интерьер кафе с акцентом на природные материалы</div>
      </div>
      <div class="portfolio-item">
        <img src="https://i.imgur.com/k2BfqK6.png" alt="Проект 5" />
        <div class="caption">Проект 5: Дизайн выставочного стенда</div>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Контакты</h2>
    <ul class="contact-info">
      <li>Телефон: +79655236973</li>
      <li>WhatsApp: +79655236973</li>
      <li>ВКонтакте: <a href="https://vk.com/dponomarev2003" target="_blank" rel="noopener noreferrer" style="color:#bb86fc;">vk.com/dponomarev2003</a></li>
      <li>Email: <a href="mailto:daniel.ponomarevd11@gmail.com" style="color:#bb86fc;">daniel.ponomarevd11@gmail.com</a></li>
    </ul>
  </section>

  <footer>
    <p>© 2025 Даниил Пономарев. Все права защищены.</p>
  </footer>
</body>
</html>
