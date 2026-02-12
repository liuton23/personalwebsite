# 💻 Personal Portfolio - Tong Liu

A premium dark console-themed portfolio website featuring a sleek terminal aesthetic with smooth animations and interactive elements.

![Console Theme](https://img.shields.io/badge/Theme-Dark%20Console-00d9ff?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-00ff88?style=for-the-badge)
![Responsive](https://img.shields.io/badge/Responsive-Yes-a78bfa?style=for-the-badge)

## ✨ Features

### 🎨 Premium Dark Console Design
- **Terminal Aesthetic** - Monospace fonts (Consolas, Monaco, Fira Code) for authentic console feel
- **Cyberpunk Color Palette** - Electric cyan (#00d9ff), blue (#0ea5e9), purple accents
- **Neon Glow Effects** - Subtle glowing effects on interactive elements
- **Console Symbols** - Terminal prompts (>, $, //) throughout the interface
- **Smooth Animations** - Custom cubic-bezier transitions (400ms) for professional feel

### 🖥️ Interactive Elements
- **Glowing Navigation** - Navbar with terminal prompt symbols and hover effects
- **Terminal Windows** - Project cards styled as console windows with colored dots (● ● ●)
- **Pulsing Timeline** - Animated timeline dots with gradient glow
- **Hover Transformations** - Cards lift and glow on interaction
- **Custom Scrollbar** - Cyan gradient scrollbar with glow effect
- **Scan Lines** - Subtle terminal scan line effect in hero section

### 📱 Fully Responsive
- Mobile-optimized hamburger menu
- Adaptive layouts for all screen sizes
- Touch-friendly interactions
- Responsive typography and spacing

### 🎯 Sections Include
- **Hero** - Gradient name with blinking cursor and personal introduction
- **About** - Professional summary with job-seeking status
- **Experience** - Interactive timeline with console-style cards
- **Projects** - Terminal window project showcases
- **Education** - Academic background with glowing badges
- **Skills** - Interactive skill tags with transform effects
- **Contact** - Multi-channel contact cards with icons

## 🚀 Live Demo

Visit the live site: `https://liuton23.github.io/personalwebsite/`

## 📂 Files Included

```
Personal-Website/
├── index.html      # Main HTML structure
├── styles.css      # Dark console theme styling
├── script.js       # Interactive features & animations
└── README.md       # Project documentation
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, animations, gradients, flexbox, grid
- **JavaScript (Vanilla)** - Intersection Observer, scroll effects, mobile menu
- **Responsive Design** - Mobile-first approach

## 💻 Local Development

### Quick Start
```bash
# Clone the repository
git clone https://github.com/liuton23/personalwebsite.git

# Navigate to directory
cd [personalwebsite]

# Open in browser
start index.html
```

### Using Live Server (Recommended)
1. Install "Live Server" extension in VSCode
2. Right-click `index.html` → "Open with Live Server"
3. Enjoy auto-reload on file changes!

## 🌐 Deployment Options

### GitHub Pages (Recommended)
1. Push code to your GitHub repository
2. Go to **Settings** → **Pages**
3. Source: Select **main** branch, **/ (root)** folder
4. Click **Save**
5. Site will be live at: `https://liuton23.github.io/personalwebsite/`

### Netlify
1. Visit [netlify.com](https://www.netlify.com/)
2. Drag and drop the project folder
3. Instant deployment with custom URL

### Vercel
1. Visit [vercel.com](https://vercel.com/)
2. Import your GitHub repository
3. Deploy with one click

## 🎨 Customization

### Color Scheme
Edit CSS variables in `styles.css`:

```css
:root {
    /* Dark Console Theme Colors */
    --bg-primary: #0a0e27;          /* Main background */
    --bg-secondary: #0f1323;        /* Section backgrounds */
    --bg-card: #161b33;             /* Card backgrounds */

    /* Console Colors */
    --primary-cyan: #00d9ff;        /* Primary accent */
    --primary-blue: #0ea5e9;        /* Secondary accent */
    --accent-purple: #a78bfa;       /* Purple accent */
    --neon-green: #00ff88;          /* Terminal green */
    --terminal-yellow: #fbbf24;     /* Warning/dates */

    /* Text Colors */
    --text-primary: #e2e8f0;        /* Main text */
    --text-secondary: #94a3b8;      /* Secondary text */
    --text-glow: #00d9ff;           /* Glowing text */
}
```

### Content Updates
- **Personal Info**: Edit `index.html` hero section
- **Experience**: Update timeline items in `#experience` section
- **Projects**: Add/modify project cards in `#projects` section
- **Skills**: Update skill tags in `#skills` section
- **Contact**: Change contact info in `#contact` section

### Adding Projects
Duplicate this block in the `#projects` section:

```html
<div class="project-card">
    <h3>Your Project Name</h3>
    <div class="project-tech">
        <span class="tech-tag">Technology</span>
        <span class="tech-tag">Framework</span>
    </div>
    <p class="project-date">Month Year</p>
    <ul class="project-details">
        <li>Feature or achievement 1</li>
        <li>Feature or achievement 2</li>
        <li>Feature or achievement 3</li>
    </ul>
</div>
```

## 🎭 Special Features

### Console Easter Egg
Open the browser console (F12) to see a custom terminal-themed message with:
- Cyan glowing text effects
- Terminal symbols (>, $, →)
- Contact information in neon green

### Animations
- **Fade In Up** - Section content animates on scroll
- **Glow Pulse** - Title glows with animated effect
- **Cursor Blink** - Terminal cursor blinks next to name
- **Timeline Pulse** - Experience dots pulse continuously
- **Hover Lifts** - Cards lift and glow on hover

### Performance
- Smooth 60fps animations using GPU-accelerated transforms
- Intersection Observer for efficient scroll animations
- Optimized CSS with custom properties
- Minimal JavaScript for fast load times

## 🌟 Browser Support

| Browser | Version |
|---------|---------|
| Chrome  | ✅ Latest |
| Firefox | ✅ Latest |
| Safari  | ✅ Latest |
| Edge    | ✅ Latest |

## 📝 To-Do / Future Enhancements

- [ ] Add project screenshots/images
- [ ] Implement downloadable resume PDF
- [ ] Add contact form with backend
- [ ] Create blog section
- [ ] Add testimonials carousel
- [ ] Integrate analytics (Google Analytics)
- [ ] Add more terminal animations (typing effects)
- [ ] Create particle.js background effect
- [ ] Add language toggle (i18n)
- [ ] Implement service worker for offline support

## 📄 License

MIT License - Feel free to use this template for your own portfolio!

## 🤝 Connect

- **Email**: trevor.liu28@gmail.com
- **LinkedIn**: [linkedin.com/in/trevortongliu](https://linkedin.com/in/trevortongliu)
- **GitHub**: [github.com/liuton23](https://github.com/liuton23)

---

<p align="center">
  Built with ❤️ using HTML, CSS, and JavaScript<br>
  <code>> console.log("Actively seeking new opportunities!")</code>
</p>
