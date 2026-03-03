# Nothing - Landing Page
A responsive landing page for store **Nothing** — built with pure HTML and SCSS, bundled with Parcel.

🔗 Demo
---
[Live DEMO](https://tetianasobolieva.github.io/layout_landing-page-N/#categories))

## 🎨Design
[Nothing](https://www.figma.com/file/DtkQmQ797hk0nI4KfMi2Uq/BOSE-New-Version?type=design&node-id=6802-139&t=L7eKz5YKLN0m5WxR-0)

## 🛠 Tech Stack
---

* **HTML5** — semantic markup
* **CSS3 / SCSS** — styling with variables, nesting and partials
* **Parcel** — module bundler and dev server

## 📁 Project Structure
---

```textlayout_landing-page-N/
├── .github/workflows/      # GitHub Actions settings (CI/CD)
├── src/                    # Project source files
│   ├── images/             # Graphic assets (png, svg)
│   │   └── icons/          # Interface icons
│   ├── scripts/            # JavaScript logic
│   │   └── main.js         # Main script file
│   ├── styles/             # Project styles (SCSS)
│   │   ├── blocks/         # Styles for individual components/blocks
│   │   ├── utils/          # Helper files (variables, mixins)
│   │   └── index.scss      # Main stylesheet
│   └── index.html          # Main page template
├── .parcel-cache/          # Parcel bundler cache
├── node_modules/           # Project dependencies
└── README.md               # Project description

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
