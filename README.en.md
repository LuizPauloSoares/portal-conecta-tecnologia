# Portal Conecta Tecnologia

[🇧🇷 Português](README.md) | [🇺🇸 English](README.en.md)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/status-completed-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)

Educational activity of **refactoring an HTML 4.01 page into semantic HTML5**, with modern CSS in a separate file. The project keeps the content and look of the original portal, replacing layout tables, `<font>` tags and obsolete attributes with semantic tags, Grid and CSS.

## 📑 Table of Contents

- [What the code does](#-what-the-code-does)
- [How it works](#-how-it-works)
- [Technologies used](#-technologies-used)
- [File structure](#-file-structure)
- [Prerequisites](#-prerequisites)
- [How to clone the project](#-how-to-clone-the-project)
- [Installation and setup](#-installation-and-setup)
- [Usage examples](#-usage-examples)
- [What changed: HTML 4.01 → HTML5](#-what-changed-html-401--html5)
- [Project status](#-project-status)
- [Roadmap](#-roadmap)
- [License](#-license)
- [Author and credits](#-author-and-credits)
- [Contact](#-contact)

## 💡 What the code does

**Portal Conecta Tecnologia** is a fictional institutional page about programming, innovation and professional training. It contains:

- Header and navigation menu with buttons
- Welcome section
- Latest news
- List of available courses
- Activity schedule (table)
- Contact form (demo only, does not send data)
- Sidebar with highlights, useful links and a poll (demo only)
- Footer with a "Back to top" link

## ⚙️ How it works

- `index.html` defines the **structure and meaning** of the content, using semantic tags.
- `estilo.css` handles **all the appearance**: colors, fonts, spacing and layout.
- The two-column layout (main content + sidebar) uses **CSS Grid** applied to the `body`.
- On screens up to 768px wide, a **media query** switches everything to a single column.
- The form and the poll are demo only and do not send data to any server.

## 🛠️ Technologies used

- **HTML5** (semantic tags: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`)
- **CSS3** (Grid, Flexbox, media queries, transitions)

## 📁 File structure

```
portal-conecta-tecnologia/
├── index.html        # Refactored HTML5 version
├── refatora.html     # Original HTML 4.01 version (for comparison)
├── estilo.css        # Styles for the HTML5 version
├── README.md         # Portuguese version
└── README.en.md      # This file (English)
```

## 📋 Prerequisites

- A current browser (Chrome, Firefox, Edge or Safari)
- Optional: [Git](https://git-scm.com/) to clone the repository
- Optional: a code editor, such as [VS Code](https://code.visualstudio.com/)

There are no dependencies and no packages to install.

## 📥 How to clone the project

```bash
git clone https://github.com/LuizPauloSoares/portal-conecta-tecnologia.git
cd portal-conecta-tecnologia
```

## 🚀 Installation and setup

1. Clone the repository (command above) or download the ZIP using GitHub's **Code** button.
2. Keep `index.html` and `estilo.css` **in the same folder**.
3. Open `index.html` by double-clicking it or drag the file into your browser.
4. To see the original version, open `refatora.html` and compare both pages.

## 🖼️ Usage examples

> Add the project screenshots here (for example, in a `docs/` folder).

```
![HTML5 version](docs/screenshot-html5.png)
![HTML 4.01 version](docs/screenshot-html4.png)
```

- Click the menu buttons to navigate between sections.
- Shrink the browser window below 768px to see the responsive layout.
- Hover over the menu and form buttons to see the transitions.

## 🔄 What changed: HTML 4.01 → HTML5

| HTML 4.01 (`refatora.html`) | HTML5 (`index.html` + `estilo.css`) |
|---|---|
| Long `<!DOCTYPE HTML PUBLIC ...>` | `<!DOCTYPE html>` |
| `<meta http-equiv="Content-Type">` | `<meta charset="UTF-8">` |
| No language set | `<html lang="pt-BR">` |
| Layout built with `<table>` | `<header>`, `<nav>`, `<main>`, `<aside>`, `<footer>` + CSS Grid |
| `<font>` tags | CSS classes |
| `bgcolor`, `text`, `link`, `align` attributes | CSS properties |
| `<a name="topo">` | `id="topo"` |
| Blocks separated by `<hr>` | `<section>` and `<article>` |
| Loose text in form fields | `<label for>` + `id` |
| Email with `type="text"` | `type="email"` |
| `<b>` and `<i>` | `<strong>` and `<em>` |
| `<input type="button">` | `<button type="button">` |
| External links without `rel` | `rel="noopener noreferrer"` |
| Not responsive | `<meta viewport>` + media query |

## 📌 Project status

✅ **Completed** as an educational activity. Future improvements are in the roadmap.

## 🗺️ Roadmap

- [ ] Use CSS variables (`:root`) for colors
- [ ] Add `scroll-behavior: smooth` to the navigation
- [ ] Create a dedicated class for the news titles
- [ ] Use `<fieldset>` and `<legend>` in the poll
- [ ] Add a hamburger menu for mobile
- [ ] Validate the HTML and CSS with the [W3C Validator](https://validator.w3.org/)
- [ ] Publish on GitHub Pages

## 📄 License

Distributed under the **MIT** license. See the `LICENSE` file for more details.

## 👤 Author and credits

**Luiz Paulo Soares dos Santos**

Educational activity on modernizing HTML 4.01 into HTML5.

## 📬 Contact

- 📧 Email: [luizdayspring@gmail.com](mailto:luizdayspring@gmail.com)
- 📸 Instagram: [@lu1z_st](https://www.instagram.com/lu1z_st/)
- 💼 LinkedIn: [luiz-paulo-soares](https://www.linkedin.com/in/luiz-paulo-soares/)
- 🐙 GitHub: [LuizPauloSoares](https://github.com/LuizPauloSoares)
