# Violet Figueroa | Security Portfolio Website

Welcome to the source repository for my GitHub Pages security portfolio site deployed at **[violetfigueroa.github.io](https://violetfigueroa.github.io/)**

## 🎯 About This Site

This repository contains the HTML/CSS/JavaScript source for my professional cybersecurity portfolio. It showcases:

- **Real-world incident response & digital forensics projects**
- **Vulnerability assessment & risk management case studies**
- **Application security (OWASP Top 10) demonstrations**
- **Network security & infrastructure analysis work**
- **Professional experience & technical capabilities**

The site is fully responsive, accessible (WCAG 2.1 compliant), and features both light and dark mode themes.

## 🚀 Quick Start

This site is automatically deployed via GitHub Pages. Any changes pushed to the `main` branch are live at:
- **https://violetfigueroa.github.io/**

### Local Development

To work on the site locally:

```bash
# Clone the repository
git clone https://github.com/VioletFigueroa/VioletFigueroa.github.io.git
cd VioletFigueroa.github.io

# Open in your browser
open index.html
# or
firefox index.html
```

No build process is required—the site is static HTML/CSS/JavaScript.

## 📁 Repository Structure

```
.
├── index.html              # Main portfolio site (home page)
├── README.md               # This file
├── LICENSE                 # License information
├── SECURITY.md             # Security & responsible disclosure
└── assets/                 # Optional: Future images, additional CSS, etc.
    └── (Currently in index.html as single-file design)
```

## 🛠️ Technical Stack

- **HTML5** – Semantic markup and accessibility
- **CSS3** – Modern responsive design with CSS variables
- **JavaScript (ES6+)** – Theme toggle, smooth interactions
- **Accessibility** – WCAG 2.1 compliant, keyboard navigation
- **Performance** – Single-file architecture, zero external dependencies
- **Dark Mode** – Automatic detection + manual override with localStorage

## 🎨 Features

### Responsive Design
- Mobile-first approach
- Desktop, tablet, and mobile optimized
- Flexible grid layouts using CSS Grid

### Accessibility
- Semantic HTML structure
- WCAG 2.1 Level AA compliant
- Keyboard navigation support
- Focus indicators visible
- Screen reader compatible
- High color contrast ratios

### Dark Mode
- System preference detection
- Manual theme toggle
- Persistent user preference (localStorage)
- Smooth transitions between themes

### Project Showcase
- Grid-based project cards
- Tool/technology tags
- Direct links to GitHub projects
- Project type categorization
- Hover interactions

## 📊 Content Sections

1. **Navigation** – Links to all sections, theme toggle
2. **Hero Section** – Introduction and call-to-action buttons
3. **Experience** – Professional background at Accessible Places
4. **Featured Projects** – Incident response, forensics, DFIR
5. **Vulnerability & Risk Management** – Security architecture, assessments
6. **Application Security** – OWASP Top 10 demonstrations
7. **Network Security** – Infrastructure and analysis
8. **Technical Capabilities** – Skills demonstrated through projects
9. **Contact** – Links to email, GitHub, LinkedIn, main portfolio

## 🔗 Links & Resources

- **Main Portfolio Profile:** [github.com/VioletFigueroa](https://github.com/VioletFigueroa)
- **GitHub Profile README:** [VioletFigueroa/VioletFigueroa](https://github.com/VioletFigueroa/VioletFigueroa)
- **Featured Projects:** See portfolio site for links to all GitHub repositories
- **Professional Links:**
  - LinkedIn: [linkedin.com/in/violet-figueroa](https://www.linkedin.com/in/violet-figueroa/)
  - Email: [violet@violetfigueroa.com](mailto:violet@violetfigueroa.com)

## 🔒 Security & Responsible Disclosure

See [SECURITY.md](./SECURITY.md) for responsible disclosure policy and security best practices information.

## 📜 License

This portfolio site is licensed under the Educational License. See [LICENSE](./LICENSE) for full details.

All featured project work is completed in controlled lab environments with explicit authorization and follows ethical security research practices.

## 🛠️ Customization

### Updating Project Information

Edit `index.html` and update:
- Project card content (descriptions, links)
- Experience section details
- Skills and capabilities
- Contact information

### Changing Colors

CSS variables in `index.html` `<style>` section:

```css
:root {
    --color-primary: #10b981;           /* Primary accent color */
    --color-primary-hover: #059669;     /* Hover state */
    --color-background: #ffffff;        /* Light mode background */
    /* ... more variables ... */
}

html.dark {
    /* Dark mode overrides */
}
```

### Adding New Sections

1. Add new `<section>` in the `<main>` element
2. Update navigation links in `<header>`
3. Assign unique `id` attribute for anchor linking
4. Use existing class names for consistent styling

## 📱 Browser Support

- Chrome/Chromium (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ✨ Features & Best Practices

### Performance
- Single-file design (zero HTTP requests for resources)
- Minimal CSS
- No external dependencies
- Fast loading and rendering

### SEO
- Semantic HTML structure
- Descriptive page title
- Meta viewport for mobile
- Structured heading hierarchy

### Accessibility
- ARIA labels where appropriate
- Focus management
- Color contrast compliance
- Keyboard navigation
- Screen reader optimization

## 🚀 Deployment

This site automatically deploys via GitHub Pages:

1. Push changes to `main` branch
2. GitHub Pages automatically builds and deploys
3. Changes live within seconds at https://violetfigueroa.github.io/

### Custom Domain

To use a custom domain, add a `CNAME` file:

```
violetfigueroa.com
```

Then update DNS records at your domain registrar (see [GitHub Pages documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)).

## 📧 Contact & Questions

- **Email:** violet@violetfigueroa.com
- **LinkedIn:** [linkedin.com/in/violet-figueroa](https://www.linkedin.com/in/violet-figueroa/)
- **GitHub:** [github.com/VioletFigueroa](https://github.com/VioletFigueroa)

---

**Last Updated:** January 28, 2026

**Interview Ready:** Yes ✓

*Passionate about making cybersecurity more accessible, sustainable, and inclusive. This portfolio demonstrates real-world security expertise through hands-on projects and professional experience.*
