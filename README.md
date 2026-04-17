<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Повышение прикуса на практике — Sklyarov Center</title>
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
 
.roboto-<uniquifier> {
  font-family: "Roboto", sans-serif;
  font-optical-sizing: auto;
  font-weight: <weight>;
  font-style: normal;
  font-variation-settings:
    "wdth" 100;
}
  

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

:root {
  --accent: #649DF8;
  --accent-hover: #4d87e0;
  --bg: #FFFFFF;
  --bg-alt: #F7F7F9;
  --border: #E0E0E0;
  --text: #3A3A3A;
  --text-heading: #000000;
  --radius: 12px;
  --max-w: 860px;
}



body {
  font-family: 'Manrope', sans-serif;
  font-size: 17px;
  line-height: 1.65;
  color: var(--text);
  background: var(--bg);
  -webkit-font-smoothing: antialiased;
}

h1, h2, h3 {
  font-family: 'roboto', Georgia, serif;
  color: var(--text-heading);
  line-height: 1.15;
  letter-spacing: -0.01em;
}

h1 { font-size: clamp(34px, 5.5vw, 52px); font-weight: 700; }
h2 { font-size: clamp(28px, 4.5vw, 40px); font-weight: 700; margin-bottom: 32px; }
h3 { font-size: 22px; font-weight: 700; }

.container {
  max-width: var(--max-w);
  margin: 0 auto;
  padding: 0 24px;
}

section { padding: 80px 0; }
section.alt-bg { background: var(--bg-alt); }

/* ===== CTA BUTTON ===== */
.btn {
  display: inline-block;
  padding: 16px 40px;
  background: var(--accent);
  color: #fff;
  font-family: 'Manrope', sans-serif;
  font-size: 16px;
  font-weight: 600;
  text-decoration: none;
  border-radius: 50px;
  border: none;
  cursor: pointer;
  transition: background 0.2s, transform 0.2s;
  letter-spacing: 0.01em;
}
.btn:hover { background: var(--accent-hover); transform: translateY(-1px); }

/* ===== HERO ===== */
.hero { padding: 60px 0 80px; background: var(--bg); }

.hero-inner {
  display: flex;
  align-items: flex-start;
  gap: 48px;
}

.hero-text { flex: 1; padding-top: 20px; }

.hero-label {
  display: inline-block;
  font-size: 13px;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  color: var(--accent);
  margin-bottom: 16px;
}

.hero-title { margin-bottom: 20px; }

.hero-subtitle {
  font-size: 18px;
  color: var(--text);
  margin-bottom: 24px;
  max-width: 480px;
}

.hero-author {
  font-size: 15px;
  color: #666;
  margin-bottom: 32px;
}

.hero-pricing {
  display: flex;
  align-items: baseline;
  gap: 12px;
  margin-bottom: 8px;
  flex-wrap: wrap;
}

.price-current {
  font-family: 'roboto', Georgia, serif;
  font-weight: 900;
  font-size: 36px;
  color: var(--text-heading);
}

.price-old {
  font-size: 20px;
  color: #999;
  text-decoration: line-through;
}

.price-usd {
  font-size: 15px;
  color: #888;
}

.hero-timer {
  margin: 16px 0 28px;
  font-size: 14px;
  color: #666;
}

.hero-timer-label { margin-bottom: 4px; font-weight: 500; }

.hero-bonuses {
  margin-top: 20px;
  font-size: 14px;
  color: #666;
  line-height: 1.8;
}

.hero-photo-wrap {
  flex: 0 0 300px;
  text-align: center;
}

.hero-photo {
  width: 100%;
}

.hero-photo img {
  width: 100%;
  height: auto;
  border-radius: var(--radius);
  object-fit: cover;
}

.hero-photo-caption {
  font-size: 14px;
  color: #666;
  margin-top: 12px;
  line-height: 1.5;
}

/* ===== PROBLEM ===== */
.problem-intro {
  font-size: 19px;
  margin-bottom: 40px;
  max-width: 640px;
  line-height: 1.7;
}

.pain-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
}

.pain-card {
  padding: 28px;
  background: var(--bg);
  border: 1px solid var(--border);
  border-radius: var(--radius);
}

.pain-card p { font-size: 16px; line-height: 1.6; }

/* ===== PROGRAM ===== */
.program-list {
  list-style: none;
  counter-reset: prog;
}

