# Personal Website - Tong Liu

A modern, responsive personal portfolio website built from your resume.

## Files Included

- `index.html` - Main HTML structure
- `styles.css` - Styling and responsive design
- `script.js` - Interactive features and animations

## Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Modern UI** - Clean, professional design with smooth animations
- **Interactive Navigation** - Sticky navbar with smooth scrolling
- **Mobile Menu** - Hamburger menu for mobile devices
- **Sections Include:**
  - Hero section with quick links
  - About me
  - Professional experience timeline
  - Projects showcase
  - Education details
  - Technical skills
  - Contact information

## How to Use

### Option 1: Local Viewing
1. Simply open `index.html` in your web browser
2. All files are in the same directory and will work locally

### Option 2: Deploy to GitHub Pages
1. Create a new GitHub repository
2. Upload all three files (index.html, styles.css, script.js)
3. Go to Settings → Pages
4. Select "main" branch as source
5. Your site will be published at `https://yourusername.github.io/repository-name`

### Option 3: Deploy to Netlify
1. Visit [netlify.com](https://www.netlify.com/)
2. Drag and drop the folder containing all files
3. Your site will be live instantly with a custom URL

### Option 4: Deploy to Vercel
1. Visit [vercel.com](https://vercel.com/)
2. Import your project or drag and drop files
3. Deploy with one click

## Customization

### Colors
Edit the CSS variables in `styles.css` at the top:
```css
:root {
    --primary-color: #2563eb;  /* Change primary color */
    --secondary-color: #1e40af; /* Change secondary color */
    /* ... other colors */
}
```

### Content
- Edit `index.html` to update any text, links, or information
- All content is easily editable in plain HTML

### Adding More Projects
In `index.html`, find the `#projects` section and duplicate the `.project-card` div:
```html
<div class="project-card">
    <h3>Your Project Name</h3>
    <div class="project-tech">
        <span class="tech-tag">Technology</span>
    </div>
    <p class="project-date">Date</p>
    <ul class="project-details">
        <li>Project detail 1</li>
        <li>Project detail 2</li>
    </ul>
</div>
```

## Browser Compatibility

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Tips

1. **Update Links**: Make sure all external links (GitHub, LinkedIn) are working
2. **Add Images**: Consider adding a profile photo in the hero section
3. **SEO**: Add meta tags in the `<head>` section for better search engine visibility
4. **Analytics**: Add Google Analytics to track visitors
5. **Custom Domain**: Purchase a custom domain and point it to your hosted site

## Future Enhancements

Consider adding:
- Blog section
- Dark mode toggle
- More animations
- Project screenshots
- Testimonials section
- Download resume button
- Contact form with backend

## License

Feel free to modify and use this website as your own.

---

Built with HTML, CSS, and JavaScript
