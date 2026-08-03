# Mechanics In Design

![HTML5](https://img.shields.io/badge/HTML5-orange?style=for-the-badge&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-blue?style=for-the-badge&logo=css3)
![Git](https://img.shields.io/badge/Git-red?style=for-the-badge&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github)
![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-success?style=for-the-badge&logo=github)

A responsive two-page landing website built with **HTML5** and **CSS3** showcasing:

- **Modern Furniture**
- **Professional Vehicle Diagnostics**

This project demonstrates responsive web design, semantic HTML5, modern CSS3, Git version control, GitHub collaboration, and deployment with GitHub Pages.

---

[Live Demo](https://eyongtarh.github.io/mechasign/)

---

[GitHub Repository](https://github.com/eyongtarh/mechasign)

---

# Table of Contents

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
- [Pull Request Example](#pull-request-example)
- [Testing](#testing)
- [Future Improvements](#future-improvements)
- [Learning Outcomes](#learning-outcomes)
- [Screenshots](#screenshots)
- [Author](#author)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

# Project Overview

Mechanics In Design is a responsive website consisting of two modern landing pages.

## Furniture Landing Page

The Furniture page showcases stylish furniture products using a clean hero layout.

Features include:

- Responsive hero section
- Product image
- Product description
- Call-to-action button
- Responsive layout

---

## Vehicle Diagnostics Landing Page

The Diagnostics page promotes professional vehicle diagnostic services.

Features include:

- Responsive hero section
- Service image
- Service description
- Call-to-action button
- Responsive layout

---

# Features

- Responsive two-page website
- Furniture landing page
- Vehicle diagnostics landing page
- Responsive navigation bar
- Hero sections
- Call-to-action buttons
- Responsive images
- Mobile-friendly layout
- Semantic HTML5
- Modern CSS3 styling
- Flexbox layout
- Clean and maintainable code
- Git version control
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

Move into the project directory.

```bash
cd mechasign
```

---

# Running the Project

## Option 1 — Live Server (Recommended)

1. Open the project in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click **index.html**.
4. Select:

```
Open with Live Server
```

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

to open the project in your default browser.

---

## Option 3 — GitHub Pages

Visit the deployed version:

[GitHub Repository](https://github.com/eyongtarh/mechasign)

---

# Deployment

This project is deployed using **GitHub Pages**.

[Live Website](https://eyongtarh.github.io/mechasign/)

Whenever updates are merged into the **main** branch, GitHub Pages automatically rebuilds and publishes the latest version of the site.

---

# Website Pages

## Furniture Page

**File**

```text
index.html
```

**Purpose**

- Showcase modern furniture collections.
- Present featured furniture products.
- Encourage visitors to browse furniture designs.

---

## Diagnostics Page

**File**

```text
diagnostics.html
```

**Purpose**

- Promote professional vehicle diagnostic services.
- Explain available diagnostic solutions.
- Encourage customers to schedule a vehicle inspection.

---

# Navigation

The website includes a responsive navigation menu for switching between both landing pages.

| Navigation Link | Destination        |
| --------------- | ------------------ |
| Furniture       | `index.html`       |
| Diagnostics     | `diagnostics.html` |

---

# Responsive Design

The website includes:

- Responsive navigation
- Flexbox layouts
- Responsive hero sections
- Responsive images
- Mobile-friendly design
- Modern typography
- Hover effects
- Rounded buttons
- Flexible spacing

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

---

Check modified files.

```bash
git status
```

---

Stage files.

```bash
git add .
```

---

Commit changes.

```bash
git commit -m "Improve furniture and diagnostics landing pages"
```

---

Push the branch.

```bash
git push -u origin improve-landing-pages
```

---

Open GitHub.

Create a Pull Request.

Merge into **main** after approval.

---

# Pull Request Example

## Title

```
Improve furniture and diagnostics landing pages
```

## Description

```markdown
## Summary

- Redesigned both landing pages
- Added responsive hero sections
- Added call-to-action buttons
- Improved navigation
- Enhanced typography and spacing
- Improved overall user experience

## Testing

- Opened both pages in browser
- Verified navigation links
- Verified images load correctly
- Checked responsive layout
```