.program-list li {
  counter-increment: prog;
  padding: 20px 0;
  border-bottom: 1px solid var(--border);
  font-size: 16px;
  display: flex;
  align-items: baseline;
  gap: 16px;
}

.program-list li::before {
  content: counter(prog, decimal-leading-zero);
  font-family: 'roboto', Georgia, serif;
  font-size: 14px;
  color: var(--accent);
  font-weight: 700;
  flex-shrink: 0;
  width: 28px;
}

.program-list li:last-child { border-bottom: none; }

.program-highlight {
  background: var(--accent);
  color: #fff;
  border-radius: var(--radius);
  padding: 24px 28px;
  margin-top: 24px;
  font-size: 16px;
}

.program-cta { margin-top: 40px; text-align: center; }

/* ===== RESULTS ===== */
.results-list {
  list-style: none;
  display: flex;
  flex-direction: column;
  gap: 16px;
}

.results-list li {
  padding: 24px;
  border-left: 3px solid var(--accent);
  background: var(--bg);
  border-radius: 0 var(--radius) var(--radius) 0;
  font-size: 16px;
  line-height: 1.6;
}

/* ===== SPEAKER ===== */
.speaker-inner {
  display: flex;
  gap: 48px;
  align-items: flex-start;
}

.speaker-photo { flex: 0 0 260px; }

.speaker-photo img {
  width: 100%;
  border-radius: var(--radius);
  object-fit: cover;
}

.speaker-info { flex: 1; }

.speaker-name {
  font-size: 28px;
  margin-bottom: 8px;
}

.speaker-title {
  color: #666;
  font-size: 16px;
  margin-bottom: 24px;
}

.speaker-credentials {
  list-style: none;
  margin-bottom: 28px;
}

.speaker-credentials li {
  padding: 8px 0;
  font-size: 15px;
  border-bottom: 1px solid var(--border);
}

.speaker-credentials li:last-child { border-bottom: none; }

.speaker-quote {
  font-style: italic;
  font-size: 16px;
  color: #555;
  border-left: 3px solid var(--accent);
  padding-left: 20px;
  margin-top: 8px;
}

/* ===== REVIEWS ===== */
.reviews-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
}

.review-card {
  padding: 28px;
  background: var(--bg);
  border: 1px solid var(--border);
  border-radius: var(--radius);
}

.review-text {
  font-size: 15px;
  font-style: italic;
  line-height: 1.7;
  color: #444;
}

.review-text::before { content: '«'; color: var(--accent); font-size: 20px; }
.review-text::after { content: '»'; color: var(--accent); font-size: 20px; }

/* ===== PRICING ===== */
.pricing-card {
  max-width: 520px;
  margin: 0 auto;
  padding: 48px 40px;
  border: 2px solid var(--accent);
  border-radius: var(--radius);
  text-align: center;
  background: var(--bg);
}

.pricing-card h3 {
  font-size: 24px;
  margin-bottom: 24px;
}

.pricing-includes {
  list-style: none;
  text-align: left;
  margin-bottom: 32px;
}

.pricing-includes li {
  padding: 10px 0;
  font-size: 15px;
  border-bottom: 1px solid #eee;
  padding-left: 24px;
  position: relative;
}

.pricing-includes li::before {
  content: '✓';
  position: absolute;
  left: 0;
  color: var(--accent);
  font-weight: 700;
}

.pricing-includes li:last-child { border-bottom: none; }

.pricing-includes li.highlight-item {
  font-weight: 600;
  color: var(--text-heading);
}

.pricing-prices { margin-bottom: 28px; }

.pricing-foreign {
  margin-top: 16px;
  font-size: 14px;
}

.pricing-foreign a { color: var(--accent); text-decoration: underline; }

/* ===== FAQ ===== */
.faq-item { border-bottom: 1px solid var(--border); }

.faq-question {
  width: 100%;
  background: none;
  border: none;
  padding: 24px 0;
  text-align: left;
  font-family: 'Manrope', sans-serif;
  font-size: 16px;
  font-weight: 600;
  color: var(--text-heading);
  cursor: pointer;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 16px;
}

.faq-question .faq-icon {
  font-size: 22px;
  color: var(--accent);
  flex-shrink: 0;
  transition: transform 0.2s;
}

.faq-item.open .faq-icon { transform: rotate(45deg); }

.faq-answer {
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.3s ease;
}

.faq-item.open .faq-answer { max-height: 300px; }

