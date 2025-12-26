# Professional Portfolio Website

A modern, responsive portfolio website template designed to showcase your work, skills, and projects as a designer/developer.

## 📁 Project Structure

```
new-portfolio/
├── index.html           # Main portfolio page
├── styles.css          # Global styles and responsive design
├── script.js           # Interactive functionality
├── assets/
│   ├── images/         # Place your images here
│   │   ├── profile.jpg     # Your profile/featured image
│   │   ├── project1.jpg    # Project showcase images
│   │   ├── project2.jpg
│   │   ├── project3.jpg
│   │   └── project4.jpg
│   └── fonts/          # Optional: Custom font files
└── README.md           # This file
```

## ✨ Features

### Modern Design
- Clean, professional aesthetic with gradient accents
- Consistent color scheme (Primary: Indigo, Secondary: Pink, Accent: Amber)
- Smooth animations and transitions
- Beautiful hover effects

### Responsive Layout
- Mobile-first approach
- Fully responsive from 480px to 1200px+ screens
- Hamburger menu for mobile devices
- Optimized touch interactions

### Sections
1. **Navigation Bar** - Sticky navbar with smooth scrolling
2. **Hero Section** - Eye-catching introduction with featured image
3. **Skills Section** - 6 skill cards highlighting your expertise
4. **Projects Section** - 4 project cards with descriptions and tags
5. **Contact Section** - Contact information and message form
6. **Social Links** - Integration with GitHub, LinkedIn, Twitter, and Dribbble

### Interactive Features
- Smooth scroll navigation
- Mobile menu toggle with animation
- Form submission with email integration
- Intersection Observer animations
- Scroll-based navbar effects
- Keyboard navigation support

## 🚀 Getting Started

### 1. Open in Browser
Simply open `index.html` in your web browser to view the portfolio.

### 2. Customize Content

#### Update Personal Information
Edit the following in `index.html`:

```html
<!-- Hero Section -->
<h1 class="hero-title">Your Name</h1>
<p class="hero-subtitle">Your Job Title</p>

<!-- Contact Info -->
<a href="mailto:your.email@example.com">your.email@example.com</a>
<a href="tel:+1234567890">+1 (234) 567-890</a>
```

#### Update Skills
Modify the skill cards in the **Skills & Expertise** section:

```html
<div class="skill-card">
    <div class="skill-icon">💻</div>
    <h3>Your Skill Name</h3>
    <p>Your skill description and technologies</p>
</div>
```

#### Update Projects
Replace project information in the **Featured Projects** section:

```html
<div class="project-card">
    <div class="project-image">
        <img src="assets/images/project1.jpg" alt="Project Title">
    </div>
    <div class="project-content">
        <h3>Your Project Title</h3>
        <p>Project description...</p>
        <div class="project-tags">
            <span class="tag">Technology</span>
        </div>
        <div class="project-links">
            <a href="your-project-url" class="project-link">View Project</a>
            <a href="github-repo-url" class="project-link">Source Code</a>
        </div>
    </div>
</div>
```

#### Update Social Links
Replace the social links at the bottom of the contact section:

```html
<a href="https://github.com/your-username" class="social-icon">...</a>
```

### 3. Add Images

Place your images in the `assets/images/` folder:
- `profile.jpg` - Featured image in hero section
- `project1.jpg`, `project2.jpg`, etc. - Project showcase images

**Note:** If images are missing, placeholders will display automatically.

### 4. Customize Colors

Edit CSS variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;      /* Main accent color */
    --secondary-color: #ec4899;    /* Secondary accent */
    --accent-color: #f59e0b;       /* Tertiary accent */
    --dark-bg: #0f172a;            /* Dark background */
    --light-bg: #f8fafc;           /* Light background */
    --text-dark: #1e293b;          /* Main text color */
    --text-light: #475569;         /* Secondary text */
    --text-muted: #94a3b8;         /* Muted text */
}
```

## 📱 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Deployment

### Deploy to Netlify
1. Push your code to a GitHub repository
2. Connect your repository to Netlify
3. Netlify will automatically deploy your site

### Deploy to GitHub Pages
1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select the branch and folder to deploy

### Deploy to Vercel
1. Import your repository to Vercel
2. Vercel will automatically deploy your site

## 📧 Email Integration

The contact form is set up to open your default email client with:
- Recipient: `john@example.com` (update this)
- Subject: From the form input
- Body: Includes name, email, and message

To change the recipient email, update in `script.js`:

```javascript
const mailtoLink = `mailto:your.email@example.com?subject=...`;
```

## 🎨 Customization Tips

1. **Font Family**: Change in `styles.css` → `font-family: 'Your Font', sans-serif;`
2. **Typography**: Adjust font sizes in the `:root` section
3. **Spacing**: Modify padding/margin values in the CSS
4. **Animations**: Adjust `--transition` variable for animation speed
5. **Breakpoints**: Modify media queries for different screen sizes

## 📝 SEO Optimization

Update the following in `index.html`:

```html
<title>Your Name - Designer & Developer</title>
<meta name="description" content="Your professional portfolio description">
```

## 🚀 Performance Tips

1. **Optimize Images**: Compress images before adding to `assets/images/`
2. **Lazy Loading**: Images load on demand using Intersection Observer
3. **CSS**: Minify `styles.css` for production
4. **JavaScript**: Minify `script.js` for production

## 📚 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients, flexbox, and grid
- **JavaScript (Vanilla)** - No frameworks or dependencies
- **Intersection Observer API** - For scroll animations

## 📄 File Sizes

- `index.html` - ~12 KB
- `styles.css` - ~20 KB
- `script.js` - ~6 KB
- **Total** - ~38 KB (lightweight and fast)

## 🔒 Privacy & Security

- No external tracking or analytics by default
- All data is handled locally
- Email form uses standard mailto links

## 💡 Enhancement Ideas

- Add a blog section
- Implement dark/light theme toggle
- Add testimonials section
- Include case studies
- Add search functionality
- Create a newsletter signup
- Add animations on scroll
- Implement a service worker for offline support

## 🐛 Troubleshooting

### Images Not Showing
- Verify image file paths in `index.html`
- Check that images exist in `assets/images/` folder
- Use correct file extensions (.jpg, .png, etc.)

### Mobile Menu Not Working
- Check that JavaScript is enabled in browser
- Verify `script.js` is linked in `index.html`
- Check browser console for errors (F12)

### Form Not Sending
- Ensure your email client is configured on your system
- Update the email address in `script.js`
- Try with a different email client

### Styling Issues
- Clear browser cache (Ctrl+Shift+Delete)
- Check for CSS conflicts
- Verify `styles.css` is linked correctly

## 📞 Support

For questions or issues, refer to the code comments within each file.

## 📄 License

Feel free to use this template for your personal or commercial portfolio.

---

**Happy Building! 🎉**

Make this portfolio truly yours by updating the content, colors, and images to reflect your unique style and accomplishments.
