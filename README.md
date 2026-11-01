# TD7 – CSS Hamburger Menu in Mobile

## 📌 Project Overview
This project implements a responsive hamburger navigation menu for a Laundry Web App using HTML and CSS.

The hamburger menu is displayed only on mobile screens. When the user clicks the hamburger button, the navigation menu appears from the right side using the CSS `:focus` pseudo-class.

## ✨ Features
- Responsive navigation bar.
- Hamburger menu visible only on mobile screens.
- Navigation menu hidden by default.
- Menu appears when the hamburger button receives focus.
- Right-aligned menu panel.
- Navigation links for Home, Services, About Us, and Contact Us.
- No JavaScript used.

## 🛠️ Technologies Used
- HTML5
- CSS3
- Flexbox
- CSS Media Queries
- CSS `:focus` pseudo-class
- Adjacent Sibling Selector (`+`)

## 📂 Project Structure

```text
TD7-Hamburger-Menu/
│
├── index.html
├── style.css
└── README.md
```

## ⚙️ How It Works

1. The hamburger button is hidden by default on desktop screens.
2. CSS Media Queries make it visible on mobile screens.
3. The navigation menu is initially hidden using `display: none`.
4. The `:focus` pseudo-class detects when the hamburger button receives focus.
5. The adjacent sibling selector (`+`) displays the navigation menu.

## 🚀 How to Run

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Open `index.html` in your browser.
4. Use Chrome Developer Tools to switch to mobile responsive view.
5. Click the hamburger icon to view the navigation menu.

## 🎯 Learning Outcome

Learned how to create a CSS-only hamburger menu using Flexbox, media queries, pseudo-classes, and sibling selectors without JavaScript.

---

**Project:** Tutedude TD7 – CSS Hamburger Menu in Mobile  
**Status:** Completed
