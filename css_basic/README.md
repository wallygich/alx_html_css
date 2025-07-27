# alx_html_css
# Responsive Web Layout Project

This project is a simple, responsive website built using **only HTML, CSS, and JavaScript**. It follows strict web standards and includes clean design practices while avoiding the use of any external libraries or frameworks.

## 📁 Project Structure

.
├── index.html # Main homepage
├── tweets.html # A sample page with a tweet feed table
├── base.css # Core styles and layout, including flexbox grid
├── style.css # Custom styling (colors, typography, etc.)
└── README.md # This file

markdown
Copy
Edit

## 🧩 Features

- ✅ Fully **responsive** layout using CSS Flexbox
- ✅ Viewport meta tag for proper mobile scaling
- ✅ Clean, minimalist theme with custom color and font enhancements
- ✅ Unicode logo (`★`) for a personal touch
- ✅ Semantic HTML structure (header, article, aside, footer)
- ✅ Stylish tweet table on `tweets.html`

## 🚫 Restrictions

- ❌ No external CSS or JavaScript libraries allowed (e.g., no Bootstrap, React, Vue, etc.)
- ❌ No changes to the Flexbox layout strategy defined in `base.css`
- ✅ All enhancements done in `style.css` only (non-positioning styles)

## 🧪 Compliance

- All code passes [W3C HTML Validation](https://validator.w3.org/)
- CSS is W3C-compliant
- All files end with a new line

## 📝 Instructions

To make the site render properly on smartphones:

1. Add the class `works_on_smartphone` to the `<body>` tag.
2. Ensure the following meta tag is present in the `<head>`:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">