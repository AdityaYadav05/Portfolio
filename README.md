# Aditya Yadav - Professional Portfolio

## 🚀 About This Portfolio

A modern, fully responsive portfolio website showcasing the work and skills of Aditya Yadav, a Frontend Developer at Astro Setu. This portfolio features stunning animations, smooth transitions, and a beautiful UI design.

## ✨ Features

- **Custom Cursor**: Interactive custom cursor with smooth following effect
- **Smooth Animations**: Fade-in, slide-in, and parallax effects throughout
- **Responsive Design**: Fully responsive across all devices (mobile, tablet, desktop)
- **Floating Badges**: Animated skill badges on the hero section
- **Skill Progress Bars**: Animated progress bars showing skill proficiency
- **Interactive Cards**: Tilt effect and hover animations on project and skill cards
- **Timeline**: Beautiful timeline for experience section
- **Contact Form**: Functional contact form with email integration
- **Scroll Animations**: Elements animate as you scroll through the page
- **Gradient Orbs**: Dynamic gradient background with floating orbs
- **Mobile Menu**: Hamburger menu for mobile navigation

## 📁 Project Structure

```
portfolio/
├── index.html       # Main HTML file
├── style.css        # CSS styles and animations
├── script.js        # JavaScript for interactivity
├── profile.jpg      # Your profile image
└── README.md        # This file
```

## 🛠️ Technologies Used

- HTML5
- CSS3 (Custom Properties, Flexbox, Grid, Animations)
- Vanilla JavaScript (ES6+)
- Google Fonts (Playfair Display, Outfit)
- Font Awesome Icons

## 📋 Sections

1. **Hero Section**: Introduction with animated text and profile image
2. **About Section**: Personal information and statistics
3. **Skills Section**: Technical skills with progress bars
4. **Experience Section**: Work experience timeline
5. **Projects Section**: Featured projects with images
6. **Contact Section**: Contact form and details
7. **Footer**: Copyright and credits

## 🎨 Color Scheme

- Primary: #6366f1 (Indigo)
- Secondary: #a855f7 (Purple)
- Accent: #ec4899 (Pink)
- Background: Dark theme with gradient accents

## 🚀 How to Use

1. **Extract the ZIP file** to your desired location
2. **Open index.html** in your web browser
3. **Customize the content**:
   - Replace `profile.jpg` with your own image
   - Update personal information in `index.html`
   - Modify colors in `style.css` (CSS variables at the top)
   - Add your project images and links

## 📝 Customization Guide

### Changing Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #a855f7;
    --accent-color: #ec4899;
    /* ... more colors */
}
```

### Adding Projects
Add new project cards in the `projects-grid` section:
```html
<div class="project-card">
    <div class="project-image">
        <img src="your-image.jpg" alt="Project Name">
        <!-- ... -->
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Description</p>
        <!-- ... -->
    </div>
</div>
```

### Updating Skills
Modify skill cards in the `skills-grid` section and adjust the `data-progress` attribute.

### Contact Form
The contact form opens the user's default email client. To integrate with a backend:
- Add form handling in `script.js`
- Consider using services like Formspree, EmailJS, or your own backend

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## 🔧 Performance Optimizations

- Lazy loading for images
- Intersection Observer for scroll animations
- CSS animations (hardware accelerated)
- Optimized JavaScript
- Minimal external dependencies

## 📞 Contact Information

- **Email**: adityayadavvv12@gmail.com
- **Phone**: +91 9936096673
- **GitHub**: [AdityaYadav05](https://github.com/AdityaYadav05)
- **LinkedIn**: [Adiya-Yadav](https://linkedin.com/in/Adiya-Yadav)

## 📄 License

This project is open source and available for personal and commercial use.

## 🙏 Credits

- **Design & Development**: Aditya Yadav
- **Fonts**: Google Fonts
- **Icons**: Font Awesome
- **Images**: Unsplash (for project placeholders)

## 🚀 Deployment

You can deploy this portfolio to:

- **GitHub Pages**: Free and easy
- **Netlify**: Drag and drop deployment
- **Vercel**: Great for modern web projects
- **Your own hosting**: Upload via FTP

### GitHub Pages Deployment:
1. Create a new GitHub repository
2. Upload all files
3. Go to Settings > Pages
4. Select main branch and save
5. Your site will be live at `https://username.github.io/repository-name`

## 💡 Tips

- Keep your portfolio updated with new projects
- Add Google Analytics to track visitors
- Optimize images for faster loading
- Test on multiple devices and browsers
- Add more animations sparingly for better UX

## 🐛 Troubleshooting

**Images not showing?**
- Check file paths and names
- Ensure images are in the same directory

**Animations not working?**
- Make sure JavaScript is enabled
- Check browser console for errors

**Form not working?**
- Verify email client is set up
- Check spam folder for test emails

---

**Made with ❤️ by Aditya Yadav**

For any questions or support, feel free to reach out!
