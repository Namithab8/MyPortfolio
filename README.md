# Namitha B - Portfolio Website

A modern, responsive, and professional personal portfolio website for Namitha B, a Software Engineer specializing in Java Full Stack Development.

## Features

- **Dark Theme** with navy blue, black, and white colors with cyan/sky-blue accents
- **Glassmorphism UI** with frosted glass effect cards
- **Smooth Animations** using AOS (Animate On Scroll)
- **Typing Effect** in the hero section
- **Responsive Design** for desktop, tablet, and mobile devices
- **Sticky Navigation** with scroll progress indicator
- **Back-to-Top Button** for easy navigation
- **Interactive Elements** with hover effects and transitions
- **Contact Form** with validation
- **Social Media Integration** (LinkedIn, GitHub, LeetCode)

## Sections

1. **Hero** - Professional introduction with typing animation
2. **About** - Personal description and background
3. **Education** - Academic qualifications in timeline format
4. **Experience** - Work experience with animated cards
5. **Skills** - Technical skills categorized with icons
6. **Projects** - Project showcases with hover effects
7. **Contact** - Contact information and form
8. **Footer** - Copyright and social links

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables and animations
- **JavaScript (ES6+)** - Interactive features and animations
- **Font Awesome** - Icons
- **Google Fonts** - Poppins and Inter typography
- **AOS Library** - Scroll animations

## How to Use

1. **Clone or download** the files to your local machine
2. **Open `index.html`** in a web browser
3. **Customize** the content as needed:
   - Update personal information in `index.html`
   - Modify colors in `styles.css` CSS variables
   - Adjust animations in `script.js`
4. **Add your resume** by updating the download link in `script.js`
5. **Deploy** to a hosting service (GitHub Pages, Netlify, Vercel, etc.)

## Customization

### Colors
Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #0a192f;
    --secondary-color: #112240;
    --accent-color: #64ffda;
    /* ... other variables */
}
```

### Profile Image
Replace the placeholder in `index.html`:

```html
<div class="profile-placeholder">
    <i class="fas fa-user"></i>
</div>
```

With your actual image:

```html
<img src="your-image.jpg" alt="Namitha B" class="profile-img">
```

### Resume
Update the download link in `script.js`:

```javascript
downloadResume.addEventListener('click', (e) => {
    e.preventDefault();
    window.open('path-to-your-resume.pdf', '_blank');
});
```

### Social Links
Update all social media links in `index.html` with your actual profiles.

## File Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # Styling and animations
├── script.js       # JavaScript functionality
└── README.md       # Documentation
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Optimized CSS with CSS variables
- Minimal external dependencies
- Lazy loading for animations
- Smooth scrolling implementation

## Future Enhancements

- Add blog section
- Integrate with a backend for contact form
- Add more project showcases
- Implement dark/light mode toggle
- Add testimonials section
- Integrate with Google Analytics

## Credits

- Designed & Developed by Namitha B
- Icons by Font Awesome
- Fonts by Google Fonts
- Animations by AOS Library

## License

This project is open source and available for personal and commercial use.

---

**Contact:** namunamita30@gmail.com
**LinkedIn:** www.linkedin.com/in/namitha-b-4b75b1273
**GitHub:** https://github.com/Namithab8
