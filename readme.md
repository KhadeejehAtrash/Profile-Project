# Khadeejeh | Front-End Developer Portfolio

This is a personal portfolio website showcasing projects, built with **HTML, SCSS (BEM methodology)**, and fully **responsive design**.

---

## **Project Structure**

```
src/
├── index.html
├── main.scss
├── scss/
│   ├── base/
│   │   ├── _resets.scss
│   │   └── base.scss
│   ├── blocks/
│   │   ├── _header.scss
│   │   ├── _intro.scss
│   │   ├── _projects.scss
│   │   ├── _cards.scss
│   │   ├── _buttons.scss
│   │   └── _footer.scss
│   └── utils/
│       ├── _variables.scss
│       ├── _mixins.scss
│       └── utils.scss
├── assets/
│   ├── profile.png
│   ├── 1.png
│   ├── 2.png
│   └── project3.png
└── dist/
    └── main.css
```

---

## **Technologies Used**

- **HTML5** — Semantic markup (header, main, section, footer)  
- **SCSS / Sass** — Modular SCSS with variables, mixins, and nesting  
- **BEM methodology** — For class naming and structure  
- **Responsive Design** — Desktop, tablet, and mobile support  
- **CSS Features** — Transitions, scroll-snap, clamp for typography  

---

## **Features**

- Fully responsive layout for **desktop, tablet, and mobile**  
- Interactive **project cards** with hover effects (transform + box-shadow)  
- Smooth **button hover transitions**  
- Header sticks to top and can shrink on scroll *(ready for JS integration)*  
- Accessible colors and font contrast  
- Images include **meaningful alt attributes**  

---

## **Setup Instructions**

1. Clone the repository:

```bash
git clone https://github.com/yourusername/portfolio.git
```

2. Navigate to the project folder:

```bash
cd portfolio/src
```

3. Compile SCSS to CSS:

```bash
# Using Sass CLI
sass main.scss dist/main.css
```

4. Open `index.html` in your browser.

---

## **SCSS Notes**

- **Variables**: Defined in `utils/_variables.scss` for colors, spacing, typography, and transitions.  
- **Mixins**: `utils/_mixins.scss` includes responsive helpers and container layout.  
- **Reset**: `base/_resets.scss` resets browser defaults.  
- **Blocks**: Each component (header, intro, projects, cards, buttons, footer) is in a separate SCSS file.  

---

## **Future Enhancements**

- Add **JavaScript scroll effect** for shrinking header.  
- Include **more sections** like Skills, Contact Form, and Resume.  
- Add **intro animations** (fade-in / slide-in) for visual appeal.  
- Implement **light/dark mode toggle** using SCSS variables.  

---

## **Accessibility Considerations**

- High contrast colors for readability  
- Keyboard accessible focus for links and buttons  
- Alt text for images  
- Reduced motion preference supported  

---

## **License**

This project is open source and free to use.

