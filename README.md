# Mechanics In Design

![HTML5](https://img.shields.io/badge/HTML5-HTML5-orange?style=for-the-badge&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-CSS3-blue?style=for-the-badge&logo=css3)
![Git](https://img.shields.io/badge/Git-Version%20Control-red?style=for-the-badge&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)
![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub%20Pages-success?style=for-the-badge&logo=github)

A responsive two-page landing website built with **HTML5** and **CSS3** showcasing:

- 🪑 Modern Furniture
- 🚗 Professional Vehicle Diagnostics

This project demonstrates responsive web design, semantic HTML5, modern CSS3, Git version control, GitHub collaboration, and deployment with GitHub Pages.

---

## [🌐Live Demo](https://eyongtarh.github.io/mechasign/)

---

## [📂 GitHub Repository](https://github.com/eyongtarh/mechasign)

---

# 📖 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Running the Project](#running-the-project)
- [Deployment](#deployment)
- [Website Pages](#website-pages)
- [Navigation](#navigation)
- [Responsive Design](#responsive-design)
- [Git Workflow](#git-workflow)
- [Pull Request Workflow](#pull-request-workflow)
- [Testing](#testing)
- [Future Improvements](#future-improvements)
- [Learning Outcomes](#learning-outcomes)
- [Screenshots](#screenshots)
- [Author](#author)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

# Project Overview

**Mechanics In Design** is a responsive multi-page website consisting of two modern landing pages.

The project was built to practice:

- Semantic HTML5
- CSS3 styling
- Responsive web design
- Git branching
- GitHub Pull Requests
- GitHub Pages deployment

---

## 🪑 Furniture Landing Page

**File**

```text
index.html
```

The Furniture page showcases stylish furniture products using a clean hero layout.

### Features

- Responsive hero section
- Modern typography
- Furniture image
- Call-to-action button
- Responsive navigation
- Mobile-friendly layout

---

## 🚗 Vehicle Diagnostics Landing Page

**File**

```text
diagnostics.html
```

The Diagnostics page promotes professional vehicle diagnostic services.

### Features

- Responsive hero section
- Vehicle image
- Service description
- Call-to-action button
- Responsive navigation
- Mobile-friendly layout

---

# Features

- Responsive two-page website
- Modern navigation bar
- Furniture landing page
- Vehicle diagnostics landing page
- Hero sections
- Call-to-action buttons
- Responsive images
- Responsive layout using Flexbox
- Semantic HTML5
- Modern CSS3 styling
- Accessible navigation
- Footer
- GitHub Pages deployment

---

# Project Structure

```text
mechasign/
│
├── assets/
│   ├── css/
│   │   └── style.css
│   │
│   └── images/
│       ├── car.jpg
│       └── table.jpg
│
├── index.html
├── diagnostics.html
├── README.md
└── .gitignore
```

---

# Technologies Used

- HTML5
- CSS3
- Git
- GitHub
- GitHub Pages
- Visual Studio Code

---

# Getting Started

## Clone the Repository

```bash
git clone https://github.com/eyongtarh/mechasign.git
```

Move into the project folder.

```bash
cd mechasign
```

---

# Running the Project

## Option 1 — Live Server (Recommended)

1. Open the project in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click **index.html**.
4. Select **Open with Live Server**.

The website opens at:

```
http://127.0.0.1:5500/index.html
```

---

## Option 2 — Open in Browser

Double-click:

```
index.html
```

to open the website in your default browser.

---

## Option 3 — GitHub Pages

[Visit the deployed website](https://eyongtarh.github.io/mechasign/)

---

# Deployment

This project is deployed using **GitHub Pages**.

[Live Website](https://eyongtarh.github.io/mechasign/)

Whenever new changes are merged into the **main** branch, GitHub Pages automatically rebuilds and publishes the latest version of the website.

---

# Website Pages

| Page        | File               | Description                      |
| ----------- | ------------------ | -------------------------------- |
| Furniture   | `index.html`       | Modern furniture landing page    |
| Diagnostics | `diagnostics.html` | Vehicle diagnostics landing page |

---

# Navigation

The website includes a responsive navigation bar allowing users to switch between both pages.

| Navigation  | Destination        |
| ----------- | ------------------ |
| Furniture   | `index.html`       |
| Diagnostics | `diagnostics.html` |

---

# Responsive Design

The website includes:

- Responsive navigation
- Flexbox layouts
- Hero sections
- Responsive images
- Hover animations
- Modern typography
- Mobile-friendly layout
- Responsive buttons
- Footer that stays at the bottom of the page

---

# Git Workflow

Create a feature branch.

```bash
git switch -c improve-landing-pages
```

or

```bash
git checkout -b improve-landing-pages
```

Check your changes.

```bash
git status
```

Stage your files.

```bash
git add .
```

Commit your changes.

```bash
git commit -m "Improve furniture and diagnostics landing pages"
```

Push the branch.

```bash
git push -u origin improve-landing-pages
```

Open GitHub and create a Pull Request.

Merge into **main** after approval.

---

# Pull Request Workflow

## Pull Request Title

```
Improve furniture and diagnostics landing pages
```

## Pull Request Description

```markdown
## Summary

- Redesigned both landing pages
- Added responsive hero sections
- Added call-to-action buttons
- Improved navigation
- Enhanced typography and spacing
- Added semantic HTML5 elements
- Improved accessibility
- Added responsive footer

## Testing

- Opened both pages in browser
- Verified navigation links
- Verified responsive layout
- Verified images load correctly
- Tested button hover effects
- Tested mobile responsiveness
```
