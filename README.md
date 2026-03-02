# Nothing - Landing Page
A responsive landing page for store **Nothing** — built with pure HTML and SCSS, bundled with Parcel.

🔗 Demo
---
[Live DEMO](https://tetianasobolieva.github.io/layout_landing-page-N/)

## 🛠 Tech Stack
---

* **HTML5** — semantic markup
* **CSS3 / SCSS** — styling with variables, nesting and partials
* **Parcel** — module bundler and dev server

## 📁 Project Structure
---

```text
layout_landing-page-N/
├── .github/workflows/      # Настройки GitHub Actions (CI/CD)
├── src/                    # Исходные файлы проекта
│   ├── images/             # Графические ресурсы (png, svg)
│   │   └── icons/          # Иконки интерфейса
│   ├── scripts/            # JavaScript логика
│   │   └── main.js         # Основной файл скриптов
│   ├── styles/             # Стили проекта (SCSS)
│   │   ├── blocks/         # Стили отдельных компонентов/блоков
│   │   ├── utils/          # Вспомогательные файлы (переменные, миксины)
│   │   └── index.scss      # Главный файл стилей
│   └── index.html          # Главная страница (шаблон)
├── .parcel-cache/          # Кэш сборщика Parcel
├── node_modules/           # Зависимости проекта
└── README.md               # Описание проекта

```text

🧱 Разделы страницы (Sections)
Проект состоит из следующих функциональных блоков:

Header — навигационная панель с логотипом, контактным номером и функциональным бургер-меню.

Menu — полноэкранное мобильное меню (overlay) для удобной навигации на смартфонах.

Recommended — блок с карточками флагманских продуктов (Phone, Ear), включая цены и краткое описание.

Store — раздел с категориями товаров (Audio, Accessories) для быстрого перехода к покупкам.

About us — информационный блок о миссии и философии компании.

Contact us — подвал сайта с формой обратной связи и актуальными контактными данными.