.faq-answer p {
  padding-bottom: 24px;
  font-size: 15px;
  color: #555;
}

.faq-answer a { color: var(--accent); }

/* ===== FOOTER ===== */
footer {
  padding: 40px 0;
  background: var(--text-heading);
  color: #aaa;
  font-size: 14px;
}

.footer-inner {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 16px;
}

.footer-brand {
  font-family: 'roboto', Georgia, serif;
  font-weight: 700;
  font-size: 16px;
  color: #fff;
  letter-spacing: 0.08em;
}

.footer-links a {
  color: #aaa;
  text-decoration: none;
  margin-left: 20px;
  transition: color 0.2s;
}

.footer-links a:hover { color: #fff; }

/* ===== RESPONSIVE ===== */
@media (max-width: 768px) {
  section { padding: 56px 0; }

  .hero-inner {
    flex-direction: column;
    gap: 32px;
    text-align: center;
  }

  .hero-photo-wrap { flex: none; width: 240px; margin: 0 auto; }
  .hero-subtitle { margin: 0 auto 24px; }
  .hero-pricing { justify-content: center; }
  .hero-timer { text-align: center; }

  .pain-grid,
  .reviews-grid {
    grid-template-columns: 1fr;
  }

  .speaker-inner {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .speaker-photo { flex: none; width: 200px; }
  .speaker-quote { text-align: left; }

  .pricing-card { padding: 36px 24px; }

  .footer-inner {
    flex-direction: column;
    text-align: center;
  }

  .footer-links a { margin: 0 10px; }
}
body {
  height: auto !important;
  overflow: auto !important;
}
</style>
</head>
<body>

<!-- ===== HERO ===== -->
<section class="hero">
  <div class="container">
    <div class="hero-inner">
      <div class="hero-text">
        <span class="hero-label">Онлайн мастер-класс · 3 мая</span>
        <h1 class="hero-title">Повышение прикуса<br>на практике</h1>
        <p class="hero-subtitle">Простой, пошаговый, безопасный алгоритм для предсказуемых результатов без осложнений</p>

        <div class="hero-pricing">
          <span class="price-current">7 900 ₽</span>
          <span class="price-old">9 900 ₽</span>
          <span class="price-usd">103$ <span style="text-decoration:line-through;color:#bbb">115$</span></span>
        </div>

        <div class="hero-timer">
          <div class="hero-timer-label">До повышения цены:</div>
          <script src="//megatimer.ru/get/678e509aa3b33c7a58b3405c2a7f7a0d.js"></script>
        </div>

        <a href="#pricing" class="btn">Записаться на мастер-класс</a>

        <div class="hero-bonuses">
          Рабочая тетрадь + Именной сертификат с подписью + Запись на 3 месяца
        </div>
      </div>
      <div class="hero-photo-wrap">
        <div class="hero-photo">
          <img src="https://i.imgur.com/J6FfRXk.png" alt="Илья Скляров — врач-ортопед, к.м.н.">
        </div>
        <p class="hero-photo-caption">Илья Скляров — врач-ортопед, к.м.н.,<br>основатель SmileClinic</p>
      </div>
    </div>
  </div>
</section>

<!-- ===== PROBLEM ===== -->
<section id="problem" class="alt-bg">
  <div class="container">
    <h2>Знакомо?</h2>
    <p class="problem-intro">Ошибка даже на 1–2 мм может кардинально повлиять на работу суставов, баланс мышц и эстетику лица.</p>
    <div class="pain-grid">
      <div class="pain-card">
        <p>Боитесь получить обострение в суставе или мышечный спазм после изменения высоты прикуса</p>
      </div>
      <div class="pain-card">
        <p>Не знаете, от какой точки отталкиваться, и работаете «на глаз» вместо протокола</p>
      </div>
      <div class="pain-card">
        <p>Не понимаете, когда прикус нужно повышать, а когда — снижать</p>
      </div>
      <div class="pain-card">
        <p>Избегаете тотальных работ из страха навредить суставу или увеличить нижнюю треть лица</p>
      </div>
    </div>
  </div>
</section>

<!-- ===== PROGRAM ===== -->
<section id="program">
  <div class="container">
    <h2>Программа мастер-класса</h2>
    <ol class="program-list">
      <li>3 подхода к повышению прикуса: эстетический, функциональный, структурный</li>
      <li>Формулы расчёта повышения высоты прикуса</li>
      <li>Повышение прикуса при различных скелетных классах</li>
      <li>«Красные флаги» для повышения прикуса</li>
      <li>Разбор повышения прикуса на примере клинических кейсов</li>
      <li>Алгоритм адаптации пациентов</li>
      <li>Чек-лист по выявлению противопоказаний</li>
      <li>Разборы мифов, связанных с повышением прикуса</li>
    </ol>
    <div class="program-highlight">
      Онлайн-сессия «вопрос-ответ» с Ильёй Скляровым — 45–60 минут живого общения
    </div>
    <div class="program-cta">
      <a href="#pricing" class="btn">Записаться на мастер-класс</a>
    </div>
  </div>
</section>

<!-- ===== RESULTS ===== -->
<section id="results" class="alt-bg">
  <div class="container">
    <h2>Что вы получите</h2>
    <ul class="results-list">
      <li>Конкретная формула расчёта новой высоты прикуса — без догадок и интуиции</li>
      <li>Пошаговый протокол: от фиксации исходной точки А до перевода пациента в новый прикус</li>
      <li>Понимание, когда прикус повышать, а когда снижать — и почему</li>
      <li>Протокол безопасной адаптации пациента на временных реставрациях</li>
      <li>Чек-лист из 12 пунктов для оценки дизайна улыбки: режущие края, окклюзионная плоскость и другие параметры</li>
      <li>Оценка рисков и «красных флагов» — чтобы не браться за кейсы, которые навредят</li>
    </ul>
  </div>
</section>

<!-- ===== SPEAKER ===== -->
<section id="speaker">
  <div class="container">
    <h2>Спикер</h2>
    <div class="speaker-inner">
      <div class="speaker-photo">
        <img src="https://i.imgur.com/J6FfRXk.png" alt="Илья Скляров">
      </div>
      <div class="speaker-info">
        <h3 class="speaker-name">Илья Скляров</h3>
        <p class="speaker-title">Врач-ортопед, к.м.н., основатель и главный идеолог SmileClinic</p>
        <ul class="speaker-credentials">
          <li>Клиника в ТОП лучших клиник мира (Leading Dental Centers of The World)</li>
          <li>Лучший стоматолог-ортопед 2024 (Startsmile TOP & Forbes)</li>
          <li>Первый в России сертифицированный ментор KoisCenter (Сиэтл, США)</li>
          <li>Основатель и лектор Sklyarov Center</li>
        </ul>
        <blockquote class="speaker-quote">
          «Я объездил весь мир в поисках лучших практик, внедрил их в свою работу в России и теперь готов поделиться этим опытом с вами на мастер-классе»
        </blockquote>
      </div>
    </div>
  </div>
</section>

<!-- ===== REVIEWS ===== -->
<section id="reviews" class="alt-bg">
  <div class="container">
    <h2>Отзывы участников</h2>
    <div class="reviews-grid">
      <div class="review-card">
        <p class="review-text">Я осталась в восторге от курса! Очень подробно и доходчиво подается информация, все четко и информативно! Отдельно большое спасибо службе заботы, которые всегда находились на связи. Искренне рекомендую коллегам, курс действительно стоит своих денег!</p>
      </div>
      <div class="review-card">
        <p class="review-text">Благодаря Вашему курсу весь мой подход к пациентам поменялся, как будто всю свою практику я ждала этого курса. Все планирование встало на свои места.</p>
      </div>
      <div class="review-card">
        <p class="review-text">Хотелось бы поблагодарить организаторов курса и лично Илью Александровича за такой замечательный курс. Немного отпугивала цена, но курс себя полностью оправдал, ни о чём не жалею. Хочу на офлайн курс к вам!</p>
      </div>
      <div class="review-card">
        <p class="review-text">Все по полкам разложено и без лишней воды!</p>
      </div>
    </div>
  </div>
</section>

<!-- ===== PRICING ===== -->
<section id="pricing">
  <div class="container">
    <h2 style="text-align:center;">Участие в мастер-классе</h2>
    <div class="pricing-card">
      <h3>Повышение прикуса на практике</h3>
      <ul class="pricing-includes">
        <li>Онлайн мастер-класс</li>
        <li>Лайф-сессия «вопрос-ответ» с Ильёй Скляровым</li>
        <li>Рабочая тетрадь и полезные материалы</li>
        <li class="highlight-item">Именной сертификат с подписью Ильи Склярова</li>
        <li>Доступ к записи на 3 месяца</li>
      </ul>
      <div class="pricing-prices">
        <div class="hero-pricing" style="justify-content:center;">
          <span class="price-current">7 900 ₽</span>
          <span class="price-old">9 900 ₽</span>
        </div>
        <div class="price-usd" style="margin-top:8px;">103$ <span style="text-decoration:line-through;color:#bbb">115$</span></div>
      </div>
      <button class="btn gc-buy-btn">Оплатить участие</button>
      <div class="pricing-foreign">
        <a href="#faq">Оплатить зарубежной картой →</a>
      </div>
    </div>
  </div>
</section>

<!-- ===== FAQ ===== -->
<section id="faq" class="alt-bg">
  <div class="container">
    <h2>Частые вопросы</h2>
    <div class="faq-item">
      <button class="faq-question">Будет ли запись мастер-класса? <span class="faq-icon">+</span></button>
      <div class="faq-answer">
        <p>Да, запись будет доступна в личном кабинете на GetCourse в течение 3 месяцев после мастер-класса.</p>
      </div>
    </div>
    <div class="faq-item">
      <button class="faq-question">Можно ли оплатить зарубежной картой? <span class="faq-icon">+</span></button>
      <div class="faq-answer">
        <p>Да, оплата зарубежной картой возможна. Свяжитесь с нами в <a href="https://wa.me/79770891702?text=%D0%97%D0%B4%D1%80%D0%B0%D0%B2%D1%81%D1%82%D0%B2%D1%83%D0%B9%D1%82%D0%B5!%20%D0%A5%D0%BE%D1%87%D1%83%20%D0%BE%D0%BF%D0%BB%D0%B0%D1%82%D0%B8%D1%82%D1%8C%20%D0%B7%D0%B0%D1%80%D1%83%D0%B1%D0%B5%D0%B6%D0%BD%D0%BE%D0%B9%20%D0%BA%D0%B0%D1%80%D1%82%D0%BE%D0%B9">WhatsApp</a> или <a href="https://t.me/+79770891702">Telegram</a> для получения инструкции.</p>
      </div>
    </div>
    <div class="faq-item">
      <button class="faq-question">Я оплатил(-а), но не пришёл доступ <span class="faq-icon">+</span></button>
      <div class="faq-answer">
        <p>Проверьте папку «Спам» в почте. Если письма нет — напишите нам в <a href="https://wa.me/79770891702?text=%D0%97%D0%B4%D1%80%D0%B0%D0%B2%D1%81%D1%82%D0%B2%D1%83%D0%B9%D1%82%D0%B5!%20%D0%9D%D0%B5%20%D0%BF%D1%80%D0%B8%D1%88%D0%B5%D0%BB%20%D0%B4%D0%BE%D1%81%D1%82%D1%83%D0%BF">WhatsApp</a> или <a href="https://t.me/+79770891702">Telegram</a>, поможем разобраться.</p>
      </div>
    </div>
  </div>
</section>

<!-- ===== FOOTER ===== -->
<footer>
  <div class="container">
    <div class="footer-inner">
      <div class="footer-brand">SKLYAROVCENTER</div>
      <div style="color:#888;">© 2025 Все права защищены</div>
      <div class="footer-links">
        <a href="https://wa.me/79770891702?text=%D0%97%D0%B4%D1%80%D0%B0%D0%B2%D1%81%D1%82%D0%B2%D1%83%D0%B9%D1%82%D0%B5!%20%D0%A3%20%D0%BC%D0%B5%D0%BD%D1%8F%20%D0%B2%D0%BE%D0%B7%D0%BD%D0%B8%D0%BA%20%D0%B2%D0%BE%D0%BF%D1%80%D0%BE%D1%81%20%D0%BF%D0%BE%20%D0%BC%D0%B0%D1%81%D1%82%D0%B5%D1%80-%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D1%83" target="_blank">WhatsApp</a>
        <a href="https://t.me/+79770891702" target="_blank">Telegram</a>
      </div>
    </div>
  </div>
</footer>

<!-- GetCourse payment widget -->
<script id="173aa51a9c3a4f2b6d863b572040b2e73d534520" src="https://school-sklyarovcenter.ru/pl/lite/widget/script?id=1591244"></script>

<script>
document.querySelectorAll('.faq-question').forEach(function(btn) {
  btn.addEventListener('click', function() {
    var item = btn.closest('.faq-item');
    item.classList.toggle('open');
  });
});
</script>

</body>
</html>
