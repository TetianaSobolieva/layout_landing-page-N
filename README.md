# Nothing - Landing Page
A responsive landing page for store **Nothing** — built with pure HTML and SCSS, bundled with Parcel.

🔗 Demo
---
[Live DEMO](https://tetianasobolieva.github.io/layout_landing-page-N/)

## 🎨Design
[Nothing](https://www.figma.com/file/DtkQmQ797hk0nI4KfMi2Uq/BOSE-New-Version?type=design&node-id=6802-139&t=L7eKz5YKLN0m5WxR-0)

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

```
## 🚀 Getting Started
---
### Prerequisites

- **Node.js** v14+
- **npm**
### Installation

```bash
# Clone the repository
git clone https://github.com/TetianaSobolieva/layout_landing-page-N.git

# Navigate to the project folder
cd landing-page-N

# Install dependencies
npm install
```
### Running locally
```bash
npm start
```
The app will open at http://localhost:1234

### Build for production
```
npm run build
```

# 🧱 Разделы страницы (Sections)
---

- **Header** — logo, phone number, burger menu  
- **Menu** — mobile navigation overlay  
- **Recommended** — featured product cards  
- **Store** — product categories  
- **About us** — company description  
- **Contact us** — contact form and info
