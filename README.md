# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Navigation**: Mobile-friendly hamburger menu with smooth scrolling
- **Project Showcase**: Grid layout for displaying projects
- **Contact Section**: Easy way for visitors to get in touch
- **Semantic HTML5**: Proper structure for accessibility and SEO
- **CSS Grid & Flexbox**: Modern layout techniques
- **Smooth Animations**: Scroll-triggered animations and hover effects

## File Structure

```
personal-website/
├── index.html          # Main HTML structure
├── style.css           # CSS styling and layout
├── script.js           # JavaScript interactivity
├── assets/             # Images and media files
│   ├── profile.jpg     # Your profile picture
│   ├── project1.jpg    # Project 1 screenshot
│   ├── project2.jpg    # Project 2 screenshot
│   └── project3.jpg    # Project 3 screenshot
└── README.md           # This file
```

## Getting Started

1. Clone or download this repository
2. Add your own images to the `assets/` folder:
   - Replace `profile.jpg` with your profile picture
   - Replace project images with your actual project screenshots
3. Customize the content in `index.html`:
   - Update your name in the title and navigation
   - Modify the hero section text
   - Update the about section with your information
   - Replace project details with your actual projects
   - Update contact information
4. Open `index.html` in your web browser to view the site

## Customization

### Colors
The main color scheme is defined in `style.css`. Look for:
- Primary color: `#007bff` (blue)
- Background gradients in the hero section
- Text colors and hover states

### Fonts
The site uses Google Fonts (Inter). You can change the font by:
1. Updating the Google Fonts import in `index.html`
2. Changing the `font-family` property in `style.css`

### Adding Projects
To add more projects:
1. Copy an existing `.project__card` div in `index.html`
2. Update the image, title, description, and links
3. Add the new project image to the `assets/` folder

## Deployment

### GitHub Pages
1. Push this repository to GitHub
2. Go to repository Settings > Pages
3. Select the main branch as source
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify/Vercel
1. Connect your GitHub account to Netlify or Vercel
2. Import this repository
3. Deploy with default settings
4. Your site will be live with a custom URL

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Grid, Flexbox, and animations
- **JavaScript**: Interactivity and smooth scrolling
- **Google Fonts**: Typography
- **Responsive Design**: Mobile-first approach

## Browser Support

This website supports all modern browsers:
- Chrome/Edge 88+
- Firefox 85+
- Safari 14+
- Mobile browsers (iOS Safari, Android Chrome)

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: Remember to replace placeholder content (names, emails, project details) with your actual information before deploying.
