# CSS Advanced - Headphone Company Landing Page

## 📋 Project Overview

This project is the **second phase** of implementing a webpage from a Figma design. After creating the HTML structure in the previous project (`0x02. HTML, advanced`), we now focus on **CSS styling and visual presentation** to match the designer's specifications exactly.

## 🎯 Learning Objectives

By the end of this project, you should be able to explain the following concepts without external help:

### CSS Fundamentals
- What is CSS and how it works with HTML
- How to add style to an element
- What is a class and how to use it
- What is a selector and how to apply CSS rules
- How to compute CSS Specificity Value
- What are Box properties in CSS
- How the browser loads a webpage

### Advanced CSS Concepts
- CSS positioning and layout techniques
- Flexbox and CSS Grid fundamentals
- Responsive design principles
- CSS custom properties (variables)
- Modern CSS methodologies

## 🛠️ Technical Requirements

### General Guidelines
- All files must end with a new line character
- A `README.md` file is mandatory at the project root
- **No external libraries allowed** - pure HTML/CSS only
- No CSS frameworks (Bootstrap, Tailwind, etc.)
- No JavaScript frameworks or libraries
- Code must be W3C compliant and validate with W3C CSS Validator

### CSS Standards
- Use modern CSS3 features where appropriate
- Implement responsive design principles
- Follow CSS best practices for organization
- Use semantic class naming conventions
- Optimize for performance and maintainability

## 📁 Project Structure

```
holbertonschool-web-development/
└── css_advanced/
    ├── README.md
    ├── index.html          (copied from html_advanced)
    ├── styles.css          (new CSS file)
    └── images/             (folder for assets)
        ├── logo.png
        └── ...
```

## 🎨 Design Reference

The design specifications are available on Figma:
- [Page in Figma](https://www.figma.com/design/...)
- Access the fig file for detailed measurements and specifications
- Remember to "Duplicate to your Drafts" for full design access

### Design Notes
- **Fonts needed:** `source-sans-pro` and `Spin-Cycle-OT`
- Some values may be in float format - feel free to round them
- Pay attention to spacing, colors, and typography specifications
- Ensure pixel-perfect implementation where possible

## 🏗️ Implementation Approach

### Phase 1: Setup and Preparation
1. **Copy HTML Structure**
   - Copy `index.html` from the `html_advanced` project
   - Ensure all HTML structure is complete and valid
   - Add link to CSS file in the `<head>` section

2. **CSS File Organization**
   - Create `styles.css` file
   - Organize CSS with clear sections and comments
   - Use consistent formatting and indentation

### Phase 2: Base Styling
1. **CSS Reset/Normalize**
   - Remove default browser styles
   - Set consistent baseline styles

2. **Typography**
   - Import required fonts (source-sans-pro, Spin-Cycle-OT)
   - Set font families, sizes, and weights
   - Implement proper text hierarchy

3. **Color Scheme**
   - Extract exact colors from Figma design
   - Use CSS custom properties for consistent theming

### Phase 3: Layout Implementation
1. **Header Section**
   - Position logo and navigation
   - Implement responsive navigation
   - Add hover effects and interactions

2. **Main Content Areas**
   - Hero/banner section styling
   - Content sections layout
   - Images and media integration

3. **Footer Section**
   - Footer layout and styling
   - Links and contact information

### Phase 4: Responsive Design
1. **Mobile-First Approach**
   - Start with mobile styles
   - Add breakpoints for larger screens
   - Ensure proper scaling and usability

2. **Cross-Browser Compatibility**
   - Test across different browsers
   - Add vendor prefixes where needed
   - Ensure graceful degradation

## ✅ Validation Requirements

Before submission, ensure your CSS:
- [ ] Passes W3C CSS Validator without errors
- [ ] Matches the Figma design specifications
- [ ] Is responsive across different screen sizes
- [ ] Uses semantic class naming conventions
- [ ] Has clean, organized, and commented code
- [ ] Loads efficiently without performance issues

## 🔍 Key CSS Techniques to Implement

### Layout Methods
- **Flexbox** for navigation and content alignment
- **CSS Grid** for complex layouts (if needed)
- **Positioning** for precise element placement
- **Float alternatives** using modern CSS

### Styling Techniques
- **CSS Variables** for consistent theming
- **Pseudo-classes** for hover and focus states
- **Media queries** for responsive design
- **CSS transitions** for smooth interactions

### Performance Optimizations
- **Efficient selectors** to minimize CSS specificity conflicts
- **Optimized images** and assets
- **Minimal CSS** without redundancy
- **Critical CSS** considerations

## 🚀 Getting Started

1. **Setup Your Environment**
   ```bash
   cd holbertonschool-web-development
   mkdir css_advanced
   cd css_advanced
   ```

2. **Copy HTML Structure**
   ```bash
   cp ../html_advanced/index.html .
   ```

3. **Create CSS File**
   ```bash
   touch styles.css
   ```

4. **Link CSS to HTML**
   Add to your HTML `<head>` section:
   ```html
   <link rel="stylesheet" href="styles.css">
   ```

5. **Start Styling**
   - Begin with CSS reset
   - Add typography and colors
   - Implement layout section by section

## 📚 Resources

### CSS References
- [MDN CSS Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [CSS-Tricks](https://css-tricks.com/)
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS Grid Layout Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)

### Validation Tools
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
- [CSS Lint](http://csslint.net/)

### Design Tools
- [Figma Design File](https://www.figma.com/design/...)
- [Google Fonts](https://fonts.google.com/) for font imports
- [Adobe Color](https://color.adobe.com/) for color extraction

### Browser Dev Tools
- Chrome DevTools CSS features
- Firefox Developer Tools
- Safari Web Inspector

## 💡 Pro Tips

### CSS Organization
```css
/* ==========================================================================
   CSS Reset and Base Styles
   ========================================================================== */

/* ==========================================================================
   Typography
   ========================================================================== */

/* ==========================================================================
   Layout - Header
   ========================================================================== */

/* ==========================================================================
   Layout - Main Content
   ========================================================================== */

/* ==========================================================================
   Layout - Footer
   ========================================================================== */

/* ==========================================================================
   Media Queries
   ========================================================================== */
```

### Responsive Breakpoints
```css
/* Mobile First */
/* Styles for mobile devices */

@media (min-width: 768px) {
  /* Tablet styles */
}

@media (min-width: 1024px) {
  /* Desktop styles */
}
```

### CSS Custom Properties
```css
:root {
  --primary-color: #000000;
  --secondary-color: #ffffff;
  --font-primary: 'source-sans-pro', sans-serif;
  --font-secondary: 'Spin-Cycle-OT', cursive;
}
```

## 👨‍💻 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- Project Repository: [holbertonschool-web-development](https://github.com/holbertonschool/holbertonschool-web-development)

---

## 📝 Notes

This project builds upon the HTML structure created in the previous `html_advanced` project. The focus is on implementing professional-level CSS that accurately reflects the design specifications while maintaining clean, scalable, and maintainable code.

Remember: **Design fidelity is key!** Your implementation should match the Figma design as closely as possible while using modern CSS best practices.