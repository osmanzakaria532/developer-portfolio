# developer-portfolio



---

## 🧠 Code Summary

This HTML file is a **basic personal portfolio landing page** that includes:

- A header with navigation
- A banner with an image, title, short bio, and buttons

---

## 🔍 Detailed Structure

### 1. `<!DOCTYPE html>`

Declares the document type as HTML5.

---

### 2. `<head>`

Contains meta and link tags:

- `<meta charset="UTF-8">` ensures character encoding is UTF-8.
- `<meta name="viewport"...>` sets responsive design.
- `<link rel="stylesheet" href="styles/style.css">` links to external CSS.

---

### 3. `<body class="open-sans">`

Applies a font class, possibly from a CSS import (likely from Google Fonts).

---

### 4. `<header class="header">`

Main header element with two parts:

#### ✅ Navigation (`<nav>`)

- **Logo**: `ma<span class="text-primary">r</span>y` (the "r" is styled differently).
- **Menu Items**:
  - Portfolio
  - Blog
  - Hire Me (button styled with class `btn-primary`)

#### ✅ Banner Section (`<div class="banner">`)

Contains:

- **Developer Image**: Left side (`developer.png`)
- **Intro Content**:
  - Greeting: "Hi, I am"
  - Name: "Mary Hardy"
  - Description Paragraph
  - Buttons:
    - Download CV
    - Contact (Both with Font Awesome icons, class: `fa-solid`)
- **Profile Image**: Positioned separately (`hardy.png`)

---

## 🧩 External Dependencies

- **CSS File**: `styles/style.css` handles all layout and styling.
- **Font Awesome Icons**: Used for download and phone buttons (not included in the HTML, must be loaded in `<head>`).
- **Images**: Two image assets are used (`developer.png`, `hardy.png`).

---

## ⚠️ Issues / Suggestions

1. **Font Awesome Not Linked**
   - Add the following in `<head>` to enable icons:
     ```html
     <script src="https://kit.fontawesome.com/yourkitid.js" crossorigin="anonymous"></script>
     ```

2. **Broken Anchor Closing**
   - In the blog list item:
     ```html
     <li>
       <a href="">blog</a></a> <!-- Extra </a> tag -->
     </li>
     ```

3. **Accessibility**
   - Use `alt` text that describes the image content meaningfully.
   - Use semantic tags (like `<main>`, `<section>`) for better structure.

---

## ✅ Good Practices Used

- Semantic HTML (`<nav>`, `<header>`)
- Separation of concerns (HTML + external CSS)
- Use of CSS classes for styling

---

## 📌 Next Steps / Enhancements

- Add proper routes or `href` values to the `<a>` tags
- Link to a real downloadable CV file
- Add footer section with social links
- Improve responsive design using media queries

---

## 📸 Preview Design Elements

| Section | Element | Description |
|--------|---------|-------------|
| Header | Logo & Nav | Shows name and menu |
| Banner | Intro Text | Includes greeting, name, short bio |
| Banner | Buttons | Download CV & Contact |
| Images | Developer & Profile | Visual appeal and branding |

---

## 🛠 Technologies Used

- **HTML5**
- **CSS3** (linked externally)
- **Font Awesome (icon library)** *(requires linking)*

---

## 📁 Author Notes

> This is a good starter layout for a portfolio homepage. With a few improvements and proper styling, it can evolve into a complete personal website.
