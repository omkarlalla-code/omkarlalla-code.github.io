# Omkar Nitin Lalla - Personal Website

A clean, minimal personal website for Omkar Nitin Lalla, showcasing his work as a 16-year-old full stack developer from Pune, Maharashtra.

## Overview

This website serves as both a portfolio and marketing tool, designed to position Omkar as a competent young developer seeking opportunities. The site showcases his technical skills, academic projects, and well-rounded personality.

## Design Philosophy

- **Minimalist Aesthetic**: Clean, professional design with no clutter
- **Two-Color System**: 
  - Primary color (#2c3e50) for header and footer
  - Secondary background (#f8fafc) for main content
- **Fast Loading**: Pure HTML/CSS with no external dependencies
- **Mobile Responsive**: Optimized for all screen sizes
- **Accessible**: Semantic HTML and proper focus states

## Features

- **Professional Layout**: Single-page design with smooth scrolling navigation
- **Project Showcase**: Detailed descriptions of technical projects including:
  - AI-Powered Periodic Table
  - Diplomatic Document Generator
  - Aviation Route Planning
  - MediaPipe API Documentation
  - Music Recommendation Research
  - Educational Web Tools

- **Skills Display**: Comprehensive technical abilities including:
  - Programming languages (Python, JavaScript, HTML/CSS, SQL, LaTeX)
  - Technologies (AI integration, web development, data analysis)
  - Specialized knowledge (aviation, academic research, international relations)

- **Personal Interests**: Well-rounded profile including aviation, Model UN, photography, gaming, and reading

## File Structure

```
Personal_Website/
├── index.html          # Main HTML structure
├── styles.css          # CSS styling and responsive design
└── README.md           # This file
```

## GitHub Pages Setup

To host this website on GitHub Pages:

1. **Create a new repository** on GitHub:
   - Repository name: `username.github.io` (for user site) or any name (for project site)
   - Make it public
   - Initialize with README

2. **Upload files**:
   ```bash
   git clone https://github.com/username/repository-name.git
   cd repository-name
   # Copy the files (index.html, styles.css) to this directory
   git add .
   git commit -m "Add personal website"
   git push origin main
   ```

3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Source: Deploy from a branch
   - Branch: main / (root)
   - Save

4. **Access the site**:
   - User site: `https://username.github.io`
   - Project site: `https://username.github.io/repository-name`

## Local Development

To run locally:

1. **Clone or download** the files to your local machine
2. **Open index.html** in any modern web browser
3. **No server required** - it's a static website

For development with live reload:
```bash
# Using Python's built-in server
python -m http.server 8000

# Using Node.js live-server (if installed)
npx live-server
```

## Browser Compatibility

- **Chrome**: Full support
- **Firefox**: Full support  
- **Safari**: Full support
- **Edge**: Full support
- **Mobile browsers**: Responsive design optimized for all mobile devices

## Customization

### Updating Contact Information

Edit the contact section in `index.html`:
```html
<div class="contact-item">
    <strong>Email:</strong>
    <a href="mailto:your-email@example.com">your-email@example.com</a>
</div>
```

### Adding New Projects

Add project cards to the projects grid:
```html
<div class="project-card">
    <h3>Project Name</h3>
    <p>Project description...</p>
    <div class="project-tech">
        <span>Technology 1</span>
        <span>Technology 2</span>
    </div>
</div>
```

### Modifying Color Scheme

Update CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2c3e50;     /* Header/footer color */
    --secondary-color: #f8fafc;   /* Main background */
    --accent: #3b82f6;            /* Links and highlights */
}
```

## SEO Optimization

The website includes:
- Semantic HTML structure
- Meta description for search engines
- Proper heading hierarchy (h1, h2, h3)
- Descriptive alt attributes (when images are added)
- Clean URL structure

## Performance

- **No external dependencies**: All CSS is inline, no JavaScript frameworks
- **Optimized images**: Use when adding images (WebP format recommended)
- **Minified CSS**: Can be minified for production
- **Caching**: Static files cache well on CDNs

## Accessibility Features

- **Semantic HTML**: Proper use of header, main, section, footer elements
- **Keyboard Navigation**: All interactive elements are keyboard accessible
- **Focus States**: Clear focus indicators for navigation
- **Color Contrast**: WCAG AA compliant color combinations
- **Responsive Text**: Scales appropriately on different devices
- **Reduced Motion**: Respects user's motion preferences

## Content Guidelines

When updating content:
- Keep descriptions concise and professional
- Use active voice and specific achievements
- Include technical details to demonstrate expertise
- Maintain consistent tone throughout
- Update project technologies as skills develop

## Future Enhancements

Potential additions while maintaining minimalism:
- Contact form with backend integration
- Blog section for technical writing
- Project galleries with screenshots
- Resume/CV download link
- Analytics integration (Google Analytics)

## Technical Stack

- **HTML5**: Semantic structure and accessibility
- **CSS3**: Modern styling with Flexbox and Grid
- **No JavaScript**: Pure static website for maximum compatibility
- **No frameworks**: Vanilla web technologies only

## License

This website template is designed specifically for Omkar Nitin Lalla. Feel free to use as inspiration for your own personal website.

---

**Created**: January 2025  
**Last Updated**: January 2025  
**Version**: 1.0

For questions or updates, contact: lallanitin66@gmail.com