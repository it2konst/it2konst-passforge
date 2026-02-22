<div align="center">

# 🔐 PassForge

### Cryptographically secure password generator

**Beautifully crafted, single-file, zero-dependency password generator that runs entirely in your browser.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![No Dependencies](https://img.shields.io/badge/dependencies-0-brightgreen)]()

[English](#-features) · [Русский](#-возможности)

</div>

---

## 🌐 English

### ✨ Features

**Password Generation**

- Cryptographically secure randomness via `crypto.getRandomValues()`
- Adjustable length from 4 to 64 characters
- Four character types: uppercase, lowercase, digits, symbols
- Guaranteed inclusion of at least one character from each selected type
- Fisher-Yates shuffle for unbiased distribution

**Strength Analysis**

- Real-time entropy-based strength calculation
- Brute-force crack time estimation (assuming 10 billion guesses/sec)
- Color-coded animated strength bar (red → orange → purple → green)
- Five strength levels: Very Weak, Weak, Good, Strong, Excellent

**User Experience**

- Dark / Light theme with smooth transitions and `localStorage` persistence
- One-click copy to clipboard with visual confirmation
- Session-based password history (last 8 passwords)
- Toast notification system
- Keyboard shortcut: `Space` to regenerate instantly
- Shake animation when attempting to deselect the last character type

**Design & Animations**

- Glassmorphism navigation with backdrop blur
- Floating gradient orb background animations
- SVG noise texture overlay
- Staggered entrance animations (fadeUp)
- Scroll-reveal via IntersectionObserver
- Fully responsive - mobile, tablet, desktop

**Content**

- Security tips section with 6 actionable cards
- FAQ accordion with smooth expand/collapse transitions

### 🛡️ Privacy

PassForge runs **100% client-side**. No data is ever sent to any server. No cookies, no tracking, no analytics. Your passwords never leave your device.

### 🚀 Quick Start

No build tools, no dependencies. Just open the file:

```bash
git clone https://github.com/it2konst/passforge.git
cd passforge
open index.html
```

Or deploy to any static hosting: GitHub Pages, Netlify, Vercel, Cloudflare Pages - just upload `index.html`.

### 🏗️ Tech Stack

| Technology             | Purpose                                    |
| ---------------------- | ------------------------------------------ |
| HTML5                  | Semantic structure                         |
| CSS3 Custom Properties | Theming system (30+ variables)             |
| Vanilla JavaScript     | All logic, zero dependencies               |
| Web Crypto API         | Cryptographically secure random generation |
| IntersectionObserver   | Scroll-triggered animations                |
| localStorage           | Theme preference persistence               |

### 📁 Project Structure

```
passforge/
└── index.html    ← entire app in a single file
```

Yes, that's it. One file. ~1300 lines of clean, commented code containing HTML structure, CSS styles, and JavaScript logic.

### ⌨️ Keyboard Shortcuts

| Key     | Action                |
| ------- | --------------------- |
| `Space` | Generate new password |

### 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'feat: add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🇷🇺 Русский

### ✨ Возможности

**Генерация паролей**

- Криптографически стойкая случайность через `crypto.getRandomValues()`
- Настраиваемая длина от 4 до 64 символов
- Четыре типа символов: заглавные, строчные, цифры, спецсимволы
- Гарантированное включение минимум одного символа каждого выбранного типа
- Перемешивание по алгоритму Фишера-Йетса для равномерного распределения

**Анализ надёжности**

- Расчёт надёжности в реальном времени на основе энтропии
- Оценка времени взлома брутфорсом (при 10 млрд попыток/сек)
- Анимированная цветовая шкала (красный → оранжевый → фиолетовый → зелёный)
- Пять уровней: Очень слабый, Слабый, Хороший, Сильный, Отличный

**Пользовательский опыт**

- Тёмная / Светлая тема с плавными переходами и сохранением в `localStorage`
- Копирование в буфер обмена одним нажатием с визуальным подтверждением
- Сессионная история паролей (последние 8)
- Система toast-уведомлений
- Горячая клавиша: `Пробел` для моментальной перегенерации
- Shake-анимация при попытке отключить последний тип символов

**Дизайн и анимации**

- Навигация с эффектом glassmorphism и backdrop blur
- Плавающие градиентные orbs на фоне
- SVG noise-текстура для глубины
- Каскадные анимации появления (fadeUp)
- Scroll-reveal через IntersectionObserver
- Полная адаптивность - мобильные, планшеты, десктоп

**Контент**

- Секция советов по безопасности (6 карточек)
- FAQ-аккордеон с плавным раскрытием

### 🛡️ Приватность

PassForge работает **на 100% на стороне клиента**. Никакие данные не отправляются на сервер. Без cookies, без трекинга, без аналитики. Ваши пароли никогда не покидают ваше устройство.

### 🚀 Быстрый старт

Без сборщиков, без зависимостей. Просто откройте файл:

```bash
git clone https://github.com/it2konst/passforge.git
cd passforge
open index.html
```

Или разверните на любом статическом хостинге: GitHub Pages, Netlify, Vercel, Cloudflare Pages - просто загрузите `index.html`.

### 🏗️ Технологии

| Технология             | Назначение                              |
| ---------------------- | --------------------------------------- |
| HTML5                  | Семантическая структура                 |
| CSS3 Custom Properties | Система тем (30+ переменных)            |
| Vanilla JavaScript     | Вся логика, ноль зависимостей           |
| Web Crypto API         | Криптостойкая генерация случайных чисел |
| IntersectionObserver   | Анимации при скролле                    |
| localStorage           | Сохранение выбранной темы               |

### ⌨️ Горячие клавиши

| Клавиша  | Действие                   |
| -------- | -------------------------- |
| `Пробел` | Сгенерировать новый пароль |

### 🤝 Вклад в проект

Буду рад вашему участию! Порядок действий:

1. Сделайте форк репозитория
2. Создайте ветку (`git checkout -b feature/amazing-feature`)
3. Зафиксируйте изменения (`git commit -m 'feat: add amazing feature'`)
4. Отправьте ветку (`git push origin feature/amazing-feature`)
5. Откройте Pull Request

### 📄 Лицензия

Проект лицензирован под MIT - подробности в файле [LICENSE](LICENSE).

---

<div align="center">

Made with ❤️ and pure vanilla code

**⭐ Star this repo if you find it useful!**

</div>
