# Personal Academic Website Customization Guide

This guide will help you customize your personal academic website template.

## Quick Start

1. **Enable GitHub Pages**:
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select "Deploy from a branch"
   - Choose `main` or your desired branch
   - Your website will be available at: `https://victormorand.github.io/VictorMorand/`

2. **Customize the Content**:
   Edit `index.html` to replace placeholder content with your information.

## Section-by-Section Customization

### About Section
- Replace the placeholder image URL with your profile photo
- Update the introduction text
- Add your research interests
- Add your current position

### Research Section
- Add your current research projects
- Update project titles and descriptions
- List your research areas

### Publications Section
- Add your journal articles with proper citations
- Include links to PDFs, DOIs, and code repositories
- Add conference papers with links to slides

### CV Section
- Update education details (degrees, universities, years)
- Add professional experience
- Link to your full CV PDF (upload the PDF to the repository)

### Contact Section
- Update email address
- Add office location
- Update institution name
- Update social media links (GitHub, Google Scholar, LinkedIn, Twitter)

## Styling Customization

Edit `styles.css` to customize the appearance:

### Color Scheme
Change the CSS variables in the `:root` section:
```css
:root {
    --primary-color: #2c3e50;     /* Main dark color */
    --secondary-color: #3498db;    /* Accent blue */
    --accent-color: #e74c3c;       /* Highlight red */
    --text-color: #333;            /* Main text */
    --light-bg: #f8f9fa;          /* Alternate sections */
}
```

### Fonts
Replace the font-family in the `body` selector:
```css
body {
    font-family: 'Your-Font-Name', sans-serif;
}
```

## Adding Content

### Adding a New Publication
Copy this template and modify:
```html
<div class="publication">
    <p class="pub-title">Your Paper Title</p>
    <p class="pub-authors">Authors: Your Name, Co-author Names</p>
    <p class="pub-venue">Conference/Journal Name, Year</p>
    <p class="pub-links">
        <a href="link-to-pdf">PDF</a> | 
        <a href="link-to-doi">DOI</a> | 
        <a href="link-to-code">Code</a>
    </p>
</div>
```

### Adding a New Project
Copy this template and modify:
```html
<div class="project">
    <h4>Project Title</h4>
    <p>Project description including objectives, methodology, and outcomes.</p>
</div>
```

## Tips

1. **Images**: Store images in an `images/` folder in your repository
2. **PDFs**: Store CV and paper PDFs in a `files/` folder
3. **Mobile Testing**: Always test on mobile devices after making changes
4. **SEO**: Update the meta description in the `<head>` section for better search visibility

## GitHub Pages Configuration

The `_config.yml` file contains basic GitHub Pages settings. You can customize:
- `title`: Your name/site title
- `description`: A brief description of your site
- `email`: Your contact email

## Need Help?

- Check the [GitHub Pages documentation](https://docs.github.com/en/pages)
- Review HTML/CSS tutorials for deeper customization
- Test changes locally before pushing to GitHub

## License

This template is free to use and customize for your personal academic website.
