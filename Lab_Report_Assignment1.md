# Lab Report
## CSE 309/311: Web Engineering Lab
### Assignment 1: Personalized Portfolio Website

---

**Student Name:** Mohammad Shamsuddoha (Shams)  
**Student ID:** _________________________  
**Section:** _________________________  
**Course:** CSE 309/311 - Web Engineering Lab  
**Submitted To:** _________________________  
**Date of Submission:** _________________________  

---

## 1. Introduction

### 1.1 Objective
The primary objective of this assignment was to design and develop a personal portfolio website using core web development technologies. The portfolio serves as a professional online presence showcasing personal information, skills, projects, and contact details.

### 1.2 Tools & Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure and semantic markup of the website |
| CSS3 | Styling, animations, and visual design |
| Font Awesome 6.0 | Icon library for visual elements |
| Google Fonts (Inter) | Custom typography |
| Git & GitHub | Version control and code repository |

---

## 2. Project Structure

The project consists of the following files:

```
Personalized-Portfolio/
├── index.html          # Main HTML document
├── styles.css          # Stylesheet with all CSS rules
├── LICENSE             # Project license file
└── README.md           # Project documentation
```

---

## 3. Website Features & Implementation

### 3.1 Navigation Bar
A fixed navigation bar was implemented at the top of the page with smooth scrolling functionality. The navigation includes links to:
- Home
- About
- Projects
- Skills
- Contact

**Key CSS Properties Used:**
- `position: fixed` for sticky navigation
- `backdrop-filter: blur(20px)` for glassmorphism effect
- CSS animations for shimmer effect on hover

### 3.2 Hero Section
The hero section serves as the landing area featuring:
- Profile image with floating animation
- Personal introduction and tagline
- Call-to-action buttons

**Code Implementation:**
```html
<section id="home" class="hero">
    <div class="hero-content">
        <div class="profile-image">
            <img src="..." alt="Profile Picture">
        </div>
        <h1>Yoo Bruv, I'm Shams</h1>
        <p class="tagline">"Hacking code, mastering ML..."</p>
        <div class="hero-buttons">
            <a href="#about" class="btn-primary">Trace My Path</a>
            <a href="#contact" class="btn-secondary">Ping Me</a>
        </div>
    </div>
</section>
```

### 3.3 About Section
This section provides detailed information about the developer including:
- Personal introduction
- Background information
- Areas of interest displayed in a grid layout

### 3.4 Projects Section
A showcase of featured projects with:
- Project cards with images
- Descriptions
- Links to GitHub repositories

**Grid Layout Implementation:**
```css
.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 40px;
}
```

### 3.5 Skills Section
The skills section is divided into two categories:

**Technical Skills:**
- Arch Linux / Ubuntu Server (90%)
- Proxmox & Virtualization (85%)
- Docker & Containerization (85%)
- Networking & VPN / AdGuard (80%)
- Python (ML, Automation) (80%)
- Bash / Shell Scripting (75%)
- Web Development (HTML, CSS, JS) (70%)
- Telegram Bot & API Automation (75%)
- ML / Data Analysis (65%)
- Crypto Trading / Dashboard (70%)

**Soft Skills:**
- Problem Solving & Analytical Thinking
- Creativity & Innovation
- Self-Motivation & Initiative
- Attention to Detail
- Collaboration & Communication
- Adaptability & Learning Agility

### 3.6 Contact Section
Comprehensive contact section featuring:
- Contact information (email, phone, location)
- Social media links (LinkedIn, GitHub, Twitter, Instagram)
- Contact form with input fields

---

## 4. CSS Techniques & Styling

### 4.1 CSS Custom Properties (Variables)
CSS variables were used for consistent theming:

```css
:root {
    --background: #1c1c1c;
    --foreground: #ffffff;
    --primary: #ff5722;
    --secondary: #ffc107;
    --card: #2d2d2d;
    --border: #374151;
    --radius: 8px;
}
```

### 4.2 Advanced CSS Features Used
1. **CSS Grid** - For responsive layouts
2. **Flexbox** - For flexible container layouts
3. **CSS Animations & Keyframes** - For dynamic effects
4. **Gradient Backgrounds** - For visual appeal
5. **Box Shadows** - For depth and elevation
6. **Transitions** - For smooth state changes
7. **Backdrop Filter** - For glassmorphism effects

### 4.3 Responsive Design
The website implements responsive design principles using:
- `auto-fit` and `minmax()` functions in CSS Grid
- Flexible units (%, rem, em)
- Media query ready structure

---

## 5. Color Scheme

| Color | Hex Code | Usage |
|-------|----------|-------|
| Background | #1c1c1c | Main background color |
| Foreground | #ffffff | Primary text color |
| Primary | #ff5722 | Accent color (Orange) |
| Secondary | #ffc107 | Secondary accent (Yellow) |
| Card | #2d2d2d | Card backgrounds |
| Muted | #cccccc | Subdued text |

---

## 6. Key Learning Outcomes

Through this assignment, the following concepts were learned and applied:

1. **Semantic HTML5** - Proper use of semantic tags (`<nav>`, `<section>`, `<footer>`, etc.)
2. **CSS Layouts** - Implementation of modern CSS Grid and Flexbox layouts
3. **CSS Variables** - Using custom properties for maintainable code
4. **Animations** - Creating smooth CSS animations and transitions
5. **Responsive Design** - Building layouts that adapt to different screen sizes
6. **External Resources** - Integrating CDN libraries (Font Awesome, Google Fonts)
7. **Version Control** - Using Git and GitHub for code management

---

## 7. Challenges Faced & Solutions

| Challenge | Solution |
|-----------|----------|
| Creating smooth animations | Used CSS keyframes with cubic-bezier timing functions |
| Implementing glassmorphism | Applied backdrop-filter with rgba backgrounds |
| Skill bar visualization | Used CSS width property with percentage values |
| Consistent spacing | Created reusable CSS variables and container classes |

---

## 8. Future Improvements

1. Add JavaScript for form validation and submission
2. Implement a dark/light mode toggle
3. Add more project showcases
4. Integrate a blog section
5. Add page loading animations
6. Implement contact form backend functionality

---

## 9. Screenshots

*(Insert screenshots of your website here)*

- Home Page / Hero Section
- About Section
- Projects Section
- Skills Section
- Contact Section

---

## 10. Repository Link

**GitHub Repository:** https://github.com/shams909/Personalized-Portfolio

---

## 11. Conclusion

This assignment successfully demonstrates the implementation of a personal portfolio website using HTML5 and CSS3. The project showcases various web development concepts including semantic markup, responsive design, CSS animations, and modern styling techniques. The portfolio effectively presents personal information, skills, and projects in a visually appealing manner.

The use of CSS custom properties ensures maintainability, while the implementation of CSS Grid and Flexbox provides a robust responsive layout system. The glassmorphism design trend and smooth animations contribute to a modern user experience.

---

## 12. References

1. MDN Web Docs - HTML5 Reference: https://developer.mozilla.org/en-US/docs/Web/HTML
2. MDN Web Docs - CSS Reference: https://developer.mozilla.org/en-US/docs/Web/CSS
3. Font Awesome Icons: https://fontawesome.com/
4. Google Fonts: https://fonts.google.com/
5. CSS-Tricks - A Complete Guide to Grid: https://css-tricks.com/snippets/css/complete-guide-grid/
6. CSS-Tricks - A Complete Guide to Flexbox: https://css-tricks.com/snippets/css/a-guide-to-flexbox/

---

**Signature:** _________________________  
**Date:** _________________________

