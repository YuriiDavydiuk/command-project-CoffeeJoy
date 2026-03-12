# ☕ CoffeeJoy

> **Насолоджуйся кожним ковтком. Знайди свою ідеальну каву.**

Веб-сайт магазину кави, який допомагає користувачам ознайомитися з асортиментом, дізнатися про продукцію та оформити підписку на новини.

---

## 🌐 Live Demo

🔗 [https://yuriidavydiuk.github.io/command-project-CoffeeJoy/](https://yuriidavydiuk.github.io/command-project-CoffeeJoy/)

---

## ✨ Функціонал

- ☕ **Меню/каталог** — перегляд асортименту кавової продукції
- 🪟 **Модальні вікна** — детальна інформація про продукти
- 💬 **Відгуки** — секція з відгуками задоволених клієнтів
- 📍 **Локація** — карта з адресою магазину
- 📧 **Форма підписки** — підписка на новини та акції
- 📱 **Адаптивна верстка** — підтримка мобільних (від 375px), планшетів (768px) та десктопів (1440px)
- 🍔 **Бургер-меню** — для мобільних пристроїв та планшету

---

## 🛠 Технології

| Категорія | Технологія |
|-----------|-----------|
| Розмітка | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) |
| Стилізація | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) |
| Логіка | ![JavaScript](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| Збірник | ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white) |
| Шрифти | Google Fonts |

---

## 🚀 Запуск проєкту

### Попередні вимоги

- [Node.js](https://nodejs.org/) v18+
- npm

### Інструкція

```bash
# 1. Клонуй репозиторій
git clone https://github.com/YuriiDavydiuk/command-project-CoffeeJoy.git

# 2. Перейди до папки проєкту
cd command-project-CoffeeJoy

# 3. Встанови залежності
npm install

# 4. Запусти dev-сервер
npm run dev
```

Проєкт відкриється за адресою `http://localhost:5173`

### Збірка для продакшну

```bash
npm run build
```

---

## 📁 Структура проєкту

```
command-project-CoffeeJoy/
├── src/
│   ├── css/
│   │   ├── reset.css              # Скидання стилів браузера
│   │   ├── base.css               # Базові стилі
│   │   ├── common.css             # Спільні компоненти
│   │   ├── container.css          # Контейнер та сітка
│   │   ├── header.css             # Хедер
│   │   ├── mobile-menu.css        # Бургер-меню
│   │   ├── hero.css               # Секція Hero
│   │   ├── welcome.css            # Секція привітання
│   │   ├── experience.css         # Секція досвіду
│   │   ├── quality.css            # Секція якості
│   │   ├── location.css           # Секція локації
│   │   ├── testimonials.css       # Секція відгуків
│   │   ├── subcribe.css           # Секція підписки
│   │   ├── success-sub.css        # Успішна підписка
│   │   ├── utils.css              # Утиліти
│   │   └── footer.css             # Футер
│   ├── img/                       # Зображення
│   ├── js/
│   │   ├── menu.js                # Логіка меню
│   │   └── modal-menu.js          # Бургер-меню
│   └── partials/
│       ├── header.html            # Розмітка хедера
│       ├── hero.html              # Розмітка секції Hero
│       ├── welcome.html           # Розмітка секції привітання
│       ├── experience.html        # Розмітка секції досвіду
│       ├── quality.html           # Розмітка секції якості
│       ├── location.html          # Розмітка секції локації
│       ├── testimonials.html      # Розмітка секції відгуків
│       ├── subscribe.html         # Розмітка секції підписки
│       ├── success-sub.html       # Розмітка успішної підписки
│       ├── mobile-menu.html       # Розмітка бургер-меню
│       └── footer.html            # Розмітка футера
├── public/
│   └── index.html                 # Точка входу
├── main.js                        # Головний JS-файл
├── vite.config.js                 # Конфігурація Vite
├── package.json
├── .prettierrc.json
├── .editorconfig
├── .gitignore
├── README.md                      # Документація (UA)
└── README.en.md                   # Документація (EN)
```

---

## 📐 Брейкпоінти

| Пристрій | Ширина |
|----------|--------|
| 📱 Mobile | від 375px |
| 📟 Tablet | від 768px |
| 🖥 Desktop | від 1440px |

---

## 👥 Команда

| Ім'я | Роль | GitHub |
|------|------|--------|
| Yurii Davydiuk | Developer | [@YuriiDavydiuk](https://github.com/YuriiDavydiuk) |

---

## 📄 Ліцензія

MIT © 2026 CoffeeJoy
